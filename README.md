local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

Fluent:Notify({ Title = "Notification", Content = "obrigado por usa meu script $" })




local Window = Fluent:CreateWindow({
    Title = "FIRE HUB🔥" .. Fluent.Version,
    TabWidth = 130, Size = UDim2.fromOffset(580, 460), Theme = "Red"
})

local alvodongc
local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "Nome"
local Nzx = Instance.new("ImageButton")
ScreenGui.Parent = game.CoreGui

-- Criando o UICorner para deixar o botão redondo
local Estetica = Instance.new("UICorner")
Estetica.CornerRadius = UDim.new(1, 0) -- O "1" faz o botão ficar completamente redondo
Estetica.Parent = Nzx -- Aplica o UICorner ao botão Nzx

Nzx.Name = "Nzx"
Nzx.Parent = ScreenGui
Nzx.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Nzx.Position = UDim2.new(0.799450576, 0, 0.278925627, 0)
Nzx.Size = UDim2.new(0, 60, 0, 60)
Nzx.Visible = true
Nzx.Draggable = true     
Nzx.Active = true     
Nzx.Selectable = true
Nzx.Image = "rbxassetid://103006981698580" -- Id da imagem aqui

-- Função para alternar a visibilidade de "alvodongc"
for i, v in pairs(game.CoreGui:GetDescendants()) do
    if v.Name == "CanvasGroup" then
        alvodongc = v.Parent
    end
end

local function FVGE_fake_script()
    Nzx.MouseButton1Up:Connect(function()
        task.wait()
        if not toggle then
            toggle = true
            alvodongc.Visible = true
        else
            toggle = false
            alvodongc.Visible = false
        end
    end)
end
coroutine.wrap(FVGE_fake_script)()





local MainTab = Window:AddTab({ Title = "sounds🦠⚒️🦠" })

MainTab:AddButton({
    Title = "moan",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 134211073313990,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "Kiss id.",
    Callback = function()local args = {
    [1] = workspace,
    [2] = 86302772867087 ,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "Moan id",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 106835463235574,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "sorry",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 169664410,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id estourado",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 2778973486 ,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id?",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 117384045216316,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

local MainTab = Window:AddTab({ Title = "sounds v2💤" })

MainTab:AddButton({
    Title = "id noy",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8484439709,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id GOOFH",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 8604866972,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id LKG",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 93300439155773,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id BNG",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 6987177472,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

local MainTab = Window:AddTab({ Title = "sounds v3👾" })

MainTab:AddButton({
    Title = "Id memes",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 7550163267594,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id posso",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 103211341252816,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})

MainTab:AddButton({
    Title = "id ",
    Callback = function()
        print("Botão clicado!")local args = {
    [1] = workspace,
    [2] = 2778973486,
    [3] = 1
}

game:GetService("ReplicatedStorage").RE:FindFirstChild("1Gu1nSound1s"):FireServer(unpack(args))
    end
})


