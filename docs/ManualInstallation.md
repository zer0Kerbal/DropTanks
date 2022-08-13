---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Drop Tank Wrapper (DROP) by Kerbal Hacks
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Drop Tank Wrapper (DROP) by Kerbal Hacks

[Home](./index.md)

Stockalike curved wraparound droptanks with an integrated decoupler for Kerbal Space Program

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `DropTankWrapper` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KerbalHacks/DropTankWrapper`
* Extract the package's `KerbalHacks` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KerbalHacks` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/KerbalHacks/DropTankWrapper`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KerbalHacks/DropTankWrapper`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KerbalHacks/DropTankWrapper`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [KerbalHacksLtd]
      + [DropTankWrapper]
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
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-NC-SA-4.0.txt
        * changelog.md
        * DropTankWrapper.version
          ManualInstallation.htm
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
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
