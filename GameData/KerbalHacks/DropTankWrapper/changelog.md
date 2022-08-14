# Changelog  
  
| modName    | Drop Tank Wrapper (DROP)                                          |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-NC-SA-4.0                                                   |
| author     | Enceos and zer0Kerbal                                             |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209332-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/DropTankWrapper)        |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/DropTankWrapper)      |
| spacedock  | (https://spacedock.info/mod/1127)                                 |
| ckan       | DropTankWrapper                                                   |

## Version 1.0.99.0-adoption - `<Thank you Enceos>` edition

* 12 Aug 2022  
* Released for Kerbal Space Program [KSP 1.12.x]

### Summary 1.0.99.0

* Adoption by zer0Kerbal
* Localization
  * English
  * Dutch thank you to @renejant (*bedankt!*)

### docs/

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Parts-Catalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* closes #36 - docs/

### Add localized tags to parts

* Add
  * [DropTankWrapper.cfg] v1.0.0.0
    * adds localized tags to parts
* closes #38 - Add localized tags to parts

### Localization 1.0.99.0

* Create
  * Localization/
    * <en-us.cfg>
    * <nl-nl.cfg> v1.0.1.0
      * thank you to @renejant (*bedankt!*)
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* updates #14 - Localization Master
* closes #15- English <en-us.cfg>
* closes #26 - Dutch <nl-nl.cfg>
* closes #32 - Part Localization
* closes #37 - Localization Issue

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* rename parts to standardized names (e.g. drop-)
  * <WrapperTankLong> --> <drop-tank-sleeve> v2.0.0.0
  * <WrapperTankBracelet> --> <drop-tank-bracelet> v2.0.0.0
  * <WrapperTank> --> <drop-tank-wrapper> v2.0.0.0
  * <WrapperCap> --> <drop-tank-cap> v2.0.0.0
  * <WrapperTankWristband> --> <drop-tank-wristband> v2.0.0.0
  * Add
    * <ghostParts.cfg> v1.3.0.1
    * in order to prevent name changes from breaking compatibility
* closes #35 - Asset Updates

### Compatibility 1.0.99.0

* Add
  * <InterstellarFuelSwitch.cfg> v1.0.0.0
  * <TweakScale.cfg> v1.0.0.0

### Documentation

* Update
  * [Readme.md]
  * [.version]
    * remove [KSP_VERSION_MAX]

### Status 1.0.99.0

* Issues
  * closes #2 - Release 1.0.9.9-adoption
  * closes #10 - Drop Tank Wrapper (DROP) 1.0.99.0-adoption `<Thank you Enceos>`
  * closes #11 - 1.0.99.0 Verify Legal Mumbo Jumbo
  * closes #12 - 1.0.99.0 Update Documentation
  * closes #13 - 1.0.99.0 Update Social Media

---

## Version 1.0.0.0-release - `<Archive>` edition

* 26 Dec 2016
* Released for Kerbal Space Program 1.3.0
* Last release by Enceos

### Status 1.0.0.0

* Issues
  * closes #3 - Adoption - social media
  * closes #4 - Adoption Legal MumboJumbo
  * closes #5 - Adoption Documentation
  * closes #6 - Adoption - GitHub
  * closes #7 - Previous Versions
  * closes #8 - 1.0.0.0 for Kerbal Space Program 1.3.0

---
