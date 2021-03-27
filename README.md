# lua-require
Lightweight duplicate of Lua's require function based on understanding and behavior. <br>

Only tested on [Luvit](https://luvit.io/) <br>

Running the library is as simple as requiring it, it will override the current environment's require with a duplicated one. <br>
```lua
require('require');
```
