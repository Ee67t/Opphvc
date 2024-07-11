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

Section:NewButton("Brick Wall", "Brick Wall", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Brick Wall")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Arcade : Classic", "Arcade : Classic", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Arcade : Classic")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Cubed", "Cubed", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Cubed")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Greed", "Greed", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Greed")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Elderic", "Elderic", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Elderic")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Epic", "Epic", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Epic")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Exotica", "Exotica", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Exotica")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Divinity", "Divinity", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Divinity")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Exotica : FULL POWER", "Exotica : FULL POWER", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Exotica : FULL POWER")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Exotica : OVERDRIVE", "Exotica : OVERDRIVE", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Exotica : OVERDRIVE")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("The Bloxxer", "The Bloxxer", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("The Bloxxer")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Exotica Maxinus", "Exotica Maxinus", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Exotica Maxinus")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Brick Wall : Legacy", "Brick Wall : Legacy", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Brick Wall : Legacy")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Fractal : Singularity", "Fractal : Singularity", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Fractal : Singularity")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Fractal", "Fractal", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Fractal")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Black Flame", "Black Flame", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Black Flame")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Singularity Point : TON 618", "Singularity Point : TON 618", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Singularity Point : TON 618")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Gabriel Judge Of Hell", "Gabriel Judge Of Hell", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Gabriel Judge Of Hell")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Gabriel The Apostate Of Hate", "Gabriel The Apostate Of Hate", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Gabriel The Apostate Of Hate")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Gambler", "Gambler", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Gambler")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("1 Grand : 2009", "1 Grand : 2009", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("1 Grand : 2009")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Void", "Void", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Void")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Fractured Time", "Fractured Time", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Fractured Time")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Void : Chaos", "Void : Chaos", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Void : Chaos")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Brick Wall : Nature", "Brick Wall : Nature", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Brick Wall : Nature")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Jazz Zone", "Jazz Zone", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Jazz Zone")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Pride", "Pride", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Pride")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Legendary", "Legendary", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Legendary")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("V2", "V2", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("V2")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Limbo", "Limbo", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Limbo")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)

Section:NewButton("Portal", "Portal", function()
    local args = {
    [1] = game:GetService("ReplicatedStorage"):WaitForChild("Auras"):WaitForChild("Portal")
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("AuraEquip"):FireServer(unpack(args))
    
end)
