local Library = loadstring(game:HttpGet(("https://raw.githubusercontent.com/new103/Extreme/main/README.md"),true))()
local Window = Library.CreateLib("เสกกู by พี่นิวส์", "Synapse")

local Tab = Window:NewTab("เสกของต่างๆ")
local Section = Tab:NewSection("เสกตึงๆ")
Section:NewButton("เสกเงิน", "เสกเงิน", function()
    print("Clicked")
end)
local Tab = Window:NewTab("ออโต้ฟาม")
local Section = Tab:NewSection("ฟามต่างๆ")
Section:NewButton("ฟามหิน", "ฟามหิน", function()
    print("Clicked")
end)
Section:NewButton("ฟามผลไม้ต่างๆ", "ฟามผลไม้ต่างๆ", function()
    print("Clicked")
end)
