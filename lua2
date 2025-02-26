--[[
	Roblox2Lua
	----------
	
	This code was generated using
	Deluct's Roblox2Lua plugin.
]]--

--// Instances

local ghostPart = workspace:WaitForChild("Ghost")

local screen_gui = Instance.new("ScreenGui")
screen_gui.IgnoreGuiInset = false
screen_gui.ResetOnSpawn = true
screen_gui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
screen_gui.Parent = game:GetService("CoreGui")

local frame = Instance.new("Frame")
frame.AnchorPoint = Vector2.new(0, 1)
frame.BackgroundColor3 = Color3.new(0.0470588, 0.0470588, 0.0470588)
frame.BackgroundTransparency = 0.5
frame.BorderColor3 = Color3.new(0, 0, 0)
frame.BorderSizePixel = 0
frame.Position = UDim2.new(0, 0, 1, 0)
frame.Size = UDim2.new(0, 435, 0, 287)
frame.Visible = true
frame.Parent = screen_gui

local uicorner = Instance.new("UICorner")
uicorner.CornerRadius = UDim.new(0.05000000074505806, 0)
uicorner.Parent = frame

local uilist_layout = Instance.new("UIListLayout")
uilist_layout.Padding = UDim.new(0.019999999552965164, 0)
uilist_layout.HorizontalAlignment = Enum.HorizontalAlignment.Center
uilist_layout.SortOrder = Enum.SortOrder.LayoutOrder
uilist_layout.Parent = frame

local title = Instance.new("TextLabel")
title.Font = Enum.Font.Merriweather
title.RichText = true
title.Text = "GHOST INFORMATION"
title.TextColor3 = Color3.new(1, 0.956863, 0.792157)
title.TextScaled = true
title.TextSize = 14
title.TextWrapped = true
title.BackgroundColor3 = Color3.new(1, 1, 1)
title.BackgroundTransparency = 1
title.BorderColor3 = Color3.new(0, 0, 0)
title.BorderSizePixel = 0
title.Position = UDim2.new(0.0310344826, 0, 0, 0)
title.Size = UDim2.new(0.968, 0,0.108, 0)
title.Visible = true
title.Name = "Title"
title.Parent = frame

local separator = Instance.new("TextLabel")
separator.Font = Enum.Font.Merriweather
separator.RichText = true
separator.Text = "IDADE: "
separator.TextColor3 = Color3.new(1, 1, 1)
separator.TextScaled = true
separator.TextSize = 14
separator.TextTransparency = 1
separator.TextWrapped = true
separator.BackgroundColor3 = Color3.new(1, 1, 1)
separator.BackgroundTransparency = 1
separator.BorderColor3 = Color3.new(0, 0, 0)
separator.BorderSizePixel = 0
separator.LayoutOrder = 1
separator.Position = UDim2.new(0.0310344826, 0, 0.141093731, 0)
separator.Size = UDim2.new(0.968, 0,0.045, 0)
separator.Visible = true
separator.Name = "Separator"
separator.Parent = frame

local age = Instance.new("TextLabel")
age.Font = Enum.Font.Merriweather
age.RichText = true
age.Text = "IDADE: "
age.TextColor3 = Color3.new(1, 1, 1)
age.TextScaled = true
age.TextSize = 14
age.TextWrapped = true
age.TextXAlignment = Enum.TextXAlignment.Left
age.BackgroundColor3 = Color3.new(1, 1, 1)
age.BackgroundTransparency = 1
age.BorderColor3 = Color3.new(0, 0, 0)
age.BorderSizePixel = 0
age.LayoutOrder = 2
age.Position = UDim2.new(0.0844701305, 0, 0.211874962, 0)
age.Size = UDim2.new(0.862, 0,0.08, 0)
age.Visible = true
age.Name = "Age"
age.Parent = frame
local function updateAgeState(ghostPart)
	task.spawn(function()
		repeat task.wait() until ghostPart:GetAttribute("Age") ~= nil
		ghostPart:GetAttributeChangedSignal("Age"):Connect(function()
			local hunting = ghostPart:GetAttribute("Age") or false
			if hunting then
				age.Text = "IDADE: "..hunting
			end
		end)
	end)
end

local current_room = Instance.new("TextLabel")
current_room.Font = Enum.Font.Merriweather
current_room.RichText = true
current_room.Text = "QUARTO ATUAL: "
current_room.TextColor3 = Color3.new(1, 1, 1)
current_room.TextScaled = true
current_room.TextSize = 14
current_room.TextWrapped = true
current_room.TextXAlignment = Enum.TextXAlignment.Left
current_room.BackgroundColor3 = Color3.new(1, 1, 1)
current_room.BackgroundTransparency = 1
current_room.BorderColor3 = Color3.new(0, 0, 0)
current_room.BorderSizePixel = 0
current_room.LayoutOrder = 3
current_room.Position = UDim2.new(0.0844701305, 0, 0.321718693, 0)
current_room.Size = UDim2.new(0.862, 0,0.08, 0)
current_room.Visible = true
current_room.Name = "CurrentRoom"
current_room.Parent = frame
local function updateCurrentState(ghostPart)
	task.spawn(function()
		repeat task.wait() until ghostPart:GetAttribute("CurrentRoom") ~= nil
		ghostPart:GetAttributeChangedSignal("CurrentRoom"):Connect(function()
			local hunting = ghostPart:GetAttribute("CurrentRoom") or false
			if hunting then
				current_room.Text = "QUARTO ATUAL: "..hunting
			end
		end)
	end)
end

local favorite_room = Instance.new("TextLabel")
favorite_room.Font = Enum.Font.Merriweather
favorite_room.RichText = true
favorite_room.Text = "QUARTO FAVORITO: "
favorite_room.TextColor3 = Color3.new(1, 1, 1)
favorite_room.TextScaled = true
favorite_room.TextSize = 14
favorite_room.TextWrapped = true
favorite_room.TextXAlignment = Enum.TextXAlignment.Left
favorite_room.BackgroundColor3 = Color3.new(1, 1, 1)
favorite_room.BackgroundTransparency = 1
favorite_room.BorderColor3 = Color3.new(0, 0, 0)
favorite_room.BorderSizePixel = 0
favorite_room.LayoutOrder = 4
favorite_room.Position = UDim2.new(0.0844701305, 0, 0.431562424, 0)
favorite_room.Size = UDim2.new(0.862, 0,0.08, 0)
favorite_room.Visible = true
favorite_room.Name = "FavoriteRoom"
favorite_room.Parent = frame
local function updateFavoriteState(ghostPart)
	task.spawn(function()
		repeat task.wait() until ghostPart:GetAttribute("FavoriteRoom") ~= nil
		ghostPart:GetAttributeChangedSignal("FavoriteRoom"):Connect(function()
			local hunting = ghostPart:GetAttribute("FavoriteRoom") or false
			if hunting then
				favorite_room.Text = "QUARTO FAVORITO: "..hunting
			end
		end)
	end)
end

local gender = Instance.new("TextLabel")
gender.Font = Enum.Font.Merriweather
gender.RichText = true
gender.Text = "GÊNERO: "
gender.TextColor3 = Color3.new(1, 1, 1)
gender.TextScaled = true
gender.TextSize = 14
gender.TextWrapped = true
gender.TextXAlignment = Enum.TextXAlignment.Left
gender.BackgroundColor3 = Color3.new(1, 1, 1)
gender.BackgroundTransparency = 1
gender.BorderColor3 = Color3.new(0, 0, 0)
gender.BorderSizePixel = 0
gender.LayoutOrder = 5
gender.Position = UDim2.new(0.0844701305, 0, 0.541406155, 0)
gender.Size = UDim2.new(0.862, 0,0.08, 0)
gender.Visible = true
gender.Name = "Gender"
gender.Parent = frame
local function updatePhotoState(ghostPart)
	task.spawn(function()
		repeat task.wait() until ghostPart:GetAttribute("Gender") ~= nil
		ghostPart:GetAttributeChangedSignal("Gender"):Connect(function()
			local hunting = ghostPart:GetAttribute("Gender") or false
			if hunting then
				gender.Text = "GÊNERO: "..hunting
			end
		end)
	end)
end

local photo_reward = Instance.new("TextLabel")
photo_reward.Font = Enum.Font.Merriweather
photo_reward.RichText = true
photo_reward.Text = "RECOMPENSA FOTO: "
photo_reward.TextColor3 = Color3.new(1, 1, 1)
photo_reward.TextScaled = true
photo_reward.TextSize = 14
photo_reward.TextWrapped = true
photo_reward.TextXAlignment = Enum.TextXAlignment.Left
photo_reward.BackgroundColor3 = Color3.new(1, 1, 1)
photo_reward.BackgroundTransparency = 1
photo_reward.BorderColor3 = Color3.new(0, 0, 0)
photo_reward.BorderSizePixel = 0
photo_reward.LayoutOrder = 6
photo_reward.Position = UDim2.new(0.0844701305, 0, 0.651249886, 0)
photo_reward.Size = UDim2.new(0.862, 0,0.08, 0)
photo_reward.Visible = true
photo_reward.Name = "PhotoReward"
photo_reward.Parent = frame
local function updatePhotoState(ghostPart)
	task.spawn(function()
		repeat task.wait() until ghostPart:GetAttribute("PhotoRewardAvailable") ~= nil
		ghostPart:GetAttributeChangedSignal("PhotoRewardAvailable"):Connect(function()
			local hunting = ghostPart:GetAttribute("PhotoRewardAvailable") or false
			if hunting == true then
				photo_reward.Text = "RECOMPENSA FOTO: "..hunting
			end
		end)
	end)
end

local visual_model = Instance.new("TextLabel")
visual_model.Font = Enum.Font.Merriweather
visual_model.RichText = true
visual_model.Text = "APARÊNCIA:"
visual_model.TextColor3 = Color3.new(1, 1, 1)
visual_model.TextScaled = true
visual_model.TextSize = 14
visual_model.TextWrapped = true
visual_model.TextXAlignment = Enum.TextXAlignment.Left
visual_model.BackgroundColor3 = Color3.new(1, 1, 1)
visual_model.BackgroundTransparency = 1
visual_model.BorderColor3 = Color3.new(0, 0, 0)
visual_model.BorderSizePixel = 0
visual_model.LayoutOrder = 10
visual_model.Position = UDim2.new(0.0844701305, 0, 0.870937347, 0)
visual_model.Size = UDim2.new(0.862, 0,0.08, 0)
visual_model.Visible = true
visual_model.Name = "VisualModel"
visual_model.Parent = frame
local function updateModelState(ghostPart)
	task.spawn(function()
		repeat task.wait() until ghostPart:GetAttribute("VisualModel") ~= nil
		ghostPart:GetAttributeChangedSignal("VisualModel"):Connect(function()
			local hunting = ghostPart:GetAttribute("VisualModel") or false
			if hunting then
				visual_model.Text = "APARÊNCIA: "..hunting
			end
		end)
	end)
end

local laser_visible = Instance.new("TextLabel")
laser_visible.Font = Enum.Font.Merriweather
laser_visible.RichText = true
laser_visible.Text = "VISÍVEL NO LASER:"
laser_visible.TextColor3 = Color3.new(1, 1, 1)
laser_visible.TextScaled = true
laser_visible.TextSize = 14
laser_visible.TextWrapped = true
laser_visible.TextXAlignment = Enum.TextXAlignment.Left
laser_visible.BackgroundColor3 = Color3.new(1, 1, 1)
laser_visible.BackgroundTransparency = 1
laser_visible.BorderColor3 = Color3.new(0, 0, 0)
laser_visible.BorderSizePixel = 0
laser_visible.LayoutOrder = 7
laser_visible.Position = UDim2.new(0.0844701305, 0, 0.761093616, 0)
laser_visible.Size = UDim2.new(0.862, 0,0.08, 0)
laser_visible.Visible = true
laser_visible.Name = "LaserVisible"
laser_visible.Parent = frame
local function updateLaserState(ghostPart)
	task.spawn(function()
		repeat task.wait() until ghostPart:GetAttribute("LaserVisible") ~= nil
		ghostPart:GetAttributeChangedSignal("LaserVisible"):Connect(function()
			local hunting = ghostPart:GetAttribute("LaserVisible") or false
			if hunting == true then
				laser_visible.Text = "VISÍVEL NO LASER: SIM"
			end
		end)
	end)
end

local hunting = Instance.new("TextLabel")
hunting.Font = Enum.Font.Merriweather
hunting.RichText = true
hunting.Text = "CAÇANDO:"
hunting.TextColor3 = Color3.new(1, 1, 1)
hunting.TextScaled = true
hunting.TextSize = 14
hunting.TextWrapped = true
hunting.TextXAlignment = Enum.TextXAlignment.Left
hunting.BackgroundColor3 = Color3.new(1, 1, 1)
hunting.BackgroundTransparency = 1
hunting.BorderColor3 = Color3.new(0, 0, 0)
hunting.BorderSizePixel = 0
hunting.LayoutOrder = 7
hunting.Position = UDim2.new(0.0844701305, 0, 0.761093616, 0)
hunting.Size = UDim2.new(0.862, 0,0.08, 0)
hunting.Visible = true
hunting.Name = "Hunting"
hunting.Parent = frame
local function updateHuntingState(ghostPart)
	task.spawn(function()
		repeat task.wait() until ghostPart:GetAttribute("Hunting") ~= nil
		ghostPart:GetAttributeChangedSignal("Hunting"):Connect(function()
			local hunting = ghostPart:GetAttribute("Hunting") or false
			if hunting and hunting == true then
				hunting.Text = "CAÇANDO: SIM"
				hunting.TextColor3 = Color3.fromRGB(255, 0, 0)  -- Vermelho
			else
				hunting.Text = "CAÇANDO: NÃO"
				hunting.TextColor3 = Color3.fromRGB(0, 255, 0)  -- Verde
			end
		end)
	end)
end
updateAgeState(ghostPart)
updateLaserState(ghostPart)
updateModelState(ghostPart)
updatePhotoState(ghostPart)
updateCurrentState(ghostPart)
updateFavoriteState(ghostPart)
updateHuntingState(ghostPart)
