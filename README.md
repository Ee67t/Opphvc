local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Catch_dde's Hub | Horrors RNG", HidePremium = false, IntroEnabled = false, SaveConfig = true, ConfigFolder = "ExoConfig"})

-- Values
getgenv().setSpeed = 0
getgenv().getLuck = false
getgenv().getLuckPerSecond = false
getgenv().autoRoll = false
getgenv().autoSkip = true
getgenv().fastRoll = false
getgenv().shouldDelay = true

-- Services and Events
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local InventoryEvent = ReplicatedStorage.Events.InventoryEvent
local RollEvent = ReplicatedStorage.Events.StartRoll
local Players = game:GetService("Players")
local StarterGui = game:GetService("StarterGui")
local UserInputService = game:GetService("UserInputService")

-- Functions
local function fireEquipEvent()
    InventoryEvent:FireServer("Equip", "Super Luck Potion", "Usable")
end

local function fireRollEvent()
    RollEvent:FireServer()
end

function startLuck()
    while getLuck == true do
        task.wait(0.000000000000001)
        for i = 1, 15 do
            fireEquipEvent()
        end
    end
end

function startLuckPerSec()
    while getLuckPerSecond == true do
        task.wait(0.5)
        for i = 1, 25 do
            fireEquipEvent()
        end
    end
end

function startRoll()
    while autoRoll == true do
        fireRollEvent()
        Wait()
    end
end

function fastRollFunc()
    while fastRoll == true do

        if autoSkip then
            local args = {
                [1] = "Skip"
            }
            ReplicatedStorage.Events.RolledFromClient:FireServer(unpack(args))
        else
            local args = {
                [1] = "Equip"
            }
            ReplicatedStorage.Events.RolledFromClient:FireServer(unpack(args))
        end

        Wait()
    end
end

function giveLuckInstant()
    for i = 1, 25 do
        if shouldDelay then
            Wait()
        end
        fireEquipEvent()
    end
end

function giveLuckInstantOp()
    for i = 1, 250 do
        if shouldDelay then
            Wait()
        end
        fireEquipEvent()
    end
end

function giveLuckInstantOpOp()
    for i = 1, 1000 do
        if shouldDelay then
            Wait()
        end
        fireEquipEvent()
    end
end

-- Draggable GUI
local function makeDraggable(gui)
    local dragging
    local dragInput
    local dragStart
    local startPos

    local function update(input)
        local delta = input.Position - dragStart
        gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
    end

    gui.InputBegan:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
            dragging = true
            dragStart = input.Position
            startPos = gui.Position

            input.Changed:Connect(function()
                if input.UserInputState == Enum.UserInputState.End then
                    dragging = false
                end
            end)
        end
    end)

    gui.InputChanged:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
            dragInput = input
        end
    end)

    UserInputService.InputChanged:Connect(function(input)
        if dragging and input == dragInput then
            update(input)
        end
    end)
end

-- Tabs
local luckTab = Window:MakeTab({
    Name = "Luck",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
local rollTab = Window:MakeTab({
    Name = "Rolling",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
local miscTab = Window:MakeTab({
    Name = "Misc",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})

-- Toggles
luckTab:AddToggle({
    Name = "Get Luck (laggy)",
    Default = false,
    Callback = function(Value)
        getLuck = Value
        startLuck()
    end
})
luckTab:AddToggle({
    Name = "Add Delay",
    Default = true,
    Callback = function(Value)
        shouldDelay = Value
    end
})
luckTab:AddToggle({
    Name = "Get Luck Per Second (not as laggy)",
    Default = false,
    Callback = function(Value)
        getLuckPerSecond = Value
        startLuckPerSec()
    end
})
rollTab:AddToggle({
    Name = "Auto Roll",
    Default = false,
    Callback = function(Value)
        autoRoll = Value
        startRoll()
    end
})
rollTab:AddToggle({
    Name = "Fast Roll (lots and LOTS of money)",
    Default = false,
    Callback = function(Value)
        fastRoll = Value
        fastRollFunc()
    end
})
rollTab:AddToggle({
    Name = "Skip Auto Roll (only when you use fast roll too)",
    Default = true,
    Callback = function(Value)
        autoSkip = Value
    end
})

-- Buttons
miscTab:AddButton({
    Name = "Destroy Gui",
    Callback = function()
        OrionLib:Destroy()
    end    
})
luckTab:AddButton({
    Name = "Gain 100x Luck",
    Callback = function()
        giveLuckInstant()
    end    
})
luckTab:AddButton({
    Name = "Gain 1000x Luck (laggy if not delayed)",
    Callback = function()
        giveLuckInstantOp()
    end    
})
luckTab:AddButton({
    Name = "Gain 4000x Luck (May Crash Game if not delayed)",
    Callback = function()
        giveLuckInstantOpOp()
    end    
})

OrionLib:Init()

task.spawn(function()
    while true do
        local guiFrame = game.CoreGui:FindFirstChild("Orion"):FindFirstChildOfClass("Frame")
        if guiFrame then
            makeDraggable(guiFrame)
            break
        end
        task.wait(0.1)
    end
end)
