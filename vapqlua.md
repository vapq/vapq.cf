# VapqLUA Docs
 * Created VapqLUA, powered by MaterialLUA
 * Added the "Hacker" theme. *thanks jekyll* 
 <p align="center">
  <b>Navigation</b><br>
  <a href="https://vapq.cf">Home</a> |
  <a href="">VapqLUA (Current Page)</a> |
  <a href="#discord">Discord</a>
  <br><br>
</p>
---

<h1 id="lua">Docs:</h1>

```lua
local Material = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kinlei/MaterialLua/master/Module.lua"))()

local UI = Material.Load({
     Title = "Getting Started",
     Style = 3,
     SizeX = 400,
     SizeY = 100,
     Theme = "Light"
})

local Page = UI.New({
    Title = "Main"
})

Page.Button({
    Text = "Click Me!",
    Callback = function()
       print("Clicked!") 
    end
})
```
