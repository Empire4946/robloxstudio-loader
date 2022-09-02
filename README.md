# robloxstudio-loader
Loader for your Scripts. (UI LIB)
> Made by Empire



# Script
```lua
-- // BASIC

_G.ScriptName = "Made By Empire" -- Your Script Name
_G.ImageID = 657238196 -- Default: 657238196

-- // PROPERTIES

_G.WaitingSpeed = 1
--[[ docu:
Default: 3
Waiting Speed = How long before loading
]]

_G.LoadingSpeed = 1
--[[ docu:
Default: 1
Loading Speed = How fast you want the loading to be
]]

_G.WorkingSpeed = 3
--[[ docu:
Default: 3
Working Speed = How long "Wait, I'm working"
]]


-- // Functions

function ExecuteScript()
    -- // PUT YOUR SCRIPT HERE!
    print("Script")
end


-- // UI LIB (Obfuscated cause I'm cool.)

loadstring(game:HttpGet("https://raw.githubusercontent.com/Empire4946/robloxstudio-loader/main/lib.lua",true))()
```
