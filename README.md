local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))() loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Jim's RNG", "Ocean")

local Tab = Window:NewTab("Main Menu")
local Section = Tab:NewSection("All Auras")

Section:NewButton("Ancient", "Ancient", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Ancient")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))

end)

Section:NewButton("Ancient Prophecy", "Ancient Prophecy", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Ancient Prophecy")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))

end)

Section:NewButton("Devourer of Gods", "Devourer of Gods", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Devourer of Gods")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))

end)

Section:NewButton("Arcade", "Arcade", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Arcade")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Gluttony", "Gluttony", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Gluttony")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Baseplate", "Baseplate", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Baseplate")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Nebula", "Nebula", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Nebula")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Earth", "Earth", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Earth")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Rifter : Classic", "Rifter : Classic", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Rifter : Classic")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Bey, The Gambling One", "Bey, The Gambling One", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Bey, The Gambling One")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Wishing Star : Classic", "Wishing Star : Classic", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Wishing Star : Classic")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Supreme Calamitas", "Supreme Calamitas", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Supreme Calamitas")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Abomination", "Abomination", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Abomination")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("1x1x1x1x1", "1x1x1x1x1", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("1x1x1x1x1")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Mr. BEASTT!!!!!!!!!!!!!!", "Mr. BEASTT!!!!!!!!!!!!!!", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Mr. BEASTT!!!!!!!!!!!!!!")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Arcade : グラインド地区", "Arcade : グラインド地区", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Arcade : グラインド地区")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Polychrome", "Polychrome", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Polychrome")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Asgore", "Asgore", function()
   local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Asgore")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)
