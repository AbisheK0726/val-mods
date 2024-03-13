# CraftFromContainers by aedenthorn
## Description
---
This mod allows you to pull resources from all containers in range when:

* crafting an item
* upgrading an item
* building a construction piece
* adding fuel or ore to a smelter
* adding wood to a kiln
* adding fuel to a fire, standing torch, or sconce,
* cooking food in a cooking station
* doing whatever it is you do with windmills

It also provides several modifier keys for advanced behaviour

* a modifier key (**left shift** by default) that, when held, pulls until full for ore and fuel.
* a modifier key (**left ctrl** by default) that, when held, pulls the resources into the player inventory instead of building/crafting.
* a modifier key to turn off the mod's behaviour entirely (**left alt** by default) when held down. This behaviour can also be reversed in the config to only allow this mod to perform its function when the key is held down by setting **SwitchPrevent** to **true**.

## Features
---

Crafting stations and build menu will show an item's creatability based on resources available in all nearby containers rather than just player
inventory.

Resource requirement numbers will now also show the total amount available in nearby chests. You can customize this in the
config file.

Resources that the player's inventory doesn't have enough of will flash yellow (customizable) instead of red.

When building a container, there will now be particle effect lines between the container and crafting stations in range, thanks to bakaspaceman who wrote this code!

## Prevent Lists
---

There are two prevent lists in the config:

* **FuelDisallowTypes** - specifies types of consumables like wood and coal that are disallowed (does not apply to kilns, as kilns considered wood an ore)
* **OreDisallowTypes** - specifies types of ore (anything that is transformed into something else) that are disallowed.

Both lists should be comma separated with no spaces, e.g. RoundLog,FineWood.

Item names are available [here](https://www.reddit.com/r/valheim/comments/lig8ml/spawn_item_command_list/).

## Config
---
A config file **BepInEx/config/aedenthorn.CraftFromContainers.cfg** is created after running the game once with this mod).

You can adjust the config values by editing this file using a text editor or in-game using the [Config Manager](https://www.nexusmods.com/valheim/mods/740).

## Notes
---
This mod replaces the **Player.ConsumeResources** method, so may conflict with anything that tries to patch that.

If you want to see what's happening behind the scenes, the log will spew out mildly informative information about where the resources are coming from (see screenshot).

## Technical
---
To install this mod, the easiest way is to just use [**Vortex**](https://www.nexusmods.com/about/vortex/), the Nexus Mods mod manager. It should take care of all dependencies.

To install manually, place the dll file in the BepInEx/plugins folder. You will need BepInEx.

Code is at https://github.com/aedenthorn/ValheimMods.

If you want to complain or ask for help or help me test my mods, you can visit [my Discord server](https://discord.gg/bs6zHuj).

[Click here for a list of all my mods for Valheim](https://www.nexusmods.com/valheim/articles/104).