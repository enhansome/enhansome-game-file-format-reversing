# 🎮 Awesome Game File Format Reversing with stars

[Awesome](https://github.com/sindresorhus/awesome) ⭐ 497,514 | 🐛 102 | 📅 2026-08-18
[License: CC0-1.0](LICENSE)
[Website](https://velocityra.github.io/awesome-game-file-format-reversing/)

> A collection of documentation, code, tools, and resources for reverse engineering and working with video game file formats.

<!-- site:skip-start -->

> \[!TIP]
>
> ### 🌐 [Browse this list as a website](https://velocityra.github.io/awesome-game-file-format-reversing/)
>
> *(recommended for easier navigation)*

<!-- site:skip-end -->

## 📖 About

Video games store their assets in specialized, usually undocumented formats for models, textures, animations, audio, archives, scripts, and level data.

This list is for developers and modders working with such formats. It provides tools and knowledge to understand, extract, convert, and work with them across many games and engines.

**Contributions are welcome!** Submit pull requests to add new tools, documentation, or corrections.

## 🗺️ How to Use This List

* **Newcomers**: Start with [Learning Resources & Tutorials](#-learning-resources--tutorials) and [General Tools](#️-general-tools)
* **Looking for a specific game**: Use Ctrl+F or check the [Contents](#-contents) for studio/game-specific sections
* **Working with an engine**: See [Engines](#️-engines) and [Middleware & SDKs](#-middleware--sdks)
* **Need help**: Join the communities in [Forums & Communities](#forums--communities) and [Discord Servers](#discord-servers)

<!-- START doctoc -->

## 📑 Contents

* [👥 Communities & Wikis](#-communities--wikis)
  * [Forums & Communities](#forums--communities)
  * [Discord Servers](#discord-servers)
  * [Knowledge Bases & Format Databases](#knowledge-bases--format-databases)
  * [Platform & SDK Documentation](#platform--sdk-documentation)
  * [Game-Specific Wikis](#game-specific-wikis)
  * [📚 Learning Resources & Tutorials](#-learning-resources--tutorials)
    * [🎥 Video Tutorials](#-video-tutorials)
  * [Asset Databases](#asset-databases)
* [🛠️ General Tools](#️-general-tools)
  * [🎨 Asset Viewers & Converters](#-asset-viewers--converters)
    * [3D Models & Viewers](#3d-models--viewers)
    * [Textures & Images](#textures--images)
    * [Sprites, Tiles & Tilemaps](#sprites-tiles--tilemaps)
    * [Fonts](#fonts)
    * [DCC Tool Plugins (Blender / 3ds Max / Godot)](#dcc-tool-plugins-blender--3ds-max--godot)
  * [📦 Archive Extractors](#-archive-extractors)
  * [🔊 Audio Tools](#-audio-tools)
  * [🌐 Translation & Localization](#-translation--localization)
  * [🔍 Hex Editors](#-hex-editors)
    * [Scripts & Templates](#scripts--templates)
  * [🔬 Format Analysis & Reverse Engineering](#-format-analysis--reverse-engineering)
    * [Binary Templates & Format Descriptions](#binary-templates--format-descriptions)
    * [Disassemblers, Decompilers & Analysis Frameworks](#disassemblers-decompilers--analysis-frameworks)
    * [IDA / Hex-Rays Plugins](#ida--hex-rays-plugins)
    * [Managed & Bytecode Decompilers (.NET / Java / Script)](#managed--bytecode-decompilers-net--java--script)
    * [Decompilation Project Toolchains](#decompilation-project-toolchains)
    * [Static Recompilation](#static-recompilation)
    * [Ghidra & IDA Platform Loaders](#ghidra--ida-platform-loaders)
    * [Binary Visualization & Diffing](#binary-visualization--diffing)
    * [Hooking, Memory & Runtime Tools](#hooking-memory--runtime-tools)
    * [Console-specific RE (PlayStation / Xbox)](#console-specific-re-playstation--xbox)
  * [💻 Development Libraries](#-development-libraries)
  * [📂 Script Collections & Multi-Game Tools](#-script-collections--multi-game-tools)
    * [Multi-Game Viewers & Explorers](#multi-game-viewers--explorers)
    * [Cross-Game Libraries & Extractors](#cross-game-libraries--extractors)
    * [Noesis / 3ds Max / Format Script Packs](#noesis--3ds-max--format-script-packs)
    * [ROM/Save Extraction, Detection & Modding](#romsave-extraction-detection--modding)
    * [Emulators & TAS Tools](#emulators--tas-tools)
    * [Franchise & Studio Toolkits](#franchise--studio-toolkits)
* [⚙️ Engines](#️-engines)
  * [GameMaker](#gamemaker)
  * [Source (Valve)](#source-valve)
    * [Engines, Libraries & Full Toolkits](#engines-libraries--full-toolkits)
    * [Maps & BSP](#maps--bsp)
    * [Models (MDL/SMD)](#models-mdlsmd)
    * [Textures & Materials (VTF/VMT)](#textures--materials-vtfvmt)
    * [Packages & Filesystem (VPK/GCF/GMA/WAD)](#packages--filesystem-vpkgcfgmawad)
    * [KeyValues, VDF & Choreography](#keyvalues-vdf--choreography)
    * [DCC Plugins (Blender / 3ds Max / Maya / XSI)](#dcc-plugins-blender--3ds-max--maya--xsi)
    * [Legacy Tools & Downloads (ModDB)](#legacy-tools--downloads-moddb)
  * [Unity](#unity)
  * [Unreal Engine](#unreal-engine)
    * [Full Engine Reimplementations & Source Ports](#full-engine-reimplementations--source-ports)
    * [Asset Parsers & Libraries](#asset-parsers--libraries)
    * [Explorers, Viewers & PAK/IoStore Tools](#explorers-viewers--pakiostore-tools)
    * [SDK & Structure Dumpers](#sdk--structure-dumpers)
    * [Blueprint, UnrealScript & Shaders](#blueprint-unrealscript--shaders)
    * [Maps, Saves, Localization & Mappings](#maps-saves-localization--mappings)
    * [Modding Frameworks & Toolkits](#modding-frameworks--toolkits)
    * [DCC Plugins & ActorX (Blender / 3ds Max)](#dcc-plugins--actorx-blender--3ds-max)
    * [Legacy Tools & Downloads (ModDB)](#legacy-tools--downloads-moddb-1)
  * [CryEngine](#cryengine)
  * [Dagor Engine](#dagor-engine)
  * [Fox Engine](#fox-engine)
  * [Hedgehog Engine](#hedgehog-engine)
  * [Northlight Engine](#northlight-engine)
  * [Pragma Engine](#pragma-engine)
  * [Build Engine](#build-engine)
  * [Cobra Engine](#cobra-engine)
  * [3DSTATE](#3dstate)
  * [AtiSushi Engine](#atisushi-engine)
  * [Genie Engine](#genie-engine)
  * [Bruns Engine](#bruns-engine)
  * [RPG Maker](#rpg-maker)
  * [Ren'Py](#renpy)
  * [BGI (Buriko General Interpreter)](#bgi-buriko-general-interpreter)
  * [RealLive](#reallive)
  * [Kirikiri](#kirikiri)
  * [Glulx VM (Interactive Fiction)](#glulx-vm-interactive-fiction)
  * [Z-machine VM (Interactive Fiction)](#z-machine-vm-interactive-fiction)
  * [Magnetic Scrolls VM (Interactive Fiction)](#magnetic-scrolls-vm-interactive-fiction)
  * [AGT (Adventure Game Toolkit)](#agt-adventure-game-toolkit)
  * [Level 9 VM (Interactive Fiction)](#level-9-vm-interactive-fiction)
  * [TADS VM (Interactive Fiction)](#tads-vm-interactive-fiction)
  * [ADRIFT VM (Interactive Fiction)](#adrift-vm-interactive-fiction)
  * [Alan VM (Interactive Fiction)](#alan-vm-interactive-fiction)
  * [Twine (Interactive Fiction)](#twine-interactive-fiction)
  * [Yarn Spinner (Dialogue Middleware)](#yarn-spinner-dialogue-middleware)
  * [Rawthrills G7 Engine](#rawthrills-g7-engine)
  * [OpenSpace](#openspace)
  * [LithTech Engine](#lithtech-engine)
  * [Adventure Game Studio (AGS)](#adventure-game-studio-ags)
  * [BioWare Aurora Engine](#bioware-aurora-engine)
  * [Clickteam Fusion](#clickteam-fusion)
  * [Dark Engine](#dark-engine)
  * [SCI Engine (Sierra)](#sci-engine-sierra)
  * [SCUMM](#scumm)
  * [UTAGE](#utage)
  * [Adobe Flash (SWF)](#adobe-flash-swf)
  * [Godot](#godot)
  * [HaxeFlixel](#haxeflixel)
* [🔧 Middleware & SDKs](#-middleware--sdks)
  * [Fast3d/F3dex (N64)](#fast3df3dex-n64)
  * [Havok](#havok)
  * [JSYSTEM (GameCube/Wii)](#jsystem-gamecubewii)
  * [SEAD (Nintendo EAD/EPD Engine)](#sead-nintendo-eadepd-engine)
  * [Mii (RFL/FFL Face Library)](#mii-rflffl-face-library)
  * [Katana Engine (Koei Tecmo)](#katana-engine-koei-tecmo)
  * [M3G (Mobile 3D Graphics API)](#m3g-mobile-3d-graphics-api)
  * [NETLizard (J2ME Game Engine)](#netlizard-j2me-game-engine)
  * [MikuMikuDance](#mikumikudance)
  * [RenderWare](#renderware)
  * [CRI](#cri)
  * [PSB (Persistent Serialized Binary)](#psb-persistent-serialized-binary)
  * [XNA](#xna)
  * [Sappy (GBA Audio)](#sappy-gba-audio)
  * [RAD Game Tools](#rad-game-tools)
  * [Nintendo SDKs & Hardware](#nintendo-sdks--hardware)
    * [Switch](#switch)
    * [iQue Player](#ique-player)
    * [Wii U](#wii-u)
    * [3DS](#3ds)
    * [GameCube & Wii](#gamecube--wii)
    * [Nintendo DS / DSi](#nintendo-ds--dsi)
    * [Nintendo 64](#nintendo-64)
    * [SNES / NES](#snes--nes)
    * [Game Boy / GBA](#game-boy--gba)
    * [Cross-Platform Formats & Archives](#cross-platform-formats--archives)
  * [Sharp X68000 SDKs & Hardware](#sharp-x68000-sdks--hardware)
  * [PlayStation SDKs & Hardware](#playstation-sdks--hardware)
  * [Xbox SDKs & Hardware](#xbox-sdks--hardware)
  * [FMOD](#fmod)
  * [SpeedTree](#speedtree)
  * [Wwise](#wwise)
  * [Prism3D](#prism3d)
* [Game & Studio Tools](#game--studio-tools)
  * [11 bit studios (Frostpunk)](#11-bit-studios-frostpunk)
  * [1C Company / Best Way](#1c-company--best-way)
    * [Men of War](#men-of-war)
    * [Royal Quest Online](#royal-quest-online)
    * [Adventures of Captain Blood](#adventures-of-captain-blood)
  * [2K Czech / Illusion Softworks](#2k-czech--illusion-softworks)
  * [2K Games / Firaxis Games](#2k-games--firaxis-games)
    * [WWE 2K](#wwe-2k)
  * [3D Realms](#3d-realms)
    * [Duke Nukem 3D](#duke-nukem-3d)
    * [Duke Nukem: Manhattan Project](#duke-nukem-manhattan-project)
    * [Duke Nukem: Zero Hour](#duke-nukem-zero-hour)
    * [Duke Nukem Forever (2001)](#duke-nukem-forever-2001)
    * [Duke Nukem Forever (2011)](#duke-nukem-forever-2011)
    * [Shadow Warrior](#shadow-warrior)
    * [The Outforce](#the-outforce)
  * [3DO / New World Computing](#3do--new-world-computing)
    * [Might and Magic: World of Xeen](#might-and-magic-world-of-xeen)
    * [Heroes of Might and Magic II](#heroes-of-might-and-magic-ii)
    * [Heroes of Might and Magic III](#heroes-of-might-and-magic-iii)
    * [Heroes of Might and Magic IV](#heroes-of-might-and-magic-iv)
  * [4A Games](#4a-games)
    * [Metro](#metro)
  * [5th Cell](#5th-cell)
  * [8monkey Labs](#8monkey-labs)
  * [Acclaim Entertainment (Turok)](#acclaim-entertainment-turok)
  * [Accolade (Eradicator)](#accolade-eradicator)
  * [Acornsoft](#acornsoft)
    * [Elite](#elite)
  * [Akella](#akella)
  * [Action Forms (Chasm: The Rift)](#action-forms-chasm-the-rift)
  * [Activision / Infinity Ward / Treyarch](#activision--infinity-ward--treyarch)
    * [Call of Duty](#call-of-duty)
    * [Call to Power II](#call-to-power-ii)
    * [Tony Hawk's Pro Skater](#tony-hawks-pro-skater)
    * [Ghostbusters](#ghostbusters)
    * [A Series of Unfortunate Events](#a-series-of-unfortunate-events)
    * [Spider-Man (Neversoft)](#spider-man-neversoft)
    * [Wolfenstein (2009)](#wolfenstein-2009)
    * [PSX Activision Games](#psx-activision-games)
  * [Adeline Software International](#adeline-software-international)
    * [Little Big Adventure 1](#little-big-adventure-1)
    * [Little Big Adventure 2](#little-big-adventure-2)
  * [ADvertainment Software (Quiver)](#advertainment-software-quiver)
  * [Aether Studios (Rivals of Aether)](#aether-studios-rivals-of-aether)
  * [AKI Corporation](#aki-corporation)
  * [Amber Studio](#amber-studio)
  * [Analgesic Productions](#analgesic-productions)
    * [Anodyne](#anodyne)
    * [Anodyne 2](#anodyne-2)
    * [Even the Ocean](#even-the-ocean)
  * [Angel Matrix (Neon White)](#angel-matrix-neon-white)
  * [Angel Studios / Rockstar San Diego](#angel-studios--rockstar-san-diego)
  * [Ankama Games](#ankama-games)
    * [Wakfu](#wakfu)
  * [Anthony Bongers](#anthony-bongers)
  * [Ape, Inc](#ape-inc)
  * [Arc System Works](#arc-system-works)
    * [Under Night In-Birth](#under-night-in-birth)
    * [True Remembrance](#true-remembrance)
  * [Apogee Software](#apogee-software)
    * [Crystal Caves](#crystal-caves)
    * [Duke Nukem II](#duke-nukem-ii)
    * [Blake Stone (Aliens of Gold, Planet Strike)](#blake-stone-aliens-of-gold-planet-strike)
  * [Argonaut Games](#argonaut-games)
  * [Arkane Studios](#arkane-studios)
  * [Armature Studio (Batman: Arkham Origins Blackgate)](#armature-studio-batman-arkham-origins-blackgate)
  * [Arrowhead Game Studios (Helldivers 2)](#arrowhead-game-studios-helldivers-2)
  * [Assembly Line (Supaplex)](#assembly-line-supaplex)
  * [Asmik Ace Entertainment (LSD: Dream Emulator)](#asmik-ace-entertainment-lsd-dream-emulator)
  * [Asobo Studio](#asobo-studio)
  * [Atlus](#atlus)
  * [Attack on Titan](#attack-on-titan)
  * [Aurogon (Gujian)](#aurogon-gujian)
  * [Avalanche Studios (Generation Zero)](#avalanche-studios-generation-zero)
  * [Bandai Namco](#bandai-namco)
    * [THE iDOLM@STER Cinderella Girls Starlight Stage](#the-idolmster-cinderella-girls-starlight-stage)
    * [Dragon Ball](#dragon-ball)
    * [Tales Of](#tales-of)
  * [Battlestate Games (Escape from Tarkov)](#battlestate-games-escape-from-tarkov)
  * [BeamNG GmbH (BeamNG.drive)](#beamng-gmbh-beamngdrive)
  * [Bethesda](#bethesda)
  * [BioWare](#bioware)
    * [Mass Effect](#mass-effect)
    * [Dragon Age: Origins](#dragon-age-origins)
  * [Bitmap Brothers](#bitmap-brothers)
    * [The Chaos Engine](#the-chaos-engine)
    * [Speedball 2](#speedball-2)
  * [Black Element Software (Alpha Prime)](#black-element-software-alpha-prime)
  * [Blizzard Entertainment](#blizzard-entertainment)
    * [World of Warcraft](#world-of-warcraft)
    * [StarCraft (original) & Brood War](#starcraft-original--brood-war)
    * [StarCraft II & Heroes of the Storm](#starcraft-ii--heroes-of-the-storm)
    * [Overwatch](#overwatch)
    * [Warcraft III](#warcraft-iii)
    * [Diablo](#diablo)
    * [Hearthstone](#hearthstone)
  * [Bob Hays (Hypercycles)](#bob-hays-hypercycles)
  * [Bohemia Interactive](#bohemia-interactive)
  * [Blueside (Kingdom Under Fire II)](#blueside-kingdom-under-fire-ii)
  * [Boss Game Studios (Top Gear Rally)](#boss-game-studios-top-gear-rally)
  * [Brno Transit](#brno-transit)
  * [Bugbear Entertainment (FlatOut)](#bugbear-entertainment-flatout)
  * [Bugbear Entertainment (Team6 Engine - FlatOut 3)](#bugbear-entertainment-team6-engine---flatout-3)
  * [Bugs Bunny: Lost in Time](#bugs-bunny-lost-in-time)
  * [Bugbear Entertainment (Wreckfest)](#bugbear-entertainment-wreckfest)
  * [Bullfrog Productions](#bullfrog-productions)
    * [PowerMonger](#powermonger)
    * [Dungeon Keeper](#dungeon-keeper)
    * [Syndicate Wars](#syndicate-wars)
    * [Populous: The Beginning](#populous-the-beginning)
    * [Hi-Octane](#hi-octane)
    * [Creation](#creation)
    * [Theme Park](#theme-park)
    * [Quake III: Revolution](#quake-iii-revolution)
  * [Burut CT](#burut-ct)
  * [Capcom](#capcom)
    * [RE Engine](#re-engine)
    * [MT Framework](#mt-framework)
    * [Resident Evil](#resident-evil)
    * [Monster Hunter](#monster-hunter)
    * [Devil May Cry](#devil-may-cry)
    * [Street Fighter](#street-fighter)
    * [CP System (Arcade)](#cp-system-arcade)
    * [Ultimate Marvel vs Capcom 3](#ultimate-marvel-vs-capcom-3)
    * [Mega Man](#mega-man)
    * [Gregory Horror Show](#gregory-horror-show)
    * [Gotcha Force](#gotcha-force)
    * [Phoenix Wright: Ace Attorney](#phoenix-wright-ace-attorney)
    * [Dragon's Dogma](#dragons-dogma)
    * [Dragon's Dogma 2](#dragons-dogma-2)
    * [Haunting Ground](#haunting-ground)
  * [CCP Games (EVE Online)](#ccp-games-eve-online)
  * [CCR (RF Online)](#ccr-rf-online)
  * [CD Projekt Red](#cd-projekt-red)
    * [The Witcher 3 / REDEngine 3](#the-witcher-3--redengine-3)
    * [The Witcher](#the-witcher)
    * [Cyberpunk 2077 / REDEngine 4](#cyberpunk-2077--redengine-4)
  * [Century Interactive](#century-interactive)
    * [Bermuda Syndrome](#bermuda-syndrome)
  * [Charybdis (Machines: Wired for War)](#charybdis-machines-wired-for-war)
  * [Chris Sawyer (Transport Tycoon)](#chris-sawyer-transport-tycoon)
  * [Chronic Logic (Gish)](#chronic-logic-gish)
  * [Chuck Sommerville (Chip's Challenge)](#chuck-sommerville-chips-challenge)
  * [CIRCUS (Da Capo)](#circus-da-capo)
  * [Climax Studios (Rocket Knight)](#climax-studios-rocket-knight)
  * [Cloud Imperium Games (Star Citizen)](#cloud-imperium-games-star-citizen)
  * [Clover Studio (Okami)](#clover-studio-okami)
  * [Creat Studio](#creat-studio)
  * [Compile Heart (Hyperdimension Neptunia)](#compile-heart-hyperdimension-neptunia)
  * [Conic Games](#conic-games)
    * [Exponential Idle](#exponential-idle)
  * [Constantine](#constantine)
  * [Contrail (Legend of Legaia)](#contrail-legend-of-legaia)
  * [Codemasters](#codemasters)
  * [CR-Space (Martial Heroes)](#cr-space-martial-heroes)
  * [Croteam](#croteam)
  * [Crows Crows Crows](#crows-crows-crows)
  * [Cryo Interactive](#cryo-interactive)
    * [Dune (1992)](#dune-1992)
  * [Crystal Dynamics / Eidos Interactive](#crystal-dynamics--eidos-interactive)
  * [Custom Order Maid 3D2](#custom-order-maid-3d2)
  * [Cyan Worlds](#cyan-worlds)
  * [CyberConnect2](#cyberconnect2)
  * [CyberFlix](#cyberflix)
  * [CyberStep (CosmicBreak)](#cyberstep-cosmicbreak)
  * [Cygames (Granblue Fantasy Relink)](#cygames-granblue-fantasy-relink)
  * [Cygnus Studios (Raptor: Call of the Shadows)](#cygnus-studios-raptor-call-of-the-shadows)
  * [D3 Publisher](#d3-publisher)
    * [Earth Defense Force](#earth-defense-force)
  * [Datamost (The Bilestoad)](#datamost-the-bilestoad)
  * [Disney Interactive](#disney-interactive)
    * [Toontown Online](#toontown-online)
    * [Club Penguin](#club-penguin)
  * [Deck13 Interactive (Lords of the Fallen)](#deck13-interactive-lords-of-the-fallen)
  * [Delphine Software](#delphine-software)
    * [Another World](#another-world)
    * [Fade to Black](#fade-to-black)
    * [Flashback](#flashback)
    * [Igor](#igor)
  * [DeLyric Games (Target)](#delyric-games-target)
  * [Demiurge Studios](#demiurge-studios)
  * [Di Gi Charat](#di-gi-charat)
  * [Digital Extremes](#digital-extremes)
    * [The Darkness II](#the-darkness-ii)
  * [Digital Anvil (Freelancer)](#digital-anvil-freelancer)
  * [Digital Illusions (SkyRoads)](#digital-illusions-skyroads)
  * [Distinctive Software (Stunts)](#distinctive-software-stunts)
  * [Dogbyte Games](#dogbyte-games)
  * [Doki Denki Studio (Piglet's Big Game)](#doki-denki-studio-piglets-big-game)
  * [DOKA Studios](#doka-studios)
  * [Double Fine (Psychonauts, Costume Quest)](#double-fine-psychonauts-costume-quest)
  * [Dynamix / Sierra](#dynamix--sierra)
    * [Tribes Series](#tribes-series)
  * [Edelweiss](#edelweiss)
    * [Sakuna: Of Rice and Ruin](#sakuna-of-rice-and-ruin)
  * [Ecstatica](#ecstatica)
  * [Eden Games (Test Drive Unlimited 2)](#eden-games-test-drive-unlimited-2)
  * [EgoSoft (X4)](#egosoft-x4)
  * [Eighting (Naruto: Gekitō Ninja Taisen!)](#eighting-naruto-gekitō-ninja-taisen)
  * [Electronic Arts](#electronic-arts)
    * [Frostbite](#frostbite)
      * [Battlefield Series](#battlefield-series)
      * [Star Wars: Battlefront](#star-wars-battlefront)
    * [RenderWare](#renderware-1)
      * [Criterion Games](#criterion-games)
    * [EAGL / Black Box / Other](#eagl--black-box--other)
      * [Need for Speed Series](#need-for-speed-series)
    * [SAGE / W3D](#sage--w3d)
      * [Command & Conquer Series](#command--conquer-series)
    * [SSX](#ssx)
    * [Fountain of Dreams](#fountain-of-dreams)
    * [General Tools](#general-tools)
  * [Enhance Games (Rez)](#enhance-games-rez)
  * [Epic Games](#epic-games)
    * [Ken's Labyrinth](#kens-labyrinth)
    * [Radix: Beyond the Void](#radix-beyond-the-void)
    * [Jazz Jackrabbit 2](#jazz-jackrabbit-2)
    * [Fortnite](#fortnite)
    * [Unreal](#unreal)
    * [Unreal Tournament](#unreal-tournament)
  * [Experience Inc. (Ray Gigant)](#experience-inc-ray-gigant)
  * [Eurocom](#eurocom)
  * [Eutechnyx (Ford Racing)](#eutechnyx-ford-racing)
  * [Factor 5](#factor-5)
    * [Turrican](#turrican)
  * [Falcom (Ys)](#falcom-ys)
  * [FarSight Studios (The Pinball Arcade)](#farsight-studios-the-pinball-arcade)
  * [Fireglow Games](#fireglow-games)
    * [Sudden Strike](#sudden-strike)
    * [Sudden Strike: Resource War](#sudden-strike-resource-war)
    * [Sudden Strike II](#sudden-strike-ii)
    * [Tools](#tools)
  * [Firefly Studios](#firefly-studios)
    * [Stronghold](#stronghold)
  * [Fatshark](#fatshark)
    * [Warhammer: End Times - Vermintide](#warhammer-end-times---vermintide)
  * [Firestarter (Hover Ace)](#firestarter-hover-ace)
  * [Free Radical Design (TimeSplitters)](#free-radical-design-timesplitters)
  * [Frictional Games (Amnesia, Soma)](#frictional-games-amnesia-soma)
  * [FromSoftware](#fromsoftware)
    * [Documentation & Wikis](#documentation--wikis)
    * [Format Libraries & Templates](#format-libraries--templates)
    * [Archives, Unpackers & Encryption](#archives-unpackers--encryption)
    * [Models, Animation & FLVER](#models-animation--flver)
    * [Maps & Level Editors](#maps--level-editors)
    * [Scripting, FX, Params & Runtime Modding](#scripting-fx-params--runtime-modding)
  * [Frontier Developments (Dog's Life)](#frontier-developments-dogs-life)
  * [Funcom](#funcom)
    * [Dreamfall: The Longest Journey](#dreamfall-the-longest-journey)
    * [Secret World Legends](#secret-world-legends)
  * [Gamania Digital Entertainment (Bright Shadow)](#gamania-digital-entertainment-bright-shadow)
  * [Game Freak](#game-freak)
    * [Gen I & II](#gen-i--ii)
    * [Gen III](#gen-iii)
    * [Gen VI](#gen-vi)
    * [Gen V](#gen-v)
    * [Switch (Gen VIII+)](#switch-gen-viii)
  * [Gameloft](#gameloft)
  * [GarageGames](#garagegames)
    * [Marble Blast](#marble-blast)
  * [Gearbox Software](#gearbox-software)
    * [MechWarrior 4](#mechwarrior-4)
    * [Borderlands](#borderlands)
  * [Genius Sonority](#genius-sonority)
  * [Genki](#genki)
  * [Giant Network (King of Kings 3)](#giant-network-king-of-kings-3)
  * [GlassesCatGames (Devil Slayer - Raksasi)](#glassescatgames-devil-slayer---raksasi)
  * [Glowmade (King of Meat)](#glowmade-king-of-meat)
  * [FSZHS Zhengshi (封神召唤师)](#fszhs-zhengshi-封神召唤师)
  * [画皮世界 (Painted Skin World)](#画皮世界-painted-skin-world)
  * [Good-Feel (Yoshi's Wooly World)](#good-feel-yoshis-wooly-world)
  * [Grasshopper Manufacture (No More Heroes, Killer7)](#grasshopper-manufacture-no-more-heroes-killer7)
    * [Sine Mora](#sine-mora)
  * [Gravity (Ragnarok Online)](#gravity-ragnarok-online)
  * [Gray Design Associates](#gray-design-associates)
  * [Gremlin Interactive](#gremlin-interactive)
    * [Actua Soccer](#actua-soccer)
    * [Hogs of War](#hogs-of-war)
    * [Realms of the Haunting](#realms-of-the-haunting)
    * [Strike Series (Desert Strike, Jungle Strike, Urban Strike)](#strike-series-desert-strike-jungle-strike-urban-strike)
  * [Grezzo](#grezzo)
  * [GSC Game World](#gsc-game-world)
    * [S.T.A.L.K.E.R](#stalker)
  * [Guard Crush Games / Lizardcube (Streets of Rage 4)](#guard-crush-games--lizardcube-streets-of-rage-4)
  * [Gumi (Brave Frontier)](#gumi-brave-frontier)
  * [Gust (Koei Tecmo)](#gust-koei-tecmo)
  * [H2O Entertainment (Aidyn Chronicles)](#h2o-entertainment-aidyn-chronicles)
  * [Haggard Games](#haggard-games)
  * [HAL Laboratory](#hal-laboratory)
  * [Harmonix](#harmonix)
  * [07th Expansion (Higurashi)](#07th-expansion-higurashi)
  * [Hasbro Interactive (Frogger)](#hasbro-interactive-frogger)
  * [Haydee](#haydee)
  * [Heavy Gear](#heavy-gear)
  * [Heavy Iron Studios](#heavy-iron-studios)
  * [Headfirst Productions](#headfirst-productions)
    * [Call of Cthulhu: Dark Corners of the Earth](#call-of-cthulhu-dark-corners-of-the-earth)
  * [Her Interactive (Nancy Drew)](#her-interactive-nancy-drew)
  * [HeroForge (HeroForge)](#heroforge-heroforge)
  * [HoYoverse](#hoyoverse)
    * [Honkai: Star Rail](#honkai-star-rail)
  * [HROT](#hrot)
  * [Honey Parade / Marvelous Entertainment](#honey-parade--marvelous-entertainment)
  * [Hudson Soft](#hudson-soft)
    * [Faxanadu](#faxanadu)
  * [Hulabee Entertainment](#hulabee-entertainment)
  * [Hydravision Entertainment](#hydravision-entertainment)
    * [ObsCure](#obscure)
  * [Human Entertainment (Tadaima Yuusha Boshuuchuu Okawari)](#human-entertainment-tadaima-yuusha-boshuuchuu-okawari)
  * [Human Head Studios](#human-head-studios)
    * [Prey](#prey)
  * [id Software](#id-software)
    * [Commander Keen](#commander-keen)
    * [Catacomb 3-D & Adventure Series](#catacomb-3-d--adventure-series)
    * [Wolfenstein 3D & Spear of Destiny](#wolfenstein-3d--spear-of-destiny)
    * [Doom Engine (id Tech 1) & Ports](#doom-engine-id-tech-1--ports)
    * [Quake & Wolfenstein Engines (id Tech 2/3)](#quake--wolfenstein-engines-id-tech-23)
    * [Modern DOOM (id Tech 4 / 6 / 7)](#modern-doom-id-tech-4--6--7)
    * [Legacy Tools & Downloads (ModDB)](#legacy-tools--downloads-moddb-2)
    * [Rise of the Triad](#rise-of-the-triad)
  * [Illusion](#illusion)
  * [Incredible Technologies](#incredible-technologies)
  * [iNiS](#inis)
  * [Infinite Fall (Night in the Woods)](#infinite-fall-night-in-the-woods)
  * [Infinity Ltd. (The Battle of Olympus)](#infinity-ltd-the-battle-of-olympus)
  * [Inkle](#inkle)
  * [Inland Productions](#inland-productions)
    * [WCW Nitro](#wcw-nitro)
    * [WCW/nWo Thunder](#wcwnwo-thunder)
  * [Innerloop Studios](#innerloop-studios)
  * [Intelligent Systems](#intelligent-systems)
    * [Fire Emblem: Three Houses](#fire-emblem-three-houses)
    * [Paper Mario 64](#paper-mario-64)
    * [Paper Mario: TTYD / Super Paper Mario](#paper-mario-ttyd--super-paper-mario)
    * [Paper Mario: The Origami King](#paper-mario-the-origami-king)
  * [Interactive Studios](#interactive-studios)
    * [Glover](#glover)
  * [Interplay / Black Isle Studios](#interplay--black-isle-studios)
    * [Fallout](#fallout)
    * [Fallout 2](#fallout-2)
    * [Dragon Wars](#dragon-wars)
  * [IO Interactive](#io-interactive)
    * [007 First Light](#007-first-light)
  * [Ion Storm](#ion-storm)
    * [Anachronox](#anachronox)
    * [Daikatana](#daikatana)
    * [Deus Ex](#deus-ex)
  * [ITE Media (Hugo)](#ite-media-hugo)
  * [Ironclad Games / Stardock](#ironclad-games--stardock)
    * [Sins of a Solar Empire](#sins-of-a-solar-empire)
  * [Iron Gate AB](#iron-gate-ab)
  * [Iron Lore Entertainment](#iron-lore-entertainment)
    * [Titan Quest](#titan-quest)
  * [Jagex](#jagex)
  * [Jellyvision](#jellyvision)
  * [JiangHu Studio (Wushu Chronicles 2)](#jianghu-studio-wushu-chronicles-2)
  * [Jordan Mechner (Prince of Persia)](#jordan-mechner-prince-of-persia)
  * [Juice Games (Juiced)](#juice-games-juiced)
  * [Julegame](#julegame)
    * [League of Angels](#league-of-angels)
  * [Jupiter](#jupiter)
  * [Keen Games (Enshrouded, Portal Knights)](#keen-games-enshrouded-portal-knights)
  * [Keen Software House](#keen-software-house)
  * [KingsIsle Entertainment (Wizard101)](#kingsisle-entertainment-wizard101)
  * [Koei Tecmo](#koei-tecmo)
    * [Fatal Frame](#fatal-frame)
    * [Nioh](#nioh)
  * [Konami](#konami)
    * [Metal Gear Solid](#metal-gear-solid)
    * [Silent Hill](#silent-hill)
    * [Castlevania](#castlevania)
    * [Elebits](#elebits)
    * [Enthusia Professional Racing](#enthusia-professional-racing)
    * [Love Plus](#love-plus)
    * [Zone of the Enders](#zone-of-the-enders)
  * [Kuju London](#kuju-london)
  * [Kuro Games](#kuro-games)
    * [Wuthering Waves](#wuthering-waves)
  * [Larian Studios](#larian-studios)
    * [Divinity: Original Sin 2](#divinity-original-sin-2)
    * [Divine Divinity / Beyond Divinity](#divine-divinity--beyond-divinity)
  * [Level-5](#level-5)
  * [Lionhead Studios (Black & White)](#lionhead-studios-black--white)
  * [Lobotomy Software (PowerSlave / Duke Nukem 3D Saturn)](#lobotomy-software-powerslave--duke-nukem-3d-saturn)
  * [Lucky Chicken Games (Casper: Spirit Dimensions)](#lucky-chicken-games-casper-spirit-dimensions)
  * [Looking Glass Studios](#looking-glass-studios)
    * [System Shock](#system-shock)
    * [System Shock 2](#system-shock-2)
    * [Thief](#thief)
    * [Ultima Underworld](#ultima-underworld)
  * [Looney Tunes: Carrot Crazy](#looney-tunes-carrot-crazy)
  * [LucasArts](#lucasarts)
  * [Macrospace](#macrospace)
    * [Fatal Force: Earth Assault](#fatal-force-earth-assault)
  * [Marigul (Tamagotchi Town)](#marigul-tamagotchi-town)
  * [Massive Development](#massive-development)
    * [Archimedean Dynasty](#archimedean-dynasty)
  * [Massive Entertainment](#massive-entertainment)
    * [AquaNox](#aquanox)
    * [World in Conflict](#world-in-conflict)
  * [Mattel Electronics (Intellivision)](#mattel-electronics-intellivision)
  * [Maxis](#maxis)
    * [3D Pinball for Windows](#3d-pinball-for-windows)
    * [SimCity](#simcity)
    * [SimCity 2000](#simcity-2000)
    * [SimCity BuildIt](#simcity-buildit)
    * [The Sims 1](#the-sims-1)
    * [The Sims 2](#the-sims-2)
  * [Mega Crit (Slay the Spire)](#mega-crit-slay-the-spire)
  * [Media.Vision](#mediavision)
  * [Mercedes-Benz Truck Racing](#mercedes-benz-truck-racing)
  * [Archetype Interactive (Meridian 59)](#archetype-interactive-meridian-59)
  * [Metropolis Software](#metropolis-software)
    * [Gorky 17](#gorky-17)
  * [Microids](#microids)
    * [Still Life 2](#still-life-2)
  * [MicroProse](#microprose)
    * [X-COM (UFO Defense / Terror from the Deep)](#x-com-ufo-defense--terror-from-the-deep)
    * [XCOM Apocalypse](#xcom-apocalypse)
  * [Microsoft Studios / Bungie / Turn 10](#microsoft-studios--bungie--turn-10)
    * [Halo](#halo)
    * [Destiny](#destiny)
    * [Marathon (1994)](#marathon-1994)
    * [Gears of War](#gears-of-war)
    * [Forza](#forza)
    * [Age of Empires](#age-of-empires)
    * [Microsoft Plus! for Windows XP](#microsoft-plus-for-windows-xp)
    * [3D Movie Maker](#3d-movie-maker)
  * [Midway](#midway)
    * [Area 51](#area-51)
    * [Gauntlet](#gauntlet)
    * [NARC](#narc)
    * [NBA Hangtime](#nba-hangtime)
    * [NBA Jam](#nba-jam)
    * [NFL Blitz](#nfl-blitz)
    * [San Francisco Rush: The Rock](#san-francisco-rush-the-rock)
  * [Mindscape](#mindscape)
  * [Mind Shear Software (In Pursuit of Greed)](#mind-shear-software-in-pursuit-of-greed)
  * [MindStorm Software](#mindstorm-software)
  * [MIST Games (Stella Maiden: Girls of the Stars)](#mist-games-stella-maiden-girls-of-the-stars)
  * [MiST Land / GFI](#mist-land--gfi)
  * [Mithis Entertainment](#mithis-entertainment)
    * [Nexus: The Jupiter Incident](#nexus-the-jupiter-incident)
  * [Mobius Digital (Outer Wilds)](#mobius-digital-outer-wilds)
  * [Mojang Studios](#mojang-studios)
  * [Monolith Productions](#monolith-productions)
    * [F.E.A.R](#fear)
    * [Trespasser](#trespasser)
    * [Blood](#blood)
    * [Blood 2: The Chosen](#blood-2-the-chosen)
    * [No One Lives Forever](#no-one-lives-forever)
    * [Shogo: Mobile Armor Division](#shogo-mobile-armor-division)
    * [Captain Claw](#captain-claw)
  * [Monolith Soft](#monolith-soft)
    * [Xenoblade Chronicles](#xenoblade-chronicles)
  * [Moonsprout Games (Bug Fables)](#moonsprout-games-bug-fables)
  * [Moorhuhn](#moorhuhn)
  * [Mucky Foot Productions](#mucky-foot-productions)
  * [NanaOn-Sha](#nanaon-sha)
  * [Mythic Entertainment (Dark Age of Camelot)](#mythic-entertainment-dark-age-of-camelot)
  * [Natsume (Harvest Moon)](#natsume-harvest-moon)
  * [NetDevil (Dungeon Runners)](#netdevil-dungeon-runners)
  * [NetEase Games](#netease-games)
    * [Beyond the World](#beyond-the-world)
    * [LifeAfter](#lifeafter)
  * [Nexon](#nexon)
    * [MapleStory](#maplestory)
    * [MapleStory 2](#maplestory-2)
  * [Nival](#nival)
  * [Nihilistic Software](#nihilistic-software)
  * [Nikita](#nikita)
  * [Ninja Kiwi (Bloons TD)](#ninja-kiwi-bloons-td)
  * [MercurySteam](#mercurysteam)
    * [Metroid Dread](#metroid-dread)
  * [NoriaWorks Entertainment (Speed Haste)](#noriaworks-entertainment-speed-haste)
  * [Nosferatu: The Wrath of Malachi](#nosferatu-the-wrath-of-malachi)
  * [Novotrade](#novotrade)
    * [Story Painting](#story-painting)
  * [Nintendo EAD](#nintendo-ead)
    * [Animal Crossing](#animal-crossing)
    * [AST](#ast)
    * [Luigi's Mansion](#luigis-mansion)
    * [Pikmin](#pikmin)
    * [Pikmin 2](#pikmin-2)
    * [Mario Artist](#mario-artist)
    * [Mario Kart: Double Dash](#mario-kart-double-dash)
    * [Super Mario 64](#super-mario-64)
    * [Super Mario 64 DS](#super-mario-64-ds)
    * [Super Mario (Other)](#super-mario-other)
      * [Super Mario Sunshine](#super-mario-sunshine)
      * [Super Mario Galaxy & Odyssey](#super-mario-galaxy--odyssey)
      * [Mario Kart](#mario-kart)
      * [Mario Party](#mario-party)
      * [New Super Mario Bros.](#new-super-mario-bros)
      * [Classic & 2D Mario](#classic--2d-mario)
      * [Other Games & Decompilations](#other-games--decompilations)
    * [New Super Mario Bros Wii](#new-super-mario-bros-wii)
    * [Zelda](#zelda)
    * [Wii Sports](#wii-sports)
    * [Star Fox Adventures](#star-fox-adventures)
    * [Star Fox 64](#star-fox-64)
    * [Star Fox 64 3D](#star-fox-64-3d)
    * [Super Monkey Ball](#super-monkey-ball)
    * [F-Zero](#f-zero)
    * [Chibi-Robo](#chibi-robo)
    * [Snowboard Kids](#snowboard-kids)
    * [Wave Race 64](#wave-race-64)
    * [Yoshi's Story](#yoshis-story)
    * [Tetris](#tetris)
    * [The New Tetris](#the-new-tetris)
    * [New Super Mario Bros DS](#new-super-mario-bros-ds)
    * [Metroid Prime](#metroid-prime)
    * [Donkey Kong Country Returns](#donkey-kong-country-returns)
    * [Pokemon](#pokemon)
  * [NPC Studio (Fields of Mistria)](#npc-studio-fields-of-mistria)
  * [Nippon Ichi Software](#nippon-ichi-software)
    * [Disgaea](#disgaea)
    * [Yomawari](#yomawari)
  * [Ntreev Soft](#ntreev-soft)
  * [Obsidian Entertainment](#obsidian-entertainment)
    * [Neverwinter Nights 2](#neverwinter-nights-2)
  * [Oddworld Inhabitants](#oddworld-inhabitants)
    * [Spyro the Dragon](#spyro-the-dragon)
    * [Jak and Daxter](#jak-and-daxter)
  * [Origin Systems](#origin-systems)
    * [Ultima VII](#ultima-vii)
    * [Ultima IX: Ascension](#ultima-ix-ascension)
    * [Strike Commander](#strike-commander)
    * [Wing Commander](#wing-commander)
  * [Orion Games](#orion-games)
  * [Outrage Entertainment](#outrage-entertainment)
    * [Descent 3](#descent-3)
  * [Pangea Software (Bugdom)](#pangea-software-bugdom)
  * [Panic (Playdate)](#panic-playdate)
  * [Paradigm Entertainment](#paradigm-entertainment)
  * [Paradox Interactive](#paradox-interactive)
  * [Parallax Software (Descent)](#parallax-software-descent)
  * [Pearl Abyss (Crimson Desert)](#pearl-abyss-crimson-desert)
  * [People Can Fly](#people-can-fly)
    * [Painkiller](#painkiller)
    * [Dreamkiller](#dreamkiller)
  * [Petroglyph Games](#petroglyph-games)
  * [Phenomic](#phenomic)
    * [SpellForce](#spellforce)
  * [Piranha Bytes](#piranha-bytes)
    * [Gothic 3](#gothic-3)
  * [Pivotal Games](#pivotal-games)
  * [PlatinumGames](#platinumgames)
    * [Bayonetta](#bayonetta)
    * [Nier: Automata / Replicant](#nier-automata--replicant)
  * [Pole Chudes 2](#pole-chudes-2)
  * [Polygon Magic (Galerians)](#polygon-magic-galerians)
  * [Polytron (Fez)](#polytron-fez)
  * [PopCap Games](#popcap-games)
  * [ppy (osu!)](#ppy-osu)
  * [Primal Software](#primal-software)
    * [The I of the Dragon](#the-i-of-the-dragon)
  * [Primula (TAISHO x ALICE)](#primula-taisho-x-alice)
  * [Procedural Arts](#procedural-arts)
    * [Façade](#façade)
  * [Psygnosis](#psygnosis)
    * [WipeOut](#wipeout)
  * [Punchline](#punchline)
  * [Quantic Dream](#quantic-dream)
  * [Radical Entertainment](#radical-entertainment)
  * [Rare](#rare)
    * [Donkey Kong Country](#donkey-kong-country)
    * [Banjo-Kazooie](#banjo-kazooie)
    * [Banjo-Tooie](#banjo-tooie)
    * [Donkey Kong 64](#donkey-kong-64)
    * [Diddy Kong Racing](#diddy-kong-racing)
    * [Perfect Dark](#perfect-dark)
    * [GoldenEye 007](#goldeneye-007)
    * [Conker's Bad Fur Day](#conkers-bad-fur-day)
    * [Dinosaur Planet](#dinosaur-planet)
    * [Banjo-Kazooie (Xbox 360)](#banjo-kazooie-xbox-360)
    * [Grabbed by the Ghoulies](#grabbed-by-the-ghoulies)
  * [Raven Software](#raven-software)
    * [Shadowcaster](#shadowcaster)
    * [Heretic II](#heretic-ii)
    * [Soldier of Fortune](#soldier-of-fortune)
    * [Jedi Knight: Jedi Academy / Jedi Outcast](#jedi-knight-jedi-academy--jedi-outcast)
    * [Marvel: Ultimate Alliance](#marvel-ultimate-alliance)
  * [Rebel Act](#rebel-act)
  * [Rebellion Developments](#rebellion-developments)
    * [Judge Dredd: Dredd vs Death](#judge-dredd-dredd-vs-death)
    * [Aliens vs. Predator 2](#aliens-vs-predator-2)
    * [Aliens vs. Predator (2010)](#aliens-vs-predator-2010)
  * [Red Storm Entertainment](#red-storm-entertainment)
  * [Reflections Interactive](#reflections-interactive)
  * [Relic Entertainment](#relic-entertainment)
    * [Homeworld](#homeworld)
  * [Remedy Entertainment](#remedy-entertainment)
    * [Max Payne](#max-payne)
    * [Alan Wake 2](#alan-wake-2)
  * [Riot Games](#riot-games)
    * [League of Legends](#league-of-legends)
    * [Valorant](#valorant)
  * [Ritual Entertainment](#ritual-entertainment)
  * [Roblox](#roblox)
  * [RobTop Games](#robtop-games)
    * [Geometry Dash](#geometry-dash)
  * [Robit Studios (Treasure Adventure World)](#robit-studios-treasure-adventure-world)
  * [RockSolid Software (Blast Thru)](#rocksolid-software-blast-thru)
  * [Rockstar Games](#rockstar-games)
  * [Runecraft](#runecraft)
  * [Runic Games](#runic-games)
    * [Torchlight](#torchlight)
    * [Torchlight II](#torchlight-ii)
  * [Saber Interactive](#saber-interactive)
  * [Sacnoth (Koudelka)](#sacnoth-koudelka)
  * [SCS Software (Euro Truck Simulator)](#scs-software-euro-truck-simulator)
  * [Sega](#sega)
    * [Homebrew & Audio/Video Format Tools](#homebrew--audiovideo-format-tools)
    * [Model 2 Arcade Games](#model-2-arcade-games)
    * [Crazy Taxi](#crazy-taxi)
    * [Ryu Ga Gotoku Studio (Dragon Engine)](#ryu-ga-gotoku-studio-dragon-engine)
    * [Shenmue](#shenmue)
    * [Phantasy Star](#phantasy-star)
    * [Sonic Team (Hedgehog Engine)](#sonic-team-hedgehog-engine)
      * [Decompilations & Reconstructions](#decompilations--reconstructions)
      * [Retro Engine (RSDK)](#retro-engine-rsdk)
      * [Sonic Adventure](#sonic-adventure)
      * [Sonic Heroes & Shadow](#sonic-heroes--shadow)
      * [Classic & Handheld Sonic](#classic--handheld-sonic)
      * [Modern Hedgehog Engine & Mod Managers](#modern-hedgehog-engine--mod-managers)
    * [Creative Assembly](#creative-assembly)
      * [Alien: Isolation](#alien-isolation)
      * [Total War Series](#total-war-series)
    * [Puyo Puyo](#puyo-puyo)
    * [System & Middleware](#system--middleware)
    * [Camelot Software Planning (Shining Force)](#camelot-software-planning-shining-force)
    * [Other Games](#other-games)
  * [Sensible Software (Cannon Fodder)](#sensible-software-cannon-fodder)
  * [Sierra On-Line](#sierra-on-line)
    * [Quest for Glory V: Dragonfire](#quest-for-glory-v-dragonfire)
    * [Leisure Suit Larry](#leisure-suit-larry)
  * [Sigma Team](#sigma-team)
  * [Slitherine / Proxy Studios](#slitherine--proxy-studios)
  * [Snail Games (Age of Wushu)](#snail-games-age-of-wushu)
  * [SNK](#snk)
    * [Neo Geo Pocket](#neo-geo-pocket)
    * [SNK Heroines](#snk-heroines)
  * [Snowblind Studios](#snowblind-studios)
    * [Baldur's Gate: Dark Alliance](#baldurs-gate-dark-alliance)
  * [SoftClub](#softclub)
    * [Treasure Island (2005)](#treasure-island-2005)
  * [SoftLab-NN](#softlab-nn)
  * [Sony PlayStation Studios](#sony-playstation-studios)
    * [Guerrilla Games (Decima Engine)](#guerrilla-games-decima-engine)
    * [Insomniac Games](#insomniac-games)
    * [Naughty Dog](#naughty-dog)
    * [Polyphony Digital](#polyphony-digital)
    * [Santa Monica Studio](#santa-monica-studio)
    * [Sucker Punch](#sucker-punch)
    * [Other First Party / Japan Studio](#other-first-party--japan-studio)
    * [Sony Online Entertainment](#sony-online-entertainment)
    * [Evolution Studios](#evolution-studios)
    * [Bend Studio](#bend-studio)
  * [Southend Interactive (Sacred Citadel)](#southend-interactive-sacred-citadel)
  * [Speed Racer](#speed-racer)
  * [Spike Chunsoft](#spike-chunsoft)
    * [Danganronpa](#danganronpa)
    * [Kamaitachi no Yoru](#kamaitachi-no-yoru)
  * [Square Enix](#square-enix)
    * [Final Fantasy](#final-fantasy)
    * [Final Fantasy XI](#final-fantasy-xi)
    * [Final Fantasy XV](#final-fantasy-xv)
    * [Final Fantasy XIII](#final-fantasy-xiii)
    * [Final Fantasy VII](#final-fantasy-vii)
    * [Final Fantasy VIII](#final-fantasy-viii)
    * [Final Fantasy IX](#final-fantasy-ix)
    * [Chrono Trigger](#chrono-trigger)
    * [Chrono Cross](#chrono-cross)
    * [Xenogears](#xenogears)
    * [Xenosaga](#xenosaga)
    * [Vagrant Story](#vagrant-story)
    * [Soul Blazer](#soul-blazer)
    * [Sleeping Dogs](#sleeping-dogs)
    * [The World Ends With You](#the-world-ends-with-you)
    * [Babylon's Fall](#babylons-fall)
    * [Hitman](#hitman)
    * [Final Fantasy XIV](#final-fantasy-xiv)
    * [Tactics Ogre: Let Us Cling Together](#tactics-ogre-let-us-cling-together)
    * [Valkyrie Anatomia](#valkyrie-anatomia)
    * [Bravely Default](#bravely-default)
    * [Romancing SaGa](#romancing-saga)
  * [Stainless Games (Carmageddon)](#stainless-games-carmageddon)
  * [Starbreeze Studios](#starbreeze-studios)
  * [Stern Pinball](#stern-pinball)
  * [Studio MDHR (Cuphead)](#studio-mdhr-cuphead)
  * [Studio Pixel](#studio-pixel)
    * [Cave Story](#cave-story)
    * [Kero Blaster / Pink Hour / Pink Heaven](#kero-blaster--pink-hour--pink-heaven)
  * [Supercell](#supercell)
  * [SuperTuxKart](#supertuxkart)
  * [Surreal Software](#surreal-software)
  * [Take-Two Interactive](#take-two-interactive)
    * [Ripper](#ripper)
  * [TaleWorlds Entertainment](#taleworlds-entertainment)
    * [Mount\&Blade](#mountblade)
  * [Tamsoft](#tamsoft)
  * [Tate Interactive (Kao the Kangaroo)](#tate-interactive-kao-the-kangaroo)
  * [Tecmo (Tecmo Super Bowl)](#tecmo-tecmo-super-bowl)
    * [Solomon's Key](#solomons-key)
  * [Team Shanghai Alice (Touhou)](#team-shanghai-alice-touhou)
  * [Techland](#techland)
  * [Telltale Games](#telltale-games)
  * [Terminal Reality](#terminal-reality)
    * [Tools / Libraries](#tools--libraries)
    * [Documentation](#documentation)
    * [POD1 Style (POD1,EPD,POD2,POD6)](#pod1-style-pod1epdpod2pod6)
      * [Terminal Velocity / Fury3](#terminal-velocity--fury3)
      * [Nocturne](#nocturne)
    * [POD3 Style (POD3,POD4,POD5)](#pod3-style-pod3pod4pod5)
      * [BloodRayne](#bloodrayne)
    * [4x4 Evolution](#4x4-evolution)
    * [4x4 Evolution 2](#4x4-evolution-2)
  * [Terrible Toybox](#terrible-toybox)
  * [Terry Cavanagh](#terry-cavanagh)
    * [VVVVVV](#vvvvvv)
  * [The End Is Nigh](#the-end-is-nigh)
  * [The Learning Company](#the-learning-company)
    * [Super Solvers: Gizmos & Gadgets!](#super-solvers-gizmos--gadgets)
  * [Thekla Inc (The Witness)](#thekla-inc-the-witness)
  * [THQ / Rainbow Studios](#thq--rainbow-studios)
    * [Barnyard](#barnyard)
    * [Cars](#cars)
    * [MX vs ATV](#mx-vs-atv)
    * [Twisted Metal](#twisted-metal)
    * [Motocross Madness](#motocross-madness)
  * [Titus Interactive](#titus-interactive)
    * [Blues Brothers](#blues-brothers)
    * [Titus the Fox & Moktar](#titus-the-fox--moktar)
  * [Toaplan](#toaplan)
    * [Twin Cobra](#twin-cobra)
  * [Toby Fox (Undertale)](#toby-fox-undertale)
  * [Topheavy Studios (The Guy Game)](#topheavy-studios-the-guy-game)
  * [Torus Games](#torus-games)
  * [Touch Foo (Swordigo)](#touch-foo-swordigo)
  * [Treasure](#treasure)
    * [Mischief Makers](#mischief-makers)
  * [Troika Games (Vampire: The Masquerade)](#troika-games-vampire-the-masquerade)
    * [Temple of Elemental Evil](#temple-of-elemental-evil)
    * [Arcanum](#arcanum)
  * [TT Games (LEGO Island)](#tt-games-lego-island)
    * [Toy Story 2](#toy-story-2)
    * [Toy Story Racer](#toy-story-racer)
    * [Sonic R](#sonic-r)
  * [Turbine](#turbine)
  * [Type-Moon](#type-moon)
    * [Witch on the Holy Night](#witch-on-the-holy-night)
  * [Ubisoft](#ubisoft)
    * [OpenSpace](#openspace-1)
    * [Anvil / Scimitar](#anvil--scimitar)
    * [LyN Engine](#lyn-engine)
    * [Odin Engine](#odin-engine)
    * [YETI Engine](#yeti-engine)
    * [Unreal Engine](#unreal-engine-1)
    * [CryEngine / Dunia](#cryengine--dunia)
    * [Snowdrop Engine](#snowdrop-engine)
    * [Jade Engine](#jade-engine)
    * [Other Games / General](#other-games--general)
    * [Anno 1800](#anno-1800)
  * [Unicorn Games Studio](#unicorn-games-studio)
  * [Unique Development Studios (Futurama)](#unique-development-studios-futurama)
  * [United Software Artists](#united-software-artists)
    * [Amulets & Armor](#amulets--armor)
  * [Vicarious Visions](#vicarious-visions)
    * [Skylanders](#skylanders)
  * [Virtys (Mist Legacy)](#virtys-mist-legacy)
  * [Visceral Games (Dead Space, Dante's Inferno)](#visceral-games-dead-space-dantes-inferno)
  * [VTech (V.Smile)](#vtech-vsmile)
  * [Volition](#volition)
  * [Wargaming (World of Warships)](#wargaming-world-of-warships)
  * [WayForward](#wayforward)
    * [DuckTales: Remastered](#ducktales-remastered)
  * [Webzen (Archlord 2)](#webzen-archlord-2)
  * [강림2:제천대성 (Descent 2: Jecheondaeseong)](#강림2제천대성-descent-2-jecheondaeseong)
  * [Westwood Studios](#westwood-studios)
    * [Blade Runner (1997)](#blade-runner-1997)
    * [Command & Conquer](#command--conquer)
    * [Nox](#nox)
  * [Whoopee Camp (Tomba!)](#whoopee-camp-tomba)
  * [Williams Electronics](#williams-electronics)
  * [Working Designs (Lunar)](#working-designs-lunar)
  * [Yostar / Revived Witch](#yostar--revived-witch)
  * [Z-Axis](#z-axis)
* [🔗 Related Lists](#-related-lists)
* [📄 License](#-license)
* [🙏 Acknowledgments](#-acknowledgments)

<!-- END doctoc -->

## 👥 Communities & Wikis

*Knowledge bases, forums, and learning resources for reverse engineering and file formats.*

### Forums & Communities

* [ZenHAX](https://zenhax.com/) - Game hacking and reverse engineering forum.
* [ResHax](https://reshax.com/) - Game Reversing Archives and Formats.
* [XeNTaX Forum (defunct)](https://web.archive.org/web/20231024043128/https://forum.xentax.com/) - Game archive and format research forum.

### Discord Servers

* [REGames](https://discord.com/invite/regames-760531247704702996) - Community for game reverse engineering and file format research.
* [The VG Resource](https://discord.com/invite/tsr) - Community for The VG Resource asset databases (models, textures, sprites, sounds).
* [The Cutting Room Floor (TCRF)](https://discord.com/invite/SGeE8dcWR6) - Community for discovering and documenting unused and debug game content.
* [Reverse Engineering](https://discord.com/invite/reverse-engineering-391398885819547652) - General reverse engineering community and resources.
* [noclip.website](https://discord.com/invite/bkJmKKv) - Community for the noclip.website in-browser game viewer project.

*Note: Many game-specific and studio-specific Discord servers exist for individual games and franchises. This list includes only general-purpose reverse engineering communities.*

### Knowledge Bases & Format Databases

* [RetroReversing](https://github.com/RetroReversing/retroReversing) ⭐ 686 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-10 - Curated list of retro game development and reverse-engineering resources, tools, and documentation, published as the RetroReversing.com website/wiki.
* [XeNTaXBackup](https://github.com/XeNTaXBackup/XeNTaXBackup.github.io) ⭐ 71 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-01-21 - Public backup of the XeNTaX game file format reverse engineering forum and wiki, preserving community knowledge on game format documentation, QuickBMS scripts, and format research.
* [Just Solve the File Format Problem](http://fileformats.archiveteam.org/wiki/Game_data_files) - ArchiveTeam's wiki for file formats.
* [XeNTaX Wiki (defunct)](https://web.archive.org/web/20230822181840/https://wiki.xentax.com/index.php/Game_File_Format_Central) - Massive database of file format specifications.

### Platform & SDK Documentation

* [awesome-gbdev](https://github.com/gbdev/awesome-gbdev) ⭐ 4,485 | 🐛 21 | 📅 2026-07-22 - Curated list of Game Boy development resources, including reverse-engineering tools, hardware/format documentation, disassemblers, and emulators.
* [Awesome PlayStation Vita](https://github.com/MuxaJlbl4/Awesome-PlayStation-Vita) ⭐ 1,795 | 🐛 0 | 🌐 Markdown | 📅 2026-08-03 - Comprehensive PS Vita resource list including reverse engineering tools, file format decompilers (.rco, .rcs), and RE utilities.
* [awesome-gbadev](https://github.com/gbadev-org/awesome-gbadev) ⭐ 1,328 | 🐛 6 | 📅 2026-01-30 - Curated list of Game Boy Advance development resources, including documentation, tools, and libraries relevant to GBA file formats and homebrew.
* [Architecture of consoles](https://github.com/flipacholas/Architecture-of-consoles) ⭐ 1,102 | 🐛 28 | 📅 2026-08-18 - Series of technical articles on console hardware architecture, covering CPU, graphics, and file/memory layout across many platforms.
* [Pan Docs](https://github.com/gbdev/pandocs) ⭐ 780 | 🐛 137 | 🌐 Markdown | 📅 2026-06-09 - The single, most comprehensive technical reference to the Game Boy hardware available to the public, including cartridge header, memory bank controller, and save format documentation.
* [rom-properties](https://github.com/GerbilSoft/rom-properties) ⭐ 652 | 🐛 96 | 🌐 C++ | 📅 2026-08-19 - Shell extension for Windows and Linux that shows information about ROM and disc image files. Supports over 500 game and system file formats across dozens of consoles and handhelds.
  * Features: Metadata viewing (title, publisher, region), icon/boxart extraction, save game management, and explorer integration.
* [awesome-megadrive](https://github.com/And-0/awesome-megadrive) ⭐ 454 | 🐛 3 | 📅 2026-05-05 - Curated list of Sega Mega Drive/Genesis development resources, including hardware documentation, disassemblers, and format tools.
* [gb-ctr](https://github.com/Gekkio/gb-ctr) ⭐ 434 | 🐛 2 | 🌐 Typst | 📅 2026-08-16 - Game Boy: Complete Technical Reference, an in-depth document covering Game Boy console hardware internals.
* [PSVita-RE-tools](https://github.com/TeamFAPS/PSVita-RE-tools) ⭐ 383 | 🐛 14 | 🌐 C | 📅 2023-02-20 - Collection of PlayStation Vita reverse-engineering tools.
* [SiliconRE](https://github.com/furrtek/SiliconRE) ⭐ 229 | 🐛 23 | 🌐 Verilog | 📅 2026-08-19 - Traces, schematics, and technical writeups from silicon-level reverse engineering of custom game console/arcade chips.
* [ay-3-8910\_reverse\_engineered](https://github.com/lvd2/ay-3-8910_reverse_engineered) ⭐ 106 | 🐛 2 | 🌐 Verilog | 📅 2019-11-26 - Transistor-level reverse engineering of the AY-3-8910 sound chip used in many arcade and home computer systems, with transistor-level schematics, a Verilog model, and a testbench that renders register dumps into audio.
* [ps4libdoc](https://github.com/idc/ps4libdoc) ⭐ 104 | 🐛 0 | 📅 2022-07-11 - PS4 library documentation for game development and reverse engineering reference.
* [gbadoc](https://github.com/gbadev-org/gbadoc) ⭐ 64 | 🐛 9 | 🌐 CSS | 📅 2026-08-12 - Community-driven Game Boy Advance technical documentation effort.
* [pif\_rom\_dumper](https://github.com/hcs64/pif_rom_dumper) ⭐ 30 | 🐛 4 | 🌐 Assembly | 📅 2022-03-30 - Tool for extracting N64 PIF ROM (system firmware) from Nintendo 64 hardware.
* [Psy-Q SDK Documentation](https://psx.arthus.net/sdk/Psy-Q/DOCS/) - Official PlayStation SDK documentation archive. Includes file format references, development guides, and API documentation.
  * [File Format Reference](https://psx.arthus.net/sdk/Psy-Q/DOCS/Devrefs/Filefrmt.pdf) - Official Psy-Q SDK file format documentation.
* [PSX-SPX Console Dev](https://psx-spx.consoledev.net/) - Comprehensive PlayStation technical documentation and reference. Covers hardware specifications, BIOS functions, and development resources.
  * [CD-ROM File Formats](https://psx-spx.consoledev.net/cdromfileformats/) - Detailed documentation on PlayStation CD-ROM file formats and structures.
* [gb-bootroms](https://codeberg.org/ISSOtm/gb-bootroms) - Disassembled and annotated Game Boy family boot ROMs.

### Game-Specific Wikis

* [The Cutting Room Floor](https://tcrf.net/Help:Contents/Finding_Content) - Community for discovering and documenting unused and debug game content.
* [Nintendo File Formats](https://nintendo-formats.com/) - Documentation for Wii U and Switch games.
* [Custom Mario Kart Wiiki](https://wiki.tockdom.com/wiki/List_of_File_Formats) - Formats used in Mario Kart Wii and related games.
* [Mario Kart 8 Wiki](https://mk8.tockdom.com/wiki/Main_Page) - Documentation for Mario Kart 8 formats and modding.
* [Luma's Workshop](https://www.lumasworkshop.com/wiki/Category:File_formats) - Nintendo modding wiki.
* [Splatoon Technical Wiki](https://wiki.oatmealdome.me/index.php/Special:AllPages) - Technical documentation for Splatoon game formats.
* [Souls Modding Wiki](https://www.soulsmodding.com/doku.php?id=start) - Documentation for FromSoftware formats.

### 📚 Learning Resources & Tutorials

* [kovidomi/game-reversing](https://github.com/kovidomi/game-reversing) ⭐ 1,676 | 🐛 4 | 📅 2023-04-05 - Beginner learning materials on reverse engineering video games.
* [vgmdocs](https://github.com/loveemu/vgmdocs) ⭐ 100 | 🐛 2 | 📅 2026-05-01 - Resources and documentation for video game music formats. Includes guides for GBA sound drivers, FM synth presets, conversion tools, and format documentation.
* [Inazuma-Eleven-GO-Modding](https://github.com/SxncYT/Inazuma-Eleven-GO-Modding) ⭐ 1 | 🐛 0 | 🌐 Svelte | 📅 2025-10-02 - Documentation regarding the functions of Inazuma Eleven GO Light/Shadow. Covers game scripting, format specifications, and modding techniques.
* **[DGTEFF](https://web.archive.org/web/20230817151933/http://wiki.xentax.com/index.php/DGTEFF) - Definitive Guide To Exploring File Formats.**
* [The VG Resource Wiki](https://wiki.vg-resource.com/Main_Page) - Wiki with tutorials for ripping and creating sprites, models, textures, and sounds across gaming platforms.
* [Compression Deep Dive](https://chronovore.dev/posts/2023-01-25-1234P-compression-deepdive.html) - Technical analysis of compression algorithms used in games.
* [How to Crack a Binary File Format](https://www.iwriteiam.nl/Ha_HTCABFF.html) - Classic tutorial on reverse engineering file formats.
* [How to Grab Models and Textures](https://aknavj.github.io/3d/2019/06/10/Grabbing-models-and-textures-from-game-or-3D-application.html) - Guide on extracting models and textures from games.
* [ReWolf's Retrogaming Blog](http://blog.rewolf.pl/blog/?cat=23) - Blog posts on retrogaming and reverse engineering.
* [Crazy Taxi Reverse Engineering](https://wretched.computer/post/crazytaxi) - Detailed retrospective series on reverse engineering the GameCube version of Crazy Taxi, covering archive (.all), model (.shp), texture (.tex), and audio (.adp) formats.

#### 🎥 Video Tutorials

* [Binary File Format Engineering and Reverse Engineering](https://www.youtube.com/watch?v=8OxtBxXfJHw) - Peter Bindels - ACCU 2023 conference talk on binary file format analysis and reverse engineering techniques.
* [Reverse engineering game formats for fun and profit! (or just fun)](https://www.youtube.com/watch?v=MXbo6y6MCPE) - Spencer Alves - !!Con West 2020 talk on reverse engineering game file formats.
* [What's In A Bit - Designing, Using And Reverse-engineering Binary File Formats](https://www.youtube.com/watch?v=QEIGc3tXGmM) - Peter Bindels - cpponsea talk on binary file format design and reverse engineering.
* [File Format Reverse Engineering 1 - Intro, target, and tools](https://www.youtube.com/watch?v=_zCekiF5aBQ) - CO/DE tutorial series introduction to file format reverse engineering.
* [Reverse Engineered old Compression Algorithm for Frogger](https://www.youtube.com/watch?v=BwoOB2QFXvw) - LiveOverflow - Case study on reverse engineering compression algorithms in classic games.

### Asset Databases

* [The VG Resource (archived)](https://archive.vg-resource.com/index.php) - Models, Textures, Sounds, and Sprite databases and forums.
  * [The Spriters Resource](https://www.spriters-resource.com/) - Dedicated sprite and pixel art database.
  * [The Models Resource](https://models.spriters-resource.com/) - Dedicated 3D model database.
  * [The Textures Resource](https://textures.spriters-resource.com/) - Dedicated texture database.
  * [The Sounds Resource](https://sounds.spriters-resource.com/) - Dedicated audio and music database.

## 🛠️ General Tools

*Multi-format tools that support a wide variety of unrelated games.*

### 🎨 Asset Viewers & Converters

#### 3D Models & Viewers

* [vengi](https://github.com/vengi-voxel/vengi) ⭐ 1,400 | 🐛 133 | 🌐 C | 📅 2026-08-18 - Free, open-source, actively maintained voxel editor, thumbnailer, and command-line format converter.
  * Formats: MagicaVoxel VOX/XRAW, Qubicle QB/QBT/QEF/QBCL, Sandbox VoxEdit VXM/VXR/VXC/VXB/VXT, Ace of Spades KV6/VXL, Build engine KVX, Minecraft schematic/mcworld/region/level.dat/skin, CubeWorld, Goxel, BinVox, Tiberian Sun VXL, StarMade, and 30+ more voxel and mesh formats (glTF, FBX, Quake BSP/MDL/MD2/MD3, STL, PLY, and others).
  * Features: standalone GUI editor (VoxEdit), thumbnail generator, and CLI converter (VoxConvert) sharing one format backend.
* [NifSkope](https://github.com/niftools/nifskope) ⭐ 631 | 🐛 125 | 🌐 C++ | 📅 2024-06-03 - Tool for opening and editing the NetImmerse/Gamebryo NIF format used by Morrowind, Oblivion, Skyrim, Fallout 3/NV/4, and more. See also [hexabits' fork](https://github.com/hexabits/nifskope) ⭐ 259 | 🐛 50 | 🌐 C++ | 📅 2024-08-20 with Starfield support.
* [mviewer](https://github.com/majimboo/mviewer) ⭐ 299 | 🐛 0 | 🌐 Rust | 📅 2026-04-03 - Reverse engineering tool for viewing and analyzing MView 3D file format.
* [psx-modding-toolchain](https://github.com/mateusfavarin/psx-modding-toolchain) ⭐ 193 | 🐛 9 | 🌐 C | 📅 2026-02-21 - Toolchain for PlayStation 1 modding including model and texture tools.
* [Noesis-Plugins (leeao)](https://github.com/leeao/Noesis-Plugins) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2023-08-17 - Collection of Noesis Python scripts for various game models and textures.
* [SEAnim-Docs](https://github.com/SE2Dev/SEAnim-Docs) ⭐ 24 | 🐛 1 | 📅 2018-03-19 - Specification and documentation for the SEModel/SEAnim formats used by CastImporter and related tools.
* [tmd](https://github.com/roblouie/tmd) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2020-06-12 - JavaScript application for viewing PlayStation 1 TMD models in the browser. Features orbit controls, wireframe mode, and texture support.
* [Noesis-help](https://github.com/Sparagas/Noesis-help) ⭐ 10 | 🐛 0 | 🌐 HTML | 📅 2025-11-10 - Community-written help/documentation for Rich Whitehouse's Noesis, filling gaps in the official documentation.
* [CastImporter](https://github.com/o-Astral-o/CastImporter) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2025-03-27 - Unreal Engine plugin for importing SEModel, SEAnim, and Cast files. Commonly used with Call of Duty asset extractors.
* [heightmap-viewer](https://github.com/impiaaa/heightmap-viewer) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2017-05-30 - Simple 3D viewer for loading regular heightmaps and special format heightmap files.
* [Noesis](https://richwhitehouse.com/index.php?content=inc_projects.php\&showproject=91) - Popular all-in-one tool for previewing and converting 500+ model, texture, and animation formats. Supports batch conversion, has a rich plugin ecosystem, and can handle most common game formats out of the box.
  * [Noesis Plugins (Durik256)](https://github.com/Durik256/Noesis-Plugins) ⭐ 68 | 🐛 22 | 🌐 Python | 📅 2026-04-25 - Community collection with 150+ plugins for various games including Final Fantasy series, Dark Souls 2, Dead Rising 4, Ridge Racer, NHL 21, and many others.
  * [Noesis Plugins (Zheneq)](https://github.com/Zheneq/Noesis-Plugins) ⭐ 34 | 🐛 4 | 🌐 Python | 📅 2023-07-09 - Community plugins for Megaman X8 (PC), Fatal Frame 4 (Wii), Star Wars: The Force Unleashed (Wii), Planet 51 (Wii), Silent Hill: Shattered Memories (Wii), Fire Emblem (Wii), MT Framework (3DS).
  * [Noesis Plugins (mrpostiga)](https://github.com/mrpostiga/noesis-plugins-official) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2017-02-15 - Additional community-maintained plugin collection.
  * [noesis\_iqe](https://github.com/viciious/noesis_iqe) ⭐ 12 | 🐛 1 | 🌐 C++ | 📅 2016-11-30 - Noesis plugin for exporting models to Inter-Quake Export (IQE) format.
  * [Noesis Plugins (RoadTrain)](https://github.com/RoadTrain/noesis-plugins) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2017-09-08 - LS3D engine plugin (.4ds format) supporting Mafia: The City of Lost Heaven, Chameleon, Hidden & Dangerous 2, War of Wings.
  * [noesis\_dukemdx](https://github.com/DaZombieKiller/noesis_dukemdx) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2023-01-12 - Noesis plugin for Duke Nukem Extended Model (MDX) format.
  * [Noesis Plugins (Rich Whitehouse)](https://richwhitehouse.com/index.php?content=inc_projects.php#prjmp91) - Official plugin collection by the creator of Noesis.
  * [Noesis Plugins (HimeWorks)](https://himeworks.com/noesis-plugins/) - Community plugin collection for 100+ games, primarily MMORPGs and action games.
    Games include Tales series, Midnight Club 2, Dragon Nest, Dark Souls, League of Legends, C9, Cabal Online, Monster Hunter 3, Hyperdimension Neptunia, Ys series, and many more.

#### Textures & Images

* [detex](https://github.com/hglm/detex) ⭐ 177 | 🐛 14 | 🌐 C | 📅 2023-01-17 - Low-level library for decompression and manipulation of texture blocks.
  * Formats: BC1/DXT1/S3TC, BC2-BC3, BC4/RGTC1, BC5/RGTC2, BC6 (BPTC\_FLOAT), BC7 (BPTC), ETC1, ETC2 family, KTX, DDS.
  * Features: Texture decompression, pixel format conversion.
* [Texture64](https://github.com/queueRAM/Texture64) ⭐ 101 | 🐛 6 | 🌐 C# | 📅 2021-01-02 - N64 texture ripper and editor, complementing Motex above with editing support.
* [Rainbow](https://github.com/marco-calautti/Rainbow) ⭐ 98 | 🐛 14 | 🌐 C# | 📅 2021-04-07 - Texture format converter for different consoles' graphics formats, supporting TIM2, Super Robot Wars MX, The 3rd Birthday, and more.
* [tim2view](https://github.com/lab313ru/tim2view) ⭐ 71 | 🐛 6 | 🌐 Pascal | 📅 2016-08-09 - Viewer, converter, searcher, editor, and scanner/ripper for PS2 TIM/TM2 texture formats, complementing Rainbow's TIM2 conversion support.
* [texgenpack](https://github.com/hglm/texgenpack) ⭐ 62 | 🐛 12 | 🌐 C | 📅 2018-02-05 - Compresses, decompresses, and converts texture files using a genetic algorithm. Supports KTX, DDS, ETC2, BC6/BC7, and more.
* [ImageHeat](https://github.com/bartlomiejduda/ImageHeat) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2026-07-11 - Texture viewing tool for encoded textures.
  * Formats: RGBA8888, RGB888, RGB565, DXT1, ASTC, indexed formats (PAL4/8/16).
  * Platforms: PSP, PS2, PS3, PS4, Xbox (unswizzling support).
  * Features: Decompression (RLE, PackBits, ZLIB), export to DDS/PNG/BMP.
* [GTX-Extractor](https://github.com/aboood40091/GTX-Extractor) ⭐ 35 | 🐛 4 | 🌐 Python | 📅 2019-04-11 - Extractor for GTX (GX2 Texture) format in Wii U games with bidirectional conversion.
* [BNTX-Extractor](https://github.com/aboood40091/BNTX-Extractor) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2018-05-03 - Extractor for BNTX (Binary NX Texture) format in Nintendo Switch games.
  * Formats: BC1-BC7, RGBA variants, ASTC variants
* [lfgfx](https://github.com/ethteck/lfgfx) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2022-12-13 - Python tool for reverse-engineering and analyzing N64 graphics data blobs (display lists, vertex data, textures, palettes).
* [DDS.Tools](https://github.com/BoBoBaSs84/DDS.Tools) ⭐ 19 | 🐛 1 | 🌐 C# | 📅 2026-08-14 - Simple DDS and PNG tool set that converts DDS images to PNG images and vice versa on a large scale. Has options for duplicate detection and sorting.
* [TexViewer](https://github.com/Puxtril/TexViewer) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2026-05-21 - Tool to help discover unknown texture formats.
* [detex-compress](https://github.com/hglm/detex-compress) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2015-05-19 - Fast texture compression utility built on the detex library, supporting BC1-5 and ETC1 formats.
* [Motex](https://github.com/jpburnett/motex) ⭐ 5 | 🐛 4 | 🌐 Rust | 📅 2025-12-01 - N64 texture viewer for analyzing and inspecting N64 binary texture data; useful for reverse-engineering game texture formats.
* [TextureFinder](https://github.com/Gravemind2401/TextureFinder) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2025-07-16 - Binary texture extraction utility supporting multiple game texture formats including DXGI and Xbox formats. Helps identify and extract embedded texture data from game binaries.
* [swizzleinator](https://github.com/v4nguard/swizzleinator) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-09-08 - Library for detiling/deswizzling various image formats. `no_std`-friendly. Supports PS3, PS4, and X360 texture swizzling/unswizzling.
* [BCDec](https://github.com/neptuwunium/bcdec) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-05-19 - All-in-one C++ texture decoding library and tool for BC1-BC7, ETC1/2, and ASTC formats.
* [PyNVTT](https://github.com/Hancapo/PyNVTT) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-07-01 - Python wrapper for NVIDIA Texture Tools (NVTT). Enables DDS texture format conversion and compression for game asset extraction and modding.
* [RAW pixels viewer](https://www.kernellabs.com/rawpixels/) - Web-based tool for analyzing raw image data. Displays memory dumps of frame buffers, video buffers, and uncompressed video files. Allows interactive exploration of color formats and image parameters (width, height, offset, flip, invert, zoom) to help identify unknown pixel formats.

#### Sprites, Tiles & Tilemaps

* [Tilemap Studio](https://github.com/Rangi42/tilemap-studio) ⭐ 528 | 🐛 26 | 🌐 C++ | 📅 2026-05-02 - Tilemap editor for Game Boy, GBC, GBA, NDS, SNES, Genesis, and TG16.
  * Support: pret disassemblies, Pokemon ROM hacks
* [tmxlite](https://github.com/fallahn/tmxlite) ⭐ 464 | 🐛 12 | 🌐 C++ | 📅 2026-04-27 - Lightweight C++14 parser for Tiled Map Editor's TMX/TSX tilemap format, used by many indie and hobbyist games.
* [NitroPaint](https://github.com/Garhoogin/NitroPaint) ⭐ 106 | 🐛 6 | 🌐 C | 📅 2026-08-17 - Graphics editor for Nintendo DS image formats.
  * See also [ptexconv](https://github.com/Garhoogin/ptexconv) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2026-06-29 for a command-line-only version of its texture and background converter.
  * Formats: NCLR, NCGR, NSCR
  * Compression: LZ, RLE, Huffman, LZX
* [Tile Molester](https://github.com/toruzz/TileMolester) ⭐ 106 | 🐛 25 | 🌐 Java | 📅 2024-05-04 - Multi-format, user-extensible graphics data editor for viewing and editing tile-based graphics in arbitrary binary files from game consoles.
* [gimp-rom-bin](https://github.com/bbbbbr/gimp-rom-bin) ⭐ 102 | 🐛 2 | 🌐 C | 📅 2025-11-25 - GIMP plug-in to read/write/convert ROM image, tile, and sprite files.
  * Platforms: SNES, NES, Game Boy/GBC, GBA, Neo Geo Pocket, Mega Drive/Genesis, and more.
* [chrgfx](https://github.com/drojaazu/chrgfx) ⭐ 78 | 🐛 1 | 🌐 C++ | 📅 2026-07-07 - Converts to and from tile-based (CHR) graphics formats used across many retro consoles.
* [gimp-tilemap-gb](https://github.com/bbbbbr/gimp-tilemap-gb) ⭐ 71 | 🐛 1 | 🌐 C | 📅 2024-04-16 - Console app and GIMP plug-in for importing/exporting Game Boy game tilemaps and tilesets as bitmap images or .GBM/.GBR files. Related to GBTD, GBMB, GBDK, and ZGB.
* [SNESTilesKitten](https://github.com/Skarsnik/SNESTilesKitten) ⭐ 70 | 🐛 3 | 🌐 C++ | 📅 2025-06-25 - Tile viewer, extractor, and injector for SNES ROM files with HiROM/LoROM support.
* [Nintendo\_DS\_Compressors](https://github.com/PeterLemon/Nintendo_DS_Compressors) ⭐ 41 | 🐛 1 | 🌐 C | 📅 2024-06-12 - Collection of compressors for formats used on Nintendo GBA/DS.
* [BMP2BNR](https://github.com/Cuyler36/BMP2BNR) ⚠️ Archived - Converts BMP images to GameCube banner format (BNR).
* [nds\_texcompress](https://github.com/kusma/nds_texcompress) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2017-02-07 - Texture compression tool for Nintendo DS texture formats.
* [The Spriters Toolkit](https://tools.spriters-resource.com) - Web-based suite of asset management, validation, and conversion tools by the creators of The VG Resource.
  * Formats: PNG, GLB, OBJ, FBX, DAE, ZIP.
  * Features: Sprite sheet creator, sprite splitter, 3D model viewer, asset package analyzers (sprites, models, audio).

#### Fonts

* [fntlib](https://github.com/JaanDev/fntlib) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2022-08-30 - Python library for reading and writing AngelCode BMFont bitmap .fnt font files, a format used by many game engines (cocos2d-x, Geometry Dash, and others) for in-game text rendering.

#### DCC Tool Plugins (Blender / 3ds Max / Godot)

* [blender\_magicavoxel](https://github.com/AstrorEnales/blender_magicavoxel) ⭐ 62 | 🐛 4 | 🌐 Python | 📅 2026-07-26 - MagicaVoxel `.vox` importer for Blender with hierarchy/greedy meshing, voxel hull reduction, and UV-aware material modes.
* [MagicaVoxel-Importer](https://github.com/scayze/MagicaVoxel-Importer) ⭐ 56 | 🐛 5 | 🌐 GDScript | 📅 2019-03-20 - Godot Engine plugin for importing MagicaVoxel `.vox` format files as meshes. Supports Godot 3.0+ with import scaling and centering based on voxel resolution.
  * Options: multiple meshing modes (voxel-as-model, simple cubes/quads, greedy), UV unwrapping, vertex colors, texture baking, and voxel hull pruning.
  * Material modes: ignore, vertex colors, per-color materials, palette textures, and UV-unwrapped textured models.
* [Blender\_ioEDM](https://github.com/ndevenish/Blender_ioEDM) ⭐ 52 | 🐛 15 | 🌐 Python | 📅 2019-08-27 - Experimental Blender importer/exporter for .EDM model files used in DCS World flight simulator. Supports basic geometry, textures, animations, and connectors.
* [io\_mesh\_ninjaripper](https://github.com/REDxEYE/io_mesh_ninjaripper) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2019-07-23 - Blender addon for importing NinjaRipper .rip files. Supports Blender 2.78-2.79.
* [3ds-Max-Scripts](https://github.com/tge-was-taken/3ds-Max-Scripts) ⭐ 4 | 🐛 0 | 🌐 MAXScript | 📅 2021-10-25 - Archive of 3ds Max scripts including model importing scripts for various game formats and utility scripts.
* [blender-tooling](https://github.com/bigianb/blender-tooling) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-07-02 - Scripts to import files into Blender.
* [dae-cleanup](https://github.com/3e2j/dae-cleanup) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-11-26 - Blender add-on for cleaning and post-processing DAE (Collada) files exported from Switch Toolbox, improving compatibility and reducing file size.
* [Sprite Sheet Addon for Blender](https://www.moddb.com/engines/blender-game-engine/downloads/sprite-sheet-addon-for-blender) - Sprite sheet script for Blender VSE. (video squence editor) Convert image sequences to sprite sheet.
* [Sprite Sheet Addon for Blender VSE](https://www.moddb.com/groups/blender-game-engine/downloads/sprite-sheet-addon-for-blender-vse) - Sprite sheet script for Blender VSE. (video squence editor) Convert image sequences to sprite sheet.

### 📦 Archive Extractors

* [binwalk](https://github.com/ReFirmLabs/binwalk) ⭐ 14,237 | 🐛 92 | 🌐 Rust | 📅 2026-08-11 - Firmware analysis tool for identifying and extracting embedded files and data. The Rust version (v3) provides significant speed and accuracy improvements over the original Python version.
* [AssetRipper](https://github.com/AssetRipper/AssetRipper) ⭐ 8,161 | 🐛 163 | 🌐 C# | 📅 2026-08-19 - GUI tool for extracting assets from Unity serialized files (*CAB-*\\*, *\\*.assets*, etc.) and asset bundles (*\\*.unity3d\*, *\\*.bundle\*, etc.) and converting them into the native Unity engine format.
* [Universal Extractor 2](https://github.com/Bioruebe/UniExtract2) ⭐ 4,402 | 🐛 124 | 🌐 AutoIt | 📅 2024-07-06 - Generic tool to extract files from any type of archive or installer, commonly used to unpack game installers (NSIS, InstallShield, Wise, and many more) before further asset processing.
* [GARbro](https://github.com/morkt/GARbro) ⭐ 3,254 | 🐛 276 | 🌐 C# | 📅 2024-07-08 - Visual novels resource browser and extractor supporting many formats.
* [Greaseweazle](https://github.com/keirf/greaseweazle) ⭐ 1,376 | 🐛 79 | 🌐 Python | 📅 2026-06-16 - Hardware and tools for reading/writing floppy disks at the raw flux level, widely used for archiving copy-protected game floppies.
* [innoextract](https://github.com/dscharrer/innoextract) ⭐ 1,340 | 🐛 69 | 🌐 C++ | 📅 2025-02-06 - Extracts installers created by Inno Setup without running them, commonly used to unpack game installers before further asset processing.
* [extract-xiso](https://github.com/XboxDev/extract-xiso) ⭐ 1,128 | 🐛 40 | 🌐 C | 📅 2025-05-15 - Xbox ISO (XISO) creation, modification, and extraction utility for original Xbox disc images.
* [OmniDrive](https://github.com/RibShark/OmniDrive) ⭐ 1,074 | 🐛 19 | 🌐 Assembly | 📅 2026-07-18 - Firmware modification for MediaTek MT1959-based Hitachi-LG optical disc drives, enabling raw sector and lead-in/lead-out reading of CD/DVD/BD media including proprietary game discs.
* [UWPDumper](https://github.com/Wunkolo/UWPDumper) ⭐ 952 | 🐛 40 | 🌐 C++ | 📅 2024-09-03 - DLL and Injector for dumping UWP applications at run-time to bypass encrypted file system protection.
* [Aaru](https://github.com/aaru-dps/Aaru) ⭐ 614 | 🐛 212 | 🌐 C# | 📅 2026-08-13 - Data Preservation Suite for dumping and analyzing media (optical, magnetic, and solid-state) into forensic disc images, with format identification, checksumming, and decoding across a huge range of game and computer platforms. See also [libaaruformat](https://github.com/aaru-dps/libaaruformat) ⭐ 26 | 🐛 3 | 🌐 C | 📅 2026-07-31, the C implementation of the Aaru image format.
* [maxcso](https://github.com/unknownbrackets/maxcso) ⭐ 508 | 🐛 28 | 🌐 C | 📅 2024-06-30 - Fast CSO compression utility for PSP and PS2 game ISO files used with emulators.
* [redumper](https://github.com/superg/redumper) ⭐ 484 | 🐛 104 | 🌐 C++ | 📅 2026-08-14 - Low-level CD dumper utility for bit-perfect optical disc preservation, used by the Redump.org preservation community.
* [archives](https://github.com/mholt/archives) ⭐ 438 | 🐛 9 | 🌐 Go | 📅 2026-08-05 - Cross-platform archive library for Go supporting many formats. Provides unified API and virtual file systems compatible with `io/fs`.
  * Formats: .zip, .tar (including compressed variants), .rar (read-only), .7z (read-only), brotli, bzip2, gzip, lz4, lzip, minlz, snappy/S2, xz, zlib, zstandard.
  * Features: Stream-oriented APIs, automatic format identification, password-protected 7-Zip/RAR support, insert into .tar/.zip without recreating, multithreaded Gzip, DeepFS for traversing archives transparently.
* [unshield](https://github.com/twogood/unshield) ⭐ 435 | 🐛 38 | 🌐 C | 📅 2026-03-28 - Library and CLI tool to extract InstallShield CAB archives, commonly used to unpack older game installers before further asset processing.
* [GameExtractor](https://github.com/wattostudios/GameExtractor) ⭐ 310 | 🐛 14 | 🌐 Java | 📅 2026-08-01 - Multi-game archive tool supporting 4000+ games.
* [HxCFloppyEmulator](https://github.com/jfdelnero/HxCFloppyEmulator) ⭐ 195 | 🐛 11 | 🌐 C | 📅 2026-08-13 - HxC floppy drive emulator toolkit; reads and converts a wide range of retro floppy disk image formats, including many game-console/computer-specific ones.
* [xvdtool](https://github.com/emoose/xvdtool) ⭐ 177 | 🐛 11 | 🌐 C# | 📅 2026-04-25 - Command-line tool for manipulating Xbox One XVD/XVC package files, with support for decryption, hashing, resignation, and VHD conversion.
* [ExtractData](https://github.com/lioncash/ExtractData) ⭐ 172 | 🐛 0 | 🌐 C | 📅 2025-04-25 - Extraction tool for Japanese visual novel/game archives, using Susie Plugin (.spi) modules to decode proprietary archive and image formats. Originally developed by Yuu.
* [dexvert](https://github.com/Sembiance/dexvert) ⭐ 167 | 🐛 2 | 🌐 Python | 📅 2026-08-12 - Identifies and converts over 3,700 file formats to modern equivalents, including many game-specific archive, texture, and model formats.
* [fluxfox](https://github.com/dbalsom/fluxfox) ⭐ 155 | 🐛 4 | 🌐 Rust | 📅 2026-08-16 - Floppy disk image library in Rust for emulators, focused on PC platform disk images with initial Amiga/Macintosh/Atari ST support.
  * Features: Track bitstream access, copy-protection visualization, common PC floppy disk controller (NEC uPD765A) operation emulation.
* [SabreTools](https://github.com/SabreTools/SabreTools) ⭐ 143 | 🐛 10 | 🌐 C# | 📅 2026-08-12 - DAT-based ROM/disc image management tool with advanced editing and sorting features.
* [DiskImageTool](https://github.com/Digitoxin1/DiskImageTool) ⭐ 110 | 🐛 7 | 🌐 Visual Basic .NET | 📅 2026-08-09 - Floppy disk image manager with built-in bitstream analysis, Greaseweazle support, and optional Kryoflux integration.
* [RVWorld (RomVault)](https://github.com/RomVault/RVWorld) ⭐ 103 | 🐛 15 | 🌐 C# | 📅 2026-08-19 - DAT-file-driven ROM set organizer/verifier for identifying, sorting, and repairing game ROM and disc image collections.
* [SAMdisk](https://github.com/simonowen/samdisk) ⭐ 97 | 🐛 6 | 🌐 C++ | 📅 2026-05-30 - Portable disk image utility specializing in copy-protected PC-compatible floppy formats, commonly used to preserve original game floppy disks.
* [RIDE](https://github.com/tomas-nestorovic/RIDE) ⭐ 85 | 🐛 36 | 🌐 C++ | 📅 2026-08-17 - Windows tool for low-level raw floppy disk access and browsing legacy filesystems (ZX Spectrum, MS-DOS, and others) found on preserved game disks.
* [iPoPS](https://github.com/julianxhokaxhiu/iPoPS) ⭐ 84 | 🐛 3 | 🌐 C | 📅 2025-09-19 - Converts PSX discs and ISOs into PBP format for playback on PSP.
* [isodump](https://github.com/Lameguy64/isodump) ⭐ 49 | 🐛 3 | 🌐 C++ | 📅 2021-01-13 - PlayStation ISO content extraction tool. Extracts files from PSX ISO/BIN images, supports ISO9660 filesystem, XA and STR files. Generates MKPSXISO-compatible XML project files for rebuilding ISOs.
* [cicdec](https://github.com/Bioruebe/cicdec) ⭐ 43 | 🐛 11 | 🌐 C# | 📅 2024-06-16 - Unpacker for installers made with Clickteam Install Creator, used to extract game data bundled by that installer format.
* [uninno](https://github.com/onitake/uninno) ⭐ 42 | 🐛 3 | 🌐 Perl | 📅 2024-03-09 - Portable command-line unpacking tool for Inno Setup installers, commonly used to unpack game installers before further asset processing.
* [UnkrawerterGBA](https://github.com/MCJack123/UnkrawerterGBA) ⭐ 36 | 🐛 3 | 🌐 C++ | 📅 2022-03-05 - Game Boy Advance ROM extractor and converter for games using the Krawall sound engine. Exports audio as XM or S3M module files. Supports automatic detection of instrument/sample lists and modules, direct rip mode for lossless extraction, and can be used as a library.
  * See also [krawall](https://github.com/sebknzl/krawall) ⭐ 69 | 🐛 2 | 🌐 C | 📅 2014-10-01, the original XM/S3M player engine source used by these games.
* [RTB-QuickBMS-Scripts](https://github.com/RandomTBush/RTB-QuickBMS-Scripts) ⭐ 28 | 🐛 2 | 📅 2026-03-20 - Collection of QuickBMS scripts for various games.
* [edccchk](https://github.com/claunia/edccchk) ⭐ 24 | 🐛 0 | 🌐 C | 📅 2025-03-09 - EDC/ECC checker for raw (2352 bytes/sector) CD images, used to verify game disc dump integrity.
* [ps4tools](https://github.com/harlequin/ps4tools) ⭐ 23 | 🐛 3 | 🌐 C | 📅 2019-05-21 - Tools for extracting PS4 file formats including PUP, PKG, PFS, and trophy files.
* [spoondec](https://github.com/Bioruebe/spoondec) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2023-10-16 - Extractor for Spoon (Xenocode) virtualized installer packages, used to extract game data bundled by that installer format.
* [flux-analyze](https://github.com/kristomu/flux-analyze) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2026-04-24 - Analysis and recovery tool for IBM MFM floppy flux image data.
* [innounpy](https://github.com/lkraider/innounpy) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2013-01-21 - Multiplatform Python unpacker for Inno Setup installers, a pure-Python alternative to innoextract for extracting game installer contents.
* [mdsx](https://github.com/Marisa-Chan/mdsx) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2025-12-16 - Decompressor/decrypter for MDS v2 / MDX disc image formats (DAEMON Tools).
* [quickbms-scripts (devinacker)](https://github.com/devinacker/quickbms-scripts) ⭐ 5 | 🐛 0 | 📅 2021-01-13 - Small collection of QuickBMS scripts for extracting game archives, covering MTV Club Dead (`.dta`), Klik & Play/Click & Create/The Games Factory (`.gam`, `.cca`, `.mus`, `.snd`), and Twisted: The Game Show (`Stream` directory).
* [romrepomgr](https://github.com/claunia/romrepomgr) ⭐ 5 | 🐛 2 | 🌐 C# | 📅 2025-12-23 - ROM Repository Manager for organizing and deduplicating game ROM/disc image collections.
* [dumplib](https://github.com/drojaazu/dumplib) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2014-09-07 - Library for working with media images (ROMs, disk images) from older video game consoles.
* [PKGTool](https://github.com/thesupersonic16/PKGTool) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2017-08-18 - Tool for extracting and repacking PKG files from The Legend of Heroes: Trails of Cold Steel.
* [wad-tools](https://github.com/libertyernie/wad-tools) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2022-11-28 - Tools for WAD archive format (Wii/GameCube). Fork of BFGR WadTools with enhanced command-line options for wadpacker and wadunpacker, including custom output directories and common-key.bin path specification. Supports C++and C++/CLI compilation.
* [mymc](https://github.com/uyjulian/mymc) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-01-10 - Utility for working with PlayStation 2 memory card images (PCSX2 format). Supports importing/exporting save games in MAX Drive (.max) and EMS (.psu) formats, viewing memory card contents, creating new memory card images, and adding/extracting individual files. Includes GUI and command-line interfaces.
* [QuickBMS](https://aluigi.altervista.org/quickbms.htm) - Universal archive extractor and reimporter with extensive script database covering thousands of games. Uses BMS scripting language to describe archive formats.

### 🔊 Audio Tools

* [vgmstream](https://github.com/vgmstream/vgmstream) ⭐ 2,226 | 🐛 28 | 🌐 C | 📅 2026-08-17 - Audio playback library supporting 1000+ game audio formats including looping, multi-channel streams, and console-specific codecs. Works as a standalone player or Winamp/foobar2000 plugin. If a game audio file exists, vgmstream probably plays it.
* [vgmtrans](https://github.com/vgmtrans/vgmtrans) ⭐ 1,256 | 🐛 93 | 🌐 C++ | 📅 2026-08-19 - Video Game Music Translator; converts proprietary game audio sequence/soundfont formats from many games/consoles into standard MIDI/DLS/SF2.
* [BassoonTracker](https://github.com/steffest/BassoonTracker) ⭐ 1,167 | 🐛 31 | 🌐 JavaScript | 📅 2026-08-05 - Web-based old-school Amiga music tracker in plain JavaScript. Plays and edits Amiga Mod files and FastTracker XM files.
* [Wwise-Unpacker](https://github.com/Vextil/Wwise-Unpacker) ⭐ 789 | 🐛 36 | 🌐 Batchfile | 📅 2026-07-18 - Windows tool for extracting audio from Wwise PCK and BNK containers to OGG or MP3 format. Works with any game using Wwise audio middleware.
* [jpsxdec](https://github.com/m35/jpsxdec) ⭐ 595 | 🐛 47 | 🌐 Java | 📅 2026-05-17 - Cross-platform PlayStation 1 audio and video converter.
* [impulse-tracker](https://github.com/jthlim/impulse-tracker) ⭐ 442 | 🐛 1 | 🌐 Assembly | 📅 2024-10-20 - Original source code release for Impulse Tracker, the DOS music tracker behind the widely-used IT module format found in many games' soundtracks.
  * Chips: YM2151/2203/2413/2608/2610/2612, OPL2/3, QSound, C140/C352, Konami K005289/007232/051649/053260/054539, SegaPCM, MultiPCM, RF5C68/400, ES5506, BSMT2000, Williams DCS/DAC/CVSD, and more.
* [ww2ogg](https://github.com/hcs64/ww2ogg) ⭐ 394 | 🐛 8 | 🌐 C++ | 📅 2024-10-12 - Converts Wwise RIFF/RIFX Vorbis audio (.wem files) to standard Ogg Vorbis format. Command-line tool with packed codebook support for various encoding variants. Note: vgmstream is recommended for playback, but ww2ogg is useful when Ogg Vorbis output is specifically required.
* [wwiser](https://github.com/bnnm/wwiser) ⭐ 359 | 🐛 4 | 🌐 Python | 📅 2026-08-15 - Wwise .bnk explorer and audio simulator. Python tool for parsing Wwise soundbank files, viewing HIRC audio scripting data, generating TXTP files for vgmstream playback, and dumping bank contents. Works with any game using Wwise audio middleware.
* [nsfplay](https://github.com/bbbradsmith/nsfplay) ⭐ 324 | 🐛 4 | 🌐 C++ | 📅 2025-02-04 - NSF (Nintendo Sound Format) player and library for NES/Famicom game-music rips, including expansion-audio chip emulation and command-line WAV rendering/metadata utilities.
* [VGMusicStudio](https://github.com/Kermalis/VGMusicStudio) ⭐ 309 | 🐛 51 | 🌐 C# | 📅 2024-07-13 - Music player and visualizer for GBA (MP2K format, SDAT) and NDS handheld game audio. Supports playback and extraction with SoundFont2 support, built on the same author's [SoundFont2](https://github.com/Kermalis/SoundFont2) ⭐ 33 | 🐛 0 | 🌐 C# | 📅 2022-08-31, [KMIDI](https://github.com/Kermalis/KMIDI) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2023-05-17, [KFLP](https://github.com/Kermalis/KFLP) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2023-07-05, and [DLS2](https://github.com/Kermalis/DLS2) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2022-09-01 libraries for reading/writing SF2, MIDI, FL Studio project, and DLS files.
* [VGAudio](https://github.com/Thealexbarney/VGAudio) ⭐ 257 | 🐛 28 | 🌐 C# | 📅 2023-02-12 - .NET library for encoding, decoding, and manipulating audio files from video games.
  * Formats: BRSTM, BCSTM, BFSTM, IDSP, HPS, DSP (Nintendo formats).
* [LoopingAudioConverter](https://github.com/libertyernie/LoopingAudioConverter) ⭐ 215 | 🐛 14 | 🌐 C# | 📅 2026-06-30 - Tool for converting many game audio formats to looping WAV, OGG, or FLAC files. Supports many console formats through VGAudio and vgmstream.
* [OPL3BankEditor](https://github.com/Wohlstand/OPL3BankEditor) ⭐ 174 | 🐛 24 | 🌐 C++ | 📅 2026-07-24 - Cross-platform editor for OPL3 FM instrument bank formats used by numerous DOS-era games and sound drivers (IBK, OP2/GENMIDI, TMB, WOPL, and others).
* [wwiseutil](https://github.com/hpxro7/wwiseutil) ⭐ 150 | 🐛 27 | 🌐 Go | 📅 2018-10-17 - Tool for manipulating Wwise SoundBank and File Package files. Works with any game using Wwise audio middleware.
  * Formats: .bnk, .nbnk (SoundBank), .pck, .npck (File Package), WEM (audio).
  * Features: Unpacking WEM audio, audio replacement with metadata updates, loop point editing.
* [vgmtools](https://github.com/vgmrips/vgmtools) ⭐ 148 | 🐛 4 | 🌐 C | 📅 2026-08-16 - Collection of tools for the VGM (Video Game Music) file format, including conversion and inspection utilities.
* [gbsplay](https://github.com/mmitch/gbsplay) ⭐ 122 | 🐛 15 | 🌐 C | 📅 2026-08-17 - Game Boy sound player for GBS (Game Boy Sound) format music rips.
* [archive-follin](https://github.com/breakintoprogram/archive-follin) ⭐ 102 | 🐛 0 | 🌐 Python | 📅 2025-08-13 - Recovered assembler music source code and drivers written by Tim and Geoff Follin for NES/SNES/Genesis games at Software Creations (Silver Surfer, Plok, Solstice, and others), preserved from original 3" floppy disks.
  * Components: SymbTool, InfoTool, Nitro Studio GUI
* [adpcm](https://github.com/superctr/adpcm) ⭐ 101 | 🐛 0 | 🌐 C | 📅 2025-12-15 - ADPCM encoder/decoder library and CLI covering game/arcade sound-chip codecs: Yamaha ADPCM-A/B (YM2610/Y8950/YM2608), Yamaha AICA (Dreamcast), Oki/Dialogic VOX (MSM6295 arcade sound chip, MSM6258 X68000), Brian Schmidt BSMT2000/QSound (arcade), and YMZ280B.
* [vgm\_ripping](https://github.com/hcs64/vgm_ripping) ⭐ 95 | 🐛 3 | 🌐 C | 📅 2022-10-18 - Sources for game music ripping tools.
* [Citric-Composer](https://github.com/gota7/Citric-Composer) ⭐ 89 | 🐛 32 | 🌐 C# | 📅 2024-04-15 - Editor for 3DS, Wii U, and Switch sound files. See also [Tiniifan's fork](https://github.com/Tiniifan/Citric-Composer) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-04-15.
* [es-ps2-vag-tool](https://github.com/eurotools/es-ps2-vag-tool) ⭐ 46 | 🐛 3 | 🌐 C# | 📅 2026-06-13 - Tool to convert Sony PS2 VAG files to WAV PCM 16-bit encoding and vice versa.
* [pmdmini](https://github.com/mistydemeo/pmdmini) ⭐ 43 | 🐛 1 | 🌐 C++ | 📅 2022-10-04 - C/C++ library for playing back PMD/MXDRV chiptunes from the NEC PC-98, used by many PC-98-era games' Yamaha YM2203/YM2608 soundtracks.
* [wwise-audio-tools](https://github.com/WolvenKit/wwise-audio-tools) ⭐ 39 | 🐛 4 | 🌐 C++ | 📅 2024-01-26 - Static and dynamic library plus command-line tool for converting Wwise WEM files to OGG format. Modern replacement for ww2ogg and revorb with easier integration.
* [EZNSF](https://github.com/bbbradsmith/eznsf) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2023-04-22 - Tool for transforming NSF (NES Sound Format) music rip files into playable NES ROMs, using Python and the CC65 toolchain.
* [gc-dspadpcm-encode](https://github.com/jackoalan/gc-dspadpcm-encode) ⭐ 35 | 🐛 0 | 🌐 C | 📅 2023-10-23 - Nintendo GameCube DSP-ADPCM encoder tool.
* [Wwise-BNKExtract](https://github.com/rickvg/Wwise-BNKExtract) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2016-05-11 - Extraction utility for Wwise soundbank files (BNK format, file version 113 and earlier). Extracts WEM audio files for conversion to OGG Vorbis format.
* [QuattroPlay](https://github.com/superctr/QuattroPlay) ⭐ 31 | 🐛 4 | 🌐 C | 📅 2025-02-22 - Reimplementation of the Quattro sound driver used in Namco arcade games from the mid-1980s to late 1990s.
* [es-ima-adpcm-encoder-decoder](https://github.com/eurotools/es-ima-adpcm-encoder-decoder) ⭐ 24 | 🐛 0 | 🌐 C# | 📅 2025-12-08 - Tool to convert IMA ADPCM files to WAV PCM 16-bit encoding and vice versa.
* [manatools](https://github.com/dakrk/manatools) ⭐ 20 | 🐛 17 | 🌐 C++ | 📅 2025-08-17 - Tools for working with Dreamcast audio and music formats (MLT, MPB, MSB).
* [SDATTool](https://github.com/froggestspirit/SDATTool) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2025-02-11 - Tool for unpacking and packing Nintendo DS SDAT audio files (SSEQ sequences, SBNK banks, SWAR samples).
* [NitroTools](https://github.com/Gota7/NitroTools) ⭐ 20 | 🐛 2 | 🌐 C# | 📅 2018-12-23 - Toolkit for extracting and editing Nintendo DS SDAT audio.
* [PMDDotNET](https://github.com/kuma4649/PMDDotNET) ⭐ 20 | 🐛 0 | 🌐 C# | 📅 2025-12-20 - .NET port of PMD (Professional Music Driver), a widely-used sound driver/sequence format in PC-98 and other Japanese PC games.
* [mod2vgm](https://github.com/superctr/mod2vgm) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2024-08-18 - Converts Protracker MOD modules to VGM using the OPL4 chip, for use in game audio pipelines.
* [soundbank-editor](https://github.com/t1f7/soundbank-editor) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2016-07-04 - Python-based editor for Wwise soundbank files (.bnk). List, extract, and replace WEM sounds while preserving headers, events, and metadata. Works with any game using Wwise audio middleware.
* [WwiseParser](https://github.com/xyx0826/WwiseParser) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2025-09-11 - C# library for parsing Wwise 2016.1 SoundBank object formats. Supports deserializing Wwise objects, rebuilding hierarchies (Master-Mixer and Actor-Mixer), and dumping SoundBank files to JSON. Works with any game using Wwise audio middleware.
* [ZENSF](https://github.com/bbbradsmith/zensf) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2020-02-10 - Tool for building an NES ROM music album from a collection of NSF files using a custom expanded mapper (iNES Mapper 031). See also [EZNSF](https://github.com/bbbradsmith/eznsf) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2023-04-22 for an easier-to-use alternative.
* [gaxtapper](https://github.com/loveemu/gaxtapper) ⭐ 11 | 🐛 11 | 🌐 C++ | 📅 2024-08-31 - Automated GSF ripper for GAX Sound Engine. Extracts game audio from titles using GAX, outputting GSF format files.
* [MDXtract](https://github.com/Optiroc/MDXtract) ⭐ 11 | 🐛 0 | 🌐 HTML | 📅 2026-07-01 - Python tools for extracting instrument and sample data from files used by the MXDRV and PMD sound drivers, common across many Japanese PC-88/PC-98 games.
* [ray2get](https://github.com/Synthesis/ray2get) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2026-01-19 - Convert the .apm music files from Rayman 2 (PC) to .wav.
* [openpsf](https://github.com/myst6re/openpsf) ⭐ 8 | 🐛 3 | 🌐 C++ | 📅 2021-07-17 - Tiny library to stream PSF (Portable/PlayStation Sound Format) files.
  * See also [psflib](https://github.com/myst6re/psflib) ⭐ 1 | 🐛 1 | 🌐 C | 📅 2021-07-10 for a lower-level PSF reading library.
* [fsb5\_split](https://github.com/CyberBotX/fsb5_split) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2021-04-07 - Tool to split a multi-stream FSB5 into multiple single-stream FSB5s.
* [MCAConverter](https://github.com/onepiecefreak3/MCAConverter) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2024-07-31 - Converter for Capcom's MCA format. Converts MCA to WAVs and vice versa.
* [nsfid](https://github.com/karmic64/nsfid) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2025-07-03 - Play-routine/sound-driver identifier for binary music rips from computers and video game consoles (including NSF), matching byte-pattern signatures against a configurable driver database.
* [M1](https://github.com/enver-haase/M1) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2024-07-05 - Arcade and pinball music player by Richard Bannister, emulating original sound hardware to play back music directly from MAME-compatible ROM dumps across hundreds of unrelated arcade/pinball titles.
* [es-xbox-adpcm-tool](https://github.com/eurotools/es-xbox-adpcm-tool) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-06-13 - Tool to convert Xbox ADPCM files to WAV PCM 16-bit encoding and vice versa.
* [es-dsp-adpcm-tool](https://github.com/eurotools/es-dsp-adpcm-tool) ⭐ 5 | 🐛 1 | 🌐 C# | 📅 2022-09-25 - Nintendo GameCube DSP audio data encoder. Converts GameCube DSP ADPCM to WAV PCM 16-bit encoding and vice versa.
* [nitro-play](https://github.com/DanielPXL/nitro-play) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-18 - Parser for Nintendo DS SDAT audio format with music export.
* [libnus3audio](https://github.com/jam1garner/libnus3audio) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2022-08-23 - Rust library for working with nus3audio files.
* [oki-adpcm2](https://github.com/philpem/oki-adpcm2) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2026-03-22 - Reverse engineering and reimplementation of the OKI ADPCM2 compression scheme used by many arcade sound boards.
* [ntrWavTool](https://github.com/turtleisaac/ntrWavTool) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2023-04-05 - Converts WAV to IMA ADPCM SWAV for use in DS games.
* [Audio Overload SDK](https://github.com/hcs64/aosdk) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2021-01-22 - SDK for game audio format engines supporting QSF (Capcom), SSF (Sega Saturn), PSF/PSF2 (PlayStation), and DSF (Dreamcast) formats.
* [HIRCDump](https://github.com/neptuwunium/HIRCDump) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2022-01-23 - Dump soundbank samples via event IDs.
* [es-eurocom-adpcm-encoder-decoder](https://github.com/eurotools/es-eurocom-adpcm-encoder-decoder) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2023-08-23 - Tool to convert custom Eurocom ADPCM files to WAV PCM 16-bit encoding and vice versa.
* [nus3audio](https://github.com/jam1garner/nus3audio) ⚠️ Archived - Nus3audio container extractor and rebuilder (use vgmstream to handle the extracted idsp/opus streams). Archived but still functional.
* [dpcmtool](https://github.com/karmic64/dpcmtool) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2021-03-26 - NSF DPCM sample ripper and bit-reversal tool for NES audio.
  * See also karmic64's other retro audio format tools: [64vgmplay](https://github.com/karmic64/64vgmplay) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2020-10-27 (OPL1/2 VGM converter/player for the Commodore 64 SFX Sound Expander/FM-YAM), [makegsf](https://github.com/karmic64/makegsf) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2023-12-21 (scriptable GSF/miniGSF creator for GBA sound rips), [nsf2nes](https://github.com/karmic64/nsf2nes) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2021-03-01 (NSF-to-NES-ROM converter), [KokonoePlayer-Lite](https://github.com/karmic64/KokonoePlayer-Lite) ⭐ 2 | 🐛 0 | 🌐 Assembly | 📅 2024-01-04 (Sega Genesis/Mega Drive VGM player with sample support), and [snes-mod-player](https://github.com/karmic64/snes-mod-player) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-03-16 (Amiga MOD converter/player for SNES).
* [atrac9j](https://github.com/ShadelessFox/atrac9j) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2026-01-10 - Java port of the LibAtrac9 library for decoding ATRAC9 audio format used in PlayStation games.
* [DSP2BRSTM](https://github.com/onepiecefreak3/DSP2BRSTM) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2018-08-01 - Converter and multichannel creator for DSP to BRSTM. Merges multiple DSP files into one multichannel BRSTM. Also supports DSP to WAV conversion.
* [Fmod5Sharp](https://github.com/Masusder/Fmod5Sharp) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-01-23 - Managed C# library for decoding FMOD 5 sound banks (FSB files).
* [vgmstream-funkify](https://github.com/gheskett/vgmstream-funkify) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2021-02-02 - vgmstream library for playback of various streamed audio formats used in video games.
* Formats: PCM8, PCM16, PCM32, GCADPCM, IMAADPCM, VORBIS
* Exports: WAV (PCM formats), OGG (Vorbis)
* Features: Sample extraction, metadata reading, format detection

### 🌐 Translation & Localization

* [Kuriimu2](https://github.com/FanTranslatorsInternational/Kuriimu2) ⭐ 430 | 🐛 166 | 🌐 C# | 📅 2026-08-18 - Next-gen version of Kuriimu.
* [Kuriimu](https://github.com/IcySon55/Kuriimu) ⭐ 374 | 🐛 111 | 🌐 C# | 📅 2023-08-04 - General purpose game translation toolkit.
* [jstrings](https://github.com/drojaazu/jstrings) ⭐ 43 | 🐛 0 | 🌐 C++ | 📅 2023-01-03 - Tool for finding JIS-based Japanese text strings in binary data, useful for locating text in Japanese game files.
* [TF3 (Translation Framework 3)](https://github.com/Kaplas80/TF3) ⭐ 21 | 🐛 12 | 🌐 C# | 📅 2024-09-03 - General-purpose game translation framework with per-game plugins, including [Yakuza](https://github.com/Kaplas80/TF3.YakuzaPlugins) ⭐ 5 | 🐛 1 | 🌐 C# | 📅 2023-04-01 and [Zwei](https://github.com/Kaplas80/TF3.ZweiPlugins) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2022-08-20 series plugins.

### 🔍 Hex Editors

* [010 Editor](https://www.sweetscape.com/010editor/) - Professional hex editor with powerful template system for analyzing binary file structures (paid).
* [ImHex](https://github.com/WerWolv/ImHex) ⭐ 54,499 | 🐛 386 | 🌐 C++ | 📅 2026-08-19 - Modern, open-source hex editor with pattern language for reverse engineering file formats (free).

#### Scripts & Templates

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,259 | 🐛 34 | 🌐 Rust | 📅 2026-04-30 - Command-line hex viewer with colored output.
* [WpfHexEditorIDE](https://github.com/abbaye/WpfHexEditorIDE) ⭐ 928 | 🐛 15 | 🌐 C# | 📅 2026-06-29 - Full-featured binary analysis IDE for Windows built with WPF and .NET. Features VS-style docking, project system, and multiple specialized editors.
* [hexerator](https://github.com/crumblingstatue/hexerator) ⭐ 368 | 🐛 26 | 🌐 Rust | 📅 2026-08-08 - Versatile GUI hex editor focused on binary file exploration and aiding pattern recognition. Written in Rust.
* [binxelview](https://github.com/bbbradsmith/binxelview) ⭐ 249 | 🐛 5 | 🌐 C# | 📅 2026-08-18 - Binary image explorer that renders raw binary data as a bitmap at adjustable width/bit-depth/palette, for visually spotting embedded graphics data inside ROMs and other game files.
* [hxd-plugin-framework](https://github.com/maelh/hxd-plugin-framework) ⭐ 188 | 🐛 6 | 🌐 Pascal | 📅 2022-02-11 - Plugin framework for HxD hex editor to support custom file formats.
* [Alpha-Offset-Fixer](https://github.com/alphazolam/Alpha-Offset-Fixer) ⭐ 1 | 🐛 0 | 🌐 Roff | 📅 2021-10-04 - 010 Editor script to help with relative offsets in binary templates.
* [hex](https://github.com/cosarara/hex) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2014-09-26 - Simple hexadecimal editor with vi-like modal interface.
* [xcd-rgb](https://anongit.hacktivis.me/git/xcd-rgb.git) - Command-line hexdump with colored output, based on [xcd](https://git.sr.ht/~breadbox/xcd).

### 🔬 Format Analysis & Reverse Engineering

#### Binary Templates & Format Descriptions

* [fq](https://github.com/wader/fq) ⭐ 10,564 | 🐛 57 | 🌐 Go | 📅 2026-08-17 - "jq for binary formats" - command-line tool, language, and decoder collection for querying and inspecting binary and text formats, useful for ad-hoc exploration of unfamiliar game file formats.
* [ImHex-Patterns](https://github.com/WerWolv/ImHex-Patterns) ⭐ 996 | 🐛 48 | 🌐 Rust | 📅 2026-08-18 - Binary format pattern database for ImHex hex editor, with game file format definitions and reverse-engineering templates.
* [bitfield](https://github.com/wavedrom/bitfield) ⭐ 394 | 🐛 19 | 🌐 JavaScript | 📅 2024-02-22 - Tool for rendering bit field diagrams from JSON descriptions, useful for documenting binary formats.
* [010-Editor-Templates](https://github.com/tge-was-taken/010-Editor-Templates) ⭐ 54 | 🐛 3 | 🌐 C++ | 📅 2026-03-01 - Collection of 010 Editor binary templates for game file format analysis.
* [010GameTemplates](https://github.com/Nenkai/010GameTemplates) ⭐ 43 | 🐛 0 | 🌐 C# | 📅 2026-06-18 - Collection of 010 Editor templates for various games including Gran Turismo, Forza, Project Cars, Ridge Racer 7, Tales of Vesperia, Xenoblade Chronicles, Granblue Fantasy: Relink, Driveclub, WWE 2K, and many others.
* [hogsy/formats](https://github.com/hogsy/formats) ⭐ 10 | 🐛 0 | 🌐 Assembly | 📅 2025-12-03 - Collection of reversed binary format specifications in [Rehex](https://github.com/solemnwarning/rehex) ⭐ 2,476 | 🐛 26 | 🌐 C++ | 📅 2026-07-23 Binary Template format, covering games from many studios.
  * Features: Templates are easily translatable to C/C++; related loader implementations in the [Hei library](https://github.com/QuartermindGames/hei) ⭐ 23 | 🐛 4 | 🌐 C | 📅 2026-08-12.
  * Studios/Games: Acclaim (Vista 3D engine: Turok Evolution; Unknown engine: Burnout?), Blitz Games/BlitzTech 1 (Glover, Chicken Run, Frogger 2, Action Man), BottleRocket (The Mark of Kri, Rise of the Kasai, Xiaolin Showdown), Core Design (Project Eden, Herdy Gerdy), Computer Artworks (The Thing, Evolva), Creative Reality (Martian Gothic: Unification), Gee Whiz! (Zombie Wars), Guerrilla Cambridge / Millennium Interactive (C-12: Final Resistance), Infogrames/Gremlin Interactive (Hogs of War), Lucasfilm Games (Ares Engine), Midway Studios Austin / Inevitable Entertainment (The Hobbit 2003, Area 51), nStigate/Nihilistic (Vampire: The Masquerade – Redemption), Oddworld Inhabitants (Stranger's Wrath), SCE Studio Cambridge (Primal), SingleTrac (Outwars), Tate Interactive, Team Ico, Traveller's Tales (Haven: Call of the King), Appeal S.A. (Outcast).
  * Formats: DAT, PSI, SPT, WAD, CLU, HGT, ACW, EDN, PAK, MSH, GFX/TEX, MIN, DFS, NOD, and more.
* [astraea](https://github.com/aethelwerks/astraea) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2020-07-24 - Framework and scripting language for reverse engineering and describing binary file formats.
* [010 Templates / ImHex Patterns](https://github.com/neptuwunium/bt) ⚠️ Archived - Templates for binary analysis.
* [GameRes010Templates](https://github.com/miccTronic/GameRes010Templates) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-06-26 - 010 Editor templates for reading resource files from various games.
  * Games: LithTech 5/Monolith (F.E.A.R. 2, Condemned 2), Asura Engine/Rebellion (Aliens vs. Predator 2010), Unreal Engine 1/2 (Thief: Deadly Shadows, Deus Ex: Invisible War), Incubation (Blue Byte, 1997), Nocturne/Demon Engine/Terminal Reality (Nocturne, Blair Witch I/II/III), King's Quest VIII: The Mask of Eternity.
* [mafia-formats](https://github.com/pudingus/mafia-formats) ⭐ 1 | 🐛 0 | 📅 2020-11-18 - 010 Editor templates for Mafia: The City of Lost Heaven file formats.
* [gsaxml](https://github.com/Candoran2/gsaxml) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-08-26 - XML description of the binary format of compiled GSA (Game Script Archive) files.
* [gameyaml](https://github.com/Herringway/gameyaml) ⭐ 0 | 🐛 0 | 🌐 PowerShell | 📅 2023-09-26 - YAML documentation of internal data structures for a dozen classic RPGs (Chrono Trigger, Dragon Warrior Monsters, EarthBound, Final Fantasy IV/V/VI, Golden Sun, Kirby Super Star, Mother 2/3, Out of This World, Pokemon, Paper Mario, Super Mario Bros, Super Mario World).
* [Kaitai Struct](https://kaitai.io/) - Declarative language for describing binary data structures with code generation for multiple programming languages.

#### Disassemblers, Decompilers & Analysis Frameworks

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) ⭐ 72,502 | 🐛 1,917 | 🌐 Java | 📅 2026-08-18 - NSA's software reverse engineering (SRE) framework. Includes disassembly, assembly, decompilation, graphing, and scripting. Extensible through Java and Python plugins.
* [Cutter](https://github.com/rizinorg/cutter) ⭐ 19,475 | 🐛 493 | 🌐 C++ | 📅 2026-08-13 - Free and open-source GUI-based reverse engineering platform powered by Rizin, for analyzing game binaries and file formats.
* [RetDec](https://github.com/avast/retdec) ⭐ 8,606 | 🐛 458 | 🌐 C++ | 📅 2026-05-26 - Retargetable machine-code decompiler based on LLVM, supporting multiple architectures and file formats — useful for reverse engineering game binaries. Currently in limited maintenance.
* [qiling](https://github.com/qilingframework/qiling) ⭐ 6,064 | 🐛 123 | 🌐 Python | 📅 2026-07-22 - Advanced binary emulation framework. Emulates multi-platforms (Windows, macOS, Linux, Android, BSD, UEFI, DOS) and multi-architectures (x86, ARM, MIPS, RISC-V, PowerPC). Supports PE, Mach-O, ELF formats with fine-grain instrumentation, cross-architecture debugging, and dynamic hot patching.
* [Steamless](https://github.com/atom0s/Steamless) ⭐ 4,972 | 🐛 25 | 🌐 C# | 📅 2024-03-30 - DRM remover for the SteamStub packer variants, unpacking Steam-protected game executables to enable further static/dynamic analysis of the underlying binary.
* [diaphora](https://github.com/joxeankoret/diaphora) ⭐ 4,370 | 🐛 35 | 🌐 Python | 📅 2026-08-18 - Advanced binary diffing tool (IDA/Binary Ninja/Ghidra) for comparing game binaries across versions/patches, widely used in game reverse engineering workflows.
* [iced](https://github.com/icedland/iced) ⭐ 3,548 | 🐛 56 | 🌐 Rust | 📅 2026-08-17 - Blazing fast and correct x86/x64 disassembler, assembler, decoder, and encoder. Available for Rust, .NET, Java, Python, and Lua. Useful for reverse engineering game binaries.
* [SafeDiscShim](https://github.com/RibShark/SafeDiscShim) ⭐ 563 | 🐛 36 | 🌐 C++ | 📅 2025-09-29 - Compatibility tool that allows SafeDisc-protected games relying on the insecure Macrovision Security Driver (secdrv.sys) to run on modern versions of Windows, enabling further analysis of the underlying game binaries.
* [ProjectorRays](https://github.com/ProjectorRays/ProjectorRays) ⭐ 289 | 🐛 13 | 🌐 C++ | 📅 2025-11-13 - Decompiler for Adobe/Macromedia Shockwave and Director movies (.dcr/.dir), used across many CD-ROM-era multimedia and point-and-click games.
* [Ouroboros](https://github.com/Hexorg/Ouroboros) ⭐ 258 | 🐛 2 | 🌐 Rust | 📅 2025-12-02 - Symbolic-execution decompiler written in Rust. Recovers high-level structure from binaries using symbolic execution and constraint tracking. Features CFG recovery, structural reconstruction (if/else, loops), calling convention inference, and beautiful UI with egui.
* [Mizuchi](https://github.com/macabeus/mizuchi) ⭐ 72 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-17 - Automatic decompilation tool using plugin-based pipeline to convert assembly to C source code matching binary targets.
* [Pattern16](https://github.com/Dasaav-dsv/Pattern16) ⭐ 53 | 🐛 4 | 🌐 C++ | 📅 2024-01-07 - Fastest x86-64 signature matching library. Optimized for reverse engineering with speeds up to 25 GB/s. Uses AVX1, SSE4.1, SSE2, CMOVE, BMI2, and BMI1. Header-only C++ library for pattern scanning in memory regions.
* [zoltan](https://github.com/jac3km4/zoltan) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - Generates DWARF debug symbols and headers on the fly for reverse engineering game executables, by matching annotated C/C++ pattern signatures against a target binary.
* [Arm64Disassembler](https://github.com/neptuwunium/Arm64Disassembler) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-12-20 - Lightweight C# Arm64 disassembler library.
* [atlas](https://github.com/nblockbuster/atlas) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-06-15 - Hashing tool for reverse engineering work. Plugin-based system supporting FNV (0, 1, 1a), MD2/MD4/MD5, Murmur2/3, SipHash, SHA1/SHA2/SHA3, XXHash/XXHash3. Useful for analyzing hashed values in game file formats.
* [hlsldecompiler-rs](https://github.com/cohaereo/hlsldecompiler-rs) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-04-11 - Statically linked 3dmigoto Rust wrapper for HLSL shader decompilation.
* [ExeGag](https://github.com/efimandreev0/ExeGag) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-03-08 - Tool to edit game strings into compiled ELF files.
* [BinaryX](https://github.com/Cuyler36/BinaryX) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2020-12-12 - BinaryReader capable of reading both BigEndian and LittleEndian schemes.

#### IDA / Hex-Rays Plugins

* [HexRaysCodeXplorer](https://github.com/REhints/HexRaysCodeXplorer) ⭐ 2,638 | 🐛 16 | 🌐 C++ | 📅 2025-11-27 - Hex-Rays Decompiler plugin for better code navigation in reverse engineering. Automates code reconstruction of C++ applications and modern malware. Features include automatic type reconstruction, virtual function table detection, and RTTI analysis.
* [IDArling](https://github.com/IDArlingTeam/IDArling) ⚠️ Archived - Collaborative reverse engineering plugin for IDA Pro and Hex-Rays. Enables multiple users to work on the same IDA database simultaneously.
* [FakePDB](https://github.com/Mixaill/FakePDB) ⭐ 641 | 🐛 29 | 🌐 C++ | 📅 2025-12-10 - Tool for PDB generation from IDA Pro database. Supports IDA >= 7.0. Can generate PDB files, export IDA database to JSON, find binary signatures, and import function names from JSON.
* [microavx](https://github.com/gaasedelen/microavx) ⭐ 332 | 🐛 4 | 🌐 Python | 📅 2023-04-28 - AVX lifter for the Hex-Rays Decompiler. Extends IDA Pro decompiler with partial support for Intel Advanced Vector Extensions (AVX) instructions. Demonstrates how Hex-Rays microcode can be used to lift and decompile new or previously unsupported instructions.
* [HexForge](https://github.com/elastic/HexForge) ⭐ 86 | 🐛 1 | 🌐 Python | 📅 2025-05-31 - IDA plugin that extends the functionality of the assembly and hex view, allowing you to decode/decrypt/alter data directly from the IDA Pro interface.
* [ida-images](https://github.com/rr-/ida-images) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2022-09-17 - Image preview plugin for the IDA disassembler, previewing embedded raster images directly in the binary view.

#### Managed & Bytecode Decompilers (.NET / Java / Script)

* [dnSpy](https://github.com/dnSpy/dnSpy) ⚠️ Archived - .NET debugger and assembly editor. Essential for inspecting and editing .NET game binaries (Unity games, etc.) even without source code. Supports decompilation to C#.
* [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) ⭐ 15,600 | 🐛 103 | 🌐 Java | 📅 2026-07-17 - A Java 8+ Jar & Android APK reverse engineering suite. Includes multiple decompilers (FernFlower, Procyon, CFR), bytecode assemblers, and a keyword search feature.
* [jd-gui](https://github.com/java-decompiler/jd-gui) ⭐ 15,176 | 🐛 248 | 🌐 Java | 📅 2024-07-08 - A standalone graphical utility that decompile and displays Java source codes of .class files. Supports Drag and Drop and Zip/Jar files.
* [Recaf](https://github.com/Col-E/Recaf) ⭐ 7,337 | 🐛 67 | 🌐 Java | 📅 2026-08-17 - Modern Java bytecode editor. Easy-to-use interface for editing Java bytecode with decompiler integration, built-in compiler, bytecode assembler, and support for standard Java and Android applications.
* [JPEXS Free Flash Decompiler](https://github.com/jindrapetrik/jpexs-decompiler) ⭐ 5,817 | 🐛 5 | 🌐 Java | 📅 2026-08-08 - Free Flash (SWF) decompiler/editor for viewing and modifying ActionScript 1/2/3 bytecode, shapes, sprites, sounds, and other tags in SWF files, widely used for reverse-engineering Flash-based games.
* [hermes-dec](https://github.com/P1sec/hermes-dec) ⭐ 1,146 | 🐛 7 | 🌐 Python | 📅 2026-08-11 - Decompiler and disassembler for React Native Hermes bytecode (HBC).
* [JSC-PyDecrypt-Tool](https://github.com/bartlomiejduda/JSC-PyDecrypt-Tool) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2025-10-13 - Decrypts JSC (JavaScript Compiled) files from Cocos2d games. Requires valid encryption key extracted via Frida from running game instances.
* [UnityDowngradingTools](https://github.com/efimandreev0/UnityDowngradingTools) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-22 - Utility tools for fixing and adapting AssetRipper decompiles to older Unity versions (e.g., PS Vita Sally Face port).
* [unluac](https://sourceforge.net/projects/unluac/) - A decompiler for Lua 5.1. Capability to decompile most Lua 5.1 binaries, including those with custom opcodes or modified headers found in various games.

#### Decompilation Project Toolchains

* [m2c](https://github.com/matt-kempster/m2c) ⭐ 624 | 🐛 62 | 🌐 Python | 📅 2026-08-15 - MIPS and PowerPC decompiler.
* [decomp.me](https://github.com/decompme/decomp.me) ⭐ 600 | 🐛 128 | 🌐 TypeScript | 📅 2026-08-16 - Collaborative decompilation and reverse engineering website, widely used to reverse game binaries function-by-function against a reference build.
* [objdiff](https://github.com/encounter/objdiff) ⭐ 518 | 🐛 88 | 🌐 Rust | 📅 2026-08-17 - Local diffing tool for decompilation projects.
* [splat](https://github.com/ethteck/splat) ⭐ 348 | 🐛 41 | 🌐 Python | 📅 2026-07-27 - Binary splitting tool to assist with decompilation and modding projects.
* [decomp-toolkit](https://github.com/encounter/decomp-toolkit) ⭐ 278 | 🐛 30 | 🌐 Rust | 📅 2026-03-02 - GameCube & Wii decompilation toolkit.
* [decomp-permuter](https://github.com/simonlindholm/decomp-permuter) ⭐ 211 | 🐛 48 | 🌐 Python | 📅 2026-08-05 - Randomly permute C files to better match a target binary.
* [ccc](https://github.com/chaoticgd/ccc) ⭐ 105 | 🐛 2 | 🌐 C++ | 📅 2026-06-07 - Library and command-line tools for parsing debugging symbols from PS2 games, focused on STABS symbols embedded in .mdebug ELF sections; aids recovery of function/struct names for decompilation projects.
* [ds-decomp](https://github.com/AetiasHax/ds-decomp) ⭐ 84 | 🐛 9 | 🌐 Rust | 📅 2026-08-14 - Toolkit for decompiling Nintendo DS games, with ROM extraction, building, symbol analysis, and asset handling tools.
* [spimdisasm](https://github.com/Decompollaborate/spimdisasm) ⭐ 77 | 🐛 7 | 🌐 Python | 📅 2026-08-06 - MIPS disassembler used across N64 decompilation projects to produce matching assembly.
* [dwarf2cpp](https://github.com/seilc/dwarf2cpp) ⚠️ Archived - Converts DWARF v1 debug data from ELF files into C/C++ definitions including structs, enums, unions, and function definitions. Useful for reverse engineering games with DWARF debug information.
* [libgfxd](https://github.com/glankk/libgfxd) ⭐ 15 | 🐛 2 | 🌐 C | 📅 2025-10-29 - Display list decompiler library, the de facto N64 F3D/F3DEX display list disassembler underlying gfxd-rs above.
* [delink](https://github.com/HaydnTrigg/delink) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 - Symbol splitting tool for decompilation projects, supporting ELF (DWARF), Mach-O (STABS/SYMTAB), and PE (PDB) binary formats.
* [objdiff-web](https://github.com/encounter/objdiff-web) ⭐ 11 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-10 - Web interface and VS Code extension for objdiff, a local diffing tool for decompilation projects.
* [research](https://github.com/ProjectDreamland/research) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2016-02-24 - Research on game engine and decompiled game code.
* [libgcc\_vr4300](https://github.com/Decompollaborate/libgcc_vr4300) ⭐ 8 | 🐛 4 | 🌐 C | 📅 2023-11-17 - Subset of GCC's libgcc rebuilt for the MIPS VR4300 CPU (Nintendo 64), used by N64 decompilation projects to match compiler-emitted intrinsic/runtime routines.
* [pygfxd](https://github.com/Thar0/pygfxd) ⭐ 8 | 🐛 1 | 🌐 C | 📅 2026-03-14 - Python 3 bindings for libgfxd using ctypes.
* [zea](https://github.com/Decompollaborate/zea) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2022-10-21 - Matching (de)compression implementations for Nintendo's MIO0, YAY0, and YAZ0 cartridge compression algorithms, used across N64/GameCube-era Mario and Zelda titles for decompilation and asset extraction.
* [gnuv2\_demangle](https://github.com/Decompollaborate/gnuv2_demangle) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-11-09 - Demangler for GNU v2 (GCC 2.x) C++ mangled symbol names, used when recovering readable symbol names in decompilation projects for games built with old GCC toolchains (e.g. N64/PS1-era titles).
* [address\_space](https://github.com/Decompollaborate/address_space) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-05-11 - Rust crate providing types for MIPS ROM and VRAM address spaces, sizes, and ranges, used by N64 decompilation tooling (e.g. alongside mapfile\_parser) for matching original compiled code.
* [gfxd-rs](https://github.com/Decompollaborate/gfxd-rs) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-11-16 - Safe Rust wrapper for glankk's libgfxd, the de facto N64 F3D/F3DEX display list disassembler, built on the gfxd-sys FFI bindings crate. Used in N64 decompilation projects to disassemble Fast3D graphics microcode.
* [texture2c](https://github.com/Decompollaborate/texture2c) ⭐ 1 | 🐛 7 | 🌐 C | 📅 2023-04-26 - Converts Nintendo 64 texture formats to C source/data arrays for use in N64 decompilation and modding projects.

#### Static Recompilation

* [XenonRecomp](https://github.com/hedge-dev/XenonRecomp) ⭐ 6,443 | 🐛 90 | 🌐 C++ | 📅 2025-08-04 - Tool for recompiling Xbox 360 games to native executables. Converts Xbox 360 executables into C++ code that can be recompiled for any platform.
* [PS2Recomp](https://github.com/ran-j/PS2Recomp) ⭐ 3,178 | 🐛 59 | 🌐 C++ | 📅 2026-08-18 - Static recompiler and runtime that converts PlayStation 2 ELF binaries into C++ to produce native PC ports.
* [SR (Static Recompiler)](https://github.com/M-HT/SR) ⭐ 407 | 🐛 12 | 🌐 C | 📅 2026-08-16 - Static recompilation project that converts several classic DOS games into native Windows/Linux (x86/ARM) ports (Albion, Septerra Core, X-COM, Warcraft: Orcs & Humans, and others).
* [NWiiRecomp](https://github.com/BlackLineInteractive/NWiiRecomp) ⭐ 23 | 🐛 0 | 🌐 C++ | 📅 2026-08-07 - Static recompilation and runtime toolkit for Nintendo GameCube and Wii binaries, for building native PC ports.
* [nWiiURecomp](https://github.com/BlackLineInteractive/nWiiURecomp) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2026-08-05 - Static recompilation and runtime toolkit for Nintendo Wii U binaries (based on NWiiRecomp), for building native PC ports.
* [SHO-GTA-VCS-PS2Recomp](https://github.com/BlackLineInteractive/SHO-GTA-VCS-PS2Recomp) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-08-05 - Application of PS2Recomp specifically tailored with function maps/configs to statically recompile Silent Hill Origins and GTA: Vice City Stories.

#### Ghidra & IDA Platform Loaders

* [Ghidra-Switch-Loader](https://github.com/Adubbz/Ghidra-Switch-Loader) ⭐ 365 | 🐛 9 | 🌐 Java | 📅 2026-06-22 - Ghidra loader extension for Nintendo Switch executable formats (NCA, XCI), enabling decompilation and reverse engineering of Switch games.
* [ghidra\_psx\_ldr](https://github.com/lab313ru/ghidra_psx_ldr) ⭐ 323 | 🐛 14 | 🌐 Java | 📅 2026-07-09 - PlayStation 1 binary loader for Ghidra.
* [Ghidra-GameCube-Loader](https://github.com/Cuyler36/Ghidra-GameCube-Loader) ⭐ 319 | 🐛 21 | 🌐 Java | 📅 2026-05-24 - Nintendo GameCube binary loader for Ghidra reverse engineering framework.
* [ghidra-emotionengine-reloaded](https://github.com/chaoticgd/ghidra-emotionengine-reloaded) ⭐ 229 | 🐛 11 | 🌐 Java | 📅 2026-06-20 - Ghidra extension adding PlayStation 2 (Emotion Engine) support, including the MIPS R5900 processor with VU macromode and PS2 ELF/IRX loaders.
* [idaxex](https://github.com/emoose/idaxex) ⭐ 213 | 🐛 7 | 🌐 C++ | 📅 2026-08-11 - XEX/XBE loader plugin for IDA 9, plus the xex1tool CLI, supporting most known Xbox and Xbox 360 executable file formats.
* [XEXLoaderWV](https://github.com/zeroKilo/XEXLoaderWV) ⭐ 169 | 🐛 4 | 🌐 Java | 📅 2026-08-01 - Ghidra loader module for Xbox 360 XEX executable files.
* [N64LoaderWV](https://github.com/zeroKilo/N64LoaderWV) ⭐ 166 | 🐛 1 | 🌐 Java | 📅 2026-08-01 - Ghidra loader module for Nintendo 64 ROMs.
* [ghidra-gekko-broadway-lang](https://github.com/aldelaro5/ghidra-gekko-broadway-lang) ⭐ 134 | 🐛 4 | 📅 2022-02-09 - Ghidra processor language for Gekko/Broadway CPU (GameCube/Wii) disassembly and decompilation.
* [ghidra-allegrex](https://github.com/kotcrab/ghidra-allegrex) ⭐ 129 | 🐛 5 | 🌐 Kotlin | 📅 2026-07-24 - Ghidra processor module adding support for the Allegrex CPU (PSP).
* [GhidraOrbis](https://github.com/astrelsky/GhidraOrbis) ⭐ 86 | 🐛 0 | 🌐 Java | 📅 2026-06-24 - Ghidra support for Orbis OS (PlayStation 4) specific software and file formats.
* [Ghidra-SegaSaturn-Loader](https://github.com/VGKintsugi/Ghidra-SegaSaturn-Loader) ⭐ 55 | 🐛 9 | 🌐 Java | 📅 2025-12-29 - Sega Saturn binary loader for Ghidra.
* [VitaLoaderRedux](https://github.com/CreepNT/VitaLoaderRedux) ⭐ 49 | 🐛 4 | 🌐 Java | 📅 2025-12-28 - PlayStation Vita ELF-PRX loader for Ghidra. Successor to the deprecated [VitaLoader](https://github.com/CreepNT/VitaLoader) ⚠️ Archived.
* [GhidraSPU](https://github.com/aerosoul94/GhidraSPU) ⭐ 30 | 🐛 1 | 🌐 Java | 📅 2023-07-07 - SPU processor implementation for Ghidra (PlayStation 3 Cell).
* [GhidraProspero](https://github.com/astrelsky/GhidraProspero) ⭐ 13 | 🐛 0 | 🌐 Java | 📅 2026-01-13 - Ghidra support for Prospero OS (PlayStation 5).
* [ghidra\_mdebug](https://github.com/astrelsky/ghidra_mdebug) ⚠️ Archived - Ghidra analyzer adding support for the .mdebug debugging symbol format (PS2/MIPS).
* [libNidResolver](https://github.com/astrelsky/libNidResolver) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2024-04-07 - Library for resolving PlayStation 5 (Prospero) NIDs in another process, aiding GhidraProspero-based analysis.
* [Ghidra-RSP](https://github.com/Random06457/Ghidra-RSP) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2024-09-18 - Nintendo 64 RSP processor module and loader for Ghidra.
* [ghidra-delinker-extension](https://github.com/widberg/ghidra-delinker-extension) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2026-04-22 - Ghidra extension for delinking executables into relocatable object files. Supports ELF and PE formats, enabling the extraction of functions or data into object files for recompilation or integration into other projects.
* [NTRGhidra](https://github.com/onepiecefreak3/NTRGhidra) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2025-09-28 - Nintendo DS binary loader for Ghidra reverse engineering framework.

#### Binary Visualization & Diffing

* [pics](https://github.com/corkami/pics) ⭐ 11,471 | 🐛 5 | 🌐 Assembly | 📅 2024-02-18 - File formats dissections and visualizations for reverse engineering.
* [binocle](https://github.com/sharkdp/binocle) ⭐ 1,315 | 🐛 25 | 🌐 Rust | 📅 2025-01-21 - Graphical binary data visualization tool. Colorizes bytes and renders them as pixels to identify patterns and image-like structures in game files.
* [Veles](https://github.com/codilime/veles) ⚠️ Archived - Binary analysis and visualization tool for reverse engineering (open-source, archived; the codisec.com site is gone).
* [biodiff](https://github.com/8051Enthusiast/biodiff) ⭐ 892 | 🐛 6 | 🌐 Rust | 📅 2024-08-07 - Hex diff viewer that uses alignment algorithms to show differences between binary files.
* [DataExplorer](https://github.com/x64dbg/DataExplorer) ⭐ 92 | 🐛 0 | 🌐 C | 📅 2026-03-15 - Data explorer plugin for x64dbg debugger that integrates the pattern language from ImHex.
* [binviz](https://github.com/VelocityRa/binviz) ⭐ 47 | 🐛 3 | 🌐 C++ | 📅 2021-08-05 - Binary visualization tool for identifying patterns and structure in unknown files. Creates visual representations showing potential compression/encryption, structured data and padding at a glance. Helpful for spotting where assets begin/end in unstructured archives.
* [bdiff](https://github.com/ethteck/bdiff) ⭐ 25 | 🐛 17 | 🌐 Rust | 📅 2024-11-04 - Binary diff tool for decompilation and modding projects with hex viewing and symbol map integration.
* [Monkey-Moore](https://github.com/rjricken/monkey-moore) ⭐ 20 | 🐛 1 | 🌐 C++ | 📅 2026-06-09 - High-performance pattern matching utility for ROM hacking and reverse engineering. Multi-threaded Boyer-Moore algorithm with wildcard support and endianness control for discovering non-standard text encodings.
* [Bin2Obj](https://github.com/hogsy/Bin2Obj) ⚠️ Archived - Converts arbitrary binary data into a Wavefront OBJ point cloud, useful for spotting vertex/mesh data when reverse-engineering unknown formats.

#### Hooking, Memory & Runtime Tools

* [PINCE](https://github.com/korcankaraokcu/PINCE) ⭐ 3,063 | 🐛 6 | 🌐 Python | 📅 2026-08-15 - GDB front-end/reverse engineering tool with a Cheat Engine-like interface for Linux.
* [Reloaded-II](https://github.com/Reloaded-Project/Reloaded-II) ⭐ 1,010 | 🐛 182 | 🌐 C# | 📅 2026-08-13 - Universal .NET Core powered modding framework for any native game (x86, x64). DLL injection based mod loader with mod management system, optional mod SDK, and extensive plugin support.
* [ReClassEx](https://github.com/ajkhoury/ReClassEx) ⭐ 929 | 🐛 8 | 🌐 C++ | 📅 2021-07-05 - ReClass Extended, a fork of ReClass with additional features for reverse engineering in-memory class/struct layouts of running game processes, aiding recovery of file format structures.
* [hooking](https://github.com/alphaSeclab/hooking) ⭐ 343 | 🐛 0 | 📅 2020-06-11 - Massive repository of resources about hooking for all platforms (Windows, Linux, Android, iOS). Includes 300+ tools and 600+ articles.
* [Reloaded.Hooks](https://github.com/Reloaded-Project/Reloaded.Hooks) ⭐ 254 | 🐛 8 | 🌐 C# | 📅 2024-11-29 - Advanced native function hooks for x86 and x64. High-performance hooking library for .NET with support for unit testing hooks. Used in Reloaded modding framework.
* [ReClass.NET](https://github.com/FransBouma/ReClass.NET) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2023-07-04 - Advanced memory class layout reverse engineering tool widely used for analyzing in-memory game data structures, helping translate runtime structures into file format definitions.

#### Console-specific RE (PlayStation / Xbox)

* [pcsx-redux](https://github.com/grumpycoders/pcsx-redux) ⭐ 982 | 🐛 152 | 🌐 C++ | 📅 2026-08-12 - Collection of tools, research, hardware design, and libraries for PlayStation 1 development and reverse engineering, built around a fork of the PCSX emulator with an integrated debugger, assembler, and GPU/memory analysis tooling.
* [Ghidra-Cpp-Class-Analyzer](https://github.com/astrelsky/Ghidra-Cpp-Class-Analyzer) ⚠️ Archived - Ghidra C++ Class and Run Time Type Information (RTTI) analyzer, useful for recovering class hierarchies in game binaries compiled from C++.
* [psxprev](https://github.com/rickomax/psxprev) ⭐ 257 | 🐛 28 | 🌐 C# | 📅 2023-11-09 - Playstation (PSX) Files Previewer and Extractor. Supports various model, texture, and animation formats.
* [Velocity](https://github.com/hetelek/Velocity) ⭐ 242 | 🐛 57 | 🌐 C++ | 📅 2025-10-21 - Cross-platform Xbox 360 file browser/editor (STFS containers, profiles, and more) built on the XboxInternals library.
* [psxrev](https://github.com/emu-russia/psxrev) ⭐ 159 | 🐛 12 | 🌐 C# | 📅 2025-01-20 - Sony PlayStation PCB/chips reverse engineering documentation and resources.
* [ida\_gel](https://github.com/aerosoul94/ida_gel) ⭐ 106 | 🐛 2 | 🌐 C | 📅 2019-10-03 - Collection of IDA loaders for various game console ELF files (PS3, PS Vita, Wii U).
* [xbox-reversing](https://github.com/emoose/xbox-reversing) ⭐ 78 | 🐛 2 | 🌐 Python | 📅 2024-10-22 - Tools and documentation for reverse engineering Xbox 360 file formats. Includes IDA Pro loaders and 010 Editor templates for STFS, GDFX, XDBF, and XEX format analysis.
* [xbox-winfsp](https://github.com/emoose/xbox-winfsp) ⭐ 78 | 🐛 11 | 🌐 C# | 📅 2024-02-27 - Brings native support for Xbox filesystems (FATX, STFS, GDFX/XGD/XDVDFS) to Windows via WinFsp.
* [vitadump](https://github.com/xyzz/vitadump) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2017-11-30 - Tools to assist working with memory dumps obtained from PS Vita.
* [SPRXPatcher](https://github.com/NotNite/SPRXPatcher) ⭐ 42 | 🐛 0 | 🌐 C# | 📅 2024-08-12 - Modern PlayStation 3 ELF patcher for loading SPRX plugin files into decrypted executables.
* [vutrace](https://github.com/chaoticgd/vutrace) ⭐ 37 | 🐛 0 | 🌐 C | 📅 2024-06-22 - PlayStation 2 vector unit tracing debugger.
* [xbedump](https://github.com/XboxDev/xbedump) ⭐ 25 | 🐛 3 | 🌐 C | 📅 2020-09-27 - Tool for dumping and analyzing header information and signing original Xbox XBE (executable) files.
* [X360](https://github.com/mtolly/X360) ⭐ 23 | 🐛 0 | 🌐 C# | 📅 2014-10-01 - Archive of DJ SkunkieButt's X360 .NET library and Le Fluffie GUI for browsing/editing Xbox 360 file formats (STFS, GPD, and more).
* [XCompression](https://github.com/gibbed/XCompression) ⭐ 19 | 🐛 2 | 🌐 C# | 📅 2019-07-14 - .NET wrapper library for XMemCompress, the LZX-based compression scheme commonly found in Xbox 360 game data.
* [sce-symbol-scanner](https://github.com/LostTemplarRH/sce-symbol-scanner) ⭐ 13 | 🐛 1 | 🌐 Kotlin | 📅 2026-04-20 - Detects SCE SDK functions in ELF files, primarily for PS2. Command-line interface and Ghidra plugin.
* [XDBF-Manager](https://github.com/hetelek/XDBF-Manager) ⭐ 7 | 🐛 1 | 🌐 C++ | 📅 2012-07-10 - Browser/editor for Xbox 360 XDBF (dashboard/game-data) files.
* [010-Templates](https://github.com/KillzXGaming/010-Templates) ⭐ 5 | 🐛 0 | 📅 2020-08-05 - Collection of 010 Editor binary templates for understanding the structure of various video game binary formats.
* [chtdb](https://github.com/tge-was-taken/chtdb) ⭐ 1 | 🐛 0 | 📅 2024-11-25 - Cheats and patches database for PSX games, primarily intended for use with DuckStation emulator. Contains GameShark codes and patches for various games.

### 💻 Development Libraries

* [Kaitai Struct](https://github.com/kaitai-io/kaitai_struct) ⭐ 4,655 | 🐛 525 | 🌐 Shell | 📅 2026-08-17 - Declarative language and code generator for binary data parsers in C++, C#, Go, Java, JavaScript, Python, Rust, and more; widely used for documenting and parsing game file formats.
* [binrw](https://github.com/jam1garner/binrw) ⭐ 845 | 🐛 39 | 🌐 Rust | 📅 2026-07-23 - Rust library for reading and writing binary file formats with derive macros. Successor to `binread`.
* [WLA-DX](https://github.com/vhelin/wla-dx) ⭐ 605 | 🐛 27 | 🌐 C | 📅 2026-08-17 - Multi-target assembler/linker toolchain (Z80, 6502, 65816, SPC700, HuC6280, Game Boy) widely used across retro console ROM hacking and homebrew development.
* [XenosRecomp](https://github.com/hedge-dev/XenosRecomp) ⭐ 489 | 🐛 8 | 🌐 C++ | 📅 2026-03-12 - Tool for converting Xbox 360 shaders to HLSL.
* [Hexa.NET.ImGui](https://github.com/HexaEngine/Hexa.NET.ImGui) ⭐ 340 | 🐛 26 | 🌐 C# | 📅 2026-08-01 - .NET wrapper for ImGui, useful for creating tools with graphical interfaces.
* [mojoshader](https://github.com/icculus/mojoshader) ⭐ 215 | 🐛 19 | 🌐 C | 📅 2026-04-28 - Library for parsing and translating compiled Direct3D 8/9 shader bytecode to other shading languages (GLSL, ARB, etc.), widely used by Linux/macOS ports and reimplementations of Windows games to run their original shaders on OpenGL/Vulkan.
* [ooz](https://github.com/powzix/ooz) ⭐ 206 | 🐛 4 | 🌐 C++ | 📅 2019-02-13 - Open-source decompressor for Oodle compression formats used in many modern games. Supports Kraken, Mermaid, Selkie, Leviathan, LZNA, Bitknit.
* [bcdec](https://github.com/iOrange/bcdec) ⭐ 190 | 🐛 3 | 🌐 C | 📅 2025-10-23 - Small header-only C library to decompress any BC (block-compressed) texture format, widely used for game textures.
* [BCnEncoder.NET](https://github.com/Nominom/BCnEncoder.NET) ⭐ 154 | 🐛 23 | 🌐 C# | 📅 2026-04-05 - Cross-platform .NET texture encoding library supporting BC1-3/DXT, BC4-5/RGTC, and BC6-7/BPTC block compression, outputting KTX or DDS files.
* [Cast](https://github.com/dtzxporter/cast) ⭐ 148 | 🐛 10 | 🌐 Python | 📅 2026-07-22 - Open container format and libraries for models, animations, materials, and game world scenes.
  * Purpose: Designed to reproduce the same 3D scene identically across different DCC/3D software packages.
  * Usage: Adopted as a common interchange/export format by numerous game asset-extraction and conversion tools.
* [XeNTaXTools-Legacy](https://github.com/XeNTaXTools/XeNTaXTools-Legacy) ⭐ 98 | 🐛 0 | 🌐 C++ | 📅 2023-12-15 - Legacy tools scraped from the XeNTaX forums.
* [ndspy](https://github.com/RoadrunnerWMC/ndspy) ⭐ 87 | 🐛 4 | 🌐 Python | 📅 2026-03-15 - Python library for reading and modifying Nintendo DS file formats (BMG, SSEQ, LZ10, NSBMD).
* [ReverseBox](https://github.com/bartlomiejduda/ReverseBox) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2026-07-11 - Python library for reverse engineering with utilities for checksums, compression, encryption, hashing, and image processing.
  * Features: Checksums (Adler32, CRC variants, Fletcher, XOR), compression (BZIP2, LZ4, LZMA, MIO0, PackBits, RLE variants), encryption (ROT13, XOR cipher), hashing (FNV, DJB2, MD5, SHA, Murmur3).
  * Formats: 100+ pixel formats including DXT, PVRTC, ETC, ASTC, BC formats, with swizzling support for multiple platforms.
* [Assimp.Net](https://github.com/StirlingLabs/Assimp.Net) ⭐ 49 | 🐛 4 | 🌐 C# | 📅 2023-10-18 - C# .NET Core wrapper for the Open Asset Import Library (Assimp) for importing 3D models.
* [DirectXTexNet](https://github.com/deng0/DirectXTexNet) ⭐ 33 | 🐛 0 | 🌐 C# | 📅 2024-05-22 - .NET wrapper for DirectXTex, a library for working with DirectX texture formats.
* [ds-rom](https://github.com/AetiasHax/ds-rom) ⭐ 26 | 🐛 6 | 🌐 Rust | 📅 2026-07-21 - Rust library for parsing and manipulating Nintendo DS ROM file formats and components.
* [tegra\_swizzle](https://github.com/ScanMountGoat/tegra_swizzle) ⭐ 23 | 🐛 3 | 🌐 Rust | 📅 2026-07-31 - Library implementing Tegra X1 block linear texture memory tiling, used by Switch game textures.
* [GCNToolKit](https://github.com/Cuyler36/GCNToolKit) ⭐ 20 | 🐛 0 | 🌐 C# | 📅 2019-12-19 - Toolkit for modifying and creating GameCube file formats.
* [GameFormatReader](https://github.com/lioncash/GameFormatReader) ⭐ 17 | 🐛 0 | 🌐 C# | 📅 2017-07-13 - Library for reading various game formats (mostly Nintendo ones).
* [GL Editor Framework](https://github.com/jupahe64/GL_EditorFramework) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2022-05-01 - OpenGL-based framework for creating 3D game editors with hardware-accelerated graphics.
* [Oodle-Tools](https://github.com/Tamely/Oodle-Tools) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2022-06-02 - Oodle compression and decompression bindings for C#. Useful for working with modern games that use Oodle.
* [Amicitia.IO](https://github.com/tge-was-taken/Amicitia.IO) ⭐ 16 | 🐛 2 | 🌐 C# | 📅 2025-11-22 - High performance File IO library with full support for big endian and offsets.
* [Orthrus](https://github.com/NWPlayer123/Orthrus) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-08-15 - Work-in-progress modding toolkit for cross-system format interoperability.
  * Formats: Yay0/Yaz0 (Nintendo compression, N64/GameCube/Wii/Wii U/Switch), Panda3D Multifile archives and BAM/BOO binary models.
* [DrSwizzler](https://github.com/Shadowth117/DrSwizzler) ⭐ 10 | 🐛 1 | 🌐 C# | 📅 2025-09-24 - Library for deswizzling and detiling texture data.
* [SFGraphics](https://github.com/ScanMountGoat/SFGraphics) ⭐ 10 | 🐛 36 | 🌐 C# | 📅 2026-03-24 - OpenGL graphics library for rendering game formats, used in various format viewers.
* [CTLib](https://github.com/narahiero/CTLib) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2022-10-05 - Utility library to create and convert various file formats used in Mario Kart Wii custom tracks.
* [vmf](https://github.com/Galaco/vmf) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2019-02-12 - Go library for parsing Valve's Hammer Editor .vmf map files.
* [tinybcdec](https://github.com/jandk/tinybcdec) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2026-07-26 - Small block compression decoder library in pure Java. Zero dependencies, focus on speed and accuracy with support for partial decodes.
  * Formats: BC1-DXT1, BC2-DXT3, BC3-DXT5, BC4-ATI1, BC5-ATI2, BC6H, BC7.
* [mojodds](https://github.com/icculus/mojodds) ⭐ 6 | 🐛 2 | 🌐 C | 📅 2021-07-10 - Simple, dependency-free DirectDraw Surface (.DDS) texture decoder routines in portable C, commonly used for loading game textures without linking DirectX.
* [DragonLib](https://github.com/neptuwunium/DragonLib) ⚠️ Archived - Common library for file format research.
* [SharpRiff](https://github.com/gigaherz/SharpRiff) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2013-10-30 - .NET library for reading and writing RIFF format files, such as .wav, .avi, or WebP.
* [Console-Swizzler](https://github.com/matyamod/Console-Swizzler) ⭐ 4 | 🐛 3 | 🌐 C | 📅 2024-05-21 - C library to swizzle DDS textures for console games. Supports PS4 and Switch texture swizzling/unswizzling with configurable GOB block heights. Includes CLI tool for batch processing.
* [prs.net](https://github.com/FraGag/prs.net) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2013-05-13 - PRS compression/decompression library and GUI front-end for the .NET Framework. PRS is based on LZ77 with run-length encoding and is used in numerous games since the SEGA Saturn, including Phantasy Star Universe.
* [wiiu\_swizzle](https://github.com/ScanMountGoat/wiiu_swizzle) ⭐ 4 | 🐛 5 | 🌐 Rust | 📅 2026-04-01 - Library implementing Wii U texture memory tiling/swizzling.
* [TinyBCSharp](https://github.com/jandk/TinyBCSharp) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-04-05 - C# library for decoding/encoding BC (DXT/BC1-7) compressed texture formats.
* [assert-offset](https://github.com/cohaereo/assert-offset) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-06-24 - Rust derive macro for asserting the memory offset of fields in a struct. Useful for low-level FFI and embedded development.
* [ASH](https://github.com/Bigchillghost/ASH) ⭐ 2 | 🐛 0 | 📅 2023-10-16 - Skeleton and skeletal animation format analyzer. Binary format reverse-engineering framework for parsing and visualizing skeletal animation data used across many games.
* [replatform64](https://github.com/Herringway/replatform64) ⭐ 2 | 🐛 0 | 🌐 D | 📅 2026-01-20 - Framework for porting classic console games (SNES/NES/Game Boy) to modern platforms, including asset extraction and repacking.
* [Byaml-Tool](https://github.com/KillzXGaming/Byaml-Tool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2018-02-17 - Simple BYAML tool which currently just converts endianness using Syroot's Byaml library.
* [arbitrary-int](https://github.com/widberg/arbitrary-int) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2023-12-02 - Lightweight Rust implementation of arbitrary-sized integers (e.g., `u1`, `u9`, `u120`) using const generics. Useful for parsing bit-packed binary formats.
* [NvTriStrip.Net](https://github.com/Shadowth117/NvTriStrip.Net) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-08-06 - .NET port of Nvidia's NvTriStrip triangle stripifier library.
* [MeshSharp](https://github.com/MinshuG/MeshSharp) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2023-02-02 - 3D library in pure C# for reading and writing multiple formats.
  * Formats: FBX, STL, PLY.
* [formast](https://github.com/amorilia/formast) ⭐ 0 | 🐛 9 | 🌐 C++ | 📅 2012-11-18 - FormAST exposes file format descriptions through a simple API.
* [NKZIPLib](https://github.com/pixeldesu/NKZIPLib) ⚠️ Archived - C# library for parsing NKZIP archive files used in MMO games from the early 2000s. Simple format with no compression - files stored sequentially with header containing magic, version, raw data bytes, and file count.
* [Syroot.BinaryData](https://gitlab.com/Syroot/BinaryData) - .NET library for easy binary data reading/writing with support for various endianness and encodings.

### 📂 Script Collections & Multi-Game Tools

#### Multi-Game Viewers & Explorers

* [noclip.website](https://github.com/magcius/noclip.website) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser 3D viewer for 100+ games across multiple platforms and studios.
  * Games: Source Engine games (17 titles including Half-Life 2, Portal 1 & 2, Team Fortress 2, CS:GO, L4D2), GoldSrc games (Half-Life, Counter-Strike, TFC, Day of Defeat), Quake,
    Nintendo games (Mario 64, Mario Kart series, Zelda series, Pikmin, Luigi's Mansion, Super Mario Galaxy 1 & 2/Odyssey, Paper Mario series, Kirby, Smash Bros Melee/Brawl, Metroid Prime 1-3, Pokemon Snap/Platinum/HGSS, Pilotwings 64, Wii Sports), Rare games (Banjo-Kazooie, DKC), GTA series (III, Vice City, San Andreas), Crash Bandicoot, Spyro trilogy, Ratchet & Clank 1 & 2, Dark Souls, Katamari Damacy, Kingdom Hearts 1 & 2, Final Fantasy X, Dragon Quest VIII, Okami, Psychonauts, Need for Speed: Most Wanted, SpongeBob games, Jet Set Radio, Crazy Taxi, Sonic Colors, Ragnarok Online, Morrowind, World of Warcraft, Descent 1 & 2, Outer Wilds, Halo CE, and more.
  * Also covers oddities such as the Microsoft Plus! for Windows XP screensavers and Wii channel banners.
* [diii4a](https://github.com/glKarin/com.n0n3m4.diii4a) ⭐ 591 | 🐛 158 | 🌐 C | 📅 2026-08-16 - Multi-engine Android/desktop port collection for idTech-derived games, reading each game's original assets.
  * Games: DOOM 3, Quake 4, Prey (2006), Quake 1/2/3, RTCW, ETW, RealRTCW, GZDoom, OpenJK (Jedi Knight), Serious Sam, Icarus, Skin Deep, Quadrilateral Cowboy.
* [MeltyTool](https://github.com/MeltyPlayer/MeltyTool) ⭐ 200 | 🐛 60 | 🌐 C# | 📅 2026-08-19 - Multitool for viewing/extracting assets from various N64/GCN/3DS/PC games.
  * Games: Super Mario 64, Mario Artist (Polygon Studio, Talent Studio), Paper Mario TTYD, Super Paper Mario, Mario Kart Double Dash, Pikmin 1 & 2, Super Mario Sunshine, Chibi-Robo, Super Smash Bros. Melee, Battalion Wars 1 & 2, Super Mario 64 DS, Luigi's Mansion 3D, Majora's Mask 3D, Ocarina of Time 3D, Professor Layton vs. Phoenix Wright, Dead Space, Glover, Halo Wars, Celeste 64, Pokemon Colosseum, and more.
* [BinaryDataExplorer](https://github.com/RayCarrot/BinaryDataExplorer) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2022-04-29 - Binary data explorer and analyzer supporting formats from Rayman, Klonoa, PS1, Game Boy, and GBA games with interactive structure visualization.
* [psarc](https://github.com/ShadelessFox/psarc) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-01-25 - Viewer for PlayStation Archive (PSARC) archives. Supports listing and extracting files from PSARC archives with GUI and CLI interfaces.
* [FModel](https://fmodel.app/) - High-level package explorer and asset viewer for Unreal Engine 4 & 5, Unity, and other modern games. Supporting 1000+ games, it provides advanced visualization for textures, models (with animation support), audio, and specialized formats. Features include package bulk export, AES key management, and a robust search engine.

#### Cross-Game Libraries & Extractors

* [ScummVM](https://github.com/scummvm/scummvm) ⭐ 2,781 | 🐛 45 | 🌐 C++ | 📅 2026-08-19 - The canonical multi-engine interpreter that reimplements dozens of classic adventure/RPG engines, reading each game's original data files instead of emulating a CPU.
  * Engines/Studios: LucasArts SCUMM, Sierra AGI/SCI, Revolution's Virtual Theatre, Adventure Soft's AGOS, Delphine's Cinematique/Cruise, Coktel Vision's GOB, Westwood/Revolution's BS1/2 (Beneath a Steel Sky, Broken Sword), Wintermute, Grim Fandango's GrimE, Humongous Entertainment's SCUMM-derived titles, and 50+ other engines.
  * Formats: each engine's own resource/archive formats (e.g. SCUMM .SM/.LFL/.HE0, SCI resource maps, AGI VOL/DIR, and dozens more), parsed directly rather than through hardware/CPU emulation.
* [FuckGalEngine](https://github.com/Inori/FuckGalEngine) ⭐ 1,010 | 🐛 12 | 🌐 C | 📅 2022-02-06 - Large collection of tools for translating Galgames (Japanese visual novels), including archive unpacking/repacking and program hooking for in-place modification.
  * Engines: AdvHD, AliceSoft (Ain), BGI, CatSystem2, DeboLua, EntisGLS, Eushully, ExHIBIT, FLATZ, Falcom, GIGA, InnocentGrey, Kirikiri, LC-ScriptEngine, Leaf, Majiro, Makura, Malie, Minato, Minori, NScript, NekoSDK, Nitro+, PJADV, QLIE, RahuEngine, Seven Wonder, SiglusEngine, Silky, Solfa, Tactics, YukaScript, Yuris, and others.
* [XNALaraMesh](https://github.com/johnzero7/XNALaraMesh) ⭐ 593 | 🐛 38 | 🌐 Python | 📅 2023-11-15 - Blender addon to import/export XNALara/XPS model rips and poses, a format used to share fan-made model extractions across hundreds of unrelated games.
* [resource\_dasm](https://github.com/fuzziqersoftware/resource_dasm) ⭐ 151 | 🐛 9 | 🌐 C++ | 📅 2026-08-18 - Classic Mac OS resource fork disassembler and reverse-engineering toolkit, with format decoders for dozens of classic Macintosh games.
* [bevy\_trenchbroom](https://github.com/Noxmore/bevy_trenchbroom) ⭐ 147 | 🐛 11 | 🌐 Rust | 📅 2026-08-13 - Quake level format support (.map, .bsp) and TrenchBroom integration for Bevy engine. Enables loading and rendering of Quake-based game levels.
* [ReflectionHLE](https://github.com/ReflectionHLE/ReflectionHLE) ⭐ 135 | 🐛 6 | 🌐 C | 📅 2026-07-17 - Collection of source ports/reimplementations spanning multiple unrelated DOS studios, reading each game's original data files.
  * Games: id Software (Keen Dreams, Wolfenstein 3D and derived games), the 3D Catacomb Adventure series, Apogee Software (Bio Menace).
* [HyoutaTools](https://github.com/AdmiralCurtiss/HyoutaTools) ⭐ 74 | 🐛 8 | 🌐 C# | 📅 2025-12-14 - .NET CLI collection of tools for packing and unpacking video game archives. Includes functions for extracting data from and reinserting data into various games.
* [amuse](https://github.com/AxioDL/amuse) ⭐ 60 | 🐛 4 | 🌐 C++ | 📅 2024-06-09 - Real-time MIDI/SFX sequencer and alternate runtime library for games using Factor 5/Nintendo's MusyX audio engine.
  * Games: Metroid Prime series, Star Fox Adventures, Paper Mario: The Thousand Year Door (GameCube), Indiana Jones and the Infernal Machine, Star Wars Episode I, and the Rogue Squadron series.
  * Features: command-line audio-group player, SNG-to-MIDI converter, WAV song renderer, library API for engine integration, and physical/virtual MIDI keyboard support.
* [vgio](https://github.com/joshuaskelly/vgio) ⭐ 42 | 🐛 13 | 🌐 Python | 📅 2026-02-13 - Python library for reading and writing game file formats. Supports Quake, Duke Nukem 3D, Quake II, Hexen II, HROT, and Devil Daggers (BSP, MAP, and related formats).
* [libgamearchive](https://github.com/Malvineous/libgamearchive) ⭐ 26 | 🐛 2 | 🌐 C++ | 📅 2017-10-02 - Camoto C++ library and command-line utilities for examining, extracting, and editing archive/group file formats used by classic DOS games.
  * Games: Doom, Duke Nukem 3D, Blake Stone, Halloween Harry, Word Rescue, Cosmo's Cosmic Adventures, Crystal Caves, Monster Bash, God of Thunder, Jill of the Jungle, Xargon, Vinyl Goddess From Mars, and more.
* [reamberPy](https://github.com/Eve-ning/reamberPy) ⭐ 24 | 🐛 4 | 🌐 Python | 📅 2024-11-08 - Vertical scrolling rhythm game (VSRG) mapping toolbox for data extraction, manipulation, and analysis.
  * Games: osu!mania, StepMania, BMS, and partially O2Jam.
  * Features: Map I/O, format conversion, map image generation, pattern extraction.
* [gamearchive.js](https://github.com/camoto-project/gamearchivejs) ⭐ 21 | 🐛 0 | 🌐 JavaScript | 📅 2022-10-31 - JavaScript library for reading and writing custom archive formats used by MS-DOS games from the 1990s, with a unified API across formats.
  * Games: Alien Carnage, Bio Menace, Blake Stone, Blood, Catacomb 3-D series, Commander Keen 4-6, Cosmo's Cosmic Adventures, Crystal Caves, Dangerous Dave, Death Rally, Descent, Doom, Duke Nukem 3D, Duke Nukem II, Halloween Harry, Hocus Pocus, Lost Vikings, Monster Bash, Raptor, Redneck Rampage, Shadow Warrior, Spear of Destiny, Stargunner, Terminal Velocity, Wolfenstein 3-D, Word Rescue, and more (55+ games total).
  * Formats: BNK, RFF, gamemaps (id RLEW/Carmack), VOL, STN, exe-embedded archives, WAD, GRP (BUILD), HOG, DLT, POD, GLB, BPA, EPF, DAT (various), GXLib, LBR, and others.
* [UTPackage.js](https://github.com/bunnytrack/UTPackage.js) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-11 - JavaScript library for reading Unreal Tournament 99 package format. Compatible with other Unreal Engine 1 games including Deus Ex, Rune, Harry Potter, Clive Barker's Undying, Nerf Arena Blast, and Wheel of Time.
* [Alexandria](https://github.com/Burton-Radons/Alexandria) ⭐ 16 | 🐛 1 | 🌐 C# | 📅 2014-08-11 - .NET library collection for viewing and processing data from many classic PC games, with a plugin-oriented architecture.
  * Games: Demon's Souls, Dark Souls, Dark Souls 2; Sierra AGI adventures; SSI Gold Box RPGs (most comprehensive Gold Box decoder available); Ultima I-IX, Ultima Underworld 1-2, System Shock; Morrowind; Outcast; Albion; Arcanum; Planets Edge; Nintendo DS and Wii games; Super Famicom games; Unreal engine games.
  * Features: Unified viewer/modifier interface, script visualizer for Gold Box games, Visual Studio plugin framework.
* [porter-lib](https://github.com/dtzxporter/porter-lib) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2025-11-28 - Rust library for extracting 3D models, animations, and game assets across multiple games. Cross-platform (Windows, Linux, macOS).
* [modId](https://github.com/owenmpierce/modId) ⭐ 13 | 🐛 2 | 🌐 C | 📅 2023-06-24 - Tool for generating EGAGRAPH/VGAGRAPH-style graphics archive files for the 16-bit DOS games made by id Software.
* [retrocompress](https://github.com/bbitmaster/retrocompress) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-01 - Provably-optimal compressor/decompressor for the 3-bit-command/5-bit-length LZ-style compression format family shared by many 4th/5th-gen Nintendo, Capcom, Konami, and HAL Laboratory titles.
  * Games: Super Mario World, Kirby's Adventure (NES), Kirby Super Star (SNES), Super Metroid (SNES), The Legend of Zelda: A Link to the Past, Castlevania IV, Pokemon Gold/Silver, and other Capcom/Konami SNES titles using the "Konami block" variant.
  * Features: O(n) dynamic-programming shortest-path optimal parser (SA-IS suffix arrays, Kasai LCP); full repacker for Kirby's Adventure (NES) that produces a verified valid ROM.
* [UnrealXPS](https://github.com/johnzero7/UnrealXPS) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2015-08-31 - Custom file format importer for bringing XNALara/XPS model rips into Unreal Engine.
* [GameArchives](https://github.com/PikminGuts92/GameArchives) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-07-19 - C# library for reading 14+ video game archive formats.
  * Formats: Ark, PSARC, PACKAGE, PFS, STFS, XDVDFS, U8. See also [maxton's fork](https://github.com/maxton/GameArchives) ⭐ 99 | 🐛 8 | 🌐 C# | 📅 2021-02-19 with FSAR support for Sing Party.
  * Games: Harmonix titles (Frequency, Amplitude, Guitar Hero series, Rock Band series 1-4, Beatles, Green Day, Lego, VR, Karaoke Revolution, Disney Fantasia),
    Konami rhythm games (DDR Universe 1-3, DDR 2010, Dance Masters), FreeStyleGames (DJ Hero series, Guitar Hero Live, Sing Party), Psychonauts, Power Gig.
* [TrbModelConverter](https://github.com/AdventureT/TrbModelConverter) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2020-05-11 - Extracts 3D model data from .trb archive format to FBX. Supports Nicktoons series, Barnyard, de Blob, and other games.

#### Noesis / 3ds Max / Format Script Packs

* [bartlomiejduda/Tools](https://github.com/bartlomiejduda/Tools) ⭐ 210 | 🐛 7 | 🌐 Python | 📅 2026-08-05 - Collection of tools to manage and modify files from many various games. Includes archive tools, binary templates, and format-specific utilities.
  * Games: 150+ titles including Harry Potter series, Bully, Crash Bandicoot series, Tony Hawk's Underground, Sonic 2006/Unleashed, Resident Evil 7, Silent Hill series, Just Cause, Splinter Cell, SimCity 3000, LEGO games, The Sims series, Super Mario Sunshine, Star Wars Jedi Academy, Tekken 5, Transformers, Beyond Good & Evil, and many more.
* [MidiConverters](https://github.com/ValleyBell/MidiConverters) ⭐ 145 | 🐛 7 | 🌐 C | 📅 2026-01-25 - Large collection of game-specific music sequence format to MIDI converters.
  * Games: Final Fantasy VII (PSX AKAO), Core Design Mega Drive games (Asterix and the Great Rescue and others, cdmd2mid), Cotton, Sega System 32 arcade (Sys32MidiDec), Taito Zoom arcade (TaitoZoom), OutRun (toutrun2mid), Konami Mega Drive games (konamimd2mid), Neo Geo Pocket (ngp2mid), and 30+ other proprietary/tracker sequence formats.
* [vgm-disasm](https://github.com/loveemu/vgm-disasm) ⭐ 49 | 🐛 7 | 🌐 Assembly | 📅 2026-05-25 - Disassembly collection of classic video game music drivers. Disassembles VGM (Video Game Music) files for educational and preservation purposes.
* [GameFileFormatsRE](https://github.com/LolHacksRule/GameFileFormatsRE) ⭐ 33 | 🐛 1 | 🌐 Python | 📅 2026-01-08 - Collection of Noesis scripts, binary templates, and BMS scripts for reverse-engineered game file formats across 30+ studios.
  * Studios/Games: AlphaDream (Mario & Luigi: Bowser's Inside Story, Dream Team, Paper Jam), Nintendo EAD/EPD (Zelda: Breath of the Wild, Xenoblade, Mario Kart), NDCube (Animal Crossing: Pocket Camp), RetroStudios (Donkey Kong Country Returns 3D), IntelligentSystems, Housemarque, Ubisoft (UbiArt, LyN, SnowDrop, Just Dance engines), EA Redwood Shores, Gameloft, PopCap, Rovio, ZenStudios, VicariousVisions, BightGames, ChimeraEntertainment, DisneyMobile, Exient, Funlabs, Hasbro, PlayFirst, PlayMechanix, TinyCo/JamCity, Transmension, VetaSoft, Xeen, and more.
* [RTB-3DSMax-Scripts](https://github.com/RandomTBush/RTB-3DSMax-Scripts) ⭐ 31 | 🐛 9 | 🌐 MAXScript | 📅 2026-07-07 - Comprehensive collection of 3ds Max scripts for importing models from dozens of games and engines.
  * Games: Pokémon (Switch/3DS), Zelda (BOTW/TOTK/Wind Waker HD), Mario (Odyssey/Kart 8/3D World), Splatoon (1-3), Hyperdimension Neptunia series, Crash Bandicoot N. Sane Trilogy, Sonic (Unleashed/Riders), Telltale Games (Walking Dead/Batman), and many more.
  * Highlights: Support for ISM2, IGZ, MDL, D3DMesh, and Nintendo BFRES/BCH formats across PS1, PS3, Wii, Wii U, and Switch.
* [gameformats](https://github.com/dstien/gameformats) ⭐ 30 | 🐛 1 | 🌐 C++ | 📅 2023-06-29 - Tools and reverse-engineered specifications for game file formats including Midtown Madness 3 DICE textures, Stunts resource editor and data unpacker.
* [Murugo/Misc-Game-Research](https://github.com/Murugo/Misc-Game-Research) ⭐ 28 | 🐛 5 | 🌐 Python | 📅 2026-02-18 - Research artifacts and tools for various games.
  * Games: Vib-Ribbon (PS1), Gitaroo Man (PS2), Silent Hill 2 & 3 (PS2), Kingdom Hearts series (PS2), Rule of Rose (PS2), Musashi: Samurai Legend (PS2).
* [EdnessP/scripts](https://github.com/EdnessP/scripts) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-06-18 - Collection of scripts for various game file formats.
  * Games: Bully series, Burnout series (1, 2, 3, Legends, CRASH!), Call of Duty: Finest Hour, Jak & Daxter series (1, II, 3, X), Midnight Club series (2, 3), Saints Row series (2, Undercover), The Sims series (Bustin' Out, Urbz, 2, Pets, Castaway), The Simpsons Game, Tomb Raider (Wii), Need for Speed: Shift (PSP), Activision/Atari Anthology, Adventure Time, Bomberman Act:Zero, Big Rigs, Castle Strike, Driver: San Francisco, Epic Mickey, Exit, Freaky Flyers, Ready 2 Rumble Boxing, SpongeBob's Surf & Skate Roadtrip, Strike Suit Zero/Infinity, Yakuza 1 & 2 (PS2), and more.
* [dragon\_noesis](https://github.com/neptuwunium/dragon_noesis) ⚠️ Archived - Collection of Noesis plugins for various game formats including Dragon engine.
* [Noesis Plugins](https://richwhitehouse.com/index.php?content=inc_projects.php\&showproject=91) - Community plugin collections extending Noesis support to hundreds more games.
  * See [6 major plugin collections](https://richwhitehouse.com/index.php?content=inc_projects.php#prjmp91) including Tales series, Midnight Club 2, Visceral Games titles, and many more formats.

#### ROM/Save Extraction, Detection & Modding

* [Zygisk-Il2CppDumper](https://github.com/Perfare/Zygisk-Il2CppDumper) ⭐ 3,269 | 🐛 173 | 🌐 C | 📅 2024-08-09 - Dumps IL2Cpp metadata from Unity games running on Android via Zygisk, enabling reverse-engineering of obfuscated game code and data.
* [RomPatcher.js](https://github.com/marcrobledo/RomPatcher.js) ⭐ 1,173 | 🐛 19 | 🌐 JavaScript | 📅 2026-07-11 - JavaScript ROM patcher supporting IPS, BPS, UPS, APS, PPF, and other binary patch formats across many console ROM formats (used for Mario, Pokemon, Smash, and countless other ROM hacks).
* [awesome-n64-development](https://github.com/command-tab/awesome-n64-development) ⭐ 573 | 🐛 1 | 🌐 Python | 📅 2026-07-12 - Curated list of Nintendo 64 development and reverse-engineering resources including decompilation projects (SM64, Zelda OOT, Paper Mario), ROM analysis tools (N64LoaderWV for Ghidra), disassemblers, and asset extraction utilities.
* [N64-Tools](https://github.com/jombo23/N64-Tools) ⭐ 333 | 🐛 39 | 🌐 C++ | 📅 2026-07-26 - Collection of N64 romhacking tools spanning multiple unrelated games.
  * Games: GoldenEye 007 (asset decompressor, ObjToAn8 model/animation converter), Eternal Darkness (decompressor), Conker's Bad Fur Day (font ripper), Super Smash Bros (file injector), plus general N64 utilities.
  * Tools: `GEDecompressor` (Blitz/Bolt/BOFS format decoders), `objtoan8`, `N64MidiTool`, `N64SoundbankTool`, `N64SoundListTool`, MIPS disassembler, and Analog Controls Mod xdelta patches for various games.
* [game-extraction-toolbox](https://github.com/shawngmc/game-extraction-toolbox) ⭐ 134 | 🐛 51 | 🌐 Python | 📅 2025-05-15 - Python CLI tools for extracting ROMs from game rereleases and investigating game files.
* [save-decrypters](https://github.com/bucanero/save-decrypters) ⭐ 129 | 🐛 5 | 🌐 C | 📅 2026-07-17 - Collection of custom save-game decrypters and checksum fixers for PS3, PSP, and PS4.
  * Games: GTA5, The Last of Us, Uncharted series, Metal Gear Solid series, Resident Evil series, Final Fantasy XIII series, and many more.
* [CrateModLoader](https://github.com/TheBetaM/CrateModLoader) ⭐ 47 | 🐛 12 | 🌐 C# | 📅 2022-07-02 - Mod loader with game-specific format detection, extraction, modification, and rebuilding across multiple games.
* [FileDetectionRuleSets](https://github.com/neptuwunium/FileDetectionRuleSets) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2025-11-19 - Rule sets for file format detection across various tools and platforms.
  * Supports extracting ROMs from collections like Capcom Arcade Stadium, Street Fighter 30th Anniversary Collection, Mega Man Legacy Collections, SNK 40th Anniversary Collection, and many more.
* [TSERipper](https://github.com/BLiNXthetimesweeperGOD/TSERipper) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-06-15 - Asset ripping tool for Torus Games handheld titles. Converts sprites, maps, and assets from GBA, Nintendo DS, Leapster, and N-Gage games into usable formats.
* [AmazeDSExtractor](https://github.com/RayCarrot/AmazeDSExtractor) ⭐ 1 | 🐛 1 | 🌐 C# | 📅 2025-08-18 - Archive extractor for 20+ Nintendo DS games by Amaze Entertainment.
  * Games: Spyro: Shadow Legacy, Ice Age 2, The Legend of Spyro series, and others

#### Emulators & TAS Tools

* [BizHawk](https://github.com/TASEmulators/BizHawk) ⭐ 2,728 | 🐛 792 | 🌐 C# | 📅 2026-08-18 - Multi-system emulator built for tool-assisted speedrunning, with full rerecording, RAM search/watch, Lua scripting, and debugging tools across 20+ systems (NES, SNES, Genesis, Game Boy/GBA, N64, PS1, and more).
* [ScriptHawk](https://github.com/Isotarge/ScriptHawk) ⭐ 96 | 🐛 5 | 🌐 Lua | 📅 2025-02-21 - Collection of BizHawk Lua scripts for RAM watching, memory manipulation, and TAS tooling across dozens of games.

#### Franchise & Studio Toolkits

* [savegame-editors](https://github.com/marcrobledo/savegame-editors) ⭐ 1,303 | 🐛 136 | 🌐 JavaScript | 📅 2026-07-21 - Compilation of browser-based (HTML5) console savegame editors.
  * Games: The Legend of Zelda (Tears of the Kingdom, Breath of the Wild), Super Smash Bros. Ultimate, Hyrule Warriors (Wii U, Age of Calamity), Kid Icarus: Uprising, Final Fantasy Explorers, Mario Kart 7, Kirby (Super Kirby Clash, Team Kirby Clash Deluxe, Kirby's Blowout Blast), Picross 3D Round 2, Sushi Striker, Pokémon Picross, Pokémon Shuffle, Rhythm Paradise Megamix, StreetPass Mii Plaza.
* [Smithbox](https://github.com/vawser/Smithbox) ⭐ 694 | 🐛 6 | 🌐 C# | 📅 2026-08-19 - Comprehensive modding toolkit for modern FromSoftware games.
  * Games: Elden Ring, Elden Ring: Nightreign, Armored Core VI, Sekiro, Dark Souls 1-3, Bloodborne, Demon's Souls.
  * Features: Map editor, model editor (FLVER), param editor, text editor, graphics param editor (GPARAM), material editor (MTD/MATBIN), texture viewer, file browser.
* [libultraship](https://github.com/Kenix3/libultraship) ⭐ 339 | 🐛 159 | 🌐 C++ | 📅 2026-08-16 - Shared reimplementation of libultra (the Nintendo 64 SDK) and the O2R asset packaging system powering the Ship of Harkinian family of N64 decompilation PC ports.
  * Games: The Legend of Zelda: Ocarina of Time (Shipwright), The Legend of Zelda: Majora's Mask (2ship2harkinian), Star Fox 64 (Starship), Mario Kart 64 (SpaghettiKart).
* [WitchyBND](https://github.com/ividyon/WitchyBND) ⭐ 254 | 🐛 15 | 🌐 C# | 📅 2026-07-06 - Unpacker/repacker for FromSoftware game formats.
  * Games: Dark Souls 1-3, Bloodborne, Sekiro, Elden Ring, Armored Core VI
  * Formats: BND3, BND4, FFXBND, DCX, BXF3, BXF4, FMG, GPARAM, LUAGNL, LUAINFO, TPF, FXR1, FXR3, MATBIN
* [DSLuaDecompiler](https://github.com/katalash/DSLuaDecompiler) ⭐ 158 | 🐛 2 | 🌐 C# | 📅 2025-05-10 - Decompiler for Lua/HavokScript bytecode in Dark Souls, DS3, Bloodborne, and Sekiro. Actively maintained successor to garyttierney/DSLuaDecompiler.
* [EditorCore](https://github.com/exelix11/EditorCore) ⚠️ Archived - Archived, proof-of-concept extensible 3D level editor for Nintendo Switch games with a plugin architecture.
  * Features: 3D level editing with search, drag, raycast, and undo; path rendering; per-game plugin extensions (see [OdysseyEditor](https://github.com/exelix11/OdysseyEditor) ⚠️ Archived and [EditorCore-Examples](https://github.com/exelix11/EditorCore-Examples) ⚠️ Archived).
  * Games: Super Mario Odyssey, Mario Kart 8 Deluxe, Captain Toad: Treasure Tracker.
* [Paramdex](https://github.com/soulsmods/Paramdex) ⭐ 44 | 🐛 1 | 📅 2026-03-06 - Parameter file format specifications for FromSoftware games (DS1-3, Bloodborne, Sekiro, Demon's Souls, Elden Ring, Armored Core VI). Actively maintained successor to garyttierney/Paramdex.
* [Supercell-Flat-Converter](https://github.com/Daniil-SV/Supercell-Flat-Converter) ⚠️ Archived - Converts Supercell game assets between optimized Flatbuffer format and standard glTF. Supports Brawl Stars, Clash of Clans, Clash Royale, Clash Mini, and Squad Busters.
* [Nuxe](https://github.com/JKAnderson/Nuxe) ⭐ 38 | 🐛 0 | 🌐 C# | 📅 2026-07-13 - Game data unpacker for FromSoftware titles (Dark Souls, Elden Ring, Sekiro).
* [SC2FLA-FOSS-Edition](https://github.com/GenericName1911/SC2FLA-FOSS-Edition) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2025-12-29 - Converts Supercell .sc asset format (2D sprites/animations) to Adobe Animate .fla files. Supports Brawl Stars, Clash of Clans, Clash Royale, Squad Busters with SCTX texture support and spritesheet generation.
* [mapfile\_parser](https://github.com/Decompollaborate/mapfile_parser) ⭐ 29 | 🐛 0 | 🌐 Rust | 📅 2026-08-18 - Library for parsing linker map files, used across multiple N64 decompilation projects to assist with matching original compiled code during reverse engineering.
* [SCTX Converter](https://github.com/Daniil-SV/SCTX-Converter) ⭐ 26 | 🐛 0 | 🌐 C++ | 📅 2026-05-11 - Converts Supercell Texture (.sctx) files to PNG with metadata extraction in JSON format. Supports texture streaming and mip-mapping data.
* [BinderKeys](https://github.com/JKAnderson/BinderKeys) ⭐ 13 | 🐛 0 | 📅 2026-04-22 - Encryption keys and path dictionaries for unpacking FromSoftware BinderLight container files across multiple games.
* [Lunacy](https://github.com/NefariousTechSupport/Lunacy) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2024-02-04 - Level editor and asset extractor for Ratchet & Clank and Resistance (Insomniac Games PS3), parsing main.dat and assetlookup.dat game files.
* [fsvfs](https://github.com/Dasaav-dsv/fsvfs) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-06-25 - Cross-platform userspace filesystem for mounting FromSoftware game archives (Dark Souls, Elden Ring, Armored Core).
* [FormatX](https://github.com/Force67/FormatX) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2020-05-11 - Ever-evolving collection of tools for extracting various game file formats.
  * Games: Control, Mafia III, The Binding of Isaac: Rebirth, Tomb Raider, Toy Soldiers.
* [BOLTextract](https://github.com/heinermann/BOLTextract) ⭐ 5 | 🐛 1 | 🌐 C++ | 📅 2026-08-10 - Extractor for Mass Media Games' BOLT archive format, unpacking embedded files from ROMs/binaries across the studio's many console ports.
  * Games: Mystic Midway: Rest in Pieces, Voyeur, 3-D TableSports, The Game of Life, Bassmasters 2000, Namco Museum, Ms. Pac-Man: Maze Madness, Power Rangers: Lightspeed Rescue, Starcraft 64, Pac-Man Collection, Shrek Super Party, Blackthorne, Rock n' Roll Racing, The Lost Vikings.
* [FC.LPKG.Tool](https://github.com/Ekey/FC.LPKG.Tool) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-05-24 - Extracts LPKG archive format from FURYU Corporation games including Cardfight Vanguard, MONARK, and Mushoku Tensei.
* [mhpf-tools](https://github.com/christorrella/mhpf-tools) ⭐ 3 | 🐛 2 | 🌐 Python | 📅 2021-04-23 - Pack/unpack tool for the Melbourne House Pack File format (.PCK) used in Test Drive Unlimited (PSP/PS2) resource archives.
* [Test-Drive-5-Mod-Tools](https://github.com/Dummiesman/Test-Drive-5-Mod-Tools) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-12-30 - Modding tools for Test Drive series. Supports level and object imports for Test Drive 4, 5, 6, and Off-Road 3.
* [fish-tools](https://github.com/christorrella/fish-tools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-04-15 - Unpacking script for the Melbourne House "FISH" Tone Library file format used in Test Drive Unlimited (PSP).

## ⚙️ Engines

*Tools specific to widespread third-party game engines.*

### GameMaker

* [UndertaleModTool](https://github.com/UnderminersTeam/UndertaleModTool) ⭐ 2,003 | 🐛 319 | 🌐 C# | 📅 2026-08-19 - Tool for modding/decompiling GameMaker games.
* [OpenGMK](https://github.com/OpenGMK/OpenGMK) ⭐ 400 | 🐛 31 | 🌐 Rust | 📅 2026-07-16 - Rewrite of the GameMaker Classic (8.x) engine runners with additional tooling, loading and executing original .gmk-derived game data.
* [cinnamon](https://github.com/Project-Sunshine-Native/cinnamon) ⭐ 367 | 🐛 11 | 🌐 C | 📅 2026-08-14 - GameMaker runtime reimplementation ('Cinnamon') that loads original compiled GameMaker game data, in the tradition of phosphorvm and OpenGMK.
* [GM8Decompiler](https://github.com/OpenGMK/GM8Decompiler) ⭐ 199 | 🐛 10 | 📅 2024-02-12 - Decompiler for GameMaker 8.x executables, recovering the original game's assets and code from compiled `.exe` files.
* [UndertaleTools](https://github.com/fjay69/UndertaleTools) ⭐ 92 | 🐛 7 | 🌐 C# | 📅 2023-08-02 - GameMaker data.win unpacker/packer.
* [Butterscotch](https://github.com/efimandreev0/Butterscotch) ⭐ 63 | 🐛 23 | 🌐 C | 📅 2026-08-04 - GameMaker runtime reimplementation that loads original compiled GameMaker game data, in the tradition of phosphorvm and OpenGMK.
* [GMSD](https://github.com/lynn/GMSD) ⭐ 58 | 🐛 4 | 🌐 F# | 📅 2016-08-12 - GameMaker Studio decompiler in F#.
* [GMS-Explorer](https://github.com/puggsoy/GMS-Explorer) ⭐ 22 | 🐛 6 | 🌐 C# | 📅 2025-05-17 - Game Maker Studio `data.win` explorer.
* [gmspack](https://github.com/ryohey/gmspack) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2018-11-01 - C reimplementation for extracting the `data.win` file produced by GameMaker Studio, ported from UndertaleTools.
* [gm\_data\_win](https://github.com/jam1garner/gm_data_win) ⭐ 13 | 🐛 2 | 🌐 Rust | 📅 2021-10-23 - GameMaker Studio 2 data.win editor/library written in Rust, developed for Rivals of Aether modding.
* [phosphorvm](https://github.com/asumagic/phosphorvm) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2018-12-01 - Open-source reimplementation of the GameMaker: Studio runner, reading original compiled GameMaker data/executables.
* [pugIFF](https://github.com/nkrapivin/pugIFF) ⭐ 7 | 🐛 0 | 🌐 Yacc | 📅 2021-04-01 - GameMaker IFF gamefile reader in GML.
* [YYTextureView](https://github.com/YAL-GameMaker-Tools/YYTextureView) ⭐ 4 | 🐛 0 | 🌐 Haxe | 📅 2022-01-04 - Tool for exploring textures in GameMaker games.
* [gm-modding-gui](https://github.com/jam1garner/gm-modding-gui) ⭐ 4 | 🐛 2 | 🌐 Rust | 📅 2021-08-06 - Simple UI for modding GameMaker 2 games.
* [LojRipper](https://github.com/nkrapivin/LojRipper) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2020-07-10 - Tool to dump .win files from GameMaker YYC-compiled executables for game modding purposes.
* [libaltar](https://github.com/Prashant-Jonny/libaltar) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2014-02-26 - Library for processing GameMaker: Studio binary file formats (decompiler).
* [gamemaker2-data-research](https://github.com/jam1garner/gamemaker2-data-research) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2018-10-31 - Tools/Documentation for GameMaker 2 data files.

### Source (Valve)

#### Engines, Libraries & Full Toolkits

* [halflife](https://github.com/ValveSoftware/halflife) ⭐ 4,342 | 🐛 2,122 | 🌐 C++ | 📅 2024-10-02 - Valve's official Half-Life 1 SDK source release, containing the client/server game-logic DLL source that defines GoldSrc's original data formats.
* [noclip.website (Source Engine)](https://github.com/magcius/noclip.website/tree/main/src/SourceEngine) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Source engine map viewer supporting Counter-Strike: Source, Day of Defeat: Source, Half-Life 2, Half-Life 2: Deathmatch, Half-Life 2: Lost Coast, Half-Life 2: Episode 1, Half-Life 2: Episode 2, Team Fortress 2, Portal, Portal 2, Counter-Strike: Global Offensive, Left 4 Dead 2, The Stanley Parable, Infra, Neo Tokyo, and Estranged: Act I.
* [noclip.website (GoldSrc)](https://github.com/magcius/noclip.website/tree/main/src/GoldSrc) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser GoldSrc map viewer supporting Half-Life, Counter-Strike, Team Fortress Classic, and Day of Defeat.
* [xash3d-fwgs](https://github.com/FWGS/xash3d-fwgs) ⭐ 2,720 | 🐛 446 | 🌐 C | 📅 2026-08-18 - Cross-platform reimplementation of the GoldSrc engine, loading original Half-Life BSP/WAD/MDL game data. Actively maintained; companion to hlsdk-portable.
* [ValveResourceFormat](https://github.com/ValveResourceFormat/ValveResourceFormat) ⭐ 2,377 | 🐛 74 | 🌐 C# | 📅 2026-08-18 - Source 2 Viewer is a powerful tool that allows you to browse VPK archives, view, extract, and decompile Source 2 assets, including maps, models, materials, textures, sounds, and more. Also includes C# library for reading and writing Valve Source engine resource files.
* [source-engine](https://github.com/nillerusr/source-engine) ⭐ 2,207 | 🐛 131 | 🌐 C++ | 📅 2025-11-25 - Modified Source engine (2017) developed by Valve and leaked in 2020. Not for commercial purposes.
* [Kisak-Strike](https://github.com/SwagSoftware/Kisak-Strike) ⭐ 1,208 | 🐛 27 | 🌐 C++ | 📅 2025-07-25 - Open-source, fully buildable CS:GO port on Source 1; requires original game assets.
* [Crowbar](https://github.com/ZeqMacaw/Crowbar) ⭐ 811 | 🐛 45 | 🌐 Visual Basic .NET | 📅 2026-08-08 - All-in-one GoldSource and Source Engine modding tool: decompile/compile MDL model files, unpack game packages, and publish addons to Steam Workshop.
* [ReGameDLL\_CS](https://github.com/rehlds/ReGameDLL_CS) ⭐ 774 | 🐛 283 | 🌐 C++ | 📅 2026-07-09 - Enhanced, cross-platform server-side GameDLL reimplementation for Counter-Strike 1.6 and Condition Zero, a GoldSrc-format companion to ReHLDS.
  * See also [FWGS's fork](https://github.com/FWGS/regamedll) ⚠️ Archived.
* [awpy](https://github.com/pnxenopoulos/awpy) ⭐ 609 | 🐛 29 | 🌐 Python | 📅 2026-08-04 - Python library for parsing and analyzing Counter-Strike 2 .dem demo files (via a Rust demoparser backend) and CS2 .nav navigation-mesh files, exposing tick-level player/event data as dataframes.
* [halflife-updated](https://github.com/twhl-community/halflife-updated) ⭐ 482 | 🐛 22 | 🌐 C++ | 📅 2026-08-02 - TWHL community-maintained, modernized fork of Valve's Half-Life 1 SDK with bug fixes and cross-platform build support.
* [hlsdk-portable](https://github.com/FWGS/hlsdk-portable) ⭐ 393 | 🐛 51 | 🌐 C++ | 📅 2026-08-17 - Cross-platform, actively maintained continuation of the Half-Life SDK for GoldSource and Xash3D, used to build original HL1 mod DLLs on modern OSes.
* [freehl](https://github.com/eukara/freehl) ⭐ 318 | 🐛 10 | 🌐 QuakeC | 📅 2025-11-12 - Clean-room reimplementation of Half-Life and Half-Life: Deathmatch in QuakeC, reading original GoldSrc game data. The same author maintains similar clean-room reimplementations of other GoldSrc-era mod SDKs (freecs for Counter-Strike 1.5, freesci for Science and Industry, freegunman for Gunman Chronicles, freehunger for They Hunger, freegearbox for Opposing Force, freetfc for Team Fortress Classic, freepoke646 for Poke646).
* [HalfMapper](https://github.com/gzalo/HalfMapper) ⭐ 164 | 🐛 4 | 🌐 C++ | 📅 2021-09-11 - Renderer that loads and displays all Half-Life maps simultaneously, exploring the Black Mesa Research Facility by parsing the game's original BSP map data.
* [vitaXash3D](https://github.com/fgsfdsfgs/vitaXash3D) ⭐ 160 | 🐛 33 | 🌐 C | 📅 2023-06-14 - PS Vita port of Xash3D-FWGS, loading original GoldSrc BSP/WAD/MDL game data (Half-Life, Counter-Strike, and other GoldSrc titles) natively on the Vita.
* [SourceUtils](https://github.com/Metapyziks/SourceUtils) ⭐ 144 | 🐛 37 | 🌐 C# | 📅 2026-01-23 - Source Engine file format exporting toolkit with a WebGL-based map viewer, converting BSP maps and their assets for in-browser rendering.
* [nuclide](https://github.com/VeraVisions/nuclide) ⭐ 140 | 🐛 3 | 🌐 QuakeC | 📅 2025-11-12 - Software development kit for building new games and mods on id Tech, used by freehl and related clean-room GoldSrc-era reimplementations.
* [sourcepp](https://github.com/craftablescience/sourcepp) ⭐ 136 | 🐛 14 | 🌐 C++ | 📅 2026-08-06 - C++20 library suite for parsing Source Engine file formats (VTF, MDL, VVD, VPK, BSP, etc.).
* [Unity-Source-Tools](https://github.com/lewa-j/Unity-Source-Tools) ⭐ 111 | 🐛 13 | 🌐 C# | 📅 2021-01-04 - Unity plugin for importing and extracting Source Engine game resources (maps and models).
* [sledge-formats](https://github.com/LogicAndTrick/sledge-formats) ⭐ 100 | 🐛 3 | 🌐 C# | 📅 2026-08-12 - C# parsers and formats for Half-Life 1 and related engines.
* [uSource](https://github.com/DeadZoneLuna/uSource) ⭐ 92 | 🐛 9 | 🌐 C# | 📅 2022-11-21 - Unity plugin for importing Source Engine formats (MDL, BSP, VTF, VMT, VPK, VVD, VTX).
* [srctools](https://github.com/TeamSpen210/srctools) ⭐ 86 | 🐛 10 | 🌐 Python | 📅 2026-07-21 - Python modules for working with Source Engine file formats.
  * Formats: VMF, BSP, VPK.
* [source1import](https://github.com/kristiker/source1import) ⭐ 71 | 🐛 17 | 🌐 Python | 📅 2025-02-28 - Python scripts for importing Source 1 game assets (materials, models, particle effects) into Source 2.
* [cs2typescript](https://github.com/Ansimist/cs2typescript) ⭐ 63 | 🐛 2 | 🌐 C# | 📅 2025-09-16 - Converts Counter-Strike 2 map-scripting files from .vts (TypeScript source) to the compiled .vts\_c format.
* [Hammer5Tools](https://github.com/dertwist/Hammer5Tools) ⭐ 57 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - Suite of editors (SoundEvent, SmartProp, Hotkey, Loading) for Counter-Strike 2 / Source 2 Workshop Tools content creation, complementing Valve's official Hammer 5 editor.
* [ps2-hl-tools](https://github.com/supadupaplex/ps2-hl-tools) ⭐ 45 | 🐛 3 | 🌐 C++ | 📅 2022-01-27 - Tools for extracting and converting PS2 Half-Life port resources, including .pak archives, .dol models, .spz sprites, .psi images, .psf fonts, .vag music, .nod AI nodes, .epc model precache lists.
* [vpulse-editor](https://github.com/LionDoge/vpulse-editor) ⭐ 32 | 🐛 0 | 🌐 Rust | 📅 2026-08-05 - Unofficial editor for Source 2's Pulse visual scripting graph files, used in Dota 2, CS2, and Deadlock, filling a gap left by the lack of official Valve tooling for this format.
* [UEditingTools](https://github.com/adenexvfx/UEditingTools) ⭐ 19 | 🐛 0 | 📅 2024-11-22 - Unreal Engine 5 widget/pipeline for importing CS2, CS:GO, CS:S, TF2, and CS 1.6 player, weapon, and viewmodel assets with correct skeletons, cameras, and sequencer/level placement; companion to the same author's io\_scene\_CSGO Blender importer.
* [SourceLoader](https://github.com/K0bin/sourceloader) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2018-04-28 - Source Engine map loader supporting BSP, VTF, and MDL formats with OBJ export.
* [lambda-core](https://github.com/Galaco/lambda-core) ⭐ 14 | 🐛 14 | 🌐 Go | 📅 2025-11-06 - Go library for parsing Source Engine asset formats (VMT, VTF, MDL, BSP) with filesystem and resource management.
* [FreeTS](https://github.com/Frag-Net/FreeTS) ⭐ 5 | 🐛 0 | 🌐 QuakeC | 📅 2026-06-29 - Clean-room reimplementation of The Specialists, another GoldSrc-era Half-Life mod, built on Nuclide and freehl.
* [DemoViewer](https://github.com/dertwist/DemoViewer) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-04-20 - Viewer for Counter-Strike 2 / Source 2 .dem demo/replay files.
* [hvox](https://github.com/fgsfdsfgs/hvox) ⭐ 3 | 🐛 0 | 🌐 Nim | 📅 2020-02-10 - Standalone player for Half-Life's sentence system, loading the game's original voice-pack WAV files and synthesizing SENTENCES.TXT-style scripted lines with per-word pitch/volume/timing control codes.
* [go-valve](https://github.com/handsomematt/go-valve) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2018-03-21 - Go library for querying A2S server information from Source servers.
* [powerjack](https://github.com/cohaereo/powerjack) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-12-06 - Team Fortress 2 asset viewer and demo player. Features improved rendering with direct lightmap sampling from BSP data.

#### Maps & BSP

* [bspsrc](https://github.com/ata4/bspsrc) ⭐ 860 | 🐛 39 | 🌐 Java | 📅 2026-08-13 - Java-based map decompiler for Source engine .bsp files, reconstructing editable .vmf sources for Hammer.
* [GtkRadiant](https://github.com/TTimo/GtkRadiant) ⭐ 656 | 🐛 170 | 🌐 C | 📅 2024-08-18 - Open source, cross-platform level editor for id Tech and Source engine games.
* [GodotGoldSrcBSP](https://github.com/DataPlusProgram/GodotGoldSrcBSP) ⭐ 158 | 🐛 3 | 🌐 GDScript | 📅 2021-10-20 - Godot plugin to load GoldSrc BSP map files, companion to the same author's Godot-GoldSrc-MDL-Importer.
* [HammerAddons](https://github.com/TeamSpen210/HammerAddons) ⭐ 157 | 🐛 84 | 🌐 Python | 📅 2026-07-30 - Hammer editor addons for BSP file processing, entity support, and auto-packing Source Engine game assets.
* [Scopa](https://github.com/radiatoryang/scopa) ⭐ 154 | 🐛 1 | 🌐 C# | 📅 2026-01-08 - Unity level design plugin for importing Quake .MAP, Half-Life .RMF, Source .VMF map formats, and .WAD textures.
* [VMF2OBJ](https://github.com/Dylancyclone/VMF2OBJ) ⭐ 137 | 🐛 15 | 🌐 Java | 📅 2024-05-31 - Tool for converting Source Engine VMF map files to OBJ format with materials.
* [bsp\_tool](https://github.com/snake-biscuits/bsp_tool) ⭐ 129 | 🐛 99 | 🌐 Python | 📅 2026-08-15 - Python library and CLI for reading, analysing, and editing .bsp map files across many Quake-derived engines.
  * Engines: Source (VBSP), GoldSrc, idTech/Quake, Quake II, Quake III, Respawn's Source fork (Titanfall 1/2, Apex Legends), Infinity Ward (Call of Duty).
* [WifeRadiant](https://github.com/erysdren/WifeRadiant) ⭐ 115 | 🐛 7 | 🌐 C++ | 📅 2026-08-18 - Open-source, cross-platform level editor for idTech, Source Engine, and GoldSrc based games; modern fork of NetRadiant.
* [valve-bsp-parser](https://github.com/ReactiioN1337/valve-bsp-parser) ⭐ 109 | 🐛 3 | 🌐 C++ | 📅 2024-01-05 - Parser for Valve BSP (Binary Space Partition) map files.
* [LibBSP](https://github.com/wfowler1/LibBSP) ⭐ 106 | 🐛 5 | 🌐 C# | 📅 2026-04-19 - C# library for parsing BSP map files across Quake-derived engines, including Quake 1/2/3, GoldSrc, Source, and other idTech forks. Used by BSP Importer for Unity3D and BSP Decompiler.
* [hlbsp](https://github.com/rein4ce/hlbsp) ⭐ 97 | 🐛 2 | 🌐 JavaScript | 📅 2020-04-26 - Half-Life WebGL level and model viewer, loading and rendering the game's original .bsp and .mdl files.
* [uQuake3](https://github.com/mikezila/uQuake3) ⭐ 83 | 🐛 1 | 🌐 C# | 📅 2015-06-09 - Unity3D importer for Quake 3 BSP map files, enabling Quake 3 levels to be loaded and used inside the Unity engine.
* [corvid](https://github.com/KILLTUBE/corvid) ⭐ 75 | 🐛 2 | 🌐 Python | 📅 2024-10-26 - Source Engine level converter for Call of Duty.
* [bsp-decompiler](https://github.com/wfowler1/bsp-decompiler) ⭐ 59 | 🐛 8 | 🌐 C# | 📅 2025-08-28 - Decompiler for many BSP map formats (Quake, GoldSrc, Source, and other id Tech-derived engines), reconstructing editable map sources.
* [VMFInstanceInserter](https://github.com/Metapyziks/VMFInstanceInserter) ⭐ 41 | 🐛 9 | 🌐 C# | 📅 2020-05-04 - Tool for inserting func\_instance entities into Source Engine VMF map files.
* [bsp](https://github.com/Galaco/bsp) ⭐ 39 | 🐛 4 | 🌐 Go | 📅 2025-11-02 - Go library for parsing Valve Source Engine .bsp (Binary Space Partition) map files.
* [BspZipGUI](https://github.com/Moltard/BspZipGUI) ⭐ 37 | 🐛 1 | 🌐 C# | 📅 2026-01-19 - GUI wrapper around Valve's BspZip command-line utility for packing custom files (materials, models, sounds) into Source Engine BSP map files.
* [csgo-centrifuge](https://github.com/saiko-tech/csgo-centrifuge) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2023-03-07 - Go API and CLI for extracting data from CS:GO BSP files, including radar overviews and map structure information.
* [vmflib-godot](https://github.com/craftablescience/vmflib-godot) ⭐ 13 | 🐛 0 | 🌐 GDScript | 📅 2023-03-10 - Godot 4 library for creating and exporting Source Engine VMF map files (targeted at Portal 2).
* [Chisel.Import.Source](https://github.com/Henry00IS/Chisel.Import.Source) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2024-09-28 - Valve Map Format (VMF) importer for Unity's Chisel Editor, allowing Source Engine VMF maps to be imported and edited in Unity.
* [func\_godot\_docs](https://github.com/func-godot/func_godot_docs) ⭐ 9 | 🐛 8 | 🌐 HTML | 📅 2025-12-28 - Documentation for FuncGodot, a Godot plugin for building levels using the id Tech/Quake .MAP text-based map format.
* [VertAlert](https://github.com/ItEndsWithTens/VertAlert) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2013-03-28 - Finds, displays, and optionally rounds floating point plane coordinates in Source Engine .vmf map files.
* [qbsp-gltf](https://github.com/JarrodDoyle/qbsp-gltf) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-05-27 - CLI tool to convert Quake 2 BSP map files to binary glTF (.glb) models.
* [SourcePorter](https://github.com/dertwist/SourcePorter) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-07-29 - Tool for porting/decompiling Counter-Strike: Global Offensive BSP maps to Counter-Strike 2's VMF/Source 2 format.
* [map-files](https://github.com/iOrange/map-files) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2013-10-05 - '.MAP Files' article and accompanying source code documenting the id Tech .MAP editable level-source format used by Quake/Half-Life-derived engines.

#### Models (MDL/SMD)

* [VPhysics-Jolt](https://github.com/misyltoad/VPhysics-Jolt) ⭐ 1,435 | 🐛 113 | 🌐 C++ | 📅 2025-05-18 - Volt, a drop-in replacement for the Source Engine's VPhysics module built on Jolt Physics, parsing the engine's compiled VPhysics collision model (`.phy`) data to reconstruct rigid bodies, ragdolls, and constraints.
* [HalfLifeAssetManager](https://github.com/SamVanheer/HalfLifeAssetManager) ⚠️ Archived - Tool to view and edit Half-Life 1 (GoldSrc) MDL models.
* [source-engine-model-loader](https://github.com/gkjohnson/source-engine-model-loader) ⭐ 86 | 🐛 3 | 🌐 JavaScript | 📅 2024-06-18 - Three.js loader for parsing Source Engine model formats (MDL, VMT, VTF, VTX, VVD).
* [Godot-GoldSrc-MDL-Importer](https://github.com/DataPlusProgram/Godot-GoldSrc-MDL-Importer) ⭐ 76 | 🐛 2 | 🌐 GDScript | 📅 2023-09-01 - Plugin that imports GoldSrc .mdl model files into Godot.
* [StdPatch](https://github.com/kohtep/StdPatch) ⭐ 28 | 🐛 1 | 🌐 C++ | 📅 2020-06-13 - StudioMDL Compiler Patcher that removes limitations of the Source Engine models compiler. Allows compiling high-poly models by expanding vertex arrays, weight arrays, and flexcontroller arrays. Includes StdInjector for DLL injection into studiomdl process.
* [hlmvqt](https://github.com/iOrange/hlmvqt) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2023-01-10 - Half-Life model viewer written from scratch using Qt 6.
* [studiomodel](https://github.com/Galaco/studiomodel) ⭐ 9 | 🐛 1 | 🌐 Go | 📅 2025-11-02 - Go library for loading Valve studiomodel formats.
  * Formats: .mdl, .vtx, .vvd.
* [valve-vrm](https://github.com/UnBeatWaterGH/valve-vrm) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-12-20 - Documentation and converter for Valve's experimental VRM model format.

#### Textures & Materials (VTF/VMT)

* [VTFLib](https://github.com/NeilJed/VTFLib) ⭐ 188 | 🐛 11 | 🌐 C++ | 📅 2023-03-19 - C/C++ library for reading/writing VTF and VMT texture/material files. See also [panzi's fork](https://github.com/panzi/VTFLib) ⭐ 49 | 🐛 1 | 🌐 C++ | 📅 2026-07-03 — Linux port adding a CMake build, libtxc\_dxtn support, and buffer-overflow fixes.
* [MareTF](https://github.com/craftablescience/MareTF) ⭐ 126 | 🐛 15 | 🌐 C++ | 📅 2026-07-10 - Utility for creating, editing, and displaying VTF (Valve Texture Format) files. Supports all VTF versions used in Source Engine games (Half-Life 2, Portal, Counter-Strike, Team Fortress 2, etc.).
* [AutoVTF](https://github.com/NvC-DmN-CH/AutoVTF) ⭐ 70 | 🐛 11 | 🌐 C# | 📅 2024-12-05 - C# WinForms tool for working with VTF files. Monitors materials folder and automatically converts updated images to VTF format, preserving VTF settings. Features drag-and-drop conversion, advanced VTF options panel, and Hammer++ hotloading support.
  * Formats: PNG, BMP, TGA, JPG, PSD (input), VTF (output).
* [vtf2img](https://github.com/julienc91/vtf2img) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2020-05-12 - Python library for converting Valve Texture Format (VTF) files to standard image formats.
* [vtf](https://github.com/Galaco/vtf) ⭐ 13 | 🐛 1 | 🌐 Go | 📅 2025-11-06 - Go library for parsing and converting Source Engine .vtf texture format files.
* [vmt](https://github.com/Galaco/vmt) ⭐ 6 | 🐛 1 | 🌐 Go | 📅 2025-11-02 - Go library for parsing Source Engine .vmt Valve Material format files.

#### Packages & Filesystem (VPK/GCF/GMA/WAD)

* [VPKEdit](https://github.com/craftablescience/VPKEdit) ⭐ 729 | 🐛 49 | 🌐 C++ | 📅 2026-08-10 - Cross-platform GUI and CLI tool for creating, reading, and writing many pack file formats used across Source, GoldSrc, and Quake-family games.
  * Formats: VPK (Source 1/2), GCF, GMA, WAD (GoldSrc), PAK (Quake/HL1), PK3 (Quake II), PK4 (Quake IV/Doom 3), BSP (Source 1), XZP (Xbox HL2), VPP (Red Faction/Saints Row), PCK (Godot), ZIP, and more.
  * Features: In-pack preview of audio, images, VTF textures, and Source 1 models without extraction; available for Windows, macOS, and Linux.
* [vpk](https://github.com/ValvePython/vpk) ⭐ 188 | 🐛 9 | 🌐 Python | 📅 2023-09-20 - Python library and CLI for opening, searching, extracting, and creating Valve VPK archives.
* [ValvePak](https://github.com/ValveResourceFormat/ValvePak) ⭐ 151 | 🐛 0 | 🌐 C# | 📅 2026-08-08 - C# .NET library for reading and writing Source 2 VPK (Valve PacK) archives. Part of the ValveResourceFormat project.
* [WadMaker](https://github.com/pwitvoet/wadmaker) ⭐ 65 | 🐛 6 | 🌐 C# | 📅 2026-05-12 - Command-line tools for creating and extracting Half-Life (GoldSrc) texture WADs and sprites.
* [vpk\_fuse](https://github.com/ElementW/vpk_fuse) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2023-04-15 - FUSE filesystem for mounting and browsing the contents of Valve VPK package files.
* [filesystem](https://github.com/Galaco/filesystem) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2025-11-06 - Go library for managing Source Engine VPK archives (Counter-Strike: Source, CS:GO, Team Fortress 2, etc.).
* [jvpklib](https://github.com/ata4/jvpklib) ⭐ 11 | 🐛 2 | 🌐 Java | 📅 2014-02-20 - Simple Java library for reading Valve VPK archive files used in Source Engine games.
* [fgptool](https://github.com/craftablescience/fgptool) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-01-09 - Tool for cracking filepath hashes in The Orange Box PS3 file groups (.vpk format).
* [WAD3xtract](https://github.com/ElementW/WAD3xtract) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2015-01-03 - Command-line extractor for Half-Life's WAD3 texture archive format.

#### KeyValues, VDF & Choreography

* [ValveKeyValue](https://github.com/ValveResourceFormat/ValveKeyValue) ⭐ 192 | 🐛 9 | 🌐 C# | 📅 2026-08-08 - .NET library for parsing Valve's KeyValue format used in Source/Source 2 engines.
* [vsif2vcd](https://github.com/MrSoup678/vsif2vcd) ⭐ 13 | 🐛 1 | 🌐 C++ | 📅 2025-05-29 - Decompiles VCD choreography scenes from Source Engine `scenes.image` files back into editable `.vcd` files.
* [keyvalues](https://github.com/Galaco/keyvalues) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2023-12-15 - Go library for parsing Source Engine KeyValue format files (gameinfo.txt, vmt, vmf, etc.).
* [vdf-parser](https://github.com/lukezbihlyj/vdf-parser) ⭐ 5 | 🐛 4 | 🌐 PHP | 📅 2016-04-04 - Parser for Valve Data Format (VDF) files used in Source games.
* [VDataEditor](https://github.com/dertwist/VDataEditor) ⚠️ Archived - Desktop editor for Source 2 KV3 data files (.vdata, .vsmart, .vpcf).
* [checksum](https://github.com/Galaco/checksum) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2025-07-05 - Utility for calculating CRC32 checksums for Source Engine file validation.

#### DCC Plugins (Blender / 3ds Max / Maya / XSI)

* [SourceIO](https://github.com/REDxEYE/SourceIO) ⭐ 955 | 🐛 15 | 🌐 Python | 📅 2026-08-14 - Blender 3.6+ addon for importing Source Engine assets (models, maps, textures, materials) for both Source 1 and Source 2.
  * Formats: Source 1 — MDL, BSP, VTF, VMT; Source 2 — VMDL, VMAP, VTEX, VMAT.
  * Games: CS:GO, TF2, Source Filmmaker, Garry's Mod, HL2 + episodes, Portal 1/2, L4D2, Black Mesa, Vindictus, Titanfall 1, CS2, Half-Life: Alyx, Aperture Desk Job, S\&Box.
* [Plumber](https://github.com/lasa01/Plumber) ⭐ 500 | 🐛 33 | 🌐 Rust | 📅 2026-06-13 - Blender add-on for importing Source 1 engine maps, models, materials and textures from CS:GO, TF2, CS:S, and other titles.
  * Features: full map import (brushes, overlays, lights, props, skyboxes), MDL/material/texture import with color options, and embedded file browser.
* [Blender Source Tools](https://github.com/Artfunkel/BlenderSourceTools) ⭐ 285 | 🐛 5 | 🌐 Python | 📅 2025-11-01 - Blender addon for importing and exporting Source Engine model and animation formats. Enables 3D asset creation and modification for all Source Engine games in Blender.
* [SourceOps](https://github.com/bonjorno7/SourceOps) ⭐ 181 | 🐛 24 | 🌐 Python | 📅 2025-09-04 - Blender addon for exporting models to Source 1. More convenient alternative to Blender Source Tools. Features export objects as SMD or FBX, export actions as SMD, generate QC based on UI settings, buttons to compile and view models, and experimental export for brushes and displacements to VMF. Requires Blender 2.83 or newer.
* [AutoMDL](https://github.com/NvC-DmN-CH/AutoMDL) ⭐ 31 | 🐛 9 | 🌐 Python | 📅 2024-05-17 - Blender 4+ addon for Source engine MDL compilation workflow. Automatically compiles .blend files to .mdl format when saved in a models folder, with Hammer++ hotloading support. Features automatic material path detection, collision model support, and studiomdl.exe integration.
* [io\_scene\_CSGO](https://github.com/adenexvfx/io_scene_CSGO) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2025-12-29 - Blender addon for importing Counter-Strike: Global Offensive model formats (QC, SMD, DMX), with batch conversion and SFM2 DMX to FBX support.
* [io\_texture\_VTF](https://github.com/REDxEYE/io_texture_VTF) ⚠️ Archived - Blender addon for importing and exporting Source Engine VTF texture files. (Archived)
* [io\_mesh\_SourceBSP](https://github.com/REDxEYE/io_mesh_SourceBSP) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2018-08-30 - Blender addon for importing and exporting Source Engine BSP map files.
* [SMDMaya](https://github.com/ThomasCat/SMDMaya) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2026-05-26 - Import and export Valve SMD and DMX files natively within Autodesk Maya.

#### Legacy Tools & Downloads (ModDB)

* [3D Studio Max SMD Import Plugin](https://www.moddb.com/games/half-life/downloads/3d-studio-max-smd-import-plug-in-import-smd-mode) - Plugin for 3DS Max 9, 2008, and 2009 to import SMD files from Valve games. Inspired by Cannonfodder's work for 3DS Max 5-7.
* [3D Studio Max SMD Export Plug-in](https://www.moddb.com/games/half-life/downloads/3d-studio-max-smd-export-plug-in) - Plugin for 3DS Max 9, 2008, and 2009 to export Source reference and animation sequence SMD files. Supports Standard and Multi/Sub-Object materials, Editable Mesh and Editable Poly geometry, Skin and Physique modifiers, and helper nodes.
* [Dvondrake's SMD exporter for Blender](https://www.moddb.com/groups/source-developers/downloads/dvondrake-smd-blender) - The first fully-functional Source engine SMD exporter for Blender. Supports reference, physics and animation, and has an accompanying video tutorial.
* [Autodesk Softimage Mod Tool 7.5 (Source Developers)](https://www.moddb.com/groups/source-developers/downloads/autodesk-softimage-mod-tool-75) - (Formerly the XSI Mod Tool) A completely free version of the Autodesk Softimage modelling package. Plugins for Source, CryEngine 2, Unreal Engine 3, XNA, Unity, and more are available.
* [Blender3D SMD Exporter (Half-Life 2)](https://www.moddb.com/games/half-life-2/downloads/blender3d-smd-exporter) - Provides support for Blender3D to export models to the Half-Life 2 SMD format. Supports rigged meshes as well as animations.
* [Goldsrc Model Viewer (V 0.3a Beta2)](https://www.moddb.com/games/half-life/downloads/goldsrc-model-viewer-v-03a-beta2-archived-for-other-use) - Simple model viewer for GoldSrc engine (Half-Life 1) models. Supports MDL format (v0.3a Beta2, archived). Note: MDL v4 support not yet added.
* [Half Life 2 MDL (v37) Importer V 0.9 Beta for 3DS](https://www.moddb.com/games/half-life-2/downloads/half-life-2-mdl-v37-importer-v-0-9-beta-for-3ds)
* [Jed's Half-Life Model Viewer 1.36](https://www.moddb.com/games/half-life/downloads/jeds-half-life-model-viewer-136) - Modified version of Mete Ciragan's Half-Life Model Viewer 1.25 with support for new Half-Life engine texture features (v1.36).
* [Source Model Viewer \[Build: 2019-04-23\] (Half-Life 2)](https://www.moddb.com/games/half-life-2/downloads/source-model-viewer-build-2019-04-23)
* [VTF-2-TGA Convertor Utility (Half-Life 2)](https://www.moddb.com/games/half-life-2/downloads/vtf-2-tga-convertor-utility) - Batch converter for VTF files to TGA format.
* [Texture Tool v1.2.1 (Half-Life)](https://www.moddb.com/mods/half-life-episode-two/downloads/texture-tool) - Tool for auto-generating texture flag scripts for the external loader feature in Trinity\Abyss. Useful for flagging hundreds of external high-resolution textures for in-game usage.
* [BSP Decompiler by 005 (Half-Life)](https://www.moddb.com/games/half-life/downloads/bsp-decompiler-by-005) - 005 (created by 005) is a decompiler for most BSP formats. Support may vary between engines. Also supports outputing to many different map editor file formats.
* [Bloody Knife + Addon DB Skin Tutorial (Counter-Strike: Source)](https://www.moddb.com/games/counter-strike-source/downloads/bloody-knife-addon-db-skin-tutorial) - Official tutorial addon with full narrated video tutorial (20+ minutes) on how to modify skins for Source-based games.
* [Bloodlines Character Search Tool v1.0 (Vampire: The Masquerade – Bloodlines)](https://www.moddb.com/games/vampire-the-masquerade-bloodlines/downloads/bloodlines-character-search-tool-v10)
* [Detail Tool v1.0 (Half-Life)](https://www.moddb.com/mods/half-life-episode-two/downloads/detail-tool-v10) - Tool for auto-generating "detailtextures.txt" for the detail file generator used by the Trinity\Abyss engine.
* [Game Server Browser & Admin Tool 1.2.1 (Half-Life 2)](https://www.moddb.com/games/half-life-2/downloads/game-server-browser-admin-tool-1-2-1) - A versatile tool that benefits both gamers and administrators alike.
* [GMad Extractor (Garry's Mod)](https://www.moddb.com/mods/garrys-mod-11-half-life-rebuilt/downloads/gmad-extractor) - A noice, custom, GUI that allows extracting Garry's Mod addon files (.GMA)
* [Half Life 1 Modding Kit Addon 2](https://www.moddb.com/mods/half-life-modding-kit/downloads/half-life-1-modding-kit-addon-2) - Map files and prefabs for Half-Life 1 modding. Includes: M60, Barrett 50 cal, Black Mesa Van, military tanks/trucks, vending machines, computers, and more. Not all tested.
* [Half-Life Asset Manager V3.0.0](https://www.moddb.com/games/half-life/downloads/half-life-asset-manager-v300) - Modeling tool based on Half-Life Model Viewer 2 with many improvements. Best model viewer for Half-Life 1. Note: Only supports Half-Life 1/GoldSource, not Half-Life 2/Source and Source 2 (v3.0.0).
* [Half-Life DLL Decompiler](https://www.moddb.com/games/half-life/downloads/half-life-dll-decompiler) - DLL decompiling tool for pre-Steam CD-retail versions of Half-Life. Source code provided for programmers and developers.
* [Half-Life: Insecure - Mapping Tools and Source Code v1.3](https://www.moddb.com/mods/half-life-insecure/downloads/half-life-insecure-mapping-tools-and-source-code-version-13) - Mapping tools and source code for Half-Life: Insecure mod. Made specifically for the Steam version of Half-Life (v1.3).
* [Half-Life Quick Mod Creation tool](https://www.moddb.com/games/half-life/downloads/half-life-quick-mod-creation-tool) - Quick tool for creating Half-Life mods from scratch. Generates custom liblist.gam and folder structure.
* [Half-Life to Quake 3 .MAP converter](https://www.moddb.com/games/half-life/downloads/half-life-to-quake-3-map-converter) - A small utility for mappers to convert .map output from worldcraft 3.3 to quake3 format, and back.
* [Half-Life Unified SDK Map Decompiler (Counter-Strike)](https://www.moddb.com/games/counter-strike/downloads/half-life-unified-sdk-map-decompiler) - Powerful tool by SamVanheer for decompiling Half-Life 1 BSP version 29 and 30 files. Written in C# for better maintainability and source code accessibility. Also supports original Half-Life and Half-Life Alpha 0.52 BSP files. Features two decompilation strategies (tree-based and face-to-brush) and applies Nodraw texture.
* [Keybinder Source Tool (Counter-Strike: Source)](https://www.moddb.com/games/counter-strike-source/downloads/keybinder-source-tool) - Bilingual (English/German) tool for configuring Counter-Strike: Source. Create or customize config files, bind keys for faster buying, and adjust 30+ graphic settings via simple mouse clicks. Features expert mode and backup functionality.
* [Jed's Half-Life Model Viewer 1.36 (Counter-Strike)](https://www.moddb.com/games/counter-strike/downloads/jeds-half-life-model-viewer-1361) - Model viewer with skin editor and pack viewer functionality for Half-Life models (v1.36).
* [Xash studioMDL Goldsrc Large Model Compiler (Counter-Strike)](https://www.moddb.com/games/counter-strike/downloads/xash-studiomdl-goldsrc-large-model-compiler) - Large model compiler for Half-Life mods supporting models up to 16MB, 9x blending, $texrendermode command, and textures up to 1024x1023.
* [Half-Life Studio Model Decompiler v1.2.1 (Win32, Linux, Mac)](https://www.moddb.com/games/half-life/downloads/half-life-studio-model-decompilerwin32-linux-mac) - Cross-platform Half-Life Studio Model decompiler (Windows, Linux, macOS). Similar to Kratisto's mdldec with improvements: detects texrendermodes, custom activities, Paranoia 2/PrimeXT features, fixed UV-coords and animations, Crowbar-like .qc output.
* [Valve Batch Compile Tool](https://www.moddb.com/engines/source/downloads/valve-batch-compile-tool) - A map compiling manager bringing a breeze to mappers.
* [XSI Valve Source Tools](https://www.moddb.com/downloads/valve-source-tools) - Source engine plugin for Mod Tool 7.5/6 and 32-bit Softimage. Features SMD import/export for models/animations, VMF import/export for Hammer maps, weightmap import/export, skeleton tools, and sample rigs (Valve Biped).
* [Wedge MDL Compiler (QC Generator) 1.0.1](https://www.moddb.com/company/wedge/downloads/wedge-mdl-compiler-qc-generator-1-0-1) - QC Generator and MDL Compiler for quickly creating QC files for model compilation. Russian language only (v1.0.1, registered version only).
* [Windows Vista/7 Phoneme Extractor 1.3](https://www.moddb.com/groups/source-developers/downloads/windows-vista7-phoneme-extractor-13) - A Faceposer phoneme extractor that functions on Windows Vista and 7 (and provides better results than under XP) for Source 2007 and 2009.
* [XSI Mod Tool 6.01](https://www.moddb.com/groups/source-developers/downloads/xsi-mod-tool-601) - A completely free version of the professional Softimage|XSI modelling package. Supports Source, CryEngine 2, Unreal Engine 3, XNA, Unity, and more.

### Unity

* [AssetStudio (Perfare)](https://github.com/Perfare/AssetStudio) ⚠️ Archived - Tool for exploring, extracting, and exporting assets and assetbundles (original version).
* [Il2CppDumper](https://github.com/Perfare/Il2CppDumper) ⭐ 9,310 | 🐛 156 | 🌐 C# | 📅 2024-08-18 - Unity IL2CPP reverse engineer tool for extracting IL2CPP metadata and converting IL2CPP binaries.
* [noclip.website (Unity)](https://github.com/magcius/noclip.website/tree/main/src/Common/Unity) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - From-scratch TypeScript/Rust reader for Unity SerializedFile and AssetBundle data. Reconstructs GameObject hierarchies, meshes, textures (including Crunch), and materials for in-browser rendering; drives the A Short Hike, Neon White, and Outer Wilds viewers.
* [Asset Bundle Extractor (UABE)](https://github.com/SeriousCache/UABE) ⚠️ Archived - Editor for .assets and AssetBundle files (archived; consider UABEA for active development).
* [XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator) ⭐ 3,343 | 🐛 445 | 🌐 C# | 📅 2026-07-24 - Universal translation framework for Unity games. Supports automatic text translation with various translator backends and IL2CPP support.
* [UnityExplorer](https://github.com/sinai-dev/UnityExplorer) ⚠️ Archived - In-game UI for exploring, debugging, and modifying IL2CPP and Mono Unity games.
* [UtinyRipper](https://github.com/mafaca/UtinyRipper) ⭐ 3,092 | 🐛 892 | 🌐 C# | 📅 2022-01-14 - Extracts and exports Unity assets from serialized `.assets` files and AssetBundle files into Unity-importable project format. Supports a wide range of Unity versions.
* [Il2CppInspector](https://github.com/djkaty/Il2CppInspector) ⭐ 3,031 | 🐛 66 | 🌐 C | 📅 2022-05-13 - Powerful automated tool for reverse engineering Unity IL2CPP binaries. Outputs IL2CPP type definitions, metadata and method pointers as C# stub code, creates .NET assembly shim DLLs, and generates C++ scaffolding for all types, methods, function pointers and API functions.
* [disunity](https://github.com/ata4/disunity) ⚠️ Archived - Early experimental Java command-line toolset for extracting and inspecting Unity asset and asset bundle files. Archived since 2018 and largely superseded by AssetStudio/UABEA, but historically significant.
* [Cpp2IL](https://github.com/SamboyCoding/Cpp2IL) ⭐ 2,575 | 🐛 46 | 🌐 C# | 📅 2026-08-17 - Decompiler for Unity IL (Intermediate Language) code and assets.
* [UABEA (Unity Asset Bundle Extractor Avalonia)](https://github.com/nesrak1/UABEA) ⭐ 2,390 | 🐛 144 | 🌐 C# | 📅 2026-05-11 - C# UABE for newer versions of Unity. Cross-platform Unity asset bundle and serialized file editor/extractor built with Avalonia.
* [AssetStudio (aelurum fork)](https://github.com/aelurum/AssetStudio) ⭐ 2,017 | 🐛 51 | 🌐 C# | 📅 2025-10-15 - Actively maintained fork with UI optimization and enhancements.
* [AssetStudio (zhangjiequan fork)](https://github.com/zhangjiequan/AssetStudio) ⭐ 1,846 | 🐛 29 | 🌐 C# | 📅 2024-03-04 - Continuation of Perfare's AssetStudio with support for new Unity versions and additional improvements.
* [UnityPy](https://github.com/K0lb3/UnityPy) ⭐ 1,400 | 🐛 20 | 🌐 Python | 📅 2026-08-01 - Python module that makes it possible to extract/unpack and edit Unity assets.
* [AssetsTools.NET](https://github.com/nesrak1/AssetsTools.NET) ⭐ 677 | 🐛 36 | 🌐 C# | 📅 2026-08-02 - Read and write Unity assets/bundle files, based on UABE.
* [IL2CPP\_Resolver](https://github.com/sneakyevil/IL2CPP_Resolver) ⭐ 472 | 🐛 15 | 🌐 C++ | 📅 2024-07-30 - Runtime API resolver for IL2CPP-compiled Unity games, locating classes, methods, and fields from global-metadata at runtime.
* [UABEANext](https://github.com/nesrak1/UABEANext) ⭐ 381 | 🐛 4 | 🌐 C# | 📅 2026-07-27 - Research and modding tool for SerializedFiles and Asset Bundles.
* [il2cpp-modder](https://github.com/juanmjacobs/il2cpp-modder) ⭐ 178 | 🐛 3 | 🌐 C# | 📅 2021-07-26 - Generate DLL injection templates for reverse engineering and modding Unity IL2CPP games. Automatically generates code for method hooks, field modifications, and implementation replacements without requiring manual pointer arithmetic.
* [unity-texture-toolkit](https://github.com/esterTion/unity-texture-toolkit) ⭐ 178 | 🐛 1 | 🌐 PHP | 📅 2026-07-14 - PHP toolbox for exporting Texture2D assets and other data from Unity3D asset bundles.
* [Beebyte-Deobfuscator](https://github.com/OsOmE1/Beebyte-Deobfuscator) ⭐ 129 | 🐛 7 | 🌐 C# | 📅 2021-02-17 - Plugin for Il2CppInspector that deobfuscates Beebyte-obfuscated IL2CPP type/member names in Unity game binaries.
* [Il2CppInspectorPlugins](https://github.com/djkaty/Il2CppInspectorPlugins) ⭐ 115 | 🐛 2 | 🌐 C# | 📅 2024-01-05 - Plugins for Il2CppInspector to inspect and reverse-engineer Unity game binaries and extract game data.
* [mikunyan](https://github.com/Ishotihadus/mikunyan) ⭐ 70 | 🐛 1 | 🌐 C++ | 📅 2026-01-10 - Scriptable Unity asset deserializer for Ruby.
* [UnityLive2DExtractor](https://github.com/aelurum/UnityLive2DExtractor) ⭐ 58 | 🐛 0 | 🌐 C# | 📅 2025-09-08 - Extracts Live2D Cubism 3 assets from Unity AssetBundles. Handles moc3 models, motion3 animations, physics3 configuration, and other Live2D format files.
* [TypeTreeDumps](https://github.com/AssetRipper/TypeTreeDumps) ⭐ 45 | 🐛 8 | 🌐 Shell | 📅 2026-07-24 - Archive of Unity version struct layouts (type tree information) since version 3.4.0, essential for asset format understanding.
* [texture2ddecoder](https://github.com/K0lb3/texture2ddecoder) ⭐ 21 | 🐛 2 | 🌐 C++ | 📅 2026-01-16 - Texture decoder library powering UnityPy's Texture2D asset decoding; distinct from KiruyaMomochi's Texture2DDecoder above. See also [texture2ddecoder-rs](https://github.com/K0lb3/texture2ddecoder-rs) ⭐ 33 | 🐛 10 | 🌐 Rust | 📅 2026-04-08, a pure Rust no-std rewrite.
* [Texture2DDecoder](https://github.com/KiruyaMomochi/Texture2DDecoder) ⭐ 7 | 🐛 1 | 🌐 C++ | 📅 2026-01-25 - Decodes Unity Texture2D assets to standard image files; based on AssetStudio.
* [CC3Decrypt](https://github.com/tge-was-taken/CC3Decrypt) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2017-10-14 - Decrypts Unity asset bundle headers used by Chain Chronicle 3.
* [Unity Asset Editor v0.2 (7 Days To Die)](https://www.moddb.com/games/7-days-to-die/downloads/unity-asset-editor) - Plugin-based asset editor, exporter, and importer for Unity Engine games. Can import and export assets in raw data format and be extended through plugins to support additional asset types (v0.2).
* [Unity3DCompressor](https://gitgoon.dev/IllusionMods/Unity3DCompressor) - Utility for compressing Unity asset bundles using LZ4 to reduce file size and improve load times.

### Unreal Engine

#### Full Engine Reimplementations & Source Ports

* [UnrealTournamentPatches](https://github.com/OldUnreal/UnrealTournamentPatches) ⭐ 1,472 | 🐛 556 | 📅 2026-08-15 - Community patch project for the original Unreal Tournament (1999) and Unreal (1998), maintaining and extending the original engine while reading the games' original asset formats.
* [SurrealEngine](https://github.com/dpjudas/SurrealEngine) ⭐ 1,094 | 🐛 14 | 🌐 C++ | 📅 2026-08-18 - Reimplementation of the Unreal Engine 1 engine that reads original Unreal/Unreal Tournament package/map assets to make the games playable on modern systems.

#### Asset Parsers & Libraries

* [UAssetGUI](https://github.com/atenfyr/UAssetGUI) ⭐ 1,030 | 🐛 15 | 🌐 C# | 📅 2026-08-14 - GUI tool for viewing and editing Unreal Engine UAsset files.
* [CUE4Parse](https://github.com/FabianFG/CUE4Parse) ⭐ 613 | 🐛 25 | 🌐 C# | 📅 2026-08-18 - C# Parser for UE archives.
* [UAssetAPI](https://github.com/atenfyr/UAssetAPI) ⭐ 479 | 🐛 4 | 🌐 C# | 📅 2026-08-14 - Low-level .NET library for reading and writing Unreal Engine game assets.
* [Unreal-Library](https://github.com/EliotVU/Unreal-Library) ⭐ 472 | 🐛 4 | 🌐 C# | 📅 2026-08-15 - Library for reading and writing Unreal Engine file formats.
* [JsonAsAsset](https://github.com/JsonAsAsset/JsonAsAsset) ⭐ 357 | 🐛 0 | 🌐 C++ | 📅 2026-08-18 - Unreal Engine plugin to import assets from JSON data exported by FModel.
* [JsonAsAsset](https://github.com/JsonAsAsset/Reflection) ⭐ 357 | 🐛 0 | 🌐 C++ | 📅 2026-08-18 - Unreal Engine asset reconstruction toolkit; an in-editor plugin that rebuilds engine assets (materials, data assets, curves, and more) from JSON dumps produced by CUE4Parse/FModel.
* [UEFormat](https://github.com/h4lfheart/UEFormat) ⭐ 323 | 🐛 2 | 🌐 Python | 📅 2026-08-14 - Library for working with Unreal Engine file formats.
* [OodleUE](https://github.com/WorkingRobot/OodleUE) ⭐ 143 | 🐛 0 | 🌐 C++ | 📅 2026-06-04 - Automatically pulls and packages the latest Oodle Data compression SDK builds from Unreal Engine 5's private git repo, since RAD's Oodle libraries are otherwise difficult to obtain standalone.
* [uasset-rs](https://github.com/jorgenpt/uasset-rs) ⭐ 119 | 🐛 3 | 🌐 Rust | 📅 2025-06-25 - Rust library for parsing Unreal Engine asset (.uasset) files.
* [pyUE4Parse](https://github.com/MinshuG/pyUE4Parse) ⭐ 85 | 🐛 8 | 🌐 Python | 📅 2026-03-21 - UE4 asset parser/reader in Python.
* [binfold](https://github.com/trumank/binfold) ⭐ 65 | 🐛 0 | 🌐 Rust | 📅 2026-07-17 - Fast symbol-porting tool that matches and transfers large numbers of symbols between similar binaries (e.g. across UE game versions/builds) using pattern signatures.
* [UEAssetToolkitGenerator](https://github.com/LongerWarrior/UEAssetToolkitGenerator) ⭐ 44 | 🐛 16 | 🌐 C# | 📅 2023-09-09 - UE asset extraction tool that converts compiled UE4 assets to JSON format.
* [UEAssetToolkit](https://github.com/Archengius/UEAssetToolkit) ⭐ 35 | 🐛 3 | 🌐 C++ | 📅 2022-10-06 - Toolkit for extracting and modifying Unreal Engine assets.
* [AssetTools](https://github.com/PedroMartinsMenezes/AssetTools) ⭐ 26 | 🐛 1 | 🌐 C# | 📅 2026-08-16 - Converts UE .uasset and .umap files to JSON and back, supporting UE5 asset formats.
* [Core](https://github.com/JsonAsAsset/Core) ⭐ 25 | 🐛 0 | 🌐 C# | 📅 2026-08-18 - Extension of JsonAsAsset's Reflection above that fetches referenced Unreal Engine assets automatically, hands-free.
* [ueformat-rust](https://github.com/Mqlvin/ueformat-rust) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-05-13 - Rust parser for UEFormat (.uemodel) meshes, converting UE4/5 extracted assets to STL format.

#### Explorers, Viewers & PAK/IoStore Tools

* [FModel](https://github.com/4sval/FModel) ⭐ 3,052 | 🐛 13 | 🌐 C# | 📅 2026-08-15 - Explorer and asset viewer for Unreal Engine archives, supporting UE4 and UE5.
  * Formats: PAK, UTOC, UCAS (IoStore), UAsset, localization files.
  * Features: Texture/mesh/audio preview, JSON export, map viewer with OpenGL renderer, diff between versions.
  * Games: Fortnite, Valorant, PUBG, MultiVersus, Stray, GTA III/Vice City/San Andreas (Definitive Edition), and many other UE4/UE5 titles.
* [UEViewer (UModel)](https://github.com/gildor2/UEViewer) ⭐ 2,912 | 🐛 26 | 🌐 C++ | 📅 2024-03-16 - Viewer and exporter for Unreal Engine 1-4 assets (UE Viewer).
  * [Compatibility Table](https://www.gildor.org/projects/umodel/compat) - Official compatibility list.
* [UnrealPakViewer](https://github.com/jashking/UnrealPakViewer) ⭐ 1,452 | 🐛 38 | 🌐 C++ | 📅 2026-03-06 - Viewer and extractor for UE4 PAK archive files supporting decompression and batch extraction.
* [UnrealPakTool](https://github.com/allcoolthingsatoneplace/UnrealPakTool) ⭐ 720 | 🐛 26 | 🌐 Batchfile | 📅 2021-08-28 - Extracts and lists .pak archive files from Unreal Engine 4 games (win64).
* [repak](https://github.com/trumank/repak) ⭐ 553 | 🐛 13 | 🌐 Rust | 📅 2026-02-20 - Unreal Engine .pak file library and CLI in Rust.
* [rust-u4pak](https://github.com/panzi/rust-u4pak) ⭐ 163 | 🐛 16 | 🌐 Rust | 📅 2023-02-01 - Rust CLI to unpack, pack, list, check, and mount Unreal Engine 4 .pak archives.
* [UnrealPakLoaderPlugin](https://github.com/calben/UnrealPakLoaderPlugin) ⭐ 69 | 🐛 0 | 🌐 C++ | 📅 2018-11-20 - Library simplifying runtime loading of Unreal Engine .pak files and their asset registries from within a UE project.
* [UnrealExporter](https://github.com/luk-gg/UnrealExporter) ⭐ 45 | 🐛 2 | 🌐 C# | 📅 2026-06-18 - Batch file exporter.
* [CPakParser](https://github.com/TheNaeem/CPakParser) ⭐ 31 | 🐛 0 | 🌐 C++ | 📅 2023-07-12 - High-performance UE5 PAK parser with Oodle decompression support and USMAP loading.
* [Snooper](https://github.com/FModel/Snooper/tree/opengl) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2026-08-16 - OpenGL based 3D viewer for cooked UE packages.
* [Unreal Media Ripper (UMR)](https://github.com/sezero/umr) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2022-03-16 - Extracts media from Unreal UPKG files, supporting versions 63-85 with 64-bit and big-endian system support.

#### SDK & Structure Dumpers

* [UEVR](https://github.com/praydog/UEVR) ⭐ 4,455 | 🐛 209 | 🌐 C++ | 📅 2026-07-26 - Universal Unreal Engine VR Mod. Powerful runtime reversing tool that provides an overlay for inspecting objects, classes, and properties in almost any UE4/5 game.
* [Dumper-7](https://github.com/Encryqed/Dumper-7) ⭐ 2,176 | 🐛 37 | 🌐 C | 📅 2026-08-06 - Unreal Engine SDK generator supporting all UE4 and UE5 versions, dumping engine classes/structs/offsets from a running game via DLL injection; the de facto standard modern UE SDK dumper and basis for several other tools already listed (e.g. UETools-GUI).
* [UEDumper](https://github.com/Spuckwaffel/UEDumper) ⭐ 1,379 | 🐛 0 | 🌐 C++ | 📅 2026-04-18 - UE 4.19-5.3 reverse engineering tool for dumping SDK, analyzing structures, and identifying memory offsets.
* [UE4Dumper](https://github.com/kp7742/UE4Dumper) ⭐ 947 | 🐛 26 | 🌐 C++ | 📅 2026-03-04 - Tool for dumping Unreal Engine 4 assets and structures.
* [UnrealDumper-4.25](https://github.com/guttir14/UnrealDumper-4.25) ⭐ 616 | 🐛 20 | 🌐 C++ | 📅 2023-01-28 - Unreal Engine SDK and structure dumper for extracting runtime data from UE game binaries.
* [AndUEDumper](https://github.com/MJx0/AndUEDumper) ⭐ 463 | 🐛 17 | 🌐 C++ | 📅 2026-08-03 - Android UE4/5 dumper generating SDK and function scripts, supporting ARM64, ARM, x86, and x86\_64 ABIs.
* [UETools-GUI](https://github.com/Cranch-fur/UETools-GUI) ⭐ 77 | 🐛 0 | 🌐 C++ | 📅 2026-08-18 - Dumper-7 based GUI tool for rapid debugging and SDK extraction from Unreal Engine games.
* [Gibbed.Unreflect](https://github.com/gibbed/Gibbed.Unreflect) ⭐ 9 | 🐛 1 | 🌐 C# | 📅 2022-12-08 - Runtime reflection tool for Unreal Engine games, enabling datamining of Borderlands and other UE titles through binary structure analysis.

#### Blueprint, UnrealScript & Shaders

* [UE-Explorer](https://github.com/UE-Explorer/UE-Explorer) ⭐ 351 | 🐛 4 | 🌐 C# | 📅 2026-08-15 - Package explorer and UnrealScript decompiler for classic Unreal Engine games, supporting `.upk` and `.u` files (UE1–UE3).
* [kismet-analyzer](https://github.com/trumank/kismet-analyzer) ⭐ 119 | 🐛 2 | 🌐 C# | 📅 2026-01-11 - Tools for analyzing and manipulating kismet bytecode in cooked Unreal Engine assets. Generates CFG graphs and class hierarchies from blueprint/kismet scripts.
* [UEShaderMapExtractor](https://github.com/WistfulHopes/UEShaderMapExtractor) ⭐ 54 | 🐛 0 | 🌐 C++ | 📅 2025-12-24 - Tool to extract and identify shaders from Unreal Engine material shadermaps.
* [kismet-debugger](https://github.com/trumank/kismet-debugger) ⭐ 33 | 🐛 1 | 🌐 C++ | 📅 2024-04-27 - Proof-of-concept debugger for stepping through kismet/blueprint bytecode in release-build Unreal Engine games (UE4SS mod).
* [unhood](https://github.com/yole/unhood) ⭐ 25 | 🐛 6 | 🌐 C# | 📅 2015-05-23 - Decompiler for the UnrealEngine 3 version of UnrealScript. Tested with Unreal Tournament 3 and compatible with other UE3 games (Gears of War, Mass Effect, Mirror's Edge, etc.).
* [BPPseudoCodeGen](https://github.com/Archengius/BPPseudoCodeGen) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2020-07-23 - Generate C++ pseudo-code from parsed blueprint code.

#### Maps, Saves, Localization & Mappings

* [UE4-AES-Key-Extracting-Guide](https://github.com/Cracko298/UE4-AES-Key-Extracting-Guide) ⭐ 466 | 🐛 4 | 📅 2024-04-25 - Guide for extracting AES encryption keys from Unreal Engine 4 games.
* [uesave](https://github.com/trumank/uesave) ⭐ 466 | 🐛 11 | 🌐 Rust | 📅 2026-04-23 - Rust library for reading and writing Unreal Engine save files.
* [UnrealMappingsDumper](https://github.com/TheNaeem/UnrealMappingsDumper) ⭐ 422 | 🐛 58 | 🌐 C++ | 📅 2022-12-19 - Generates .usmap mapping files for datamining UE4/5 game files.
* [Unreal-Mappings-Archive](https://github.com/TheNaeem/Unreal-Mappings-Archive) ⭐ 339 | 🐛 26 | 📅 2026-06-25 - Archive of Unreal Engine mapping files.
* [stove](https://github.com/bananaturtlesandwich/stove) ⭐ 161 | 🐛 15 | 🌐 Rust | 📅 2024-12-13 - Cooked Unreal Engine map editor for viewing and modifying levels without original project files.
* [UT4X-Converter](https://github.com/xtremexp/UT4X-Converter) ⭐ 74 | 🐛 6 | 🌐 Java | 📅 2026-06-30 - Converts Unreal Tournament maps between game versions (UT99/UT2004 → UT3/UT4 and UT4 → UT3).
* [UnrealLocresEditor](https://github.com/Snoozeds/UnrealLocresEditor) ⭐ 59 | 🐛 9 | 🌐 C# | 📅 2026-01-05 - GUI tool for editing Unreal localization resource (.locres) file format.
* [Unreal Save Dumper](https://github.com/GMatrixGames/UnrealSaveDumper) ⭐ 26 | 🐛 4 | 🌐 C# | 📅 2025-07-28 - CLI program to dump UE4/5 .sav save files to JSON, displaying versioning and engine information.
* [UEFN-AES-Loader](https://github.com/Aleman-sein-Vater/UEFN-AES-Loader) ⭐ 20 | 🐛 0 | 🌐 C++ | 📅 2026-06-30 - DLL for applying AES encryption keys to decrypt encrypted UE game assets and data files.
* [t3d2map](https://github.com/hogsy/t3d2map) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2021-11-08 - Converts Unreal `.T3D` text map documents to Quake's `.MAP` brush format.
* [UnrealKeyr](https://github.com/Falkrian/UnrealKeyr) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-07-20 - Finds and validates AES-256 encryption keys in Unreal Engine 4 game binaries, .pak files, and IoStore containers.

#### Modding Frameworks & Toolkits

* [RE-UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) ⭐ 2,805 | 🐛 257 | 🌐 C++ | 📅 2026-08-19 - Lua scripting system, SDK generator, blueprint mod loader, and live property editor for UE4/5 games.
* [UE-Modding-Tools](https://github.com/Buckminsterfullerene02/UE-Modding-Tools) ⭐ 1,214 | 🐛 0 | 📅 2026-08-08 - Databank of generic UE modding tools.
* [UE\_Modding](https://github.com/Dmgvol/UE_Modding) ⭐ 576 | 🐛 0 | 📅 2026-06-10 - Comprehensive collection of guides and resources for modding Unreal Engine 4 and 5 games.
* [UE4-DDS-Tools](https://github.com/matyalatte/UE4-DDS-Tools) ⭐ 135 | 🐛 16 | 🌐 Python | 📅 2024-05-19 - Texture modding tool for Unreal Engine games; injects and extracts DDS textures from .uasset/.uexp files without needing the original source project.
* [unreal\_auto\_mod](https://github.com/Mythical-Github/unreal_auto_mod) ⭐ 47 | 🐛 1 | 🌐 Python | 📅 2025-04-10 - Tools for managing Unreal Engine mod projects and automated building.
* [UE.Toolkit](https://github.com/RyoTune/UE.Toolkit) ⭐ 15 | 🐛 1 | 🌐 C# | 📅 2026-08-19 - Modding toolkit for UE games with UObject/UDataTable inspection and editing via Reloaded II, runtime data modification.

#### DCC Plugins & ActorX (Blender / 3ds Max)

* [io\_scene\_psk\_psa](https://github.com/DarklightGames/io_scene_psk_psa) ⭐ 619 | 🐛 5 | 🌐 Python | 📅 2026-07-16 - Blender addon for importing and exporting PSK (skeletal mesh) and PSA (animation) formats used in Unreal Engine. Supports PSK/PSKX mesh import with vertex normals, extra UV channels, vertex colors, and shape keys.
* [blender3d\_import\_psk\_psa](https://github.com/Befzz/blender3d_import_psk_psa) ⭐ 561 | 🐛 39 | 🌐 Python | 📅 2023-12-21 - Blender addon for importing PSK (skeletal mesh) and PSA (animation) formats from Unreal Engine.
* [ActorX](https://github.com/gildor2/ActorX) ⭐ 101 | 🐛 1 | 🌐 C++ | 📅 2021-09-05 - Epic Games' ActorX plugin source code for Unreal skeletal animation format (PSK/PSA).
* [SkelEdit](https://github.com/gildor2/SkelEdit) ⭐ 46 | 🐛 0 | 🌐 C++ | 📅 2020-02-29 - Cross-platform PSK/PSKX/PSA (ActorX) skeletal mesh viewer with wxWidgets UI and OpenGL renderer.
* [blender\_t3d](https://github.com/crapola/blender_t3d) ⭐ 24 | 🐛 5 | 🌐 Python | 📅 2025-06-12 - Blender import/export add-on for Unreal `.T3D` map files.
* [io\_scene\_ase](https://github.com/DarklightGames/io_scene_ase) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2026-07-16 - Blender exporter for the legacy ASE (ASCII Scene Export) format used by Unreal Engine 1 & 2 games (e.g., Unreal Tournament 2004).

#### Legacy Tools & Downloads (ModDB)

* [ActorX Tools](https://www.moddb.com/groups/unreal-tournament-3-mod-developers/downloads/actorx-tools-for-maya-85-3dsmax-9) - The ActorX Tool is a plugin for various 3d creation packages allowing you to import skeletal meshes and animations in Unreal Engine games.
* [ActorX Softimage Exporter](https://www.moddb.com/downloads/actorx-softimage-exporter) - ActorX plugin for Softimage to export skeletal meshes and animations to binary formats for Unreal Editor import. Install by extracting to \Application\Plugins.
  * Formats: .psk, .psa (skeletal meshes and animations), .ase (static meshes).
* [U3D](https://www.moddb.com/games/unreal-tournament/downloads/u3d-v10-unreal-model-conversion-tool) - Presently there are at least four other unreal model converters out there but as you may know, each one has it's own set of limitations that either make the conversion process a pain in the rear, or plug in to a specific version of 3D StudioMAX.
* [Unreal to Deus Ex mesh converter](https://www.moddb.com/games/deus-ex/downloads/unreal-to-deus-ex-mesh-converter) - Converts Unreal/Unreal Tournament meshes to Deus Ex format. Enables use of Unreal export utilities (MilkShape 3D, 3ds2unr, etc.).
* [DUT TOOL-2.0.2.0 (Unreal Tournament 3)](https://www.moddb.com/mods/defend-unreal-territories/downloads/dut-tool-2020) - C# tool for creating Unreal Tournament 3 mods (v2.0.2.0).
* [UEd Style Tools for Maya (Unreal Tournament)](https://www.moddb.com/games/unreal-tournament/downloads/ued-style-tools-for-maya) - Tool window for Maya providing UEd-style CSG tools and addressing common issues when building meshes/brushes for Unreal Editor maps. Handles size differences between Maya and UEd with fast controls.
* [UShock - Unreal level viewer (Unreal Tournament)](https://www.moddb.com/games/unreal-tournament/downloads/ushock-unreal-level-viewer) - Experimental Unreal level viewer for Unreal Engine games from Unreal 1 to UT2004 (tested: Unreal 1, UT99, WOT, Unreal 2, UT2003, UT2004). Loads dependent packages (textures, static meshes, etc.) and displays using OpenGL renderer.
* [Unreal Unit Converter](https://www.moddb.com/downloads/unreal-unit-converter1)
* [PS3 Mod Tools version 2.1 (Unreal Tournament 3)](https://www.moddb.com/games/unreal-tournament-3/downloads/ps3-mod-tools-version-21) - Tools for publishing Unreal Tournament 3 modifications with PS3 support (v2.1).
* [WOTgreal Package Exporter (Unreal Tournament)](https://www.moddb.com/games/unreal-tournament/downloads/wotgreal-package-exporter) - Tool for viewing and exporting static (non-animated) textures, models, and sounds from Unreal Engine 1/2 games. Also decompiles UC scripts. Created by Dean Harmon.
* [Advanced Model Support SDK (Unreal Tournament)](https://www.moddb.com/mods/ut-skins-voices-mods-fixes/downloads/advanced-model-support-sdk) - Documentation for Unreal Tournament modellers creating plugin player models with Advanced Model Support v102 or v110. Also for modellers and programmers working on larger mods using skeletal models and/or Advanced Model Support code.
* [Blender 2.49 Scripts for UT2004](https://www.moddb.com/games/unreal-tournament-2004/downloads/blender-249-scripts-for-ut2004) - Scripts with all PSA / PSK converters available IQM converter for use with noesis ASE export And other useful stuff
* [February 2015 Unreal Development Kit (UDK)](https://www.moddb.com/engines/unreal-development-kit/downloads/february-2015-unreal-development-kit-udk) - Final version of the UDK by Epic (February 2015 release). Unreal Development Kit is the free edition of Unreal Engine 3.
* [UnrealKey](https://github.com/devinacker/UnrealKey) ⭐ 145 | 🐛 12 | 🌐 C++ | 📅 2022-11-20 - Tool for automatically finding AES-256 decryption keys for Unreal Engine 4 encrypted pak files, by launching a game's executable and detecting the loading/decryption of encrypted paks.

### CryEngine

* [Far-Cry-1-Source-Full](https://github.com/StrongPC123/Far-Cry-1-Source-Full) ⭐ 966 | 🐛 6 | 🌐 C++ | 📅 2024-04-09 - Full source code for Far Cry 1 by Crytek — leaked non-commercial reference release for CryEngine 1, useful for understanding original CryEngine file formats and engine internals.
* [Cryengine-Converter](https://github.com/Markemp/Cryengine-Converter) ⭐ 282 | 🐛 43 | 🌐 C# | 📅 2026-06-21 - Converts CryEngine binary asset files to Collada (.dae) for import into Blender, Maya, and 3ds Max.
  * Formats: .cgf (geometry), .chr (character), .skin (skinned mesh), .caf (animation), .dba (animation database), .cryxml (binary XML).
  * Games: MechWarrior Online, ArcheAge, Hunt: Showdown, Star Citizen.
* [DDS-Unsplitter](https://github.com/Markemp/DDS-Unsplitter) ⭐ 11 | 🐛 4 | 🌐 C# | 📅 2025-05-26 - Reassembles CryEngine split .dds texture files (where a texture is stored as a base .dds plus one or more patch/mip sidecar files) back into a single usable .dds.
* [010-Templates](https://github.com/Markemp/010-Templates) ⭐ 11 | 🐛 0 | 📅 2026-04-19 - 010 Editor binary templates for CryEngine, Lumberyard, and Open 3D Engine asset files.
  * Formats: .cgf, .chr, .skin (geometry/character/skinned mesh), .caf, .dba (animation), with a unified entry point that auto-detects CryTek / CrChF / Ivo variants.
  * Games: MechWarrior Online, ArcheAge (CryTek format), Hunt: Showdown (CrChF), Star Citizen (Ivo).
* [OGPreyExplorer](https://github.com/ogarvey/OGPreyExplorer) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-08-14 - All-in-one asset tool for Prey (2017): browses and extracts PAK archives, and converts .cgf/.skin model files to .dae and .glTF via Cryengine-Converter.
* [Far Cry 1 Noesis import plugin](https://www.moddb.com/games/far-cry/downloads/far-cry-1-noesis-import-plugin) - Noesis plugin for importing Far Cry 1 models. Export from Noesis to CryEngine is not supported.
* [Far Cry 1 3dsmax 9 plugin](https://www.moddb.com/games/far-cry/downloads/far-cry-1-3dsmax-9-plugin) - 3DS Max 9 plugin for exporting Far Cry 1 models.
* [CryEngine 2 3d archive](https://www.moddb.com/games/crysis/downloads/cryengine-2-3d-archive) - Archive of CryEngine 2 resources and files useful for creating modifications for Crysis and Crysis Wars.
* [CryENGINE 2 Resources (Crysis)](https://www.moddb.com/games/crysis/downloads/cryengine-2-resources1) - Archive of CryEngine 2 resources and files useful for creating modifications for Crysis and Crysis Wars.
* [CryEngine2 Archive (Crysis)](https://www.moddb.com/games/crysis/downloads/cryengine2-archive) - Archive of CryEngine 2 tutorials in browser-readable format for Crysis modding.
* [Crysis Benchmarking Tool 1.05](https://www.moddb.com/games/crysis/downloads/crysis-benchmarking-tool-1-05) - Robust front-end tool for benchmarking Crysis (v1.05).
* [Cryengine Mod SDK 1.4 (Far Cry)](https://www.moddb.com/games/far-cry/downloads/cryengine-mod-sdk-14) - Official Far Cry 1 SDK released by Crytek (v1.4).
* [Enhanced Gibbed Tools with Hash Decoder (Far Cry 2)](https://www.moddb.com/games/far-cry-2/downloads/enhanced-gibbed-tools-with-hash-decoder) - Modified version of Gibbed's Far Cry 2 tools by Wobatt with hash decoder functionality. Based on original tools by Rick (Gibbed) with additional enhancements. Not officially endorsed by original author.
* [Far Cry 2 Mod Tools](https://www.moddb.com/mods/far-cry-2-redux/downloads/far-cry-2-mod-tools) - Updated version of Far Cry 2 mod tools with additional features and improved compatibility.
* [Far Cry 3 Mod Tools](https://www.moddb.com/mods/far-cry-3-redux/downloads/far-cry-3-mod-tools) - Updated modding tools for Far Cry 3.
* [FCMAP Tool v0.3B-0.5B (Far Cry)](https://www.moddb.com/mods/fcmap-tool/downloads/fcmap-tool-v03b-05b) - 💙 FCMAP is the first automated tool in the world of Far Cry 1 mapping and modding, written by me in Python 3.
* [FCMAP Tool v1.0 (Far Cry)](https://www.moddb.com/mods/fcmap-tool/downloads/fcmap-tool-v05-10) - 💙 FCMAP is the first automated tool in the world of Far Cry 1 mapping and modding, written by me in Python 3.

### Dagor Engine

* [Dagor Engine](https://github.com/GaijinEntertainment/DagorEngine) ⭐ 2,947 | 🐛 74 | 🌐 C++ | 📅 2026-08-16 - Open-source release of the Dagor Engine (War Thunder, Enlisted) including parts of the toolchain.
* [dagor-file-formats](https://github.com/AlexKimov/dagor-file-formats) ⭐ 4 | 🐛 0 | 📅 2024-04-16 - Community reverse-engineering research and format templates for the Dagor Engine.

### Fox Engine

* [FoxKit](https://github.com/youarebritish/FoxKit) ⭐ 47 | 🐛 21 | 🌐 ShaderLab | 📅 2024-05-19 - General-purpose Fox Engine data editor. Includes a Route Builder for AI routes (.frt).
* [FtexTool](https://github.com/Atvaark/FtexTool) ⭐ 43 | 🐛 3 | 🌐 C# | 📅 2017-10-31 - Fox Engine Texture (.ftex) to DDS converter.
* [FoxTool](https://github.com/Atvaark/FoxTool) ⭐ 37 | 🐛 0 | 🌐 C# | 📅 2020-09-01 - Fox Engine file format parsing and manipulation tool.
* [FoxEngine.TranslationTool](https://github.com/Atvaark/FoxEngine.TranslationTool) ⭐ 28 | 🐛 8 | 🌐 C# | 📅 2025-05-18 - Translation and modding tool for Fox Engine games, providing file format parsing and manipulation.
* [FvTwool](https://github.com/BobDoleOwndU/FvTwool) ⭐ 11 | 🐛 0 | 🌐 C# | 📅 2024-07-15 - MGSV .fv2 editor.
* [GzsTool](https://github.com/BobDoleOwndU/GzsTool) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2017-05-29 - Fox Engine dat, fpk, fpkd, pftxs and sbp unpacker/repacker.
* [FoxLib](https://github.com/youarebritish/FoxLib) ⭐ 8 | 🐛 3 | 🌐 F# | 📅 2018-10-24 - Library for reading and writing Fox Engine file formats (lba, frt, fmtt, pcsp, fv2).
* [FoxEngineLib](https://github.com/cra0kalo/FoxEngineLib) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2017-01-20 - Library for parsing 3D formats used by the Fox Engine in Metal Gear Solid V.

### Hedgehog Engine

* [HedgeLib](https://github.com/Radfordhound/HedgeLib) ⭐ 119 | 🐛 46 | 🌐 C++ | 📅 2026-06-25 - C++ library and collection of tools that aims to make modding games in the Sonic the Hedgehog franchise easier.
* [RflTemplates](https://github.com/blueskythlikesclouds/RflTemplates) ⭐ 18 | 🐛 0 | 📅 2024-12-13 - 010 Editor binary templates for Hedgehog Engine 2 RFL files.
* [Hedgehog Engine Blender I/O](https://github.com/hedge-dev/HedgehogEngineBlenderIO) ⭐ 14 | 🐛 4 | 🌐 Python | 📅 2026-03-19 - WIP Blender add-on for Hedgehog Engine I/O including import/export and animation editing.
* [surfboard-templates](https://github.com/DeaTh-G/surfboard-templates) ⭐ 7 | 🐛 1 | 🌐 C | 📅 2024-05-10 - Templates for various versions of the SWIF file format used primarily in Hedgehog Engine games.
* [Shadow-the-Hedgehog-.BON-MTN-import-export-tool](https://github.com/Shadowth117/Shadow-the-Hedgehog-.BON-MTN-import-export-tool) ⭐ 3 | 🐛 0 | 🌐 MAXScript | 📅 2019-09-20 - Script for applying external properties from Shadow the Hedgehog .BON files to their respective bones in .DFF model files after importing with AAP's RWIO plugin for 3ds Max.
* [SonicHeroesUTXEditor](https://github.com/Heroes-Hacking-Central/SonicHeroesUTXEditor) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2025-12-12 - UTX editor for Sonic Heroes.
* [HedgehogEngineReversing](https://github.com/WistfulHopes/HedgehogEngineReversing) ⭐ 0 | 🐛 0 | 📅 2024-01-18 - BinSync project for Hedgehog Engine reversing.

### Northlight Engine

* [OpenAWE](https://github.com/OpenAWE-Project/OpenAWE) ⭐ 212 | 🐛 13 | 🌐 C++ | 📅 2026-05-16 - Open source reimplementation of the Alan Wake Engine (later known as Northlight).
* [neat](https://github.com/TomEvin/neat) ⭐ 55 | 🐛 3 | 📅 2023-10-28 - Northlight Engine Archive Tool (supports Quantum Break, Control, Alan Wake 2).
* [control-unpack](https://github.com/profMagija/control-unpack) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2021-01-09 - Extractors and converters for various Northlight file formats used in Control (rmdp, rmdl, texco, strings).
* [NorthlightFontMaker](https://github.com/eprilx/NorthlightFontMaker) ⭐ 11 | 🐛 0 | 🌐 C# | 📅 2026-07-09 - Tool for creating and editing custom bitmap fonts for the Northlight engine (\*.binfnt).
* [BlenderNorthlight](https://github.com/OpenAWE-Project/BlenderNorthlight) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-06-07 - Blender plugin for loading binmsh/binfbx files from Northlight Engine games (Control, Alan Wake 2, Quantum Break).

### Pragma Engine

* [io\_pragma\_engine](https://github.com/REDxEYE/io_pragma_engine) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2020-04-02 - Blender plugin for importing and exporting Pragma Engine models.

### Build Engine

* [Raze](https://github.com/ZDoom/Raze) ⭐ 880 | 🐛 138 | 🌐 C++ | 📅 2025-11-19 - GZDoom-derived source port for Build engine games including Duke Nukem 3D, Blood, Shadow Warrior, Redneck Rampage, Exhumed/Powerslave and Ion Fury, reading each game's original GRP/RFF/ART assets.
* [NBlood](https://github.com/NBlood/NBlood) ⭐ 793 | 🐛 115 | 🌐 C++ | 📅 2026-08-18 - Reverse-engineered source ports of Build engine games (Blood, Duke Nukem 3D, Redneck Rampage, Shadow Warrior, Exhumed, PowerSlave) based on EDuke32 engine technology.
* [jfbuild](https://github.com/jonof/jfbuild) ⭐ 134 | 🐛 3 | 🌐 C | 📅 2026-06-28 - JonoF's port of Ken Silverman's Build engine, reading the engine's native ART/MAP/GRP data. Depends on his [jfaudiolib](https://github.com/jonof/jfaudiolib) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2025-12-27 port of the AudioLib sound library used by Apogee games, and powers his [jfduke3d](https://github.com/jonof/jfduke3d) ⭐ 139 | 🐛 4 | 🌐 C | 📅 2026-01-25 and [jfsw](https://github.com/jonof/jfsw) ⭐ 97 | 🐛 3 | 🌐 C | 📅 2026-01-25 ports below.
* [vanilla\_duke3D](https://github.com/fabiensanglard/vanilla_duke3D) ⭐ 127 | 🐛 0 | 🌐 C++ | 📅 2013-01-23 - Mirror of Ken Silverman's original "Build" engine source release (GAME.EXE and companion tools), the DOS engine behind Duke Nukem 3D, Shadow Warrior, and Blood, reading the engine's native MAP/ART/GRP data.
* [Blood-RE](https://github.com/NBlood/Blood-RE) ⭐ 35 | 🐛 0 | 🌐 C++ | 📅 2025-12-06 - Source code reconstruction of Blood, reading the original game's GRP/ART/MAP data.
* [jftekwar](https://github.com/jonof/jftekwar) ⭐ 27 | 🐛 1 | 🌐 C | 📅 2026-06-03 - JonoF's Build engine port of Capstone Software's William Shatner's TekWar, reading the original game's ART/MAP/palette data. See also [jfwhaven](https://github.com/jonof/jfwhaven) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2026-01-25, his port of Capstone's Witchaven.
* [buildengine](https://github.com/icculus/buildengine) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2021-07-12 - icculus.org's Linux/macOS port of Ken Silverman's Build Engine, the DOS engine behind Duke Nukem 3D, Shadow Warrior, and Blood, reading the engine's native MAP/ART/GRP data.
* [BUILD Map Importer](https://github.com/jensnt/io_import_build_map) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2025-12-02 - Blender add-on for importing BUILD maps (Blood, Duke Nukem 3D, etc.) that can auto-extract textures from `.ART`, `.GRP`, and `.RFF` files.
  * Import options: split sectors/walls/sky, preserve sprite offsets, reuse materials, shade to vertex colors, and store original map data in custom properties.
* [Build286](https://github.com/FrenkelS/Build286) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2026-02-14 - Port of Ken Silverman's Build Engine to 16-bit DOS PCs (e.g. 286 processors with VGA/MCGA graphics).
* [Blood: Fresh Supply Modding Guide](https://github.com/svkaiser/BloodEX-Modding-Docs) ⭐ 3 | 🐛 0 | 📅 2026-01-13 - Documents loading persistent and loose mod files for Blood: Fresh Supply, including its RFF and KPF resource formats.
* [Xtract (macOS port)](https://github.com/rusq/xtract) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2024-11-25 - macOS-compatible port of Xtract, extracting art assets from Build engine GRP archive files (Duke Nukem 3D, Blood, and others).
* [Build palette editing tools (Duke Nukem 3D)](https://www.moddb.com/mods/black-shadow/downloads/build-palette-editing-tools) - Tools for manipulating and creating palettes for BUILD Engine games including Duke Nukem 3D. Work in progress.

### Cobra Engine

* [cobra-tools](https://github.com/OpenNaja/cobra-tools) ⭐ 152 | 🐛 15 | 🌐 Python | 📅 2026-08-18 - Suite of GUI tools for extracting and modifying OVL and OVS archives, as well as editing associated file formats and models for the Cobra Engine (Frontier Developments).

### 3DSTATE

* [3DS MAX 5 and 3DS MAX 6 converter](https://www.moddb.com/engines/3dstate/downloads/3ds-max-5-and-3ds-max-6-converter) - Converts 3DS Max scenes to 3DSTATE WLD format, preserving lighting, shadows, and effects. Includes script for rendering to texture and converting to binary 3dstate format.

### AtiSushi Engine

* [AtiSushi](https://github.com/REDxEYE/AtiSushi) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-11-22 - UniLoader plugin for importing AtiSushi engine files.

### Genie Engine

* [geniedoc](https://github.com/aap/geniedoc) ⭐ 16 | 🐛 1 | 📅 2017-04-14 - Documentation of Age of Empires II .dat files (Genie Engine formats).

### Bruns Engine

* [brunsdec](https://github.com/Bioruebe/brunsdec) ⭐ 9 | 🐛 0 | 🌐 Haxe | 📅 2019-01-29 - Decryptor for Bruns Engine encrypted assets (magic number `EENC`), deriving a per-file XOR key from the file header to recover encrypted PNG images.

### RPG Maker

* [EasyRPG Player](https://github.com/EasyRPG/Player) ⭐ 1,214 | 🐛 435 | 🌐 C++ | 📅 2026-08-03 - Open-source interpreter that runs RPG Maker 2000/2003 games natively, reading their LCF data formats (LMU maps, LDB/LMT databases) via liblcf.
* [mkxp](https://github.com/Ancurio/mkxp) ⭐ 586 | 🐛 45 | 🌐 C++ | 📅 2026-01-18 - Open-source reimplementation of the Ruby Game Scripting System (RGSS) used by RPG Maker XP, VX, and VX Ace, running games natively by reading their RGSSAD/RGSS2A/RGSS3A archives. See also the more actively maintained [mkxp-z fork](https://github.com/mkxp-z/mkxp-z) ⭐ 365 | 🐛 154 | 🌐 C++ | 📅 2026-06-30.
* [EasyRPG Editor](https://github.com/EasyRPG/Editor) ⭐ 421 | 🐛 45 | 🌐 C++ | 📅 2026-07-06 - Qt6-based game editor for creating EasyRPG games; can import and edit existing RPG Maker 2000/2003 projects by reading/writing their LCF map and database files via liblcf.
* [Luminol](https://github.com/Astrabit-ST/Luminol) ⭐ 146 | 🐛 25 | 🌐 Rust | 📅 2026-08-11 - Cross-platform RPG Maker XP/VX/VX Ace editor rewrite in Rust, reading the RGSS project data (rxdata/rvdata maps and databases).
* [liblcf](https://github.com/EasyRPG/liblcf) ⭐ 140 | 🐛 41 | 🌐 C++ | 📅 2026-08-03 - C++ library for reading and writing the LCF formats used by RPG Maker 2000/2003 and EasyRPG projects.
* [rgssad](https://github.com/luxrck/rgssad) ⭐ 41 | 🐛 0 | 🌐 Rust | 📅 2020-01-15 - Extract rgssad/rgss2a/rgss3a files from RPG Maker games.
* [RGSS-Decryptor](https://github.com/usagirei/RGSS-Decryptor) ⭐ 38 | 🐛 3 | 🌐 C# | 📅 2018-08-04 - Command-line decryptor for RGSS archives (RPG Maker XP/VX/VX Ace). See also [Bioruebe's fork](https://github.com/Bioruebe/RGSS-Decryptor) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2018-08-03 adding a Windows shell extension.
* [rmvdec](https://github.com/Bioruebe/rmvdec) ⭐ 32 | 🐛 0 | 🌐 C# | 📅 2023-01-27 - Decrypter for RPG Maker MV resource files (.rpgmvp, .rpgmvo, .rpgmvm).
* [rpga](https://github.com/elizagamedev/rpga) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2015-12-13 - RPG archive extraction and creation utility. Can extract and create RPG Maker XP+ archives and Wolf RPG archives (though Wolf archive creation does not work yet).

### Ren'Py

*Visual novel engine used in many indie and commercial visual novels.*

* [unrpa](https://github.com/Lattyware/unrpa) ⭐ 754 | 🐛 20 | 🌐 Python | 📅 2022-06-27 - Program to extract files from the RPA archive format used in Ren'Py visual novels.

### BGI (Buriko General Interpreter)

*Visual novel engine (Ethornell) used by many Japanese visual novels.*

* [BGIKit](https://github.com/xupefei/BGIKit) ⚠️ Archived - Script decoder and encoder for the Ethornell/BGI visual novel engine (archived).
* [openbgi](https://github.com/Cytlan/openbgi) ⭐ 70 | 🐛 0 | 🌐 C | 📅 2026-08-08 - Open-source reimplementation of the Ethornell/BGI (Buriko General Interpreter) visual novel engine.
* [BGI](https://github.com/txt231/BGI) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2026-08-02 - Experimental reimplementation of the BGI (Buriko General Interpreter) visual novel engine: bytecode VM emulator (BGITool), opcode disassembler (BGIPiler) and tracer (BGITracer), and a resource viewer (BGIExplorer) for BGI's texture/bitmap formats.

### RealLive

*Visual novel engine used by Key (Clannad, Kanon, Little Busters!), Circus, and other Japanese publishers.*

* [rlvm](https://github.com/eglaysher/rlvm) ⭐ 166 | 🐛 22 | 🌐 C++ | 📅 2024-09-08 - Open-source RealLive engine clone for Linux and macOS, reading original RealLive visual novel game data.

### Kirikiri

*Visual novel engine (KAG/TJS scripting) used by many Japanese visual novels.*

* [Xp3Viewer-AfterStory](https://github.com/Inori/Xp3Viewer-AfterStory) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2015-03-10 - Updated viewer for Kirikiri's XP3 archive format.

### Glulx VM (Interactive Fiction)

*Virtual machine format for parser-based interactive fiction, designed by Andrew Plotkin as a successor to the Z-machine; the standard compilation target for Inform 7.*

* [Quixe](https://github.com/erkyrath/quixe) ⭐ 173 | 🐛 26 | 🌐 JavaScript | 📅 2025-09-01 - Pure-JavaScript interpreter for the Glulx interactive-fiction virtual machine, playing .ulx/.gblorb game files directly in the browser with no server component.
* [Glulxe](https://github.com/erkyrath/glulxe) ⭐ 124 | 🐛 6 | 🌐 C | 📅 2026-05-05 - Reference interpreter for the Glulx virtual machine, written by its designer Andrew Plotkin.
* [Git](https://github.com/DavidKinder/Git) ⭐ 56 | 🐛 3 | 🌐 C | 📅 2026-05-03 - Fast interpreter for the Glulx interactive-fiction virtual machine, playing .ulx/.gblorb game files; roughly 5x faster than Glulxe and about twice as fast as Frotz on equivalent Inform-compiled stories.
* [IF Archive Specs](https://github.com/iftechfoundation/ifarchive-if-specs) ⭐ 27 | 🐛 9 | 🌐 Python | 📅 2026-05-30 - Official specification documents for the Glk display API, the Glulx virtual machine, and the Blorb resource-container format used by Z-machine/Glulx interactive fiction.
* [if-decompiler](https://github.com/curiousdannii/if-decompiler) ⭐ 22 | 🐛 9 | 🌐 Rust | 📅 2021-07-11 - Decompiles Glulx story files back into C source code (Glulxtoc/IF-Decompiler), for recovering original game logic from compiled .ulx files.
* [Windows-Glulxe](https://github.com/DavidKinder/Windows-Glulxe) ⭐ 12 | 🐛 0 | 🌐 HTML | 📅 2026-08-18 - Windows front-end for Andrew Plotkin's Glulxe reference interpreter combined with Windows Glk, playing Glulx .ulx/.gblorb game files.
* [Zag](https://github.com/Banbury/zag) ⭐ 10 | 🐛 4 | 🌐 Java | 📅 2020-01-19 - Actively maintained fork of Andrew Plotkin's Zag Glulx interpreter (Python), updated to support Glulx spec version 3; recommended over the original repo by its own author.
* [glulx-llvm](https://github.com/dfremont/glulx-llvm) ⭐ 10 | 🐛 2 | 🌐 C | 📅 2021-11-14 - Experimental LLVM backend targeting the Glulx interactive-fiction virtual machine, allowing C and other LLVM-frontend languages to compile to Glulx .ulx bytecode.
* [babel-tool](https://github.com/iftechfoundation/babel-tool) ⭐ 10 | 🐛 2 | 🌐 HTML | 📅 2026-03-01 - Reference implementation of the Treaty of Babel: a multi-format C API and CLI suite (babel, babel-get, babel-list, ifiction-aggregate, etc.) for extracting metadata/cover art from interactive-fiction story files, identifying their VM format and IFID, and bundling story files with metadata into the Blorb resource-container format.
* [mrifk](https://github.com/wertercatt/mrifk) ⭐ 6 | 🐛 0 | 🌐 Haskell | 📅 2025-09-11 - Decompiler and disassembler for the Glulx virtual machine, reconstructing readable Inform-6-style disassembly and source listings from compiled .ulx story files.

### Z-machine VM (Interactive Fiction)

*Virtual machine format used by Infocom's parser-based text adventures (Zork, Enchanter, etc.) and still a common compilation target for modern works written in Inform 6/7; predecessor to Glulx.*

* [Inform 7](https://github.com/ganelson/inform) ⭐ 1,637 | 🐛 9 | 🌐 C | 📅 2026-06-24 - Core distribution of the Inform 7 natural-language interactive fiction authoring system, compiling through Inform 6 to Z-code or Glulx bytecode.
* [Parchment](https://github.com/curiousdannii/parchment) ⭐ 483 | 🐛 42 | 🌐 TypeScript | 📅 2026-08-17 - The actively maintained successor to Andrew Plotkin's original Parchment web interactive-fiction player, running Z-machine and Glulx games in the browser via WASM-compiled interpreters (through the Emglken/Glk bridge).
* [Gargoyle](https://github.com/garglk/garglk) ⭐ 423 | 🐛 66 | 🌐 C++ | 📅 2026-08-14 - Cross-platform multi-format interactive-fiction player supporting Z-machine, Glulx, TADS, Hugo, and other IF virtual machine formats.
* [Infocom Z-code Interpreters](https://github.com/erkyrath/infocom-zcode-terps) ⭐ 366 | 🐛 0 | 🌐 Assembly | 📅 2023-11-23 - Historical collection of Infocom's original Z-machine interpreters for 1980s home computers, mostly as 6502/Z-80 assembly source.
* [Lectrote](https://github.com/erkyrath/lectrote) ⭐ 268 | 🐛 49 | 🌐 JavaScript | 📅 2025-10-04 - Electron-based interactive fiction interpreter, playing Z-code and Glulx games.
* [Inform 6](https://github.com/DavidKinder/Inform6) ⭐ 234 | 🐛 21 | 🌐 C | 📅 2026-04-27 - Compiler for the Inform 6 language, producing Z-machine (.z3/.z5/.z8) story files and, as the code generator behind Inform 7, Glulx (.ulx) game files.
* [encrusted](https://github.com/DeMille/encrusted) ⭐ 151 | 🐛 15 | 🌐 Rust | 📅 2022-06-20 - Z-machine interpreter written in Rust for classic Infocom-era text adventures like Zork, compiling to WebAssembly for browser play.
* [mojozork](https://github.com/icculus/mojozork) ⭐ 147 | 🐛 6 | 🌐 C | 📅 2026-07-25 - Simple Z-machine interpreter implemented in a single C file, with an experimental online-multiplayer mode for playing classic Infocom Z-code story files together.
* [Windows-Frotz](https://github.com/DavidKinder/Windows-Frotz) ⭐ 117 | 🐛 6 | 🌐 C | 📅 2026-04-01 - Windows front-end for the Frotz Z-machine interpreter core, playing Infocom and other Z-code game files on Windows.
* [ifvms.js](https://github.com/curiousdannii/ifvms.js) ⭐ 99 | 🐛 12 | 🌐 JavaScript | 📅 2025-07-12 - Suite of pure-JavaScript interactive-fiction virtual machine interpreters (Z-machine and Glulx) for browser-based play.
* [zork-1978-01](https://github.com/MITDDC/zork-1978-01) ⭐ 70 | 🐛 1 | 🌐 Roff | 📅 2022-08-10 - Source code for a January 1978 version of Zork, predating Infocom's founding; an early Z-machine-era snapshot of the game's development at MIT.
* [Zorkduino](https://github.com/rossumur/Zorkduino) ⭐ 59 | 🐛 4 | 🌐 C++ | 📅 2014-05-22 - Z-machine interpreter for Arduino, playing classic Infocom Z-code games on a TV.
* [Fabularium](https://github.com/tccowper/fabularium) ⭐ 50 | 🐛 10 | 🌐 C++ | 📅 2019-10-07 - Multi-format interactive-fiction player for Android, bundling Z-machine, Glulx, Hugo, TADS, and other IF virtual-machine interpreters into a single app; the mobile counterpart to Gargoyle.
* [Twisty](https://github.com/sussman/twisty) ⭐ 38 | 🐛 48 | 🌐 C | 📅 2017-07-09 - Text-adventure interpreter for Android, playing both Z-machine and Glulx game files.
* [Viola](https://github.com/DFillmore/viola) ⭐ 30 | 🐛 18 | 🌐 Python | 📅 2024-05-06 - Z-Machine interpreter written in Python.
* [Glk API reference implementations](https://github.com/erkyrath/cheapglk) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2025-06-05 - Reference implementations of Glk, the display API most Z-machine/Glulx interpreters use: [CheapGlk](https://github.com/erkyrath/cheapglk) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2025-06-05 (headless/minimal), [GlkTerm](https://github.com/erkyrath/glkterm) ⭐ 18 | 🐛 9 | 🌐 C | 📅 2021-07-08 (curses), [RemGlk](https://github.com/erkyrath/remglk) ⭐ 26 | 🐛 13 | 🌐 C | 📅 2025-06-12 (remote-procedure-call/JSON), and [XGlk](https://github.com/erkyrath/xglk) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2021-06-26 (X11, unmaintained since 2000).
* [Windows Glk](https://github.com/DavidKinder/Windows-Glk) ⭐ 14 | 🐛 3 | 🌐 C++ | 📅 2026-08-16 - Windows implementation of Andrew Plotkin's Glk display-API specification, used by many Z-code/Glulx interpreters.
* [Gnusto-Frotz-Tops20](https://github.com/athornton/gnusto-frotz-tops20) ⭐ 12 | 🐛 1 | 🌐 Perl | 📅 2020-02-07 - Port of the Frotz Z-machine interpreter to the TOPS-20 operating system, playing Infocom game files.
* [Fizmo](https://github.com/erkyrath/fizmo) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2022-12-01 - C Z-machine interpreter for POSIX systems, playing Infocom and other Z-machine game files (all versions except 6). See also [IosFizmo](https://github.com/erkyrath/iosfizmo) ⭐ 48 | 🐛 2 | 🌐 Objective-C | 📅 2022-12-02, an iOS port.
* [Inform Mapper](https://github.com/attilathedud/inform_mapper) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-19 - Interactive web graphing application for Z-machine story files (.z1-.z8), parsing a game's object tree to visualize rooms, objects, and their parent/sibling/containment relations. The actively maintained successor to the author's own [ZTree](https://github.com/attilathedud/ZTree) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2017-10-24.
* [zmach](https://github.com/kmill/zmach) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-13 - Z-machine interpreter that dynamically recompiles Z-code (version 5 story files) to JavaScript.
* [Discoggin](https://github.com/iftechfoundation/discoggin) ⭐ 6 | 🐛 13 | 🌐 Python | 📅 2025-07-05 - Discord bot that plays parser and choice-based interactive fiction directly in a Discord channel, supporting Z-code (.z1-.z8/.zblorb), Glulx (.ulx/.gblorb), Ink, and YarnSpinner game files, with persisted per-channel save sessions.
* [HugoJS](https://github.com/juhana/hugojs) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2022-04-26 - Online interpreter for Hugo, another parser-based interactive-fiction virtual-machine format, running compiled Hugo game files in the browser.
* [ztools](https://github.com/erkyrath/ztools) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-01-23 - Classic Infocom Z-machine toolkit (txd disassembler, infodump story-file dumper, and related utilities) for inspecting Z-code game files.
* [language-inform7](https://github.com/iftechfoundation/language-inform7) ⭐ 2 | 🐛 0 | 📅 2022-07-02 - Language grammar definition for Inform 7, the natural-language authoring system that compiles to Z-machine/Glulx story files.
* [Frotz](https://gitlab.com/DavidGriffith/frotz) - The original portable Frotz Z-machine interpreter core, written by Stefan Jokisch and extended by David Griffith since 1997; development moved from GitHub to GitLab, and it underlies many derivative interpreters (Windows-Frotz, Gnusto-Frotz-Tops20, etc.).
* [Infocom Historical Source Archive](https://github.com/historicalsource) - Leaked/preserved original ZIL (Zork Implementation Language) source code for most of Infocom's text-adventure catalog, each compiling to the original Z-machine (.z3/.z5) story-file format; includes several unreleased/unfinished titles.
  * Games: Zork I, Zork II, Zork III (plus the 1977 mainframe original, Solid-Gold editions, and 1982/1987/1988 Sampler minizork variants), Zork Zero, Enchanter, Sorcerer, Spellbreaker, Deadline, Suspect, Suspended, Starcross, Infidel, The Witness, Ballyhoo, Border Zone, Bureaucracy, Cutthroats, Hollywood Hijinx, The Hitchhiker's Guide to the Galaxy (plus Solid-Gold edition), Journey, Leather Goddesses of Phobos (plus Gold edition), Moonmist, Nord and Bert Couldn't Make Head or Tail of It, Planetfall (plus Gold edition), Plundered Hearts, Seastalker, Sherlock: The Riddle of the Crown Jewels, James Clavell's Shogun, Stationfall, Trinity, Wishbringer (plus Gold edition), A Mind Forever Voyaging, Beyond Zork, Arthur: The Quest for Excalibur, The Lurking Horror, the 1984 Infocom Sampler, and unreleased/unfinished titles (Checkpoint, The Restaurant at the End of the Universe, a German-language Zork translation, James Cameron's The Abyss).

### Magnetic Scrolls VM (Interactive Fiction)

*Custom virtual machine format used by Magnetic Scrolls' text adventures (The Pawn, Guild of Thieves, Wonderland, etc.), a UK studio whose parser games rivaled Infocom's in the 1980s.*

* [Magnetic](https://github.com/DavidKinder/Magnetic) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2026-02-12 - Interpreter for the Magnetic Scrolls text-adventure games (1985-1991) by the UK studio of the same name, playing the original .mag story files; written by Niclas Karlsson with additional code by David Kinder.

### AGT (Adventure Game Toolkit)

*Text-adventure authoring system popular on Compuserve in the late 1980s; AGT games compile to a custom game-data format read by the AGiliTy interpreter.*

* [Windows AGiliTy](https://github.com/DavidKinder/Windows-AGiliTy) ⭐ 8 | 🐛 2 | 🌐 C | 📅 2026-02-26 - Windows port of Robert Masenten's AGiliTy interpreter for AGT (Adventure Game Toolkit) games, playing the original AGT game-data files.

### Level 9 VM (Interactive Fiction)

*Custom virtual machine format used by Level 9's text adventures (Snowball, Jewels of Darkness, etc.), a UK studio known for cramming ambitious parser games onto 8-bit cassette systems.*

* [Level9-Public](https://github.com/MikeTheTechie/Level9-Public) ⭐ 81 | 🐛 2 | 🌐 Assembly | 📅 2026-01-30 - Preservation archive of roughly 500 recovered Level 9 floppy disks (of about 1000 originally produced), dumped mainly via Atari ST emulation between 2021-2024; source material for reconstructing original Level 9 game-data files.
* [Level9](https://github.com/DavidKinder/Level9) ⭐ 46 | 🐛 2 | 🌐 C | 📅 2026-07-28 - Interpreter for Level 9's text-adventure games, originally written by Glen Summers and extended by David Kinder, playing the original Level 9 game-data files.

### TADS VM (Interactive Fiction)

*Text Adventure Development System, Michael J. Roberts' object-oriented interactive-fiction authoring system and its own bytecode format; a longtime rival to Inform, also playable through Gargoyle.*

* [tads-sources](https://github.com/tajmone/tads-sources) ⭐ 17 | 🐛 0 | 🌐 HTML | 📅 2020-08-25 - Consolidated, easy-to-build source mirror of TADS 2, TADS 3, and HTML TADS, Michael J. Roberts' text-adventure authoring system and its own virtual-machine format.
* [TADS2-html5](https://github.com/my2iu/TADS2-html5) ⭐ 6 | 🐛 4 | 🌐 C | 📅 2019-11-17 - Port of the TADS 2 interpreter to HTML5/WebAssembly, playing original .gam TADS 2 story files in the browser.

### ADRIFT VM (Interactive Fiction)

*Adventure Development & Runner Interactive Fiction Toolkit, a point-and-click-authored text-adventure format with its own closed-source runner/VM.*

* [FrankenDrift](https://github.com/awlck/frankendrift) ⭐ 9 | 🐛 14 | 🌐 Visual Basic .NET | 📅 2026-07-31 - Cross-platform, open-source frontend for the closed-source ADRIFT Runner, playing original .taf ADRIFT game files outside Windows.
* [Starlane](https://github.com/awlck/starlane) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2026-08-15 - C++ reimplementation of the ADRIFT 5 interactive-fiction engine, loading and playing original .taf ADRIFT game files with Qt, console, and Glk frontends outside the closed-source Windows runner.

### Alan VM (Interactive Fiction)

*Text-adventure authoring language designed by Thomas Nilsson, compiling to its own bytecode format read by the Alan interpreter.*

* [Alan](https://github.com/alan-if/alan) ⭐ 19 | 🐛 9 | 🌐 Assembly | 📅 2026-08-18 - Official compiler and interpreter for the Alan interactive-fiction authoring language, playing the original Alan game-data format.

### Twine (Interactive Fiction)

*Hypertext/choice-based interactive fiction tool; Twine stories are HTML files embedding Twee-format passage data, run by a story-format-specific JavaScript runtime (Harlowe, SugarCube, Chapbook, etc.).*

* [twine-specs](https://github.com/iftechfoundation/twine-specs) ⭐ 101 | 🐛 5 | 📅 2024-07-04 - Format specifications for Twine, covering the Twee passage-map format, the HTML story-archive format, and the story-format JavaScript API.

### Yarn Spinner (Dialogue Middleware)

*Engine-agnostic dialogue scripting system used by many indie and commercial games; Yarn scripts compile to a bytecode/JSON format executed at runtime.*

* [Yarn Spinner](https://github.com/YarnSpinnerTool/YarnSpinner) ⭐ 2,827 | 🐛 3 | 🌐 C# | 📅 2026-08-11 - Core compiler and engine-agnostic runtime for Yarn Spinner, compiling `.yarn` dialogue scripts to a bytecode/JSON format consumed by game engines (Unity, Godot, etc.). See also [YSRun-Single](https://github.com/erkyrath/YSRun-Single) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-07-02, a single-turn GlkOte wrapper for running the compiled dialogue JSON from the command line.

### Rawthrills G7 Engine

* [G7Reader](https://github.com/Surasia/G7Reader) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2024-06-29 - Small utility to read Rawthrills G7 Engine archive files.

### OpenSpace

* [openspace-ps2-extractor](https://github.com/byvar/openspace-ps2-extractor) ⭐ 7 | 🐛 1 | 🌐 Java | 📅 2018-09-17 - Extractor for OpenSpace PS2 archive files.
* [BinarySerializer.OpenSpace](https://github.com/BinarySerializer/BinarySerializer.OpenSpace) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2026-02-26 - BinarySerializer extension library for serializing OpenSpace game formats.

### LithTech Engine

*Engine used in No One Lives Forever, F.E.A.R., Condemned, Blood 2, Shogo, and other Monolith games. See also [Monolith Productions](#monolith-productions) for game-specific tools.*

* [io\_scene\_jupex](https://github.com/Five-Damned-Dollarz/io_scene_jupex) ⭐ 21 | 🐛 5 | 🌐 Python | 📅 2024-11-15 - Blender addon for importing LithTech Jupiter EX world/map files (.world). Supports games built on the Jupiter EX engine (F.E.A.R., Condemned, No One Lives Forever 2).
* [io\_scene\_lithtech (haekb)](https://github.com/haekb/io_scene_lithtech) ⭐ 20 | 🐛 9 | 🌐 Python | 📅 2021-11-15 - Blender addon for importing LithTech model and animation files. Supports ABC (LithTech 1/2 era, used in Blood 2, NOLF, Shogo) and LTB formats.
  * See also [Five-Damned-Dollarz's fork](https://github.com/Five-Damned-Dollarz/io_scene_lithtech) ⭐ 10 | 🐛 6 | 🌐 Python | 📅 2025-10-23 with additional model support.
* [io\_scene\_modl](https://github.com/cmbasnett/io_scene_modl) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2018-06-20 - Blender addon for importing and exporting .modl model files from LithTech Jupiter Engine games.
* [godot-dat-reader](https://github.com/haekb/godot-dat-reader) ⭐ 10 | 🐛 1 | 🌐 GDScript | 📅 2021-10-03 - Godot 3.2 importer for LithTech DAT world/level files.
* [godot-abc-reader](https://github.com/haekb/godot-abc-reader) ⭐ 7 | 🐛 0 | 🌐 GDScript | 📅 2021-08-04 - Godot 3.2 importer for LithTech ABC model files used in Blood 2, No One Lives Forever, and Shogo.
* [godot-dtx-reader](https://github.com/haekb/godot-dtx-reader) ⭐ 6 | 🐛 0 | 🌐 GDScript | 📅 2020-11-22 - Godot 3.2 importer for LithTech DTX texture files used across LithTech 1/2/Jupiter engine games.
* [lpsdecoder](https://github.com/haekb/lpsdecoder) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2019-12-27 - Extracts and converts PS2 LithTech LPS archive format.

### Adventure Game Studio (AGS)

* [AGSUnpacker](https://github.com/adm244/AGSUnpacker) ⭐ 42 | 🐛 2 | 🌐 C# | 📅 2026-08-10 - Unpacker/packer for compiled Adventure Game Studio (AGS) 2.x–3.x game resources.
  * See also [Ghidra-ReAGS](https://github.com/adm244/Ghidra-ReAGS) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-06-08 for AGS script (scom3) decompilation via Ghidra.
  * Formats: executable (.exe), archives (.ags, .xxx), sprites (.spr), rooms (.crm), scripts (.scom3, .dta), translation files (.trs, .tra).
  * Features: asset extraction, sprite unpack/repack, room background preview/replace, translation file generation and compilation, string injection from translation files.
* [ags2\_decomp](https://github.com/adm244/ags2_decomp) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-08-16 - Matching decompilation of Adventure Game Studio 2.x runtime engine for reverse engineering and software preservation.

### BioWare Aurora Engine

*Used in Neverwinter Nights, Star Wars: Knights of the Old Republic, Jade Empire, and other BioWare titles.*

* [xoreos](https://github.com/xoreos/xoreos) ⭐ 1,166 | 🐛 37 | 🌐 C++ | 📅 2026-07-17 - Open-source reimplementation of BioWare's Aurora engine and its derivatives, targeting full portability of all Aurora-based games.
  * Games: Neverwinter Nights, Neverwinter Nights 2, Knights of the Old Republic, KotOR II: The Sith Lords, Jade Empire, Sonic Chronicles: The Dark Brotherhood, The Witcher, Dragon Age: Origins, Dragon Age II.
  * Status: resource management, many file format parsers, partial in-game graphics and area rendering (spectator mode) — gameplay not yet implemented.

### Clickteam Fusion

* [CTFAK2.0](https://github.com/CTFAK/CTFAK2.0) ⚠️ Archived - Decompiler and asset dumper for games built with Clickteam Fusion 2.5 (archived; superseded by CTFAK3). Reads MFA-like internal structures and outputs assets via a plugin system.

### Dark Engine

*Used in Thief: The Dark Project, Thief 2: The Metal Age, and System Shock 2 (Looking Glass Studios).*

* [openDarkEngine](https://github.com/volca02/openDarkEngine) ⭐ 169 | 🐛 9 | 🌐 C++ | 📅 2018-05-14 - Open-source multiplatform reimplementation of the Dark Engine, reading original Thief and System Shock 2 game data (level, mesh, and DAT resource formats).
* [AngelLoader](https://github.com/FenPhoenix/AngelLoader) ⚠️ Archived - Standalone fan mission loader/manager for the original Thief trilogy, System Shock 2, and The Dark Mod, installing and organizing Dark Engine FM archives (zip/7z) with readme/screenshot extraction and metadata handling.
* [de-specs](https://github.com/JarrodDoyle/de-specs) ⭐ 2 | 🐛 0 | 🌐 Max | 📅 2025-03-09 - [ImHex](https://imhex.werwolv.net/) pattern files for parsing Dark Engine file formats used in Thief and System Shock 2.
  * Formats: .MIS (mission), .GAM (game data), .COW (world geometry); further formats planned.
* [7-Zip Speed Optimizer](https://github.com/FenPhoenix/7-Zip-Speed-Optimizer) ⚠️ Archived - Repackages Thief/System Shock 2/Dark Mod fan mission .7z archives so FM loaders (AngelLoader, FMSel) can scan them up to 70x faster, while retaining 7z's compression advantage.
* [KCModelEditor](https://github.com/JarrodDoyle/KCModelEditor) ⭐ 1 | 🐛 8 | 🌐 C# | 📅 2026-07-19 - GUI tooling for browsing and editing Dark Engine model files, written in C# using the Godot engine.

### SCI Engine (Sierra)

*Sierra On-Line's Script Creation Interpreter, used in King's Quest, Space Quest, Police Quest, Leisure Suit Larry, Gabriel Knight, and many other Sierra titles.*

* [SCICompanion](https://github.com/icefallgames/SCICompanion) ⭐ 86 | 🐛 14 | 🌐 C++ | 📅 2021-04-28 - Full-featured IDE for creating and editing Sierra SCI engine games (SCI0 through SCI1.1). Supports editing scripts, rooms, sounds, views, fonts, pics, cursors, messages, and palettes. Official site: [scicompanion.com](https://scicompanion.com).
* [NAGI](https://github.com/sonneveld/nagi) ⭐ 42 | 🐛 4 | 🌐 C | 📅 2022-05-14 - Reimplementation of Sierra's AGI (Adventure Game Interpreter) engine, parsing and executing original AGI game resource files.
* [FOSS SCI Drivers](https://github.com/roybaer/foss_sci_drivers) ⭐ 24 | 🐛 1 | 🌐 Assembly | 📅 2021-08-13 - From-scratch open-source drivers for Sierra's SCI (Creative Interpreter) engine, covering archive, audio, and editor support.
* [SCI2AGI](https://github.com/jhhoward/SCI2AGI) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2024-11-24 - Converts Sierra SCI engine resources (PIC, VIEW, and others) to the earlier AGI engine's format.

### SCUMM

*LucasArts adventure game engine used in Monkey Island, Maniac Mansion, Day of the Tentacle, Fate of Atlantis, Sam & Max, and other classic titles.*

* [nutcracker](https://github.com/BLooperZ/nutcracker) ⭐ 63 | 🐛 9 | 🌐 Python | 📅 2026-05-15 - Tools for extracting and editing resources in SCUMM engine games (v5–v8 + HE variants).
  * Features: extract/rebuild game resource archives, extract/inject text strings, extract/replace background and object images (including EGA), decompile game scripts to Windex-like syntax.
  * Fonts: CHAR chunk fonts (v5–v7, HE) and NUT fonts (v7–v8) — extract as PNG, re-encode back.
  * SMUSH: extract video frames, compress SMUSH videos (compatible with scummvm-tools).
* [MMUCS](https://github.com/haywirephoenix/MMUCS) ⭐ 7 | 🐛 2 | 🌐 C# | 📅 2026-06-01 - Modular environment for analysis, extraction, and visualization of SCUMM engine assets and legacy media formats.

### UTAGE

*Unity-based Japanese visual-novel/ADV plugin.*

* [utagedec](https://github.com/Bioruebe/utagedec) ⭐ 4 | 🐛 0 | 🌐 Haxe | 📅 2019-01-29 - Decryptor for UTAGE visual novel engine encrypted assets (.utage), reversing the engine's modified XOR encryption scheme.

### Adobe Flash (SWF)

* [Ruffle](https://github.com/ruffle-rs/ruffle) ⭐ 18,435 | 🐛 5,623 | 🌐 Rust | 📅 2026-08-19 - Flash Player emulator written in Rust that parses and executes SWF files and ActionScript bytecode, used to preserve and play thousands of Flash-based web games.
* [Swivel](https://github.com/Herschel/Swivel) ⭐ 226 | 🐛 27 | 🌐 Haxe | 📅 2026-03-28 - Converts Adobe Flash SWF files to video, for archiving or sharing Flash-based games and animations.
* [rust-flash-lso](https://github.com/ruffle-rs/rust-flash-lso) ⭐ 20 | 🐛 8 | 🌐 Rust | 📅 2026-08-13 - Rust parser/encoder for Adobe Flash Local Shared Object (.sol) save files and the underlying AMF0/AMF3 serialization formats used by Flash games.

### Godot

* [gdsdecomp](https://github.com/GDRETools/gdsdecomp) ⭐ 4,075 | 🐛 37 | 🌐 C++ | 📅 2026-08-16 - Godot reverse engineering toolkit for game file format recovery, GDScript bytecode decompilation, and PCK archive extraction (Godot 2.x, 3.x, 4.x).

### HaxeFlixel

* [flxanimate](https://github.com/Dot-Stuff/flxanimate) ⭐ 74 | 🐛 5 | 🌐 Haxe | 📅 2026-01-04 - Plays back Adobe Animate texture atlas exports (used widely by Friday Night Funkin' and its mods) in HaxeFlixel.
* [BetterTextureAtlas](https://github.com/Dot-Stuff/BetterTextureAtlas) ⭐ 56 | 🐛 5 | 🌐 JavaScript | 📅 2026-07-30 - Adobe Animate extension that enhances Texture Atlas exports, extending the animation file format with extra data (blend modes, baked filters) for use by players like flxanimate.

## 🔧 Middleware & SDKs

*Game development middleware, libraries, and SDK-provided formats used across multiple titles and platforms.*

### Fast3d/F3dex (N64)

*SGI's microcode format for defining 3D graphics on the Nintendo 64. Used in [Super Mario 64](#super-mario-64), [Paper Mario 64](#paper-mario-64), [Banjo-Kazooie](#rare), and many other N64 titles.*

* [noclip.website (Banjo)](https://github.com/magcius/noclip.website/blob/main/src/BanjoKazooie/f3dex.ts) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - F3DEX implementation for Banjo-Kazooie viewer.
* [RT64](https://github.com/rt64/rt64) ⭐ 1,575 | 🐛 88 | 🌐 C++ | 📅 2026-08-06 - N64 graphics renderer implementing the RDP/F3D microcode family with enhancements (widescreen, higher resolutions, ray tracing) for emulators and native ports.
* [fast64](https://github.com/Fast-64/fast64) ⭐ 525 | 🐛 79 | 🌐 Python | 📅 2026-08-15 - Blender plugin for exporting F3D display lists for N64 decompilation projects (Super Mario 64, Ocarina of Time).
* [MeltyTool (F3dzex2)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/F3dzex2) ⭐ 200 | 🐛 60 | 🌐 C# | 📅 2026-08-19 - F3DZEX2 format support.
* [n64-fast3d-engine](https://github.com/Emill/n64-fast3d-engine) ⭐ 146 | 🐛 7 | 🌐 C++ | 📅 2022-03-09 - N64 Fast3D engine implementation.
* [F3DEX3](https://github.com/HackerN64/F3DEX3) ⭐ 143 | 🐛 1 | 🌐 C | 📅 2026-07-19 - Modern, heavily rewritten F3D-family microcode for N64 romhacks; rewrites vertex/lighting code from scratch for higher performance, adds new visual features (simultaneous vertex colors + normals, ambient occlusion), and improves accuracy over F3DEX2.
* [n64rawgfx](https://github.com/Octocontrabass/n64rawgfx) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2013-11-22 - Exports and imports uncompressed ("raw") N64 graphics (RGBA, CI, IA, I formats) to/from BMP files, e.g. for Super Mario 64 texture editing.
* [F3DEX2Decoder](https://github.com/Mr-Wiseguy/F3DEX2Decoder) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2022-02-20 - Decoder for F3DEX2 display lists.
* [F3D2F3DEX](https://github.com/Trenavix/F3D2F3DEX) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2018-12-15 - Converter between F3D variants.
* [pigment64](https://github.com/decompals/pigment64) ⭐ 4 | 🐛 3 | 🌐 Rust | 📅 2025-12-29 - Rust library for converting N64 image data (Intensity, IA, CI, RGBA formats) between native and PNG formats, used by N64 decompilation projects.
* [Hack64 Fast3D Commands](https://hack64.net/wiki/doku.php?id=super_mario_64:fast3d_display_list_commands) - Documentation for Fast3D display list commands.
* [CloudModding F3DZEX2](https://wiki.cloudmodding.com/oot/F3DZEX2) - Documentation for F3DZEX2 format.

### Havok

*Physics and animation middleware used in hundreds of games across all platforms.*

* [HavokLib](https://github.com/PredatorCZ/HavokLib) ⭐ 94 | 🐛 5 | 🌐 C++ | 📅 2026-03-06 - C++ library for reading, converting, and upgrading/downgrading Havok physics packfiles across versions (5.0.0-2017).
* [MapEditor](https://github.com/BF3RM/MapEditor) ⭐ 79 | 🐛 59 | 🌐 TypeScript | 📅 2026-08-19 - Realtime map editor mod for Venice Unleashed (Battlefield 3).
* [TagTools](https://github.com/blueskythlikesclouds/TagTools) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2020-11-15 - Tools for editing Havok 2015/2016 binary tag files. Includes TagTools converter and CollisionConverter for converting rigid bodies to static compound shapes with type and flag tags.
* [havok2fbx](https://github.com/Highflex/havok2fbx) ⭐ 33 | 🐛 2 | 🌐 C++ | 📅 2015-11-19 - Converts Havok files to Autodesk FBX.
* [HavokNoesis](https://github.com/PredatorCZ/HavokNoesis) ⭐ 14 | 🐛 1 | 🌐 C++ | 📅 2019-05-13 - Noesis plugin for Havok format.
* [SSE-Fallout-4-Animation-Converter](https://github.com/Backporter/SSE-Fallout-4-Animation-Converter) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2021-09-12 - Tool to convert animations to PS4 format for Skyrim Special Edition and Fallout 4.
* [FF16-Model-Importer](https://github.com/KillzXGaming/FF16-Model-Importer) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2024-12-04 - Tool to export and import Final Fantasy XVI .mdl file binaries as .gltf or .dae.
* [Havok IO (Blender)](https://github.com/NewSkyLine-dev/havokmax-blender) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2025-11-24 - Havok tool for Blender (replaces legacy HavokMax 3ds Max plugin). Blender add-on that imports `.hkx`, `.hkt`, `.hka`, `.igz`, and `.pak` files from Havok XML and binary archives.
  * Capabilities: builds armatures and keyframed actions from animation data, constructs static meshes from geometry blocks, and unwraps PAK/IGZ containers.
* [hkxlib](https://github.com/aerisarn/hkxlib) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2017-04-09 - JAXB parser for editing TAGXML formatted Havok files.
* [hkxEdit](https://github.com/aerisarn/hkxEdit) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2017-01-04 - Visual editor for Havok 2010.2 files based on hkxlib, written in Java.
* [HavokPreviewToolsBatch2018](https://github.com/asasasasasbc/HavokPreviewToolsBatch2018) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2024-10-01 - Batch conversion script for Havok Preview Tool 2018 that can automatically convert Havok HKX/HKT files' format.
* [Blender HKX](https://github.com/BadDogSkyrim/blender-hkx) ⭐ 2 | 🐛 0 | 📅 2023-02-25 - Blender addon for importing and exporting Havok HKX animation format.
* [hkxcmd](https://github.com/BadDogSkyrim/hkxcmd) ⭐ 1 | 🐛 0 | 📅 2017-08-29 - Command-line tool for parsing, converting, and modifying Havok HKX animation format files.
* [hkxcmd (aerisarn fork)](https://github.com/aerisarn/hkxcmd) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2012-02-26 - Tool for working with HKX (Havok animation format) used in Elder Scrolls and Fallout series.

### JSYSTEM (GameCube/Wii)

*Nintendo's in-house middleware used to develop GameCube and Wii era games. Used in [Pikmin](#pikmin), [Pikmin 2](#pikmin-2), [Luigi's Mansion](#luigis-mansion), [Super Mario Sunshine](#super-mario-other), [Super Mario Galaxy](#super-mario-other), [Wind Waker](#zelda), [Twilight Princess](#zelda), [Mario Kart: Double Dash](#mario-kart-double-dash), and many other first-party GameCube/Wii titles.*

* [noclip.website (JSYSTEM)](https://github.com/magcius/noclip.website/tree/main/src/Common/JSYSTEM) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser viewer for JSYSTEM formats.
* [aurora](https://github.com/encounter/aurora) ⭐ 457 | 🐛 10 | 🌐 C++ | 📅 2026-08-16 - Source-level GameCube & Wii GX graphics compatibility layer, used by decompilation and static-recompilation projects to run original GC/Wii rendering code on modern backends (Dawn/WebGPU).
* [MeltyTool (JSystem)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/JSystem) ⭐ 200 | 🐛 60 | 🌐 C# | 📅 2026-08-19 - JSystem format viewer/exporter.
* [RiiStudio](https://github.com/snailspeed3/RiiStudio) ⭐ 112 | 🐛 27 | 🌐 C++ | 📅 2025-08-04 - Modern editor for J3D models.
* [SuperBMD](https://github.com/Sage-of-Mirrors/SuperBMD) ⭐ 42 | 🐛 16 | 🌐 C# | 📅 2022-12-08 - BMD/BDL model converter for GameCube/Wii games.
* [WiiExplorer](https://github.com/SuperHackio/WiiExplorer) ⭐ 38 | 🐛 0 | 🌐 C# | 📅 2026-04-23 - Wii filesystem explorer.
* [J3D-Model-Viewer](https://github.com/LordNed/J3D-Model-Viewer) ⭐ 19 | 🐛 1 | 🌐 C# | 📅 2018-01-29 - Viewer for J3D models.
* [ARCTool](https://github.com/tpwrules/ARCTool) ⚠️ Archived - Python script to extract RARC, Yaz0, and U8 archives.
* [Hack.io](https://github.com/SuperHackio/Hack.io) ⭐ 16 | 🐛 1 | 🌐 C# | 📅 2026-07-21 - Libraries for J3D Era formats.
* [j3dview](https://github.com/blank63/j3dview) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2021-03-25 - J3DGraph viewer.
* [WArchive-Tools](https://github.com/LordNed/WArchive-Tools) ⭐ 13 | 🐛 1 | 🌐 C# | 📅 2020-03-31 - Tools for working with RARC archives.
* [JStudio (LordNed)](https://github.com/LordNed/JStudio) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2021-03-11 - Classes for Wind Waker J\* tools.
* [pyblo2-gui](https://github.com/RenolY2/pyblo2-gui) ⭐ 11 | 🐛 3 | 🌐 Python | 📅 2025-02-08 - GUI for working with BLO files.
* [J3DUltra](https://github.com/Sage-of-Mirrors/J3DUltra) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2025-12-10 - Advanced J3D model tool.
* [yaz0-decode-encode](https://github.com/RenolY2/yaz0-decode-encode) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2014-09-13 - Yaz0 compression tool.
* [BMDCubed](https://github.com/Sage-of-Mirrors/BMDCubed) ⭐ 9 | 🐛 3 | 🌐 C# | 📅 2017-05-08 - Converts skinned COLLADA (.dae) files to the Binary Model Data (BMD) format used by first-party Nintendo GameCube and Wii games.
* [j3d-animation-editor](https://github.com/tarsa129/j3d-animation-editor) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2023-04-23 - Editor for a variety of J3D animation files.
* [blojob](https://github.com/arookas/blojob) ⭐ 8 | 🐛 2 | 🌐 C# | 📅 2017-01-02 - J2DGraph BLO format tool.
* [gclib](https://github.com/LagoLunatic/gclib) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-08-11 - Python implementations of several GameCube file formats for ROM hacking.
* [Yaz0Decoder](https://github.com/Cuyler36/Yaz0Decoder) ⚠️ Archived - Yaz0 compression decoder.
* [RARClib.py](https://github.com/RenolY2/RARClib.py) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-11-14 - Python library for RARC format.
* [wsystool](https://github.com/XAYRGA/wsystool) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2025-01-11 - WAVESYSTEM modification toolkit for JSYSTEM games.
* [Jekyll](https://github.com/Sage-of-Mirrors/Jekyll) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2024-09-28 - J3D animation tool.
* [ibnktool](https://github.com/XAYRGA/ibnktool) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-07-01 - JAudio instrument bank tool.
* [pyjmap](https://github.com/SunakazeKun/pyjmap) ⚠️ Archived - JMap format library.
* [jpc\_conv](https://github.com/PikHacker/jpc_conv) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-08-10 - JParticle converter.
* [p2setoolkit](https://github.com/NerduMiner/p2setoolkit) ⭐ 4 | 🐛 0 | 🌐 D | 📅 2024-02-24 - Toolkit for disassembling/reassembling Pikmin 2 BMS sequenced music files.
* [rarc-rs](https://github.com/gcnhax/rarc-rs) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2018-05-17 - Rust library for RARC archives.
* [GCFontTool](https://github.com/Sage-of-Mirrors/GCFontTool) ⭐ 4 | 🐛 4 | 🌐 C# | 📅 2022-12-08 - GameCube font tool.
* [RarcPack](https://github.com/Sage-of-Mirrors/RarcPack) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2015-10-30 - RARC archive packer.
* [atirut.bdl](https://github.com/atirutw/atirut.bdl) ⭐ 4 | 🐛 0 | 🌐 GDScript | 📅 2023-04-29 - JSYSTEM BMD/BDL model importer for Godot Engine.
* [Rain336/JSystem](https://github.com/Rain336/JSystem) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2023-04-03 - Rust libraries for parsing Nintendo Wii/GameCube file formats.
  * Formats: BCSV, RARC, U8.
* [jampacked](https://github.com/XAYRGA/jampacked) ⭐ 3 | 🐛 1 | 🌐 C# | 📅 2021-09-05 - BAA unpacker for JSYSTEM games.
* [chutools](https://github.com/TwilitRealm/chutools) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2026-08-07 - Collection of tools for JAudio audio assets in Nintendo games, an updated version of XAYRGA's JAMTools.
  * Formats: JASE, JBST, IBNK (v1/v2), BMS (disassembler).
* [pyjkernel](https://github.com/SunakazeKun/pyjkernel) ⚠️ Archived - Python library for JKernel formats.
* [pikmin2-stb](https://github.com/RenolY2/pikmin2-stb) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-02-05 - JStudio format tool.
* [BTITool](https://github.com/Sage-of-Mirrors/BTITool) ⭐ 1 | 🐛 2 | 🌐 C# | 📅 2021-11-16 - BTI texture tool.
* [blemd](https://github.com/Sage-of-Mirrors/blemd) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-02-19 - Blender addon for J3D models.
* [libbti](https://github.com/Sage-of-Mirrors/libbti) ⭐ 0 | 🐛 1 | 🌐 C | 📅 2022-04-03 - BTI texture library.
* [Amnoid GC Resources](http://amnoid.de/gc/) - Documentation and resources for GameCube file formats.
* [Luma's Workshop (BMD)](https://lumasworkshop.com/wiki/BMD/BDL_\(File_Format\)) - BMD/BDL format documentation.
* [Wiki.CloudModding (JSYSTEM)](https://wiki.cloudmodding.com/zgcn/JSYSTEM) - JSYSTEM format documentation.
* [Tockdom BMD/BDL](https://wiki.tockdom.com/wiki/BMD_and_BDL_\(File_Format\)) - BMD/BDL format documentation.

### SEAD (Nintendo EAD/EPD Engine)

*Decompilation of Nintendo EAD/EPD's internal engine and standard library, used across many first-party Wii U and Switch titles including New Super Mario Bros. U.*

* [sead](https://github.com/aboood40091/sead) ⭐ 54 | 🐛 0 | 🌐 C++ | 📅 2026-07-25 - Decompilation of the sead engine/library developed by Nintendo EAD (now EPD), present in New Super Mario Bros. U and other titles. Includes the `agl` graphics library and an `nw_ptcl` wrapper for NintendoWareForCafe's Eft particle library.

### Mii (RFL/FFL Face Library)

*Nintendo's Mii avatar creation/rendering libraries, used across the Wii, Wii U, 3DS, and Switch.*

* [FFL-Testing](https://github.com/ariankordi/FFL-Testing) ⭐ 42 | 🐛 1 | 🌐 C++ | 📅 2026-05-08 - Mii rendering sample and renderer server built on the FFL decompilation. Fork of [aboood40091/FFL-Testing](https://github.com/aboood40091/FFL-Testing) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2026-03-12 with added rendering server functionality.
* [ffl](https://github.com/aboood40091/ffl) ⭐ 27 | 🐛 1 | 🌐 C++ | 📅 2026-03-12 - Decompilation of FFL (Face Library), the successor to RFL used for Mii avatars on Wii U, 3DS, and Switch.
* [RFL](https://github.com/koopthekoopa/RFL) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2026-05-30 - Decompilation of the Revolution Face Library (RFL), Nintendo's Mii avatar library for the Wii.

### Katana Engine (Koei Tecmo)

*Koei Tecmo's in-house engine and asset formats (G1M models, G1T texture archives, G1A/G2A skeletal animations), used across Team Ninja, Omega Force, and Gust titles as well as several external collaborations.*

* [Project-G1M](https://github.com/Joschuka/Project-G1M) ⭐ 92 | 🐛 14 | 🌐 C++ | 📅 2026-02-09 - Native C++ Noesis plugin for G1M model, G1T texture, and G1A/G2A skeletal animation files. Used across Nioh, Dead or Alive 5/6, the Warriors series (Dynasty/Samurai Warriors, Hyrule Warriors, Fire Emblem Warriors), Atelier, Toukiden, Fire Emblem: Three Houses, and Persona 5 Scramble. Supersedes the same author's Python-based [fmt\_g1m](https://github.com/Joschuka/fmt_g1m) ⚠️ Archived.

### M3G (Mobile 3D Graphics API)

*Java Mobile 3D Graphics API (JSR-184) used by many J2ME mobile games in the 2000s.*

* [m3gcore](https://github.com/toaarnio/m3gcore) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2012-08-07 - Core engine implementation (in C) of the M3G (JSR-184) API, originally developed at Nokia Research Center and later released as open source through the Symbian Foundation.

### NETLizard (J2ME Game Engine)

* [netlizard](https://github.com/glKarin/netlizard) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2023-04-26 - Parser utility and Qt4 GUI tool for NETLizard 3D J2ME game resource files (models, textures, fonts, text, sprites), reversed from decompiled Java source.
* [NETLizard\_idTech4](https://github.com/glKarin/NETLizard_idTech4) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2025-12-15 - Converter from NETLizard 3D J2ME game resource files to idTech4 format.

### MikuMikuDance

*Freeware animation program and its associated model and motion formats (.pmx, .pmd, .vmd).*

* [MMD Tools](https://github.com/MMD-Blender/blender_mmd_tools) ⭐ 3,210 | 🐛 13 | 🌐 Python | 📅 2026-08-13 - Blender add-on for importing/exporting MikuMikuDance assets. Supports physics, bone constraints, and motion/pose data.
* [MMD Tools Append](https://github.com/MMD-Blender/blender_mmd_tools_append) ⭐ 641 | 🐛 18 | 🌐 Python | 📅 2026-08-17 - Companion extension for MMD Tools that provides material/scene controls, lighting presets, and Rigify helpers.
* [MikuMikuLibrary](https://github.com/blueskythlikesclouds/MikuMikuLibrary) ⭐ 242 | 🐛 11 | 🌐 C# | 📅 2026-04-22 - Library for working with MikuMikuDance formats.

### RenderWare

*Cross-platform 3D engine and middleware developed by Criterion Games. Powering the Grand Theft Auto trilogy (III, Vice City, San San Andreas), Burnout series, and many other titles.*

* [librw](https://github.com/aap/librw) ⭐ 804 | 🐛 50 | 🌐 C++ | 📅 2026-08-09 - Re-implementation of the RenderWare Graphics engine.
* [DragonFF](https://github.com/Parik27/DragonFF) ⭐ 515 | 🐛 76 | 🌐 Python | 📅 2026-08-16 - Blender add-on for RenderWare `.dff` models, `.txd` textures, `.col` collisions, and `.ipl` map data.
* [Blender-3D-RW-Anm-plugin](https://github.com/Psycrow101/Blender-3D-RW-Anm-plugin) ⭐ 45 | 🐛 7 | 🌐 Python | 📅 2025-10-18 - Import and export RenderWare animations (.anm) into Blender 3D.
* [rwio](https://github.com/aap/rwio) ⭐ 42 | 🐛 10 | 🌐 C++ | 📅 2024-10-30 - RenderWare import/export plugin for 3ds Max.
* [rwd3d9](https://github.com/aap/rwd3d9) ⭐ 27 | 🐛 0 | 🌐 C++ | 📅 2017-01-07 - D3D9 extension of RenderWare for GTA III and Vice City.
* [g3DTZ](https://github.com/guard3/g3DTZ) ⭐ 27 | 🐛 3 | 🌐 C++ | 📅 2024-11-10 - GAME.DTZ archive extraction utility for GTA: Liberty City Stories and Vice City Stories, supporting both the PSP and PS2 versions.
* [RenderWareFile](https://github.com/igorseabra4/RenderWareFile) ⭐ 15 | 🐛 3 | 🌐 C# | 📅 2023-10-18 - Library for working with RenderWare binary files.
* [GTARW-BlenderMapExport](https://github.com/ajanhallinta/GTARW-BlenderMapExport) ⭐ 9 | 🐛 0 | 📅 2021-01-04 - Blender IPL/IDE map exporter for GTA San Andreas and Vice City, companion to the DragonFF add-on.
* [RenderWareNET](https://github.com/Venomalia/RenderWareNET) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2026-02-19 - Library to work with RenderWare 3 formats.
* [rwfury](https://github.com/Hancapo/rwfury) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-02 - Python library for reading and writing RenderWare formats.
  * Games: GTA III, Vice City, San Andreas
  * Formats: DFF (3D models), TXD (textures), IMG (archives), COL (collision), IFP (animation)
* [RWIDE2YTYP](https://github.com/Hancapo/RWIDE2YTYP) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2021-07-22 - RenderWare .IDE to Five .YTYP and NY .IDE converter.

### CRI

*CRI Middleware formats (CPK archives, ADX audio, etc.) used in many Japanese games across multiple platforms.*

* [CriPakTools](https://github.com/esperknight/CriPakTools) ⭐ 252 | 🐛 10 | 🌐 C# | 📅 2018-05-20 - Tools for extracting and repacking CRI CPK archives used in many Japanese games.
* [SonicAudioTools](https://github.com/blueskythlikesclouds/SonicAudioTools) ⭐ 166 | 🐛 2 | 🌐 C# | 📅 2024-01-16 - Toolset for modifying CRIWARE file formats.
  * Features: ACB Editor, ACB Finder (link AWB to ACB), ACB Injector, CPK Unpacker.
  * Formats: .acb, .awb, .cpk, .adx, .adx2, .csb.
* [CriPakTools (GUI)](https://github.com/wmltogether/CriPakTools) ⭐ 139 | 🐛 0 | 🌐 C# | 📅 2019-09-20 - GUI version of CriPakTools with additional features including Shift-JIS support, 2GB+ CPK support for PS3, batch mode, compression support, and improved CPK header handling.
* [HCADecoder](https://github.com/Nyagamon/HCADecoder) ⭐ 139 | 🐛 4 | 🌐 C++ | 📅 2018-01-23 - Original decoder for CRI's HCA (ADX2) audio format, the canonical reference implementation other HCA tools are based on.
* [CriCodecs](https://github.com/Youjose/CriCodecs) ⭐ 101 | 🐛 0 | 🌐 C++ | 📅 2026-07-31 - Python frontend for CRI codec tools.
* [UsmToolkit](https://github.com/Rikux3/UsmToolkit) ⚠️ Archived - Converts CRI USM video files into user-friendly formats, using ffmpeg and vgmstream. See also [UsmToolkitHandler](https://github.com/KojoBailey/UsmToolkitHandler) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2025-11-04, a companion tool that speeds up the conversion process.
* [CriFsV2Lib](https://github.com/Sewer56/CriFsV2Lib) ⭐ 43 | 🐛 5 | 🌐 C# | 📅 2024-02-03 - Library for working with CRI FileSystem V2 archives.
* [hca](https://github.com/Ishotihadus/hca) ⭐ 22 | 🐛 1 | 🌐 C | 📅 2023-04-24 - Efficient, high-quality decoder for CRI's HCA (ADX2) audio format used by many CRIWARE-based games.
* [AfsLib](https://github.com/Sewer56/AfsLib) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2025-12-07 - Simple, relatively fast library for reading and writing CRIWare AFS archives.
* [AfsBatch](https://github.com/tge-was-taken/AfsBatch) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2019-11-12 - Batch AFS packer. Packs each subdirectory in a given directory into an AFS file of the same name.
* [GoldWave\_HcaFile](https://github.com/esterTion/GoldWave_HcaFile) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2024-09-06 - HCA/ACB playback and export plugin for the GoldWave audio editor.
* [Universal-CPK-Mod-Installer](https://github.com/PTKay/Universal-CPK-Mod-Installer) ⭐ 2 | 🐛 0 | 🌐 Batchfile | 📅 2020-07-18 - Universal installer for CPK mod files.

### PSB (Persistent Serialized Binary)

*Serialized data/archive format used by many Japanese visual novel and mobile game engines (M2/Emote, CatSystem2, and others).*

* [psbfile](https://github.com/number201724/psbfile) ⭐ 72 | 🐛 0 | 🌐 C | 📅 2022-07-02 - Decompiler and rebuilder for the galgame PSB file format.

### XNA

*Microsoft XNA Framework model format used in various Xbox 360 and PC games.*

* [FNA](https://github.com/FNA-XNA/FNA) ⭐ 3,032 | 🐛 60 | 🌐 C# | 📅 2026-08-18 - Accuracy-focused reimplementation of the XNA4 framework for modern platforms, reading original .xnb content files; widely used to port XNA-based games (Terraria, Bastion, Fez, and others).
* [blender\_xna](https://github.com/REDxEYE/blender_xna) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2023-05-30 - Blender import plugin for XNA model formats.

### Sappy (GBA Audio)

*SDK-provided formats for the Game Boy Advance sound engine. Used in [Pokémon Gen III](#gen-iii) and many other GBA titles.*

* [agbplay](https://github.com/ipatix/agbplay) ⭐ 154 | 🐛 5 | 🌐 C++ | 📅 2026-06-30 - Music player and music ripper for GBA.
* [gba-mus-ripper](https://github.com/berg8793/gba-mus-ripper) ⭐ 35 | 🐛 2 | 🌐 C++ | 📅 2020-09-12 - GBA music ripper.
* [saptapper](https://github.com/loveemu/saptapper) ⭐ 32 | 🐛 2 | 🌐 C++ | 📅 2026-05-18 - Automated GSF ripper for Game Boy Advance games using the Sappy driver. Extracts music from GBA ROMs automatically.
* [engine-software-gba-tools](https://github.com/lunasorcery/engine-software-gba-tools) ⚠️ Archived - Tools for interacting with music data in GBA games that use the Engine Software (developer) replayer.
* [Sappy (Touched)](https://github.com/Touched/Sappy) ⭐ 20 | 🐛 0 | 🌐 Visual Basic | 📅 2015-05-14 - Fork with additional features.
* [shinen-gax-python](https://github.com/beanieaxolotl/shinen-gax-python) ⭐ 9 | 🐛 7 | 🌐 Python | 📅 2026-01-09 - Python tools for Shin'en Multimedia's GAX Sound Engine used in Game Boy Advance games. Includes conversion, unpacking, waveform dumping, and song rendering tools. Also supports NAX Sound Engine format.
* [gsfopt](https://github.com/loveemu/gsfopt) ⭐ 9 | 🐛 3 | 🌐 C++ | 📅 2021-06-01 - GSF (GBA Sound Format) optimizer tool. Optimizes GSF sets by removing unused code/data, converts minigsfs/gsflibs to single GSF files, and includes timing functionality for auto-tagging.
* [deadbeef\_GSFdecoder](https://github.com/joshbarrass/deadbeef_GSFdecoder) ⭐ 4 | 🐛 7 | 🌐 C | 📅 2024-02-14 - GSF decoder plugin for DeaDBeeF media player. Enables playback of GSF (GBA Sound Format) files in DeaDBeeF, based on viogsf/VBA-M.
* [sappy](https://github.com/maddievision/sappy) ⭐ 3 | 🐛 0 | 🌐 Visual Basic 6.0 | 📅 2025-09-06 - GBA sound tool.
* [SapPy](https://github.com/mayhaps-perchance/SapPy) ⚠️ Archived - Python-based GBA sound tool.

### RAD Game Tools

*Middleware provider (Bink video, Granny 3D, Miles Sound System) used in hundreds of games across all platforms.*

* [Granny Converter Library](https://github.com/Anohros/GrannyConverterLibrary) ⭐ 33 | 🐛 3 | 🌐 C++ | 📅 2026-07-26 - C++ library for converting Granny2 (.gr2) models and animations to FBX format.
* [opengr2](https://github.com/arves100/opengr2) ⭐ 16 | 🐛 3 | 🌐 C | 📅 2022-05-31 - Open source Granny2 (.gr2) input/output library and tools, with accompanying file format documentation.
* [libbink](https://github.com/jmarshall23/libbink) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2026-08-01 - GPL-licensed RAD Bink 1 video encoder/decoder reimplementation.
* [Knit](https://github.com/neptuwunium/Knit) ⚠️ Archived - Fully managed C# reader for Granny 2 files used in many games.
* [opengr2-rs](https://github.com/NoFr1ends/opengr2-rs) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2023-09-03 - Open source Rust parser for Granny2 (.gr2) files.
* [GR2Toolkit](https://github.com/REDxEYE/GR2Toolkit) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-11-11 - Toolkit for working with Granny 3D (GR2) model format files.
* [opengr2-bevy](https://github.com/NoFr1ends/opengr2-bevy) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2024-06-28 - Bevy engine file loader for Granny2 (.gr2) files, built on opengr2-rs.

### Nintendo SDKs & Hardware

*Formats and tools generic to Nintendo consoles or SDKs.*

#### Switch

* [Goldleaf](https://github.com/XorTroll/Goldleaf) ⭐ 3,020 | 🐛 91 | 🌐 C | 📅 2026-05-16 - Multi-purpose homebrew tool for the Nintendo Switch, browsing/installing NSP and NCA titles and inspecting the filesystem.
* [nsz](https://github.com/nicoboss/nsz) ⭐ 2,343 | 🐛 36 | 🌐 Python | 📅 2026-08-13 - Homebrew-compatible NSP/XCI compressor and decompressor for Nintendo Switch game dumps.
* [nxdumptool](https://github.com/DarkMatterCore/nxdumptool) ⭐ 1,279 | 🐛 19 | 🌐 C | 📅 2026-08-04 - Generates XCI, NSP, HFS0, ExeFS, and RomFS dumps from Nintendo Switch gamecards and installed titles.
* [nut](https://github.com/blawar/nut) ⭐ 1,266 | 🐛 76 | 🌐 Python | 📅 2026-01-19 - Multi-purpose utility to organize, manage, and install Nintendo Switch NSP, NSZ, XCI and XCZ files, with USB/network install serving for Tinfoil.
* [hactool](https://github.com/SciresM/hactool) ⭐ 1,177 | 🐛 29 | 🌐 C | 📅 2023-12-04 - Tool to view information about, decrypt, and extract Nintendo Switch file formats including NCA, XCI, PFS0, HFS0, RomFS, ExeFS, save data, and more.
* [NX-Shell](https://github.com/joel16/NX-Shell) ⭐ 1,080 | 🐛 18 | 🌐 C | 📅 2022-12-10 - Multi-purpose file manager homebrew for the Nintendo Switch, browsing and previewing images, audio, and archives on the filesystem.
* [nstool](https://github.com/jakcron/nstool) ⭐ 542 | 🐛 14 | 🌐 C++ | 📅 2024-10-14 - General purpose tool to read and extract Nintendo Switch file formats (NSO, NRO, NCA, etc.).
* [SimpleModManager](https://github.com/nadrino/SimpleModManager) ⭐ 460 | 🐛 21 | 🌐 C++ | 📅 2026-02-23 - Homebrew mod manager for the Nintendo Switch (Atmosphere CFW), organizing LayeredFS mod overlay folders per game title ID.
* [XCI-Explorer](https://github.com/StudentBlake/XCI-Explorer) ⭐ 451 | 🐛 21 | 🌐 C# | 📅 2024-03-08 - Tool for viewing contents of Nintendo Switch XCI and NSP files. Features include viewing metadata, exploring partitions, checking NCA hashes, extracting NCA, and modifying certificates.
* [NxFileViewer](https://github.com/Myster-Tee/NxFileViewer) ⭐ 341 | 🐛 12 | 🌐 C# | 📅 2025-10-08 - GUI viewer for the contents of Nintendo Switch container files.
* [TegraRcmSmash](https://github.com/rajkosto/TegraRcmSmash) ⭐ 163 | 🐛 4 | 🌐 C++ | 📅 2018-06-21 - C++ reimplementation of fusee-launcher for Nintendo Switch RCM payloads.
* [exefs\_patches](https://github.com/misson20000/exefs_patches) ⭐ 129 | 🐛 6 | 📅 2025-08-03 - ExeFS patching tool for Nintendo Switch.
* [goldbricks](https://github.com/blawar/goldbricks) ⭐ 115 | 🐛 2 | 🌐 C | 📅 2019-11-09 - Homebrew Nintendo Switch client for installing NSP packages via USB, GDrive or a nut server.
* [HACGUI](https://github.com/shadowninja108/HACGUI) ⭐ 72 | 🐛 2 | 🌐 C# | 📅 2020-04-06 - A comprehensive interface for extracting Nintendo Switch contents, deriving keys, and mounting filesystems (NAND, RomFS, Save).
* [hac2l](https://github.com/Atmosphere-NX/hac2l) ⭐ 56 | 🐛 3 | 🌐 C++ | 📅 2024-10-31 - Modern rewrite of hactool for viewing, decrypting, and extracting Nintendo Switch file formats, especially NCA (Nintendo Content Archive).
* [switch-libpulsar](https://github.com/p-sam/switch-libpulsar) ⭐ 12 | 🐛 0 | 🌐 C | 📅 2021-08-01 - Switch homebrew library to load, parse, and play sounds from BFSAR (binary sound archive) files and related audio file formats.
* [nxtik](https://github.com/jam1garner/nxtik) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2024-08-09 - Library and tool for parsing Nintendo Switch .tik (ticket) files.
* [switch-reversing](https://github.com/SciresM/switch-reversing) ⭐ 10 | 🐛 0 | 📅 2024-10-08 - Reverse engineering resources for Nintendo Switch.
* [LegacySwitchLibraries](https://github.com/KillzXGaming/LegacySwitchLibraries) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2026-05-21 - Switch file format libraries for Switch Toolbox and other programs.
* [nxo-parser](https://github.com/jam1garner/nxo-parser) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2020-12-30 - Rust parsers for Nintendo Switch executable formats (NSO/NRO).

#### iQue Player

* [iQueTool](https://github.com/emoose/iQueTool) ⭐ 17 | 🐛 1 | 🌐 C# | 📅 2018-12-03 - File manipulator for iQue Player (神游机) file formats.
* [iQuePlayer-SecureKernel](https://github.com/decompals/iQuePlayer-SecureKernel) ⭐ 5 | 🐛 2 | 🌐 C | 📅 2025-04-27 - Reverse engineering of the iQue Player Secure Kernel (SK).
* [iQuePlayer-BootROM](https://github.com/decompals/iQuePlayer-BootROM) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2024-04-01 - Matching decompilation of the iQue Player (Chinese N64 variant) Boot ROM.
* [iQuePlayer-SystemApp](https://github.com/decompals/iQuePlayer-SystemApp) ⭐ 3 | 🐛 1 | 🌐 C++ | 📅 2026-01-12 - Reverse engineering of the iQue Player System App (SA).

#### Wii U

* [noclip.website (Wii U Transfer Tool)](https://github.com/magcius/noclip.website/tree/main/src/rres) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser viewer for the Wii U Transfer Tool's scenes, reading the app's NW4R/BRRES assets.
* [wfs-tools](https://github.com/koolkdev/wfs-tools) ⭐ 92 | 🐛 12 | 🌐 C++ | 📅 2026-03-01 - Command-line tools for the Wii U WFS filesystem, built on wfslib. See also [wfs-tools-web](https://github.com/koolkdev/wfs-tools-web) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-16, a web-based version powered by WebAssembly.
* [wudump](https://github.com/FIX94/wudump) ⭐ 78 | 🐛 14 | 🌐 C | 📅 2022-02-15 - Dumps raw images from a Wii U game disc. See also [disc2app](https://github.com/koolkdev/disc2app) ⭐ 58 | 🐛 1 | 🌐 C | 📅 2020-12-05, a fork that extracts decrypted .app/.h3/.tmd/.cert/.tik content instead of a raw dump.
* [WiiUTools](https://github.com/NWPlayer123/WiiUTools) ⭐ 70 | 🐛 3 | 🌐 Python | 📅 2016-07-01 - Collection of Python utilities for working with Wii U file formats including IPK packages, RPX executables, SARC archives, and texture editing (TexHaxU/TexHaxU2).
* [Cafe-Shader-Studio](https://github.com/KillzXGaming/Cafe-Shader-Studio) ⭐ 63 | 🐛 14 | 🌐 C# | 📅 2023-04-12 - Shader editor and viewer for Wii U games.
* [wiiu-things](https://github.com/ihaveamac/wiiu-things) ⭐ 61 | 🐛 3 | 🌐 Python | 📅 2024-05-27 - Scripts and notes documenting the Wii U FST (filesystem table) format layout.
* [wfslib](https://github.com/koolkdev/wfslib) ⭐ 55 | 🐛 7 | 🌐 C++ | 📅 2026-08-01 - WFS (WiiU File System) library and tools.
* [fuse-wiiu](https://github.com/Maschell/fuse-wiiu) ⭐ 49 | 🐛 1 | 🌐 Java | 📅 2022-02-01 - FUSE filesystem for extracting data from Wii U titles in various formats.
* [nusserver](https://github.com/ihaveamac/nusserver) ⭐ 41 | 🐛 0 | 🌐 Python | 📅 2018-01-16 - Custom Nintendo Update Server (NUS) implementation, companion to nuspacker/nustool.
* [nuspacker](https://github.com/ihaveamac/nuspacker) ⭐ 40 | 🐛 4 | 🌐 Java | 📅 2017-11-13 - Packs files into an installable Wii U content format (NUS package).
* [WiiUZip](https://github.com/jam1garner/WiiUZip) ⭐ 19 | 🐛 2 | 🌐 C# | 📅 2017-08-01 - Archive manager for Wii U filetypes.
* [wiiuqt](https://github.com/koolkdev/wiiuqt) ⭐ 16 | 🐛 1 | 🌐 C++ | 📅 2017-03-24 - Qt-based Wii U NAND tools, built alongside koolkdev's wfs-tools.
* [GTX-Extractor](https://github.com/Gota7/GTX-Extractor) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2017-07-22 - Wii U GX2 texture extraction tool. Converts GTX texture files to DDS format for use in modding and asset extraction.

#### 3DS

* [Checkpoint](https://github.com/BernardoGiordano/Checkpoint) ⭐ 3,051 | 🐛 33 | 🌐 C++ | 📅 2026-08-13 - Fast and simple homebrew save management framework for 3DS and Switch.
* [GodMode9](https://github.com/d0k3/GodMode9) ⭐ 2,603 | 🐛 29 | 🌐 C | 📅 2026-08-01 - Full access file browser and manager for Nintendo 3DS handling game file formats and system files.
* [Anemone3DS](https://github.com/astronautlevel2/Anemone3DS) ⭐ 1,138 | 🐛 33 | 🌐 C | 📅 2026-08-18 - Theme and splashscreen manager for the Nintendo 3DS, handling BCSTM audio and theme/splash archive formats.
* [custom-install](https://github.com/ihaveamac/custom-install) ⭐ 908 | 🐛 34 | 🌐 Python | 📅 2026-06-05 - Installs a CIA title directly to an SD card for the Nintendo 3DS without needing to run an installer on-console.
* [3dsconv](https://github.com/ihaveamac/3dsconv) ⭐ 633 | 🐛 8 | 🌐 Python | 📅 2024-08-13 - Python script converting Nintendo 3DS CCI (.cci/.3ds) cart images to the CIA format, with support for decrypted, NCCH-encrypted, and zerokey-encrypted images.
* [Project\_CTR](https://github.com/3DSGuy/Project_CTR) ⭐ 569 | 🐛 21 | 🌐 C | 📅 2026-06-14 - A collection of custom Nintendo 3DS tools.
  * [ctrtool](https://github.com/3DSGuy/Project_CTR/tree/master/ctrtool) ⭐ 569 | 🐛 21 | 🌐 C | 📅 2026-06-14 - Read/extract 3DS file formats (CXI, CFA, CCI, CIA).
  * [makerom](https://github.com/3DSGuy/Project_CTR/tree/master/makerom) ⭐ 569 | 🐛 21 | 🌐 C | 📅 2026-06-14 - Create 3DS file formats.
* [3DS-rom-tools](https://github.com/ihaveamac/3DS-rom-tools) ⭐ 436 | 🐛 2 | 🌐 Python | 📅 2023-03-17 - Tools and guides for working with Nintendo 3DS game/application formats (.3ds, .cci, .app, .cxi, .cfa, .cia).
* [3dstool](https://github.com/dnasdw/3dstool) ⭐ 411 | 🐛 2 | 🌐 C | 📅 2026-01-24 - All-in-one tool for extracting and creating 3DS file formats.
  * Formats: CIA, CCI, NCCH, NCSD.
* [Ohana3DS-Rebirth](https://github.com/gdkchan/Ohana3DS-Rebirth) ⭐ 209 | 🐛 47 | 🌐 C# | 📅 2022-09-17 - Tool to view, extract, and replace models, textures, and animations from decrypted 3DS ROMs (BCH, CGFX).
* [faketik](https://github.com/ihaveamac/faketik) ⭐ 111 | 🐛 0 | 🌐 Makefile | 📅 2025-10-03 - Generates and installs fake Nintendo 3DS ticket (.tik) files to make missing titles re-appear.
* [NDecrypt](https://github.com/SabreTools/NDecrypt) ⭐ 85 | 🐛 2 | 🌐 C# | 📅 2026-07-10 - Encryption/decryption utility for Nintendo cartridge images, supporting Nintendo DS, DSi, 3DS, and New 3DS cartridge formats.
* [save3ds](https://github.com/wwylele/save3ds) ⭐ 78 | 🐛 5 | 🌐 Rust | 📅 2026-08-01 - Extract/import/FUSE tool for the Nintendo 3DS common save format (DISA/DIFF), covering save data, extdata, and the title database. Upstream of ihaveamac's save3ds fork.
* [braindump](https://github.com/neobrain/braindump) ⚠️ Archived - Early homebrew tool for dumping 3DS game cartridges and eShop titles. Archived, but has no already-listed direct successor for this specific niche.
* [3ds-save-tool](https://github.com/wwylele/3ds-save-tool) ⭐ 58 | 🐛 2 | 🌐 Python | 📅 2025-01-05 - Tools for parsing and extracting files from Nintendo 3DS save (DISA) and extdata (DIFF) containers.
* [ctrcdnfetch](https://github.com/luigoalma/ctrcdnfetch) ⭐ 53 | 🐛 3 | 🌐 C++ | 📅 2022-03-06 - Downloads title content from the Nintendo CDN for the 3DS without requiring a console, working around post-11.8 server-side checks.
* [Lasagna](https://github.com/BernardoGiordano/Lasagna) ⭐ 47 | 🐛 4 | 🌐 C++ | 📅 2018-01-30 - LayeredFS patch manager for Luma3DS, organizing romfs/exefs mod overlay folder structures.
* [pyctr](https://github.com/ihaveamac/pyctr) ⭐ 40 | 🐛 35 | 🌐 Python | 📅 2026-07-10 - Python library for reading Nintendo 3DS file formats (NCCH, ExeFS, RomFS, CIA, and more), used by several other 3DS tools.
* [RomFS-Builder](https://github.com/SciresM/RomFS-Builder) ⭐ 35 | 🐛 1 | 🌐 C# | 📅 2017-07-08 - Program to convert a folder in Windows into a 3DS RomFS binary. For use with makerom.
* [3dscrypto-tools](https://github.com/yellows8/3dscrypto-tools) ⭐ 29 | 🐛 0 | 🌐 C | 📅 2020-06-03 - Nintendo 3DS crypto tools: decrypt NCCH, CDN titles/tickets, save images, SpotPass/BOSS containers, and New3DS FIRM ARM9 sections.
* [otptool](https://github.com/SciresM/otptool) ⭐ 27 | 🐛 3 | 🌐 C | 📅 2021-10-19 - Tool for Nintendo OTP (One-Time Programmable) files.
* [png2bclim](https://github.com/kwsch/png2bclim) ⭐ 23 | 🐛 0 | 🌐 C# | 📅 2015-11-22 - Converter between PNG and the Nintendo BCLIM texture format.
* [eshop-analysis](https://github.com/d0k3/eshop-analysis) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2021-02-28 - Python script to analyze and parse Nintendo 3DS eShop title-list data.
* [HomeMenuEditor3DS](https://github.com/mrissaoussama/HomeMenuEditor3DS) ⭐ 20 | 🐛 0 | 🌐 C# | 📅 2025-06-01 - Tool for editing the Nintendo 3DS Home Menu layout database, moving/organizing/renaming titles and folders.
* [3ds-FUSE](https://github.com/DarkKirb/3ds-FUSE) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2017-05-21 - FUSE module for mounting and browsing 3DS-related file formats.
* [3dsconv-c](https://github.com/soarqin/3dsconv-c) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2019-11-18 - C port of ihaveamac's 3dsconv, converting Nintendo 3DS CCI cart images to CIA format.
* [CECTool](https://github.com/FlagBrew/CECTool) ⭐ 15 | 🐛 3 | 🌐 C++ | 📅 2019-08-03 - Proof-of-concept tool for injecting data into the 3DS's CEC (StreetPass) message format.
* [crotools](https://github.com/shinyquagsire23/crotools) ⭐ 14 | 🐛 1 | 🌐 C++ | 📅 2022-09-27 - Collection of tools for the Nintendo 3DS CRO/CRR shared-library binary format.
* [bchtool](https://github.com/dnasdw/bchtool) ⭐ 13 | 🐛 1 | 🌐 C++ | 📅 2019-03-02 - Tool for exporting and importing BCH model files used in Nintendo 3DS games.
* [rebuild-title-database](https://github.com/ihaveamac/rebuild-title-database) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2024-04-08 - Script to rebuild the contents of a Nintendo 3DS title.db Title Database, working alongside save3ds\_fuse.
* [txobtool](https://github.com/dnasdw/txobtool) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2019-05-25 - Tool for exporting and importing CGFX graphics files used in Nintendo 3DS games.
* [ctpktool](https://github.com/dnasdw/ctpktool) ⭐ 10 | 🐛 2 | 🌐 C++ | 📅 2019-07-09 - Tool for exporting/importing CTPK texture package files used in Nintendo 3DS games.
* [ctpktool](https://github.com/dnasdw/ctpktool) ⭐ 10 | 🐛 2 | 🌐 C++ | 📅 2019-07-09 - Tool for working with CTPK texture package files.
* [cmd-gen](https://github.com/ihaveamac/cmd-gen) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2019-06-07 - Experimental script to generate CMD files for Nintendo 3DS SD titles.
* [videoinject](https://github.com/ihaveamac/videoinject) ⚠️ Archived - Tool for injecting/creating Nintendo 3DS moflex video files.
* [rofs\_dumper](https://github.com/PabloMK7/rofs_dumper) ⭐ 10 | 🐛 2 | 🌐 C++ | 📅 2024-12-09 - Dumps very early Nintendo 3DS ROFS containers.
* [splashtool](https://github.com/profi200/splashtool) ⭐ 10 | 🐛 1 | 🌐 C++ | 📅 2017-12-25 - Generates Nintendo 3DS splash screen files in a custom format, with support for compression and common pixel formats.
* [save-data-copy-tool](https://github.com/ihaveamac/save-data-copy-tool) ⭐ 8 | 🐛 2 | 🌐 Makefile | 📅 2025-08-16 - Copies Nintendo 3DS save data between gamecard and digital versions of the same game.
* [dumptik](https://github.com/ihaveamac/dumptik) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2019-01-22 - Dumps all ticket (.tik) files from a Nintendo 3DS console.
* [BcmdlImporter](https://github.com/KillzXGaming/BcmdlImporter) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2022-07-16 - Tool to import DAE, FBX, and OBJ models into Nintendo 3DS BCMDL (CGFX-based) format without external libraries or toolkits.
* [save-crypto-finder](https://github.com/ihaveamac/save-crypto-finder) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-04-13 - Determines which titles a collection of encrypted Nintendo 3DS save files belong to, using boot9 and movable.sed.
* [bclimtool](https://github.com/dnasdw/bclimtool) ⭐ 6 | 🐛 1 | 🌐 C++ | 📅 2018-07-27 - Tool for decoding and encoding the Nintendo BCLIM texture format.
* [firmswap](https://github.com/ihaveamac/firmswap) ⚠️ Archived - Python implementation of the hardmod downgrade for Nintendo 3DS, working directly with FIRM partition data.
* [search-3ds](https://github.com/ihaveamac/search-3ds) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2017-08-13 - Searches the contents of encrypted/decrypted files used on the Nintendo 3DS system.
* [restore-overwritten-secureinfo](https://github.com/ihaveamac/restore-overwritten-secureinfo) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2024-12-14 - Restores a Nintendo 3DS console's SecureInfo\_A/B file from inspect.log data.
* [bclyt-stuff](https://github.com/Stary2001/bclyt-stuff) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2017-12-31 - Research and tools for the Nintendo BCLYT layout format, used across 3DS, Wii U, and Switch UI layouts.
* [3DS-Font](https://github.com/JayFoxRox/3ds-font) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2016-09-02 - Extracts and recreates Nintendo 3DS shared BCFNT font files, for use in the Citra emulator or homebrew projects.
* [gen-title-info-entry](https://github.com/ihaveamac/gen-title-info-entry) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2019-05-31 - Experimental script to generate the Title Info Entry structure used in a Nintendo 3DS title.db.
* [3ds-bannertool](https://github.com/ihaveamac/3ds-bannertool) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2024-11-30 - Tool for creating Nintendo 3DS banners; fork of carstene1ns/3ds-bannertool adding Windows Unicode fixes and a CMake build system.
* [layeredFS](https://github.com/ihaveamac/layeredFS) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2016-03-11 - LayeredFS mod for OSX/Linux/UNIX, modified to work from a decompressed code.bin instead of exefs.bin.

#### GameCube & Wii

* [Dolphin](https://github.com/dolphin-emu/dolphin) ⭐ 15,416 | 🐛 459 | 🌐 C++ | 📅 2026-08-18 - GameCube and Wii emulator that parses and implements support for GameCube/Wii disc and asset file formats.
* [noclip.website (Wii Banners)](https://github.com/magcius/noclip.website/tree/main/src/Common/NW4R/lyt) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - Renderer for NW4R LYT UI layouts, used to play back animated Wii channel banners from `banner.bin` archives. Parses BRLYT layouts, BRLAN animations, and NW4R bitmap fonts.
* [Kamek](https://github.com/Treeki/Kamek) ⭐ 96 | 🐛 6 | 🌐 C# | 📅 2026-06-09 - Code injection engine for GameCube and Wii games, compiling and linking custom C++ code against the original DOL/REL executables.
* [nod](https://github.com/encounter/nod) ⭐ 62 | 🐛 15 | 🌐 Rust | 📅 2026-07-17 - Rust library for reading and writing Nintendo Optical Disc images (GameCube and Wii). Includes nodtool CLI for extraction, conversion, and verification.
  * Formats: ISO (GCM), WIA/RVZ, WBFS, CISO, NFS (Wii U VC), GCZ, TGC.
* [gc-ipl](https://github.com/ogamespec/gc-ipl) ⭐ 56 | 🐛 1 | 🌐 C | 📅 2023-07-23 - Open source reimplementation of the GameCube IPL (boot ROM).
* [pyisotools](https://github.com/JoshuaMKW/pyisotools) ⭐ 48 | 🐛 2 | 🌐 Python | 📅 2025-10-17 - Python library for working with GameCube ISOs (GCM).
* [GeckoLoader](https://github.com/JoshuaMKW/GeckoLoader) ⭐ 44 | 🐛 3 | 🌐 Python | 📅 2024-02-11 - Extends the available code space for Gecko codes on Wii/GameCube games, allowing thousands of lines of Gecko code per game.
* [ida-wii-loaders](https://github.com/heinermann/ida-wii-loaders) ⭐ 30 | 🐛 10 | 🌐 C++ | 📅 2014-05-17 - IDA Pro loader plugins for the GameCube/Wii REL (relocatable module) and DOL executable file formats.
* [dolsdk2001](https://github.com/doldecomp/dolsdk2001) ⭐ 28 | 🐛 2 | 🌐 C | 📅 2025-09-18 - Decompilation of the 5-23-2001 version of the Dolphin (GameCube) SDK libraries.
* [WiiTools](https://github.com/Megazig/WiiTools) ⭐ 26 | 🐛 1 | 🌐 C++ | 📅 2013-10-08 - Tools for Wii reverse engineering and function identification to help hacking Wii games.
* [HopperPPC-Plugin](https://github.com/Sappharad/HopperPPC-Plugin) ⭐ 23 | 🐛 1 | 🌐 Objective-C | 📅 2018-06-29 - GameCube/Wii .DOL loader and PowerPC (Gecko) disassembly plugin for the Hopper Disassembler.
* [Kuribo](https://github.com/DotKuribo/Kuribo) ⭐ 23 | 🐛 0 | 🌐 C++ | 📅 2024-08-24 - Embedded Wii Channel mod loader, installing mods from an SD card. Loads its own .kxe executable format (supporting GCC, Clang, and CodeWarrior) as well as legacy Kamek .kmk executables.
* [open\_rvl](https://github.com/kiwi515/open_rvl) ⚠️ Archived - Decompilation of the RVL SDK (Nintendo's Wii operating system libraries), archived but a reference for the Wii's system-level formats.
* [mapdas](https://github.com/intns/mapdas) ⭐ 20 | 🐛 2 | 🌐 C# | 📅 2021-12-15 - Tools for working with Metrowerks symbol map (.map) and Gekko/Dolphin executable (.dol) files.
* [GCReLink](https://github.com/Cuyler36/GCReLink) ⚠️ Archived - Tool for unpacking and repacking GameCube and Wii relocatable modules (REL files).
* [triforce-header-patcher](https://github.com/FIX94/triforce-header-patcher) ⭐ 16 | 🐛 1 | 🌐 C | 📅 2021-10-28 - Verifies Triforce arcade disc images and patches in the correct headers.
* [triforce-nand-iso-extract](https://github.com/FIX94/triforce-nand-iso-extract) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2017-09-13 - Converts Triforce (Namco/Sega/Nintendo GameCube-based arcade board) NAND images to ISO files.
* [FunKii](https://github.com/AuroraWright/FunKii) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2019-08-10 - Command-line downloader for Wii content from the Nintendo CDN, packaging titles into installable WAD files (including DLC handling).
* [wii-shop-channel](https://github.com/vabold/wii-shop-channel) ⭐ 13 | 🐛 5 | 🌐 C | 📅 2025-11-28 - Decompilation of the Wii Shop Channel, reading an existing WAD dump of the channel.
* [libansnd](https://github.com/Oaisus/libansnd) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2026-02-04 - Audio library for Wii and GameCube homebrew with support for ADPCM audio decoding and arbitrary resampling. Supports up to 48 simultaneous voices with hardware ADPCM decoding.
* [EGG](https://github.com/vabold/EGG) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-04-15 - Decompilation of Nintendo's EGG library, a Wii-era in-house engine used across multiple first-party Wii games.
* [gc-gcm](https://github.com/jam1garner/gc-gcm) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2021-02-10 - Tool for GameCube GCM file format.
* [gc-c-kit](https://github.com/RenolY2/gc-c-kit) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2020-01-12 - Toolkit for compiling C code using devkitppc and injecting it into a GameCube Executable (DOL). Can be adapted to different GC games.
* [cgrr-gamecube](https://github.com/sopoforic/cgrr-gamecube) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2015-06-13 - Tools for GameCube file formats.
* [LibGCM](https://github.com/Sage-of-Mirrors/LibGCM) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2017-03-26 - Library for GameCube memory card formats.
* [geckocode-libs](https://github.com/JoshuaMKW/geckocode-libs) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-05-18 - Python library for parsing and editing Gecko Codes for the Wii/GCN.
* [dolreader](https://github.com/RenolY2/dolreader) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2021-07-08 - Reader for GameCube/Wii DOL executable format.
* [Chihuahua](https://github.com/Sage-of-Mirrors/Chihuahua) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2018-10-18 - Tool for GameCube/Wii file formats.
* [gci-bt](https://github.com/jam1garner/gci-bt) ⭐ 1 | 🐛 0 | 📅 2019-12-24 - GameCube GCI file tool with Bluetooth support.
* [DTMText](https://github.com/heinermann/DTMText) ⚠️ Archived - Converts Dolphin emulator DTM tool-assisted-speedrun movie files to and from a human-editable text format, to support diffing/version-controlling TAS inputs (GameCube, single controller only).

#### Nintendo DS / DSi

* [apicula](https://github.com/scurest/apicula) ⭐ 225 | 🐛 20 | 🌐 Rust | 📅 2025-01-21 - Converter for Nintendo DS .nsbmd 3D model format.
* [apicula/wiki/FILETYPES](https://github.com/scurest/apicula/wiki/FILETYPES) ⭐ 225 | 🐛 20 | 🌐 Rust | 📅 2025-01-21 - Documentation for Nintendo DS file types.
* [NTRGhidra](https://github.com/pedro-javierf/NTRGhidra) ⭐ 220 | 🐛 5 | 🌐 Java | 📅 2026-03-24 - Ghidra plugin for Nintendo DS.
* [TinkeDSi](https://github.com/R-YaTian/TinkeDSi) ⭐ 78 | 🐛 7 | 🌐 C# | 📅 2026-07-27 - Viewer and extractor for Nintendo DS/DSi file formats.
* [Flipnote-Encoder](https://github.com/RinLovesYou/Flipnote-Encoder) ⭐ 67 | 🐛 10 | 📅 2021-05-14 - Cross-platform Flipnote Studio (Nintendo DSi) encoder and signer, producing valid .ppm files.
* [sdatxtract](https://github.com/oreo639/sdatxtract) ⭐ 39 | 🐛 0 | 🌐 C | 📅 2021-02-06 - Command-line Nintendo DS Sound DATa (SDAT) extraction utility.
* [Ekona](https://github.com/SceneGate/Ekona) ⚠️ Archived - Nintendo DS file format library.
* [Hatenatools](https://github.com/pbsds/Hatenatools) ⚠️ Archived - Python tools for Flipnote Studio (Nintendo DSi) file formats. Supports reading and writing .ppm (Flipnote files), .tmb (thumbnail files), .ugo (user data), and .ntft (image files). Can extract metadata, frames, and audio from Flipnote files.
* [narchive](https://github.com/nickworonekin/narchive) ⭐ 23 | 🐛 1 | 🌐 C# | 📅 2019-04-28 - Tool for extracting and creating NARC archives used in DS games.
* [NitroSDK](https://github.com/ntrtwl/NitroSDK) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2026-08-17 - Official Nintendo DS SDK.
* [nitro-fs](https://github.com/DanielPXL/nitro-fs) ⭐ 14 | 🐛 0 | 🌐 TypeScript | 📅 2024-03-14 - Nintendo DS filesystem tools.
* [nitro-g3d-tools](https://github.com/Ermelber/nitro-g3d-tools) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2020-08-17 - Tools for Nintendo DS 3D graphics.
* [NitroModel ConverterGUI](https://github.com/TheGameratorT/NitroModel_ConverterGUI) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2019-11-23 - Converts between Nintendo DS Nitro model formats (NSBMD/NSBTX from ASS/IMD).
* [Nds4j](https://github.com/turtleisaac/Nds4j) ⭐ 9 | 🐛 0 | 🌐 Java | 📅 2024-10-31 - Java library for Nintendo DS formats.
* [nitroefx](https://github.com/Fexty12573/nitroefx) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2026-06-29 - Nintendo DS effect tools.
* [nitrogfx](https://github.com/red031000/nitrogfx) ⭐ 8 | 🐛 4 | 🌐 C | 📅 2026-08-07 - Nintendo DS graphics tools.
* [narc](https://github.com/lhearachel/narc) ⚠️ Archived - NARC archive tool for Nintendo DS.
* [nitrog3d](https://github.com/red031000/nitrog3d) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-11-12 - Nintendo DS 3D tools.
* [NitroSharp](https://github.com/PlatinumMaster/NitroSharp) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2023-05-31 - Nintendo DS file format library.
* [NitroSystem](https://github.com/ntrtwl/NitroSystem) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-02-26 - Nintendo DS system library.
* [NitroEffectMaker](https://github.com/HaroohiePals/NitroEffectMaker) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-08-22 - Effect editor for Nintendo DS.
* [DSlash](https://github.com/ElementW/dslash) ⭐ 0 | 🐛 1 | 🌐 C | 📅 2015-03-22 - Nintendo DS ROM viewing/extraction tool based on ndstrim (GitHub mirror of the original Google Code project).
* [Nitro Files](https://wiki.vg-resource.com/Nitro_Files) - Documentation for Nintendo DS file formats.
* [REGames Editor](https://www.reddit.com/r/REGames/comments/12o004k/a_friend_and_i_made_a_full_editor_for_a_nintendo/) - Full-featured editor for Nintendo DS games.

#### Nintendo 64

* [N64Recomp](https://github.com/N64Recomp/N64Recomp) ⭐ 8,041 | 🐛 57 | 🌐 C++ | 📅 2026-05-27 - Tool to statically recompile N64 games into native executables. Converts N64 binaries into C code that can be compiled for any platform.
* [glankk/n64](https://github.com/glankk/n64) ⭐ 115 | 🐛 4 | 🌐 C | 📅 2026-06-16 - Collection of N64 development tools.
  * Tools: `gfxdis` (F3DEX2 display list disassembler/decompiler), `gru` (Lua environment for manipulating raw binaries, N64 ROMs, Zelda64 file systems, UPS patches, and GameShark codes), `grc` (resource compiler for linkable N64 texture objects), `ed64rdb`/`gs` (remote debugging and GameShark upload utilities).
* [UltraCIC](https://github.com/mikeryan/UltraCIC) ⭐ 104 | 🐛 1 | 🌐 Assembly | 📅 2018-08-19 - Reverse-engineered clone of the Nintendo 64 CIC lockout/authentication chip.
* [ido-static-recomp](https://github.com/decompals/ido-static-recomp) ⭐ 79 | 🐛 10 | 🌐 C++ | 📅 2025-07-05 - Static recompilation of the SGI IDO 5.3/7.1 C compilers for modern platforms, letting N64 decompilation projects rebuild with the original toolchain to verify byte-matching output.
* [ultralib](https://github.com/decompals/ultralib) ⭐ 67 | 🐛 11 | 🌐 C | 📅 2026-04-19 - Reverse engineering and matching decompilation of libultra (the N64 SDK), supporting multiple IDO/GCC compiler and library versions.
* [gzinject](https://github.com/krimtonz/gzinject) ⭐ 26 | 🐛 4 | 🌐 C | 📅 2024-03-13 - WAD editing utility primarily used for patching N64 Virtual Console emulators and replacing the embedded ROM, with a documented patch file format.
* [N64-IPL](https://github.com/decompals/N64-IPL) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2024-03-13 - Matching disassemblies of the N64 boot code (IPL1, IPL2, and IPL3).
* [AudiobankToC](https://github.com/sauraen/AudiobankToC) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2022-01-03 - Scripts for converting between N64 Audiobank bank files and C code. Matches on binary -> C -> binary for banks in OoT.
* [ipl3checksum](https://github.com/Decompollaborate/ipl3checksum) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-01-17 - Python and Rust library to calculate the IPL3 (boot code) checksum for N64 ROMs, used to validate/patch ROMs in decompilation and recompilation workflows.
* [ido-rs](https://github.com/EllipticEllipsis/ido-rs) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2023-06-19 - Rust programs for handling SGI IDO compiler data formats (st, ucode, binasm), complementing ido-static-recomp above in N64 decompilation toolchains.
* [seq64](https://github.com/gheskett/seq64) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2024-02-11 - Full-featured editor for Nintendo 64 music sequencing (Audioseq format). Supports Super Mario 64, Mario Kart 64, and The Legend of Zelda: Ocarina of Time.

#### SNES / NES

* [jamulator](https://github.com/andrewrk/jamulator) ⭐ 621 | 🐛 2 | 🌐 Go | 📅 2013-06-07 - Early static recompiler converting NES ROMs into native executables via LLVM (unmaintained, historically notable predecessor to upernes/nesrecomp).
* [bsnes-plus](https://github.com/devinacker/bsnes-plus) ⭐ 362 | 🐛 101 | 🌐 C++ | 📅 2025-03-22 - Debug-oriented fork of bsnes with a tracer, memory/VRAM viewers, and breakpoints, widely used for SNES ROM hacking and reverse engineering.
* [DiztinGUIsh](https://github.com/DizTools/DiztinGUIsh) ⭐ 338 | 🐛 54 | 🌐 C# | 📅 2026-08-09 - Super NES ROM disassembler with tracelog capture/analysis and a focus on collaborative workflow; exports .asm files that reassemble back into the original binary.
* [asar](https://github.com/RPGHacker/asar) ⭐ 255 | 🐛 94 | 🌐 C++ | 📅 2026-07-08 - SNES assembler for applying patches to existing ROM images or building new ones from scratch; the long-standing standard assembler used across SNES ROM hacking projects.
* [SuperFamiconv](https://github.com/Optiroc/SuperFamiconv) ⭐ 189 | 🐛 22 | 🌐 C++ | 📅 2026-07-03 - Command-line tool to convert graphics to Super Nintendo format.
* [nesrecomp](https://github.com/mstan/nesrecomp) ⭐ 88 | 🐛 1 | 🌐 C | 📅 2026-08-14 - Static recompiler ecosystem for NES games (part of the R.A.I.D. community), converting 6502 ROM code into portable native code, similar in approach to upernes and GB Recompiled above.
* [Dispel](https://github.com/pelrun/Dispel) ⭐ 84 | 🐛 3 | 🌐 C | 📅 2023-02-09 - Disassembler for 65816/SNES ROM images.
* [SatellaWave](https://github.com/LuigiBlood/sat_wave) ⭐ 73 | 🐛 9 | 🌐 C# | 📅 2025-04-11 - Satellaview (BS-X) server manager/tool exporting broadcast satellite data as BSX-\*.bin files playable in bsnes-plus and snes9x, covering channels including Derby Stallion 96.
* [snes-assembly-book](https://github.com/Ersanio/snes-assembly-book) ⭐ 43 | 🐛 0 | 📅 2026-08-11 - 65c816 assembly guide covering opcodes and the inner workings of the SNES, aimed at ROM hacking and reverse engineering.
* [upernes](https://github.com/mandraga/upernes) ⭐ 38 | 🐛 1 | 🌐 Assembly | 📅 2025-06-20 - NES to Super NES recompiler; disassembles NES ROMs and converts 6502 code to SNES 65C816 assembly with hardware emulation.
* [NES-Sprite-Editor](https://github.com/eonarheim/NES-Sprite-Editor) ⭐ 37 | 🐛 0 | 🌐 JavaScript | 📅 2024-01-03 - Simple sprite editor for NES games.
* [M1TE2](https://github.com/nesdoug/M1TE2) ⭐ 31 | 🐛 4 | 🌐 C# | 📅 2025-11-24 - SNES Mode 1 Tile Editor for generating, editing, and arranging SNES tiles and tilemaps (2bpp/4bpp) with palette support. Designed for Mode 1 but works with any mode needing 2bpp or 4bpp graphics.
* [BSFlashManager](https://github.com/devinacker/BSFlashManager) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2020-02-23 - Tool for managing BS-X / Satellaview memory pack flash cartridges for the SNES, reading and writing the Satellaview's flash memory format.
* [snes-tile-tool](https://github.com/fo-fo/snes-tile-tool) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2016-07-26 - SNES tile graphics conversion tool.
* [nintendulatordx](https://github.com/fo-fo/nintendulatordx) ⭐ 6 | 🐛 1 | 🌐 C | 📅 2015-07-12 - Modified version of the Nintendulator NES emulator adding source-level debugging capabilities for NES ROM reverse engineering.
* [nes-header-info](https://github.com/infval/nes-header-info) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2022-02-24 - Tool for parsing and displaying iNES/NES 2.0 header information from NES ROM files.

#### Game Boy / GBA

* [metroboy](https://github.com/aappleby/metroboy) ⭐ 1,170 | 🐛 4 | 🌐 C++ | 📅 2025-02-23 - Repository of gate-level simulators and reverse-engineering tools for the original Game Boy hardware.
* [gbrom-tutorial](https://github.com/travisgoodspeed/gbrom-tutorial) ⭐ 1,155 | 🐛 0 | 📅 2026-08-17 - Tutorial for extracting the Game Boy boot ROM from die photographs.
* [gb-schematics](https://github.com/Gekkio/gb-schematics) ⭐ 696 | 🐛 0 | 📅 2024-05-18 - Reverse engineered Game Boy-related hardware schematics.
* [HexManiacAdvance](https://github.com/haven1433/HexManiacAdvance) ⭐ 464 | 🐛 21 | 🌐 C# | 📅 2026-03-17 - Hex editor for Game Boy Advance ROMs with scripting support.
* [GB Recompiled](https://github.com/arcanite24/gb-recompiled) ⭐ 425 | 🐛 5 | 🌐 Python | 📅 2026-08-05 - Static recompiler for Game Boy and Game Boy Color ROMs that translates LR35902 assembly directly to portable C code.
* [maskromtool](https://github.com/travisgoodspeed/maskromtool) ⭐ 388 | 🐛 28 | 🌐 C++ | 📅 2026-08-14 - CAD tool for extracting bits from mask ROM die photographs, used to recover boot ROM and other on-die data.
* [mgbdis](https://github.com/mattcurrie/mgbdis) ⭐ 320 | 🐛 14 | 🌐 Assembly | 📅 2026-07-31 - Game Boy ROM disassembler with RGBDS-compatible output.
* [gba\_explorer](https://github.com/attilathedud/gba_explorer) ⭐ 100 | 🐛 2 | 🌐 Vue | 📅 2018-12-12 - Explorer for Game Boy Advance ROMs, browsing and extracting embedded text, graphics, and sound data.
* [gbcam-rev-engineer](https://github.com/AntonioND/gbcam-rev-engineer) ⚠️ Archived - Tools used to reverse engineer the Game Boy Camera's sensor and communication protocol using an Arduino UNO.
* [windfish](https://github.com/jverkoey/windfish) ⭐ 84 | 🐛 43 | 🌐 Assembly | 📅 2021-02-14 - Tracing disassembler and UI for Game Boy ROMs, integrated with SameBoy for emulation and debugging.
* [gbadisasm](https://github.com/camthesaxman/gbadisasm) ⭐ 71 | 🐛 0 | 🌐 C | 📅 2022-02-14 - Game Boy Advance ROM disassembler.
* [gameboy-audio-dumper](https://github.com/FIX94/gameboy-audio-dumper) ⭐ 67 | 🐛 3 | 🌐 C | 📅 2022-08-02 - Dumps Game Boy ROMs and save files over an analog audio connection.
* [gbcamextract](https://github.com/jkbenaim/gbcamextract) ⭐ 53 | 🐛 0 | 🌐 C | 📅 2022-05-08 - Extracts photos from Game Boy Camera / Pocket Camera save files, including the Hello Kitty camera variant.
* [luvdis](https://github.com/aarant/luvdis) ⭐ 52 | 🐛 5 | 🌐 Python | 📅 2021-06-29 - Pure-Python Game Boy Advance disassembler.
* [dmg-schematics](https://github.com/msinger/dmg-schematics) ⭐ 46 | 🐛 2 | 🌐 KiCad Schematic | 📅 2026-05-18 - Reverse engineered schematics of the Game Boy's DMG-CPU B chip, including the SM83 CPU core. Successor to the archived DMG-CPU-Inside project.
* [gameboy-rom-parser](https://github.com/MarkMcCaskey/gameboy-rom-parser) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2023-07-06 - Rust parser for (Super) Game Boy (Color) ROM headers.
* [UnkrawerterGBA](https://github.com/MCJack123/UnkrawerterGBA) ⭐ 36 | 🐛 3 | 🌐 C++ | 📅 2022-03-05 - Game Boy Advance ROM extractor and converter.
* [gba-cartridge](https://github.com/jojolebarjos/gba-cartridge) ⭐ 34 | 🐛 0 | 🌐 Makefile | 📅 2022-05-10 - Experiments documenting how Game Boy Advance cartridges work.
* [Tilemap-Creator](https://github.com/erandis-vol/Tilemap-Creator) ⭐ 31 | 🐛 3 | 🌐 C# | 📅 2021-12-14 - Tileset and tilemap editor for the Game Boy Advance.
* [game-boy-camera-manager](https://github.com/marcrobledo/game-boy-camera-manager) ⭐ 24 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-25 - Tool for managing Game Boy Camera data, including both save (SRAM) photos and ROM contents.
* [gba\_dumper](https://github.com/attilathedud/gba_dumper) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2017-08-23 - Set of utilities for text modifications in GBA ROMs. Since GBA games use homebrew text encodings rather than ASCII, streamlines building a translation table from search matches, dumping translated ROM text, and re-injecting edited strings.
* [gba-lz77](https://github.com/lunasorcery/gba-lz77) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2019-12-09 - LZ77 compressor/decompressor producing byte-identical output to the GBA's LZ77 implementation, verified against LEGO Island 2 (GBA).
* [nds-slot2](https://github.com/IvanVeloz/nds-slot2) ⭐ 9 | 🐛 0 | 📅 2026-05-07 - Nintendo DS slot-2 (GBA slot) reverse engineering documentation.
* [cgrr-gameboy](https://github.com/sopoforic/cgrr-gameboy) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2015-06-05 - Tools for Game Boy file formats.
* [ninmonitorroms](https://github.com/0xabad1dea/ninmonitorroms) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2020-07-25 - Recovered Game Boy debug monitor ROMs, partial ROM images pulled from an official Nintendo Game Boy emulator.
* [gbp-decode](https://github.com/HerrZatacke/gbp-decode) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2024-05-16 - Set of functions to decode Game Boy Printer print job data.

#### Cross-Platform Formats & Archives

* [emuiibo](https://github.com/XorTroll/emuiibo) ⭐ 1,388 | 🐛 30 | 🌐 C++ | 📅 2026-04-05 - Virtual amiibo (amiibo emulation) system for Nintendo Switch, evolved from ogniK5377's switch-nfp-mitm.
* [AmiiboAPI](https://github.com/N3evin/AmiiboAPI) ⚠️ Archived - RESTful API and database of amiibo NFC tag data.
* [ninfs](https://github.com/ihaveamac/ninfs) ⭐ 536 | 🐛 28 | 🌐 Python | 📅 2026-07-10 - FUSE filesystem tool to mount Nintendo 3DS and Switch container/filesystem formats (CCI, CDN, CIA, NAND, NCA, RomFS, SD, etc.) for direct file browsing.
* [Nintendo-File-Formats](https://github.com/kinnay/Nintendo-File-Formats) ⭐ 107 | 🐛 1 | 🌐 Markdown | 📅 2026-08-12 - Documentation for Wii U and Switch file formats.
* [3DSkit](https://github.com/Tyulis/3DSkit) ⭐ 78 | 🐛 11 | 🌐 Python | 📅 2024-08-25 - Tool to extract and repack many file formats found on Nintendo DS, DSi, 3DS, Wii U, and Switch.
* [BFRES-Viewer](https://github.com/KillzXGaming/BFRES-Viewer) ⭐ 52 | 🐛 1 | 🌐 C# | 📅 2018-05-07 - Viewer for Nintendo BFRES model format files.
* [oead](https://github.com/zeldamods/oead) ⭐ 47 | 🐛 10 | 🌐 C++ | 📅 2026-08-01 - Library for recent Nintendo EAD first-party formats (BOTW/TOTK-era SARC, Yaz0, AAMP, BYML, and more), with Rust core and Python bindings. See also [cs-oead](https://github.com/EPD-Libraries/cs-oead) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2026-08-04 for a C# wrapper.
* [BFRES-Tool](https://github.com/aboood40091/BFRES-Tool) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2018-12-18 - Tool for working with Nintendo BFRES files.
* [3dsfont](https://github.com/dnasdw/3dsfont) ⭐ 36 | 🐛 0 | 🌐 C++ | 📅 2019-07-08 - Toolkit for Nintendo BCFNT and BFFNT font files (3DS, Wii U, Switch).
* [BFRES-Extractor](https://github.com/LordNed/BFRES-Extractor) ⭐ 33 | 🐛 1 | 🌐 C++ | 📅 2022-03-03 - Extractor for Nintendo BFRES format files.
* [SSBHLib](https://github.com/Ploaj/SSBHLib) ⭐ 29 | 🐛 31 | 🌐 C# | 📅 2022-12-08 - Library for reading and writing Nintendo SSBH rendering format files (used by Super Smash Bros. Ultimate and other Switch games).
* [nutexb](https://github.com/jam1garner/nutexb) ⭐ 15 | 🐛 2 | 🌐 Rust | 📅 2026-07-04 - Rust library for working with Namco Nutexb textures, found in Smash Ultimate and other Switch games.
* [KCollisionLibrary](https://github.com/KillzXGaming/KCollisionLibrary) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2022-05-14 - Library for reading and editing Nintendo KCL collision file binaries used by various games.
* [MSBTConverter](https://github.com/KillzXGaming/MSBTConverter) ⭐ 12 | 🐛 2 | 🌐 C# | 📅 2024-09-27 - Tool to convert Nintendo MSBT text files to YAML and back.
* [BFRES-Shader-Maker](https://github.com/KillzXGaming/BFRES-Shader-Maker) ⭐ 11 | 🐛 1 | 🌐 C# | 📅 2026-05-25 - Tool for building BFSHA/BNSH shader binaries from scratch using a given BFRES and GLSL code.
* [ssbh\_lib](https://github.com/ultimate-research/ssbh_lib) ⭐ 11 | 🐛 28 | 🌐 Rust | 📅 2026-08-14 - Rust library for reading and writing Nintendo SSBH rendering format files (used by Super Smash Bros. Ultimate and other Switch games).
* [msclang](https://github.com/jam1garner/msclang) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2020-05-10 - Custom C-to-MSC-bytecode compiler; MSC is the bytecode format used by Super Smash Bros. for Wii U for character logic.
* [mscdec](https://github.com/jam1garner/mscdec) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2020-11-06 - Decompiler that converts MSC bytecode (Super Smash Bros. for Wii U) back to C.
* [darctool](https://github.com/dnasdw/darctool) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2022-10-02 - Tool for extracting and creating DARC archive files used in Nintendo games.
* [sarctool](https://github.com/jam1garner/sarctool) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2022-12-22 - Command-line tool for working with Nintendo SARC archive files.
* [sarc](https://github.com/jam1garner/sarc) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2022-12-22 - Rust library for reading and writing Nintendo SARC and SZS (yaz0 compressed SARC) archive formats.
* [IONET](https://github.com/Ploaj/IONET) ⭐ 7 | 🐛 1 | 🌐 C# | 📅 2022-08-11 - .NET library for reading and writing several 3D model formats into a common object model.
* [BymlLibrary](https://github.com/EPD-Libraries/BymlLibrary) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2024-06-28 - Modern C# library for reading/writing Nintendo BYML (Binary YAML) files, versions 2-7, including Tears of the Kingdom's v7 nodes.
* [MessageStudio](https://github.com/EPD-Libraries/MessageStudio) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2026-01-10 - Modern C# implementation of Nintendo MessageStudio (LMS) text file formats.
* [pymsc](https://github.com/jam1garner/pymsc) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2020-08-14 - Python library for MSC format files.
* [img2nutexb](https://github.com/jam1garner/img2nutexb) ⭐ 6 | 🐛 1 | 🌐 Rust | 📅 2021-05-29 - Converts standard images (PNG, JPG, GIF, DDS, TGA, TIFF, ICO, BMP) to Nutexb, the Namco texture format used in Smash Ultimate and other Switch games.
* [aamp2xml](https://github.com/jam1garner/aamp2xml) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2017-05-14 - Converter for Nintendo AAMP parameter archive files (used across Breath of the Wild and other Nintendo EAD games) to/from XML.
* [msbt2sheets](https://github.com/CaXaPeK/msbt2sheets) ⭐ 5 | 🐛 1 | 🌐 C# | 📅 2025-06-06 - Converter for MSBT files to spreadsheet format.
* [amiitool.net](https://github.com/ca1e/amiitool.net) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2024-08-18 - C# port of amiitool, for decrypting/encrypting Nintendo amiibo NFC tag dumps.
* [Jungle](https://github.com/kinnay/Jungle) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - Accurate parser/encoder for various Nintendo file formats.
* [GARC-Unpack](https://github.com/vgmoose/GARC-Unpack) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2016-10-20 - Unpacker for Nintendo GARC archive format.
* [Lzarc-Tool](https://github.com/Fuzzy2319/Lzarc-Tool) ⭐ 4 | 🐛 2 | 🌐 C# | 📅 2026-04-02 - Tool for LZARC compressed archive format.
* [rust\_lzss](https://github.com/silentdragonz/rust_lzss) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2018-05-13 - Rust library implementing Nintendo's LZSS decompression, used across many Nintendo game formats.
* [BFRES-Model-Importer](https://github.com/KillzXGaming/BFRES-Model-Importer) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2018-05-18 - Script for injecting and replacing models in Nintendo BFRES files (Switch and Wii U), maintaining and extending smb123w64gb's original work.
* [CLMS](https://github.com/Trippixyz/CLMS) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2024-08-19 - C# library for Nintendo LMS (Message Studio) text format files (MSBT, MSBP, MSBF).
* [lzarc](https://github.com/jam1garner/lzarc) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2021-05-03 - Rust library and CLI for working with LZARC compressed archives used in Paper Mario Color Splash.
* [TSCBReader](https://github.com/Sage-of-Mirrors/TSCBReader) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2017-03-28 - Reader for TSCB format files.
* [KMP-Expander](https://github.com/Ermelber/KMP-Expander) ⭐ 3 | 🐛 2 | 🌐 C# | 📅 2022-03-09 - Expander for KMP format files.
* [bntx](https://github.com/jam1garner/bntx) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-01-04 - Rust library for working with Nintendo BNTX textures.
* [umsbt\_cmd\_extractor](https://github.com/efimandreev0/umsbt_cmd_extractor) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-01-05 - Command extractor for UMSBT files.
* [img2bntx](https://github.com/jam1garner/img2bntx) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-06-20 - Converts standard images to Nintendo BNTX texture format.
* [PyMsyt](https://github.com/NiceneNerd/PyMsyt) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2021-05-07 - Python library wrapping MSYT for editing Nintendo MSBT text files, used across Breath of the Wild and other Nintendo games.
* [BFRES-to-FBX-Converter](https://github.com/jdperos/BFRES-to-FBX-Converter) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2021-01-10 - Windows tool to convert Nintendo BFRES model files to FBX, built on the FBX SDK.
* [asb](https://github.com/EPD-Libraries/asb) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2023-06-06 - Base library for parsing and recompiling Nintendo ASB (Animation State Binary) and AINB files.
* [SarcLibrary](https://github.com/EPD-Libraries/SarcLibrary) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2026-08-18 - Modern C# reader/writer for Nintendo SEAD/SEPD SARC archives.
* [BntxLibrary](https://github.com/EPD-Libraries/BntxLibrary) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-08-01 - Simple C# IO library for the Nintendo BNTX texture format.
* [RstbLibrary](https://github.com/EPD-Libraries/RstbLibrary) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-04-06 - C# IO library for Nintendo Resource Size Table (RSTB/RESTBL) files.
* [sarc-extract](https://github.com/RenolY2/sarc-extract) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2015-07-31 - Extractor for SARC archive format.
* [zbic](https://github.com/kinnay/zbic) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-08-13 - Python package implementing the ZBIC compression algorithm used on Nintendo Switch.
* [AudioToolkit](https://github.com/EPD-Libraries/AudioToolkit) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-02-29 - IO library for file formats in Nintendo's nw::snd/nn::atk (NintendoWare) audio namespace.
* [MSBTEditor](https://github.com/efimandreev0/MSBTEditor) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2025-04-12 - MSBT text extractor/replacer for .msbt and .umsbt LE-files.
* [msc-debugger](https://github.com/jam1garner/msc-debugger) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2018-03-13 - Debugger for MSC bytecode files, the scripting format used in Super Smash Bros. for Wii U character logic.
* [AampLibrary](https://github.com/KillzXGaming/AampLibrary) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-07-23 - Library for editing v1 and v2 Nintendo AAMP parameter archive files.
* [Nintendo-File-Samples](https://github.com/kinnay/Nintendo-File-Samples) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-16 - Test set of Nintendo file format samples covering various edge cases, for validating tools against.
* [AinbLibrary](https://github.com/EPD-Libraries/AinbLibrary) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2024-10-25 - C# library for Nintendo AINB (AI Node Binary) files.
* [txtg](https://github.com/EPD-Libraries/txtg) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2023-05-15 - Experimental parser for the Nintendo TexToGo (TXTG) file format.
* [AalSharp](https://github.com/EPD-Libraries/AalSharp) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-07-31 - C# IO library for BARS and other Nintendo AAL audio resource file formats.
* [Syroot.NintenTools.Bfres](https://gitlab.com/Syroot/NintenTools) - Library for reading/writing Nintendo BFRES model format (Wii U).

### Sharp X68000 SDKs & Hardware

* [mdxtools](https://github.com/vampirefrog/mdxtools) ⭐ 91 | 🐛 22 | 🌐 C | 📅 2026-07-15 - Collection of tools for handling the MDX music format used on the Sharp X68000.
* [wav2adpcm](https://github.com/tantanGH/wav2adpcm) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-01-07 - Converts WAV PCM audio into the Sharp X68000's native ADPCM sound format.
* [png2xsp](https://github.com/Mikejmoffitt/png2xsp) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2025-03-12 - Converts PNG spritesheets into the Sharp X68000's XSP sprite library data format.

### PlayStation SDKs & Hardware

*Formats and tools generic to PlayStation consoles/SDKs, not tied to a specific game.*

* [vita2hos](https://github.com/xerpi/vita2hos) ⭐ 1,257 | 🐛 4 | 🌐 C | 📅 2025-06-07 - PlayStation Vita to Horizon OS (Nintendo Switch OS) translation layer (not an emulator), parsing Vita's executable format to run titles under Switch's OS.
* [uofw](https://github.com/uofw/uofw) ⭐ 432 | 🐛 35 | 🌐 C | 📅 2026-02-11 - The Unofficial Official FirmWare, a complete reverse engineering project for the latest PSP firmware.
* [LibOrbisPkg](https://github.com/maxton/LibOrbisPkg) ⭐ 359 | 🐛 21 | 🌐 C# | 📅 2023-10-24 - Library, GUI, and CLI for creating, inspecting, and modifying PS4 PKG, SFO, PFS, and related package/filesystem formats.
* [pkg2zip](https://github.com/lusid1/pkg2zip) ⭐ 279 | 🐛 1 | 🌐 C | 📅 2026-08-04 - Decrypts PlayStation Vita PKG files and repackages their contents (apps, DLC, patches, themes, PSM, PSX, PSP) into zip archives.
* [psvpfstools](https://github.com/motoharu-gosuto/psvpfstools) ⭐ 145 | 🐛 24 | 🌐 C++ | 📅 2022-02-06 - Set of tools to decrypt the PFS (PlayStation File System) filesystem layer used on PS Vita.
* [pspdecrypt](https://github.com/John-K/pspdecrypt) ⭐ 135 | 🐛 20 | 🌐 C | 📅 2024-06-07 - Simple tool to decrypt PSP binaries.
* [psp-media-engine-cracking-the-unknown](https://github.com/mcidclan/psp-media-engine-cracking-the-unknown) ⭐ 36 | 🐛 0 | 🌐 Assembly | 📅 2026-08-14 - Research documentation on the PSP's Media Engine, covering its Virtual Mobile Engine (VME), specialized move instructions, bitstream/context handling, local DMACs, VLD unit, and H.264 decoder.
* [PsxVram-SDL](https://github.com/romhack/PsxVram-SDL) ⭐ 19 | 🐛 1 | 🌐 C | 📅 2022-08-06 - PlayStation 1 VRAM viewer.
* [kirk](https://github.com/ProximaV/kirk) ⭐ 16 | 🐛 0 | 🌐 C++ | 📅 2024-08-17 - IDA Pro processor module for the PSP's KIRK crypto engine.
* [PSY-Q SDK Version Finder](https://github.com/jdperos/psyq-version-finder) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2026-03-02 - GUI tool for PS1 decompilation projects that identifies which Sony PSY-Q SDK version(s) a binary was built with, via color-coded byte-level signature diffing across 10+ SDK releases.

### Xbox SDKs & Hardware

*Formats and tools generic to the Xbox platform/OS, not tied to a specific game.*

* [SlimEra](https://github.com/XWine1/SlimEra) ⭐ 158 | 🐛 0 | 🌐 C++ | 📅 2025-07-22 - Slim Win32 reference implementations of select DLLs from the Xbox ERA operating system (e.g. D3DCompiler\_46.dll, xg\_x.dll), intended for research/analysis tooling rather than running full games.
* [XDL Compiler](https://github.com/XWine1/XDLCompiler) ⭐ 129 | 🐛 1 | 🌐 C# | 📅 2025-06-28 - Compiler for XDL, an IDL-like interface definition language (with versioning support) used to generate headers for reversing Xbox ERA OS components.
* [dump-xbox-dvd](https://github.com/JayFoxRox/dump-xbox-dvd) ⭐ 19 | 🐛 9 | 🌐 C | 📅 2018-04-16 - Dumps original Xbox game discs (XGD) to redump preservation standard using Kreon-firmware optical drives.
* [xbox-dvd-compress](https://github.com/JayFoxRox/xbox-dvd-compress) ⭐ 14 | 🐛 1 | 🌐 C++ | 📅 2018-08-12 - Proof-of-concept tools to inspect redump-format Xbox DVD images: extracts embedded authoring-tool version tags and traces the RNG seed used to generate sector padding, as groundwork for compression.
* [XboxAudio2](https://github.com/XWine1/XboxAudio2) ⭐ 12 | 🐛 0 | 🌐 C | 📅 2025-11-15 - XAudio2 wrapper providing XMA2 audio format support for Xbox TitleOS applications.
* [UnXiP](https://github.com/JayFoxRox/UnXiP) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2022-11-20 - Extracts XIP archive files from the original Xbox dashboard, based on Voltaic's PIXIT research.

### FMOD

*Audio middleware used in thousands of games for sound bank management and streaming.*

* [python-fsb5](https://github.com/HearthSim/python-fsb5) ⭐ 160 | 🐛 17 | 🌐 Python | 📅 2021-12-26 - Python library and command-line tool for extracting audio from FMOD FSB5 (FMOD Sample Bank) files. Decodes samples to WAV/OGG depending on codec.
* [Fmod5Sharp](https://github.com/SamboyCoding/Fmod5Sharp) ⭐ 48 | 🐛 3 | 🌐 C# | 📅 2026-07-13 - Managed C# library for decoding FMOD 5 sound banks (FSB5 and .bank files). Extracts individual audio samples and converts them to WAV or OGG.
  * See also [AssetRipper's fork](https://github.com/AssetRipper/Fmod5Sharp) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-03-16 with additional fixes used by the AssetRipper project.
  * Formats: PCM8, PCM16, PCM32, GCADPCM, IMAADPCM, VORBIS, FADPCM.
* [FMODSoundBankEditor](https://github.com/TheAdmiester/FMODSoundBankEditor) ⭐ 8 | 🐛 1 | 🌐 C# | 📅 2021-01-18 - GUI editor for FSB4 version FMOD sound bank (.fsb) files. Supports viewing, replacing, and exporting audio samples. Primarily developed for Xbox 360 Forza titles.
* [Fmod5Sharp (AssetRipper fork)](https://github.com/AssetRipper/Fmod5Sharp) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-03-16 - AssetRipper's maintained fork of SamboyCoding/Fmod5Sharp; a C# decoder for FMOD 5 FSB sound banks used internally by the AssetRipper Unity asset extraction pipeline.

### SpeedTree

*Procedural vegetation middleware used in many AAA games.*

* [Spt2Fbx](https://github.com/VenoMKO/Spt2Fbx) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2020-06-01 - Converts SpeedTree `.spt` files (up to v4.1) to `.fbx` static meshes. Drag-and-drop tool that preserves UV sets for diffuse, leaf card dimensions, pivot data, and leaf dimming.

### Wwise

*Audio middleware by Audiokinetic used in many AAA titles for sound bank management.*

* [bnkextr](https://github.com/eXpl0it3r/bnkextr) ⭐ 281 | 🐛 3 | 🌐 C++ | 📅 2025-02-18 - C++ command-line tool for extracting WEM audio files from Wwise BNK soundbank containers. Works with any game using Wwise audio middleware.
* [wwiser-utils](https://github.com/bnnm/wwiser-utils) ⭐ 80 | 🐛 1 | 🌐 Python | 📅 2026-08-15 - Companion utilities for wwiser, covering Wwise SoundBank (.bnk) and .wem audio files.
* [BnkExtractor](https://github.com/AssetRipper/BnkExtractor) ⭐ 33 | 🐛 4 | 🌐 C# | 📅 2024-12-27 - C# extraction library for Wwise audio containers. Extracts WEM audio files from BNK soundbanks and PCK file packages. Works with any game using Wwise audio middleware.
* [Unreal Engine Wwise Extractor](https://github.com/florensie/ue-wwise-extractor) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2022-04-07 - Python script to extract and convert Wwise BNK audio files from Unreal Engine pak files.
* [ExportUtilityWwise](https://github.com/djhaled/ExportUtilityWwise) ⭐ 5 | 🐛 1 | 🌐 C# | 📅 2026-05-19 - Console tool that exports Wwise audio events from Unreal Engine-based games (Valorant, Sea of Thieves, and others) to WAV files, automating sound extraction.

### Prism3D

* [Prism3D-file-formats](https://github.com/AlexKimov/Prism3D-file-formats) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2020-05-11 - File formats and tools for games built on the Prism3D engine.

## Game & Studio Tools

### 11 bit studios (Frostpunk)

* [Frostract - Frostpunk idx and dat unpacker](https://www.moddb.com/games/frostpunk/downloads/frostract-frostpunk-idx-and-dat-unpacker)

### 1C Company / Best Way

#### Men of War

* [Men of War 3DS Max Exporter Tools](https://www.moddb.com/games/men-of-war/downloads/men-of-war-3ds-max-exporter-tools) - 3DS Max exporter tools for Men of War. Supports 32-bit versions of 3DS Max 8, 9, 2008, and 2009 only. Mirrored here as the original Best Way download is no longer available.

#### Royal Quest Online

* [RQ.TOC.Tool](https://github.com/Ekey/RQ.TOC.Tool) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-01-02 - Tool for extracting archives from Royal Quest Online game files.

#### Adventures of Captain Blood

* [cb-file-formats](https://github.com/AlexKimov/cb-file-formats) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-04-14 - 010 Editor templates describing the file formats of Adventures of Captain Blood (Приключения Капитана Блада).

### 2K Czech / Illusion Softworks

* [MafiaToolkit](https://github.com/Greavesy1899/MafiaToolkit) ⭐ 153 | 🐛 9 | 🌐 C# | 📅 2026-07-17 - Toolkit with file format parsers and map editor for Mafia series (Mafia II, Mafia III, Mafia Definitive Edition), supporting SDS and XBin formats.
* [Gibbed.Illusion](https://github.com/gibbed/Gibbed.Illusion) ⭐ 23 | 🐛 3 | 🌐 C# | 📅 2019-05-03 - Tools for parsing and editing Illusion engine-based games, including Mafia II.
* [Max4dsTools](https://github.com/pudingus/Max4dsTools) ⭐ 19 | 🐛 3 | 🌐 MAXScript | 📅 2022-03-27 - 3ds Max plugin for import and export of the 4ds model format used in Mafia: The City of Lost Heaven. Supports meshes, LODs, billboarding, sectors, portals, skinned models, materials, and glows.
* [mafia-formats](https://github.com/RoadTrain/mafia-formats) ⭐ 11 | 🐛 0 | 📅 2020-11-20 - 010 Editor templates for Mafia: The City of Lost Heaven file formats. Also partly for Hidden & Dangerous 2 and Wings of War.
* [mafia-re (decomp)](https://github.com/Marvisak/mafia-re) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2025-03-03 - Matching decompilation of Mafia: The City of Lost Heaven.
* [EffectsBinEditor](https://github.com/legion2809/EffectsBinEditor) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2024-08-11 - Effects.bin editor for Mafia: The City of Lost Heaven written in C# (WPF application). Program to add or remove particle effects from a particular mission.

### 2K Games / Firaxis Games

* [Civilization IV Plugins for 3DS Max 6](https://www.moddb.com/games/civilization-iv-original/downloads/civilization-iv-plugins-for-3ds-max-6) - Official plugin for 3DS Max 6 with support for 3D models used in Sid Meier's Civilization IV.
* [Civilization IV Plugins for 3DS Max 7+](https://www.moddb.com/games/civilization-iv-original/downloads/civilization-iv-plugins-for-3ds-max-7) - Official plugin for 3DS Max 7 and newer with support for 3D models used in Sid Meier's Civilization IV.
* [OpenCiv3](https://github.com/C7-Game/OpenCiv3) ⭐ 638 | 🐛 99 | 🌐 C# | 📅 2026-08-05 - Open-source Civilization III remake with tools for parsing and importing original Civ3 game data.

#### WWE 2K

* [MusicListEditor](https://github.com/james-wallace-ghub/MusicListEditor) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2024-11-12 - Editor for the MusicList.jsfb music loop table used by WWE 2K23 and WWE 2K24, letting you browse, page through, and search slots by name or internal ID.

### 3D Realms

* [cosmore (decomp)](https://github.com/smitelli/cosmore) ⭐ 143 | 🐛 2 | 🌐 C | 📅 2024-10-23 - Matching decompilation of Cosmo's Cosmic Adventure (96% complete).
* [BioMenaceDecomp (decomp)](https://github.com/lethal-guitar/BioMenaceDecomp) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2024-12-27 - Matching decompilation of Bio Menace.

#### Duke Nukem 3D

* [jfduke3d](https://github.com/jonof/jfduke3d) ⭐ 139 | 🐛 4 | 🌐 C | 📅 2026-01-25 - JonoF's port of Duke Nukem 3D, built on his [jfbuild](https://github.com/jonof/jfbuild) ⭐ 134 | 🐛 3 | 🌐 C | 📅 2026-06-28 Build engine port, reading the original game's GRP/ART/MAP data.
* [DukeSharp](https://github.com/jmarshall23/DukeSharp) ⭐ 35 | 🐛 0 | 🌐 C# | 📅 2022-05-30 - Complete C# Unity port of Duke Nukem 3D's Build engine and game code from the original 1.4 Atomic Edition source, including a CON-to-C# (DukeScript) converter for existing mods.
* [duke3d](https://github.com/icculus/duke3d) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2021-07-12 - icculus.org's Linux port of Duke Nukem 3D, built from the officially released source code, reading the original game's GRP/ART/MAP data.
* [Clean Duke3D](https://github.com/Henrique194/clean-duke3d) ⭐ 6 | 🐛 1 | 🌐 C | 📅 2026-05-17 - Modern source port of Duke Nukem 3D focused on a clean, portable codebase, reading the original game's GRP/ART/MAP data.
* [DukeMapT3D](https://github.com/jmarshall23/DukeMapT3D) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2022-06-14 - Converts Duke Nukem 3D (Build engine) maps to Unreal Engine T3D format.
* [Landscaping Tools (Duke Nukem 3D)](https://www.moddb.com/games/duke-nukem-3d/downloads/landscaping-tools) - Files and resources for creating landscape terrain in Duke Nukem 3D. Includes tutorial files and example maps (not intended for gameplay).
* [Duke Nukem 3D source code](https://www.moddb.com/games/duke-nukem-3d/downloads/duke-nukem-3d-source-code) - Full source code to the classic first person shooter Duke Nukem 3D. Based on the v1.5 code. Installations on how to compile can be found in the included README.TXT.

#### Duke Nukem: Manhattan Project

* [Duke Nukem Manhattan Project Mesh & Bones Editing Tool](https://www.moddb.com/games/duke-nukem-manhattan-project/downloads/duke-nukem-manhattan-project-mesh-bones-editing-tool) - Official mesh and bones editing tool for Duke Nukem Manhattan Project

#### Duke Nukem: Zero Hour

* [DukeNukemZeroHour](https://github.com/Gillou68310/DukeNukemZeroHour) ⭐ 271 | 🐛 0 | 🌐 C | 📅 2025-11-06 - Decompilation of Duke Nukem: Zero Hour (N64).

#### Duke Nukem Forever (2001)

* [Blender to CPJ Plugin for DNF2001](https://www.moddb.com/mods/dnf2001-restoration-project/downloads/blender-to-cpj-plugin-for-dnf2001) - This plugin will allow you to export to the proprietary CPJ format for DNF2001 from blender.
* [Updated Blender to CPJ Plugin (Duke Nukem Forever 2001)](https://www.moddb.com/mods/dnf2001-restoration-project/downloads/updated-blender-to-cpj-plugin) - This plugin will allow you to export to the proprietary CPJ format for DNF2001 from blender.
* [DukeNukemForever](https://github.com/jmarshall23/DukeNukemForever) ⭐ 37 | 🐛 1 | 🌐 C++ | 📅 2022-07-27 - Remake of the leaked 2001 Duke Nukem Forever build on the idTech 4 engine, reading the leaked build's original assets.

#### Duke Nukem Forever (2011)

* [DukeForeverSDK](https://github.com/DaZombieKiller/DukeForeverSDK) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2024-07-15 - Unofficial modding SDK for Duke Nukem Forever (2011).
* [MegaPackageExtractor](https://github.com/DaZombieKiller/MegaPackageExtractor) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2022-08-02 - Duke Nukem Forever (2011) MegaPackage.dat extractor.

#### Shadow Warrior

* [jfsw](https://github.com/jonof/jfsw) ⭐ 97 | 🐛 3 | 🌐 C | 📅 2026-01-25 - JonoF's port of Shadow Warrior, built on his [jfbuild](https://github.com/jonof/jfbuild) ⭐ 134 | 🐛 3 | 🌐 C | 📅 2026-06-28 Build engine port, reading the original game's GRP/ART/MAP data.
* [shadowwarrior](https://github.com/icculus/shadowwarrior) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2021-07-12 - icculus.org Linux port of 3D Realms' Shadow Warrior, built from the officially released source code.

#### The Outforce

* [Outforce meshes extractor](https://www.moddb.com/games/the-outforce/downloads/outforce-meshes-extractor) - Mesh and model extractor for The Outforce. Created by szkaradek123.
* [The Outforce Box extractor tool](https://www.moddb.com/games/the-outforce/downloads/the-outforce-box-extractor-tool) - \*.box archive extractor tool for the game "The Outforce"

### 3DO / New World Computing

#### Might and Magic: World of Xeen

* [XeenTools](https://github.com/HiPhish/XeenTools) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2019-04-11 - Open-source C library and CLI tools for resource files of Might & Magic IV: Clouds of Xeen and Might & Magic IV: Darkside of Xeen. Supports CC archive containers, MAZExxxx.DAT/.MOB maps, ATT/OBJ/MON/GND/SKY sprite formats, PAL palettes, FNT fonts, and CFG/CHR/FAC/FWL/RAW files.

#### Heroes of Might and Magic II

* [fheroes2](https://github.com/ihhub/fheroes2) ⭐ 3,437 | 🐛 434 | 🌐 C++ | 📅 2026-08-17 - Recreation of Heroes of Might and Magic II game engine that requires and parses original .AGG archive format, providing high-resolution graphics and improved AI.

#### Heroes of Might and Magic III

* [vcmi](https://github.com/vcmi/vcmi) ⭐ 5,788 | 🐛 703 | 🌐 C++ | 📅 2026-08-18 - Open-source reimplementation of the Heroes of Might and Magic III engine, loading and reading the original game's data files (H3sprite.lod, Heroes3.exe resources, maps, campaigns).

#### Heroes of Might and Magic IV

* [engine4heroes](https://github.com/ihhub/engine4heroes) ⭐ 23 | 🐛 0 | 🌐 C++ | 📅 2026-06-24 - Recreation of the Heroes of Might and Magic IV game engine; like fheroes2 above, requires and reads the original commercial game's data files.

### 4A Games

#### Metro

* [MetroTC](https://github.com/iOrange/MetroTC) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2019-08-13 - Universal texture converter for all Metro games (2033, Last Light, Exodus) by 4A Games.

### 5th Cell

* [locksmith (decomp)](https://github.com/redraincatching/locksmith) ⭐ 0 | 🐛 0 | 📅 2024-08-07 - Matching decompilation of Lock's Quest.

### 8monkey Labs

* [Translation Tool (Darkest of Days)](https://www.moddb.com/games/darkest-of-days/downloads/darkest-of-days-translation-tool)

### Acclaim Entertainment (Turok)

* [turok3 (decomp)](https://github.com/Drahsid/turok3) ⚠️ Archived - Matching decompilation of Turok 3: Shadow of Oblivion (N64).
* [ReVoltTrackEditor](https://github.com/Dummiesman/ReVoltTrackEditor) ⭐ 11 | 🐛 1 | 🌐 C# | 📅 2023-04-25 - Track editor for Re-Volt that reads original editor project files (.rtu, WAV, BMP) and exports tracks compatible with Re-Volt/RVGL.

### Accolade (Eradicator)

* [erad\_ripper](https://github.com/Yagotzirck/erad_ripper) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2018-10-25 - Resource extractor for Eradicator (1996, DOS).

### Acornsoft

#### Elite

* [elite-source-code-nes](https://github.com/markmoxon/elite-source-code-nes) ⭐ 404 | 🐛 0 | 🌐 Assembly | 📅 2026-08-01 - Fully documented, line-by-line annotated source code for the NES conversion of Elite (1984), part of a wider software-archaeology project by the same author covering Elite's BBC Micro, Commodore 64, Apple II, and other ports.

### Akella

*Sea Dogs, Pirates of the Caribbean, Age of Pirates.*

* [storm-engine](https://github.com/storm-devs/storm-engine) ⚠️ Archived - Open-source reimplementation of the Storm Engine, the game engine behind Sea Dogs, Pirates of the Caribbean, and Age of Pirates, reading original game assets.

### Action Forms (Chasm: The Rift)

* [Chasm-Reverse](https://github.com/Panzerschrek/Chasm-Reverse) ⭐ 176 | 🐛 31 | 🌐 C++ | 📅 2025-12-09 - Reverse engineering and reimplementation of Chasm: The Rift (Action Forms, 1997), reading the original game's data files.
* [chasm-tools](https://github.com/jmickle66666666/chasm-tools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2018-03-03 - Python tools for hacking and extracting data from Chasm: The Rift (1997, Action Forms).

### Activision / Infinity Ward / Treyarch

#### Call of Duty

* [Greyhound](https://github.com/Scobalula/Greyhound) ⭐ 471 | 🐛 4 | 🌐 C++ | 📅 2024-07-28 - Asset extractor for several Call of Duty titles (Black Ops 3/4, WWII, Infinite Warfare, Modern Warfare 2019/II).

* [KisakCOD](https://github.com/SwagSoftware/KisakCOD/) ⭐ 419 | 🐛 23 | 🌐 C++ | 📅 2026-08-08 - Open-source, fully buildable reimplementation of Call of Duty 4 multiplayer; aimed at mod developers.

* [gsc-tool](https://github.com/xensik/gsc-tool) ⭐ 315 | 🐛 6 | 🌐 C++ | 📅 2026-07-25 - Compiler/decompiler for IW Engine GSC game scripts (Black Ops, Ghosts, Modern Warfare, Vanguard, Warzone).

* [iw4x-client](https://github.com/iw4x/iw4x-client) ⭐ 302 | 🐛 31 | 🌐 C++ | 📅 2026-08-14 - Client reimplementation/mod for Call of Duty: Modern Warfare 2 (IW4 engine) multiplayer, including the built-in ZoneBuilder asset/fastfile pipeline tool used by the IW3x/IW5x porting utilities.

* [zonetool](https://github.com/ZoneTool/zonetool) ⭐ 164 | 🐛 15 | 🌐 C++ | 📅 2021-11-14 - Fastfile linker for Call of Duty titles (CoD4, MW, MW2, MW3), parsing and reconstructing IW3/IW4/IW5 fastfile archives.

* [iw3xo-radiant](https://github.com/xoxor4d/iw3xo-radiant) ⭐ 126 | 🐛 3 | 🌐 C++ | 📅 2025-05-02 - Enhanced Radiant level editor modification for Call of Duty 4 (IW3 Engine).

* [blender-cod](https://github.com/CoDEmanX/blender-cod) ⭐ 106 | 🐛 18 | 🌐 Python | 📅 2023-02-13 - Blender add-on for Call of Duty modding.

* [CoD4 Mod Tools 1.1 (mirror)](https://github.com/promod/CoD4-Mod-Tools) ⭐ 83 | 🐛 2 | 🌐 C++ | 📅 2018-05-13 - Repository containing the original Call of Duty 4 Mod Tools and 1.1 update from Infinity Ward.

* [Cordycep](https://github.com/Scobalula/Cordycep) ⭐ 81 | 🐛 0 | 🌐 C++ | 📅 2024-08-21 - Tool that utilizes modified game executables to load fast files for Call of Duty.

* [x64 ZoneTool](https://github.com/Joelrau/x64-zt) ⭐ 65 | 🐛 15 | 🌐 C++ | 📅 2026-08-06 - Fastfile unlinker and linker for x64 Call of Duty titles.

* [Tyrant](https://github.com/Scobalula/Tyrant) ⭐ 52 | 🐛 5 | 🌐 C# | 📅 2025-07-04 - RE Engine asset extractor for Call of Duty file formats.

* [WraithXArchon](https://github.com/dtzxporter/WraithXArchon/) ⚠️ Archived - Legendary Call of Duty asset extraction tool.

* [zonebuilder](https://github.com/RagdollPhysics/zonebuilder) ⭐ 30 | 🐛 0 | 🌐 C++ | 📅 2018-02-10 - Fastfile generator for IW4 (Modern Warfare 2).

* [gsc-asm](https://github.com/ZoneTool/gsc-asm) ⭐ 27 | 🐛 0 | 🌐 C++ | 📅 2019-09-18 - GSC assembler/disassembler for IW5 (Call of Duty: Modern Warfare 3).

* [lui-tool](https://github.com/xensik/lui-tool) ⭐ 24 | 🐛 0 | 🌐 C++ | 📅 2026-04-01 - Utility to assemble and disassemble IW engine UI scripts. Supports Call of Duty: Ghosts (IW6).

* [IWMenuDumper](https://github.com/aerosoul94/IWMenuDumper) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2018-05-31 - Decompiler for IW Engine menu files (Modern Warfare 2, Modern Warfare 3).

* [iwd-tool](https://github.com/ZoneTool/iwd-tool) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2019-09-17 - Command-line tool for generating IWD files for Call of Duty.

* [Unreal-SeTools](https://github.com/djhaled/Unreal-SeTools) ⭐ 17 | 🐛 3 | 🌐 C++ | 📅 2026-05-19 - Unreal Engine editor plugin to batch-import Call of Duty SEModel (.semodel) files, including meshes, animations, and materials.

* [iw4x-map-porting-utility](https://github.com/iw4x/iw4x-map-porting-utility) ⭐ 13 | 🐛 7 | 🌐 C# | 📅 2024-10-10 - Middleware to simplify porting maps from Call of Duty 4 (IW3) to Modern Warfare 2 (IW4), unifying export from iw3x-port to ZoneBuilder.

* [Mappie](https://github.com/timing1337/Mappie) ⚠️ Archived - Call of Duty map extraction tool for modern titles (MW19, BOCW, VG, MWII).

* [iw3x-port](https://github.com/iw4x/iw3x-port) ⭐ 12 | 🐛 4 | 🌐 C++ | 📅 2026-05-26 - Community-driven map/asset converter for porting Call of Duty 4 (2007, IW3) content to IW4 (Modern Warfare 2), used with IW4x's ZoneBuilder.

* [ShibaInu](https://github.com/Scobalula/ShibaInu) ⭐ 11 | 🐛 0 | 🌐 C# | 📅 2022-01-15 - Weapon file converter for Call of Duty Mod Tools.

* [iw4-open-formats](https://github.com/iw4x/iw4-open-formats/blob/main/src/iw4-of/assets/assets.cpp) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2026-03-19 - Asset conversion system for MW2 formats.

* [Kobra](https://github.com/VenomModding/Kobra) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2024-06-30 - Fork of Greyhound with added support for XEffect, GDT, and more. Used for Call of Duty asset extraction.

* [flac-tool](https://github.com/alicealys/flac-tool) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2022-07-23 - Converts FLAC audio files to be compatible with the IW engine.

* [iw5x-port](https://github.com/iw4x/iw5x-port) ⭐ 5 | 🐛 1 | 🌐 C++ | 📅 2025-08-11 - Asset/map export and conversion port utility for IW5 (Call of Duty: Modern Warfare 2 2009), analogous to iw3x-port for IW4.

* [img-format-helper](https://github.com/iw4x/img-format-helper) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2023-08-19 - Tool to visualize, export, and convert IWI image formats used across Call of Duty (IW engine) asset dumps.

* [shader-tool](https://github.com/alicealys/shader-tool) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2025-12-05 - Library to parse, assemble, and disassemble DirectX Shader Bytecode (DXBC) objects used by the IW engine.

* [zonebuilder-wrapper](https://github.com/iw4x/zonebuilder-wrapper) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-06-13 - Wrapper around ZoneBuilder for building IW4x-compatible Call of Duty assets.

* [IWI DDS Fast Converter V1.40 (Call of Duty 2)](https://www.moddb.com/games/call-of-duty-2/downloads/iwi-dds-fast-converter-v140)

* [x to xmodel\_export converter 1.6 cod5 Version (Call of Duty: World at War)](https://www.moddb.com/games/call-of-duty-world-at-war/downloads/x-to-xmodel-exporter-converter-16-cod5-version) - Converter for DirectX (*.x) and Wavefront Object (*.obj) files to Call of Duty: World at War xmodel\_export format. Converted files can then be converted to xmodel using the Asset Manager. Place xconv.exe in CoD5 directory and run (v1.6).

* [BSP Decompiler (Call of Duty)](https://www.moddb.com/games/call-of-duty/downloads/bsp-decompiler) - Hereby we release our decompiler and the sources. May it prove to be useful for you or your team.

* [Call of Duty 1 Milkshape plugins](https://www.moddb.com/games/call-of-duty/downloads/call-of-duty-1-milkshape-plugins) - Series of Milkshape plugins for Call of Duty 1. Created by scorpiomidget.

* [Call of Duty 1 Mod Tools No Installer Version](https://www.moddb.com/games/call-of-duty/downloads/call-of-duty-1-mod-tools-no-installer-version) - Alternative version for users experiencing installation issues with the official installer, typically caused by missing or corrupt game registry entries.

* [Call of Duty 2 Mod Tools](https://www.moddb.com/games/call-of-duty-2/downloads/call-of-duty-2-mod-tools) - Official modding tools for Call of Duty 2.

* [Call of Duty 2 Mod Tools No Installer](https://www.moddb.com/games/call-of-duty-2/downloads/call-of-duty-2-mod-tools-no-installer) - Alternative version for users experiencing installation issues with the official installer, typically caused by missing or corrupt game registry entries.

* [Iwi Converter (Call of Duty 2)](https://www.moddb.com/games/call-of-duty-2/downloads/iwi-converter) - IWI converter with multi-file selection support for Call of Duty 2. Created to address lack of multi-select support in other IWI converters.

* [KV Map Converter v2 Beta2 (Call of Duty 4: Modern Warfare)](https://www.moddb.com/games/call-of-duty-4-modern-warfare/downloads/kv-map-converter-v2-beta2) - Utility by KillerVirus for converting Source Engine maps to Call of Duty 4: Modern Warfare format (v2 Beta2).

#### Call to Power II

* [civctp2](https://github.com/civctp2/civctp2) ⭐ 111 | 🐛 92 | 🌐 C | 📅 2026-08-10 - Community-maintained source port of Call to Power II, built from the officially released source code and reading the original game's data files.

#### Tony Hawk's Pro Skater

* [C2M](https://github.com/sheilan102/C2M) ⭐ 76 | 🐛 3 | 🌐 C# | 📅 2022-12-05 - Tool to export maps from Call of Duty games.
* [thps2-tools](https://github.com/JayFoxRox/thps2-tools) ⭐ 28 | 🐛 3 | 🌐 Python | 📅 2020-01-03 - Collection of tools for Tony Hawk's Pro Skater 2.
* [psx\_texture\_extractor](https://github.com/slfx77/psx_texture_extractor) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-02-17 - Extractor for textures within Neversoft's PS1 model format, supporting 4, 8, and 16-bit textures (16-bit support incomplete).
* [Hed-Extract](https://github.com/Daniel-McCarthy/Hed-Extract) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2021-08-17 - Extractor/packer for Tony Hawk's Project 8 (PSP) .hed/.wad files.
* [neversoft-multitool](https://github.com/slfx77/neversoft-multitool) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2026-07-26 - .NET tool (WinUI 3 GUI + cross-platform CLI) for extracting and converting Neversoft Entertainment game assets across the PS1, Dreamcast, Xbox, GameCube, PC, and PS2 eras (1998-2006): Tony Hawk's Pro Skater 1-4/THUG/THUG2/THAW (this section), plus Spider-Man, Apocalypse, and Guitar Hero (PS2).
  * Formats: PSX/PVR/RLE/BMR/ZLB/BMP/TGA/PS2 TEX/RenderWare TXD/Xbox TEX textures; WAD+HED/PKR3/PRE/DDX/BON/PAK archives with recursive disc-image extraction (ISO9660/Xbox XDVDFS/GameCube GCM/Dreamcast GDI); PS1 XA/VAB audio.
* [RLE-GIMP-Plugin](https://github.com/Daniel-McCarthy/RLE-GIMP-Plugin) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2021-09-24 - GIMP plugin for Neversoft's .rle 16-bit image format.
* [THPS2X-Formats](https://github.com/Vadru93/THPS2X-Formats) ⭐ 3 | 🐛 1 | 📅 2020-06-24 - Binary format documentation for Tony Hawk's Pro Skater 2X level files (.DDM, .DDX, .psx, .trg).
* [TonyWad](https://github.com/cuckydev/TonyWad) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2023-09-20 - Extracts WAV audio from PS2 Tony Hawk games.
* [WAD Tool v1.0 (Tony Hawk's Pro Skater)](https://www.moddb.com/games/tony-hawks-pro-skater/downloads/wad-tool-v10) - A small tool to build and extract WAD files from early thps-engine based games.
* [TOXEC (The Obj to Xmodel Export Converter)](https://www.moddb.com/games/call-of-duty-world-at-war/downloads/toxec-the-obj-to-xmodel-export-converter) - Converter for OBJ files to Xmodel format. For use with Call of Duty 4 and Call of Duty: World at War mapping.
* [DDS/IWI Converter 1.5 (Call of Duty 2)](https://www.moddb.com/games/call-of-duty-2/downloads/dds-iwi-converter-1-5)

#### Ghostbusters

* [Gibbed.Ghostbusters](https://github.com/gibbed/Gibbed.Ghostbusters) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2017-05-15 - Tools and code for use with Ghostbusters: The Video Game (2009).

#### A Series of Unfortunate Events

* [resPack](https://github.com/XAYRGA/resPack) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2023-12-02 - Extractor for Xbox A Series of Unfortunate Events archive files.

#### Spider-Man (Neversoft)

* [spidey-decomp](https://github.com/krystalgamer/spidey-decomp) ⭐ 121 | 🐛 9 | 🌐 C | 📅 2026-08-17 - Decompilation of Neversoft's Spider-Man (PC port), useful for studying formats and game internals.

#### Wolfenstein (2009)

* [Wolfenstein-SPK-Tool](https://github.com/dortkoldantaciz/Wolfenstein-SPK-Tool) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-14 - Extract and repack tool for Wolfenstein (2009) .spk files.

#### PSX Activision Games

* [gRLE](https://github.com/gdkchan/gRLE) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2015-05-06 - Viewer/editor/creator for \*.rle files used in PSX Activision games.

### Adeline Software International

#### Little Big Adventure 1

* [lba1-classic](https://github.com/2point21/lba1-classic) ⭐ 473 | 🐛 4 | 🌐 Assembly | 📅 2022-02-27 - Official release of the Little Big Adventure 1 engine source code, published with preservation in mind (game assets not included; requires original data files).

#### Little Big Adventure 2

* [lba2-classic](https://github.com/2point21/lba2-classic) ⭐ 539 | 🐛 0 | 🌐 Assembly | 📅 2021-12-22 - Official release of the Little Big Adventure 2 engine source code, published with preservation in mind (game assets not included; requires original data files).

### ADvertainment Software (Quiver)

* [quiver\_ripper](https://github.com/Yagotzirck/quiver_ripper) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2018-09-24 - Resource extractor for Quiver (1997, DOS).

### Aether Studios (Rivals of Aether)

* [rivals-modding-tool](https://github.com/jam1garner/rivals-modding-tool) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2018-09-15 - Modding tool for Rivals of Aether (GameMaker-based fighting game).

### AKI Corporation

* [WCWvsNWOWorldTourRecomp](https://github.com/jessetbh/WCWvsNWOWorldTourRecomp) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2026-08-15 - Native PC port of WCW vs. nWo World Tour (N64) via static recompilation, with a companion [WCWSyms](https://github.com/jessetbh/WCWSyms) ⭐ 2 | 🐛 0 | 📅 2026-07-06 repo of reverse-engineered function/data symbol TOMLs for the N64Recomp toolchain.
* [WCWnWoRevengeRecomp](https://github.com/jessetbh/WCWnWoRevengeRecomp) ⭐ 17 | 🐛 0 | 🌐 C++ | 📅 2026-08-15 - Native PC port of WCW/nWo Revenge (N64) via static recompilation (bring your own ROM).
* [AkiLauncher](https://github.com/jessetbh/AkiLauncher) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2026-08-09 - Native Windows hub that downloads and launches the AKI-engine N64 wrestling recompilations above.
* [WWFNoMercyRecomp](https://github.com/jessetbh/WWFNoMercyRecomp) ⭐ 11 | 🐛 2 | 🌐 C | 📅 2026-08-15 - Native PC port of WWF No Mercy (N64) via static recompilation.
* [WWFWrestleMania2000Recomp](https://github.com/jessetbh/WWFWrestleMania2000Recomp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-08-15 - Native PC port of WWF WrestleMania 2000 (N64) via static recompilation.
* [VPW64Recomp](https://github.com/jessetbh/VPW64Recomp) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2026-08-15 - Native PC port of Virtual Pro Wrestling 64 (N64) via static recompilation.
* [VPW2Recomp](https://github.com/jessetbh/VPW2Recomp) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-08-15 - Native PC port of Virtual Pro Wrestling 2 (N64) via static recompilation.

### Amber Studio

* [amber-file-formats](https://github.com/AlexKimov/amber-file-formats) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-02-02 - File formats and viewer plugins for Amber Studio games.

### Analgesic Productions

#### Anodyne

* [Anodyne-1-Repo](https://github.com/analgesicproductions/Anodyne-1-Repo) ⭐ 391 | 🐛 1 | 🌐 ActionScript | 📅 2024-06-04 - Official source code release for Anodyne.
* [AnodyneSharp](https://github.com/PixieCatSupreme/AnodyneSharp) ⭐ 55 | 🐛 0 | 🌐 C# | 📅 2026-02-04 - C#/MonoGame rewrite of Anodyne, based on the original game's source code.
* [anodyne-map-scraper](https://github.com/thejoshwolfe/anodyne-map-scraper) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2016-11-29 - Scrapes and reconstructs the overworld map from Anodyne's original game data.

#### Anodyne 2

* [Anodyne-2-Open-Source](https://github.com/analgesicproductions/Anodyne-2-Open-Source) ⭐ 157 | 🐛 0 | 🌐 C# | 📅 2024-08-14 - Official source code and assets release for Anodyne 2: Return to Dust.

#### Even the Ocean

* [Even-The-Ocean-Open-Source](https://github.com/analgesicproductions/Even-The-Ocean-Open-Source) ⭐ 117 | 🐛 3 | 🌐 Haxe | 📅 2024-06-21 - Official source code release for Even the Ocean.

### Angel Matrix (Neon White)

* [noclip.website (Neon White)](https://github.com/magcius/noclip.website/tree/main/src/NeonWhite) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Neon White viewer.

### Angel Studios / Rockstar San Diego

* [gta-v-data-dumps](https://github.com/DurtyFree/gta-v-data-dumps) ⭐ 1,021 | 🐛 18 | 📅 2026-06-09 - Collection of GTA V data dumps (vehicles, weapons, peds, natives, etc.) generated from RAGE-format research; reference for modding and scripting.
* [CodeWalker](https://github.com/dexyfex/CodeWalker) ⭐ 733 | 🐛 129 | 🌐 C# | 📅 2025-04-11 - GUI tool for viewing and editing GTA V's RAGE engine data, including RPF archive contents, YFT/YDR/YDD models, YTD textures, and YMAP/YTYP world data.
* [MeltyTool](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/AngelStudios) ⭐ 200 | 🐛 60 | 🌐 C# | 📅 2026-08-19 - Multitool for viewing/extracting assets from various N64/GCN/3DS/PC games en-masse.
* [VichoTools](https://github.com/Hancapo/VichoTools) ⭐ 44 | 🐛 7 | 🌐 Python | 📅 2026-07-21 - Blender add-on for GTA V modding; handles YMAP scene files, YTD texture dictionaries, and animation clips extraction and editing.
* [blender\_io\_GTA5Ped](https://github.com/lucasvinbr/blender_io_GTA5Ped) ⭐ 40 | 🐛 4 | 🌐 Python | 📅 2024-02-27 - Blender import/export add-on for GTA V pedestrian (ped) meshes via OpenIV's openFormats (.odd/.odr/.mesh/.skel).
* [Folder2YTD](https://github.com/Hancapo/Folder2YTD) ⭐ 33 | 🐛 4 | 🌐 C# | 📅 2025-07-14 - Tool to create and pack GTA V .YTD texture archive files from image folders; supports PNG, DDS, TGA, JPG, WebP, GIF, PSD with quality settings and mipmap generation.
* [libertyv](https://github.com/koolkdev/libertyv) ⭐ 24 | 🐛 1 | 🌐 C# | 📅 2015-03-16 - Grand Theft Auto V resource viewer for RAGE engine RPF archives and models.
* [OpenMapTools](https://github.com/dexyfex/OpenMapTools) ⭐ 20 | 🐛 0 | 🌐 C# | 📅 2020-01-01 - OpenFormats map conversion toolkit by dexyfex (CodeWalker author): converts GTA San Andreas IPL and GTA IV IDE/OPL/ONV map files into GTA V's RAGE .ymap.xml/.ytyp.xml/.ynv formats for porting map mods, for use with CodeWalker's RPF import.
* [AngelStudiosBlenderAddon](https://github.com/Dummiesman/AngelStudiosBlenderAddon) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2025-12-10 - Blender add-on that handles several formats used in Angel Studios/Rockstar San Diego games from \~1999-2006. Supports Midnight Club 2, Midtown Madness 1, and other titles.
  * Formats: BMS, DLP, MOD/XMOD, BND, SKEL, GEO.
* [PKGImportExport](https://github.com/Dummiesman/PKGImportExport) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2023-07-31 - Blender addon for importing and exporting Angel Studios ModPackage (PKG) format files from Midnight Club and related titles.
* [RageAudioTool](https://github.com/CamxxCore/RageAudioTool) ⭐ 13 | 🐛 1 | 🌐 C# | 📅 2017-06-27 - Reverse engineering tool for the RAGE engine's audio metadata file formats, used in Rockstar games such as GTA and Red Dead Redemption.
* [tt-decomp (decomp)](https://github.com/OZORDI/tt-decomp) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2026-04-22 - AI-assisted matching decompilation of Rockstar Games Presents Table Tennis (Xbox 360, 2006), lifting PowerPC assembly into C++ toward a cross-platform SDL2/OpenGL port.
* [GTAVHandlingEditor](https://github.com/ikt32/GTAVHandlingEditor) ⭐ 9 | 🐛 1 | 🌐 C++ | 📅 2025-01-25 - Real-time handling editor for Grand Theft Auto V.
* [RAGE-Console-Texture-Editor](https://github.com/indirivacua/RAGE-Console-Texture-Editor) ⭐ 8 | 🐛 0 | 🌐 Pascal | 📅 2016-05-23 - Texture editor for console versions of Rockstar RAGE engine games.
  * Games: GTA IV, GTA V (PS3/Xbox 360), Red Dead Redemption, Midnight Club: Los Angeles, Max Payne 3.
* [MidtownExtractor](https://github.com/0x1F9F1/MidtownExtractor) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2018-07-01 - Midtown Madness 1/2 and Midnight Club 2 file extractor.
* [Coords2YMAP](https://github.com/indirivacua/Coords2YMAP) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2020-01-26 - Converts GTA San Andreas/Vice City .IDE/.OPL map coordinate files into GTA V's RAGE .YTYP/.YMAP formats, for porting classic-era map mods.
* [Noesis Plugins (Red Dead Redemption)](https://github.com/Gh0stBlade/NoesisPlugins) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2019-02-10 - Various Python scripts for Noesis to import and export textures and models from Rockstar games.
* [VichoModdingX](https://github.com/Hancapo/VichoModdingX) ⭐ 0 | 🐛 0 | 📅 2024-11-21 - GTA V modding guide covering RAGE engine format workflows (CodeWalker, Sollumz, YMAP, YTD tools).
* [TexFury.NET](https://github.com/Hancapo/TexFury.NET) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-07-21 - Fast image-to-DDS conversion and YTD texture dictionary toolkit for .NET, supporting RAGE engine formats used in Grand Theft Auto and Red Dead series.
* [MidnightClub2 (Noesis)](https://himeworks.com/noesis-plugins/) - Noesis plugin for Midnight Club 2 model formats.

### Ankama Games

#### Wakfu

* [vakfu](https://github.com/jac3km4/vakfu) ⭐ 33 | 🐛 1 | 🌐 Rust | 📅 2026-05-03 - Isometric map renderer for Wakfu, reading the game's original map data files directly (no bundled assets — requires the player's own game install).
* [wakfu-bdata-gen](https://github.com/jac3km4/wakfu-bdata-gen) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - Tool that extracts binary data struct layouts for Wakfu by analyzing the game's Java bytecode (JAR), generating the definitions consumed by wakfu-bdata.
* [wakfu-bdata](https://github.com/jac3km4/wakfu-bdata) ⭐ 2 | 🐛 1 | 🌐 Rust | 📅 2026-04-30 - Rust crate for decoding Wakfu's binary game-data files, using struct layouts recovered by wakfu-bdata-gen.

### Anthony Bongers

* [GhostsAndGraves (decomp)](https://github.com/AnthonyBongers/GhostsAndGraves) ⭐ 20 | 🐛 0 | 🌐 Assembly | 📅 2025-11-22 - Matching decompilation of Ghosts And Graves (NES, 100%).

### Ape, Inc

* [ebsrc](https://github.com/Herringway/ebsrc) ⭐ 178 | 🐛 9 | 🌐 Assembly | 📅 2024-07-22 - Source recreation of EarthBound (SNES), disassembled and reorganized into buildable C/asm source.
* [mother3 (decomp)](https://github.com/Kurausukun/mother3) ⭐ 79 | 🐛 8 | 🌐 Assembly | 📅 2026-08-17 - Decompilation of Mother 3 (GBA).
* [EBME](https://github.com/Supremekirb/EBME) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2026-05-19 - GUI editor for EarthBound's overworld areas.
* [ebbinex](https://github.com/Herringway/ebbinex) ⭐ 14 | 🐛 1 | 🌐 D | 📅 2023-06-05 - Simple utility for extracting data from Earthbound ROM files.
* [earthbound-script-dumper](https://github.com/CataLatas/earthbound-script-dumper) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2021-02-11 - EarthBound text script dumper.
* [nspcplay](https://github.com/Herringway/nspcplay) ⚠️ Archived - Player and parser for NSPC, the SNES music sequence format used by EarthBound and other SNES games.
* [ebtexted](https://github.com/PKHackers/ebtexted) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2017-07-30 - Tomato's EarthBound text editor.

### Arc System Works

#### Under Night In-Birth

* [UNIB.Data.Tool](https://github.com/Ekey/UNIB.Data.Tool) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2024-01-26 - Archive extractor for Under Night In-Birth II Sys:Celes game data files.

#### True Remembrance

* [AMLUnpacker\_TrueRemembrance](https://github.com/infval/AMLUnpacker_TrueRemembrance) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2020-05-31 - Unpacker for True Remembrance's (Nintendo 3DS) imageArcive.arc archive format, extracting images to PNG.

### Apogee Software

#### Crystal Caves

* [OpenCrystalCaves](https://github.com/OpenCrystalCaves/OpenCrystalCaves) ⭐ 89 | 🐛 2 | 🌐 C++ | 📅 2026-08-13 - Unofficial open-source engine reimplementation of the Crystal Caves trilogy (1991, Apogee Software), reading the original game's assets.

#### Duke Nukem II

* [Duke2Reconstructed (decomp)](https://github.com/lethal-guitar/Duke2Reconstructed) ⭐ 366 | 🐛 0 | 🌐 C | 📅 2025-04-13 - Reconstructed source code for Duke Nukem II (1993, Apogee Software), based on disassembly of the original executable and reading the game's original data files.

#### Blake Stone (Aliens of Gold, Planet Strike)

* [BStone](https://github.com/bibendovsky/bstone) ⭐ 364 | 🐛 56 | 🌐 C | 📅 2026-08-08 - Unofficial source port for Blake Stone series (Aliens of Gold and Planet Strike) with support for original game asset formats including external textures.

### Argonaut Games

* [PS1-BRender-Reverse](https://github.com/OverSurge/PS1-Argonaut-Reverse) ⭐ 88 | 🐛 1 | 🌐 Python | 📅 2024-02-24 - Reverse engineering tools for PlayStation 1 BRender engine games like Harry Potter and Croc 2.
* [croc (decomp)](https://github.com/xeeynamo/croc) ⭐ 35 | 🐛 0 | 🌐 C | 📅 2024-03-31 - Matching decompilation of Croc: Legend of the Gobbos.
* [CrocUtils](https://github.com/vs49688/CrocUtils) ⭐ 15 | 🐛 1 | 🌐 C++ | 📅 2025-10-10 - Collection of utilities for Croc: The Legend of Gobbos, complementing Argonaut's ASF/BRP audio/video codec formats with additional encoding/decoding tools. Not related to Rexhunter99/CrocUtils, which covers map loading/archive unpacking instead.
* [CrocExplorerWV](https://github.com/zeroKilo/CrocExplorerWV) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2019-08-08 - Croc Explorer by Warranty Voider, a tool to explore and extract the game content of Croc: The Legend of Gobbos (distinct from the same author's Croc2ExplorerWV for Croc 2).
* [Stratigise](https://github.com/Argonaut-PS1-Reverse/Stratigise) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-06-13 - WIP tool for disassembling and (re)assembling ASL binaries for Croc 1.
* [Croc2ExplorerWV](https://github.com/zeroKilo/Croc2ExplorerWV) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2019-08-17 - Tool to explore the game content of Croc 2.
* [CrocUtils](https://github.com/Rexhunter99/CrocUtils) ⭐ 4 | 🐛 0 | 📅 2018-02-16 - Utilities for Croc game file formats.

### Arkane Studios

* [ArxLibertatis](https://github.com/arx/ArxLibertatis) ⭐ 1,076 | 🐛 70 | 🌐 C++ | 📅 2024-08-22 - Cross-platform engine port of Arx Fatalis that reads the original game's PAK data files, with extensive bug fixes and modernization over the 2002 engine.
* [disrev](https://github.com/chipolux/disrev) ⭐ 17 | 🐛 1 | 🌐 C++ | 📅 2023-11-19 - Python tools for extracting and modifying Dishonored 2 assets.
* [Obscura](https://github.com/Mikompilation/Obscura) ⭐ 11 | 🐛 2 | 🌐 C++ | 📅 2026-07-15 - Modding toolkit for Dishonored games.
* [ArxFatalisManifests](https://github.com/arx/ArxFatalisManifests) ⭐ 1 | 🐛 0 | 📅 2020-06-30 - Manifests describing the file layouts of different Arx Fatalis data file variants/releases, used by the ArxLibertatis engine reimplementation.
* [dishonored2\_scripts](https://github.com/usernametoolo/dishonored2_scripts/blob/master/tools/scripts/unpack_resources.py) ⭐ 0 | 🐛 0 | 📅 2016-12-12 - Resource extraction script for unpacking .pak archives.
* [Arx Fatalis .PAK unpacker](https://www.moddb.com/games/arx-fatalis/downloads/arx-fatalis-pak-unpacker-v13) - Tool for unpacking PAK files from Arx Fatalis. Includes source code. Created by CTPAX-X Team (v1.3).
* [Field Editor 0.5.1 Tautologist tool (Dishonored)](https://www.moddb.com/games/dishonored/downloads/field-editor-051-tautologist-tool) - Field editor for Dishonored with improved menu system, keyboard shortcuts, auto-completing text boxes, additional grouping and fields, live filtering/searching, settings persistence, and XML file browsing (v0.5.1).

### Armature Studio (Batman: Arkham Origins Blackgate)

* [BAOB.ARA.Tool](https://github.com/Ekey/BAOB.ARA.Tool) ⚠️ Archived - Tool for extracting ARA archives from Batman: Arkham Origins Blackgate.

### Arrowhead Game Studios (Helldivers 2)

* [filediver](https://github.com/xypwn/filediver) ⭐ 117 | 🐛 11 | 🌐 Go | 📅 2026-08-18 - Extractor for Helldivers 2. Supports extracting models, audio, video, and textures.
* [Hellextractor](https://github.com/Xaymar/Hellextractor) ⚠️ Archived - Another Helldivers 2 extractor (archived, recommended to use [filediver](https://github.com/xypwn/filediver) ⭐ 117 | 🐛 11 | 🌐 Go | 📅 2026-08-18 instead).
* [helldivers2-rs](https://github.com/nblockbuster/helldivers2-rs) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2024-04-03 - Work-in-progress tool to extract files from Helldivers 2.
* [hd2-name-db](https://github.com/dtzxporter/hd2-name-db) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-09-04 - Community database documenting extracted game assets from Helldivers 2, helping identify and organize game content.

### Assembly Line (Supaplex)

* [superplexed](https://github.com/kaimitai/superplexed) ⭐ 21 | 🐛 0 | 🌐 C++ | 📅 2022-12-14 - Supaplex level and graphics editing suite.

### Asmik Ace Entertainment (LSD: Dream Emulator)

* [lsddecomp (decomp)](https://github.com/FirecatFG/lsddecomp) ⭐ 10 | 🐛 1 | 🌐 C | 📅 2024-09-13 - Matching decompilation of LSD: Dream Emulator (PS1).

### Asobo Studio

* [RatDecomp](https://github.com/ZounaModding/RatDecomp) ⭐ 31 | 🐛 0 | 🌐 C++ | 📅 2026-08-14 - Decompilation project for Ratatouille (GameCube) with original game data parsing and reconstruction.
* [fmtk](https://github.com/widberg/fmtk) ⭐ 27 | 🐛 0 | 🌐 C++ | 📅 2026-04-19 - FUEL Modding Toolkit.
* [FUELDecompilation](https://github.com/widberg/FUELDecompilation) ⭐ 27 | 🐛 1 | 🌐 C++ | 📅 2026-03-14 - FUEL decompilation project.
* [bff](https://github.com/widberg/bff) ⭐ 14 | 🐛 2 | 🌐 Rust | 📅 2026-08-08 - BigFile Friend. Successor to `dpc`, supports Zouna file formats.
* [atk](https://github.com/widberg/atk) ⭐ 9 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-06 - Asobo Toolkit. Supporting Asobo and Black Sheep Studio games.
  * Games: FUEL, Ratatouille, Toy Story 3, WALL-E, and more.
  * Features: BigFile extraction, Zouna structure parsing.
* [ZounaBinaryTemplates](https://github.com/ZounaModding/ZounaBinaryTemplates) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2026-06-13 - 010 Editor binary templates and Noesis scripts for Zouna engine file formats, with documentation on engine internals (Seads spatial partitioning system).
  * Games: Ratatouille (PC, PS2, GC, Xbox), WALL-E (PC), Toy Story 3 (PS2), SpongeBob SquarePants: Revenge of the Flying Dutchman (PS2, GC), A Plague Tale (PC), Microsoft Flight Simulator 2024 (PC), Shaun White 2 (PC), Castleween (PS2), Garfield, Noddy.
  * Formats: Bitmap\_Z, Mesh\_Z, Material\_Z, World\_Z, Node\_Z, Skel\_Z, Skin\_Z, Animation\_Z, Lod\_Z, and more Zouna \_Z resource types.
* [ImZouna](https://github.com/widberg/ImZouna) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-05 - ImHex patterns for Zouna data structures used in Asobo Studio games (FUEL, WALL-E, Ratatouille, Toy Story 3, A Plague Tale series, Microsoft Flight Simulator, and more).
* [Asobo-ArithmeticCoderC](https://github.com/widberg/Asobo-ArithmeticCoderC) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2022-07-17 - Reference implementation of Asobo's arithmetic coder.
* [fror-research](https://github.com/widberg/fror-research) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-02-19 - Ford Racing Off Road research.
* [fuel-map](https://github.com/widberg/fuel-map) ⭐ 1 | 🐛 3 | 🌐 Python | 📅 2026-07-02 - FUEL map notes and assets.
* [blender\_fuel](https://github.com/widberg/blender_fuel) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-04-21 - Blender scripts for FUEL.
* [fmt\_fuel](https://github.com/widberg/fmt_fuel) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2021-06-28 - Noesis scripts for FUEL.
* [fuel-save-editor](https://github.com/widberg/fuel-save-editor) ⭐ 0 | 🐛 0 | 🌐 Nim | 📅 2026-06-28 - FUEL save editor.

### Atlus

* [noclip.website (Tokyo Mirage Sessions ♯FE)](https://github.com/magcius/noclip.website/tree/main/src/TokyoMirageSessionsSharpFE) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Tokyo Mirage Sessions ♯FE (Wii U) map viewer. Parses APAK archives plus BFRES models and BNTX textures, with lightmap, gimmick, and map-layout support.
* [AemulusModManager](https://github.com/TekkaGB/AemulusModManager) ⭐ 106 | 🐛 40 | 🌐 C# | 📅 2024-09-18 - Mod package manager for Persona 4 Golden (PC), Persona 3 FES, Persona 5, and Persona 5 Strikers. Automatically merges conflicting bin, bmd, pm1, bf, and tbl files from different mods.
* [Atlus-Script-Tools](https://github.com/tge-was-taken/Atlus-Script-Tools) ⭐ 104 | 🐛 14 | 🌐 C# | 📅 2026-05-17 - Set of tools for working with Atlus script formats including flow script files (.bf) and message script files (.bmd, .bm2). Supports Persona series, SMT series, Catherine, Trauma Center, and more.
* [GFD-Studio](https://github.com/tge-was-taken/GFD-Studio) ⭐ 95 | 🐛 19 | 🌐 C# | 📅 2025-09-10 - Model editor for viewing, editing and converting models in GMD/GFS format used in P3D, P4D, P5D, and Persona 5.
* [Amicitia](https://github.com/tge-was-taken/Amicitia) ⭐ 92 | 🐛 22 | 🌐 C# | 📅 2024-03-11 - Tool for working with Persona 3/4/5 file formats.
* [PersonaEditor](https://github.com/Meloman19/PersonaEditor) ⭐ 73 | 🐛 18 | 🌐 C# | 📅 2024-12-27 - File editor for Persona series (3, 4, 5) supporting multiple container formats (BIN, PAK, PAC, CPK, P00, ARC, PM1, BF, BVP, TBL, FTD) with asset extraction and modification.
* [p4g-saveconv](https://github.com/zarroboogs/p4g-saveconv) ⭐ 59 | 🐛 8 | 🌐 Python | 📅 2020-07-31 - Persona 4 Golden save converter. Converts PS Vita saves to PC format and vice versa, including data00XX.bin, system.bin, and sdslot.dat files.
* [smt1dasm](https://github.com/spannerisms/smt1dasm) ⭐ 25 | 🐛 0 | 🌐 Assembly | 📅 2022-11-17 - Disassembly of Shin Megami Tensei J1.0 for the SNES.
* [AtlusFileSystemLibrary](https://github.com/tge-was-taken/AtlusFileSystemLibrary) ⭐ 17 | 🐛 4 | 🌐 C# | 📅 2020-07-09 - Library containing utilities for working with file systems used in Atlus games.
* [P5X\_vFileContentExtract](https://github.com/DeathChaos25/P5X_vFileContentExtract) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2025-09-07 - Content extractor for Persona 5 X vFile archives.
* [GMDTool](https://github.com/lemoncove/GMDTool) ⭐ 10 | 🐛 3 | 🌐 C# | 📅 2020-09-04 - Command-line utility to convert Persona .GMD model files to Collada .DAE format. Uses GFDLibrary for GMD loading.
* [DDS3-Model-Studio](https://github.com/tge-was-taken/DDS3-Model-Studio) ⭐ 9 | 🐛 4 | 🌐 C# | 📅 2024-07-21 - WIP Model editing tools for DDS3 engine based SMT games (SMT: Nocturne, DDS 1 & 2, Raidou 1 & 2).
* [p4u2modtools](https://github.com/zarroboogs/p4u2modtools) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2018-08-08 - Modding tools for Persona 4 Arena Ultimax, Persona 4 Arena, etc. Includes bddata.bin extraction tools and custom game update creation.
* [p5-rte](https://github.com/TheHiddenHour/p5-rte) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2020-01-26 - Real-time editing tool for Persona 5 on jailbroken PS3. Allows editing of persona slots, stats, and skills using PS3Lib.
* [PersonaRandomizer](https://github.com/ShrineFox/PersonaRandomizer) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-07-03 - Program for quickly randomizing files in Persona 3 FES, Persona 4, and Persona 5. Supports randomizing various TBL files including PERSONA, UNIT, SKILL, ITEM, NAME, and ENCOUNT tables.
* [yafe](https://github.com/tge-was-taken/yafe) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2021-09-06 - Field editor for Persona 5 allowing import of FBN and HBN files into 3ds Max for visual editing.
* [AtlusPM1MessageScriptEditor](https://github.com/tge-was-taken/AtlusPM1MessageScriptEditor) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2024-04-07 - Message script editor for Persona 1.
* [EvtTool](https://github.com/tge-was-taken/EvtTool) ⭐ 3 | 🐛 1 | 🌐 C# | 📅 2024-04-13 - Persona 5 (Royal) EVT file editor. Converts EVT/ECS/LSD files to JSON and vice versa.
* [SMT1L1ON](https://github.com/tge-was-taken/SMT1L1ON) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2018-02-24 - Translation tools for Shin Megami Tensei 1.
* [p5s-txteditor](https://github.com/samudebug/p5s-txteditor) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2021-03-27 - Text editor for editing text files found in Persona 5 Strikers.
* [P5RFieldTexUtility](https://github.com/ShrineFox/P5RFieldTexUtility) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-06-26 - Utility for quickly extracting field textures and duplicating edits in Persona 5 Royal. Supports batch extraction and repacking of .BIN files with DDS texture support.
* [EPLGen](https://github.com/ShrineFox/EPLGen) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-03-29 - GUI for quickly generating EPL leafs featuring animated sprites for Persona 5 Royal. Supports particle effect creation with DDS textures and GMD file integration.
* [P5CharacterSwapper](https://github.com/ShrineFox/P5CharacterSwapper) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2020-12-20 - Batch-replaces P5 character models/animations by ID. Can retarget models and animations if specified.
* [P4U2TrialEditor](https://github.com/kiwi515/P4U2TrialEditor) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2022-07-22 - Trial/Lesson editor for Persona 4 Arena Ultimax (2.0 and later), complementing p4u2modtools.

### Attack on Titan

* [AoTBinTool](https://github.com/Kaplas80/AoTBinTool) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2021-03-28 - Packer/unpacker for Attack on Titan BIN archive files.

### Aurogon (Gujian)

* [GuJian3Manager](https://github.com/Kaplas80/GuJian3Manager) ⭐ 33 | 🐛 4 | 🌐 C# | 📅 2024-09-03 - Extracts, repacks, and decrypts Gujian 3 (古剑奇谭三) data files (Oodle-compressed, XXTEA-encrypted .xxx files).

### Avalanche Studios (Generation Zero)

* [Gibbed.JustCause4](https://github.com/gibbed/Gibbed.JustCause4) ⭐ 26 | 🐛 0 | 🌐 C# | 📅 2019-01-02 - File unpacking and asset extraction tool for Just Cause 4.
* [JC.ARC.Tool](https://github.com/Ekey/JC.ARC.Tool) ⚠️ Archived - Tool for extracting ARC archives from the Just Cause series.
* [ApexPredator](https://github.com/REDxEYE/ApexPredator) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2026-06-22 - Tool/library for reading Apex Engine assets. Currently supports Generation Zero. Written in C++.
* [AE.ARC.Tool](https://github.com/Ekey/AE.ARC.Tool) ⚠️ Archived - Tool for extracting ARC archives from games built on Avalanche Studios' Apex Engine.

### Bandai Namco

* [noclip.website (Klonoa)](https://github.com/magcius/noclip.website/tree/main/src/rres) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Klonoa viewer.
* [noclip.website (Katamari Damacy)](https://github.com/magcius/noclip.website/tree/main/src/KatamariDamacy) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Katamari Damacy viewer.
* [kl2\_lv\_decomp (decomp)](https://github.com/entriphy/kl2_lv_decomp) ⭐ 40 | 🐛 0 | 🌐 C | 📅 2025-03-07 - Matching decompilation of Klonoa 2: Lunatea's Veil (PS2).
* [MBTL.BIN.Tool](https://github.com/Ekey/MBTL.BIN.Tool) ⭐ 37 | 🐛 1 | 🌐 C# | 📅 2024-05-11 - Tool for extracting BIN archives from MELTY BLOOD: TYPE LUMINA.
* [RRUnpacker](https://github.com/Nenkai/RRUnpacker) ⭐ 18 | 🐛 5 | 🌐 C# | 📅 2026-07-02 - Unpacker for Ridge Racer PSP/6/7/PS Vita and Go Vacation .DAT files. Supports extraction of all files including custom compressed ones.
* [Dragon-Ball-Legends (decomp)](https://github.com/GodkuHacking/Dragon-Ball-Legends) ⭐ 14 | 🐛 0 | 🌐 Smali | 📅 2024-05-09 - Matching decompilation of Dragon Ball Legends (Android APK).
* [SoulCalibur2-game-unpacker](https://github.com/PS2Homebrew-arcade/SoulCalibur2-game-unpacker) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2025-10-02 - Unpacker for Soul Calibur 2 game files.
* [BinarySerializer.Klonoa](https://github.com/BinarySerializer/BinarySerializer.Klonoa) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2024-07-13 - Serializer for Klonoa games.
* [ggst\_collision\_editor\_rs](https://github.com/WistfulHopes/ggst_collision_editor_rs) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2022-05-02 - Collision editor for Guilty Gear Strive.
* [ARC](https://github.com/Bigchillghost/ARC) ⭐ 3 | 🐛 0 | 📅 2024-05-12 - Animation Recipe Cracker for Bandai Namco games.
* [BBFSUnpacker](https://github.com/Nenkai/BBFSUnpacker) ⭐ 3 | 🐛 1 | 🌐 C# | 📅 2025-02-13 - Extraction tool for Ridge Racer Drifttopia files.
* [TalesOfFantasy (Noesis)](https://himeworks.com/noesis-plugins/) - Noesis plugins for Tales series.

#### THE iDOLM\@STER Cinderella Girls Starlight Stage

* [DereTore](https://github.com/OpenCGSS/DereTore) ⭐ 201 | 🐛 12 | 🌐 C# | 📅 2022-06-27 - Music and beatmap authoring toolkit for THE iDOLM\@STER Cinderella Girls Starlight Stage.
* [libcgss](https://github.com/hozuki/libcgss) ⭐ 103 | 🐛 3 | 🌐 C++ | 📅 2020-06-10 - Helper library for THE iDOLM\@STER Cinderella Girls Starlight Stage (CGSS/DereSute), supporting HCA audio decoding and ACB archive exploring; also applies to THE iDOLM\@STER Million Live! Theater Days (MLTD).
* [Million-Live-Quintet-Player](https://github.com/KinoMyu/Million-Live-Quintet-Player) ⭐ 61 | 🐛 2 | 🌐 C++ | 📅 2021-07-02 - Unit simulator for MLTD, decoding the game's original .hca audio files.
* [MilliSim](https://github.com/hozuki/MilliSim) ⭐ 34 | 🐛 9 | 🌐 C# | 📅 2018-10-24 - Extensible simulator for THE iDOLM\@STER Million Live! Theater Days (MLTD), reading the game's original beatmap data.
* [StarlightDirector](https://github.com/hozuki/StarlightDirector) ⭐ 20 | 🐛 2 | 🌐 C# | 📅 2018-10-31 - Beatmap editor for THE iDOLM\@STER Cinderella Girls Starlight Stage.

#### Dragon Ball

* [DragonBallLegends](https://github.com/GodkuHacking/DragonBallLegends) ⭐ 16 | 🐛 3 | 🌐 Python | 📅 2024-03-19 - Complete decompile dump of Dragon Ball Legends mobile game; includes asset extraction and Python mods.
* [DBFModToolCollection](https://github.com/Tiniifan/DBFModToolCollection) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-05-25 - Collection of tools to simplify modding on Dragon Ball Fusion. Includes utilities for working with game files and archives.
* [binunpack](https://github.com/shibbo/binunpack) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2016-12-26 - Program for unpacking the BIN archives in DragonBall: Revenge of King Piccolo, written in Python 3.
* [Pokemon-Tekken-Ripping-Tool](https://github.com/hadashisora/Pokemon-Tekken-Ripping-Tool) ⭐ 0 | 🐛 1 | 🌐 MAXScript | 📅 2018-01-04 - Tool for unpacking archives and extracting assets from Pokemon Tekken / Pokken Tournament.

#### Tales Of

* [XV2-Tools](https://github.com/LazyBone152/XV2-Tools) ⭐ 51 | 🐛 40 | 🌐 C# | 📅 2026-07-31 - Set of tools for modifying Dragon Ball Xenoverse 2 files.
* [TalesOfTools](https://github.com/DaZombieKiller/TalesOfTools) ⭐ 20 | 🐛 3 | 🌐 C# | 📅 2026-03-22 - Tools for Tales Of series (Xillia, Xillia 2, Zestiria, Berseria, Graces f Remastered); archive unpacking/repacking and ImHex patterns for format analysis.
* [gracesf\_model\_tool](https://github.com/eArmada8/gracesf_model_tool) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-12-17 - Tool to extract mesh/model data from Tales of Graces f (PS3); converts to .glb/.fmt formats.

### Battlestate Games (Escape from Tarkov)

* [TarkinItemExporter](https://github.com/bmpq/TarkinItemExporter) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2026-04-09 - Escape from Tarkov item data exporter.

### BeamNG GmbH (BeamNG.drive)

* [Blender-JBeam-Editor](https://github.com/BeamNG/Blender-JBeam-Editor) ⭐ 90 | 🐛 10 | 🌐 Python | 📅 2024-08-09 - Official Blender plugin to import, modify, and export BeamNG.drive's JBeam vehicle-part format using Blender's modelling tools.
* [vscode-jbeam-editor](https://github.com/BeamNG/vscode-jbeam-editor) ⭐ 44 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-09 - VS Code extension: lightweight visualizer/editor for BeamNG.drive's JBeam physics-definition files.

### Bethesda

*The Elder Scrolls, Fallout series, and Starfield.*

* [OpenMW](https://github.com/OpenMW/openmw) ⭐ 6,517 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 - Open-source unofficial engine reimplementation of Morrowind that reads and parses the original game's ESM/ESP plugin files and BSA archives to run without Bethesda's original engine.
* [noclip.website (Morrowind)](https://github.com/magcius/noclip.website/tree/main/src/Morrowind) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Morrowind viewer.
* [daggerfall-unity](https://github.com/Interkarma/daggerfall-unity) ⭐ 3,468 | 🐛 76 | 🌐 C# | 📅 2026-06-30 - Open-source recreation of The Elder Scrolls II: Daggerfall in the Unity engine, reverse-engineering and loading the original Daggerfall (DOS) game data and formats.
* [OpenTESArena](https://github.com/afritz1/OpenTESArena) ⭐ 1,399 | 🐛 20 | 🌐 C++ | 📅 2026-08-13 - Open-source reimplementation of The Elder Scrolls: Arena's engine that reads the original game's data files (CFA, IMG, SET, and other Arena-specific formats).
* [NifTools Blender Addon](https://github.com/niftools/blender_niftools_addon) ⭐ 435 | 🐛 111 | 🌐 Python | 📅 2024-06-16 - Blender add-on to enable import and export of NetImmerse file formats including .nif, .kf, and .egm used in Elder Scrolls and Fallout games.
* [BodySlide and Outfit Studio](https://github.com/ousnius/BodySlide-and-Outfit-Studio) ⭐ 359 | 🐛 12 | 🌐 C++ | 📅 2026-08-17 - Tool to convert, create, and customize outfits and bodies for Bethesda games.
* [Synthesis](https://github.com/Mutagen-Modding/Synthesis) ⭐ 345 | 🐛 189 | 🌐 C# | 📅 2026-08-12 - Framework and GUI to empower people to create mods via code instead of by hand, mainly used to create patches.
* [PyNifly](https://github.com/BadDogSkyrim/PyNifly) ⭐ 301 | 🐛 117 | 🌐 Python | 📅 2026-08-16 - Export/import tools between Blender and the NIF format, using Bodyslide/Outfit Studio's Nifly layer. Supports Skyrim LE, Skyrim SE, Fallout 4, Fallout New Vegas, Fallout 76, and Fallout 3.
* [Champollion](https://github.com/Orvid/Champollion) ⭐ 145 | 🐛 13 | 🌐 C++ | 📅 2023-10-17 - PEX to Papyrus decompiler for Skyrim, Fallout 4, Fallout 76, and Starfield. Decompiles binary .pex scripts to human-readable .psc format.
* [SkyrimSETest](https://github.com/Nukem9/skyrimse-test) ⭐ 134 | 🐛 8 | 🌐 C++ | 📅 2023-11-24 - Reverse-engineering collection for Skyrim Special Edition with analysis of game formats and resources.
* [BSA Browser](https://github.com/AlexxEG/BSA_Browser) ⭐ 129 | 🐛 3 | 🌐 C# | 📅 2026-04-18 - Bethesda Archive browser and extractor for BSA and BA2 archives.
* [Spriggit](https://github.com/Mutagen-Modding/Spriggit) ⭐ 127 | 🐛 44 | 🌐 C# | 📅 2026-07-10 - Tool to facilitate converting Bethesda plugin files to a text based format that can be stored in Git.
* [nifly](https://github.com/ousnius/nifly) ⭐ 78 | 🐛 0 | 🌐 C++ | 📅 2026-07-29 - C++ library for reading and writing NIF (NetImmerse/Gamebryo/Creation Engine) files used in Bethesda games. Clean-room design with full read/write support.
* [SugarBombEngine](https://github.com/the-big-mt/SugarBombEngine) ⭐ 73 | 🐛 0 | 🌐 C++ | 📅 2023-11-21 - Open-source reimplementation of Bethesda's Gamebryo-derived engine branch (id Tech 4/OpenMW-based) targeting Fallout 3 and Fallout: New Vegas; loads the original game data rather than bundling any.
* [ck-cmd](https://github.com/aerisarn/ck-cmd) ⭐ 71 | 🐛 36 | 🌐 C++ | 📅 2025-01-27 - Command-line helper for executing some Creation Kit/Engine commands.
* [nifxml](https://github.com/niftools/nifxml) ⭐ 47 | 🐛 36 | 🌐 Python | 📅 2024-09-15 - Repository for the nif.xml file, which contains the NIF file format description for NetImmerse/Gamebryo NIF model format used in Elder Scrolls and Fallout games.
* [Material-Editor](https://github.com/ousnius/Material-Editor) ⭐ 38 | 🐛 1 | 🌐 C# | 📅 2026-05-25 - Small UI application to edit BGSM/BGEM material files used in Bethesda games.
* [UProjOblivionRemastered](https://github.com/nathtest/UProjOblivionRemastered) ⭐ 18 | 🐛 3 | 🌐 C++ | 📅 2025-05-08 - Similar UE 5.3.2 SDK project for Oblivion Remastered built from a UE4SS dump; used alongside FModel-extracted assets for Blueprint modding.
* [Altar](https://github.com/Kein/Altar) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2026-01-07 - Unreal Engine 5.3 SDK project for Oblivion Remastered, generated from a UE4SS class dump, letting modders write native C++/Blueprint code against the game's classes.
* [Gibbed.Fallout4](https://github.com/gibbed/Gibbed.Fallout4) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2017-07-19 - Tools for Fallout 4 file formats.
* [daggerfallconnect](https://github.com/Interkarma/daggerfallconnect) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2015-03-14 - Foundational C# library for reading The Elder Scrolls II: Daggerfall's proprietary archive/asset formats, archived from Google Code; historical basis for the Daggerfall modding/tooling ecosystem underlying daggerfall-unity.
* [recreation](https://github.com/Force67/recreation) ⭐ 7 | 🐛 1 | 🌐 C++ | 📅 2026-08-16 - Modern ECS-driven game engine that loads Bethesda game content (Skyrim SE, Fallout 4, Fallout 76). Parses ESM/ESL, BSA/BA2, and NIF formats, converting to engine-native formats at load time.
* [DDS Texture Scanner](https://github.com/niston/TextureScan) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2023-06-03 - Application scanning for DDS textures with abnormal dimensions.
* [HBT2Skyrim](https://github.com/aerisarn/HBT2Skyrim) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2017-07-24 - Converts Havok animation format (HBT 6.6) to Skyrim-compatible format using hkxcmd and AssetCC2.
* [SSE-Fallout-4-Sound-Music-Converter](https://github.com/Backporter/SSE-Fallout-4-Sound-Music-Converter) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2021-09-23 - Audio converter for Fallout 4 and Skyrim; converts .xwm and .wav files to PS4 format.
* [CBash](https://github.com/aerisarn/CBash) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2022-11-13 - Library for reading and writing plugin files (.esm, .esp) for The Elder Scrolls IV/V and Fallout: New Vegas.
* [SSE-Fallout-4-Voice-Dialog-Converter](https://github.com/Backporter/SSE-Fallout-4-Voice-Dialog-Converter) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2021-09-23 - Voice dialog converter for Fallout 4 and Skyrim; converts .fuz files to PS4 format.
* [max\_nif\_plugin](https://github.com/aerisarn/max_nif_plugin) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2015-08-02 - Plugin for 3ds Max to work with NIF format used in The Elder Scrolls games.
* [BAE](https://www.nexusmods.com/starfield/mods/165) - Bethesda Archive Extractor application for BSA/BA2 archives.
* [xEdit](https://tes5edit.github.io) - Advanced graphical module editor and conflict detector for Bethesda games.
* [F2 TOOLS PAK BY LEONARDO (Fallout 2)](https://www.moddb.com/games/fallout-2/downloads/f2-tools-pak-by-leonardo) - Toolset for creating Fallout 2 mods. For more information, see Readme.txt in the archive. Archive contains: BIS mapper, Dims mapper, SFall script editor, Notepad++, Frame animator.
* [Fallout2 FRM converter v 2.0](https://www.moddb.com/games/fallout-2/downloads/fallout2-frm-converter-v-20) - Convert Fallout's FRM image files to the BMP, JPG, PNG, TGA, TIF, PBM, PGM and PPM files formats, and then convert BMP, TIF and PNG files back into FRM's! Use your own art in Fallout....
* [Wrye Bash](https://wrye-bash.github.io) - Swiss army knife for modding Bethesda games with features including mod installation, conflict manager, load order manager and automatic merging.
* [hkxc](https://www.nexusmods.com/skyrimspecialedition/mods/126214) - CLI tool to convert between x86/x64 HKX and XML animation files.
* [HKX Conversion Tool](https://www.nexusmods.com/skyrimspecialedition/mods/128839) - hkxc Windows GUI for converting between HKX and XML animations files.
* [hkxPoser](https://www.nexusmods.com/skyrimspecialedition/mods/11783) - .hkx animation file editor.
* [DDS Texture Converter](https://www.nexusmods.com/skyrimspecialedition/mods/111378) - Application for bulk conversion and resizing of DDS textures.
* [Daggerfall utilities](https://www.moddb.com/games/daggerfall/downloads/daggerfall-utilities) - Archive of tools for the DOS version of Daggerfall, including quest editing tools and character modification tools.
* [ES Plugin Cracker 0.001b (Elder Scrolls IV: Oblivion)](https://www.moddb.com/games/oblivion/downloads/es-plugin-cracker-0-001b) - Rudimentary Win32 application for loading plugins authored with a higher Construction Set version (v0.001b).
* [Cathedral Assets Optimizer](https://www.nexusmods.com/skyrimspecialedition/mods/23316) - Tool to automatically optimize BSAs, meshes, textures and animations for Bethesda games.

### BioWare

#### Mass Effect

* [Gibbed.MassEffectAndromeda](https://github.com/gibbed/Gibbed.MassEffectAndromeda) ⭐ 65 | 🐛 19 | 🌐 C# | 📅 2022-06-22 - Tools for Mass Effect: Andromeda file formats.
* [Gibbed.MassEffect2](https://github.com/gibbed/Gibbed.MassEffect2) ⭐ 29 | 🐛 1 | 🌐 C# | 📅 2021-11-02 - Tools for Mass Effect 2 file formats.

#### Dragon Age: Origins

* [NorthernLights](https://github.com/lachjames/NorthernLights) ⭐ 30 | 🐛 2 | 🌐 C# | 📅 2022-02-16 - Open-source reimplementation of the Aurora/Odyssey engine, targeting the two Knights of the Old Republic games. Includes the KotOR Level Editor (KLE).

* [Gibbed.DragonAge.SaveGenerator](https://github.com/gibbed/Gibbed.DragonAge.SaveGenerator) ⭐ 17 | 🐛 1 | 🌐 C# | 📅 2017-07-22 - Save game generator tool for Dragon Age.

* [StarForge](https://github.com/Astral-C/StarForge) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2025-10-06 - Tool for Star Wars: Knights of the Old Republic file formats.

* [Dragon Age Origins 3dsmax Import Export script](https://www.moddb.com/games/dragon-age-origins/downloads/dragon-age-origins-3dsmax-import-export-script) - Dragon Age Origins 3dsmax import export script. Version 5.38. Reportedly works best with 3dsmax 2013

* [Kotor Tool 1](https://www.moddb.com/games/star-wars-knights-of-the-old-republic/downloads/kotor-tool-1) - Tool for extracting files, changing game rules, and customizing levels in Knights of the Old Republic.

### Bitmap Brothers

#### The Chaos Engine

* [ChaosEngine](https://github.com/GitExl/ChaosEngine) ⭐ 3 | 🐛 0 | 🌐 D | 📅 2017-07-29 - Reimplementation of the Chaos Engine (CD32) engine that reads original CD32 game data files to run the game on modern systems.

#### Speedball 2

* [speedball2-re-amiga](https://github.com/simon-frankau/speedball2-re-amiga) ⭐ 17 | 🐛 0 | 🌐 Assembly | 📅 2023-05-05 - Reverse engineering of Speedball 2 for the Commodore Amiga, following up on the same author's [Mega Drive/Genesis reversing](https://github.com/simon-frankau/speedball2-re) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2022-12-05.

### Black Element Software (Alpha Prime)

* [Alpha Prime RES Unpacker](https://www.moddb.com/mods/alpha-prime-dominus-prime/downloads/alpha-prime-res-unpacker-modding-tool) - Modding Tool for opening the .RES files for the "data00.res" and "data01.res" in Alpha Prime.

### Blizzard Entertainment

* [StormLib](https://github.com/ladislav-zezula/StormLib) ⭐ 648 | 🐛 3 | 🌐 C | 📅 2026-08-18 - Official library for reading and writing MPQ (MoPaQ) archives, the format used by Warcraft III, StarCraft, Diablo, and World of Warcraft (pre-Cataclysm).
* [CascLib](https://github.com/ladislav-zezula/CascLib) ⭐ 486 | 🐛 0 | 🌐 C++ | 📅 2026-07-21 - Open-source library for reading CASC (Content Addressable Storage Container) storages used in Blizzard games since 2014.
* [MPQExtractor](https://github.com/Kanma/MPQExtractor) ⭐ 163 | 🐛 1 | 🌐 C++ | 📅 2026-08-18 - Command-line tool to extract files from Blizzard MPQ (MoPaQ) archives.
* [CASCExtractor](https://github.com/Kanma/CASCExtractor) ⭐ 37 | 🐛 5 | 🌐 C++ | 📅 2016-08-16 - Command-line tool to extract files from Blizzard CASC storages.

#### World of Warcraft

* [noclip.website (World of Warcraft - Vanilla, The Burning Crusade, Wrath of the Lich King)](https://github.com/magcius/noclip.website/tree/main/src/WorldOfWarcraft) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser World of Warcraft (Vanilla) viewer.
* [WoWee](https://github.com/Kelsidavis/WoWee) ⭐ 650 | 🐛 2 | 🌐 C++ | 📅 2026-08-19 - Native C++ World of Warcraft client reimplementation with a custom Vulkan renderer, parsing original WMO/M2 model and terrain data.
  * Supports: Vanilla 1.12, The Burning Crusade 2.4.3, and Wrath of the Lich King 3.3.5a client data and network protocols.
* [OWLib](https://github.com/overtools/OWLib) ⭐ 585 | 🐛 4 | 🌐 C# | 📅 2026-07-19 - DataTool program that lets you extract models, maps, and files from Overwatch.
* [wow.export](https://github.com/Kruithne/wow.export) ⭐ 522 | 🐛 73 | 🌐 JavaScript | 📅 2026-06-22 - Export toolkit for World of Warcraft models and textures.
* [WoWDBDefs](https://github.com/wowdev/WoWDBDefs) ⭐ 319 | 🐛 8 | 🌐 C# | 📅 2026-08-18 - Client database definitions for World of Warcraft (DBD files for extracting game data).
* [wow-listfile](https://github.com/wowdev/wow-listfile) ⭐ 203 | 🐛 0 | 🌐 C# | 📅 2026-08-18 - Community-maintained listfile of known file paths inside World of Warcraft's CASC storage, used by CascLib/wow\.export and similar tools to resolve file IDs to names.
* [WebWowViewerCpp](https://github.com/Deamon87/WebWowViewerCpp) ⭐ 72 | 🐛 2 | 🌐 C++ | 📅 2025-05-07 - C++/WebAssembly in-browser viewer for World of Warcraft maps and models, reading original ADT/WMO/M2 client data.
* [Neo](https://github.com/WowDevTools/Neo) ⭐ 65 | 🐛 4 | 🌐 C# | 📅 2018-01-20 - Map editor for World of Warcraft (Wrath of the Lich King and Warlords of Draenor), reading and writing the client's original terrain/ADT map data.
* [DBCD](https://github.com/wowdev/DBCD) ⭐ 53 | 🐛 0 | 🌐 C# | 📅 2026-08-15 - C# library for reading DBC/DB2 client database files from World of Warcraft.
* [WoWExportTools](https://github.com/Marlamin/WoWExportTools) ⚠️ Archived - Export World of Warcraft assets to portable formats.
* [TACTSharp](https://github.com/wowdev/TACTSharp) ⭐ 9 | 🐛 1 | 🌐 C# | 📅 2026-08-15 - C# library for loading World of Warcraft's CASC storage via memory-mapped file access, for faster load times and lower memory use than other CASC libraries.
* [3DS/Obj MDX Converter](https://www.moddb.com/games/warcraft-iii/downloads/3ds-obj-mdx-converter)

#### StarCraft (original) & Brood War

* [ChkForge](https://github.com/heinermann/ChkForge) ⭐ 14 | 🐛 38 | 🌐 C++ | 📅 2024-05-30 - StarCraft (Brood War) map editor built with Qt, using ChkDraft's MappingCoreLib for CHK/map management, StormLib/CascLib for MPQ/CASC archive access, and OpenBW for terrain rendering and simulation.
* [llvm-bw](https://github.com/heinermann/llvm-bw) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2020-02-04 - Compiles LLVM IR into StarCraft: Brood War map trigger scripts, targeting the CHK trigger/scripting bytecode format used inside .scx/.chk map files.
* [factorio-starcraft-assettool](https://github.com/heinermann/factorio-starcraft-assettool) ⭐ 2 | 🐛 1 | 🌐 C++ | 📅 2025-07-19 - Extracts and converts StarCraft: Remastered assets (sprites, animations, tilesets, palettes) from the game's CASC storage for use in the factorio-starcraft mod.
  * Formats: CASC storage, GRP sprites, animation files, tile sets, LIT palettes.

#### StarCraft II & Heroes of the Storm

* [s2protocol](https://github.com/Blizzard/s2protocol) ⭐ 640 | 🐛 48 | 🌐 Python | 📅 2026-07-16 - Python library to decode StarCraft II replay protocols.

* [heroprotocol](https://github.com/Blizzard/heroprotocol) ⭐ 401 | 🐛 21 | 🌐 Python | 📅 2026-02-20 - Python library to decode Heroes of the Storm replays.

* [m3addon](https://github.com/SC2Mapster/m3addon) ⚠️ Archived - Blender addon to import and export .m3 files used in StarCraft II and Heroes of the Storm.

* [M3\_Import](https://github.com/CaptainD001/M3_Import) ⭐ 15 | 🐛 10 | 🌐 MAXScript | 📅 2019-06-19 - 3ds Max importer for StarCraft II M3 models.

* [Starcraft Modding Tools](https://www.moddb.com/games/starcraft/downloads/starcraft-modding-tools) - Collection of tools for editing StarCraft's primary data (DAT) files.

* [WoW Model Viewer 5.0.7 (World of Warcraft)](https://www.moddb.com/games/world-of-warcraft/downloads/wow-model-viewer-5-0-7) - The WoW Model Viewer is a 3D model viewer for World of Warcraft. It uses the data files included with the game to display the models from the game: creatures, characters, spell effects, doodads, items, etc.

* [Blizzard DATA unpacker (Warcraft: Orcs & Humans)](https://www.moddb.com/games/warcraft-orcs-humans/downloads/blizzard-data-unpacker) - Unpacker DATA archives from Blizzard games: - Warcraft: Orcs and Humans \[1994] - Blackthorne \[1994] - Lost Vikings \[1993] (partially, there may be broken files) With source codes in C.

#### Overwatch

* [Prometheus](https://github.com/saturn-xvi/prometheus) ⭐ 591 | 🐛 9 | 🌐 C++ | 📅 2026-05-15 - Research and reverse-engineering project documenting Overwatch game internals including managers, ECS, STU, data structures, game messages, and components.

#### Warcraft III

* [mdx-m3-viewer](https://github.com/flowtsohg/mdx-m3-viewer) ⭐ 175 | 🐛 15 | 🌐 TypeScript | 📅 2025-08-27 - WebGL viewer for MDX and M3 model files used by Warcraft III and StarCraft II respectively.
* [ReterasModelStudio](https://github.com/Retera/ReterasModelStudio) ⭐ 120 | 🐛 16 | 🌐 Java | 📅 2026-02-23 - Java-based MDX model editor/studio for Warcraft III, distributed via Hive Workshop, with libraries for reading/writing WC3 model formats.
* [BLPConverter](https://github.com/Kanma/BLPConverter) ⭐ 90 | 🐛 5 | 🌐 C++ | 📅 2026-06-24 - Command-line tool to convert Blizzard BLP image files to PNG or TGA.
* [PHP-MPQ](https://github.com/cipherxof/PHP-MPQ) ⭐ 19 | 🐛 3 | 🌐 PHP | 📅 2018-07-31 - Native PHP library for reading the MPQ (MoPaQ) archive format, with support for Warcraft III & StarCraft II maps.
* [PHP-BLP](https://github.com/cipherxof/PHP-BLP) ⭐ 11 | 🐛 1 | 🌐 PHP | 📅 2018-07-24 - Blizzard BLP image file parser for PHP, using GD/ImageMagick for decoding.
* [mdx-m3-optimizer](https://github.com/flowtsohg/mdx-m3-optimizer) ⭐ 7 | 🐛 1 | 🌐 C++ | 📅 2019-08-29 - Optimizes MDX and M3 model files used by Warcraft III and StarCraft II respectively.
* [war3-objectdata](https://github.com/flowtsohg/war3-objectdata) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2023-05-13 - Helper library for reading and working with Warcraft III object data files (unit/item/ability data).
* [Formats](https://github.com/HiveWorkshop/Formats) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2019-10-31 - Kaitai Struct grammar for Warcraft III's WTG (map trigger) format, split into modular sub-grammars (trigger, ECA, variable, parameter, category, header).

#### Diablo

* [DevilutionX](https://github.com/diasurgical/DevilutionX) ⭐ 9,688 | 🐛 477 | 🌐 C++ | 📅 2026-08-15 - Actively maintained, cross-platform engine reimplementation of Diablo 1 and Hellfire that reads the original game's MPQ data files.
  * Ports: Windows, Linux, macOS, and numerous consoles/handhelds.
* [devilution](https://github.com/diasurgical/devilution) ⭐ 8,990 | 🐛 42 | 🌐 C++ | 📅 2025-09-15 - Decompilation of the original 1996 Diablo, matching the shipped retail binary; the reference decompilation DevilutionX is built from.
* [freeablo](https://github.com/wheybags/freeablo) ⭐ 2,172 | 🐛 63 | 🌐 C++ | 📅 2023-04-13 - Open-source, cross-platform reimplementation of the Diablo 1 engine that reads the original game's MPQ data files. Archived by its author but a notable, long-running project.
* [OpenD2](https://github.com/eezstreet/OpenD2) ⭐ 602 | 🐛 18 | 🌐 C | 📅 2021-05-31 - Open-source rewrite of the Diablo 2 game engine that uses the original game's data files (MPQ archives) and original save files, rather than reimplementing/replacing them.
* [DGEngine](https://github.com/dgcor/DGEngine) ⭐ 269 | 🐛 12 | 🌐 C++ | 📅 2025-07-21 - Engine reimplementation for Diablo 1, reading the original game's MPQ data files.
* [d1-graphics-tool](https://github.com/diasurgical/d1-graphics-tool) ⭐ 51 | 🐛 13 | 🌐 C++ | 📅 2025-03-15 - GUI tool to display and edit Diablo 1's CEL/CL2 graphics files and their PAL/TRN/TIL/MIN/SOL/AMP metadata formats.
* [D2RModding-SpriteEdit](https://github.com/eezstreet/D2RModding-SpriteEdit) ⭐ 46 | 🐛 6 | 🌐 C# | 📅 2022-03-29 - Basic editor for Diablo II: Resurrected's sprite image files, tested with inventory sprite data.
* [modding-tools](https://github.com/diasurgical/modding-tools) ⭐ 44 | 🐛 3 | 🌐 JavaScript | 📅 2025-04-17 - Collection of modding tools for Diablo 1 and DevilutionX.
* [psx-tools](https://github.com/diasurgical/psx-tools) ⭐ 30 | 🐛 2 | 🌐 C | 📅 2026-04-11 - Tools for working with the data files of the PlayStation port of Diablo.
* [devilution-comparer](https://github.com/diasurgical/devilution-comparer) ⭐ 22 | 🐛 4 | 🌐 Rust | 📅 2022-06-09 - Helper tool for comparing devilution's decompiled functions against the original Diablo binary.
* [D2RModding-StrEdit](https://github.com/eezstreet/D2RModding-StrEdit) ⭐ 21 | 🐛 0 | 🌐 C# | 📅 2023-02-22 - Editor for Diablo II: Resurrected's string translation files, which moved from the proprietary .TBL format to a collection of JSON files.
* [d2rlint](https://github.com/eezstreet/d2rlint) ⭐ 20 | 🐛 3 | 🌐 TypeScript | 📅 2026-02-25 - Linter for Diablo II: Resurrected's tab-delimited "Excel" data files and JSON string tables, flagging common modding data errors.
* [diablo-file-formats](https://github.com/doggan/diablo-file-formats) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2015-01-19 - Parses binary file formats found within Diablo 1 MPQ archives into convenient run-time data structures.
* [devilutionx-asset-optimizer](https://github.com/diasurgical/devilutionx-asset-optimizer) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2026-06-07 - Unpacks Diablo's MPQ archive and converts/minifies its assets into DevilutionX's optimized CLX formats, reducing memory usage on constrained platforms.
* [d2rdoc](https://github.com/eezstreet/d2rdoc) ⭐ 4 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-08 - Augmented version of Blizzard's official Diablo II: Resurrected modding documentation, covering the data file formats introduced in the 3.0 "Reign of the Warlock" expansion.
* [TXTeditor](https://github.com/yinyin333333/TXTeditor) ⭐ 4 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-19 - Windows desktop editor for Diablo II / Diablo II: Resurrected tab-separated `.txt` data files and D2R JSON string files.
  * Features: canvas-rendered virtual grid built for large tables, cell/range/row/column selection, copy/cut/paste with fill operations, row/column insert/clone/hide/delete.
  * Built as a Tauri v2 desktop app.
* [mpqfs](https://github.com/diasurgical/mpqfs) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2026-08-09 - MPQ v1 archive reader/writer library with streaming integration, used by DevilutionX to read Diablo's original MPQ data files.
* [DT1-Tools](https://github.com/eezstreet/DT1-Tools) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2013-12-20 - Paul Siramy's classic DT1 tile file tools for Diablo II, updated with 64-bit Windows support.
* [clx-conversion-tools](https://github.com/diasurgical/clx-conversion-tools) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2024-10-12 - Graphics format conversion tools for DevilutionX's CLX sprite format.
* [vector-lsp](https://github.com/eezstreet/vector-lsp) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-06-10 - Language Server Protocol (LSP) server for Diablo II and Diablo II: Resurrected's structured, delimited data files (tab-delimited .txt, CSV).
  * Features: Real-time diagnostics, hover documentation, go-to-definition, and an extensible plugin system for IDE-supported editing of D2/D2R data tables.
* [mpq-server](https://github.com/doggan/mpq-server) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2017-06-04 - Node.js server that exposes the contents of any MPQ archive over a local HTTP REST API, for personal use with legally-owned game data.
* [mpq-extract](https://github.com/doggan/mpq-extract) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-03 - Command-line Node.js extractor for Blizzard's MPQ (MoPaQ) archive format, given an input MPQ and a listfile of internal file paths. Used across Warcraft III, StarCraft, Diablo, and World of Warcraft.
* [devilutionx-font-converter](https://github.com/diasurgical/devilutionx-font-converter) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-08-25 - Converts TrueType/OpenType fonts into DevilutionX's custom bitmap font format.

#### Hearthstone

* [proto-extractor](https://github.com/HearthSim/proto-extractor) ⭐ 94 | 🐛 3 | 🌐 C# | 📅 2024-07-30 - Extracts and generates C# classes from the protobuf definitions compiled into Hearthstone's binaries, used to decode the game's network protocol and data.

### Bob Hays (Hypercycles)

* [hypercycles-sdl](https://github.com/Herschel/hypercycles-sdl) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2018-10-12 - Modern SDL port of the 1995 DOS game Hypercycles, built from its released original source. Loads the original game's PCX/RAW/MDI graphics and audio assets and .DAT/.DEF level and object data files directly.

### Bohemia Interactive

* [BI Editing Tools 2 (ARMA 2)](https://www.moddb.com/games/arma-2/downloads/bi-editing-tools-2) - Complete editing tool suite for Bohemia Interactive's game engine used in ARMA II. This installer will overwrite previously released BI Editing Tools for Arma I (user made data are intact) and it can not be possible to pack and finalize content for Arma I using the newer tools. Despite it may be ...
* [CWR](https://github.com/BohemiaInteractive/CWR) ⭐ 924 | 🐛 10 | 🌐 C++ | 📅 2026-08-18 - Arma: Cold War Assault (Operation Flashpoint: Cold War Crisis) Remastered - official modernized C++20 engine and game source release, reading the original game's native PBO/config data formats.

### Blueside (Kingdom Under Fire II)

* [KUF2.PKG.Tool](https://github.com/Ekey/KUF2.PKG.Tool) ⚠️ Archived - Tool for extracting PKG archives from Kingdom Under Fire II.

### Boss Game Studios (Top Gear Rally)

* [noclip.website (Top Gear Rally)](https://github.com/magcius/noclip.website/tree/main/src/TopGearRally) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Top Gear Rally (N64) track viewer covering all five tracks plus mirrored variants, with a Python extractor for pulling track data out of the ROM. Renders spline-animated scenery, animated textures, and reflections on top of an F3DEX display-list interpreter.

### Brno Transit

* [krtekex](https://github.com/iOrange/krtekex) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-07-18 - Command-line unpacker for the indie game Brno Transit's krtek.dat asset pack file.

### Bugbear Entertainment (FlatOut)

* [bfstool](https://github.com/xNyaDev/bfstool) ⭐ 28 | 🐛 5 | 🌐 Rust | 📅 2025-08-07 - Tool for working with BFS (BugBear File System) archives.
  * Games: FlatOut (1, 2, Head On), FlatOut: Ultimate Carnage, Rally Trophy, Tough Trucks, Sega Rally Revo, and more.
  * Formats: .bfs archives (BFS v1 and v2), zlib compression.
  * Features: List/extract/create archives, glob pattern filtering, CRC32/MD5/SHA1 checksums for unknown files, compression optimization.
* [FlatOutW32BGMTool](https://github.com/gaycoderprincess/FlatOutW32BGMTool) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2026-07-23 - Tool for handling .w32 (tracks) and .bgm (vehicles) files in FlatOut games.
  * Games: FlatOut 1/2/Ultimate Carnage, Rally Trophy, Tough Trucks.
  * Formats: .w32 (maps/tracks), .bgm (vehicles), .fbx (import/export), collision (.cdb.gen).
  * Features: Export to/import from FBX, format conversion (FO2 ↔ FO1, FOUC ↔ others), track editing, material/shader export, BVH zone modification.
* [blender\_flatout2\_trackai\_importer](https://github.com/gmazy/blender_flatout2_trackai_importer) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-04-03 - Blender addon for importing trackai.bin files from FlatOut 2.
* [xnya game-mods cryptutil collection](https://github.com/xNyaDev/game-mods) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2024-09-11 - Encryption key dumping utilities for BugBear games (in \*\_cryptutil directories).
  * `xnya_rallytrophy_cryptutil`: Dump encryption keys from Rally Trophy for decrypted execution.
  * `xnya_retrodemo_cryptutil`: Dump encryption keys from Bugbear Retro Demo 2002 for decrypted execution.
  * Integration: Works with bfstool for archive handling.

### Bugbear Entertainment (Team6 Engine - FlatOut 3)

* [team6tool](https://github.com/ermaccer/team6tool) ⭐ 7 | 🐛 4 | 🌐 C++ | 📅 2025-09-30 - Tool for extracting models and textures from Team6 engine games.
  * Games: FlatOut 3, ESR, Pizza Dude (Team6 engine v2 only).
  * Formats: .dcm (models), .dct (textures, exports as DDS).
  * Features: Extract vehicles, characters, and objects to OBJ format; preserve material data (excludes environment maps).

### Bugs Bunny: Lost in Time

* [BuggyBunny](https://github.com/hadashisora/BuggyBunny) ⭐ 2 | 🐛 2 | 🌐 C# | 📅 2019-07-09 - Unpacker and repacker for .bzz game archives from Bugs Bunny Lost in Time, extracting sound, text, and image data.

### Bugbear Entertainment (Wreckfest)

* [wreckfest\_toolbox](https://github.com/gmazy/wreckfest_toolbox) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2026-05-11 - Blender addon for importing and exporting Wreckfest game formats (SCNE, VHCL, BMAP).

### Bullfrog Productions

#### PowerMonger

* [powermonger-terrain](https://github.com/jankfactor/powermonger-terrain) ⭐ 5 | 🐛 0 | 📅 2023-07-16 - Investigation with code into the terrain generation used by PowerMonger (1990).

#### Dungeon Keeper

* [KeeperFX](https://github.com/dkfans/keeperfx) ⭐ 989 | 🐛 453 | 🌐 C | 📅 2026-08-18 - Decompiled and continuously rewritten fan port of Dungeon Keeper 1, reading the original game's data files. Long-running community project with extensive modding/campaign support.
* [OpenKeeper](https://github.com/tonihele/openkeeper) ⭐ 493 | 🐛 96 | 🌐 Java | 📅 2026-08-17 - Open-source remake of Dungeon Keeper II in Java/jMonkeyEngine, running entirely on the original game assets.
* [GLKeeper](https://github.com/codenamecpp/GLKeeper) ⭐ 39 | 🐛 0 | 🌐 C++ | 📅 2026-08-13 - Dungeon Keeper II reimplementation in C++/OpenGL, loading the original assets (not yet playable).
* [Dungeon Keeper Remake](https://github.com/Themperror/Dungeon-Keeper-Remake) ⭐ 35 | 🐛 0 | 🌐 C++ | 📅 2026-03-29 - Dungeon Keeper 1 remake in C++/DirectX 11 that drops into the original game folder. Includes RNC decompression for the game's compressed assets and Smacker (SMK) video playback.
* [dk2-tools](https://github.com/ufdada/dk2-tools) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2021-04-04 - 010 Editor binary templates and conversion scripts documenting Dungeon Keeper 2 file formats.
  * Formats: WAD, SPR, EngineTextures.dat/.dir (archives), KWD/KLD (levels), KMF (models), BF4 (fonts), KCS (camera sweeps), SDT/\*BANK.map/\*SFX.map (audio), STR, residx.dat, HiScores.dat, Addressbook.dat.
* [ADiKtEd](https://github.com/dkfans/ADiKtEd) ⭐ 6 | 🐛 8 | 🌐 C | 📅 2024-02-22 - Advanced Dungeon Keeper 1 map/level editor, reading and writing the game's DAT, CLM, TNG, LGT, APT, WLB, and FLG level-data files (with RNC decompression support) via the bundled libadikted library.
* [pngpal2raw](https://github.com/dkfans/pngpal2raw) ⭐ 0 | 🐛 1 | 🌐 C++ | 📅 2025-02-05 - Converts PNG images (with a palette) into the Bullfrog Engine's native RAW/DAT/JTY sprite formats used by Dungeon Keeper 1.
* [po2ngdat](https://github.com/dkfans/po2ngdat) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2025-12-31 - Converts gettext PO/POT translation files into the Bullfrog Engine's NGDAT (.dat) translation-string format used by Dungeon Keeper 1/KeeperFX.
* [sndbanker](https://github.com/dkfans/sndbanker) ⭐ 0 | 🐛 1 | 🌐 C++ | 📅 2015-09-24 - Packs WAV sound files into the Bullfrog Engine's DAT sound-bank format used by Dungeon Keeper 1/KeeperFX.

#### Syndicate Wars

* [Syndicate Wars Port](https://github.com/swfans/syndwarsfx) ⭐ 239 | 🐛 92 | 🌐 C | 📅 2026-07-29 - Open-source reverse-engineered port of Bullfrog's Syndicate Wars, reading the original game's data files.

#### Populous: The Beginning

* [Populous-The-Beginning-Public](https://github.com/TylerTheFox/Populous-The-Beginning-Public) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2026-08-07 - Reverse-engineering and reimplementation work on Populous: The Beginning (C++).
* [PopResourceEditor](https://github.com/Toksisitee/PopResourceEditor) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2025-06-27 - Asset editor and manager in C++ for Populous: The Beginning, with preview, import, modification and export of the game's data files.
  * Formats: Level (v2) maps, Palette (256-color indexed), Sprite, Sky, Blocks (3D texture atlas), BigFade/Cliff/Fade (landscape textures), Disp (displacement maps), Alpha, Ghost.

#### Hi-Octane

* [HiOctaneTools](https://github.com/movAX13h/HiOctaneTools) ⭐ 32 | 🐛 2 | 🌐 C# | 📅 2023-02-12 - Level inspector and editor for Hi-Octane (1995) in C#, based on srtuss's and movAX13h's reverse-engineering of the game's files. Includes a Bullfrog object data to Wavefront OBJ converter.
* [hi-octane202x](https://github.com/woalexan/hi-octane202x) ⭐ 13 | 🐛 6 | 🌐 C++ | 📅 2026-08-16 - Recreation of Hi-Octane in C++/Irrlicht, running on the original game data (`HIOCTANE.CD`), with an integrated level editor.

#### Creation

* [creation\_tk](https://github.com/hogsy/creation_tk) ⚠️ Archived - Utility for reading, extracting, and converting files from Bullfrog's cancelled game Creation.

#### Theme Park

* [ThemeParkResourceViewer](https://github.com/tigrouind/ThemeParkResourceViewer) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2025-11-30 - Resource viewer/extractor for Theme Park (1994).

#### Quake III: Revolution

* [Q3R\_tools](https://github.com/Yagotzirck/Q3R_tools) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2018-11-15 - Resource extractor for Quake III: Revolution (2001, PS2), Bullfrog Productions' final game.

### Burut CT

* [xtend-engine-file-formats](https://github.com/AlexKimov/xtend-engine-file-formats) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-05-18 - File formats and tools for Burut CT games built on the xtend engine.

### Capcom

*Many titles use [Havok](#havok) or [CRI](#cri) middleware alongside proprietary engines.*

#### RE Engine

* [REFramework](https://github.com/praydog/REFramework) ⭐ 5,339 | 🐛 644 | 🌐 C++ | 📅 2026-08-13 - Powerful scripting framework and mod loader for RE Engine games. Provides an overlay with a resource editor, object explorer, and various developer tools.
* [REE.PAK.Tool](https://github.com/Ekey/REE.PAK.Tool) ⭐ 389 | 🐛 4 | 🌐 C# | 📅 2026-04-22 - Tools for extracting and repacking PAK archives from games based on RE ENGINE.
  * See also [REEngine\_UnPAK-Desktop](https://github.com/SilverEzredes/REEngine_UnPAK-Desktop) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2024-06-03 for a desktop GUI version.
* [RE-Mesh-Editor](https://github.com/NSACloud/RE-Mesh-Editor) ⚠️ Archived - Visual scene and mesh editor for RE Engine games.
  * See also [fmt\_RE\_MESH-Noesis-Plugin](https://github.com/alphazolam/fmt_RE_MESH-Noesis-Plugin) ⭐ 185 | 🐛 19 | 🌐 Python | 📅 2024-09-21 for the modern version with extensive format support.
* [EMV-Engine](https://github.com/alphazolam/EMV-Engine) ⭐ 173 | 🐛 15 | 🌐 Lua | 📅 2024-07-31 - REFramework Lua scripts including a Resource Editor tool for RE Engine games.
  * See also [EMV-Engine-SILVER](https://github.com/SilverEzredes/EMV-Engine-SILVER) ⭐ 49 | 🐛 0 | 🌐 Lua | 📅 2026-06-03 for updated support (Resident Evil 4, MH Wilds).
* [RE\_RSZ](https://github.com/alphazolam/RE_RSZ) ⭐ 150 | 🐛 9 | 🌐 Roff | 📅 2026-03-30 - 010 Editor binary template for RE Engine files containing RSZ data (SCN, PFB, USER, RCOL, FSMV2, MOTFSM, BHVT). Uses a companion DLL and per-game JSON structure dumps.
  * Games: Apollo Justice: Ace Attorney Trilogy, Dead Rising Deluxe Remaster, Devil May Cry 5, Dragon's Dogma 2, Ghost Trick, Monster Hunter: Rise, Monster Hunter Wilds, Resident Evil 2/3/4/7 Remake, Resident Evil Village, Resident Evil Re:Verse, Street Fighter 6.
* [REasy](https://github.com/seifhassine/REasy) ⭐ 105 | 🐛 5 | 🌐 Python | 📅 2026-08-19 - Modding toolkit for RE Engine games, with a resource packer/unpacker and file editors.
  * Games: Resident Evil 2/3/4/7/8/9, Devil May Cry 5, Monster Hunter Rise/Wilds, Dragon's Dogma 2, Onimusha 2, Pragmata, Street Fighter 6.
* [REE-Content-Editor](https://github.com/kagenocookie/REE-Content-Editor) ⭐ 99 | 🐛 11 | 🌐 C# | 📅 2026-08-17 - Mod development editor and file patcher for RE Engine games.
* [REEngine-Modding-Documentation](https://github.com/Havens-Night/REEngine-Modding-Documentation) ⭐ 99 | 🐛 2 | 📅 2026-04-11 - GitHub wiki covering RE Engine modding: installing/packaging mods, extracting game files, textures, models, troubleshooting, ID lookups, and a curated tool directory.
* [ree-pak-rs](https://github.com/eigeen/ree-pak-rs) ⭐ 70 | 🐛 4 | 🌐 Rust | 📅 2026-04-02 - Rust-based library and CLI for RE Engine `.pak` files.
* [REMSG\_Converter](https://github.com/dtlnor/REMSG_Converter) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2026-07-24 - RE Engine message text converter (`.msg.17` etc.).
* [MDF-Manager](https://github.com/Silvris/MDF-Manager) ⭐ 36 | 🐛 0 | 🌐 C# | 📅 2025-03-06 - C# WPF GUI editor for RE Engine material definition files (`.mdf2`), with library/compendium browsing and batch conversion between game versions. See also [SilverEzredes's fork](https://github.com/SilverEzredes/MDF-Manager_RE4R) ⚠️ Archived with RE4 Remake support.
* [ReachForGodot](https://github.com/kagenocookie/ReachForGodot) ⭐ 26 | 🐛 0 | 🌐 C# | 📅 2025-07-06 - Godot-based scene and data editor for RE Engine games.
* [RE-Engine-010-Templates](https://github.com/alphazolam/RE-Engine-010-Templates) ⭐ 18 | 🐛 2 | 🌐 Roff | 📅 2024-08-15 - Collection of 010 templates for RE Engine games by alphaZomega.
* [RE-Engine-Lib](https://github.com/kagenocookie/RE-Engine-Lib) ⭐ 16 | 🐛 1 | 🌐 C# | 📅 2026-08-16 - .NET library for reading and writing RE Engine resource files.
* [GhidraREFramework](https://github.com/Fexty12573/GhidraREFramework) ⭐ 14 | 🐛 1 | 🌐 Java | 📅 2026-02-24 - Ghidra scripts for importing TDB (type database) data from RE Engine games using il2cpp dumps.
* [REngine-MSG-Tool](https://github.com/ca1e/REngine-MSG-Tool) ⭐ 6 | 🐛 5 | 🌐 C# | 📅 2023-04-28 - CLI tool for unpacking and repacking RE Engine message/text files (`.msg.14`, `.msg.15`, `.msg.17`).
* [RE4-EFX-Template](https://github.com/NSACloud/RE4-EFX-Template) ⭐ 5 | 🐛 0 | 🌐 Roff | 📅 2025-04-23 - 010 template for Resident Evil 4 Remake EFX files.
* [RE-Engine-VSDF-Template](https://github.com/Silvris/RE-Engine-VSDF-Template) ⭐ 4 | 🐛 0 | 🌐 Roff | 📅 2021-04-15 - Template for RE Engine VSDF files.
* [RszTool](https://github.com/kagenocookie/RszTool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-06-24 - Resource editor for RE Engine `.user`, `.pfb`, and `.scn` files. Supports editing RSZ data in a GUI.
* [RE\_RSZ](https://github.com/SilverEzredes/RE_RSZ) ⭐ 1 | 🐛 0 | 🌐 Roff | 📅 2026-01-03 - 010 Editor template for RE Engine RSZ data.

#### MT Framework

* [Gibbed.MT](https://github.com/gibbed/Gibbed.MT) ⭐ 20 | 🐛 4 | 🌐 C# | 📅 2022-12-08 - Tools for modding MT Framework-based Capcom games including archive unpacker/packer for .arc files.
* [GMDConverter](https://github.com/onepiecefreak3/GMDConverter) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2018-12-19 - Converter for the GMD file format from Capcom's MT Framework. Supports Version 1 and Version 2.
  * Features: BNK Editor (soundbanks), PCK Editor (packages), Loop Calculator, WEM Creator, WWCT/WWBK/WWPK/EPVSP editors.
  * Formats: .nbnk/.bnk, .npck/.pck, .wwct, .wwbk/.wwpk, .epvsp, .wem.
* [xfs2json](https://github.com/Fexty12573/xfs2json) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-05-09 - Converts Capcom MT Framework XFS binary format to JSON for Monster Hunter Generations Ultimate and other MT Framework games.
* [GFDConverter](https://github.com/onepiecefreak3/GFDConverter) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2018-05-22 - Converts GFD (v1) to GFD (v2) from Capcom's MT Framework.
* [ARC Unpacker & Repacker](https://www.moddb.com/games/devil-may-cry-4/downloads/arc-unpacker-repacker-v09428) - Modding tool letting you extract and repack ARC file containers in MT Framework games (Resident Evil 5, Resident Evil 6, Dragon’s Dogma, Devil May Cry 4, and other Capcom titles) which can also convert many of the file formats in the archives.

#### Resident Evil

* [OpenBiohazard2](https://github.com/OpenBiohazard2/OpenBiohazard2) ⭐ 282 | 🐛 4 | 🌐 Go | 📅 2026-08-17 - Open source re-implementation of the original Resident Evil 2 engine (Go, OpenGL), reading the original game's data files.
* [recvx-decomp (decomp)](https://github.com/AshfordFamily/recvx-decomp) ⭐ 213 | 🐛 2 | 🌐 C | 📅 2026-08-18 - Matching decompilation of Resident Evil - Code: Veronica X (PS2).
* [re4-research](https://github.com/emoose/re4-research) ⭐ 60 | 🐛 25 | 🌐 C++ | 📅 2023-01-15 - Mod tools and research for Resident Evil 4 (UHD).
* [reevengi-tools](https://github.com/pmandin/reevengi-tools) ⭐ 52 | 🐛 1 | 🌐 C | 📅 2026-01-06 - Tools written to verify the reverse engineering of classic Resident Evil file formats (models, textures, pre-rendered backgrounds, and archives).
* [recv-dc-decomp (decomp)](https://github.com/fmil95/recv-dc-decomp) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2026-01-20 - Matching decompilation of Resident Evil - Code: Veronica (Dreamcast).
* [RECVX-Texture-Tool](https://github.com/dortkoldantaciz/RECVX-Texture-Tool) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-24 - Texture extractor/repacker for Resident Evil Code Veronica X.
* [BioHazard File Archive Tool (Resident Evil 4)](https://www.moddb.com/games/resident-evil-4/downloads/biohazard-file-archive-tool) - File archive tool for Resident Evil 4. Two versions available: one designed for Windows XP, another ported for Windows 7. Both are 32-bit but work on 64-bit systems. Windows 7 version is backwards compatible with XP.

#### Monster Hunter

* [Mod3-MHW-Importer](https://github.com/AsteriskAmpersand/Mod3-MHW-Importer) ⭐ 118 | 🐛 2 | 🌐 Python | 📅 2025-01-05 - Blender Import-Exporter for Monster Hunter World Mod3 model format.
* [MHXXSwitchSaveEditor](https://github.com/Dawnshifter/MHXXSwitchSaveEditor) ⭐ 117 | 🐛 17 | 🌐 C# | 📅 2023-10-18 - Save editor for Monster Hunter XX (Switch and 3DS versions).
* [WorldChunkTool](https://github.com/mhvuze/WorldChunkTool) ⭐ 111 | 🐛 3 | 🌐 C# | 📅 2020-01-21 - Decompresses and extracts chunk\*.bin files from Monster Hunter World and Iceborne.
* [RingingBloom](https://github.com/Silvris/RingingBloom) ⭐ 72 | 🐛 13 | 🌐 C# | 📅 2025-03-25 - WWise audio editing toolkit for Monster Hunter: World and other Capcom titles.
* [mhw\_armor\_edit](https://github.com/fre-sch/mhw_armor_edit) ⭐ 40 | 🐛 7 | 🌐 Python | 📅 2020-02-07 - Editor for Monster Hunter World game data formats (\*.am\_dat, \*.wp\_dat, \*.eq\_crt, etc.) for armor, weapons, and equipment.
* [MHST2-Save-Tools](https://github.com/AsteriskAmpersand/MHST2-Save-Tools) ⭐ 38 | 🐛 8 | 🌐 Python | 📅 2021-08-01 - Save file tools for Monster Hunter Stories 2.
* [mh1j (decomp)](https://github.com/2Tie/mh1j) ⭐ 36 | 🐛 2 | 🌐 C | 📅 2026-08-17 - Matching decompilation of Monster Hunter (PS2, Japanese release).
* [MH-Tools-and-Scripts](https://github.com/Silvris/MH-Tools-and-Scripts) ⭐ 34 | 🐛 4 | 🌐 Python | 📅 2024-05-25 - Tools and scripts for handling Monster Hunter series files (MH1-GU, Frontier, World, Generations Ultimate).
* [APMMHXSaveEditor](https://github.com/ezapm/APMMHXSaveEditor) ⭐ 30 | 🐛 4 | 🌐 C# | 📅 2019-03-19 - Save file editor for Monster Hunter X (Capcom, 3DS), reading and writing the game's original save data format.
* [MHW-Research](https://github.com/TheCrazyT/MHW-Research) ⭐ 29 | 🐛 0 | 🌐 Roff | 📅 2020-06-06 - Research and tools for Monster Hunter: World file formats.
* [Leviathon](https://github.com/AsteriskAmpersand/Leviathon) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2023-01-11 - Decompiler/compiler for Monster Hunter World THK files with language specification.
* [MHR Tex Chopper](https://github.com/AsteriskAmpersand/MHR_Tex_Chopper) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2025-03-07 - Converts Monster Hunter Rise textures to/from DDS format for extraction and re-import.
* [Material-Editing](https://github.com/AsteriskAmpersand/Material-Editing) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2020-10-09 - Monster Hunter World MRL3 material file format editor.
* [MHR\_Research](https://github.com/NSACloud/MHR_Research) ⭐ 19 | 🐛 0 | 📅 2021-01-11 - Research and 010 templates for Monster Hunter Rise.
* [MHWs Tex Chopper](https://github.com/AsteriskAmpersand/MHWs_Tex_Chopper) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2025-04-06 - Monster Hunter World texture extraction and editing tool.
* [CTC-MHW-Editor](https://github.com/AsteriskAmpersand/CTC-MHW-Editor) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2024-09-05 - Blender plugin for editing CTC and CCL file formats in Monster Hunter World.
* [PMO Importer](https://github.com/AsteriskAmpersand/PMO-Importer) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2025-07-25 - Blender importer for Monster Hunter Freedom Unite PMO model format with documentation.
* [pmo\_export](https://github.com/Kurogami2134/pmo_export) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2026-07-19 - Blender addon for exporting PMO model format used by Monster Hunter Freedom Unite and Monster Hunter Portable 3rd.
* [MHR-EFX-Template](https://github.com/NSACloud/MHR-EFX-Template) ⭐ 7 | 🐛 0 | 🌐 Roff | 📅 2023-01-18 - 010 template for Monster Hunter Rise EFX files.
* [Hyperthermia MHW IB Converter](https://github.com/AsteriskAmpersand/Hyperthermia-MHW-IB-Converter) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2020-02-24 - Monster Hunter World / Iceborne format conversion tool.
* [mhst2-arc-tool](https://github.com/Fexty12573/mhst2-arc-tool) ⭐ 3 | 🐛 2 | 🌐 C++ | 📅 2021-08-08 - Archive tool for Monster Hunter Stories 2.

#### Devil May Cry

* [dmc\_hd\_tools](https://github.com/Kerilk/dmc_hd_tools) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2018-05-23 - Toolkit for Devil May Cry HD Collection including Noesis plugins and binary templates.

#### Street Fighter

* [3s-decomp (decomp)](https://github.com/crowded-street/3s-decomp) ⭐ 269 | 🐛 0 | 🌐 C | 📅 2026-04-03 - Matching decompilation of Street Fighter III: 3rd Strike (PS2).
* [MMDK](https://github.com/alphazolam/MMDK) ⭐ 58 | 🐛 3 | 🌐 Lua | 📅 2024-12-06 - Moveset editing toolkit for Street Fighter 6. Includes motion and collision data editors.

#### CP System (Arcade)

* [cpsb](https://github.com/fabiensanglard/cpsb) ⭐ 143 | 🐛 1 | 🌐 TeX | 📅 2026-05-18 - "The Book of CP-System": open-source hardware study and documentation of Capcom's CP System arcade board (1989-1995), used by Street Fighter II, Final Fight, and Ghouls 'n Ghosts.
* [CPS1-sound-extract](https://github.com/bentorkington/cps1-sound-extract) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2022-01-30 - Extracts ADPCM samples and MIDI stage tunes from CPS1 arcade sound ROMs (Z80/YM2151/OKI MSM6295), documenting the CPS1 sound ROM memory map.
* [cpss](https://github.com/fabiensanglard/cpss) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2024-11-29 - Reconstructs Capcom CPS-1 sprite/palette sheets from arcade ROM dumps, deinterleaving GFXROM graphics data and locating in-ROM color palettes for supported games (e.g. Street Fighter II).

#### Ultimate Marvel vs Capcom 3

* [umvc3-tools](https://github.com/tge-was-taken/umvc3-tools) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2024-10-03 - Ultimate Marvel vs Capcom 3 tools and research. Includes MT Framework Model (MOD) import/export plugin for 3ds Max, Texture (TEX) converter, Material (MTL) converter, and binary templates.
* [ThreeWorkTool](https://github.com/EternalYoshi/ThreeWorkTool) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2026-06-14 - GUI tool for managing MT .arc files in Ultimate Marvel vs Capcom 3. Supports DDS texture imports, character animation keyframe import/exports, and archive file management.

#### Mega Man

* [rmz3 (decomp)](https://github.com/mmzret/rmz3) ⭐ 40 | 🐛 262 | 🌐 Assembly | 📅 2026-07-24 - Decompilation of Mega Man Zero 3 (Rockman Zero 3, Japanese version, Game Boy Advance).
* [mmx4 (decomp)](https://github.com/sozud/mmx4) ⭐ 28 | 🐛 0 | 🌐 C | 📅 2025-08-25 - Matching decompilation of Mega Man X4 (PS1).
* [gc-mm-collection-patcher](https://github.com/FIX94/gc-mm-collection-patcher) ⭐ 18 | 🐛 3 | 🌐 C | 📅 2020-08-20 - Patches to improve the emulated NES ports bundled in Mega Man Anniversary Collection (GameCube).
* [rw2 (disasm)](https://github.com/Kak2X/rw2) ⭐ 8 | 🐛 0 | 🌐 Assembly | 📅 2026-05-28 - Disassembly of Rockman World 2, the Japanese original of Mega Man II (Game Boy).
* [MegaManPoweredUpTool](https://github.com/efimandreev0/MegaManPoweredUpTool) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2023-12-28 - Tool to extract main archive from Mega Man Powered Up.
* [MegaManLINKExtract](https://github.com/efimandreev0/MegaManLINKExtract) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2023-12-29 - Tool to work with Mega Man Powered Up .link archive files.

#### Gregory Horror Show

* [GregoryHorrorShow-Blender-IO](https://github.com/boringhexi/GregoryHorrorShow-Blender-IO) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-01-25 - Imports PS2 Gregory Horror Show assets (`.ghs`, `.map-pm2`, `.pm2`) into Blender.
* [ghs-tools](https://github.com/boringhexi/ghs-tools) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2025-09-13 - Tools for unpacking and analyzing Gregory Horror Show (PS2) game data, extracting models and converting textures.

#### Gotcha Force

* [gotcha-afs-tool](https://github.com/RenolY2/gotcha-afs-tool) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-12-26 - Unpacker and repacker for Gotcha Force's AFS format (tested on GameCube version).

#### Phoenix Wright: Ace Attorney

* [pwaa1 (decomp)](https://github.com/atasro2/pwaa1) ⭐ 51 | 🐛 3 | 🌐 C | 📅 2025-07-28 - Matching decompilation of Phoenix Wright: Ace Attorney (Gyakuten Saiban, Japan).
* [pzzcompressor\_jojo](https://github.com/infval/pzzcompressor_jojo) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2020-05-28 - PZZ (de)compressor for JoJo's Bizarre Adventure: Golden Wind (PS2).
  * Formats: .pzz (compression).
  * Features: Compress and decompress game archives.
* [PZZ-ARC](https://github.com/penguino118/PZZ-ARC) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-04-13 - Tool to manage PZZ archives in JoJo's Bizarre Adventure: Golden Wind (PS2). See also [gd-giogio-modloader](https://github.com/penguino118/gd-giogio-modloader) ⭐ 1 | 🐛 11 | 🌐 GDScript | 📅 2025-10-07, a WIP mod loader for GioGio's Bizarre Adventure (PS2) by the same author.

#### Dragon's Dogma

* [Dragon's Dogma Research](https://github.com/Atvaark/DragonsDogma.Research) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2017-03-28 - File format research and documentation for Dragon's Dogma.

#### Dragon's Dogma 2

* [Gibbed.DragonsDogma2](https://github.com/gibbed/Gibbed.DragonsDogma2) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-03-04 - File format extraction and modding tools for Dragon's Dogma 2 (RE Engine).

#### Haunting Ground

* [HG-TEX](https://github.com/316austin316/HG-TEX) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-11-21 - Extracts textures from Haunting Ground (Capcom, PS2) .TEX files to editable .BMP and imports modified .BMP images back into .TEX files.

### CCP Games (EVE Online)

* [yretenai/Jackdaw](https://github.com/neptuwunium/Jackdaw) ⚠️ Archived - Research project for Carbon Engine file formats used in EVE Online.

### CCR (RF Online)

* [RF Online Addon](https://github.com/Cardboard-box-a/cbb-rf-online-addon) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2026-02-27 - Blender 4.3 importer/exporter for RF Online `.msh`, `.bn`, `.ani`, and `.bsp` formats.

### CD Projekt Red

#### The Witcher 3 / REDEngine 3

* [WolvenKit (legacy)](https://github.com/WolvenKit/WolvenKit-7) ⭐ 102 | 🐛 19 | 🌐 C# | 📅 2025-12-28 - REDEngine 3 file editor designed to simplify and accelerate modding workflow for The Witcher 3.
* [TW3-PS4-Texture-Patcher](https://github.com/Backporter/TW3-PS4-Texture-Patcher) ⭐ 3 | 🐛 0 | 📅 2021-03-04 - Tool for patching The Witcher 3 PS4 texture file formats with custom data
* [WolvenManager](https://github.com/rfuzzo/WolvenManager) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2022-09-13 - Manager for Witcher game file formats.

#### The Witcher

* [Blender 2.49 exporter for The Witcher](https://www.moddb.com/games/the-witcher/downloads/blender-exporter-for-the-witcher) - Blender 2.49 script for exporting static models to The Witcher 1 MDL format.
* [twMax v1.2.3.2 -- mdb Importer for 3DSMax (The Witcher)](https://www.moddb.com/games/the-witcher/downloads/twmax-v1232-mdb-importer-for-3dsmax) - Model importer for The Witcher's binary model format (MDB) that imports compiled models into 3DS Max 9 (v1.2.3.2).
* [Extra tools (The Witcher)](https://www.moddb.com/games/the-witcher/downloads/extra-tools) - Tools for working with The Witcher file formats: DLG (dialogue), QST (quest), BIF, MDB, GFF, and NSS files.

#### Cyberpunk 2077 / REDEngine 4

* [Cyber Engine Tweaks](https://github.com/maximegmd/CyberEngineTweaks) ⭐ 4,803 | 🐛 39 | 🌐 C++ | 📅 2026-05-09 - Framework to script mods using Lua with access to all the internal scripting features.
* [WolvenKit](https://github.com/WolvenKit/WolvenKit) ⭐ 1,181 | 🐛 335 | 🌐 C# | 📅 2026-08-18 - REDEngine 4 file editor designed to simplify and accelerate modding workflow for Cyberpunk 2077.
* [redscript](https://github.com/jac3km4/redscript) ⭐ 510 | 🐛 20 | 🌐 Rust | 📅 2026-06-09 - Compiler and decompiler for redscript (Cyberpunk 2077 scripting language)
* [RED4ext](https://github.com/WopsS/RED4ext) ⭐ 437 | 🐛 6 | 🌐 C++ | 📅 2026-03-09 - Library that extends REDengine 4. It allows modders to add new features to the game, modify existing ones, and create custom scripts.
* [CP77Tools](https://github.com/WolvenKit/CP77Tools) ⚠️ Archived - Command-line archive modding tools for Cyberpunk 2077's REDEngine 4 file formats.
* [CyberpunkSaveEditor](https://github.com/PixelRick/CyberpunkSaveEditor) ⭐ 354 | 🐛 25 | 🌐 C++ | 📅 2024-05-20 - Editor for Cyberpunk 2077 .sav.dat save files; manipulates node tree structures, inventory, quest flags, and item properties
* [TweakXL](https://github.com/psiberx/cp2077-tweak-xl) ⭐ 122 | 🐛 2 | 🌐 C++ | 📅 2026-07-28 - Reference-based TweakDB modification framework.
* [ArchiveXL](https://github.com/psiberx/cp2077-archive-xl) ⭐ 118 | 🐛 4 | 🌐 C++ | 📅 2026-08-13 - Modding tool that allows loading custom resources without overriding existing ones.
* [Gibbed.RED4](https://github.com/gibbed/Gibbed.RED4) ⭐ 61 | 🐛 0 | 🌐 C# | 📅 2021-09-16 - Tools for Cyberpunk 2077 file formats.
* [MlsetupBuilder](https://github.com/Neurolinked/MlsetupBuilder) ⭐ 25 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-12 - Tool for building and editing Cyberpunk 2077 .mlsetup files.
* [red4ext-rs](https://github.com/jac3km4/red4ext-rs) ⭐ 19 | 🐛 4 | 🌐 Rust | 📅 2026-07-23 - Rust bindings for RED4ext, enabling native Cyberpunk 2077 mods and RTTI/game-data introspection to be written in Rust.
* [fmt\_CP77mesh](https://github.com/alphazolam/fmt_CP77mesh) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2021-09-28 - Noesis plugin for reading and writing Cyberpunk 2077 mesh and texture file formats (.mesh, .xbm)
* [Cyberpunk-TweakDB-Schema](https://github.com/gibbed/Cyberpunk-TweakDB-Schema) ⭐ 6 | 🐛 0 | 📅 2020-12-25 - Reverse-engineered schema documentation for Cyberpunk 2077's TweakDB binary file format (tweakdb.bin)
* [cppdeclmangle](https://github.com/Mozz3d/cppdeclmangle) ⭐ 4 | 🐛 2 | 🌐 Python | 📅 2026-07-22 - Standalone inline C++ parser, mangler, and hasher script intended for reversing and deriving Cyberpunk 2077 hashed linker names.
* [CR2WTools](https://github.com/rfuzzo/CR2WTools) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2020-03-22 - WIP library for reading CR2W files (Witcher/Cyberpunk format).
* [red4ext-rs-dumper](https://github.com/jac3km4/red4ext-rs-dumper) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - RED4ext plugin that dumps Cyberpunk 2077's live RTTI type system (classes, enums, bitfields, offsets, alignment) into Rust source definitions.
* [Hash2077](https://github.com/0x1F9F1/Hash2077) ⭐ 1 | 🐛 2 | 🌐 C++ | 📅 2026-01-05 - Optimized brute-force dehasher for recovering symbol names in Cyberpunk 2077 using the Adler-32/SHA-256 hashes recorded in cyberpunk2077\_addresses.json.
* [CyberpunkReversing](https://github.com/alphanin9/CyberpunkReversing) - Collection of reverse engineering tools for Cyberpunk 2077 including address helpers, RTTI type recovery, and framework hash checking

### Century Interactive

#### Bermuda Syndrome

* [bermuda](https://github.com/cyxx/bermuda) ⚠️ Archived - Reimplementation of the engine used in Bermuda Syndrome, reading the original DOS release's data files; ports to Emscripten, libretro, and SDL2.

### Charybdis (Machines: Wired for War)

* [machines](https://github.com/markol/machines) ⭐ 66 | 🐛 4 | 🌐 C++ | 📅 2022-08-02 - GL port of Machines: Wired for War (1999), released as free software with permission from rights holder Night Dive Studios; loads and reads the original game's data files.

### Chris Sawyer (Transport Tycoon)

* [OpenTTD](https://github.com/OpenTTD/OpenTTD) ⭐ 8,184 | 🐛 411 | 🌐 C++ | 📅 2026-08-18 - Open-source reimplementation of Chris Sawyer's Transport Tycoon Deluxe, able to load the original game's GRF graphics/sound data files and pioneering the widely-used NewGRF format for custom vehicle/graphics data.

### Chronic Logic (Gish)

* [freegish](https://github.com/freegish/freegish) ⭐ 85 | 🐛 5 | 🌐 C | 📅 2026-08-13 - Official open-source release of Gish (Chronic Logic, 2004), a physics-based puzzle-platformer.

### Chuck Sommerville (Chip's Challenge)

* [Lexy's Labyrinth](https://github.com/eevee/lexys-labyrinth) ⭐ 87 | 🐛 24 | 🌐 JavaScript | 📅 2024-06-20 - Browser-based reimplementation of Chip's Challenge 1 and 2, able to load the original MS Chip's Challenge DAT/CCL level files and Steam Chip's Challenge 2 C2G/C2M files, with a built-in level editor and demo/replay recording.
* [Tile World](https://github.com/zrax/tworld) ⭐ 6 | 🐛 3 | 🌐 C | 📅 2024-03-22 - Cross-platform emulator of the original Chip's Challenge game engine (created for the Atari Lynx, later ported to MS Windows), loading the copyrighted CHIPS.DAT level set and other Chip's Challenge .dat level files.

### CIRCUS (Da Capo)

* [DCGF-Tool](https://github.com/gdkchan/DCGF-Tool) ⭐ 3 | 🐛 0 | 🌐 Visual Basic | 📅 2015-02-24 - Extractor/compressor for Da Capo: Girl's Symphony \*.PAK archives, with text and arts editing.

### Climax Studios (Rocket Knight)

* [RK.ARC.Tool](https://github.com/Ekey/RK.ARC.Tool) ⚠️ Archived - Tool for extracting ARC archives from Rocket Knight (2010).

### Cloud Imperium Games (Star Citizen)

* [StarBreaker](https://github.com/diogotr7/StarBreaker) ⭐ 124 | 🐛 13 | 🌐 Rust | 📅 2026-08-01 - Reverse engineering and analyzing Star Citizen's game files (P4k, DataCore, chf, etc.).
* [DataCapture](https://github.com/starcitizendotguide/DataCapture) ⚠️ Archived - Captures meta-data packets from Star Citizen for statistics.
* [SCExporter](https://github.com/Kjasi/SCExporter) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2022-05-05 - Blender tools for exporting Star Citizen models.

### Clover Studio (Okami)

* [noclip.website (Okami)](https://github.com/magcius/noclip.website/tree/main/src/rres) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Okami viewer.
* [GodHand-Noesis-Plugin](https://github.com/Al-Hydra/GodHand-Noesis-Plugin) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2024-06-09 - Noesis plugin for viewing God Hand models, skeletons, and textures.

### Creat Studio

* [creat-file-formats](https://github.com/AlexKimov/creat-file-formats) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-03-23 - File formats and viewer plugins for Creat Studio games.

### Compile Heart (Hyperdimension Neptunia)

* [karakurism-unscrambler](https://github.com/ElementW/karakurism-unscrambler) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2014-10-27 - Asset unscrambler for Hyperdimension Neptunia: The App, a mobile spin-off title.

### Conic Games

#### Exponential Idle

* [ExponentialIdle-SaveGameEditor](https://github.com/UnknownCollections/ExponentialIdle-SaveGameEditor) ⭐ 16 | 🐛 3 | 🌐 Vue | 📅 2023-03-14 - Save game editor for the mobile idle game Exponential Idle, with a documented TypeScript interface for the save data format and its encryption scheme.

### Constantine

* [constantine-file-formats](https://github.com/AlexKimov/constantine-file-formats) ⭐ 3 | 🐛 2 | 🌐 Batchfile | 📅 2019-02-19 - Game file formats and tools for Constantine (2005).

### Contrail (Legend of Legaia)

* [LegaiaText](https://github.com/gdkchan/LegaiaText) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2016-08-09 - Text editor for Legend of Legaia.

### Codemasters

* [codemasters-file-formats](https://github.com/AlexKimov/codemasters-file-formats) ⚠️ Archived - File formats and tools for Codemasters games.

### CR-Space (Martial Heroes)

* [Diamond](https://github.com/tge-was-taken/Diamond) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2026-04-07 - Reverse engineering and enhancement project for Martial Heroes. Provides tooling, parsers, and client-side improvements including binary parsers, VFS archive tools, and 010 Editor templates.

### Croteam

* [Serious-Engine](https://github.com/icculus/Serious-Engine) ⭐ 174 | 🐛 21 | 🌐 C++ | 📅 2023-07-24 - Official open-source release of Croteam's Serious Engine, used by the classic Serious Sam games.
* [SeriousSaveEditor](https://github.com/widberg/SeriousSaveEditor) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-12-25 - Save editor for Serious Sam games.
  * Games: Serious Sam: The First Encounter, The Second Encounter, and more.

### Crows Crows Crows

* [Mariella](https://github.com/EpicMinecartz/Mariella) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2022-05-04 - Save editor for The Stanley Parable: Ultra Deluxe.

### Cryo Interactive

#### Dune (1992)

* [dune-extract](https://github.com/madmoose/dune-extract) ⭐ 17 | 🐛 2 | 🌐 Rust | 📅 2025-12-02 - Resource extractor for Cryo's Dune CD version; lists and extracts files from DUNE.DAT, decompressing HSQ-compressed resources and exporting sprites as PNG.

### Crystal Dynamics / Eidos Interactive

* [OpenLara](https://github.com/XProger/OpenLara) ⭐ 5,060 | 🐛 167 | 🌐 C | 📅 2026-07-26 - Open-source reimplementation of the classic Tomb Raider engine, reading the original games' level and asset data.
* [OpenTomb](https://github.com/opentomb/OpenTomb) ⚠️ Archived - Open-source engine remake for classic Tomb Raider 1-5, reading the original games' level and asset formats (archived, but a landmark reference).
* [TRX](https://github.com/LostArtefacts/TRX) ⭐ 971 | 🐛 159 | 🌐 C | 📅 2026-08-18 - Open-source re-implementation of Tomb Raider I, II, and III that reads the original games' level and asset data (PHD/TR2 formats) while adding enhancements and bug fixes.
* [TOMB5](https://github.com/TOMB5/TOMB5) ⭐ 516 | 🐛 26 | 🌐 C | 📅 2022-02-03 - Tomb Raider: Chronicles disassembly translated to C source code.
* [TR2Main](https://github.com/Arsunt/TR2Main) ⭐ 203 | 🐛 18 | 🌐 C++ | 📅 2023-08-06 - Open source reimplementation of Tomb Raider II (1997) via DLL injection into the original EXE, decompiling and fixing the original game while reading its original level/asset data.
* [KAIN2 (decomp)](https://github.com/Gh0stBlade/KAIN2) ⭐ 173 | 🐛 2 | 🌐 C | 📅 2024-04-24 - Decompiled source code for Legacy of Kain: Soul Reaver (Crystal Dynamics, 1999), based on the PC build.
* [Tomb-Editor](https://github.com/TombEngine/Tomb-Editor) ⭐ 125 | 🐛 203 | 🌐 C# | 📅 2026-08-18 - Level editor for the classic Tomb Raider engines and custom engines such as TombEngine and TRX.
* [soul-re (decomp)](https://github.com/fmil95/soul-re) ⭐ 77 | 🐛 1 | 🌐 C | 📅 2026-06-30 - Matching decompilation of Legacy of Kain: Soul Reaver (PS1).
* [TR2X](https://github.com/LostArtefacts/TR2X) ⚠️ Archived - Open-source enhancement/remaster project for Tomb Raider II, based on decompilation and reading the original game data.
* [TR-Rando](https://github.com/LostArtefacts/TR-Rando) ⭐ 62 | 🐛 54 | 🌐 C# | 📅 2026-07-04 - Randomizer for Tomb Raider I-III and Remastered, modifying item pickups, secrets, enemies, Lara's appearance, level order, and text.
* [trview](https://github.com/chreden/trview) ⭐ 43 | 🐛 52 | 🌐 C++ | 📅 2026-08-18 - Level visualizer for Tomb Raider 1-5 with speedrunning in mind. View room layouts, triggers, and analyze route possibilities.
  * Formats: .TR2, .TR4, .TRC, .PHD
* [TR2-Level-Viewer](https://github.com/suruz/TR2-Level-Viewer) ⭐ 35 | 🐛 2 | 🌐 C# | 📅 2026-01-28 - Cross-platform Unity level viewer for the classic Tomb Raider II.
* [cdcEngineTools](https://github.com/Gh0stBlade/cdcEngineTools) ⭐ 29 | 🐛 4 | 🌐 C | 📅 2019-09-04 - Extracts DRM and CDRM resource archives from CDC Engine Tomb Raider games across PC, PS2, PS3, PSP, Xbox 360, and Wii platforms.
  * Games: Tomb Raider: Legend, Anniversary, Underworld.
  * Formats: DRM, CDRM (compressed DRM blocks), BIGFILE.
* [ModelEx](https://github.com/TheSerioliOfNosgoth/ModelEx) ⭐ 28 | 🐛 6 | 🌐 C# | 📅 2025-04-10 - Tool for viewing and exporting 3D models from Legacy of Kain and CDC engine games.
  * Games: Legacy of Kain (Soul Reaver 1 & 2, Defiance), Gex 3: Deep Cover Gecko, Tomb Raider (Legend, Anniversary).
* [CDCE.TIGER.Tool](https://github.com/Ekey/CDCE.TIGER.Tool) ⭐ 28 | 🐛 4 | 🌐 C# | 📅 2025-08-06 - Extracts TIGER archives and dumps DRM resources from CDC Engine (Foundation Engine) games.
  * Games: Tomb Raider (2013), Rise of the Tomb Raider, Shadow of the Tomb Raider, Lara Croft and the Temple of Osiris, Marvel's Avengers.
* [gex64decomp (decomp)](https://github.com/matbourgon/gex64decomp) ⭐ 27 | 🐛 12 | 🌐 C | 📅 2026-07-27 - Matching decompilation of Gex 64: Enter the Gecko (N64).
* [dxhr](https://github.com/rrika/dxhr) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2025-12-20 - Tools for processing Deus Ex: Human Revolution data files.
  * Features: Blender extensions for loading unit and mesh files (`cdcunit.py`, `cdcmesh.py`), command-line DRM file explorer, FUSE mount for BIGFILE.000 archives.
  * Formats: DRM, BIGFILE.
* [cdcEngine](https://github.com/TheIndra55/cdcEngine) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2024-12-24 - Partial decompilation and reverse engineering research of the CDC engine, based on Tomb Raider: Legend.
* [Gibbed.CrystalDynamics](https://github.com/gibbed/Gibbed.CrystalDynamics) ⭐ 17 | 🐛 4 | 🌐 C# | 📅 2026-06-24 - Archive tools for Crystal Dynamics games.
  * Games: Tomb Raider (2013), Deus Ex: Human Revolution.
* [TR7AE-level-viewer](https://github.com/TheIndra55/TR7AE-level-viewer) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2024-05-25 - Web-based level viewer using three.js for CDC engine Tomb Raider titles.
  * Games: Tomb Raider: Legend, Tomb Raider: Anniversary.
* [FoundationEngine](https://github.com/Gh0stBlade/FoundationEngine) ⭐ 8 | 🐛 0 | 🌐 CMake | 📅 2023-08-16 - Reverse-engineered source code for Crystal Dynamics' CDC Foundation Engine, based on Legacy of Kain: Soul Reaver 2 (lc2) PC build artifacts.
* [TR42PRJ](https://github.com/sapper-trle/TR42PRJ) ⭐ 8 | 🐛 0 | 🌐 Pascal | 📅 2025-10-21 - Converts a Tomb Raider 4 `.TR4` level file back into a TRLE project `.prj` file.
* [TR7AE-Mesh-Exporter](https://github.com/Raq1/TR7AE-Mesh-Exporter) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-11-14 - Noesis plugin for exporting meshes from Tomb Raider: Legend and Tomb Raider: Anniversary.
* [TR2Draw](https://github.com/Arsunt/TR2Draw) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2017-09-10 - Dynamic library implementing Tomb Raider II's graphic routines, a companion project to TR2Main.
* [Blood Omen 2 3D Rip Tools](https://www.moddb.com/games/blood-omen-2/downloads/blood-omen-2-3d-rip-tools) - A group of cli to export and manipulate blood omen 2 raw 3d model into wavefront and dds textures
* [TRosettaStone](https://opentomb.github.io/TRosettaStone3/trosettastone.html) - Extensive documentation on the Tomb Raider file formats (TR1-5).

### Custom Order Maid 3D2

* [COM3D2.ModelExportMMD](https://github.com/pleaserespond/COM3D2.ModelExportMMD) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2022-03-26 - Exports Custom Order Maid 3D2 models to MMD (MikuMikuDance) format.

### Cyan Worlds

* [Plasma](https://github.com/H-uru/Plasma) ⭐ 235 | 🐛 123 | 🌐 C++ | 📅 2026-08-18 - Cyan Worlds' open-sourced Plasma game engine (used by Myst Online: Uru Live / Uru: Ages Beyond Myst), reading the original Age/PRP file formats.
* [M4Revolution](https://github.com/tomysshadow/M4Revolution) ⭐ 93 | 🐛 0 | 🌐 C++ | 📅 2026-08-16 - Command line tool that fixes Myst IV: Revelation's video playback by re-encoding the game's proprietary cached texture/video data.
* [dirtsand](https://github.com/H-uru/dirtsand) ⭐ 40 | 🐛 10 | 🌐 C++ | 📅 2026-07-04 - Reference game server daemon (vault, auth, file/asset server) for Myst Online: Uru Live, implementing the Plasma engine's network protocol and Age/PRP asset distribution.
* [korman](https://github.com/H-uru/korman) ⭐ 35 | 🐛 58 | 🌐 Python | 📅 2026-08-01 - Blender add-on for creating and exporting Ages (PRP format) compatible with Cyan Worlds' Plasma engine and its open-source CyanWorlds.com Engine variant.
* [libhsplasma](https://github.com/H-uru/libhsplasma) ⭐ 34 | 🐛 8 | 🌐 C++ | 📅 2026-08-01 - Cross-platform library for reading/writing Plasma engine data files (PRP ages, textures, etc.) and the associated network protocol.
* [mystextract](https://github.com/erkyrath/mystextract) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-05-14 - Extracts the HyperTalk script code from the HyperCard stacks of the original 1993 Macintosh release of Myst.

### CyberConnect2

* [JAPI](https://github.com/Kapilarny/JAPI) ⭐ 11 | 🐛 2 | 🌐 C++ | 📅 2026-08-16 - Modding API for JoJo's Bizarre Adventure: All-Star Battle R, providing hooks into the game's CC2 engine and file formats.
* [Arrow-Forge](https://github.com/ImGoldenWind/Arrow-Forge) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2026-08-15 - File editing toolkit for JoJo's Bizarre Adventure: All-Star Battle R.
* [cc2\_anm\_export\_blender](https://github.com/maxcabd/cc2_anm_export_blender) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-10-05 - Blender exporter addon for .xfbin animation files used by CyberConnect2 games.
* [nuccbin](https://github.com/maxcabd/nuccbin) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2024-09-17 - Serializer/deserializer for nuccChunkBinary files from Naruto to Boruto: Shinobi Striker and Ultimate Ninja Storm Connections.
* [NUCC-010-Template-Library](https://github.com/KojoBailey/NUCC-010-Template-Library) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2024-09-04 - 010 Editor template library for CyberConnect2's XFBIN/NUCC container format and its chunk types (textures, nuccBinary sub-formats), aiming for one template covering all XFBINs.
* [nucc-cpp-library](https://github.com/KojoBailey/nucc-cpp-library) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2026-06-12 - C++ library for serialising and deserialising CyberConnect2 NUCC data, for projects that interact with XFBIN files.
* [nucc-cpp-parser](https://github.com/KojoBailey/nucc-cpp-parser) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2025-08-05 - Drag-and-drop terminal tool for unpacking CyberConnect2 NUCC XFBIN files into editable formats and repacking them.
* [japi-merging-rs](https://github.com/KojoBailey/japi-merging-rs) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-02-22 - JAPI plugin that merges XFBIN mod data for simpler, more compatible JoJo's Bizarre Adventure: All-Star Battle R modding. See also [JAPI-XFBIN-Merger](https://github.com/KojoBailey/JAPI-XFBIN-Merger) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-02-11, the earlier C++ version of this plugin.
* [Samurai-vs-Zombies-Data-Parser](https://github.com/KojoBailey/Samurai-vs-Zombies-Data-Parser) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2025-03-19 - C++ library to parse TXT data files from Samurai vs Zombies Defense.

### CyberFlix

* [DFET](https://github.com/M3tox/DFET) ⭐ 18 | 🐛 2 | 🌐 C++ | 📅 2026-07-25 - "DreamFactory Extraction Tool" extracts data from games built on CyberFlix's DreamFactory engine, fully supporting Titanic: Adventure Out of Time (and its demo) and partially DUST: A Tale of the Wired West.

### CyberStep (CosmicBreak)

* [CB.KAR.Tool](https://github.com/Ekey/CB.KAR.Tool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-10-20 - Tool for extracting KAR archives from CosmicBreak Universal.

### Cygames (Granblue Fantasy Relink)

* [GBFRBlenderTools](https://github.com/WistfulHopes/GBFRBlenderTools) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2026-07-29 - Blender addon for importing Granblue Fantasy Relink mesh models.
* [GBFR2Blender2GBFR](https://github.com/WistfulHopes/GBFR2Blender2GBFR) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2024-03-19 - Tools for importing/exporting animations and collision data for Granblue Fantasy Relink.

### Cygnus Studios (Raptor: Call of the Shadows)

* [dosraptor](https://github.com/skynettx/dosraptor) ⭐ 337 | 🐛 3 | 🌐 C | 📅 2024-03-22 - Original DOS source code (v1.2) for Cygnus Studios' Raptor: Call of the Shadows (published by Apogee Software, 1994), including the Apogee Sound System and a free DMX-library replacement (APODMX) in place of the proprietary DMX library.
* [raptor](https://github.com/skynettx/raptor) ⭐ 122 | 🐛 13 | 🌐 C | 📅 2026-08-16 - Reverse engineering and tooling project for Raptor: Call of the Shadows, working with the game's original data files.

### D3 Publisher

#### Earth Defense Force

* [EDFModLoader](https://github.com/BlueAmulet/EDFModLoader) ⭐ 57 | 🐛 9 | 🌐 C++ | 📅 2025-10-11 - Mod loader and format tool for Earth Defense Force games, handling .cpk archive extraction and modification.
* [sgott](https://github.com/zeddidragon/sgott) ⭐ 24 | 🐛 9 | 🌐 JavaScript | 📅 2026-07-29 - SGO archive transformation tool for Earth Defense Force games.
* [edf-tools](https://github.com/AUK233/edf-tools) ⭐ 6 | 🐛 1 | 🌐 C++ | 📅 2026-08-14 - Tools for modding Sandlot's Earth Defense Force games.
* [blender-mdb-addon](https://github.com/BlueAmulet/blender-mdb-addon) ⚠️ Archived - Blender importer for Earth Defense Force 4.1 and 5 .mdb model files.

### Datamost (The Bilestoad)

* [bilestoad-apple2](https://github.com/historicalsource/bilestoad-apple2) ⭐ 30 | 🐛 0 | 📅 2019-04-20 - Original developer source code and data for The Bilestoad (Datamost, 1983), an Apple II gladiatorial combat game.

### Disney Interactive

#### Toontown Online

* [omUlette](https://github.com/lifelandman/omUlette) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2026-03-21 - Lightweight exporter for Panda3D `.egg` files (used in Toontown) that works without Panda3D installed.

#### Club Penguin

* [Waddle Forever](https://github.com/nhaar/Waddle-Forever) ⭐ 162 | 🐛 21 | 🌐 TypeScript | 📅 2026-08-17 - Singleplayer, playable digital preservation archive of Club Penguin, serving the original Flash client/assets from various points in the game's history.
  * See also [Cvolton's fork](https://github.com/Cvolton/Waddle-Forever) ⭐ 0 | 🐛 0 | 📅 2026-02-22.
* [yukon](https://github.com/wizguin/yukon) ⭐ 129 | 🐛 11 | 🌐 JavaScript | 📅 2025-08-23 - HTML5 reimplementation of the Club Penguin client, reading original game assets.
* [yukon-server](https://github.com/wizguin/yukon-server) ⭐ 51 | 🐛 8 | 🌐 JavaScript | 📅 2026-02-17 - Server implementation for the yukon Club Penguin client reimplementation.

### Deck13 Interactive (Lords of the Fallen)

* [LOTF.PKG.Tool](https://github.com/Ekey/LOTF.PKG.Tool) ⚠️ Archived - Tool for extracting PKG archives from Lords of the Fallen (2014).

### Delphine Software

#### Another World

* [Another World Bytecode Interpreter](https://github.com/fabiensanglard/Another-World-Bytecode-Interpreter) ⭐ 912 | 🐛 7 | 🌐 C++ | 📅 2025-03-05 - Cleaned-up, well-documented interpreter ("Fabother World") for Another World / Out of This World's custom polygon-based bytecode VM, reading the original game's .bank resource files.
* [rawgl](https://github.com/cyxx/rawgl) ⚠️ Archived - Reimplementation of the engine used in Another World / Out of This World, reading the original DOS/Amiga/Atari ST/3DO release's data files; renders with SDL/OpenGL.
  * See also [another\_js](https://github.com/cyxx/another_js) ⚠️ Archived, an HTML5 port of the same reimplementation, and [infernal\_js](https://github.com/cyxx/infernal_js) ⚠️ Archived, an HTML5 port of Eric Chahi's earlier Amstrad CPC game Infernal Runner.
* [aw64](https://github.com/jnmartin84/aw64) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2022-08-23 - Nintendo 64 port of the Another World Bytecode Interpreter, reading the original game's .bank resource files.

#### Fade to Black

* [f2bgl](https://github.com/cyxx/f2bgl) ⚠️ Archived - Re-implementation of the engine used in Fade to Black (1995), reading the original PC release's data files. See also [usineur's fork](https://github.com/usineur/f2bgl) ⭐ 20 | 🐛 1 | 🌐 C++ | 📅 2022-03-01 with PlayStation Vita and Nintendo Switch ports.

#### Flashback

* [REminiscence](https://github.com/cyxx/REminiscence) ⚠️ Archived - Reimplementation of the engine used in Flashback: The Quest for Identity, reading the original DOS/Amiga/3DO/CD32 release's data files.
* [extract\_fb\_genesis](https://github.com/cyxx/extract_fb_genesis) ⚠️ Archived - Extracts and converts data files from the Flashback Sega Genesis ROM (Europe, Japan, USA, and September 1992 prototype versions).

#### Igor

* [igor](https://github.com/cyxx/igor) ⚠️ Archived - Reimplementation of the interpreter for Igor: Objetivo Uikokahonia, reading the original game's data files.

### DeLyric Games (Target)

* [target\_ripper](https://github.com/Yagotzirck/target_ripper) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2018-09-24 - Resource extractor for Target (1998, Windows).

### Demiurge Studios

* [DS.SAR.Tool](https://github.com/Ekey/DS.SAR.Tool) ⚠️ Archived - Tool for extracting SAR archives from Demiurge Studios titles.
  * Games: Puzzle & Glory, Marvel Puzzle Quest, SEGA Heroes: Match-3 RPG Quest.

### Di Gi Charat

* [di-gi-charat-hacktools](https://github.com/karmic64/di-gi-charat-hacktools) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2024-01-03 - Hacking and translation tools for Di Gi Charat: DiGiCommunication (GBA).
* [dgcf-hacktools](https://github.com/karmic64/dgcf-hacktools) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2022-03-06 - Translation and hacking tools for Di Gi Charat Fantasy (PC).

### Digital Extremes

#### The Darkness II

* [TheDarknessIIDecompiled](https://github.com/FromDarkHell/TheDarknessIIDecompiled) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2020-11-03 - Decompiled Lua source code extracted from The Darkness II (2012), useful as a reference for modding and format research.

### Digital Anvil (Freelancer)

* [Librelancer](https://github.com/Librelancer/Librelancer) ⭐ 603 | 🐛 88 | 🌐 C# | 📅 2026-08-17 - Open-source reimplementation of the Freelancer engine in C# and OpenGL, requiring a Freelancer installation for original game data.

### Digital Illusions (SkyRoads)

* [skyhigh\_releases](https://github.com/kaimitai/skyhigh_releases) ⭐ 14 | 🐛 1 | 📅 2022-07-02 - Releases for the Sky High SkyRoads editor, covering the 1993 DOS game's level and graphics data.

### Distinctive Software (Stunts)

* [restunts2](https://github.com/dstien/restunts2) ⭐ 5 | 🐛 0 | 🌐 Assembly | 📅 2025-10-17 - Reverse engineering and modernization effort for Stunts (1990, DOS), using Ghidra analysis and Open Watcom to port the original executable to portable C while preserving behavior; supports building fully-ported or hybrid original/ported executables.

### Dogbyte Games

* [DB.XPAK.Tool](https://github.com/Ekey/DB.XPAK.Tool) ⚠️ Archived - Tool for extracting XPAK archives from Dogbyte Games racing titles.
  * Games: Offroad Legends, Offroad Legends 2.

### Doki Denki Studio (Piglet's Big Game)

* [pbg (decomp)](https://github.com/tgsm/pbg) ⭐ 15 | 🐛 1 | 🌐 C | 📅 2026-08-18 - Matching decompilation of Piglet's Big Game (GameCube).

### DOKA Studios

* [reSL (decomp)](https://github.com/konovalov-aleks/reSL) ⭐ 37 | 🐛 6 | 🌐 C++ | 📅 2026-08-08 - Matching decompilation of ShortLine v1.1.

### Double Fine (Psychonauts, Costume Quest)

* [noclip.website (Psychonauts)](https://github.com/magcius/noclip.website/tree/main/src/psychonauts) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Psychonauts viewer.
* [DoubleFine-Explorer](https://github.com/bgbennyboy/DoubleFine-Explorer) ⭐ 66 | 🐛 2 | 🌐 Pascal | 📅 2023-11-05 - Explorer, viewer, and dumper for Double Fine game archives (Moai, Buddha, Remonkeyed engines). View, extract, and convert text, speech, music, scripts, and images.
  * Games: Broken Age, Brutal Legend, Costume Quest, Costume Quest 2, Day of the Tentacle Remastered, Full Throttle Remastered, Grim Fandango Remastered, Headlander, Iron Brigade, Massive Chalice, Psychonauts (Steam/GOG), Stacking, The Cave, Kinect Party.
* [Psychonauts-Explorer](https://github.com/bgbennyboy/Psychonauts-Explorer) ⭐ 14 | 🐛 2 | 🌐 Pascal | 📅 2018-05-22 - Tool to extract, view, and convert game resources from Psychonauts, supporting archives, DDS images, audio extraction (WAV/OGG), and PC/Xbox/PS2 versions.
* [BLPT](https://github.com/gdkchan/BLPT) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2016-03-18 - Package extractor/inserter for Brutal Legend's \*.\~h and \*.\~p archive files.
* [CostumeQuest-Decomp (decomp)](https://github.com/Costume-Quest-Modding/CostumeQuest-Decomp) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2025-06-18 - Matching decompilation of Costume Quest (PC).

### Dynamix / Sierra

#### Tribes Series

* [Tribes 2 3D Studio MAX Export Plug-in](https://www.moddb.com/games/tribes-2/downloads/tribes-2-3d-studio-max-export-plug-in) - Export plugin for 3D Studio MAX v2.5 for creating and modifying objects in Tribes 2. Requires 3D Studio MAX (professional 3D modeling suite, recommended for advanced users).
* [Tribes: Vengeance Editing Tools](https://www.moddb.com/games/tribes-vengeance/downloads/tribes-vengeance-editing-tools) - Beta release of TribesEd for creating Tribes: Vengeance maps.
* [Tribes 1.40 LoDFix plugin](https://www.moddb.com/games/tribes/downloads/tribes-140-lodfix-plugin) - Plugin that fixes a known level of detail (LOD) issue with certain weapons in Tribes. Affects users with field of view (FOV) higher than default. Place LoDFix.dll in plugins folder. Created by Groove (v1.40).

### Edelweiss

#### Sakuna: Of Rice and Ruin

* [sakunaTool](https://github.com/LinkOFF7/sakunaTool) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2022-07-19 - Tool for extracting and packaging ARC archive files from Sakuna of Rice and Ruin, with support for LZ4 compression control.
* [SakunaTools](https://github.com/Kaplas80/SakunaTools) ⭐ 10 | 🐛 2 | 🌐 C# | 📅 2022-09-16 - Tools for translating Sakuna: Of Rice and Ruin.

### Ecstatica

* [Ecstatica Recompiled](https://github.com/spacefarergames/EcstaticaRecompiled) ⭐ 20 | 🐛 2 | 🌐 Assembly | 📅 2026-05-20 - Full 64-bit native port and recompilation of Ecstatica 1 and 2 for modern Windows, reverse-engineering game structures and assets.

### Eden Games (Test Drive Unlimited 2)

* [tdups2checksum](https://github.com/itsmattkc/tdups2checksum) ⭐ 12 | 🐛 0 | 🌐 C | 📅 2022-02-17 - Reverse-engineered and reimplemented checksum algorithm for Test Drive Unlimited (PS2) save game files.
* [TDU2.BIG.Tool](https://github.com/Ekey/TDU2.BIG.Tool) ⚠️ Archived - Tool for extracting BIG archives from Test Drive Unlimited 2.

### EgoSoft (X4)

* [X4Tools](https://github.com/REDxEYE/X4Tools) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-10-29 - Standalone plugin for importing and exporting assets from X4 game.

### Eighting (Naruto: Gekitō Ninja Taisen!)

* [noclip.website (Naruto: Gekitō Ninja Taisen! 4)](https://github.com/magcius/noclip.website/tree/main/src/NarutoGNT4) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser stage viewer for Naruto: Gekitō Ninja Taisen! 4 (GameCube), the Japan-only fourth entry in the series known in the West as Naruto: Clash of Ninja. Unpacks the game's FPK archives and their compression.

### Electronic Arts

#### Frostbite

* [Frostbite-Scripts](https://github.com/NicknineTheEagle/Frostbite-Scripts) ⭐ 122 | 🐛 9 | 🌐 Python | 📅 2026-01-10 - Scripts and tools for Frostbite engine games.

##### Battlefield Series

* [BF1942 3dsmax 8 plugin](https://www.moddb.com/games/battlefield-1942/downloads/bf1942-3dsmax-8-plugin) - Plugin for 3DS Max 8 to import/export Battlefield 1942 meshes and animations. Extracted from the Battlefield Mod Development Toolkit 1.0B by DICE.
* [BF2 Maya 4-6 Tools](https://www.moddb.com/games/battlefield-2/downloads/bf2-maya-4-6-tools) - Official Battlefield 2 tools for Maya 4-6 for exporting and importing game assets. Also included with the BF2 Editor but provided separately here.
* [BF42 3dsMax plugins 2.762](https://www.moddb.com/mods/battlefield-2-play-for-free-mod/downloads/bf42-3dsmax-plugins-2762) - 3DS Max plugins for Battlefield 2/1942 for Max 9 and higher (v2.762).
* [BGF Heightmap Converter](https://www.moddb.com/games/battlefield-2/downloads/bgf-heightmap-converter-utility) - Utility for viewing and resizing heightmap (.RAW) files. Primarily intended for converting maps from Battlefield 1942 or Battlefield Vietnam to Battlefield 2, but can also be used to change a BF2 map to a different size.
* [DDS Viewer Plugin (Battlefield Vietnam)](https://www.moddb.com/games/battlefield-vietnam/downloads/dds-viewer-plugin) - Plugin for previewing DDS files in folder preview window before conversion. Useful for mappers and modders.
* [NVIDIA DDS Utilities (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/nvidia-dds-utilities) - Collection of utilities for manipulating DDS image files: nvDXT (command-line binary), detach (extracts MIP levels), stitch (recombines MIP levels), and readDXT (reads compressed images).
* [NVIDIA Texture Atlas Tool (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/nvidia-texture-atlas-tool) - A collection of tools for creating texture atlases, which can help to increase batch sizes.
* [POE2 3DS Max 6-8 BF2 Tools (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/poe2-3ds-max-6-8-tools) - POE2's advanced rendition of the 3DS Max BF2 tools (for Max 6-8).
* [POE2 3DS Max 9 BF2 Tools (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/poe2-3ds-max-9-bf2-tools) - POE2's advanced rendition of the 3DS Max BF2 tools (for Max 9).
* [Windows Texture Viewer v089b (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/windows-texture-viewer-v089b) - Tool for viewing .dds texture files. Shows resolution, DDS format, mipmap count, and alpha channel used by HUD.
* [Texture Tool 0.2 (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/texture-tool-0-2) - Ecomap that automates the texturing of BF2 maps.
* [Clan Tool (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/clan-tool) - Advanced Tactical Center for Battlefield 2. Connect team members to online sessions, create detailed tactics together in real time. Includes zoom, text tools, export tactics, and Custom Map Wizard.
* [Dragon UnPACKer (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/dragon-unpacker) - Tool for viewing and extracting files from game archive formats (e.g., Quake 2 PAK files). Includes HyperRipper for scanning files for known formats.
  * Formats: MP3, OGG, WAV, AVI, TGA, BMP.

##### Star Wars: Battlefront

* [FrostyToolsuite](https://github.com/CadeEvs/FrostyToolsuite) ⭐ 751 | 🐛 21 | 🌐 C# | 📅 2024-09-26 - Comprehensive modding platform for games running on DICE's Frostbite engine. Provides an editor and plugin SDK for browsing, editing, and exporting Frostbite game assets.
* [Bad-Company-2-Map-Editor](https://github.com/Powback/Bad-Company-2-Map-Editor) ⭐ 44 | 🐛 9 | 🌐 C# | 📅 2020-09-28 - Frostbite engine map editor for Battlefield: Bad Company 2; supports loading, editing, and saving terrain, models, and textures.
* [IceBloc](https://github.com/marv7000/IceBloc) ⭐ 24 | 🐛 1 | 🌐 C# | 📅 2024-04-15 - Frostbite asset extractor.
* [ZeroMunge](https://github.com/Gametoast/ZeroMunge) ⭐ 10 | 🐛 12 | 🌐 C# | 📅 2026-06-07 - Reimplementation of Star Wars: Battlefront's asset 'munge' build pipeline, converting mod source assets into the game's native packed formats.
* [Frostbite 3ds Max Scripts](https://github.com/Highflex/frostbite_3dsmax_scripts) ⭐ 9 | 🐛 0 | 🌐 Groff | 📅 2016-05-22 - 3ds Max scripts for importing Frostbite engine assets, enabling mesh and skeleton extraction from Battlefield and other Frostbite games.
* [Gametoast Documentation](https://github.com/Gametoast/Documentation) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-01-16 - Wiki, source files, and example projects documenting Star Wars: Battlefront and Battlefront II (SWBFI & SWBFII) file formats and modding.
* [ZeroWorldStats](https://github.com/Gametoast/ZeroWorldStats) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2018-08-22 - Extracts and reports statistics from Star Wars: Battlefront world/level files.
* [ZeroLocalizationTool](https://github.com/Gametoast/ZeroLocalizationTool) ⭐ 2 | 🐛 7 | 🌐 C# | 📅 2026-06-14 - Extracts and edits localization strings from Star Wars: Battlefront's packed data files.
* [SWBF2-ODF](https://github.com/Gametoast/SWBF2-ODF) ⭐ 2 | 🐛 0 | 📅 2017-11-25 - VS Code extension providing IntelliSense/syntax support for Star Wars: Battlefront II's ODF (Object Definition Format) files.
* [data\_PSP\_SND](https://github.com/Gametoast/data_PSP_SND) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-05-04 - Star Wars: Battlefront II (PSP/PS2) sound-effect build project, documenting and converting the shared PSP/PS2 .sfx (VAG) audio format.
* [MeshViewer\_OpenGL](https://github.com/Gametoast/MeshViewer_OpenGL) ⭐ 0 | 🐛 0 | 📅 2021-04-01 - OpenGL viewer for Star Wars: Battlefront II's native .msh mesh assets.
* [StarWars Battlefront unpacker / decoder](https://www.moddb.com/games/star-wars-battlefront/downloads/starwars-battlefront-unpacker-decoder) - Custom toolset for unpacking and extracting Star Wars: Battlefront archives.
* [Star Wars: Battlefront Modification Tools](https://www.moddb.com/games/star-wars-battlefront/downloads/star-wars-battlefront-modification-tools) - Official modding tools for creating levels in Star Wars: Battlefront. Originally from Game Front. Download subject to End User License Agreement terms.
* [3D Object Converter (Star Wars Battlefront II)](https://www.moddb.com/games/star-wars-battlefront-ii/downloads/3d-object-converter) - Polygon-based 3D object file format converter supporting 440 file formats.

#### RenderWare

*See also [RenderWare](#renderware) for general engine tools.*

##### Criterion Games

* [libbndl](https://github.com/Bo98/libbndl) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2026-08-04 - Library for reading BUNDLE archives used in Burnout Paradise.
* [burnout-data-tool](https://github.com/Sokka06/burnout-data-tool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-07-07 - Multi-purpose tool for Burnout 3 and Burnout Revenge archive and asset management.

#### EAGL / Black Box / Other

* [Castaway (decomp)](https://github.com/HaydnTrigg/Castaway) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2026-01-21 - Matching decompilation of The Sims 2: Castaway.

##### Need for Speed Series

* [noclip.website (Need for Speed: Most Wanted)](https://github.com/magcius/noclip.website/tree/main/src/NeedForSpeedMostWanted) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Need for Speed: Most Wanted viewer.
* [OpenNFS](https://github.com/OpenNFS/OpenNFS) ⭐ 820 | 🐛 4 | 🌐 C++ | 📅 2026-06-21 - Reverse-engineered asset loaders for Need for Speed games 1-6 (PC and PSX), extracting tracks, cars, images, music, and other assets for modern engine integration.
* [NFSPluginSDK](https://github.com/berkayylmao/NFSPluginSDK) ⭐ 49 | 🐛 3 | 🌐 C++ | 📅 2024-12-22 - Reverse-engineered compiled types for BlackBox era Need for Speed games; SDK for creating plugins/script mods.
* [Binary](https://github.com/NFSCO/Binary) ⭐ 48 | 🐛 0 | 🌐 C# | 📅 2024-06-15 - Tool for editing Black Box Need for Speed binary .BIN, .BUN, .LZC files.
* [NFS.BIN.Tool](https://github.com/Ekey/NFS.BIN.Tool) ⭐ 20 | 🐛 3 | 🌐 C# | 📅 2026-07-28 - Tool for extracting ZZDATA archives from NFS console games.
* [Icebreaker](https://github.com/R-033/icebreaker) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2023-10-16 - NIS (NFS Most Wanted cutscene files) editing tool.
* [UCGT](https://github.com/NI240SX/UCGT) ⭐ 12 | 🐛 0 | 🌐 Java | 📅 2026-07-18 - NFS Undercover geometry editor (file compiler/decompiler).
* [MAD x VP6 x MPC x MPV x WMV Compiler](https://github.com/bluesky-dev12/MAD-x-VP6-x-MPC-x-MPV-x-WMV-Compiler) ⭐ 9 | 🐛 2 | 🌐 Rust | 📅 2025-04-20 - Compilation of tools for compiling WMV, MAD, VP6, MPC and MPV video formats for Black Box games.
* [HighStakesRE](https://github.com/e-rk/HighStakesRE) ⭐ 9 | 🐛 0 | 🌐 GDScript | 📅 2026-04-08 - Reverse-engineered remake of Need for Speed 4: High Stakes in Godot with tools to convert and import original game assets (cars, tracks).
* [NFS Carbon PDFData Compiler](https://github.com/bluesky-dev12/PFDataCompiler) ⭐ 8 | 🐛 3 | 🌐 C++ | 📅 2024-03-27 - Helper to convert music to NFS Carbon format.
* [Vivianne](https://github.com/TheXDS/Vivianne) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2026-08-10 - NFS 3/4 All-in-one VIV and FSH/QFS editor that aims to provide you with tools to edit textures, car performance and fedata files.
* [AutoZone Hot Pursuit](https://github.com/americusmaximus/AZHP) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2025-08-26 - Open-source re-implementation of Need for Speed: Hot Pursuit (1998) with reverse-engineered resource management, rendering, and original game asset support.
* [NFS.Unpacker](https://github.com/bluesky-dev12/NFS.Unpacker) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2024-01-28 - Tool for unpacking and extracting Need for Speed game files. Directly addresses NFS asset format extraction and reverse engineering.
* [NFS SPEECHTOOL](https://github.com/TheUnpunished/SpeechTool) ⭐ 7 | 🐛 1 | 🌐 Java | 📅 2023-09-10 - Speech audio files editor for NFS ProStreet, Undercover & World.
* [NFS TMXTOOL](https://github.com/TheUnpunished/tmxtool) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2024-03-15 - TMX audio files encoder for NFS ProStreet, Undercover & World.
* [nfshpr\_exporter](https://github.com/BlueAmulet/nfshpr_exporter) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-11-18 - Blender addon to export models in Need for Speed: Hot Pursuit Remastered's file format.

#### SAGE / W3D

##### Command & Conquer Series

* [CnC\_Red\_Alert](https://github.com/electronicarts/CnC_Red_Alert) ⚠️ Archived - Official source code release for Command & Conquer: Red Alert.
* [CnC\_Generals\_Zero\_Hour](https://github.com/electronicarts/CnC_Generals_Zero_Hour) ⚠️ Archived - Official source code release for Command & Conquer: Generals and Zero Hour.

  * Tools: Level Edit (public editor), Free Dedicated Server (FDS) build.
  * Dependencies: DirectX (8+), RAD Bink, RAD Miles Sound System, NvDXTLib, Umbra, GameSpy, SafeDisk API, Microsoft Cab, RTPatch, Lightscape.
* [Command & Conquer: Renegade (source release)](https://github.com/electronicarts/CnC_Renegade) ⚠️ Archived - Official source code release for C\&C Renegade and tools (archived; GPLv3 with additional terms).
* [CNC\_TS\_and\_RA2\_Mission\_Editor](https://github.com/electronicarts/CNC_TS_and_RA2_Mission_Editor) ⭐ 182 | 🐛 0 | 🌐 C++ | 📅 2024-04-15 - FinalSun & FinalAlert2 level editors for Command & Conquer: Tiberian Sun and Red Alert 2.
* [RA3Bar-RA3Launcher](https://github.com/lanyizi/RA3Bar-RA3Launcher) ⭐ 127 | 🐛 3 | 🌐 C++ | 📅 2023-02-07 - Reimplementation of RA3.exe, the Command & Conquer: Red Alert 3 game launcher.
* [C\&C big extractor](https://www.moddb.com/groups/tiberium-essence-fans/downloads/cc-big-extractor) - Tool for extracting files from Command & Conquer BIG archive files. Supports: Generals, Generals: Zero Hour, Tiberium Wars, Kane's Wrath, Red Alert 3, Red Alert 3: Uprising, Tiberian Twilight. Originally uploaded by bibber.
* [Command & Conquer 3 Asset Extractor](https://www.moddb.com/groups/tiberium-essence-fans/downloads/command-conquer-3-asset-extractor) - This program can extract asset files from C\&C streams. This program can extract asset files from C\&C streams. You can also extract models (W3DAnimation, W3DCollisionBox, W3DContainer, W3DHierarchy, W3DMesh), textures (OnDemandTexture, Texture) and sounds/music (AudioFile, AudioFileMP3Passthrough,...)
* [C\&C: Renegade Official Modding Tools](https://www.moddb.com/games/cc-renegade/downloads/cc-renegade-official-modding-tools) - Official set of modding tools for Command & Conquer: Renegade.
* [CnC Renegade Tools](https://www.moddb.com/games/cc-renegade/downloads/cnc-renegade-tools) - CnC Renegade Tools by Westwood to help modders in making mods for Renegade.
* [Final Big (C\&C: Generals)](https://www.moddb.com/games/cc-generals/downloads/final-big) - No further information avaliable.
* [Final Big 3 (C\&C: Generals)](https://www.moddb.com/games/cc-generals/downloads/final-big-3) - Version 0.2 released March 5th, 2003.
* [Gmax+RenX+Renegade Public Tools (C\&C: Generals Zero Hour)](https://www.moddb.com/games/cc-generals-zero-hour/downloads/gmaxrenxrenegade-public-tools) - This contains 3 modelling tools for editing C\&C Generals and Renegade.

#### SSX

* [SSX Collection Multitool](https://github.com/GlitcherOG/SSX-Collection-Multitool) ⭐ 22 | 🐛 4 | 🌐 C# | 📅 2026-07-25 - Collection of tools for the SSX franchise.
* [ssx (decomp)](https://github.com/ssxdecomp/ssx) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2026-03-20 - Matching decompilation of SSX (2000).
* [ssx3 (decomp)](https://github.com/ssxdecomp/ssx3) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - Matching decompilation of SSX 3 (2003).
* [ssxdvd (decomp)](https://github.com/ssxdecomp/ssxdvd) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-07-03 - Matching decompilation of SSX Tricky (2001).
* [SSX-Research](https://github.com/Linkz64/SSX-Research) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2022-10-27 - Documentation of SSX data structures (models, textures, audio, and more).
* [Icesaw-SSX-Level-Editor-Plugin](https://github.com/GlitcherOG/Icesaw-SSX-Level-Editor-Plugin) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-07-13 - Unity plugin for editing SSX levels exported by the SSX Collection Multitool (instances, triggers, effects).
* [SSX-Level-Viewer](https://github.com/GlitcherOG/SSX-Level-Viewer) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2023-06-07 - Unity-based viewer for SSX levels.
* [SSX-Library](https://github.com/GlitcherOG/SSX-Library) ⭐ 3 | 🐛 15 | 🌐 C# | 📅 2026-08-17 - C#/.NET library for extracting, creating, and modifying SSX game files, serving as a framework for GUI/CLI modding tools.
* [SSX-Terrain-Editor](https://github.com/Linkz64/SSX-Terrain-Editor) ⭐ 2 | 🐛 0 | 🌐 GDScript | 📅 2025-07-26 - Godot-based editor for modding SSX terrain bezier surfaces, companion to the SSX Collection Multitool (currently SSX Tricky only).
* [bxtools](https://github.com/Linkz64/bxtools) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-06-02 - Blender plugin for modding SSX games, currently focused on SSX Tricky level editing for the SSX Collection Multitool's JSON project format.

#### Fountain of Dreams

* [fod](https://github.com/devinsmith/fod) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-08-19 - Reverse engineering and reimplementation of Fountain of Dreams (1990 DOS game). Decodes TPICT title screen and character creation resources from the EXEPACK-packed executables; internal format documentation hosted alongside the repo.

#### General Tools

* [EA-Graphics-Manager](https://github.com/bartlomiejduda/EA-Graphics-Manager) ⭐ 34 | 🐛 7 | 🌐 Python | 📅 2026-04-20 - Handles FSH, SSH, XSH, PSH, GSH, ASH, QFS and MSH files from EA games. Parse, preview, and export/import graphics as DDS/PNG/BMP.
  * Games: FIFA series (97, 2000, 06, 09, 14, Street, UEFA Euro 2004), Need For Speed series (1994, II, High Stakes, Hot Pursuit 2, Porsche Unleashed, Carbon, Undercover), Medal of Honor series (Frontline, Rising Sun, Vanguard, European Assault), Madden NFL (06, 08), NHL series (2001, 2002, 2005, 07), NBA Live 97, MVP Baseball/NCAA Baseball (2005, 2007), SSX series, Cricket (2005, 2007), Harry Potter (Chamber of Secrets, Quidditch World Cup), Def Jam: Fight For New York, Fight Night Round 3, GoldenEye, SimCity 4 Deluxe, Triple Play 2000, ReBoot, F.A. Premier League Football Manager 2000, EA Playground (Wii), and more across PS1, PS2, PSP, PC, Xbox, Wii, and Zeebo platforms.
* [EA-Font-Manager](https://github.com/bartlomiejduda/EA-Font-Manager) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2026-03-08 - Handles EA font files (FFN, PFN, XFN, MFN, SFN formats). Preview, decode flags, edit character tables, and convert font images.
  * Games: FIFA 97, Need for Speed series (2, High Stakes, Hot Pursuit, Undercover), NBA Live 06-07, SSX series, MVP Baseball 2005, Medal of Honor: European Assault,
    NHL series, Def Jam: Fight for NY, Harry Potter and the Chamber of Secrets, The Sims, and more.
* [AZMCO](https://github.com/americusmaximus/AZMCO) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2026-05-05 - Open source implementation and reverse-engineering of Motor City Online (EA, 2001); parses original game data files.
* [n64graphics\_ci](https://github.com/DavidSM64/n64graphics_ci) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2019-04-11 - Converts between PNG and N64 CI (Color Index) texture formats (CI4, CI8). Handles N64-specific texture format conversions for game asset extraction.
* [EA-Loc-Manager](https://github.com/bartlomiejduda/EA-Loc-Manager) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-10-13 - Extract and import localization files (LOC format) from EA games. Supports UTF-8, UTF-16, and Latin-1 encodings.
  * Games: Harry Potter and the Chamber of Secrets (PS2), Medal of Honor: European Assault (Xbox), SSX On Tour, SSX Tricky (PS2), NHL 07 (PSP), and more.

### Enhance Games (Rez)

* [Rezun](https://github.com/XAYRGA/Rezun) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2025-04-03 - Unpacks .dat and .bnk files in Rez Infinite.

### Epic Games

#### Ken's Labyrinth

* [klabkit-sdl](https://github.com/kaimitai/klabkit-sdl) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2023-03-10 - Unofficial Ken's Labyrinth Editor's Toolkit (kkit/sdl) for editing the DOS game's level and resource data.

#### Radix: Beyond the Void

* [Rad-X](https://github.com/jval1972/Rad-X) ⭐ 44 | 🐛 4 | 🌐 Pascal | 📅 2025-08-07 - Remake/source port of Radix: Beyond the Void (1995, developed by Neural Storm Entertainment, published by Epic MegaGames), reading the original game's data files.

#### Jazz Jackrabbit 2

* [jazz2-native (Jazz² Resurrection)](https://github.com/deathkiller/jazz2-native) ⭐ 692 | 🐛 10 | 🌐 C++ | 📅 2026-08-13 - Open-source C++ reimplementation of Jazz Jackrabbit 2 (1998, Epic MegaGames), reading the original game's level, tileset and animation data; partially supports the JJ2+ extension and MLLE.
* [project-carrot](https://github.com/soulweaver91/project-carrot) ⭐ 39 | 🐛 20 | 🌐 C++ | 📅 2017-08-28 - Alternative open-source spiritual clone of the Jazz Jackrabbit 2 engine, reading the original game's data.
  * See also companion tools: [project-carrot-pcae](https://github.com/soulweaver91/project-carrot-pcae) ⭐ 2 | 🐛 3 | 🌐 C++ | 📅 2017-05-16 (animation extractor), [project-carrot-pclc](https://github.com/soulweaver91/project-carrot-pclc) ⭐ 3 | 🐛 2 | 🌐 C++ | 📅 2017-04-08 (level converter), [project-carrot-pctc](https://github.com/soulweaver91/project-carrot-pctc) ⭐ 2 | 🐛 1 | 🌐 C++ | 📅 2017-04-08 (tileset converter).
* [MLLE](https://github.com/Violet-CLM/MLLE) ⭐ 14 | 🐛 30 | 🌐 C# | 📅 2025-06-28 - Alternative multi-layer level editor for Jazz Jackrabbit 2 and related games, extending the original JCS level editor's format with additional features (e.g. JJ2+ infinite scrolling layers).
* [jazz2langtool](https://github.com/jindrapetrik/jazz2langtool) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2017-12-10 - Tool for reading and editing Jazz Jackrabbit 2 language files.

#### Fortnite

* [fortnite-aes-archive](https://github.com/dippyshere/fortnite-aes-archive) ⭐ 179 | 🐛 3 | 🌐 Python | 📅 2026-07-30 - Archive of AES decryption keys for Fortnite's PAK files, covering almost every dynamic and main PAK key.
* [JohnWickParse](https://github.com/SirWaddles/JohnWickParse) ⭐ 95 | 🐛 6 | 🌐 Rust | 📅 2021-10-19 - Parser for Fortnite PAK, uasset, and uexp files; provides serialization and extraction of game assets.
* [JFortniteParse](https://github.com/FabianFG/JFortniteParse) ⭐ 43 | 🐛 4 | 🌐 Kotlin | 📅 2025-11-03 - JVM Unreal Engine 4 asset parser library for Fortnite and Valorant; parses PAK files, textures, sounds, meshes, and localization files.
* [JModel](https://github.com/FabianFG/JModel) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2020-02-28 - Fortnite asset explorer for viewing and parsing PAK game files. Extracts Unreal Engine assets from game.

#### Unreal

* [UnrealNX](https://github.com/fgsfdsfgs/unreal_nx) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2022-12-26 - Nintendo Switch loader/port for Unreal (1998) and Unreal Gold, patching and running the official OldUnreal 227j aarch64-Linux binaries against the original game's installed data files.

#### Unreal Tournament

* [unreal-archive](https://github.com/unreal-archive/unreal-archive) ⭐ 57 | 🐛 19 | 🌐 Java | 📅 2026-08-17 - Unreal series mod community content indexer for Unreal, UT, UT2003/2004, and UT3; scans and categorizes mod file formats.

### Experience Inc. (Ray Gigant)

* [RG.BIN.Tool](https://github.com/Ekey/RG.BIN.Tool) ⚠️ Archived - Tool for extracting BIN archives from Ray Gigant.

### Eurocom

* [eurochef](https://github.com/eurotools/eurochef) ⭐ 21 | 🐛 23 | 🌐 Rust | 📅 2024-04-11 - Rust crates and utilities for Eurocom EngineX(T) files. Supports texture extraction, entity extraction, map extraction, filelist re-packing, EDB to Euroland 4 decompiler, and Blender plugin.
  * Games: Sphinx and the Shadow of Set Demo Disc, Buffy The Vampire Slayer: Chaos Bleeds, Sphinx and the Cursed Mummy, Spyro: A Hero's Tail, Robots, Predator: Concrete Jungle, Batman Begins, Ice Age 2: The Meltdown, Pirates of the Caribbean: At World's End, Ice Age: Dawn of the Dinosaurs, G-Force, Spider-Man 4, GoldenEye 007.
  * Formats: EDB, ELX, SFX, filelist (v4-v10).
  * Platforms: PC, Xbox, Xbox 360, GameCube, Wii, PlayStation 2.
* [sphinxtools](https://github.com/Swyter/sphinxtools) ⭐ 10 | 🐛 4 | 🌐 C | 📅 2016-11-30 - Unpackers and modding tools for the GameCube version of Sphinx and the Cursed Mummy. Extracts files from Filelist.000 containers, includes 010 Editor binary templates for EDB and SFX formats, and provides demuxing tools for GameCube IMA ADPCM audio.
* [eurosound-editor](https://github.com/eurotools/eurosound-editor) ⭐ 7 | 🐛 3 | 🌐 C# | 📅 2024-05-08 - .NET program reimplementing the original EuroSound tool by Eurocom for editing EngineX sound files.
* [eurosound-explorer](https://github.com/eurotools/eurosound-explorer) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2026-08-11 - C# tool for viewing parameters and extracting audio from SFX files compatible with Eurocom games.
* [blender-addon](https://github.com/eurotools/blender-addon) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-06-27 - Import and export Eurocom Scene Export (.ESE) files in Blender. Supports 3D models, skins + animations, cameras, maps and scripts.
* [Hero-s-Tail-Decomp](https://github.com/LivewireCB/Hero-s-Tail-Decomp) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2026-08-19 - In-progress decompilation of Spyro: A Hero's Tail.
* [hashcodes](https://github.com/eurotools/hashcodes) ⭐ 4 | 🐛 1 | 🌐 C | 📅 2023-07-07 - Public hashcodes list for various Eurocom games, useful for cross-checking.
* [gforce-tools](https://github.com/Swyter/gforce-tools) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2022-10-31 - 010 Editor binary templates for newer Eurocom/EngineX formats. Includes Filelist extractor script supporting version 7 (Athens 2004, Spyro: A Hero's Tail, Robots, Predator: Concrete Jungle, Batman Begins, Ice Age 2, Pirates of the Caribbean: At World's End, The Mummy: Tomb of the Dragon Emperor, 007: Quantum of Solace, Ice Age: Dawn of the Dinosaurs, G-Force, Dead Space: Extraction, Spider-Man 4 prototype, GoldenEye 007).
* [eurotext](https://github.com/eurotools/eurotext) ⭐ 2 | 🐛 1 | 🌐 C# | 📅 2026-01-03 - Custom tool to edit and inspect text-based EngineX spreadsheets.
* [binary-templates](https://github.com/eurotools/binary-templates) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-06-14 - 010 Editor binary templates for visually opening Sphinx and EngineX file formats.
* [euroland-elf-texture-extractor](https://github.com/eurotools/euroland-elf-texture-extractor) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-07-26 - Tool to extract textures from random EuroLand data files (\*.elf) that may not be inspectable otherwise (e.g. different versions that don't work with the EuroLand .exe).
* [sphinx-savegame-editor](https://github.com/eurotools/sphinx-savegame-editor) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-05-18 - C# tool to edit and view savegame files for The Sphinx and the Cursed Mummy game.
* [euroland\_exporters](https://github.com/eurotools/euroland_exporters) ⚠️ Archived - Import and export Eurocom Scene Export (.ESE) files in Blender; 3D models, skins + animations, cameras, maps and scripts.

### Eutechnyx (Ford Racing)

* [Caper (decomp)](https://github.com/dashr9230/Caper) ⭐ 4 | 🐛 1 | 🌐 C | 📅 2026-07-20 - Matching decompilation of The Italian Job (2001).
* [Gt2 (decomp)](https://github.com/dashr9230/Gt2) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-07-30 - Matching decompilation of Ford Racing (2000).

### Factor 5

#### Turrican

* [Turrican2Editor](https://github.com/GitExl/Turrican2Editor) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2020-11-27 - Level editor for the CDTV version of Turrican II, supporting tilemap, entity and starting-location editing.
* [TurricanExtract](https://github.com/GitExl/TurricanExtract) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-04-06 - Extracts levels, tiles, objects, graphics and palettes from the CDTV versions of Turrican 1 and Turrican 2.

### Falcom (Ys)

* [Ouroboros/Falcom](https://github.com/Ouroboros/Falcom) ⭐ 76 | 🐛 1 | 🌐 C | 📅 2023-08-24 - Tools for many Trails/Kiseki games and other Falcom titles.
  * Games: Trails in the Sky FC/SC/the 3rd, Trails of Zero, Trails of Azure, Trails of Cold Steel III/IV, Trails into Reverie, Trails through Daybreak, Zwei II.
* [KuroTools](https://github.com/nnguyen259/KuroTools) ⭐ 61 | 🐛 1 | 🌐 Python | 📅 2026-07-21 - Tools for working with Trails through Daybreak (Kuro no Kiseki) .dat, .mdl, and .tbl file formats; compatible with multiple games using the same engine
* [Trails-Research-Group/Doc](https://github.com/Trails-Research-Group/Doc) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-08-01 - Documentation for modding Trails/Kiseki series games with tools and techniques for modifying game assets (textures, models, scripts, animations)
* [Aureole](https://github.com/Kyuuhachi/Aureole) ⭐ 24 | 🐛 2 | 🌐 Rust | 📅 2026-02-19 - Suite of tools for modding the classic Trails/Kiseki games.
* [Legacy of the Wizard Tool](https://github.com/bbbradsmith/lotwtool) ⭐ 15 | 🐛 2 | 🌐 C# | 📅 2024-04-15 - Editor for Legacy of the Wizard (NES) / Dragon Slayer IV (Famicom, MSX1, MSX2), directly editing the original ROM's map, item, and other game data.
* [YsViDecomp (decomp)](https://github.com/GrantBenR/YsViDecomp) ⭐ 9 | 🐛 0 | 📅 2025-08-28 - Matching decompilation of Ys VI (Steam).
* [misc\_kiseki](https://github.com/eArmada8/misc_kiseki) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-12-02 - Collection of utilities for modding Falcom's Trails/Kiseki series including model injection, item table decoders, and name table decoders
* [Ys8\_IT3](https://github.com/eArmada8/Ys8_IT3) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-06-21 - Tool for extracting and repacking Ys VIII/IX asset data from IT3 format files; exports meshes, textures, and animations
* [ed8\_dlc\_tables](https://github.com/eArmada8/ed8_dlc_tables) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-04-13 - Python scripts for creating custom DLC tables (.tbl files) for Trails of Cold Steel and Tokyo Xanadu eX+
* [yumia\_switch\_icons](https://github.com/eArmada8/yumia_switch_icons) ⭐ 1 | 🐛 0 | 📅 2025-03-23 - Modding tool for Atelier Yumia that works with game file formats (.fdata files and resource databases)
* [unpackpka](https://github.com/eArmada8/unpackpka) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-08-19 - Tool to unpack .pka archive files to .pkg files for Legend of Heroes games (Trails of Cold Steel III/IV)

### FarSight Studios (The Pinball Arcade)

* [pba-tools](https://github.com/JayFoxRox/pba-tools) ⭐ 13 | 🐛 6 | 🌐 C | 📅 2025-08-15 - Converts The Pinball Arcade (PBA) proprietary table files to JSON, TGA, and OBJ/MTL for viewing table meshes and textures. Extraction/conversion only; cannot yet create PBA files.

### Fireglow Games

#### Sudden Strike

* [War Action](https://github.com/americusmaximus/WarAction) ⭐ 20 | 🐛 3 | 🌐 C++ | 📅 2026-05-06 - Open source implementation of Sudden Strike Gold (1.2.1), decompilation parsing original game data and assets.

#### Sudden Strike: Resource War

* [War Motion](https://github.com/americusmaximus/WarMotion) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2025-08-22 - Open source implementation of Sudden Strike: Resource War (2.4), decompilation reading original game data.

#### Sudden Strike II

* [War Storm](https://github.com/americusmaximus/WarStorm) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2025-08-26 - Open source implementation of Sudden Strike II Gold (2.2), decompilation parsing original game data.

#### Tools

* [War Tool Kit](https://github.com/americusmaximus/WarToolKit) ⭐ 10 | 🐛 1 | 🌐 C++ | 📅 2024-12-20 - Collection of tools for Sudden Strike game file formats (.pck graphics, .sue archives); includes pckView graphics viewer.

### Firefly Studios

#### Stronghold

* [Sourcehold](https://github.com/sourcehold/Sourcehold) ⭐ 278 | 🐛 30 | 🌐 C++ | 📅 2024-07-08 - Open-source re-implementation of Stronghold 1 that reads and uses original game file formats (bundle, cpk, dat).

### Fatshark

#### Warhammer: End Times - Vermintide

* [VermintideBundleTool](https://github.com/Atvaark/VermintideBundleTool) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2015-11-04 - Tool to extract Stingray Engine bundle files from Warhammer: End Times - Vermintide for format research and modding.

### Firestarter (Hover Ace)

* [fsex](https://github.com/iOrange/fsex) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2021-02-17 - Command-line archive extractor for Firestarter/Hover Ace's .tntFolder game pak archives.

### Free Radical Design (TimeSplitters)

* [tspak](https://github.com/OpenRadical/tspak) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2021-11-09 - Small utility for extracting TimeSplitters .pak files. Supports P4CK (Timesplitters 1 & 2 PS2), P5CK (TimeSplitters: Future Perfect), and P8CK (TimeSplitters 2 GameCube/Xbox).

### Frictional Games (Amnesia, Soma)

* [AmnesiaTheDarkDescent](https://github.com/FrictionalGames/AmnesiaTheDarkDescent) ⭐ 3,658 | 🐛 18 | 🌐 C++ | 📅 2020-10-12 - Official open-source release of Amnesia: The Dark Descent (2010) by Frictional Games, including the HPL2 engine source code.
* [AmnesiaAMachineForPigs](https://github.com/FrictionalGames/AmnesiaAMachineForPigs) ⭐ 1,452 | 🐛 7 | 🌐 C++ | 📅 2023-09-25 - Official open-source release of Amnesia: A Machine for Pigs by Frictional Games, including the HPL2 engine source code used for this title.
* [AmnesiaLoader](https://github.com/REDxEYE/AmnesiaLoader) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-05-27 - UniLoader addon for most Frictional Games titles (Amnesia series, Soma, etc).

### FromSoftware

*Demon's Souls, Dark Souls, Bloodborne, Sekiro, Elden Ring.*

#### Documentation & Wikis

* [Awesome Elden Ring](https://github.com/sovietspaceship/awesome-elden-ring) ⭐ 63 | 🐛 0 | 📅 2023-11-25 - Curated list of resources and tools for Elden Ring.
* [Sekiro Modding Wiki](https://github.com/SekiroResurrection/modding-wiki) ⭐ 46 | 🐛 0 | 📅 2022-01-08 - Documentation for Sekiro modding.
* [ds3-open-re](https://github.com/garyttierney/ds3-open-re) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2021-03-12 - Open reverse engineering resources for Dark Souls 3.
* [elden-ring-open-re](https://github.com/garyttierney/elden-ring-open-re) ⭐ 7 | 🐛 0 | 📅 2022-03-12 - Public knowledge on reverse engineering Elden Ring.
* [Souls Modding Wiki](https://www.soulsmodding.com/doku.php?id=start) - Documentation for FromSoftware formats.

#### Format Libraries & Templates

* [SoulsFormats](https://github.com/JKAnderson/SoulsFormats) ⚠️ Archived - .NET library for reading and writing FromSoftware file formats (Dark Souls, Demon's Souls, Bloodborne, Sekiro, and others), the foundational library used by SoulsAssetPipeline, DSMapStudio, and most other Souls modding tools.
* [soulstruct](https://github.com/Grimrukh/soulstruct) ⭐ 174 | 🐛 18 | 🌐 Python | 📅 2026-08-18 - Python library for Dark Souls file formats and modding.
* [dstools](https://github.com/katalash/dstools) ⭐ 141 | 🐛 9 | 🌐 C# | 📅 2020-02-27 - Tools for Dark Souls file formats.
* [libER](https://github.com/Dasaav-dsv/libER) ⭐ 72 | 🐛 11 | 🌐 C++ | 📅 2025-04-24 - ELDEN RING API library with focus on binary compatibility and safety. Written in modern C++20 with byte-perfect documentation of ELDEN RING type layouts, type safety, thread safety, and non-invasive modifications. Supports symbol definition files separated by game version.
* [DarkSoulsIII.FileFormats](https://github.com/Atvaark/DarkSoulsIII.FileFormats) ⭐ 59 | 🐛 1 | 📅 2017-04-14 - Library for reading Dark Souls III file formats.
* [SoulsTemplates](https://github.com/JKAnderson/SoulsTemplates) ⚠️ Archived - 010 Editor templates for Souls formats.
* [DS2AnimToolset](https://github.com/LordRadai/DS2AnimToolset) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2026-08-14 - Set of tools to parse and compile Dark Souls 2 morpheme animation binaries.
* [DarkSoulsII.FileFormats](https://github.com/Atvaark/DarkSoulsII.FileFormats) ⭐ 14 | 🐛 1 | 📅 2017-03-28 - Archive file format reference and dumped game assets (.anibnd, .hqbnd, .hqobjbnd).
* [DS2Template](https://github.com/LordRadai/DS2Template) ⭐ 3 | 🐛 0 | 📅 2026-02-14 - Collection of 010 .bt templates specifically made for Dark Souls II
* [fstools-rs](https://github.com/soulsmods/fstools-rs) ⭐ 3 | 🐛 4 | 🌐 Rust | 📅 2026-03-04 - Dark Souls file format tools and viewer components for format research and asset manipulation. Actively maintained canonical repo (garyttierney/fstools-rs is a stale, unmaintained mirror).
* [Coremats](https://github.com/JKAnderson/Coremats) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2026-08-01 - .NET library for FromSoftware formats.
* [soulsformats-rs](https://github.com/garyttierney/soulsformats-rs) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2021-07-18 - Rust library that can read/write file formats from FromSoftware's recent games.
* [soulstruct-gui](https://github.com/Grimrukh/soulstruct-gui) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-22 - GUI editor for Dark Souls binary data structures and game parameters.

#### Archives, Unpackers & Encryption

* [BinderTool](https://github.com/Atvaark/BinderTool) ⭐ 342 | 🐛 17 | 🌐 C# | 📅 2022-03-25 - Tool for extracting and repacking BND/BHD archives.
* [UXM-Selective-Unpack](https://github.com/Nordgaren/UXM-Selective-Unpack) ⭐ 331 | 🐛 2 | 🌐 C# | 📅 2026-02-15 - Enables file modding for Dark Souls 1, Dark Souls 2/SotFS, Dark Souls 3, and Sekiro by unpacking game archives and patching the executable to load loose files. More actively maintained fork of UXM with broader game support.
* [Yabber](https://github.com/JKAnderson/Yabber) ⚠️ Archived - Unpacker/repacker for FromSoftware container formats (BND, BHD/BDT, DCX, and more), one of the most fundamental FromSoftware modding tools.
* [UXM](https://github.com/JKAnderson/UXM) ⭐ 183 | 🐛 2 | 🌐 C# | 📅 2025-05-26 - Unpacker for Dark Souls III and Sekiro archives.
* [ER.BDT.Tool](https://github.com/Ekey/ER.BDT.Tool) ⭐ 69 | 🐛 0 | 🌐 C# | 📅 2022-03-21 - Extractor for BDT archive files (main data container format).
* [SaveMerge](https://github.com/JKAnderson/SaveMerge) ⚠️ Archived - Editor for merging and transferring Dark Souls 3 save files.
* [DS3PortingTool](https://github.com/GompDS/DS3PortingTool) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2026-06-16 - Tool for porting BND archives (models, textures, animations) from other FromSoftware games onto Dark Souls 3, handling the associated format conversions.
* [ER.DATA.Tool](https://github.com/Ekey/ER.DATA.Tool) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2025-06-21 - Tool for extracting data archives from mobile game Earth Revival (Project Arrival).
* [ParamCrypt](https://github.com/Grimrukh/ParamCrypt) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-07-13 - Encryption tool for Dark Souls param files.
* [TextureToTpf](https://github.com/GompDS/TextureToTpf) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2022-11-26 - Converts DDS files into FromSoftware TPF texture containers for PC.
* [YarrTools](https://github.com/GompDS/YarrTools) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2023-07-14 - YarrToMap moves loose DDS files into Dark Souls 3 texture binders (removing unused textures and balancing binder sizes), for use with the YARR hot-reload workflow.
* [MapTexPack3](https://github.com/GompDS/MapTexPack3) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-04-30 - Console app that automates packing loose DDS textures into Dark Souls 3 TPFBDT/BHD binders, pruning unused textures and balancing binder sizes.
* [unpoka](https://github.com/JKAnderson/unpoka) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-08-01 - Unpacking tool for gamedata from FromSoftware's PSP game Monster Hunter Diary: Poka Poka Airou Village (Monhan Nikki).

#### Models, Animation & FLVER

* [DSAnimStudio](https://github.com/Meowmaritus/DSAnimStudio) ⭐ 570 | 🐛 50 | 🌐 C# | 📅 2026-05-20 - Animation and cutscene editor for Souls games.
* [soulstruct-blender](https://github.com/Grimrukh/soulstruct-blender) ⭐ 185 | 🐛 63 | 🌐 Python | 📅 2026-07-20 - Blender plugin for soulstruct.
* [FLVER\_Editor](https://github.com/asasasasasbc/FLVER_Editor) ⭐ 175 | 🐛 8 | 🌐 C# | 📅 2026-01-02 - Multifunctional editor to edit and view FromSoftware game's FLVER files (Sekiro, Dark Souls, Bloodborne, etc.).
* [JortPob](https://github.com/infernoplus/JortPob) ⭐ 79 | 🐛 32 | 🌐 C# | 📅 2026-08-17 - Total conversion tool that ports Morrowind's assets (models, terrain, NPCs, dialogue) into Elden Ring via ModEngine3, converting Bethesda's data into FromSoftware's FLVER/BND/MSB formats and Wwise audio pipeline.
* [FromSoftware-Blender-Importer](https://github.com/FelixBenter/FromSoftware-Blender-Importer) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2022-07-18 - Blender importer for FromSoftware FLVER formats. Supports Dark Souls 1, 2, 3, and Sekiro: Shadows Die Twice (characters, partsbnds, and maps for DS1/DS3).
* [dark\_souls\_hkx](https://github.com/Danilodum/dark_souls_hkx) ⭐ 32 | 🐛 3 | 🌐 C++ | 📅 2016-04-24 - Noesis plugins for Dark Souls HKX (Havok animation) format with extra root bone and root motion support.
* [DSR-TPUP](https://github.com/JKAnderson/DSR-TPUP) ⚠️ Archived - Utility to extract and replace textures in Dark Souls: Remastered.
* [SoulsAssetPipeline](https://github.com/Meowmaritus/SoulsAssetPipeline) ⭐ 23 | 🐛 0 | 🌐 C# | 📅 2026-05-19 - C# pipeline for importing and exporting assets from FromSoftware's Souls games, built on top of SoulsFormats.
* [blender-flver](https://github.com/elizagamedev/blender-flver) ⭐ 21 | 🐛 3 | 🌐 Python | 📅 2020-04-28 - Blender addon for importing/exporting FLVER models from FromSoftware games. Supports Dark Souls, Dark Souls: Remastered, Bloodborne, and Sekiro.
* [ERClipGeneratorTool](https://github.com/The12thAvenger/ERClipGeneratorTool) ⭐ 18 | 🐛 0 | 🌐 C# | 📅 2023-10-04 - Editor for hkbClipGenerators in Havok Behavior (.hkx) animation files.
* [FbxImporter](https://github.com/The12thAvenger/FbxImporter) ⭐ 13 | 🐛 1 | 🌐 C# | 📅 2025-12-16 - Tool for importing FBX meshes into FLVER model files, supporting vertex-deformed cloth meshes, for Dark Souls 3, Sekiro, and Elden Ring.
* [FBX2FLVER-MTDFIX](https://github.com/infernoplus/FBX2FLVER-MTDFIX) ⭐ 11 | 🐛 0 | 🌐 C# | 📅 2021-02-08 - Tool to import FBX models into Dark Souls 1 flver format with MTD fixing.
* [BBAnimConverter](https://github.com/Sanadsk/BBAnimConverter) ⭐ 10 | 🐛 0 | 📅 2019-03-30 - Converts Dark Souls 3 and Bloodborne PS4 Havok animations into HavokTools-friendly files.
* [MTD-Editor](https://github.com/JKAnderson/MTD-Editor) ⚠️ Archived - Material definition (MTD) editor for FromSoftware games.
* [ERMaterialConvertTool](https://github.com/ividyon/ERMaterialConvertTool) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-07-06 - Tool for Elden Ring modding to convert one FLVER (model file) material to another.
* [FlverFixer](https://github.com/GompDS/FlverFixer) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2022-12-08 - Fixes GX lists and buffer layouts in FLVER model files to match the materials used by the mesh, for Dark Souls 3, Sekiro and Elden Ring.
* [TAE Importer/Exporter for Elden Ring](https://github.com/FWang1221/TAE-Importer-Exporter-For-Elden-Ring) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2023-06-09 - Tool for importing/exporting TAE (Time Act Editor) animation files for Elden Ring.
* [FlverMapMigrator](https://github.com/Shadowth117/FlverMapMigrator) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2024-05-07 - Tool for migrating map flver model files for Dark Souls 3 (DS3).
* [soulstruct-havok](https://github.com/Grimrukh/soulstruct-havok) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-20 - Havok HKX file reader and writer for Dark Souls game animations and physics.
* [SoulsGrassConvert](https://github.com/ividyon/SoulsGrassConvert) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-09-07 - Tool for Souls modding (Elden Ring, Sekiro, Armored Core VI) to convert and edit GRASS files as GLTF files.

#### Maps & Level Editors

* [noclip.website (DarkSouls)](https://github.com/magcius/noclip.website/tree/main/src/DarkSouls) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Dark Souls map viewer.
* [noclip.website (Dark Souls collision)](https://github.com/magcius/noclip.website/tree/main/src/DarkSoulsCollisionData) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - Separate in-browser viewer for Dark Souls' collision geometry, rendering the hit meshes independently of the visual map data.
* [DSMapStudio](https://github.com/soulsmods/DSMapStudio) ⭐ 666 | 🐛 40 | 🌐 C# | 📅 2025-05-25 - Map/level editor for Souls/Bloodborne/Elden Ring.
* [dark-souls-map-viewer](https://github.com/colevk/dark-souls-map-viewer) ⭐ 52 | 🐛 1 | 🌐 JavaScript | 📅 2020-02-05 - Web-based Dark Souls map viewer.
* [DSMSPortable](https://github.com/mountlover/DSMSPortable/tree/main) ⭐ 18 | 🐛 0 | 🌐 C# | 📅 2024-07-01 - Portable version of DSMapStudio.

#### Scripting, FX, Params & Runtime Modding

* [ModEngine2](https://github.com/soulsmods/ModEngine2) ⚠️ Archived - Rewrite of Mod Engine, a runtime code patching and injection library for FromSoftware games. Supports Dark Souls 3 and Elden Ring.
* [DarkScript3](https://github.com/AinTunez/DarkScript3) ⭐ 120 | 🐛 12 | 🌐 HTML | 📅 2026-03-08 - IDE for editing FromSoftware's EMEVD event script files with a high-level JavaScript-like language (MattScript).
* [ESDLang](https://github.com/thefifthmatt/ESDLang) ⭐ 53 | 🐛 5 | 🌐 C# | 📅 2025-10-21 - Decompiler for ESD event script format.
* [EldenRingHKS](https://github.com/ividyon/EldenRingHKS) ⭐ 23 | 🐛 0 | 📅 2024-10-10 - Curated repository of Elden Ring HKS (HavokScript) AI/behavior script edits, useful reference for HavokScript decompilation/modding work.
* [ESDStudio](https://github.com/GompDS/ESDStudio) ⭐ 18 | 🐛 2 | 🌐 C# | 📅 2025-12-30 - Desktop app for editing FromSoftware Talk ESD (dialogue/behavior state machine) files.
* [Zeditor](https://github.com/AinTunez/Zeditor) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2020-06-28 - Editor for FromSoftware's ESD (Event Script Data) files used in Souls games.
* [fxr](https://github.com/EvenTorset/fxr) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-17 - JavaScript library for parsing, creating, and editing FromSoftware FXR files.
* [Gibbed.DarkSouls](https://github.com/gibbed/Gibbed.DarkSouls) ⭐ 11 | 🐛 0 | 🌐 C# | 📅 2018-05-05 - Tools & code for use with Dark Souls.
* [Dark-Souls-II-Mod-Loader](https://github.com/Atvaark/Dark-Souls-II-Mod-Loader) ⚠️ Archived - File system hook for modding and runtime file replacement.
* [BloodBorne-SFX-Bible-and-FXR-Research](https://github.com/Shadowth117/BloodBorne-SFX-Bible-from-Xenobyte-and-Gazu---all-FXR-files-cataloged) ⭐ 0 | 🐛 0 | 📅 2026-01-09 - Tool for extracting, renaming, and researching SFX and FXR files from Bloodborne.
* [FxrQuery](https://github.com/GompDS/FxrQuery) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2022-12-22 - Gathers FXR particle-effect data from a Dark Souls 3/Elden Ring install using a game-directory Config.xml and an FXR-ID spreadsheet CSV.
* [CutsceneEdit](https://github.com/GompDS/CutsceneEdit) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2023-02-25 - Console tool to move and rotate cameras/objects in Dark Souls 3 MQB cutscene files via simple command syntax.

### Frontier Developments (Dog's Life)

* [dogcomp](https://github.com/IWILLCRAFT-M0d/dogcomp) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2026-08-10 - Matching decompilation of Dog's Life (2003, PS2).
* [dogs-life-docs](https://github.com/Dogmander/dogs-life-docs) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2022-12-20 - Research on Dog's Life (PS2) internal engine (FGDK3) and its file formats.

### Funcom

#### Dreamfall: The Longest Journey

* [DreamView](https://github.com/illusionyy/DreamView) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2019-10-18 - Viewer for 3D models and animations from Dreamfall: The Longest Journey, originally by Tobias Pfaff.

#### Secret World Legends

* [SwlRdbExporter](https://github.com/Xeio/SwlRdbExporter) ⭐ 8 | 🐛 2 | 🌐 C# | 📅 2021-05-28 - Exports files from Secret World Legends RDB archives.

### Gamania Digital Entertainment (Bright Shadow)

* [BS.PAK.Tool](https://github.com/Ekey/BS.PAK.Tool) ⚠️ Archived - Tool for extracting PAK archives from Bright Shadow.

### Game Freak

*Pokémon games across various generations.*
*See also [Sappy (GBA Audio)](#sappy-gba-audio) for GBA-era Pokémon audio tools.*

* [PKHeX](https://github.com/kwsch/PKHeX) ⭐ 5,054 | 🐛 3 | 🌐 C# | 📅 2026-08-16 - Universal save file editor for Pokémon games. Supports all generations from Gen I to the latest Switch titles. Includes tools for legitimacy checking, PID/IV generation, and more.

#### Gen I & II

* [pokered (decomp)](https://github.com/pret/pokered) ⭐ 4,883 | 🐛 22 | 🌐 Assembly | 📅 2026-08-13 - Matching decompilation of Pokémon Red (100%).
* [pokecrystal (decomp)](https://github.com/pret/pokecrystal) ⭐ 2,493 | 🐛 59 | 🌐 Assembly | 📅 2026-08-13 - Matching decompilation of Pokémon Crystal (100%).
* [pokefirered (decomp)](https://github.com/pret/pokefirered) ⭐ 1,560 | 🐛 25 | 🌐 C | 📅 2026-08-04 - Matching decompilation of Pokémon FireRed (100%).
* [pokeyellow (decomp)](https://github.com/pret/pokeyellow) ⭐ 865 | 🐛 3 | 🌐 Assembly | 📅 2026-08-10 - Matching decompilation of Pokémon Yellow (100%).
* [pokegold (decomp)](https://github.com/pret/pokegold) ⭐ 706 | 🐛 4 | 🌐 Assembly | 📅 2026-08-13 - Matching decompilation of Pokémon Gold (100%).
* [pokeheartgold (decomp)](https://github.com/pret/pokeheartgold) ⭐ 571 | 🐛 8 | 🌐 Assembly | 📅 2026-08-14 - Matching decompilation of Pokémon HeartGold (100%).
* [pokegold-spaceworld (decomp)](https://github.com/pret/pokegold-spaceworld) ⭐ 393 | 🐛 2 | 🌐 Assembly | 📅 2026-08-18 - Matching decompilation of Pokémon Gold (SpaceWorld Demo) (100%).
* [polished-map](https://github.com/Rangi42/polished-map) ⭐ 242 | 🐛 38 | 🌐 C++ | 📅 2026-05-02 - Polished map editor for Gen II.
* [puzzleleague64 (decomp)](https://github.com/angheloalf/puzzleleague64) ⭐ 35 | 🐛 0 | 🌐 C | 📅 2026-08-15 - Matching decompilation of Pokémon Puzzle League.
* [xd-decomp (decomp)](https://github.com/TeamOrre/xd-decomp) ⭐ 27 | 🐛 2 | 🌐 C | 📅 2026-05-24 - Matching decompilation of Pokémon XD: Gale of Darkness (GameCube).
* [map-editor](https://github.com/KernelEquinox/map-editor) ⭐ 19 | 🐛 1 | 🌐 C++ | 📅 2022-08-30 - Map editor for Generation I/II Pokémon games.

#### Gen III

*See also [Sappy (GBA Audio)](#sappy-gba-audio) for audio tools used in these games.*

* [pokeemerald (decomp)](https://github.com/pret/pokeemerald) ⭐ 3,389 | 🐛 84 | 🌐 C | 📅 2026-08-04 - Matching decompilation of Pokémon Emerald (100%).
* [pokeruby (decomp)](https://github.com/pret/pokeruby) ⭐ 983 | 🐛 32 | 🌐 C | 📅 2026-04-09 - Matching decompilation of Pokémon Ruby (100%).
* [porymap](https://github.com/huderlem/porymap) ⭐ 639 | 🐛 77 | 🌐 C++ | 📅 2026-07-31 - Modern map editor for Gen III Pokémon games.
* [poryscript](https://github.com/huderlem/poryscript) ⭐ 299 | 🐛 10 | 🌐 Go | 📅 2026-05-31 - Higher-level scripting language and compiler that compiles to the native Gen III Pokémon decompilation script bytecode format.
* [GBA\_RTCRead](https://github.com/megaboyexe/GBA_RTCRead) ⭐ 84 | 🐛 4 | 🌐 C | 📅 2021-04-10 - Tool to read/write data in the real-time clock (RTC) chip found inside carts of some GBA games, including Pokémon Ruby/Sapphire/Emerald and Boktai.
* [Porytiles](https://github.com/grunt-lucas/porytiles) ⭐ 72 | 🐛 151 | 🌐 C++ | 📅 2026-07-30 - Overworld tileset compiler for Pokémon Generation III decompilation projects.
  * Games: Pokémon Ruby (pokeruby), Pokémon FireRed (pokefirered), Pokémon Emerald (pokeemerald).
* [MEH](https://github.com/shinyquagsire23/MEH) ⚠️ Archived - Map editor for Gen III.
* [pokeemerald-jp (decomp)](https://github.com/pret/pokeemerald-jp) ⭐ 60 | 🐛 3 | 🌐 Assembly | 📅 2021-10-08 - Matching decompilation of Pokémon Emerald (JP) (100%).
* [AwesomeMapEditor](https://github.com/Sierraffinity/AwesomeMapEditor) ⭐ 43 | 🐛 4 | 🌐 C++ | 📅 2017-06-14 - Alternative map editor for Gen III.
* [blue-spider](https://github.com/cosarara/blue-spider) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2025-11-13 - Map editor for Pokémon Ruby/Sapphire/Emerald.
* [porydaw](https://github.com/huderlem/porydaw) ⭐ 16 | 🐛 0 | 🌐 C++ | 📅 2026-08-18 - Music editor for the Pokémon Generation 3 decompilation projects that edits the game's native music data format.
* [poryaaaa](https://github.com/huderlem/poryaaaa) ⭐ 15 | 🐛 1 | 🌐 C | 📅 2026-08-18 - Audio synthesizer emulating the GBA's native m4a (Sappy) sound engine, used to author music compatible with the Gen III decompilation projects.
* [Porymap-Animation](https://github.com/GriffinRichards/Porymap-Animation) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2025-06-16 - JavaScript plug-in that adds animated map tiles to porymap.
* [Pokemon-Editor](https://github.com/erandis-vol/Pokemon-Editor) ⚠️ Archived - Editor for 3rd generation Pokémon game data (e.g. sprites).
* [SaveStadium](https://github.com/Ploaj/SaveStadium) ⭐ 8 | 🐛 1 | 🌐 C# | 📅 2021-01-19 - Save file editor for Pokémon Stadium games.
* [gomons](https://github.com/huderlem/gomons) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2023-08-30 - Go library that can read and modify Pokémon Emerald save files.
* [Cry-Editor](https://github.com/erandis-vol/Cry-Editor) ⚠️ Archived - Cry (Pokémon sound effect) editor for 3rd generation Pokémon games.
* [Wargrave-Pokemon-Gen2-Editors](https://github.com/sandbPublic/Wargrave-Pokemon-Gen2-Editors) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2021-05-01 - Editors for Pokémon Gen 2 games.
* [Pokemon-Shuffle-Unpacker](https://github.com/SciresM/Pokemon-Shuffle-Unpacker) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2015-05-31 - Unpacker for Pokémon Shuffle archive files.
* [psfrag](https://github.com/jkbenaim/psfrag) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2019-12-07 - Utility for scanning, extracting, and building a database of code fragments in the Pokémon Stadium games.
* [JPoke-Export](https://github.com/vgmoose/JPoke-Export) ⭐ 1 | 🐛 2 | 🌐 Java | 📅 2014-01-15 - Pokémon save file exporter.
* [Bulbapedia (Gen I)](https://bulbapedia.bulbagarden.net/wiki/Save_data_structure_\(Generation_I\)) - Save data structure documentation for Generation I.
* [Bulbapedia (Gen II)](https://bulbapedia.bulbagarden.net/wiki/Save_data_structure_\(Generation_II\)) - Save data structure documentation for Generation II.
* [Bulbapedia (Gen III)](https://bulbapedia.bulbagarden.net/wiki/Save_data_structure_\(Generation_III\)) - Save data structure documentation for Generation III.

#### Gen VI

* [pokediamond (decomp)](https://github.com/pret/pokediamond) ⭐ 515 | 🐛 6 | 🌐 Assembly | 📅 2025-12-24 - Matching decompilation of Pokémon Diamond (100%).
* [pokeplatinum (decomp)](https://github.com/pret/pokeplatinum) ⭐ 512 | 🐛 18 | 🌐 C | 📅 2026-08-17 - Matching decompilation of Pokémon Platinum (100%).
* [pk3DS](https://github.com/kwsch/pk3DS) ⭐ 483 | 🐛 51 | 🌐 C# | 📅 2026-02-27 - ROM editor and randomizer for Generation 6 Pokémon games (X/Y, Omega Ruby/Alpha Sapphire).
* [Personal-Editor](https://github.com/SciresM/Personal-Editor) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2014-12-03 - Editor for Generation 6 Pokémon games (Pokémon X/Y and Pokémon OR/AS). Use on extracted files from Personal.GARC.

#### Gen V

* [poketcg (decomp)](https://github.com/pret/poketcg) ⭐ 326 | 🐛 5 | 🌐 Assembly | 📅 2026-08-13 - Matching decompilation of Pokémon TCG (100%).
* [pmd-red (decomp)](https://github.com/pret/pmd-red) ⭐ 277 | 🐛 3 | 🌐 C | 📅 2026-05-07 - Matching decompilation of Pokémon Mystery Dungeon: Red Rescue Team (100%).
* [pokestadium (decomp)](https://github.com/pret/pokestadium) ⭐ 199 | 🐛 5 | 🌐 C | 📅 2026-08-18 - Matching decompilation of Pokémon Stadium (100%).
* [pokepinball (decomp)](https://github.com/pret/pokepinball) ⭐ 197 | 🐛 4 | 🌐 Assembly | 📅 2026-08-01 - Matching decompilation of Pokémon Pinball (100%).
* [pokepinballrs (decomp)](https://github.com/pret/pokepinballrs) ⭐ 138 | 🐛 9 | 🌐 Assembly | 📅 2026-08-17 - Matching decompilation of Pokémon Pinball: Ruby & Sapphire (100%).
* [pmd-sky (decomp)](https://github.com/pret/pmd-sky) ⭐ 127 | 🐛 2 | 🌐 Assembly | 📅 2026-08-12 - Matching decompilation of Pokémon Mystery Dungeon: Explorers of Sky (100%).
* [poketcg2 (decomp)](https://github.com/pret/poketcg2) ⭐ 89 | 🐛 5 | 🌐 Assembly | 📅 2026-08-01 - Matching decompilation of Pokémon TCG 2 (100%).
* [pokestadiumgs (decomp)](https://github.com/pret/pokestadiumgs) ⭐ 49 | 🐛 0 | 🌐 C | 📅 2026-07-10 - Matching decompilation of Pokémon Stadium 2 (100%).
* [ppmdu](https://github.com/PsyCommando/ppmdu) ⭐ 47 | 🐛 20 | 🌐 C++ | 📅 2022-12-19 - Combined toolset for exporting/importing graphics, audio, and script data to and from Pokémon Mystery Dungeon: Explorers of Time/Darkness/Sky (NDS).
* [pokeblack (decomp)](https://github.com/pokemodding/pokeblack) ⭐ 41 | 🐛 0 | 🌐 Assembly | 📅 2026-08-19 - Matching decompilation of Pokémon Black.
* [SwissArmyKnife](https://github.com/PlatinumMaster/SwissArmyKnife) ⭐ 16 | 🐛 4 | 🌐 C# | 📅 2023-11-04 - Cross-platform ROM editor for Generation V Pokémon games (Black, White, Black 2, White 2). Supports editing map containers, text, events, zone headers, entities, and encounters.
* [pbr-dtk (decomp)](https://github.com/bgsamm/pbr-dtk) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2026-07-10 - Matching decompilation of Pokémon Battle Revolution.

#### Switch (Gen VIII+)

* [PKHeX.Mobile](https://github.com/kwsch/PKHeX.Mobile) ⭐ 849 | 🐛 8 | 🌐 C# | 📅 2024-05-30 - Pokémon save editor for Android and iOS, mobile companion to PKHeX.
* [PKHeX-Plugins](https://github.com/architdate/PKHeX-Plugins) ⭐ 675 | 🐛 10 | 🌐 C# | 📅 2024-05-08 - Collection of plugins for PKHeX.
* [pkNX](https://github.com/kwsch/pkNX) ⭐ 443 | 🐛 14 | 🌐 C# | 📅 2026-07-16 - All-in-one ROM editor and randomizer for Switch Pokémon games (Let's Go, Sword/Shield, Brilliant Diamond/Shining Pearl, Legends: Arceus, Scarlet/Violet).
* [RaidCrawler](https://github.com/LegoFigure11/RaidCrawler) ⭐ 175 | 🐛 5 | 🌐 C# | 📅 2026-07-26 - Raid viewer for Pokémon Scarlet and Violet.
* [PKHeX\_Raid\_Plugin](https://github.com/Leanny/PKHeX_Raid_Plugin) ⭐ 94 | 🐛 4 | 🌐 C# | 📅 2026-04-02 - PKHeX plugin to display raid data and additional Pokémon info.
* [HOME-Live-Plugin](https://github.com/Manu098vm/HOME-Live-Plugin) ⭐ 73 | 🐛 0 | 🌐 C# | 📅 2026-07-30 - PKHeX plugin to view and dump Pokémon from the Pokémon HOME application.
* [SeedSearcher](https://github.com/Leanny/SeedSearcher) ⭐ 69 | 🐛 19 | 🌐 C# | 📅 2023-01-14 - Seed finder for Pokémon Sword and Shield RNG manipulation.
* [PCHex](https://github.com/Strackeror/PCHex) ⭐ 48 | 🐛 9 | 🌐 C | 📅 2015-12-05 - 3DS homebrew Pokémon save editor.
* [PKHeX-Auto-Legality-Mod](https://github.com/architdate/PKHeX-Auto-Legality-Mod) ⚠️ Archived - Modded Showdown import function for PKHeX enabling automatic Pokémon legality fixing.
* [EtumrepMMO](https://github.com/kwsch/EtumrepMMO) ⭐ 38 | 🐛 0 | 🌐 C# | 📅 2026-01-11 - Reverses captured entities in Pokémon Legends: Arceus back to their origin (group) RNG seed.
* [GFBMDL\_Plugin](https://github.com/Reisyukaku/GFBMDL_Plugin) ⭐ 21 | 🐛 8 | 🌐 Python | 📅 2019-12-20 - Blender plugin for importing models and animations from Switch Pokémon games.
* [PokeFilename](https://github.com/architdate/PokeFilename) ⭐ 17 | 🐛 0 | 🌐 C# | 📅 2026-07-22 - PKHeX plugin to customize PKM output filenames.
* [PKHeXRNG](https://github.com/kwsch/PKHeXRNG) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2020-01-06 - PKHeX plugin for Citra RNG manipulation via RPC game-data fetching.
* [PIDFinder](https://github.com/ca1e/PIDFinder) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2022-04-27 - Assistant tool for abusing Pokémon PID/IV pseudo-random number generation.
* [pokenamehex](https://github.com/vaz/pokenamehex) ⭐ 1 | 🐛 0 | 🌐 Ruby | 📅 2017-10-14 - Utility for hex-editing Pokémon name strings, working with the games' internal character encoding table.

### Gameloft

* [GameloftEngineLoader](https://github.com/REDxEYE/GameloftEngineLoader) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-11-23 - UniLoader addon for importing Gameloft engine PIG files. Supports meshes, textures, transforms, nodes, and compression (LZ4, ZSTD).
* [Greenier-Farm-3-Decomp (decomp)](https://github.com/SmithGoll/Greenier-Farm-3-Decomp) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2025-05-01 - Matching decompilation of Green Farm 3.
* [SF.GLA.Tool](https://github.com/Ekey/SF.GLA.Tool) ⚠️ Archived - Tool for extracting GLA archives from Sniper Fury.

### GarageGames

#### Marble Blast

* [Marble Blast Web](https://github.com/Vanilagy/MarbleBlast) ⭐ 193 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-17 - Web port of Marble Blast Gold, Platinum, and Ultra with asset importing from original Torque 3D Engine files (.dif, .dts, .mis).

### Gearbox Software

* [Gibbed.Borderlands3.Datamining](https://github.com/gibbed/Gibbed.Borderlands3.Datamining) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2019-10-25 - Datamining tools for Borderlands 3.
* [Borderlands 2 Texture Modding Tool for PC](https://www.moddb.com/games/borderlands-2/downloads/borderlands-2-texture-modding-tool-for-pc) - PC-only guide and tool (TexMod) for extracting, editing, and using textures in Borderlands 2. TexMod is a popular texture tool also used for Arkham City, Tomb Raider, and other games.

#### MechWarrior 4

* [MW4 Sound Extractor (MechWarrior 4: Mercenaries)](https://www.moddb.com/games/mechwarrior-4-mercenaries/downloads/mw4-sound-extractor) - Sound extractor for MechWarrior 4: Mercenaries. Created by mektek, one of the first tools created for the game.
* [Gibbed.Borderlands2](https://github.com/gibbed/Gibbed.Borderlands2) ⭐ 683 | 🐛 76 | 🌐 C# | 📅 2022-12-08 - Save editor and modding tools for Borderlands 2, including a save game editor and Spark TMS pack/unpack utilities.

#### Borderlands

* [Gibbed's Borderlands 3 Tools](https://github.com/gibbed/Gibbed.Borderlands3) ⭐ 237 | 🐛 9 | 🌐 C# | 📅 2019-09-16 - Tools and code for working with Borderlands 3 game files and formats.
* [Gibbed.BorderlandsOz](https://github.com/gibbed/Gibbed.BorderlandsOz) ⭐ 185 | 🐛 19 | 🌐 C# | 📅 2022-12-08 - Tools for Borderlands: The Pre-Sequel game format parsing and editing.
* [Gibbed's Borderlands Save Editor](https://github.com/gibbed/Gibbed.Borderlands) ⭐ 58 | 🐛 1 | 🌐 C# | 📅 2019-04-03 - Tools and code for parsing and editing Borderlands game save files and binary formats.
* [borderlands2](https://github.com/apocalyptech/borderlands2) ⭐ 17 | 🐛 5 | 🌐 Python | 📅 2024-01-01 - Command-line save editor for Borderlands 2 and Borderlands: The Pre-Sequel that decodes the protobuf-based savegame format to JSON/text for editing character stats, inventory, currencies, and challenges, then re-encodes it back to a console/PC-playable save.
* [Gibbed.BorderlandsEnhanced.Datamining](https://github.com/gibbed/Gibbed.BorderlandsEnhanced.Datamining) ⭐ 10 | 🐛 2 | 🌐 C# | 📅 2022-12-08 - Datamining tools for Borderlands Enhanced game format extraction.
* [Gibbed's Borderlands 2 Datamining Tools](https://github.com/gibbed/Gibbed.Borderlands2.Datamining) ⭐ 8 | 🐛 3 | 🌐 C# | 📅 2022-12-08 - Datamining tools for extracting game data (items, missions, balance, currencies, customizations, perks) from running Borderlands 2 instances.
* [Gibbed.BorderlandsOz.Datamining](https://github.com/gibbed/Gibbed.BorderlandsOz.Datamining) ⭐ 7 | 🐛 2 | 🌐 C# | 📅 2022-12-08 - Datamining tools that dump game data from running instances of Borderlands: The Pre-Sequel.
* [ft-explorer](https://github.com/apocalyptech/ft-explorer) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2024-07-10 - GUI browser for Borderlands resource data used by BLCMM modding tool, browsing Unreal Engine structures from Borderlands 2, TPS, and Tales from the Borderlands.

### Genius Sonority

*Pokémon Colosseum, Pokémon XD: Gale of Darkness.*

* [Blender HAL DAT Model Addon](https://github.com/StarsMmd/Blender-Addon-Gamecube-Models) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2026-07-10 - Blender addon for importing and exporting HAL Laboratory's GameCube .dat model format, primarily for Pokemon Colosseum and XD: Gale of Darkness, with compatibility for Super Smash Bros. Melee, Kirby Air Ride, Chibi-Robo!, and Killer7.
* [tdmextractor](https://github.com/NerduMiner/tdmextractor) ⭐ 6 | 🐛 0 | 🌐 D | 📅 2024-08-04 - Archive extractor and repacker for "The Denpa Men" series (TDM1/TDM2/TDM3/TDMF archives). Can replace the usage of the existing quickbms script for The Denpa Men 3.
* [pokemon\_fsys\_tool](https://github.com/gamemasterplc/pokemon_fsys_tool) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2023-02-11 - Tool for FSYS archive format used in Pokémon Colosseum/XD.
* [PokemonFSYSConverter](https://github.com/vgmoose/PokemonFSYSConverter) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2017-12-30 - Program to extract .obm and textures out of .fsys files found in some GameCube/Wii titles.

### Genki

*Jade Cocoon: Story of the Tamamayu, Jade Cocoon 2.*

* [GUTArchiveTools](https://github.com/igorciz777/GUTArchiveTools) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2026-07-28 - Archive tools for GUT (Genki Utility) archive format used in Genki's PS2 racing games (Tokyo Xtreme Racer series, Kaido Racer, Shutokou Battle, etc.).
* [Jade-Cocoon-Unpacker-Repacker](https://github.com/Meos4/Jade-Cocoon-Unpacker-Repacker) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2025-04-19 - Tool to unpack and repack DATA.001 archive files from Jade Cocoon (PS1).
* [Jade-Cocoon-2-Unpacker-Repacker](https://github.com/Meos4/Jade-Cocoon-2-Unpacker-Repacker) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2025-04-19 - Tool to unpack and repack archive files from Jade Cocoon 2 (PS2).
* [Tamamayu-Monogatari-Dennou-Bijutsukan-Unpacker](https://github.com/Meos4/Tamamayu-Monogatari-Dennou-Bijutsukan-Unpacker) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2023-12-16 - Unpacker for DATA.001 archives from Tamamayu Monogatari Dennou Bijutsukan demo (PS1).
* [KengoPS2Tools](https://github.com/igorciz777/KengoPS2Tools) ⭐ 0 | 🐛 1 | 🌐 C++ | 📅 2025-08-23 - Tools for unpacking, rebuilding, and inserting files into the FID.BIN archive format used in Genki's Kengo series (PS2).
* [GNKSoundTools](https://github.com/igorciz777/GNKSoundTools) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2024-12-22 - Sound modding tools for PS2 Genki games.
* [TXR3-Text-Editor](https://github.com/igorciz777/TXR3-Text-Editor) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-03-20 - Text editor for Tokyo Xtreme Racer 3.

### Giant Network (King of Kings 3)

* [KOK3.LPQ.Tool](https://github.com/Ekey/KOK3.LPQ.Tool) ⚠️ Archived - Tool for extracting LPQ archives from King of Kings 3.

### GlassesCatGames (Devil Slayer - Raksasi)

* [DSR.ALP.Tool](https://github.com/Ekey/DSR.ALP.Tool) ⚠️ Archived - Tool for extracting and repacking Lua ALP archives from Devil Slayer - Raksasi.

### Glowmade (King of Meat)

* [KM.ARCHIVE.Tool](https://github.com/Ekey/KM.ARCHIVE.Tool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-05-16 - Tool for extracting archives from King of Meat (Technical Test build).

### FSZHS Zhengshi (封神召唤师)

* [FS.MP3.Tool](https://github.com/Ekey/FS.MP3.Tool) ⚠️ Archived - Tool for extracting MP3 archives from the mobile game FSZHS Zhengshi (封神召唤师).

### 画皮世界 (Painted Skin World)

* [HP.EPK.Tool](https://github.com/Ekey/HP.EPK.Tool) ⚠️ Archived - Tool for extracting EPK archives from the mobile game 画皮世界 (Painted Skin World).

### Good-Feel (Yoshi's Wooly World)

* [gfa-packer](https://github.com/jam1garner/gfa-packer) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2017-04-18 - Tool for repacking GFA archives located in Yoshi's Wooly World.

### Grasshopper Manufacture (No More Heroes, Killer7)

* [No-More-RSL](https://github.com/Timo654/No-More-RSL) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2021-07-03 - Unpacker/repacker for Grasshopper Manufacture .RSL format. Works with most if not all Grasshopper Manufacture games using this format.

#### Sine Mora

* [SMM.OBB.Tool](https://github.com/Ekey/SMM.OBB.Tool) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2026-01-21 - Tool for extracting OBB archives from the Sine Mora mobile port.
* [SM.BIN.Tool](https://github.com/Ekey/SM.BIN.Tool) ⚠️ Archived - Tool for extracting BIN archives from Sine Mora / Sine Mora EX, co-developed with Digital Reality.

### Gravity (Ragnarok Online)

* [noclip.website (Ragnarok Online)](https://github.com/magcius/noclip.website/tree/main/src/RagnarokOnline) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Ragnarok Online map viewer.
  * Formats: RSW (world), GND (ground/terrain), RSM (models), GAT (altitude/collision), SPR/ACT (sprites and sprite animation), STR (effects), Granny (`.gr2` models and animation).
  * Features: Water, weather and particle effects, dynamic lights, shadows, warp portals, name tags, pathfinding, era selection, and BGM playback.
* [libgrf](https://github.com/cmbasnett/libgrf) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2020-12-16 - Library for reading GRF archives found in Ragnarok Online.
* [grf-python](https://github.com/cmbasnett/grf-python) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2020-02-25 - Python wrapper for libgrf.

### Gray Design Associates

* [OpenNitemare3D](https://github.com/BBQGiraffe/OpenNitemare3D) ⭐ 51 | 🐛 13 | 🌐 C# | 📅 2022-08-23 - Reimplementation of Nitemare 3D (1994), reading the original game's data files.
* [Nitemare3D DAT Extractor](https://github.com/BBQGiraffe/Nitemare-3D-DAT-Extractor) ⭐ 3 | 🐛 1 | 🌐 C# | 📅 2019-09-01 - Extracts menu art and audio from Nitemare 3D (1994) and the Hugo's House Of Horrors series' SND.DAT/UIF.DAT archives, producing PCX images and MIDI/VOC/PCM sound files.
* [LibHugo](https://github.com/BBQGiraffe/LibHugo) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2020-07-24 - C++ library for reading image and sound data from Hugo's House Of Horrors and Nitemare 3D.
* [Hugo's House Of Horrors Midi Rip](https://github.com/BBQGiraffe/Hugos-House-Of-Horrors-Midi-Rip) ⭐ 1 | 🐛 0 | 📅 2019-09-02 - Ripped MIDI music files extracted from Hugo's House Of Horrors using the DAT Extractor above.

### Gremlin Interactive

#### Actua Soccer

* [ActuaSoccer](https://github.com/amroibrahim/ActuaSoccer) ⭐ 6 | 🐛 0 | 📅 2022-11-08 - Code analysis notes on Gremlin Interactive's officially released Actua Soccer/Euro 96 DOS source code, covering the Watcom C++/DOS4GW toolchain needed to rebuild it and reverse-engineering findings about the game's internals.
* [acuta-soccer-mocap-viewer](https://github.com/JimMarshall35/acuta-soccer-mocap-viewer) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2023-01-29 - Viewer for Actua Soccer's proprietary motion-capture data files.

#### Hogs of War

* [OpenHoW](https://github.com/hogsy/OpenHoW) ⚠️ Archived - Open-source reimplementation of Gremlin Interactive's Hogs of War (PC/PSX) that reads and renders the original game's data files.

#### Realms of the Haunting

* [roth\_ripper](https://github.com/Yagotzirck/roth_ripper) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2019-10-05 - Resource extractor for Realms of the Haunting (1996, DOS).

#### Strike Series (Desert Strike, Jungle Strike, Urban Strike)

* [StrikeLZSS](https://github.com/infval/StrikeLZSS) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2020-07-14 - LZSS compressor/decompressor for Desert Strike, Jungle Strike, and Urban Strike (Sega Mega Drive/Genesis).

### Grezzo

*Ocarina of Time 3D, Majora's Mask 3D, Luigi's Mansion remake, Ever Oasis.*

* [noclip.website (OoT3D)](https://github.com/magcius/noclip.website/tree/main/src/OcarinaOfTime3D) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Ocarina of Time 3D viewer.
* [noclip.website (Luigi's Mansion 3D)](https://github.com/magcius/noclip.website/tree/main/src/OcarinaOfTime3D) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Luigi's Mansion 3D viewer, sharing Grezzo's CMB/ZAR/ZSI loader with the OoT3D and Majora's Mask 3D viewers.
* [Switch-Toolbox](https://github.com/KillzXGaming/Switch-Toolbox/tree/master/File_Format_Library/FileFormats/Grezzo) ⭐ 1,203 | 🐛 403 | 🌐 C# | 📅 2026-07-24 - A tool to edit many video game file formats
* [MeltyTool (Grezzo)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/Grezzo) ⭐ 200 | 🐛 60 | 🌐 C# | 📅 2026-08-19 - Grezzo format viewer/exporter.
* [Scarlet](https://github.com/xdanieldzd/Scarlet) ⭐ 115 | 🐛 20 | 🌐 C# | 📅 2019-12-17 - General purpose 3DS/Vita game tool.
* [N3DSCmbViewer](https://github.com/xdanieldzd/N3DSCmbViewer) ⭐ 39 | 🐛 0 | 🌐 C# | 📅 2022-04-13 - Viewer for 3DS CMB models.
* [io\_scene\_cmb](https://github.com/M-1-RLG/io_scene_cmb) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2021-07-16 - Blender add-on for Grezzo's "Ctr Model Binary" (CMB) format.
* [irarc\_unpacker](https://github.com/efimandreev0/irarc_unpacker) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-02-28 - Unpacker for IRARC archive format from Blaster Master Zero and Azure Striker Gunvolt (3DS).
* [GARTool](https://github.com/efimandreev0/GARTool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-01-04 - Tool tested with Ever Oasis and Luigi's Mansion.
* [Gar/Zar UnPacker](https://gbatemp.net/threads/release-gar-zar-unpacker-v0-1.385264/) - Archive unpacker for Ocarina of Time 3D and Majora's Mask 3D.

### GSC Game World

#### S.T.A.L.K.E.R

* [OpenXRay](https://github.com/OpenXRay/xray-16) ⭐ 3,543 | 🐛 293 | 🌐 C++ | 📅 2026-07-30 - Community-maintained, improved version of GSC Game World's X-Ray Engine (S.T.A.L.K.E.R.: Shadow of Chernobyl / Clear Sky / Call of Pripyat) that loads and renders the original games' assets and archives.
* [OGSR-Engine](https://github.com/OGSR/OGSR-Engine) ⭐ 586 | 🐛 30 | 🌐 C++ | 📅 2026-08-15 - Actively maintained fork/continuation of the X-Ray Engine (S.T.A.L.K.E.R.) with extensive bugfixes and feature additions, reading original S.T.A.L.K.E.R. game data.
* [ixray-1.6-stcop](https://github.com/ixray-team/ixray-1.6-stcop) ⭐ 440 | 🐛 71 | 🌐 C++ | 📅 2026-08-19 - Actively maintained, modernized continuation of the X-Ray engine (S.T.A.L.K.E.R.), reading the series' original game data files. See also [ixray-1.5-stcs](https://github.com/ixray-team/ixray-1.5-stcs) ⭐ 38 | 🐛 0 | 🌐 C++ | 📅 2026-01-29, the same team's stable X-Ray 1.5 branch.
* [blender-xray](https://github.com/PavelBlend/blender-xray) ⭐ 266 | 🐛 22 | 🌐 Python | 📅 2026-06-06 - Blender import/export addon for S.T.A.L.K.E.R. X-Ray Engine formats (OGF, OMF, ANM, SKL, SKLS), enabling extraction and manipulation of STALKER game assets.
* [bumpx](https://github.com/iOrange/bumpx) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2022-02-03 - Generates bump/bump# textures from normal, gloss, and height maps for S.T.A.L.K.E.R and Metro 2033 build 375.
* [LtxParser](https://github.com/JKAnderson/LtxParser) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2017-06-02 - C# library for loading .ltx trees from the STALKER series.
* [deepshadows-file-formats](https://github.com/AlexKimov/deepshadows-file-formats) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-03-17 - File formats, plugins, and tools for games by Deep Shadows (pre-merger with GSC Game World).
* [Geometry Decompiler plugin for 3dsmax](https://www.moddb.com/games/stalker/downloads/geometry-decompiler-plugin-for-3dsmax) - This plugin is designed to import into 3ds Max (works with versions 7-8, not tested on version 9) map geometry files of the game STALKER"
* [STALKER game archives unpacker](https://www.moddb.com/mods/old-good-stalker-evolution/downloads/stalker-game-archives-unpacker) - Needed for unpacking game archives - if you want to try to install russian version of mod - you'll need this.
* [STALKER Extractor](https://www.moddb.com/games/stalker/downloads/stalker-extractor) - STALKER database extractor. Compatible with all game versions. Allows choosing files to extract.
* [S.T.A.L.K.E.R Mod Tool](https://www.moddb.com/games/stalker/downloads/stalker-mod-tool) - NOT MY ADDON! The S.T.A.L.K.E.R mod tool used to extract the files from the .db files. Place all gamedata files into a folder called old once you have extracted every .db to a folder called gamedata in stalkers main directory like. G:\program files\THQ\S.T.A.L.K.E.R. - Shadow of Chernobyl\gamedat...
* [Unpack Pack xr files Stalker (S.T.A.L.K.E.R.: Call of Pripyat)](https://www.moddb.com/games/stalker-call-of-pripyat/downloads/unpack-pack-xr-files-stalker) - Gathered most of the pearl scripts into a heap and adapted them to a single library. The archives are all taken from the AMK website, and re-uploaded here because they were on a Yandex disk
* [XRay Exporter v2.03 (S.T.A.L.K.E.R. Shadow of Chernobyl)](https://www.moddb.com/games/stalker/downloads/xray-exporter-v203) - Official SDK 0.4 export plugins for 3ds Max 7, 8, 9, 2008, 2009, 2010, 2011, LightWave 3D 7.5 and 8.0, and Maya 7, 8, 8.5, 2008, 2009, 2010. In addition, missing libraries have been added.
* [XRay Exporter v2.03 (S.T.A.L.K.E.R.: Call of Pripyat)](https://www.moddb.com/games/stalker-call-of-pripyat/downloads/xray-exporter-v2031) - Official export plugins for SDK 0.5, 0.6, 0.7 for 3ds Max 8, 9, 2008, 2009, 2010, 2011, LightWave 3D 8.0 and Maya 7, 8, 8.5, 2008, 2009, 2010. Also added missing libraries.
* [X-ray game asset tools pack FINAL](https://www.moddb.com/games/stalker/downloads/x-ray-game-asset-tools-pack-final) - Complete toolset for editing all aspects of S.T.A.L.K.E.R. games. Includes: AI Wrapper 2.2 (compiling AI levels), converter (geometry and models), ACDC pack (editing all.spawn), and Milkshape/Maya plugins....
* [Clear Sky: Game Database Unpacker](https://www.moddb.com/games/stalker/downloads/clear-sky-game-database-unpacker) - This utility allows you to unpack all the game files.
* [STALKER utilities pack](https://www.moddb.com/games/stalker/downloads/stalker-utilities-pack) - Tool for editing LTX configuration files in S.T.A.L.K.E.R. games.
* [Updated Milkshape plugin](https://www.moddb.com/games/stalker/downloads/updated-milkshape-plugin) - Updated Milkshape plugin for S.T.A.L.K.E.R. (dated 01/08/2016).
* [Database converter (S.T.A.L.K.E.R.: Call of Pripyat)](https://www.moddb.com/mods/call-of-chernobyl/downloads/cop-coc-db-converter) - COP/COC converter, which unpacks db files to gamedata files.
* [Extractor de archivos para S.T.A.L.K.E.R.: Shadow of Chernobyl](https://www.moddb.com/games/stalker/downloads/extractor-de-archivos-para-stalker-shadow-of-chernobyl) - Lightweight program for extracting all files from S.T.A.L.K.E.R.: Shadow of Chernobyl for modding purposes.
* [General X Ray SDK CS-CoP Tools (S.T.A.L.K.E.R.: Call of Pripyat)](https://www.moddb.com/games/stalker-call-of-pripyat/downloads/general-x-ray-sdk-tools) - General X Ray SDK Tools. This archive contains dds2tgaLE X-Ray game asset converter 02 june 2011 rev10192 Fake flatness CS\&CoP; Compilers 2010 v3.0

### Guard Crush Games / Lizardcube (Streets of Rage 4)

* [bigfile\_tools](https://github.com/JadingTsunami/bigfile_tools) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2023-09-11 - Tools for editing Streets of Rage 4's proprietary bigfile game data format.
  * Features: Bigfile Editor (imports/exports compressed and uncompressed bigfiles, browses and edits annotated game data tables in a GUI), Level Editor (individually swaps enemy, pickup, and breakable spawn points in any playable level).
* [SOR4TEX](https://github.com/Jayveer/SOR4TEX) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2020-05-04 - Extracts textures from Streets of Rage 4 texture and texture-table files.

### Gumi (Brave Frontier)

* [client (decomp)](https://github.com/decompfrontier/client) ⭐ 11 | 🐛 9 | 🌐 C | 📅 2025-05-30 - Matching decompilation of Brave Frontier client.
* [scripts](https://github.com/decompfrontier/scripts) ⭐ 1 | 🐛 3 | 🌐 Python | 📅 2025-03-28 - Scripts to help investigate Brave Frontier client data, from the same team as the client matching decompilation.

### Gust (Koei Tecmo)

* [gust\_tools](https://github.com/VitaSmith/gust_tools) ⭐ 283 | 🐛 25 | 🌐 C | 📅 2025-11-13 - Utilities for archive management and data extraction for Gust PC games (Atelier, Blue Reflection, Nights of Azure).
* [Project-G1M](https://github.com/Joschuka/Project-G1M) ⭐ 92 | 🐛 14 | 🌐 C++ | 📅 2026-02-09 - Noesis plugin for importing G1M 3D model format used in Gust and Bandai Namco games.
* [Cethleann](https://github.com/neptuwunium/Cethleann) ⚠️ Archived - KTGL (Soft Engine) data exploration and research tool for Koei Tecmo games.
* [atelier\_pak\_decrypt](https://github.com/shizukachan/atelier_pak_decrypt) ⭐ 77 | 🐛 3 | 🌐 C | 📅 2018-04-27 - Small utility to decrypt GUST .pak archives.
* [gust\_stuff](https://github.com/eArmada8/gust_stuff) ⭐ 48 | 🐛 2 | 🌐 Python | 📅 2026-04-12 - Modding toolkit for G1M model files used in Gust games (Atelier series).
* [slpm86183 (decomp)](https://github.com/Erizur/slpm86183) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2026-02-08 - Matching decompilation of Pop'N Music CS1 (PS1).

### H2O Entertainment (Aidyn Chronicles)

* [aidyn (decomp)](https://github.com/blackgamma7/aidyn) ⭐ 39 | 🐛 0 | 🌐 C++ | 📅 2026-08-02 - Matching decompilation of Aidyn Chronicles: The First Mage (N64).

### Haggard Games

* [gh-file-formats](https://github.com/AlexKimov/gh-file-formats) ⭐ 0 | 🐛 0 | 🌐 Batchfile | 📅 2024-06-09 - File formats and hex-editor templates for Haggard Games titles.

### HAL Laboratory

*Kirby, Super Smash Bros series.*

* [noclip.website (Melee)](https://github.com/magcius/noclip.website/tree/main/src/SuperSmashBrosMelee) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Melee stage viewer.
* [noclip.website (Super Smash Bros Brawl)](https://github.com/magcius/noclip.website/tree/main/src/rres) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Super Smash Bros Brawl viewer.
* [noclip.website (SYSDOLPHIN)](https://github.com/magcius/noclip.website/tree/main/src/SYSDOLPHIN) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser SYSDOLPHIN format viewer.
* [noclip.website (Kirby Air Ride)](https://github.com/magcius/noclip.website/tree/main/src/KirbyAirRide) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Kirby Air Ride viewer.
* [noclip.website (Kirby's Return to Dream Land)](https://github.com/magcius/noclip.website/tree/main/src/rres) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser Kirby's Return to Dream Land viewer.
* [melee (decomp)](https://github.com/doldecomp/melee) ⭐ 997 | 🐛 31 | 🌐 C | 📅 2026-08-19 - Matching decompilation of Super Smash Bros. Melee.
* [ARCropolis](https://github.com/Raytwo/ARCropolis) ⭐ 370 | 🐛 7 | 🌐 Rust | 📅 2026-04-21 - Modding framework for loading and managing community-made mods and plugins for Super Smash Bros. Ultimate. Powered by Skyline for Switch homebrew.
* [skyline](https://github.com/skyline-dev/skyline) ⭐ 308 | 🐛 13 | 🌐 C++ | 📅 2026-04-12 - Environment for runtime hooking and code patching within Super Smash Bros. Ultimate. Provides linking, runtime hooking, and code patching capabilities for Switch homebrew modding.
* [kirby64 (decomp)](https://github.com/Kirby64Ret/kirby64) ⭐ 228 | 🐛 3 | 🌐 Assembly | 📅 2026-08-19 - Work-in-progress decompilation of Kirby 64: The Crystal Shards (N64).
* [MeltyTool (Sysdolphin)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/Sysdolphin) ⭐ 200 | 🐛 60 | 🌐 C# | 📅 2026-08-19 - Sysdolphin format viewer/exporter.
* [ssb-decomp-re (decomp)](https://github.com/vetritheretri/ssb-decomp-re) ⭐ 180 | 🐛 3 | 🌐 C | 📅 2026-08-12 - Matching decompilation of Super Smash Bros. (N64).
* [BrawlLib](https://github.com/libertyernie/brawltools) ⭐ 158 | 🐛 126 | 🌐 C# | 📅 2023-10-24 - Library for reading/writing file formats from Super Smash Bros. Brawl and other Wii games.
* [Smash-Forge](https://github.com/jam1garner/Smash-Forge) ⭐ 154 | 🐛 62 | 🌐 C# | 📅 2026-05-26 - Open source editor for Super Smash Bros. 4 file formats.
* [slippi-ssbm-asm](https://github.com/project-slippi/slippi-ssbm-asm) ⭐ 151 | 🐛 20 | 🌐 Assembly | 📅 2026-05-01 - Assembly tools for Super Smash Bros. Melee Slippi format.
* [smash-minecraft-skins](https://github.com/jam1garner/smash-minecraft-skins) ⭐ 113 | 🐛 36 | 🌐 Rust | 📅 2025-01-04 - Mod for downloading and converting a Minecraft username's skin into Super Smash Bros. Ultimate's in-game skin format.
* [kar (decomp)](https://github.com/doldecomp/kar) ⭐ 87 | 🐛 0 | 🌐 Assembly | 📅 2025-02-26 - Decompilation of Kirby Air Ride.
* [brawl (decomp)](https://github.com/doldecomp/brawl) ⭐ 74 | 🐛 3 | 🌐 C++ | 📅 2026-08-17 - Matching decompilation of Super Smash Bros. Brawl.
* [HSDLib](https://github.com/Ploaj/HSDLib) ⭐ 70 | 🐛 50 | 🌐 C# | 📅 2026-08-15 - Library for HAL's HSD format (used in Super Smash Bros Melee).
* [kdceditor](https://github.com/devinacker/kdceditor) ⭐ 60 | 🐛 4 | 🌐 C++ | 📅 2019-09-09 - Kirby's Dream Course / Kirby Bowl level editor (C++/Qt), reading and writing the game's level data format.
* [kirbydreamland (decomp)](https://github.com/huderlem/kirbydreamland) ⭐ 50 | 🐛 0 | 🌐 Assembly | 📅 2020-06-16 - Matching disassembly of Kirby's Dream Land (Game Boy).
* [kale](https://github.com/devinacker/kale) ⭐ 45 | 🐛 0 | 🌐 C++ | 📅 2015-08-01 - Kirby's Adventure Level Editor (KALE), a C++/Qt tool for editing Kirby's Adventure (NES) level data.
* [StudioSB](https://github.com/Ploaj/StudioSB) ⭐ 44 | 🐛 38 | 🌐 C# | 📅 2023-09-27 - Model application for Super Smash Bros. Ultimate. Work-in-progress tool for viewing and working with SSBU model files.
* [ArcExplorer](https://github.com/ScanMountGoat/ArcExplorer) ⭐ 43 | 🐛 18 | 🌐 C# | 📅 2026-06-23 - File browser and extractor for Super Smash Bros. Ultimate's data.arc file. Supports Windows, macOS, and Linux with network connection support.
* [brawllib\_rs](https://github.com/rukai/brawllib_rs) ⭐ 26 | 🐛 3 | 🌐 Rust | 📅 2025-12-18 - Rust library and reimplementation of BrawlLib for reading Super Smash Bros. Brawl file formats.
* [ArcCross](https://github.com/Ploaj/ArcCross) ⭐ 25 | 🐛 6 | 🌐 C# | 📅 2021-10-19 - File extractor for Super Smash Bros. Ultimate's ARC file. Replaced by ArcExplorer but useful for data.arc files prior to game version 5.0.
* [ssbu-arc-extract](https://github.com/FIX94/ssbu-arc-extract) ⭐ 20 | 🐛 1 | 🌐 C | 📅 2018-12-05 - Extracts and injects files from Super Smash Bros. Ultimate's data.arc.
* [k64cs-project](https://github.com/shygoo/k64cs-project) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2017-12-01 - Hacking tools and notes for Kirby 64: The Crystal Shards. Includes web-based model viewer, Collada DAE to Kirby64 geometry converter, ROM/RAM structure notes, and debugger scripts.
* [rdb\_tool](https://github.com/Raytwo/rdb_tool) ⭐ 9 | 🐛 1 | 🌐 Rust | 📅 2022-07-04 - Tool for patching RDB files in Super Smash Bros. Ultimate. Allows patching files into RDB archives using file hash-based syntax.
* [GekkoAssembler](https://github.com/CryZe/GekkoAssembler) ⚠️ Archived - Assembles Gekko Assembly to Action Replay or Gecko Cheat Code format. Used for GameCube and Wii game modding.
* [smash-arc](https://github.com/jam1garner/smash-arc) ⭐ 9 | 🐛 1 | 🌐 Rust | 📅 2023-12-09 - Library for working with Super Smash Bros. Ultimate's ARC format.
* [MeleeMedia](https://github.com/Ploaj/MeleeMedia) ⭐ 9 | 🐛 1 | 🌐 C# | 📅 2026-02-26 - Media extractor for Super Smash Bros Melee.
* [KirbyAirRideTools](https://github.com/LuigiBlood/KirbyAirRideTools) ⭐ 7 | 🐛 1 | 🌐 C# | 📅 2024-01-22 - Tools for Kirby Air Ride file formats.
* [RDLMINT](https://github.com/firubii/RDLMINT) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2018-09-03 - Disassembler and assembler for Kirby's Return to Dream Land's MINT bytecode. Can unpack and disassemble MINT Archives, and recompile and repack MINT XBIN scripts.
* [tristar](https://github.com/devinacker/tristar) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2015-11-20 - Map viewer for Kirby: Triple Deluxe and Kirby's Return to Dream Land, reading a Wii disc image or decrypted RomFS dump.
* [BoxBoyLevelEditor](https://github.com/monkeyman192/BoxBoyLevelEditor) ⭐ 6 | 🐛 3 | 🌐 Python | 📅 2020-04-15 - Level editor for HAL Laboratory's BoxBoy! (Nintendo 3DS), reading and writing the game's level data format.
* [smash-sli](https://github.com/jam1garner/smash-sli) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2023-07-12 - Rust library for reading and writing soundlabelinfo.sli files from Super Smash Bros. Ultimate.
* [smash-bgm-property](https://github.com/jam1garner/smash-bgm-property) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2023-07-12 - Rust library for reading and writing bgm\_property.bin files from Super Smash Bros. Ultimate.
* [SSB4-File-Format-Documentation](https://github.com/jam1garner/SSB4-File-Format-Documentation) ⭐ 4 | 🐛 1 | 📅 2020-02-16 - Documentation of Super Smash Bros. 4 (Wii U) file formats, including GTX image files.
* [mint-explorer](https://github.com/FireyFly/mint-explorer) ⭐ 4 | 🐛 2 | 🌐 JavaScript | 📅 2018-04-10 - Tool for exploring archive/package files for the Mint scripting engine found in various games, notably the Kirby series. Parses packages, files, classes, and methods. Complements RDLMINT above for MINT bytecode work.
* [arc-fuse](https://github.com/jam1garner/arc-fuse) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2023-12-30 - FUSE wrapper for Super Smash Bros. Ultimate's ARC filetype.
* [arc-network](https://github.com/jam1garner/arc-network) ⭐ 3 | 🐛 1 | 🌐 Rust | 📅 2021-03-06 - Skyline plugin providing network access to Super Smash Bros. Ultimate's data.arc file, for use with ARC browsing/extraction tools.
* [smash-fnv](https://github.com/jam1garner/smash-fnv) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2023-07-12 - Rust library for reading and writing sound\_volume\_fighter\_num\_table.fnv files from Super Smash Bros. for Nintendo 3DS and Wii U and Super Smash Bros. Ultimate.
* [smash-csb](https://github.com/jam1garner/smash-csb) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2023-07-12 - Rust library for reading and writing commonsoundtable.csb files from Super Smash Bros. Ultimate.
* [smash-svt](https://github.com/jam1garner/smash-svt) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2023-07-12 - Rust library for reading and writing sound\_volume\_table.svt files from Super Smash Bros. for 3DS/Wii U and Ultimate.
* [Smash 4 CSS Database Editor](https://github.com/Cuyler36/Smash-4-CSS-Database-Editor) ⚠️ Archived - Editor for Super Smash Bros. 4 character database file (ui\_character\_db.bin).
* [minecraft-stdat-viewer](https://github.com/jam1garner/minecraft-stdat-viewer) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2020-10-29 - Viewer for Super Smash Bros. Ultimate's Minecraft stage breakable-block (stdat) format.
* [smush-file](https://github.com/jam1garner/smush-file) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2021-07-24 - Library and CLI for identifying/describing files from Super Smash Bros. Ultimate's smush container format.
* [Sm4shExplorer](https://github.com/jam1garner/Sm4shExplorer) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2018-10-18 - Tool for managing the file-system of Super Smash Bros. for Wii U.
* [BrawlStageManager](https://github.com/libertyernie/BrawlStageManager) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2014-01-30 - Stage (.pac/.rel) and song (.brstm) managers for Brawl mods.
* [DATReaderC](https://github.com/EstevanBR/DATReaderC) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2016-07-06 - A C program that reads a .dat file (Super Smash Bros. Melee)
* [Melee DAT format](https://smashboards.com/threads/melee-dat-format.292603/) - Documentation for Melee's DAT format.

### Harmonix

*Rock Band, Guitar Hero, Amplitude, Dance Dance Revolution Universe, Frequency, Karaoke Revolution.*

* [Nautilus](https://github.com/trojannemo/Nautilus) ⭐ 115 | 🐛 1 | 🌐 C# | 📅 2026-07-30 - All-in-one modding toolkit for Rock Band 3, handling CON/RBA package extraction/repacking, MIDI/DTA editing, milo scene conversion, and album art (WAD) processing.
* [rb3 (decomp)](https://github.com/DarkRTA/rb3) ⭐ 114 | 🐛 0 | 🌐 C++ | 📅 2026-07-16 - Matching decompilation of Rock Band 3 (Wii).
* [LibForge](https://github.com/maxton/LibForge) ⭐ 35 | 🐛 11 | 🌐 C# | 📅 2021-02-21 - Library for reading, writing, and converting Forge engine formats (Rock Band 4, Rock Band VR, FUSER). See also [PikminGuts92's fork](https://github.com/PikminGuts92/LibForge) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2018-12-29 with v2 RB MIDI support, MAGMA v1 milos support, and AMP/RBVR .mid\_\* file support.
  * Formats: MIDI, PNG/BMP (textures), FBX/OBJ (models), DTA/DTB, RBmid, RBsong, lipsync, CON/GP4/PKG (packages).
* [pikaxe](https://github.com/PikminGuts92/pikaxe) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-07-15 - Milo engine modding tool for Harmonix games. Supports Guitar Hero 1-2, Guitar Hero Encore: Rocks the 80s, Rock Band series, Dance Central, and other Milo engine titles. Handles DTA, GLTF, and ARK formats across Xbox, Wii, and PS3. Evolution of Mackiloha.
* [BFForever](https://github.com/PikminGuts92/BFForever) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2026-08-11 - Library for managing and creating game files for BandFuse (PS3, Xbox 360). Handles RIFF files, CELT audio encoding/decoding.
* [themethod3](https://github.com/DarkRTA/themethod3) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2025-05-26 - Tool for decrypting MOGG audio files used by the Rock Band series.
* [re-notes](https://github.com/PikminGuts92/re-notes) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-07-21 - Reverse engineering notes and templates for Harmonix games (Dance Dance Revolution Universe, DJ Hero, Karaoke Revolution) and other titles. Includes 010 Editor templates, Python scripts, and data dumps for BlitzTech, Forge, and Milo engines.
* [DtxCS](https://github.com/maxton/DtxCS) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2021-01-12 - C# library for parsing and interpreting DTA/DTB scripting format used in Rock Band and Guitar Hero games.
* [ghlcrypt](https://github.com/maxton/ghlcrypt) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2019-11-09 - C# tool for Guitar Hero Live.
* [praise-mod](https://github.com/PikminGuts92/praise-mod) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2023-02-05 - Toolkit for creating Guitar Praise custom content. Converts Clone Hero songs to GP format. Supports ogg vorbis audio.
* [CON-Tools](https://github.com/PikminGuts92/CON-Tools) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2018-03-08 - Create, modify, and combine Rock Band CON files. Convert to Phase Shift, Wii, and PS3 formats.
* [WorshipTools](https://github.com/PikminGuts92/WorshipTools) ⚠️ Archived - Converts Jam Band songs to Clone Hero format. (Archived)
* [PyMilo](https://github.com/PikminGuts92/PyMilo) ⚠️ Archived - Python library for managing milo files from Harmonix games. Includes GUI and archive extraction utilities. (Archived)
* [amplitools](https://github.com/PikminGuts92/amplitools) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-11-09 - Tools for Amplitude '03.
* [offbeat](https://github.com/PikminGuts92/offbeat) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2023-09-24 - Rust library for Dance Dance Revolution Universe. Includes DDM to glTF converter.
* [Beatles Rock Band Blender plugin](https://www.moddb.com/games/rock-band/downloads/beatles-rock-band-blender-plugin) - Blender plugin for The Beatles: Rock Band. Created by Turk645.

### 07th Expansion (Higurashi)

* [higurashi-gba-hacktools](https://github.com/karmic64/higurashi-gba-hacktools) ⭐ 27 | 🐛 0 | 🌐 C | 📅 2024-08-06 - Protection removal tool and technical information for the Inside-cap GBA ports of the Higurashi visual novels.

### Hasbro Interactive (Frogger)

* [frogger2-vss](https://github.com/HighwayFrogs/frogger2-vss) ⭐ 116 | 🐛 0 | 🌐 C | 📅 2023-05-08 - Import of the Frogger 2 Visual Source Safe backup ('End of Project' tape backup), the primary source archive the other HighwayFrogs Frogger 2 platform repos derive from.
* [frogger-psx (decomp)](https://github.com/HighwayFrogs/frogger-psx) ⭐ 58 | 🐛 0 | 🌐 C | 📅 2025-06-17 - Matching decompilation of Frogger (1997, PS1, 100%).
* [frogger2-pc](https://github.com/HighwayFrogs/frogger2-pc) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2025-06-16 - Compileable setup of Frogger 2 for PC, recovered from the End of Project VSS backup.
* [frogger2-n64](https://github.com/HighwayFrogs/frogger2-n64) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2024-01-20 - Official source code to the cancelled N64 port of Frogger 2: Swampy's Revenge.
* [frogger2-dc](https://github.com/HighwayFrogs/frogger2-dc) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2023-06-20 - Official source code for Frogger 2: Swampy's Revenge (Dreamcast version).
* [frogger2-psx](https://github.com/HighwayFrogs/frogger2-psx) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2023-06-20 - Official source code for Frogger 2: Swampy's Revenge for the Sony PlayStation.
* [frogger-gb](https://github.com/HighwayFrogs/frogger-gb) ⭐ 6 | 🐛 0 | 🌐 Assembly | 📅 2025-01-04 - Source code to Frogger for Game Boy / Game Boy Color.
* [frogger2-gbc](https://github.com/HighwayFrogs/frogger2-gbc) ⭐ 3 | 🐛 0 | 🌐 Makefile | 📅 2025-01-04 - Source code to Frogger 2 for Game Boy / Game Boy Color.

### Haydee

* [HaydeeTools](https://github.com/johnzero7/HaydeeTools) ⭐ 23 | 🐛 16 | 🌐 Python | 📅 2023-10-28 - Blender addon to import/export Haydee game models, animations, and poses.

### Heavy Gear

* [heavygear-file-formats](https://github.com/AlexKimov/heavygear-file-formats) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2019-03-02 - File formats for Heavy Gear 1 and 2.

### Heavy Iron Studios

* [noclip.website (SpongeBob Battle for Bikini Bottom)](https://github.com/magcius/noclip.website/tree/main/src/HeavyIron) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser SpongeBob BFBB viewer.
* [noclip.website (SpongeBob The Movie)](https://github.com/magcius/noclip.website/tree/main/src/HeavyIron) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser SpongeBob The Movie viewer.
* [noclip.website (SpongeBob Revenge of the Flying Dutchman)](https://github.com/magcius/noclip.website/tree/main/src/SpongebobRevengeOfTheFlyingDutchman) ⭐ 4,241 | 🐛 87 | 🌐 TypeScript | 📅 2026-08-10 - In-browser SpongeBob ROTFD viewer.
* [bfbb (decomp)](https://github.com/bfbbdecomp/bfbb) ⭐ 176 | 🐛 13 | 🌐 C++ | 📅 2026-08-10 - Matching decompilation of SpongeBob SquarePants: Battle for Bikini Bottom.
* [IndustrialPark](https://github.com/igorseabra4/IndustrialPark) ⭐ 60 | 🐛 20 | 🌐 C# | 📅 2026-07-22 - Viewer and editor for SpongeBob SquarePants: Battle for Bikini Bottom and Scooby-Doo games.
* [bfbbpc](https://github.com/seilc/bfbbpc) ⭐ 21 | 🐛 0 | 🌐 C++ | 📅 2023-08-09 - PC port and decompilation of SpongeBob SquarePants: Battle for Bikini Bottom, based on the GameCube version with features from the Xbox version.
* [HipHopTool](https://github.com/igorseabra4/HipHopTool) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2024-05-08 - Tool and library for working with `HIP/HOP` archive files in Heavy Iron Studios games (Scooby-Doo, SpongeBob BB, Incredibles).
* [HeavyModManager](https://github.com/igorseabra4/HeavyModManager) ⭐ 10 | 🐛 3 | 🌐 C# | 📅 2026-08-19 - Mod manager for GameCube and Wii games (Scooby-Doo, Spongebob, Incredibles).
* [HiHoTool](https://github.com/igorseabra4/HiHoTool) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2020-02-14 - Tool and library for working with `.HO` archive files in Heavy Iron Studios games (Ratatouille, WALL-E, Up, SpongeBob's Truth or Square, Family Guy).
* [IndustrialParkHans](https://github.com/igorseabra4/IndustrialParkHans) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2022-12-08 - Save file editor for Heavy Iron Studios games (Scooby-Doo, SpongeBob BB, Incredibles) on GameCube, PS2, and Xbox.
* [SBMI-Decomp (decomp)](https://github.com/Juanen100/SBMI-Decomp) ⭐ 1 | 🐛 1 | 🌐 C# | 📅 2026-08-13 - Matching decompilation of SpongeBob Moves In! (Android).
* [BFBBJSPTool](https://github.com/igorseabra4/BFBBJSPTool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2018-06-13 - JSP tool for SpongeBob SquarePants: Battle for Bikini Bottom.
* [SpyroETDChunkTool](https://github.com/igorseabra4/SpyroETDChunkTool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2018-12-14 - Chunk tool for Spyro: Enter the Dragonfly.

### Headfirst Productions

#### Call of Cthulhu: Dark Corners of the Earth

* [COC\_DCoTE\_export](https://github.com/Trololp/COC_DCoTE_export) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-01-24 - Export tools for Call of Cthulhu: Dark Corners of the Earth (Headfirst Productions, 2005).

### Her Interactive (Nancy Drew)

* [AVFExt](https://github.com/puggsoy/AVFExt) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2025-10-26 - AVF file converter/extractor for Her Interactive games (in particular the Nancy Drew series).

### HeroForge (HeroForge)

* [HeroForge\_parser](https://github.com/REDxEYE/HeroForge_parser) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2019-08-26 - Library for parsing CKB files from HeroForge character creation platform.
* [HeroBuilder](https://github.com/REDxEYE/HeroBuilder) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2022-02-04 - Blender addon for loading HeroForge characters into Blender. Works with CKB files exported from HeroForge.

### HoYoverse

#### Honkai: Star Rail

* [reliquary-archiver](https://github.com/IceDynamix/reliquary-archiver) ⭐ 410 | 🐛 8 | 🌐 Rust | 📅 2026-07-26 - Parses Honkai: Star Rail's network packets to export relic (artifact) data for use with optimizer tools such as fribbels hsr-optimizer. Built on [reliquary](https://github.com/IceDynamix/reliquary) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2026-07-17, the author's library for parsing the game's network protocol.
* [HSR-Scanner](https://github.com/kel-z/HSR-Scanner) ⭐ 202 | 🐛 13 | 🌐 Python | 📅 2026-07-22 - Scanner for exporting light cone, relic, and character data from Honkai: Star Rail to JSON format.

### HROT

* [hrot-cli-tools](https://github.com/joshuaskelly/hrot-cli-tools) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2020-06-18 - Command-line pak/unpak tools for HROT PAK files, complementing [hrotex](https://github.com/iOrange/hrotex) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2021-02-02 above with archive creation support.
* [hrotex](https://github.com/iOrange/hrotex) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2021-02-02 - Command-line archive extractor for HROT's game .pak archives.

### Honey Parade / Marvelous Entertainment

* [blenderBUM](https://github.com/Al-Hydra/blenderBUM) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-11-16 - Blender addon for importing models, animations, and textures from Honey Parade/Marvelous games (.bum, .lzs, .lza formats).

### Hudson Soft

*Mario Party series (Nintendo 64).*

* [PartyPlanner64](https://github.com/PartyPlanner64/PartyPlanner64) ⭐ 134 | 🐛 61 | 🌐 TypeScript | 📅 2025-10-06 - Full-featured board editor and modding tool for Mario Party (N64) games.
* [bland2digtool](https://github.com/gamemasterplc/bland2digtool) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2022-12-11 - Bomberman Land 2 (GameCube) DIG file extractor and rebuilder.
* [mpromtool](https://github.com/gamemasterplc/mpromtool) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2025-03-03 - Mario Party 1-3 (N64) ROM extractor and rebuilder tool.
* [symbols](https://github.com/PartyPlanner64/symbols) ⭐ 3 | 🐛 2 | 📅 2025-09-15 - Debug symbol maps for reverse engineering Mario Party games.
* [mpdsarchivetool](https://github.com/gamemasterplc/mpdsarchivetool) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2024-05-08 - Mario Party DS archive (.bin) extraction tool.
* [mpn64sprtool](https://github.com/gamemasterplc/mpn64sprtool) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2024-05-21 - Tool for dumping and rebuilding sprite graphics from Mario Party N64 games (1-3).
* [bm642romtool](https://github.com/gamemasterplc/bm642romtool) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2025-08-01 - Bomberman 64 The Second Attack ROM compression tool.
* [hsfview](https://github.com/Muzzarino/hsfview) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2019-06-14 - Model viewer for Mario Party (Wii).
* [marioparty8](https://github.com/gamemasterplc/marioparty8) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-22 - GameCube/Wii decompilation of Mario Party 8 using decomp-toolkit with reconstructed binaries and formats.
* [marioparty7](https://github.com/gamemasterplc/marioparty7) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2025-04-12 - Work-in-progress decompilation of Mario Party 7 with reconstructed game binary and file formats.
* [marioparty6](https://github.com/gamemasterplc/marioparty6) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-07-22 - GameCube/Wii decompilation of Mario Party 6 using decomp-toolkit with reconstructed binaries and formats.
* [marioparty5](https://github.com/gamemasterplc/marioparty5) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-05-29 - Work-in-progress decompilation of Mario Party 5 with reconstructed game binary and file formats.

#### Faxanadu

* [faxedit](https://github.com/kaimitai/faxedit) ⭐ 11 | 🐛 3 | 🌐 C++ | 📅 2026-08-18 - Echoes of Eolis: Faxanadu (NES) editing suite.
* [faxanadu (disassembly)](https://github.com/chipx86/faxanadu) ⭐ 3 | 🐛 0 | 🌐 HTML | 📅 2026-07-13 - Disassembly of Faxanadu for the NES.
* [retro-tinkertoys](https://github.com/chipx86/retro-tinkertoys) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-07-13 - Ghidra scripts for retro disassembly work, developed alongside the Faxanadu (NES) disassembly.
* [faxanatools](https://github.com/chipx86/faxanatools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-10-13 - Tools to explore the inner workings of and craft new adventures for Faxanadu (NES).

### Hulabee Entertainment

* [hulabee](https://github.com/cyxx/hulabee) ⚠️ Archived - Tools and a VM for Hulabee Entertainment's proprietary engine, used across its adventure games for kids (Moop and Dreadly in the Treasure on Bing Bong Island, Ollo in the Sunny Valley Fair, Mike's Monstrous Adventure).

### Hydravision Entertainment

#### ObsCure

* [obscure-hvp](https://github.com/YouKnow-sys/obscure-hvp) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2025-12-04 - CLI tool to extract and rebuild HVP archives from Obscure, Obscure II, and Final Exam, covering the PC, PS2, PSP, Xbox, and Wii versions.
* [obscure1-map-parser](https://github.com/ran-j/obscure1-map-parser) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-04-27 - Desktop application for parsing and visualizing binary `.map` files from ObsCure (2004); decodes entity types (blocks, characters, dialog, environment, items, objectives) and presents them as JSON with a map visualization view.
* [HydraVision-Obscure-010-Editor-Templates](https://github.com/Al-Hydra/HydraVision-Obscure-010-Editor-Templates) ⭐ 2 | 🐛 1 | 📅 2026-01-16 - 010 Editor binary templates for Obscure (2004) and Obscure II (2007).

### Human Entertainment (Tadaima Yuusha Boshuuchuu Okawari)

* [TYBOTools](https://github.com/gdkchan/TYBOTools) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2017-11-08 - Translation toolkit for Tadaima Yuusha Boshuuchuu Okawari (SNES).

### Human Head Studios

* [Gwynhala's Model Exporter (Rune)](https://www.moddb.com/games/rune/downloads/gwynhalas-model-exporter) - Rune SuperCoolModel Exporter for Milkshape 3D by Gwynhala
* [io\_scene\_scm](https://github.com/cmbasnett/io_scene_scm) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-03-14 - Blender add-on for importing and exporting SuperCoolModel (SCM) files from Rune (2001).

#### Prey

* [Prey2006](https://github.com/FriskTheFallenHuman/Prey2006) ⭐ 104 | 🐛 10 | 🌐 C | 📅 2026-07-23 - Source port/engine project for Prey (2006, Human Head Studios), built on id Tech 4 and reading the original game's data files.

### id Software

#### Commander Keen

* [omnispeak](https://github.com/sulix/omnispeak) ⭐ 316 | 🐛 14 | 🌐 C | 📅 2026-07-12 - Open-source re-implementation of the Commander Keen in Goodbye Galaxy (episodes 4-6) engine, reading the original game's data files.
* [Commander Keen 4 Tandy source port](https://github.com/FrenkelS/keensource456tandy) ⭐ 24 | 🐛 9 | 🌐 C | 📅 2024-01-14 - Source port of Commander Keen 4 adding Tandy 320x200 16-color graphics mode support, reading the original game's EGA data files.
* [TED5](https://github.com/Fleex255/TED5) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2014-06-14 - id Software's original TED5 level editor used for Commander Keen, restored and running on modern systems.

#### Catacomb 3-D & Adventure Series

* [CatacombGL](https://github.com/ArnoAnsems/CatacombGL) ⭐ 188 | 🐛 19 | 🌐 C++ | 📅 2026-08-15 - OpenGL source port for Catacomb 3-D (1991, id Software) and the Catacomb Adventure series (Softdisk, 1992-1993: The Catacomb Abyss, Armageddon, and Apocalypse), reading the original games' EGA/VGA graphics, level, and sound data.

#### Wolfenstein 3D & Spear of Destiny

* [wolf3d](https://github.com/id-Software/wolf3d) ⭐ 2,519 | 🐛 1 | 📅 2012-02-06 - id Software's official 1995 open-source release of Wolfenstein 3D, including the original VSWAP/GAMEMAPS/AUDIOT-reading engine.
* [WolfensteinCGA](https://github.com/jhhoward/WolfensteinCGA) ⭐ 350 | 🐛 15 | 🌐 C | 📅 2026-04-14 - Wolfenstein 3D port targeting CGA graphics, reading the original game's VSWAP/GAMEMAPS assets.
* [Wolf3D-Mac (original release)](https://github.com/Blzut3/Wolf3D-Mac) ⚠️ Archived - id Software's original Macintosh source release for Wolfenstein 3D: First & Second Encounter, including the original VSWAP/GAMEMAPS-reading engine code. *(Archived.)*
* [ECWolf](https://github.com/ECWolfEngine/ECWolf) ⭐ 47 | 🐛 71 | 🌐 C++ | 📅 2026-02-23 - Cross-platform Wolfenstein 3D and Spear of Destiny source port also supporting Super 3-D Noah's Ark and Blake Stone, reading original VSWAP/GAMEMAPS/AUDIOT data.
* [wolf4sdl](https://github.com/fabiangreffrath/wolf4sdl) ⭐ 41 | 🐛 3 | 🌐 C++ | 📅 2026-05-04 - SDL port of Wolfenstein 3D and Spear of Destiny, the canonical open-source base for the Wolf3D modding/tooling ecosystem, reading the original id Software level/graphics/sound formats.
* [MacWolf for DOS](https://github.com/FrenkelS/Wolf3D-Mac-for-DOS) ⭐ 28 | 🐛 14 | 🌐 C | 📅 2026-06-29 - Ports the Macintosh version of Wolfenstein 3D (different graphics, sound, music and levels from the DOS version) to run on DOS.
* [MacWolfSDL](https://github.com/kaylagator/MacWolfSDL) ⭐ 20 | 🐛 9 | 🌐 C | 📅 2025-08-18 - Accurate SDL3 source port of Macintosh Wolfenstein 3D, reading the original Mac resource-fork game data (including Third Encounter scenario compatibility).
* [Wolf3DExtract](https://github.com/HiPhish/Wolf3DExtract) ⭐ 19 | 🐛 2 | 🌐 C | 📅 2019-05-20 - Command-line tool for extracting graphics, sounds, and level assets from the PC version of Wolfenstein 3D.
* [eced](https://github.com/InsanityBringer/eced) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2022-04-09 - Level editor for blzut3's ECWolf, a Wolfenstein 3D-engine derivative, editing the game's level format.
* [WolfstoneExtract](https://github.com/ECWolfEngine/WolfstoneExtract) ⭐ 3 | 🐛 3 | 🌐 C++ | 📅 2025-12-26 - Extracts Wolfenstein 3D-compatible game data from an installed copy of Wolfenstein II: The New Colossus or Wolfenstein: Youngblood, converting the modern titles' archives and Wwise BNK/WEM audio into a wolfstone.pk3/elitehans.pk3 usable with ECWolf-based source ports.
* [WolfViewer](https://github.com/ioan-chera/WolfViewer) ⭐ 2 | 🐛 1 | 🌐 Java | 📅 2015-11-12 - Wolfenstein 3D viewer and editor for Android, displaying map walls and sprites.
* [MacWolfEd](https://github.com/ioan-chera/MacWolfEd) ⭐ 1 | 🐛 0 | 🌐 Swift | 📅 2020-08-16 - macOS editor for Wolfenstein 3D and Spear of Destiny, editing levels, graphics, sounds, and music directly from the original game folder.

#### Doom Engine (id Tech 1) & Ports

* [SLADE](https://github.com/sirjuddington/SLADE) ⭐ 861 | 🐛 316 | 🌐 C++ | 📅 2026-08-18 - The comprehensive Doom-engine (id Tech 1) editor. Edit WAD/PK3/ZIP archives, maps, textures, graphics, sounds, and text lumps, with support for Doom, Heretic, Hexen, Strife, and other id Tech 1 games.
* [UltimateDoomBuilder](https://github.com/UltimateDoomBuilder/UltimateDoomBuilder) ⭐ 545 | 🐛 411 | 🌐 C# | 📅 2026-07-22 - The actively maintained successor to Doom Builder / GZDoom Builder; a comprehensive map editor for Doom-engine (id Tech 1) games, reading and writing WAD map data.
* [Eternity Engine](https://github.com/team-eternity/eternity) ⭐ 266 | 🐛 217 | 🌐 C++ | 📅 2026-08-13 - Advanced Doom source port that originated the UDMF map format and introduces its own EDF (Eternity Definition File) format for game data.
* [DOOM64-RE (decomp)](https://github.com/Erick194/DOOM64-RE) ⭐ 235 | 🐛 1 | 🌐 C | 📅 2025-05-30 - Matching decompilation of Doom 64.
* [PSXDOOM-RE (decomp)](https://github.com/Erick194/PSXDOOM-RE) ⭐ 160 | 🐛 1 | 🌐 C | 📅 2025-05-30 - Matching decompilation of Doom (PlayStation).
* [wadext](https://github.com/ZDoom/wadext) ⭐ 122 | 🐛 3 | 🌐 C | 📅 2024-01-01 - Simple WAD extraction command-line tool for Doom engine (id Tech 1) mods. Extracts and converts Doom format patches/flats to PNG and sounds to WAV. Supports Doom, Heretic, Hexen, and Strife palettes.
* [Eureka](https://github.com/ioan-chera/eureka-editor) ⭐ 105 | 🐛 132 | 🌐 C++ | 📅 2026-08-14 - Cross-platform map editor for the Doom engine (id Tech 1).
* [wadc](https://github.com/jmtd/wadc) ⭐ 81 | 🐛 27 | 🌐 Java | 📅 2025-07-25 - Programming language and compiler for const
* [WhackEd4](https://github.com/GitExl/WhackEd4) ⭐ 55 | 🐛 15 | 🌐 Python | 📅 2026-01-07 - Modern replacement for the DOS-based Dehacked tool, loading and editing Doom Dehacked (.deh/.bex) patch files.
* [wad2gltf](https://github.com/DethRaid/wad2gltf) ⭐ 27 | 🐛 1 | 🌐 C++ | 📅 2024-03-17 - Converts Doom WAD map geometry to the glTF runtime format.
* [UDMF-Convert](https://github.com/CO2/UDMF-Convert) ⭐ 13 | 🐛 2 | 🌐 C++ | 📅 2010-09-05 - Converts Doom maps to/from the UDMF (Universal Doom Map Format) text-based map format.
* [DOOMP](https://github.com/Ret-HZ/DOOMP) ⚠️ Archived - Doom file format parser and extractor.
* [WADMerge](https://github.com/GitExl/WADMerge) ⭐ 8 | 🐛 0 | 🌐 D | 📅 2016-08-05 - Merges multiple Doom WAD files into one, correctly combining TEXTURE/PNAMES lumps, maps, and namespaced/text lumps.
* [DoomRPG-RE-3DS](https://github.com/efimandreev0/DoomRPG-RE-3DS) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2026-01-08 - Nintendo 3DS port of the reverse engineered Doom RPG.
* [ExtractDoomDisk](https://github.com/gibbed/ExtractDoomDisk) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2021-09-16 - Extractor for Doom disk image files.
* [WolfensteinRPG-RE-3DS](https://github.com/efimandreev0/WolfensteinRPG-RE-3DS) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2025-08-19 - Reverse-engineered implementation of Wolfenstein RPG ported to Nintendo 3DS with SDL2, Zlib, and OpenAL dependencies.
* [UDMF-Converter-EE](https://github.com/ioan-chera/UDMF-Converter-EE) ⭐ 0 | 🐛 1 | 🌐 C++ | 📅 2019-10-03 - UDMF map format converter specifically for the Eternity Engine.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
