# Script-joao-kavoUi local = loadstring(jogo:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
Janela local = kavoUi.CreateLib("DeadlyHub","DarkTheme")



local MainTab = Janela:NovaTab("Principal")
Seção Principal local =
Guia Principal:NewSection("SeçãoPrincipal")

MainSection:NewButton("NAME ESP", "Q para ligar e desligar", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/Exunys/ESP-Script/main/ESP.lua"))()
fim)

MainSection:NewButton("ESP", "", função()
  Preenchimento local Color = Color3.fromRGB(175,25,255)
Modo de profundidade local = "AlwaysOnTop"
Transparência de preenchimento local = 0,5
Cor de contorno local = Cor3.fromRGB(255,255,255)
Transparência de contorno local = 0

local CoreGui = jogo:FindService("CoreGui")
Jogadores locais = jogo:FindService("Jogadores")
lp local = Jogadores.JogadorLocal
conexões locais = {}

Armazenamento local = Instance.new("Pasta")
Armazenamento.Parent = CoreGui
Armazenamento.Nome = "Destaque_Armazenamento"

função local Destaque(plr)
    Destaque local = Instance.new("Destaque")
    Destaque.Nome = plr.Nome
    Destaque.FillColor = CorDePreenchimento
    Destaque.DepthMode = ModoProfundidade
    Destaque.FillTransparency = PreencherTransparência
    Destaque.CorDoEsboço = CorDoEsboço
    Destaque.Transparência do contorno = 0
    Destaque.Parent = Armazenamento
    
    plrchar local = plr.Caractere
    se plrchar então
        Destaque.Adornee = plrchar
    fim

    conexões[plr] = plr.CharacterAdded:Connect(função(char)
        Destaque.Adornee = char
    fim)
fim

Jogadores.PlayerAdded:Conectar(Destaque)
para i,v em seguida, Players:GetPlayers() faça
    Destaque(v)
fim

Jogadores.PlayerRemoving:Connect(função(plr)
    local plrname = plr.Nome
    se Armazenamento[plrname] então
        Armazenamento[plrname]:Destruir()
    fim
    se conexões[plr] então
        conexões[plr]:Desconectar()
    fim
fim)
fim)

MainSection:NewButton("Arremessar", nil, function()
    loadstring(jogo:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_5wpM7bBcOPspmX7lQ3m75SrYNWqxZ858ai3tJdEAId6jSI05IOUB224FQ0VSAswH.lua.txt'),true))()
fim)

MainSection:NewButton("Voar", nil, function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98 \117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\ 89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\5 5\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\1 00\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\11 4\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53 \50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
fim)

MainSection:NewButton("Xray", "Pressione E para ativar/desativar", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/HeyGyt/xray/main/main"))()
fim)

MainSection:NewButton("FullBright", nulo, função()
    jogo:GetService("Iluminação").Brilho = 2
            jogo:GetService("Iluminação").ClockTime = 14
            jogo:GetService("Iluminação").FogEnd = 100000
            jogo:GetService("Iluminação").GlobalShadows = falso
            jogo:GetService("Iluminação").OutdoorAmbient = Color3.fromRGB(128, 128, 128)
fim)

MainSection:NewButton("Salto infinito", nil, function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/HeyGyt/infjump/main/main"))()
fim)

MainSection:NewButton("Airswim", nil, function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/HeyGyt/airswim/main/main"))()
fim)






Jogos locais = Janela:NovaGuia("JogosðŸŽ®")
local GamesSection = Jogos:NovaSeção("Jogos")


GamesSection:NewButton("ðŸ BrookhavenðŸ ", "", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
fim)

GamesSection:NewButton("ðŸ”ªMM2ðŸ”ª", "", função()
    loadstring(jogo:HttpGet(('https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/MM2%20Admin%20Panel'),true))()
fim)

GamesSection:NewButton("BedwarsðŸ›Œ", "", função()
    	loadstring(jogo:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()	
fim)

GamesSection:NewButton("Vida na Prisão", "", function()
    loadstring(jogo:HttpGet('https://pastebin.com/raw/iZ64yzjE'))()
fim)

GamesSection:NewButton("ðŸ'ªMuscle LegendsðŸ'ª", "", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/harisiskandar178/Roblox-Script/main/Muscle%20Legend"))()
fim)

GamesSection:NewButton("Quebrar", "", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/Nikita365/Break-In-Story-/main/Break%20In%20Story%20Hub"))()
fim)

GamesSection:NewButton("Nico's Nextbots", "", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/NicoNextBots", true))()
fim)

GamesSection:NewButton("PortasðŸ' ", "", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Doors"))()
fim)

GamesSection:NewButton("Evadir", "", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Evade"))()
fim)

GamesSection:NewButton("Amigos do arco-íris", "", function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/JNHHGaming/Rainbow-Friends/main/Rainbow%20Friends"))()
fim)

GamesSection:NewButton("Batalhas de tapa", "", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/TheScriptMaster1/ScriptMaster-Hub/main/scriptmasterhub.lua')))()
fim)

GamesSection:NewButton("Cozinhe Hambúrgueres", "", function()
    loadstring(jogo:HttpGet(('https://pastebin.com/raw/YUqvvEAB')))()
fim)





Administradores locais = Janela:NovaGuia("Administradores")
local AdminsSection = Admins:NovaSeção("Administradores")

AdminsSection:NewButton("Rendimento infinito", nil, function()
    loadstring(jogo:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
fim)

AdminsSection:NewButton("CMD-X", nulo, função()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source", verdadeiro))()
fim)

AdminsSection:NewButton("Administrador de Destinos", nil, function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
fim)




local Misc = Janela:NovaGuia("Misc")
local MiscSection = Misc:NewSection("Misc")


MiscSection:NewButton("Teclado", nil, função()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
fim)

MiscSection:NewButton("GUI de animações FE", nil, function()
    loadstring(jogo:HttpGet("https://raw.githubusercontent.com/GamingScripter/Animation-Hub/main/Animation%20Gui", true))()
fim)

MiscSection:NewButton("Reingressar", nil, function()
    local ts = jogo:GetService("TeleportService")

local p = jogo:GetService("Jogadores").LocalPlayer

 

ts:Teleport(jogo.PlaceId, p)
fim)




Créditos locais = Window:NewTab("Créditos")
local CreditsSection = Créditos:NovaSeção("Créditos")


CreditsSection:NewLabel("Feito por Deadly_Frenzy_")
CreditsSection:NewLabel("Inscreva-se em Deadly_Frenzy_ no YouTube")
CreditsSection:NewLabel("Siga deadly_frenzy_ no TikTok")
CreditsSection:NewLabel("Conta do Deadly_Frenzy_ Roblox: F0X42512")
CréditosSeção:NovoRótulo("")
CreditsSection:NewLabel("imgood_atnameing_things me ajudou")
CreditsSection:NewLabel("Siga imgood_atnameing_things no TikTok")
CreditsSection:NewLabel("imgood_atnameing_things Conta Roblox: duckarmy609")
