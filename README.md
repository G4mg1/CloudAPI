--[=[

]=]

-- Instances: 31 | Scripts: 4 | Modules: 3 | Tags: 0
local G2L = {};

-- StarterGui.Main
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["Name"] = [[Main]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;

-- StarterGui.Main.Executor
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["Visible"] = false;
G2L["2"]["ZIndex"] = 999999999;
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(37, 37, 37);
G2L["2"]["Size"] = UDim2.new(0, 628, 0, 366);
G2L["2"]["Position"] = UDim2.new(0.11614, 0, 0.15496, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Executor]];


-- StarterGui.Main.Executor.Top
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["ZIndex"] = 999999999;
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["3"]["Size"] = UDim2.new(0, 627, 0, 48);
G2L["3"]["Position"] = UDim2.new(-0, 0, 0, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Name"] = [[Top]];


-- StarterGui.Main.Executor.Top.Logo
G2L["4"] = Instance.new("ImageLabel", G2L["3"]);
G2L["4"]["ZIndex"] = 999999999;
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
G2L["6"]["ZIndex"] = 999999999;
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


-- StarterGui.Main.Executor.Top.OK
G2L["7"] = Instance.new("ImageButton", G2L["3"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["ZIndex"] = 999999999;
G2L["7"]["Image"] = [[rbxassetid://104361429236506]];
G2L["7"]["Size"] = UDim2.new(0, 44, 0, 41);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Name"] = [[OK]];
G2L["7"]["Position"] = UDim2.new(0.92271, 0, 0.06583, 0);


-- StarterGui.Main.Executor.Top.OK.LocalScript
G2L["8"] = Instance.new("LocalScript", G2L["7"]);



-- StarterGui.Main.Executor.Top.OK.UIAspectRatioConstraint
G2L["9"] = Instance.new("UIAspectRatioConstraint", G2L["7"]);



-- StarterGui.Main.Executor.Buttons
G2L["a"] = Instance.new("Frame", G2L["2"]);
G2L["a"]["ZIndex"] = 999999999;
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(62, 62, 62);
G2L["a"]["Size"] = UDim2.new(0, 130, 0, 293);
G2L["a"]["Position"] = UDim2.new(0.77406, 0, 0.16775, 0);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Name"] = [[Buttons]];


-- StarterGui.Main.Executor.Buttons.UIListLayout
G2L["b"] = Instance.new("UIListLayout", G2L["a"]);
G2L["b"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["b"]["Padding"] = UDim.new(0, 5);
G2L["b"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["b"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.Main.Executor.Buttons.Execute
G2L["c"] = Instance.new("TextButton", G2L["a"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 21;
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c"]["ZIndex"] = 999999999;
G2L["c"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[Execute]];
G2L["c"]["Name"] = [[Execute]];
G2L["c"]["Position"] = UDim2.new(0.0818, 0, 0.02878, 0);


-- StarterGui.Main.Executor.Buttons.Execute.Icon
G2L["d"] = Instance.new("ImageLabel", G2L["c"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["d"]["Image"] = [[rbxassetid://79920557754899]];
G2L["d"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["BackgroundTransparency"] = 1;
G2L["d"]["Name"] = [[Icon]];
G2L["d"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- StarterGui.Main.Executor.Buttons.Execute.Icon.UIAspectRatioConstraint
G2L["e"] = Instance.new("UIAspectRatioConstraint", G2L["d"]);



-- StarterGui.Main.Executor.Buttons.Clear
G2L["f"] = Instance.new("TextButton", G2L["a"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 21;
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f"]["ZIndex"] = 999999999;
G2L["f"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[Clear]];
G2L["f"]["Name"] = [[Clear]];
G2L["f"]["Position"] = UDim2.new(0.0818, 0, 0.34743, 0);


-- StarterGui.Main.Executor.Buttons.Clear.Icon
G2L["10"] = Instance.new("ImageLabel", G2L["f"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["10"]["Image"] = [[rbxassetid://130478301898420]];
G2L["10"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["Name"] = [[Icon]];
G2L["10"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- StarterGui.Main.Executor.Buttons.Clear.Icon.UIAspectRatioConstraint
G2L["11"] = Instance.new("UIAspectRatioConstraint", G2L["10"]);



-- StarterGui.Main.Executor.Buttons.Inject
G2L["12"] = Instance.new("TextButton", G2L["a"]);
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextSize"] = 21;
G2L["12"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(82, 82, 82);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["12"]["ZIndex"] = 999999999;
G2L["12"]["Size"] = UDim2.new(0, 113, 0, 88);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[Inject]];
G2L["12"]["Name"] = [[Inject]];
G2L["12"]["Position"] = UDim2.new(0.0818, 0, 0.66609, 0);


-- StarterGui.Main.Executor.Buttons.Inject.Icon
G2L["13"] = Instance.new("ImageLabel", G2L["12"]);
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["13"]["Image"] = [[rbxassetid://97455361098525]];
G2L["13"]["Size"] = UDim2.new(-0.04, 29, -0.04, 35);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["BackgroundTransparency"] = 1;
G2L["13"]["Name"] = [[Icon]];
G2L["13"]["Position"] = UDim2.new(0.72341, 0, 0.64824, 0);


-- StarterGui.Main.Executor.Buttons.Inject.Icon.UIAspectRatioConstraint
G2L["14"] = Instance.new("UIAspectRatioConstraint", G2L["13"]);



-- StarterGui.Main.Executor.CodeBar
G2L["15"] = Instance.new("TextBox", G2L["2"]);
G2L["15"]["Name"] = [[CodeBar]];
G2L["15"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["15"]["ZIndex"] = 999999999;
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["TextWrapped"] = true;
G2L["15"]["TextSize"] = 18;
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["15"]["MultiLine"] = true;
G2L["15"]["ClearTextOnFocus"] = false;
G2L["15"]["PlaceholderText"] = [[Print("hello kid")]];
G2L["15"]["Size"] = UDim2.new(0, 461, 0, 293);
G2L["15"]["Position"] = UDim2.new(0.0207, 0, 0.16667, 0);
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["Text"] = [[]];


-- StarterGui.Main.Executor.API
G2L["16"] = Instance.new("Folder", G2L["2"]);
G2L["16"]["Name"] = [[API]];


-- StarterGui.Main.Executor.API.Main_API
G2L["17"] = Instance.new("ModuleScript", G2L["16"]);
G2L["17"]["Name"] = [[Main_API]];


-- StarterGui.Main.Executor.API.Caller
G2L["18"] = Instance.new("LocalScript", G2L["16"]);
G2L["18"]["Name"] = [[Caller]];


-- StarterGui.Main.Executor.API.UIDrag
G2L["19"] = Instance.new("ModuleScript", G2L["16"]);
G2L["19"]["Name"] = [[UIDrag]];


-- StarterGui.Main.Executor.UIStroke
G2L["1a"] = Instance.new("UIStroke", G2L["2"]);
G2L["1a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1a"]["LineJoinMode"] = Enum.LineJoinMode.Miter;
G2L["1a"]["Thickness"] = 4.6;
G2L["1a"]["Color"] = Color3.fromRGB(62, 62, 62);


-- StarterGui.Main.PA
G2L["1b"] = Instance.new("ImageButton", G2L["1"]);
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["ZIndex"] = 999999999;
G2L["1b"]["Image"] = [[rbxassetid://107210361311982]];
G2L["1b"]["Size"] = UDim2.new(0, 47, 0, 74);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Name"] = [[PA]];
G2L["1b"]["Position"] = UDim2.new(0.87132, 0, 0.16332, 0);


-- StarterGui.Main.PA.UIDrag
G2L["1c"] = Instance.new("ModuleScript", G2L["1b"]);
G2L["1c"]["Name"] = [[UIDrag]];


-- StarterGui.Main.PA.LocalScript
G2L["1d"] = Instance.new("LocalScript", G2L["1b"]);



-- StarterGui.Main.PA.LocalScript
G2L["1e"] = Instance.new("LocalScript", G2L["1b"]);



-- StarterGui.Main.PA.UIAspectRatioConstraint
G2L["1f"] = Instance.new("UIAspectRatioConstraint", G2L["1b"]);



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

G2L_MODULES[G2L["17"]] = {
Closure = function()
    local script = G2L["17"];local M = {}

local function notify(Title, Message, Duration)
	game.StarterGui:SetCore("SendNotification", {
		Title = Title or "Setting",
		Text = Message,
		Icon = "rbxassetid://107210361311982",
		Duration = Duration or 5
	})
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
	local succes, err = pcall(function()
		loadstring(code)()
	end)
	
	if succes then
		return true
		
	else
		return false, notify("Setting", "Error on Executing "..tostring(err), 5)
	end
end


function M.Inject_run()
	Inject()
end

return M


end;
};
G2L_MODULES[G2L["19"]] = {
Closure = function()
    local script = G2L["19"];local M = {}

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
G2L_MODULES[G2L["1c"]] = {
Closure = function()
    local script = G2L["1c"];local M = {}

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
local function C_8()
local script = G2L["8"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent.Executor.Visible = false
		script.Parent.Parent.Parent.Parent.PA.Visible = true
	end)
end;
task.spawn(C_8);
-- StarterGui.Main.Executor.API.Caller
local function C_18()
local script = G2L["18"];
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
task.spawn(C_18);
-- StarterGui.Main.PA.LocalScript
local function C_1d()
local script = G2L["1d"];
	local uidrag = require(script.Parent.UIDrag)
	uidrag.UIDrag(script.Parent)
end;
task.spawn(C_1d);
-- StarterGui.Main.PA.LocalScript
local function C_1e()
local script = G2L["1e"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Executor.Visible = true
		script.Parent.Visible = false
	end)
end;
task.spawn(C_1e);

return G2L["1"], require;
