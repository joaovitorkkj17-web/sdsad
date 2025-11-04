-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Vk = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local ScrollingFrame = Instance.new("ScrollingFrame")
local TextButton_2 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Open = Instance.new("Frame")
local TextButton_5 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Vk.Name = "Vk"
Vk.Parent = ScreenGui
Vk.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Vk.BorderColor3 = Color3.fromRGB(0, 0, 0)
Vk.BorderSizePixel = 0
Vk.Position = UDim2.new(0.242770165, 0, 0.23565574, 0)
Vk.Size = UDim2.new(0.512176573, 0, 0.527072489, 0)

UICorner.Parent = Vk

Frame.Parent = Vk
Frame.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Size = UDim2.new(1, 0, 0.128299147, 0)

UICorner_2.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.22882615, 0, -0.606060386, 0)
TextLabel.Size = UDim2.new(0.609934628, 0, 2.16279054, 0)
TextLabel.Font = Enum.Font.FredokaOne
TextLabel.Text = "VK HUB -  Eternal Nights 🍕"
TextLabel.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(-0.014858841, 0, -0.24242425, 0)
TextLabel_2.Size = UDim2.new(0.116621055, 0, 1.42424214, 0)
TextLabel_2.Font = Enum.Font.FredokaOne
TextLabel_2.Text = "Vk"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.19316493, 0, 1.09090912, 0)
TextLabel_3.Size = UDim2.new(0.430142581, 0, 1.69696975, 0)
TextLabel_3.Font = Enum.Font.FredokaOne
TextLabel_3.Text = "ESP Animatronics"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = Frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.0995542333, 0, 3, 0)
TextLabel_4.Size = UDim2.new(0.422713161, 0, 1.24242425, 0)
TextLabel_4.Font = Enum.Font.FredokaOne
TextLabel_4.Text = "ESP Itens"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 170, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

Frame_2.Parent = Vk
Frame_2.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0, 0, 0.870879114, 0)
Frame_2.Size = UDim2.new(1, 0, 0.129120901, 0)

UICorner_3.Parent = Frame_2

TextButton.Parent = Vk
TextButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.931649327, 0, 0, 0)
TextButton.Size = UDim2.new(0.0668647811, 0, 0.1244113, 0)
TextButton.Font = Enum.Font.FredokaOne
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_4.Parent = TextButton

ScrollingFrame.Parent = Vk
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(83, 83, 83)
ScrollingFrame.BorderColor3 = Color3.fromRGB(255, 0, 0)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0, 0, 0.1244113, 0)
ScrollingFrame.Size = UDim2.new(0.194650814, 0, 0.742579937, 0)

TextButton_2.Parent = ScrollingFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Size = UDim2.new(0, 119, 0, 31)
TextButton_2.Font = Enum.Font.FredokaOne
TextButton_2.Text = "Main"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

UICorner_5.Parent = TextButton_2

TextButton_3.Parent = Vk
TextButton_3.BackgroundColor3 = Color3.fromRGB(111, 111, 111)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.646359563, 0, 0.151626274, 0)
TextButton_3.Size = UDim2.new(0.28380385, 0, 0.194392651, 0)
TextButton_3.Font = Enum.Font.FredokaOne
TextButton_3.Text = "Desativado"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true

UICorner_6.Parent = TextButton_3

TextButton_4.Parent = Vk
TextButton_4.BackgroundColor3 = Color3.fromRGB(94, 94, 94)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.540861785, 0, 0.38489747, 0)
TextButton_4.Size = UDim2.new(0.28380385, 0, 0.194392651, 0)
TextButton_4.Font = Enum.Font.FredokaOne
TextButton_4.Text = "Desativado"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

UICorner_7.Parent = TextButton_4

Open.Name = "Open"
Open.Parent = ScreenGui
Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Open.BorderColor3 = Color3.fromRGB(0, 0, 0)
Open.BorderSizePixel = 0
Open.Position = UDim2.new(0.107370339, 0, 0.321721315, 0)
Open.Size = UDim2.new(0.0818926319, 0, 0.131147534, 0)
Open.Visible = false

TextButton_5.Parent = Open
TextButton_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.0333333351, 0, 0.0937500075, 0)
TextButton_5.Size = UDim2.new(0.922222197, 0, 0.78125006, 0)
TextButton_5.Font = Enum.Font.FredokaOne
TextButton_5.Text = "Abrir Hub"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextStrokeColor3 = Color3.fromRGB(170, 0, 255)
TextButton_5.TextWrapped = true

-- Scripts:

local function NZJXSY_fake_script() -- Vk.Local Script 
	local script = Instance.new('LocalScript', Vk)

	local frame = script.Parent
	
	local stroke = frame:FindFirstChildOfClass("UIStroke")
	if not stroke then
		stroke = Instance.new("UIStroke")
		stroke.Parent = frame
		stroke.Thickness = 4
		stroke.Transparency = 0
	end
	
	stroke.Color = Color3.fromRGB(255, 0, 0)
	
	
end
coroutine.wrap(NZJXSY_fake_script)()
local function SINDEV_fake_script() -- TextButton.Local Script 
	local script = Instance.new('LocalScript', TextButton)

	local button = script.Parent
	local vkFrame = button.Parent  
	local screenGui = vkFrame.Parent
	
	
	local openFrame = screenGui:FindFirstChild("Open")
	
	button.MouseButton1Click:Connect(function()
		
		vkFrame.Visible = false
	
		
		if openFrame then
			openFrame.Visible = true
		else
			warn("Frame 'Open' não encontrado no ScreenGui!")
		end
	end)
	
end
coroutine.wrap(SINDEV_fake_script)()
local function ZRNRQH_fake_script() -- Vk.LocalScript 
	local script = Instance.new('LocalScript', Vk)

	local UserInputService = game:GetService("UserInputService")
	local frame = script.Parent
	
	local dragging = false
	local dragInput = nil
	local dragStart = nil
	local startPos = nil
	
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale,
			startPos.X.Offset + delta.X,
			startPos.Y.Scale,
			startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or
			input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or
			input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
	
end
coroutine.wrap(ZRNRQH_fake_script)()
local function TKUA_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	local player = game.Players.LocalPlayer
	local button = script.Parent
	local camera = workspace.CurrentCamera
	
	local targetsFolder = workspace:WaitForChild("Game"):WaitForChild("Animatronics"):WaitForChild("Animatronics")
	
	
	local animatronicsColors = {
		Puppet = Color3.fromRGB(0, 0, 0),        
		Chica = Color3.fromRGB(255, 255, 0),     
		Cupcake = Color3.fromRGB(255, 105, 180), 
		Freddy = Color3.fromRGB(139, 69, 19),    
		Bonnie = Color3.fromRGB(0, 85, 255),     
		Foxy = Color3.fromRGB(255, 140, 0)       
	}
	
	local espEnabled = false 
	
	
	local function createBillboard(model, color)
		if model:FindFirstChild("HumanoidRootPart") and not model:FindFirstChild("ESP_Mark") then
			local hrp = model.HumanoidRootPart
	
			local mark = Instance.new("Folder")
			mark.Name = "ESP_Mark"
			mark.Parent = model
	
			local billboard = Instance.new("BillboardGui")
			billboard.Name = "ESP_Billboard"
			billboard.Parent = mark
			billboard.Adornee = hrp
			billboard.Size = UDim2.new(0, 200, 0, 50)
			billboard.AlwaysOnTop = true
	
			local text = Instance.new("TextLabel")
			text.Parent = billboard
			text.Size = UDim2.new(1, 0, 1, 0)
			text.BackgroundTransparency = 1
			text.TextColor3 = color
			text.Font = Enum.Font.GothamBold
			text.TextScaled = true
	
			local highlight = Instance.new("Highlight")
			highlight.Name = "ESP_Highlight"
			highlight.Parent = mark
			highlight.Adornee = hrp
			highlight.FillColor = color
			highlight.OutlineColor = color
			highlight.FillTransparency = 0.7
	
			task.spawn(function()
				while espEnabled and model.Parent and mark.Parent == model do
					local char = player.Character
					if char and char:FindFirstChild("HumanoidRootPart") then
						local distance = (char.HumanoidRootPart.Position - hrp.Position).Magnitude
						text.Text = model.Name .. " - " .. math.floor(distance) .. "m"
					end
					task.wait(0.1)
				end
			end)
		end
	end
	
	
	local function activateESP()
		for name, color in pairs(animatronicsColors) do
			local mob = targetsFolder:FindFirstChild(name)
			if mob then
				createBillboard(mob, color)
			end
		end
	end
	
	
	local function deactivateESP()
		for _, model in ipairs(targetsFolder:GetChildren()) do
			local mark = model:FindFirstChild("ESP_Mark")
			if mark then
				mark:Destroy()
			end
		end
	end
	
	
	button.MouseButton1Click:Connect(function()
		espEnabled = not espEnabled
		if espEnabled then
			button.Text = "ESP: ON"
			activateESP()
		else
			button.Text = "ESP: OFF"
			deactivateESP()
		end
	end)
	
	
	button.Text = "ESP: OFF"
end
coroutine.wrap(TKUA_fake_script)()
local function DLDQYWZ_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	local player = game.Players.LocalPlayer
	local button = script.Parent
	local espEnabled = false 
	
	
	local function findPart(model)
		for _, obj in ipairs(model:GetDescendants()) do
			if obj:IsA("BasePart") then
				return obj
			end
		end
		return nil
	end
	
	local function createESP(target, color)
		if target:FindFirstChild("ESP_Mark") then return end
	
		local part = findPart(target)
		if not part then
			warn("Nenhuma parte encontrada para ESP em:", target.Name)
			return
		end
	
		local mark = Instance.new("Folder")
		mark.Name = "ESP_Mark"
		mark.Parent = target
	
		local billboard = Instance.new("BillboardGui")
		billboard.Parent = mark
		billboard.Adornee = part
		billboard.Size = UDim2.new(0, 200, 0, 50)
		billboard.AlwaysOnTop = true
	
		local text = Instance.new("TextLabel")
		text.Parent = billboard
		text.Size = UDim2.new(1, 0, 1, 0)
		text.BackgroundTransparency = 1
		text.TextColor3 = color
		text.Font = Enum.Font.GothamBold
		text.TextScaled = true
	
		local highlight = Instance.new("Highlight")
		highlight.Parent = mark
		highlight.Adornee = part
		highlight.FillColor = color
		highlight.OutlineColor = color
		highlight.FillTransparency = 0.5
	
		task.spawn(function()
			while target.Parent and espEnabled do
				local char = player.Character
				if char and char:FindFirstChild("HumanoidRootPart") then
					local dist = (char.HumanoidRootPart.Position - part.Position).Magnitude
					text.Text = target.Name .. " - " .. math.floor(dist) .. "m"
				end
				task.wait(0.1)
			end
		end)
	end
	
	local function scanWorkspace()
		for _, obj in ipairs(workspace:GetChildren()) do
			if obj:IsA("Tool") then
				createESP(obj, Color3.fromRGB(0, 0, 255))
			end
		end
	end
	
	
	workspace.ChildAdded:Connect(function(obj)
		if espEnabled and obj:IsA("Tool") then
			task.wait(0.1)
			createESP(obj, Color3.fromRGB(0, 0, 255))
		end
	end)
	
	
	button.MouseButton1Click:Connect(function()
		espEnabled = not espEnabled
		if espEnabled then
			button.Text = "ESP: ON"
			scanWorkspace()
		else
			button.Text = "ESP: OFF"
			
			for _, obj in ipairs(workspace:GetChildren()) do
				if obj:IsA("Tool") and obj:FindFirstChild("ESP_Mark") then
					obj.ESP_Mark:Destroy()
				end
			end
		end
	end)
	
	
	button.Text = "ESP: OFF"
end
coroutine.wrap(DLDQYWZ_fake_script)()
local function QVDZBG_fake_script() -- TextButton_5.Local Script 
	local script = Instance.new('LocalScript', TextButton_5)

	local button = script.Parent
	local currentFrame = button.Parent 
	local screenGui = currentFrame.Parent
	
	
	local vkFrame = screenGui:FindFirstChild("Vk")
	
	button.MouseButton1Click:Connect(function()
		
		currentFrame.Visible = false
	
		
		if vkFrame then
			vkFrame.Visible = true
		else
			warn("Frame 'Vk' não encontrado no ScreenGui!")
		end
	end)
	
end
coroutine.wrap(QVDZBG_fake_script)()
local function PTZQQVZ_fake_script() -- Open.Local Script 
	local script = Instance.new('LocalScript', Open)

	local frame = script.Parent
	local UserInputService = game:GetService("UserInputService")
	
	local dragging = false
	local dragStart = nil
	local startPos = nil
	
	frame.Active = true
	frame.Selectable = true
	
	frame.MouseButton1Down:Connect(function(input)
	    dragging = true
	    dragStart = input.Position
	    startPos = frame.Position
	
	    local connMove, connUp
	    connMove = UserInputService.InputChanged:Connect(function(input2)
	        if dragging and input2.UserInputType == Enum.UserInputType.MouseMovement then
	            local delta = input2.Position - dragStart
	            frame.Position = UDim2.new(
	                startPos.X.Scale,
	                startPos.X.Offset + delta.X,
	                startPos.Y.Scale,
	                startPos.Y.Offset + delta.Y
	            )
	        end
	    end)
	
	    connUp = UserInputService.InputEnded:Connect(function(input2)
	        if input2.UserInputType == Enum.UserInputType.MouseButton1 then
	            dragging = false
	            connMove:Disconnect()
	            connUp:Disconnect()
	        end
	    end)
	end)
	
	
end
coroutine.wrap(PTZQQVZ_fake_script)()
local function YCUNZ_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	local UserInputService = game:GetService("UserInputService")
	local frame = script.Parent
	
	local dragging = false
	local dragInput = nil
	local dragStart = nil
	local startPos = nil
	
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale,
			startPos.X.Offset + delta.X,
			startPos.Y.Scale,
			startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or
			input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or
			input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
	
end
coroutine.wrap(YCUNZ_fake_script)()
