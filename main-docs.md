**加载图像**

```lua
function love.load()
    名称 = love.graphics.NewImage("图片路劲")
end
```



**绘制图像**

```lua
function love.draw()
	love.graphics.draw(名称, x坐标, y坐标)
end
```



**加载+播放声音**

```lua
function love.load()
	名称 = love.audio.newSource("音乐路劲", "stream") -加载
	love.audio.play(名称) -播放
end
```



**绘图文本**

```lua
function love.draw()
	love.graphics.print("文字", x坐标, y坐标)
end
```



**检测按下按键**

```lua
love.keyboard.isDown("按键")
```

