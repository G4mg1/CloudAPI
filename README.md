--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 35 | Scripts: 5 | Modules: 4 | Tags: 0
local G2L = {};

-- ReplicatedFirst.CloudAPI
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["Name"] = [[CloudAPI]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- ReplicatedFirst.CloudAPI.Main
G2L["2"] = Instance.new("LocalScript", G2L["1"]);
G2L["2"]["Name"] = [[Main]];


-- ReplicatedFirst.CloudAPI.Main.MainModule
G2L["3"] = Instance.new("ModuleScript", G2L["2"]);
G2L["3"]["Name"] = [[MainModule]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main
G2L["4"] = Instance.new("ScreenGui", G2L["3"]);
G2L["4"]["Name"] = [[Main]];
G2L["4"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor
G2L["5"] = Instance.new("Frame", G2L["4"]);
G2L["5"]["Visible"] = false;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(37, 37, 37);
G2L["5"]["Size"] = UDim2.new(0, 628, 0, 366);
G2L["5"]["Position"] = UDim2.new(0.11614, 0, 0.15496, 0);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Name"] = [[Executor]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top
G2L["6"] = Instance.new("Frame", G2L["5"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["6"]["Size"] = UDim2.new(0, 627, 0, 48);
G2L["6"]["Position"] = UDim2.new(-0, 0, 0, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Name"] = [[Top]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top.Logo
G2L["7"] = Instance.new("ImageLabel", G2L["6"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["7"]["Image"] = [[rbxassetid://107210361311982]];
G2L["7"]["Size"] = UDim2.new(-0.01, 42, 0, 48);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Name"] = [[Logo]];
G2L["7"]["Position"] = UDim2.new(0.02073, 0, 0.14, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top.Logo.UIAspectRatioConstraint
G2L["8"] = Instance.new("UIAspectRatioConstraint", G2L["7"]);



-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top.TextLabel
G2L["9"] = Instance.new("TextLabel", G2L["6"]);
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["TextSize"] = 19;
G2L["9"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/JosefinSans.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9"]["TextColor3"] = Color3.fromRGB(178, 178, 178);
G2L["9"]["BackgroundTransparency"] = 1;
G2L["9"]["Size"] = UDim2.new(0, 200, 0, 35);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Text"] = [[Cloud Executor]];
G2L["9"]["Position"] = UDim2.new(0.09091, 0, 0.14, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top.UICorner
G2L["a"] = Instance.new("UICorner", G2L["6"]);
G2L["a"]["CornerRadius"] = UDim.new(0, 9);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top.OK
G2L["b"] = Instance.new("ImageButton", G2L["6"]);
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["Image"] = [[rbxassetid://104361429236506]];
G2L["b"]["Size"] = UDim2.new(0, 44, 0, 41);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Name"] = [[OK]];
G2L["b"]["Position"] = UDim2.new(0.92271, 0, 0.06583, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top.OK.UIAspectRatioConstraint
G2L["c"] = Instance.new("UIAspectRatioConstraint", G2L["b"]);



-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top.OK.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["b"]);



-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons
G2L["e"] = Instance.new("Frame", G2L["5"]);
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["e"]["Size"] = UDim2.new(0, 130, 0, 293);
G2L["e"]["Position"] = UDim2.new(0.77406, 0, 0.16775, 0);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["Name"] = [[Buttons]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.UIListLayout
G2L["f"] = Instance.new("UIListLayout", G2L["e"]);
G2L["f"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["f"]["Padding"] = UDim.new(0, 5);
G2L["f"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["f"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Execute
G2L["10"] = Instance.new("TextButton", G2L["e"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextSize"] = 21;
G2L["10"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["10"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[Execute]];
G2L["10"]["Name"] = [[Execute]];
G2L["10"]["Position"] = UDim2.new(0.0818, 0, 0.02878, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Execute.Icon
G2L["11"] = Instance.new("ImageLabel", G2L["10"]);
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["11"]["Image"] = [[rbxassetid://79920557754899]];
G2L["11"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["BackgroundTransparency"] = 1;
G2L["11"]["Name"] = [[Icon]];
G2L["11"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Execute.Icon.UIAspectRatioConstraint
G2L["12"] = Instance.new("UIAspectRatioConstraint", G2L["11"]);



-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Clear
G2L["13"] = Instance.new("TextButton", G2L["e"]);
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["TextSize"] = 21;
G2L["13"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["13"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Text"] = [[Clear]];
G2L["13"]["Name"] = [[Clear]];
G2L["13"]["Position"] = UDim2.new(0.0818, 0, 0.34743, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Clear.Icon
G2L["14"] = Instance.new("ImageLabel", G2L["13"]);
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["14"]["Image"] = [[rbxassetid://130478301898420]];
G2L["14"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["BackgroundTransparency"] = 1;
G2L["14"]["Name"] = [[Icon]];
G2L["14"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Clear.Icon.UIAspectRatioConstraint
G2L["15"] = Instance.new("UIAspectRatioConstraint", G2L["14"]);



-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Inject
G2L["16"] = Instance.new("TextButton", G2L["e"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextSize"] = 21;
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["16"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[Inject]];
G2L["16"]["Name"] = [[Inject]];
G2L["16"]["Position"] = UDim2.new(0.0818, 0, 0.66609, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Inject.Icon
G2L["17"] = Instance.new("ImageLabel", G2L["16"]);
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["17"]["Image"] = [[rbxassetid://97455361098525]];
G2L["17"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["BackgroundTransparency"] = 1;
G2L["17"]["Name"] = [[Icon]];
G2L["17"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Buttons.Inject.Icon.UIAspectRatioConstraint
G2L["18"] = Instance.new("UIAspectRatioConstraint", G2L["17"]);



-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.CodeBar
G2L["19"] = Instance.new("TextBox", G2L["5"]);
G2L["19"]["CursorPosition"] = -1;
G2L["19"]["Name"] = [[CodeBar]];
G2L["19"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextWrapped"] = true;
G2L["19"]["TextSize"] = 18;
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["19"]["MultiLine"] = true;
G2L["19"]["ClearTextOnFocus"] = false;
G2L["19"]["PlaceholderText"] = [[Print("hello kid")]];
G2L["19"]["Size"] = UDim2.new(0, 461, 0, 293);
G2L["19"]["Position"] = UDim2.new(0.0207, 0, 0.16667, 0);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.API
G2L["1a"] = Instance.new("Folder", G2L["5"]);
G2L["1a"]["Name"] = [[API]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.API.Main_API
G2L["1b"] = Instance.new("ModuleScript", G2L["1a"]);
G2L["1b"]["Name"] = [[Main_API]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.API.Caller
G2L["1c"] = Instance.new("LocalScript", G2L["1a"]);
G2L["1c"]["Name"] = [[Caller]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.API.UIDrag
G2L["1d"] = Instance.new("ModuleScript", G2L["1a"]);
G2L["1d"]["Name"] = [[UIDrag]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.UIStroke
G2L["1e"] = Instance.new("UIStroke", G2L["5"]);
G2L["1e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1e"]["LineJoinMode"] = Enum.LineJoinMode.Miter;
G2L["1e"]["Thickness"] = 4.6;
G2L["1e"]["Color"] = Color3.fromRGB(62, 62, 62);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.PA
G2L["1f"] = Instance.new("ImageButton", G2L["4"]);
G2L["1f"]["BorderSizePixel"] = 0;
G2L["1f"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1f"]["Image"] = [[rbxassetid://107210361311982]];
G2L["1f"]["Size"] = UDim2.new(0, 47, 0, 74);
G2L["1f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1f"]["Name"] = [[PA]];
G2L["1f"]["Position"] = UDim2.new(0.87132, 0, 0.16332, 0);


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.PA.UIAspectRatioConstraint
G2L["20"] = Instance.new("UIAspectRatioConstraint", G2L["1f"]);



-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.PA.UIDrag
G2L["21"] = Instance.new("ModuleScript", G2L["1f"]);
G2L["21"]["Name"] = [[UIDrag]];


-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.PA.LocalScript
G2L["22"] = Instance.new("LocalScript", G2L["1f"]);



-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.PA.LocalScript
G2L["23"] = Instance.new("LocalScript", G2L["1f"]);



-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["3"]] = {
Closure = function()
    local script = G2L["3"];local M = {}

function M.ReturnGui(Gui)
	Gui.Parent = game.Players.LocalPlayer.PlayerGui
end

return M
end;
};
G2L_MODULES[G2L["1b"]] = {
Closure = function()
    local script = G2L["1b"];local M = {}

local function notify(Title, Message, Duration)
	game.StarterGui:SetCore("SendNotification", {
		Title = Title or "Setting",
		Text = Message,
		Icon = "rbxassetid://107210361311982",
		Duration = Duration or 5
	})
end

local function Execute(Code)
	local success, err = pcall(function()
		loadstring(Code.Text)()
	end)
	if success then
		return true
	else
		notify("Setting", "Error on Executing "..tostring(err), 5)
		return false
	end
end

local function Inject()
	local remote = game.ReplicatedStorage:FindFirstChild("__CloudAPI__")
	if not remote then
		remote = Instance.new("RemoteFunction")
		remote.Name = "__CloudAPI__"
		remote.Parent = game.ReplicatedStorage
		notify("Setting", "Injected", 5)
	else
		notify("Setting", "Already Injected", 5)
	end
end

function M.Code_run(code)
	return Execute(code)
end

function M.Clear_run(code)
	return Clear(code)
end

function M.Inject_run()
	Inject()
end

return M


end;
};
G2L_MODULES[G2L["1d"]] = {
Closure = function()
    local script = G2L["1d"];local M = {}

function M.UIDrag(frame)
    local dragging = false
    local dragInput, mousePos, framePos

    frame.InputBegan:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
            dragging = true
            mousePos = input.Position
            framePos = frame.Position

            input.Changed:Connect(function()
                if input.UserInputState == Enum.UserInputState.End then
                    dragging = false
                end
            end)
        end
    end)

    frame.InputChanged:Connect(function(input)
        if dragging and (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
            dragInput = input
        end
    end)

    game:GetService("UserInputService").InputChanged:Connect(function(input)
        if dragging and input == dragInput then
            local delta = input.Position - mousePos
            frame.Position = UDim2.new(
                framePos.X.Scale,
                framePos.X.Offset + delta.X,
                framePos.Y.Scale,
                framePos.Y.Offset + delta.Y
            )
        end
    end)
end

return M


end;
};
G2L_MODULES[G2L["21"]] = {
Closure = function()
    local script = G2L["21"];local M = {}

function M.UIDrag(frame)
    local dragging = false
    local dragInput, mousePos, framePos

    frame.InputBegan:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
            dragging = true
            mousePos = input.Position
            framePos = frame.Position

            input.Changed:Connect(function()
                if input.UserInputState == Enum.UserInputState.End then
                    dragging = false
                end
            end)
        end
    end)

    frame.InputChanged:Connect(function(input)
        if dragging and (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
            dragInput = input
        end
    end)

    game:GetService("UserInputService").InputChanged:Connect(function(input)
        if dragging and input == dragInput then
            local delta = input.Position - mousePos
            frame.Position = UDim2.new(
                framePos.X.Scale,
                framePos.X.Offset + delta.X,
                framePos.Y.Scale,
                framePos.Y.Offset + delta.Y
            )
        end
    end)
end

return M


end;
};
-- ReplicatedFirst.CloudAPI.Main
local function C_2()
local script = G2L["2"];
	local ok = require(script.MainModule)
	ok.ReturnGui(script.MainModule.Main)
end;
task.spawn(C_2);
-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.Top.OK.LocalScript
local function C_d()
local script = G2L["d"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent.Executor.Visible = false
		script.Parent.Parent.Parent.Parent.PA.Visible = true
	end)
end;
task.spawn(C_d);
-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.Executor.API.Caller
local function C_1c()
local script = G2L["1c"];
	local btns = script.Parent.Parent.Buttons
	local API_Async = require(script.Parent.Main_API)
	local UIDrag = require(script.Parent.UIDrag)
	
	local Button = {
		Execute = btns.Execute;
		Clear = btns.Clear;
		Inject = btns.Inject;
	}
	
	local code = script.Parent.Parent.CodeBar
	
	Button.Execute.MouseButton1Click:Connect(function()
		API_Async.Code_run(code.Text)
	end)
	
	Button.Clear.MouseButton1Click:Connect(function()
		code.Text = ""
	end)
	
	Button.Inject.MouseButton1Click:Connect(function()
		API_Async.Inject_run()
	end)
	
	local frame = script.Parent.Parent.Parent.Executor
	
	UIDrag.UIDrag(frame)
end;
task.spawn(C_1c);
-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.PA.LocalScript
local function C_22()
local script = G2L["22"];
	local uidrag = require(script.Parent.UIDrag)
	uidrag.UIDrag(script.Parent)
end;
task.spawn(C_22);
-- ReplicatedFirst.CloudAPI.Main.MainModule.Main.PA.LocalScript
local function C_23()
local script = G2L["23"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Executor.Visible = true
		script.Parent.Visible = false
	end)
end;
task.spawn(C_23);

return G2L["1"], require;
