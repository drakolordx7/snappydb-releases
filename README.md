# SnappyDB releases

Installers for SnappyDB, a Windows launcher for mods and games from ModDB and Indie DB. This repository holds the releases only. SnappyDB checks it for updates and installs them itself.

## Install

1. Download `SnappyDB-Setup-<version>.exe` from the [latest release](../../releases/latest).
2. Run it. It installs for your user account only and needs no admin rights.

The installer isn't code-signed yet, so Windows may warn that it "protected your PC". Click **More info**, then **Run anyway**. On Windows 11 with Smart App Control turned on, unsigned apps are blocked outright; SnappyDB can't run there until signed builds are available.

## What it does

You browse ModDB and Indie DB inside the app and press Download. SnappyDB works out whether a file is a mod, a patch or a standalone game, and puts each mod in its own setup. A setup is built from the copy of the game you already have, and your real game folder is never changed. Supported games:

- Classic Doom (through UZDoom) and Quake (through Ironwail)
- Half-Life, Counter-Strike 1.6 and the other GoldSrc games
- Half-Life 2, its episodes, Counter-Strike: Source, Portal and Source SDK mods
- Battlefield 1942, Vietnam, 2 and 2142
- Command & Conquer: Generals and Zero Hour
- Star Wars: Empire at War - Forces of Corruption
- S.T.A.L.K.E.R.: Shadow of Chernobyl, Clear Sky, Call of Pripyat and Anomaly
- Mount & Blade: Warband and Bannerlord
- Unreal Tournament (1999) and Unreal Gold

Other games get a plain file overlay. Doom, Half-Life and Counter-Strike 1.6 are tested by playing them; the rest are checked against real ModDB downloads but haven't been played through SnappyDB yet.

Installers that can't be unpacked run inside [Sandboxie-Plus](https://sandboxie-plus.com/downloads/), which you install separately.

## Requirements

Windows 10 or 11, 64-bit.
