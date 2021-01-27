# Homepage
 * Welcome to [vapq.cf](https://vapq.cf)!
 <p align="center">
  <b>Navigation</b><br>
  <a href="#">Home (Current Page)</a> |
  <a href="#lua">VapqLUA</a> |
  <a href="#">Discord</a>
  <br><br>
</p>

<h1 id="lua">VapqLUA</h1>

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
