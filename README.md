# GTA-V Extracted Data Dumps
This is a collection of various GTA V data dumps mostly useful for modding &amp; scripting. All of these are auto generated and some are enhanced with data from my GTA V researches.
#### Join our GTA 5 Modding Discord server: https://discord.plebmasters.de
# My other projects
[![Durty Cloth Tool](https://i.imgur.com/ZINtfW8.png)](https://cloth.durty.dev/)
[![Pleb Masters Forge Logo](https://i.imgur.com/hotlSPf.png)](https://forge.plebmasters.de)
[![Durty Map Editor Logo](https://i.imgur.com/WsRJv3u.png)](https://durty.me)

## All data up2date as of GTA V update: **v3570.0 (Online 1.71) [DLC: mp2025_01_g9ec]**
---
### Please create an issue if you have any problems with the data, so I can improve my generator. You are also welcome to create issues for dumps you would like to see.
---
## **Data dumps overview**
- **IPLs** ([ipls.json](ipls.json)) **837** ipls in total (Usable with IPL natives)
- **Speech Voices** ([speeches.json](speeches.json)) **361368** speech voices with **361368** speeches in total (Usable with PLAY AMBIENT SPEECH natives)
- **Particle Effects** ([particleEffectsCompact.json](particleEffectsCompact.json)) **359** particle effect dictionaries & **2853** particle effects in total (Usable with START PARTICLE FX natives)
- **Ped Scenario names** ([scenariosCompact.json](scenariosCompact.json)) **247** scenarios in total (Usable with SCENARIO related natives)
- **Ped Scenario group names** ([scenarioGroupNames.json](scenarioGroupNames.json)) **235** scenario groups in total (Usable with SCENARIO_GROUP natives)
- **Animations** ([animDictsCompact.json](animDictsCompact.json)) **19568** animation dictionaries & **261067** animations in total (Usable with TASK PLAY ANIM native)
- **Movement Clipsets** ([movementClipsetsCompact.json](movementClipsetsCompact.json)) **557** movement clipsets in total (Usable with SET PED MOVEMENT CLIPSET native)
- **Walking Movement Clipsets** ([movementClipsetsWalkingCompact.json](movementClipsetsWalkingCompact.json)) **207** movement clipsets in total (Usable with SET PED MOVEMENT CLIPSET native)
- **(Vehicle Navigation) Nodes** ([nodes.zip](nodes.zip), contains JSON) **259** node cells with **67454** nodes in total (Mostly useful for vehicle navigation, see navigation meshes dump for ped navigation data)
- **(Offroad & Ped) Navigation Meshes** ([mega.nz MSGPACK download (.7z)](https://mega.nz/file/lLZWwJbR#T3Xm3nQKRTP1Z0XrkzgbbINo54d6wK2Na4Nj6tYfbXI), see [NAVIGATIONMESH.md](navigationmesh.md) for more info) **4915** navmeshes with **7374949** polygons in total (See navigationmesh.md for the messagepack model)
- **Ped Overlay Collections (Tattoos)** ([pedOverlayCollections.json](pedOverlayCollections.json)) **39** ped overlay collections with **3373** overlays in total (Usable tattos/badges with ped decoration native)
- **Timecycle Modifiers** ([timecycleModifiers.json](timecycleModifiers.json)) **1068** timecycle modifiers in total (Usable with TIMECYCLE MODIFIER natives)
- **Explosion Types names** ([explosionTypesCompact.json](explosionTypesCompact.json)) **88** explosion types in total (Usable with ADD EXPLOSION native)
- **Cam Shake Types names** ([camShakeTypesCompact.json](camShakeTypesCompact.json)) **23** cam shake types in total (Usable with SHAKE CAM & SHAKE GAMEPLAY cam natives)
- **Audio / Sound names & ref names** ([soundNames.json](soundNames.json)) **43428** audio names from a total of **43** unique audio refs (Usable with PLAY_SOUND natives)
- **Pickup Types names** ([pickupTypes.json](pickupTypes.json)) **175** pickup types in total (Usable with CREATE PICKUP natives)
- **Vehicle Mod Kits & Mods** ([vehicleModKits.json](vehicleModKits.json)) **587** vehicle mod kits with **35029** mods in total (Usable with SET_VEHICLE_MOD_KIT,SET_VEHICLE_LIVERY & SET_VEHICLE_MOD natives)
- **Vehicles** ([vehicles.json](vehicles.json)) **906** vehicle infos in total (Usable with VEHICLE natives)
- **AnimpostFX names** ([animPostFxNamesCompact.json](animPostFxNamesCompact.json)) **173** animpostfx names in total (Usable with ANIMPOSTFX natives)
- **Ped Component Variations** with cloth names and translations ([pedComponentVariations.json](pedComponentVariations.json)) **33967** component variations & **5985** ped props from a total of **96** ped component variation collections (Usable with COMPONENT VARIATION & PED PROP natives)
- **Ped Component Variations** without cloth names and translations ([pedComponentVariations_free.json](pedComponentVariations_free.json)) **33967** component variations & **5985** ped props from a total of **96** ped component variation collections (Usable with COMPONENT VARIATION & PED PROP natives)
- **Ped Apparel Restriction tag names** ([pedApparelRestrictionTags.json](pedApparelRestrictionTags.json)) **476** ped apparel restriction tags in total (Usable with PED RESTRICTION natives)
- **Waypoint recording names** ([waypointRecordings.json](waypointRecordings.json)) **831** waypoint recording infos in total (Usable with WAYPOINT RECORDING natives)
- **Garages** ([garages.json](garages.json)) **32** garage infos in total (Usable with GARAGE natives)
- **Vehicle Handlings** ([vehicleHandlings.json](vehicleHandlings.json)) **824** vehicle handling infos in total (Shared for all existing vehicles, see handling id in vehicles dump)
- **Zones** ([zones.json](zones.json)) **97** zone infos in total (Usable with some ZONE natives, contains all bounds coords for the zones)
- **Static Emitters** ([staticEmitters.json](staticEmitters.json)) **870** static emitter infos in total (Usable with STATIC_EMITTER natives)
- **Ambient Zones** ([ambientZones.json](ambientZones.json)) **1413** ambient zone infos in total (Usable with AMBIENT_ZONE natives)
- **MLO / Interiors** ([mloInteriors.json](mloInteriors.json)) **382** MLO interiors at 834 locations in total (Useful for modding, also contains in game locations of interiors)
- **Peds** ([peds.json](peds.json)) **1097** peds in total (Useful for various natives related to peds)
- **Vehicle Colors** ([vehicleColors.json](vehicleColors.json)) Contains all **Xenon Colors, Window Colors, PrimarySecondaryColors & Vehicle Plates** data (Useful for various natives related to vehicle)
- **Createable Objects** ([ObjectList.ini](ObjectList.ini) **20363** createable objects in total (The objects that can be created with most common loaded ytyps) (Useful for CREATE_OBJECT native)
- **Alarm Sound names** ([alarmSounds.json](alarmSounds.json)) **15** alarm sound names in total (Usable with ALARM natives)
- **Shaders** ([shaders.json](shaders.json)) **415** shaders in total
- **Train tracks** ([traintracks.json](traintracks.json)) **12** train tracks in total (Usable with TRACK natives)
- **Ped Damage Packs** ([pedDamagePacks.json](pedDamagePacks.json)) **72** ped damage packs in total (Usable with APPLY_​PED_​DAMAGE_​PACK native)
- **Music Event names** ([musicEventNames.json](musicEventNames.json)) **2781** music event names in total (Usable with MUSIC_EVENT natives)
- **Mission Audio Bank names** ([missionAudioBankNames.json](missionAudioBankNames.json)) **22** mission audio bank names in total (Usable with MISSION_AUDIO_BANK natives)
- **Ambient Audio Bank names** ([ambientAudioBankNames.json](ambientAudioBankNames.json)) **144** ambient audio bank names in total (Usable with AMBIENT_AUDIO_BANK natives)
- **Script Audio Bank names** ([scriptAudioBankNames.json](scriptAudioBankNames.json)) **617** script audio bank names in total (Usable with SCRIPT_AUDIO_BANK natives)
- **Mission Complete Audio names** ([missionCompleteAudioNames.json](missionCompleteAudioNames.json)) **4** mission complete audio names in total (Usable with PLAY_MISSION_COMPLETE_AUDIO native)
- **Police Report names** ([policeReportNames.json](policeReportNames.json)) **193** police report names in total (Usable with PLAY_​POLICE_​REPORT native)
- **Audio Scene names** ([audioSceneNames.json](audioSceneNames.json)) **3645** audio scene names in total (Usable with AUDIO_SCENE natives)
- **Cutscene names** ([cutsceneNames.json](cutsceneNames.json)) **792** cut scene names in total (Usable with CUT_ or CUTSCENE_ natives)
- **Weapons** ([weapons.json](weapons.json)) **183** weapons with **479** components in total (Usable with WEAPON natives)
- **Radio Stations** ([radioStations.json](radioStations.json)) **86** radio stations in total (Usable with RADIO_STATION natives)

## **Objects location dumps**
Object location dumps contain positions of various objects of a specific type, on the GTA V map (including all interiors / MLOs).
- **Vending Machines** ([worldVendingMachines.json](objectslocations/worldVendingMachines.json)) **345** in total
- **Bin/Dumpster/Recycle Bins** ([worldBinsDumpsters.json](objectslocations/worldBinsDumpsters.json) & [worldRecycleBins.json](objectslocations/worldRecycleBins.json)) **7761** bins/dumpsters in total & **133** recycle bins in total
- **Gas Pump Stations** ([worldGasPumps.json](objectslocations/worldGasPumps.json)) **157** in total
- **Jukeboxes** ([worldJukeboxes.json](objectslocations/worldJukeboxes.json)) **6** in total
- **Dart Discs** ([worldDartDiscs.json](objectslocations/worldDartDiscs.json)) **13** in total
- **Bus Stops** ([worldBusStops.json](objectslocations/worldBusStops.json) & [worldBusStopSigns.json](objectslocations/worldBusStopSigns.json)) **48** bus stops in total & **1** bus stop sign in total
- **Parknmeters** ([worldParknmeters.json](objectslocations/worldParknmeters.json)) **547** in total
- **Telescopes** ([worldTelescopes.json](objectslocations/worldTelescopes.json)) **116** in total
- **News Paper Dispenser** ([worldNewsPaperDispensers.json](objectslocations/worldNewsPaperDispensers.json)) **796** in total
- **ATMs** ([worldAtms.json](objectslocations/worldAtms.json)) **121** in total
- **Public Phones** ([worldPublicPhones.json](objectslocations/worldPublicPhones.json) & [worldExtraPhones.json](objectslocations/worldExtraPhones.json)) **432** public phones in total & **324** extra phones in total
- **Radio Towers** ([worldRadioTowers.json](objectslocations/worldRadioTowers.json)) **86** in total
- **Antennas** ([worldAntennas.json](objectslocations/worldAntennas.json)) **15** in total
- **Mobile Masts** ([worldMobileMasts.json](objectslocations/worldMobileMasts.json)) **8** in total
- **Air Masts** ([worldAirMasts.json](objectslocations/worldAirMasts.json)) **16** in total
- **Fire Hydrants, Hoses & Drisers** ([worldFireHydrantDriser.json](objectslocations/worldFireHydrantDriser.json)) **1458** in total
- **Post Boxes** ([worldPostBoxes.json](objectslocations/worldPostBoxes.json)) **195** in total
- **Letter Boxes** ([worldLetterBoxes.json](objectslocations/worldLetterBoxes.json)) **378** in total
- **Harvest fields** (orange trees, vine grapes, corns, salad, pumpkin, tomatoes) ([worldHarvestFields.json](objectslocations/worldHarvestFields.json)) **623** in total
- **Fruit stands** ([worldFruitStands.json](objectslocations/worldFruitStands.json)) **13** in total
- **Seats** (Benches, Chairs etc.) ([worldSeats.json](objectslocations/worldSeats.json)) **8059** in total
- **Food stands** (Hotdogs & Burger) ([worldFoodStands.json](objectslocations/worldFoodStands.json)) **23** in total
- **Container cabins** ([worldContainerCabins.json](objectslocations/worldContainerCabins.json)) **154** in total
- **Street lights** ([worldStreetLights.json](objectslocations/worldStreetLights.json)) **5873** in total
- **Traffic lights** ([worldTrafficLights.json](objectslocations/worldTrafficLights.json)) **1058** in total
- **Cctv cameras** ([worldCctvs.json](objectslocations/worldCctvs.json)) **1647** in total
- **Electricity boxes** ([worldElectricityBoxes.json](objectslocations/worldElectricityBoxes.json)) **1931** in total
- **Wrecked vehicles** ([worldWreckedCars.json](objectslocations/worldWreckedCars.json) & [worldWreckedBikes.json](objectslocations/worldWreckedBikes.json)) **489** wrecked cars in total & **150** wrecked bikes in total
- **Oil jacks** ([worldOilJacks.json](objectslocations/worldOilJacks.json)) **62** in total
- **Satellite dishes** ([worldSatDishes.json](objectslocations/worldSatDishes.json)) **834** in total

## **Assets**
- **Vehicle Manufacturer / Brand logos** ([vehicle-manufacturers-logos](assets/vehicle-manufacturers-logos))
- **Freemode ped parent faces** ([freemode-ped-parents](assets/freemode-ped-parents))

## **Misc dumps**
- **PS3 Builds info XML** ([ps3-builds.xml](ps3-builds.xml)) Early builds information dump from PS3 development versions, can hint some useful information
- **Vehicle driving style flags** ([drivingStyleFlagValues.json](drivingStyleFlagValues.json)) List of known & unknown GTA V driving style flag values
- **Vehicle handling flags** ([handlingFlagValues.json](handlingFlagValues.json)) List of known & unknown GTA V handling related flag values
- **Various game flags** ([flagValues.json](flagValues.json)) List of various known & unknown GTA V flag values for YTYP, YMAP & other data formats. Most known flags researched by the modding community!
- **Multiplayer ped clothes restriction tags** ([pedApparelRestrictionTags.json](pedApparelRestrictionTags.json)) Up2date collection of all available restriction tags for research purposes
- **Vehicle model manufacturers** ([vehiclesManufacturers.json](vehiclesManufacturers.json)) Up2date collection of all available vehicle model manufacturers
- **Vehicle model flags** ([vehiclesFlags.json](vehiclesFlags.json)) Up2date collection of all available vehicle flags for research purposes
- **Vehicle plate types** ([vehiclesPlateTypes.json](vehiclesPlateTypes.json)) Up2date collection of all available vehicle plate types
- **Vehicle rewards** ([vehiclesRewards.json](vehiclesRewards.json)) Up2date collection of all available vehicle rewards
- **Vehicle types** ([vehiclesTypes.json](vehiclesTypes.json)) Up2date collection of all available vehicle types
- **Vehicle wheel types** ([vehiclesWheelTypes.json](vehiclesWheelTypes.json)) Up2date collection of all available vehicle wheel types
- **Event Types enum** ([eEventType.txt](eEventType.txt)) Up2date dump of available & resolved event types enum