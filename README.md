# Regolith Hydrogen Reduction
This is a mod for [Solar Expanse](https://solar-expanse.xsolla.site/). It adds regolith as a resource to planets, moons and larger asteroids in the solar system. Regolith is used in [hydrogen reduction](https://www.sciencedirect.com/science/article/pii/S0032063321001264). For balancing this is an energy intensive process, allowing to utilize a ubiquous resource in the solar system to gain a trickle of basic resources on most bodies. The process utilizes heated hydrogen to stip the oxygen from a variety of minerals resulting in water and the usable minerals.

For more details on added resources refer to [deposits.yaml](./regolith_hydrogen_reduction/deposits.yaml)

Inspired by (ted505)[https://github.com/ted505]'s regolith mod (only available in discord).

# Known issues
When using research to unlock the regolith reduction I ran into the issue that when the research was already done, the buildings will not be unlocked. To circumvent this, the buildings are unlocked from the beginning.


# Installation
## Dependencies
It requires [Teddit](https://github.com/ted505/solar-expanse-teddit) YAML modding framework for Solar Expanse and (BepInEx)[https://github.com/BepInEx/BepInEx]. For installation of Teddit, refer to the readme of Teddit repository.

## Installing the regolith mod
To install this mod, copy the contents of the zip into the `Solar Expanse\BepInEx\plugins\Teddit\mods` directory, so that you have then the path `Solar Expanse\BepInEx\plugins\Teddit\mods\solar_expanse_regolith-x.x`

If you have a previous version installed, make sure you delete the old version.