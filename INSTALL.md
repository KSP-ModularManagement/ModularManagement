# Modular Management

A convenient entry point Package for KSP modding with all batteries included.

**KSPe** is Lisias' Extensions and utilities for Kerbal Space Program

**ModuleManager /L** is Lisias' fork of ModuleManager.

**ModuleManagerWatchDog** is a Watch Dog for Module Manager.

## Installation Instructions

To install, place the `GameData` folder from the package inside your Kerbal Space Program `GameData` folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**:
	+ Delete `<KSP_ROOT>/GameData/TweakScaleCompanion`
* Extract the package's `GameData/` folder into your KSP's as follows:
	+ `<PACKAGE>/GameData/TweakScaleCompanion ` --> `<KSP_ROOT>/GameData`
		- Overwrite any preexisting files.

The following file layout must be present after installation (includes the non included dependencies listed below):

```
<KSP_ROOT>
	[GameData]
		[000_KSPe]
			...
		[ModuleManagerWatchDog]
			...
		[ModuleManager]
			...
		000_KSPe.dll
		666_ModuleManagerWatchDog.dll
		ModuleManager.dll
		...
	KSP.log
	PartDatabase.cfg
	...
```


### Dependencies

N/A

