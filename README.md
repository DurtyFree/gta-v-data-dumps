# GTA-V Extracted Data Dumps
This is a collection of various GTA V data dumps mostly useful for modding &amp; scripting. All of these are auto generated and some are enhanced with data from my GTA V researches.
#### Join our GTA 5 Modding Discord server: https://discord.gg/hgSutAU
# My other projects
[![Durty Cloth Tool](https://i.imgur.com/ZINtfW8.png)](https://cloth.durty.dev/)
[![Pleb Masters Forge Logo](https://i.imgur.com/hotlSPf.png)](https://forge.plebmasters.de)
[![Durty Map Editor Logo](https://i.imgur.com/WsRJv3u.png)](https://durty.me)

## All data up2date as of GTA V update: **v2545 (Online 1.58) [DLC: mpsecurity]**
---
### Please create an issue if you have any problems with the data, so I can improve my generator. You are also welcome to create issues for dumps you would like to see.
---
## **Data dumps overview**
- **IPLs** ([ipls.json](ipls.json)) **1184** ipls in total (Usable with IPL natives)
- **Speech Voices** ([speeches.json](speeches.json)) **1083** speech voices with **150055** speeches in total (Usable with PLAY AMBIENT SPEECH natives)
- **Particle Effects** ([particleEffectsCompact.json](particleEffectsCompact.json)) **313** particle effect dictionaries & **2514** particle effects in total (Usable with START PARTICLE FX natives)
- **Ped Scenario names** ([scenariosCompact.json](scenariosCompact.json)) **245** scenarios in total (Usable with SCENARIO related natives)
- **Ped Scenario group names** ([scenarioGroupNames.json](scenarioGroupNames.json)) **235** scenario groups in total (Usable with SCENARIO_GROUP natives)
- **Animations** ([animDictsCompact.json](animDictsCompact.json)) **18269** animation dictionaries & **222978** animations in total (Usable with TASK PLAY ANIM native)
- **Movement Clipsets** ([movementClipsetsCompact.json](movementClipsetsCompact.json)) **557** movement clipsets in total (Usable with SET PED MOVEMENT CLIPSET native)
- **Walking Movement Clipsets** ([movementClipsetsWalkingCompact.json](movementClipsetsWalkingCompact.json)) **207** movement clipsets in total (Usable with SET PED MOVEMENT CLIPSET native)
- **(Vehicle Navigation) Nodes** ([nodes.zip](nodes.zip), contains JSON) **259** node cells with **67454** nodes in total (Mostly useful for vehicle navigation, see navigation meshes dump for ped navigation data)
- **(Offroad & Ped) Navigation Meshes** ([mega.nz MSGPACK download](https://mega.nz/file/oc5UyDqY#-PRv5u6ve0yr3uxHDsQOul5ik98wYUMEmDeF5u-38wE), see [NAVIGATIONMESH.md](navigationmesh.md) for more info) **4810** navmeshes with **7121736** polygons in total (See navigationmesh.md for the messagepack model)
- **Ped Overlay Collections (Tattoos)** ([pedOverlayCollections.json](pedOverlayCollections.json)) **33** ped overlay collections with **3043** overlays in total (Usable tattos/badges with ped decoration native)
- **Timecycle Modifiers** ([timecycleModifiers.json](timecycleModifiers.json)) **2895** timecycle modifiers in total (Usable with TIMECYCLE MODIFIER natives)
- **Explosion Types names** ([explosionTypesCompact.json](explosionTypesCompact.json)) **79** explosion types in total (Usable with ADD EXPLOSION native)
- **Cam Shake Types names** ([camShakeTypesCompact.json](camShakeTypesCompact.json)) **21** cam shake types in total (Usable with SHAKE CAM & SHAKE GAMEPLAY cam natives)
- **Audio / Sound names & ref names** ([soundNames.json](soundNames.json)) **2100** audio names from a total of **62** unique audio refs (Usable with PLAY_SOUND natives)
- **Pickup Types names** ([pickupTypes.json](pickupTypes.json)) **160** pickup types in total (Usable with CREATE PICKUP natives)
- **Vehicle Mod Kits & Mods** ([vehicleModKits.json](vehicleModKits.json)) **457** vehicle mod kits with **22465** mods in total (Usable with SET_VEHICLE_MOD_KIT,SET_VEHICLE_LIVERY & SET_VEHICLE_MOD natives)
- **Vehicles** ([vehicles.json](vehicles.json)) **758** vehicle infos in total (Usable with VEHICLE natives)
- **AnimpostFX names** ([animPostFxNamesCompact.json](animPostFxNamesCompact.json)) **155** animpostfx names in total (Usable with ANIMPOSTFX natives)
- **REMOVED** **Ped Component Variations** ([pedComponentVariations.json](pedComponentVariations.json)) **28044** component variations & **4523** ped props from a total of **80** ped component variation collections (Usable with COMPONENT VARIATION & PED PROP natives)
- **Ped Apparel Restriction tag names** ([animPostFxNamesCompact.json](animPostFxNamesCompact.json)) **438** ped apparel restriction tags in total (Usable with PED RESTRICTION natives)
- **Waypoint recording names** ([waypointRecordings.json](waypointRecordings.json)) **807** waypoint recording infos in total (Usable with WAYPOINT RECORDING natives)
- **Garages** ([garages.json](garages.json)) **32** garage infos in total (Usable with GARAGE natives)
- **Vehicle Handlings** ([vehicleHandlings.json](vehicleHandlings.json)) **679** vehicle handling infos in total (Shared for all existing vehicles, see handling id in vehicles dump)
- **Zones** ([zones.json](zones.json)) **97** zone infos in total (Usable with some ZONE natives, contains all bounds coords for the zones)
- **Static Emitters** ([staticEmitters.json](staticEmitters.json)) **846** static emitter infos in total (Usable with STATIC_EMITTER natives)
- **Ambient Zones** ([ambientZones.json](ambientZones.json)) **1339** ambient zone infos in total (Usable with AMBIENT_ZONE natives)
- **MLO / Interiors** ([mloInteriors.json](mloInteriors.json)) **351** MLO interiors at 799 locations in total (Useful for modding, also contains in game locations of interiors)
- **Peds** ([peds.json](peds.json)) **983** peds in total (Useful for various natives related to peds)
- **Vehicle Colors** ([vehicleColors.json](vehicleColors.json)) Contains all **Xenon Colors, Window Colors, PrimarySecondaryColors & Vehicle Plates** data (Useful for various natives related to vehicle)
- **Createable Objects** ([ObjectList.ini](ObjectList.ini) **18456** createable objects in total (The objects that can be created with most common loaded ytyps) (Useful for CREATE_OBJECT native)
- **Alarm Sound names** ([alarmSounds.json](alarmSounds.json)) **60** alarm sound names in total (Usable with ALARM natives)
- **Shaders** ([shaders.json](shaders.json)) **415** shaders in total
- **Train tracks** ([traintracks.json](traintracks.json)) **12** train tracks in total (Usable with TRACK natives)
- **Ped Damage Packs** ([pedDamagePacks.json](pedDamagePacks.json)) **72** ped damage packs in total (Usable with APPLY_​PED_​DAMAGE_​PACK native)
- **Music Event names** ([musicEventNames.json](musicEventNames.json)) **1567** music event names in total (Usable with MUSIC_EVENT natives)
- **Mission Audio Bank names** ([missionAudioBankNames.json](missionAudioBankNames.json)) **22** mission audio bank names in total (Usable with MISSION_AUDIO_BANK natives)
- **Ambient Audio Bank names** ([ambientAudioBankNames.json](ambientAudioBankNames.json)) **144** ambient audio bank names in total (Usable with AMBIENT_AUDIO_BANK natives)
- **Script Audio Bank names** ([scriptAudioBankNames.json](scriptAudioBankNames.json)) **562** script audio bank names in total (Usable with SCRIPT_AUDIO_BANK natives)
- **Mission Complete Audio names** ([missionCompleteAudioNames.json](missionCompleteAudioNames.json)) **4** mission complete audio names in total (Usable with PLAY_MISSION_COMPLETE_AUDIO native)
- **Police Report names** ([policeReportNames.json](policeReportNames.json)) **50** police report names in total (Usable with PLAY_​POLICE_​REPORT native)
- **Audio Scene names** ([audioSceneNames.json](audioSceneNames.json)) **1129** audio scene names in total (Usable with AUDIO_SCENE natives)
- **Cutscene names** ([cutsceneNames.json](cutsceneNames.json)) **739** cut scene names in total (Usable with CUT_ or CUTSCENE_ natives)
- **Weapons** ([weapons.json](weapons.json)) **165** weapons with **418** components in total (Usable with WEAPON natives)
- **Radio Stations** ([radioStations.json](radioStations.json)) **79** radio stations in total (Usable with RADIO_STATION natives)

## **Objects location dumps**
Object location dumps contain positions of various objects of a specific type, on the GTA V map (including all interiors / MLOs).
- **Vending Machines** ([worldVendingMachines.json](objectslocations/worldVendingMachines.json)) **329** in total
- **Bin/Dumpster/Recycle Bins** ([worldBinsDumpsters.json](objectslocations/worldBinsDumpsters.json) & [worldRecycleBins.json](objectslocations/worldRecycleBins.json)) **7754** bins/dumpsters in total & **127** recycle bins in total
- **Gas Pump Stations** ([worldGasPumps.json](objectslocations/worldGasPumps.json)) **157** in total
- **Jukeboxes** ([worldJukeboxes.json](objectslocations/worldJukeboxes.json)) **6** in total
- **Dart Discs** ([worldDartDiscs.json](objectslocations/worldDartDiscs.json)) **12** in total
- **Bus Stops** ([worldBusStops.json](objectslocations/worldBusStops.json) & [worldBusStopSigns.json](objectslocations/worldBusStopSigns.json)) **48** bus stops in total & **1** bus stop sign in total
- **Parknmeters** ([worldParknmeters.json](objectslocations/worldParknmeters.json)) **547** in total
- **Telescopes** ([worldTelescopes.json](objectslocations/worldTelescopes.json)) **116** in total
- **News Paper Dispenser** ([worldNewsPaperDispensers.json](objectslocations/worldNewsPaperDispensers.json)) **796** in total
- **ATMs** ([worldAtms.json](objectslocations/worldAtms.json)) **121** in total
- **Public Phones** ([worldPublicPhones.json](objectslocations/worldPublicPhones.json) & [worldExtraPhones.json](objectslocations/worldExtraPhones.json)) **432** public phones in total & **311** extra phones in total
- **Radio Towers** ([worldRadioTowers.json](objectslocations/worldRadioTowers.json)) **86** in total
- **Antennas** ([worldAntennas.json](objectslocations/worldAntennas.json)) **4** in total
- **Mobile Masts** ([worldMobileMasts.json](objectslocations/worldMobileMasts.json)) **8** in total
- **Air Masts** ([worldAirMasts.json](objectslocations/worldAirMasts.json)) **16** in total
- **Fire Hydrants, Hoses & Drisers** ([worldFireHydrantDriser.json](objectslocations/worldFireHydrantDriser.json)) **1430** in total
- **Post Boxes** ([worldPostBoxes.json](objectslocations/worldPostBoxes.json)) **195** in total
- **Letter Boxes** ([worldLetterBoxes.json](objectslocations/worldLetterBoxes.json)) **378** in total
- **Harvest fields** (orange trees, vine grapes, corns, salad, pumpkin, tomatoes) ([worldHarvestFields.json](objectslocations/worldHarvestFields.json)) **623** in total
- **Fruit stands** ([worldFruitStands.json](objectslocations/worldFruitStands.json)) **13** in total
- **Seats** (Benches, Chairs etc.) ([worldSeats.json](objectslocations/worldSeats.json)) **7994** in total
- **Food stands** (Hotdogs & Burger) ([worldFoodStands.json](objectslocations/worldFoodStands.json)) **23** in total
- **Container cabins** ([worldContainerCabins.json](objectslocations/worldContainerCabins.json)) **154** in total
- **Street lights** ([worldStreetLights.json](objectslocations/worldStreetLights.json)) **5873** in total
- **Traffic lights** ([worldTrafficLights.json](objectslocations/worldTrafficLights.json)) **1058** in total
- **Cctv cameras** ([worldCctvs.json](objectslocations/worldCctvs.json)) **1609** in total
- **Electricity boxes** ([worldElectricityBoxes.json](objectslocations/worldElectricityBoxes.json)) **1904** in total
- **Wrecked vehicles** ([worldWreckedCars.json](objectslocations/worldWreckedCars.json) & [worldWreckedBikes.json](objectslocations/worldWreckedBikes.json)) **484** wrecked cars in total & **148** wrecked bikes in total
- **Oil jacks** ([worldOilJacks.json](objectslocations/worldOilJacks.json)) **62** in total