if not game:IsLoaded() then
    game.Loaded:Wait()
    end 

game.StarterGui:SetCore("SendNotification", {
        Title = "Creator";
        Text = "Demoww#6235"; 
        Duration = 5;
    })


game.StarterGui:SetCore("SendNotification", {
        Title = "Whitelist removed";
        Text = "idk why lmao"; 
        Duration = 5;
    })

game.StarterGui:SetCore("SendNotification", {
        Title = "Text -chriscmds";
        Text = "and press f9 to see the full comand list"; 
        Duration = 5;
    })











game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-ns" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Noslow Activated";
        Text = "Imagine Using Noslow xD"; 
        Duration = 5;
    })
         
		while wait() do
for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
    if v.Name == "Justice Combination" then
local action = game.Players.LocalPlayer.Character:WaitForChild("Action")
    if action then wait() action:Destroy() end end
    if v.Name == "Action" then
v:Destroy()
end
    if v.Name == "Attacking" then
v:Destroy()
end
    if v.Name == "Using" then
v:Destroy()
end
    if v.Name == "hyper" then
    v:Destroy()
    end
    if v.Name == "Hyper" then
    v:Destroy()
    end
    if v.Name == "heavy" then
    v:Destroy()
    end
    if v.Name == "KiBlasted" then
        v:Destroy()
        end
        if v.Name == "Tele" then
        v:Destroy()
        end
        if v.Name == "tele" then
        v:Destroy()
        end
        if v.Name == "Killed" then
            v:Destroy()
            end
            if v.Name == "Slow" then
            v:Destroy()
            end
if v.Name == "Block" and v.Value == true then
v.Value = false
end
end
end

	end;
end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-rs" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "HairStylist Activated";
        Text = ""; 
        Duration = 5;
    })
            
             local args = {
		[1] = workspace.FriendlyNPCs:FindFirstChild("Hair Stylist")
	}

	game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(unpack(args))
	
	wait(.3)
	local args = {
		[1] = {
			[1] = "Yes"
		}
	}

	game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))
	wait(.3)
	

	local args = {
		[1] = "woah"
	}

	game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(unpack(args))
end
  
end);  
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-iy" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Infinte yield ";
        Text = "activated"; 
        Duration = 5;
    })
         loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
      end;
end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-ks" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "ki spam";
        Text = "activated"; 
        Duration = 5;
    })
           loadstring(game:HttpGet(('https://pastebin.com/raw/rEespPud'),true))()
     end;
end);

game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-sp" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "speed activated";
        Text = ""; 
        Duration = 5;
    })
         loadstring(game:HttpGet(('https://pastebin.com/raw/JgbJ0Tn4'),true))()
        end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-tn" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Top Respauwn Activated";
        Text = "press k to respauwn"; 
        Duration = 5;
    })
      local lplr = game:GetService("Players").LocalPlayer
local mouse = lplr:GetMouse()

mouse.KeyDown:connect(function(key)
    if key == "k" then
        game:GetService("TweenService"):Create(lplr.Character.HumanoidRootPart, TweenInfo.new(0.3, Enum.EasingStyle.Linear), {CFrame = CFrame.new(100, 100, 100)}):Play()
    end
    end)

mouse.KeyDown:connect(function(key)
    if key == "i" then
        local action = lplr.Character.SuperAction
        action:Destroy()
    end
    end)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-dg" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Dragon queue Activated";
        Text = "press n to use"; 
        Duration = 5;
    })

  loadstring(game:HttpGet(('https://pastebin.com/raw/ddEJm8z2'),true))()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-h" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Hide level ";
        Text = "Activated"; 
        Duration = 5;
    })

      loadstring(game:HttpGet(('https://pastebin.com/raw/4zrzLDZV'),true))()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-block" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "AutoBlock Activated";
        Text = "Press f"; 
        Duration = 5;
    })
        loadstring(game:HttpGet(('https://pastebin.com/raw/UKgK3SYS'),true))()
end;
     end);

game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-gm" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "godmode Activated ";
        Text = "Why u use godmode??"; 
        Duration = 5;
    })
      game:GetService("RunService").Stepped:Connect(function()
firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, game.Workspace.Touchy.Part, 0)
firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, game.Workspace.Touchy.Part, 1)
if game.Players.LocalPlayer.PlayerGui:FindFirstChild("Popup") then
game.Players.LocalPlayer.PlayerGui.Popup:Remove()
end end)
 
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-us" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Ultimate spam";
        Text = "Activated"; 
        Duration = 5;
    })
         loadstring(game:HttpGet(('https://pastebin.com/raw/mR7ZPZGh'),true))()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-ak" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Antikick";
        Text = "Activated"; 
        Duration = 5;
    })
        loadstring(game:HttpGet(('https://pastebin.com/raw/qErssPhJ'),true))()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-hr" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Hard reset ";
        Text = "Activated"; 
        Duration = 5;
    })
         loadstring(game:HttpGet(('https://pastebin.com/raw/TK7s9pb3'),true))()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-atack" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Melee spam  ";
        Text = "Activated"; 
        Duration = 5;
    })  
       loadstring(game:HttpGet(('https://pastebin.com/raw/SuCm1x7c'),true))()
end;
     end); 
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-toppad" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting";
        Text = "GL"; 
        Duration = 5;
    }) 
        loadstring(game:HttpGet(('https://pastebin.com/raw/YnQetaay'),true))()
 end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-lock" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Lock Activated v to use";
        Text = "lmao using lock in pvp"; 
        Duration = 5;
    }) 
       loadstring(game:HttpGet(('https://pastebin.com/raw/KRUMhGfr'),true))()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-earth" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "Might by laggy there"; 
        Duration = 5;
    }) 
       game:GetService("TeleportService"):Teleport(536102540, game.Players.LocalPlayer)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-namek" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "Wtf u doing there"; 
        Duration = 5;
    }) 
       game:GetService("TeleportService"):Teleport(882399924, game.Players.LocalPlayer)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-space" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "Hmmm..."; 
        Duration = 5;
    })
        game:GetService("TeleportService"):Teleport(478132461, game.Players.LocalPlayer)
end;
     end); 
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-sw" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "U helping right?"; 
        Duration = 5;
    })
         game:GetService("TeleportService"):Teleport(2046990924, game.Players.LocalPlayer)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-future" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "Why to go future?"; 
        Duration = 5;
    })
       game:GetService("TeleportService"):Teleport(569994010, game.Players.LocalPlayer)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-queue" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = ""; 
        Duration = 5;
    })
          game:GetService("TeleportService"):Teleport(3565304751, game.Players.LocalPlayer)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-zaros" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "Do all guests they give good exp"; 
        Duration = 5;
    })
         game:GetService("TeleportService"):Teleport(2651456105, game.Players.LocalPlayer)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-heaven" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "Noice"; 
        Duration = 5;
    })
            game:GetService("TeleportService"):Teleport(3552157537, game.Players.LocalPlayer)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-brolypad" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "GL"; 
        Duration = 5;
    })
       loadstring(game:HttpGet(('https://pastebin.com/raw/gFj09fmm'),true))()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-autoearth" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Doing guests";
        Text = "xD"; 
        Duration = 5;
    })
     game.workspace.FriendlyNPCs["Quest Giver"]:Destroy()
game.workspace.FriendlyNPCs["Quest Giver"]:Destroy()
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Bulma"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "Yes"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Spaceship"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "No"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
--/////////////////////////////////////////////////////
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Trunks [Future]"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "Yes"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["TimeMachine"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "No"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Quest Giver"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "Yes"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["NamekianShip"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "No"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.7)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Elder Kai"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "Yes"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(2.5)
local ChatStart = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart
ChatStart:FireServer(
	workspace.FriendlyNPCs["Korin"]
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
wait (0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "DRINK"
	}
)
wait(0.5)
local ChatAdvance = game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance
ChatAdvance:FireServer(
	{
		[1] = "k"
	}
)
 end;
end);

game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-rj" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Rejoining ";
        Text = ":D"; 
        Duration = 5;
    })
      game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
end;
end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-ars" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Auto respauwn activated ";
        Text = "These motherfucker skids"; 
        Duration = 5;
    })
       _G.k = false
local plr = game.Players.LocalPlayer
plr.Chatted:Connect(function(x)
    if x == "" and _G.k == false then
wait(.8)
_G.k = true
local args = {
    [1] = "",
    [2] = ""
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
elseif x == "" and _G.k == true then
wait(.8)
_G.k = false
local args = {
    [1] = "",
    [2] = ""
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end
end)





game:GetService("RunService").RenderStepped:Connect(function()
    for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do 
    if v.Name:find("MoveStart") and _G.k == false then
        v:Destroy()
    if game.PlaceId == 536102540 then
     local args = {
        [1] = workspace.FriendlyNPCs:FindFirstChild("Hair Stylist")
        }
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(unpack(args))
        wait(.3)
    local args = {
        [1] = {
                [1] = "Yes"
            }
        }
    
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))
        wait(.3)
    local args = {
        [1] = "woah"
        }
    game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(unpack(args))
    else
    game.Players.LocalPlayer.Character.Head:Destroy()
    end
    end
    end
    end)
end;
end);    
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-dc" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Dragon Crush glitch activated ";
        Text = "Use Noslow and u can atack op"; 
        Duration = 5;
    })
     local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:connect(function(key)
if key == "y" or key == "7" or key == "6" or key == "5" or key == "4" or key == "3" or key == "2" or key == "1" or key == "r" or key == "t" then 
 wait(0.1)
 local plr = game.Players.LocalPlayer
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Throw"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Blocked"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["HitDown"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["BoneBreak"]:Destroy()
    end
end)

local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:connect(function(key)
if key == "y" or key == "t" or key == "r" or key == "7" or key == "6" or key == "5" or key == "4" or key == "3" or key == "2" or key == "1"  then
 wait(0.1)
local plr = game.Players.LocalPlayer
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["Flip"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["Throw"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["Blocked"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["HitDown"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["BoneBreak"]:Destroy()
    end
end)
end;
end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-dt" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Dragon Throw glitch activated ";
        Text = "Use Noslow and u can atack op"; 
        Duration = 5;
    })
    local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:connect(function(key)
if key == "y" or key == "7" or key == "6" or key == "5" or key == "4" or key == "3" or key == "2" or key == "1" or key == "r" or key == "t" then 
 wait(0.1)
 local plr = game.Players.LocalPlayer
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Throw"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Blocked"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["HitDown"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["BoneBreak"]:Destroy()
    end
end)

local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:connect(function(key)
if key == "y" or key == "t" or key == "r" or key == "7" or key == "6" or key == "5" or key == "4" or key == "3" or key == "2" or key == "1"  then
 wait(0.1)
local plr = game.Players.LocalPlayer
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["Flip"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["Throw"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["Blocked"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["HitDown"]:Destroy()
        game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["BoneBreak"]:Destroy()
    end
end)
end;
end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-htc" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Teleporting..";
        Text = "ready for good exp :D"; 
        Duration = 5;
    })
         game:GetService("TeleportService"):Teleport(882375367, game.Players.LocalPlayer)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-chriscmds" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "press f9 ";
        Text = "to see the full comand list"; 
        Duration = 5;
    })
        loadstring(game:HttpGet(('https://pastebin.com/raw/rFFMZiKZ'),true))()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-nc" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Noclip activated ";
        Text = "press j to activate and deactive"; 
        Duration = 5;
    })
     local StealthMode = false
local noclip = true
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local mouse = player:GetMouse()

mouse.KeyDown:Connect(function(key)
    if key == "j" then
        noclip = not noclip
        if not StealthMode then
            Indicator.Text = "Noclip: " .. (noclip and "Enabled" or "Disabled")
        end
    end
end)

while true do
    player = game.Players.LocalPlayer
    character = player.Character
    if noclip then
        for _, v in pairs(character:GetDescendants()) do
            pcall(function()
                if v:IsA("BasePart") then
                    v.CanCollide = false
                end
            end)
        end
    end
    game:GetService("RunService").Stepped:wait()
end
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-invis" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "invisible activated ";
        Text = "use -dg to someone now"; 
        Duration = 5;
    })
        lplr=game.Players.LocalPlayer;
char=lplr.Character;

function extrashit()
   game.Players.LocalPlayer.Character.Head['face']:Remove()
   char.Humanoid:EquipTool(lplr.Backpack["Flash Strike"])
   char["Flash Strike"]:Activate()
end;
game.Workspace.Live[lplr.Name].HumanoidRootPart["PowerLevel"]:Remove()


extrashit()
char["Flash Strike"].Activator.Animation:Remove()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-aq" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "anti warmhole activated ";
        Text = ""; 
        Duration = 5;
    })
       game.Workspace.Wormhole:Destroy()
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-beerus" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "beerus animation ";
        Text = "activated"; 
        Duration = 5;
    })
      _G.x = true

if not game:IsLoaded() then
game.Loaded:Wait()
end


    local player = game.Players.LocalPlayer
    local mouse = player:GetMouse()
    local Animate
    local Humanoid = player.Character:FindFirstChild('Humanoid')
      local Animation = Instance.new("Animation", player.Character)
      Animation.AnimationId = "rbxassetid://1171558651"
      Animate = Humanoid:LoadAnimation(Animation)
      Animate:Play()


end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-rainbow" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "hair godmode ";
        Text = "activated"; 
        Duration = 5;
    })
       local plr = game:service'Players'.LocalPlayer
game.Workspace.Live[plr.Name].Parent = game.Workspace.Effects
wait()
local args1 = game:GetService("Workspace").FriendlyNPCs["Hair Stylist"]
game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(args1)
wait(0.30)
local args = {
    [1] = {
        [1] = "Yes",
    },
}
game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))

game:GetService("RunService").RenderStepped:connect(function()
    game:GetService("Players").LocalPlayer.PlayerGui.Setup.Enabled = false
    game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(game:GetService("Players").LocalPlayer.PlayerGui.Setup.Frame.Side.HairColor,"up")
end)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-vanish" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "vanish activated ";
        Text = "press k to enable and disable"; 
        Duration = 5;
    })
       keybind = {'k'}

if not game:IsLoaded() then
   game.Loaded:Wait(); 
end;
wait(3);

--{auto block}--
lplr=game.Players.LocalPlayer;
run=game:GetService('RunService');
mouse=lplr:GetMouse();

args = {
[1] = 0.2
};

ez=false;
run.RenderStepped:connect(function()
if ez then
    lplr.Backpack.ServerTraits.Vanish:FireServer(unpack(args))
end;
end)

mouse.KeyDown:connect(function(key)
if key==keybind[1] then
ez=not ez;
    lplr.Backpack.ServerTraits.Vanish:FireServer(unpack(args))
end;
end)
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-nimbus" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "nimbus animation ";
        Text = "activated"; 
        Duration = 5;
    })
       if not game:IsLoaded() then
    game.Loaded:wait();
end;
wait(3)

lplr=game.Players.LocalPlayer;
char=lplr.Character;

part=Instance.new("Part",char);
function NimbusFunction(lol)
   part.Name = lol
end;

NimbusFunction('Nimbus');
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-chat" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "chat enabled";
        Text = "chat spy"; 
        Duration = 5;
    })
        return(function(IIlIIlIIIIllll,IIlIlllIlllIll,IIIlIIlllI)local IlIlIlIlIlIllIllllIIlI=string.char;local lllllIlIIIIIllllI=string.sub;local llIIllllIlIllIIIIll=table.concat;local IlIllllIIllIllI=math.ldexp;local llIIIIlllIlIllI=getfenv or function()return _ENV end;local IllIIlIlI=select;local lllIIIlIlllllIIlllIl=unpack or table.unpack;local llIIlIlllI=tonumber;local function lIIlIlIllIIlI(IIlIIlIIIIllll)local lllllllIIIl,IIlIlIlIIlIlIIIIlllllIlI,llIllIIIIlIlIIIlII="","",{}local IlIIIllIIIIIIlIIllIllllIl=256;local lllIIIlIlllllIIlllIl={}for IIlIlllIlllIll=0,IlIIIllIIIIIIlIIllIllllIl-1 do lllIIIlIlllllIIlllIl[IIlIlllIlllIll]=IlIlIlIlIlIllIllllIIlI(IIlIlllIlllIll)end;local IIlIlllIlllIll=1;local function lIlIIIlI()local lllllllIIIl=llIIlIlllI(lllllIlIIIIIllllI(IIlIIlIIIIllll,IIlIlllIlllIll,IIlIlllIlllIll),36)IIlIlllIlllIll=IIlIlllIlllIll+1;local IIlIlIlIIlIlIIIIlllllIlI=llIIlIlllI(lllllIlIIIIIllllI(IIlIIlIIIIllll,IIlIlllIlllIll,IIlIlllIlllIll+lllllllIIIl-1),36)IIlIlllIlllIll=IIlIlllIlllIll+lllllllIIIl;return IIlIlIlIIlIlIIIIlllllIlI end;lllllllIIIl=IlIlIlIlIlIllIllllIIlI(lIlIIIlI())llIllIIIIlIlIIIlII[1]=lllllllIIIl;while IIlIlllIlllIll<#IIlIIlIIIIllll do local IIlIlllIlllIll=lIlIIIlI()if lllIIIlIlllllIIlllIl[IIlIlllIlllIll]then IIlIlIlIIlIlIIIIlllllIlI=lllIIIlIlllllIIlllIl[IIlIlllIlllIll]else IIlIlIlIIlIlIIIIlllllIlI=lllllllIIIl..lllllIlIIIIIllllI(lllllllIIIl,1,1)end;lllIIIlIlllllIIlllIl[IlIIIllIIIIIIlIIllIllllIl]=lllllllIIIl..lllllIlIIIIIllllI(IIlIlIlIIlIlIIIIlllllIlI,1,1)llIllIIIIlIlIIIlII[#llIllIIIIlIlIIIlII+1],lllllllIIIl,IlIIIllIIIIIIlIIllIllllIl=IIlIlIlIIlIlIIIIlllllIlI,IIlIlIlIIlIlIIIIlllllIlI,IlIIIllIIIIIIlIIllIllllIl+1 end;return table.concat(llIllIIIIlIlIIIlII)end;local lIlIIIlI=lIIlIlIllIIlI('24426627526625O27627225A23R24X27224Q25225324T27225624R24Z25825B24T27I26626227625525B24Z25726626127623Y24Y25B24N25724S24T26625X27624224X25925B24Y28128328527R27624027V27X27127925024R24T24Q27225724M25725924R24Q25725627224R24S27223X24U24N23L24D25225B28T23X25924S25324U24Q25A27226624L27625224Q24Q24U24T26C26P26P25627H25924X24S25625B24U24U26O2A024Z26P2A425326P24P25725825224X24X25124T26P26H26L26L26E26H26G26J26J26G26G26L26F26E26F2AT26G26K26P25324B26J25925424024W26L25824S25525923V26L23T25B24C23O26F24O26K24P24Z24N24W23X24X24N24M24R23X24124M23S24X23L23X24Y26G24K26F24124324K25924Y23U24024024Q25524524A24N24F24N24N26N23X24523R26G24824A23X23Y26M26K26626527624T2BS27Y27624S25724V24R25728S2D127623V24S24Y26626027624325727F24X25628J27523Y24123X23U2D627524625725B25628528725U27624D24X24W2902E926R23U24N24U27X25Q2762A424U24Y25328D24Q2532E826P25024T2E82DR26624C2DP24N26625W2762492DN23X28524O2EM27X2892DY29R24U2F524S2F725927X2F12752442BZ24024B24W2A02E22DX2662A02E92572E92FS2FW25B25824Y2912882D329824124W24324N24T25724Y2542DJ27624U24R2G12EM26625V2GG2GI2EL25924724Q28E2EM28725R2GG29H24O29D25723Y24S24X2EF24S2EO2DC2662632E624X24Y2A12GF2752E72HD24S26L2FS2542H324Z23W24924C26427627521Q24X24E2HS2HT2HT27S2752482E824Q2EV2FO27L26625S2762BU2942FH23X25B24W24T2EX24Y2DQ25Y27623U28V24Q23X25324K2572HY2HT26K24E2F02IB2GS2H628524924R25326625I2F22DN2H22H428524Q24N29B2IG2552912IR25524W28E2EV2BJ2532I52GW27523W2572EK2EM2H025623X24Q2A125B2JI2662E52752JP24Q2I324S29B2532IK26625H27624A25725425B24R24Y24Q2JG2IQ2GA29024Z2KP24B24O2FW24Q2GV2IB2832DM27P2K32572JU2DA2DC2I525K2762G72L224T2L424A2E82572482KD29029H24W2552662IV23L24926625T27625929C2IQ2982472IH2GS2FP2IU2HZ26621A2692HF26629I25B2532862IZ2752F324Q28G2842ME27Z2HG2LX2902DQ2MM2662E724W24W28X2I52FA2662MJ28524F2562E22DQ2I12662IO24M2I52IM27524L23X2KR25724Z29M2IV24B2402DE27524A24723X2M924F24C24224B24A24J2FS2F52KO2A127X25N2E62LX24325B2512572NE28S2NG2LD2L426625Z2802822MK2J42J62IA2I225324W2562LJ2862KO27G2KE2N62KP2EV24P2MC24Q2IV27625Y2IY2HA2I224S28M2662LA2MN29D2JG2MU2GC23Y25B2D82E92482P827W2FS23S27H2532G12572672672772O429D24C2PI2PH2PJ2K92PM27X2NB2MZ24X24T2JQ2EP24W2H92DF24A25324Z2D02D22752MV24P2EV23V2QF24Z2EV2IR2IT2662PV27523R26623827625O26H2762QV2PW2QU2LP2792752PV2PV2D229M2R62PV27S2RD2RA2QD2782R72DK2M52762HS2RK2PV2MR2RK2HS2Q62RD2HS2HS2OG26626Y2NM28J25Q26V2DE2F12PV26M2752D22892K62752N62S82SE2I92LT2662EH2DE2GM27S2RK27S2IV2RD27S27S2GW2RK2DK2RK2I02GF2HS2SS28J25P2752S12RM2R625Q24C2GF25M2M527S2DK2HS2SL2D22EH2N62R72HS2R42R72R42RT2662O32HZ2P22R52HS2PB2HT2TU2TQ25L2HT2QX2TM2R023K2R72J82TT2762D22RK2D22KG2752RD2D22D225E2R527S25F2R02752HA25C2UN2GF2UQ2HZ2D22TF2SK2752HS25G2DE2UC2662RD2V32U12UH26625D2V325J2DE2D22732UX2R72V92D22S92R727026628O2TQ2VB2752TQ2SR2UY2R72SV2SH2S12U92SQ2R52D22VS2VC2662SV23Q2QD2QJ27526I2DE2HA2T12U127S2D22TE26S28J26A2R62SE23P2762WK2RF2WN27524B2R62722ST2DE26Z2772412GF2TK2SH2UW2T227S26W2SZ2RX2HF27S24A2WL27R2WR2662XC2WQ2762WT2PV2722WE2DE2SO2PV2WC2792LU2HA2HA2VV2D626X2M52HA27Z2T12UO2QD26U2R527Z2S52HZ2Y02R72RD2XU2662Y52RK27Z2WI2Y92D62RP2752UW2UF2LU2DK2DK2XW2IM2XY2HZ2DK2IM2Y22GF2DK2YF2752IM2Y82HT2YW2YB2YM2GF2Z12662IM26T2M52Z62YL2D626Q2792U127Z27Z26R2DJ23M2D62U62RI2622XF2ZR2772W627Z2UT2V32LS2ZL26626O2772PV2IM2ZI27525Q26C2ZB2662ZN27Z26026D310C2R92HF23T2762MR266310L2SH276310P2R7310R2762T7310O2UA2HT310S2P62772ZI2OG26P2R82IZ2VI2HT2F12MY2762RZ2G42TK2I52XL2U12IA2GM26N2V327S2IA2IA2D0310G2UX2RI2HY310S2Q6310X2752GM28A2SI2EH2QV2V02SD2YM26E2OF2662QQ2PV2HS2ZT276312A2V531282D22HK2WV31282OG311Q310H2892U42QV311V2HT311L2OG2892PV2RK2OG2VP2R52F126J2UR2892TS2HF28922N2RE2XE27631392XI27522J2R625O2W628926G310V2WI289313G2R4312D313F2R6313R26622G313H313J2662R22VQ2W62E531272762J82F12F12E52SL2OG2WA2F12RD2OG2HS26F2R5289310B2VQ2752E53130311C2K52WU2752OG27S310H314E31282WK2RK28926B2M5312V2RL2ZP2OG220313A313U3157312X2PV2OG2682R02W62F12M82762EH314F2WU2U1314T266314V24D312L2663151314W2OG2IY2RD2F12OG24F2662VJ2F12TA315R315Y31282XC2RD28931602V32752892892WT2RK2E524831162E52E52LS2RK2GM2462ZJ2GL316T2LS2G42GM312B316D2SI316C2RD311O266247316Z31732742762E52IA2P2316F314Q2SL2F12WT311B310J2SA2762X72RO2762LR2SJ2752LW29D29724N2M028S2IG2FH2QD2752HD2AE24S2S224T2GI2TU2M6269318825Q2IY2N626P24X2542GE2MR2FZ2PS2N52762OZ2JQ2642AO318R26L1D2M82JS26624U2GY2H02JB2H52H72872N62N82NA2762ND2NF2NH310T2662NK2S22NO2NQ2T72NS2NU2NW2NY2DN2E72D82TR2PX24Q2O62O82OA2KS2OD2K42MY24T2G62G82GA2GC2542PU2EV25531862582EV23P25W25V23N2M52R42OG2R429M2N623P27223N2ZD311Z2662G724D2EL2KX2KV2KX2FS2MT2MV2592I52FJ2XG29Z2E831B02I52T72GH2GJ2592MF2662OR2O92F628I31AQ31BA2GP2GR2GT259319427626P27W29M31B331992OB24Z24J2722WN2N628L2PN2W823N26C29M2W824F24Y2DI2MY24L319X25731BY23P2642NX2VQ316Y31AJ2U12X92HY316R2W82YM2432R724I2R62WG2XF31CV2QV316R2U431CS2762ZD316Y313U31D5311M2TO2NM313L31CO316Z2X92SO2SH31112RK2HA310W2VT2XR317M2HS2GW2RR313B27531DQ31DS26631D825O316Y311W2HK2X9314L2R72Q62TQ311D2V231B3317N2U42TQ2MY2V231AQ2SP310I2XA2662UM2ZS2XF31EK31DV2VE312X2W6311N313M28J31EP276313U31EV313U2VL31EQ28J2LU31412QD2SL2752DW2V72HA2SL2HS2E531CR31E231DE2VU2UK2R52R52HA317I2R72HA2RF2HT31CZ310531E4310V2ZP2HS311531EL31BQ313T31CY313H316Y2T427531DO2662HK2PV2TC313U31G831DV2R231D031DA31D327531GE2R7313U31GJ313U31FR312K2U42O325O2O327S2TX31DJ2662U12U92XR2RW2R731GR2SH2U831FK266314O31DM2Z72TL319Q31EG2V031E32HA31H831FN319C2R6318831D22HT2V72UF317K2UD316Z2V72UJ311R31112XQ2K72RN311X2XD26623O31EW2HT31I3317J31HY2VT2762IA2D22XR31EG31E72Y3311131I42U42T22D22UM31II2R62RM2HS29O313Q2XF31IR31FS27S2Q62602ZP27S31I331FY27531J131DV31IU31DY28J2ZZ2602WI27S24X2XD313U31JD31GF27S3111312K2WW2V931J72DK2V431IY2GF31BC31J22FT31G02762GE31F12DK2VE2YM2ZP2DK2LO31JT31K42ZW2GF31GY31K727Z2VL2UF2HA2Q62VN314S2S02M52S72ZE2GF2F12YG2662WY2HZ27S27Z31FP319831G228J31ED31152HA317M316Z2T731KG2D62VX2HT2IM2TN31IG310C2SL27S2E531IH2VZ31HP28J2SU2R52SX2UR27Z31FM31KS2WL2V031882MR2R42R431E931AQ2972E02O824S23V2GB24S2472DQ2T731M228531M52FS31CE318531872M52M72S231C92DI31952E02QQ31B92GO2EM2QV2MY2PL24X24Z31LY2O72852642Y52UF31CN2R32DY2S231N02W32HS2602WT31N731CW31DV2DK313E2662XY311H319C2QJ23S2DE31AJ31HQ2EV2QD31L92QD31JJ2Z8317K310V2M92762YD31JO31LA31IH31IC2RL2VT2T42RB31DV31O531DV31NG266317M2PV2LA2PV2DK313U31OE31DV2WY2PV26W31D82VB31DR313U31OO31O931KW2RU317L2ZD2HS31EN314T31EM31JV27531OA26631D1319C2722OG2W831E92X92RC2VT2HS310N31HO31HS2DE310F2VT31OA31CX27631P32U32M52GM312C2HT31LT31HZ2R331IH31L831HZ31HM310Y2RN31O631NQ31NQ31HJ2MR2KP2MP31AY31B62MW2672MR2XM2XD2XL27S311T2DJ310H2W8316Y31I231HZ310S2HZ24231NB2QV31PU31I72HT26731PX31I12TY31R031N431QX31NL31AG2RN');local IIlIlllIlllIll=(bit or bit32);local IlIIIllIIIIIIlIIllIllllIl=IIlIlllIlllIll and IIlIlllIlllIll.bxor or function(IIlIlllIlllIll,IIlIlIlIIlIlIIIIlllllIlI)local lllllllIIIl,IlIIIllIIIIIIlIIllIllllIl,lllllIlIIIIIllllI=1,0,10 while IIlIlllIlllIll>0 and IIlIlIlIIlIlIIIIlllllIlI>0 do local lllIIIlIlllllIIlllIl,lllllIlIIIIIllllI=IIlIlllIlllIll%2,IIlIlIlIIlIlIIIIlllllIlI%2 if lllIIIlIlllllIIlllIl~=lllllIlIIIIIllllI then IlIIIllIIIIIIlIIllIllllIl=IlIIIllIIIIIIlIIllIllllIl+lllllllIIIl end IIlIlllIlllIll,IIlIlIlIIlIlIIIIlllllIlI,lllllllIIIl=(IIlIlllIlllIll-lllIIIlIlllllIIlllIl)/2,(IIlIlIlIIlIlIIIIlllllIlI-lllllIlIIIIIllllI)/2,lllllllIIIl*2 end if IIlIlllIlllIll<IIlIlIlIIlIlIIIIlllllIlI then IIlIlllIlllIll=IIlIlIlIIlIlIIIIlllllIlI end while IIlIlllIlllIll>0 do local IIlIlIlIIlIlIIIIlllllIlI=IIlIlllIlllIll%2 if IIlIlIlIIlIlIIIIlllllIlI>0 then IlIIIllIIIIIIlIIllIllllIl=IlIIIllIIIIIIlIIllIllllIl+lllllllIIIl end IIlIlllIlllIll,lllllllIIIl=(IIlIlllIlllIll-IIlIlIlIIlIlIIIIlllllIlI)/2,lllllllIIIl*2 end return IlIIIllIIIIIIlIIllIllllIl end local function IIlIlIlIIlIlIIIIlllllIlI(lllllllIIIl,IIlIlllIlllIll,IIlIlIlIIlIlIIIIlllllIlI)if IIlIlIlIIlIlIIIIlllllIlI then local IIlIlllIlllIll=(lllllllIIIl/2^(IIlIlllIlllIll-1))%2^((IIlIlIlIIlIlIIIIlllllIlI-1)-(IIlIlllIlllIll-1)+1);return IIlIlllIlllIll-IIlIlllIlllIll%1;else local IIlIlllIlllIll=2^(IIlIlllIlllIll-1);return(lllllllIIIl%(IIlIlllIlllIll+IIlIlllIlllIll)>=IIlIlllIlllIll)and 1 or 0;end;end;local IIlIlllIlllIll=1;local function lllllllIIIl()local IIlIlIlIIlIlIIIIlllllIlI,lllllllIIIl,lllllIlIIIIIllllI,lllIIIlIlllllIIlllIl=IIlIIlIIIIllll(lIlIIIlI,IIlIlllIlllIll,IIlIlllIlllIll+3);IIlIlIlIIlIlIIIIlllllIlI=IlIIIllIIIIIIlIIllIllllIl(IIlIlIlIIlIlIIIIlllllIlI,222)lllllllIIIl=IlIIIllIIIIIIlIIllIllllIl(lllllllIIIl,222)lllllIlIIIIIllllI=IlIIIllIIIIIIlIIllIllllIl(lllllIlIIIIIllllI,222)lllIIIlIlllllIIlllIl=IlIIIllIIIIIIlIIllIllllIl(lllIIIlIlllllIIlllIl,222)IIlIlllIlllIll=IIlIlllIlllIll+4;return(lllIIIlIlllllIIlllIl*16777216)+(lllllIlIIIIIllllI*65536)+(lllllllIIIl*256)+IIlIlIlIIlIlIIIIlllllIlI;end;local function llIIlIlllI()local lllllllIIIl=IlIIIllIIIIIIlIIllIllllIl(IIlIIlIIIIllll(lIlIIIlI,IIlIlllIlllIll,IIlIlllIlllIll),222);IIlIlllIlllIll=IIlIlllIlllIll+1;return lllllllIIIl;end;local function llIllIIIIlIlIIIlII()local IIlIlIlIIlIlIIIIlllllIlI,lllllllIIIl=IIlIIlIIIIllll(lIlIIIlI,IIlIlllIlllIll,IIlIlllIlllIll+2);IIlIlIlIIlIlIIIIlllllIlI=IlIIIllIIIIIIlIIllIllllIl(IIlIlIlIIlIlIIIIlllllIlI,222)lllllllIIIl=IlIIIllIIIIIIlIIllIllllIl(lllllllIIIl,222)IIlIlllIlllIll=IIlIlllIlllIll+2;return(lllllllIIIl*256)+IIlIlIlIIlIlIIIIlllllIlI;end;local function llIIlllIIIIIlIl()local IIlIlllIlllIll=lllllllIIIl();local lllllllIIIl=lllllllIIIl();local lllllIlIIIIIllllI=1;local IlIIIllIIIIIIlIIllIllllIl=(IIlIlIlIIlIlIIIIlllllIlI(lllllllIIIl,1,20)*(2^32))+IIlIlllIlllIll;local IIlIlllIlllIll=IIlIlIlIIlIlIIIIlllllIlI(lllllllIIIl,21,31);local lllllllIIIl=((-1)^IIlIlIlIIlIlIIIIlllllIlI(lllllllIIIl,32));if(IIlIlllIlllIll==0)then if(IlIIIllIIIIIIlIIllIllllIl==0)then return lllllllIIIl*0;else IIlIlllIlllIll=1;lllllIlIIIIIllllI=0;end;elseif(IIlIlllIlllIll==2047)then return(IlIIIllIIIIIIlIIllIllllIl==0)and(lllllllIIIl*(1/0))or(lllllllIIIl*(0/0));end;return IlIllllIIllIllI(lllllllIIIl,IIlIlllIlllIll-1023)*(lllllIlIIIIIllllI+(IlIIIllIIIIIIlIIllIllllIl/(2^52)));end;local IlIllllIIllIllI=lllllllIIIl;local function lIIlIlIllIIlI(lllllllIIIl)local IIlIlIlIIlIlIIIIlllllIlI;if(not lllllllIIIl)then lllllllIIIl=IlIllllIIllIllI();if(lllllllIIIl==0)then return'';end;end;IIlIlIlIIlIlIIIIlllllIlI=lllllIlIIIIIllllI(lIlIIIlI,IIlIlllIlllIll,IIlIlllIlllIll+lllllllIIIl-1);IIlIlllIlllIll=IIlIlllIlllIll+lllllllIIIl;local lllllllIIIl={}for IIlIlllIlllIll=1,#IIlIlIlIIlIlIIIIlllllIlI do lllllllIIIl[IIlIlllIlllIll]=IlIlIlIlIlIllIllllIIlI(IlIIIllIIIIIIlIIllIllllIl(IIlIIlIIIIllll(lllllIlIIIIIllllI(IIlIlIlIIlIlIIIIlllllIlI,IIlIlllIlllIll,IIlIlllIlllIll)),222))end return llIIllllIlIllIIIIll(lllllllIIIl);end;local IIlIlllIlllIll=lllllllIIIl;local function IIlIIlIIllIIl(...)return{...},IllIIlIlI('#',...)end local function lIlIIIlI()local IIlIIlIIIIllll={};local IlIllllIIllIllI={};local IIlIlllIlllIll={};local IlIlIlIlIlIllIllllIIlI={[#{"1 + 1 = 111";{61;6;648;245};}]=IlIllllIIllIllI,[#{"1 + 1 = 111";{430;946;195;644};{425;436;152;810};}]=nil,[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]=IIlIlllIlllIll,[#{"1 + 1 = 111";}]=IIlIIlIIIIllll,};local IIlIlllIlllIll=lllllllIIIl()local lllllIlIIIIIllllI={}for IIlIlIlIIlIlIIIIlllllIlI=1,IIlIlllIlllIll do local lllllllIIIl=llIIlIlllI();local IIlIlllIlllIll;if(lllllllIIIl==1)then IIlIlllIlllIll=(llIIlIlllI()~=0);elseif(lllllllIIIl==2)then IIlIlllIlllIll=llIIlllIIIIIlIl();elseif(lllllllIIIl==0)then IIlIlllIlllIll=lIIlIlIllIIlI();end;lllllIlIIIIIllllI[IIlIlIlIIlIlIIIIlllllIlI]=IIlIlllIlllIll;end;IlIlIlIlIlIllIllllIIlI[3]=llIIlIlllI();for lIlIIIlI=1,lllllllIIIl()do local IIlIlllIlllIll=llIIlIlllI();if(IIlIlIlIIlIlIIIIlllllIlI(IIlIlllIlllIll,1,1)==0)then local IlIIIllIIIIIIlIIllIllllIl=IIlIlIlIIlIlIIIIlllllIlI(IIlIlllIlllIll,2,3);local lllIIIlIlllllIIlllIl=IIlIlIlIIlIlIIIIlllllIlI(IIlIlllIlllIll,4,6);local IIlIlllIlllIll={llIllIIIIlIlIIIlII(),llIllIIIIlIlIIIlII(),nil,nil};if(IlIIIllIIIIIIlIIllIllllIl==0)then IIlIlllIlllIll[#("cEE")]=llIllIIIIlIlIIIlII();IIlIlllIlllIll[#("Ey2z")]=llIllIIIIlIlIIIlII();elseif(IlIIIllIIIIIIlIIllIllllIl==1)then IIlIlllIlllIll[#("eLA")]=lllllllIIIl();elseif(IlIIIllIIIIIIlIIllIllllIl==2)then IIlIlllIlllIll[#("bHT")]=lllllllIIIl()-(2^16)elseif(IlIIIllIIIIIIlIIllIllllIl==3)then IIlIlllIlllIll[#("8fW")]=lllllllIIIl()-(2^16)IIlIlllIlllIll[#("m1pO")]=llIllIIIIlIlIIIlII();end;if(IIlIlIlIIlIlIIIIlllllIlI(lllIIIlIlllllIIlllIl,1,1)==1)then IIlIlllIlllIll[#("QB")]=lllllIlIIIIIllllI[IIlIlllIlllIll[#("of")]]end if(IIlIlIlIIlIlIIIIlllllIlI(lllIIIlIlllllIIlllIl,2,2)==1)then IIlIlllIlllIll[#("LQW")]=lllllIlIIIIIllllI[IIlIlllIlllIll[#{{794;69;44;211};{88;153;926;727};{239;996;788;629};}]]end if(IIlIlIlIIlIlIIIIlllllIlI(lllIIIlIlllllIIlllIl,3,3)==1)then IIlIlllIlllIll[#("JgvN")]=lllllIlIIIIIllllI[IIlIlllIlllIll[#("p4WF")]]end IIlIIlIIIIllll[lIlIIIlI]=IIlIlllIlllIll;end end;for IIlIlllIlllIll=1,lllllllIIIl()do IlIllllIIllIllI[IIlIlllIlllIll-1]=lIlIIIlI();end;return IlIlIlIlIlIllIllllIIlI;end;local function lIIlIlIllIIlI(IIlIlllIlllIll,IIlIIlIIIIllll,llIllIIIIlIlIIIlII)IIlIlllIlllIll=(IIlIlllIlllIll==true and lIlIIIlI())or IIlIlllIlllIll;return(function(...)local IlIIIllIIIIIIlIIllIllllIl=IIlIlllIlllIll[1];local lllllIlIIIIIllllI=IIlIlllIlllIll[3];local llIIllllIlIllIIIIll=IIlIlllIlllIll[2];local IlIllllIIllIllI=IIlIIlIIllIIl local lllllllIIIl=1;local lIlIIIlI=-1;local IIlIIlIIllIIl={};local IlIlIlIlIlIllIllllIIlI={...};local IllIIlIlI=IllIIlIlI('#',...)-1;local llIIlIlllI={};local IIlIlIlIIlIlIIIIlllllIlI={};for IIlIlllIlllIll=0,IllIIlIlI do if(IIlIlllIlllIll>=lllllIlIIIIIllllI)then IIlIIlIIllIIl[IIlIlllIlllIll-lllllIlIIIIIllllI]=IlIlIlIlIlIllIllllIIlI[IIlIlllIlllIll+1];else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=IlIlIlIlIlIllIllllIIlI[IIlIlllIlllIll+#{{498;453;58;736};}];end;end;local IIlIlllIlllIll=IllIIlIlI-lllllIlIIIIIllllI+1 local IIlIlllIlllIll;local lllllIlIIIIIllllI;while true do IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("a")];if lllllIlIIIIIllllI<=#("ey5fdtBe59yoyflFMfjHMtuDVabjZAZT3VrRzrF6YDFxyBfx")then if lllllIlIIIIIllllI<=#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{547;166;608;35};"1 + 1 = 111";{582;404;415;807};{471;408;474;29};"1 + 1 = 111";"1 + 1 = 111";{135;215;172;406};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{192;8;32;129};"1 + 1 = 111";{437;136;189;134};"1 + 1 = 111";}then if lllllIlIIIIIllllI<=#("nSjY8fu5OgR")then if lllllIlIIIIIllllI<=#("nzmJH")then if lllllIlIIIIIllllI<=#("67")then if lllllIlIIIIIllllI<=#("")then if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";}]]==IIlIlllIlllIll[#("nU1A")])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#{"1 + 1 = 111";{91;24;661;593};{345;318;297;307};}];end;elseif lllllIlIIIIIllllI>#("H")then local IIlIlllIlllIll=IIlIlllIlllIll[#("vU")]IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll](IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll+1])else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("zc")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("GWY")]];end;elseif lllllIlIIIIIllllI<=#("8mU")then local IIlIlllIlllIll=IIlIlllIlllIll[#("Fr")]local IlIIIllIIIIIIlIIllIllllIl,lllllllIIIl=IlIllllIIllIllI(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll](IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll+1]))lIlIIIlI=lllllllIIIl+IIlIlllIlllIll-1 local lllllllIIIl=0;for IIlIlllIlllIll=IIlIlllIlllIll,lIlIIIlI do lllllllIIIl=lllllllIIIl+1;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];end;elseif lllllIlIIIIIllllI==#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{808;214;479;73};}then local lllllllIIIl=IIlIlllIlllIll[#("K8")];local IlIIIllIIIIIIlIIllIllllIl=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("MPg")]];IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl+1]=IlIIIllIIIIIIlIIllIllllIl;IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl]=IlIIIllIIIIIIlIIllIllllIl[IIlIlllIlllIll[#("ACm3")]];else local IIlIIlIIIIllll;local lllllIlIIIIIllllI;local llIllIIIIlIlIIIlII;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("NG")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("qjn")]][IIlIlllIlllIll[#("GcNY")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{804;497;238;155};{769;439;102;513};}]]=IIlIlllIlllIll[#("fUI")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("2oT")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];llIllIIIIlIlIIIlII=IIlIlllIlllIll[#("ISA")];lllllIlIIIIIllllI=IIlIlIlIIlIlIIIIlllllIlI[llIllIIIIlIlIIIlII]for IIlIlllIlllIll=llIllIIIIlIlIIIlII+1,IIlIlllIlllIll[#("IEry")]do lllllIlIIIIIllllI=lllllIlIIIIIllllI..IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll];end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ll")]]=lllllIlIIIIIllllI;lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("A1")]]=IIlIlllIlllIll[#("IZr")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIIlIIIIllll=IIlIlllIlllIll[#("Qn")]IIlIlIlIIlIlIIIIlllllIlI[IIlIIlIIIIllll](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,IIlIIlIIIIllll+1,IIlIlllIlllIll[#{{326;137;273;429};"1 + 1 = 111";"1 + 1 = 111";}]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllllIIIl=IIlIlllIlllIll[#("Tg4")];end;elseif lllllIlIIIIIllllI<=#("ag8c6ex9")then if lllllIlIIIIIllllI<=#("NkIR6o")then if not IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Zd")]]then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("TVW")];end;elseif lllllIlIIIIIllllI>#("dq0jxiJ")then local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Bz")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("9jv")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("D3")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("Ch7")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("tG")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Dyi")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("6R")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("frV")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];do return end;else do return end;end;elseif lllllIlIIIIIllllI<=#("50VvpDfIP")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Oc")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("veA")]][IIlIlllIlllIll[#("mPTm")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("3m")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("yeY")]][IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("D0gD")]]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{333;636;64;692};{98;35;913;193};}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("V75")]][IIlIlllIlllIll[#("EayN")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{527;275;687;470};"1 + 1 = 111";}]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("ZsJ")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("49")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("DAL")]][IIlIlllIlllIll[#("UGD1")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("WY")]]==IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("UOvx")]])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("x8q")];end;elseif lllllIlIIIIIllllI==#("nrnHKKK8ua")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{763;796;101;449};}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("1uI")]]+IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{733;350;596;238};}]];else local lllllIlIIIIIllllI;lllllIlIIIIIllllI=IIlIlllIlllIll[#("7l")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]()lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("KJ")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("tdl")]][IIlIlllIlllIll[#("VMyh")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("1j")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ug3")]][IIlIlllIlllIll[#("JbOi")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ao")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("u96")]][IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";{640;975;525;998};{768;601;494;845};}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("4V")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("uHQ")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("MX")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("l8g")]]+IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("FPaF")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{264;890;230;985};}]][IIlIlllIlllIll[#("Yb2")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("bbBC")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];do return end;end;elseif lllllIlIIIIIllllI<=#("QrqF6zsS221IXhgsa")then if lllllIlIIIIIllllI<=#("OIM3hS75GRpJzY")then if lllllIlIIIIIllllI<=#("YoIF0sdX0WRx")then llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("QvB")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";}]];elseif lllllIlIIIIIllllI>#("AADqJnQDVXkJH")then local IIlIIlIIIIllll;local lllllIlIIIIIllllI;lllllIlIIIIIllllI=IIlIlllIlllIll[#("3I")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("Y94")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("9I")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("tS")]]=IIlIlllIlllIll[#("WEO")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("ZR")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1])lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("Ws")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("z5W")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("Isvk")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("Zj")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1])lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ke")]]then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("DQe")];end;else IIlIIlIIIIllll[IIlIlllIlllIll[#("sWo")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("da")]];end;elseif lllllIlIIIIIllllI<=#{{30;933;639;387};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{629;927;769;277};{981;586;470;709};{109;161;620;960};{666;759;555;639};"1 + 1 = 111";{776;643;972;184};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{22;197;910;722};}then local IIlIIlIIIIllll;local lllllIlIIIIIllllI;lllllIlIIIIIllllI=IIlIlllIlllIll[#("uj")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("oyN")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("9stv")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{710;792;643;780};"1 + 1 = 111";}]]=IIlIlllIlllIll[#("kGV")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("ZA")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("PGZ")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("3Q")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("e4z")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("1Mpg")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{90;660;650;771};}]]=IIlIlllIlllIll[#("a8S")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("iR")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("uyV")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("Jf")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ozm")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("S1tW")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{754;692;537;781};{569;451;445;331};}]]=IIlIlllIlllIll[#("rLe")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("vZ")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#{{96;476;751;499};{391;686;344;56};{365;888;688;620};}]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("rx")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("TnG")]];elseif lllllIlIIIIIllllI==#("gAumGgo89kifdCy5")then local IIlIlllIlllIll=IIlIlllIlllIll[#("u0")]IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll](IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll+1])else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("QO")]]=IIlIlllIlllIll[#("TOc")];end;elseif lllllIlIIIIIllllI<=#("sklyDntVBH4DzXeS9QUn")then if lllllIlIIIIIllllI<=#("FWxEts435Bl20iBJyN")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Qq")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("fAz")]][IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("z4BK")]]];elseif lllllIlIIIIIllllI==#("bCeKuGKydyeVNS9XyZ3")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("89")]]=(not IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("rfZ")]]);else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("a3")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("eHJ")]];end;elseif lllllIlIIIIIllllI<=#("4A2FfSKJOOiLdHm2Alc7T")then local llIllIIIIlIlIIIlII;local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("OH")]]=IIlIlllIlllIll[#("MTd")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("mc")]]=IIlIlllIlllIll[#("tWS")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("xE")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#{"1 + 1 = 111";{436;363;416;298};"1 + 1 = 111";}]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("kv")];llIllIIIIlIlIIIlII=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{457;886;289;526};"1 + 1 = 111";"1 + 1 = 111";}]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=llIllIIIIlIlIIIlII;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("1CcP")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("IR")]]=IIlIlllIlllIll[#("CB8")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("rH")]]=IIlIlllIlllIll[#("u2Y")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";}]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("aNR")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("DL")];llIllIIIIlIlIIIlII=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("VV6")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=llIllIIIIlIlIIIlII;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#{{254;926;622;162};"1 + 1 = 111";{86;847;48;855};"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("nD")]]=IIlIlllIlllIll[#("D7H")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("AK")]]=IIlIlllIlllIll[#{"1 + 1 = 111";{87;985;462;685};{538;664;103;483};}];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#{{721;476;628;284};{83;524;791;130};}]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("68D")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("1S")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("YvD")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("xf")]]=(IIlIlllIlllIll[#{{697;335;616;653};{852;204;148;738};{435;281;918;262};}]~=0);lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("57")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("J2F")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("OG")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("5oW")]][IIlIlllIlllIll[#("pPEx")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("dh")];llIllIIIIlIlIIIlII=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("eGs")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=llIllIIIIlIlIIIlII;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#{"1 + 1 = 111";{27;728;205;209};"1 + 1 = 111";{142;219;433;728};}]];elseif lllllIlIIIIIllllI>#("1F1QIk1ucTFDsMKJFM6bTz")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("vQ")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("1zK")]][IIlIlllIlllIll[#("3z3U")]];else local lllllllIIIl=IIlIlllIlllIll[#("oD")]IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllllIIIl+1,IIlIlllIlllIll[#("ToN")]))end;elseif lllllIlIIIIIllllI<=#("DRfGgxmX5B9IxOzkARsMzfKoLs1RAbRlCpy")then if lllllIlIIIIIllllI<=#("COV806Jcsdm5fBHuBX0yh15XGFx4U")then if lllllIlIIIIIllllI<=#("ghqASV5uWDHI6Hf5L9FxVPAa1L")then if lllllIlIIIIIllllI<=#("7CuJPsE6fPQSVzfax0K5yRK4")then local lllllIlIIIIIllllI;local lIlIIIlI;local IIlIIlIIIIllll;IIlIIlIIIIllll=IIlIlllIlllIll[#("EbT")];lIlIIIlI=IIlIlIlIIlIlIIIIlllllIlI[IIlIIlIIIIllll]for IIlIlllIlllIll=IIlIIlIIIIllll+1,IIlIlllIlllIll[#("jSOf")]do lIlIIIlI=lIlIIIlI..IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll];end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Wl")]]=lIlIIIlI;lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("d8")]][IIlIlllIlllIll[#("zH9")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("N2WN")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("66")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("kPu")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("HpOq")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Yy")]]=IIlIlllIlllIll[#("2sO")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("yR")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("DWe")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("D4")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("8r2")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("TM")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("PXz")]][IIlIlllIlllIll[#("QQVi")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("FZ")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Vts")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("cy6R")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{131;21;631;64};"1 + 1 = 111";}]]=IIlIlllIlllIll[#("zkj")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("0e")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("jhv")]))elseif lllllIlIIIIIllllI==#("zxdCSpJhc83C31oCLaq5qT7PO")then local IIlIIlIIIIllll;local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("NI")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ohG")]][IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";{315;344;52;222};"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Mf")]][IIlIlllIlllIll[#("kJX")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("CJsq")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("vt")]][IIlIlllIlllIll[#("VaQ")]]=IIlIlllIlllIll[#("bH0q")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("jST")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("U8")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{759;818;14;870};}]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("jrR")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("3Q")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("hK3")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("y31D")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("L2")]]=IIlIlllIlllIll[#("xSv")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("aG")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("jgA")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Tq")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("BQQ")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("0h")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("VDq")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("cxgp")]];else local lllIIIlIlllllIIlllIl=IIlIlllIlllIll[#("of")];local IlIIIllIIIIIIlIIllIllllIl={};for IIlIlllIlllIll=1,#llIIlIlllI do local IIlIlllIlllIll=llIIlIlllI[IIlIlllIlllIll];for lllllllIIIl=0,#IIlIlllIlllIll do local lllllllIIIl=IIlIlllIlllIll[lllllllIIIl];local lllllIlIIIIIllllI=lllllllIIIl[1];local IIlIlllIlllIll=lllllllIIIl[2];if lllllIlIIIIIllllI==IIlIlIlIIlIlIIIIlllllIlI and IIlIlllIlllIll>=lllIIIlIlllllIIlllIl then IlIIIllIIIIIIlIIllIllllIl[IIlIlllIlllIll]=lllllIlIIIIIllllI[IIlIlllIlllIll];lllllllIIIl[1]=IlIIIllIIIIIIlIIllIllllIl;end;end;end;end;elseif lllllIlIIIIIllllI<=#{"1 + 1 = 111";"1 + 1 = 111";{164;541;7;75};"1 + 1 = 111";"1 + 1 = 111";{727;299;530;662};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{410;102;617;211};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{669;371;878;957};"1 + 1 = 111";{285;460;788;8};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{428;97;985;484};"1 + 1 = 111";"1 + 1 = 111";{843;835;954;262};{299;621;728;864};"1 + 1 = 111";}then llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("a1O")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("9k")]];elseif lllllIlIIIIIllllI>#("hQAzYPgrBRSbaSMtbgN2ZPaHDeJk")then local IIlIlllIlllIll=IIlIlllIlllIll[#("2V")]local IlIIIllIIIIIIlIIllIllllIl,lllllllIIIl=IlIllllIIllIllI(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll](IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll+1]))lIlIIIlI=lllllllIIIl+IIlIlllIlllIll-1 local lllllllIIIl=0;for IIlIlllIlllIll=IIlIlllIlllIll,lIlIIIlI do lllllllIIIl=lllllllIIIl+1;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];end;else local IIlIlllIlllIll=IIlIlllIlllIll[#("Ch")]IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]()end;elseif lllllIlIIIIIllllI<=#("mIJICdKGbQSrYjbSkIVxaBQdBjCP25Tg")then if lllllIlIIIIIllllI<=#("vojiEJObY9A4KaF9ZrGYX5W1GgsL4O")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("u8")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("OvC")]];elseif lllllIlIIIIIllllI>#{{355;648;640;623};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{965;579;756;371};{774;686;924;674};"1 + 1 = 111";{987;856;354;170};{760;175;738;125};{119;262;380;772};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{224;271;459;844};"1 + 1 = 111";{804;755;71;755};{326;351;152;239};{242;42;890;908};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{443;719;449;61};}then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Ld")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("B7y")]]-IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("mOUp")]];else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("7c")]]=#IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("BUq")]];end;elseif lllllIlIIIIIllllI<=#("k3DsoIKhqLHRCStLxpjPoLCUtnbDJ5tTd")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("4p")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("nPc")]]+IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("WV6c")]];elseif lllllIlIIIIIllllI==#("cIX0MLxIWdQLRSiSqggy3JCT8aGgJuqXNn")then IIlIIlIIIIllll[IIlIlllIlllIll[#("nez")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("iN")]];else local IlIIIllIIIIIIlIIllIllllIl=IIlIlllIlllIll[#("KuG")];local lllllllIIIl=IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl]for IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl+1,IIlIlllIlllIll[#("fjh8")]do lllllllIIIl=lllllllIIIl..IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll];end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{277;560;245;294};}]]=lllllllIIIl;end;elseif lllllIlIIIIIllllI<=#("WXGOJrQYzeTGtu0OmNQvDge1Lep9CW27Dcx4UDHgm")then if lllllIlIIIIIllllI<=#("cPpEmWSQek72mPTOcFbQxNlVdr853TfKiSdAMg")then if lllllIlIIIIIllllI<=#("DrVRRaLZRlfBceHxADFB5YWWueyUEMsc5NJz")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("jF")]]={};elseif lllllIlIIIIIllllI==#("5EUCCrUXscFLvO6hP6PF8vMN1ue2dFAGiVE8U")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("sF")]]=(not IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("b2B")]]);else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("hC")]]={};end;elseif lllllIlIIIIIllllI<=#("DHc8cc2ii8x5qQ33NJ1gKhm1UYN9DKj8xQDiD9t")then local lllllllIIIl=IIlIlllIlllIll[#("ra")]IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl]=IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllllIIIl+1,IIlIlllIlllIll[#("bLL")]))elseif lllllIlIIIIIllllI>#("VTlgGhoTMoh5gNzvtlonz2PJYyIKnVBOorv15fuM")then local IIlIIlIIIIllll;local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Yi")]][IIlIlllIlllIll[#("6im")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("87yu")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("kP")]][IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]]=IIlIlllIlllIll[#("j0EX")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("mi")]]={};lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("x3")]][IIlIlllIlllIll[#("TI4")]]=IIlIlllIlllIll[#("jGEj")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";}]][IIlIlllIlllIll[#("AbN")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{185;490;443;42};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Q1")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#{"1 + 1 = 111";{272;763;831;131};{379;972;656;783};}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("Yo")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("C9k")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("XYd5")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Xr")]]=IIlIlllIlllIll[#("Z8P")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("zb")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("GQ0")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("UD")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("j9S")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("qKXA")]];else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("vP")]][IIlIlllIlllIll[#{"1 + 1 = 111";{430;260;476;668};"1 + 1 = 111";}]]=IIlIlllIlllIll[#("nW3a")];end;elseif lllllIlIIIIIllllI<=#("3xoDo1TqhYqVfk2dNshKOG1XEQZqIAo0MOGFBfKHYtf7")then if lllllIlIIIIIllllI<=#("2igEYsXmc5xGC9IcDTSJAiCPxNHSLVtB3NLHSXTgBO")then if IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{510;854;74;162};}]]then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("Wm5")];end;elseif lllllIlIIIIIllllI==#("Si89gbEvLxyUTRBglVeMrM6NYybtP9LhWJTHyOBRgzT")then if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("B7")]]~=IIlIlllIlllIll[#("e9VY")])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#{"1 + 1 = 111";{594;584;626;646};{637;871;747;451};}];end;else local lllllIlIIIIIllllI;local IIlIIlIIIIllll;local llIIlIlllI,lIIlIlIllIIlI;local IlIlIlIlIlIllIllllIIlI;local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("FC")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("LX")];IlIlIlIlIlIllIllllIIlI=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("SPY")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IlIlIlIlIlIllIllllIIlI;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IlIlIlIlIlIllIllllIIlI[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";{297;683;151;596};"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("g9")]llIIlIlllI,lIIlIlIllIIlI=IlIllllIIllIllI(IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]))lIlIIIlI=lIIlIlIllIIlI+lllllIlIIIIIllllI-1 IIlIIlIIIIllll=0;for IIlIlllIlllIll=lllllIlIIIIIllllI,lIlIIIlI do IIlIIlIIIIllll=IIlIIlIIIIllll+1;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=llIIlIlllI[IIlIIlIIIIllll];end;lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("dB")]llIIlIlllI={IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,lIlIIIlI))};IIlIIlIIIIllll=0;for IIlIlllIlllIll=lllllIlIIIIIllllI,IIlIlllIlllIll[#("pqWa")]do IIlIIlIIIIllll=IIlIIlIIIIllll+1;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=llIIlIlllI[IIlIIlIIIIllll];end lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllllIIIl=IIlIlllIlllIll[#("73l")];end;elseif lllllIlIIIIIllllI<=#{"1 + 1 = 111";{362;446;666;700};{996;140;258;482};{669;510;281;66};"1 + 1 = 111";{697;374;393;932};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{115;967;457;788};"1 + 1 = 111";{626;362;400;369};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{538;563;151;963};{48;59;126;794};"1 + 1 = 111";{671;770;587;361};"1 + 1 = 111";{607;727;590;703};"1 + 1 = 111";{406;306;336;311};"1 + 1 = 111";{740;588;988;212};{560;663;854;622};{935;864;169;1};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{952;280;76;407};{760;216;499;69};{225;273;575;786};"1 + 1 = 111";{431;176;404;973};"1 + 1 = 111";"1 + 1 = 111";{874;504;88;525};{417;855;429;717};"1 + 1 = 111";"1 + 1 = 111";{841;432;841;40};{120;784;86;723};"1 + 1 = 111";"1 + 1 = 111";}then if lllllIlIIIIIllllI>#("cESR6Siro4S2x8ab9HAosnomYhSjFFn3vKQdMQIkUL3bX")then do return end;else local IIlIlllIlllIll=IIlIlllIlllIll[#("gE")]IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll](IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll+1])end;elseif lllllIlIIIIIllllI==#("Q9BoVm1ybYoF2Z99WTRYGWs6zt8oESunAFCTSqUbc7J1ZhX")then local lllllIlIIIIIllllI;local llIIlIlllI;local lIlIIIlI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ba")]]=IIlIlllIlllIll[#("9TP")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("hV")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{885;231;372;355};{13;179;6;19};"1 + 1 = 111";}]][IIlIlllIlllIll[#("PRSH")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("dC")]]=IIlIlllIlllIll[#("tIN")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Mb")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Mtj")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lIlIIIlI=IIlIlllIlllIll[#("di2")];llIIlIlllI=IIlIlIlIIlIlIIIIlllllIlI[lIlIIIlI]for IIlIlllIlllIll=lIlIIIlI+1,IIlIlllIlllIll[#("k4Cl")]do llIIlIlllI=llIIlIlllI..IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll];end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("dU")]]=llIIlIlllI;lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Tp")]][IIlIlllIlllIll[#{{861;414;353;285};"1 + 1 = 111";"1 + 1 = 111";}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("JcdI")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Ks")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("zNg")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("jm")];lIlIIIlI=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("lVi")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=lIlIIIlI;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=lIlIIIlI[IIlIlllIlllIll[#("xNDL")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("bs")]]=IIlIlllIlllIll[#("03J")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{486;49;612;882};}]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#{"1 + 1 = 111";{838;943;303;823};"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#{{61;257;966;910};"1 + 1 = 111";}]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("rOQ")]))else local IIlIIlIIIIllll;local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("oI")]]=IIlIlllIlllIll[#("R3L")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";}]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("FJ3")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("uC")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("bly")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#("aOOu")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("e8")]]=IIlIlllIlllIll[#("BEN")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("yc")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#{{982;920;721;168};{400;757;480;640};"1 + 1 = 111";}]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("6u")];IIlIIlIIIIllll=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("zdI")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=IIlIIlIIIIllll;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIIlIIIIllll[IIlIlllIlllIll[#{"1 + 1 = 111";{939;770;684;936};{991;73;453;788};{414;667;413;784};}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("QH")]]=IIlIlllIlllIll[#("UgS")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("91")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("YGS")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("vg")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("8LE")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("KU")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("cR9")]][IIlIlllIlllIll[#("9XXK")]];end;elseif lllllIlIIIIIllllI<=#("lVYjt9X4RFZCnM3sEbfxxqqG9QWJnBhrGpdT4k3ASIbnBsXAdpyXbBv5ErkOmnQqxI58Ikzs")then if lllllIlIIIIIllllI<=#("POZodfR2vG7dupf3ipMapnF1V02xZ231eOxWGQAmDV1STncr0eA4Wr3Cj8En")then if lllllIlIIIIIllllI<=#("tdENg8Q3sxDZzHExXhHXLGUC8eXV4NHlmajRxeMoxyIS7fxVzfv06A")then if lllllIlIIIIIllllI<=#("YtbOcl49PZqNzyW9SGsBm8bF3RbxYqRoWzuyuBKdCz22QC8xMfN")then if lllllIlIIIIIllllI<=#("O9zZrHVvjIkyib0aczPr5o8YgjYBTOUTOvKX9FgYPo44nEUOM")then local lllllIlIIIIIllllI;lllllIlIIIIIllllI=IIlIlllIlllIll[#("OK")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("1tI")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("cZ")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("GnM")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("jD")]]=IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Ro")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("Air")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if not IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Xf")]]then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("u2O")];end;elseif lllllIlIIIIIllllI==#("tnBvAAaLTiStNFYCUXCdbIs0MRueKMAjZVtGrr5kWzV8fvMzfW")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("TN")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("0Ua")]]+IIlIlllIlllIll[#("Hevu")];else local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Yx")]]=(not IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Dix")]]);lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("9hb")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Zv")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("9o")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("dMR")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("r3")]]=IIlIlllIlllIll[#{"1 + 1 = 111";{944;20;966;85};"1 + 1 = 111";}];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("UU")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1])lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("oA")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("FP3")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("8v")]]=IIlIlllIlllIll[#("iEZ")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("cW")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("t0k")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if not IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("p8")]]then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("dLW")];end;end;elseif lllllIlIIIIIllllI<=#("6mI6W5LTSf6bhSIF1krjD1qrMWuVqf58X3D7rZILRIneZyOpH0Un")then local lllllllIIIl=IIlIlllIlllIll[#("vl")]IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl]=IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllllIIIl+1,IIlIlllIlllIll[#("sdl")]))elseif lllllIlIIIIIllllI>#("Mqf5qtaLZDNj8nnoLnbNRD4OlCohenAuSkkNybaGH91fK51jAa6NT")then local llIllIIIIlIlIIIlII;local lllllIlIIIIIllllI;lllllIlIIIIIllllI=IIlIlllIlllIll[#("JM")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1])lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("nW")];llIllIIIIlIlIIIlII=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("1Xd")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=llIllIIIIlIlIIIlII;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("kHKO")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("yY")]]=IIlIlllIlllIll[#("pgk")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ec")]]=IIlIlllIlllIll[#("Cmj")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("G2")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("Ph3")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("T7")]]~=IIlIlllIlllIll[#("tgzp")])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("0Ex")];end;else local lllllllIIIl=IIlIlllIlllIll[#("iJ")];local IlIIIllIIIIIIlIIllIllllIl=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("tHG")]];IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl+1]=IlIIIllIIIIIIlIIllIllllIl;IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl]=IlIIIllIIIIIIlIIllIllllIl[IIlIlllIlllIll[#("NXld")]];end;elseif lllllIlIIIIIllllI<=#("givBTYe3GMcsCYcL1KmGgRMYdqLeReqWLhdcq6rlBOEodqEchYjxBmEzH")then if lllllIlIIIIIllllI<=#("xDn9lBvpRuUau4raeDnxVXWI7254vzNPFTJY8CCc3YKjshEofAibkjX")then local lllllIlIIIIIllllI;local lllIIIlIlllllIIlllIl;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("0V")]]=IIlIlllIlllIll[#("61n")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("bW")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("0JW")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("FK")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("S0Q")]][IIlIlllIlllIll[#("adxC")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("AO")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("MUr")]][IIlIlllIlllIll[#{"1 + 1 = 111";{232;305;217;500};{874;72;153;896};"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{398;132;802;337};{875;729;290;320};}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{237;711;142;726};"1 + 1 = 111";}]][IIlIlllIlllIll[#("WoE8")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("TG")]]=IIlIlllIlllIll[#("QTF")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllIIIlIlllllIIlllIl=IIlIlllIlllIll[#("SLq")];lllllIlIIIIIllllI=IIlIlIlIIlIlIIIIlllllIlI[lllIIIlIlllllIIlllIl]for IIlIlllIlllIll=lllIIIlIlllllIIlllIl+1,IIlIlllIlllIll[#("sqil")]do lllllIlIIIIIllllI=lllllIlIIIIIllllI..IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll];end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("u0")]]=lllllIlIIIIIllllI;lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("j4")]]=IIlIlllIlllIll[#("Qmc")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("OG")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("r3l")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("sG")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("3T8")]][IIlIlllIlllIll[#("DeaY")]];elseif lllllIlIIIIIllllI>#("QQcsGB3sSeFMvDcNalE7nNo0zQZ6pLEv68isAiGC4qCnM13MyGa9P0xc")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{206;940;887;823};"1 + 1 = 111";}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ART")]][IIlIlllIlllIll[#("GDO4")]];else local IlIIIllIIIIIIlIIllIllllIl=IIlIlllIlllIll[#("hS")];local lllIIIlIlllllIIlllIl=IIlIlllIlllIll[#("lLTU")];local lllllIlIIIIIllllI=IlIIIllIIIIIIlIIllIllllIl+2 local IlIIIllIIIIIIlIIllIllllIl={IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl](IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl+1],IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI])};for IIlIlllIlllIll=1,lllIIIlIlllllIIlllIl do IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+IIlIlllIlllIll]=IlIIIllIIIIIIlIIllIllllIl[IIlIlllIlllIll];end;local IlIIIllIIIIIIlIIllIllllIl=IlIIIllIIIIIIlIIllIllllIl[1]if IlIIIllIIIIIIlIIllIllllIl then IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IlIIIllIIIIIIlIIllIllllIl lllllllIIIl=IIlIlllIlllIll[#("CmJ")];else lllllllIIIl=lllllllIIIl+1;end;end;elseif lllllIlIIIIIllllI<=#("m3ZM7cgLjQxuUn1Pcc6lbnIXmIUKFQgMf2moRZ6nuNClHrOsitNXA0A8vb")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ll")]][IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";{437;134;996;280};}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ER3r")]];elseif lllllIlIIIIIllllI==#("zsGfEKUo1aN8mgT1yVvq54BBkcsloCo2PAH4ZH8LWdWsGvBRR9bmaVFF1e5")then local IlIlIlIlIlIllIllllIIlI=llIIllllIlIllIIIIll[IIlIlllIlllIll[#("jzD")]];local lIlIIIlI;local lllllIlIIIIIllllI={};lIlIIIlI=IIIlIIlllI({},{__index=function(lllllllIIIl,IIlIlllIlllIll)local IIlIlllIlllIll=lllllIlIIIIIllllI[IIlIlllIlllIll];return IIlIlllIlllIll[1][IIlIlllIlllIll[2]];end,__newindex=function(IIlIlIlIIlIlIIIIlllllIlI,IIlIlllIlllIll,lllllllIIIl)local IIlIlllIlllIll=lllllIlIIIIIllllI[IIlIlllIlllIll]IIlIlllIlllIll[1][IIlIlllIlllIll[2]]=lllllllIIIl;end;});for lllIIIlIlllllIIlllIl=1,IIlIlllIlllIll[#{"1 + 1 = 111";{436;401;569;468};"1 + 1 = 111";"1 + 1 = 111";}]do lllllllIIIl=lllllllIIIl+1;local IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if IIlIlllIlllIll[#("1")]==87 then lllllIlIIIIIllllI[lllIIIlIlllllIIlllIl-1]={IIlIlIlIIlIlIIIIlllllIlI,IIlIlllIlllIll[#("xrU")]};else lllllIlIIIIIllllI[lllIIIlIlllllIIlllIl-1]={IIlIIlIIIIllll,IIlIlllIlllIll[#("r6V")]};end;llIIlIlllI[#llIIlIlllI+1]=lllllIlIIIIIllllI;end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{568;195;190;660};{772;290;12;240};}]]=lIIlIlIllIIlI(IlIlIlIlIlIllIllllIIlI,lIlIIIlI,llIllIIIIlIlIIIlII);else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("1O")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Xvz")]]-IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("eNA3")]];end;elseif lllllIlIIIIIllllI<=#("qJ9AVUtXJYc0XUF1ii5YMMEpAb235cdUMHumdxHWcOh37lAppNvTjgZPeU9U1A2HUr")then if lllllIlIIIIIllllI<=#("pArYWMiW8EKroMNOrQuKFRQitxX5MVLiP7jZ8YKgbu1kECUhnWK0ASTJUjFzZmk")then if lllllIlIIIIIllllI<=#("3BNrCYPDfnJkZFO1NPS0lVT7nLeYtlrYkPrcYDQzggUmiJToFNWjFtaiSQd0T")then local IlIlIlIlIlIllIllllIIlI=llIIllllIlIllIIIIll[IIlIlllIlllIll[#("J3h")]];local lIlIIIlI;local lllllIlIIIIIllllI={};lIlIIIlI=IIIlIIlllI({},{__index=function(lllllllIIIl,IIlIlllIlllIll)local IIlIlllIlllIll=lllllIlIIIIIllllI[IIlIlllIlllIll];return IIlIlllIlllIll[1][IIlIlllIlllIll[2]];end,__newindex=function(IIlIlIlIIlIlIIIIlllllIlI,IIlIlllIlllIll,lllllllIIIl)local IIlIlllIlllIll=lllllIlIIIIIllllI[IIlIlllIlllIll]IIlIlllIlllIll[1][IIlIlllIlllIll[2]]=lllllllIIIl;end;});for lllIIIlIlllllIIlllIl=1,IIlIlllIlllIll[#("xPar")]do lllllllIIIl=lllllllIIIl+1;local IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if IIlIlllIlllIll[#("S")]==87 then lllllIlIIIIIllllI[lllIIIlIlllllIIlllIl-1]={IIlIlIlIIlIlIIIIlllllIlI,IIlIlllIlllIll[#("cGQ")]};else lllllIlIIIIIllllI[lllIIIlIlllllIIlllIl-1]={IIlIIlIIIIllll,IIlIlllIlllIll[#("9QD")]};end;llIIlIlllI[#llIIlIlllI+1]=lllllIlIIIIIllllI;end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("HM")]]=lIIlIlIllIIlI(IlIlIlIlIlIllIllllIIlI,lIlIIIlI,llIllIIIIlIlIIIlII);elseif lllllIlIIIIIllllI>#("j46UaknLdj9sTeaHYP2ZsRAht0OjuiAZPp70pyIIb4KMklL6hl1y84ICFZBkGe")then local IlIIIllIIIIIIlIIllIllllIl=IIlIlllIlllIll[#("ra")]local lllllIlIIIIIllllI={IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,IlIIIllIIIIIIlIIllIllllIl+1,lIlIIIlI))};local lllllllIIIl=0;for IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl,IIlIlllIlllIll[#("6cIS")]do lllllllIIIl=lllllllIIIl+1;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=lllllIlIIIIIllllI[lllllllIIIl];end else if IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("HY")]]then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("blN")];end;end;elseif lllllIlIIIIIllllI<=#("4UjOEgjqBgtYzgX6hoSbiqb1VSFvB6yc6NP2bIhZ84BqOfivS2s5XdhNSs2VLY0E")then local IlIIIllIIIIIIlIIllIllllIl=IIlIlllIlllIll[#("HTk")];local lllllllIIIl=IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl]for IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl+1,IIlIlllIlllIll[#("0uYc")]do lllllllIIIl=lllllllIIIl..IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll];end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("dR")]]=lllllllIIIl;elseif lllllIlIIIIIllllI>#("q1VB45Kh3do0UmPJjOIODp3GckSPvnje7Ixnx4X7SX493X7gmlCkrZpb8pzUm5WP3")then local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("9y")]][IIlIlllIlllIll[#("A8b")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("kFTA")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("Qm")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("9TK")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";}]][IIlIlllIlllIll[#("6ob")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Mx0f")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("AW")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1])lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("AI")]]=(IIlIlllIlllIll[#{{801;693;387;250};{517;837;884;251};"1 + 1 = 111";}]~=0);lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("nfq")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("7I")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("xs")]]=(IIlIlllIlllIll[#("SEn")]~=0);lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("Yon")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("4g")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Va")]]=(IIlIlllIlllIll[#("sA7")]~=0);lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];llIllIIIIlIlIIIlII[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Jp")]];else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("4d")]][IIlIlllIlllIll[#("2GL")]]=IIlIlllIlllIll[#("PWHf")];end;elseif lllllIlIIIIIllllI<=#("3lZCmo0K5Pu3NomMCjW8WhsuphGdVXbpgT4VqV9muR4KReMkHKDM25xW3EleTXZhOfX3u")then if lllllIlIIIIIllllI<=#("vRjKOfmSOlFuHluzxlvi2WJ5DH2W6LrTZfoVDsqrJkZaJyqOXpTMImJJhoggmBWd3WG")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{122;278;31;361};"1 + 1 = 111";}]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("5mc")]][IIlIlllIlllIll[#("2cUz")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Ug")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("OyS")]][IIlIlllIlllIll[#("HLCy")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("kE")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Oth")]][IIlIlllIlllIll[#("BilU")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{488;742;161;138};"1 + 1 = 111";}]][IIlIlllIlllIll[#("DHk")]]=IIlIlllIlllIll[#("0apF")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("j2")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("UtX")]][IIlIlllIlllIll[#("K3ab")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("gJ")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("FEk")]][IIlIlllIlllIll[#("aY4R")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("UR")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("q64")]][IIlIlllIlllIll[#("jGDc")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Le")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("J6B")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("v5")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("F7S")]][IIlIlllIlllIll[#("YKzj")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("IY")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("CDc")]];elseif lllllIlIIIIIllllI>#("7J5d4dKS6Jveqo9R1PkNGPOoljfiyWgW2ZRntQREN1MJ2c08CfloL25r5R1U8BtkCJlC")then if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("bF")]]~=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("JdvX")]])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("GdC")];end;else if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("8z")]]==IIlIlllIlllIll[#("Dkg0")])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("rGM")];end;end;elseif lllllIlIIIIIllllI<=#("Vxl7RaOcexjthQsK2ka3zsMY6FlIBhs0yARS9q41ro0uSB1VbLJylJjCVyblZgL7ds5R9K")then local lllllIlIIIIIllllI=IIlIlllIlllIll[#("Hn")];local lllIIIlIlllllIIlllIl=IIlIlllIlllIll[#("OHbG")];local IlIIIllIIIIIIlIIllIllllIl=lllllIlIIIIIllllI+2 local lllllIlIIIIIllllI={IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1],IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl])};for IIlIlllIlllIll=1,lllIIIlIlllllIIlllIl do IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl+IIlIlllIlllIll]=lllllIlIIIIIllllI[IIlIlllIlllIll];end;local lllllIlIIIIIllllI=lllllIlIIIIIllllI[1]if lllllIlIIIIIllllI then IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl]=lllllIlIIIIIllllI lllllllIIIl=IIlIlllIlllIll[#("ux0")];else lllllllIIIl=lllllllIIIl+1;end;elseif lllllIlIIIIIllllI==#("MqiLjCrgGOBH0I4PZqo7MpTblO3qzFjVBb7hc799ErFHzJVzjOgBVN7xIhAGJaSaEPfZLWN")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("rl")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("S0Y")]]+IIlIlllIlllIll[#{{758;11;354;459};{325;245;947;198};{654;88;259;997};"1 + 1 = 111";}];else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("n7")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("bGE")]];end;elseif lllllIlIIIIIllllI<=#("qoEuUlNM2EhUzT9YdKK5HEBDJEdTE5YxanjGjNNxEYNe37MVPrWamSuXXaVph3i6QUUkKEOA7nBT0xKM2rdl")then if lllllIlIIIIIllllI<=#("Xks3vSi1xoLPQzimBklNvd9rL6BBjyZZ6X2KCroVGJL9Zdk8BzBh2JYUlarzrSS9zVT3GIVj6AhWD9")then if lllllIlIIIIIllllI<=#("IWD9U6S7y8izB9ZEX1LKeuqC3NrlCBbrlJUMYT7cQYu5yjtkg5t51AymGbghPHF661n2pnQe4J4")then if lllllIlIIIIIllllI<=#("9vdTsgeHhgAWlHgXN0yjty8H6C43ppbrFhnj7xYIC8Z0BCRTg3CdlU6LyHX1llq2fhqds7Zqb")then local lllIIIlIlllllIIlllIl=IIlIlllIlllIll[#{{532;106;579;385};"1 + 1 = 111";}];local IlIIIllIIIIIIlIIllIllllIl={};for IIlIlllIlllIll=1,#llIIlIlllI do local IIlIlllIlllIll=llIIlIlllI[IIlIlllIlllIll];for lllllllIIIl=0,#IIlIlllIlllIll do local lllllllIIIl=IIlIlllIlllIll[lllllllIIIl];local lllllIlIIIIIllllI=lllllllIIIl[1];local IIlIlllIlllIll=lllllllIIIl[2];if lllllIlIIIIIllllI==IIlIlIlIIlIlIIIIlllllIlI and IIlIlllIlllIll>=lllIIIlIlllllIIlllIl then IlIIIllIIIIIIlIIllIllllIl[IIlIlllIlllIll]=lllllIlIIIIIllllI[IIlIlllIlllIll];lllllllIIIl[1]=IlIIIllIIIIIIlIIllIllllIl;end;end;end;elseif lllllIlIIIIIllllI>#("SvJigFVlWxX7gVkMWBJ7vpR7UskNAjdlcvcLcpAsfaz4eibG2RlyReDCOLyXtiWNsM5USKKHap")then if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("dD")]]==IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("SQUQ")]])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("DBL")];end;else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("jk")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("3B7")]][IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("4Pjf")]]];end;elseif lllllIlIIIIIllllI<=#("v0X3MrPUS8PE72K6B1N96nVLCnqXshPyCnhL0SVGOzePNi82iNiPyp4hfmCza2BLtrbTV8gTghvI")then local lllllllIIIl=IIlIlllIlllIll[#("NA")]IIlIlIlIIlIlIIIIlllllIlI[lllllllIIIl](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllllIIIl+1,IIlIlllIlllIll[#("ZPE")]))elseif lllllIlIIIIIllllI>#("g7sozOP899ls9GOqxFV7DvvhohjHAJq4x89oijMnWMtsZBVCCDTMKLQUMlarEhJBTr6bHzhm2Hk1c")then local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Hy")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("qxo")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("EM")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("blo")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("O5")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("up5")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("gk")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("g29")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];do return end;else if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("gK")]]==IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("pMfd")]])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("ipE")];end;end;elseif lllllIlIIIIIllllI<=#{"1 + 1 = 111";{431;373;750;738};"1 + 1 = 111";{82;380;737;904};{50;3;603;576};{691;671;389;156};{509;451;692;325};"1 + 1 = 111";"1 + 1 = 111";{709;148;196;599};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{846;377;789;268};"1 + 1 = 111";"1 + 1 = 111";{905;524;15;406};"1 + 1 = 111";{708;118;465;46};{345;854;488;250};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{618;706;671;381};{291;400;560;688};{594;853;502;296};"1 + 1 = 111";"1 + 1 = 111";{27;994;57;166};{318;37;345;918};"1 + 1 = 111";{692;940;665;996};{986;665;512;25};"1 + 1 = 111";{672;863;819;420};"1 + 1 = 111";{413;919;229;796};{7;705;368;769};{920;600;866;767};"1 + 1 = 111";"1 + 1 = 111";{936;670;963;328};{2;128;109;590};"1 + 1 = 111";{350;364;517;979};"1 + 1 = 111";{853;78;965;655};"1 + 1 = 111";{720;982;166;802};"1 + 1 = 111";{249;366;106;429};"1 + 1 = 111";{747;972;354;772};"1 + 1 = 111";"1 + 1 = 111";{168;394;380;415};"1 + 1 = 111";"1 + 1 = 111";{578;539;876;644};{555;205;832;520};"1 + 1 = 111";"1 + 1 = 111";{237;256;466;144};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{674;722;160;468};{624;191;977;464};{793;736;15;912};"1 + 1 = 111";{253;336;870;563};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{571;396;37;848};"1 + 1 = 111";"1 + 1 = 111";}then if lllllIlIIIIIllllI<=#("Dmo3aHfi3s9bbtkPZqURehhZ4z49jaNkTzYRcCCa86ch8Ky5t5DS1Lhvfz9LNg82PYsMGEMyYUTif91")then local llIllIIIIlIlIIIlII;local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ZD")]]=IIlIlllIlllIll[#("8u7")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("Kx")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#{"1 + 1 = 111";{203;243;221;81};{279;67;98;580};}]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("qs")];llIllIIIIlIlIIIlII=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("JgZ")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=llIllIIIIlIlIIIlII;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("GImK")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("dF")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1])lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("R2")]]then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("2Jq")];end;elseif lllllIlIIIIIllllI>#("a8QoH4sirDLOD1y27kCjqWAZsf3h28qgIOLOBUuVGkuc2857v0k5IRdoI05CakqsmFfYpTBnZQOgBx6u")then local IIlIlllIlllIll=IIlIlllIlllIll[#("xv")]IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]()else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("o9")]][IIlIlllIlllIll[#("LyB")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ZSd7")]];end;elseif lllllIlIIIIIllllI<=#("5WbYvI0LvgKY3Vu4b0y2hSMA6f1c6Xk3LqezoF16om4N1A65tmAHJCdnjM1pRYPI5QnMR6PH9BO4X9IHj6")then local IlIIIllIIIIIIlIIllIllllIl=IIlIlllIlllIll[#("oX")]local lllllIlIIIIIllllI={IIlIlIlIIlIlIIIIlllllIlI[IlIIIllIIIIIIlIIllIllllIl](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,IlIIIllIIIIIIlIIllIllllIl+1,lIlIIIlI))};local lllllllIIIl=0;for IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl,IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";{469;418;54;488};{717;38;436;487};}]do lllllllIIIl=lllllllIIIl+1;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=lllllIlIIIIIllllI[lllllllIIIl];end elseif lllllIlIIIIIllllI>#("TyOuin0oNOLpBIvSkltoyI3IhYiBkdtgVf5krvey0Rb2ylmxBqyuZRulFgnuezdKtFFvNlBZh6yQGaj6LW9")then local lllllIlIIIIIllllI;local llIIlIlllI;local lIlIIIlI;lIlIIIlI=IIlIlllIlllIll[#("rTx")];llIIlIlllI=IIlIlIlIIlIlIIIIlllllIlI[lIlIIIlI]for IIlIlllIlllIll=lIlIIIlI+1,IIlIlllIlllIll[#("V13q")]do llIIlIlllI=llIIlIlllI..IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll];end;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("iK")]]=llIIlIlllI;lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{14;807;952;348};}]][IIlIlllIlllIll[#("GzL")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("3sPu")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("O6")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("tt")];lIlIIIlI=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("kIs")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=lIlIIIlI;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=lIlIIIlI[IIlIlllIlllIll[#("YabA")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("0c")]]=IIlIlllIlllIll[#("zj8")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{489;315;104;74};"1 + 1 = 111";}]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("gxm")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#{{280;821;745;725};"1 + 1 = 111";}]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("Bpt")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllllIIIl=IIlIlllIlllIll[#("MNd")];else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("t7")]]=#IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ZON")]];end;elseif lllllIlIIIIIllllI<=#("P8qdUTPkiUsBNCJ3R1Tp0Jn3tPPF6qTsAk4voBM3GpRxN7ceBqpUcUdgUxUfdko1aabDImOpp0TL21qxMLdQb8pQgX")then if lllllIlIIIIIllllI<=#("1RGZvb0vM5KHnM9FmaCo3gyEDgIZcVuvUMXITbxKcFOBceZecEdPPISVtcxpDat1KnWMZBWkN2mzC6CyqDWIRQR")then if lllllIlIIIIIllllI<=#("4boQOhgbkW0YsnpLS2bWvttxL88anWk4GKSXmfHGWlnPgNfdnl0YO50LS2fPjgXzM5sSFCzNvG9jfOp734Wc5")then lllllllIIIl=IIlIlllIlllIll[#("8VJ")];elseif lllllIlIIIIIllllI==#("qLUhft91vQzYcktxIVXnDh5QFdMhWptUDqPS8yxeNFktVrLeOHvapS2iPdMbS2efvOuWGMzkySK77M4mDHEp3s")then local llIllIIIIlIlIIIlII;local lllllIlIIIIIllllI;IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{774;67;635;450};}]]=IIlIIlIIIIllll[IIlIlllIlllIll[#{"1 + 1 = 111";{597;101;134;457};"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("F2")];llIllIIIIlIlIIIlII=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("UpG")]];IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI+1]=llIllIIIIlIlIIIlII;IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("cB8G")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("HK")]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("qu6")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("6B")]]=#IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("AkU")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("f2")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("HhW")]][IIlIlllIlllIll[#("BZje")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("3z")]]=#IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("fdz")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Dx")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("oLU")]]-IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{184;229;321;246};"1 + 1 = 111";{791;508;279;334};"1 + 1 = 111";}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("NH")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("4d8")]]+IIlIlllIlllIll[#("ASmz")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("6o")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("L4f")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Ux")]]~=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ySZt")]])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#{{286;227;66;324};{716;42;905;92};"1 + 1 = 111";}];end;else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("CY")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("T9q")]];end;elseif lllllIlIIIIIllllI<=#("VyHc4WvxUAe7h6ZJbhlMHh4ldjzIkyZlciKy8JFycv0I2OXqN7ChSR7NEu9VxXlxK248xCKCNXKlrxtzvi5m6SEv")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("8h")]]=IIlIlllIlllIll[#("QMv")];elseif lllllIlIIIIIllllI==#("63OKTbojE79UY3kxaE5gVvgbKzn28A2zIXBI623VvcYAtPIpV06nJoALXNauYxldeKlbCMBhLjVTHQR418hiEO0tx")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("Lj")]]=(IIlIlllIlllIll[#("4SS")]~=0);else IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{653;175;284;173};}]]=IIlIIlIIIIllll[IIlIlllIlllIll[#("8s8")]];end;elseif lllllIlIIIIIllllI<=#("Vt2J780VvTEGXizYNADRdh5fEZpcJAU2OM1hpclX2Vu7Buk8TQbB0QWNyWehTYm59L1kqrILnQYrW7OiPqs2ztc80nTD7")then if lllllIlIIIIIllllI<=#{{697;762;801;20};{874;407;869;439};"1 + 1 = 111";"1 + 1 = 111";{205;853;419;372};{351;558;91;65};"1 + 1 = 111";{287;614;280;338};{740;921;825;245};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{985;524;882;515};"1 + 1 = 111";{120;274;468;312};"1 + 1 = 111";"1 + 1 = 111";{900;512;946;98};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{52;377;970;600};"1 + 1 = 111";{67;407;868;242};"1 + 1 = 111";{709;815;45;370};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{629;916;998;649};{756;373;744;710};"1 + 1 = 111";{884;455;531;291};{905;893;334;520};{710;685;659;335};"1 + 1 = 111";"1 + 1 = 111";{366;71;967;4};{625;401;13;30};{611;30;571;660};"1 + 1 = 111";{693;635;145;707};{869;751;394;522};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{512;770;964;798};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{13;565;984;943};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{411;567;892;688};"1 + 1 = 111";{796;115;647;660};{197;251;206;229};{997;329;625;477};{994;380;489;379};"1 + 1 = 111";"1 + 1 = 111";{787;555;3;472};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{13;739;354;804};{547;598;292;137};"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";{858;418;334;799};{98;633;969;378};{885;669;955;164};{471;355;299;862};"1 + 1 = 111";{627;461;357;85};"1 + 1 = 111";"1 + 1 = 111";{71;622;851;793};"1 + 1 = 111";}then lllllllIIIl=IIlIlllIlllIll[#("PMa")];elseif lllllIlIIIIIllllI>#("FPGf847Rlfx7M329UWS5PtWMXS8OskCF8q8VZlZ8Q3xDsZvWxV2XsoZl34rq6tybN19u5gjJ6UoV6ts8vlrHsPlTCX25")then local IIlIlllIlllIll=IIlIlllIlllIll[#("b3")]IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll](IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll+1])else if not IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("p3")]]then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("F8z")];end;end;elseif lllllIlIIIIIllllI<=#("JbxFv0BZb1pLs1JadoKLt4Uc1S8Qp2iooQyS1qKE2iuub59XMTzIrtKOruON1VKjSbxND1iWOgTlJAa5TkdHDK65fTAHM7M")then if lllllIlIIIIIllllI>#("JlM9JxuVKM4lLyf2tS4RScQieCHTBMkRFMMyXaxvZs60QVtROIm3c4zGFE5hZLt8CmR8WResvI2AgZCshZf2AqPKng2tfp")then IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("U8")]]=(IIlIlllIlllIll[#("xs0")]~=0);else local lllllIlIIIIIllllI;llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("eS8")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";{771;896;741;588};}]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("EN")]]={};lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("GJ")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("NLH")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("1W")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{{764;584;443;229};"1 + 1 = 111";"1 + 1 = 111";}]][IIlIlllIlllIll[#("m22c")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("sF")]]=IIlIlllIlllIll[#("pgM")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("jh")]]=IIlIlllIlllIll[#("uhP")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("is")]]=IIlIlllIlllIll[#("68v")];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];lllllIlIIIIIllllI=IIlIlllIlllIll[#("Fk")]IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI]=IIlIlIlIIlIlIIIIlllllIlI[lllllIlIIIIIllllI](lllIIIlIlllllIIlllIl(IIlIlIlIIlIlIIIIlllllIlI,lllllIlIIIIIllllI+1,IIlIlllIlllIll[#("5xQ")]))lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ZM")]][IIlIlllIlllIll[#("Ke4")]]=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ZROC")]];lllllllIIIl=lllllllIIIl+1;IIlIlllIlllIll=IlIIIllIIIIIIlIIllIllllIl[lllllllIIIl];IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("SR")]]=llIllIIIIlIlIIIlII[IIlIlllIlllIll[#("V0J")]];end;elseif lllllIlIIIIIllllI>#("o87zEdu56E3IEc9zQbM99FCJlIgVPZUngbNBiA8pW3izGSkInRmrDpHTHzn67KqhTPBDzIqpdxngxdcDxJH7NCV1E44Umcrm")then if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("ua")]]~=IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#{"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";"1 + 1 = 111";}]])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("Uhn")];end;else if(IIlIlIlIIlIlIIIIlllllIlI[IIlIlllIlllIll[#("u3")]]~=IIlIlllIlllIll[#("6SZn")])then lllllllIIIl=lllllllIIIl+1;else lllllllIIIl=IIlIlllIlllIll[#("W3u")];end;end;lllllllIIIl=lllllllIIIl+1;end;end);end;return lIIlIlIllIIlI(true,{},llIIIIlllIlIllI())();end)(string.byte,table.insert,setmetatable);
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-ag" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "AntiGlitch activated";
        Text = "........"; 
        Duration = 5;
    })
while wait() do
local p = game.Players.LocalPlayer
local c = p.Character
local ms = c.LowerTorso:WaitForChild("BodyVelocity")
if ms then ms:Destroy()
end
end
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-hw" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Hide Wings ";
        Text = "Activated"; 
        Duration = 5;
    })
if (not game:IsLoaded()) then
    game.Loaded:Wait();
end;
local lplr=game:GetService('Players').LocalPlayer;
local char=game:GetService('Workspace'):waitForChild('Live'):waitForChild(lplr.Name);
function xd(char)
    lmfao=false;
    if (getgenv().enabler==false) then
        ran:Disconnect();
    else
        repeat wait();
            if (char:findFirstChild('RebirthWings')) then
                x=char.HumanoidRootPart.CFrame.X;
                y=char.HumanoidRootPart.CFrame.Y;
                z=char.HumanoidRootPart.CFrame.Z;
                char.HumanoidRootPart.CFrame=CFrame.new(x,y,z) + Vector3.new(0,-200,0);
                char.RebirthWings.Handle.AccessoryWeld:Destroy();
                char.HumanoidRootPart.CFrame=CFrame.new(x,y,z);
                x,y,z=nil;
                char.RebirthWings:Destroy();
                lmfao=true;
            end;
            if (char:findFirstChild('RealHalo')) then
                x=char.HumanoidRootPart.CFrame.X;
                y=char.HumanoidRootPart.CFrame.Y;
                z=char.HumanoidRootPart.CFrame.Z;
                char.HumanoidRootPart.CFrame=CFrame.new(x,y,z) + Vector3.new(0,-200,0);
                char.RealHalo.Handle.AccessoryWeld:Destroy();
                char.HumanoidRootPart.CFrame=CFrame.new(x,y,z);
                x,y,z=nil;
                char.RealHalo:Destroy();
                lmfao=true;
            end;
        until lmfao==true or getgenv().enabler==false;
    end;
end;
repeat wait()
    for i,v in pairs(char:getChildren()) do
        if v:IsA('Model') then
            lmao=true;
            xd(char);
            break;
        end;
    end;
until lmao==true;
lmao=false;
lplr.CharacterRemoving:connect(function() lmfao=true;end);
lplr.CharacterAdded:connect(function(v)
    char=v;
    xd(char);
    print('reconnected');
end);
end;
     end);
game.Players.LocalPlayer.Chatted:Connect(function(x)
	if x == "-hl" then
                 game.StarterGui:SetCore("SendNotification", {
        Title = "Hide level ";
        Text = "Activated"; 
        Duration = 5;
    })

      loadstring(game:HttpGet(('https://pastebin.com/raw/4zrzLDZV'),true))()
end;
     end);
