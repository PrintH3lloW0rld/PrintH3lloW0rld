---Booting Up UI Library
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Philippines Hub", HidePremium = false, IntroEnabled = false, SaveConfig = true, ConfigFolder = "OrionTest"})
---Tab
local CreditTab = Window:MakeTab({
	Name = "Credits",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local BloxTab = Window:MakeTab({
	Name = "Blox Fruits",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
---Section
local Section = BloxTab:AddSection({
	Name = "Blox Fruits Script"
})
---Blox Fruit Buttons
BloxTab:AddButton({
	Name = "Zen Hub",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/ZenHub/main/Loader", true))()
  	end    
})
BloxTab:AddButton({
	Name = "CFrame Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/CFrame3310/CFrameHub/main/BloxFruit_Mobile.lua"))()
  	end    
})
BloxTab:AddButton({
	Name = "Neva Hub",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/VEZ2/NEVAHUB/main/2'))()
  	end    
})
BloxTab:AddButton({
	Name = "Sxrge Script Hub (Support BloxFruits)",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/sxrge3k/sxrge_ssh_hub/main/sxrge_script_hub"))()
  	end    
})
BloxTab:AddButton({
	Name = "Mukuro Hub",
	Callback = function()
        loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
  	end    
})
BloxTab:AddButton({
	Name = "Hoho Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HohoV2/main/ScriptLoad.lua"))()
  	end    
})
BloxTab:AddButton({
	Name = "Unique Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AkiraNus/UniquehubKak/main/FreeCr.Xenonhub"))()
  	end    
})
BloxTab:AddButton({
	Name = "PlayBack Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/NeaPchX2/Playback-X-HUB/main/Protected.lua.txt"))()
  	end    
})
BloxTab:AddButton({
	Name = "String Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/StringV2/StringHub/main/BF.txt", true))()
  	end    
})
BloxTab:AddButton({
	Name = "RTN Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/WindowsXp12/rtnhub/main/bloxfruit.lua"))()
  	end    
})
BloxTab:AddButton({
	Name = "BloxFruits (idk what name)",
	Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/HSzQz2g3", true))()
  	end    
})
BloxTab:AddButton({
	Name = "Mango Hub",
	Callback = function()
        getgenv().WaterMark = true
        loadstring(game:HttpGet("https://gitlab.com/L1ZOT/mango-hub/-/raw/main/Mango-Bloxf-Fruits-Beta"))()
  	end    
})
BloxTab:AddButton({
	Name = "Ripper Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/RIPPERHUBV2.lua"))()
  	end    
})
BloxTab:AddButton({
	Name = "ATR Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/ATR",true))()
  	end    
})
BloxTab:AddButton({
	Name = "Maru Hub",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/joi-droid/MaruHubBF/main/GOHANSSJ3'))()
  	end
})
BloxTab:AddButton({
	Name = "Ripper Hub V1 (idk this will work)",
	Callback = function()
        _G.Color = Color3.fromRGB(52, 190, 255)
        loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/NEWBF.lua"))()
  	end    
})
BloxTab:AddButton({
	Name = "Project Meow",
	Callback = function()
        loadstring(game:HttpGet"https://rawscripts.net/raw/Project-Meow_421")()
  	end    
})
BloxTab:AddButton({
	Name = "Tawan X Hub",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/kill55547/TAWAN_HUB/main/hub.lua.txt', true))()
  	end    
})
BloxTab:AddButton({
	Name = "Astro Hub",
	Callback = function()
        loadstring(game:HttpGet'https://raw.githubusercontent.com/AstroScripter/ASTROHUB/main/Main/BloxFruit-1.lua')()
  	end    
})
BloxTab:AddButton({
	Name = "SMZ Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Frerfgzz/free-script/main/SMZHUBv2BETA"))()
  	end    
})
BloxTab:AddButton({
	Name = "Power X Hub",
	Callback = function()
        _G.Color = Color3.fromRGB(0, 255, 17)
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/PowerxCANDYYY/BFFREE/main/POWERX.lua"),true))()
  	end    
})
BloxTab:AddButton({
	Name = "Netnayay hub (idk whats the true name)",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/NinoGod/NetnaYay/8d21ce23346c500c93bb8b4a71f7791e4058a70b/startload.lua'))()
  	end    
})
BloxTab:AddButton({
	Name = "Ren Hub",
	Callback = function()
      	loadstring(game:HttpGet("https://raw.githubusercontent.com/MxntyButDiff/Blox-Fruit/main/Bf-Obf.txt"))()
  	end    
})
local Section = CreditTab:AddSection({
	Name = "Credits to Mark Fedillaga"
})
local Section = CreditTab:AddSection({
	Name = "Facebook: Mark Fedillaga"
})
local Section = CreditTab:AddSection({
	Name = "Youtube: BaconExploiter"
})
local Section = CreditTab:AddSection({
	Name = "Note: This is Not All My Script"
})
