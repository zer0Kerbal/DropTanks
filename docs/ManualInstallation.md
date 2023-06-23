---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.0.0
Drop Tanks (DROP)
created: 01 Oct 2019
updated: 27 May 2023

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->

## [Drop Tanks (DROP)][mod]

[Home](./index.md)

Stockalike curved conformal (wrap-around) DropTanksIII with an integrated decoupler

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `KerbalHacks` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KerbalHacks/DropTanks`
* Extract the package's `KerbalHacks` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KerbalHacks` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/KerbalHacks/DropTanks`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KerbalHacks/DropTanks`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KerbalHacks/DropTanks`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [KerbalHacksLtd]
      + [DropTanks]
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
          ManualInstallation.htm
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-NC-SA-4.0.txt
        * changelog.md
        * DropTanks.version
        * readme.htm
      ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Kerbal Hacks Ltd. (KH/L)][KHL]

[KHL]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-*/ "Kerbal Hacks Ltd. (KH/L)"