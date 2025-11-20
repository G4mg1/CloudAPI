--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 32 | Scripts: 4 | Modules: 3 | Tags: 0
local G2L = {};

-- StarterGui.Main
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["Name"] = [[Main]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.Main.Executor
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["Visible"] = false;
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(37, 37, 37);
G2L["2"]["Size"] = UDim2.new(0, 628, 0, 366);
G2L["2"]["Position"] = UDim2.new(0.11614, 0, 0.15496, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Executor]];


-- StarterGui.Main.Executor.Top
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["3"]["Size"] = UDim2.new(0, 627, 0, 48);
G2L["3"]["Position"] = UDim2.new(-0, 0, 0, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Name"] = [[Top]];


-- StarterGui.Main.Executor.Top.Logo
G2L["4"] = Instance.new("ImageLabel", G2L["3"]);
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["4"]["Image"] = [[rbxassetid://107210361311982]];
G2L["4"]["Size"] = UDim2.new(-0.01, 42, 0, 48);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["BackgroundTransparency"] = 1;
G2L["4"]["Name"] = [[Logo]];
G2L["4"]["Position"] = UDim2.new(0.02073, 0, 0.14, 0);


-- StarterGui.Main.Executor.Top.Logo.UIAspectRatioConstraint
G2L["5"] = Instance.new("UIAspectRatioConstraint", G2L["4"]);



-- StarterGui.Main.Executor.Top.TextLabel
G2L["6"] = Instance.new("TextLabel", G2L["3"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["TextSize"] = 19;
G2L["6"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/JosefinSans.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6"]["TextColor3"] = Color3.fromRGB(178, 178, 178);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Size"] = UDim2.new(0, 200, 0, 35);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Text"] = [[Cloud Executor]];
G2L["6"]["Position"] = UDim2.new(0.09091, 0, 0.14, 0);


-- StarterGui.Main.Executor.Top.UICorner
G2L["7"] = Instance.new("UICorner", G2L["3"]);
G2L["7"]["CornerRadius"] = UDim.new(0, 9);


-- StarterGui.Main.Executor.Top.OK
G2L["8"] = Instance.new("ImageButton", G2L["3"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["Image"] = [[rbxassetid://104361429236506]];
G2L["8"]["Size"] = UDim2.new(0, 44, 0, 41);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Name"] = [[OK]];
G2L["8"]["Position"] = UDim2.new(0.92271, 0, 0.06583, 0);


-- StarterGui.Main.Executor.Top.OK.UIAspectRatioConstraint
G2L["9"] = Instance.new("UIAspectRatioConstraint", G2L["8"]);



-- StarterGui.Main.Executor.Top.OK.LocalScript
G2L["a"] = Instance.new("LocalScript", G2L["8"]);



-- StarterGui.Main.Executor.Buttons
G2L["b"] = Instance.new("Frame", G2L["2"]);
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["b"]["Size"] = UDim2.new(0, 130, 0, 293);
G2L["b"]["Position"] = UDim2.new(0.77406, 0, 0.16775, 0);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Name"] = [[Buttons]];


-- StarterGui.Main.Executor.Buttons.UIListLayout
G2L["c"] = Instance.new("UIListLayout", G2L["b"]);
G2L["c"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["c"]["Padding"] = UDim.new(0, 5);
G2L["c"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["c"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.Main.Executor.Buttons.Execute
G2L["d"] = Instance.new("TextButton", G2L["b"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextSize"] = 21;
G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["d"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Text"] = [[Execute]];
G2L["d"]["Name"] = [[Execute]];
G2L["d"]["Position"] = UDim2.new(0.0818, 0, 0.02878, 0);


-- StarterGui.Main.Executor.Buttons.Execute.Icon
G2L["e"] = Instance.new("ImageLabel", G2L["d"]);
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["e"]["Image"] = [[rbxassetid://79920557754899]];
G2L["e"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["Name"] = [[Icon]];
G2L["e"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- StarterGui.Main.Executor.Buttons.Execute.Icon.UIAspectRatioConstraint
G2L["f"] = Instance.new("UIAspectRatioConstraint", G2L["e"]);



-- StarterGui.Main.Executor.Buttons.Clear
G2L["10"] = Instance.new("TextButton", G2L["b"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextSize"] = 21;
G2L["10"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["10"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[Clear]];
G2L["10"]["Name"] = [[Clear]];
G2L["10"]["Position"] = UDim2.new(0.0818, 0, 0.34743, 0);


-- StarterGui.Main.Executor.Buttons.Clear.Icon
G2L["11"] = Instance.new("ImageLabel", G2L["10"]);
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["11"]["Image"] = [[rbxassetid://130478301898420]];
G2L["11"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["BackgroundTransparency"] = 1;
G2L["11"]["Name"] = [[Icon]];
G2L["11"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- StarterGui.Main.Executor.Buttons.Clear.Icon.UIAspectRatioConstraint
G2L["12"] = Instance.new("UIAspectRatioConstraint", G2L["11"]);



-- StarterGui.Main.Executor.Buttons.Inject
G2L["13"] = Instance.new("TextButton", G2L["b"]);
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["TextSize"] = 21;
G2L["13"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["13"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Text"] = [[Inject]];
G2L["13"]["Name"] = [[Inject]];
G2L["13"]["Position"] = UDim2.new(0.0818, 0, 0.66609, 0);


-- StarterGui.Main.Executor.Buttons.Inject.Icon
G2L["14"] = Instance.new("ImageLabel", G2L["13"]);
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["14"]["Image"] = [[rbxassetid://97455361098525]];
G2L["14"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["BackgroundTransparency"] = 1;
G2L["14"]["Name"] = [[Icon]];
G2L["14"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- StarterGui.Main.Executor.Buttons.Inject.Icon.UIAspectRatioConstraint
G2L["15"] = Instance.new("UIAspectRatioConstraint", G2L["14"]);



-- StarterGui.Main.Executor.CodeBar
G2L["16"] = Instance.new("TextBox", G2L["2"]);
G2L["16"]["Name"] = [[CodeBar]];
G2L["16"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextWrapped"] = true;
G2L["16"]["TextSize"] = 18;
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["16"]["MultiLine"] = true;
G2L["16"]["ClearTextOnFocus"] = false;
G2L["16"]["PlaceholderText"] = [[Print("hello kid")]];
G2L["16"]["Size"] = UDim2.new(0, 461, 0, 293);
G2L["16"]["Position"] = UDim2.new(0.0207, 0, 0.16667, 0);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[]];


-- StarterGui.Main.Executor.API
G2L["17"] = Instance.new("Folder", G2L["2"]);
G2L["17"]["Name"] = [[API]];


-- StarterGui.Main.Executor.API.Main_API
G2L["18"] = Instance.new("ModuleScript", G2L["17"]);
G2L["18"]["Name"] = [[Main_API]];


-- StarterGui.Main.Executor.API.Caller
G2L["19"] = Instance.new("LocalScript", G2L["17"]);
G2L["19"]["Name"] = [[Caller]];


-- StarterGui.Main.Executor.API.UIDrag
G2L["1a"] = Instance.new("ModuleScript", G2L["17"]);
G2L["1a"]["Name"] = [[UIDrag]];


-- StarterGui.Main.Executor.UIStroke
G2L["1b"] = Instance.new("UIStroke", G2L["2"]);
G2L["1b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1b"]["LineJoinMode"] = Enum.LineJoinMode.Miter;
G2L["1b"]["Thickness"] = 4.6;
G2L["1b"]["Color"] = Color3.fromRGB(62, 62, 62);


-- StarterGui.Main.PA
G2L["1c"] = Instance.new("ImageButton", G2L["1"]);
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Image"] = [[rbxassetid://107210361311982]];
G2L["1c"]["Size"] = UDim2.new(0, 47, 0, 74);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Name"] = [[PA]];
G2L["1c"]["Position"] = UDim2.new(0.87132, 0, 0.16332, 0);


-- StarterGui.Main.PA.UIAspectRatioConstraint
G2L["1d"] = Instance.new("UIAspectRatioConstraint", G2L["1c"]);



-- StarterGui.Main.PA.UIDrag
G2L["1e"] = Instance.new("ModuleScript", G2L["1c"]);
G2L["1e"]["Name"] = [[UIDrag]];


-- StarterGui.Main.PA.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1c"]);



-- StarterGui.Main.PA.LocalScript
G2L["20"] = Instance.new("LocalScript", G2L["1c"]);



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

G2L_MODULES[G2L["18"]] = {
Closure = function()
    local script = G2L["18"];local M = {}

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
G2L_MODULES[G2L["1a"]] = {
Closure = function()
    local script = G2L["1a"];local M = {}

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
G2L_MODULES[G2L["1e"]] = {
Closure = function()
    local script = G2L["1e"];local M = {}

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
-- StarterGui.Main.Executor.Top.OK.LocalScript
local function C_a()
local script = G2L["a"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent.Executor.Visible = false
		script.Parent.Parent.Parent.Parent.PA.Visible = true
	end)
end;
task.spawn(C_a);
-- StarterGui.Main.Executor.API.Caller
local function C_19()
local script = G2L["19"];
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
task.spawn(C_19);
-- StarterGui.Main.PA.LocalScript
local function C_1f()
local script = G2L["1f"];
	local uidrag = require(script.Parent.UIDrag)
	uidrag.UIDrag(script.Parent)
end;
task.spawn(C_1f);
-- StarterGui.Main.PA.LocalScript
local function C_20()
local script = G2L["20"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Executor.Visible = true
		script.Parent.Visible = false
	end)
end;
task.spawn(C_20);

return G2L["1"], require;
