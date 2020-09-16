RPG Maker 2000 Editor EX
========================

This project maintains a binary patch for RPG Maker 2000 Editor to add new features and capabilities. All additional features
are compatible with native `RPG_RT.exe` binary.

This patch is only compatible with the latest english version of `RPG2000.exe` from steam.

* Compatible `rpg2000.exe` md5sum: `e92269c755ea80753f43acfdf9520441`

Features
--------

* You can now copy and paste battle event code from battle events into common events and visa versa.
This feature allows you to call common events from battle, and run battle event code in those common events.

How to install
--------------

The patch was created using the `bsdiff` utility and can be applied with `bspatch`.

It is recommended to use WSL on windows or command line on linux / macos. Other `bspatch` compatible utilities may be found by searching the internet.

*You should backup your rpg2000.exe copy before applying the patch!*

```bash
cp rpg2000.exe rpg2000.orig.exe
bspatch rpg2000.orig.exe rpg2000.exe rpg2000ex.bspatch
```


