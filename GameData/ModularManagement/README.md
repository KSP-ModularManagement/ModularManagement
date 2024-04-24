# Modular Management

A convenient entry point Package for KSP modding with all batteries included.


## In a Hurry

* [Source](https://github.com/KSP-ModularManagement/ModularManagement)
	+ [Issue Tracker](https://github.com/KSP-ModularManagement/ModularManagement/issues)
* Documentation
	+ [Forum](https://forum.kerbalspaceprogram.com/index.php?/topic/192216-*)
	+ [Project's README](https://github.com/KSP-ModularManagement/ModularManagement/blob/master/README.md)
	+ [Install Instructions](https://github.com/KSP-ModularManagement/ModularManagement/blob/master/INSTALL.md)
* Official Distribution Sites:
	+ [CurseForge](https://www.curseforge.com/kerbal/ksp-mods/modularmanagement)
	+ [Homepage](http://ksp.lisias.net/add-ons/ModularManagement) on L Aerospace
	+ [Latest Release](https://github.com/KSP-ModularManagement/ModularManagement/releases)


## Description

**Modular Management** is a a convenient entry point Package for KSP modding with all batteries included.

It pre packages imprescindible (or very useful at least) components for starting up a safe and cohesive KSP installation in a single shot with components **well maintained and well supported** by the authors.

You **will not** be left high and dry while flying your favorites crafts over Kerbin and beyound!


### Current Modules

#### `KSPe`

Offer standardised, KSP version abstracted features, utilities and helpers to help the fellow KSP Add'On Author to seamless support past, present and (hopefully) future versions of KSP without needing even a recompile.

Fellow Authors willing to use this library are welcome to read the documentation available [here](https://github.com/KSP-ModularManagement/KSPe/wiki).

#### `Module Manager /L`

ModuleManager is a mod that let you write patches that edit other parts at load time.

This is Lisias' fork for Module Manager, and it's intended to bring functionality and performant improvements to ModuleManager - with great to moderate success being achieved toward these goals (most of the time!), as well others not mentioned here.

Backwards compatibility is guaranteed - including functional bugs on `Module Manager - Forum`. `MM/L`'s patching output will be always the same as `Module Manager - Forum`, salvo new (and optional) features when not present on `Module Manager - Forum`.

#### `Module Manager Watch Dog`

`MMWD` is a Watch Dog to monitor Module Manager, preventing known (and unsolved) bugs on KSP 1.8 and newer that affects it.

Additional services for updating specific DLLs on `GameData` are now part of the solution, making it useful even for KSP <= 1.7.3 .


## Installation

Detailed installation instructions are now on its own file (see the [In a Hurry](#in-a-hurry) section) and on the distribution file.

### Notes

* Module Manager /L **does not** replaces Forum Module Manager if it is already installed.
	+ If you plan to use MM/L you need to manually remove FMM from your `GameData` **BEFORE** installing **Modular Management**.
* If Forum Module Manager is installed after Module Manager /L is active, The Watch Dog will bark and you will need to remove one of them in order to run KSP.

### License

* This work is licensed as follows:
	+ [SKL 1.0](https://ksp.lisias.net/SKL-1_0.txt). See [here](./LICENSE.SKL-1_0)
		+ You are free to:
			- Use : unpack and use the material in any computer or device
			- Redistribute: redistribute the original package in any medium
		+ Under the following terms:
			- You agree to use the material only on (or to) KSP
			- You don't alter the package in any form or way (but you can embedded it)
			- You don't change the material in any way, and retain any copyright notices
			- You must explicitly state the author's Copyright, as well an Official Site for downloading the original and new versions (the one you used to download is good enough)
	+ Individual packages under the `GameData` directory are distributed under their own licenses.

Be advised that redistribution of derivatives is expressibly forbidden.

See [NOTICE](./NOTICE) for further copyright and trademarks notices.


## Acknowledgments

<a href="https://www.flaticon.com/free-icons/cube" title="cube icons">Cube icons created by Freepik - Flaticon</a>


## References

* KSPe ([LisiasT](https://github.com/Lisias))
	+ [GitHub](https://github.com/KSP-ModularManagement/KSPe).
* ModuleManager /L ([LisiasT](https://github.com/Lisias))
	+ [GitHub](https://github.com/KSP-ModularManagement/ModuleManager).
* Module Manager Watch Dog ([LisiasT](https://github.com/Lisias))
	+ [GitHub](https://github.com/KSP-ModularManagement/ModuleManagerWatchDog).
