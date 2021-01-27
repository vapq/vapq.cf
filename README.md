# Homepage:
 * Welcome to [vapq.cf](https://vapq.cf) [](https://camo.githubusercontent.com/388cc064196ad4a669966771bff6cf99e6810ba66cfcc497cae81cf410c3cc11/68747470733a2f2f692e696d6775722e636f6d2f413478534173572e676966)!
 <p align="center">
  <b>Navigation</b><br>
  <a href="#">Home (Current Page)</a> |
  <a href="#lua">VapqLUA</a> |
  <a href="#discord">Discord</a>
  <br><br>
</p>

<h1 id="lua">VapqLUA:</h1>

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

<h1 id="discord">Discord:</h1>
<div align="center">
<iframe src="https://discord.com/widget?id=786633449149956116&theme=dark" width="1000" height="300" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>
</div>
