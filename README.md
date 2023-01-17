```
--[[SYNAPSE X ONLY, MEANT TO BE USED WITH ROBLOX ALT ACCOUNT MANAGER]]--

--[[PUT THIS SCRIPT IN YOUR AUTOEXEC]]--

getgenv().settings = {
    MainAccount = "coolDude23_1", --the main acc, case sensitve
    Rendering = false, --rendering or no (recommended off)
    AltFps = 5, --fps you want the alt at
    DestroyMap = true, -- destroys the map on the alts client (also recommended)
    
}

loadstring(Game:HttpGet("https://raw.githubusercontent.com/hyperclocked333/DifficultyMachineR/main/script"))()
