print("ChoPro x HUB [1/4] wait script")
wait("1")
local HWID = {
	"27F22ABF-45BC-4566-B6C0-402C5EEA3056", --chokun6616pro3
	".", --
	".", --
	".", --
}
local KEY = {
	"4MxKH9C5LXUE6wzumSb5YLG6yNoqR4mGxs4zRQQGaAynZ0IODT",
	"1Ou5mxzhi4pmFSNp1NCTrEYTfc4r4RBpPKX3Y6rpM19X4KS0OI",
	"qn0r92c6Pti4ChPCS0V3CAE7oXV4NU84dWUcsp52yDQ5fX6Jwq",
	"BRvq2Sf7L5x3WBwwqKtOfER3leHfBVTfGlq822rteRlbrXSgTA",
}
local LOL = game:GetService("RbxAnalyticsService"):GetClientId()
if game.PlaceId == 537413528 then
	print("ChoPro x HUB [2/4] MAP true")
	wait("1")
----------------------------------------------------------------------
if 
_G.Key == KEY[1] and LOL == HWID[1]
or
_G.Key == KEY[2] and LOL == HWID[2]
or
_G.Key == KEY[3] and LOL == HWID[3]
or
_G.Key == KEY[4] and LOL == HWID[4]
then
	print("ChoPro x HUB [3/4] HWID and KEY true")
	wait("1.5")
	print("ChoPro x HUB [4/4] Ready")
	if _G.Mode == "Farm" then
 while true do
		  game.workspace.Gravity = 0
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-57.3277435, 54.11306, 723.097717, -0.999458313, -4.35474812e-09, -0.032909818, -2.43262122e-09, 1, -5.84459166e-08, 0.032909818, -5.83342015e-08, -0.999458313)
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(25, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-52.8971481, 51.6515312, 8698.07812, -0.999616921, -0.00748590147, 0.0266463459, -7.22909554e-09, 0.962729931, 0.270464629, -0.0276779067, 0.270361006, -0.962361097)}):Play()
wait(25)
game.workspace.Gravity = 192
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-56.2867813, -350.44455, 9496.73535, 0.182033226, -9.23010504e-08, -0.983292401, -1.59918905e-08, 1, -9.68299076e-08, 0.983292401, 3.33509647e-08, 0.182033226) * CFrame.new(0,-2,0)
wait("3")
game.Players.LocalPlayer.Character.Humanoid.Health = 0
wait("16.5")
end
   else
--timeAUtofarm
local tf = 0
local timeZ = 0
local Farmv2 = false
--Chest
local CommonChest = false
local UncommonChest = false
local RareChest = false
local EpicChest = false
local LegendaryChest = false
--Teams
local BlackTeam = false
local BlueTeam  = false 
local GreenTeam = false   
local MagentaTeam = false 
local RedTeam = false    
local WhiteTeam = false
local YellowTeam = false
--Teleport
local Teleport = Game.Players.LocalPlayer.Character.HumanoidRootPart
--Con
_G.autofarm_mode = ""
_G.autofarm = false
function CommonChest()
local args = {
    [1] = "Common Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end

function UncommonChest()
local args = {
    [1] = "Uncommon Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end

function RareChest()
local args = {
    [1] = "Rare Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end

function EpicChest()
local args = {
    [1] = "Epic Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end

function LegendaryChest()
local args = {
    [1] = "Legendary Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
function FarmV2()
while _G.AUTOFARM do
game.workspace.Gravity = 0
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-57.3277435, 54.11306, 723.097717, -0.999458313, -4.35474812e-09, -0.032909818, -2.43262122e-09, 1, -5.84459166e-08, 0.032909818, -5.83342015e-08, -0.999458313)
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(20, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-52.8971481, 51.6515312, 8698.07812, -0.999616921, -0.00748590147, 0.0266463459, -7.22909554e-09, 0.962729931, 0.270464629, -0.0276779067, 0.270361006, -0.962361097)}):Play()
wait("20")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-57.3277435, 54.11306, 723.097717, -0.999458313, -4.35474812e-09, -0.032909818, -2.43262122e-09, 1, -5.84459166e-08, 0.032909818, -5.83342015e-08, -0.999458313)
end
end

function GetGo()
while _G.AUTOFARM do
wait("1")
workspace.ClaimRiverResultsGold:FireServer()
end
end

   --
   local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
    library:CreateWatermark("ChoPro x Hub map Build A Boat For Treasure") -- Config แตกนะเดียวค่อยแก้รอเน็ตมาก่อน By MeowX#0001
    local CenterHubNo1 = library:CreateWindow("ChoPro x Hub",Enum.KeyCode.RightControl)
    local Tab = CenterHubNo1:CreateTab("script")
    local Sector1 = Tab:CreateSector("Farm","left")
	local Sector2 = Tab:CreateSector("Teleport","left") --right
	local Sector3 = Tab:CreateSector("Buy Chest","right")
	local Sector4 = Tab:CreateSector("Mis","right")
    Sector1:AddLabel("Farm")
    Sector1:AddToggle("Auto Farm gold⛵",_G.autofarm,function(t)
       _G.AUTOFARM = t
if tf ~= 0 and timeZ ~= 0 then	   
	   while _G.AUTOFARM do
		  game.workspace.Gravity = 0
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-57.3277435, 54.11306, 723.097717, -0.999458313, -4.35474812e-09, -0.032909818, -2.43262122e-09, 1, -5.84459166e-08, 0.032909818, -5.83342015e-08, -0.999458313)
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(tf, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-52.8971481, 51.6515312, 8698.07812, -0.999616921, -0.00748590147, 0.0266463459, -7.22909554e-09, 0.962729931, 0.270464629, -0.0276779067, 0.270361006, -0.962361097)}):Play()
wait(timeZ)
game.workspace.Gravity = 192
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-56.2867813, -350.44455, 9496.73535, 0.182033226, -9.23010504e-08, -0.983292401, -1.59918905e-08, 1, -9.68299076e-08, 0.983292401, 3.33509647e-08, 0.182033226) * CFrame.new(0,-2,0)
wait("3")
game.Players.LocalPlayer.Character.Humanoid.Health = 0
wait("16.5")
end
elseif tf == 0 and timeZ == 0 then	
	 
	 end
if Farmv2 == true then
FarmV2()
Game.Players.LocalPlayer:Kick("รออัดเดต")
end
		if _G.AUTOFARM == false then
       
		end	
end)
Sector1:AddToggle("Auto Get",false,function(t)
if t == true then
GetGo()
Game.Players.LocalPlayer:Kick("รออัพเดต")
end
if t == false then
 _G.AUTOFARM = false

end
end)
Sector1:AddDropdown("auto farm mode",{
"mode fast",
"mode normat",
"mode slow",
"Auto farmV2"
},_G.autofarm_mode,false,function(t)
if t == "mode fast" then
print(t)
tf = 10
timeZ = 10
end	
if t == "mode normat" then
print(t)
tf = 15
timeZ = 15
end	
 if t == "mode slow" then
print(t)
tf = 25
timeZ = 25
 end	
 if t == "Auto farmV2" then
Farmv2 = true
tf = 0
timeZ = 0
 end
end)
Sector2:AddDropdown("Teams",{
"Black Team   ⬛",
"Blue Team    🟦",
"Green Team   🟩",
"Magenta Team 🟪",
"Red Team     🟥",
"White Team   ⬜",
"Yellow Team  🟨",
},"",false,function(t)
if t == "Black Team   ⬛" then
 BlackTeam = true
 BlueTeam  = false 
 GreenTeam = false   
 MagentaTeam = false 
 RedTeam = false    
 WhiteTeam = false
  YellowTeam = false
end
if t == "Blue Team    🟦" then
BlackTeam = false
 BlueTeam  = true 
 GreenTeam = false   
 MagentaTeam = false 
 RedTeam = false    
 WhiteTeam = false
  YellowTeam = false
end
if t == "Green Team   🟩" then
BlackTeam = false
 BlueTeam  = false 
 GreenTeam = true  
 MagentaTeam = false 
 RedTeam = false    
 WhiteTeam = false
  YellowTeam = false
end
if t == "Magenta Team 🟪" then
BlackTeam = false
 BlueTeam  = false 
 GreenTeam = false   
 MagentaTeam = true
 RedTeam = false    
 WhiteTeam = false
  YellowTeam = false
end	
if t == "Red Team     🟥" then
BlackTeam = false
 BlueTeam  = false 
 GreenTeam = false   
 MagentaTeam = false 
 RedTeam = true 
 WhiteTeam = false
  YellowTeam = false
end
if t == "White Team   ⬜" then
BlackTeam = false
 BlueTeam  = false 
 GreenTeam = false   
 MagentaTeam = false 
 RedTeam = false    
 WhiteTeam = true
  YellowTeam = false
end
if t == "Yellow Team  🟨" then
BlackTeam = false
 BlueTeam  = false 
 GreenTeam = false   
 MagentaTeam = false 
 RedTeam = false    
 WhiteTeam = false
  YellowTeam = true
end
end)
_G.TP = true
 Sector2:AddToggle("Teleport Teams",false,function(t)
 if t == true then
	 _G.TP = true
   while _G.TP do
	 wait("0.1")
	 print("do")
     if BlackTeam == true then
      Teleport.CFrame = CFrame.new(-479.183594, -9.35057735, -69.5191345, 0.0191004109, 0.0480180942, -0.998663843, 8.59629257e-09, 0.998846054, 0.048026856, 0.99981755, -0.000917341269, 0.0190783702)
      end
	  if BlueTeam == true then
      Teleport.CFrame = CFrame.new(371.556, -9.78000164, 299.929535, 0.0484575145, -4.20890123e-09, 0.998825252, -2.11321289e-08, 1, 5.23906651e-09, -0.998825252, -2.13611759e-08, 0.0484575145)
	   end 
	   if GreenTeam == true then
	   Teleport.CFrame = CFrame.new(-479.034119, -9.74000263, 294.020416, 0.016509505, 5.1710586e-08, -0.999863684, 1.7944769e-09, 1, 5.17472643e-08, 0.999863684, -2.64855404e-09, 0.016509505)  
	   end
	   if MagentaTeam == true then
       Teleport.CFrame = CFrame.new(370.649811, -9.89999676, 646.890808, -0.0276095718, -7.04997234e-08, 0.999618769, 9.30200805e-09, 1, 7.07835284e-08, -0.999618769, 1.12527649e-08, -0.0276095718)
	   end
	   if RedTeam == true then
	   Teleport.CFrame = CFrame.new(371.780914, -9.78000164, -64.3214493, 0.0582691319, -4.38945698e-08, 0.99830091, 8.79327056e-10, 1, 4.39179537e-08, -0.99830091, -1.68122805e-09, 0.0582691319)
	   end
	  if WhiteTeam == true then
	   Teleport.CFrame = CFrame.new(-49.1447296, -9.81999874, -494.950012, -0.999949396, 2.60278412e-08, 0.010057237, 2.68992757e-08, 1, 8.65122658e-08, -0.010057237, 8.6778428e-08, -0.999949396)
	  end
	   if YellowTeam == true then
	   Teleport.CFrame = CFrame.new(-478.062744, -9.85999584, 639.235229, -0.0173586681, -1.61047122e-08, -0.999849319, -1.2159628e-08, 1, -1.58960329e-08, 0.999849319, 1.18818617e-08, -0.0173586681)
	   end 	 	 	  	    	
   end
 end
if t == false then
_G.TP = false
wait("0.1")
end
end)
Sector3:AddButton("Buy Common Chest🟢",function()   
CommonChest()
end)	
Sector3:AddButton("Buy Uncommon Chest🟡",function()   
UncommonChest()
end)	
Sector3:AddButton("Buy Rare Chest🔴",function()   
RareChest()
end)	
Sector3:AddButton("Buy Epic Chest🔵",function()   
EpicChest()
end)
Sector3:AddButton("Buy Legendary Chest🟣",function()   
LegendaryChest()
end)
Sector3:AddDropdown("Auto buy chest",{
"Common Chest",
"Uncommon Chest",
"Rare Chest",
"Epic Chest",
"Legendary Chest",
},"",false,function(t)
if t == "Common Chest" then
CommonChest = true --true
UncommonChest = false
RareChest = false
EpicChest = false
LegendaryChest = false
end
if t == "Uncommon Chest" then
CommonChest = false
UncommonChest = true --true
RareChest = false
EpicChest = false
LegendaryChest = false
end
if t == "Rare Chest" then
CommonChest = false
UncommonChest = false
RareChest = true --true
EpicChest = false
LegendaryChest = false
end
if t == "Epic Chest" then
CommonChest = false
UncommonChest = false
RareChest = false
EpicChest = true --true
LegendaryChest = false
end
if t == "Legendary Chest" then
CommonChest = false
UncommonChest = false
RareChest = false
EpicChest = false
LegendaryChest = true --true
end
end)
_G.B = true
Sector3:AddToggle("Buy Chest",false,function(t)
_G.B = true
 if t == true then
 _G.B = true
 if CommonChest == true then
 while _G.B do
 local args = {
    [1] = "Common Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

 wait("1")
end
 end
 if UncommonChest == true then
 while _G.B do
 wait("1")
 local args = {
    [1] = "Uncommon Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
 end
 end
 if RareChest == true then
while _G.B do
wait("1")
local args = {
    [1] = "Rare Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
end
if EpicChest == true then
while _G.B do
wait("1")
local args = {
    [1] = "Epic Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
end
 if LegendaryChest == true then
 while _G.B do
 wait("1")
 local args = {
    [1] = "Legendary Chest",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
 end
 end
 end
 if t == false then
 _G.B = false
 end
end)
--_G.B = false

-- TAD 2
function PlasticBlock()
local args = {
    [1] = "PlasticBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
function GrassBlock()
local args = {
    [1] = "GrassBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))	
end
function SandBlock()
local args = {
    [1] = "SandBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))	
end
function RustedBlock()
local args = {
    [1] = "RustedBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))	
end
function BouncyBlock()
local args = {
    [1] = "BouncyBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))	
end
function FabricBlock()
local args = {
    [1] = "FabricBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
function StoneBlock()
local args = {
    [1] = "StoneBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
function GlassBlock()
local args = {
    [1] = "GlassBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
function SmoothWoodBlock()
local args = {
    [1] = "SmoothWoodBlock",
    [2] = 1
}
workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
function WoodBlock()
local args = {
    [1] = "WoodBlock",
    [2] = 1
}

workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end
Sector4:AddButton("Open GUI Inventory",function()   
game.Players.LocalPlayer.PlayerGui.BuildGui.InventoryFrame.Visible = true
end)
Sector4:AddButton("anti afk by RTrade(YT)",function()   
loadstring(game:HttpGet(('https://raw.githubusercontent.com/RTrade/Voidz/main/Protected%20(12).lua'),true))()
end)	
local Tab = CenterHubNo1:CreateTab("Buy")
local Sector1 = Tab:CreateSector("Buy Block","left")
Sector1:AddButton("Buy Wood Block",function()   
WoodBlock()
end)
Sector1:AddButton("Buy SmoothWoodBlock",function()   
WoodBlock()
end)
Sector1:AddButton("Buy GlassBlock",function()   
GlassBlock()
end)
Sector1:AddButton("Buy StoneBlockk",function()   
StoneBlock()
end)
Sector1:AddButton("Buy FabricBlock",function()   
FabricBlock()
end)
Sector1:AddButton("Buy PlasticBlock",function()   
PlasticBlock()
end)	
Sector1:AddButton("Buy GrassBlock",function()   
GrassBlock()
end)	
Sector1:AddButton("Buy SandBlock",function()   
SandBlock()
end)	
Sector1:AddButton("Buy RustedBlock",function()   
RustedBlock()
end)	
Sector1:AddButton("Buy BouncyBlock",function()   
BouncyBlock()
end)
end
 else
     print("")
	  print("")
	   print("")
	 print("ChoPro x HUB [ERROR] HWID OR KEYS ERROR")
	 print("ChoPro x HUB [/HWID] Copy HWID Ctrl + v ")
	 print("ChoPro x HUB [KEY] Buy script IN discord : https://discord.gg/ryMh5FYSYY")
	 setclipboard("**HWID : "..LOL)
end	 
elseif game.PlaceId == 621129760 then
_G.Key = "CHOPRO-570149632P"
if _G.Key == "CHOPRO-570149632P" then
    local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
    library:CreateWatermark("ChoPro x Hub map kat") -- Config แตกนะเดียวค่อยแก้รอเน็ตมาก่อน By MeowX#0001
    local CenterHubNo1 = library:CreateWindow("ChoPro x Hub",Enum.KeyCode.RightControl)
    local Tab = CenterHubNo1:CreateTab("script")
    local Sector1 = Tab:CreateSector("Set knife","left")
	local Sector2 = Tab:CreateSector("Set script","left")
    Sector1:AddLabel("--KNIFE--")
    Sector1:AddToggle("knife (for ICT)",false,function(t)
       _G.K = t
	   while _G.K do
		   wait("0.1")
local Weapon = "Knife" 
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(Weapon))
wait("1")
game.Players.LocalPlayer.Character.HumanoidRootPart:Destroy()
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.Body.Size = Vector3.new(1048,1048,1048)
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.Body.Transparency = 1
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.ArmL.Size = Vector3.new(1048,1048,1048)
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.ArmL.Transparency = 1
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.ArmR.Size = Vector3.new(1048,1048,1048)
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.ArmR.Transparency = 1
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.IcyHead.Size = Vector3.new(1048,1048,1048)
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.IcyHead.Transparency = 1
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.EffectHolder.Size = Vector3.new(1048,1048,1048)
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.EffectHolder.Transparency = 1
		if _G.K == false then
       print("test")
		end	
	   end
    end)
	Sector1:AddToggle("knife (for F)",false,function(t)
       _G.K = t
	   while _G.K do
		   wait("0.000001")
		game.Players.LocalPlayer.Character.HumanoidRootPart:Destroy()
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.EffectHolder.Size = Vector3.new(2048,2048,2048)
game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.EffectHolder.Transparency = 1
		if _G.K == false then
       print("d")
		end	
	   end
    end)
    Sector1:AddButton("BUTTON BY CENTERHUB",function()
        print("CENTERHUB")
    end)
Sector2:AddButton("Delete Map",function()
        game.workspace.MapMain.MapParts:Destroy()
    end)
Sector2:AddButton("Delete Lobby",function()
        game.workspace.Lobby.MapParts:Destroy()
    end)	
Sector2:AddButton("Gravity 0",function()
        game.workspace.Gravity = 0
    end)
Sector2:AddButton("Reset",function()
        game.Players.LocalPlayer.Character.Humanoid.Health = 0
    end)
Sector2:AddLabel("Teleport")	
Sector2:AddToggle("Teleport to Home",false,function(t)
       _G.K = t
	   while _G.K do
		   wait("0.00000000000001")
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7.99061489, 14.1974401, -68.5265656, -0.882951915, 0, -0.469463408, 0, 1, 0, 0.469463408, 0, -0.882951915)
		if _G.K == false then
       print("d")
		end	
	   end
    end)
Sector2:AddLabel("HIT BLOX SIZE ")
Sector2:AddButton("HIT 1048",function()
        print("CENTERHUB")
    end)
Sector2:AddButton("HIT 2048",function()
local ER = game.Players.LocalPlayer.Character.WeaponHandle.WeaponModel.EffectHolder
          if ER then
ER.Size = Vector3.new(2048,2048,2048)

		  end
    end)
else
	print("no")	
end	
elseif game.PlaceId == 574407221 then
print("ChoPro x HUB [2/4] MAP true")
print("ChoPro x HUB [3/4] FREE")
print("ChoPro x HUB [4/4] Ready")
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("ChoPro X hub", "DarkTheme")
local Tab = Window:NewTab("Players")
local Section = Tab:NewSection("Teleport")
 
--------------------
 
players = {}
for i,v in pairs(game:GetService("Players"):GetChildren()) do
   table.insert(players,v.Name)
end
Section:NewButton("kill all", " ", function()
while true do
local a = Game.Players.LocalPlayer.Character

		wait("0.00001")
for i , v in pairs(game.Players:GetPlayers()) do
	v.Character.HumanoidRootPart.CFrame = a.HumanoidRootPart.CFrame  * CFrame.new(0,50,0)
    v.Character.HumanoidRootPart.CanCollide = false
	v.Character.HumanoidRootPart.Size = Vector3.new(20,100,20)
	v.Character.HumanoidRootPart.Transparency = 1
	end
end
end)
Section:NewDropdown("Select Player", " ", players, function(abc)
    Select = abc
end)
Section:NewButton("Refresh", " ", function()
    table.clear(players)
_G.K = false
for i,v in pairs(game:GetService("Players"):GetChildren()) do
   table.insert(players,v.Name)
end
end)
Section:NewButton("Teleport v1", " ", function()
_G.K = true
    while _G.K  do
wait("0.000000000001")
Game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Game.Players[Select].character.HumanoidRootPart.CFrame * CFrame.new(0,50,0)
Game.Players[Select].Character.HumanoidRootPart.Size = Vector3.new(20,120,20)
Game.Players[Select].Character.HumanoidRootPart.CanCollide = false
Game.Players[Select].Character.HumanoidRootPart.Transparency = 0.5
end
end)
Section:NewButton("Teleport v1 un", " ", function()
_G.K = true
    while _G.K  do
wait("0.000000000001")
Game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Game.Players[Select].character.HumanoidRootPart.CFrame * CFrame.new(0,-40,0)
Game.Players[Select].Character.HumanoidRootPart.Size = Vector3.new(20,120,20)
Game.Players[Select].Character.HumanoidRootPart.CanCollide = false
Game.Players[Select].Character.HumanoidRootPart.Transparency = 0.5
end
end)
Section:NewButton("Teleport v2 ", " ", function()
_G.K = true
    while _G.K  do
wait("0.000000000001")
Game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Game.Players[Select].character.HumanoidRootPart.CFrame * CFrame.new(0,490,490)
Game.Players[Select].Character.HumanoidRootPart.Size = Vector3.new(50,1000,1000)
Game.Players[Select].Character.HumanoidRootPart.CanCollide = false
Game.Players[Select].Character.HumanoidRootPart.Transparency = 0.5
end
end)
Section:NewButton("Teleport v2 un ", " ", function()
_G.K = true
    while _G.K  do
wait("0.000000000001")
Game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Game.Players[Select].character.HumanoidRootPart.CFrame * CFrame.new(0,50,0)
Game.Players[Select].Character.HumanoidRootPart.Size = Vector3.new(1000,1000,1000)
Game.Players[Select].Character.HumanoidRootPart.CanCollide = false
Game.Players[Select].Character.HumanoidRootPart.Transparency = 0.5
end
end)
Section:NewButton("Teleport itme", " ", function()
game.workspace.Gravity = 0
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1465.30457, 80.4331665, 1302.20496, -0.764998615, 7.49616476e-08, -0.644031942, 3.17333786e-08, 1, 7.87005305e-08, 0.644031942, 3.97684872e-08, -0.764998615)
wait("0.1")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1537.62598, 62.2246475, 1031.40955, 0.358497173, -3.85401613e-08, -0.933530807, 1.26319918e-07, 1, 7.2254438e-09, 0.933530807, -1.20513832e-07, 0.358497173)
wait("0.1")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1124.77405, 62.2249718, 1031.0481, 0.0564258434, 4.0894359e-09, 0.998406768, -1.28696547e-08, 1, -3.36862183e-09, -0.998406768, -1.26590729e-08, 0.0564258434)
wait("0.1")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1481.33044, 80.425621, 1290.55896, -0.756504118, 8.36622576e-08, -0.653988898, -1.8721924e-10, 1, 1.28142673e-07, 0.653988898, 9.70629017e-08, -0.756504118)
wait("0.1") 
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1537.14783, 62.2255135, 1154.37146, -0.315739602, -1.52889985e-08, -0.948845863, -5.9675898e-08, 1, 3.74459841e-09, 0.948845863, 5.78055506e-08, -0.315739602)
wait("0.1") 
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1566.16516, 80.4254227, 1010.50031, 0.371409446, 8.74739214e-09, -0.928469181, 7.93292472e-08, 1, 4.11548626e-08, 0.928469181, -8.89400624e-08, 0.371409446)
wait("0.1") 
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1128.07678, 62.6252823, 1161.94067, 0.813342094, -3.28138192e-08, 0.581785738, 3.20936486e-08, 1, 1.1534671e-08, -0.581785738, 9.28999278e-09, 0.813342094)
wait("0.1")
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1453.53589, 62.2226868, 1269.23401, -0.754345179, 0, -0.656477928, 0, 1, 0, 0.656477928, 0, -0.754345179)
end)
local Tab = Window:NewTab("Set Scripts")
local Section = Tab:NewSection("Gravity")
Section:NewButton("Gravity 192", " ", function()
game.workspace.Gravity = 192
end)
Section:NewButton("Teleport Home", " ", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1333.72595, 62.0571556, 1092.84619, -0.662634194, -5.38551959e-09, 0.74894321, 1.29762701e-09, 1, 8.33891178e-09, -0.74894321, 6.49749721e-09, -0.662634194)
end)
local Section = Tab:NewSection("auto farm")
Section:NewToggle("Auto farm", "ToggleInfo", function(state)
    if state then
_G.E = true
while _G.E do
local a = game.Players.LocalPlayer.Character.HumanoidRootPart
for i,v in pairs(game.Workspace.Crates.CashCrate:GetChildren()) do
wait(0.1)
v.CFrame = a.CFrame * CFrame.new(0,0,0) --1y
v.CanCollide = false
v.Anchored = true
end
end
    else
        _G.E = false
    end
end)
while true do
	 wait("0")
	 Game.Players.LocalPlayer.Character.HumanoidRootPart.Size = Vector3.new(1,2,1)
 end
 else 
 --game.Players.LocalPlayer:Kick("ERROR MAP")
 print("ChoPro x HUB [2/4] ERROR MAP :"..game.PlaceId)
 print("")
end	
