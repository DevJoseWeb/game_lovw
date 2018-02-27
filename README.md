Game feito em Lua, usando LOVE.

Desenvolvedor
web2ajax@gmail.com

love .

LÖVE is licensed under the liberal zlib/libpng license. This means that:

It costs nothing.
You can use it freely for commercial purposes with no limitations.


It’s pretty easy to get started with LÖVE, just check out these code snippets.

Drawing text
function love.draw()
love.graphics.print("Hello World!", 400, 300)
end
Drawing an image
function love.load()
whale = love.graphics.newImage("whale.png")
end
function love.draw()
love.graphics.draw(whale, 300, 200)
end
Playing a sound
function love.load()
sound = love.audio.newSource("music.ogg")
love.audio.play(sound)
end
