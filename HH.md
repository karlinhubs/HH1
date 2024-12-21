local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Haidez Hub V1", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

-- Criando a aba Fisch
local FischTab = Window:MakeTab({
    Name = "Fisch",
    Icon = "rbxassetid://126633428869869",  -- Ícone para a aba Fisch
    PremiumOnly = false
})

-- Criando a seção dentro da aba Fisch
local FischSection = FischTab:AddSection({
    Name = "Seção Fisch"
})

-- Criando os botões na aba Fisch
FischTab:AddButton({
    Name = "God Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/kiciahook/kiciahook/refs/heads/main/loader.lua"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Romix Hub",
    Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/fcbdda745da39b237faf2766f6d8d9cb.lua"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Solix Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/debunked69/Solixreworkkeysystem/refs/heads/main/solix%20new%20keyui.lua"))() 
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Mercury Hub",
    Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/c019f214a19894b50f0b8e817b70d25f.lua"))() 
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Naoki Hub",
    Callback = function()
        loadstring(game:HttpGet("https://naokihub.vercel.app", true))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Nil Hub",
    Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/2c5f110f91165707959fc626b167e036.lua"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "KNCRYPT Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/Kncrypt/refs/heads/main/sources/Fisch.lua"))({true})
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Cupink Hub",
    Callback = function()
        loadstring(game:HttpGet("https://you.whimper.xyz/sources/CupPink/fisch.lua"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Speed Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Average Hub",
    Callback = function()
        loadstring(game:HttpGet("https://gist.githubusercontent.com/AverageHub/1980eccce4133d77fb24d166dc296125/raw/2d9c88acc21a302d92aed0e8b6f0dcd287c8b96b/gistfile1.txt"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

FischTab:AddButton({
    Name = "Hidden Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/tulontop/HiddenRevamp/refs/heads/main/Loader.luau"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

-- Criando a aba Blox-Fruits
local BloxFruitsTab = Window:MakeTab({
    Name = "Blox-Fruits",
    Icon = "rbxassetid://126633428869869",  -- Ícone para a aba Blox-Fruits
    PremiumOnly = false
})

-- Criando a seção dentro da aba Blox-Fruits
local BloxFruitsSection = BloxFruitsTab:AddSection({
    Name = "Seção Blox-Fruits"
})

-- Criando os botões na aba Blox-Fruits
BloxFruitsTab:AddButton({
    Name = "ThurdenZ Hub",
    Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/ThundarZ/Welcome/refs/heads/main/Main/Loader/AllGame.lua'))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

BloxFruitsTab:AddButton({
    Name = "Speed Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

BloxFruitsTab:AddButton({
    Name = "HOHO Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

BloxFruitsTab:AddButton({
    Name = "Alchemy Hub",
    Callback = function()
        loadstring(game:HttpGet("https://scripts.alchemyhub.xyz"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

BloxFruitsTab:AddButton({
    Name = "Moon Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Jadelly261/BloxFruits/main/MoonHub", true))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

BloxFruitsTab:AddButton({
    Name = "Redz Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

BloxFruitsTab:AddButton({
    Name = "XT Hub",
    Callback = function()
        loadstring(game:HttpGet("https://github.com/Basicallyy/Basicallyy/raw/main/Min_XT_V2_.lua"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

BloxFruitsTab:AddButton({
    Name = "Xero Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/verudous/Xero-Hub/refs/heads/main/main.lua"))() 
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})

BloxFruitsTab:AddButton({
    Name = "Banana Hub",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/obiiyeuem/vthangsitink/main/BananaHub.lua"))()
        OrionLib:MakeNotification({
            Name = "Script Executado",
            Content = "O script foi executado com sucesso.",
            Image = "rbxassetid://4483345998",  -- Você pode mudar a imagem se quiser
            Time = 5
        })
    end
})
