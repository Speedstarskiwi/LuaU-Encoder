# LuaU-Encoder

This encodes a inputted **luau** script into **bytecode** which `luau_load` can read and decode from the VM.

Crash Course on how the hell this works (kinda useless but still for skiddies and newbies):

Lua Script -> Luau Bytecode -> Luau Script -> Decode from VM -> Execute into Roblox.

`A = 41, B = 42, C = 43`

`7072696E74 = print`

Each symbol or letter gets converted into luau bytecode (encoded) then VM decodes it.

# LuaU-Notes

`00` -> empty when from luau to conversion.
