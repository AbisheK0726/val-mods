# AutoFuel by aedenthorn
## Description

This mod makes fireplaces (includes torches, etc.) and smelters (includes kilns, etc.) suck up fuel (consumables) and ore (transformables) from the ground and nearby containers.

With this mod you can either

a) put coal, wood, or ore in a nearby container and the furnace and kiln should suck it up, or
b) drop coal, wood, or ore on the ground near kilns or smelters.

There are three configurable ranges:

* **fireplaceRange**
* **smelterOreRange**
* **smelterFuelRange**

The default range for each type of fueling is 5 meters.

## Config

A config file **BepInEx/config/aedenthorn.AutoFuel.cfg** is created after running the game once with this mod).

You can adjust the config values by editing this file using a text editor or in-game using the [Config Manager](https://www.nexusmods.com/valheim/mods/740).

There are two prevent lists in the config:

* **FuelDisallowTypes** - specifies types of consumables like wood and coal that are disallowed (does not apply to kilns, as kilns considered wood an ore)
* **OreDisallowTypes** - specifies types of ore (anything that is transformed into something else) that are disallowed.

You can optionally set a hotkey to toggle the behaviour on and off, and you can adjust the ranges for containers and ground pulling (default 10 meters each).

You can reset the config by opening the in-game console (F5) and typing **autofuel reset** and pressing **Enter**.

## Technical

To install this mod, the easiest way is to just use [**Vortex**](https://www.nexusmods.com/about/vortex/), the Nexus Mods mod manager. It should take care of all dependencies.

To install manually, place the dll file in the BepInEx/plugins folder. You will need BepInEx.

Code is at https://github.com/aedenthorn/ValheimMods.

If you want to complain or ask for help or help me test my mods, you can visit [my Discord server](https://discord.gg/bs6zHuj).

[Click here for a list of all my mods for Valheim](https://www.nexusmods.com/valheim/articles/104).