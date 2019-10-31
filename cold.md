if syn then
  print("ColdFuscator loaded!")
  messagebox("Welcome to ColdFuscator, "..game.Players.LocalPlayer.Name..". Put your script in the textbox and a click somewhere outside the GUI then a file will be saved at your workspace folder. Credits to coldnight#8060", "ColdFuscator", 0x00000040)
else
  game.Players.LocalPlayeR:Kick("You need Synapse X to run the script!")
end

LettersTable = {}
LettersTable[1] = "A"
LettersTable[2] = "B"
LettersTable[3] = "C"
LettersTable[4] = "D"
LettersTable[5] = "E"
LettersTable[6] = "F"
LettersTable[7] = "G"
LettersTable[8] = "H"
LettersTable[9] = "I"
LettersTable[10] = "J"
LettersTable[11] = "K"
LettersTable[12] = "L"
LettersTable[13] = "M"
LettersTable[14] = "N"
LettersTable[15] = "O"
LettersTable[16] = "P"
LettersTable[17] = "Q"
LettersTable[18] = "R"
LettersTable[19] = "S"
LettersTable[20] = "T"
LettersTable[21] = "U"
LettersTable[22] = "V"
LettersTable[23] = "W"
LettersTable[24] = "X"
LettersTable[25] = "Y"
LettersTable[26] = "Z"
LettersTable[27] = "a"
LettersTable[28] = "b"
LettersTable[29] = "c"
LettersTable[30] = "d"
LettersTable[31] = "e"
LettersTable[32] = "f"
LettersTable[33] = "g"
LettersTable[34] = "h"
LettersTable[35] = "i"
LettersTable[36] = "j"
LettersTable[37] = "k"
LettersTable[38] = "l"
LettersTable[39] = "m"
LettersTable[40] = "n"
LettersTable[41] = "o"
LettersTable[42] = "p"
LettersTable[43] = "q"
LettersTable[44] = "r"
LettersTable[45] = "s"
LettersTable[46] = "t"
LettersTable[47] = "u"
LettersTable[48] = "v"
LettersTable[49] = "w"
LettersTable[50] = "x"
LettersTable[51] = "y"
LettersTable[52] = "z"

math.randomseed(tick())

local UIS = game:GetService("UserInputService")
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local TextBox = Instance.new("TextBox")
--Properties:
ScreenGui.Parent = game.CoreGui
ScreenGui.Name = LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..math.random(0, 1000000)

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.654148519, 0, 0.154028431, 0)
Frame.Size = UDim2.new(0, 648, 0, 380)
Frame.Selectable = true
Frame.Active = true
Frame.Draggable = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.Size = UDim2.new(0, 182,0, 44)
TextLabel.Font = Enum.Font.SourceSansLight
TextLabel.Text = "ColdFuscator"
TextLabel.TextColor3 = Color3.new(1, 1, 1)
TextLabel.TextSize = 35
TextLabel.TextWrapped = true

ScrollingFrame.Parent = Frame
ScrollingFrame.BackgroundColor3 = Color3.new(1, 1, 1)
ScrollingFrame.BackgroundTransparency = 1
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0, 0, 0.115789473, 0)
ScrollingFrame.Size = UDim2.new(0, 646, 0, 335)
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 0, 70000)

TextBox.Parent = ScrollingFrame
TextBox.BackgroundColor3 = Color3.new(0.0980392, 0.0980392, 0.0980392)
TextBox.BorderSizePixel = 0
TextBox.Size = UDim2.new(0, 648, 0, 1000000)
TextBox.ClearTextOnFocus = false
TextBox.Font = Enum.Font.SourceSansLight
TextBox.MultiLine = true
TextBox.Text = "print(\"Hello world!\")"
TextBox.TextColor3 = Color3.new(1, 1, 1)
TextBox.TextSize = 20
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

function Encrypt(encryptedCode)
	writefile("ColdFuscated-"..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..LettersTable[math.random(1, 52)]..""..math.random(0, 1000000)..".lua", encryptedCode)
	messagebox("Script saved successfully!", "ColdFuscator", 0x00000000)
	TextBox.Text = ""
end

UIS.TextBoxFocusReleased:Connect(function(Box)
	if Box == TextBox then
		if TextBox.Text:lower() == "cold:close()" then
			ScreenGui:Destroy()
		else
			--

local Script = TextBox.Text 


function Encode(Text)
	Text = tostring(Text)
	local Table = {}
	for i = 1, #Text do
		local T = Text:sub(i, i)
		table.insert(Table, T)
	end
	local T = {}
	local MyText = "'"
	for i, v in pairs(Table) do
		local Key = string.byte(v)
		MyText = MyText..math.floor(Key/128)
		Key = Key % 128
		MyText = MyText..math.floor(Key/64)
		Key = Key % 64
		MyText = MyText..math.floor(Key/32)
		Key = Key % 32
		MyText = MyText..math.floor(Key/16)
		Key = Key % 16
		MyText = MyText..math.floor(Key/8)
		Key = Key % 8
		MyText = MyText..math.floor(Key/4)
		Key = Key % 4
		MyText = MyText..math.floor(Key/2)
		Key = Key % 2
		MyText = MyText..math.floor(Key/1)
		Key = Key % 1
		MyText=MyText.."','"
	end
	MyText = MyText:sub(1, #MyText -1)
	if tonumber(MyText) then
		MyText = tonumber(MyText)
	end
	return MyText
end
local Encoded = Encode(Script)
Encrypt([[
	-- ColdFuscator made by coldnight#8060
	local ColdEncrypted = ]].."table.concat({"..Encoded.."})"..[[ function decode(str) local function binary_to_string(bin) return string.char(tonumber(bin, 2));end;return (str:gsub("(".. ("[01]"):rep(8) .. ")", binary_to_string));end;local Binary = ColdEncrypted _G.ColdeEncode = decode(Binary);loadstring(_G.ColdeEncode)()
	]])
		end
	end
end)
