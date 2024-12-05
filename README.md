
local numberz = nil

while wait(2.5) do
	if true then
		if not game:GetService("Players").LocalPlayer.PlayerGui.HUD.Inventory.ScrollingFrameList:FindFirstChild("Frog") then
			numberz = "x0"
		else
			numberz = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Inventory.ScrollingFrameList["Frog"].ImageButton.Stack.Text
		end
	end
end

spawn(function()
	while task.wait() do
		if true then
			if not game.Players.LocalPlayer:WaitForChild("PlayerGui"):FindFirstChild("work 1") then
				task.wait(.5)
				local work1 = Instance.new("ScreenGui")
				local Frame = Instance.new("Frame")
				local ImageLabel = Instance.new("ImageLabel")
				local Name_coin = Instance.new("TextLabel")


				work1.Name = "work 1"
				work1.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
				work1.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

				Frame.Parent = work1
				Frame.BackgroundColor3 = Color3.new(0, 0, 0)
				Frame.BackgroundTransparency = 0.30000001192092896
				Frame.BorderColor3 = Color3.new(0, 0, 0)
				Frame.BorderSizePixel = 0
				Frame.Size = UDim2.new(999, 999, 999, 999)

				ImageLabel.Parent = Frame
				ImageLabel.BackgroundColor3 = Color3.new(1, 1, 1)
				ImageLabel.BackgroundTransparency = 1
				ImageLabel.BorderColor3 = Color3.new(0, 0, 0)
				ImageLabel.BorderSizePixel = 0
				ImageLabel.Position = UDim2.new(9.77149321e-05, 0, 0.000169326391, 0)
				ImageLabel.Size = UDim2.new(0, 260, 0, 244)
				ImageLabel.Image = "rbxassetid://134711731758237"

				if true then
					repeat
						wait(3)
						Name_coin.Name = "Name_coin"
						Name_coin.Parent = ImageLabel
						Name_coin.BackgroundColor3 = Color3.new(1, 1, 1)
						Name_coin.BackgroundTransparency = 1
						Name_coin.BorderColor3 = Color3.new(0, 0, 0)
						Name_coin.BorderSizePixel = 0
						Name_coin.Position = UDim2.new(1.08059192, 0, 0.142421901, 0)
						Name_coin.Size = UDim2.new(0, 263, 0, 153)
						Name_coin.Font = Enum.Font.Bodoni
						Name_coin.Text = numberz
						Name_coin.TextColor3 = Color3.new(1, 1, 1)
						Name_coin.TextSize = 100
					until false
				end	
			end
		end
	end
end)
