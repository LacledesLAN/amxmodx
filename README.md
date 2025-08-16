# AMX Mod X Binaries (Linux)

This repository mirrors the compiled asses of *AMX Mod X* and *Metamod*, as released under their respective licenses.

The game server admins of [Laclede's LAN](https://lacledeslan.com/), do this so that the contents can be used as git-
submodules, for our automated build of our [game servers](https://github.com/LacledesLAN/README.1ST/tree/master/GameServers).

## AMX Mod X (Currently Version 1.10.0-git5467 (dev build))

[AMX Mod X](https://github.com/alliedmodders/amxmodx) is a versatile Half-Life metamod plugin which is targeted toward
server administration. It has a wide array of scripting capabilities so people can write "plugins", or files which add
on to a mod's functionality. Plugins can take form in administrative services (adding new admin commands), statistics
generation (StatsX), fun additions (god-mode, etc), gameplay changes (WC3, CSDM), and much, much more!

### Links

* [Official Website](https://www.amxmodx.org/)
* [Official GIT Repository](https://github.com/alliedmodders/amxmodx)

## Metamod (Currently Version 1.21.1-am)

Metamod is a plugin/DLL manager that sits between the Half-Life Engine and an HL Game mod, allowing the dynamic
loading/unloading of mod-like DLL plugins to add functionality to the HL server or game mod.

The purpose of MetaMod is to function "one level up" from the normal Half-Life game mod DLL. Sitting between the mod
game DLL and the Half-Life engine/binary, it intercepts the function calls between the two, with the option of passing
them along untouched, as well as passing them on to as any number of additional mod-like DLLs.

Thus, you can actually have multiple "mod-like" DLLs in operation at one time. I say "mod-like" because these additional
DLLs (we'll call them "plugins") are not intended to provide a full "game"; that functionality is still provided by the
"game dll". However, these plugins can add to or modify the functionality provided by the game dll, or by the engine
itself - for instance, adding new server commands, or new client commands, or even disabling commands built into the
game dll. Although the plugin isn't intended to provide full HL-game functionality, since it's receiving the same
information given to the game DLL, it has the opportunity to do anything the game DLL can do (given enough coding
effort of course).

### Links

* [Official Website](http://metamod.org/)
