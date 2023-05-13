# Modular Management

A convenient entry point Package for KSP modding with all batteries included.

**KSPe** is Lisias' Extensions and utilities for Kerbal Space Program

**ModuleManager /L** is Lisias' fork of ModuleManager.

**ModuleManagerWatchDog** is a Watch Dog for Module Manager.


## Installation Instructions

To install, place the `GameData` folder from the package inside your Kerbal Space Program `GameData` folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**:
	+ Delete `<KSP_ROOT>/GameData/000_KSPe/`
	+ Delete `<KSP_ROOT>/GameData/ModularManagement/`
	+ Delete `<KSP_ROOT>/GameData/ModularManagementWatchDog/`
	+ Delete `<KSP_ROOT>/GameData/000_KSPe.dll`
* Extract the package's `GameData/` folder into your KSP's as follows:
	+ `<PACKAGE>/GameData` --> `<KSP_ROOT>/`
		- Overwrite any preexisting files.

The following file layout must be present after installation (includes the non included dependencies listed below):

```
<KSP_ROOT>
	[GameData]
		[000_KSPe]
			[Plugins]
				...
			[patches]
				...
			CHANGE_LOG.md
			LICENSE
			LICENSE.3rdParties
			LICENSE.KSPAPIExtensions
			LICENSE.KSPe.GPL-2_0
			LICENSE.KSPe.SKL-1_0
			NOTICE
			README.md
			KSPe.version
		[ModularManagement]
			LICENSE
			ModularManagement.version
			NOTICE
			README.md
		[ModuleManager]
			CHANGE_LOG
			ModuleManager.version
			...
		[ModuleManagerWatchDog]
			CHANGE_LOG
			ModuleManagerWatchDog.version
			...
		000_KSPe.dll
		666_ModuleManagerWatchDog.dll
		ModuleManager.dll
		...
	[PluginData]
		[ModuleManager]
			...
	KSP.log
	PartDatabase.cfg
	...
```


### Dependencies

N/A

