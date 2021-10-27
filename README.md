# GTA-V Extracted Data Dumps
This is a collection of various GTA V data dumps mostly useful for modding &amp; scripting. All of these are auto generated and some are enhanced with data from my GTA V researches.
#### Join our GTA 5 Modding Discord server: https://discord.gg/hgSutAU
# Useful projects
If you are in search for an easy way to browse those GTA V data, try **Pleb Masters: Forge**.
[![Pleb Masters Forge Logo](https://i.imgur.com/hotlSPf.png)](https://forge.plebmasters.de)
[![Durty Map Editor Logo](https://i.imgur.com/WsRJv3u.png)](https://durty.me)

## All data up2date as of GTA V update: **v2372 (Online 1.57) [DLC: mptuner]**
---
### Please create an issue if you have any problems with the data, so I can improve my generator. You are also welcome to create issues for dumps you would like to see.
---
## **Data dumps overview**
- **IPLs** (ipls.json) **1156** ipls in total (Usable with IPL natives)
- **Speech Voices** (speeches.json) **1083** speech voices with **150055** speeches in total (Usable with PLAY AMBIENT SPEECH natives)
- **Particle Effects** (particleEffectsCompact.json) **311** particle effect dictionaries & **2472** particle effects in total (Usable with START PARTICLE FX natives)
- **Ped Scenario names** (scenariosCompact.json) **245** scenarios in total (Usable with SCENARIO related natives)
- **Ped Scenario group names** (scenarioGroupNames.json) **235** scenario groups in total (Usable with SCENARIO_GROUP natives)
- **Animations** (animDictsCompact.json) **17545** animation dictionaries & **198968** animations in total (Usable with TASK PLAY ANIM native)
- **Movement Clipsets** (movementClipsetsCompact.json) **557** movement clipsets in total (Usable with SET PED MOVEMENT CLIPSET native)
- **Walking Movement Clipsets** (movementClipsetsWalkingCompact.json) **207** movement clipsets in total (Usable with SET PED MOVEMENT CLIPSET native)
- **(Vehicle Navigation) Nodes** (nodes.zip, contains JSON) **259** node cells with **67454** nodes in total (Mostly useful for vehicle navigation, see navigation meshes dump for ped navigation data)
- **(Offroad & Ped) Navigation Meshes** (MSGPACK Download: https://mega.nz/file/oc5UyDqY#-PRv5u6ve0yr3uxHDsQOul5ik98wYUMEmDeF5u-38wE) **4801** navmeshes with **7115440** polygons in total (See navigationmesh.md for the messagepack model)
- **Ped Overlay Collections (Tattoos)** (pedOverlayCollections.json) **32** ped overlay collections with **2981** overlays in total (Usable tattos/badges with ped decoration native)
- **Timecycle Modifiers** (timecycleModifiers.json) **2871** timecycle modifiers in total (Usable with TIMECYCLE MODIFIER natives)
- **Explosion Types names** (explosionTypesCompact.json) **78** explosion types in total (Usable with ADD EXPLOSION native)
- **Cam Shake Types names** (camShakeTypesCompact.json) **21** cam shake types in total (Usable with SHAKE CAM & SHAKE GAMEPLAY cam natives)
- **Audio / Sound names & ref names** (soundNames.json) **2077** audio names from a total of **62** unique audio refs (Usable with PLAY_SOUND natives)
- **Pickup Types names** (pickupTypes.json) **154** pickup types in total (Usable with CREATE PICKUP natives)
- **Vehicle Mod Kits & Mods** (vehicleModKits.json) **442** vehicle mod kits with **21358** mods in total (Usable with SET_VEHICLE_MOD_KIT,SET_VEHICLE_LIVERY & SET_VEHICLE_MOD natives)
- **Vehicles** (vehicles.json) **741** vehicle infos in total (Usable with VEHICLE natives)
- **AnimpostFX names** (animPostFxNamesCompact.json) **155** animpostfx names in total (Usable with ANIMPOSTFX natives)
- **REMOVED** **Ped Component Variations** (pedComponentVariations.json) **27257** component variations & **4127** ped props from a total of **78** ped component variation collections (Usable with COMPONENT VARIATION & PED PROP natives)
- **Ped Apparel Restriction tag names** (animPostFxNamesCompact.json) **415** ped apparel restriction tags in total (Usable with PED RESTRICTION natives)
- **Waypoint recording names** (waypointRecordings.json) **807** waypoint recording infos in total (Usable with WAYPOINT RECORDING natives)
- **Garages** (garages.json) **32** garage infos in total (Usable with GARAGE natives)
- **Vehicle Handlings** (vehicleHandlings.json) **663** vehicle handling infos in total (Shared for all existing vehicles, see handling id in vehicles dump)
- **Zones** (zones.json) **97** zone infos in total (Usable with some ZONE natives, contains all bounds coords for the zones)
- **Static Emitters** (staticEmitters.json) **820** static emitter infos in total (Usable with STATIC_EMITTER natives)
- **Ambient Zones** (ambientZones.json) **1314** ambient zone infos in total (Usable with AMBIENT_ZONE natives)
- **MLO / Interiors** (mloInteriors.json) **346** MLO interiors at 789 locations in total (Useful for modding, also contains in game locations of interiors)
- **Peds** (peds.json) **934** peds in total (Useful for various natives related to peds)
- **Vehicle Colors** (vehicleColors.json) Contains all **Xenon Colors, Window Colors, PrimarySecondaryColors & Vehicle Plates** data (Useful for various natives related to vehicle)
- **Createable Objects** (ObjectList.ini) **17255** createable objects in total (The objects that can be created with most common loaded ytyps) (Useful for CREATE_OBJECT native)
- **Alarm Sound names** (alarmSounds.json) **60** alarm sound names in total (Usable with ALARM natives)
- **Shaders** (shaders.json) **417** shaders in total
- **Train tracks** (traintracks.json) **12** train tracks in total (Usable with TRACK natives)
- **Ped Damage Packs** (pedDamagePacks.json) **72** ped damage packs in total (Usable with APPLY_​PED_​DAMAGE_​PACK native)
- **Music Event names** (musicEventNames.json) **1549** music event names in total (Usable with MUSIC_EVENT natives)
- **Mission Audio Bank names** (missionAudioBankNames.json) **22** mission audio bank names in total (Usable with MISSION_AUDIO_BANK natives)
- **Ambient Audio Bank names** (ambientAudioBankNames.json) **144** ambient audio bank names in total (Usable with AMBIENT_AUDIO_BANK natives)
- **Script Audio Bank names** (scriptAudioBankNames.json) **553** script audio bank names in total (Usable with SCRIPT_AUDIO_BANK natives)
- **Mission Complete Audio names** (missionCompleteAudioNames.json) **4** mission complete audio names in total (Usable with PLAY_MISSION_COMPLETE_AUDIO native)
- **Police Report names** (policeReportNames.json) **50** police report names in total (Usable with PLAY_​POLICE_​REPORT native)
- **Audio Scene names** (audioSceneNames.json) **1116** audio scene names in total (Usable with AUDIO_SCENE natives)

## **Objects location dumps**
Object location dumps contain positions of various objects of a specific type, on the GTA V map (including all interiors / MLOs).
- **Vending Machines** (worldVendingMachines.json) **329** in total
- **Bin/Dumpster/Recycle Bins** (worldBinsDumpsters.json & worldRecycleBins.json) **7751** bins/dumpsters in total & **127** recycle bins in total
- **Gas Pump Stations** (worldGasPumps.json) **157** in total
- **Jukeboxes** (worldJukeboxes.json) **6** in total
- **Dart Discs** (worldDartDiscs.json) **12** in total
- **Bus Stops** (worldBusStops.json & worldBusStopSigns.json) **48** bus stops in total & **1** bus stop sign in total
- **Parknmeters** (worldParknmeters.json) **547** in total
- **Telescopes** (worldTelescopes.json) **106** in total
- **News Paper Dispenser** (worldNewsPaperDispensers.json) **796** in total
- **ATMs** (worldAtms.json) **121** in total
- **Public Phones** (worldPublicPhones.json & worldExtraPhones.json) **432** public phones in total & **310** extra phones in total
- **Radio Towers** (worldRadioTowers.json) **86** in total
- **Antennas** (worldAntennas.json) **4** in total
- **Mobile Masts** (worldMobileMasts.json) **8** in total
- **Air Masts** (worldAirMasts.json) **16** in total
- **Fire Hydrants, Hoses & Drisers** (worldFireHydrantDriser.json) **1430** in total
- **Post Boxes** (worldPostBoxes.json) **195** in total
- **Letter Boxes** (worldLetterBoxes.json) **378** in total
- **Harvest fields** (orange trees, vine grapes, corns, salad, pumpkin, tomatoes) (worldHarvestFields.json) **623** in total
- **Fruit stands** (worldFruitStands.json) **13** in total
- **Seats** (Benches, Chairs etc.) (worldSeats.json) **7952** in total
- **Food stands** (Hotdogs & Burger) (worldFoodStands.json) **23** in total
- **Container cabins** (worldContainerCabins.json) **154** in total
- **Street lights** (worldStreetLights.json) **5873** in total
- **Traffic lights** (worldTrafficLights.json) **1058** in total
- **Cctv cameras** (worldCctvs.json) **1606** in total
- **Electricity boxes** (worldElectricityBoxes.json) **1904** in total
- **Wrecked vehicles** (worldWreckedCars.json & worldWreckedBikes.json) **484** wrecked cars in total & **148** wrecked bikes in total