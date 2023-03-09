**This documentation is a work in progress.**

# Overview
This repository includes documentation on how to create mods for the game [Dwerve](https://store.steampowered.com/app/1132760/Dwerve/). It also contains source code for official Dwerve [mods](Mods) as well as [templates](Templates) that you can copy and edit in order to make your own mods quickly and easily. The templates also include base sprites that you can reskin.

# Capabilities
The mod system lets you customize the stats and sprites for Dwerve, towers, and enemies. You can also mod the general game configuration which determines when towers, power stones, and artifacts get unlocked. For example, you could reskin a turret, have it deal massive knockback, and unlock it in the first level.

# File Format
Dwerve uses [TOML](https://TOML.io/en) to describe mods. TOML is a config file format that is easy to read and write. The templates contains TOML files for all content that can be modded including all towers and enemies. To create a new mod, just copy and paste an example mod to a new folder and edit any TOML and image files.

# Example Mod
This is the TOML file for the [Super Fast Walk](Mods/SuperFastWalk) mod which simply doubles Dwerve's movement speed:

```TOML
ModTarget = "Dwerve"

[Stats]
Speed = 8.6 # original speed is 4.3
```

Template toml files such as [Dwerve.Stats.toml](Templates/Dwerve/Dwerve.Stats.toml) contains every moddable stat set to their default value.

# CurseForge
All Dwerve mods are hosted on CurseForge, a platform that let's you browse, download, and manage mods via the CurseForge website or the in-game UI. Both official and user-created mods can be found on [Dwerve's CurseForge page](https://www.curseforge.com/dwerve/mods). From there, you can also upload your own mods by pressing [Start Project](https://www.curseforge.com/project/80345/6101/create). A mod is simply a zip file that contains TOML and image files.

# Official Mods
Our team has built 12 official mods for Dwerve. The mod source code for each is available in this repository for you to reference when creating your own mods. Here is a list of the official mods:

* [All Artifacts](Mods/AllArtifacts)
* [Anytime Dash](Mods/AnytimeDash)
* [Complete Arsenal](Mods/CompleteArsenal)
* [Endless Smash](Mods/EndlessSmash)
* [Forever Traps](Mods/ForeverTraps)
* [Funny Chakram](Mods/FunnyChakram)
* [Long-Range Scattershot](Mods/LongRangeScattershot)
* [Red Hair](Mods/RedHair)
* [Turd Slimes](Mods/TurdSlimes)
* [Super Fast Walk](Mods/SuperFastWalk)
* [Ten Power Stones](Mods/TenPowerStones)
* [Wicked Fast Wargboars](Mods/WickedFastWargboars)

# Join our Community
Want to share your mod or ask the devs a question? Join the [Half Human Games Discord](https://discordapp.com/invite/halfhumangames) and follow [@HalfHumanGames](https://twitter.com/intent/user?screen_name=HalfHumanGames) on Twitter! Report any mod-related bugs via the [Issue Tracker](https://github.com/HalfHumanGames/DwerveMods/issues).
___
Copyright © 2019 Half Human Games, Inc. All Rights Reserved.