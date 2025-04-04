local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "StarHubBR", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Um Simples Oi!",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddParagraph("Oi","Depois de muito tempo consegui fazer um belo painel para você ter os melhores scripts salvos! demorou? Muito pois não tenho muito tempo e você que pagou e muito querido mesmo!")

local Section = Tab:AddSection({
	Name = "Suporte"
})
Tab:AddButton({
	Name = "StarHub",
	Callback = function()
      		setclipboard("https://discord.gg/BSuP8CFgYd")
  	end    
})

local Tab = Window:MakeTab({
	Name = "Brookhaven",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Com Key"
})
Tab:AddButton({
	Name = "Chaos Hub",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Aviso!",
	Content = "Compre para ter acesso!",
	Image = "rbxassetid://4483345998",
	Time = 5
})

  	end    
})

local Section = Tab:AddSection({
	Name = "Sem Key"
})
Tab:AddButton({
	Name = "Rael Hub!",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Aviso!",
	Content = "Compre para ter acesso!",
	Image = "rbxassetid://4483345998",
	Time = 5
})
  	end    
})

local Tab = Window:MakeTab({
	Name = "MM2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "MM2"
})
Tab:AddButton({
	Name = "YARHM",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Aviso!",
	Content = "Compre para ter acesso!",
	Image = "rbxassetid://4483345998",
	Time = 5
})
  	end    
})
Tab:AddButton({
	Name = "Não sei o Nome",
	Callback = function()
      		OrionLib:MakeNotification({
	Name = "Aviso!",
	Content = "Compre para ter acesso!",
	Image = "rbxassetid://4483345998",
	Time = 5
})
  	end    
})


