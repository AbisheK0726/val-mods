*_**COMPATIBLE WITH LATEST UPDATE! VERSION 1.4.0**_*
___________________________________________________________________________________
_**What is it?:**_

Unrestricted Portals is a mod that allows players to take any item through portals. The mod is highly customizable, allowing players to restrict or unrestrict every individual item.
___________________________________________________________________________________
_**Why install it?:**_

Because Valheim has so many resources that are separated by tons of land and water, it makes grinding certain resources a pain. Having to go from one point ﻿to another takes lots of time. It is a useless grind. The developers fixed this by adding portals. This would be a solution, but they then blacklisted certain items. The blacklist of certain items forced players to go back to doing the useless grind.

If you think being able to take every item across portals is too overpowered or easy, then you can edit the configuration file to:


- Make every item teleportable. (Can be overridden by individual item entries .)
- Make every item unteleportable. (Can be overridden by individual item entries.)
- Make individual items teleportable.
- Make individual items unteleportable.


___________________________________________________________________________________
_**How do you install it?:**_

1) Go to [BepInExPack Valheim](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/)
2) Download it and follow the installation manual
3) Drag the unzipped Unrestricted Portals folder into -> *<Steam Location>\steamapps\common\Valheim\BepInEx\plugins*

The next time you start your game, the mod will be enabled. To disable it, just remove it from the mods folder or change the configuration.
___________________________________________________________________________________
_**How do you use it?:**_

To update the config, use the command:
"/update" or "/reload"

By default, the mod will let you take 100% of previously restricted items through portals.


- Make every item _teleportable_-> **AllTeleportable: True** AND **NoneTeleportable: False**
- Make every item _unteleportable_-> **AllTeleportable: False** AND **NoneTeleportable: True**
- Make every item have their default teleportation restriction -> **AllTeleportable: False** AND **NoneTeleportable: False**
****
- Make individual items _teleportable (example)_ -> **TinOre: True**
- Make individual items _unteleportable (example)_ -> **CopperOre: False**
****


_[ Item names need to use either token syntax or prefab syntax.](https://github.com/Valheim-Modding/Wiki/wiki/ObjectDB-Table)_

The configuration file is located at -> ***<Steam Location>\steamapps\common\Valheim\BepInEx\config\UnrestrictedPortals.yml***
___________________________________________________________________________________