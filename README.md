-- // Gui To Script By Sea_Dev | franekxd1234500 \\ --

-- // INSTANCES: 22 | SCRIPTS: 6 | MODULES: 0 \\ --

local UI = {}

-- // StarterGui.Radio \\ --
UI["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"))
UI["1"]["Name"] = [[Radio]]
UI["1"]["ResetOnSpawn"] = false

-- // StarterGui.Radio.Sound \\ --
UI["2"] = Instance.new("Sound", UI["1"])
UI["2"]["Looped"] = true

-- // StarterGui.Radio.Frame \\ --
UI["3"] = Instance.new("Frame", UI["1"])
UI["3"]["Active"] = true
UI["3"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0)
UI["3"]["Style"] = Enum.FrameStyle.RobloxRound
UI["3"]["Size"] = UDim2.new(0.19, 0, 0.18, 0)
UI["3"]["Position"] = UDim2.new(0.80247, 0, 0.38801, 0)
UI["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0)

-- // StarterGui.Radio.Frame.Input \\ --
UI["4"] = Instance.new("TextBox", UI["3"])
UI["4"]["CursorPosition"] = -1
UI["4"]["TextWrapped"] = true
UI["4"]["TextSize"] = 28
UI["4"]["Name"] = [[Input]]
UI["4"]["TextYAlignment"] = Enum.TextYAlignment.Top
UI["4"]["TextScaled"] = true
UI["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
UI["4"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal)
UI["4"]["RichText"] = true
UI["4"]["PlaceholderText"] = [[Sound ID Example: 1234567890]]
UI["4"]["Size"] = UDim2.new(0.96, 0, 0.47, 0)
UI["4"]["Position"] = UDim2.new(0.02, 0, 0.02, 0)
UI["4"]["BorderColor3"] = Color3.fromRGB(28, 43, 54)
UI["4"]["Text"] = [[]]

-- // StarterGui.Radio.Frame.Input.LocalScript \\ --
UI["5"] = Instance.new("LocalScript", UI["4"])


-- // StarterGui.Radio.Frame.Input.LocalScript \\ --
UI["6"] = Instance.new("LocalScript", UI["4"])


-- // StarterGui.Radio.Frame.Input.UICorner \\ --
UI["7"] = Instance.new("UICorner", UI["4"])


-- // StarterGui.Radio.Frame.Play \\ --
UI["8"] = Instance.new("TextButton", UI["3"])
UI["8"]["TextWrapped"] = true
UI["8"]["BorderSizePixel"] = 0
UI["8"]["TextSize"] = 14
UI["8"]["TextColor3"] = Color3.fromRGB(0, 0, 0)
UI["8"]["TextYAlignment"] = Enum.TextYAlignment.Top
UI["8"]["TextScaled"] = true
UI["8"]["BackgroundColor3"] = Color3.fromRGB(0, 255, 0)
UI["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal)
UI["8"]["Size"] = UDim2.new(0.47, 0, 0.4, 0)
UI["8"]["Name"] = [[Play]]
UI["8"]["BorderColor3"] = Color3.fromRGB(0, 255, 0)
UI["8"]["Text"] = [[Play]]
UI["8"]["Position"] = UDim2.new(0.02, 0, 0.53, 0)

-- // StarterGui.Radio.Frame.Play.LocalScript \\ --
UI["9"] = Instance.new("LocalScript", UI["8"])


-- // StarterGui.Radio.Frame.Play.UICorner \\ --
UI["a"] = Instance.new("UICorner", UI["8"])


-- // StarterGui.Radio.Frame.Stop \\ --
UI["b"] = Instance.new("TextButton", UI["3"])
UI["b"]["TextWrapped"] = true
UI["b"]["BorderSizePixel"] = 0
UI["b"]["TextSize"] = 14
UI["b"]["TextColor3"] = Color3.fromRGB(0, 0, 0)
UI["b"]["TextYAlignment"] = Enum.TextYAlignment.Top
UI["b"]["TextScaled"] = true
UI["b"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0)
UI["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal)
UI["b"]["Size"] = UDim2.new(0.47, 0, 0.4, 0)
UI["b"]["Name"] = [[Stop]]
UI["b"]["BorderColor3"] = Color3.fromRGB(255, 0, 0)
UI["b"]["Text"] = [[Stop]]
UI["b"]["Position"] = UDim2.new(0.51, 0, 0.53, 0)

-- // StarterGui.Radio.Frame.Stop.LocalScript \\ --
UI["c"] = Instance.new("LocalScript", UI["b"])


-- // StarterGui.Radio.Frame.Stop.UICorner \\ --
UI["d"] = Instance.new("UICorner", UI["b"])


-- // StarterGui.Radio.Frame.Text \\ --
UI["e"] = Instance.new("TextLabel", UI["3"])
UI["e"]["TextWrapped"] = true
UI["e"]["TextStrokeTransparency"] = 0
UI["e"]["BorderSizePixel"] = 0
UI["e"]["TextYAlignment"] = Enum.TextYAlignment.Top
UI["e"]["TextScaled"] = true
UI["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
UI["e"]["TextSize"] = 14
UI["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal)
UI["e"]["TextColor3"] = Color3.fromRGB(255, 255, 255)
UI["e"]["BackgroundTransparency"] = 1
UI["e"]["Size"] = UDim2.new(1, 0, 0.3, 0)
UI["e"]["BorderColor3"] = Color3.fromRGB(28, 43, 54)
UI["e"]["Text"] = [[Sea_Dev Free Radio]]
UI["e"]["Name"] = [[Text]]
UI["e"]["Position"] = UDim2.new(0, 0, -0.3, 0)

-- // StarterGui.Radio.Frame.LocalScript \\ --
UI["f"] = Instance.new("LocalScript", UI["3"])


-- // StarterGui.Radio.StarterGui \\ --
UI["10"] = Instance.new("Frame", UI["1"])
UI["10"]["BorderSizePixel"] = 0
UI["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
UI["10"]["Style"] = Enum.FrameStyle.RobloxRound
UI["10"]["Size"] = UDim2.new(0.33635, 0, 0.30651, 0)
UI["10"]["Position"] = UDim2.new(0.33141, 0, 0.34589, 0)
UI["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0)
UI["10"]["Name"] = [[StarterGui]]

-- // StarterGui.Radio.StarterGui.UICorner \\ --
UI["11"] = Instance.new("UICorner", UI["10"])


-- // StarterGui.Radio.StarterGui.TextLabel \\ --
UI["12"] = Instance.new("TextLabel", UI["10"])
UI["12"]["TextWrapped"] = true
UI["12"]["BorderSizePixel"] = 0
UI["12"]["TextScaled"] = true
UI["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
UI["12"]["TextSize"] = 14
UI["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal)
UI["12"]["TextColor3"] = Color3.fromRGB(0, 0, 0)
UI["12"]["BackgroundTransparency"] = 1
UI["12"]["Size"] = UDim2.new(0.94621, 0, 0.14525, 0)
UI["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0)
UI["12"]["Text"] = [[Welcome To Sea_Dev Free Radio]]
UI["12"]["Position"] = UDim2.new(0.02412, 0, 0.07139, 0)

-- // StarterGui.Radio.StarterGui.TextLabel \\ --
UI["13"] = Instance.new("TextLabel", UI["10"])
UI["13"]["TextWrapped"] = true
UI["13"]["BorderSizePixel"] = 0
UI["13"]["TextScaled"] = true
UI["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
UI["13"]["TextSize"] = 14
UI["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal)
UI["13"]["TextColor3"] = Color3.fromRGB(0, 0, 0)
UI["13"]["BackgroundTransparency"] = 1
UI["13"]["Size"] = UDim2.new(0.96333, 0, 0.57542, 0)
UI["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0)
UI["13"]["Text"] = [[Just Be Sure That You Have The List Of The Ids For The Sound And You Only Hear It Use This For Maybe Your Video Or More]]
UI["13"]["Position"] = UDim2.new(0.0249, 0, 0.27893, 0)

-- // StarterGui.Radio.StarterGui.TextButton \\ --
UI["14"] = Instance.new("TextButton", UI["10"])
UI["14"]["TextWrapped"] = true
UI["14"]["BorderSizePixel"] = 0
UI["14"]["TextSize"] = 14
UI["14"]["TextColor3"] = Color3.fromRGB(0, 0, 0)
UI["14"]["TextScaled"] = true
UI["14"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0)
UI["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal)
UI["14"]["Size"] = UDim2.new(0.03423, 0, 0.10615, 0)
UI["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0)
UI["14"]["Text"] = [[X]]
UI["14"]["Position"] = UDim2.new(0.02411, 0, 0.02926, 0)

-- // StarterGui.Radio.StarterGui.TextButton.LocalScript \\ --
UI["15"] = Instance.new("LocalScript", UI["14"])


-- // StarterGui.Radio.StarterGui.TextButton.UICorner \\ --
UI["16"] = Instance.new("UICorner", UI["14"])
UI["16"]["CornerRadius"] = UDim.new(0, 3)

-- // StarterGui.Radio.Frame.Input.LocalScript \\ --
local function SCRIPT_5()
local script = UI["5"]
	local textBox = script.Parent
	
	-- Function to validate input
	local function onTextChanged()
		local input = textBox.Text
		local newText = ""
	
		-- Loop through each character in the current text
		for i = 1, #input do
			local char = input:sub(i, i) -- Get each character
	
			-- Check if the character is a digit
			if char:match("%d") then
				newText = newText .. char -- Append digit to newText
			end
		end
	
		-- Update the TextBox with the filtered text
		textBox.Text = newText
	
		-- Set the cursor position to the end of the text
		textBox.CursorPosition = #newText
	end
	
	-- Connect the TextBox's TextChanged event to the function
	textBox:GetPropertyChangedSignal("Text"):Connect(onTextChanged)
	
end
task.spawn(SCRIPT_5)
-- // StarterGui.Radio.Frame.Input.LocalScript \\ --
local function SCRIPT_6()
local script = UI["6"]
	---------------------
	--Varialbles--
	---------------------
	
	
	
	---------------------
	--PartSetup--
	---------------------
	
	
	---------------------
	--Script--
	---------------------
	
	while true do
		script.Parent.PlaceholderColor3 = Color3.new(255/255,0/255,0/255)
		for i = 0,255,10 do
			wait()
			script.Parent.PlaceholderColor3 = Color3.new(255/255,i/255,0/255)
		end
		for i = 255,0,-10 do
			wait()
			script.Parent.PlaceholderColor3 = Color3.new(i/255,255/255,0/255)
		end
		for i = 0,255,10 do
			wait()
			script.Parent.PlaceholderColor3 = Color3.new(0/255,255/255,i/255)
		end
		for i = 255,0,-10 do
			wait()
			script.Parent.PlaceholderColor3 = Color3.new(0/255,i/255,255/255)
		end
		for i = 0,255,10 do
			wait()
			script.Parent.PlaceholderColor3 = Color3.new(i/255,0/255,255/255)
		end
		for i = 255,0,-10 do 
			wait()
			script.Parent.PlaceholderColor3 = Color3.new(255/255,0/255,i/255)
		end
	end
	
	
	--made by coopersonmaganlal
end
task.spawn(SCRIPT_6)
-- // StarterGui.Radio.Frame.Play.LocalScript \\ --
local function SCRIPT_9()
local script = UI["9"]
	--Don't touch anything in this script unless you know what you're doing
	script.Parent.MouseButton1Click:connect(function()
	local input = script.Parent.Parent.Input.Text
	local sound = script.Parent.Parent.Parent.Sound
	sound.SoundId = 'rbxassetid://'..input
	sound:Play() end)
end
task.spawn(SCRIPT_9)
-- // StarterGui.Radio.Frame.Stop.LocalScript \\ --
local function SCRIPT_c()
local script = UI["c"]
	--Don't touch anything in this script unless you know what you're doing
	script.Parent.MouseButton1Click:connect(function()	
	script.Parent.Parent.Parent.Sound:Stop()
	end)
end
task.spawn(SCRIPT_c)
-- // StarterGui.Radio.Frame.LocalScript \\ --
local function SCRIPT_f()
local script = UI["f"]
	-- Variables to hold original volume levels
	local originalVolumes = {}
	
	-- Function to find all sounds and set their volumes to 0
	local function setSoundsVolume(volume)
		-- Iterate through all descendants of the game
		for _, sound in ipairs(workspace:GetDescendants()) do
			if sound:IsA("Sound") then
				if not originalVolumes[sound] then
					originalVolumes[sound] = sound.Volume  -- Store the original volume
				end
				sound.Volume = volume
			end
		end
	
		-- Also check SoundService
		for _, sound in ipairs(game:GetService("SoundService"):GetDescendants()) do
			if sound:IsA("Sound") then
				if not originalVolumes[sound] then
					originalVolumes[sound] = sound.Volume  -- Store the original volume
				end
				sound.Volume = volume
			end
		end
	end
	
	-- Function to restore original volumes
	local function restoreVolumes()
		for sound, volume in pairs(originalVolumes) do
			if sound:IsA("Sound") then
				sound.Volume = volume
			end
		end
	end
	
	-- Simulated button clicks for Play and Stop (replace with your actual button references)
	local playButton = script.Parent:WaitForChild("Play")  -- Adjust the path as necessary
	local stopButton = script.Parent:WaitForChild("Stop")  -- Adjust the path as necessary
	
	playButton.MouseButton1Click:Connect(function()
		setSoundsVolume(0)  -- Set volume to 0 when Play is clicked
	end)
	
	stopButton.MouseButton1Click:Connect(function()
		restoreVolumes()  -- Restore original volumes when Stop is clicked
	end)
	
end
task.spawn(SCRIPT_f)
-- // StarterGui.Radio.StarterGui.TextButton.LocalScript \\ --
local function SCRIPT_15()
local script = UI["15"]
	local button = script.Parent  -- Reference to the TextButton
	
	button.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.StarterGui:Destroy()
	end)
	
end
task.spawn(SCRIPT_15)

return UI["1"], require;
