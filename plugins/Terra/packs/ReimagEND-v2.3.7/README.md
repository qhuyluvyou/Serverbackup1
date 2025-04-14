![ReimagEND](https://github.com/user-attachments/assets/c407dcf6-ae98-4a7b-8db8-36b41d3ee7d3)

## A Terra pack designed to reimagine the End with new biomes, features, and terrain to explore

Part of this pack uses resources from Astrash's Aeropelago pack, found [here](https://github.com/Astrashh/Aeropelago).

This pack is a *WORK IN PROGRESS*.  

It is currently survival ready, but not feature complete. Expect frequent changes which may be incompatible (i.e, cause chunk borders) with older versions of the pack. 

Vanilla End Cites generate with their loot tables unaffected while custom structures don't have custom loot table implementation as of the current moment.

## Installation
Download the ReimagEnd pack from the [releases page](https://github.com/justaureus/ReimagEND/releases) for a reliable pack version 
or from the main ReimagEnd branch for changes that haven't been applied to the latest release yet.

Follow this [installation guide](https://terra.polydev.org/install/index.html) for your particular platform.

Fabric users will have to edit the `level.dat` in order to apply custom generation to the end dimension.

#### Bukkit.yml Quick Reference 
##### Affects just the Vanilla End Dimension
```
worlds:
  world_the_end:
    generator: Terra:REIMAGEND
```
##### More than One Config Pack for Multiple Worlds 
```
worlds:
  world:
    generator: Terra:OVERWORLD
  world_the_end:
    generator: Terra:REIMAGEND
```

## How to Disable Biomes
Dislike a particular biome? 
Well, you can customize everything in ReimagEnd to your liking and that includes disabling any biomes!

Go to the corresponding distribution stage for that biome type (end, aether, & void), which can be found in `biome-providers\stages`
###### Place a # in front of the weighted item representing the biome in the list to comment out the biome and disable it

## Overworld-Like Aether Pockets
By default, overworld-like Aether pockets generate throughout the frontier of the outer end. 

Aether pocket generation can be disabled by going to the `meta.yml` and toggling the `toggle-aether-pockets` value
###### Place a # in front of the stage to comment out the stage

## Dragon Island Difficulty Tweaks
ReimagEnd has optional dragon island difficulty tweaks that can be enabled to make the dragon fight a bit more challenging, which are listed below.
- Pitfall into the void around the dragon fountain that now resides on a small floating island in the center.
- Vex spawners under the dragon fountain that make approaching the fountain a bit more challenging.
- Vex spawners within the top and bottom sections of the dragon pillars that give the end crystals a bit more protection against those who seek to destroy them.

Go to the `meta.yml` to enable and configure these features
