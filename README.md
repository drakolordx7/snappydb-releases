# SnappyDB releases

Installers for SnappyDB, a Windows launcher for mods and games from ModDB and Indie DB. This repository holds the releases only. SnappyDB checks it for updates and installs them itself.

## Install

1. Download `SnappyDB-Setup-<version>.exe` from the [latest release](../../releases/latest).
2. Run it. It installs for your user account only and needs no admin rights.

The installer isn't code-signed yet, so Windows may warn that it "protected your PC". Click **More info**, then **Run anyway**. On Windows 11 with Smart App Control turned on, unsigned apps are blocked outright; SnappyDB can't run there until signed builds are available.

## What it does

You browse ModDB and Indie DB inside the app and press Download. SnappyDB works out whether a file is a mod, a patch or a standalone game, and puts each mod in its own setup. A setup is built from the copy of the game you already have, and your real game folder is never changed. Version 0.1 supports classic Doom (through UZDoom) and Half-Life mods, plus a plain file overlay for other games.

Installers that can't be unpacked run inside [Sandboxie-Plus](https://sandboxie-plus.com/downloads/), which you install separately.

## Requirements

Windows 10 or 11, 64-bit.
