
# Loot Multiplier for Valheim

This is mod multiplies loot drops when you destroy, kill or pick up something. Drop multiplier can be configured.

## Installation (manual)

If you are installing this manually, do the following

1. Extract the archive into a folder. **Do not extract into the game folder.**
2. Move the contents of `plugins` folder into `<GameDirectory>\Bepinex\plugins`.
3. Run the game.
4. To change the drop rate, use the config at \BepInEx\config\castix_LootMultiplier.cfg

## Configuration
```
## Settings file was created by plugin LootMultiplier v1.0.8
## Plugin GUID: castix_LootMultiplier

[General]

## Material Multiplier
# Setting type: Int32
# Default value: 1
Multiplier for resources = 1

##  Monster Drop Multiplier
# Setting type: Int32
# Default value: 1
Multiplier for monster drops = 1

## Pickup Multiplier
# Setting type: Int32
# Default value: 1
Multiplier for pickable objects = 1

[Whitelist]

## Whitelist
# Setting type: Boolean
# Default value: false
Enable whitelist filter = false
```

## How to set up the custom whitelist

1. Enable the whitelist in the Loot Multiplier config.
2. Open the whitelist.txt file. It always has to be in the same directory as the plugin .dll (example: <GameDirectory>\BepInEx\plugins\LootMultiplier\whitelist.txt)
3. Add items to the list by writing the Prefab name of the item you want. One per line.
4. If the whitelist is enabled, only the allowed items inside it will be multiplied.

![](https://i.imgur.com/a1uSfeB.png)

##Changelog
1.0.0
- Release

1.0.1
- fixed monster drops

1.0.2
- added loot multiplier to items that are picked up

1.0.3
- fixed berry bushes being interactable after you picked all the berries

1.0.4
- fixed spawning a redundant prefab if you set the multiplier to 1
- spread the loot multiplier into 3 categories: materials, loot (from monsters) and pickup

1.0.5
- made config a bit easier to understand
- fixed drops not working for x2 multiplier
- monster drop multiplier now works on all animals and monsters

1.0.6
- added a custom whitelist for all multipliers

1.0.7
- fixed multiplier only working on the first pickable on the whitelist

1.0.8
- loot multiplier now works for honey/queen bees, fish and valuables

