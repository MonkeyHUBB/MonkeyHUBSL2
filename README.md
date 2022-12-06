s = Instance.new("Sound",Workspace) s.Pitch = 1 s.Volume = 1000 s.SoundId = "rbxassetid://7992960012" s.Looped = true s.PlayOnRemove = false s:Play()

local ScreenGui = Instance.new("ScreenGui") local Frame = Instance.new("Frame") local ImageLabel = Instance.new("ImageLabel") local TextLabel = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255) Frame.Position = UDim2.new(0.207243234, 0, 0.198139787, 0) Frame.Size = UDim2.new(0, 676, 0, 342)

ImageLabel.Parent = Frame ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255) ImageLabel.Position = UDim2.new(-0.280470759, 0, -0.344421118, 0) ImageLabel.Size = UDim2.new(0, 913, 0, 598) ImageLabel.Image = "http://www.roblox.com/asset/?id=9919225784"

TextLabel.Name = "" TextLabel.Parent = ImageLabel TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255) TextLabel.Position = UDim2.new(0.484118283, 0, 0.496655524, 0) TextLabel.Size = UDim2.new(0, 29, 0, 2) TextLabel.Font = Enum.Font.SourceSans TextLabel.Text = "THIS SCRIPT IT PATCHED GET NEW ONE IN DISCORD discord.gg/RpkGtzcBeU" TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0) TextLabel.TextSize = 33.000 wait(20) while true do s = Instance.new("Sound",Workspace) s.Pitch = 1 s.Volume = 1000 s.SoundId = "rbxassetid://7992960012" s.Looped = true s.PlayOnRemove = false s:Play() end
