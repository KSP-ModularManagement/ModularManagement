# Module Manager Watch Dog :: Change Log

* 2023-0313: 1.1.0.4 (LisiasT) for KSP >= 1.2.2
	+ Makes the thing survivable if KSP starts with the `pwd` set to anywhere but the `KSPUtil.ApplicationRootPath`.
	+ Closes issue:
		- [#6](https://github.com/net-lisias-ksp/ModuleManagerWatchDog/issues/6) Resurrect the multiple ModuleManager DLLs check for KSP 1.12.x 
* 2022-1112: 1.1.0.3 (LisiasT) for KSP >= 1.2.2
	+ ***DITCHED***
* 2022-0719: 1.1.0.2 (LisiasT) for KSP >= 1.2.2
	+ Fixes a mishap while updating the target DLL.
* 2022-0621: 1.1.0.1 (LisiasT) for KSP >= 1.2.2
	+ Adds a Install Checker for:
		- The tool itself
		- ModuleManager /L
		- TweakScale
	+ Closes issue:
		- [#5](https://github.com/net-lisias-ksp/ModuleManagerWatchDog/issues/5) Cook a `GameData/*.dll` update tool 
* 2022-0621: 1.1.0.0 (LisiasT) for KSP >= 1.2.2
	+ ***DTICHED*** due a stupid mistake on handling pathnames... #facePalm 
* 2021-0907: 1.0.1.1 (LisiasT) for KSP >= 1.2.2
	+ Promoted to Release
	+ Revamping the Redist checks, promoting modularity and selective deployment
	+ Adding checks for KSP 1.12.x due changes on how DLLs are loaded.
		- Prevents MM and MM /L forks from stomping each other toes. 
* 2021-0907: 1.0.1.0 (LisiasT) for KSP >= 1.2.2
	+ ***Ditched*** due a deployment mishap.
* 2021-0705: 1.0.0.0 BETA (LisiasT) for KSP >= 1.2.2
	+ Added rules to be enforced for:
		- Scale Redist not having duplicated DLLs, being present when needed and on the correct place  
		- Interstellar Redist not having duplicated DLLs, being present when needed and on the correct place  
	+ Allowing the rules to be waived or enforced on the running KSP version at user's discretion (by a patch on a ConfigNode file)
		- Including the Module Manager ones. 
	+ Allowing the thing to run on KSP >= 1.2.2, as this thingy can be useful on many KSP versions now.
* 2020-0612: 0.0.2.0 (LisiasT) for KSP >= 1.4
	+ Minor fixes and adjustments
* 2020-0612: 0.0.1.0 (LisiasT) for KSP >= 1.4
	+ Initial public release
	+ Works on KSP >= 1.4, but it's only needed on KSP >= 1.8 