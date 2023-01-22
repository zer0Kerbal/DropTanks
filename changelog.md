# Changelog  
  
| modName    | Drop Tanks (DROP)                                                 |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-NC-SA-4.0                                                   |
| author     | Enceos and zer0Kerbal                                             |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209332-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/DropTanks)              |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/DropTanks)            |
| spacedock  | (https://spacedock.info/mod/1127)                                 |
| ckan       | DropTanks                                                         |

# Release Notes

# Version 1.1.1.0-release - `<help137: TweakScale>` edition

* Released
  * 21 Jan 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](http://github.com/zer0Kerbal)

### Summary 1.1.1.0

* Double True Trouble in drop-tank-sleeve
* <TweakScale.cfg> v1.0.1.0
  * Not all scaled
    * thank you to [help137](https://github.com/help137)
  * [defaultScale]
    * was 2.5 now is 1.25
* proper credit given to help137 for pointing out the red herring.
* closes #51 - [BUG] <drop-tank-sleeve-125.cfg>
* closes #52 - [Bug 🐞]: Tweakscale patch only affects long tank.

### Status 1.1.1.0

* Issues
  * closes #49 - Drop Tanks (DROP) 1.1.1.0-release `<help137: TweakScale>` edition
  * closes #50 - 1.1.1.0 Additional Tasks

---

## Version 1.1.0.0-release - `<help137: Wet Paint>` edition

* Released
  * 03 Dec 2022
  * for Kerbal Space Program 1.12.4
  * by [zer0Kerbal](http://github.com/zer0Kerbal)

### Summary 1.1.0.0

* KSP verison update
* Linting and Minor Updates
* seems the release delivery system was a tad behind, 1.0.99.0-adoption should have been available months ago.
* Red Herring
  * thank you to [help137](https://github.com/help137)
* closes #46 - [Bug 🐞]: Directory for the model and texture files is incorrect in all 4 .cfg files

### Status 1.1.0.0

* Issues
  * closes #42 - Drop Tank Wrapper (DROP) 1.1.0.0-release `<Wet Paint>`
  * closes #43 - 1.1.0.0-release Verify Legal Mumbo Jumbo
  * closes #44 - 1.1.0.0-release Update Documentation
  * closes #45 - 1.1.0.0-release Update Social Media
  * updates #14 - Localization - Master

---

## Version 1.0.99.0-adoption - `<Thank you Enceos>` edition

* Released
  * 03 Dec 2023
  * for Kerbal Space Program 1.12.3
  * by [zer0Kerbal](http://github.com/zer0Kerbal)

### Summary 1.0.99.0

* Adoption by zer0Kerbal
* Localization
  * English
  * Dutch thank you to @renejant (*bedankt!*)

### Parts 1.0.99.0

* Update
  * [drop-tank-*] v2.0.0.0
    * [tags] = #autoLOC_500531 // fueltank ?lfo liquid oxidizer propellant rocket
  * Add
    * [maxTemp] was 3200 now 2000
    * [stagingIcon] = DECOUPLER_HOR
    * [breakingForce] = 50
    * [breakingTorque] = 50
    * [DRAG_CUBE]
    * thumbnail

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
  * [DropTanks.cfg] v1.0.0.0
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
  * <InterstellarFuelSwitch.cfg> v1.0.1.0
    * missing drop-tank-bracelet-125 patch since, well, the mess below:
      * quantities, masses, and cost are totally messed up
      * don't have enough aspirin to take this one down
      * don't have a clue what Xe and EE (battery) should be
        * e.g. Cap tank is:
          * Structural
          * 65 LF
          * 45 LF + 55 OX
          * 40 MP
          * 45 LF + 55 OX + 30 MP
          * 1800 Xe
          * 1500 Xe + 20 MP
        * but should be?
          * Structural
          * 120 LF
          * 54 LF + 66 OX
          * 180 MP
          * 45 LF + 55 OX + 30 MP
          * 1800 Xe
          * 1500 Xe + 20 MP
  * <TweakScale.cfg> v1.0.0.0
    * all parts have a [bulkheadProfiles] = size1 but defaultScale of 2.5
      * didn't fix it because it's a bug in the original tweakscale.cfg

### Documentation

* Update
  * [Readme.md] v1.6.9.4
  * [_releaseNotes.md] v1.3.2.1
  * [.version]
    * remove [KSP_VERSION_MAX]

### Status 1.0.99.0

* Issues
  * closes #10 - Drop Tanks (DROP) 1.0.99.0-adoption `<Thank you Enceos>`
  * closes #11 - 1.0.99.0 Verify Legal Mumbo Jumbo
  * closes #12 - 1.0.99.0 Update Documentation
  * closes #13 - 1.0.99.0 Update Social Media
  * closes #2 - Release 1.0.9.9-adoption

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
