# Oceanus

Oceanus makes your world smaller without the need for an intrusive world border. This is done by preventing land generation once you've travelled a certain distance, creating a circular world surrounded by endless ocean.

## Configurability (datapack only)

All configurable values can be accessed in the directory `data/oceanus/worldgen/density_function/configurable.`

* Unaffected Radius: Radius around spawn where terrain generation is unchanged from vanilla
* Falloff Radius: Width of the band in which land is gradually overtaken by the ocean
* Mushroom islands: Enable or disable mushroom island generation in the endless ocean
* Offset: Offset the center of the unaffected/falloff area
* Ocean Variability: How varied the ocean terrain is, from endless deep ocean to regular ocean generation
  
<details>
<summary> Default Values </summary>

* Unnaffected Radius: 5000 blocks
* Falloff Radius: 2000 blocks
* Mushroom islands: enabled
* Offset: none
* Ocean Variability: 30%

</details>

## Compatibility

In general any mods or packs that don't drastically alter worldgen should be compatible with Oceanus, including most popular biome mods. An easy way to verify this for datapacks is by using the [Datapack Map](https://map.jacobsjo.eu/) by jacobsjo. 

If Oceanus doesn't seem to be working, try changing the load order of the pack, it should generally be at the bottom of the list.

To check compatibility with specific mods, check our [wiki](https://github.com/Lizdtre/Oceanus/wiki/Compatibility). To request compatibility with a specific mod, use the [Issues](https://github.com/Lizdtre/Oceanus/issues) page.


## FAQ

Does this work with pre-existing worlds?

> Yes! Generation in the unaffected radius is, well, unaffected. So as long as you haven't travelled beyond that (or are willing to regenerate those chunks), you should be able to use Oceanus on any existing world without creating ugly chunk borders. Still, always make backups.

Will you port the pack to versions before 1.19?

> Datapacks couldn't really change worldgen before that. Others are free to take this idea and make it a mod for those versions.
 
---
Also checkout [One Survival Island](https://modrinth.com/datapack/one-survival-island) by Klinbee

Credit to [Uni](https://github.com/unnecessarymb) for the vanilla coordinate density function

Gallery maps created with the [Datapack Map](https://map.jacobsjo.eu/) by jacobsjo
