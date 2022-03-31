# Changelog  
  
| modName    | NotSoSimpleConstruction (NSSC)                                       |
| ---------- | -------------------------------------------------------------------- |
| license    | GPLv3                                                                |
| author     | RealGecko, MrCarrot and zer0Kerbal                                   |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/191504-*)     |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/NotSoSimpleConstruction)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/NotSoSimpleConstruction) |
| spacedock  | (https://spacedock.info/mod/1078)                                    |
| ckan       | NotSoSimpleConstruction                                              |

## Version 1.0.99.1-prerelease - `<Pilot Surveys>`

* 23 Mar 2022
* Released for for KSP 1.12.3

### Configs

* [ExperienceTraits.cfg] v1.0.1.0
  * add (uncomment)
  * [ELSurveySkill]
    * add to Pilots
    * SimpleConstruction! not longer adds as of 4.0.99.5-prerelease
* fixes #40 - ExperienceTraits.cfg

### Status

* Issues/Requests
  * closed #41 - Not So SimpleConstruction! (NSSC!) 1.0.99.1-prerelease `<Pilot Surveys>`
  * closed #42 - 1.0.99.1 Verify Legal Mumbo Jumbo
  * closed #43 - 1.0.99.1 Update Documentation
  * closed #44 - 1.0.99.1 Update Social Media

---

## Version 1.0.99.0 - Somebody Order these Parts?

* 23 Mar 2022
* Released for for KSP 1.12.3

### Parts

* Part.cfg
  * updated all from Extraplanetary Launchpads
  * moved up one folder level and removed old folders
  * split [recyclebin.cfg] into [RecylceBinLarge.cfg] and [RecylceBinSmall.cfg]
  * move patches from files into [KerbalInventorySystem.cfg]
  * Added
    * [ElAuger]
    * [ElSmallAuger]
    * [ElTinyAuger]
    * [MicroPad.cfg]
    * [OrbitalDock.cfg]
* Assets
  * move models/textures to Assets/
  * update pointers to .dds
  * converted/renamed [model000.mbm] --> [Auguer000.png]
* added @thumbs
* added [DRAG_CUBES]
* added preliminary [ModuleCargoPart]

### Configs

* moved into /Configs/
  * [ExperienceTraits.cfg]
  * [SurveyStation.cfg] v1.0.0.2
  * [SurveyStationForAllCrewed.cfg] v1.0.0.2
* created [ghostparts.cfg] v1.0.0.0 so that will hide in editors (but not flight) SimpleConstructions! MicroPad

### Compatibility

* create [KerbalInventorySystem.cfg] v1.0.0.0
* rename [CCK.cfg] to [CommunityCategoryKit.cfg]

### docs/

* Create
  * docs/
    * [404.md]
    * [Attributions.md]
    * [ManualInstallation.md]
    * [LegalMumboJumbo.md]
    * [Localizations.md]
    * [resourceFlow.md]
    * [PartInvoice.md]
    * LegalMumboJumbo/
      * [FORUM-01.png]
      * [FORUM-02.png]
      * [License.md]
    * ReleaseNotes/
      * [1.0.0.0.md]
      * [1.0.1.0.md]
      * [1.0.2.0.md]
      * [1.0.2.2.md]
      * [1.0.99.0.md]

### Documentation

* Updated
  * [readme.md] v1.6.6.0
  * converted [changelog.cfg] to [changelog.md]
  * _releasenotes v1.3.1.1
  * update release version
  * update minimum KSP version

### Localization

* Localized all parts
  * using Elementary Launchpads localization tags
  * using Squad localization tags
* closes #11 - Localization - Master
* closes #12 - American English <us-en.cfg>
* closes #13 - Brazilian Portuguese <pt-br.cfg>
* closes #14 - German (Deutsch) <de.cfg>
* closes #15 - Spanish <es-es.cfg>
* closes #16 - French <fr-fr.cfg>
* closes #17 - Italian (Italiano) <it-it.cfg>
* closes #18 - Japanese <ja.cfg>
* closes #19 - Russian (Русский) <ru.cfg>
* closes #20 - Simplified Chinese <zh-cn.cfg>
* closes #21 - Mexican Spanish <es-mx.cfg>
* closes #22 - Korean <ko.cfg>
* closes #23 - Dutch (Nederlands) <nl-nl.cfg>
* closes #24 - Norwegian (Norsk) <no-no.cfg>
* closes #25 - Polish (Polski) <pl.cfg>
* closes #26 - Swedish (Svenska) <sw-sw.cfg>
* closes #27 - Taiwanese <zh-tw.cfg>
* closes #28 - Hawai'ian <ha.cfg>
* closes #29 - Part Localization

### Status

* Issues/Requests
  * closes #2 - Optional MM patch to add SurveyStation module to all manned command parts - contributed by   LEGIONBOSS
  * closes #5 - Update Not So SimpleConstruction! (NSSC) 1.0.99.0-prerelease <NAME>
  * closes #7 - Not So SimpleConstruction (NSSC) 1.0.99.0-prerelease <NAME>
  * closes #8 - 1.0.99.0 Verify Legal Mumbo Jumbo
  * closes #9 - 1.0.99.0 Update Documentation
  * closes #10 - 1.0.99.0 Social Media
  * closes #7 - Version 1.0.99.0-prerelease
  * closes #8 - 1.0.99.0-prerelease Legal MumboJumbo
  * closes #9 - 1.0.99.0-prerelease Update documentation
  * closes #10 - 1.0.99.0-prerelease Social Media
  * closes #16 - 1.0.99.0-prerelease Release
  * closes #30 - Create SurveyStation optional.txt
  * closes #32 - Repo update
  * closes #31 - RepoUpdate

---

## Version 1.0.2.2.1

* for Kerbal Space Program 1.8.1
* Released on 2020-02-10

* .version file hot fix
* #1 - Fix version file URL property - contributed by HebaruSan

## Version 1.0.2.2 - Brushing off the Construction Dust

* adopted for curation by zer0Kerbal

* Updated
  * large .png -> .dds
  * updated Readme.md
  * renamed GitHub repository to NotSoSimpleConstruction
  * modernization, polish, update pass on .cfg
  * merged in patches

* Added
  * moved changelog into separate file
  * Changelog.md -> Kerbal Changelog Changelog.cfg
  * added Disposable Pad (in GameData/ExtraplanetaryLaunchpads/parts)
  * added Orbital Dock (GameData/ExtraplanetaryLaunchpads/parts)
  * added LaunchPad2 (GameData/ExtraplanetaryLaunchpads/parts)
  * added Control Reference (GameData/ExtraplanetaryLaunchpads/parts)
  * added .version file
  * added license(s) file(s)

* Social Media
  * created Forum Thread
  * updated SpaceDock
  * updated CKAN/NetKAN

* Backend
  * automated deploy/release process

## Version 1.0.2

* 2017-03-13
* for Kerbal Space Program 1.3.1

* Removed K&K Planetary Cupola definition as KPBS now has extensive EL support
* Mallet MM patch (for KIS) tweaked

## Version 1.0.1

* Released on 2016-11-29
* for Kerbal Space Program 1.2.2

* Added support for KPBS, K&K Planetary Cupola is now survey station too

## Version 1.0.0

* for Kerbal Space Program 1.2.1
* Released on 2016-11-20

* Original release by RealGecko
