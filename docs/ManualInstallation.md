---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Not So SimpleConstruction! (NSSC)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Not So SimpleConstruction! (NSSC)

[Home](./index)

Adds Mallet, Survey Stake, Recycler, Disposable Pad, and Orbital Dock; and turns Cupola module to Survey Station. Requires SimpleConstruction! for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the MOD-NAME folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/NotSoSimpleConstruction`
* Extract the package's `NotSoSimpleConstruction/` folder into your KSP's GameData as follows:
  * `<PACKAGE>/SimpleConstruction` --> `<KSP_ROOT>/GameData/NotSoSimpleConstruction`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/NotSoSimpleConstruction`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/NotSoSimpleConstruction`
* Extract the package's `GameData/` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/NotSoSimpleConstruction`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [ExtraplanetaryLaunchpads] 
      *(see SimpleConstruction! for manual installation directions)*
    + [NotSoSimpleConstruction]
      + [Assets]
        ...
      + [Compatibility]
        ...
      + [Configs]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * changelog.md
      * GPLv3.txt
      * readme.htm
      * NotSoSimpleConstruction.version
    + [SimpleConstruction]
      *(see SimpleConstruction! for manual installation directions)*
      ...
    ...
    * [Module Manager][mm] or [Module Manager /L][mml]
  * KSP.log
  ...
```

### Dependencies

* [SimpleConstruction! (SCON!)][SCON]
* *either*
  * [Module Manager][mm]
  * [Module Manager /L][mml]

[SCON]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-* "SimpleConstruction! (SCON!)"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
