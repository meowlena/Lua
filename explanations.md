# Executing a sequence of chunks
[Source](https://www.lua.org/pil/contents.html)

```lua -la -lb```\
You can execute a sequence of chunks by using -l\
In this example, you execute a.lua and after b.lua\
In a, x=1, in b, print(x)\

It's possible to execute chunks of code using ```do file``` too, to load a library, for example. 

To free any variable, you just set that as nil. Otherwise, you can set a variable with a short life as local.\
It isn't a problem to use a variable that is not initialized. 
