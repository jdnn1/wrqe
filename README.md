
-- Instances:

local wrqehubv3 = Instance.new("ScreenGui")
local Hub = Instance.new("Frame")
local name = Instance.new("TextLabel")
local dahood = Instance.new("TextButton")
local jail = Instance.new("TextButton")
local funky = Instance.new("TextButton")
local mm2 = Instance.new("TextButton")
local struck = Instance.new("TextButton")
local silly = Instance.new("ImageLabel")
local silly2 = Instance.new("ImageLabel")
local ds1 = Instance.new("TextLabel")
local moresilly = Instance.new("ImageLabel")
local msdw = Instance.new("TextLabel")

--Properties:

wrqehubv3.Name = "wrqehubv3"
wrqehubv3.Parent = game.Workspace
wrqehubv3.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Hub.Name = "Hub"
Hub.Parent = wrqehubv3
Hub.BackgroundColor3 = Color3.fromRGB(85, 85, 127)
Hub.BorderSizePixel = 0
Hub.Position = UDim2.new(0.536170483, 0, 0.269326687, 0)
Hub.Size = UDim2.new(0, 534, 0, 276)
Hub.Active = true
Hub.Draggable = true

name.Name = "name"
name.Parent = Hub
name.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
name.BorderColor3 = Color3.fromRGB(85, 85, 127)
name.BorderSizePixel = 0
name.Position = UDim2.new(-0.000105154199, 0, -0.000161765274, 0)
name.Size = UDim2.new(0, 534, 0, 45)
name.Font = Enum.Font.Unknown
name.Text = "wrqehub V3"
name.TextColor3 = Color3.fromRGB(255, 255, 255)
name.TextSize = 30.000

dahood.Name = "dahood"
dahood.Parent = Hub
dahood.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
dahood.BorderSizePixel = 0
dahood.Position = UDim2.new(0.0505198948, 0, 0.205387175, 0)
dahood.Size = UDim2.new(0, 76, 0, 45)
dahood.Style = Enum.ButtonStyle.RobloxRoundButton
dahood.Font = Enum.Font.Unknown
dahood.Text = "Dahood"
dahood.TextColor3 = Color3.fromRGB(0, 0, 0)
dahood.TextSize = 14.000
dahood.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/SpaceYes/Lua/Main/DaHood.Lua'))()
end)

jail.Name = "jail"
jail.Parent = Hub
jail.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
jail.BorderSizePixel = 0
jail.Position = UDim2.new(0.807943821, 0, 0.205376819, 0)
jail.Size = UDim2.new(0, 76, 0, 45)
jail.Style = Enum.ButtonStyle.RobloxRoundButton
jail.Font = Enum.Font.Unknown
jail.Text = "Jailbreak"
jail.TextColor3 = Color3.fromRGB(0, 0, 0)
jail.TextSize = 14.000
jail.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/piglex9/icetray3/main/latest.lua"))()
end)

funky.Name = "funky"
funky.Parent = Hub
funky.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
funky.BorderSizePixel = 0
funky.Position = UDim2.new(0.238733426, 0, 0.205387175, 0)
funky.Size = UDim2.new(0, 76, 0, 45)
funky.Style = Enum.ButtonStyle.RobloxRoundButton
funky.Font = Enum.Font.Unknown
funky.Text = "Funky Friday"
funky.TextColor3 = Color3.fromRGB(0, 0, 0)
funky.TextSize = 13.000
funky.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/wally-rblx/funky-friday-autoplay/main/main.lua",true))()
end)

mm2.Name = "mm2"
mm2.Parent = Hub
mm2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
mm2.BorderSizePixel = 0
mm2.Position = UDim2.new(0.427635431, 0, 0.205753624, 0)
mm2.Size = UDim2.new(0, 76, 0, 45)
mm2.Style = Enum.ButtonStyle.RobloxRoundButton
mm2.Font = Enum.Font.Unknown
mm2.Text = "MM2"
mm2.TextColor3 = Color3.fromRGB(0, 0, 0)
mm2.TextSize = 14.000
mm2.MouseButton1Down:connect(function()
	getgenv().mainKey = "nil" local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https://api.eclipsehub.xyz/auth"c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)()
end)

struck.Name = "struck"
struck.Parent = Hub
struck.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
struck.BorderSizePixel = 0
struck.Position = UDim2.new(0.619745851, 0, 0.205753624, 0)
struck.Size = UDim2.new(0, 76, 0, 45)
struck.Style = Enum.ButtonStyle.RobloxRoundButton
struck.Font = Enum.Font.Unknown
struck.Text = "Strucid"
struck.TextColor3 = Color3.fromRGB(0, 0, 0)
struck.TextSize = 14.000
struck.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/jdnn1/strucid/main/README.md'))()
end)

silly.Name = "silly"
silly.Parent = Hub
silly.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
silly.BorderSizePixel = 0
silly.Size = UDim2.new(0, 190, 0, 44)
silly.Image = "rbxassetid://11176073563"

silly2.Name = "silly2"
silly2.Parent = Hub
silly2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
silly2.BorderSizePixel = 0
silly2.Position = UDim2.new(0.669534981, 0, 0, 0)
silly2.Size = UDim2.new(0, 176, 0, 44)
silly2.Image = "rbxassetid://11176073563"

ds1.Name = "ds1"
ds1.Parent = Hub
ds1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ds1.BackgroundTransparency = 1.000
ds1.BorderSizePixel = 0
ds1.Position = UDim2.new(0.342512906, 0, 0.159420297, 0)
ds1.Size = UDim2.new(0, 183, 0, 13)
ds1.Font = Enum.Font.Unknown
ds1.Text = "discord.gg/JsrEpqwNrd"
ds1.TextColor3 = Color3.fromRGB(255, 255, 255)
ds1.TextSize = 14.000

moresilly.Name = "moresilly"
moresilly.Parent = Hub
moresilly.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
moresilly.BorderSizePixel = 0
moresilly.Position = UDim2.new(0.33348465, 0, 0.420289844, 0)
moresilly.Size = UDim2.new(0, 191, 0, 145)
moresilly.Image = "rbxassetid://11176073563"

msdw.Name = "msdw"
msdw.Parent = Hub
msdw.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
msdw.BackgroundTransparency = 1.000
msdw.BorderSizePixel = 0
msdw.Position = UDim2.new(0.348130882, 0, 0.474637687, 0)
msdw.Size = UDim2.new(0, 183, 0, 13)
msdw.Font = Enum.Font.Unknown
msdw.Text = "more soon dw"
msdw.TextColor3 = Color3.fromRGB(255, 255, 255)
msdw.TextSize = 14.000
