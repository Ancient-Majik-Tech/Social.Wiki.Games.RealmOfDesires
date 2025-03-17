[Page]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/README.md
[Page Proj Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Project.md
[Page Sys Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Project.md#system-layout
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Learning/LearningHome.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Changes/ChangesHome.md

[Sec Welcome]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#welcome
[Sec Details]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#system-details
[Sec Features]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#features

[Feat BaseGame]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#base-game-main-content-package-feature
[Feat NonRaces]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#skills-stats-and-attributes-feature
[Feat SexSkills]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#skilled-sexualization-feature
[Feat Human1]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#humand-tribes-of-the-plains-feature
[Feat Demons1]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#demon-warriors-of-the-9-gates-feature
[Feat Dragons1]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#dragons-of-the-westermountains-feature
[Feat Drakes1]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#drakes-of-the-lowlands-feature
[Feat Zombies1]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#zombiefolk-of-the-rotten-marshes-feature
[Feat LivingUndead1]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#living-undead-of-the-haunted-lands-feature
[Feat Succubi1]:https://github.com/Ancient-Majik-Tech/Social.Wiki.Games.RealmOfDesires/blob/main/Project/Systems/ContentPackagesSys.md#succubi-of-the-dreamscapes-feature

[Tag Feat ContentPack]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/FeatureTags_DL.md
[Tag Sys ContentHandle]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemTags_DL.md
[Tag Sys ContentPackages]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Design%20Layout/Project/SystemTags_DL.md

# Realms Tutorial Collections: "Realm of Desires" - Systems - Content Packages

## Site Index

- [Home][Page Home]
	- [Project][Page Proj Home]
		- [Systems][Page Sys Home]
			- Content Packages (You are here)
	- [Learning][Page Learn Home]
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Welcome][Sec Welcome]
	- [System Details][Sec Details]
	- [Features][Sec Features]

### Welcome

Welcome to the Content Packages System's documentation page. This page is dedicated to helping you understand the system and its features. However please note that for understanding how to use the project you should check out [Learning][Page Learn Home] for all the dedicated learning for the given project.

### System Details

- Details
	- Name: Content Packages 
	- SystemID: Desires.ContentPacks
	- IDPiece: ContentPacks
	- Version: V 0.1.0
	- Status: Active
	- Implimented Version: V D 0.0.4.0
	- Last Changed: V D 0.0.4.0
	- Tags
		- [Content Handler][Tag Sys ContentHandle]
		- [Content Packages][Tag Sys ContentPackages]

This system is designed to make development easier by including all data into easy to organize packages of data, this allows for more clear picture of pieces of content.

### Features

- Features
	- [Base Game Main Content Package][Feat BaseGame]
	- [Skills Stats and atrributes][Feat NonRaces]
	- [Skilled Sexualization][Feat SexSkills]
	- [Human tribes of the plains][Feat Human1]
	- [Demon Warriors of the 9 Gates][Feat Demons1]
	- [Dragons of the Westermountains][feat Dragons1]
	- [Drakes of the Lowlands][Feat Drakes1]
	- [Zombiefolk of the Rotten Marshes][Feat Zombies1]
	- [Living Undead of the Haunted Lands][Feat LivingUndead1]
	- [Succubi of the Dreamscapes][Feat Succubi1]


### Base Game Main Content Package Feature

This feature provides the basis of the base game. All Packages marked as a child of this package will be in the base game and will not require any DLC's to attain.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.BaseGame
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base >

### Skills Stats and Attributes Feature

This feature provides all the basic data definitions, these are used to provide the base functionality of the game providing all skills (except sexual), stats, attributes, work, buildings, rooms. All the core data for the simulation.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.DataDefs
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.Skills, Parent:Base >

### Skilled Sexualization Feature

This feature provides all the basic definitions for all sexual skills, jobs, buildings and more.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.SexSkills
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.Skills.Sex, Parent:Base >

### Human Tribtes of the Plains Feature

This feature will bring 8 human tribal based races from all across the realms.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.HumanTribes1
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.RacesPack.Human1, Parent:Base >

### Demon Warriors of the 9 Gates Feature

This feature will bring 6 Demons, 4 Devils and assorted demonic or dark aligned creatures to the world.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.Demon1
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.RacesPack.Demon1, Parent:Base >

### Dragons of the Westermountains Feature

This feature will bring a variety of dragon species to the realm.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.Dragons1
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.RacesPack.Dragons1, Parent:Base >

### Drakes of the lowlands Feature

This feature will bring other dragonkin based races for example: Drakes, Draconians. 

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.Drakes1
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.RacesPack.Drakes1, Parent:Base >

### Zombiefolk of the Rottent Marshes Feature

This feature will bring the zombiefolk, the risen dead from across the realms to the Realm of Desires.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.Zombie1
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.RacesPack.Zombie1, Parent:Base >

### Living Undead of the Haunted Lands Feature

This feature will bring the living undead to the Realm of Desire.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.LiveDead1
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.RacesPack.LiveDead1, Parent:Base >

### Succubi of the Dreamscapes Feature

This feature will introduce the races of the Succubi, this will include also incubi and races that serve them.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: ContentPacks.Succubi1
	- Impliment System Version: V 0.1.0
	- Last Change V 0.1.0
	- Tags
		- [ContentPack][Tag Feat ContentPack]< ID:Base.RacesPack.Succubi, Parent:Base >