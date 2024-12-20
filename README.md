local function CreateWindow()
	local as = Instance.new('ScreenGui')
	local ab = Instance.new('Frame')
	ab.Parent = as
	as.Parent = game.Players.LocalPlayer.PlayerGui
	ab.Size = UDim2.new(0, 200, 0, 200)
	ab.Position = UDim2.new(0.5, -100, 0.5, -100)
	ab.BackgroundColor3 = Color3.new(0, 0, 0)
	ab.BackgroundTransparency = 0.5
	ab.BorderSizePixel = 0
	return as, ab
end
