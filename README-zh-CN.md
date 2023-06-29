# 《战匠杜沃》Mods
观看这个 4 分钟的视频，了解为  [《战匠杜沃》Dwerve](https://store.steampowered.com/app/1132760/Dwerve/) 制作自己的模组是多么快速和容易！

[![Dwerve Mods Tutorial Video](Assets/video-thumbnail.png)](https://youtu.be/0PtbafPWmwE)

## 概览
这篇文章介绍了如何为 [《战匠杜沃》Dwerve](https://store.steampowered.com/app/1132760/Dwerve/) 创建mod 。 同时也包括了战匠杜沃mod工具的源代码，以及对应的范例文件，还有可以用任何sprite编辑器轻松编辑Sprite动画的sprite表。

## 功能介绍
该mod系统能够允许大家轻松地编辑数据以及图像。你也可以更改游戏中防御塔，能量石，神器的解锁，比如，你可以更改防御塔的外形，使其可以击退并眩晕敌人。

## 文件格式
战匠杜沃使用 [TOML](https://TOML.io/en) 来编辑mod。TOML是门槛低，阅读容易的文件格式，想要创建新的mod，只要下载mod范例文件夹，然后直接编辑其中的TOML以及图像文件即可。想要更改各类Spirit图以及材质等，我们推荐使用 [Aseprite](https://store.steampowered.com/app/431730/Aseprite/)，不过也可以使用免费的 [Piskel](https://www.piskelapp.com/)，我们在这里为大家准备了一些范例 [《战匠杜沃》Dwerve](Templates/Dwerve), [Towers](Templates/Towers), [Enemies](Templates/Enemies), 和 [Configuration](Templates/Configuration)。

## 范例MOD
范例TOML文件例如 [Dwerve.Stats.toml](Templates/Dwerve/Dwerve.Stats.toml) 含有各种能够修改的数据以及默认数值。你可以忽略那些不需要更改的数据，当然强迫症的话也可以删掉它们。我们这里给大家提供了[Super Fast Walk凌波微步]的范例文件 [Super Fast Walk](Mods/SuperFastWalk/SuperFastWalk.toml)，这个mod将原先4.3移动速度的杜沃提升了一倍。

```TOML
ModTarget = "Dwerve"

[Stats]
Speed = 8.6
```

## CurseForge
所有mod以及活动都在 [CurseForge](https://www.curseforge.com/dwerve/mods) 中收录，大家可以在这里寻找，下载，管理各种游戏的mod。你也可以通过 [创建project](https://www.curseforge.com/project/80345/6101/create) 上传属于自己的mod。

## 官方Mod
* [全神器 - 全神器解锁](Mods/AllArtifacts)
* [任意冲锋 - 冲刺不再有冷却时间！](Mods/AnytimeDash)
* [全解锁 - 解锁所有防御塔和陷阱！](Mods/CompleteArsenal)
* [全部砸烂 - 随心所欲挥动巨锤！](Mods/EndlessSmash)
* [永久陷阱 - 陷阱不再有持续时间限制！](Mods/ForeverTraps)
* [逗比飞轮 - 飞轮现在十分缓慢，但是会击飞敌人！](Mods/FunnyChakram)
* [长距离散射 - 大幅度延长霰弹散射的范围！](Mods/LongRangeScattershot)
* [红发 - 让杜沃长红毛~](Mods/RedHair)
* [粑粑史莱姆 - 把所有史莱姆变成粑粑！](Mods/TurdSlimes)
* [凌波微步 - 杜沃现在跑得飞快！](Mods/SuperFastWalk)
* [十全十美 - 现在可以有10个能量石！](Mods/TenPowerStones)
* [光速战豚 - 让这些敌人跑得飞快！](Mods/WickedFastWargboars)

## 加入我们的社区！
希望和开发团队直接交流？还是分享更多的mod？欢迎加入我们的社区！[Half Human Games Discord](https://discordapp.com/invite/halfhumangames)，也可以关注我们的推特 [@HalfHumanGames](https://twitter.com/intent/user?screen_name=HalfHumanGames)，想要反馈bug的话也可以通过 [Issue Tracker](https://github.com/HalfHumanGames/DwerveMods/issues)。期待大家带来的作品！
___
*Copyright © 2019 Half Human Games, Inc. All Rights Reserved.*