<script src="https://cdn.jsdelivr.net/npm/@widgetbot/crate@3" async defer>
  new Crate({
    server: '786633449149956116',
    channel: '799267896713805830',
    glyph: ['https://cdn.discordapp.com/avatars/293731150239891456/f7d78d0c7e6522ed296bfa315b3a1969.png', '100%']
  })
</script>
# Latest Updates <img src="https://i.imgur.com/A4xSAsW.gif">:
 * Created VapqLUA, powered by MaterialLUA
 * Added the "Hacker" theme. *thanks jekyll* 
 <p align="center">
  <b>Navigation</b><br>
  <a href="#">Home (Current Page)</a> |
  <a href="#lua">VapqLUA</a> |
  <a href="#discord">Discord</a>
  <br><br>
</p>
---

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
---

<div align="center">
<img src="https://img.shields.io/badge/Built%20With-LOVE%20By%20the%20vapq%20staff-orange?style=for-the-badge&logo=github" alt="Image Unable To Load.">
</div>

<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400&display=swap" rel="stylesheet">
<style>
.foot {
font-family: 'Open Sans', sans-serif;
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 2.5rem;
  background-color: #282828;
}
.sex {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  color: white;
  font-size: 12px;
}
</style>

<div class="foot">
<a class="sex">&copy; vapq.cf 2020 - 2021</a>
</div>
