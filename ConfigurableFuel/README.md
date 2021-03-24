# Configurable Fire
This mod adds configurability to Fires.

## Specifications
* Fires supported - FirePit, Bonfire and Hearth
* Configure Max and Start Count, Type and Burn Duration of Fuel for Fires.
* Disable use the need for Fuels.
* Extinguish and re-light Fires.
* Modifier Key (Default: G) for toggling Fires.

## Installation
1. Install BepInEx
2. Unzip `ConfigurableFire.zip`
3. Copy `ConfigurableFire.dll` to `Valheim\BepInEx\plugins`

## Configuration
* Config file will auto generate after Valheim is run for the first time after adding the Mod.
* Or additionally download add the .cfg to `.\BepInEx\config\goonlou.ConfigurableFire.cfg`.  

~~~ini
## Settings file was created by plugin Configurable Fire v0.1.0
## Plugin GUID: goonlou.ConfigurableFire

[00_General]

## Allow all fires to burn without fuel
# Setting type: Boolean
# Default value: false
all_Nofuel = false

## Allow all fires to be extinguishable
# Setting type: Boolean
# Default value: true
ExtinguishableFires = true

## Modifier key to toggle fires on and off. Use https://docs.unity3d.com/Manual/ConventionalGameInput.html
# Setting type: String
# Default value: G
toggleFireKey = G

## Enable this mod
# Setting type: Boolean
# Default value: true
Enabled = true

[01_fire_pit]

## Allow fire Pit to burn without fuel
# Setting type: Boolean
# Default value: false
fire_pit_NoFuel = false

## Fuel type for Fire Pit. Swap with any Prefab Name https://github.com/Valheim-Modding/Wiki/wiki/ObjectDB-Table
# Setting type: String
# Default value: Wood
fire_pit_FuelType = Wood

## Maximum fuel level for Fire Pit
# Setting type: Single
# Default value: 10
fire_pit_MaxFuel = 10

## Start fuel level for Fire Pit
# Setting type: Single
# Default value: 1
fire_pit_StartFuel = 1

## Time for Fire Pit to burn 1 fuel (sec)
# Setting type: Single
# Default value: 5000
fire_pit_FuelTimeToBurn = 5000

[02_bonfire]

## Allow Bonfire to burn without fuel
# Setting type: Boolean
# Default value: false
bonfire_NoFuel = false

## Fuel type for Bonfire pit. Swap with any Prefab Name https://github.com/Valheim-Modding/Wiki/wiki/ObjectDB-Table
# Setting type: String
# Default value: Wood
bonfire_FuelType = Wood

## Maximum fuel level for Bonfire pit
# Setting type: Single
# Default value: 10
bonfire_MaxFuel = 10

## Start fuel level for Bonfire pit
# Setting type: Single
# Default value: 0
bonfire_StartFuel = 0

## Time for Bonfire pit to burn 1 fuel (sec)
# Setting type: Single
# Default value: 5000
bonfire_FuelTimeToBurn = 5000

[03_hearth]

## Allow Hearth to burn without fuel
# Setting type: Boolean
# Default value: false
hearth_NoFuel = false

## Fuel type for Hearth pit. Swap with any Prefab Name https://github.com/Valheim-Modding/Wiki/wiki/ObjectDB-Table
# Setting type: String
# Default value: Wood
hearth_FuelType = Wood

## Maximum fuel level for Hearth pit
# Setting type: Single
# Default value: 20
hearth_MaxFuel = 20

## Start fuel level for Hearth pit
# Setting type: Single
# Default value: 0
hearth_StartFuel = 0

## Time for Hearth pit to burn 1 fuel (sec)
# Setting type: Single
# Default value: 5000
hearth_FuelTimeToBurn = 5000
~~~

## Changelog
* v0.1.0: Initial Release
* v0.0.1: Rename Mod from ConfigurableFuel to ConfigurableFire

## Planned Future Updates
* Support for Standing Torches and Sconce.
* Bug fixes.