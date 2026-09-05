# 🎮 Awesome Game File Format Reversing with stars

[Awesome](https://github.com/sindresorhus/awesome) ⭐ 503,117 | 🐛 106 | 📅 2026-09-02
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
    * [Dota 2](#dota-2)
    * [Portal](#portal)
  * [reSource Engine (Respawn Entertainment)](#resource-engine-respawn-entertainment)
  * [Unity](#unity)
    * [Asset Extraction & Asset Bundle Tools](#asset-extraction--asset-bundle-tools)
    * [IL2CPP & Managed-Code Reverse Engineering](#il2cpp--managed-code-reverse-engineering)
    * [Modding, Translation & Runtime Injection](#modding-translation--runtime-injection)
    * [Texture Decoders](#texture-decoders)
    * [Save File Tools](#save-file-tools)
    * [VideoClip Transcoding](#videoclip-transcoding)
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
  * [ACK-3D](#ack-3d)
  * [Cobra Engine](#cobra-engine)
  * [3DSTATE](#3dstate)
  * [AtiSushi Engine](#atisushi-engine)
  * [Genie Engine](#genie-engine)
  * [Bruns Engine](#bruns-engine)
  * [Stargaze Engine](#stargaze-engine)
  * [GIANTS Engine](#giants-engine)
  * [Blitz3D / BlitzPlus](#blitz3d--blitzplus)
  * [StepMania](#stepmania)
  * [RPG Maker](#rpg-maker)
  * [Wolf RPG Editor](#wolf-rpg-editor)
  * [SRPG Studio](#srpg-studio)
  * [Ren'Py](#renpy)
  * [AliceSoft (Alice/System 4 Engine)](#alicesoft-alicesystem-4-engine)
  * [Aquaplus (Leaf)](#aquaplus-leaf)
    * [ToHeart2 DX PLUS](#toheart2-dx-plus)
    * [Utawarerumono](#utawarerumono)
  * [Escude](#escude)
  * [Eushully](#eushully)
  * [Mware](#mware)
  * [Unison Shift](#unison-shift)
  * [BGI (Buriko General Interpreter)](#bgi-buriko-general-interpreter)
  * [RealLive](#reallive)
  * [Kirikiri](#kirikiri)
  * [ONScripter](#onscripter)
  * [Light.vn](#lightvn)
  * [C,system Engine](#csystem-engine)
  * [CatSystem2](#catsystem2)
  * [Propeller Engine](#propeller-engine)
  * [Whale Engine](#whale-engine)
  * [AaruSystem Engine](#aarusystem-engine)
  * [ADVSYS3 Engine](#advsys3-engine)
  * [AILSystem Engine](#ailsystem-engine)
  * [Artemis Engine](#artemis-engine)
  * [AVG32](#avg32)
  * [AVGEngine V2 / GxEngine V3](#avgengine-v2--gxengine-v3)
  * [Bishop Engine](#bishop-engine)
  * [Circus (Mes Engine)](#circus-mes-engine)
  * [CIS Engine](#cis-engine)
  * [DDSystem](#ddsystem)
  * [Debonosu Works Engine](#debonosu-works-engine)
  * [Edoire](#edoire)
  * [elf / Silky's](#elf--silkys)
  * [EntisGLS](#entisgls)
  * [FamilyAdvSystem Engine](#familyadvsystem-engine)
  * [Famous Writer](#famous-writer)
  * [FFA System Engine](#ffa-system-engine)
  * [FVP Engine](#fvp-engine)
  * [GSIWin](#gsiwin)
  * [GsPack4](#gspack4)
  * [GXC Engine](#gxc-engine)
  * [InnocentGrey](#innocentgrey)
  * [Kaguya](#kaguya)
  * [Kurumi Engine](#kurumi-engine)
  * [Liar-soft / raiL-soft](#liar-soft--rail-soft)
  * [LiLiM / Sugar Engine](#lilim--sugar-engine)
  * [LiveMaker](#livemaker)
  * [LucaSystem](#lucasystem)
  * [Lucifen](#lucifen)
  * [Majiro](#majiro)
  * [Malie](#malie)
  * [Marble Engine](#marble-engine)
  * [NekoGameSDK](#nekogamesdk)
  * [NeXAS](#nexas)
  * [PJADV Engine](#pjadv-engine)
  * [RioShiina](#rioshiina)
  * [rUGP (AGES Player)](#rugp-ages-player)
  * [Siglus](#siglus)
  * [Silky Engine (AI6WIN)](#silky-engine-ai6win)
  * [SLG System](#slg-system)
  * [SofthouseChara Aoi](#softhousechara-aoi)
  * [Softpal](#softpal)
  * [Sogna Engine](#sogna-engine)
  * [Tactics ADV/Script Engine](#tactics-advscript-engine)
  * [Tanuki Soft / Kaeru Soft (BCS)](#tanuki-soft--kaeru-soft-bcs)
  * [Tmr-Hiro ADV System](#tmr-hiro-adv-system)
  * [TS System](#ts-system)
  * [Valkyria's Engine](#valkyrias-engine)
  * [WildBug](#wildbug)
  * [WillPlus/AdvHD](#willplusadvhd)
  * [Xuse / Eternal](#xuse--eternal)
  * [Yuka System](#yuka-system)
  * [YU-RIS](#yu-ris)
  * [Glulx VM (Interactive Fiction)](#glulx-vm-interactive-fiction)
  * [Z-machine VM (Interactive Fiction)](#z-machine-vm-interactive-fiction)
    * [Interpreters & Players](#interpreters--players)
    * [Authoring & Compiler Tools](#authoring--compiler-tools)
    * [Story File Tools, Disassemblers & Archives](#story-file-tools-disassemblers--archives)
    * [Glk Display API & Libraries](#glk-display-api--libraries)
  * [Magnetic Scrolls VM (Interactive Fiction)](#magnetic-scrolls-vm-interactive-fiction)
  * [AGT (Adventure Game Toolkit)](#agt-adventure-game-toolkit)
  * [Level 9 VM (Interactive Fiction)](#level-9-vm-interactive-fiction)
  * [TADS VM (Interactive Fiction)](#tads-vm-interactive-fiction)
  * [ADRIFT VM (Interactive Fiction)](#adrift-vm-interactive-fiction)
  * [Alan VM (Interactive Fiction)](#alan-vm-interactive-fiction)
  * [Twine (Interactive Fiction)](#twine-interactive-fiction)
  * [Yarn Spinner (Dialogue Middleware)](#yarn-spinner-dialogue-middleware)
  * [Rawthrills G7 Engine](#rawthrills-g7-engine)
  * [Marmalade SDK](#marmalade-sdk)
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
  * [PICO-8 (Lexaloffle Games)](#pico-8-lexaloffle-games)
* [🔧 Middleware & SDKs](#-middleware--sdks)
  * [Fast3d/F3dex (N64)](#fast3df3dex-n64)
  * [Granite SDK](#granite-sdk)
  * [Havok](#havok)
  * [JSYSTEM (GameCube/Wii)](#jsystem-gamecubewii)
  * [SEAD (Nintendo EAD/EPD Engine)](#sead-nintendo-eadepd-engine)
  * [Mii (RFL/FFL Face Library)](#mii-rflffl-face-library)
  * [Katana Engine (Koei Tecmo)](#katana-engine-koei-tecmo)
  * [M3G (Mobile 3D Graphics API)](#m3g-mobile-3d-graphics-api)
  * [Murder Engine](#murder-engine)
  * [NETLizard (J2ME Game Engine)](#netlizard-j2me-game-engine)
  * [Nebula Engine](#nebula-engine)
  * [MikuMikuDance](#mikumikudance)
  * [Cal3D](#cal3d)
  * [Spine (2D Skeletal Animation Middleware)](#spine-2d-skeletal-animation-middleware)
  * [RenderWare](#renderware)
  * [CRI](#cri)
  * [PSB (Persistent Serialized Binary)](#psb-persistent-serialized-binary)
  * [XNA](#xna)
  * [Sappy (GBA Audio)](#sappy-gba-audio)
  * [RAD Game Tools](#rad-game-tools)
  * [Virtools](#virtools)
  * [Nintendo SDKs & Hardware](#nintendo-sdks--hardware)
    * [Switch](#switch)
    * [iQue Player](#ique-player)
    * [Wii U](#wii-u)
    * [3DS](#3ds)
      * [Container & ROM Formats (CXI/CFA/CCI/CIA/NCCH/RomFS)](#container--rom-formats-cxicfacciciancchromfs)
      * [Encryption, Keys, Save Data, Titles & CDN](#encryption-keys-save-data-titles--cdn)
      * [Graphics, Models, Textures & Fonts (CTPK/BCH/CGFX/BCLIM)](#graphics-models-textures--fonts-ctpkbchcgfxbclim)
      * [Homebrew, CFW & Mod Tools](#homebrew-cfw--mod-tools)
    * [GameCube & Wii](#gamecube--wii)
      * [Disc Images, Filesystem & Memory Card Formats](#disc-images-filesystem--memory-card-formats)
      * [Executables, Code Injection & Modding](#executables-code-injection--modding)
      * [SDK, System Libraries & Decompilations](#sdk-system-libraries--decompilations)
      * [Emulation, Audio, Video & Wii Channel Tools](#emulation-audio-video--wii-channel-tools)
    * [Nintendo DS / DSi](#nintendo-ds--dsi)
    * [Nintendo 64](#nintendo-64)
    * [SNES / NES](#snes--nes)
    * [Game Boy / GBA](#game-boy--gba)
      * [ROM Tools, Disassemblers & Format Libraries](#rom-tools-disassemblers--format-libraries)
      * [Hardware & Die-Level Reverse Engineering](#hardware--die-level-reverse-engineering)
      * [Game Boy Camera & Printer](#game-boy-camera--printer)
      * [Mobile Adapter GB](#mobile-adapter-gb)
    * [Cross-Platform Formats & Archives](#cross-platform-formats--archives)
      * [Archive & Container Formats](#archive--container-formats)
      * [Text, Message & Localization (MSBT/LMS)](#text-message--localization-msbtlms)
      * [Models, Textures, Fonts & Rendering](#models-textures-fonts--rendering)
      * [Scripting, Parameters & Game Data](#scripting-parameters--game-data)
      * [Audio](#audio)
      * [amiibo (NFC Tag Data)](#amiibo-nfc-tag-data)
  * [Sharp X68000 SDKs & Hardware](#sharp-x68000-sdks--hardware)
  * [PlayStation SDKs & Hardware](#playstation-sdks--hardware)
  * [WonderSwan SDKs & Hardware](#wonderswan-sdks--hardware)
  * [Xbox SDKs & Hardware](#xbox-sdks--hardware)
  * [Games for Windows Live (GFWL)](#games-for-windows-live-gfwl)
  * [Tamagotchi (Bandai) Hardware](#tamagotchi-bandai-hardware)
    * [Tamagotchi Paradise](#tamagotchi-paradise)
  * [Digimon Color (Bandai) Hardware](#digimon-color-bandai-hardware)
  * [Sega SDKs & Hardware](#sega-sdks--hardware)
  * [FMOD](#fmod)
  * [SpeedTree](#speedtree)
  * [Wwise](#wwise)
  * [Prism3D](#prism3d)
  * [Steam (Valve) Platform Tools](#steam-valve-platform-tools)
* [Game & Studio Tools](#game--studio-tools)
  * [0verflow (School Days)](#0verflow-school-days)
  * [11 bit studios (Frostpunk)](#11-bit-studios-frostpunk)
  * [1C Company / Best Way](#1c-company--best-way)
    * [Men of War](#men-of-war)
    * [Royal Quest Online](#royal-quest-online)
    * [Adventures of Captain Blood](#adventures-of-captain-blood)
  * [2K Czech / Illusion Softworks](#2k-czech--illusion-softworks)
  * [2K Games / Firaxis Games](#2k-games--firaxis-games)
    * [BioShock](#bioshock)
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
    * [Might and Magic VI, VII, VIII](#might-and-magic-vi-vii-viii)
    * [Heroes of Might and Magic II](#heroes-of-might-and-magic-ii)
    * [Heroes of Might and Magic III](#heroes-of-might-and-magic-iii)
    * [Heroes of Might and Magic IV](#heroes-of-might-and-magic-iv)
  * [4A Games](#4a-games)
    * [Metro](#metro)
  * [5pb. / Nitroplus (Steins;Gate)](#5pb--nitroplus-steinsgate)
    * [Re:Zero: -Starting Life in Another World- Death or Kiss](#rezero--starting-life-in-another-world--death-or-kiss)
    * [Memories Off: -Innocent Fille-](#memories-off--innocent-fille-)
  * [4Head Studios](#4head-studios)
  * [5th Cell](#5th-cell)
  * [8monkey Labs](#8monkey-labs)
  * [A\&F Software (Chuckie Egg)](#af-software-chuckie-egg)
  * [Access Games (Deadly Premonition)](#access-games-deadly-premonition)
  * [Acclaim Entertainment (Turok)](#acclaim-entertainment-turok)
  * [Accolade (Eradicator)](#accolade-eradicator)
  * [Acornsoft](#acornsoft)
    * [Elite](#elite)
  * [Acquire (Akiba's Trip)](#acquire-akibas-trip)
  * [Akella](#akella)
  * [Action Forms (Chasm: The Rift)](#action-forms-chasm-the-rift)
  * [Activ Pub (Rival Realms)](#activ-pub-rival-realms)
  * [Activision / Infinity Ward / Treyarch](#activision--infinity-ward--treyarch)
    * [Call of Duty](#call-of-duty)
      * [Asset Extraction & Conversion Tools](#asset-extraction--conversion-tools)
      * [Fastfile & Zone Tools](#fastfile--zone-tools)
      * [Map & Level Editing Tools](#map--level-editing-tools)
      * [Scripting, UI, Audio & Shader Tools](#scripting-ui-audio--shader-tools)
      * [Modding Kits & Client Tools](#modding-kits--client-tools)
      * [Save Tools](#save-tools)
      * [Demo Recording & Playback Tools](#demo-recording--playback-tools)
    * [Call to Power II](#call-to-power-ii)
    * [Tony Hawk's Pro Skater](#tony-hawks-pro-skater)
    * [Ghostbusters](#ghostbusters)
    * [A Series of Unfortunate Events](#a-series-of-unfortunate-events)
    * [Spider-Man (Neversoft)](#spider-man-neversoft)
    * [Spider-Man: The Movie (Treyarch)](#spider-man-the-movie-treyarch)
    * [Spider-Man: Web of Shadows (Treyarch)](#spider-man-web-of-shadows-treyarch)
    * [Wolfenstein (2009)](#wolfenstein-2009)
    * [PSX Activision Games](#psx-activision-games)
  * [Adeline Software International](#adeline-software-international)
    * [Little Big Adventure 1](#little-big-adventure-1)
    * [Little Big Adventure 2](#little-big-adventure-2)
    * [Time Commando](#time-commando)
  * [ADvertainment Software (Quiver)](#advertainment-software-quiver)
  * [Aether Studios (Rivals of Aether)](#aether-studios-rivals-of-aether)
  * [AKI Corporation](#aki-corporation)
  * [Alfa System (Neon Genesis Evangelion 2)](#alfa-system-neon-genesis-evangelion-2)
  * [Algoryx (Algodoo / Phun)](#algoryx-algodoo--phun)
  * [Amber Studio](#amber-studio)
  * [Analgesic Productions](#analgesic-productions)
    * [Anodyne](#anodyne)
    * [Anodyne 2](#anodyne-2)
    * [Even the Ocean](#even-the-ocean)
  * [Andrew Shouldice (Tunic)](#andrew-shouldice-tunic)
  * [Angel Matrix (Neon White)](#angel-matrix-neon-white)
  * [Angel Studios / Rockstar San Diego](#angel-studios--rockstar-san-diego)
  * [Ankama Games](#ankama-games)
    * [Wakfu](#wakfu)
  * [Anthony Bongers](#anthony-bongers)
  * [Ape, Inc](#ape-inc)
  * [Arc System Works](#arc-system-works)
    * [Under Night In-Birth](#under-night-in-birth)
    * [True Remembrance](#true-remembrance)
    * [BlazBlue](#blazblue)
  * [Apogee Software](#apogee-software)
    * [Crystal Caves](#crystal-caves)
    * [Duke Nukem II](#duke-nukem-ii)
    * [Blake Stone (Aliens of Gold, Planet Strike)](#blake-stone-aliens-of-gold-planet-strike)
  * [ArenaNet (Guild Wars)](#arenanet-guild-wars)
    * [Guild Wars 2](#guild-wars-2)
  * [Argentum Online](#argentum-online)
  * [Argonaut Games](#argonaut-games)
  * [Arkane Studios](#arkane-studios)
  * [Armature Studio (Batman: Arkham Origins Blackgate)](#armature-studio-batman-arkham-origins-blackgate)
  * [Armonica (Detective Instinct)](#armonica-detective-instinct)
  * [Arrowhead Game Studios (Helldivers 2)](#arrowhead-game-studios-helldivers-2)
  * [Ascaron Entertainment (Sacred)](#ascaron-entertainment-sacred)
  * [Assembly Line (Supaplex)](#assembly-line-supaplex)
  * [Asmik Ace Entertainment (LSD: Dream Emulator)](#asmik-ace-entertainment-lsd-dream-emulator)
  * [Asobo Studio](#asobo-studio)
  * [Atari, Inc. (Raiders of the Lost Ark)](#atari-inc-raiders-of-the-lost-ark)
  * [Atlus](#atlus)
  * [ATOM Team (Atom RPG)](#atom-team-atom-rpg)
  * [Attack on Titan](#attack-on-titan)
  * [Aurogon (Gujian)](#aurogon-gujian)
  * [Avalanche Studios (Generation Zero)](#avalanche-studios-generation-zero)
  * [Bandai Namco](#bandai-namco)
    * [Jump Force](#jump-force)
    * [Mobile Suit Gundam: Extreme Vs. Series](#mobile-suit-gundam-extreme-vs-series)
    * [THE iDOLM@STER Cinderella Girls Starlight Stage](#the-idolmster-cinderella-girls-starlight-stage)
    * [Gakuen iDOLM@STER](#gakuen-idolmster)
    * [THE iDOLM@STER: SHINY COLORS Song for Prism](#the-idolmster-shiny-colors-song-for-prism)
    * [Dragon Ball](#dragon-ball)
    * [Tales Of](#tales-of)
  * [Bakemonogatari](#bakemonogatari)
  * [Banpresto](#banpresto)
    * [Super Robot Wars](#super-robot-wars)
  * [Battle Raper](#battle-raper)
  * [Battlestate Games (Escape from Tarkov)](#battlestate-games-escape-from-tarkov)
  * [BeamNG GmbH (BeamNG.drive)](#beamng-gmbh-beamngdrive)
  * [Beetle Crazy Cup](#beetle-crazy-cup)
  * [BeeWorks (Mushroom Garden Neo)](#beeworks-mushroom-garden-neo)
  * [Behaviour Interactive (Dead by Daylight)](#behaviour-interactive-dead-by-daylight)
  * [Bethesda](#bethesda)
    * [Elder Scrolls](#elder-scrolls)
    * [Fallout](#fallout)
  * [Bigpoint (Drakensang Online)](#bigpoint-drakensang-online)
  * [Big Boat Interactive (Battlezone: Combat Commander)](#big-boat-interactive-battlezone-combat-commander)
  * [BioWare](#bioware)
    * [Mass Effect](#mass-effect)
    * [Dragon Age: Origins](#dragon-age-origins)
    * [Star Wars: The Old Republic](#star-wars-the-old-republic)
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
      * [Diablo I / Hellfire](#diablo-i--hellfire)
      * [Diablo II / Resurrected](#diablo-ii--resurrected)
    * [Hearthstone](#hearthstone)
  * [Bloody Roar](#bloody-roar)
  * [Blue Byte (The Settlers)](#blue-byte-the-settlers)
    * [Albion](#albion)
    * [Anno 1602](#anno-1602)
  * [Bluehole Studio (TERA)](#bluehole-studio-tera)
  * [BLUEPOCH (Reverse: 1999)](#bluepoch-reverse-1999)
  * [Bob Hays (Hypercycles)](#bob-hays-hypercycles)
  * [Bohemia Interactive](#bohemia-interactive)
  * [Bokura](#bokura)
    * [Blue Protocol: Star Resonance](#blue-protocol-star-resonance)
  * [Blueside (Kingdom Under Fire II)](#blueside-kingdom-under-fire-ii)
  * [Bone Town](#bone-town)
  * [Boss Game Studios (Top Gear Rally)](#boss-game-studios-top-gear-rally)
  * [Brain Jar Games (Dead as Disco)](#brain-jar-games-dead-as-disco)
  * [Brno Transit](#brno-transit)
  * [Brøderbund](#brøderbund)
    * [Lode Runner](#lode-runner)
    * [Karateka](#karateka)
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
    * [Magic Carpet](#magic-carpet)
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
    * [Dead Rising](#dead-rising)
  * [Carbon Games (AirMech)](#carbon-games-airmech)
  * [Carbine Studios (WildStar)](#carbine-studios-wildstar)
  * [CCP Games (EVE Online)](#ccp-games-eve-online)
  * [CCR (RF Online)](#ccr-rf-online)
  * [CD Projekt Red](#cd-projekt-red)
    * [The Witcher 3 / REDEngine 3](#the-witcher-3--redengine-3)
    * [The Witcher](#the-witcher)
    * [Cyberpunk 2077 / REDEngine 4](#cyberpunk-2077--redengine-4)
  * [Century Interactive](#century-interactive)
    * [Bermuda Syndrome](#bermuda-syndrome)
  * [Charybdis (Machines: Wired for War)](#charybdis-machines-wired-for-war)
  * [Chasing Carrots (Halls of Torment)](#chasing-carrots-halls-of-torment)
  * [Chris Sawyer (Transport Tycoon & Locomotion)](#chris-sawyer-transport-tycoon--locomotion)
  * [Chronic Logic (Gish)](#chronic-logic-gish)
  * [Chuck Sommerville (Chip's Challenge)](#chuck-sommerville-chips-challenge)
  * [Chucklefish (Starbound)](#chucklefish-starbound)
  * [CIRCUS (Da Capo)](#circus-da-capo)
  * [Climax Entertainment (Landstalker)](#climax-entertainment-landstalker)
  * [Climax Studios (Rocket Knight)](#climax-studios-rocket-knight)
    * [Sudeki](#sudeki)
  * [Cloud Imperium Games (Star Citizen)](#cloud-imperium-games-star-citizen)
  * [Clover Studio (Okami)](#clover-studio-okami)
  * [Creat Studio](#creat-studio)
  * [Com2uS](#com2us)
    * [Inotia4](#inotia4)
    * [Summoners War: Sky Arena](#summoners-war-sky-arena)
  * [Compile Heart (Hyperdimension Neptunia)](#compile-heart-hyperdimension-neptunia)
  * [Conic Games](#conic-games)
    * [Exponential Idle](#exponential-idle)
  * [Constantine](#constantine)
  * [Contrail (Legend of Legaia)](#contrail-legend-of-legaia)
  * [Codemasters](#codemasters)
  * [CR-Space (Martial Heroes)](#cr-space-martial-heroes)
  * [Creature Labs (Creatures)](#creature-labs-creatures)
  * [Croteam](#croteam)
  * [Crows Crows Crows](#crows-crows-crows)
  * [Cryo Interactive](#cryo-interactive)
    * [Dune (1992)](#dune-1992)
  * [Crystal Dynamics / Eidos Interactive](#crystal-dynamics--eidos-interactive)
    * [Legacy of Kain](#legacy-of-kain)
    * [Gex](#gex)
    * [Tomb Raider](#tomb-raider)
    * [Deus Ex](#deus-ex)
  * [Custom Order Maid 3D2](#custom-order-maid-3d2)
  * [Cyan Worlds](#cyan-worlds)
  * [CyberConnect2](#cyberconnect2)
  * [Cyberdreams](#cyberdreams)
  * [CyberFlix](#cyberflix)
  * [CyberStep (CosmicBreak)](#cyberstep-cosmicbreak)
  * [Cygames (Granblue Fantasy Relink)](#cygames-granblue-fantasy-relink)
    * [Dragalia Lost](#dragalia-lost)
    * [Princess Connect Re:Dive](#princess-connect-redive)
    * [Uma Musume Pretty Derby](#uma-musume-pretty-derby)
  * [Cygnus Studios (Raptor: Call of the Shadows)](#cygnus-studios-raptor-call-of-the-shadows)
  * [D3 Publisher](#d3-publisher)
    * [Earth Defense Force](#earth-defense-force)
  * [Data Design Interactive (LEGO Rock Raiders)](#data-design-interactive-lego-rock-raiders)
  * [Datamost (The Bilestoad)](#datamost-the-bilestoad)
  * [Day 1 Studios / FASA Interactive (MechAssault)](#day-1-studios--fasa-interactive-mechassault)
  * [Disney Interactive](#disney-interactive)
    * [Toontown Online](#toontown-online)
    * [Club Penguin](#club-penguin)
  * [Deck13 Interactive (Lords of the Fallen)](#deck13-interactive-lords-of-the-fallen)
  * [Deep Red Games](#deep-red-games)
    * [AtmosFear](#atmosfear)
    * [Total Overdose](#total-overdose)
  * [Delphine Software](#delphine-software)
    * [Another World](#another-world)
    * [Fade to Black](#fade-to-black)
    * [Flashback](#flashback)
    * [Igor](#igor)
  * [DeLyric Games (Target)](#delyric-games-target)
  * [Demiurge Studios](#demiurge-studios)
  * [Denton Designs (The Great Escape)](#denton-designs-the-great-escape)
  * [Di Gi Charat](#di-gi-charat)
  * [Digital Extremes](#digital-extremes)
    * [The Darkness II](#the-darkness-ii)
    * [Warframe](#warframe)
  * [Digital Anvil (Freelancer)](#digital-anvil-freelancer)
  * [Digital Illusions (SkyRoads)](#digital-illusions-skyroads)
  * [Distinctive Software (Stunts)](#distinctive-software-stunts)
  * [Dogbyte Games](#dogbyte-games)
  * [Doki Denki Studio (Piglet's Big Game)](#doki-denki-studio-piglets-big-game)
  * [DOKA Studios](#doka-studios)
  * [Double Damage Games (Rebel Galaxy Outlaw)](#double-damage-games-rebel-galaxy-outlaw)
  * [Dragon Soul (MMORPG)](#dragon-soul-mmorpg)
  * [Dragon's Prophet](#dragons-prophet)
  * [DreamForge Intertainment (Ravenloft)](#dreamforge-intertainment-ravenloft)
  * [DreamWorks Interactive (The Lost World: Jurassic Park)](#dreamworks-interactive-the-lost-world-jurassic-park)
  * [Double Fine (Psychonauts, Costume Quest)](#double-fine-psychonauts-costume-quest)
  * [Dynamix / Sierra](#dynamix--sierra)
    * [Tribes Series](#tribes-series)
    * [Earthsiege](#earthsiege)
  * [Edelweiss](#edelweiss)
    * [Sakuna: Of Rice and Ruin](#sakuna-of-rice-and-ruin)
  * [Ecstatica](#ecstatica)
  * [Eden Games (Test Drive Unlimited 2)](#eden-games-test-drive-unlimited-2)
  * [Edge of Reality](#edge-of-reality)
  * [EgoSoft (X4)](#egosoft-x4)
  * [Eighting (Naruto: Gekitō Ninja Taisen!)](#eighting-naruto-gekitō-ninja-taisen)
  * [Electronic Arts](#electronic-arts)
    * [Frostbite](#frostbite)
      * [Battlefield Series](#battlefield-series)
      * [Star Wars: Battlefront](#star-wars-battlefront)
    * [RenderWare](#renderware-1)
      * [Criterion Games](#criterion-games)
    * [EAGL / Black Box / Other](#eagl--black-box--other)
      * [Harry Potter Series](#harry-potter-series)
      * [Need for Speed Series](#need-for-speed-series)
      * [688 Attack Sub](#688-attack-sub)
    * [SAGE / W3D](#sage--w3d)
      * [Command & Conquer Series](#command--conquer-series)
    * [SSX](#ssx)
    * [Fountain of Dreams](#fountain-of-dreams)
    * [Medal of Honor](#medal-of-honor)
    * [Seven Cities of Gold](#seven-cities-of-gold)
    * [General Tools](#general-tools)
    * [Starflight](#starflight)
    * [Star Wars Jedi: Fallen Order](#star-wars-jedi-fallen-order)
  * [Elemental Games (Space Rangers)](#elemental-games-space-rangers)
  * [Ember Lab (Kena: Bridge of Spirits)](#ember-lab-kena-bridge-of-spirits)
  * [Enhance Games (Rez)](#enhance-games-rez)
  * [Epic Games](#epic-games)
    * [ZZT](#zzt)
    * [Ken's Labyrinth](#kens-labyrinth)
    * [Jazz Jackrabbit](#jazz-jackrabbit)
    * [Radix: Beyond the Void](#radix-beyond-the-void)
    * [Tyrian](#tyrian)
    * [Jazz Jackrabbit 2](#jazz-jackrabbit-2)
    * [Fortnite](#fortnite)
    * [Unreal](#unreal)
    * [Unreal Tournament](#unreal-tournament)
  * [Epoch Co. (Lupin Sansei - Pandora no Isan)](#epoch-co-lupin-sansei---pandora-no-isan)
  * [Experience Inc. (Ray Gigant)](#experience-inc-ray-gigant)
  * [Eurocom](#eurocom)
  * [Eutechnyx (Ford Racing)](#eutechnyx-ford-racing)
  * [Evil Dog Games (Punk-O-Matic 2)](#evil-dog-games-punk-o-matic-2)
  * [Factor 5](#factor-5)
    * [Turrican](#turrican)
  * [Failbetter Games](#failbetter-games)
    * [Sunless Skies](#sunless-skies)
  * [FAKT Software (Crazy Machines)](#fakt-software-crazy-machines)
  * [Falcom (Ys)](#falcom-ys)
  * [Fallen Princess Knight](#fallen-princess-knight)
  * [FarSight Studios (The Pinball Arcade)](#farsight-studios-the-pinball-arcade)
  * [fg-games](#fg-games)
    * [Phantom of the Kill](#phantom-of-the-kill)
    * [The Alchemist Code](#the-alchemist-code)
    * [Aster Tatariqus](#aster-tatariqus)
  * [Fireglow Games](#fireglow-games)
    * [Sudden Strike](#sudden-strike)
    * [Sudden Strike: Resource War](#sudden-strike-resource-war)
    * [Sudden Strike II](#sudden-strike-ii)
    * [Tools](#tools)
  * [Firefly Studios](#firefly-studios)
    * [Stronghold](#stronghold)
  * [Fatshark](#fatshark)
    * [Warhammer: End Times - Vermintide](#warhammer-end-times---vermintide)
  * [Fire Chief](#fire-chief)
  * [Firestarter (Hover Ace)](#firestarter-hover-ace)
  * [First Star Software](#first-star-software)
    * [Spy vs Spy II](#spy-vs-spy-ii)
    * [Spy vs Spy III](#spy-vs-spy-iii)
  * [Fred Haslam (Dragon Court)](#fred-haslam-dragon-court)
  * [Fishlabs (Galaxy on Fire)](#fishlabs-galaxy-on-fire)
  * [Flying Shine (Cross†Channel)](#flying-shine-crosschannel)
  * [Free Radical Design (TimeSplitters)](#free-radical-design-timesplitters)
  * [Frictional Games (Amnesia, Soma)](#frictional-games-amnesia-soma)
  * [FromSoftware](#fromsoftware)
    * [Documentation & Wikis](#documentation--wikis)
    * [Format Libraries & Templates](#format-libraries--templates)
    * [Archives, Unpackers & Encryption](#archives-unpackers--encryption)
    * [Models, Animation & FLVER](#models-animation--flver)
    * [Maps & Level Editors](#maps--level-editors)
    * [Scripting, FX, Params & Runtime Modding](#scripting-fx-params--runtime-modding)
    * [Armored Core](#armored-core)
  * [Frontier Developments (Dog's Life)](#frontier-developments-dogs-life)
    * [Thrillville](#thrillville)
  * [Full Fat (Beyblade V-Force)](#full-fat-beyblade-v-force)
  * [Funatics Software](#funatics-software)
  * [Funcom](#funcom)
    * [Dreamfall: The Longest Journey](#dreamfall-the-longest-journey)
    * [Secret World Legends](#secret-world-legends)
  * [Future Games (The Black Mirror)](#future-games-the-black-mirror)
  * [Gamania Digital Entertainment (Bright Shadow)](#gamania-digital-entertainment-bright-shadow)
  * [Game Arts (Thexder)](#game-arts-thexder)
  * [Game Freak](#game-freak)
    * [Gen I & II](#gen-i--ii)
    * [Gen III](#gen-iii)
    * [Gen VI](#gen-vi)
    * [Gen V](#gen-v)
    * [Switch (Gen VIII+)](#switch-gen-viii)
    * [Pokémon Ranger](#pokémon-ranger)
    * [Pokémon Mini](#pokémon-mini)
  * [Gameloft](#gameloft)
  * [GarageGames](#garagegames)
    * [Marble Blast](#marble-blast)
  * [Gas Powered Games (Supreme Commander)](#gas-powered-games-supreme-commander)
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
  * [God Summoner](#god-summoner)
  * [Golden Era Games (Grimoire: Heralds of the Winged Exemplar)](#golden-era-games-grimoire-heralds-of-the-winged-exemplar)
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
    * [Zool](#zool)
    * [Whiplash / Fatal Racing](#whiplash--fatal-racing)
  * [G.rev](#grev)
    * [SteamBot Chronicles](#steambot-chronicles)
  * [Grezzo](#grezzo)
  * [Grinding Gear Games (Path of Exile)](#grinding-gear-games-path-of-exile)
  * [GSC Game World](#gsc-game-world)
    * [S.T.A.L.K.E.R](#stalker)
  * [Guard Crush Games / Lizardcube (Streets of Rage 4)](#guard-crush-games--lizardcube-streets-of-rage-4)
  * [Gumi (Brave Frontier)](#gumi-brave-frontier)
  * [Gust (Koei Tecmo)](#gust-koei-tecmo)
  * [H2O Entertainment (Aidyn Chronicles)](#h2o-entertainment-aidyn-chronicles)
  * [Haggard Games](#haggard-games)
  * [HAL Laboratory](#hal-laboratory)
    * [Kirby](#kirby)
    * [Super Smash Bros.](#super-smash-bros)
    * [BoxBoy!](#boxboy)
  * [Harmonix](#harmonix)
  * [07th Expansion (Higurashi)](#07th-expansion-higurashi)
  * [Hasbro Interactive (Frogger)](#hasbro-interactive-frogger)
  * [Haydee](#haydee)
  * [Heavy Gear](#heavy-gear)
  * [Heavy Iron Studios](#heavy-iron-studios)
  * [Headfirst Productions](#headfirst-productions)
    * [Call of Cthulhu: Dark Corners of the Earth](#call-of-cthulhu-dark-corners-of-the-earth)
  * [Hello Games (No Man's Sky)](#hello-games-no-mans-sky)
  * [Hempuli (Baba Is You)](#hempuli-baba-is-you)
  * [Her Interactive (Nancy Drew)](#her-interactive-nancy-drew)
  * [HeroForge (HeroForge)](#heroforge-heroforge)
  * [High Voltage Software](#high-voltage-software)
    * [The Grim Adventures of Billy & Mandy](#the-grim-adventures-of-billy--mandy)
  * [HoYoverse](#hoyoverse)
    * [Genshin Impact](#genshin-impact)
    * [Honkai Impact 3rd](#honkai-impact-3rd)
    * [Honkai: Star Rail](#honkai-star-rail)
    * [Zenless Zone Zero](#zenless-zone-zero)
  * [HROT](#hrot)
  * [Honey Parade / Marvelous Entertainment](#honey-parade--marvelous-entertainment)
  * [Hudson Soft](#hudson-soft)
    * [Faxanadu](#faxanadu)
  * [Hulabee Entertainment](#hulabee-entertainment)
  * [Hummer Team](#hummer-team)
    * [Super Mario World (Unlicensed Famicom Port)](#super-mario-world-unlicensed-famicom-port)
  * [Hydravision Entertainment](#hydravision-entertainment)
    * [ObsCure](#obscure)
  * [Human Entertainment (Tadaima Yuusha Boshuuchuu Okawari)](#human-entertainment-tadaima-yuusha-boshuuchuu-okawari)
  * [Human Head Studios](#human-head-studios)
    * [Prey](#prey)
  * [HuneX (Arcana Famiglia)](#hunex-arcana-famiglia)
  * [Hypergryph](#hypergryph)
    * [Arknights](#arknights)
    * [Arknights: Endfield](#arknights-endfield)
  * [Hypixel Studios (Hytale)](#hypixel-studios-hytale)
  * [id Software](#id-software)
    * [Commander Keen](#commander-keen)
    * [Catacomb 3-D & Adventure Series](#catacomb-3-d--adventure-series)
    * [Wolfenstein 3D & Spear of Destiny](#wolfenstein-3d--spear-of-destiny)
    * [Doom Engine (id Tech 1) & Ports](#doom-engine-id-tech-1--ports)
      * [Source Ports & Engine Forks](#source-ports--engine-forks)
      * [Console, Handheld, DOS & Novelty Ports](#console-handheld-dos--novelty-ports)
      * [Level Editors & Map Tools](#level-editors--map-tools)
      * [Node Builders (BSP Tools)](#node-builders-bsp-tools)
      * [WAD/Format Libraries, Parsers & Converters](#wadformat-libraries-parsers--converters)
      * [Modding, Scripting & Content Tools](#modding-scripting--content-tools)
      * [Level Generators, Utilities & Documentation](#level-generators-utilities--documentation)
      * [Doom 64 & Hexen 64 Tools](#doom-64--hexen-64-tools)
      * [Decompilations, Source Releases & Historical Archives](#decompilations-source-releases--historical-archives)
    * [Quake & Wolfenstein Engines (id Tech 2/3)](#quake--wolfenstein-engines-id-tech-23)
      * [Official Source Releases & Historical Archives](#official-source-releases--historical-archives)
      * [Source Ports & Engine Forks](#source-ports--engine-forks-1)
      * [Level Editors, Map Compilers & BSP Tools](#level-editors-map-compilers--bsp-tools)
      * [Blender/DCC Plugins & Model/Map Importers](#blenderdcc-plugins--modelmap-importers)
      * [Format Converters, Viewers & QuakeC Tools](#format-converters-viewers--quakec-tools)
    * [Modern DOOM (id Tech 4 / 6 / 7)](#modern-doom-id-tech-4--6--7)
      * [DOOM 3 & id Tech 4 Source Ports, Editors & Tools](#doom-3--id-tech-4-source-ports-editors--tools)
      * [id Tech 4 Documentation & Community Resources](#id-tech-4-documentation--community-resources)
      * [DOOM (2016), Eternal & id Tech 6/7 Tools](#doom-2016-eternal--id-tech-67-tools)
    * [Legacy Tools & Downloads (ModDB)](#legacy-tools--downloads-moddb-2)
    * [Rise of the Triad](#rise-of-the-triad)
  * [Xatrix Entertainment (Kingpin)](#xatrix-entertainment-kingpin)
  * [Ice-Pick Lodge](#ice-pick-lodge)
  * [Idea Factory](#idea-factory)
    * [Date A Live](#date-a-live)
    * [Hidamari Sketch: Dokodemo Sugoroku x 365](#hidamari-sketch-dokodemo-sugoroku-x-365)
  * [Illusion](#illusion)
  * [Impressions Games](#impressions-games)
    * [Caesar III](#caesar-iii)
    * [Pharaoh](#pharaoh)
  * [Incredible Technologies](#incredible-technologies)
  * [iNiS](#inis)
  * [Incentive Software (Freescape)](#incentive-software-freescape)
  * [Infinite Fall (Night in the Woods)](#infinite-fall-night-in-the-woods)
  * [Infinity Ltd. (The Battle of Olympus)](#infinity-ltd-the-battle-of-olympus)
  * [Infogrames Lyon House (Sheep, Dog 'n' Wolf)](#infogrames-lyon-house-sheep-dog-n-wolf)
  * [Inkle](#inkle)
  * [Inland Productions](#inland-productions)
    * [WCW Nitro](#wcw-nitro)
    * [WCW/nWo Thunder](#wcwnwo-thunder)
  * [Innerloop Studios](#innerloop-studios)
  * [Innocent Grey](#innocent-grey)
  * [Intelligent Systems](#intelligent-systems)
    * [Panel de Pon](#panel-de-pon)
    * [Fire Emblem: Three Houses](#fire-emblem-three-houses)
    * [Paper Mario 64](#paper-mario-64)
    * [Paper Mario: TTYD / Super Paper Mario](#paper-mario-ttyd--super-paper-mario)
    * [Paper Mario: The Origami King](#paper-mario-the-origami-king)
  * [Interaction Studios](#interaction-studios)
  * [Interactive Studios](#interactive-studios)
    * [Glover](#glover)
  * [Interplay / Black Isle Studios](#interplay--black-isle-studios)
    * [Fallout](#fallout-1)
    * [Fallout 2](#fallout-2)
    * [Dragon Wars](#dragon-wars)
    * [Icewind Dale II](#icewind-dale-ii)
    * [Atomic Bomberman](#atomic-bomberman)
  * [Invert Studio (1nsane)](#invert-studio-1nsane)
  * [IO Interactive](#io-interactive)
    * [007 First Light](#007-first-light)
  * [Ion Storm](#ion-storm)
    * [Anachronox](#anachronox)
    * [Daikatana](#daikatana)
  * [ITE Media (Hugo)](#ite-media-hugo)
  * [Ironclad Games / Stardock](#ironclad-games--stardock)
    * [Sins of a Solar Empire](#sins-of-a-solar-empire)
  * [Iron Gate AB](#iron-gate-ab)
  * [Iron Lore Entertainment](#iron-lore-entertainment)
    * [Titan Quest](#titan-quest)
  * [Ivory Tower (The Crew)](#ivory-tower-the-crew)
  * [Jagex](#jagex)
    * [RuneScape Classic](#runescape-classic)
  * [Jellyvision](#jellyvision)
  * [JiangHu Studio (Wushu Chronicles 2)](#jianghu-studio-wushu-chronicles-2)
  * [Johan Kotlinski (LSDj)](#johan-kotlinski-lsdj)
  * [Jordan Mechner (Prince of Persia)](#jordan-mechner-prince-of-persia)
  * [JoWooD Vienna (Neighbours from Hell)](#jowood-vienna-neighbours-from-hell)
  * [Joymax (Silkroad Online)](#joymax-silkroad-online)
  * [Juice Games (Juiced)](#juice-games-juiced)
  * [Julegame](#julegame)
    * [League of Angels](#league-of-angels)
  * [Jupiter](#jupiter)
  * [Keen Games (Enshrouded, Portal Knights)](#keen-games-enshrouded-portal-knights)
  * [Keen Software House](#keen-software-house)
  * [KeroQ](#keroq)
  * [KID](#kid)
  * [King of Route 66](#king-of-route-66)
  * [KingsIsle Entertainment (Wizard101)](#kingsisle-entertainment-wizard101)
  * [Klei Entertainment (Oxygen Not Included)](#klei-entertainment-oxygen-not-included)
  * [Koei Tecmo](#koei-tecmo)
    * [Fatal Frame](#fatal-frame)
    * [Nioh](#nioh)
  * [Konami](#konami)
    * [BEMANI](#bemani)
    * [Yu-Gi-Oh](#yu-gi-oh)
    * [Boktai](#boktai)
    * [Metal Gear Solid](#metal-gear-solid)
      * [Archive & Data Extraction Tools](#archive--data-extraction-tools)
      * [Models, Textures, Animation & Stage Tools](#models-textures-animation--stage-tools)
      * [Save, Audio & Video Tools](#save-audio--video-tools)
      * [Scripting & Bytecode Tools](#scripting--bytecode-tools)
      * [Documentation, Decompilation & Disassembly](#documentation-decompilation--disassembly)
    * [Silent Hill](#silent-hill)
    * [Castlevania](#castlevania)
    * [Elebits](#elebits)
    * [Enthusia Professional Racing](#enthusia-professional-racing)
    * [Love Plus](#love-plus)
    * [Zone of the Enders](#zone-of-the-enders)
    * [Yu-Gi-Oh! GX: Duel Academy](#yu-gi-oh-gx-duel-academy)
    * [Yu-Gi-Oh! Tag Force](#yu-gi-oh-tag-force)
    * [Pop'n Music](#popn-music)
    * [Green Beret](#green-beret)
  * [Kuju London](#kuju-london)
  * [Kuro Games](#kuro-games)
    * [Wuthering Waves](#wuthering-waves)
  * [Lab Zero Games](#lab-zero-games)
    * [Indivisible](#indivisible)
  * [Larian Studios](#larian-studios)
    * [Divinity: Original Sin 2](#divinity-original-sin-2)
    * [Divine Divinity / Beyond Divinity](#divine-divinity--beyond-divinity)
  * [Leaf (White Album 2)](#leaf-white-album-2)
  * [LEGO Media (Junkbot)](#lego-media-junkbot)
  * [LEGOLAND (Krisalis Software)](#legoland-krisalis-software)
  * [LEGO Racers](#lego-racers)
  * [LEGO Universe](#lego-universe)
  * [Level-5](#level-5)
    * [Mobile Suit Gundam AGE](#mobile-suit-gundam-age)
    * [Dark Cloud](#dark-cloud)
    * [Inazuma Eleven](#inazuma-eleven)
    * [Yo-Kai Watch](#yo-kai-watch)
    * [Professor Layton](#professor-layton)
  * [Lionhead Studios (Black & White)](#lionhead-studios-black--white)
  * [Lobotomy Software (PowerSlave / Duke Nukem 3D Saturn)](#lobotomy-software-powerslave--duke-nukem-3d-saturn)
  * [Lucky Chicken Games (Casper: Spirit Dimensions)](#lucky-chicken-games-casper-spirit-dimensions)
  * [Looking Glass Studios](#looking-glass-studios)
    * [System Shock](#system-shock)
    * [System Shock 2](#system-shock-2)
    * [Thief](#thief)
    * [Ultima Underworld](#ultima-underworld)
  * [Looney Tunes: Carrot Crazy](#looney-tunes-carrot-crazy)
  * [Lost Saga](#lost-saga)
  * [Lowiro](#lowiro)
    * [Arcaea](#arcaea)
  * [LucasArts](#lucasarts)
  * [Macrospace](#macrospace)
    * [Fatal Force: Earth Assault](#fatal-force-earth-assault)
  * [MAGES.](#mages)
  * [Magic Bytes Software / TD Corp (Dizzy BK-0011M Port)](#magic-bytes-software--td-corp-dizzy-bk-0011m-port)
  * [Marigul (Tamagotchi Town)](#marigul-tamagotchi-town)
  * [Marvelous (Story of Seasons)](#marvelous-story-of-seasons)
  * [Marvelous (Shinobi Master Senran Kagura: New Link)](#marvelous-shinobi-master-senran-kagura-new-link)
  * [Massive Development](#massive-development)
    * [Archimedean Dynasty](#archimedean-dynasty)
  * [Massive Entertainment](#massive-entertainment)
    * [AquaNox](#aquanox)
    * [World in Conflict](#world-in-conflict)
  * [Mastertronic](#mastertronic)
  * [Matheus Valadares (diep.io)](#matheus-valadares-diepio)
  * [Mattel Electronics (Intellivision)](#mattel-electronics-intellivision)
  * [Maxis](#maxis)
    * [3D Pinball for Windows](#3d-pinball-for-windows)
    * [SimCity](#simcity)
    * [SimCity 2000](#simcity-2000)
    * [SimCity BuildIt](#simcity-buildit)
    * [The Sims 1](#the-sims-1)
    * [The Sims 2](#the-sims-2)
    * [The Sims 4](#the-sims-4)
    * [Spore](#spore)
  * [MDF (Polanie)](#mdf-polanie)
  * [Mega Crit (Slay the Spire)](#mega-crit-slay-the-spire)
  * [Media.Vision](#mediavision)
  * [Mercedes-Benz Truck Racing](#mercedes-benz-truck-racing)
  * [Archetype Interactive (Meridian 59)](#archetype-interactive-meridian-59)
  * [Metropolis Software](#metropolis-software)
    * [Gorky 17](#gorky-17)
  * [Microids](#microids)
    * [Still Life 2](#still-life-2)
    * [Syberia](#syberia)
  * [MicroProse](#microprose)
    * [X-COM (UFO Defense / Terror from the Deep)](#x-com-ufo-defense--terror-from-the-deep)
    * [XCOM Apocalypse](#xcom-apocalypse)
    * [F-15 Strike Eagle II](#f-15-strike-eagle-ii)
    * [Sid Meier's Covert Action](#sid-meiers-covert-action)
    * [Darklands](#darklands)
    * [MPS Show](#mps-show)
    * [Master of Magic](#master-of-magic)
    * [RollerCoaster Tycoon](#rollercoaster-tycoon)
  * [Microsoft Studios / Bungie / Turn 10](#microsoft-studios--bungie--turn-10)
    * [SkiFree](#skifree)
    * [Hover!](#hover)
    * [Halo](#halo)
      * [Engine, Tag Formats & Documentation](#engine-tag-formats--documentation)
      * [Asset Extraction & Viewing Tools](#asset-extraction--viewing-tools)
      * [Map Editing, Modding & DCC Tools](#map-editing-modding--dcc-tools)
    * [Destiny](#destiny)
    * [Marathon (1994)](#marathon-1994)
    * [Myth](#myth)
    * [Phantom Dust](#phantom-dust)
    * [Gears of War](#gears-of-war)
    * [Forza](#forza)
    * [Age of Empires](#age-of-empires)
    * [Microsoft Plus! for Windows XP](#microsoft-plus-for-windows-xp)
    * [3D Movie Maker](#3d-movie-maker)
    * [Minesweeper](#minesweeper)
  * [Midway](#midway)
    * [Area 51](#area-51)
    * [Gauntlet](#gauntlet)
    * [Mortal Kombat](#mortal-kombat)
    * [NARC](#narc)
    * [NBA Hangtime](#nba-hangtime)
    * [NBA Jam](#nba-jam)
    * [NFL Blitz](#nfl-blitz)
    * [San Francisco Rush: The Rock](#san-francisco-rush-the-rock)
  * [Mike Singleton (Lords of Midnight)](#mike-singleton-lords-of-midnight)
  * [Mindscape](#mindscape)
  * [Mind Shear Software (In Pursuit of Greed)](#mind-shear-software-in-pursuit-of-greed)
  * [MindStorm Software](#mindstorm-software)
  * [MIST Games (Stella Maiden: Girls of the Stars)](#mist-games-stella-maiden-girls-of-the-stars)
  * [MiST Land / GFI](#mist-land--gfi)
  * [Mithis Entertainment](#mithis-entertainment)
    * [Nexus: The Jupiter Incident](#nexus-the-jupiter-incident)
  * [Mizukagami (Tousui Kitan)](#mizukagami-tousui-kitan)
  * [Mobius Digital (Outer Wilds)](#mobius-digital-outer-wilds)
  * [Mojang Studios](#mojang-studios)
    * [Minecraft Dungeons](#minecraft-dungeons)
    * [Minecraft Legends](#minecraft-legends)
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
  * [MOSS (Caladrius Blaze)](#moss-caladrius-blaze)
  * [Mouldy Toof Studios (The Escapists)](#mouldy-toof-studios-the-escapists)
  * [Mucky Foot Productions](#mucky-foot-productions)
  * [Nadeo](#nadeo)
  * [NanaOn-Sha](#nanaon-sha)
  * [MumboJumbo](#mumbojumbo)
  * [Mythic Entertainment (Dark Age of Camelot)](#mythic-entertainment-dark-age-of-camelot)
  * [Natsume (Harvest Moon)](#natsume-harvest-moon)
    * [Telefang](#telefang)
  * [NCSoft](#ncsoft)
    * [Aion](#aion)
    * [Blade & Soul](#blade--soul)
  * [Neople (Dungeon Fighter Online)](#neople-dungeon-fighter-online)
  * [NetDevil (Dungeon Runners)](#netdevil-dungeon-runners)
  * [NetEase Games](#netease-games)
    * [Beyond the World](#beyond-the-world)
    * [LifeAfter](#lifeafter)
    * [NeoX Engine](#neox-engine)
    * [Messiah Engine](#messiah-engine)
    * [Super Mecha Champions](#super-mecha-champions)
  * [Neverland (Rune Factory Frontier)](#neverland-rune-factory-frontier)
  * [Nexon](#nexon)
    * [MapleStory](#maplestory)
    * [MapleStory 2](#maplestory-2)
    * [Dave the Diver](#dave-the-diver)
    * [Mabinogi](#mabinogi)
    * [Blue Archive](#blue-archive)
  * [Nival](#nival)
  * [Nicalis / Team Meat (The Binding of Isaac)](#nicalis--team-meat-the-binding-of-isaac)
  * [Nihilistic Software](#nihilistic-software)
  * [Nikita](#nikita)
  * [Ninja Kiwi (Bloons TD)](#ninja-kiwi-bloons-td)
  * [MercurySteam](#mercurysteam)
    * [Metroid Dread](#metroid-dread)
  * [Noble Empire Corp](#noble-empire-corp)
    * [World of Guns: Gun Disassembly](#world-of-guns-gun-disassembly)
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
      * [Classic & Portable Mario Recompilations](#classic--portable-mario-recompilations)
      * [Other Nintendo NES/Game Boy Recompilations](#other-nintendo-nesgame-boy-recompilations)
    * [New Super Mario Bros Wii](#new-super-mario-bros-wii)
    * [Zelda](#zelda)
      * [Ocarina of Time & Majora's Mask](#ocarina-of-time--majoras-mask)
      * [Zelda 64 Generic Tools & Decomp Infrastructure](#zelda-64-generic-tools--decomp-infrastructure)
      * [Wind Waker & Twilight Princess](#wind-waker--twilight-princess)
      * [Skyward Sword, Breath of the Wild & Tears of the Kingdom](#skyward-sword-breath-of-the-wild--tears-of-the-kingdom)
      * [Classic & Handheld Zelda](#classic--handheld-zelda)
    * [Wii Sports](#wii-sports)
    * [Star Fox (SNES)](#star-fox-snes)
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
    * [Metroid (Classic)](#metroid-classic)
    * [Metroid Prime](#metroid-prime)
    * [Donkey Kong Country Returns](#donkey-kong-country-returns)
    * [Pokemon](#pokemon)
    * [Punch-Out!!](#punch-out)
    * [1080° Snowboarding](#1080-snowboarding)
  * [NPC Studio (Fields of Mistria)](#npc-studio-fields-of-mistria)
  * [Nippon Ichi Software](#nippon-ichi-software)
    * [Disgaea](#disgaea)
    * [Yomawari](#yomawari)
    * [Process of Elimination](#process-of-elimination)
  * [Nitroplus](#nitroplus)
    * [Chaos;Head](#chaoshead)
  * [Ntreev Soft](#ntreev-soft)
  * [O2Jam](#o2jam)
  * [Obsidian Entertainment](#obsidian-entertainment)
    * [Neverwinter Nights 2](#neverwinter-nights-2)
  * [Ocean Software (Chase H.Q.)](#ocean-software-chase-hq)
  * [Ocean Software](#ocean-software)
    * [Head Over Heels](#head-over-heels)
    * [Cobra](#cobra)
  * [Oddworld Inhabitants](#oddworld-inhabitants)
  * [Omega Star (ωstar)](#omega-star-ωstar)
    * [Bishoujo Mangekyou series](#bishoujo-mangekyou-series)
  * [OMOCAT (OMORI)](#omocat-omori)
  * [Orange\_Juice (100% Orange Juice)](#orange_juice-100-orange-juice)
  * [Origin Systems](#origin-systems)
    * [Ultima IV](#ultima-iv)
    * [Ultima V](#ultima-v)
    * [Ultima VI](#ultima-vi)
    * [Ultima VII](#ultima-vii)
    * [Ultima IX: Ascension](#ultima-ix-ascension)
    * [Strike Commander](#strike-commander)
    * [Wing Commander](#wing-commander)
  * [Orion Games](#orion-games)
  * [Outrage Entertainment](#outrage-entertainment)
    * [Descent 3](#descent-3)
  * [Owlcat Games](#owlcat-games)
  * [Pajamas Soft (Prism Ark)](#pajamas-soft-prism-ark)
  * [Pan Studio (Duet Night Abyss)](#pan-studio-duet-night-abyss)
  * [Pangea Software (Bugdom)](#pangea-software-bugdom)
  * [Panic (Playdate)](#panic-playdate)
  * [Panik Arcade (CloverPit)](#panik-arcade-cloverpit)
  * [Paradigm Entertainment](#paradigm-entertainment)
  * [Paradox Interactive](#paradox-interactive)
  * [Parallax Software (Descent)](#parallax-software-descent)
  * [Parasite In City](#parasite-in-city)
  * [Pearl Abyss (Crimson Desert)](#pearl-abyss-crimson-desert)
  * [People Can Fly](#people-can-fly)
    * [Painkiller](#painkiller)
    * [Dreamkiller](#dreamkiller)
  * [Perfect World International](#perfect-world-international)
  * [Petroglyph Games](#petroglyph-games)
  * [Phenomic](#phenomic)
    * [SpellForce](#spellforce)
    * [BattleForge](#battleforge)
  * [Piranha Bytes](#piranha-bytes)
    * [Gothic 3](#gothic-3)
    * [Elex 2](#elex-2)
  * [Pivotal Games](#pivotal-games)
  * [Pixpil (Eastward)](#pixpil-eastward)
  * [Pixelsoft (Zentia / Xuan Yuan Xin Chuan Qi Online)](#pixelsoft-zentia--xuan-yuan-xin-chuan-qi-online)
  * [PlatinumGames](#platinumgames)
    * [Bayonetta](#bayonetta)
    * [Nier: Automata / Replicant](#nier-automata--replicant)
  * [Pocket Pair (Palworld)](#pocket-pair-palworld)
  * [Pole Chudes 2](#pole-chudes-2)
  * [Polygon Magic (Galerians)](#polygon-magic-galerians)
  * [Polytron (Fez)](#polytron-fez)
  * [PONOS (The Battle Cats)](#ponos-the-battle-cats)
  * [PopCap Games](#popcap-games)
  * [ppy (osu!)](#ppy-osu)
  * [Primal Software](#primal-software)
    * [The I of the Dragon](#the-i-of-the-dragon)
  * [Primula (TAISHO x ALICE)](#primula-taisho-x-alice)
  * [Probe Entertainment (Forsaken)](#probe-entertainment-forsaken)
  * [Procedural Arts](#procedural-arts)
    * [Façade](#façade)
  * [Prototype (console ports of Key visual novels)](#prototype-console-ports-of-key-visual-novels)
  * [Psygnosis](#psygnosis)
    * [WipeOut](#wipeout)
  * [Pterodon (Vietcong)](#pterodon-vietcong)
  * [Punchline](#punchline)
  * [Quantic Dream](#quantic-dream)
  * [Racjin](#racjin)
    * [Busin 0: Wizardry Alternative Neo](#busin-0-wizardry-alternative-neo)
  * [Radica Games (U.B. Funkeys)](#radica-games-ub-funkeys)
  * [Radical Entertainment](#radical-entertainment)
  * [Rare](#rare)
    * [Battletoads](#battletoads)
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
  * [Realmforge Studios (DARK)](#realmforge-studios-dark)
  * [Rebel Act](#rebel-act)
  * [Rebellion Developments](#rebellion-developments)
    * [Judge Dredd: Dredd vs Death](#judge-dredd-dredd-vs-death)
    * [Aliens vs. Predator 2](#aliens-vs-predator-2)
    * [Aliens vs. Predator (2010)](#aliens-vs-predator-2010)
    * [Zombie Army 4](#zombie-army-4)
  * [Red Storm Entertainment](#red-storm-entertainment)
  * [Redmoon Online](#redmoon-online)
  * [Reflections Interactive](#reflections-interactive)
  * [Relic Entertainment](#relic-entertainment)
    * [Homeworld](#homeworld)
    * [Space Marine](#space-marine)
  * [Remedy Entertainment](#remedy-entertainment)
    * [Max Payne](#max-payne)
    * [Alan Wake 2](#alan-wake-2)
  * [RESET](#reset)
  * [Riot Games](#riot-games)
    * [League of Legends](#league-of-legends)
      * [Format Libraries, Hashing & Documentation](#format-libraries-hashing--documentation)
      * [WAD Archive & Property File Tools](#wad-archive--property-file-tools)
      * [Model, Texture, Map & Animation Tools](#model-texture-map--animation-tools)
      * [Mod Managers & Skin Modding Tools](#mod-managers--skin-modding-tools)
    * [Valorant](#valorant)
  * [Ritual Entertainment](#ritual-entertainment)
  * [Rival Interactive](#rival-interactive)
  * [Rival Interactive (Real War)](#rival-interactive-real-war)
  * [Roblox](#roblox)
  * [RobTop Games](#robtop-games)
    * [Geometry Dash](#geometry-dash)
      * [Decompilation & Reverse Engineering](#decompilation--reverse-engineering)
      * [Geode Modding Framework, Bindings & SDK](#geode-modding-framework-bindings--sdk)
      * [Level Format, Editors & Rendering Tools](#level-format-editors--rendering-tools)
      * [Save Data, Encryption & Asset Tools](#save-data-encryption--asset-tools)
      * [Private Servers & Bots](#private-servers--bots)
  * [Robit Studios (Treasure Adventure World)](#robit-studios-treasure-adventure-world)
  * [RockSolid Software (Blast Thru)](#rocksolid-software-blast-thru)
  * [Rockstar Games](#rockstar-games)
  * [Rovio Entertainment](#rovio-entertainment)
    * [Bad Piggies](#bad-piggies)
    * [Angry Birds Fusion](#angry-birds-fusion)
    * [Angry Birds (Classic PC Ports)](#angry-birds-classic-pc-ports)
  * [Runecraft](#runecraft)
  * [Runic Games](#runic-games)
    * [Torchlight](#torchlight)
    * [Torchlight II](#torchlight-ii)
  * [Saber Interactive](#saber-interactive)
  * [Sachi Soft](#sachi-soft)
  * [Sacnoth (Koudelka)](#sacnoth-koudelka)
  * [San Guo Ba Ye (三国霸业)](#san-guo-ba-ye-三国霸业)
  * [SCS Software (Euro Truck Simulator)](#scs-software-euro-truck-simulator)
  * [Sega](#sega)
    * [Homebrew & Audio/Video Format Tools](#homebrew--audiovideo-format-tools)
    * [Model 2 Arcade Games](#model-2-arcade-games)
    * [maimai](#maimai)
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
  * [Serial Experiments Lain](#serial-experiments-lain)
  * [Shift Up (Goddess of Victory: NIKKE)](#shift-up-goddess-of-victory-nikke)
  * [Shiro Games](#shiro-games)
  * [Shiny Entertainment](#shiny-entertainment)
  * [Sierra On-Line](#sierra-on-line)
    * [Quest for Glory V: Dragonfire](#quest-for-glory-v-dragonfire)
    * [Leisure Suit Larry](#leisure-suit-larry)
  * [Sigma Team](#sigma-team)
  * [Silicon Knights](#silicon-knights)
    * [Eternal Darkness: Sanity's Requiem](#eternal-darkness-sanitys-requiem)
  * [Sir-Tech](#sir-tech)
    * [Jagged Alliance 2](#jagged-alliance-2)
  * [Slitherine / Proxy Studios](#slitherine--proxy-studios)
  * [SmokePatch (Football Life Series)](#smokepatch-football-life-series)
  * [Smartly Dressed Games (Unturned)](#smartly-dressed-games-unturned)
  * [Snail Games (Age of Wushu)](#snail-games-age-of-wushu)
  * [SNK](#snk)
    * [Neo Geo Pocket](#neo-geo-pocket)
    * [SNK Heroines](#snk-heroines)
  * [Snowblind Studios](#snowblind-studios)
    * [Baldur's Gate: Dark Alliance](#baldurs-gate-dark-alliance)
  * [SoftClub](#softclub)
    * [Treasure Island (2005)](#treasure-island-2005)
  * [SoftLab-NN](#softlab-nn)
  * [SoftStar Entertainment](#softstar-entertainment)
  * [Software Projects](#software-projects)
    * [Manic Miner](#manic-miner)
    * [Jet Set Willy](#jet-set-willy)
  * [Sony PlayStation Studios](#sony-playstation-studios)
    * [Guerrilla Games (Decima Engine)](#guerrilla-games-decima-engine)
    * [Insomniac Games](#insomniac-games)
      * [Spyro the Dragon](#spyro-the-dragon)
    * [SIE Japan Studio (Ape Escape)](#sie-japan-studio-ape-escape)
    * [Naughty Dog](#naughty-dog)
      * [Crash Bandicoot Series](#crash-bandicoot-series)
      * [Jak and Daxter](#jak-and-daxter)
      * [Uncharted](#uncharted)
      * [The Last of Us](#the-last-of-us)
      * [Engine & Format Tools (Multi-Game)](#engine--format-tools-multi-game)
    * [Polyphony Digital](#polyphony-digital)
    * [Santa Monica Studio](#santa-monica-studio)
    * [Sucker Punch](#sucker-punch)
    * [Other First Party / Japan Studio](#other-first-party--japan-studio)
      * [Team Ico (Ico / Shadow of the Colossus)](#team-ico-ico--shadow-of-the-colossus)
      * [LittleBigPlanet](#littlebigplanet)
    * [Sony Online Entertainment](#sony-online-entertainment)
    * [Evolution Studios](#evolution-studios)
    * [Bend Studio](#bend-studio)
    * [SuperBot Entertainment](#superbot-entertainment)
  * [Sorath (Devil Daggers)](#sorath-devil-daggers)
  * [South East Games (CastleMiner Z)](#south-east-games-castleminer-z)
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
      * [Final Fantasy VII Remake / Rebirth](#final-fantasy-vii-remake--rebirth)
    * [Final Fantasy VIII](#final-fantasy-viii)
    * [Final Fantasy IX](#final-fantasy-ix)
    * [Chrono Trigger](#chrono-trigger)
    * [Chrono Cross](#chrono-cross)
    * [Xenogears](#xenogears)
    * [Xenosaga](#xenosaga)
    * [Vagrant Story](#vagrant-story)
    * [Parasite Eve](#parasite-eve)
    * [Soul Blazer](#soul-blazer)
    * [Sleeping Dogs](#sleeping-dogs)
    * [The World Ends With You](#the-world-ends-with-you)
    * [Babylon's Fall](#babylons-fall)
    * [Hitman](#hitman)
    * [Kingdom Hearts](#kingdom-hearts)
    * [Dragon Quest](#dragon-quest)
    * [Final Fantasy X](#final-fantasy-x)
    * [World of Final Fantasy](#world-of-final-fantasy)
    * [Final Fantasy Tactics](#final-fantasy-tactics)
    * [Musashi: Samurai Legend](#musashi-samurai-legend)
    * [Final Fantasy XIV](#final-fantasy-xiv)
    * [Tactics Ogre: Let Us Cling Together](#tactics-ogre-let-us-cling-together)
    * [Tactics Ogre: The Knight of Lodis](#tactics-ogre-the-knight-of-lodis)
    * [Valkyrie Anatomia](#valkyrie-anatomia)
    * [Bravely Default](#bravely-default)
    * [Romancing SaGa](#romancing-saga)
    * [Drakengard](#drakengard)
    * [Star Ocean](#star-ocean)
    * [Secret of Evermore](#secret-of-evermore)
    * [Another Mind](#another-mind)
  * [Stainless Games (Carmageddon)](#stainless-games-carmageddon)
  * [Starbreeze Studios](#starbreeze-studios)
    * [Payday 2](#payday-2)
    * [Payday 3](#payday-3)
  * [Stern Pinball](#stern-pinball)
  * [Sting](#sting)
    * [Baroque](#baroque)
  * [Strategic Simulations (SSI)](#strategic-simulations-ssi)
    * [Red Lightning](#red-lightning)
  * [Studio MDHR (Cuphead)](#studio-mdhr-cuphead)
  * [Studio Pixel](#studio-pixel)
    * [Cave Story](#cave-story)
    * [Kero Blaster / Pink Hour / Pink Heaven](#kero-blaster--pink-hour--pink-heaven)
  * [Sudden Attack](#sudden-attack)
  * [Sunborn (Girls' Frontline)](#sunborn-girls-frontline)
    * [Girls' Frontline 2: Exilium](#girls-frontline-2-exilium)
  * [Sunsoft](#sunsoft)
  * [Supercell](#supercell)
  * [Supermassive Games (The Quarry)](#supermassive-games-the-quarry)
  * [SuperTuxKart](#supertuxkart)
  * [Surreal Software](#surreal-software)
  * [SynSophia (PriPara)](#synsophia-pripara)
  * [Taito](#taito)
    * [Densha de Go! Final](#densha-de-go-final)
    * [Groove Coaster](#groove-coaster)
  * [Take-Two Interactive](#take-two-interactive)
    * [Ripper](#ripper)
  * [TaleWorlds Entertainment](#taleworlds-entertainment)
    * [Mount\&Blade](#mountblade)
  * [Tamsoft](#tamsoft)
  * [Tate Interactive (Kao the Kangaroo)](#tate-interactive-kao-the-kangaroo)
  * [Tecmo (Tecmo Super Bowl)](#tecmo-tecmo-super-bowl)
    * [Solomon's Key](#solomons-key)
    * [N.U.D.E.@](#nude)
  * [Team17](#team17)
  * [Team Bondi (L.A. Noire)](#team-bondi-la-noire)
  * [Team Cherry (Hollow Knight: Silksong)](#team-cherry-hollow-knight-silksong)
  * [Team Salvato (Doki Doki Literature Club)](#team-salvato-doki-doki-literature-club)
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
  * [thatgamecompany (Sky)](#thatgamecompany-sky)
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
  * [Tomorrow Corporation](#tomorrow-corporation)
    * [Little Inferno](#little-inferno)
    * [Human Resource Machine](#human-resource-machine)
  * [Topheavy Studios (The Guy Game)](#topheavy-studios-the-guy-game)
  * [Toradora Portable (PSP)](#toradora-portable-psp)
  * [Torus Games](#torus-games)
  * [Touch Foo (Swordigo)](#touch-foo-swordigo)
  * [Tower Game (BK-0011M Reverse Engineering)](#tower-game-bk-0011m-reverse-engineering)
  * [Treasure](#treasure)
    * [Mischief Makers](#mischief-makers)
  * [Trese Brothers (Star Traders: Frontiers)](#trese-brothers-star-traders-frontiers)
  * [Tripwire Interactive (Killing Floor)](#tripwire-interactive-killing-floor)
  * [Troika Games (Vampire: The Masquerade)](#troika-games-vampire-the-masquerade)
    * [Temple of Elemental Evil](#temple-of-elemental-evil)
    * [Arcanum](#arcanum)
  * [TT Games (LEGO Island)](#tt-games-lego-island)
    * [Toy Story 2](#toy-story-2)
    * [Toy Story Racer](#toy-story-racer)
    * [Sonic R](#sonic-r)
  * [Turbine](#turbine)
  * [Type-Moon](#type-moon)
    * [Tsukihime](#tsukihime)
    * [Witch on the Holy Night](#witch-on-the-holy-night)
    * [Fate/stay night (Remastered)](#fatestay-night-remastered)
  * [Ubisoft](#ubisoft)
    * [OpenSpace](#openspace-1)
    * [Anvil / Scimitar](#anvil--scimitar)
    * [LyN Engine](#lyn-engine)
    * [Odin Engine](#odin-engine)
    * [YETI Engine](#yeti-engine)
    * [UbiArt Engine](#ubiart-engine)
    * [Unreal Engine](#unreal-engine-1)
    * [CryEngine / Dunia](#cryengine--dunia)
    * [Snowdrop Engine](#snowdrop-engine)
    * [Jade Engine](#jade-engine)
    * [Other Games / General](#other-games--general)
    * [Anno 1800](#anno-1800)
  * [Ultimate Play the Game (JETPAC)](#ultimate-play-the-game-jetpac)
  * [Unfrozen (Heroes of Might and Magic: Olden Era)](#unfrozen-heroes-of-might-and-magic-olden-era)
  * [Unicorn Games Studio](#unicorn-games-studio)
  * [Unique Development Studios (Futurama)](#unique-development-studios-futurama)
  * [United Software Artists](#united-software-artists)
    * [Amulets & Armor](#amulets--armor)
  * [Vicarious Visions](#vicarious-visions)
    * [Skylanders](#skylanders)
  * [Victor Interactive Software (Boku wa Chiisai)](#victor-interactive-software-boku-wa-chiisai)
  * [Virtys (Mist Legacy)](#virtys-mist-legacy)
  * [Visceral Games (Dead Space, Dante's Inferno)](#visceral-games-dead-space-dantes-inferno)
  * [VTech (V.Smile)](#vtech-vsmile)
  * [Volition](#volition)
  * [Wargaming (World of Warships)](#wargaming-world-of-warships)
  * [WayForward](#wayforward)
    * [DuckTales: Remastered](#ducktales-remastered)
    * [Mighty Switch Force: Hyper Drive Edition](#mighty-switch-force-hyper-drive-edition)
    * [A Boy and His Blob](#a-boy-and-his-blob)
    * [Double Dragon Neon](#double-dragon-neon)
    * [Shantae (GBC, unreleased prototype)](#shantae-gbc-unreleased-prototype)
  * [Webzen (Archlord 2)](#webzen-archlord-2)
  * [강림2:제천대성 (Descent 2: Jecheondaeseong)](#강림2제천대성-descent-2-jecheondaeseong)
  * [Westwood Studios](#westwood-studios)
    * [Blade Runner (1997)](#blade-runner-1997)
    * [Command & Conquer](#command--conquer)
    * [Nox](#nox)
    * [Dune II](#dune-ii)
  * [Whirlpool (Relirium - Iseki to Deai to Bouken to)](#whirlpool-relirium---iseki-to-deai-to-bouken-to)
  * [Whoopee Camp (Tomba!)](#whoopee-camp-tomba)
  * [Williams Electronics](#williams-electronics)
  * [WoGa (Hana Awase)](#woga-hana-awase)
  * [Wolfire Games (Overgrowth)](#wolfire-games-overgrowth)
  * [Wolfpack Studios (Shadowbane)](#wolfpack-studios-shadowbane)
  * [Working Designs (Lunar)](#working-designs-lunar)
  * [Wube Software (Factorio)](#wube-software-factorio)
  * [WWE Raw 2](#wwe-raw-2)
  * [Yacht Club Games](#yacht-club-games)
    * [Shovel Knight](#shovel-knight)
  * [Yeti (Root Double: Before Crime \* After Days)](#yeti-root-double-before-crime--after-days)
  * [Yogho Yogho](#yogho-yogho)
  * [Yostar](#yostar)
    * [Azur Lane](#azur-lane)
    * [Azur Promilia](#azur-promilia)
    * [Revived Witch](#revived-witch)
    * [Stella Sora](#stella-sora)
  * [Youthcat Studio](#youthcat-studio)
    * [Dyson Sphere Program](#dyson-sphere-program)
  * [Zachtronics](#zachtronics)
  * [Z-Axis](#z-axis)
  * [Zyrinx (Scorcher)](#zyrinx-scorcher)
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

* [RetroReversing](https://github.com/RetroReversing/retroReversing) ⭐ 692 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-10 - Curated list of retro game development and reverse-engineering resources, tools, and documentation, published as the RetroReversing.com website/wiki.
* [Galgame-Engine-Collect (galWiki)](https://github.com/2439905184/Galgame-Engine-Collect) ⭐ 659 | 🐛 9 | 📅 2026-06-21 - Extensive community knowledge base cataloging Japanese visual novel/galgame engines, their file formats, and associated extraction/translation tools.
* [arcade-docs](https://codeberg.org/shiz/arcade-docs) - Open documentation repository for arcade system hardware, network protocols, and file formats across many manufacturers. Migrated from the archived [GitHub mirror](https://github.com/shizmob/arcade-docs) ⚠️ Archived.
* [XeNTaXBackup](https://github.com/XeNTaXBackup/XeNTaXBackup.github.io) ⭐ 72 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-01-21 - Public backup of the XeNTaX game file format reverse engineering forum and wiki, preserving community knowledge on game format documentation, QuickBMS scripts, and format research.
* [oldgamescracking.github.io](https://github.com/OldGamesCracking/oldgamescracking.github.io) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-08-29 - Community knowledge base documenting cracking and format-preservation notes for old games.
* [Just Solve the File Format Problem](http://fileformats.archiveteam.org/wiki/Game_data_files) - ArchiveTeam's wiki for file formats.
* [XeNTaX Wiki (defunct)](https://web.archive.org/web/20230822181840/https://wiki.xentax.com/index.php/Game_File_Format_Central) - Massive database of file format specifications.

### Platform & SDK Documentation

* [awesome-gbdev](https://github.com/gbdev/awesome-gbdev) ⭐ 4,496 | 🐛 21 | 📅 2026-07-22 - Curated list of Game Boy development resources, including reverse-engineering tools, hardware/format documentation, disassemblers, and emulators.
* [Awesome PlayStation Vita](https://github.com/MuxaJlbl4/Awesome-PlayStation-Vita) ⭐ 1,807 | 🐛 0 | 🌐 Markdown | 📅 2026-08-03 - Comprehensive PS Vita resource list including reverse engineering tools, file format decompilers (.rco, .rcs), and RE utilities.
* [awesome-gbadev](https://github.com/gbadev-org/awesome-gbadev) ⭐ 1,337 | 🐛 6 | 📅 2026-01-30 - Curated list of Game Boy Advance development resources, including documentation, tools, and libraries relevant to GBA file formats and homebrew.
* [Architecture of consoles](https://github.com/flipacholas/Architecture-of-consoles) ⭐ 1,103 | 🐛 29 | 📅 2026-08-24 - Series of technical articles on console hardware architecture, covering CPU, graphics, and file/memory layout across many platforms.
* [Pan Docs](https://github.com/gbdev/pandocs) ⭐ 781 | 🐛 138 | 🌐 Markdown | 📅 2026-06-09 - The single, most comprehensive technical reference to the Game Boy hardware available to the public, including cartridge header, memory bank controller, and save format documentation.
* [rom-properties](https://github.com/GerbilSoft/rom-properties) ⭐ 656 | 🐛 97 | 🌐 C++ | 📅 2026-09-04 - Shell extension for Windows and Linux that shows information about ROM and disc image files. Supports over 500 game and system file formats across dozens of consoles and handhelds.
  * Features: Metadata viewing (title, publisher, region), icon/boxart extraction, save game management, and explorer integration.
* [awesome-megadrive](https://github.com/And-0/awesome-megadrive) ⭐ 454 | 🐛 3 | 📅 2026-05-05 - Curated list of Sega Mega Drive/Genesis development resources, including hardware documentation, disassemblers, and format tools.
* [gb-ctr](https://github.com/Gekkio/gb-ctr) ⭐ 435 | 🐛 3 | 🌐 Typst | 📅 2026-08-16 - Game Boy: Complete Technical Reference, an in-depth document covering Game Boy console hardware internals.
* [PSVita-RE-tools](https://github.com/TeamFAPS/PSVita-RE-tools) ⭐ 383 | 🐛 14 | 🌐 C | 📅 2023-02-20 - Collection of PlayStation Vita reverse-engineering tools.
* [psx-guide](https://github.com/simias/psx-guide) ⭐ 319 | 🐛 8 | 🌐 TeX | 📅 2023-03-21 - In-depth guide to writing a PlayStation emulator from scratch, covering the CPU/MIPS instruction set and memory interconnect, DMA ordering tables, GPU internals and rendering, and building a debugger with breakpoints/watchpoints.
* [SiliconRE](https://github.com/furrtek/SiliconRE) ⭐ 229 | 🐛 23 | 🌐 Verilog | 📅 2026-09-04 - Traces, schematics, and technical writeups from silicon-level reverse engineering of custom game console/arcade chips.
* [Free60 Wiki Archive](https://github.com/Free60Project/wiki) ⭐ 149 | 🐛 7 | 🌐 Dockerfile | 📅 2026-04-02 - Archived MediaWiki dump of free60.org, the community reference for Xbox 360 hardware, firmware, and file format reverse engineering.
* [awesome-dreamcast](https://github.com/dreamcastdevs/awesome-dreamcast) ⭐ 122 | 🐛 0 | 🌐 C | 📅 2026-05-29 - Curated list of Sega Dreamcast development resources, including tutorials, homebrew tools, engines, and frameworks; see also [dreamcast.wiki](https://dreamcast.wiki/Dreamcast.wiki) linked within for hardware/format documentation.
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

* [Ragnarok Research Lab](https://ragnarokresearchlab.github.io/) - Technical documentation covering Ragnarok Online's file formats, rendering systems, and game mechanics. Active continuation of the archived [RagnarokFileFormats](https://github.com/rdw-archive/RagnarokFileFormats) ⭐ 95 | 🐛 1 | 📅 2023-09-05 manifest.
* [The Cutting Room Floor](https://tcrf.net/Help:Contents/Finding_Content) - Community for discovering and documenting unused and debug game content.
* [Nintendo File Formats](https://nintendo-formats.com/) - Documentation for Wii U and Switch games.
* [Custom Mario Kart Wiiki](https://wiki.tockdom.com/wiki/List_of_File_Formats) - Formats used in Mario Kart Wii and related games.
* [Mario Kart 8 Wiki](https://mk8.tockdom.com/wiki/Main_Page) - Documentation for Mario Kart 8 formats and modding.
* [Luma's Workshop](https://www.lumasworkshop.com/wiki/Category:File_formats) - Nintendo modding wiki.
* [Splatoon Technical Wiki](https://wiki.oatmealdome.me/index.php/Special:AllPages) - Technical documentation for Splatoon game formats.
* [Souls Modding Wiki](https://www.soulsmodding.com/doku.php?id=start) - Documentation for FromSoftware formats.
* [MGSV Modding and Research Wiki](https://mgsvmoddingwiki.github.io/) - Community wiki documenting Metal Gear Solid V: The Phantom Pain's Fox Engine file formats and modding workflows.

### 📚 Learning Resources & Tutorials

* [kovidomi/game-reversing](https://github.com/kovidomi/game-reversing) ⭐ 1,686 | 🐛 4 | 📅 2023-04-05 - Beginner learning materials on reverse engineering video games.
* [vgmdocs](https://github.com/loveemu/vgmdocs) ⭐ 101 | 🐛 2 | 📅 2026-05-01 - Resources and documentation for video game music formats. Includes guides for GBA sound drivers, FM synth presets, conversion tools, and format documentation.
* [Inazuma-Eleven-GO-Modding](https://github.com/SxncYT/Inazuma-Eleven-GO-Modding) ⭐ 1 | 🐛 0 | 🌐 Svelte | 📅 2025-10-02 - Documentation regarding the functions of Inazuma Eleven GO Light/Shadow. Covers game scripting, format specifications, and modding techniques.
* **[DGTEFF](https://web.archive.org/web/20230817151933/http://wiki.xentax.com/index.php/DGTEFF) - Definitive Guide To Exploring File Formats.**
* [The VG Resource Wiki](https://wiki.vg-resource.com/Main_Page) - Wiki with tutorials for ripping and creating sprites, models, textures, and sounds across gaming platforms.
* [Compression Deep Dive](https://chronovore.dev/posts/2023-01-25-1234P-compression-deepdive.html) - Technical analysis of compression algorithms used in games.
* [How to Crack a Binary File Format](https://www.iwriteiam.nl/Ha_HTCABFF.html) - Classic tutorial on reverse engineering file formats.
* [How to Grab Models and Textures](https://aknavj.github.io/3d/2019/06/10/Grabbing-models-and-textures-from-game-or-3D-application.html) - Guide on extracting models and textures from games.
* [ReWolf's Retrogaming Blog](http://blog.rewolf.pl/blog/?cat=23) - Blog posts on retrogaming and reverse engineering.
* [Crazy Taxi Reverse Engineering](https://wretched.computer/post/crazytaxi) - Detailed retrospective series on reverse engineering the GameCube version of Crazy Taxi, covering archive (.all), model (.shp), texture (.tex), and audio (.adp) formats.

#### 🎥 Video Tutorials

* [dsasmblr/game-hacking](https://github.com/dsasmblr/game-hacking) ⭐ 5,569 | 🐛 11 | 📅 2024-06-20 - Large curated collection of tutorials, tools, and resources for reverse engineering video games.
* [retrore](https://github.com/realdmx/retrore) ⭐ 73 | 🐛 0 | 📅 2026-08-30 - Curated list of original and reverse-engineered vintage 6502 game source code, tracking disassembly projects across many classic 8-bit titles.
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

* [assimp](https://github.com/assimp/assimp) ⭐ 13,177 | 🐛 534 | 🌐 C++ | 📅 2026-09-04 - The Open Asset Import Library, loading 40+ 3D model formats into one unified data structure. Widely used as the backend for game-format model converters and viewers. See also [Assimp.Net](https://github.com/StirlingLabs/Assimp.Net) ⭐ 49 | 🐛 4 | 🌐 C# | 📅 2023-10-18 below for a .NET wrapper.
* [vengi](https://github.com/vengi-voxel/vengi) ⭐ 1,407 | 🐛 133 | 🌐 C | 📅 2026-09-03 - Free, open-source, actively maintained voxel editor, thumbnailer, and command-line format converter.
  * Formats: MagicaVoxel VOX/XRAW, Qubicle QB/QBT/QEF/QBCL, Sandbox VoxEdit VXM/VXR/VXC/VXB/VXT, Ace of Spades KV6/VXL, Build engine KVX, Minecraft schematic/mcworld/region/level.dat/skin, CubeWorld, Goxel, BinVox, Tiberian Sun VXL, StarMade, and 30+ more voxel and mesh formats (glTF, FBX, Quake BSP/MDL/MD2/MD3, STL, PLY, and others).
  * Features: standalone GUI editor (VoxEdit), thumbnail generator, and CLI converter (VoxConvert) sharing one format backend.
* [NifSkope](https://github.com/niftools/nifskope) ⭐ 630 | 🐛 125 | 🌐 C++ | 📅 2024-06-03 - Tool for opening and editing the NetImmerse/Gamebryo NIF format used by Morrowind, Oblivion, Skyrim, Fallout 3/NV/4, and more. See also [hexabits' fork](https://github.com/hexabits/nifskope) ⭐ 259 | 🐛 50 | 🌐 C++ | 📅 2024-08-20 with Starfield support.
* [mviewer](https://github.com/majimboo/mviewer) ⭐ 301 | 🐛 0 | 🌐 Rust | 📅 2026-04-03 - Reverse engineering tool for viewing and analyzing MView 3D file format.
* [psx-modding-toolchain](https://github.com/mateusfavarin/psx-modding-toolchain) ⭐ 194 | 🐛 9 | 🌐 C | 📅 2026-02-21 - Toolchain for PlayStation 1 modding including model and texture tools.
* [Noesis-Plugins (leeao)](https://github.com/leeao/Noesis-Plugins) ⭐ 40 | 🐛 1 | 🌐 Python | 📅 2023-08-17 - Collection of Noesis Python scripts for various game models and textures.
  * Games: Evil Dead: Regeneration, Harry Potter and the Chamber of Secrets (PS2), Haunting Ground (PS2), Kingdom Under Fire 2, Pokémon Master, Trapt (PS2), Artifex Mundi games, Mega Man Zero/ZX Legacy Collection (PC), Onimusha 3, Patapon 2 (PSP), The Punisher (Xbox), Eastward, Tales of Symphonia (Xbox 360), Angry Birds Star Wars (Wii), Angry Birds Trilogy (Wii/Wii U), Beat Down: Fists of Vengeance (PS2), BishiBashi Online, Double Dragon II: Wander of the Dragons (Xbox 360), Dream League Soccer, JoJo's Bizarre Adventure, Just Dance (Wii), Keyboard Mania (Arcade), Lost Kingdoms 2 (GameCube), Manhunt (PC), Manhunt 2 (Wii), Monster Hunter Explore (Android), Moshi Monsters Village (iOS), Mortal Kombat Mythologies: Sub-Zero (PSX), Mortal Kombat: Special Forces (PSX), Need for Speed: Hot Pursuit (Wii), Naruto: Uzumaki Chronicles 2, Para Para Paradise, Road Trip Adventure (PS2), Star Wars: Bounty Hunter (GameCube), Twisted Metal: Black (PS2), Vector Unit games (Android), Yu Yu Hakusho Forever (PS2), Tony Hawk's Pro Skater series (PS2).
* [tmd2obj](https://github.com/taedixon/tmd2obj) ⭐ 24 | 🐛 0 | 🌐 Java | 📅 2025-09-25 - Command-line converter from PlayStation 1 TMD models to Wavefront OBJ, extracting material colors and texture mapping.
* [SEAnim-Docs](https://github.com/SE2Dev/SEAnim-Docs) ⭐ 24 | 🐛 1 | 📅 2018-03-19 - Specification and documentation for the SEModel/SEAnim formats used by CastImporter and related tools.
* [Noesis-Py](https://github.com/atrzaska/noesis_py) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2026-09-02 - Cross-platform (Linux/macOS) reimplementation of Noesis able to load plugins written for the original Noesis, aiming for API compatibility so existing Noesis plugins work unmodified.
* [tmd](https://github.com/roblouie/tmd) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2020-06-12 - JavaScript application for viewing PlayStation 1 TMD models in the browser. Features orbit controls, wireframe mode, and texture support.
* [Noesis-help](https://github.com/Sparagas/Noesis-help) ⭐ 10 | 🐛 0 | 🌐 HTML | 📅 2025-11-10 - Community-written help/documentation for Rich Whitehouse's Noesis, filling gaps in the official documentation.
* [CastImporter](https://github.com/o-Astral-o/CastImporter) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2025-03-27 - Unreal Engine plugin for importing SEModel, SEAnim, and Cast files. Commonly used with Call of Duty asset extractors.
* [Nif-Explorer](https://github.com/Dark-Rising-Studios/Nif-Explorer) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2021-01-12 - Python tool (using PyFFI) that recursively scans a directory for .nif files containing specific NetImmerse/Gamebryo Block Types or Block Type Properties, copying matches to a results folder.
* [heightmap-viewer](https://github.com/impiaaa/heightmap-viewer) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2017-05-30 - Simple 3D viewer for loading regular heightmaps and special format heightmap files.
* [Noesis](https://richwhitehouse.com/index.php?content=inc_projects.php\&showproject=91) - Popular all-in-one tool for previewing and converting 500+ model, texture, and animation formats. Supports batch conversion, has a rich plugin ecosystem, and can handle most common game formats out of the box.
  * [Noesis Plugins (Durik256)](https://github.com/Durik256/Noesis-Plugins) ⭐ 69 | 🐛 22 | 🌐 Python | 📅 2026-04-25 - Community collection with 150+ plugins for various games including Final Fantasy series, Dark Souls 2, Dead Rising 4, Ridge Racer, NHL 21, and many others.
  * [Noesis Plugins (Zheneq)](https://github.com/Zheneq/Noesis-Plugins) ⭐ 34 | 🐛 4 | 🌐 Python | 📅 2023-07-09 - Community plugins for Megaman X8 (PC), Fatal Frame 4 (Wii), Star Wars: The Force Unleashed (Wii), Planet 51 (Wii), Silent Hill: Shattered Memories (Wii), Fire Emblem (Wii), MT Framework (3DS).
  * [Noesis Plugins (mrpostiga)](https://github.com/mrpostiga/noesis-plugins-official) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2017-02-15 - Additional community-maintained plugin collection.
  * [noesis\_iqe](https://github.com/viciious/noesis_iqe) ⭐ 12 | 🐛 1 | 🌐 C++ | 📅 2016-11-30 - Noesis plugin for exporting models to Inter-Quake Export (IQE) format.
  * [Noesis Plugins (RoadTrain)](https://github.com/RoadTrain/noesis-plugins) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2017-09-08 - LS3D engine plugin (.4ds format) supporting Mafia: The City of Lost Heaven, Chameleon, Hidden & Dangerous 2, War of Wings.
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
* [RygsDXTc](https://github.com/Cyan4973/RygsDXTc) ⭐ 98 | 🐛 0 | 🌐 C | 📅 2021-11-28 - Real-time DXT1/DXT5 texture compressor in C, based on Fabian "ryg" Giesen's farbrausch demoscene work; used as a fast encoder in many game asset pipelines.
* [AnyPalette.js](https://github.com/1j01/anypalette.js) ⭐ 74 | 🐛 12 | 🌐 JavaScript | 📅 2024-06-11 - JavaScript/Node library reading and writing a wide range of color palette file formats through one unified interface, including game formats such as StarCraft's .pal/.wpe terrain palettes alongside DCC formats (GIMP GPL, Adobe ACO/ASE/ACT, Paint Shop Pro, Paint.NET).
* [tim2view](https://github.com/lab313ru/tim2view) ⭐ 70 | 🐛 6 | 🌐 Pascal | 📅 2016-08-09 - Viewer, converter, searcher, editor, and scanner/ripper for PS2 TIM/TM2 texture formats, complementing Rainbow's TIM2 conversion support.
* [texgenpack](https://github.com/hglm/texgenpack) ⭐ 62 | 🐛 12 | 🌐 C | 📅 2018-02-05 - Compresses, decompresses, and converts texture files using a genetic algorithm. Supports KTX, DDS, ETC2, BC6/BC7, and more.
* [ImageHeat](https://github.com/bartlomiejduda/ImageHeat) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2026-09-02 - Texture viewing tool for encoded textures.
  * Formats: RGBA8888, RGB888, RGB565, DXT1, ASTC, indexed formats (PAL4/8/16).
  * Platforms: PSP, PS2, PS3, PS4, Xbox (unswizzling support).
  * Features: Decompression (RLE, PackBits, ZLIB), export to DDS/PNG/BMP.
* [GTX-Extractor](https://github.com/aboood40091/GTX-Extractor) ⭐ 35 | 🐛 4 | 🌐 Python | 📅 2019-04-11 - Extractor for GTX (GX2 Texture) format in Wii U games with bidirectional conversion.
* [BNTX-Extractor](https://github.com/aboood40091/BNTX-Extractor) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2018-05-03 - Extractor for BNTX (Binary NX Texture) format in Nintendo Switch games.
  * Formats: BC1-BC7, RGBA variants, ASTC variants
* [lfgfx](https://github.com/ethteck/lfgfx) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2022-12-13 - Python tool for reverse-engineering and analyzing N64 graphics data blobs (display lists, vertex data, textures, palettes).
* [DDS.Tools](https://github.com/BoBoBaSs84/DDS.Tools) ⭐ 19 | 🐛 0 | 🌐 C# | 📅 2026-08-31 - Simple DDS and PNG tool set that converts DDS images to PNG images and vice versa on a large scale. Has options for duplicate detection and sorting.
* [TexViewer](https://github.com/Puxtril/TexViewer) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2026-05-21 - Tool to help discover unknown texture formats.
* [detex-compress](https://github.com/hglm/detex-compress) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2015-05-19 - Fast texture compression utility built on the detex library, supporting BC1-5 and ETC1 formats.
* [Motex](https://github.com/jpburnett/motex) ⭐ 5 | 🐛 4 | 🌐 Rust | 📅 2025-12-01 - N64 texture viewer for analyzing and inspecting N64 binary texture data; useful for reverse-engineering game texture formats.
* [awsmimg](https://github.com/kmeisthax/awsmimg) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2018-07-28 - Converter between modern image formats (typically PNG) and those used by retro game hardware.
* [TextureFinder](https://github.com/Gravemind2401/TextureFinder) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2025-07-16 - Binary texture extraction utility supporting multiple game texture formats including DXGI and Xbox formats. Helps identify and extract embedded texture data from game binaries.
* [swizzleinator](https://github.com/v4nguard/swizzleinator) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-09-08 - Library for detiling/deswizzling various image formats. `no_std`-friendly. Supports PS3, PS4, and X360 texture swizzling/unswizzling.
* [BCDec](https://github.com/neptuwunium/bcdec) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-05-19 - All-in-one C++ texture decoding library and tool for BC1-BC7, ETC1/2, and ASTC formats.
* [DXTAnalyzer](https://github.com/LittleBitUA/DXTAnalyzer) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-10-30 - PyQt5 utility for viewing DDS headers and identifying pixel formats (DXT1/3/5, BC4/5/6H/7, RGBA8/BGRA8), with experimental PS3 swizzle/unswizzle (Morton Z-order) support for RGBA8 and BC1/2/3.
* [GtfDdsSharp](https://github.com/Udaya-X2/GtfDdsSharp) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-11-07 - Converts PS3 GTF (Graphics Texture Format) textures to/from DDS, used across many PS3 games.
* [PyNVTT](https://github.com/Hancapo/PyNVTT) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-07-01 - Python wrapper for NVIDIA Texture Tools (NVTT). Enables DDS texture format conversion and compression for game asset extraction and modding.
* [RAW pixels viewer](https://www.kernellabs.com/rawpixels/) - Web-based tool for analyzing raw image data. Displays memory dumps of frame buffers, video buffers, and uncompressed video files. Allows interactive exploration of color formats and image parameters (width, height, offset, flip, invert, zoom) to help identify unknown pixel formats.

#### Sprites, Tiles & Tilemaps

* [Tilemap Studio](https://github.com/Rangi42/tilemap-studio) ⭐ 531 | 🐛 26 | 🌐 C++ | 📅 2026-05-02 - Tilemap editor for Game Boy, GBC, GBA, NDS, SNES, Genesis, and TG16.
  * Support: pret disassemblies, Pokemon ROM hacks
* [tmxlite](https://github.com/fallahn/tmxlite) ⭐ 466 | 🐛 12 | 🌐 C++ | 📅 2026-04-27 - Lightweight C++14 parser for Tiled Map Editor's TMX/TSX tilemap format, used by many indie and hobbyist games.
* [NitroPaint](https://github.com/Garhoogin/NitroPaint) ⭐ 110 | 🐛 6 | 🌐 C | 📅 2026-08-30 - Graphics editor for Nintendo DS image formats.
  * See also [ptexconv](https://github.com/Garhoogin/ptexconv) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2026-09-02 for a command-line-only version of its texture and background converter.
  * Formats: NCLR, NCGR, NSCR
  * Compression: LZ, RLE, Huffman, LZX
* [Tile Molester](https://github.com/toruzz/TileMolester) ⭐ 108 | 🐛 25 | 🌐 Java | 📅 2024-05-04 - Multi-format, user-extensible graphics data editor for viewing and editing tile-based graphics in arbitrary binary files from game consoles.
* [gimp-rom-bin](https://github.com/bbbbbr/gimp-rom-bin) ⭐ 102 | 🐛 2 | 🌐 C | 📅 2026-08-24 - GIMP plug-in to read/write/convert ROM image, tile, and sprite files.
  * Platforms: SNES, NES, Game Boy/GBC, GBA, Neo Geo Pocket, Mega Drive/Genesis, and more.
* [chrgfx](https://github.com/drojaazu/chrgfx) ⭐ 78 | 🐛 1 | 🌐 C++ | 📅 2026-07-07 - Converts to and from tile-based (CHR) graphics formats used across many retro consoles.
* [SNESTilesKitten](https://github.com/Skarsnik/SNESTilesKitten) ⭐ 71 | 🐛 3 | 🌐 C++ | 📅 2025-06-25 - Tile viewer, extractor, and injector for SNES ROM files with HiROM/LoROM support.
* [gimp-tilemap-gb](https://github.com/bbbbbr/gimp-tilemap-gb) ⭐ 71 | 🐛 1 | 🌐 C | 📅 2024-04-16 - Console app and GIMP plug-in for importing/exporting Game Boy game tilemaps and tilesets as bitmap images or .GBM/.GBR files. Related to GBTD, GBMB, GBDK, and ZGB.
* [Nintendo\_DS\_Compressors](https://github.com/PeterLemon/Nintendo_DS_Compressors) ⭐ 41 | 🐛 1 | 🌐 C | 📅 2024-06-12 - Collection of compressors for formats used on Nintendo GBA/DS.
* [BMP2BNR](https://github.com/Cuyler36/BMP2BNR) ⚠️ Archived - Converts BMP images to GameCube banner format (BNR).
* [nds\_texcompress](https://github.com/kusma/nds_texcompress) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2017-02-07 - Texture compression tool for Nintendo DS texture formats.
* [rawtex](https://github.com/hitchhikr/rawtex) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2023-10-18 - GIMP 2.x save plugin for creating raw texture files for PC, PSP, NDS, PS2, and other architectures handling chunky or compressed pixel data. See also [raw2iff](https://github.com/hitchhikr/raw2iff) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-03-03, a plugin-driven tool converting RAW pictures to the Amiga IFF ILBM picture format.
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
* [Guilty\_Hell\_Sprite\_Veiwer](https://github.com/coreynguyen/Guilty_Hell_Sprite_Veiwer) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-01-03 - GPU-accelerated viewer for Unity `Texture2D`/AssetStudio sprite sheets, with Real-ESRGAN AI upscaling.
* [mxs\_xnaLara\_converter](https://github.com/coreynguyen/mxs_xnaLara_converter) ⭐ 0 | 🐛 0 | 🌐 MAXScript | 📅 2026-01-15 - MaxScript for importing XNALara/XPS `.xps`/`.mesh` model files into 3ds Max.
* [Sprite Sheet Addon for Blender](https://www.moddb.com/engines/blender-game-engine/downloads/sprite-sheet-addon-for-blender) - Sprite sheet script for Blender VSE. (video squence editor) Convert image sequences to sprite sheet.
* [Sprite Sheet Addon for Blender VSE](https://www.moddb.com/groups/blender-game-engine/downloads/sprite-sheet-addon-for-blender-vse) - Sprite sheet script for Blender VSE. (video squence editor) Convert image sequences to sprite sheet.

### 📦 Archive Extractors

* [binwalk](https://github.com/ReFirmLabs/binwalk) ⭐ 14,312 | 🐛 93 | 🌐 Rust | 📅 2026-08-11 - Firmware analysis tool for identifying and extracting embedded files and data. The Rust version (v3) provides significant speed and accuracy improvements over the original Python version.
* [AssetRipper](https://github.com/AssetRipper/AssetRipper) ⭐ 8,269 | 🐛 152 | 🌐 C# | 📅 2026-09-03 - GUI tool for extracting assets from Unity serialized files (*CAB-*\\*, *\\*.assets*, etc.) and asset bundles (*\\*.unity3d\*, *\\*.bundle\*, etc.) and converting them into the native Unity engine format.
* [Universal Extractor 2](https://github.com/Bioruebe/UniExtract2) ⭐ 4,413 | 🐛 123 | 🌐 AutoIt | 📅 2024-07-06 - Generic tool to extract files from any type of archive or installer, commonly used to unpack game installers (NSIS, InstallShield, Wise, and many more) before further asset processing.
* [GARbro](https://github.com/morkt/GARbro) ⭐ 3,280 | 🐛 276 | 🌐 C# | 📅 2024-07-08 - Visual novels resource browser and extractor supporting many formats. See also [crskycode's fork](https://github.com/crskycode/GARbro) ⭐ 775 | 🐛 7 | 🌐 C# | 📅 2026-08-28, which is actively maintained with additional format support; [nanami5270's fork](https://github.com/nanami5270/GARbro-Mod) ⭐ 137 | 🐛 3 | 🌐 C# | 📅 2026-09-01, another actively maintained fork with additional format/game support; and [UserUnknownFactor's GARbro2](https://github.com/UserUnknownFactor/GARbro2) ⭐ 60 | 🐛 3 | 🌐 C# | 📅 2026-02-23, which adds ImageMagick-based format support, sprite-sheet animation, and an in-app playback mode.
* [cartreader](https://github.com/sanni/cartreader) ⚠️ Archived - Open Source Cartridge Reader (OSCR) firmware/software for dumping ROMs and save data from game cartridges across dozens of retro systems: NES, SNES, N64, Genesis/Mega Drive, Game Boy/GBA, PC Engine/TurboGrafx-16, WonderSwan, NeoGeo Pocket, Virtual Boy, Pokémon Mini, Game Gear, Intellivision, ColecoVision, Atari 2600/5200/7800/Lynx, MSX, Commodore, Vectrex, and CPS3, among others. Archived by its author in favor of active redevelopment under the [oscartreader](https://github.com/oscartreader) org, though this repo remains the maintainers' own recommended firmware for most users.
* [Greaseweazle](https://github.com/keirf/greaseweazle) ⭐ 1,392 | 🐛 81 | 🌐 Python | 📅 2026-06-16 - Hardware and tools for reading/writing floppy disks at the raw flux level, widely used for archiving copy-protected game floppies.
* [innoextract](https://github.com/dscharrer/innoextract) ⭐ 1,355 | 🐛 72 | 🌐 C++ | 📅 2025-02-06 - Extracts installers created by Inno Setup without running them, commonly used to unpack game installers before further asset processing.
* [extract-xiso](https://github.com/XboxDev/extract-xiso) ⭐ 1,145 | 🐛 41 | 🌐 C | 📅 2025-05-15 - Xbox ISO (XISO) creation, modification, and extraction utility for original Xbox disc images.
* [OmniDrive](https://github.com/RibShark/OmniDrive) ⭐ 1,110 | 🐛 22 | 🌐 Assembly | 📅 2026-07-18 - Firmware modification for MediaTek MT1959-based Hitachi-LG optical disc drives, enabling raw sector and lead-in/lead-out reading of CD/DVD/BD media including proprietary game discs.
* [UWPDumper](https://github.com/Wunkolo/UWPDumper) ⭐ 954 | 🐛 40 | 🌐 C++ | 📅 2024-09-03 - DLL and Injector for dumping UWP applications at run-time to bypass encrypted file system protection.
* [Aaru](https://github.com/aaru-dps/Aaru) ⭐ 620 | 🐛 215 | 🌐 C# | 📅 2026-09-02 - Data Preservation Suite for dumping and analyzing media (optical, magnetic, and solid-state) into forensic disc images, with format identification, checksumming, and decoding across a huge range of game and computer platforms. See also [libaaruformat](https://github.com/aaru-dps/libaaruformat) ⭐ 26 | 🐛 3 | 🌐 C | 📅 2026-09-01, the C implementation of the Aaru image format.
* [maxcso](https://github.com/unknownbrackets/maxcso) ⭐ 514 | 🐛 28 | 🌐 C | 📅 2024-06-30 - Fast CSO compression utility for PSP and PS2 game ISO files used with emulators.
* [redumper](https://github.com/superg/redumper) ⭐ 492 | 🐛 108 | 🌐 C++ | 📅 2026-08-25 - Low-level CD dumper utility for bit-perfect optical disc preservation, used by the Redump.org preservation community.
* [archives](https://github.com/mholt/archives) ⭐ 441 | 🐛 10 | 🌐 Go | 📅 2026-08-05 - Cross-platform archive library for Go supporting many formats. Provides unified API and virtual file systems compatible with `io/fs`.
  * Formats: .zip, .tar (including compressed variants), .rar (read-only), .7z (read-only), brotli, bzip2, gzip, lz4, lzip, minlz, snappy/S2, xz, zlib, zstandard.
  * Features: Stream-oriented APIs, automatic format identification, password-protected 7-Zip/RAR support, insert into .tar/.zip without recreating, multithreaded Gzip, DeepFS for traversing archives transparently.
* [unshield](https://github.com/twogood/unshield) ⭐ 435 | 🐛 38 | 🌐 C | 📅 2026-03-28 - Library and CLI tool to extract InstallShield CAB archives, commonly used to unpack older game installers before further asset processing.
* [GameExtractor](https://github.com/wattostudios/GameExtractor) ⭐ 321 | 🐛 17 | 🌐 Java | 📅 2026-08-01 - Multi-game archive tool supporting 4000+ games.
* [HxCFloppyEmulator](https://github.com/jfdelnero/HxCFloppyEmulator) ⭐ 197 | 🐛 10 | 🌐 C | 📅 2026-08-22 - HxC floppy drive emulator toolkit; reads and converts a wide range of retro floppy disk image formats, including many game-console/computer-specific ones.
* [NDSFactory](https://github.com/Luca1991/NDSFactory) ⭐ 187 | 🐛 0 | 🌐 C++ | 📅 2025-11-28 - Generic Nintendo DS ROM extraction/repacking tool.
* [xvdtool](https://github.com/emoose/xvdtool) ⭐ 176 | 🐛 11 | 🌐 C# | 📅 2026-04-25 - Command-line tool for manipulating Xbox One XVD/XVC package files, with support for decryption, hashing, resignation, and VHD conversion. See also [XvdTool.Streaming](https://github.com/LukeFZ/XvdTool.Streaming) ⭐ 47 | 🐛 1 | 🌐 C# | 📅 2026-07-23, a rewritten/optimized version that also extracts and decrypts XVC/XVD files streamed remotely by URL, not just local files.
* [ExtractData](https://github.com/lioncash/ExtractData) ⭐ 172 | 🐛 0 | 🌐 C | 📅 2025-04-25 - Extraction tool for Japanese visual novel/game archives, using Susie Plugin (.spi) modules to decode proprietary archive and image formats. Originally developed by Yuu.
* [dexvert](https://github.com/Sembiance/dexvert) ⭐ 169 | 🐛 1 | 🌐 Python | 📅 2026-08-29 - Identifies and converts over 3,700 file formats to modern equivalents, including many game-specific archive, texture, and model formats.
* [fluxfox](https://github.com/dbalsom/fluxfox) ⭐ 159 | 🐛 5 | 🌐 Rust | 📅 2026-09-03 - Floppy disk image library in Rust for emulators, focused on PC platform disk images with initial Amiga/Macintosh/Atari ST support.
  * Features: Track bitstream access, copy-protection visualization, common PC floppy disk controller (NEC uPD765A) operation emulation.
* [SabreTools](https://github.com/SabreTools/SabreTools) ⭐ 143 | 🐛 10 | 🌐 C# | 📅 2026-08-31 - DAT-based ROM/disc image management tool with advanced editing and sorting features.
* [EasyExtractUnitypackage](https://github.com/HakuSystems/EasyExtractUnitypackage) ⭐ 123 | 🐛 1 | 🌐 C# | 📅 2026-08-27 - Extracts files from a Unity `.unitypackage` archive without needing to import it into the Unity Editor first.
* [DiskImageTool](https://github.com/Digitoxin1/DiskImageTool) ⭐ 116 | 🐛 7 | 🌐 Visual Basic .NET | 📅 2026-08-30 - Floppy disk image manager with built-in bitstream analysis, Greaseweazle support, and optional Kryoflux integration.
* [RVWorld (RomVault)](https://github.com/RomVault/RVWorld) ⭐ 103 | 🐛 14 | 🌐 C# | 📅 2026-09-05 - DAT-file-driven ROM set organizer/verifier for identifying, sorting, and repairing game ROM and disc image collections.
* [SAMdisk](https://github.com/simonowen/samdisk) ⭐ 98 | 🐛 6 | 🌐 C++ | 📅 2026-05-30 - Portable disk image utility specializing in copy-protected PC-compatible floppy formats, commonly used to preserve original game floppy disks.
* [dreamcast-cdi-burner](https://github.com/alex-free/dreamcast-cdi-burner) ⭐ 88 | 🐛 1 | 🌐 Shell | 📅 2025-01-28 - Open-source, portable Linux tool for burning Sega Dreamcast .CDI disc images to physical media.
* [iPoPS](https://github.com/julianxhokaxhiu/iPoPS) ⭐ 85 | 🐛 3 | 🌐 C | 📅 2025-09-19 - Converts PSX discs and ISOs into PBP format for playback on PSP.
* [RIDE](https://github.com/tomas-nestorovic/RIDE) ⭐ 85 | 🐛 36 | 🌐 C++ | 📅 2026-08-31 - Windows tool for low-level raw floppy disk access and browsing legacy filesystems (ZX Spectrum, MS-DOS, and others) found on preserved game disks.
* [playstation-disc-burner](https://github.com/alex-free/playstation-disc-burner) ⭐ 68 | 🐛 3 | 🌐 Shell | 📅 2025-11-01 - Open-source, portable Linux tool for burning PS1/PS2 backup discs, with options for patching the disc image before burning.
* [rnc\_propack\_source](https://github.com/lab313ru/rnc_propack_source) ⭐ 67 | 🐛 1 | 🌐 C | 📅 2026-05-19 - Decompiled source of Rob Northen Computing's RNC ProPack, a compression format used by many games across multiple platforms.
* [isodump](https://github.com/Lameguy64/isodump) ⭐ 49 | 🐛 3 | 🌐 C++ | 📅 2021-01-13 - PlayStation ISO content extraction tool. Extracts files from PSX ISO/BIN images, supports ISO9660 filesystem, XA and STR files. Generates MKPSXISO-compatible XML project files for rebuilding ISOs.
* [cicdec](https://github.com/Bioruebe/cicdec) ⭐ 44 | 🐛 11 | 🌐 C# | 📅 2024-06-16 - Unpacker for installers made with Clickteam Install Creator, used to extract game data bundled by that installer format.
* [uninno](https://github.com/onitake/uninno) ⭐ 42 | 🐛 3 | 🌐 Perl | 📅 2024-03-09 - Portable command-line unpacking tool for Inno Setup installers, commonly used to unpack game installers before further asset processing.
* [Macaron](https://github.com/Azukee/Macaron) ⭐ 41 | 🐛 3 | 🌐 C# | 📅 2021-07-27 - Archive unpacker for various visual novel/eroge engine formats.
  * Formats: AIMS (.p), AdvHD (.arc), Artemis (.pfs), CatSystem2 (.int), HyPack (.pak), Majiro Arc (.arc), NekoPack (.pak), Ren'Py (.rpa), CriWare (.cpk, initial support).
* [akaibu](https://github.com/Forlos/akaibu) ⭐ 34 | 🐛 0 | 🌐 Rust | 📅 2021-10-23 - Visual novel archive extractor and resource converter with GUI and CLI, supporting dozens of proprietary Japanese VN engine archive/image formats (ACV1, CPZ7, and many more).
* [powerpacker\_src](https://github.com/lab313ru/powerpacker_src) ⭐ 31 | 🐛 1 | 🌐 C++ | 📅 2020-08-10 - Decompiled source of Nico François' PowerPacker, an Amiga-era compression format used by many Amiga games. See also [AmigaImploder](https://github.com/lab313ru/AmigaImploder) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2018-05-31, decompiled source of another common Amiga game compression tool.
* [Visual-novel-archive-tools](https://github.com/Cosetto/Visual-novel-archive-tools) ⭐ 30 | 🐛 2 | 🌐 C# | 📅 2022-12-26 - Collection of archive read/write tools for numerous visual novel engines.
  * Engines: AMUSE, AVG\_Engine, Ai6Win/Silky, EAGLS, Escude, Lilim, NEJII, NEKOSDK, Nexas, TmrHiro, Unity, Valkyria, codeX RScript.
* [RTB-QuickBMS-Scripts](https://github.com/RandomTBush/RTB-QuickBMS-Scripts) ⭐ 28 | 🐛 2 | 📅 2026-03-20 - Collection of QuickBMS scripts for various games.
* [ae (AE - VN Tools)](https://github.com/niksaak/ae) ⭐ 28 | 🐛 1 | 🌐 Pascal | 📅 2017-04-24 - Multipurpose Delphi utility for common visual novel archive, image, and misc data formats: an archiver, an image manipulation/conversion tool (EDGE), and a raw image data reader (GrapS).
* [edccchk](https://github.com/claunia/edccchk) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2025-03-09 - EDC/ECC checker for raw (2352 bytes/sector) CD images, used to verify game disc dump integrity.
* [AssetRipper CLI](https://github.com/MeikoMei16/AssetRipper-CLI) ⭐ 25 | 🐛 0 | 🌐 C# | 📅 2026-04-07 - Command-line front-end built on AssetRipper for batch-exporting CG, character portraits, backgrounds, and audio from Unity visual-novel/gacha games via reusable extraction profiles.
* [ps4tools](https://github.com/harlequin/ps4tools) ⭐ 24 | 🐛 3 | 🌐 C | 📅 2019-05-21 - Tools for extracting PS4 file formats including PUP, PKG, PFS, and trophy files.
* [IPFBrowser](https://github.com/exectails/IPFBrowser) ⭐ 17 | 🐛 1 | 🌐 C# | 📅 2026-01-03 - Tool to extract and browse the contents of IPF archive files, used by several NHN/Webzen MMO titles.
* [spoondec](https://github.com/Bioruebe/spoondec) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2023-10-16 - Extractor for Spoon (Xenocode) virtualized installer packages, used to extract game data bundled by that installer format.
* [VNTools](https://github.com/redfoxymoon/vntools) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2026-07-07 - Collection of portable ISO C99 utilities for unpacking/packing/converting various visual novel engine archive formats (formerly published under the account hiirotsuki).
  * Engines/formats: Cromwell (`.opk`/`.pak`), IkuraGDL (`.GGP`/SM2MPX10), Studio Neko Punch, Studio-Sakura, Succubus, Silky's (`.IFL`), Carriere (`.CGD` to BMP), BasiL (`.MIF`), ARCX (`.arc`), Pinpai (`.hiz`).
* [flux-analyze](https://github.com/kristomu/flux-analyze) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2026-04-24 - Analysis and recovery tool for IBM MFM floppy flux image data.
* [innounpy](https://github.com/lkraider/innounpy) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2013-01-21 - Multiplatform Python unpacker for Inno Setup installers, a pure-Python alternative to innoextract for extracting game installer contents.
* [mdsx](https://github.com/Marisa-Chan/mdsx) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2025-12-16 - Decompressor/decrypter for MDS v2 / MDX disc image formats (DAEMON Tools).
* [quickbms-scripts (devinacker)](https://github.com/devinacker/quickbms-scripts) ⭐ 5 | 🐛 0 | 📅 2021-01-13 - Small collection of QuickBMS scripts for extracting game archives, covering MTV Club Dead (`.dta`), Klik & Play/Click & Create/The Games Factory (`.gam`, `.cca`, `.mus`, `.snd`), and Twisted: The Game Show (`Stream` directory).
* [romrepomgr](https://github.com/claunia/romrepomgr) ⭐ 5 | 🐛 2 | 🌐 C# | 📅 2025-12-23 - ROM Repository Manager for organizing and deduplicating game ROM/disc image collections.
* [dumplib](https://github.com/drojaazu/dumplib) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2014-09-07 - Library for working with media images (ROMs, disk images) from older video game consoles.
* [PKGTool](https://github.com/thesupersonic16/PKGTool) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2017-08-18 - Tool for extracting and repacking PKG files from The Legend of Heroes: Trails of Cold Steel.
* [wad-tools](https://github.com/libertyernie/wad-tools) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2022-11-28 - Tools for WAD archive format (Wii/GameCube). Fork of BFGR WadTools with enhanced command-line options for wadpacker and wadunpacker, including custom output directories and common-key.bin path specification. Supports C++and C++/CLI compilation.
* [imploder](https://github.com/hitchhikr/imploder) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-08-10 - Data/exe files cruncher/decruncher for 68000-based machines, built on the reversed implode/explode routines credited above.
* [gogextract](https://github.com/e-m-h/gogextract) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-11-19 - Shell script for extracting game files from GOG/innoextract archives.
* [uwpdumper-rs](https://github.com/coconutbird/uwpdumper-rs) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-02-11 - Rust reimplementation of UWPDumper for extracting files from sandboxed UWP applications (including Xbox Game Pass games) via DLL injection into the running process.
* [unPAKer](https://github.com/mxtherfxcker/unPAKer) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-05-26 - Generic PAK archive unpacker for game asset extraction.
* [GalArc](https://github.com/lunaswd/GalArc) ⭐ 0 | 🐛 0 | 📅 2024-10-25 - GUI archive extraction/repacking tool covering 20+ visual novel engines (formerly published under the account detached64).
  * Engines/formats: AdvHD (`arc`/`pna`), Ai5Win (`arc`/`dat`/`VSD`), Ai6Win (`arc`), Artemis (`pfs`), BiShop (`bsa`), Cmvs (`cpz`), EntisGLS (`noa`), InnocentGray (`iga`/`dat`), KID (`dat`), Kirikiri (`xp3`), Majiro (`arc`), NekoSDK (`pak`), NeXAS (`pac`), NextonLikeC (`lst`), Nitro+ (`pak`), NScripter (`ns2`/`nsa`), Palette (`pak`), PJADV (`dat`/`pak`), RPG Maker (`rgssad`/`rgss2a`/`rgss3a`), Softpal (`pac`), SystemNNN (`gpk`/`vpk`), Triangle (`CG`/`SUD`/`CGF`), Yuris (`ypf`).
* [L.A.V.E. (Linear Archive Viewer and Extractor)](https://github.com/RobseK101/lave) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2026-07-06 - Views and extracts game asset archives, with bidirectional sorting by filename, offset, size, or extension.
  * Formats: .img archives from Davilex "Raser" titles (Autobahn Raser II, London Racer, Paris-Marseille Racing) and GTA III / Vice City / San Andreas.
* [universal-explorer](https://github.com/Vulae/universal-explorer) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-08-16 - Viewer/unpacker for a variety of game archive and texture formats across multiple engines.
  * Formats: Source engine (VPK archives, VTF textures), Godot engine (PAK archives, STEX/CTEX textures), Ren'Py (RPA archives); Unity/Unreal/GameMaker support planned.
  * Continuation of the author's earlier universal-unpacker.
* [StreamZip](https://github.com/v-lenn/StreamZip) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-07-20 - Archive extraction tool for very large (150GB+) game archives with on-the-fly decompression; demonstrated on Cyberpunk 2077.
* [dat-creator](https://github.com/f-pisani/dat-creator) ⚠️ Archived - Qt/C++ file archiver with GUI for bundling files into a single DAT container, with an API for loading/extracting; useful for game asset packaging.
* [genesis-rom-workshop](https://github.com/wesellis/genesis-rom-workshop) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-06-30 - Workshop tool for inspecting and modifying Sega Genesis/Mega Drive ROMs.
* [QuickBMS](https://aluigi.altervista.org/quickbms.htm) - Universal archive extractor and reimporter with extensive script database covering thousands of games. Uses BMS scripting language to describe archive formats.

### 🔊 Audio Tools

* [vgmstream](https://github.com/vgmstream/vgmstream) ⭐ 2,243 | 🐛 21 | 🌐 C | 📅 2026-09-01 - Audio playback library supporting 1000+ game audio formats including looping, multi-channel streams, and console-specific codecs. Works as a standalone player or Winamp/foobar2000 plugin. If a game audio file exists, vgmstream probably plays it.
* [FamiStudio](https://github.com/BleuBleu/FamiStudio) ⭐ 1,938 | 🐛 38 | 🌐 C# | 📅 2026-08-10 - NES/Famicom music editor and tracker with cycle-accurate APU/expansion-audio emulation. Imports/exports NSF, FamiTracker (FTM), and FTI instrument files, and can export finished music directly for use in NES games/ROMs.
* [vgmtrans](https://github.com/vgmtrans/vgmtrans) ⭐ 1,268 | 🐛 87 | 🌐 C++ | 📅 2026-09-04 - Video Game Music Translator; converts proprietary game audio sequence/soundfont formats from many games/consoles into standard MIDI/DLS/SF2.
* [BassoonTracker](https://github.com/steffest/BassoonTracker) ⭐ 1,168 | 🐛 31 | 🌐 JavaScript | 📅 2026-08-05 - Web-based old-school Amiga music tracker in plain JavaScript. Plays and edits Amiga Mod files and FastTracker XM files.
* [Wwise-Unpacker](https://github.com/Vextil/Wwise-Unpacker) ⭐ 794 | 🐛 37 | 🌐 Batchfile | 📅 2026-07-18 - Windows tool for extracting audio from Wwise PCK and BNK containers to OGG or MP3 format. Works with any game using Wwise audio middleware.
* [jpsxdec](https://github.com/m35/jpsxdec) ⭐ 600 | 🐛 47 | 🌐 Java | 📅 2026-05-17 - Cross-platform PlayStation 1 audio and video converter.
* [impulse-tracker](https://github.com/jthlim/impulse-tracker) ⭐ 444 | 🐛 1 | 🌐 Assembly | 📅 2024-10-20 - Original source code release for Impulse Tracker, the DOS music tracker behind the widely-used IT module format found in many games' soundtracks.
  * Chips: YM2151/2203/2413/2608/2610/2612, OPL2/3, QSound, C140/C352, Konami K005289/007232/051649/053260/054539, SegaPCM, MultiPCM, RF5C68/400, ES5506, BSMT2000, Williams DCS/DAC/CVSD, and more.
* [ww2ogg](https://github.com/hcs64/ww2ogg) ⭐ 397 | 🐛 8 | 🌐 C++ | 📅 2024-10-12 - Converts Wwise RIFF/RIFX Vorbis audio (.wem files) to standard Ogg Vorbis format. Command-line tool with packed codebook support for various encoding variants. Note: vgmstream is recommended for playback, but ww2ogg is useful when Ogg Vorbis output is specifically required.
* [ymfm](https://github.com/aaronsgiles/ymfm) ⭐ 377 | 🐛 13 | 🌐 C++ | 📅 2026-07-27 - BSD-licensed emulation cores for Yamaha FM sound chips (OPM, OPN, OPL, and others) widely used across arcade and console game audio.
* [wwiser](https://github.com/bnnm/wwiser) ⭐ 367 | 🐛 3 | 🌐 Python | 📅 2026-08-23 - Wwise .bnk explorer and audio simulator. Python tool for parsing Wwise soundbank files, viewing HIRC audio scripting data, generating TXTP files for vgmstream playback, and dumping bank contents. Works with any game using Wwise audio middleware.
* [nsfplay](https://github.com/bbbradsmith/nsfplay) ⭐ 324 | 🐛 4 | 🌐 C++ | 📅 2025-02-04 - NSF (Nintendo Sound Format) player and library for NES/Famicom game-music rips, including expansion-audio chip emulation and command-line WAV rendering/metadata utilities.
* [C700](https://github.com/osoumen/C700) ⭐ 316 | 🐛 15 | 🌐 C | 📅 2023-03-06 - AU/VST software sampler plugin emulating the SNES's SPC700/DSP sound engine. Directly loads and plays SPC dumps and AddmusicM-format raw BRR sample files (also AIFF/WAV), with up to 128 waveforms across 4 banks and real-hardware sync via a G.I.M.I.C. board.
* [VGMusicStudio](https://github.com/Kermalis/VGMusicStudio) ⭐ 309 | 🐛 50 | 🌐 C# | 📅 2024-07-13 - Music player and visualizer for GBA (MP2K format, SDAT) and NDS handheld game audio. Supports playback and extraction with SoundFont2 support, built on the same author's [SoundFont2](https://github.com/Kermalis/SoundFont2) ⭐ 33 | 🐛 0 | 🌐 C# | 📅 2022-08-31, [KMIDI](https://github.com/Kermalis/KMIDI) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2023-05-17, [KFLP](https://github.com/Kermalis/KFLP) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2023-07-05, and [DLS2](https://github.com/Kermalis/DLS2) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2022-09-01 libraries for reading/writing SF2, MIDI, FL Studio project, and DLS files.
* [VGAudio](https://github.com/Thealexbarney/VGAudio) ⭐ 262 | 🐛 28 | 🌐 C# | 📅 2023-02-12 - .NET library for encoding, decoding, and manipulating audio files from video games.
  * Formats: BRSTM, BCSTM, BFSTM, IDSP, HPS, DSP (Nintendo formats).
* [snestracker](https://github.com/bazz1tv/snestracker) ⭐ 243 | 🐛 105 | 🌐 C++ | 📅 2022-05-02 - Super Nintendo Entertainment System (Super Famicom) music tracker software.
* [LoopingAudioConverter](https://github.com/libertyernie/LoopingAudioConverter) ⭐ 217 | 🐛 14 | 🌐 C# | 📅 2026-06-30 - Tool for converting many game audio formats to looping WAV, OGG, or FLAC files. Supports many console formats through VGAudio and vgmstream.
* [adplug](https://github.com/adplug/adplug) ⭐ 185 | 🐛 23 | 🌐 C++ | 📅 2026-09-03 - Hardware-independent AdLib/OPL sound player library used by many DOS-era games' music formats (.sng, .lds, .rol, .cmf, .imf, .amd, .rad, .hsc, and dozens more).
* [OPL3BankEditor](https://github.com/Wohlstand/OPL3BankEditor) ⭐ 174 | 🐛 24 | 🌐 C++ | 📅 2026-08-28 - Cross-platform editor for OPL3 FM instrument bank formats used by numerous DOS-era games and sound drivers (IBK, OP2/GENMIDI, TMB, WOPL, and others).
* [wwiseutil](https://github.com/hpxro7/wwiseutil) ⭐ 151 | 🐛 27 | 🌐 Go | 📅 2018-10-17 - Tool for manipulating Wwise SoundBank and File Package files. Works with any game using Wwise audio middleware.
  * Formats: .bnk, .nbnk (SoundBank), .pck, .npck (File Package), WEM (audio).
  * Features: Unpacking WEM audio, audio replacement with metadata updates, loop point editing.
* [vgmtools](https://github.com/vgmrips/vgmtools) ⭐ 149 | 🐛 4 | 🌐 C | 📅 2026-08-16 - Collection of tools for the VGM (Video Game Music) file format, including conversion and inspection utilities.
* [gbsplay](https://github.com/mmitch/gbsplay) ⭐ 123 | 🐛 13 | 🌐 C | 📅 2026-09-01 - Game Boy sound player for GBS (Game Boy Sound) format music rips.
* [archive-follin](https://github.com/breakintoprogram/archive-follin) ⭐ 103 | 🐛 0 | 🌐 Python | 📅 2025-08-13 - Recovered assembler music source code and drivers written by Tim and Geoff Follin for NES/SNES/Genesis games at Software Creations (Silver Surfer, Plok, Solstice, and others), preserved from original 3" floppy disks.
  * Components: SymbTool, InfoTool, Nitro Studio GUI
* [adpcm](https://github.com/superctr/adpcm) ⭐ 102 | 🐛 0 | 🌐 C | 📅 2025-12-15 - ADPCM encoder/decoder library and CLI covering game/arcade sound-chip codecs: Yamaha ADPCM-A/B (YM2610/Y8950/YM2608), Yamaha AICA (Dreamcast), Oki/Dialogic VOX (MSM6295 arcade sound chip, MSM6258 X68000), Brian Schmidt BSMT2000/QSound (arcade), and YMZ280B.
* [vgm\_ripping](https://github.com/hcs64/vgm_ripping) ⭐ 96 | 🐛 3 | 🌐 C | 📅 2022-10-18 - Sources for game music ripping tools.
* [Citric-Composer](https://github.com/gota7/Citric-Composer) ⭐ 89 | 🐛 32 | 🌐 C# | 📅 2024-04-15 - Editor for 3DS, Wii U, and Switch sound files. See also [Tiniifan's fork](https://github.com/Tiniifan/Citric-Composer) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-04-15.
* [gba-hq-mixer](https://github.com/ipatix/gba-hq-mixer) ⭐ 59 | 🐛 1 | 🌐 Assembly | 📅 2026-08-22 - High-quality sound mixer replacements for GBA games using the m4a/mp2k sound driver.
* [es-ps2-vag-tool](https://github.com/eurotools/es-ps2-vag-tool) ⭐ 46 | 🐛 0 | 🌐 C# | 📅 2026-08-22 - Tool to convert Sony PS2 VAG files to WAV PCM 16-bit encoding and vice versa.
* [pmdmini](https://github.com/mistydemeo/pmdmini) ⭐ 43 | 🐛 1 | 🌐 C++ | 📅 2022-10-04 - C/C++ library for playing back PMD/MXDRV chiptunes from the NEC PC-98, used by many PC-98-era games' Yamaha YM2203/YM2608 soundtracks.
* [wwise-audio-tools](https://github.com/WolvenKit/wwise-audio-tools) ⭐ 39 | 🐛 4 | 🌐 C++ | 📅 2024-01-26 - Static and dynamic library plus command-line tool for converting Wwise WEM files to OGG format. Modern replacement for ww2ogg and revorb with easier integration.
* [EZNSF](https://github.com/bbbradsmith/eznsf) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2023-04-22 - Tool for transforming NSF (NES Sound Format) music rip files into playable NES ROMs, using Python and the CC65 toolchain.
* [gc-dspadpcm-encode](https://github.com/jackoalan/gc-dspadpcm-encode) ⭐ 35 | 🐛 0 | 🌐 C | 📅 2023-10-23 - Nintendo GameCube DSP-ADPCM encoder tool.
* [Wwise-BNKExtract](https://github.com/rickvg/Wwise-BNKExtract) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2016-05-11 - Extraction utility for Wwise soundbank files (BNK format, file version 113 and earlier). Extracts WEM audio files for conversion to OGG Vorbis format.
* [VGMGUI](https://github.com/BENICHN/VGMGUI) ⚠️ Archived - Graphical interface for vgmstream. (Archived.)
* [QuattroPlay](https://github.com/superctr/QuattroPlay) ⭐ 31 | 🐛 4 | 🌐 C | 📅 2025-02-22 - Reimplementation of the Quattro sound driver used in Namco arcade games from the mid-1980s to late 1990s.
* [XPMCK](https://github.com/bazz1tv/XPMCK) ⭐ 27 | 🐛 23 | 🌐 Assembly | 📅 2016-04-15 - Cross-platform MML (music macro language) compiler kit and playback library collection, with bugfixes/new features on top of the original jiggawatt.org release.
  * Systems: Amstrad CPC, Atari 8-bit (400/800/XL/XE), Capcom Play System (VGM output), ColecoVision, Commodore 64, MSX (KSS output), Game Boy/Game Boy Color, PC Engine/TurboGrafx, SEGA Master System, Game Gear, Genesis.
* [es-ima-adpcm-encoder-decoder](https://github.com/eurotools/es-ima-adpcm-encoder-decoder) ⭐ 24 | 🐛 0 | 🌐 C# | 📅 2026-08-22 - Tool to convert IMA ADPCM files to WAV PCM 16-bit encoding and vice versa.
* [manatools](https://github.com/dakrk/manatools) ⭐ 20 | 🐛 17 | 🌐 C++ | 📅 2025-08-17 - Tools for working with Dreamcast audio and music formats (MLT, MPB, MSB).
* [SDATTool](https://github.com/froggestspirit/SDATTool) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2025-02-11 - Tool for unpacking and packing Nintendo DS SDAT audio files (SSEQ sequences, SBNK banks, SWAR samples).
* [NitroTools](https://github.com/Gota7/NitroTools) ⭐ 20 | 🐛 2 | 🌐 C# | 📅 2018-12-23 - Toolkit for extracting and editing Nintendo DS SDAT audio.
* [mod2vgm](https://github.com/superctr/mod2vgm) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2024-08-18 - Converts Protracker MOD modules to VGM using the OPL4 chip, for use in game audio pipelines.
* [PMDDotNET](https://github.com/kuma4649/PMDDotNET) ⭐ 20 | 🐛 0 | 🌐 C# | 📅 2025-12-20 - .NET port of PMD (Professional Music Driver), a widely-used sound driver/sequence format in PC-98 and other Japanese PC games.
* [libopenpmd](https://github.com/OPNA2608/libopenpmd) ⭐ 19 | 🐛 7 | 🌐 C | 📅 2023-01-12 - Library for parsing PMD (Professional Music Driver) files, the PC-98-era sound driver/sequence format also handled by PMDDotNET and pmdmini above.
* [soundbank-editor](https://github.com/t1f7/soundbank-editor) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2016-07-04 - Python-based editor for Wwise soundbank files (.bnk). List, extract, and replace WEM sounds while preserving headers, events, and metadata. Works with any game using Wwise audio middleware.
* [WwiseParser](https://github.com/xyx0826/WwiseParser) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2025-09-11 - C# library for parsing Wwise 2016.1 SoundBank object formats. Supports deserializing Wwise objects, rebuilding hierarchies (Master-Mixer and Actor-Mixer), and dumping SoundBank files to JSON. Works with any game using Wwise audio middleware.
* [ZENSF](https://github.com/bbbradsmith/zensf) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2020-02-10 - Tool for building an NES ROM music album from a collection of NSF files using a custom expanded mapper (iNES Mapper 031). See also [EZNSF](https://github.com/bbbradsmith/eznsf) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2023-04-22 for an easier-to-use alternative.
* [gaxtapper](https://github.com/loveemu/gaxtapper) ⭐ 11 | 🐛 11 | 🌐 C++ | 📅 2024-08-31 - Automated GSF ripper for GAX Sound Engine. Extracts game audio from titles using GAX, outputting GSF format files.
* [MDXtract](https://github.com/Optiroc/MDXtract) ⭐ 11 | 🐛 0 | 🌐 HTML | 📅 2026-07-01 - Python tools for extracting instrument and sample data from files used by the MXDRV and PMD sound drivers, common across many Japanese PC-88/PC-98 games.
* [ahx2wav](https://github.com/LemonHaze420/ahx2wav) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2018-11-18 - Converts AHX audio files (a tracker-based container format used primarily in SEGA games) to WAV, for single files or entire directories.
* [ray2get](https://github.com/Synthesis/ray2get) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2026-01-19 - Convert the .apm music files from Rayman 2 (PC) to .wav.
* [openpsf](https://github.com/myst6re/openpsf) ⭐ 8 | 🐛 3 | 🌐 C++ | 📅 2021-07-17 - Tiny library to stream PSF (Portable/PlayStation Sound Format) files.
  * See also [psflib](https://github.com/myst6re/psflib) ⭐ 1 | 🐛 1 | 🌐 C | 📅 2021-07-10 for a lower-level PSF reading library.
* [nesadpcm](https://github.com/furrykef/nesadpcm) ⭐ 7 | 🐛 0 | 🌐 Assembly | 📅 2016-07-31 - VOX (Oki MSM6295-style) ADPCM player for the NES.
* [fsb5\_split](https://github.com/CyberBotX/fsb5_split) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2021-04-07 - Tool to split a multi-stream FSB5 into multiple single-stream FSB5s.
* [MCAConverter](https://github.com/onepiecefreak3/MCAConverter) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2024-07-31 - Converter for Capcom's MCA format. Converts MCA to WAVs and vice versa.
* [nsfid](https://github.com/karmic64/nsfid) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2025-07-03 - Play-routine/sound-driver identifier for binary music rips from computers and video game consoles (including NSF), matching byte-pattern signatures against a configurable driver database.
* [M1](https://github.com/enver-haase/M1) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2024-07-05 - Arcade and pinball music player by Richard Bannister, emulating original sound hardware to play back music directly from MAME-compatible ROM dumps across hundreds of unrelated arcade/pinball titles.
* [es-xbox-adpcm-tool](https://github.com/eurotools/es-xbox-adpcm-tool) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-08-22 - Tool to convert Xbox ADPCM files to WAV PCM 16-bit encoding and vice versa.
* [es-dsp-adpcm-tool](https://github.com/eurotools/es-dsp-adpcm-tool) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-08-22 - Nintendo GameCube DSP audio data encoder. Converts GameCube DSP ADPCM to WAV PCM 16-bit encoding and vice versa.
* [nitro-play](https://github.com/DanielPXL/nitro-play) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-18 - Parser for Nintendo DS SDAT audio format with music export.
* [libnus3audio](https://github.com/jam1garner/libnus3audio) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2022-08-23 - Rust library for working with nus3audio files.
* [oki-adpcm2](https://github.com/philpem/oki-adpcm2) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2026-03-22 - Reverse engineering and reimplementation of the OKI ADPCM2 compression scheme used by many arcade sound boards.
* [crosslooper](https://github.com/Splendide-Imaginarius/crosslooper) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2024-07-16 - Automatically sets LOOPSTART/LOOPLENGTH/LOOP\_START/LOOP\_END metadata tags in audio files using statistical cross-correlation, for seamless BGM looping in RPG Maker and other engines.
* [ntrWavTool](https://github.com/turtleisaac/ntrWavTool) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2023-04-05 - Converts WAV to IMA ADPCM SWAV for use in DS games.
* [Audio Overload SDK](https://github.com/hcs64/aosdk) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2021-01-22 - SDK for game audio format engines supporting QSF (Capcom), SSF (Sega Saturn), PSF/PSF2 (PlayStation), and DSF (Dreamcast) formats.
* [XWB Studio](https://github.com/Mogolt/XWB-to-WAV-converter) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2026-06-11 - GUI tool for extracting, injecting, and converting XACT XWB (Xbox wave bank) audio; originally built for Resident Evil 4 (2005 PC) modding but applicable to other XACT-based games.
* [HIRCDump](https://github.com/neptuwunium/HIRCDump) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2022-01-23 - Dump soundbank samples via event IDs.
* [es-eurocom-adpcm-encoder-decoder](https://github.com/eurotools/es-eurocom-adpcm-encoder-decoder) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-08-22 - Tool to convert custom Eurocom ADPCM files to WAV PCM 16-bit encoding and vice versa.
* [nitro-player](https://github.com/henke37/nitro-player) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-07-14 - Player for Nitro Composer (SDAT) sequence files used in Nintendo DS games.
* [psf-shellext](https://github.com/henke37/psf-shellext) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2019-11-20 - Windows shell extension displaying tag metadata for PSF/miniPSF (PlayStation Sound Format) files in Explorer property sheets.
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

* [LunaTranslator](https://github.com/HIllya51/LunaTranslator) ⭐ 13,039 | 🐛 70 | 🌐 C++ | 📅 2026-09-05 - Full-featured visual novel translator application combining game text extraction with translation, OCR, and TTS.
  * Features: HOOK-based text extraction covering most common and niche VN engines, HOOK emulators for reading text from NS/PSP/PSV/PS2 games, embedded in-game translation overlay for supported games, built-in and pluggable OCR engines, broad translation API support (LLMs, offline MT), TTS and speech recognition, Japanese tokenization/furigana and AnkiConnect/Yomitan integration for language learners.
* [Textractor](https://github.com/Artikash/Textractor) ⭐ 2,689 | 🐛 635 | 🌐 C++ | 📅 2024-03-15 - Highly extensible universal text hooker/extractor for video games and visual novels, widely used as the base for translation and OCR pipelines.
* [GalTransl](https://github.com/GalTransl/GalTransl) ⭐ 2,258 | 🐛 40 | 🌐 Python | 📅 2026-09-05 - Automated translation pipeline for Japanese visual novels using LLMs (GPT-4, Claude, DeepSeek, Sakura), consuming the script/text JSON exported by engine-specific extraction tools (e.g. [msg-tool](https://github.com/lifegpc/msg-tool) ⭐ 56 | 🐛 3 | 🌐 Rust | 📅 2026-07-29) and re-inserting translated text. See also [GalTransl\_DumpInjector](https://github.com/GalTransl/GalTransl_DumpInjector) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2025-12-20, a companion GUI front-end wrapping VNTextPatch, msg-tool, or custom regex to dump/inject game text across many VN engines.
* [Kuriimu2](https://github.com/FanTranslatorsInternational/Kuriimu2) ⭐ 437 | 🐛 165 | 🌐 C# | 📅 2026-08-28 - Next-gen version of Kuriimu.
* [VNTranslationTools](https://github.com/arcusmaximus/VNTranslationTools) ⚠️ Archived - VNTextPatch, a text extraction/translation/patching framework for Japanese visual novels, plus VNTextProxy, a companion DLL for injecting non-Japanese text rendering into VN engines that only support Shift-JIS.
  * Engines: AdvHD, ArcGameEngine, Artemis, BGI/Ethornell, CatSystem2, Cyberworks C,system, KaGuYa, Kirikiri, Majiro, Musica, Mware, Propeller/Stuff Script Engine, RealLive, Ren'Py, ShSystem, Silky's/AI6WIN, Qlie, Softpal, SystemNNN, TmrHiroAdvSystem, Whale, YU-RIS.
  * Features: Script text extraction/repacking, SJIS-tunneling text rendering proxy, Locale Emulator relaunching.
* [Kuriimu](https://github.com/IcySon55/Kuriimu) ⭐ 376 | 🐛 111 | 🌐 C# | 📅 2023-08-04 - General purpose game translation toolkit.
* [agent](https://github.com/0xDC00/agent) ⭐ 355 | 🐛 12 | 📅 2024-04-25 - Universal script-based text hooker powered by Frida, for extracting in-memory text from Japanese games/visual novels across many engines.
* [toolkit-Localization](https://github.com/YuriSizuku/toolkit-Localization) ⭐ 66 | 🐛 0 | 🌐 Python | 📅 2026-02-03 - Collection of generic galgame localization components: `ftext` text serialization format, text/image/font extraction utilities, and Windows console/file-I/O/redirect hooking libraries used to build engine-specific translation patchers.
* [SimpleFontHook](https://github.com/SuQiandYing/SimpleFontHook) ⭐ 62 | 🐛 1 | 🌐 C++ | 📅 2026-08-24 - Hooks Galgame rendering to let the player freely substitute their own font, across many visual novel engines.
* [jstrings](https://github.com/drojaazu/jstrings) ⭐ 43 | 🐛 0 | 🌐 C++ | 📅 2023-01-03 - Tool for finding JIS-based Japanese text strings in binary data, useful for locating text in Japanese game files.
* [GalFontTool](https://github.com/SuQiandYing/GalFontTool) ⭐ 32 | 🐛 1 | 🌐 Python | 📅 2026-05-03 - Toolbox for Galgame translation and font adaptation, including font subsetting/patching utilities.
* [TF3 (Translation Framework 3)](https://github.com/Kaplas80/TF3) ⭐ 22 | 🐛 12 | 🌐 C# | 📅 2024-09-03 - General-purpose game translation framework with per-game plugins, including [Yakuza](https://github.com/Kaplas80/TF3.YakuzaPlugins) ⭐ 5 | 🐛 1 | 🌐 C# | 📅 2023-04-01 and [Zwei](https://github.com/Kaplas80/TF3.ZweiPlugins) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2022-08-20 series plugins.
* [Nepgear](https://github.com/SuQiandYing/Nepgear) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2026-06-28 - Detours-based C++ process-hooking tool for Galgame translation work.
* [CialloHook](https://github.com/Lite0812/CialloHook) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2026-08-30 - General-purpose text hooking tool for Windows Galgame executables.
* [VWF\_Calculator](https://github.com/Bunkai9448/VWF_Calculator) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-03-23 - Variable Width Font (text size) calculator to help fit translated strings within a ROM hack's original space constraints.

### 🔍 Hex Editors

* [ImHex](https://github.com/WerWolv/ImHex) ⭐ 54,698 | 🐛 394 | 🌐 C++ | 📅 2026-09-05 - Modern, open-source hex editor with pattern language for reverse engineering file formats (free).
* [010 Editor](https://www.sweetscape.com/010editor/) - Professional hex editor with powerful template system for analyzing binary file structures (paid).

#### Scripts & Templates

* [hexyl](https://github.com/sharkdp/hexyl) ⭐ 10,267 | 🐛 35 | 🌐 Rust | 📅 2026-04-30 - Command-line hex viewer with colored output.
* [WpfHexEditorIDE](https://github.com/abbaye/WpfHexEditorIDE) ⭐ 932 | 🐛 15 | 🌐 C# | 📅 2026-06-29 - Full-featured binary analysis IDE for Windows built with WPF and .NET. Features VS-style docking, project system, and multiple specialized editors.
* [hobbits](https://github.com/Mahlet-Inc/hobbits) ⭐ 749 | 🐛 33 | 🌐 Python | 📅 2025-04-16 - Multi-platform GUI for bit-based analysis, processing, and visualization of binary data, with a plugin system for custom parsers.
* [hexerator](https://github.com/crumblingstatue/hexerator) ⭐ 369 | 🐛 26 | 🌐 Rust | 📅 2026-08-30 - Versatile GUI hex editor focused on binary file exploration and aiding pattern recognition. Written in Rust.
* [binxelview](https://github.com/bbbradsmith/binxelview) ⭐ 249 | 🐛 5 | 🌐 C# | 📅 2026-08-18 - Binary image explorer that renders raw binary data as a bitmap at adjustable width/bit-depth/palette, for visually spotting embedded graphics data inside ROMs and other game files.
* [hxd-plugin-framework](https://github.com/maelh/hxd-plugin-framework) ⭐ 188 | 🐛 6 | 🌐 Pascal | 📅 2022-02-11 - Plugin framework for HxD hex editor to support custom file formats.
* [pytai](https://github.com/Dvd848/pytai) ⭐ 132 | 🐛 2 | 🌐 Python | 📅 2025-09-24 - Python-based interactive hex viewer and Kaitai Struct visualizer, rendering a binary file's parsed structure tree alongside its raw bytes.
* [Alpha-Offset-Fixer](https://github.com/alphazolam/Alpha-Offset-Fixer) ⭐ 1 | 🐛 0 | 🌐 Roff | 📅 2021-10-04 - 010 Editor script to help with relative offsets in binary templates.
* [hex](https://github.com/cosarara/hex) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2014-09-26 - Simple hexadecimal editor with vi-like modal interface.
* [xcd-rgb](https://anongit.hacktivis.me/git/xcd-rgb.git) - Command-line hexdump with colored output, based on [xcd](https://git.sr.ht/~breadbox/xcd).

### 🔬 Format Analysis & Reverse Engineering

#### Binary Templates & Format Descriptions

* [fq](https://github.com/wader/fq) ⭐ 10,588 | 🐛 61 | 🌐 Go | 📅 2026-09-03 - "jq for binary formats" - command-line tool, language, and decoder collection for querying and inspecting binary and text formats, useful for ad-hoc exploration of unfamiliar game file formats.
* [ImHex-Patterns](https://github.com/WerWolv/ImHex-Patterns) ⭐ 1,012 | 🐛 50 | 🌐 ImHex Pattern Language | 📅 2026-09-03 - Binary format pattern database for ImHex hex editor, with game file format definitions and reverse-engineering templates.
* [bitfield](https://github.com/wavedrom/bitfield) ⭐ 394 | 🐛 19 | 🌐 JavaScript | 📅 2024-02-22 - Tool for rendering bit field diagrams from JSON descriptions, useful for documenting binary formats.
* [010-Editor-Templates](https://github.com/tge-was-taken/010-Editor-Templates) ⭐ 54 | 🐛 3 | 🌐 C++ | 📅 2026-03-01 - Collection of 010 Editor binary templates for game file format analysis.
* [010GameTemplates](https://github.com/Nenkai/010GameTemplates) ⭐ 45 | 🐛 0 | 🌐 C# | 📅 2026-06-18 - Collection of 010 Editor templates for various games including Gran Turismo, Forza, Project Cars, Ridge Racer 7, Tales of Vesperia, Xenoblade Chronicles, Granblue Fantasy: Relink, Driveclub, WWE 2K, and many others.
* [hogsy/formats](https://github.com/hogsy/formats) ⭐ 10 | 🐛 0 | 🌐 Assembly | 📅 2025-12-03 - Collection of reversed binary format specifications in [Rehex](https://github.com/solemnwarning/rehex) ⭐ 2,478 | 🐛 26 | 🌐 C++ | 📅 2026-07-23 Binary Template format, covering games from many studios.
  * Features: Templates are easily translatable to C/C++; related loader implementations in the [Hei library](https://github.com/QuartermindGames/hei) ⭐ 23 | 🐛 4 | 🌐 C | 📅 2026-08-19.
  * Studios/Games: Acclaim (Vista 3D engine: Turok Evolution; Unknown engine: Burnout?), Blitz Games/BlitzTech 1 (Glover, Chicken Run, Frogger 2, Action Man), BottleRocket (The Mark of Kri, Rise of the Kasai, Xiaolin Showdown), Core Design (Project Eden, Herdy Gerdy), Computer Artworks (The Thing, Evolva), Creative Reality (Martian Gothic: Unification), Gee Whiz! (Zombie Wars), Guerrilla Cambridge / Millennium Interactive (C-12: Final Resistance), Infogrames/Gremlin Interactive (Hogs of War), Lucasfilm Games (Ares Engine), Midway Studios Austin / Inevitable Entertainment (The Hobbit 2003, Area 51), nStigate/Nihilistic (Vampire: The Masquerade – Redemption), Oddworld Inhabitants (Stranger's Wrath), SCE Studio Cambridge (Primal), SingleTrac (Outwars), Tate Interactive, Team Ico, Traveller's Tales (Haven: Call of the King), Appeal S.A. (Outcast).
  * Formats: DAT, PSI, SPT, WAD, CLU, HGT, ACW, EDN, PAK, MSH, GFX/TEX, MIN, DFS, NOD, and more.
* [Dody's Research](https://github.com/TheDodylectableX/Research) ⭐ 5 | 🐛 0 | 📅 2026-08-19 - Collection of 010 Editor binary templates and standalone/Blender/Noesis scripts documenting file formats (models, textures, archives, and more) across multiple PC and console games.
* [astraea](https://github.com/aethelwerks/astraea) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2020-07-24 - Framework and scripting language for reverse engineering and describing binary file formats.
* [010-Editor-Templates (godofknife)](https://github.com/godofknife/010-Editor-Templates) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-07-31 - Large personal collection of 010 Editor binary templates for video game and console formats.
  * Games: Persona 3/4/5 (and Royal/Portable/Reload variants), Persona Q/Q2, Shin Megami Tensei, Bully, Sonic Adventure 2, Yakuza, Spyro 5, Skylanders Ring of Heroes, Metal Gear Rising, and Tekken (BCD) data, among many others.
  * Formats: Atlus proprietary containers (BF/BED/TBL/FBN/HBN/GFD/CAR/PMD), CRI CPK archives, GameCube DSP audio, PS2 TM2/GIM/GMO textures, Xbox XACT audio banks, and Unreal Engine 4.27 UAsset/UToC/UCas container formats.
* [010 Templates / ImHex Patterns](https://github.com/neptuwunium/bt) ⚠️ Archived - Templates for binary analysis.
* [GameRes010Templates](https://github.com/miccTronic/GameRes010Templates) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-06-26 - 010 Editor templates for reading resource files from various games.
  * Games: LithTech 5/Monolith (F.E.A.R. 2, Condemned 2), Asura Engine/Rebellion (Aliens vs. Predator 2010), Unreal Engine 1/2 (Thief: Deadly Shadows, Deus Ex: Invisible War), Incubation (Blue Byte, 1997), Nocturne/Demon Engine/Terminal Reality (Nocturne, Blair Witch I/II/III), King's Quest VIII: The Mask of Eternity.
* [mafia-formats](https://github.com/pudingus/mafia-formats) ⭐ 1 | 🐛 0 | 📅 2020-11-18 - 010 Editor templates for Mafia: The City of Lost Heaven file formats.
* [gsaxml](https://github.com/Candoran2/gsaxml) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-08-26 - XML description of the binary format of compiled GSA (Game Script Archive) files.
* [gameyaml](https://github.com/Herringway/gameyaml) ⭐ 0 | 🐛 0 | 🌐 PowerShell | 📅 2023-09-26 - YAML documentation of internal data structures for a dozen classic RPGs (Chrono Trigger, Dragon Warrior Monsters, EarthBound, Final Fantasy IV/V/VI, Golden Sun, Kirby Super Star, Mother 2/3, Out of This World, Pokemon, Paper Mario, Super Mario Bros, Super Mario World).
* [Kaitai Struct](https://kaitai.io/) - Declarative language for describing binary data structures with code generation for multiple programming languages.

#### Disassemblers, Decompilers & Analysis Frameworks

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) ⭐ 74,402 | 🐛 1,939 | 🌐 Java | 📅 2026-09-02 - NSA's software reverse engineering (SRE) framework. Includes disassembly, assembly, decompilation, graphing, and scripting. Extensible through Java and Python plugins.
* [Cutter](https://github.com/rizinorg/cutter) ⭐ 19,672 | 🐛 493 | 🌐 C++ | 📅 2026-08-22 - Free and open-source GUI-based reverse engineering platform powered by Rizin, for analyzing game binaries and file formats.
* [RetDec](https://github.com/avast/retdec) ⭐ 8,620 | 🐛 458 | 🌐 C++ | 📅 2026-05-26 - Retargetable machine-code decompiler based on LLVM, supporting multiple architectures and file formats — useful for reverse engineering game binaries. Currently in limited maintenance.
* [qiling](https://github.com/qilingframework/qiling) ⭐ 6,087 | 🐛 116 | 🌐 Python | 📅 2026-09-05 - Advanced binary emulation framework. Emulates multi-platforms (Windows, macOS, Linux, Android, BSD, UEFI, DOS) and multi-architectures (x86, ARM, MIPS, RISC-V, PowerPC). Supports PE, Mach-O, ELF formats with fine-grain instrumentation, cross-architecture debugging, and dynamic hot patching.
* [Steamless](https://github.com/atom0s/Steamless) ⭐ 5,010 | 🐛 25 | 🌐 C# | 📅 2024-03-30 - DRM remover for the SteamStub packer variants, unpacking Steam-protected game executables to enable further static/dynamic analysis of the underlying binary.
* [diaphora](https://github.com/joxeankoret/diaphora) ⭐ 4,389 | 🐛 35 | 🌐 Python | 📅 2026-09-04 - Advanced binary diffing tool (IDA/Binary Ninja/Ghidra) for comparing game binaries across versions/patches, widely used in game reverse engineering workflows.
* [iced](https://github.com/icedland/iced) ⭐ 3,560 | 🐛 61 | 🌐 Rust | 📅 2026-09-04 - Blazing fast and correct x86/x64 disassembler, assembler, decoder, and encoder. Available for Rust, .NET, Java, Python, and Lua. Useful for reverse engineering game binaries.
* [SafeDiscShim](https://github.com/RibShark/SafeDiscShim) ⭐ 569 | 🐛 38 | 🌐 C++ | 📅 2025-09-29 - Compatibility tool that allows SafeDisc-protected games relying on the insecure Macrovision Security Driver (secdrv.sys) to run on modern versions of Windows, enabling further analysis of the underlying game binaries.
* [ProjectorRays](https://github.com/ProjectorRays/ProjectorRays) ⭐ 292 | 🐛 13 | 🌐 C++ | 📅 2025-11-13 - Decompiler for Adobe/Macromedia Shockwave and Director movies (.dcr/.dir), used across many CD-ROM-era multimedia and point-and-click games.
* [Ouroboros](https://github.com/Hexorg/Ouroboros) ⭐ 258 | 🐛 2 | 🌐 Rust | 📅 2025-12-02 - Symbolic-execution decompiler written in Rust. Recovers high-level structure from binaries using symbolic execution and constraint tracking. Features CFG recovery, structural reconstruction (if/else, loops), calling convention inference, and beautiful UI with egui.
* [DirectorCastRipper](https://github.com/n0samu/DirectorCastRipper) ⭐ 96 | 🐛 7 | 🌐 LiveScript | 📅 2026-08-25 - Exports assets and information from Adobe/Macromedia Director movies and casts, complementing ProjectorRays above.
* [Ruri.ShaderDecompiler](https://github.com/ShiyumeMeguri/Ruri.ShaderDecompiler) ⭐ 91 | 🐛 0 | 🌐 C# | 📅 2026-09-05 - Cross-engine shader decompiler that restores compiled DXBC/DXIL/SPIR-V shader binaries to readable HLSL, re-injecting variable-name symbol information recovered from engine-side metadata (AssetRipper for Unity, CUE4Parse for Unreal Engine).
* [Mizuchi](https://github.com/macabeus/mizuchi) ⭐ 73 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-17 - Automatic decompilation tool using plugin-based pipeline to convert assembly to C source code matching binary targets.
* [Senbei](https://github.com/Momoko-Ayase/Senbei) ⭐ 61 | 🐛 0 | 🌐 Rust | 📅 2026-09-01 - Static unpacker for binaries protected by CrackProof DRM (used by games such as Street Fighter V and Umamusume: Pretty Derby), enabling further static analysis of the underlying executable.
* [Pattern16](https://github.com/Dasaav-dsv/Pattern16) ⭐ 53 | 🐛 4 | 🌐 C++ | 📅 2024-01-07 - Fastest x86-64 signature matching library. Optimized for reverse engineering with speeds up to 25 GB/s. Uses AVX1, SSE4.1, SSE2, CMOVE, BMI2, and BMI1. Header-only C++ library for pattern scanning in memory regions.
* [Shockky](https://github.com/PaulusParssinen/Shockky) ⭐ 53 | 🐛 4 | 🌐 C# | 📅 2026-05-12 - .NET library for disassembling and assembling Adobe/Macromedia Shockwave files, complementing ProjectorRays and DirectorCastRipper above.
* [zoltan](https://github.com/jac3km4/zoltan) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - Generates DWARF debug symbols and headers on the fly for reverse engineering game executables, by matching annotated C/C++ pattern signatures against a target binary.
* [crudNES](https://github.com/hitchhikr/crudNES) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2026-03-18 - NES emulator built for reverse engineering purposes, including a tracer that records executed code.
* [retrogram](https://github.com/kmeisthax/retrogram) ⭐ 9 | 🐛 4 | 🌐 Rust | 📅 2021-05-09 - Binary program analysis toolkit for reverse engineering retro game binaries.
* [Arm64Disassembler](https://github.com/neptuwunium/Arm64Disassembler) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-12-20 - Lightweight C# Arm64 disassembler library.
* [atlas](https://github.com/nblockbuster/atlas) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-06-15 - Hashing tool for reverse engineering work. Plugin-based system supporting FNV (0, 1, 1a), MD2/MD4/MD5, Murmur2/3, SipHash, SHA1/SHA2/SHA3, XXHash/XXHash3. Useful for analyzing hashed values in game file formats.
* [hlsldecompiler-rs](https://github.com/cohaereo/hlsldecompiler-rs) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-04-11 - Statically linked 3dmigoto Rust wrapper for HLSL shader decompilation.
* [ExeGag](https://github.com/efimandreev0/ExeGag) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-03-08 - Tool to edit game strings into compiled ELF files.
* [BinaryX](https://github.com/Cuyler36/BinaryX) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2020-12-12 - BinaryReader capable of reading both BigEndian and LittleEndian schemes.

#### IDA / Hex-Rays Plugins

* [HexRaysCodeXplorer](https://github.com/REhints/HexRaysCodeXplorer) ⭐ 2,641 | 🐛 15 | 🌐 C++ | 📅 2025-11-27 - Hex-Rays Decompiler plugin for better code navigation in reverse engineering. Automates code reconstruction of C++ applications and modern malware. Features include automatic type reconstruction, virtual function table detection, and RTTI analysis.
* [IDArling](https://github.com/IDArlingTeam/IDArling) ⚠️ Archived - Collaborative reverse engineering plugin for IDA Pro and Hex-Rays. Enables multiple users to work on the same IDA database simultaneously.
* [FakePDB](https://github.com/Mixaill/FakePDB) ⭐ 647 | 🐛 29 | 🌐 C++ | 📅 2025-12-10 - Tool for PDB generation from IDA Pro database. Supports IDA >= 7.0. Can generate PDB files, export IDA database to JSON, find binary signatures, and import function names from JSON.
* [microavx](https://github.com/gaasedelen/microavx) ⭐ 331 | 🐛 4 | 🌐 Python | 📅 2023-04-28 - AVX lifter for the Hex-Rays Decompiler. Extends IDA Pro decompiler with partial support for Intel Advanced Vector Extensions (AVX) instructions. Demonstrates how Hex-Rays microcode can be used to lift and decompile new or previously unsupported instructions.
* [HexForge](https://github.com/elastic/HexForge) ⭐ 86 | 🐛 1 | 🌐 Python | 📅 2025-05-31 - IDA plugin that extends the functionality of the assembly and hex view, allowing you to decode/decrypt/alter data directly from the IDA Pro interface.
* [ida-images](https://github.com/rr-/ida-images) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2022-09-17 - Image preview plugin for the IDA disassembler, previewing embedded raster images directly in the binary view.

#### Managed & Bytecode Decompilers (.NET / Java / Script)

* [dnSpy](https://github.com/dnSpy/dnSpy) ⚠️ Archived - .NET debugger and assembly editor. Essential for inspecting and editing .NET game binaries (Unity games, etc.) even without source code. Supports decompilation to C#.
* [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) ⭐ 15,630 | 🐛 103 | 🌐 Java | 📅 2026-07-17 - A Java 8+ Jar & Android APK reverse engineering suite. Includes multiple decompilers (FernFlower, Procyon, CFR), bytecode assemblers, and a keyword search feature.
* [jd-gui](https://github.com/java-decompiler/jd-gui) ⭐ 15,192 | 🐛 248 | 🌐 Java | 📅 2024-07-08 - A standalone graphical utility that decompile and displays Java source codes of .class files. Supports Drag and Drop and Zip/Jar files.
* [Recaf](https://github.com/Col-E/Recaf) ⭐ 7,373 | 🐛 66 | 🌐 Java | 📅 2026-08-22 - Modern Java bytecode editor. Easy-to-use interface for editing Java bytecode with decompiler integration, built-in compiler, bytecode assembler, and support for standard Java and Android applications.
* [JPEXS Free Flash Decompiler](https://github.com/jindrapetrik/jpexs-decompiler) ⭐ 5,847 | 🐛 5 | 🌐 Java | 📅 2026-08-08 - Free Flash (SWF) decompiler/editor for viewing and modifying ActionScript 1/2/3 bytecode, shapes, sprites, sounds, and other tags in SWF files, widely used for reverse-engineering Flash-based games.
* [hermes-dec](https://github.com/P1sec/hermes-dec) ⭐ 1,168 | 🐛 7 | 🌐 Python | 📅 2026-08-11 - Decompiler and disassembler for React Native Hermes bytecode (HBC).
* [luajit-decompiler-v2](https://github.com/marsinator358/luajit-decompiler-v2) ⭐ 475 | 🐛 5 | 🌐 C++ | 📅 2026-05-14 - Decompiler for LuaJIT bytecode, with support for gotos and stripped bytecode (including locals/upvalues); used to recover scripts from various games embedding LuaJIT.
* [JSC-PyDecrypt-Tool](https://github.com/bartlomiejduda/JSC-PyDecrypt-Tool) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2025-10-13 - Decrypts JSC (JavaScript Compiled) files from Cocos2d games. Requires valid encryption key extracted via Frida from running game instances.
* [unluac](https://sourceforge.net/projects/unluac/) - A decompiler for Lua 5.1. Capability to decompile most Lua 5.1 binaries, including those with custom opcodes or modified headers found in various games. See also [UnluacNET](https://github.com/Fireboyd78/UnluacNET) ⭐ 35 | 🐛 0 | 🌐 C# | 📅 2018-11-20, a C# port of the original Java unluac.
* [NutCracker](https://github.com/darknesswind/NutCracker) ⭐ 28 | 🐛 14 | 🌐 C++ | 📅 2020-09-22 - Decompiler for Squirrel 3 bytecode, updated from an earlier Squirrel decompiler for compatibility with games using the Squirrel scripting language.
* [UnityDowngradingTools](https://github.com/efimandreev0/UnityDowngradingTools) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-22 - Utility tools for fixing and adapting AssetRipper decompiles to older Unity versions (e.g., PS Vita Sally Face port).

#### Decompilation Project Toolchains

* [Spice86](https://github.com/OpenRakis/Spice86) ⭐ 656 | 🐛 22 | 🌐 C# | 📅 2026-09-05 - Reverse engineers and rewrites real-mode DOS programs by running the original executable and progressively replacing its functions with C# overrides, for recreating early DOS-era games from their binaries.
* [m2c](https://github.com/matt-kempster/m2c) ⭐ 636 | 🐛 65 | 🌐 Python | 📅 2026-09-03 - MIPS and PowerPC decompiler.
* [decomp.me](https://github.com/decompme/decomp.me) ⭐ 605 | 🐛 127 | 🌐 TypeScript | 📅 2026-09-04 - Collaborative decompilation and reverse engineering website, widely used to reverse game binaries function-by-function against a reference build.
* [objdiff](https://github.com/encounter/objdiff) ⭐ 529 | 🐛 89 | 🌐 Rust | 📅 2026-08-29 - Local diffing tool for decompilation projects.
* [splat](https://github.com/ethteck/splat) ⭐ 351 | 🐛 42 | 🌐 Python | 📅 2026-07-27 - Binary splitting tool to assist with decompilation and modding projects.
* [decomp-toolkit](https://github.com/encounter/decomp-toolkit) ⭐ 280 | 🐛 31 | 🌐 Rust | 📅 2026-03-02 - GameCube & Wii decompilation toolkit.
* [decomp-permuter](https://github.com/simonlindholm/decomp-permuter) ⭐ 217 | 🐛 50 | 🌐 Python | 📅 2026-09-03 - Randomly permute C files to better match a target binary.
* [rabbitizer](https://github.com/Decompollaborate/rabbitizer) ⭐ 179 | 🐛 2 | 🌐 C | 📅 2026-05-29 - MIPS instruction decoder used across N64 decompilation projects to produce matching assembly.
* [asm-differ](https://github.com/simonlindholm/asm-differ) ⭐ 167 | 🐛 35 | 🌐 Python | 📅 2026-08-25 - Diffing tool for comparing target and current assembly output, widely used alongside decomp-permuter in decompilation projects.
* [pdb-decompiler](https://github.com/camden-smallwood/pdb-decompiler) ⭐ 129 | 🐛 7 | 🌐 Rust | 📅 2026-07-09 - Decompiles MSVC PDB debug symbol files to C++ source code, with optional IDA pseudocode export, useful for recovering source structure from Windows game binaries with debug information.
* [ccc](https://github.com/chaoticgd/ccc) ⭐ 106 | 🐛 3 | 🌐 C++ | 📅 2026-06-07 - Library and command-line tools for parsing debugging symbols from PS2 games, focused on STABS symbols embedded in .mdebug ELF sections; aids recovery of function/struct names for decompilation projects.
* [ds-decomp](https://github.com/AetiasHax/ds-decomp) ⭐ 85 | 🐛 9 | 🌐 Rust | 📅 2026-09-03 - Toolkit for decompiling Nintendo DS games, with ROM extraction, building, symbol analysis, and asset handling tools.
* [spimdisasm](https://github.com/Decompollaborate/spimdisasm) ⭐ 79 | 🐛 7 | 🌐 Python | 📅 2026-08-06 - MIPS disassembler used across N64 decompilation projects to produce matching assembly.
* [dtk-template](https://github.com/encounter/dtk-template) ⭐ 75 | 🐛 14 | 🌐 Python | 📅 2026-04-26 - Project scaffold/template for starting a new GameCube/Wii decompilation project with decomp-toolkit above.
* [dis86](https://github.com/xorvoid/dis86) ⭐ 59 | 🐛 3 | 🌐 Rust | 📅 2026-03-11 - Disassembler and decompiler for 8086 DOS binaries, useful for reverse engineering early DOS-era games.
* [dwarf2cpp](https://github.com/seilc/dwarf2cpp) ⚠️ Archived - Converts DWARF v1 debug data from ELF files into C/C++ definitions including structs, enums, unions, and function definitions. Useful for reverse engineering games with DWARF debug information.
* [dadosod](https://github.com/InusualZ/dadosod) ⭐ 23 | 🐛 3 | 🌐 Rust | 📅 2023-05-06 - Disassembles GameCube/Wii DOL executables to bootstrap a decompilation project: guesses/calculates section boundaries, splits the binary into per-section files (including `.bss`/`.sbss`/`.sbss2`), performs partial data-type detection, and generates a matching linker script.
* [delink](https://github.com/HaydnTrigg/delink) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 - Symbol splitting tool for decompilation projects, supporting ELF (DWARF), Mach-O (STABS/SYMTAB), and PE (PDB) binary formats.
* [libgfxd](https://github.com/glankk/libgfxd) ⭐ 15 | 🐛 3 | 🌐 C | 📅 2025-10-29 - Display list decompiler library, the de facto N64 F3D/F3DEX display list disassembler underlying gfxd-rs above.
* [transmuter](https://github.com/macabeus/transmuter) ⭐ 12 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-07 - Automatically mutates C, C++, or Pascal source code to match a target binary's assembly (or refine code quality while preserving the match), for matching decompilation projects.
* [objdiff-web](https://github.com/encounter/objdiff-web) ⭐ 11 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-10 - Web interface and VS Code extension for objdiff, a local diffing tool for decompilation projects.
* [ida-pdb-file-tree](https://github.com/camden-smallwood/ida-pdb-file-tree) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-04-12 - IDA Pro plugin that groups symbols in a source file tree based on PDB debug data, easing navigation when reversing a Windows game binary with matching PDB symbols.
* [research](https://github.com/ProjectDreamland/research) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2016-02-24 - Research on game engine and decompiled game code.
* [libgcc\_vr4300](https://github.com/Decompollaborate/libgcc_vr4300) ⭐ 8 | 🐛 4 | 🌐 C | 📅 2023-11-17 - Subset of GCC's libgcc rebuilt for the MIPS VR4300 CPU (Nintendo 64), used by N64 decompilation projects to match compiler-emitted intrinsic/runtime routines.
* [pygfxd](https://github.com/Thar0/pygfxd) ⭐ 7 | 🐛 1 | 🌐 C | 📅 2026-03-14 - Python 3 bindings for libgfxd using ctypes.
* [ModBase-Advance](https://github.com/kmeisthax/ModBase-Advance) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2018-07-01 - Basic template for split disassembly (decompilation) projects targeting the Game Boy Advance.
* [vpk0](https://github.com/tehzz/vpk0) ⭐ 5 | 🐛 1 | 🌐 Rust | 📅 2022-01-15 - Rust encoder/decoder for Nintendo's vpk0 compression format, used in N64-era games.
* [zea](https://github.com/Decompollaborate/zea) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2022-10-21 - Matching (de)compression implementations for Nintendo's MIO0, YAY0, and YAZ0 cartridge compression algorithms, used across N64/GameCube-era Mario and Zelda titles for decompilation and asset extraction.
* [pdb-sdk](https://github.com/jac3km4/pdb-sdk) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-05-30 - Rust library for reading and writing Microsoft PDB (Program Database) debug symbol files, useful for recovering symbol/type information from Windows game binaries.
* [gnuv2\_demangle](https://github.com/Decompollaborate/gnuv2_demangle) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-11-09 - Demangler for GNU v2 (GCC 2.x) C++ mangled symbol names, used when recovering readable symbol names in decompilation projects for games built with old GCC toolchains (e.g. N64/PS1-era titles).
* [address\_space](https://github.com/Decompollaborate/address_space) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-05-11 - Rust crate providing types for MIPS ROM and VRAM address spaces, sizes, and ranges, used by N64 decompilation tooling (e.g. alongside mapfile\_parser) for matching original compiled code.
* [c2-rs](https://github.com/freeqaz/c2-rs) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-08-30 - Clean-room native Rust port of `c2.dll`, the code generator backend of the MSVC compiler that shipped with the Xbox 360 XDK, verified byte-exact against the real compiler via a differential test harness; built to speed up and inform matching decompilation of Xbox 360 game binaries (e.g. alongside XenonRecomp-style projects).
* [gfxd-rs](https://github.com/Decompollaborate/gfxd-rs) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-11-16 - Safe Rust wrapper for glankk's libgfxd, the de facto N64 F3D/F3DEX display list disassembler, built on the gfxd-sys FFI bindings crate. Used in N64 decompilation projects to disassemble Fast3D graphics microcode.
* [grapnel](https://github.com/jac3km4/grapnel) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-05-08 - High-performance binary diffing and structural similarity engine, for comparing executables during decompilation/matching work.
* [pe-clr-tools](https://github.com/camden-smallwood/pe-clr-tools) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-03-08 - Command-line tool for working with mixed-mode (native + .NET) PE DLLs, useful when reverse engineering games with mixed managed/native binaries.
* [ModBase-GB](https://github.com/kmeisthax/ModBase-GB) ⭐ 2 | 🐛 0 | 🌐 Makefile | 📅 2018-04-29 - Basic template for split disassembly (decompilation) projects targeting the Game Boy/Game Boy Color.
* [decomp (agent)](https://github.com/bigyoshi51/decomp) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-07 - General-purpose, ROM-agnostic N64 decompilation agent; uses an LLM to iteratively read assembly, write candidate C, compile, diff, and refine until functions match byte-for-byte, wrapping splat, asm-differ, decomp-permuter, m2c, and ido-static-recomp.
* [texture2c](https://github.com/Decompollaborate/texture2c) ⭐ 1 | 🐛 7 | 🌐 C | 📅 2023-04-26 - Converts Nintendo 64 texture formats to C source/data arrays for use in N64 decompilation and modding projects.

#### Static Recompilation

* [XenonRecomp](https://github.com/hedge-dev/XenonRecomp) ⭐ 6,465 | 🐛 92 | 🌐 C++ | 📅 2025-08-04 - Tool for recompiling Xbox 360 games to native executables. Converts Xbox 360 executables into C++ code that can be recompiled for any platform.
* [PS2Recomp](https://github.com/ran-j/PS2Recomp) ⭐ 3,225 | 🐛 90 | 🌐 C++ | 📅 2026-09-02 - Static recompiler and runtime that converts PlayStation 2 ELF binaries into C++ to produce native PC ports.
* [skate3recomp](https://github.com/mchughalex/skate3recomp) ⭐ 1,288 | 🐛 73 | 🌐 C++ | 📅 2026-07-24 - Native recompilation of the Xbox 360 version of Skate 3 for Windows, Linux, and macOS, with a native Direct3D 12/Vulkan renderer replacing GPU emulation.
* [rexglue-sdk](https://github.com/rexglue/rexglue-sdk) ⭐ 846 | 🐛 38 | 🌐 C | 📅 2026-09-04 - Xbox 360 recompilation runtime and toolkit, used by static recompilation PC ports of Xbox 360 games.
* [RecompOne](https://github.com/BlackLabelHQ/RecompOne) ⭐ 507 | 🐛 2 | 🌐 C# | 📅 2026-09-02 - Static recompiler and runtime for PlayStation 1 (MIPS) game code, converting binaries into native executables.
* [SR (Static Recompiler)](https://github.com/M-HT/SR) ⭐ 414 | 🐛 11 | 🌐 C | 📅 2026-08-27 - Static recompilation project that converts several classic DOS games into native Windows/Linux (x86/ARM) ports (Albion, Septerra Core, X-COM, Warcraft: Orcs & Humans, and others).
* [psxrecomp](https://github.com/mstan/psxrecomp) ⭐ 202 | 🐛 5 | 🌐 C++ | 📅 2026-09-05 - Static recompiler for PlayStation 1 (MIPS) game code.
* [DolRecomp](https://github.com/ExpansionPak/DolRecomp) ⭐ 179 | 🐛 6 | 🌐 C | 📅 2026-08-24 - Static recompiler for GameCube, Wii, and experimental Wii U CPU code.
* [snesrecomp](https://github.com/mstan/snesrecomp) ⭐ 75 | 🐛 6 | 🌐 C | 📅 2026-09-04 - Static recompiler ecosystem for SNES games (part of the R.A.I.D. community), converting 65816 ROM code into portable native code.
* [ndsrecomp](https://github.com/mstan/ndsrecomp) ⭐ 35 | 🐛 1 | 🌐 C++ | 📅 2026-09-04 - Early-stage static recompiler for Nintendo DS games.
* [NWiiRecomp](https://github.com/BlackLineInteractive/NWiiRecomp) ⭐ 24 | 🐛 0 | 🌐 C++ | 📅 2026-08-07 - Static recompilation and runtime toolkit for Nintendo GameCube and Wii binaries, for building native PC ports.
* [segagenesisrecomp](https://github.com/mstan/segagenesisrecomp) ⭐ 24 | 🐛 0 | 🌐 C | 📅 2026-08-22 - Static recompiler for Sega Genesis/Mega Drive games.
* [gbarecomp](https://github.com/mstan/gbarecomp) ⭐ 21 | 🐛 1 | 🌐 C++ | 📅 2026-08-31 - General-purpose static recompiler for the Game Boy Advance.
* [ps1-recomp](https://github.com/PS1Recomp/ps1-recomp) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2026-08-13 - Static recompiler translating PlayStation 1 MIPS R3000A machine code into native C++ executables for PC ports.
* [gbrecompiled](https://github.com/mstan/gbrecompiled) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2026-07-23 - Static recompiler for original Game Boy ROMs.
* [nWiiURecomp](https://github.com/BlackLineInteractive/nWiiURecomp) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2026-08-05 - Static recompilation and runtime toolkit for Nintendo Wii U binaries (based on NWiiRecomp), for building native PC ports.
* [SHO-GTA-VCS-PS2Recomp](https://github.com/BlackLineInteractive/SHO-GTA-VCS-PS2Recomp) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2026-08-05 - Application of PS2Recomp specifically tailored with function maps/configs to statically recompile Silent Hill Origins and GTA: Vice City Stories.
* [smsggrecomp](https://github.com/mstan/smsggrecomp) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2026-07-18 - Static recompiler translating Sega Master System and Game Gear Z80 code into native code.
* [rexauto](https://github.com/xdzleo/rexauto) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2026-09-05 - Desktop orchestrator front-end for the ReXGlue static recompiler, automating the full Xbox 360-to-PC pipeline (extract from ISO/GoD/STFS containers, scaffold, recover jump tables via IDA, build, and self-heal missing functions) into a native x86-64 executable.
* [gcnlle](https://github.com/mstan/gcnlle) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-08-31 - Experimental, LLE-first static recompiler for the Nintendo GameCube IPL (boot ROM).
* [cdirecomp](https://github.com/mstan/cdirecomp) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-07-31 - Static recompiler for Philips CD-i game code.
* [vbrecomp](https://github.com/mstan/vbrecomp) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-07-23 - Static V810-to-C recompiler for Virtual Boy games.
* [z80-recomp-core](https://github.com/mstan/z80-recomp-core) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-07-18 - Shared Zilog Z80 static-recompiler runtime contract and instruction semantics, used across multiple Z80-based static recompilation projects.
* [m68k-recomp-core](https://github.com/mstan/m68k-recomp-core) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-08-10 - Shared clean-room Motorola 68000-family static-recompiler frontend used by Genesis/Mega Drive recompilation projects.

#### Ghidra & IDA Platform Loaders

* [Ghidra-Switch-Loader](https://github.com/Adubbz/Ghidra-Switch-Loader) ⭐ 366 | 🐛 9 | 🌐 Java | 📅 2026-08-31 - Ghidra loader extension for Nintendo Switch executable formats (NCA, XCI), enabling decompilation and reverse engineering of Switch games.
* [ghidra\_psx\_ldr](https://github.com/lab313ru/ghidra_psx_ldr) ⭐ 330 | 🐛 14 | 🌐 Java | 📅 2026-09-03 - PlayStation 1 binary loader for Ghidra.
* [Ghidra-GameCube-Loader](https://github.com/Cuyler36/Ghidra-GameCube-Loader) ⭐ 318 | 🐛 23 | 🌐 Java | 📅 2026-05-24 - Nintendo GameCube binary loader for Ghidra reverse engineering framework.
* [GhidraBoy](https://github.com/Gekkio/GhidraBoy) ⚠️ Archived - Sharp SM83 / Game Boy processor extension for Ghidra. (Archived.)
* [ghidra-emotionengine-reloaded](https://github.com/chaoticgd/ghidra-emotionengine-reloaded) ⭐ 235 | 🐛 11 | 🌐 Java | 📅 2026-08-25 - Ghidra extension adding PlayStation 2 (Emotion Engine) support, including the MIPS R5900 processor with VU macromode and PS2 ELF/IRX loaders.
* [SwitchIDAProLoader](https://github.com/pgarba/SwitchIDAProLoader) ⭐ 226 | 🐛 4 | 📅 2025-06-12 - IDA Pro loader for Nintendo Switch NRO, MOD0, and NSO binaries, parsing sections, symbols, and imports/exports.
* [idaxex](https://github.com/emoose/idaxex) ⭐ 213 | 🐛 8 | 🌐 C++ | 📅 2026-08-11 - XEX/XBE loader plugin for IDA 9, plus the xex1tool CLI, supporting most known Xbox and Xbox 360 executable file formats.
* [XEXLoaderWV](https://github.com/zeroKilo/XEXLoaderWV) ⭐ 170 | 🐛 4 | 🌐 Java | 📅 2026-08-01 - Ghidra loader module for Xbox 360 XEX executable files.
* [N64LoaderWV](https://github.com/zeroKilo/N64LoaderWV) ⭐ 166 | 🐛 1 | 🌐 Java | 📅 2026-08-01 - Ghidra loader module for Nintendo 64 ROMs.
* [ghidra-gekko-broadway-lang](https://github.com/aldelaro5/ghidra-gekko-broadway-lang) ⭐ 135 | 🐛 4 | 📅 2022-02-09 - Ghidra processor language for Gekko/Broadway CPU (GameCube/Wii) disassembly and decompilation.
* [ghidra-allegrex](https://github.com/kotcrab/ghidra-allegrex) ⭐ 129 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-25 - Ghidra processor module adding support for the Allegrex CPU (PSP).
* [ghidra\_sega\_ldr](https://github.com/lab313ru/ghidra_sega_ldr) ⭐ 95 | 🐛 2 | 🌐 Java | 📅 2024-03-09 - Sega Mega Drive/Genesis ROM loader for Ghidra.
* [GhidraOrbis](https://github.com/astrelsky/GhidraOrbis) ⭐ 88 | 🐛 0 | 🌐 Java | 📅 2026-06-24 - Ghidra support for Orbis OS (PlayStation 4) specific software and file formats.
* [Ghidra-SegaSaturn-Loader](https://github.com/VGKintsugi/Ghidra-SegaSaturn-Loader) ⭐ 57 | 🐛 9 | 🌐 Java | 📅 2025-12-29 - Sega Saturn binary loader for Ghidra.
* [VitaLoaderRedux](https://github.com/CreepNT/VitaLoaderRedux) ⭐ 49 | 🐛 4 | 🌐 Java | 📅 2025-12-28 - PlayStation Vita ELF-PRX loader for Ghidra. Successor to the deprecated [VitaLoader](https://github.com/CreepNT/VitaLoader) ⚠️ Archived.
* [ctr-elf2](https://github.com/NWPlayer123/ctr-elf2) ⭐ 41 | 🐛 0 | 🌐 Python | 📅 2021-12-11 - Rewrite of ctr-elf, converting 3DS code.bin to a loadable .elf. Supersedes [nedwill/ctr-elf](https://github.com/nedwill/ctr-elf) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2017-04-13.
* [IDA\_plugin\_3ds](https://github.com/mailwl/IDA_plugin_3ds) ⭐ 33 | 🐛 0 | 🌐 C | 📅 2018-07-20 - IDA plugin for loading decrypted Nintendo 3DS ROMs.
* [GhidraSPU](https://github.com/aerosoul94/GhidraSPU) ⭐ 30 | 🐛 1 | 🌐 Java | 📅 2023-07-07 - SPU processor implementation for Ghidra (PlayStation 3 Cell).
* [ghidra\_sdc\_ldr](https://github.com/lab313ru/ghidra_sdc_ldr) ⭐ 30 | 🐛 1 | 🌐 Java | 📅 2021-06-24 - Sega Dreamcast binary loader for Ghidra.
* [nds2elf](https://github.com/shinyquagsire23/nds2elf) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2022-01-28 - Tools for converting Nintendo DS binaries to ELF for loading in Ghidra/IDA.
* [GhidraProspero](https://github.com/astrelsky/GhidraProspero) ⭐ 13 | 🐛 0 | 🌐 Java | 📅 2026-01-13 - Ghidra support for Prospero OS (PlayStation 5).
* [ghidra\_mdebug](https://github.com/astrelsky/ghidra_mdebug) ⚠️ Archived - Ghidra analyzer adding support for the .mdebug debugging symbol format (PS2/MIPS).
* [psx\_loader](https://github.com/lab313ru/psx_loader) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2021-07-12 - PlayStation 1 executable loader for IDA (Python), companion to ghidra\_psx\_ldr above. See also [psxida](https://github.com/lab313ru/psxida) ⚠️ Archived, an IDA debugger plugin for PSX emulators (PCSX-R).
* [libNidResolver](https://github.com/astrelsky/libNidResolver) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2024-04-07 - Library for resolving PlayStation 5 (Prospero) NIDs in another process, aiding GhidraProspero-based analysis.
* [snes\_ida](https://github.com/lab313ru/snes_ida) ⭐ 6 | 🐛 1 | 🌐 C++ | 📅 2026-03-05 - SNES ROM loader and 65816 processor module for IDA Pro.
* [amiga\_hunk\_loader](https://github.com/lab313ru/amiga_hunk_loader) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2019-04-07 - Amiga Hunk executable loader for IDA Pro. See also [ghidra\_amiga\_ldr](https://github.com/lab313ru/ghidra_amiga_ldr) ⭐ 64 | 🐛 6 | 🌐 Java | 📅 2023-06-27, the equivalent loader for Ghidra, and [amigadbg](https://github.com/lab313ru/amigadbg) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2017-05-26, an AmigaOS debugger plugin for IDA Pro built to work with the Amitools emulator suite.
* [Ghidra-RSP](https://github.com/Random06457/Ghidra-RSP) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2024-09-18 - Nintendo 64 RSP processor module and loader for Ghidra.
* [ghidranite](https://github.com/jac3km4/ghidranite) ⚠️ Archived - Ammonite (Scala) scripting support for Ghidra.
* [ghidra-delinker-extension](https://github.com/widberg/ghidra-delinker-extension) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2026-04-22 - Ghidra extension for delinking executables into relocatable object files. Supports ELF and PE formats, enabling the extraction of functions or data into object files for recompilation or integration into other projects.
* [NTRGhidra](https://github.com/onepiecefreak3/NTRGhidra) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2025-09-28 - Nintendo DS binary loader for Ghidra reverse engineering framework.
* [ghidra-65816](https://github.com/mstan/ghidra-65816) ⭐ 0 | 🐛 1 | 📅 2026-03-16 - WDC 65816 (SNES CPU) processor module for Ghidra.

#### Binary Visualization & Diffing

* [pics](https://github.com/corkami/pics) ⭐ 11,479 | 🐛 5 | 🌐 Assembly | 📅 2024-02-18 - File formats dissections and visualizations for reverse engineering.
* [binocle](https://github.com/sharkdp/binocle) ⭐ 1,320 | 🐛 25 | 🌐 Rust | 📅 2025-01-21 - Graphical binary data visualization tool. Colorizes bytes and renders them as pixels to identify patterns and image-like structures in game files.
* [Veles](https://github.com/codilime/veles) ⚠️ Archived - Binary analysis and visualization tool for reverse engineering (open-source, archived; the codisec.com site is gone).
* [biodiff](https://github.com/8051Enthusiast/biodiff) ⭐ 895 | 🐛 6 | 🌐 Rust | 📅 2024-08-07 - Hex diff viewer that uses alignment algorithms to show differences between binary files.
* [DataExplorer](https://github.com/x64dbg/DataExplorer) ⭐ 94 | 🐛 0 | 🌐 C | 📅 2026-03-15 - Data explorer plugin for x64dbg debugger that integrates the pattern language from ImHex.
* [binviz](https://github.com/VelocityRa/binviz) ⭐ 48 | 🐛 3 | 🌐 C++ | 📅 2021-08-05 - Binary visualization tool for identifying patterns and structure in unknown files. Creates visual representations showing potential compression/encryption, structured data and padding at a glance. Helpful for spotting where assets begin/end in unstructured archives.
* [bdiff](https://github.com/ethteck/bdiff) ⭐ 25 | 🐛 17 | 🌐 Rust | 📅 2024-11-04 - Binary diff tool for decompilation and modding projects with hex viewing and symbol map integration.
* [Monkey-Moore](https://github.com/rjricken/monkey-moore) ⭐ 20 | 🐛 1 | 🌐 C++ | 📅 2026-06-09 - High-performance pattern matching utility for ROM hacking and reverse engineering. Multi-threaded Boyer-Moore algorithm with wildcard support and endianness control for discovering non-standard text encodings.
* [Bin2Obj](https://github.com/hogsy/Bin2Obj) ⚠️ Archived - Converts arbitrary binary data into a Wavefront OBJ point cloud, useful for spotting vertex/mesh data when reverse-engineering unknown formats.
* [saved-game-analyzer](https://github.com/RedDragonWebDesign/saved-game-analyzer) ⭐ 3 | 🐛 8 | 🌐 JavaScript | 📅 2020-09-10 - Web tool for reverse engineering simple, unencrypted binary save game formats via diffing and field labeling; a second tool lets you construct new save files from a labeled structure definition.

#### Hooking, Memory & Runtime Tools

* [PINCE](https://github.com/korcankaraokcu/PINCE) ⭐ 3,081 | 🐛 7 | 🌐 Python | 📅 2026-08-24 - GDB front-end/reverse engineering tool with a Cheat Engine-like interface for Linux.
* [Reloaded-II](https://github.com/Reloaded-Project/Reloaded-II) ⭐ 1,023 | 🐛 187 | 🌐 C# | 📅 2026-08-13 - Universal .NET Core powered modding framework for any native game (x86, x64). DLL injection based mod loader with mod management system, optional mod SDK, and extensive plugin support.
* [ReClassEx](https://github.com/ajkhoury/ReClassEx) ⭐ 930 | 🐛 8 | 🌐 C++ | 📅 2021-07-05 - ReClass Extended, a fork of ReClass with additional features for reverse engineering in-memory class/struct layouts of running game processes, aiding recovery of file format structures.
* [hooking](https://github.com/alphaSeclab/hooking) ⭐ 344 | 🐛 0 | 📅 2020-06-11 - Massive repository of resources about hooking for all platforms (Windows, Linux, Android, iOS). Includes 300+ tools and 600+ articles.
* [Reloaded.Hooks](https://github.com/Reloaded-Project/Reloaded.Hooks) ⭐ 255 | 🐛 8 | 🌐 C# | 📅 2024-11-29 - Advanced native function hooks for x86 and x64. High-performance hooking library for .NET with support for unit testing hooks. Used in Reloaded modding framework.
* [brainslug-wii](https://github.com/Chadderz121/brainslug-wii) ⭐ 56 | 🐛 11 | 🌐 C | 📅 2022-05-04 - BrainSlug, a Wii disc-loading and patching engine that links relocatable ELF "modules" into a running game, letting modders add C-based functionality without hand-assembling binary patches.
* [ReClass.NET](https://github.com/FransBouma/ReClass.NET) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2023-07-04 - Advanced memory class layout reverse engineering tool widely used for analyzing in-memory game data structures, helping translate runtime structures into file format definitions.

#### Console-specific RE (PlayStation / Xbox)

* [pcsx-redux](https://github.com/grumpycoders/pcsx-redux) ⭐ 991 | 🐛 153 | 🌐 C++ | 📅 2026-09-04 - Collection of tools, research, hardware design, and libraries for PlayStation 1 development and reverse engineering, built around a fork of the PCSX emulator with an integrated debugger, assembler, and GPU/memory analysis tooling.
* [Ghidra-Cpp-Class-Analyzer](https://github.com/astrelsky/Ghidra-Cpp-Class-Analyzer) ⚠️ Archived - Ghidra C++ Class and Run Time Type Information (RTTI) analyzer, useful for recovering class hierarchies in game binaries compiled from C++.
* [psxprev](https://github.com/rickomax/psxprev) ⭐ 259 | 🐛 28 | 🌐 C# | 📅 2023-11-09 - Playstation (PSX) Files Previewer and Extractor. Supports various model, texture, and animation formats.
* [Velocity](https://github.com/hetelek/Velocity) ⭐ 244 | 🐛 57 | 🌐 C++ | 📅 2025-10-21 - Cross-platform Xbox 360 file browser/editor (STFS containers, profiles, and more) built on the XboxInternals library.
* [psxrev](https://github.com/emu-russia/psxrev) ⭐ 159 | 🐛 12 | 🌐 C# | 📅 2025-01-20 - Sony PlayStation PCB/chips reverse engineering documentation and resources.
* [ida\_ps5\_elf\_plugin](https://github.com/flatz/ida_ps5_elf_plugin) ⭐ 151 | 🐛 0 | 🌐 Python | 📅 2026-01-07 - IDA Pro plugin/loader for PS5 ELF/SELF executables (IDA 7.5). See also [drakmor's fork](https://github.com/drakmor/ida_ps5_elf_plugin) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2026-02-13 with IDA 9+ support.
* [ida\_gel](https://github.com/aerosoul94/ida_gel) ⭐ 106 | 🐛 2 | 🌐 C | 📅 2019-10-03 - Collection of IDA loaders for various game console ELF files (PS3, PS Vita, Wii U). See also [ps3\_aero\_loader](https://github.com/krystalgamer/ps3_aero_loader) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2025-05-11, a port of the PS3 loader to modern IDA (9.1+).
* [Xbox-360-Crypto](https://github.com/GoobyCorp/Xbox-360-Crypto) ⭐ 86 | 🐛 3 | 🌐 Python | 📅 2025-01-04 - Collection of Xbox 360 cryptography and file-format tools: XeCrypt library, shadowboot ROM builder/extractor, NAND image editor with ECC recalculation, KV encryption/fuse generation, and XDK/recovery image dumper.
* [xbox-reversing](https://github.com/emoose/xbox-reversing) ⭐ 79 | 🐛 2 | 🌐 Python | 📅 2024-10-22 - Tools and documentation for reverse engineering Xbox 360 file formats. Includes IDA Pro loaders and 010 Editor templates for STFS, GDFX, XDBF, and XEX format analysis.
* [xbox-winfsp](https://github.com/emoose/xbox-winfsp) ⭐ 78 | 🐛 11 | 🌐 C# | 📅 2024-02-27 - Brings native support for Xbox filesystems (FATX, STFS, GDFX/XGD/XDVDFS) to Windows via WinFsp.
* [ps3ida](https://github.com/kakaroto/ps3ida) ⭐ 78 | 🐛 1 | 🌐 C++ | 📅 2012-08-25 - Collection of IDA scripts and plugins for PS3 executables.
* [IPS-Peek](https://github.com/vector-man/IPS-Peek) ⭐ 69 | 🐛 14 | 🌐 C# | 📅 2026-08-14 - IPS patch exploration and testing tool.
* [Up](https://github.com/landaire/Up) ⭐ 52 | 🐛 1 | 🌐 C++ | 📅 2015-03-12 - FATX file system (modified FAT variant used on the Xbox 360) explorer for Windows, Linux, and macOS.
* [vitadump](https://github.com/xyzz/vitadump) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2017-11-30 - Tools to assist working with memory dumps obtained from PS Vita.
* [SPRXPatcher](https://github.com/NotNite/SPRXPatcher) ⭐ 42 | 🐛 0 | 🌐 C# | 📅 2024-08-12 - Modern PlayStation 3 ELF patcher for loading SPRX plugin files into decrypted executables.
* [vutrace](https://github.com/chaoticgd/vutrace) ⭐ 37 | 🐛 0 | 🌐 C | 📅 2024-06-22 - PlayStation 2 vector unit tracing debugger.
* [vita-ida-physdump](https://github.com/xyzz/vita-ida-physdump) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2018-09-25 - IDA Pro loader for PS Vita physical memory dumps, detecting modules via import/export parsing and resolving NIDs against vitasdk's `db.yml`.
* [ida-emotionengine](https://github.com/oct0xor/ida-emotionengine) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2022-07-11 - IDA Pro plugin that disassembles PlayStation 2 Emotion Engine COP2 (VU0) MIPS instructions.
* [SNES-decompression-tools](https://github.com/ProtonNoir/SNES-decompression-tools) ⭐ 31 | 🐛 4 | 🌐 C++ | 📅 2026-03-30 - Collection of SNES graphics decompression tools.
* [xbedump](https://github.com/XboxDev/xbedump) ⭐ 25 | 🐛 3 | 🌐 C | 📅 2020-09-27 - Tool for dumping and analyzing header information and signing original Xbox XBE (executable) files.
* [vn\_re](https://github.com/Forlos/vn_re) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2022-12-23 - Documentation and scripts for reverse engineering and working with various visual novel engines.
* [X360](https://github.com/mtolly/X360) ⭐ 23 | 🐛 0 | 🌐 C# | 📅 2014-10-01 - Archive of DJ SkunkieButt's X360 .NET library and Le Fluffie GUI for browsing/editing Xbox 360 file formats (STFS, GPD, and more).
* [XCompression](https://github.com/gibbed/XCompression) ⭐ 19 | 🐛 2 | 🌐 C# | 📅 2019-07-14 - .NET wrapper library for XMemCompress, the LZX-based compression scheme commonly found in Xbox 360 game data.
* [sce-symbol-scanner](https://github.com/LostTemplarRH/sce-symbol-scanner) ⭐ 13 | 🐛 1 | 🌐 Kotlin | 📅 2026-04-20 - Detects SCE SDK functions in ELF files, primarily for PS2. Command-line interface and Ghidra plugin.
* [sfc-comp](https://github.com/sfc-comp/sfc-comp) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2026-01-26 - Collection of compression algorithm implementations used across SFC/SNES games.
* [libxe](https://github.com/hayleyxyz/libxe) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2026-08-09 - C++ library for Xbox 360 (Xenon) internals; implements shadowboot ROM, bootloader, and xboxupd.bin format parsing.
* [stfstool](https://github.com/carrot-c4k3/stfstool) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2025-02-27 - Command-line tool for Xbox 360 STFS packages, based on Velocity.
* [XDBF-Manager](https://github.com/hetelek/XDBF-Manager) ⭐ 7 | 🐛 1 | 🌐 C++ | 📅 2012-07-10 - Browser/editor for Xbox 360 XDBF (dashboard/game-data) files.
* [stfs-webjs](https://github.com/InvoxiPlayGames/stfs-webjs) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2022-01-30 - Reads Xbox 360 STFS container files in the web browser.
* [svod\_unpacker](https://github.com/landaire/svod_unpacker) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2012-06-22 - Unpacks Xbox 360 SVOD packages (Games on Demand, Applications, and titles installed to hard disk).
* [010-Templates](https://github.com/KillzXGaming/010-Templates) ⭐ 5 | 🐛 0 | 📅 2020-08-05 - Collection of 010 Editor binary templates for understanding the structure of various video game binary formats.
* [xVerter](https://github.com/blank-query/xverter) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Xbox 360 and original Xbox game format converter; reads and converts between GoD containers, XDVDFS ISOs (bare or full redump), ZArchive .zar, STFS content packages (XBLA/DLC/title updates), CCI, CSO, CHD, and .zip/.7z archives or extracted game directories.
* [binja-xex2](https://github.com/landaire/binja-xex2) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-12 - Xbox 360 XEX2 executable loader plugin for Binary Ninja.
* [chtdb](https://github.com/tge-was-taken/chtdb) ⭐ 1 | 🐛 0 | 📅 2024-11-25 - Cheats and patches database for PSX games, primarily intended for use with DuckStation emulator. Contains GameShark codes and patches for various games.
* [xval](https://github.com/landaire/xval) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2014-10-19 - Decryption tool for Xbox 360 xval packages.
* [Reverse-Game-Android-Toolkit](https://github.com/nowl-it/Reverse-Game-Android-Toolkit) ⭐ 1 | 🐛 5 | 🌐 TypeScript | 📅 2026-05-12 - Generic toolkit for reverse engineering Android games.
* [Lizard](https://github.com/csinkers/Lizard) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-04-01 - Debugger targeting DOSBox for reverse engineering DOS-era games, with Ghidra XML export data integration.
* [psx-showfile](https://github.com/halkuncode/psx-showfile) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2026-08-20 - PCSX-Redux Lua utility that watches PS1 CD-ROM controller reads and reports which ISO9660 file/sector is currently being loaded, using a disc-image-generated LBA map. Ships sample maps for Another Mind, Chrono Trigger, the three Final Fantasy VII discs, Gran Turismo, SaGa Frontier, and Symphony of the Night.
* [exui](https://github.com/landaire/exui) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-06-06 - Xbox 360 XUI (Xbox User Interface) decompiler.
* [muninn-ghidra](https://github.com/sabercat204/muninn-ghidra) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2026-07-28 - Ghidra plugin/scripts for reverse engineering game binaries.
* [Hunkfile-Viewer](https://github.com/zbirow/Hunkfile-Viewer) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-17 - Viewer for the Amiga Hunk executable format, used by many Amiga games.

### 💻 Development Libraries

* [Kaitai Struct](https://github.com/kaitai-io/kaitai_struct) ⭐ 4,672 | 🐛 529 | 🌐 Shell | 📅 2026-08-31 - Declarative language and code generator for binary data parsers in C++, C#, Go, Java, JavaScript, Python, Rust, and more; widely used for documenting and parsing game file formats.
* [binrw](https://github.com/jam1garner/binrw) ⭐ 851 | 🐛 40 | 🌐 Rust | 📅 2026-07-23 - Rust library for reading and writing binary file formats with derive macros. Successor to `binread`.
* [WLA-DX](https://github.com/vhelin/wla-dx) ⭐ 608 | 🐛 27 | 🌐 C | 📅 2026-08-29 - Multi-target assembler/linker toolchain (Z80, 6502, 65816, SPC700, HuC6280, Game Boy) widely used across retro console ROM hacking and homebrew development.
* [XenosRecomp](https://github.com/hedge-dev/XenosRecomp) ⭐ 493 | 🐛 8 | 🌐 C++ | 📅 2026-03-12 - Tool for converting Xbox 360 shaders to HLSL.
* [armips](https://github.com/Kingcom/armips) ⭐ 411 | 🐛 31 | 🌐 C++ | 📅 2026-08-01 - General-purpose assembler for MIPS, Allegrex, ARM, and Nintendo DS/GBA-era instruction sets, widely used for ROM hacking, homebrew development, and reverse engineering across many retro console platforms.
* [Hexa.NET.ImGui](https://github.com/HexaEngine/Hexa.NET.ImGui) ⭐ 349 | 🐛 26 | 🌐 C# | 📅 2026-08-24 - .NET wrapper for ImGui, useful for creating tools with graphical interfaces.
* [mojoshader](https://github.com/icculus/mojoshader) ⭐ 217 | 🐛 20 | 🌐 C | 📅 2026-09-03 - Library for parsing and translating compiled Direct3D 8/9 shader bytecode to other shading languages (GLSL, ARB, etc.), widely used by Linux/macOS ports and reimplementations of Windows games to run their original shaders on OpenGL/Vulkan.
* [ooz](https://github.com/powzix/ooz) ⭐ 206 | 🐛 5 | 🌐 C++ | 📅 2019-02-13 - Open-source decompressor for Oodle compression formats used in many modern games. Supports Kraken, Mermaid, Selkie, Leviathan, LZNA, Bitknit.
* [bcdec](https://github.com/iOrange/bcdec) ⭐ 190 | 🐛 3 | 🌐 C | 📅 2026-09-02 - Small header-only C library to decompress any BC (block-compressed) texture format, widely used for game textures.
* [BCnEncoder.NET](https://github.com/Nominom/BCnEncoder.NET) ⭐ 155 | 🐛 23 | 🌐 C# | 📅 2026-04-05 - Cross-platform .NET texture encoding library supporting BC1-3/DXT, BC4-5/RGTC, and BC6-7/BPTC block compression, outputting KTX or DDS files.
* [Cast](https://github.com/dtzxporter/cast) ⭐ 151 | 🐛 9 | 🌐 Python | 📅 2026-09-04 - Open container format and libraries for models, animations, materials, and game world scenes.
  * Purpose: Designed to reproduce the same 3D scene identically across different DCC/3D software packages.
  * Usage: Adopted as a common interchange/export format by numerous game asset-extraction and conversion tools.
* [XeNTaXTools-Legacy](https://github.com/XeNTaXTools/XeNTaXTools-Legacy) ⭐ 99 | 🐛 0 | 🌐 C++ | 📅 2023-12-15 - Legacy tools scraped from the XeNTaX forums.
* [ndspy](https://github.com/RoadrunnerWMC/ndspy) ⭐ 88 | 🐛 3 | 🌐 Python | 📅 2026-08-29 - Python library for reading and modifying Nintendo DS file formats (BMG, SSEQ, LZ10, NSBMD).
* [ReverseBox](https://github.com/bartlomiejduda/ReverseBox) ⭐ 51 | 🐛 2 | 🌐 Python | 📅 2026-09-02 - Python library for reverse engineering with utilities for checksums, compression, encryption, hashing, and image processing.
  * Features: Checksums (Adler32, CRC variants, Fletcher, XOR), compression (BZIP2, LZ4, LZMA, MIO0, PackBits, RLE variants), encryption (ROT13, XOR cipher), hashing (FNV, DJB2, MD5, SHA, Murmur3).
  * Formats: 100+ pixel formats including DXT, PVRTC, ETC, ASTC, BC formats, with swizzling support for multiple platforms.
* [Assimp.Net](https://github.com/StirlingLabs/Assimp.Net) ⭐ 49 | 🐛 4 | 🌐 C# | 📅 2023-10-18 - C# .NET Core wrapper for the Open Asset Import Library (Assimp) for importing 3D models.
* [DirectXTexNet](https://github.com/deng0/DirectXTexNet) ⭐ 33 | 🐛 0 | 🌐 C# | 📅 2024-05-22 - .NET wrapper for DirectXTex, a library for working with DirectX texture formats.
* [ds-rom](https://github.com/AetiasHax/ds-rom) ⭐ 27 | 🐛 7 | 🌐 Rust | 📅 2026-07-21 - Rust library for parsing and manipulating Nintendo DS ROM file formats and components.
* [tegra\_swizzle](https://github.com/ScanMountGoat/tegra_swizzle) ⭐ 23 | 🐛 3 | 🌐 Rust | 📅 2026-07-31 - Library implementing Tegra X1 block linear texture memory tiling, used by Switch game textures.
* [linoodle](https://github.com/McSimp/linoodle) ⭐ 21 | 🐛 2 | 🌐 C++ | 📅 2022-07-23 - Linux wrapper for the (Windows-only) Oodle Data Compression library, letting Linux-native tools call into Oodle for decompressing modern game assets. Used by [Smithbox-For-Linux](https://github.com/SrDeTs/Smithbox-For-Linux) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2026-07-31 above for automated Oodle setup.
* [GCNToolKit](https://github.com/Cuyler36/GCNToolKit) ⭐ 20 | 🐛 0 | 🌐 C# | 📅 2019-12-19 - Toolkit for modifying and creating GameCube file formats.
* [GameFormatReader](https://github.com/lioncash/GameFormatReader) ⭐ 17 | 🐛 0 | 🌐 C# | 📅 2017-07-13 - Library for reading various game formats (mostly Nintendo ones).
* [GL Editor Framework](https://github.com/jupahe64/GL_EditorFramework) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2022-05-01 - OpenGL-based framework for creating 3D game editors with hardware-accelerated graphics.
* [Oodle-Tools](https://github.com/Tamely/Oodle-Tools) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2022-06-02 - Oodle compression and decompression bindings for C#. Useful for working with modern games that use Oodle.
* [Amicitia.IO](https://github.com/tge-was-taken/Amicitia.IO) ⭐ 16 | 🐛 2 | 🌐 C# | 📅 2025-11-22 - High performance File IO library with full support for big endian and offsets.
* [asset-importer](https://github.com/Latias94/asset-importer) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2026-05-04 - Comprehensive Rust binding for Assimp (v6.0.5), covering 71+ import and 22+ export 3D formats (OBJ, FBX, glTF, DAE, etc.) with safe, idiomatic Rust wrappers over the C API.
* [Orthrus](https://github.com/NWPlayer123/Orthrus) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-08-22 - Work-in-progress modding toolkit for cross-system format interoperability.
  * Formats: Yay0/Yaz0 (Nintendo compression, N64/GameCube/Wii/Wii U/Switch), Panda3D Multifile archives and BAM/BOO binary models.
* [DrSwizzler](https://github.com/Shadowth117/DrSwizzler) ⭐ 10 | 🐛 1 | 🌐 C# | 📅 2025-09-24 - Library for deswizzling and detiling texture data.
* [SFGraphics](https://github.com/ScanMountGoat/SFGraphics) ⭐ 10 | 🐛 36 | 🌐 C# | 📅 2026-03-24 - OpenGL graphics library for rendering game formats, used in various format viewers.
* [vmf](https://github.com/Galaco/vmf) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2019-02-12 - Go library for parsing Valve's Hammer Editor .vmf map files.
* [CTLib](https://github.com/narahiero/CTLib) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2022-10-05 - Utility library to create and convert various file formats used in Mario Kart Wii custom tracks.
* [pyswizzle](https://github.com/Aclios/pyswizzle) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-11-06 - Python library to swizzle and deswizzle video game textures. Supports Nintendo Switch and PS4 platforms.
* [tinybcdec](https://github.com/jandk/tinybcdec) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2026-07-26 - Small block compression decoder library in pure Java. Zero dependencies, focus on speed and accuracy with support for partial decodes.
  * Formats: BC1-DXT1, BC2-DXT3, BC3-DXT5, BC4-ATI1, BC5-ATI2, BC6H, BC7.
* [mojodds](https://github.com/icculus/mojodds) ⭐ 6 | 🐛 2 | 🌐 C | 📅 2021-07-10 - Simple, dependency-free DirectDraw Surface (.DDS) texture decoder routines in portable C, commonly used for loading game textures without linking DirectX.
* [DragonLib](https://github.com/neptuwunium/DragonLib) ⚠️ Archived - Common library for file format research.
* [SharpRiff](https://github.com/gigaherz/SharpRiff) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2013-10-30 - .NET library for reading and writing RIFF format files, such as .wav, .avi, or WebP.
* [Console-Swizzler](https://github.com/matyamod/Console-Swizzler) ⭐ 4 | 🐛 3 | 🌐 C | 📅 2024-05-21 - C library to swizzle DDS textures for console games. Supports PS4 and Switch texture swizzling/unswizzling with configurable GOB block heights. Includes CLI tool for batch processing.
* [prs.net](https://github.com/FraGag/prs.net) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2013-05-13 - PRS compression/decompression library and GUI front-end for the .NET Framework. PRS is based on LZ77 with run-length encoding and is used in numerous games since the SEGA Saturn, including Phantasy Star Universe.
* [wiiu\_swizzle](https://github.com/ScanMountGoat/wiiu_swizzle) ⭐ 4 | 🐛 5 | 🌐 Rust | 📅 2026-04-01 - Library implementing Wii U texture memory tiling/swizzling.
* [TinyBCSharp](https://github.com/jandk/TinyBCSharp) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-04-05 - C# library for decoding/encoding BC (DXT/BC1-7) compressed texture formats.
* [ByteSerialization](https://github.com/akopetsch/ByteSerialization) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2025-01-30 - Declarative C# binary serialization library giving bit-level control over binary representation; define structs via attributes, similar to BinarySerializer.
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
* [patchwright](https://github.com/MortisClub/patchwright) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-07-20 - Library and CLI for writing save editors that make targeted, in-place edits to MessagePack-serialized Unity/C# game saves without a full file rebuild, preserving each field's original serialized byte width so games that expect fixed-width msgpack fields don't break from auto-minification.
* [Syroot.BinaryData](https://gitlab.com/Syroot/BinaryData) - .NET library for easy binary data reading/writing with support for various endianness and encodings.

### 📂 Script Collections & Multi-Game Tools

#### Multi-Game Viewers & Explorers

* [noclip.website](https://github.com/magcius/noclip.website) ⭐ 4,251 | 🐛 86 | 🌐 TypeScript | 📅 2026-08-26 - In-browser 3D viewer for 100+ games across multiple platforms and studios.
  * Games: Source Engine games (17 titles including Half-Life 2, Portal 1 & 2, Team Fortress 2, CS:GO, L4D2), GoldSrc games (Half-Life, Counter-Strike, TFC, Day of Defeat), Quake,
    Nintendo games (Mario 64, Mario Kart series, Zelda series, Pikmin, Luigi's Mansion, Super Mario Galaxy 1 & 2/Odyssey, Paper Mario series, Kirby, Smash Bros Melee/Brawl, Metroid Prime 1-3, Pokemon Snap/Platinum/HGSS, Pilotwings 64, Wii Sports), Rare games (Banjo-Kazooie, DKC), GTA series (III, Vice City, San Andreas), Crash Bandicoot, Spyro trilogy, Ratchet & Clank 1 & 2, Dark Souls, Katamari Damacy, Kingdom Hearts 1 & 2, Final Fantasy X, Dragon Quest VIII, Okami, Psychonauts, Need for Speed: Most Wanted, SpongeBob games, Jet Set Radio, Crazy Taxi, Sonic Colors, Ragnarok Online, Morrowind, World of Warcraft, Descent 1 & 2, Outer Wilds, Halo CE, and more.
  * Also covers oddities such as the Microsoft Plus! for Windows XP screensavers and Wii channel banners.
* [diii4a](https://github.com/glKarin/com.n0n3m4.diii4a) ⭐ 599 | 🐛 167 | 🌐 C++ | 📅 2026-09-02 - Multi-engine Android/desktop port collection for idTech-derived games, reading each game's original assets.
  * Games: DOOM 3, Quake 4, Prey (2006), Quake 1/2/3, RTCW, ETW, RealRTCW, GZDoom, OpenJK (Jedi Knight), Serious Sam, Icarus, Skin Deep, Quadrilateral Cowboy.
* [MeltyTool](https://github.com/MeltyPlayer/MeltyTool) ⭐ 206 | 🐛 60 | 🌐 C# | 📅 2026-09-05 - Multitool for viewing/extracting assets from various N64/GCN/3DS/PC games.
  * Games: Super Mario 64, Mario Artist (Polygon Studio, Talent Studio), Paper Mario TTYD, Super Paper Mario, Mario Kart Double Dash, Pikmin 1 & 2, Super Mario Sunshine, Chibi-Robo, Super Smash Bros. Melee, Battalion Wars 1 & 2, Super Mario 64 DS, Luigi's Mansion 3D, Majora's Mask 3D, Ocarina of Time 3D, Professor Layton vs. Phoenix Wright, Dead Space, Glover, Halo Wars, Celeste 64, Pokemon Colosseum, and more.
* [BinaryDataExplorer](https://github.com/RayCarrot/BinaryDataExplorer) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2022-04-29 - Binary data explorer and analyzer supporting formats from Rayman, Klonoa, PS1, Game Boy, and GBA games with interactive structure visualization.
* [psarc](https://github.com/ShadelessFox/psarc) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-01-25 - Viewer for PlayStation Archive (PSARC) archives. Supports listing and extracting files from PSARC archives with GUI and CLI interfaces.
* [FModel](https://fmodel.app/) - High-level package explorer and asset viewer for Unreal Engine 4 & 5, Unity, and other modern games. Supporting 1000+ games, it provides advanced visualization for textures, models (with animation support), audio, and specialized formats. Features include package bulk export, AES key management, and a robust search engine.

#### Cross-Game Libraries & Extractors

* [XXMI Launcher](https://github.com/SpectrumQT/XXMI-Launcher) ⭐ 2,845 | 🐛 8 | 🌐 Python | 📅 2026-06-11 - Modding platform/launcher for a shared 3dmigoto-based model-importer ecosystem spanning multiple unrelated gacha titles, installing and hot-loading custom 3D character models as mods.
  * Components: [XXMI-Libs-Package](https://github.com/SpectrumQT/XXMI-Libs-Package) ⭐ 69 | 🐛 5 | 🌐 C++ | 📅 2026-09-04 (shared fork of [bo3b/3Dmigoto](https://github.com/bo3b/3Dmigoto) ⭐ 1,215 | 🐛 94 | 🌐 C++ | 📅 2026-08-19 packaged for the launcher), [XXMITools](https://github.com/leotorrez/XXMITools) ⭐ 142 | 🐛 63 | 🌐 Python | 📅 2026-09-04 (Blender add-on to import/export mod files for the supported games), [gui\_collect](https://github.com/Petrascyll/gui_collect) ⭐ 74 | 🐛 9 | 🌐 Python | 📅 2026-07-09 (GUI tool to collect/extract model data from 3dmigoto frame dumps for use with the importers).
  * Games: Genshin Impact (GIMI), Honkai: Star Rail (SRMI), Honkai Impact 3rd (HIMI), Zenless Zone Zero (ZZMI), Wuthering Waves (WWMI).
* [ScummVM](https://github.com/scummvm/scummvm) ⭐ 2,800 | 🐛 45 | 🌐 C++ | 📅 2026-09-04 - The canonical multi-engine interpreter that reimplements dozens of classic adventure/RPG engines, reading each game's original data files instead of emulating a CPU.
  * Engines/Studios: LucasArts SCUMM, Sierra AGI/SCI, Revolution's Virtual Theatre, Adventure Soft's AGOS, Delphine's Cinematique/Cruise, Coktel Vision's GOB, Westwood/Revolution's BS1/2 (Beneath a Steel Sky, Broken Sword), Wintermute, Grim Fandango's GrimE, Humongous Entertainment's SCUMM-derived titles, and 50+ other engines.
  * Formats: each engine's own resource/archive formats (e.g. SCUMM .SM/.LFL/.HE0, SCI resource maps, AGI VOL/DIR, and dozens more), parsed directly rather than through hardware/CPU emulation.
* [3Dmigoto](https://github.com/bo3b/3Dmigoto) ⭐ 1,215 | 🐛 94 | 🌐 C++ | 📅 2026-08-19 - DirectX 11 modding wrapper that hooks the rendering pipeline to dump and inject shaders, textures, and mesh/buffer data at runtime, rather than reading on-disk archives. Originally built for fixing broken stereoscopic 3D effects; now the shared foundation for the XXMI gacha-game modding stack above, as well as countless other unrelated DX11 game shader/model mods.
* [FuckGalEngine](https://github.com/Inori/FuckGalEngine) ⭐ 1,018 | 🐛 12 | 🌐 C | 📅 2022-02-06 - Large collection of tools for translating Galgames (Japanese visual novels), including archive unpacking/repacking and program hooking for in-place modification.
  * Engines: AdvHD, AliceSoft (Ain), BGI, CatSystem2, DeboLua, EntisGLS, Eushully, ExHIBIT, FLATZ, Falcom, GIGA, InnocentGrey, Kirikiri, LC-ScriptEngine, Leaf, Majiro, Makura, Malie, Minato, Minori, NScript, NekoSDK, Nitro+, PJADV, QLIE, RahuEngine, Seven Wonder, SiglusEngine, Silky, Solfa, Tactics, YukaScript, Yuris, and others.
* [arc\_unpacker](https://github.com/vn-tools/arc_unpacker) ⚠️ Archived - Command-line extractor for images, sounds, music, and other resources from dozens of visual novel (and some other Japanese game) archive/script formats, auto-detecting the format and dispatching to the right decoder (archived).
* [XNALaraMesh](https://github.com/johnzero7/XNALaraMesh) ⭐ 595 | 🐛 38 | 🌐 Python | 📅 2023-11-15 - Blender addon to import/export XNALara/XPS model rips and poses, a format used to share fan-made model extractions across hundreds of unrelated games.
* [SExtractor](https://github.com/satan53x/SExtractor) ⭐ 498 | 🐛 12 | 🌐 Python | 📅 2026-08-12 - Extracts and imports translated text to/from Japanese visual novel scripts, combining generic TXT/BIN/JSON pattern matching with dedicated presets for many engines.
  * Engines: AZ System, Artemis, Black Rainbow, CScript, Cyberworks/CSystem, EAGLS, FVP, Kaguya, Krkr, MED, MoonHir, NekoSDK, RPG Maker MV/VX Ace, RealLive, Ren'Py, SystemC, WillPlus, Yu-ris, and generic regex-based extraction for unsupported engines.
* [GalgameReverse](https://github.com/YuriSizuku/GalgameReverse) ⭐ 466 | 🐛 2 | 🌐 C++ | 📅 2026-02-13 - Large collection of reverse-engineering scripts for Japanese visual novels/galgames across consoles and PC.
  * Games: Sony PSP/PSV titles (tm2 textures), Koei (Kin'iro no Corda, Harukanaru Toki no Naka de), Konami (Tokimeki Memorial Girl's Side 3rd Story), KID (Omoi no Kakera), prototype PSV ports (Air, Clannad, Valpurugavo Uta, Flowers, Island), Eldia (Kanda Alice mo Suiri Suru, Switch), Majiro-engine PC titles (Sorairo, Ruri no Kasane, Winter Polaris), azsystem (Ramune), SystemNNN, WillPlus/AdvHD, Yuris engine, ffa (Amanomiko), nvl-cloud, CRIWare (Iwaihime), Hibiki (Natural Vacation), LiveMaker (Aikimi), Bruns engine, Innocent Gray, ExHIBIT, Hunex, and Unity/Kirikiri/Artemis/Ren'Py/TyranoBuilder/ONScripter cross-engine titles.
  * Formats: proprietary archive (.arc), image (rct/rc8/tm2/txp/nltx/dat), script/text (mjil, ws2, spt, asb, sn.bin, story.dat), and font formats spanning the above engines; also Unity AssetBundle/global-metadata.dat text extraction and krkr xp3/xp3-hxv4 (including CxEncryption/HxEncryption key dumping and static/dynamic hash calculation).
* [chinesize](https://github.com/regomne/chinesize) ⭐ 321 | 🐛 1 | 🌐 C++ | 📅 2023-10-16 - Large collection of reverse-engineering tools/scripts for dozens of (mostly Chinese-market) visual novel engines.
  * Engines: ACPX, AdvPlayer/AdvTry (AVG32 family), advwin32, ARDScript, Artemis, BGI (Buriko General Interpreter), CatSystem2, Circus (Mes), DeboPak, DxLib, Entis GLS, ExHIBIT, FAVORITE, FFDSystem, GameScripter, GsWin (GsPack4), InnocentGrey, ISM, Kirikiri2, Liar-soft, Lpg, Lucifen, Majiro, Malie, MgBase, Musica, N2System, NeXAS, Overflow, QLIE, RealLive, rUGP, Silky, System4, SystemC, Xuse, Yatagarasu, Yuka Script, YU-RIS.
* [GameTracking](https://github.com/SteamTracking/GameTracking) ⭐ 303 | 🐛 0 | 🌐 Shell | 📅 2026-08-17 - Shared CI tooling behind the community's per-game Steam depot trackers, downloading and processing game update files across dozens of Valve titles (Dota 2, CS2, Half-Life, Portal, TF2, and more), including protobuf dumping and VPK content extraction.
* [CNGALTools](https://github.com/YeLikesss/CNGALTools) ⭐ 303 | 🐛 0 | 🌐 C++ | 📅 2026-08-30 - Large toolkit of unpacking/decryption tools for domestic and officially-licensed Chinese-market Galgames, covering 25+ unrelated studios and custom engines.
  * Studios/Engines: NVL/Navila Software Japan (BKEngine, NVLKrkr2, NVLUnity, NVLWeb), Strrationalism (Snowing), BlueAngel, Fontainebleau, ZixSolution (customized Ren'Py), iFAction, AsicxArt, XinYvanGames, SoraPlayer, Irregulars, Visual Novel Maker, Game Creator, OrangeStudio, SeparateHearts, YeTuGames, OurshowGames, CaramelMochaStudio, PygmaGame (modified Ren'Py, several sub-studios), Xso, XiangShe, YuriAVGEngine, SanHuaMiao, SugarRush, JveXingGames, PotatoFlowerProduction, and the SyawaseWorks/HikariField/NekoNyan Chinese localization publishers; also includes a universal Kirikiri XP3 decryption filter and Ren'Py/Unreal Engine unpackers.
* [Niflheim](https://github.com/Yggdrasill-Moe/Niflheim) ⭐ 217 | 🐛 3 | 🌐 C | 📅 2023-08-28 - Collection of reverse-engineering tools/scripts for Nintendo Switch ports of Japanese visual novels, covering multiple unrelated engines.
  * Engines: AliceSoft, CMVS, DDSystem, ExHIBIT, GPK2, Ivory, KaGuYa, Majiro, NEKOPACK, NeXAS, RioShiina, SOFTPAL ADV System, Studio Seldom Adventure System.
* [bevy\_trenchbroom](https://github.com/Noxmore/bevy_trenchbroom) ⭐ 153 | 🐛 11 | 🌐 Rust | 📅 2026-08-13 - Quake level format support (.map, .bsp) and TrenchBroom integration for Bevy engine. Enables loading and rendering of Quake-based game levels.
* [resource\_dasm](https://github.com/fuzziqersoftware/resource_dasm) ⭐ 152 | 🐛 9 | 🌐 C++ | 📅 2026-09-04 - Classic Mac OS resource fork disassembler and reverse-engineering toolkit, with format decoders for dozens of classic Macintosh games.
* [ReflectionHLE](https://github.com/ReflectionHLE/ReflectionHLE) ⭐ 136 | 🐛 6 | 🌐 C | 📅 2026-07-17 - Collection of source ports/reimplementations spanning multiple unrelated DOS studios, reading each game's original data files.
  * Games: id Software (Keen Dreams, Wolfenstein 3D and derived games), the 3D Catacomb Adventure series, Apogee Software (Bio Menace).
* [zx-spectrum-games](https://github.com/mrcook/zx-spectrum-games) ⭐ 110 | 🐛 1 | 🌐 Assembly | 📅 2023-12-29 - Collection of annotated ZX Spectrum game source code disassemblies as SkoolKit `.skool` files, gathering and preserving disassembly efforts spread across many authors and studios.
  * Games: Ultimate Play the Game (Knight Lore, Alien 8), Beyond Software/Lunysoft (Tir Na Nog, Dun Darach), Bug-Byte (Through The Trap Door), Mikro-Gen (Stormbringer), Firebird (Spellbound, Knight Tyme), Mirrorsoft (Dynamite Dan 2), Faster Than Light (Atic Atac), and Chaos: The Battle of Wizards.
  * Also links out to the same author's other standalone disassemblies (JetPac, Lords of Midnight, Chuckie Egg) and related third-party disassembly collections (Skool Daze, Back to Skool, Manic Miner, Jet Set Willy, The Great Escape, and several Paul Maddern/Ritchie Swann works-in-progress).
* [MyVisualNovelTransTools](https://github.com/julixian/MyVisualNovelTransTools) ⭐ 90 | 🐛 0 | 🌐 C++ | 📅 2026-08-03 - Large collection of translation-oriented extraction tools for many otherwise-unsupported visual novel engines.
  * Engines: LiLiM, ACTGS, Studio Polaris, AGSI, Ai5Win, AIL, Ankh, Aoi, AZ System, and others.
* [Tools](https://github.com/1F1E33-float32/Tools) ⭐ 85 | 🐛 0 | 🌐 Python | 📅 2025-10-25 - Large personal collection of extraction, unpacking, and text-cleaning tools spanning dozens of visual novel engines plus other unrelated engines/games. See also [Tools\_Boost](https://github.com/1F1E33-float32/Tools_Boost) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2025-10-31, an accelerated native module for performance-critical parts of the pure-Python project.
  * VN Engines: ADVPlayerHD, ArkEngine, ArtemisEngine, BGI, BSXScript, Black Cyc, BlackRainbow, CIRCUS (Mes), CatSystem2, DATE A LIVE engine, DXLib, Escude, Eushully, ExHIBIT, FSNr, HunX, IDEA FACTORY, Interheart, LiLiM, Liar-soft, Littlewitch, Malie, Mirai, NeXAS/NeXAS\_Unity, NekoSDK, PJADV, PRM, Propeller, RyuEngine, ShiinaRio, SiglusEngine, Talesshop, UTAGE, Xuse, YuRis, Kirikiri (krkr), Majiro; plus text-cleaning scripts for CMVS, Debonosu Works, FAVORITE, Genshin Impact/Honkai: Star Rail Chinese text, QLIE, Softpal, Will Co., AliceSoft, and minori-engine titles.
  * Standalone VN Games: Gensou Manège, Guunmong, HUNDRED LINE -Saishuu Bouei Gakuen-, Kieta Sekai to Tsuki to Shoujo, Sora no Kiseki the 1st, Soushin no Ars Magna, Steam Prison, Taimanin Yukikaze 2, VIRTUAL GIRL @ WORLD'S END, VenusBlood Lagoon, and several Yuzusoft titles (Bra-Ban!, ExE, Noble★Works).
  * Other: Telltale Games (Local single-player games), plus Unity- and Unreal Engine-based online games, and misc scripts for 2dfan/vndb metadata scraping and OggS audio stream cleanup.
* [HyoutaTools](https://github.com/AdmiralCurtiss/HyoutaTools) ⭐ 74 | 🐛 8 | 🌐 C# | 📅 2025-12-14 - .NET CLI collection of tools for packing and unpacking video game archives. Includes functions for extracting data from and reinserting data into various games.
* [clank](https://github.com/hashsploit/clank) ⭐ 59 | 🐛 24 | 🌐 Java | 📅 2022-08-30 - High-performance open-source server implementation of Sony's Medius (SCE-RT) online multiplayer protocol used by many PS2/PS3-era games, reverse engineering its network protocol and data structures.
  * Tools: See also the author's [medius-wireshark](https://github.com/hashsploit/medius-wireshark) ⭐ 4 | 🐛 2 | 🌐 Lua | 📅 2022-01-10, a Wireshark dissector for the Medius protocol.
  * Games: Ratchet & Clank: Up Your Arsenal, Jak X: Combat Racing, Killzone, Syphon Filter: Logan's Shadow, Amplitude, and other Sony-published online titles using Medius.
* [msg-tool](https://github.com/lifegpc/msg-tool) ⭐ 56 | 🐛 3 | 🌐 Rust | 📅 2026-07-29 - Rust CLI for exporting and importing visual novel scripts, images, and archives, with output to GalTransl JSON, YAML, or Gettext PO for translation workflows.
  * Engines: Artemis, BGI/Ethornell, CatSystem2, Circus, and many others (feature-gated, extensive per-engine script/archive/image support matrix).
* [asmodean-tools](https://github.com/hiroshil/asmodean-tools) ⭐ 50 | 🐛 1 | 🌐 Batchfile | 📅 2023-10-03 - Mirror of asmodean's long-running collection of archive/image extraction tools for dozens of Japanese visual novel/eroge titles and engines.
* [GameEngineTools](https://github.com/rewjx/GameEngineTools) ⭐ 44 | 🐛 3 | 🌐 C# | 📅 2022-07-27 - Tools for unpacking, editing, and repacking resources from several ADV game engines.
  * Engines/Games: Comic3, CatSystem-for-Unity, Calcite, AQUAStyle (tested on Touhou Genso Wanderer), Cadath.
* [vgio](https://github.com/joshuaskelly/vgio) ⭐ 42 | 🐛 13 | 🌐 Python | 📅 2026-02-13 - Python library for reading and writing game file formats. Supports Quake, Duke Nukem 3D, Quake II, Hexen II, HROT, and Devil Daggers (BSP, MAP, and related formats).
* [vn-packunpack](https://github.com/jpnoob/vn-packunpack) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2022-08-17 - Packers and unpackers for several visual novel file formats.
* [ReVN](https://github.com/Dir-A/ReVN) ⚠️ Archived - Visual novel engine reverse-engineering toolkit with pack editors, script text editors, and image/data (de)cryptors for the GSD, PJADV, CMVS, and Valkyria visual novel engines (archived). See also [RxCMVS](https://github.com/ZQF-ReVN/RxCMVS) ⚠️ Archived and [RxGSD](https://github.com/ZQF-ReVN/RxGSD) ⚠️ Archived, the standalone successor tools for the CMVS and GSD engines respectively.
* [VisualNoveltools](https://github.com/yy487/VisualNoveltools) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-09-04 - Actively-maintained personal grab-bag of unpacking/repacking, image, and script-extraction tools organized one folder per game/engine, with completeness varying by title.
  * Engines: BGI, AI5WIN/AI6WIN, Kirikiri, Lucifen, NeXAS, PJADV, Liar-soft/raiL-soft, RealLive, rUGP, Silky, Xuse, Yuka, AVG32, GsPack, ACTGS, ADVWIN32, AZ System, Studio e.go! (ego), NitroPlus, Leaf, and dozens of other individually-named titles.
* [libgamearchive](https://github.com/Malvineous/libgamearchive) ⭐ 26 | 🐛 2 | 🌐 C++ | 📅 2017-10-02 - Camoto C++ library and command-line utilities for examining, extracting, and editing archive/group file formats used by classic DOS games.
  * Games: Doom, Duke Nukem 3D, Blake Stone, Halloween Harry, Word Rescue, Cosmo's Cosmic Adventures, Crystal Caves, Monster Bash, God of Thunder, Jill of the Jungle, Xargon, Vinyl Goddess From Mars, and more.
* [reamberPy](https://github.com/Eve-ning/reamberPy) ⭐ 25 | 🐛 4 | 🌐 Python | 📅 2024-11-08 - Vertical scrolling rhythm game (VSRG) mapping toolbox for data extraction, manipulation, and analysis.
  * Games: osu!mania, StepMania, BMS, and partially O2Jam.
  * Features: Map I/O, format conversion, map image generation, pattern extraction.
* [gus](https://github.com/darkstar/gus) ⭐ 24 | 🐛 1 | 🌐 C# | 📅 2022-10-14 - "General Unpack Shell", a small extensible command-line tool to list, unpack, and (for some formats) repack archive/data files from games via a common syntax.
  * Games: ElSword (KOM), Dungeon Siege 1 & 3 (Tank/OAF), Falcom's Farland Symphony (PAC), Legend of Grimrock, Plants vs. Zombies, Might & Magic/World of Xeen (LOD), Nippon Ichi Software titles (NISPACK DAT), Fairy Bloom Freesia (TGP), YS Online (YSF), Ren'Py (RPA) games, and other Trinigy/Havok Vision Engine titles.
  * Formats: AFS, ARJ, CPK, GLB, PAC, YPAC (Yu-ris), ZIP, among others; see the project's `gus -ll` for the full supported-format list.
* [galgame-script-tool](https://github.com/cssxsh/galgame-script-tool) ⭐ 22 | 🐛 0 | 🌐 C# | 📅 2025-09-05 - Script text extraction/import tool covering multiple visual novel engines.
  * Engines: BGI/Ethornell, CatSystem2, Ikura GDL, Mutation, SYSTEM-ε, Tama-Soft, WILL.
* [gamearchive.js](https://github.com/camoto-project/gamearchivejs) ⭐ 21 | 🐛 0 | 🌐 JavaScript | 📅 2022-10-31 - JavaScript library for reading and writing custom archive formats used by MS-DOS games from the 1990s, with a unified API across formats.
  * Games: Alien Carnage, Bio Menace, Blake Stone, Blood, Catacomb 3-D series, Commander Keen 4-6, Cosmo's Cosmic Adventures, Crystal Caves, Dangerous Dave, Death Rally, Descent, Doom, Duke Nukem 3D, Duke Nukem II, Halloween Harry, Hocus Pocus, Lost Vikings, Monster Bash, Raptor, Redneck Rampage, Shadow Warrior, Spear of Destiny, Stargunner, Terminal Velocity, Wolfenstein 3-D, Word Rescue, and more (55+ games total).
  * Formats: BNK, RFF, gamemaps (id RLEW/Carmack), VOL, STN, exe-embedded archives, WAD, GRP (BUILD), HOG, DLT, POD, GLB, BPA, EPF, DAT (various), GXLib, LBR, and others.
* [UTPackage.js](https://github.com/bunnytrack/UTPackage.js) ⭐ 21 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-04 - JavaScript library for reading Unreal Tournament 99 package format. Compatible with other Unreal Engine 1 games including Deus Ex, Rune, Harry Potter, Clive Barker's Undying, Nerf Arena Blast, and Wheel of Time.
* [Alexandria](https://github.com/Burton-Radons/Alexandria) ⭐ 16 | 🐛 1 | 🌐 C# | 📅 2014-08-11 - .NET library collection for viewing and processing data from many classic PC games, with a plugin-oriented architecture.
  * Games: Demon's Souls, Dark Souls, Dark Souls 2; Sierra AGI adventures; SSI Gold Box RPGs (most comprehensive Gold Box decoder available); Ultima I-IX, Ultima Underworld 1-2, System Shock; Morrowind; Outcast; Albion; Arcanum; Planets Edge; Nintendo DS and Wii games; Super Famicom games; Unreal engine games.
  * Features: Unified viewer/modifier interface, script visualizer for Gold Box games, Visual Studio plugin framework.
* [porter-lib](https://github.com/dtzxporter/porter-lib) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-08-28 - Rust library for extracting 3D models, animations, and game assets across multiple games. Cross-platform (Windows, Linux, macOS).
* [miniTool](https://github.com/Chenx221/miniTool) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2025-07-04 - Collection of small standalone unpacking/decryption/patching utilities, each targeting a different unrelated Japanese visual novel/eroge title.
  * Games: Imokone - Todoketai Koigokoro (`.arc` unpacker), Shirokuro ~~Iroshoujou no Osananajimi wo Sewa Suru Koto ni Natta, Kanojo ni Naisho de~~ (`.arc` unpacker), Iris Mysteria! (DMM/FANZA `.encrypted` archive decryptor), Nukige-jima 1 & 2 Remaster (Artemis-engine CG extractor), Koi to Senkyo to Chocolate Steam release (multi-language `.dat` unpacker), Tsuki ni Yorisou Otome no Sahou 2 Steam release (`.pac` unpacker), Nie no Hakoniwa (EXFS archive extractor), VIRTUAL GIRL @ WORLD'S END (unpacker).
  * Also includes: a serial-verification patch for Triangle PIX GAME STUDIO engine games (tested on a dozen titles including the Mahou Senshi and Koushouken Hime Arc Braver series), a GUID-check patch for AdvHD.exe games, and a serial-check patch for Yu-Ris engine games.
* [modId](https://github.com/owenmpierce/modId) ⭐ 13 | 🐛 2 | 🌐 C | 📅 2023-06-24 - Tool for generating EGAGRAPH/VGAGRAPH-style graphics archive files for the 16-bit DOS games made by id Software.
* [retrocompress](https://github.com/bbitmaster/retrocompress) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-01 - Provably-optimal compressor/decompressor for the 3-bit-command/5-bit-length LZ-style compression format family shared by many 4th/5th-gen Nintendo, Capcom, Konami, and HAL Laboratory titles.
  * Games: Super Mario World, Kirby's Adventure (NES), Kirby Super Star (SNES), Super Metroid (SNES), The Legend of Zelda: A Link to the Past, Castlevania IV, Pokemon Gold/Silver, and other Capcom/Konami SNES titles using the "Konami block" variant.
  * Features: O(n) dynamic-programming shortest-path optimal parser (SA-IS suffix arrays, Kasai LCP); full repacker for Kirby's Adventure (NES) that produces a verified valid ROM.
* [UnrealXPS](https://github.com/johnzero7/UnrealXPS) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2015-08-31 - Custom file format importer for bringing XNALara/XPS model rips into Unreal Engine.
* [obm2bmp](https://github.com/lennylxx/obm2bmp) ⭐ 3 | 🐛 2 | 🌐 C++ | 📅 2015-01-10 - Converts the proprietary `.obm` image format to BMP.
  * Games: The King of Fighters i 2012, Street Fighter IV Volt, Double Dragon (iOS/Android).
* [GameArchives](https://github.com/PikminGuts92/GameArchives) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-07-19 - C# library for reading 14+ video game archive formats.
  * Formats: Ark, PSARC, PACKAGE, PFS, STFS, XDVDFS, U8. See also [maxton's fork](https://github.com/maxton/GameArchives) ⭐ 99 | 🐛 8 | 🌐 C# | 📅 2021-02-19 with FSAR support for Sing Party.
  * Games: Harmonix titles (Frequency, Amplitude, Guitar Hero series, Rock Band series 1-4, Beatles, Green Day, Lego, VR, Karaoke Revolution, Disney Fantasia),
    Konami rhythm games (DDR Universe 1-3, DDR 2010, Dance Masters), FreeStyleGames (DJ Hero series, Guitar Hero Live, Sing Party), Psychonauts, Power Gig.
* [TrbModelConverter](https://github.com/AdventureT/TrbModelConverter) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2020-05-11 - Extracts 3D model data from .trb archive format to FBX. Supports Nicktoons series, Barnyard, de Blob, and other games.
* [Mixup](https://github.com/Fabulu/Mixup) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-05 - Hand-translates console game disassembly into readable, modifiable JavaScript (not emulation), verifying each translated routine frame-by-frame against the original ROM running in an emulator.
  * Games: Batman: Return of the Joker (Game Boy, complete), Gradius (NES, all seven stages playable), DoDonPachi DaiOuJou (arcade, in progress).
* [amuse](https://github.com/AxioDL/amuse) - Real-time MIDI/SFX sequencer and alternate runtime library for games using Factor 5/Nintendo's MusyX audio engine.
  * Games: Metroid Prime series, Star Fox Adventures, Paper Mario: The Thousand Year Door (GameCube), Indiana Jones and the Infernal Machine, Star Wars Episode I, and the Rogue Squadron series.
  * Features: command-line audio-group player, SNG-to-MIDI converter, WAV song renderer, library API for engine integration, and physical/virtual MIDI keyboard support.

#### Noesis / 3ds Max / Format Script Packs

* [bartlomiejduda/Tools](https://github.com/bartlomiejduda/Tools) ⭐ 210 | 🐛 7 | 🌐 Python | 📅 2026-08-05 - Collection of tools to manage and modify files from many various games. Includes archive tools, binary templates, and format-specific utilities.
  * Games: 150+ titles including Harry Potter series, Bully, Crash Bandicoot series, Tony Hawk's Underground, Sonic 2006/Unleashed, Resident Evil 7, Silent Hill series, Just Cause, Splinter Cell, SimCity 3000, LEGO games, The Sims series, Super Mario Sunshine, Star Wars Jedi Academy, Tekken 5, Transformers, Beyond Good & Evil, and many more.
* [MidiConverters](https://github.com/ValleyBell/MidiConverters) ⭐ 145 | 🐛 7 | 🌐 C | 📅 2026-01-25 - Large collection of game-specific music sequence format to MIDI converters.
  * Games: Final Fantasy VII (PSX AKAO), Core Design Mega Drive games (Asterix and the Great Rescue and others, cdmd2mid), Cotton, Sega System 32 arcade (Sys32MidiDec), Taito Zoom arcade (TaitoZoom), OutRun (toutrun2mid), Konami Mega Drive games (konamimd2mid), Neo Geo Pocket (ngp2mid), and 30+ other proprietary/tracker sequence formats.
* [vgm-disasm](https://github.com/loveemu/vgm-disasm) ⭐ 49 | 🐛 7 | 🌐 Assembly | 📅 2026-05-25 - Disassembly collection of classic video game music drivers. Disassembles VGM (Video Game Music) files for educational and preservation purposes.
* [GameFileFormatsRE](https://github.com/LolHacksRule/GameFileFormatsRE) ⭐ 33 | 🐛 1 | 🌐 Python | 📅 2026-01-08 - Collection of Noesis scripts, binary templates, and BMS scripts for reverse-engineered game file formats across 30+ studios.
  * Studios/Games: AlphaDream (Mario & Luigi: Bowser's Inside Story, Dream Team, Paper Jam), Nintendo EAD/EPD (Zelda: Breath of the Wild, Xenoblade, Mario Kart), NDCube (Animal Crossing: Pocket Camp), RetroStudios (Donkey Kong Country Returns 3D), IntelligentSystems, Housemarque, Ubisoft (UbiArt, LyN, SnowDrop, Just Dance engines), EA Redwood Shores, Gameloft, PopCap, Rovio, ZenStudios, VicariousVisions, BightGames, ChimeraEntertainment, DisneyMobile, Exient, Funlabs, Hasbro, PlayFirst, PlayMechanix, TinyCo/JamCity, Transmension, VetaSoft, Xeen, and more.
* [RTB-3DSMax-Scripts](https://github.com/RandomTBush/RTB-3DSMax-Scripts) ⭐ 32 | 🐛 9 | 🌐 MAXScript | 📅 2026-07-07 - Comprehensive collection of 3ds Max scripts for importing models from dozens of games and engines.
  * Games: Pokémon (Switch/3DS), Zelda (BOTW/TOTK/Wind Waker HD), Mario (Odyssey/Kart 8/3D World), Splatoon (1-3), Hyperdimension Neptunia series, Crash Bandicoot N. Sane Trilogy, Sonic (Unleashed/Riders), Telltale Games (Walking Dead/Batman), and many more.
  * Highlights: Support for ISM2, IGZ, MDL, D3DMesh, and Nintendo BFRES/BCH formats across PS1, PS3, Wii, Wii U, and Switch.
* [gameformats](https://github.com/dstien/gameformats) ⭐ 30 | 🐛 1 | 🌐 C++ | 📅 2023-06-29 - Tools and reverse-engineered specifications for game file formats including Midtown Madness 3 DICE textures, Stunts resource editor and data unpacker.
* [Murugo/Misc-Game-Research](https://github.com/Murugo/Misc-Game-Research) ⭐ 28 | 🐛 5 | 🌐 Python | 📅 2026-02-18 - Research artifacts and tools for various games.
  * Games: Vib-Ribbon (PS1), Gitaroo Man (PS2), Silent Hill 2 & 3 (PS2), Kingdom Hearts series (PS2), Rule of Rose (PS2), Musashi: Samurai Legend (PS2).
* [EdnessP/scripts](https://github.com/EdnessP/scripts) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-06-18 - Collection of scripts for various game file formats.
  * Games: Bully series, Burnout series (1, 2, 3, Legends, CRASH!), Call of Duty: Finest Hour, Jak & Daxter series (1, II, 3, X), Midnight Club series (2, 3), Saints Row series (2, Undercover), The Sims series (Bustin' Out, Urbz, 2, Pets, Castaway), The Simpsons Game, Tomb Raider (Wii), Need for Speed: Shift (PSP), Activision/Atari Anthology, Adventure Time, Bomberman Act:Zero, Big Rigs, Castle Strike, Driver: San Francisco, Epic Mickey, Exit, Freaky Flyers, Ready 2 Rumble Boxing, SpongeBob's Surf & Skate Roadtrip, Strike Suit Zero/Infinity, Yakuza 1 & 2 (PS2), and more.
* [reconv](https://github.com/0xDC00/reconv) ⭐ 12 | 🐛 2 | 🌐 C# | 📅 2022-08-29 - Extractor/repacker library for localization-focused modding, despite a minimal README covering only a fraction of its actual scope.
  * Games: The Evil Within 2, Drakengard 2, Catherine, Assassin's Creed II, Shadow of the Tomb Raider, NieR:Automata, Final Fantasy XV, God of War: Ghost of Sparta, Zero/Project Zero 2, and the PJADV visual novel engine.
  * Formats: MSBT text, Nintendo LZ compression, and various per-game archive/text formats.
* [dragon\_noesis](https://github.com/neptuwunium/dragon_noesis) ⚠️ Archived - Collection of Noesis plugins for various game formats including Dragon engine.
* [Noesis Plugins](https://richwhitehouse.com/index.php?content=inc_projects.php\&showproject=91) - Community plugin collections extending Noesis support to hundreds more games.
  * See [6 major plugin collections](https://richwhitehouse.com/index.php?content=inc_projects.php#prjmp91) including Tales series, Midnight Club 2, Visceral Games titles, and many more formats.

#### ROM/Save Extraction, Detection & Modding

* [Zygisk-Il2CppDumper](https://github.com/Perfare/Zygisk-Il2CppDumper) ⭐ 3,282 | 🐛 173 | 🌐 C | 📅 2024-08-09 - Dumps IL2Cpp metadata from Unity games running on Android via Zygisk, enabling reverse-engineering of obfuscated game code and data.
* [Archipelago](https://github.com/ArchipelagoMW/Archipelago) ⭐ 1,639 | 🐛 598 | 🌐 Python | 📅 2026-09-02 - Multi-game item randomizer and server, generating patched ROMs/mods and syncing item checks across game worlds.
  * Games: A Hat in Time, A Link to the Past, A Short Hike, Aquaria, Blasphemous, Bomb Rush Cyberfunk, Bumper Stickers, Castlevania - Circle of the Moon, Castlevania 64, Celeste 64, Celeste (Open World), ChecksFinder, Choo-Choo Charles, Civilization VI, Dark Souls III, DLCQuest, DOOM 1993, DOOM II, EarthBound, Factorio, Faxanadu, Final Fantasy, Final Fantasy Mystic Quest, Gauntlet Legends, Heretic, Hollow Knight, Hylics 2, Inscryption, Jak and Daxter, Kingdom Hearts, Kingdom Hearts 2, Kirby's Dream Land 3, Landstalker - The Treasures of King Nole, Lingo, Lufia II Ancient Cave, Mario & Luigi Superstar Saga, Mega Man 2, Mega Man 3, MegaMan Battle Network 3, Meritous, Muse Dash, Noita, Ocarina of Time, Old School Runescape, Overcooked! 2, Paint, Pokemon Emerald, Pokemon Red and Blue, Raft, Risk of Rain 2, Satisfactory, Saving Princess, Secret of Evermore, Shivers, SMZ3, Sonic Adventure 2 Battle, Starcraft 2, Subnautica, Super Mario 64, Super Mario Land 2, Super Mario World, Super Metroid, Terraria, The Legend of Zelda, The Messenger, The Wind Waker, The Witness, Timespinner, TUNIC, Undertale, VVVVVV, Wargroove, Yacht Dice, Yoshi's Island, Yu-Gi-Oh! 2006, Zillion.
* [RomPatcher.js](https://github.com/marcrobledo/RomPatcher.js) ⭐ 1,188 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-28 - JavaScript ROM patcher supporting IPS, BPS, UPS, APS, PPF, and other binary patch formats across many console ROM formats (used for Mario, Pokemon, Smash, and countless other ROM hacks).
* [XGP-save-extractor](https://github.com/Z1ni/XGP-save-extractor) ⭐ 974 | 🐛 261 | 🌐 Python | 📅 2025-10-09 - Python script that extracts/backs up savefiles from Xbox Game Pass for PC (UWP/WGS container) games, producing a ZIP per save that can usually be dropped straight into the Steam/Epic version's save directory.
  * Games: 40+ titles including Forza Horizon 5, Starfield, Palworld, Persona 5 Royal/Tactica, Lies of P, Hades, Doom Eternal, Final Fantasy XV, Yakuza 0, Manor Lords, and more.
* [apollo-ps4](https://github.com/bucanero/apollo-ps4) ⭐ 631 | 🐛 16 | 🌐 C | 📅 2026-05-02 - Apollo Save Tool for PS4, decrypting and editing save data for a wide range of games. See also [apollo-ps5](https://github.com/bucanero/apollo-ps5) ⭐ 33 | 🐛 1 | 📅 2026-05-22 for PS5 and [apollo-saves](https://github.com/bucanero/apollo-saves) ⭐ 167 | 🐛 15 | 🌐 C | 📅 2026-08-24, the online save-game database backing the Apollo Save Tool family (PS3/PS4/PS5).
* [apollo-ps3](https://github.com/bucanero/apollo-ps3) ⭐ 594 | 🐛 21 | 🌐 C | 📅 2026-05-02 - Apollo Save Tool for PS3, decrypting and editing save data for a wide range of games. See also the author's [save-decrypters](https://github.com/bucanero/save-decrypters) ⭐ 131 | 🐛 5 | 🌐 C | 📅 2026-07-17 collection above.
* [awesome-n64-development](https://github.com/command-tab/awesome-n64-development) ⭐ 576 | 🐛 2 | 🌐 Python | 📅 2026-07-12 - Curated list of Nintendo 64 development and reverse-engineering resources including decompilation projects (SM64, Zelda OOT, Paper Mario), ROM analysis tools (N64LoaderWV for Ghidra), disassemblers, and asset extraction utilities.
* [N64-Tools](https://github.com/jombo23/N64-Tools) ⭐ 333 | 🐛 39 | 🌐 C++ | 📅 2026-07-26 - Collection of N64 romhacking tools spanning multiple unrelated games.
  * Games: GoldenEye 007 (asset decompressor, ObjToAn8 model/animation converter), Eternal Darkness (decompressor), Conker's Bad Fur Day (font ripper), Super Smash Bros (file injector), plus general N64 utilities.
  * Tools: `GEDecompressor` (Blitz/Bolt/BOFS format decoders), `objtoan8`, `N64MidiTool`, `N64SoundbankTool`, `N64SoundListTool`, MIPS disassembler, and Analog Controls Mod xdelta patches for various games.
* [randovania](https://github.com/randovania/randovania) ⭐ 217 | 🐛 323 | 🌐 Python | 📅 2026-09-05 - A randomizer platform for a multitude of games, generating patched game files with randomized item/location placement.
* [game-extraction-toolbox](https://github.com/shawngmc/game-extraction-toolbox) ⭐ 135 | 🐛 51 | 🌐 Python | 📅 2025-05-15 - Python CLI tools for extracting ROMs from game rereleases and investigating game files.
* [save-decrypters](https://github.com/bucanero/save-decrypters) ⭐ 131 | 🐛 5 | 🌐 C | 📅 2026-07-17 - Collection of custom save-game decrypters and checksum fixers for PS3, PSP, and PS4.
  * Games: GTA5, The Last of Us, Uncharted series, Metal Gear Solid series, Resident Evil series, Final Fantasy XIII series, and many more.
* [XblContainerReader](https://github.com/LukeFZ/XblContainerReader) ⭐ 48 | 🐛 1 | 🌐 C# | 📅 2024-01-24 - CLI tool and library (LibXblContainer) to parse and interact with UWP/Xbox Game Pass save game containers (`containers.index`), covering many different games that use this container format.
* [CrateModLoader](https://github.com/TheBetaM/CrateModLoader) ⭐ 47 | 🐛 12 | 🌐 C# | 📅 2022-07-02 - Mod loader with game-specific format detection, extraction, modification, and rebuilding across multiple games.
* [ModAPI](https://github.com/FluffyFishGames/ModAPI) ⭐ 24 | 🐛 7 | 🌐 C# | 📅 2026-08-10 - Desktop mod management tool for managed-code (Mono) Unity survival games, handling per-game mod loading, dependency resolution, and injection.
  * Games: The Forest, Subnautica, RAFT, Escape The Pacific, Green Hell.
* [arcadeutils](https://github.com/DragonMinded/arcadeutils) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-05-01 - Python utilities for working with various arcade binaries, including generic binary patching and compression helpers used across several arcade-game modding projects.
* [FileDetectionRuleSets](https://github.com/neptuwunium/FileDetectionRuleSets) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2025-11-19 - Rule sets for file format detection across various tools and platforms.
  * Supports extracting ROMs from collections like Capcom Arcade Stadium, Street Fighter 30th Anniversary Collection, Mega Man Legacy Collections, SNK 40th Anniversary Collection, and many more.
* [TSERipper](https://github.com/BLiNXthetimesweeperGOD/TSERipper) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-06-15 - Asset ripping tool for Torus Games handheld titles. Converts sprites, maps, and assets from GBA, Nintendo DS, Leapster, and N-Gage games into usable formats.
* [AmazeDSExtractor](https://github.com/RayCarrot/AmazeDSExtractor) ⭐ 1 | 🐛 1 | 🌐 C# | 📅 2025-08-18 - Archive extractor for 20+ Nintendo DS games by Amaze Entertainment.
  * Games: Spyro: Shadow Legacy, Ice Age 2, The Legend of Spyro series, and others

#### Emulators & TAS Tools

* [BizHawk](https://github.com/TASEmulators/BizHawk) ⭐ 2,747 | 🐛 804 | 🌐 C# | 📅 2026-09-03 - Multi-system emulator built for tool-assisted speedrunning, with full rerecording, RAM search/watch, Lua scripting, and debugging tools across 20+ systems (NES, SNES, Genesis, Game Boy/GBA, N64, PS1, and more).
* [ld-decode](https://github.com/happycube/ld-decode) ⭐ 411 | 🐛 27 | 🌐 Jupyter Notebook | 📅 2026-09-03 - Software-defined LaserDisc RF decoder, used to digitize and preserve laserdisc arcade games for emulators such as hypseus-singe/DICE.
* [hypseus-singe](https://github.com/DirtBagXon/hypseus-singe) ⭐ 235 | 🐛 1 | 🌐 C | 📅 2026-08-30 - SDL3-based continuation of Daphne/Singe, emulating laserdisc arcade games by reading their original laserdisc video/ROM data. Companion [hypseus\_singe\_data](https://github.com/DirtBagXon/hypseus_singe_data) ⭐ 50 | 🐛 1 | 📅 2026-08-23 package provides the LUA game-definition scripts for dozens of supported titles (Dragon's Lair, Space Ace, Cliff Hanger, M.A.C.H. 3, and more).
* [ScriptHawk](https://github.com/Isotarge/ScriptHawk) ⭐ 96 | 🐛 5 | 🌐 Lua | 📅 2025-02-21 - Collection of BizHawk Lua scripts for RAM watching, memory manipulation, and TAS tooling across dozens of games.
* [GBAHawk](https://github.com/alyosha-tas/GBAHawk) ⭐ 21 | 🐛 12 | 🌐 C# | 📅 2026-09-01 - Game Boy Advance emulator core fork of BizHawk, focused on hardware-accurate behavior verified against real console tests.
* [dice-libretro](https://github.com/mittonk/dice-libretro) ⭐ 9 | 🐛 1 | 🌐 C | 📅 2026-08-21 - Libretro/RetroArch port of DICE (Discrete Integrated Circuit Emulator), emulating early arcade systems built from discrete logic components with no CPU.
* [EggmansLaserForge](https://github.com/Eggmansworld/EggmansLaserForge) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2026-08-26 - Authoring tool for building playable laserdisc games for Hypseus Singe, without hand-editing LUA scripts or frame numbers.
* [Hypdroid](https://github.com/rhakka303/Hypdroid) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-09-04 - Standalone Android port of Hypseus Singe with a native gamepad-first game launcher.
* [actionmax-pi](https://github.com/DirtBagXon/actionmax-pi) ⚠️ Archived - Singe implementation of the ActionMax VHS-based arcade system for 32-bit Raspberry Pi and other SBCs.

#### Franchise & Studio Toolkits

* [savegame-editors](https://github.com/marcrobledo/savegame-editors) ⭐ 1,314 | 🐛 134 | 🌐 JavaScript | 📅 2026-08-21 - Compilation of browser-based (HTML5) console savegame editors.
  * Games: The Legend of Zelda (Tears of the Kingdom, Breath of the Wild), Super Smash Bros. Ultimate, Hyrule Warriors (Wii U, Age of Calamity), Kid Icarus: Uprising, Final Fantasy Explorers, Mario Kart 7, Kirby (Super Kirby Clash, Team Kirby Clash Deluxe, Kirby's Blowout Blast), Picross 3D Round 2, Sushi Striker, Pokémon Picross, Pokémon Shuffle, Rhythm Paradise Megamix, StreetPass Mii Plaza.
* [Smithbox](https://github.com/vawser/Smithbox) ⭐ 711 | 🐛 3 | 🌐 C# | 📅 2026-09-02 - Comprehensive modding toolkit for modern FromSoftware games.
  * Games: Elden Ring, Elden Ring: Nightreign, Armored Core VI, Sekiro, Dark Souls 1-3, Bloodborne, Demon's Souls.
  * Features: Map editor, model editor (FLVER), param editor, text editor, graphics param editor (GPARAM), material editor (MTD/MATBIN), texture viewer, file browser.
* [libultraship](https://github.com/Kenix3/libultraship) ⭐ 342 | 🐛 155 | 🌐 C++ | 📅 2026-09-02 - Shared reimplementation of libultra (the Nintendo 64 SDK) and the O2R asset packaging system powering the Ship of Harkinian family of N64 decompilation PC ports.
  * Games: The Legend of Zelda: Ocarina of Time (Shipwright), The Legend of Zelda: Majora's Mask (2ship2harkinian), Star Fox 64 (Starship), Mario Kart 64 (SpaghettiKart).
* [WitchyBND](https://github.com/ividyon/WitchyBND) ⭐ 261 | 🐛 7 | 🌐 C# | 📅 2026-07-06 - Unpacker/repacker for FromSoftware game formats.
  * Games: Dark Souls 1-3, Bloodborne, Sekiro, Elden Ring, Armored Core VI
  * Formats: BND3, BND4, FFXBND, DCX, BXF3, BXF4, FMG, GPARAM, LUAGNL, LUAINFO, TPF, FXR1, FXR3, MATBIN
* [DSLuaDecompiler](https://github.com/katalash/DSLuaDecompiler) ⭐ 159 | 🐛 2 | 🌐 C# | 📅 2025-05-10 - Decompiler for Lua/HavokScript bytecode in Dark Souls, DS3, Bloodborne, and Sekiro. Actively maintained successor to garyttierney/DSLuaDecompiler.
* [FrogLord](https://github.com/Kneesnap/FrogLord) ⭐ 144 | 🐛 16 | 🌐 Java | 📅 2026-09-04 - Modding suite supporting level creation, 3D model import, unused-content viewing, and general file editing.
  * Games: Frogger: He's Back, Frogger: The Great Quest, Frogger Beyond, Frogger Rescue, Frogger Ancient Shadow, Beast Wars: Transformers, C-12: Final Resistance, MediEvil, MediEvil II, Moon Warrior.
* [StringReloads](https://github.com/marcussacana/StringReloads) ⭐ 125 | 🐛 6 | 🌐 C# | 📅 2026-09-05 - Universal tool for injecting translated strings into any game via low-level assembly patching, without needing to reverse the game's own package/encryption format. Supports non-ASCII characters, auto word-wrap, and font/glyph-spacing adjustments. See also [LSTXLSTool](https://github.com/marcussacana/LSTXLSTool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2021-03-30 for batch-exporting/importing its LST translation files to/from a single XLSX spreadsheet.
* [DKDave/Scripts](https://github.com/DKDave/Scripts) ⭐ 58 | 🐛 0 | 🌐 Python | 📅 2026-05-24 - Collection of 250+ QuickBMS, Python, and Noesis scripts for extracting archives, textures, and audio from games across PC, PS1-PS4, PSP, Xbox/Xbox 360, GameCube, Wii, Switch, Nintendo DS, Dreamcast, Saturn, and mobile platforms; corrected/updated versions of scripts previously shared on Xentax and Zenhax.
  * Games: Metal Gear Solid series, Silent Hill 3 & Origins, Devil May Cry 4, Resident Evil 0 & 2, Jak & Daxter, Kingdom Hearts (Birth by Sleep, Remix), Prince of Persia: Sands of Time, Mass Effect 1 & 2, Control, Alan Wake 2, Ghost of Tsushima, Star Wars: The Force Unleashed, F-Zero GX, Dishonored 2, Splatoon 3, Tony Hawk's Pro Skater, and many more.
* [EditorCore](https://github.com/exelix11/EditorCore) ⚠️ Archived - Archived, proof-of-concept extensible 3D level editor for Nintendo Switch games with a plugin architecture.
  * Features: 3D level editing with search, drag, raycast, and undo; path rendering; per-game plugin extensions (see [OdysseyEditor](https://github.com/exelix11/OdysseyEditor) ⚠️ Archived and [EditorCore-Examples](https://github.com/exelix11/EditorCore-Examples) ⚠️ Archived).
  * Games: Super Mario Odyssey, Mario Kart 8 Deluxe, Captain Toad: Treasure Tracker.
* [Paramdex](https://github.com/soulsmods/Paramdex) ⭐ 44 | 🐛 1 | 📅 2026-03-06 - Parameter file format specifications for FromSoftware games (DS1-3, Bloodborne, Sekiro, Demon's Souls, Elden Ring, Armored Core VI). Actively maintained successor to garyttierney/Paramdex.
* [Nuxe](https://github.com/JKAnderson/Nuxe) ⭐ 42 | 🐛 0 | 🌐 C# | 📅 2026-08-29 - Game data unpacker for FromSoftware titles (Dark Souls, Elden Ring, Sekiro).
* [Supercell-Flat-Converter](https://github.com/Daniil-SV/Supercell-Flat-Converter) ⚠️ Archived - Converts Supercell game assets between optimized Flatbuffer format and standard glTF. Supports Brawl Stars, Clash of Clans, Clash Royale, Clash Mini, and Squad Busters.
* [SC2FLA-FOSS-Edition](https://github.com/GenericName1911/SC2FLA-FOSS-Edition) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2025-12-29 - Converts Supercell .sc asset format (2D sprites/animations) to Adobe Animate .fla files. Supports Brawl Stars, Clash of Clans, Clash Royale, Squad Busters with SCTX texture support and spritesheet generation.
* [mapfile\_parser](https://github.com/Decompollaborate/mapfile_parser) ⭐ 30 | 🐛 0 | 🌐 Rust | 📅 2026-08-22 - Library for parsing linker map files, used across multiple N64 decompilation projects to assist with matching original compiled code during reverse engineering.
* [SCTX Converter](https://github.com/Daniil-SV/SCTX-Converter) ⭐ 27 | 🐛 0 | 🌐 C++ | 📅 2026-05-11 - Converts Supercell Texture (.sctx) files to PNG with metadata extraction in JSON format. Supports texture streaming and mip-mapping data.
* [ResourceDragon](https://github.com/wearrrrr/ResourceDragon) ⭐ 18 | 🐛 4 | 🌐 C++ | 📅 2026-01-18 - Extensible viewer and extractor for proprietary archive formats, built with ImGui/SDL3/OpenGL.
  * Formats: HSP, NitroPlus MPK, PFS, Sonic Adventure PAK, Touhou 6 DAT, XP3, ZIP.
  * Features: Previews images, GIFs, audio, and archives; parses ELF and PE files; Squirrel scripting support for custom formats; native plugin loading (.dll/.so).
* [BinderKeys](https://github.com/JKAnderson/BinderKeys) ⭐ 14 | 🐛 0 | 📅 2026-08-28 - Encryption keys and path dictionaries for unpacking FromSoftware BinderLight container files across multiple games.
* [Lunacy](https://github.com/NefariousTechSupport/Lunacy) ⭐ 12 | 🐛 2 | 🌐 C# | 📅 2024-02-04 - Level editor and asset extractor for Ratchet & Clank and Resistance (Insomniac Games PS3), parsing main.dat and assetlookup.dat game files.
* [fsvfs](https://github.com/Dasaav-dsv/fsvfs) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-09-03 - Cross-platform userspace filesystem for mounting FromSoftware game archives (Dark Souls, Elden Ring, Armored Core).
* [Smithbox-For-Linux](https://github.com/SrDeTs/Smithbox-For-Linux) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2026-07-31 - Linux port of Smithbox (the FromSoftware modding toolkit above), with Linux-specific packaging (deb/rpm/pacman/AppImage/Flatpak), automated Oodle setup via linoodle, Linux Steam library detection, and Vulkan/OpenGL rendering; Windows-only features like live param reload and NavGen are unavailable.
* [BOLTextract](https://github.com/heinermann/BOLTextract) ⭐ 6 | 🐛 1 | 🌐 C++ | 📅 2026-08-10 - Extractor for Mass Media Games' BOLT archive format, unpacking embedded files from ROMs/binaries across the studio's many console ports.
  * Games: Mystic Midway: Rest in Pieces, Voyeur, 3-D TableSports, The Game of Life, Bassmasters 2000, Namco Museum, Ms. Pac-Man: Maze Madness, Power Rangers: Lightspeed Rescue, Starcraft 64, Pac-Man Collection, Shrek Super Party, Blackthorne, Rock n' Roll Racing, The Lost Vikings.
* [FormatX](https://github.com/Force67/FormatX) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2020-05-11 - Ever-evolving collection of tools for extracting various game file formats.
  * Games: Control, Mafia III, The Binding of Isaac: Rebirth, Tomb Raider, Toy Soldiers.
* [Test-Drive-Off-Road-3-Model-Extractor](https://github.com/ExIfDev/Test-Drive-Off-Road-3-Model-Extractor) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2025-05-06 - Extracts and converts models from Test Drive: Off-Road 3.
* [FC.LPKG.Tool](https://github.com/Ekey/FC.LPKG.Tool) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-05-24 - Extracts LPKG archive format from FURYU Corporation games including Cardfight Vanguard, MONARK, and Mushoku Tensei.
* [mhpf-tools](https://github.com/christorrella/mhpf-tools) ⭐ 3 | 🐛 2 | 🌐 Python | 📅 2021-04-23 - Pack/unpack tool for the Melbourne House Pack File format (.PCK) used in Test Drive Unlimited (PSP/PS2) resource archives.
* [Test-Drive-5-Mod-Tools](https://github.com/Dummiesman/Test-Drive-5-Mod-Tools) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-12-30 - Modding tools for Test Drive series. Supports level and object imports for Test Drive 4, 5, 6, and Off-Road 3.
* [SWERY-Localization-Tool](https://github.com/LittleBitUA/SWERY-Localization-Tool) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-27 - Ukrainian-localization editor for five Hidetaka Suehiro (SWERY)/White Owls games, handling each game's archive/text formats.
  * Games: Deadly Premonition, Deadly Premonition 2, The Good Life, Hotel Barcelona, THE MISSING.
* [fish-tools](https://github.com/christorrella/fish-tools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-04-15 - Unpacking script for the Melbourne House "FISH" Tone Library file format used in Test Drive Unlimited (PSP).
* [Project EGG Tools](https://github.com/Eggmansworld/Project_EGG_Tools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-04-03 - GUI toolkit for preserving Project EGG (a Japanese retro PC game distribution service covering PC-8801, PC-9801, MSX, MSX2, X1, FM-7, Mega Drive, PC Engine, and more) downloads.
  * Features: Fetches raw .bin container files from the service, extracts them via a bundled QuickBMS script, packages/repackages archives, romanizes filenames, and generates No-Intro-compatible DAT files.
* [Di-Gi-Charat-Fantasy-Tool](https://github.com/gopicolo/Di-Gi-Charat-Fantasy-Tool) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-07-22 - Text extraction/editing/reinsertion tool for Di Gi Charat Fantasy. The same author (gopicolo) has released matching text tools for several other unrelated Japanese visual novels/galgames: [Shoujo Kakumei Utena](https://github.com/gopicolo/Shoujo-Kakumei-Utena-Tool) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-08-19 (Sega Saturn), [Eiyuu Shigan - Gal Act Heroism](https://github.com/gopicolo/Eiyuu-Shigan-Tool) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-07-31 (Sega Saturn), [Nanatsuiro★Drops](https://github.com/gopicolo/Nanatsuiro-Drops-Tool) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-07-17, and [Papa no Iu Koto o Kikinasai!](https://github.com/gopicolo/Game-demo-Papa-no-Iu-Koto-o-Kikinasai-Tool) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-07-19 (PSP).

## ⚙️ Engines

*Tools specific to widespread third-party game engines.*

### GameMaker

* [UndertaleModTool](https://github.com/UnderminersTeam/UndertaleModTool) ⭐ 2,034 | 🐛 334 | 🌐 C# | 📅 2026-09-03 - Tool for modding/decompiling GameMaker games.
* [OpenGMK](https://github.com/OpenGMK/OpenGMK) ⭐ 405 | 🐛 31 | 🌐 Rust | 📅 2026-07-16 - Rewrite of the GameMaker Classic (8.x) engine runners with additional tooling, loading and executing original .gmk-derived game data.
* [cinnamon](https://github.com/Project-Sunshine-Native/cinnamon) ⭐ 390 | 🐛 1 | 🌐 C | 📅 2026-09-03 - GameMaker runtime reimplementation ('Cinnamon') that loads original compiled GameMaker game data, in the tradition of phosphorvm and OpenGMK.
* [GM8Decompiler](https://github.com/OpenGMK/GM8Decompiler) ⭐ 200 | 🐛 10 | 📅 2024-02-12 - Decompiler for GameMaker 8.x executables, recovering the original game's assets and code from compiled `.exe` files.
* [LateralGM](https://github.com/IsmAvatar/LateralGM) ⭐ 114 | 🐛 7 | 🌐 Java | 📅 2024-10-03 - Free Game Maker source file editor.
* [UndertaleTools](https://github.com/fjay69/UndertaleTools) ⭐ 92 | 🐛 7 | 🌐 C# | 📅 2023-08-02 - GameMaker data.win unpacker/packer.
* [Butterscotch](https://github.com/efimandreev0/Butterscotch) ⭐ 67 | 🐛 31 | 🌐 C | 📅 2026-08-04 - GameMaker runtime reimplementation that loads original compiled GameMaker game data, in the tradition of phosphorvm and OpenGMK.
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

* [halflife](https://github.com/ValveSoftware/halflife) ⭐ 4,363 | 🐛 2,124 | 🌐 C++ | 📅 2024-10-02 - Valve's official Half-Life 1 SDK source release, containing the client/server game-logic DLL source that defines GoldSrc's original data formats.
* [noclip.website (Source Engine)](https://github.com/magcius/noclip.website/tree/main/src/SourceEngine) ⭐ 4,251 | 🐛 86 | 🌐 TypeScript | 📅 2026-08-26 - In-browser Source engine map viewer supporting Counter-Strike: Source, Day of Defeat: Source, Half-Life 2, Half-Life 2: Deathmatch, Half-Life 2: Lost Coast, Half-Life 2: Episode 1, Half-Life 2: Episode 2, Team Fortress 2, Portal, Portal 2, Counter-Strike: Global Offensive, Left 4 Dead 2, The Stanley Parable, Infra, Neo Tokyo, and Estranged: Act I.
* [noclip.website (GoldSrc)](https://github.com/magcius/noclip.website/tree/main/src/GoldSrc) ⭐ 4,251 | 🐛 86 | 🌐 TypeScript | 📅 2026-08-26 - In-browser GoldSrc map viewer supporting Half-Life, Counter-Strike, Team Fortress Classic, and Day of Defeat.
* [xash3d-fwgs](https://github.com/FWGS/xash3d-fwgs) ⭐ 2,759 | 🐛 445 | 🌐 C | 📅 2026-09-04 - Cross-platform reimplementation of the GoldSrc engine, loading original Half-Life BSP/WAD/MDL game data. Actively maintained; companion to hlsdk-portable.
* [ValveResourceFormat](https://github.com/ValveResourceFormat/ValveResourceFormat) ⭐ 2,413 | 🐛 68 | 🌐 C# | 📅 2026-09-03 - Source 2 Viewer is a powerful tool that allows you to browse VPK archives, view, extract, and decompile Source 2 assets, including maps, models, materials, textures, sounds, and more. Also includes C# library for reading and writing Valve Source engine resource files.
* [source-engine](https://github.com/nillerusr/source-engine) ⭐ 2,221 | 🐛 130 | 🌐 C++ | 📅 2025-11-25 - Modified Source engine (2017) developed by Valve and leaked in 2020. Not for commercial purposes.
* [Kisak-Strike](https://github.com/SwagSoftware/Kisak-Strike) ⭐ 1,212 | 🐛 27 | 🌐 C++ | 📅 2025-07-25 - Open-source, fully buildable CS:GO port on Source 1; requires original game assets.
* [ReHLDS](https://github.com/rehlds/ReHLDS) ⭐ 850 | 🐛 305 | 🌐 C++ | 📅 2026-08-27 - Reverse-engineered, enhanced Half-Life Dedicated Server (HLDS) engine with bug fixes, security patches, and optimizations; GoldSrc engine companion to ReGameDLL\_CS above.
* [Crowbar](https://github.com/ZeqMacaw/Crowbar) ⭐ 821 | 🐛 46 | 🌐 Visual Basic .NET | 📅 2026-08-08 - All-in-one GoldSource and Source Engine modding tool: decompile/compile MDL model files, unpack game packages, and publish addons to Steam Workshop. See also [Crowbar-Command-Line](https://github.com/UltraTechX/Crowbar-Command-Line) ⭐ 23 | 🐛 1 | 🌐 Visual Basic .NET | 📅 2020-06-26, a command-line build of Crowbar's model decompiler for automation and integration into other tools/pipelines.
* [ReGameDLL\_CS](https://github.com/rehlds/ReGameDLL_CS) ⭐ 779 | 🐛 130 | 🌐 C++ | 📅 2026-08-27 - Enhanced, cross-platform server-side GameDLL reimplementation for Counter-Strike 1.6 and Condition Zero, a GoldSrc-format companion to ReHLDS.
  * See also [FWGS's fork](https://github.com/FWGS/regamedll) ⚠️ Archived.
* [awpy](https://github.com/pnxenopoulos/awpy) ⭐ 610 | 🐛 29 | 🌐 Python | 📅 2026-09-03 - Python library for parsing and analyzing Counter-Strike 2 .dem demo files (via a Rust demoparser backend) and CS2 .nav navigation-mesh files, exposing tick-level player/event data as dataframes.
* [halflife-updated](https://github.com/twhl-community/halflife-updated) ⭐ 487 | 🐛 22 | 🌐 C++ | 📅 2026-08-02 - TWHL community-maintained, modernized fork of Valve's Half-Life 1 SDK with bug fixes and cross-platform build support.
* [hlsdk-portable](https://github.com/FWGS/hlsdk-portable) ⭐ 401 | 🐛 49 | 🌐 C++ | 📅 2026-08-27 - Cross-platform, actively maintained continuation of the Half-Life SDK for GoldSource and Xash3D, used to build original HL1 mod DLLs on modern OSes.
* [freehl](https://github.com/eukara/freehl) ⭐ 320 | 🐛 10 | 🌐 QuakeC | 📅 2025-11-12 - Clean-room reimplementation of Half-Life and Half-Life: Deathmatch in QuakeC, reading original GoldSrc game data. The same author maintains similar clean-room reimplementations of other GoldSrc-era mod SDKs (freecs for Counter-Strike 1.5, freesci for Science and Industry, freegunman for Gunman Chronicles, freehunger for They Hunger, freegearbox for Opposing Force, freetfc for Team Fortress Classic, freepoke646 for Poke646).
* [GameTracking (SteamDatabase)](https://github.com/SteamDatabase/GameTracking) ⭐ 303 | 🐛 0 | 🌐 Shell | 📅 2026-08-17 - Automated CI system that dumps Source 2 network protobufs, entity schemas, ConVars, and console commands from official Steam depot builds whenever a tracked game updates, useful for demo-parsing and protocol reverse engineering.
  * Per-game repos: [GameTracking-CS2](https://github.com/SteamTracking/GameTracking-CS2) ⭐ 944 | 🐛 0 | 🌐 Slang | 📅 2026-08-28, [GameTracking-Deadlock](https://github.com/SteamTracking/GameTracking-Deadlock) ⭐ 71 | 🐛 0 | 🌐 C++ | 📅 2026-08-22, [GameTracking-HalfLifeAlyx](https://github.com/SteamTracking/GameTracking-HalfLifeAlyx) ⭐ 24 | 🐛 0 | 🌐 CSS | 📅 2025-08-19.
* [MetaHookSv](https://github.com/hzqst/MetaHookSv) ⭐ 248 | 🐛 36 | 🌐 C++ | 📅 2026-08-30 - Port of MetaHook to SvEngine (GoldSrc as modified by the Sven Co-op team), a client-side modding framework for Sven Co-op and other GoldSrc-based games.
* [CSMoE](https://github.com/MoeMod/CSMoE) ⭐ 233 | 🐛 32 | 🌐 C++ | 📅 2024-05-14 - "Counter-Strike Mobile-oriented Edition", a cross-platform (Windows, Linux, Android, iOS, UWP) client/engine built on Xash3D that loads the original purchased Counter-Strike 1.6/Half-Life GoldSrc game data to restore CSO/CSN:Z-style gameplay (bots, zombie modes, custom HUD).
* [PrimeXT](https://github.com/SNMetamorph/PrimeXT) ⭐ 172 | 🐛 61 | 🌐 C++ | 📅 2026-08-23 - Modernized toolkit/engine extension for the Xash3D FWGS engine (a GoldSrc reimplementation), based on XashXT and Spirit of Half-Life, adding enhanced graphics and physics for mod-makers.
* [HalfMapper](https://github.com/gzalo/HalfMapper) ⭐ 164 | 🐛 4 | 🌐 C++ | 📅 2021-09-11 - Renderer that loads and displays all Half-Life maps simultaneously, exploring the Black Mesa Research Facility by parsing the game's original BSP map data.
* [vitaXash3D](https://github.com/fgsfdsfgs/vitaXash3D) ⭐ 161 | 🐛 33 | 🌐 C | 📅 2023-06-14 - PS Vita port of Xash3D-FWGS, loading original GoldSrc BSP/WAD/MDL game data (Half-Life, Counter-Strike, and other GoldSrc titles) natively on the Vita.
* [SourceUtils](https://github.com/Metapyziks/SourceUtils) ⭐ 144 | 🐛 37 | 🌐 C# | 📅 2026-01-23 - Source Engine file format exporting toolkit with a WebGL-based map viewer, converting BSP maps and their assets for in-browser rendering.
* [nuclide](https://github.com/VeraVisions/nuclide) ⭐ 141 | 🐛 3 | 🌐 QuakeC | 📅 2025-11-12 - Software development kit for building new games and mods on id Tech, used by freehl and related clean-room GoldSrc-era reimplementations.
* [sourcepp](https://github.com/craftablescience/sourcepp) ⭐ 138 | 🐛 13 | 🌐 C++ | 📅 2026-09-04 - C++20 library suite for parsing Source Engine file formats (VTF, MDL, VVD, VPK, BSP, etc.).
* [Unity-Source-Tools](https://github.com/lewa-j/Unity-Source-Tools) ⭐ 111 | 🐛 13 | 🌐 C# | 📅 2021-01-04 - Unity plugin for importing and extracting Source Engine game resources (maps and models).
* [sledge-formats](https://github.com/LogicAndTrick/sledge-formats) ⭐ 100 | 🐛 3 | 🌐 C# | 📅 2026-08-12 - C# parsers and formats for Half-Life 1 and related engines.
* [uSource](https://github.com/DeadZoneLuna/uSource) ⭐ 92 | 🐛 9 | 🌐 C# | 📅 2022-11-21 - Unity plugin for importing Source Engine formats (MDL, BSP, VTF, VMT, VPK, VVD, VTX).
* [srctools](https://github.com/TeamSpen210/srctools) ⭐ 87 | 🐛 11 | 🌐 Python | 📅 2026-07-21 - Python modules for working with Source Engine file formats.
  * Formats: VMF, BSP, VPK.
* [source1import](https://github.com/kristiker/source1import) ⭐ 71 | 🐛 17 | 🌐 Python | 📅 2025-02-28 - Python scripts for importing Source 1 game assets (materials, models, particle effects) into Source 2.
* [cs2typescript](https://github.com/Ansimist/cs2typescript) ⭐ 63 | 🐛 2 | 🌐 C# | 📅 2025-09-16 - Converts Counter-Strike 2 map-scripting files from .vts (TypeScript source) to the compiled .vts\_c format.
* [Hammer5Tools](https://github.com/dertwist/Hammer5Tools) ⭐ 58 | 🐛 0 | 🌐 Python | 📅 2026-09-04 - Suite of editors (SoundEvent, SmartProp, Hotkey, Loading) for Counter-Strike 2 / Source 2 Workshop Tools content creation, complementing Valve's official Hammer 5 editor.
* [ps2-hl-tools](https://github.com/supadupaplex/ps2-hl-tools) ⭐ 45 | 🐛 3 | 🌐 C++ | 📅 2022-01-27 - Tools for extracting and converting PS2 Half-Life port resources, including .pak archives, .dol models, .spz sprites, .psi images, .psf fonts, .vag music, .nod AI nodes, .epc model precache lists.
* [UntitledParser](https://github.com/UncraftedName/UntitledParser) ⭐ 35 | 🐛 6 | 🌐 C# | 📅 2026-02-10 - Command-line parser and analysis tool for Source engine .dem demo files (HL2, CS:S, TF2, etc.).
* [vpulse-editor](https://github.com/LionDoge/vpulse-editor) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2026-08-05 - Unofficial editor for Source 2's Pulse visual scripting graph files, used in Dota 2, CS2, and Deadlock, filling a gap left by the lack of official Valve tooling for this format.
* [gchimp](https://github.com/khanghugo/gchimp) ⭐ 29 | 🐛 19 | 🌐 Rust | 📅 2026-09-02 - Collection of GoldSrc mapping tools in one GUI/CLI application.
  * Features: JoinMDL (combines multiple Hammer models into one), S2G (Source-to-GoldSrc model converter), SkyMod (skybox model generator from images), TexTile (texture tiling), Waddy (WAD editor), Map2Mdl (.map to .mdl converter), BLBH (baked light model accessor), plus a scripting API and misc utilities (.wav looper, .smd splitter).
* [Source2SchemaDumper](https://github.com/GAMMACASE/Source2SchemaDumper) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-07-26 - Metamod-source plugin that dumps live Source 2 schema definitions (entity classes, metatags, atomics, pulse bindings, module metadata) to JSON or KV3 from a running CS2, Deadlock, or Dota 2 server, complementing GameTracking's CI-based depot dumps.
* [S2GConverter](https://github.com/mrglaster/S2GConverter) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2025-08-20 - Python utility converting 3D models (with any polygon count and animations) from the Source engine to the GoldSource engine, including pseudo-normal-map generation and texture fusion for GoldSrc's rendering pipeline.
* [UEditingTools](https://github.com/adenexvfx/UEditingTools) ⭐ 19 | 🐛 0 | 📅 2024-11-22 - Unreal Engine 5 widget/pipeline for importing CS2, CS:GO, CS:S, TF2, and CS 1.6 player, weapon, and viewmodel assets with correct skeletons, cameras, and sequencer/level placement; companion to the same author's io\_scene\_CSGO Blender importer.
* [IDA-GameDataTracker](https://github.com/K4ryuu/IDA-GameDataTracker) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2026-03-13 - IDA Pro plugin for tracking Source engine game functions across binary updates, automatically relocating function signatures, vtable offsets, and mid-function patterns. Exports to CounterStrikeSharp and SwiftlyS2 gamedata formats for CS2/Source Engine plugin development.
* [talent](https://github.com/cgdangelo/talent) ⭐ 17 | 🐛 1 | 🌐 TypeScript | 📅 2024-04-20 - TypeScript GoldSrc demo (.dem) parser built on fp-ts parser combinators, decoding all frame types and `SVC_` network messages into readable data structures for real-time or offline demo analysis.
* [dem](https://github.com/khanghugo/dem) ⭐ 16 | 🐛 3 | 🌐 Rust | 📅 2026-05-13 - Complete GoldSrc demo (.dem) parser and writer library in Rust.
* [SourceLoader](https://github.com/K0bin/sourceloader) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2018-04-28 - Source Engine map loader supporting BSP, VTF, and MDL formats with OBJ export.
* [source2-asset-assembler](https://github.com/LionDoge/source2-asset-assembler) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-07-14 - Tool to manually assemble various Source 2 assets, by the author of vpulse-editor above.
* [lambda-core](https://github.com/Galaco/lambda-core) ⚠️ Archived - Go library for parsing Source Engine asset formats (VMT, VTF, MDL, BSP) with filesystem and resource management.
* [kdr](https://github.com/khanghugo/kdr) ⭐ 12 | 🐛 4 | 🌐 Rust | 📅 2026-04-04 - Cross-platform GoldSrc map and demo viewer/renderer (WIP), reading original .bsp map and .mdl model data with lightmaps, transparency, and bone-based model animation.
* [demogobbler](https://github.com/lipsanen/demogobbler) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2025-08-02 - C library and CLI tools for parsing and writing Source engine and GoldSrc .dem demo files.
* [FreeTS](https://github.com/Frag-Net/FreeTS) ⭐ 5 | 🐛 0 | 🌐 QuakeC | 📅 2026-06-29 - Clean-room reimplementation of The Specialists, another GoldSrc-era Half-Life mod, built on Nuclide and freehl.
* [DemoViewer](https://github.com/dertwist/DemoViewer) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-04-20 - Viewer for Counter-Strike 2 / Source 2 .dem demo/replay files.
* [hvox](https://github.com/fgsfdsfgs/hvox) ⭐ 3 | 🐛 0 | 🌐 Nim | 📅 2020-02-10 - Standalone player for Half-Life's sentence system, loading the game's original voice-pack WAV files and synthesizing SENTENCES.TXT-style scripted lines with per-word pitch/volume/timing control codes.
* [go-valve](https://github.com/handsomematt/go-valve) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2018-03-21 - Go library for querying A2S server information from Source servers.
* [dod-tools](https://github.com/cgdangelo/dod-tools) ⭐ 2 | 🐛 12 | 🌐 Rust | 📅 2025-08-31 - GUI/CLI utility for analyzing Day of Defeat (GoldSrc) .dem demo files, producing per-player Markdown/JSON match reports from POV demo recordings.
* [powerjack](https://github.com/cohaereo/powerjack) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-12-06 - Team Fortress 2 asset viewer and demo player. Features improved rendering with direct lightmap sampling from BSP data.

#### Maps & BSP

* [bspsrc](https://github.com/ata4/bspsrc) ⭐ 866 | 🐛 39 | 🌐 Java | 📅 2026-08-13 - Java-based map decompiler for Source engine .bsp files, reconstructing editable .vmf sources for Hammer.
* [GtkRadiant](https://github.com/TTimo/GtkRadiant) ⭐ 659 | 🐛 170 | 🌐 C | 📅 2024-08-18 - Open source, cross-platform level editor for id Tech and Source engine games.
* [Counter-Strike-JS](https://github.com/VadimDez/Counter-Strike-JS) ⭐ 295 | 🐛 12 | 🌐 TypeScript | 📅 2025-09-18 - Counter-Strike 1.6 client reimplementation in TypeScript that parses and renders the game's original .bsp (v30) maps and .mdl (v10) models in the browser; requires the original `cstrike` game folder.
* [bspguy](https://github.com/wootguy/bspguy) ⭐ 179 | 🐛 12 | 🌐 C | 📅 2026-09-03 - Edits GoldSrc (Half-Life) BSP maps without decompiling. Also views .MDL models. See also [UnrealKaraulov's fork](https://github.com/UnrealKaraulov/newbspguy) ⭐ 126 | 🐛 36 | 🌐 C++ | 📅 2026-03-04 with additional viewer features.
* [hlviewer.js](https://github.com/skyrim/hlviewer.js) ⭐ 179 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-02 - Browser-based GoldSrc viewer that loads and renders the engine's original .bsp maps, .wad textures, and .dem demo replays.
* [GodotGoldSrcBSP](https://github.com/DataPlusProgram/GodotGoldSrcBSP) ⭐ 159 | 🐛 3 | 🌐 GDScript | 📅 2021-10-20 - Godot plugin to load GoldSrc BSP map files, companion to the same author's Godot-GoldSrc-MDL-Importer.
* [HammerAddons](https://github.com/TeamSpen210/HammerAddons) ⭐ 157 | 🐛 84 | 🌐 Python | 📅 2026-07-30 - Hammer editor addons for BSP file processing, entity support, and auto-packing Source Engine game assets.
* [Scopa](https://github.com/radiatoryang/scopa) ⭐ 156 | 🐛 1 | 🌐 C# | 📅 2026-01-08 - Unity level design plugin for importing Quake .MAP, Half-Life .RMF, Source .VMF map formats, and .WAD textures.
* [VMF2OBJ](https://github.com/Dylancyclone/VMF2OBJ) ⭐ 138 | 🐛 15 | 🌐 Java | 📅 2024-05-31 - Tool for converting Source Engine VMF map files to OBJ format with materials.
* [bsp\_tool](https://github.com/snake-biscuits/bsp_tool) ⭐ 129 | 🐛 100 | 🌐 Python | 📅 2026-08-25 - Python library and CLI for reading, analysing, and editing .bsp map files across many Quake-derived engines.
  * Engines: Source (VBSP), GoldSrc, idTech/Quake, Quake II, Quake III, Respawn's Source fork (Titanfall 1/2, Apex Legends), Infinity Ward (Call of Duty).
* [WifeRadiant](https://github.com/erysdren/WifeRadiant) ⭐ 121 | 🐛 8 | 🌐 C++ | 📅 2026-09-01 - Open-source, cross-platform level editor for idTech, Source Engine, and GoldSrc based games; modern fork of NetRadiant.
* [valve-bsp-parser](https://github.com/ReactiioN1337/valve-bsp-parser) ⭐ 110 | 🐛 3 | 🌐 C++ | 📅 2024-01-05 - Parser for Valve BSP (Binary Space Partition) map files.
* [LibBSP](https://github.com/wfowler1/LibBSP) ⭐ 107 | 🐛 5 | 🌐 C# | 📅 2026-04-19 - C# library for parsing BSP map files across Quake-derived engines, including Quake 1/2/3, GoldSrc, Source, and other idTech forks. Used by BSP Importer for Unity3D and BSP Decompiler.
* [SDHLT](https://github.com/seedee/SDHLT) ⭐ 100 | 🐛 14 | 🌐 C++ | 📅 2026-09-02 - Half-Life engine map compile tools (compiling to the game's original .bsp/.wad formats), based on Vluzacn's ZHLT v34 with contributions from various mappers; adds shadows from studiomodels, new entities, additional tool textures, world size extensions, and J.A.C.K. portal-file optimization. See also [hltools](https://github.com/speedrun-16/hltools) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-09-02, a from-scratch rewrite of the same toolchain focused on faster compilation and a unified CLI.
* [hlbsp](https://github.com/rein4ce/hlbsp) ⭐ 97 | 🐛 2 | 🌐 JavaScript | 📅 2020-04-26 - Half-Life WebGL level and model viewer, loading and rendering the game's original .bsp and .mdl files.
* [uQuake3](https://github.com/mikezila/uQuake3) ⭐ 83 | 🐛 1 | 🌐 C# | 📅 2015-06-09 - Unity3D importer for Quake 3 BSP map files, enabling Quake 3 levels to be loaded and used inside the Unity engine.
* [corvid](https://github.com/KILLTUBE/corvid) ⭐ 75 | 🐛 2 | 🌐 Python | 📅 2024-10-26 - Source Engine level converter for Call of Duty.
* [bsp-decompiler](https://github.com/wfowler1/bsp-decompiler) ⭐ 59 | 🐛 8 | 🌐 C# | 📅 2025-08-28 - Decompiler for many BSP map formats (Quake, GoldSrc, Source, and other id Tech-derived engines), reconstructing editable map sources.
* [BS2PC](https://github.com/Triang3l/BS2PC) ⭐ 42 | 🐛 1 | 🌐 C++ | 📅 2022-09-15 - Converts Half-Life maps between the PC and PlayStation 2 port's .bsp formats.
* [VMFInstanceInserter](https://github.com/Metapyziks/VMFInstanceInserter) ⭐ 41 | 🐛 9 | 🌐 C# | 📅 2020-05-04 - Tool for inserting func\_instance entities into Source Engine VMF map files.
* [bsp](https://github.com/Galaco/bsp) ⭐ 39 | 🐛 4 | 🌐 Go | 📅 2026-09-01 - Go library for parsing Valve Source Engine .bsp (Binary Space Partition) map files.
* [BspZipGUI](https://github.com/Moltard/BspZipGUI) ⭐ 37 | 🐛 1 | 🌐 C# | 📅 2026-01-19 - GUI wrapper around Valve's BspZip command-line utility for packing custom files (materials, models, sounds) into Source Engine BSP map files.
* [hlbsp-converter](https://github.com/lewa-j/hlbsp-converter) ⭐ 33 | 🐛 2 | 🌐 C++ | 📅 2026-08-01 - Converts Half-Life (GoldSrc) .bsp map files to glTF.
* [hlbsp](https://github.com/bernhardmgruber/hlbsp) ⭐ 28 | 🐛 0 | 🌐 C++ | 📅 2020-04-27 - Reads and renders Half-Life (GoldSrc) v30 .bsp and .wad files, including Counter-Strike 1.6 mods. See also the author's [hlbsp-web](https://github.com/bernhardmgruber/hlbsp-web) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2020-02-03, a JS/WebGL port of the same project.
* [csgo-centrifuge](https://github.com/saiko-tech/csgo-centrifuge) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2023-03-07 - Go API and CLI for extracting data from CS:GO BSP files, including radar overviews and map structure information.
* [GldSrcBSPditor](https://github.com/Sergey-KoRJiK/GldSrcBSPditor) ⭐ 17 | 🐛 0 | 🌐 Pascal | 📅 2025-09-09 - GoldSrc BSP viewer and editor for Half-Life, supporting lightmap editing (import/export per face and style) and texture editing (import/export per mipmap, mass export to WAD3).
* [vmflib-godot](https://github.com/craftablescience/vmflib-godot) ⭐ 13 | 🐛 0 | 🌐 GDScript | 📅 2023-03-10 - Godot 4 library for creating and exporting Source Engine VMF map files (targeted at Portal 2).
* [Chisel.Import.Source](https://github.com/Henry00IS/Chisel.Import.Source) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2024-09-28 - Valve Map Format (VMF) importer for Unity's Chisel Editor, allowing Source Engine VMF maps to be imported and edited in Unity.
* [hlbsp-viewer](https://github.com/r4v3n6101/hlbsp-viewer) ⭐ 10 | 🐛 3 | 🌐 Rust | 📅 2024-06-17 - Viewer for Half-Life (GoldSrc) .bsp maps.
* [func\_godot\_docs](https://github.com/func-godot/func_godot_docs) ⭐ 9 | 🐛 8 | 🌐 HTML | 📅 2025-12-28 - Documentation for FuncGodot, a Godot plugin for building levels using the id Tech/Quake .MAP text-based map format.
* [BSPUtils](https://github.com/Donkie/BSPUtils) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2026-04-14 - Command-line .NET Core programs and library for interacting with the Source Engine's Binary Space Partition (.bsp) file format, including lump extraction.
* [VertAlert](https://github.com/ItEndsWithTens/VertAlert) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2013-03-28 - Finds, displays, and optionally rounds floating point plane coordinates in Source Engine .vmf map files.
* [bsparchive](https://github.com/clintonbale/bsparchive) ⭐ 5 | 🐛 2 | 🌐 C | 📅 2022-10-26 - Reads a GoldSrc .bsp map file's embedded entity data to identify and archive all of its resource dependencies (textures, sounds, sprites, models), for backing up Half-Life mod maps.
* [qbsp-gltf](https://github.com/JarrodDoyle/qbsp-gltf) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-05-27 - CLI tool to convert Quake 2 BSP map files to binary glTF (.glb) models.
* [vmfpy](https://github.com/lasa01/vmfpy) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2022-02-07 - Python parser for Valve Map Format (VMF) and Valve Material Type (VMT) files.
* [TB-Utils](https://github.com/LeGlaconus/TB-Utils) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2026-05-14 - Utilities for the TrenchBroom level editor to facilitate editing Source engine maps.
* [LightsRadExtractor](https://github.com/GAMMACASE/LightsRadExtractor) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2023-08-09 - Extracts lights.rad information (baked static lighting data) from compiled Source 1 engine BSP map files.
* [SourcePorter](https://github.com/dertwist/SourcePorter) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-07-29 - Tool for porting/decompiling Counter-Strike: Global Offensive BSP maps to Counter-Strike 2's VMF/Source 2 format.
* [map-files](https://github.com/iOrange/map-files) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2013-10-05 - '.MAP Files' article and accompanying source code documenting the id Tech .MAP editable level-source format used by Quake/Half-Life-derived engines.
* [goldsrc-bsp-viewer](https://github.com/urgorri/goldsrc-bsp-viewer) ⭐ 0 | 🐛 10 | 🌐 TypeScript | 📅 2026-09-03 - Framework-agnostic viewer for GoldSrc BSP map files from Half-Life, built with Three.js, with an optional React wrapper.

#### Models (MDL/SMD)

* [VPhysics-Jolt](https://github.com/misyltoad/VPhysics-Jolt) ⭐ 1,439 | 🐛 113 | 🌐 C++ | 📅 2025-05-18 - Volt, a drop-in replacement for the Source Engine's VPhysics module built on Jolt Physics, parsing the engine's compiled VPhysics collision model (`.phy`) data to reconstruct rigid bodies, ragdolls, and constraints.
* [HalfLifeAssetManager](https://github.com/SamVanheer/HalfLifeAssetManager) ⚠️ Archived - Tool to view and edit Half-Life 1 (GoldSrc) MDL models.
* [web-hlmv](https://github.com/danakt/web-hlmv) ⭐ 123 | 🐛 18 | 🌐 TypeScript | 📅 2026-08-23 - WebGL implementation of the Half-Life Model Viewer, running GoldSrc .mdl model previews directly in the browser.
* [source-engine-model-loader](https://github.com/gkjohnson/source-engine-model-loader) ⭐ 86 | 🐛 3 | 🌐 JavaScript | 📅 2024-06-18 - Three.js loader for parsing Source Engine model formats (MDL, VMT, VTF, VTX, VVD).
* [Godot-GoldSrc-MDL-Importer](https://github.com/DataPlusProgram/Godot-GoldSrc-MDL-Importer) ⭐ 76 | 🐛 2 | 🌐 GDScript | 📅 2023-09-01 - Plugin that imports GoldSrc .mdl model files into Godot.
* [Source2Converter](https://github.com/REDxEYE/Source2Converter) ⭐ 69 | 🐛 2 | 🌐 Python | 📅 2026-07-28 - Toolset for converting Source 1 models to Source 2, by the author of SourceIO above.
* [StdPatch](https://github.com/kohtep/StdPatch) ⭐ 28 | 🐛 1 | 🌐 C++ | 📅 2020-06-13 - StudioMDL Compiler Patcher that removes limitations of the Source Engine models compiler. Allows compiling high-poly models by expanding vertex arrays, weight arrays, and flexcontroller arrays. Includes StdInjector for DLL injection into studiomdl process.
* [HLMV-Qt](https://github.com/MoeMod/HLMV-Qt) ⭐ 15 | 🐛 3 | 🌐 C++ | 📅 2021-07-13 - Half-Life Model Viewer remixed with Qt5, optimized for macOS.
* [hlmvqt](https://github.com/iOrange/hlmvqt) ⭐ 13 | 🐛 0 | 🌐 C++ | 📅 2023-01-10 - Half-Life model viewer written from scratch using Qt 6.
* [spr-viewer](https://github.com/VadimDez/spr-viewer) ⭐ 12 | 🐛 4 | 🌐 TypeScript | 📅 2024-03-28 - Browser-based viewer for Half-Life (GoldSrc) .spr sprite files.
* [GoldSrcModelThumbnailProvider](https://github.com/crskycode/GoldSrcModelThumbnailProvider) ⭐ 11 | 🐛 1 | 🌐 C++ | 📅 2024-10-26 - Windows Explorer thumbnail provider extension that renders previews of Half-Life 1 (GoldSrc) .mdl model files directly in Explorer.
* [studiomodel](https://github.com/Galaco/studiomodel) ⭐ 9 | 🐛 1 | 🌐 Go | 📅 2025-11-02 - Go library for loading Valve studiomodel formats.
  * Formats: .mdl, .vtx, .vvd.
* [GoldSrcSpriteThumbnailProvider](https://github.com/crskycode/GoldSrcSpriteThumbnailProvider) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2025-04-03 - Windows Explorer thumbnail provider extension that renders previews of Half-Life 1 (GoldSrc) .spr sprite files directly in Explorer.
* [hlmv-web](https://github.com/crskycode/hlmv-web) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2021-05-27 - Half-Life 1 (GoldSrc) engine model loader for THREE.js, running .mdl model previews in the browser.
* [valve-vrm](https://github.com/UnBeatWaterGH/valve-vrm) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-12-20 - Documentation and converter for Valve's experimental VRM model format.
* [GoldSrcModelViewerDirectX11](https://github.com/crskycode/GoldSrcModelViewerDirectX11) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2024-10-19 - GoldSrc (Half-Life 1) .mdl model viewer built on DirectX 11.

#### Textures & Materials (VTF/VMT)

* [VTFLib](https://github.com/NeilJed/VTFLib) ⭐ 190 | 🐛 11 | 🌐 C++ | 📅 2023-03-19 - C/C++ library for reading/writing VTF and VMT texture/material files. See also [panzi's fork](https://github.com/panzi/VTFLib) ⭐ 49 | 🐛 1 | 🌐 C++ | 📅 2026-07-03 — Linux port adding a CMake build, libtxc\_dxtn support, and buffer-overflow fixes; [pyvtflib](https://github.com/lasa01/pyvtflib) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2020-09-03 — Python bindings (Windows only); and [vtflib-rs](https://github.com/lasa01/vtflib-rs) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2022-01-21 — safe Rust wrapper.
* [MareTF](https://github.com/craftablescience/MareTF) ⭐ 132 | 🐛 15 | 🌐 C++ | 📅 2026-08-31 - Utility for creating, editing, and displaying VTF (Valve Texture Format) files. Supports all VTF versions used in Source Engine games (Half-Life 2, Portal, Counter-Strike, Team Fortress 2, etc.).
* [AutoVTF](https://github.com/NvC-DmN-CH/AutoVTF) ⭐ 70 | 🐛 11 | 🌐 C# | 📅 2024-12-05 - C# WinForms tool for working with VTF files. Monitors materials folder and automatically converts updated images to VTF format, preserving VTF settings. Features drag-and-drop conversion, advanced VTF options panel, and Hammer++ hotloading support.
  * Formats: PNG, BMP, TGA, JPG, PSD (input), VTF (output).
* [vtf2img](https://github.com/julienc91/vtf2img) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2020-05-12 - Python library for converting Valve Texture Format (VTF) files to standard image formats.
* [source2utils](https://github.com/Rectus/source2utils) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2016-06-19 - Batch converter for Source 1 VMT material scripts to the Source 2 VMAT format.
* [vtf](https://github.com/Galaco/vtf) ⭐ 13 | 🐛 1 | 🌐 Go | 📅 2025-11-06 - Go library for parsing and converting Source Engine .vtf texture format files.
* [vmt](https://github.com/Galaco/vmt) ⭐ 6 | 🐛 1 | 🌐 Go | 📅 2025-11-02 - Go library for parsing Source Engine .vmt Valve Material format files.
* [VTF-Viewer](https://github.com/u1krsh/VTF-Viewer) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2026-06-14 - Cross-platform VTF viewer and VMT editor for Source Engine games (Half-Life 2, Team Fortress 2, CS:GO, Portal, Left 4 Dead).

#### Packages & Filesystem (VPK/GCF/GMA/WAD)

* [VPKEdit](https://github.com/craftablescience/VPKEdit) ⭐ 739 | 🐛 52 | 🌐 C++ | 📅 2026-08-10 - Cross-platform GUI and CLI tool for creating, reading, and writing many pack file formats used across Source, GoldSrc, and Quake-family games.
  * Formats: VPK (Source 1/2), GCF, GMA, WAD (GoldSrc), PAK (Quake/HL1), PK3 (Quake II), PK4 (Quake IV/Doom 3), BSP (Source 1), XZP (Xbox HL2), VPP (Red Faction/Saints Row), PCK (Godot), ZIP, and more.
  * Features: In-pack preview of audio, images, VTF textures, and Source 1 models without extraction; available for Windows, macOS, and Linux.
* [vpk](https://github.com/ValvePython/vpk) ⭐ 189 | 🐛 9 | 🌐 Python | 📅 2023-09-20 - Python library and CLI for opening, searching, extracting, and creating Valve VPK archives.
* [ValvePak](https://github.com/ValveResourceFormat/ValvePak) ⭐ 151 | 🐛 0 | 🌐 C# | 📅 2026-09-04 - C# .NET library for reading and writing Source 2 VPK (Valve PacK) archives. Part of the ValveResourceFormat project.
* [WadMaker](https://github.com/pwitvoet/wadmaker) ⭐ 67 | 🐛 6 | 🌐 C# | 📅 2026-05-12 - Command-line tools for creating and extracting Half-Life (GoldSrc) texture WADs and sprites.
* [vpk\_fuse](https://github.com/ElementW/vpk_fuse) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2023-04-15 - FUSE filesystem for mounting and browsing the contents of Valve VPK package files.
* [filesystem](https://github.com/Galaco/filesystem) ⭐ 16 | 🐛 1 | 🌐 Go | 📅 2025-11-06 - Go library for managing Source Engine VPK archives (Counter-Strike: Source, CS:GO, Team Fortress 2, etc.).
* [jvpklib](https://github.com/ata4/jvpklib) ⭐ 11 | 🐛 2 | 🌐 Java | 📅 2014-02-20 - Simple Java library for reading Valve VPK archive files used in Source Engine games.
* [fgptool](https://github.com/craftablescience/fgptool) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-01-09 - Tool for cracking filepath hashes in The Orange Box PS3 file groups (.vpk format).
* [WAD3xtract](https://github.com/ElementW/WAD3xtract) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2015-01-03 - Command-line extractor for Half-Life's WAD3 texture archive format.
* [vpk-tools](https://github.com/K4ryuu/vpk-tools) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-30 - Zero-dependency Valve VPK archive reader/writer for Node.js and Bun, with full v1/v2 support, CRC32 + MD5 verification, multi-chunk archives, RSA signing, diffing, and a CLI.

#### KeyValues, VDF & Choreography

* [ValveKeyValue](https://github.com/ValveResourceFormat/ValveKeyValue) ⭐ 192 | 🐛 9 | 🌐 C# | 📅 2026-08-29 - .NET library for parsing Valve's KeyValue format used in Source/Source 2 engines.
* [keyvalues3](https://github.com/kristiker/keyvalues3) ⭐ 19 | 🐛 4 | 🌐 Python | 📅 2026-06-22 - Python library for Source 2's KeyValues3 (KV3) format.
* [vsif2vcd](https://github.com/MrSoup678/vsif2vcd) ⭐ 13 | 🐛 1 | 🌐 C++ | 📅 2025-05-29 - Decompiles VCD choreography scenes from Source Engine `scenes.image` files back into editable `.vcd` files.
* [keyvalues](https://github.com/Galaco/keyvalues) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2023-12-15 - Go library for parsing Source Engine KeyValue format files (gameinfo.txt, vmt, vmf, etc.).
* [vdf-parser](https://github.com/lukezbihlyj/vdf-parser) ⭐ 5 | 🐛 4 | 🌐 PHP | 📅 2016-04-04 - Parser for Valve Data Format (VDF) files used in Source games.
* [VDataEditor](https://github.com/dertwist/VDataEditor) ⚠️ Archived - Desktop editor for Source 2 KV3 data files (.vdata, .vsmart, .vpcf).
* [checksum](https://github.com/Galaco/checksum) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2025-07-05 - Utility for calculating CRC32 checksums for Source Engine file validation.
* [keyvalues-tools](https://github.com/K4ryuu/keyvalues-tools) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-30 - Zero-dependency TypeScript parser and serializer for Valve KeyValues (KV1/VDF and KV3), for reading, editing, validating, and converting Source engine config files, with a CLI.

#### DCC Plugins (Blender / 3ds Max / Maya / XSI)

* [SourceIO](https://github.com/REDxEYE/SourceIO) ⭐ 963 | 🐛 16 | 🌐 Python | 📅 2026-09-02 - Blender 3.6+ addon for importing Source Engine assets (models, maps, textures, materials) for both Source 1 and Source 2.
  * Formats: Source 1 — MDL, BSP, VTF, VMT; Source 2 — VMDL, VMAP, VTEX, VMAT.
  * Games: CS:GO, TF2, Source Filmmaker, Garry's Mod, HL2 + episodes, Portal 1/2, L4D2, Black Mesa, Vindictus, Titanfall 1, CS2, Half-Life: Alyx, Aperture Desk Job, S\&Box.
* [Plumber](https://github.com/lasa01/Plumber) ⭐ 501 | 🐛 33 | 🌐 Rust | 📅 2026-06-13 - Blender add-on for importing Source 1 engine maps, models, materials and textures from CS:GO, TF2, CS:S, and other titles. Built on [plumber\_core](https://github.com/lasa01/plumber_core) ⭐ 23 | 🐛 2 | 🌐 Rust | 📅 2026-06-13, a standalone Rust library for converting Source Engine VMF maps into a generic 3D format.
  * Features: full map import (brushes, overlays, lights, props, skyboxes), MDL/material/texture import with color options, and embedded file browser.
* [Blender Source Tools](https://github.com/Artfunkel/BlenderSourceTools) ⭐ 288 | 🐛 5 | 🌐 Python | 📅 2025-11-01 - Blender addon for importing and exporting Source Engine model and animation formats. Enables 3D asset creation and modification for all Source Engine games in Blender.
* [SourceOps](https://github.com/bonjorno7/SourceOps) ⭐ 182 | 🐛 24 | 🌐 Python | 📅 2025-09-04 - Blender addon for exporting models to Source 1. More convenient alternative to Blender Source Tools. Features export objects as SMD or FBX, export actions as SMD, generate QC based on UI settings, buttons to compile and view models, and experimental export for brushes and displacements to VMF. Requires Blender 2.83 or newer.
* [AutoMDL](https://github.com/NvC-DmN-CH/AutoMDL) ⭐ 31 | 🐛 9 | 🌐 Python | 📅 2024-05-17 - Blender 4+ addon for Source engine MDL compilation workflow. Automatically compiles .blend files to .mdl format when saved in a models folder, with Hammer++ hotloading support. Features automatic material path detection, collision model support, and studiomdl.exe integration.
* [blender-vmt](https://github.com/lasa01/blender-vmt) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2020-04-19 - Blender addon for importing Source Engine material (.vmt) files, resolving shader parameters and texture (VTF) references.
* [io\_scene\_CSGO](https://github.com/adenexvfx/io_scene_CSGO) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2025-12-29 - Blender addon for importing Counter-Strike: Global Offensive model formats (QC, SMD, DMX), with batch conversion and SFM2 DMX to FBX support.
* [io\_texture\_VTF](https://github.com/REDxEYE/io_texture_VTF) ⚠️ Archived - Blender addon for importing and exporting Source Engine VTF texture files. (Archived)
* [io\_mesh\_SourceBSP](https://github.com/REDxEYE/io_mesh_SourceBSP) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2018-08-30 - Blender addon for importing and exporting Source Engine BSP map files.
* [SMDMaya](https://github.com/ThomasCat/SMDMaya) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2026-05-26 - Import and export Valve SMD and DMX files natively within Autodesk Maya.

#### Legacy Tools & Downloads (ModDB)

* [source-wrench](https://github.com/NameIsJakob/source-wrench) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-08-11 - Application to compile models to the Source Engine 1 MDL format.
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

#### Dota 2

* [GameTracking-Dota2](https://github.com/SteamTracking/GameTracking-Dota2) ⭐ 758 | 🐛 0 | 🌐 C++ | 📅 2026-09-04 - Continuously-updated tracker of Dota 2's client-facing data extracted from each game update, including Source 2 protobuf network/GC message schemas (demo.proto, netmessages, GC messages) and dumped client schemas/module metadata, with full version history across patches.
* [dota2-mod-manager](https://github.com/TheFleece/dota2-mod-manager) ⭐ 24 | 🐛 6 | 🌐 JavaScript | 📅 2026-09-05 - Mod manager for Dota 2, working with the game's original VPK addon format.
* [goldsrc-rs](https://github.com/goldsrc-rs/goldsrc-rs) ⭐ 2 | 🐛 1 | 🌐 Rust | 📅 2026-09-04 - Rust modding/format framework for GoldSrc (Half-Life) engine games.

#### Portal

* [PortalNXSideLoader](https://github.com/masagrator/PortalNXSideLoader) ⭐ 40 | 🐛 1 | 🌐 C | 📅 2023-01-25 - Nintendo Switch plugin for Portal 1 and 2 that sideloads files from outside game.zip, avoiding repacking and re-transferring the archive for every change.

### reSource Engine (Respawn Entertainment)

* [Legion+](https://github.com/r-ex/LegionPlus) ⚠️ Archived - Asset extraction tool for Apex Legends and Titanfall 2.
* [RePak](https://github.com/r-ex/RePak) ⭐ 40 | 🐛 4 | 🌐 C++ | 📅 2026-06-28 - Builds Respawn Entertainment `.rpak`/`.starpak` asset pack files for Apex Legends and Titanfall 2, for repacking modded assets back into the engine's runtime asset format.
* [reSource Model Templates](https://github.com/IJARika/resource_model_templates) ⭐ 18 | 🐛 0 | 📅 2026-09-04 - 010 Editor binary templates for Respawn Entertainment's reSource engine (a Source engine fork used by Titanfall and Apex Legends), focused on studio model formats.
  * Formats: MDL (v48/49/52/53/63), RMDL, RRIG, RSEQ, PHYS (Valve and Respawn variants), vertex data (VTX/VVD/VVC/VVW), VG (rev1-4), pakfile, DMX, VTF; legacy V47 structs including original Xbox variants.
* [rmdlconv](https://github.com/r-ex/rmdlconv) ⭐ 17 | 🐛 0 | 🌐 C++ | 📅 2025-09-01 - Converts between different versions of Source Engine and Respawn MDL model files.
* [fupa](https://github.com/McSimp/fupa) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2019-04-26 - RPak extractor for Respawn Entertainment's Apex Legends/Titanfall 2 asset packs.

### Unity

#### Asset Extraction & Asset Bundle Tools

* [AssetStudio (Perfare)](https://github.com/Perfare/AssetStudio) ⚠️ Archived - Tool for exploring, extracting, and exporting assets and assetbundles (original version).
* [noclip.website (Unity)](https://github.com/magcius/noclip.website/tree/main/src/Common/Unity) ⭐ 4,251 | 🐛 86 | 🌐 TypeScript | 📅 2026-08-26 - From-scratch TypeScript/Rust reader for Unity SerializedFile and AssetBundle data. Reconstructs GameObject hierarchies, meshes, textures (including Crunch), and materials for in-browser rendering; drives the A Short Hike, Neon White, and Outer Wilds viewers.
* [Asset Bundle Extractor (UABE)](https://github.com/SeriousCache/UABE) ⚠️ Archived - Editor for .assets and AssetBundle files (archived; consider UABEA for active development).
* [Unity Game Hacking Guide](https://github.com/imadr/Unity-game-hacking) ⭐ 3,460 | 🐛 16 | 📅 2022-11-14 - Guide covering Unity's on-disk game/asset file layout, extracting and editing compiled C#/UnityScript code, extracting assets, and memory hacking techniques.
* [UtinyRipper](https://github.com/mafaca/UtinyRipper) ⭐ 3,093 | 🐛 892 | 🌐 C# | 📅 2022-01-14 - Extracts and exports Unity assets from serialized `.assets` files and AssetBundle files into Unity-importable project format. Supports a wide range of Unity versions.
* [disunity](https://github.com/ata4/disunity) ⚠️ Archived - Early experimental Java command-line toolset for extracting and inspecting Unity asset and asset bundle files. Archived since 2018 and largely superseded by AssetStudio/UABEA, but historically significant.
* [UABEA (Unity Asset Bundle Extractor Avalonia)](https://github.com/nesrak1/UABEA) ⭐ 2,413 | 🐛 146 | 🌐 C# | 📅 2026-05-11 - C# UABE for newer versions of Unity. Cross-platform Unity asset bundle and serialized file editor/extractor built with Avalonia.
* [AssetStudio (aelurum fork)](https://github.com/aelurum/AssetStudio) ⭐ 2,042 | 🐛 52 | 🌐 C# | 📅 2025-10-15 - Actively maintained fork with UI optimization and enhancements.
* [AssetStudio (zhangjiequan fork)](https://github.com/zhangjiequan/AssetStudio) ⭐ 1,849 | 🐛 29 | 🌐 C# | 📅 2024-03-04 - Continuation of Perfare's AssetStudio with support for new Unity versions and additional improvements.
* [UnityPy](https://github.com/K0lb3/UnityPy) ⭐ 1,424 | 🐛 20 | 🌐 Python | 📅 2026-08-01 - Python module that makes it possible to extract/unpack and edit Unity assets.
* [AnimeStudio](https://github.com/Escartem/AnimeStudio) ⭐ 1,130 | 🐛 23 | 🌐 C++ | 📅 2026-09-03 - Actively maintained "modded AssetStudio" fork with support for many encrypted Unity titles, including all HoYoverse games.
* [UnityPack](https://github.com/HearthSim/UnityPack) ⭐ 750 | 🐛 48 | 🌐 Python | 📅 2022-01-06 - Earlier Python deserialization library for the Unity3D asset format, predating and unmaintained relative to UnityPy but still used as a lightweight dependency-free alternative.
* [AssetsTools.NET](https://github.com/nesrak1/AssetsTools.NET) ⭐ 684 | 🐛 36 | 🌐 C# | 📅 2026-08-02 - Read and write Unity assets/bundle files, based on UABE.
* [UABEANext](https://github.com/nesrak1/UABEANext) ⭐ 392 | 🐛 4 | 🌐 C# | 📅 2026-07-27 - Research and modding tool for SerializedFiles and Asset Bundles.
* [AssetStudio\_Tuanjie](https://github.com/SiMaLaoShi/AssetStudio_Tuanjie) ⭐ 339 | 🐛 8 | 🌐 C# | 📅 2025-06-04 - AssetStudio fork adapted for Tuanjie (团结引擎), the China-specific fork/variant of the Unity engine.
  * Lineage: succeeds [RazTools/Studio](https://github.com/RazTools/Studio) ⚠️ Archived (archived), whose own forks (e.g. [YarikStudio](https://github.com/yarik0chka/YarikStudio) ⚠️ Archived, discontinued) now point users to this repo as the actively maintained continuation.
* [AddressablesTools](https://github.com/nesrak1/AddressablesTools) ⭐ 144 | 🐛 12 | 🌐 C# | 📅 2026-08-09 - Reads and writes Unity Addressables data without needing Unity itself. See also [LukeFZ's fork](https://github.com/LukeFZ/AddressablesTools) ⭐ 4 | 🐛 0 | 📅 2025-01-31.
* [mikunyan](https://github.com/Ishotihadus/mikunyan) ⭐ 70 | 🐛 1 | 🌐 C++ | 📅 2026-01-10 - Scriptable Unity asset deserializer for Ruby.
* [UTTDumper](https://github.com/Razmoth/UTTDumper) ⭐ 60 | 🐛 1 | 🌐 C++ | 📅 2024-12-12 - Tool to help dump Unity type trees.
* [UnityLive2DExtractor](https://github.com/aelurum/UnityLive2DExtractor) ⭐ 58 | 🐛 0 | 🌐 C# | 📅 2025-09-08 - Extracts Live2D Cubism 3 assets from Unity AssetBundles. Handles moc3 models, motion3 animations, physics3 configuration, and other Live2D format files.
* [UnityCN-Helper](https://github.com/AXiX-official/UnityCN-Helper) ⭐ 57 | 🐛 2 | 🌐 C# | 📅 2026-02-25 - Decrypts/encrypts AssetBundle files protected by the UnityCN encryption scheme used by many Chinese Unity titles.
* [TypeTreeDumper](https://github.com/DaZombieKiller/TypeTreeDumper) ⭐ 56 | 🐛 5 | 🌐 C# | 📅 2026-02-06 - IL2CPP-based Unity TypeTree/serialization layout dumper, generating `.tpk` TypeTree databases for use with AssetsTools.NET and other Unity asset libraries.
* [TypeTreeDumps](https://github.com/AssetRipper/TypeTreeDumps) ⭐ 46 | 🐛 8 | 🌐 Shell | 📅 2026-07-24 - Archive of Unity version struct layouts (type tree information) since version 3.4.0, essential for asset format understanding.
* [TypeTreeRipper](https://github.com/DaZombieKiller/TypeTreeRipper) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2026-09-03 - Experimental C++ Unity TypeTree/serialization dumper that does not require symbols, an alternative to TypeTreeDumper. See also [LukeFZ's fork](https://github.com/LukeFZ/TypeTreeRipper) ⭐ 6 | 🐛 0 | 📅 2026-01-21.
* [ABRecompressor](https://github.com/AXiX-official/ABRecompressor) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2025-01-19 - Recompresses Unity AssetBundle files (e.g. LZ4-to-LZMA or vice versa) to reduce size or restore compatibility.
* [unity-asset](https://github.com/Latias94/unity-asset) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - Rust toolkit for inspecting, indexing, extracting, and making guarded, revision-bound edits to Unity YAML (scene/prefab) and binary serialized assets.
* [UnityAsset.NET](https://github.com/AXiX-official/UnityAsset.NET) ⭐ 11 | 🐛 0 | 🌐 C# | 📅 2026-03-05 - Work-in-progress .NET library for parsing, serializing, and patching Unity asset files.
* [UnityWebTools.NET](https://github.com/kiraio-moe/UnityWebTools.NET) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2023-09-21 - C# library for unpacking and repacking Unity WebGL `UnityWebData` (`.data`) files, complementing AssetsTools.NET for Unity WebGL builds.
* [UnityAssetLib](https://github.com/akintos/UnityAssetLib) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2021-12-15 - C# library for reading and writing Unity serialized asset files (AssetBundle, `.assets`, scenes) across engine versions, independent of AssetsTools.NET.
* [unitypatcher](https://github.com/synogen/unitypatcher) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2018-10-05 - Command-line tool for patching values inside Unity serialized asset files without needing to rebuild the whole AssetBundle.
* [UnityBundleExtractor](https://github.com/lenzarchive/UnityBundleExtractor) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-08-03 - Python script for extracting assets (models, animations, audio, textures) from Unity3D asset bundle files, with intelligent naming, structured output, and detailed logging. See also [UBE-GUI](https://github.com/lenzarchive/UBE-GUI) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-08-27, a Flask-based web interface for the same extractor with async processing and selective extraction.
* [UnityCNBurst](https://github.com/AXiX-official/UnityCNBurst) ⭐ 4 | 🐛 0 | 🌐 Zig | 📅 2025-10-31 - Brute-forces the UnityCN AssetBundle encryption key when it isn't already known, complementing UnityCN-Helper above.
* [CC3Decrypt](https://github.com/tge-was-taken/CC3Decrypt) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2017-10-14 - Decrypts Unity asset bundle headers used by Chain Chronicle 3.
* [UABS (Unity Asset Bundle Seeker)](https://github.com/PapayaModding/UABS) ⭐ 3 | 🐛 1 | 🌐 C# | 📅 2026-02-04 - Modding tool built on AssetsTools.NET for locating and extracting Unity Asset Bundle/`.bundle` contents to streamline mod-making workflows.
* [Unity Asset Editor v0.2 (7 Days To Die)](https://www.moddb.com/games/7-days-to-die/downloads/unity-asset-editor) - Plugin-based asset editor, exporter, and importer for Unity Engine games. Can import and export assets in raw data format and be extended through plugins to support additional asset types (v0.2).
* [Unity3DCompressor](https://gitgoon.dev/IllusionMods/Unity3DCompressor) - Utility for compressing Unity asset bundles using LZ4 to reduce file size and improve load times.

#### IL2CPP & Managed-Code Reverse Engineering

* [Il2CppDumper](https://github.com/Perfare/Il2CppDumper) ⭐ 9,364 | 🐛 154 | 🌐 C# | 📅 2024-08-18 - Unity IL2CPP reverse engineer tool for extracting IL2CPP metadata and converting IL2CPP binaries. See also [bombaris34's fork](https://github.com/bombaris34/il2cpp-pdb) ⭐ 52 | 🐛 1 | 🌐 C# | 📅 2026-06-06 with a native Rust PDB generator for x64 PE (`GameAssembly.dll`) that writes function names, full struct types, and typed prototypes into a real Windows PDB, auto-loaded by IDA.
* [Il2CppInspector](https://github.com/djkaty/Il2CppInspector) ⭐ 3,040 | 🐛 65 | 🌐 C | 📅 2022-05-13 - Powerful automated tool for reverse engineering Unity IL2CPP binaries. Outputs IL2CPP type definitions, metadata and method pointers as C# stub code, creates .NET assembly shim DLLs, and generates C++ scaffolding for all types, methods, function pointers and API functions.
* [Cpp2IL](https://github.com/SamboyCoding/Cpp2IL) ⭐ 2,612 | 🐛 44 | 🌐 C# | 📅 2026-09-03 - Decompiler for Unity IL (Intermediate Language) code and assets.
* [frida-il2cpp-bridge](https://github.com/vfsfitvnm/frida-il2cpp-bridge) ⭐ 1,734 | 🐛 38 | 🌐 TypeScript | 📅 2026-09-04 - TypeScript Frida module/library for dumping, tracing, or hijacking any IL2CPP application at runtime without needing the `global-metadata.dat` file; widely used as the base library for other Frida-based IL2CPP tooling, including frida-il2cpp-proto-dumper above.
* [Il2CppInspectorRedux](https://github.com/LukeFZ/Il2CppInspectorRedux) ⭐ 700 | 🐛 9 | 🌐 C# | 📅 2026-08-25 - Actively maintained continuation of Il2CppInspector, kept up to date with newer IL2CPP/Unity metadata versions.
* [Il2CppHookScripts](https://github.com/axhlzy/Il2CppHookScripts) ⭐ 659 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-02 - Frida-based scripts for parsing and hooking `libil2cpp.so` at runtime, for reverse engineering Android IL2CPP Unity games.
* [Il2CppDumper-GUI](https://github.com/AndnixSH/Il2CppDumper-GUI) ⭐ 522 | 🐛 0 | 🌐 C# | 📅 2026-06-10 - Windows GUI front-end for Il2CppDumper. See also [Il2cppDumpDroidGUI](https://github.com/Poko-Apps/Il2cppDumpDroidGUI) ⭐ 217 | 🐛 1 | 📅 2024-09-02, an Android GUI wrapper for the same tool.
* [IL2CPP\_Resolver](https://github.com/sneakyevil/IL2CPP_Resolver) ⭐ 474 | 🐛 15 | 🌐 C++ | 📅 2024-07-30 - Runtime API resolver for IL2CPP-compiled Unity games, locating classes, methods, and fields from global-metadata at runtime.
* [UnityResolve.hpp](https://github.com/issuimo/UnityResolve.hpp) ⭐ 466 | 🐛 15 | 🌐 C++ | 📅 2025-01-27 - Single-header C++ library for resolving Unity Mono/IL2CPP assemblies, classes, methods, and fields at runtime, for building game hacks/analysis tools without a dumped SDK.
* [PADumper](https://github.com/BryanGIG/PADumper) ⭐ 461 | 🐛 10 | 🌐 Kotlin | 📅 2026-01-26 - Android process memory dumper, commonly used to extract IL2CPP/`global-metadata.dat` from protected Unity games at runtime.
* [libil2cpp](https://github.com/MlgmXyysd/libil2cpp) ⭐ 250 | 🐛 0 | 📅 2024-06-11 - Collection of Unity IL2CPP runtime source code across many engine versions, used as a reference for building IL2CPP dumpers and analysis tools.
* [Il2CppMemoryDumper](https://github.com/MlgmXyysd/Il2CppMemoryDumper) ⭐ 204 | 🐛 0 | 🌐 Shell | 📅 2026-02-22 - Dumps the unprotected IL2CPP ELF executable and `global-metadata.dat` directly from process memory, bypassing on-disk packing/encryption.
* [Il2CppDumper-YuanShen](https://github.com/kagurazakasanae/Il2CppDumper-YuanShen) ⚠️ Archived - Il2CppDumper fork modified to dump `UserAssembly.dll` methods from Genshin Impact's (`YuanShen`) encrypted `global-metadata.dat`. See also [khang06's fork](https://github.com/khang06/Il2CppDumper-YuanShen) ⭐ 71 | 🐛 0 | 🌐 C# | 📅 2022-01-23 with updated metadata decryption handling. (Archived)
* [Beebyte-Deobfuscator](https://github.com/OsOmE1/Beebyte-Deobfuscator) ⭐ 131 | 🐛 7 | 🌐 C# | 📅 2021-02-17 - Plugin for Il2CppInspector that deobfuscates Beebyte-obfuscated IL2CPP type/member names in Unity game binaries.
* [Descrypt-global-metadata.dat](https://github.com/IroniaTheMaster/Descrypt-global-metadata.dat) ⭐ 128 | 🐛 1 | 🌐 Python | 📅 2024-03-31 - Decryption notes/tooling for Unity IL2CPP's global-metadata.dat.
* [Il2CppInspectorPlugins](https://github.com/djkaty/Il2CppInspectorPlugins) ⭐ 116 | 🐛 2 | 🌐 C# | 📅 2024-01-05 - Plugins for Il2CppInspector to inspect and reverse-engineer Unity game binaries and extract game data.
* [Dumpcs2Protobuf](https://github.com/Hiro420/Dumpcs2Protobuf) ⭐ 64 | 🐛 1 | 🌐 C# | 📅 2024-10-20 - Extracts obfuscated Protobuf message definitions from `dump.cs` files produced by Il2CppDumper, targeting Honkai: Star Rail and pre-3.5 Genshin Impact. See also [ProtoDumper](https://github.com/66hh/ProtoDumper) ⭐ 31 | 🐛 1 | 📅 2022-02-08, which dumps Protobuf definitions directly from Genshin Impact's Il2CppDumper-produced assemblies.
* [Il2CppDumper-for-COD](https://github.com/tien0246/Il2CppDumper-for-COD) ⭐ 40 | 🐛 7 | 🌐 C# | 📅 2026-03-20 - Il2CppDumper fork adapted for Call of Duty: Mobile's IL2CPP protections.
* [Il2Cpp Self-Dumper](https://github.com/muhammadrizwan87/il2cppdumper) ⭐ 32 | 🐛 0 | 🌐 C | 📅 2026-06-23 - Root-free, Zygisk-free native Android library that dumps IL2CPP metadata (classes, methods, fields with offsets/addresses) from inside a running Unity game's own process, writing a `dump.cs` without requiring Frida, ADB, or Zygisk.
* [Il2CppProtoDescriptorDumper](https://github.com/Hiro420/Il2CppProtoDescriptorDumper) ⭐ 29 | 🐛 0 | 🌐 C# | 📅 2026-08-21 - Extracts Protobuf descriptors from IL2CPP binaries via custom x64 emulation of the descriptor initialization routines.
* [AceMetadataUnpacker](https://github.com/Hiro420/AceMetadataUnpacker) ⭐ 29 | 🐛 0 | 🌐 C# | 📅 2026-05-15 - Unpacks `global-metadata.dat` from ACE-protected IL2CPP binaries, with best-effort XOR/Blowfish string decryption; targets Reverse: 1999 and Goddess of Victory: NIKKE.
* [il2cpp-frida-mcp](https://github.com/axhlzy/il2cpp-frida-mcp) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-02-24 - Model Context Protocol (MCP) server that exposes Frida-based IL2CPP analysis (class/method/field lookup, hooking) as tools an AI assistant can call while reverse engineering a Unity game.
* [MemoryPackDumper](https://github.com/KaniArchive/MemoryPackDumper) ⭐ 25 | 🐛 0 | 🌐 C# | 📅 2026-09-03 - Recovers MemoryPack serializer definitions from Unity IL2CPP game assemblies.
* [il2cpp-bridge-rs](https://github.com/Batchhh/il2cpp-bridge-rs) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-07-14 - Rust bridge to Unity's IL2CPP runtime for resolving types, invoking methods, and manipulating objects from native code; supports iOS, macOS, Linux, Android, and Windows targets.
* [gi-stringliteral](https://github.com/kuma-dayo/gi-stringliteral) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-07-01 - Statically recovers IL2CPP string literals from the MHY-obfuscated `global-metadata.dat` (magic `MHY\0`) used by Genshin Impact.
* [FbsDumper](https://github.com/Hiro420/FbsDumper) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2025-06-16 - Recovers FlatBuffers (`.fbs`) schema definitions from Unity IL2CPP game assemblies. See also [FbsDumperV2](https://github.com/Hiro420/FbsDumperV2) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-07-08, a rewritten successor.
* [frida-il2cpp-proto-dumper](https://github.com/repinek/frida-il2cpp-proto-dumper) ⭐ 9 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-22 - Dumps protobuf-net messages and enums from an IL2CPP Unity game into a valid .proto file, using Frida and frida-il2cpp-bridge.
* [NexusDumper](https://github.com/im-remi/NexusDumper) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-01-06 - Extracts classes, fields, and methods from Honkai: Nexus Anima's IL2CPP code; also generates an IDA `script.json` and extracts Protocol Buffers CmdIDs.
* [meta-string-edit](https://github.com/middlered/meta-string-edit) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2026-02-08 - Editor for Unity IL2CPP `global-metadata.dat` files, for inspecting and modifying embedded string literals.
* [Zygisk-Il2CppFucker](https://github.com/Darlenepurpleblack444/Zygisk-Il2CppFucker) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-09-03 - Zygisk module for reverse engineering IL2CPP binaries in Android Unity games at runtime.
* [UnityMsgpackSchemaExporter](https://github.com/middlered/unity-msgpack-schema-exporter) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-04-15 - Extracts MessagePack data schemas from compiled Unity game assemblies (DummyDll) or any other .NET assembly, and converts between compact keyless MessagePack and named-key MessagePack/JSON.
* [il2cpp-wasm-teardown](https://github.com/clericall/il2cpp-wasm-teardown) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-13 - Teardown/analysis tooling for IL2CPP compiled to WebAssembly.
* [il2cpp-runtime-dumper](https://github.com/PCIeTLP/il2cpp-runtime-dumper) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2026-08-09 - Il2CppDumper-style dumper for IL2CPP games shipping no usable `global-metadata.dat`; reads the runtime's own structures out of the live process and re-derives all struct offsets on each run instead of hardcoding them, so it survives game updates.

#### Modding, Translation & Runtime Injection

* [BepInEx](https://github.com/BepInEx/BepInEx) ⭐ 8,580 | 🐛 381 | 🌐 C# | 📅 2026-09-01 - Widely-used, general-purpose plugin/patcher framework for Unity (Mono and IL2CPP) and .NET games, providing runtime hooking and mod-loading infrastructure used by many game-specific modding tools.
* [XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator) ⭐ 3,385 | 🐛 447 | 🌐 C# | 📅 2026-08-31 - Universal translation framework for Unity games. Supports automatic text translation with various translator backends and IL2CPP support.
* [UnityExplorer](https://github.com/sinai-dev/UnityExplorer) ⚠️ Archived - In-game UI for exploring, debugging, and modifying IL2CPP and Mono Unity games.
* [MonoMod](https://github.com/MonoMod/MonoMod) ⭐ 987 | 🐛 49 | 🌐 C# | 📅 2026-08-24 - Runtime IL patching, method detouring, and modding library/toolchain for .NET/Mono games, underlying many Unity and XNA/FNA game mods.
* [UnityDoorstop](https://github.com/NeighTools/UnityDoorstop) ⭐ 588 | 🐛 24 | 🌐 C | 📅 2026-09-01 - Cross-platform native bootstrapper that loads a .NET assembly into any Unity game at startup, used as the entry point by BepInEx and other Unity mod loaders.
* [SakuraTranslator](https://github.com/fkiliver/SakuraTranslator) ⭐ 225 | 🐛 8 | 🌐 C# | 📅 2025-07-27 - XUnity.AutoTranslator translator-backend plugin providing offline Japanese-to-Chinese translation via the Sakura/GalTransl LLM models. See also [Xunity-TGW](https://github.com/HunterShenSmzh/Xunity-TGW) ⭐ 46 | 🐛 0 | 🌐 C# | 📅 2024-09-28, a modification swapping in a Text Generation WebUI backend instead.
* [il2cpp-modder](https://github.com/juanmjacobs/il2cpp-modder) ⭐ 177 | 🐛 3 | 🌐 C# | 📅 2021-07-26 - Generate DLL injection templates for reverse engineering and modding Unity IL2CPP games. Automatically generates code for method hooks, field modifications, and implementation replacements without requiring manual pointer arithmetic.
* [Unity\_CRC32\_Bypass](https://github.com/AXiX-official/Unity_CRC32_Bypass) ⭐ 46 | 🐛 2 | 🌐 C# | 📅 2026-02-25 - Bypasses Unity's CRC32 integrity check on AssetBundle files by appending extra data to the end of the file, allowing modified bundles to load.
* [AssetSideLoader](https://github.com/AXiX-official/AssetSideLoader) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2025-01-19 - LSPosed module that hooks UnityEngine's internal file-loading methods to redirect asset loads to a custom path, for side-loading replacement AssetBundles/resources without repacking the APK.

#### Texture Decoders

* [unity-texture-toolkit](https://github.com/esterTion/unity-texture-toolkit) ⭐ 178 | 🐛 1 | 🌐 PHP | 📅 2026-07-14 - PHP toolbox for exporting Texture2D assets and other data from Unity3D asset bundles.
* [texture2ddecoder](https://github.com/K0lb3/texture2ddecoder) ⭐ 21 | 🐛 2 | 🌐 C++ | 📅 2026-01-16 - Texture decoder library powering UnityPy's Texture2D asset decoding; distinct from KiruyaMomochi's Texture2DDecoder above. See also [texture2ddecoder-rs](https://github.com/K0lb3/texture2ddecoder-rs) ⭐ 33 | 🐛 9 | 🌐 Rust | 📅 2026-04-08, a pure Rust no-std rewrite.
* [Texture2DDecoder](https://github.com/KiruyaMomochi/Texture2DDecoder) ⭐ 7 | 🐛 1 | 🌐 C++ | 📅 2026-01-25 - Decodes Unity Texture2D assets to standard image files; based on AssetStudio.

#### Save File Tools

* [unity-es3-cracker](https://github.com/Chaobs/unity-es3-cracker) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-18 - Recovers the encryption password of Unity Easy Save 3 (.es3) save files by harvesting password candidates from the game's DLLs/.assets files and brute-forcing the AES key; includes a bilingual (EN/ZH) Tkinter GUI.

#### VideoClip Transcoding

* [UVCT](https://github.com/bungaku-moe/UVCT) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-11-13 - Unity VideoClip Transcoder; re-encodes a Unity game's VideoClip assets to reduce their resource size.

### Unreal Engine

#### Full Engine Reimplementations & Source Ports

* [UnrealTournamentPatches](https://github.com/OldUnreal/UnrealTournamentPatches) ⭐ 1,478 | 🐛 559 | 📅 2026-08-29 - Community patch project for the original Unreal Tournament (1999) and Unreal (1998), maintaining and extending the original engine while reading the games' original asset formats.
* [SurrealEngine](https://github.com/dpjudas/SurrealEngine) ⭐ 1,102 | 🐛 11 | 🌐 C++ | 📅 2026-09-05 - Reimplementation of the Unreal Engine 1 engine that reads original Unreal/Unreal Tournament package/map assets to make the games playable on modern systems.

#### Asset Parsers & Libraries

* [UAssetGUI](https://github.com/atenfyr/UAssetGUI) ⭐ 1,046 | 🐛 16 | 🌐 C# | 📅 2026-08-31 - GUI tool for viewing and editing Unreal Engine UAsset files.
* [CUE4Parse](https://github.com/FabianFG/CUE4Parse) ⭐ 624 | 🐛 27 | 🌐 C# | 📅 2026-09-04 - C# Parser for UE archives.
* [UAssetAPI](https://github.com/atenfyr/UAssetAPI) ⭐ 488 | 🐛 5 | 🌐 C# | 📅 2026-08-31 - Low-level .NET library for reading and writing Unreal Engine game assets.
* [Unreal-Library](https://github.com/EliotVU/Unreal-Library) ⭐ 479 | 🐛 4 | 🌐 C# | 📅 2026-08-15 - Library for reading and writing Unreal Engine file formats.
* [JsonAsAsset](https://github.com/JsonAsAsset/JsonAsAsset) ⭐ 372 | 🐛 0 | 🌐 C++ | 📅 2026-09-04 - Unreal Engine plugin to import assets from JSON data exported by FModel.
* [JsonAsAsset](https://github.com/JsonAsAsset/Reflection) ⭐ 372 | 🐛 0 | 🌐 C++ | 📅 2026-09-04 - Unreal Engine asset reconstruction toolkit; an in-editor plugin that rebuilds engine assets (materials, data assets, curves, and more) from JSON dumps produced by CUE4Parse/FModel.
* [UEFormat](https://github.com/h4lfheart/UEFormat) ⭐ 331 | 🐛 2 | 🌐 Python | 📅 2026-08-14 - Library for working with Unreal Engine file formats.
* [OodleUE](https://github.com/WorkingRobot/OodleUE) ⭐ 147 | 🐛 0 | 🌐 C++ | 📅 2026-06-04 - Automatically pulls and packages the latest Oodle Data compression SDK builds from Unreal Engine 5's private git repo, since RAD's Oodle libraries are otherwise difficult to obtain standalone.
* [uasset-rs](https://github.com/jorgenpt/uasset-rs) ⭐ 120 | 🐛 3 | 🌐 Rust | 📅 2025-06-25 - Rust library for parsing Unreal Engine asset (.uasset) files.
* [pyUE4Parse](https://github.com/MinshuG/pyUE4Parse) ⭐ 85 | 🐛 8 | 🌐 Python | 📅 2026-03-21 - UE4 asset parser/reader in Python.
* [binfold](https://github.com/trumank/binfold) ⭐ 66 | 🐛 0 | 🌐 Rust | 📅 2026-07-17 - Fast symbol-porting tool that matches and transfers large numbers of symbols between similar binaries (e.g. across UE game versions/builds) using pattern signatures.
* [UEAssetToolkitGenerator](https://github.com/LongerWarrior/UEAssetToolkitGenerator) ⭐ 44 | 🐛 16 | 🌐 C# | 📅 2023-09-09 - UE asset extraction tool that converts compiled UE4 assets to JSON format.
* [UEAssetToolkit](https://github.com/Archengius/UEAssetToolkit) ⭐ 35 | 🐛 3 | 🌐 C++ | 📅 2022-10-06 - Toolkit for extracting and modifying Unreal Engine assets.
* [Core](https://github.com/JsonAsAsset/Core) ⭐ 27 | 🐛 0 | 🌐 C# | 📅 2026-08-31 - Extension of JsonAsAsset's Reflection above that fetches referenced Unreal Engine assets automatically, hands-free.
* [AssetTools](https://github.com/PedroMartinsMenezes/AssetTools) ⭐ 26 | 🐛 1 | 🌐 C# | 📅 2026-09-05 - Converts UE .uasset and .umap files to JSON and back, supporting UE5 asset formats.
* [UE1-VertexMesh-Blender-IO](https://github.com/Skywolf285/UE1-VertexMesh-Blender-IO) ⭐ 23 | 🐛 4 | 🌐 Python | 📅 2024-12-14 - Blender exporter/importer for the Unreal Engine 1 `_a.3d`/`_d.3d` vertex mesh format.
* [pyUsmap](https://github.com/MinshuG/pyUsmap) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2024-01-07 - Python parser for Unreal Engine .usmap files.
* [ueformat-rust](https://github.com/Mqlvin/ueformat-rust) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-05-13 - Rust parser for UEFormat (.uemodel) meshes, converting UE4/5 extracted assets to STL format.
* [unreal-assets-to-glb](https://github.com/Prikalel/unreal-assets-to-glb) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-06-20 - Parses Unreal Engine 5.5 editor-time `.uasset` files and extracts static meshes (glTF/glb) and base color textures (PNG) without requiring Unreal Engine to be installed; includes a browser-based level preview mode.

#### Explorers, Viewers & PAK/IoStore Tools

* [FModel](https://github.com/4sval/FModel) ⭐ 3,116 | 🐛 13 | 🌐 C# | 📅 2026-08-30 - Explorer and asset viewer for Unreal Engine archives, supporting UE4 and UE5.
  * Formats: PAK, UTOC, UCAS (IoStore), UAsset, localization files.
  * Features: Texture/mesh/audio preview, JSON export, map viewer with OpenGL renderer, diff between versions.
  * Games: Fortnite, Valorant, PUBG, MultiVersus, Stray, GTA III/Vice City/San Andreas (Definitive Edition), and many other UE4/UE5 titles.
* [UEViewer (UModel)](https://github.com/gildor2/UEViewer) ⭐ 2,919 | 🐛 25 | 🌐 C++ | 📅 2024-03-16 - Viewer and exporter for Unreal Engine 1-4 assets (UE Viewer).
  * [Compatibility Table](https://www.gildor.org/projects/umodel/compat) - Official compatibility list.
* [UnrealPakViewer](https://github.com/jashking/UnrealPakViewer) ⭐ 1,453 | 🐛 38 | 🌐 C++ | 📅 2026-03-06 - Viewer and extractor for UE4 PAK archive files supporting decompression and batch extraction.
* [UnrealPakTool](https://github.com/allcoolthingsatoneplace/UnrealPakTool) ⭐ 718 | 🐛 26 | 🌐 Batchfile | 📅 2021-08-28 - Extracts and lists .pak archive files from Unreal Engine 4 games (win64).
* [repak](https://github.com/trumank/repak) ⭐ 561 | 🐛 13 | 🌐 Rust | 📅 2026-02-20 - Unreal Engine .pak file library and CLI in Rust.
* [u4pak](https://github.com/panzi/u4pak) ⭐ 561 | 🐛 11 | 🌐 Python | 📅 2022-10-30 - Python CLI to unpack, pack, list, test, and mount Unreal Engine 4 .pak archives, with detailed documentation of the archive/record/footer binary layout. See also [rust-u4pak](https://github.com/panzi/rust-u4pak) ⭐ 164 | 🐛 16 | 🌐 Rust | 📅 2023-02-01, the same author's faster, multi-threaded Rust rewrite distributed as a self-contained Windows binary.
* [UEcastoc](https://github.com/gitMenv/UEcastoc) ⭐ 92 | 🐛 17 | 🌐 Go | 📅 2024-02-11 - Work-in-progress unpacker/packer for Unreal Engine's IoStore `.ucas`/`.utoc` container format, aiming to enable modding of games that ship on the newer IoStore container instead of `.pak`.
* [UnrealModUnlocker-Public](https://github.com/IllusorySoftware/UnrealModUnlocker-Public) ⭐ 80 | 🐛 6 | 🌐 C | 📅 2023-10-16 - Unlocks loading of third-party/unpaked loose files for 90-95% of Unreal Engine 4 games, for testing and loading mods without repacking them into a `.pak`.
* [UnrealPakLoaderPlugin](https://github.com/calben/UnrealPakLoaderPlugin) ⭐ 69 | 🐛 0 | 🌐 C++ | 📅 2018-11-20 - Library simplifying runtime loading of Unreal Engine .pak files and their asset registries from within a UE project.
* [UPKUtils](https://github.com/wghost/UPKUtils) ⭐ 68 | 🐛 5 | 🌐 C++ | 📅 2022-11-08 - Set of utilities for UE3 cooked packages (.u, .upk, .umap), including texture export/import to/from DDS. Originally built for XCOM: Enemy Unknown/Within, also supports Batman: Arkham Asylum and Arkham City.
* [UnrealExporter](https://github.com/luk-gg/UnrealExporter) ⭐ 46 | 🐛 2 | 🌐 C# | 📅 2026-06-18 - Batch file exporter.
* [TocPatcher](https://github.com/kboykboy2/TocPatcher) ⭐ 33 | 🐛 4 | 🌐 C | 📅 2022-12-22 - Patches UE4 IoStore `.utoc` files for games that sign their containers, by merging a mod-generated toc with one from the game; bypasses the container-level signature check that blocks unsigned mod content.
* [CPakParser](https://github.com/TheNaeem/CPakParser) ⭐ 31 | 🐛 0 | 🌐 C++ | 📅 2023-07-12 - High-performance UE5 PAK parser with Oodle decompression support and USMAP loading.
* [Sace](https://github.com/SaceViewer/Sace) ⭐ 15 | 🐛 2 | 📅 2026-08-06 - Tool for low-level examination and hand-modification of Unreal Engine game assets.
* [Snooper](https://github.com/FModel/Snooper/tree/opengl) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2026-09-02 - OpenGL based 3D viewer for cooked UE packages.
* [Unreal Media Ripper (UMR)](https://github.com/sezero/umr) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2022-03-16 - Extracts media from Unreal UPKG files, supporting versions 63-85 with 64-bit and big-endian system support.
* [paksmith](https://github.com/r6e/paksmith) ⭐ 3 | 🐛 40 | 🌐 Rust | 📅 2026-09-03 - Cross-platform Rust tool for exploring and extracting Unreal Engine game assets from PAK archives, with glTF export support.
* [EfficientAssetRipper](https://github.com/exterminathan/EfficientAssetRipper) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-08-04 - Unpacks UE4/5 game files and exports them to Blender, with utility tools for previewing textures and combining models.

#### SDK & Structure Dumpers

* [UEVR](https://github.com/praydog/UEVR) ⭐ 4,487 | 🐛 213 | 🌐 C++ | 📅 2026-08-30 - Universal Unreal Engine VR Mod. Powerful runtime reversing tool that provides an overlay for inspecting objects, classes, and properties in almost any UE4/5 game.
* [Dumper-7](https://github.com/Encryqed/Dumper-7) ⭐ 2,240 | 🐛 40 | 🌐 C | 📅 2026-08-06 - Unreal Engine SDK generator supporting all UE4 and UE5 versions, dumping engine classes/structs/offsets from a running game via DLL injection; the de facto standard modern UE SDK dumper and basis for several other tools already listed (e.g. UETools-GUI).
* [UEDumper](https://github.com/Spuckwaffel/UEDumper) ⭐ 1,390 | 🐛 0 | 🌐 C++ | 📅 2026-04-18 - UE 4.19-5.3 reverse engineering tool for dumping SDK, analyzing structures, and identifying memory offsets.
* [UE4Dumper](https://github.com/kp7742/UE4Dumper) ⭐ 953 | 🐛 26 | 🌐 C++ | 📅 2026-03-04 - Tool for dumping Unreal Engine 4 assets and structures.
* [UnrealDumper-4.25](https://github.com/guttir14/UnrealDumper-4.25) ⭐ 617 | 🐛 20 | 🌐 C++ | 📅 2023-01-28 - Unreal Engine SDK and structure dumper for extracting runtime data from UE game binaries.
* [AndUEDumper](https://github.com/MJx0/AndUEDumper) ⭐ 473 | 🐛 18 | 🌐 C++ | 📅 2026-08-03 - Android UE4/5 dumper generating SDK and function scripts, supporting ARM64, ARM, x86, and x86\_64 ABIs.
* [IDAExecFunctionsImporter](https://github.com/Fischsalat/IDAExecFunctionsImporter) ⭐ 157 | 🐛 3 | 🌐 C++ | 📅 2026-07-18 - IDA plugin that imports Unreal Engine `exec` functions, the full generated C++ SDK, VTables, and global symbols (`GObjects`, `GNames`, etc.) from Dumper-7's `CppSDK`/`IDAMappings` output, for static analysis in IDA.
* [UETools-GUI](https://github.com/Cranch-fur/UETools-GUI) ⭐ 79 | 🐛 0 | 🌐 C++ | 📅 2026-08-18 - Dumper-7 based GUI tool for rapid debugging and SDK extraction from Unreal Engine games.
* [UnrealContainers](https://github.com/Fischsalat/UnrealContainers) ⭐ 47 | 🐛 0 | 🌐 C++ | 📅 2024-07-24 - Header-only C++ reimplementation of Unreal Engine's `TArray`, `FString`, `TSet`, `TMap`, `TSparseArray`, and `FBitArray` container types, letting external tools (SDK dumpers, hacks, analysis tooling) read and manipulate a live game's UE containers directly from process memory without linking the engine.
* [ue-version](https://github.com/AniLeo/ue-version) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2025-08-27 - Analyzes compiled Unreal Engine 4 and Unreal Engine 5 game binaries to determine the exact engine version used to build the game.
* [Gibbed.Unreflect](https://github.com/gibbed/Gibbed.Unreflect) ⭐ 9 | 🐛 1 | 🌐 C# | 📅 2022-12-08 - Runtime reflection tool for Unreal Engine games, enabling datamining of Borderlands and other UE titles through binary structure analysis.

#### Blueprint, UnrealScript & Shaders

* [UE-Explorer](https://github.com/UE-Explorer/UE-Explorer) ⭐ 357 | 🐛 4 | 🌐 C# | 📅 2026-08-15 - Package explorer and UnrealScript decompiler for classic Unreal Engine games, supporting `.upk` and `.u` files (UE1–UE3).
* [kismet-analyzer](https://github.com/trumank/kismet-analyzer) ⭐ 119 | 🐛 2 | 🌐 C# | 📅 2026-01-11 - Tools for analyzing and manipulating kismet bytecode in cooked Unreal Engine assets. Generates CFG graphs and class hierarchies from blueprint/kismet scripts.
* [UEShaderMapExtractor](https://github.com/WistfulHopes/UEShaderMapExtractor) ⭐ 55 | 🐛 0 | 🌐 C++ | 📅 2025-12-24 - Tool to extract and identify shaders from Unreal Engine material shadermaps.
* [kismet-debugger](https://github.com/trumank/kismet-debugger) ⭐ 33 | 🐛 1 | 🌐 C++ | 📅 2024-04-27 - Proof-of-concept debugger for stepping through kismet/blueprint bytecode in release-build Unreal Engine games (UE4SS mod).
* [unhood](https://github.com/yole/unhood) ⭐ 25 | 🐛 6 | 🌐 C# | 📅 2015-05-23 - Decompiler for the UnrealEngine 3 version of UnrealScript. Tested with Unreal Tournament 3 and compatible with other UE3 games (Gears of War, Mass Effect, Mirror's Edge, etc.).
* [BPPseudoCodeGen](https://github.com/Archengius/BPPseudoCodeGen) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2020-07-23 - Generate C++ pseudo-code from parsed blueprint code.

#### Maps, Saves, Localization & Mappings

* [uesave](https://github.com/trumank/uesave) ⭐ 476 | 🐛 12 | 🌐 Rust | 📅 2026-04-23 - Rust library for reading and writing Unreal Engine save files.
* [UE4-AES-Key-Extracting-Guide](https://github.com/Cracko298/UE4-AES-Key-Extracting-Guide) ⭐ 465 | 🐛 4 | 📅 2024-04-25 - Guide for extracting AES encryption keys from Unreal Engine 4 games.
* [UnrealMappingsDumper](https://github.com/TheNaeem/UnrealMappingsDumper) ⭐ 426 | 🐛 58 | 🌐 C++ | 📅 2022-12-19 - Generates .usmap mapping files for datamining UE4/5 game files.
* [Unreal-Mappings-Archive](https://github.com/TheNaeem/Unreal-Mappings-Archive) ⭐ 347 | 🐛 29 | 📅 2026-06-25 - Archive of Unreal Engine mapping files.
* [UEAESKeyFinder](https://github.com/EZFNDEV/UEAESKeyFinder) ⭐ 253 | 🐛 20 | 🌐 C# | 📅 2022-01-11 - Finds the AES decryption key of practically any Unreal Engine game.
* [stove](https://github.com/bananaturtlesandwich/stove) ⭐ 161 | 🐛 15 | 🌐 Rust | 📅 2024-12-13 - Cooked Unreal Engine map editor for viewing and modifying levels without original project files.
* [UnrealLocres](https://github.com/akintos/UnrealLocres) ⭐ 156 | 🐛 4 | 🌐 C# | 📅 2021-10-24 - Command-line tool for exporting and importing Unreal Engine 4 localization resource (.locres) files to/from CSV; the underlying library used by UnrealLocresEditor above.
* [UT4X-Converter](https://github.com/xtremexp/UT4X-Converter) ⭐ 74 | 🐛 2 | 🌐 Java | 📅 2026-08-30 - Converts Unreal Tournament maps between game versions (UT99/UT2004 → UT3/UT4 and UT4 → UT3).
* [Solicen.UEExtractor](https://github.com/SolicenTEAM/UEExtractor) ⭐ 62 | 🐛 0 | 🌐 C# | 📅 2026-08-27 - Extracts text strings from Unreal Engine `.pak`/`.ucas` archive files for game localization/translation workflows.
* [UnrealLocresEditor](https://github.com/Snoozeds/UnrealLocresEditor) ⭐ 60 | 🐛 9 | 🌐 C# | 📅 2026-01-05 - GUI tool for editing Unreal localization resource (.locres) file format.
* [Unreal Save Dumper](https://github.com/GMatrixGames/UnrealSaveDumper) ⭐ 26 | 🐛 4 | 🌐 C# | 📅 2025-07-28 - CLI program to dump UE4/5 .sav save files to JSON, displaying versioning and engine information.
* [UEFN-AES-Loader](https://github.com/Aleman-sein-Vater/UEFN-AES-Loader) ⭐ 20 | 🐛 0 | 🌐 C++ | 📅 2026-06-30 - DLL for applying AES encryption keys to decrypt encrypted UE game assets and data files.
* [UEManifestReader](https://github.com/EZFNDEV/UEManifestReader) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2020-10-05 - Reads and parses Unreal Engine build manifests.
* [t3d2map](https://github.com/hogsy/t3d2map) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2021-11-08 - Converts Unreal `.T3D` text map documents to Quake's `.MAP` brush format. See also [mildred/t3d2map](https://github.com/mildred/t3d2map) ⭐ 4 | 🐛 2 | 🌐 C++ | 📅 2024-02-03, an unrelated same-named tool converting Wheel of Time/Unreal T3D exports to other map formats.

#### Modding Frameworks & Toolkits

* [RE-UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) ⭐ 2,867 | 🐛 261 | 🌐 C++ | 📅 2026-09-03 - Lua scripting system, SDK generator, blueprint mod loader, and live property editor for UE4/5 games.
* [UE-Modding-Tools](https://github.com/Buckminsterfullerene02/UE-Modding-Tools) ⭐ 1,219 | 🐛 0 | 📅 2026-08-08 - Databank of generic UE modding tools.
* [UE\_Modding](https://github.com/Dmgvol/UE_Modding) ⭐ 587 | 🐛 0 | 📅 2026-06-10 - Comprehensive collection of guides and resources for modding Unreal Engine 4 and 5 games.
* [UE4-DDS-Tools](https://github.com/matyalatte/UE4-DDS-Tools) ⭐ 135 | 🐛 17 | 🌐 Python | 📅 2024-05-19 - Texture modding tool for Unreal Engine games; injects and extracts DDS textures from .uasset/.uexp files without needing the original source project.
* [unreal\_auto\_mod](https://github.com/Mythical-Github/unreal_auto_mod) ⭐ 47 | 🐛 1 | 🌐 Python | 📅 2025-04-10 - Tools for managing Unreal Engine mod projects and automated building.
* [UE.Toolkit](https://github.com/RyoTune/UE.Toolkit) ⭐ 15 | 🐛 1 | 🌐 C# | 📅 2026-08-28 - Modding toolkit for UE games with UObject/UDataTable inspection and editing via Reloaded II, runtime data modification.

#### DCC Plugins & ActorX (Blender / 3ds Max)

* [io\_scene\_psk\_psa](https://github.com/DarklightGames/io_scene_psk_psa) ⭐ 622 | 🐛 4 | 🌐 Python | 📅 2026-08-28 - Blender addon for importing and exporting PSK (skeletal mesh) and PSA (animation) formats used in Unreal Engine. Supports PSK/PSKX mesh import with vertex normals, extra UV channels, vertex colors, and shape keys.
* [blender3d\_import\_psk\_psa](https://github.com/Befzz/blender3d_import_psk_psa) ⭐ 563 | 🐛 38 | 🌐 Python | 📅 2023-12-21 - Blender addon for importing PSK (skeletal mesh) and PSA (animation) formats from Unreal Engine.
* [ActorX](https://github.com/gildor2/ActorX) ⭐ 101 | 🐛 1 | 🌐 C++ | 📅 2021-09-05 - Epic Games' ActorX plugin source code for Unreal skeletal animation format (PSK/PSA).
* [BlenderUmap2](https://github.com/MinshuG/BlenderUmap2) ⭐ 63 | 🐛 4 | 🌐 Python | 📅 2023-05-03 - Blender addon for importing Unreal Engine .umap/.uasset world and actor data exported by FModel.
* [SkelEdit](https://github.com/gildor2/SkelEdit) ⭐ 47 | 🐛 0 | 🌐 C++ | 📅 2020-02-29 - Cross-platform PSK/PSKX/PSA (ActorX) skeletal mesh viewer with wxWidgets UI and OpenGL renderer.
* [blender\_t3d](https://github.com/crapola/blender_t3d) ⭐ 24 | 🐛 5 | 🌐 Python | 📅 2025-06-12 - Blender import/export add-on for Unreal `.T3D` map files.
* [io\_scene\_ase](https://github.com/DarklightGames/io_scene_ase) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2026-07-16 - Blender exporter for the legacy ASE (ASCII Scene Export) format used by Unreal Engine 1 & 2 games (e.g., Unreal Tournament 2004).

#### Legacy Tools & Downloads (ModDB)

* [UnrealKey](https://github.com/devinacker/UnrealKey) ⭐ 145 | 🐛 12 | 🌐 C++ | 📅 2022-11-20 - Tool for automatically finding AES-256 decryption keys for Unreal Engine 4 encrypted pak files, by launching a game's executable and detecting the loading/decryption of encrypted paks.
* [UEDumper](https://github.com/EZFNDEV/UEDumper) ⭐ 111 | 🐛 5 | 🌐 C++ | 📅 2022-07-02 - SDK dumper for Unreal Engine games.
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

### CryEngine

* [Far-Cry-1-Source-Full](https://github.com/StrongPC123/Far-Cry-1-Source-Full) ⭐ 973 | 🐛 6 | 🌐 C++ | 📅 2024-04-09 - Full source code for Far Cry 1 by Crytek — leaked non-commercial reference release for CryEngine 1, useful for understanding original CryEngine file formats and engine internals.
* [Cryengine-Converter](https://github.com/Markemp/Cryengine-Converter) ⭐ 284 | 🐛 43 | 🌐 C# | 📅 2026-06-21 - Converts CryEngine binary asset files to Collada (.dae) for import into Blender, Maya, and 3ds Max.
* [io\_scene\_cgf\_extras](https://github.com/keyhom/io_scene_cgf_extras) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2024-06-30 - Companion utility scripts for io\_scene\_cgf, converting between CryEngine CGF/CAF and other model/animation formats.
* [DDS-Unsplitter](https://github.com/Markemp/DDS-Unsplitter) ⭐ 11 | 🐛 4 | 🌐 C# | 📅 2025-05-26 - Reassembles CryEngine split .dds texture files (where a texture is stored as a base .dds plus one or more patch/mip sidecar files) back into a single usable .dds.
* [010-Templates](https://github.com/Markemp/010-Templates) ⭐ 11 | 🐛 0 | 📅 2026-04-19 - 010 Editor binary templates for CryEngine, Lumberyard, and Open 3D Engine asset files.
  * Formats: .cgf, .chr, .skin (geometry/character/skinned mesh), .caf, .dba (animation), with a unified entry point that auto-detects CryTek / CrChF / Ivo variants.
  * Games: MechWarrior Online, ArcheAge (CryTek format), Hunt: Showdown (CrChF), Star Citizen (Ivo).
* [io\_scene\_cgf](https://github.com/keyhom/io_scene_cgf) ⭐ 8 | 🐛 4 | 🌐 Python | 📅 2024-05-20 - Blender add-on that natively imports CryEngine CGF model files.
  * Formats: .cgf (geometry), .chr (character), .skin (skinned mesh), .caf (animation), .dba (animation database), .cryxml (binary XML).
  * Games: MechWarrior Online, ArcheAge, Hunt: Showdown, Star Citizen.
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

* [Dagor Engine](https://github.com/GaijinEntertainment/DagorEngine) ⭐ 2,959 | 🐛 74 | 🌐 C++ | 📅 2026-08-16 - Open-source release of the Dagor Engine (War Thunder, Enlisted) including parts of the toolchain.
* [dagor-file-formats](https://github.com/AlexKimov/dagor-file-formats) ⭐ 4 | 🐛 0 | 📅 2024-04-16 - Community reverse-engineering research and format templates for the Dagor Engine.

### Fox Engine

* [FMDL-Studio-v2](https://github.com/BobDoleOwndU/FMDL-Studio-v2) ⭐ 54 | 🐛 6 | 🌐 ShaderLab | 📅 2025-03-26 - Unity Engine importer and exporter for Fox Engine models.
* [FoxKit](https://github.com/youarebritish/FoxKit) ⭐ 47 | 🐛 21 | 🌐 ShaderLab | 📅 2024-05-19 - General-purpose Fox Engine data editor. Includes a Route Builder for AI routes (.frt).
* [FtexTool](https://github.com/Atvaark/FtexTool) ⭐ 43 | 🐛 3 | 🌐 C# | 📅 2017-10-31 - Fox Engine Texture (.ftex) to DDS converter.
* [FoxTool](https://github.com/Atvaark/FoxTool) ⭐ 37 | 🐛 0 | 🌐 C# | 📅 2020-09-01 - Fox Engine file format parsing and manipulation tool.
* [FoxEngine.TranslationTool](https://github.com/Atvaark/FoxEngine.TranslationTool) ⭐ 28 | 🐛 8 | 🌐 C# | 📅 2025-05-18 - Translation and modding tool for Fox Engine games, providing file format parsing and manipulation.
* [mgsv-deminified-lua](https://github.com/TinManTex/mgsv-deminified-lua) ⭐ 24 | 🐛 0 | 🌐 Lua | 📅 2021-08-05 - Deminified (de-obfuscated) Lua scripts extracted from Metal Gear Solid V.
* [FileMonolith](https://github.com/morbidslinky/FileMonolith) ⭐ 21 | 🐛 1 | 🌐 C# | 📅 2025-08-22 - MGSV tool suite: archive unpacker, file proliferator, filename updater, mass texture converter, and archive transferrer.
* [MtarTool](https://github.com/BobDoleOwndU/MtarTool) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2025-12-28 - .mtar (Motion Archive) unpacker and repacker for Metal Gear Solid V: The Phantom Pain.
* [MockFox](https://github.com/TinManTex/MockFox) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2023-04-20 - Framework to load MGSV: The Phantom Pain Lua scripts outside of mgstpp.
* [FvTwool](https://github.com/BobDoleOwndU/FvTwool) ⭐ 11 | 🐛 0 | 🌐 C# | 📅 2024-07-15 - MGSV .fv2 editor.
* [FoxEngineTemplates](https://github.com/kapuragu/FoxEngineTemplates) ⭐ 10 | 🐛 1 | 📅 2026-08-13 - Collection of 010 Editor binary templates for Fox Engine file formats.
* [QuickHash](https://github.com/BobDoleOwndU/QuickHash) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2023-11-25 - Filename hashing utility for Metal Gear Solid V: The Phantom Pain.
* [GzsTool](https://github.com/BobDoleOwndU/GzsTool) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2017-05-29 - Fox Engine dat, fpk, fpkd, pftxs and sbp unpacker/repacker.
* [FoxLib](https://github.com/youarebritish/FoxLib) ⭐ 8 | 🐛 3 | 🌐 F# | 📅 2018-10-24 - Library for reading and writing Fox Engine file formats (lba, frt, fmtt, pcsp, fv2).
* [AutoPftxsTool](https://github.com/BobDoleOwndU/AutoPftxsTool) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2017-05-09 - Automatic Fox Engine .pftxs unpacker and repacker.
* [FcnpTool](https://github.com/BobDoleOwndU/FcnpTool) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2023-11-26 - Fox Engine .fcnp importer and exporter.
* [FoxKitPrototype](https://github.com/youarebritish/FoxKitPrototype) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2017-10-03 - General-purpose Fox Engine data editor; earlier prototype of FoxKit above.
* [FsmTool](https://github.com/BobDoleOwndU/FsmTool) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2025-10-01 - Experimental Fox Engine .fsm chunk extractor.
* [RiffNamer](https://github.com/kapuragu/RiffNamer) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2024-12-14 - Renames Wwise .wem RIFF sound files to their embedded filename markers, for MGSV and Fox Engine's implementation of Wwise.
* [HashWrangler](https://github.com/TinManTex/HashWrangler) ⭐ 5 | 🐛 1 | 🌐 C# | 📅 2022-12-08 - Tests lists of hashes against lists of strings using various MGSV hashing functions.
* [GzVoiceWwise](https://github.com/kapuragu/GzVoiceWwise) ⭐ 4 | 🐛 0 | 📅 2026-07-23 - Recreates unique Wwise soundbanks from Metal Gear Solid V: Ground Zeroes for use in The Phantom Pain (voice assets not included).
* [FrdvParser](https://github.com/BobDoleOwndU/FrdvParser) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2018-04-19 - Parses MGSV/SSD .frdv files.
* [VfxTool](https://github.com/youarebritish/VfxTool) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-09-11 - Compiles and decompiles Fox Engine .vfx files, which store compiled VFX node graphs.
* [SpchTool](https://github.com/kapuragu/SpchTool) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2026-07-09 - Tool for decompiling and compiling MGSV .spch TppSpeechData files. Based on youarebritish's LbaTool.
* [TrapTool](https://github.com/kapuragu/TrapTool) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2022-12-10 - Tool for decompiling and compiling Fox Engine and Metal Gear Solid V .trap GeoTrap files. Based on youarebritish's LbaTool.
* [TwpfTool](https://github.com/youarebritish/TwpfTool) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2022-01-26 - Fox Engine TWPF weather parameters unpacker.
* [FoxEngineLib](https://github.com/cra0kalo/FoxEngineLib) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2017-01-20 - Library for parsing 3D formats used by the Fox Engine in Metal Gear Solid V.
* [StpTool](https://github.com/kapuragu/StpTool) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-08-01 - Fox Engine .stp file unpacker and repacker. Based on BobDoleOwndU's AutoPftxsTool.
* [RdfTool](https://github.com/kapuragu/RdfTool) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-05-12 - Tool for decompiling and compiling MGSV .rdf files. Based on youarebritish's LbaTool.
* [LbaTool](https://github.com/youarebritish/LbaTool) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2020-10-30 - Fox Engine .lba compiler/decompiler; base for several of kapuragu's format tools above.
* [HtreTool](https://github.com/youarebritish/HtreTool) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2021-06-06 - Fox Engine HTRE terrain unpacker.
* [BruteGen](https://github.com/TinManTex/BruteGen) ⭐ 2 | 🐛 1 | 🌐 C# | 📅 2022-06-22 - Configurable string generator, useful for brute-forcing MGSV file hashes.
* [datfpk](https://github.com/unknown321/datfpk) ⭐ 2 | 🐛 2 | 🌐 Go | 📅 2025-10-20 - Packs and unpacks Metal Gear Solid V: The Phantom Pain file formats.
* [FrdvTool](https://github.com/kapuragu/FrdvTool) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-08-13 - Fox Engine .frdv importer and exporter.
* [nav2\_blender](https://github.com/kapuragu/nav2_blender) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-05-18 - Blender add-on for importing Fox Engine .nav2 files, based on JinMar's original add-on.
* [TcvpTool](https://github.com/kapuragu/TcvpTool) ⭐ 0 | 🐛 1 | 🌐 C# | 📅 2021-06-01 - Tool for parsing and compiling MGSV TppCoverPoint (.tcvp) files. Based on youarebritish's LbaTool.

### Hedgehog Engine

* [HedgeLib](https://github.com/Radfordhound/HedgeLib) ⭐ 119 | 🐛 46 | 🌐 C++ | 📅 2026-06-25 - C++ library and collection of tools that aims to make modding games in the Sonic the Hedgehog franchise easier.
* [RflTemplates](https://github.com/blueskythlikesclouds/RflTemplates) ⭐ 18 | 🐛 0 | 📅 2024-12-13 - 010 Editor binary templates for Hedgehog Engine 2 RFL files.
* [Hedgehog Engine Blender I/O](https://github.com/hedge-dev/HedgehogEngineBlenderIO) ⭐ 14 | 🐛 5 | 🌐 Python | 📅 2026-03-19 - WIP Blender add-on for Hedgehog Engine I/O including import/export and animation editing.
* [surfboard-templates](https://github.com/DeaTh-G/surfboard-templates) ⭐ 7 | 🐛 1 | 🌐 C | 📅 2024-05-10 - Templates for various versions of the SWIF file format used primarily in Hedgehog Engine games.
* [Shadow-the-Hedgehog-.BON-MTN-import-export-tool](https://github.com/Shadowth117/Shadow-the-Hedgehog-.BON-MTN-import-export-tool) ⭐ 3 | 🐛 0 | 🌐 MAXScript | 📅 2019-09-20 - Script for applying external properties from Shadow the Hedgehog .BON files to their respective bones in .DFF model files after importing with AAP's RWIO plugin for 3ds Max.
* [SonicHeroesUTXEditor](https://github.com/Heroes-Hacking-Central/SonicHeroesUTXEditor) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2025-12-12 - UTX editor for Sonic Heroes.
* [HedgehogEngineReversing](https://github.com/WistfulHopes/HedgehogEngineReversing) ⭐ 0 | 🐛 0 | 📅 2024-01-18 - BinSync project for Hedgehog Engine reversing.

### Northlight Engine

* [OpenAWE](https://github.com/OpenAWE-Project/OpenAWE) ⭐ 213 | 🐛 13 | 🌐 C++ | 📅 2026-05-16 - Open source reimplementation of the Alan Wake Engine (later known as Northlight).
* [neat](https://github.com/TomEvin/neat) ⭐ 55 | 🐛 3 | 📅 2023-10-28 - Northlight Engine Archive Tool (supports Quantum Break, Control, Alan Wake 2).
* [control-unpack](https://github.com/profMagija/control-unpack) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2021-01-09 - Extractors and converters for various Northlight file formats used in Control (rmdp, rmdl, texco, strings).
* [NorthlightFontMaker](https://github.com/eprilx/NorthlightFontMaker) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2026-07-09 - Tool for creating and editing custom bitmap fonts for the Northlight engine (\*.binfnt).
* [BlenderNorthlight](https://github.com/OpenAWE-Project/BlenderNorthlight) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-06-07 - Blender plugin for loading binmsh/binfbx files from Northlight Engine games (Control, Alan Wake 2, Quantum Break).

### Pragma Engine

* [io\_pragma\_engine](https://github.com/REDxEYE/io_pragma_engine) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2020-04-02 - Blender plugin for importing and exporting Pragma Engine models.

### Build Engine

* [Raze](https://github.com/ZDoom/Raze) ⭐ 881 | 🐛 139 | 🌐 C++ | 📅 2025-11-19 - GZDoom-derived source port for Build engine games including Duke Nukem 3D, Blood, Shadow Warrior, Redneck Rampage, Exhumed/Powerslave and Ion Fury, reading each game's original GRP/RFF/ART assets.
* [NBlood](https://github.com/NBlood/NBlood) ⭐ 800 | 🐛 115 | 🌐 C++ | 📅 2026-08-26 - Reverse-engineered source ports of Build engine games (Blood, Duke Nukem 3D, Redneck Rampage, Shadow Warrior, Exhumed, PowerSlave) based on EDuke32 engine technology.
* [jfbuild](https://github.com/jonof/jfbuild) ⭐ 135 | 🐛 3 | 🌐 C | 📅 2026-06-28 - JonoF's port of Ken Silverman's Build engine, reading the engine's native ART/MAP/GRP data. Depends on his [jfaudiolib](https://github.com/jonof/jfaudiolib) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2025-12-27 port of the AudioLib sound library used by Apogee games, and powers his [jfduke3d](https://github.com/jonof/jfduke3d) ⭐ 140 | 🐛 4 | 🌐 C | 📅 2026-01-25 and [jfsw](https://github.com/jonof/jfsw) ⭐ 99 | 🐛 3 | 🌐 C | 📅 2026-01-25 ports below.
* [vanilla\_duke3D](https://github.com/fabiensanglard/vanilla_duke3D) ⭐ 128 | 🐛 0 | 🌐 C++ | 📅 2013-01-23 - Mirror of Ken Silverman's original "Build" engine source release (GAME.EXE and companion tools), the DOS engine behind Duke Nukem 3D, Shadow Warrior, and Blood, reading the engine's native MAP/ART/GRP data.
* [Blood-RE](https://github.com/NBlood/Blood-RE) ⭐ 35 | 🐛 0 | 🌐 C++ | 📅 2025-12-06 - Source code reconstruction of Blood, reading the original game's GRP/ART/MAP data.
* [jftekwar](https://github.com/jonof/jftekwar) ⭐ 27 | 🐛 1 | 🌐 C | 📅 2026-06-03 - JonoF's Build engine port of Capstone Software's William Shatner's TekWar, reading the original game's ART/MAP/palette data. See also [jfwhaven](https://github.com/jonof/jfwhaven) ⭐ 28 | 🐛 0 | 🌐 C | 📅 2026-01-25, his port of Capstone's Witchaven.
* [slab6-mirror](https://github.com/vuolen/slab6-mirror) ⭐ 23 | 🐛 0 | 📅 2019-12-02 - Mirror of Ken Silverman's SLAB6, the voxel model viewer/editor for VOX, KVX (Build engine sprite format used by Shadow Warrior/Blood), and KV6 (Voxlap) formats.
* [buildengine](https://github.com/icculus/buildengine) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2021-07-12 - icculus.org's Linux/macOS port of Ken Silverman's Build Engine, the DOS engine behind Duke Nukem 3D, Shadow Warrior, and Blood, reading the engine's native MAP/ART/GRP data.
* [BUILD Map Importer](https://github.com/jensnt/io_import_build_map) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2025-12-02 - Blender add-on for importing BUILD maps (Blood, Duke Nukem 3D, etc.) that can auto-extract textures from `.ART`, `.GRP`, and `.RFF` files.
  * Import options: split sectors/walls/sky, preserve sprite offsets, reuse materials, shade to vertex colors, and store original map data in custom properties.
* [Build286](https://github.com/FrenkelS/Build286) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2026-02-14 - Port of Ken Silverman's Build Engine to 16-bit DOS PCs (e.g. 286 processors with VGA/MCGA graphics).
* [Blood: Fresh Supply Modding Guide](https://github.com/svkaiser/BloodEX-Modding-Docs) ⭐ 3 | 🐛 0 | 📅 2026-01-13 - Documents loading persistent and loose mod files for Blood: Fresh Supply, including its RFF and KPF resource formats.
* [Xtract (macOS port)](https://github.com/rusq/xtract) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2024-11-25 - macOS-compatible port of Xtract, extracting art assets from Build engine GRP archive files (Duke Nukem 3D, Blood, and others).
* [Build palette editing tools (Duke Nukem 3D)](https://www.moddb.com/mods/black-shadow/downloads/build-palette-editing-tools) - Tools for manipulating and creating palettes for BUILD Engine games including Duke Nukem 3D. Work in progress.

### ACK-3D

* [ACK-3D GCC](https://github.com/meh2481/ACK-3D-GCC) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2017-04-08 - Modern GCC/Code::Blocks recode of Lary Myers' 1993 "Animation Construction Kit" raycasting engine from his book *Amazing 3-D Games Adventure Set*, used in various early-90s shareware titles.

### Cobra Engine

* [cobra-tools](https://github.com/OpenNaja/cobra-tools) ⭐ 152 | 🐛 11 | 🌐 Python | 📅 2026-09-04 - Suite of GUI tools for extracting and modifying OVL and OVS archives, as well as editing associated file formats and models for the Cobra Engine (Frontier Developments).

### 3DSTATE

* [3DS MAX 5 and 3DS MAX 6 converter](https://www.moddb.com/engines/3dstate/downloads/3ds-max-5-and-3ds-max-6-converter) - Converts 3DS Max scenes to 3DSTATE WLD format, preserving lighting, shadows, and effects. Includes script for rendering to texture and converting to binary 3dstate format.

### AtiSushi Engine

* [AtiSushi](https://github.com/REDxEYE/AtiSushi) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2023-11-22 - UniLoader plugin for importing AtiSushi engine files.

### Genie Engine

* [geniedoc](https://github.com/aap/geniedoc) ⭐ 16 | 🐛 1 | 📅 2017-04-14 - Documentation of Age of Empires II .dat files (Genie Engine formats).

### Bruns Engine

* [brunsdec](https://github.com/Bioruebe/brunsdec) ⭐ 9 | 🐛 0 | 🌐 Haxe | 📅 2019-01-29 - Decryptor for Bruns Engine encrypted assets (magic number `EENC`), deriving a per-file XOR key from the file header to recover encrypted PNG images.

### Stargaze Engine

* [StargazeUnpack](https://github.com/TheIndra55/StargazeUnpack) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2022-05-25 - Extracts files from the .pack archives used by games running the Stargaze engine (Mountain Crime: Requital, Psycho Train).
  * Includes a Noesis plugin (fmt\_sf\_image.py) for viewing/exporting the engine's .pvrlzo and .pvr image formats.

### GIANTS Engine

* [I3DShapesTool](https://github.com/Donkie/I3DShapesTool) ⭐ 28 | 🐛 12 | 🌐 C# | 📅 2022-08-12 - Tool for extracting the binary .i3d.shapes mesh/shape files used by the GIANTS engine (Farming Simulator) to OBJ.
  * See also [I3dShapes](https://github.com/VirRus77/I3dShapes) ⭐ 3 | 🐛 2 | 🌐 C# | 📅 2020-02-15 for a .NET/C# library port (published on NuGet) supporting shape types 1-3 for programmatic use.

### Blitz3D / BlitzPlus

* [B3DDecomp](https://github.com/juanjp600/B3DDecomp) ⭐ 23 | 🐛 8 | 🌐 C# | 📅 2026-01-11 - Disassembler and decompiler for games built with the Blitz3D and BlitzPlus engines.

### StepMania

* [GrooveAuthor](https://github.com/PerryAsleep/GrooveAuthor) ⭐ 58 | 🐛 9 | 🌐 C# | 📅 2026-08-22 - Editor for authoring StepMania charts (.sm/.ssc), by an ITGmania maintainer.

### RPG Maker

* [EasyRPG Player](https://github.com/EasyRPG/Player) ⭐ 1,219 | 🐛 435 | 🌐 C++ | 📅 2026-09-01 - Open-source interpreter that runs RPG Maker 2000/2003 games natively, reading their LCF data formats (LMU maps, LDB/LMT databases) via liblcf.
* [RPG-Maker-MV-Decrypter](https://gitlab.com/Petschko/RPG-Maker-MV-Decrypter) - Decrypts and re-encrypts RPG Maker MV/MZ's built-in encrypted resource files (`.rpgmvp`/`.rpgmvo`/`.rpgmvm`). Moved from [GitHub](https://github.com/Petschko/RPG-Maker-MV-Decrypter) ⚠️ Archived (now read-only) to GitLab for continued development.
* [mkxp](https://github.com/Ancurio/mkxp) ⭐ 586 | 🐛 45 | 🌐 C++ | 📅 2026-01-18 - Open-source reimplementation of the Ruby Game Scripting System (RGSS) used by RPG Maker XP, VX, and VX Ace, running games natively by reading their RGSSAD/RGSS2A/RGSS3A archives. See also the more actively maintained [mkxp-z fork](https://github.com/mkxp-z/mkxp-z) ⭐ 371 | 🐛 156 | 🌐 C++ | 📅 2026-06-30.
* [EasyRPG Editor](https://github.com/EasyRPG/Editor) ⭐ 426 | 🐛 46 | 🌐 C++ | 📅 2026-07-06 - Qt6-based game editor for creating EasyRPG games; can import and edit existing RPG Maker 2000/2003 projects by reading/writing their LCF map and database files via liblcf.
* [RPGMaker\_LLM\_Translator](https://github.com/fkiliver/RPGMaker_LLM_Translator) ⭐ 162 | 🐛 0 | 🌐 Python | 📅 2025-09-27 - Local translator for RPG Maker games, feeding extracted Mtool/Translator++ game text through the Sakura/GalTransl offline LLM translation models for Japanese machine translation.
* [Luminol](https://github.com/Astrabit-ST/Luminol) ⭐ 147 | 🐛 25 | 🌐 Rust | 📅 2026-08-11 - Cross-platform RPG Maker XP/VX/VX Ace editor rewrite in Rust, reading the RGSS project data (rxdata/rvdata maps and databases).
* [liblcf](https://github.com/EasyRPG/liblcf) ⭐ 139 | 🐛 41 | 🌐 C++ | 📅 2026-08-03 - C++ library for reading and writing the LCF formats used by RPG Maker 2000/2003 and EasyRPG projects.
* [rgssad](https://github.com/luxrck/rgssad) ⭐ 41 | 🐛 0 | 🌐 Rust | 📅 2020-01-15 - Extract rgssad/rgss2a/rgss3a files from RPG Maker games.
* [RGSS-Decryptor](https://github.com/usagirei/RGSS-Decryptor) ⭐ 38 | 🐛 3 | 🌐 C# | 📅 2018-08-04 - Command-line decryptor for RGSS archives (RPG Maker XP/VX/VX Ace). See also [Bioruebe's fork](https://github.com/Bioruebe/RGSS-Decryptor) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2018-08-03 adding a Windows shell extension.
* [rmvdec](https://github.com/Bioruebe/rmvdec) ⭐ 32 | 🐛 0 | 🌐 C# | 📅 2023-01-27 - Decrypter for RPG Maker MV resource files (.rpgmvp, .rpgmvo, .rpgmvm).
* [rpga](https://github.com/elizagamedev/rpga) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2015-12-13 - RPG archive extraction and creation utility. Can extract and create RPG Maker XP+ archives and Wolf RPG archives (though Wolf archive creation does not work yet).
* [MakerLens](https://github.com/Kokoroou/rpgmaker-assets-viewer) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-05 - Browser-based, 100% client-side media viewer/extractor for RPG Maker MV, MZ, XP, VX, and VX Ace game assets.
* [rpg-game-decrypter-python](https://github.com/TTitanUA/rpg-game-decrypter-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-01 - Desktop GUI tool for decrypting RPG Maker MV/MZ encrypted media files; also extracts Ren'Py .rpa archives.
* [LoreInsight](https://github.com/Kokoroou/lore-insight) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-11 - Browser-based, 100% offline visualizer for RPG Maker MV/MZ event flow, parsing `Map###.json`, `CommonEvents.json`, and `MapInfos.json` into an interactive node graph of dialogue, choices, conditions, and jumps.

### Wolf RPG Editor

*Japanese doujin/indie game authoring engine used by many titles (Ao Oni, Mad Father, Ib, Yume Nikki-likes, etc.).*

* [UberWolf](https://github.com/Sinflower/UberWolf) ⭐ 181 | 🐛 1 | 🌐 C++ | 📅 2026-08-08 - GUI decrypter/unpacker for Wolf RPG Editor games, extracting encrypted `.wolf` data archives and decrypting protected game/mod files.

### SRPG Studio

*Japanese tactical/strategy RPG creation engine ("SRPG Studio").*

* [SRPGStudioReverseTools](https://github.com/HNIdesu/SRPGStudioReverseTools) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-05-04 - Scripts to decrypt, unpack, and repack the files generated by SRPG Studio.

### Ren'Py

*Visual novel engine used in many indie and commercial visual novels.*

* [unrpyc](https://github.com/CensoredUsername/unrpyc) ⭐ 1,242 | 🐛 11 | 🌐 Ren'Py | 📅 2026-02-24 - Decompiler that reconstructs readable Ren'Py .rpy script source from compiled .rpyc bytecode files.
* [unrpa](https://github.com/Lattyware/unrpa) ⭐ 760 | 🐛 20 | 🌐 Python | 📅 2022-06-27 - Program to extract files from the RPA archive format used in Ren'Py visual novels.
* [rpycdec](https://github.com/cnfatal/rpycdec) ⭐ 54 | 🐛 2 | 🌐 Python | 📅 2026-08-22 - Actively maintained tool for decompiling Ren'Py compiled script files.
  * Formats: `.rpyc`/`.rpymc` bytecode, `.rpa` archives, `.save` save files.
  * Features: decompiles to readable script code, extracts/creates RPA archives, extracts and edits save files (via JSON round-trip), extracts games from Android APKs, and extracts translations to `tl/{language}/` directories; supports Ren'Py 7.x and 8.x.
* [Rentool](https://github.com/Sirpixelalot/Rentool) ⭐ 13 | 🐛 0 | 🌐 Kotlin | 📅 2025-11-28 - Android toolkit for Ren'Py game modding: extracts and creates RPA archives, decompiles RPYC bytecode back into readable .rpy scripts, and compresses game assets, all on-device.
* [rpa-extractor](https://github.com/abhishek-s12/rpa-extractor) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - Extraction tool for Ren'Py RPA archive files.

### AliceSoft (Alice/System 4 Engine)

*Visual novel engine(s) ("System 3"/"System 4"/AinScript) by AliceSoft.*

* [alice-tools](https://github.com/nunuhara/alice-tools) ⭐ 184 | 🐛 7 | 🌐 C | 📅 2026-08-12 - Tools for extracting/editing files from AliceSoft games (AinScript decompiler/compiler, ALD/AJP/DCF/PMS asset tools, and more).
* [xsystem4](https://github.com/nunuhara/xsystem4) ⭐ 95 | 🐛 6 | 🌐 C | 📅 2026-08-26 - Cross-platform, open-source reimplementation of AliceSoft's System 4 engine, running original AliceSoft game data.
* [FNLib](https://github.com/marcussacana/FNLib) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2021-11-11 - Font editor library for the AliceSoft engine.

### Aquaplus (Leaf)

* [AquaPlusEditor](https://github.com/marcussacana/AquaPlusEditor) ⭐ 15 | 🐛 1 | 🌐 C# | 📅 2024-04-24 - Editor for Aquaplus (Leaf) visual novel engine files.

#### ToHeart2 DX PLUS

* [TH2DXP\_KIT](https://github.com/hiroshil/TH2DXP_KIT) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-14 - Localization toolkit for the PS3 version of *ToHeart2 DX PLUS*.
  * Tools: `dat_tool.py` (DAT archive extraction/repacking), `scenario_eboot_tool.py` (scenario script extraction from the EBOOT), `tpl_image_tool.py` (TPL image conversion).

#### Utawarerumono

* [UtaMeshExtractor](https://github.com/Pohrom/UtaMeshExtractor) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2016-12-31 - Extracts textures and MDL models (converted to Wavefront OBJ) from the PS3 version of *Utawarerumono: Mask of Deception*.

### Escude

* [EscudeTools](https://github.com/Chenx221/EscudeTools) ⭐ 40 | 🐛 1 | 🌐 C# | 📅 2025-12-30 - Tools for extracting and repacking Escude engine visual novel files, tested on newer titles.
* [EscudeEditor](https://github.com/marcussacana/EscudeEditor) ⭐ 27 | 🐛 1 | 🌐 C# | 📅 2018-06-18 - Editor for the Escude engine's BIN scripts and packages.
* [Bincude](https://github.com/TheVNConnoisseur/Bincude) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2026-06-11 - Tool for creating and unpacking Escude engine `.BIN` archives.

### Eushully

*Visual novel engine used by Eushully's games.*

* [Agf2Bmp2Agf](https://github.com/Zoltanar/Agf2Bmp2Agf) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2024-03-31 - Converts AGF image files used in Eushully games to BMP and back.
* [EushullyEditor](https://github.com/marcussacana/EushullyEditor) ⭐ 9 | 🐛 1 | 🌐 C# | 📅 2021-03-12 - Editor for Eushully engine visual novel files.

### Mware

*"Mware" visual novel engine.*

* [MwareStuff](https://github.com/marcussacana/MwareStuff) ⭐ 96 | 🐛 4 | 🌐 C# | 📅 2026-09-05 - Tools for working with Mware engine visual novel files.

### Unison Shift

* [UnisonShiftManager](https://github.com/marcussacana/UnisonShiftManager) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2019-10-06 - Extracts and repacks Unison Shift's (Ley-Line series) PAC and DAT archive files.

### BGI (Buriko General Interpreter)

*Visual novel engine (Ethornell) used by many Japanese visual novels.*

* [BGIKit](https://github.com/xupefei/BGIKit) ⚠️ Archived - Script decoder and encoder for the Ethornell/BGI visual novel engine (archived).
* [EthornellTools](https://github.com/arcusmaximus/EthornellTools) ⚠️ Archived - Tools for the Buriko General Interpreter (BGI)/Ethornell visual novel engine.
  * See also [VNTranslationTools](https://github.com/arcusmaximus/VNTranslationTools) ⚠️ Archived above for translating BGI scenario scripts.
  * Tools: BgiDisassembler (disassembles internal system `._bp` scripts), BgiImageEncoder (encodes images to the engine's proprietary CompressedBG format).
* [openbgi](https://github.com/Cytlan/openbgi) ⭐ 70 | 🐛 0 | 🌐 C | 📅 2026-08-26 - Open-source reimplementation of the Ethornell/BGI (Buriko General Interpreter) visual novel engine.
* [BGITool](https://github.com/xmoezzz/BGITool) ⭐ 59 | 🐛 0 | 🌐 C | 📅 2017-12-26 - Tools for working with the BGI visual novel engine, including BGIDev for scene script decompilation.
* [arc-reader](https://github.com/minirop/arc-reader) ⭐ 42 | 🐛 2 | 🌐 C | 📅 2015-09-06 - Reads and extracts files from BGI engine `.arc` archives (OverDrive/MangaGamer). See also [arc-reader-rs](https://github.com/lxl66566/arc-reader-rs) ⭐ 6 | 🐛 1 | 🌐 Rust | 📅 2026-09-01, a Rust port/rewrite.
* [Bgi\_script\_tools](https://github.com/mchubby-3rdparty/Bgi_script_tools) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2019-04-14 - Python 3 scripts (originally by kingshriek) to process extension-less BGI 1.69 scripts (e.g. Eustia's `Scenario0000`).
* [Bgi\_asdis](https://github.com/KlparetlR/Bgi_asdis) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2026-05-03 - Disassembler and assembler for BGI (Buriko General Interpreter)/Ethornell binary script files.
* [EthornellEditor](https://github.com/marcussacana/EthornellEditor) ⭐ 29 | 🐛 1 | 🌐 C# | 📅 2022-07-10 - Translation tool for Buriko General Interpreter (BGI/Ethornell) engine scripts (BGI v2; BSE scripts not supported).
* [BGIScrViewer](https://github.com/thefoggycity/BGIScrViewer) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2019-09-24 - GUI tool for viewing decompressed scripts of BGI visual novel games.
* [BGI\_Script\_Tool](https://github.com/crskycode/BGI_Script_Tool) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2021-06-27 - Exports and rebuilds text strings from BGI engine scripts (excluding the internal `._bp` files handled by EthornellTools' BgiDisassembler above).
* [BGI\_Pack\_Tool](https://github.com/crskycode/BGI_Pack_Tool) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2021-04-05 - Creates BGI engine archive files. See also the author's earlier [BGIArcPack](https://github.com/crskycode/BGIArcPack) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2021-03-02.
* [BGI\_BM\_Converter](https://github.com/Lite0812/BGI_BM_Converter) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-04-29 - Converts BGI (Buriko General Interpreter)/Ethornell engine `.bm` image files.
* [BGI](https://github.com/txt231/BGI) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2026-08-02 - Experimental reimplementation of the BGI (Buriko General Interpreter) visual novel engine: bytecode VM emulator (BGITool), opcode disassembler (BGIPiler) and tracer (BGITracer), and a resource viewer (BGIExplorer) for BGI's texture/bitmap formats.
* [BGIDscCompressor](https://github.com/akiWagashi/BGIDscCompressor) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-08-24 - Compresses/decompresses files for the Ethornell/Buriko General Interpreter (BGI) visual novel engine.

### RealLive

*Visual novel engine used by Key (Clannad, Kanon, Little Busters!), Circus, and other Japanese publishers.*

* [rlvm](https://github.com/eglaysher/rlvm) ⭐ 167 | 🐛 22 | 🌐 C++ | 📅 2024-09-08 - Open-source RealLive engine clone for Linux and macOS, reading original RealLive visual novel game data.
* [rldev](https://github.com/eglaysher/rldev) ⭐ 53 | 🐛 1 | 🌐 OCaml | 📅 2022-04-09 - RealLive development kit: compiler/decompiler for RealLive bytecode (`.ke`/`.rl` sources to `SEEN.TXT`), plus archive and asset tools, by the same author as rlvm. See also [theappleman's fork](https://github.com/theappleman/rldev) ⭐ 17 | 🐛 1 | 🌐 OCaml | 📅 2016-11-14 with fixes for the Little Busters! fan translation project.
* [nwa](https://github.com/hasenbanck/nwa) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2019-07-17 - Go library for decoding NWA, RealLive's compressed sound format.

### Kirikiri

*Visual novel engine (KAG/TJS scripting) used by many Japanese visual novels.*

* [Kirikiroid2](https://github.com/zeas2/Kirikiroid2) ⭐ 2,929 | 🐛 130 | 🌐 C++ | 📅 2024-06-05 - Cross-platform (Android and other) port of the Kirikiri2/KirikiriZ engine, running original Kirikiri visual novel game data.
* [KrkrExtract](https://github.com/xmoezzz/KrkrExtract) ⚠️ Archived - Extracts and repacks Kirikiri krkr2/krkrz XP3 archives. No longer maintained; see also the actively maintained successor [KrkrzExtract](https://github.com/xmoezzz/KrkrzExtract) ⭐ 264 | 🐛 9 | 🌐 C | 📅 2026-08-25.
* [krkrz](https://github.com/krkrz/krkrz) ⭐ 946 | 🐛 64 | 🌐 C++ | 📅 2024-03-24 - The official Kirikiri Z (KAG3/TJS2) visual novel engine project itself, including the runtime, TJS2 script compiler/VM, and XP3 archive support - upstream for many of the tools below.
* [KirikiriTools](https://github.com/arcusmaximus/KirikiriTools) ⚠️ Archived - Toolset for the Kirikiri visual novel engine.
  * See also [VNTranslationTools](https://github.com/arcusmaximus/VNTranslationTools) ⚠️ Archived above for translating Kirikiri scripts.
  * Tools: KirikiriDescrambler (descrambles/decompresses obfuscated `.ks`/`.tjs` plaintext scripts), KirikiriUnencryptedArchive (`version.dll` injection making games accept unencrypted .xp3 archives, with support for extracting encrypted/hashed file names), Xp3Pack (creates unencrypted .xp3 patch archives for use with the DLL).
* [krkrsdl2](https://github.com/krkrsdl2/krkrsdl2) ⭐ 431 | 🐛 32 | 🌐 C++ | 📅 2026-08-31 - Port of the KirikiriZ engine to platforms supported by SDL2 (macOS, Linux), running original Kirikiri game data.
* [KrkrDump](https://github.com/crskycode/KrkrDump) ⭐ 308 | 🐛 0 | 🌐 C++ | 📅 2025-09-27 - Extracts files from newer versions of the Kirikiri Z engine.
* [VisualNovelUpscaler](https://github.com/hokejyo/VisualNovelUpscaler) ⭐ 144 | 🐛 3 | 🌐 Python | 📅 2022-07-17 - One-click AI upscaling remaster tool for Kirikiri2/Z and Artemis engine visual novels; unpacks archives, converts TLG images to PNG, upscales with waifu2x/Real-ESRGAN/RealSR, and repacks.
* [KrKrZSceneManager](https://github.com/marcussacana/KrKrZSceneManager) ⭐ 111 | 🐛 0 | 🌐 C# | 📅 2023-05-24 - Scene/script manager (KiriKiriZSM) for the KirikiriZ engine.
* [KrkrExtractForCxdecV2](https://github.com/YeLikesss/KrkrExtractForCxdecV2) ⭐ 92 | 🐛 0 | 🌐 C++ | 📅 2024-06-09 - Dynamic extractor for Wamsoft's KrkrZ engine builds using the Cxdec/Hxv4 encryption scheme (2021.11+ runtime), also dumping the string hashes needed to recover original file/directory names.
* [kirikiri2](https://github.com/jeeb/kirikiri2) ⭐ 72 | 🐛 0 | 🌐 C++ | 📅 2017-02-28 - Git-svn mirror of the original Kirikiri2 engine's SVN repository, the pre-Z source many of the tools above reverse engineer against.
* [KrkrPatch](https://github.com/crskycode/KrkrPatch) ⭐ 61 | 🐛 0 | 🌐 C++ | 📅 2026-02-25 - Universal patch extension that enables file extraction/analysis on newer Kirikiri-based games.
* [hxv4\_unhash\_tools](https://github.com/MLChinoo/hxv4_unhash_tools) ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2026-08-31 - Recovers original file/directory names from hxv4-hashed Kirikiri XP3 archive contents (scripts, voice, sound, images, video), developed against Dracu-Riot! with partial support for other hxv4-crypted titles.
* [HxGamePatch](https://github.com/pkuislm/HxGamePatch) ⭐ 39 | 🐛 0 | 🌐 C++ | 📅 2023-01-06 - Patch enabling file extraction/analysis on newer Kirikiri-based games with updated encryption schemes.
* [xp3-brute](https://github.com/xmoezzz/xp3-brute) ⭐ 34 | 🐛 1 | 🌐 Rust | 📅 2026-08-25 - Unpacks, packs, and modifies Kirikiri (krkr) XP3 archives.
* [tjs2-decompiler](https://github.com/crate-1556/tjs2-decompiler) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2026-03-16 - TJS2 (TJS2100) bytecode decompiler, converting compiled Kirikiri script bytecode back into readable/executable TJS2 source. See also [tjs2Decompiler](https://github.com/xmoezzz/tjs2Decompiler) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2026-08-24, a Rust TJS2 (Kirikiri2/Kirikiri-Z) bytecode loader and decompiler.
* [KirikiriSharp](https://github.com/Project-AZUSA/KirikiriSharp) ⭐ 27 | 🐛 2 | 🌐 C# | 📅 2019-06-01 - Work-in-progress .NET parser for Kirikiri KAG/TJS visual novel scripting, used to inspect the engine's internal principles/mechanisms. Fork of [planetarian/KirikiriSharp](https://github.com/planetarian/KirikiriSharp) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2016-09-16.
* [Fuck\_Cxdec\_Check](https://github.com/1F1E33-float32/Fuck_Cxdec_Check) ⭐ 25 | 🐛 0 | 🌐 C++ | 📅 2025-02-08 - Patch bypassing the executable integrity check and disabling ASLR on recent Cxdec-protected KirikiriZ engine builds, to allow further analysis/extraction.
* [cxdec-hxv4-static-analysis](https://github.com/hktkqj/cxdec-hxv4-static-analysis) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-07-09 - Research toolkit/documentation for Cxdec/Hxv4-encrypted Kirikiri game assets, covering offline encryption-parameter recovery and verification, extraction, and TJS2 bytecode analysis.
* [Xp3Viewer-AfterStory](https://github.com/Inori/Xp3Viewer-AfterStory) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2015-03-10 - Updated viewer for Kirikiri's XP3 archive format.
* [tlg-wic-codec](https://github.com/krkrz/tlg-wic-codec) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2018-07-11 - Kirikiri TLG image codec for the Windows Imaging Component.
* [KrkrDataLoader](https://github.com/pjh456/KrkrDataLoader) ⭐ 12 | 🐛 0 | 🌐 Java | 📅 2025-02-14 - Loader/dumper for Kirikiri engine `.xp3` archive data and TJS2 script bytecode.
* [tlg\_rs](https://github.com/Forlos/tlg_rs) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2020-08-19 - Rust CLI for converting Kirikiri's TLG image format (TLG0.0/TLG6.0) to PNG.
* [amv\_decoder](https://github.com/xmoezzz/amv_decoder) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-08-25 - Experimental parser/decoder for AMV video files used by the KiriKiri2/KiriKiriZ engine. See also [AlphaMovieDecoder](https://github.com/xmoezzz/AlphaMovieDecoder) ⭐ 41 | 🐛 5 | 🌐 Common Lisp | 📅 2025-12-16, a Common Lisp implementation of the same format.
* [Cxdec\_Tools](https://github.com/1F1E33-float32/Cxdec_Tools) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-07-03 - Fully static recovery of Cxdec-encrypted resource filenames and data (no running game process required), recovering XP3 archive contents and dumping resources.
* [KrkrPbdStandViewer](https://github.com/YeLikesss/KrkrPbdStandViewer) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2026-07-21 - Viewer for Wamsoft's Kirikiri Z PBD standing-image format.
* [psdfile](https://github.com/wamsoft/psdfile) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2026-08-29 - Kirikiri Z plugin for reading (and editing/writing) Photoshop PSD files: parses layer structure, extracts per-layer or merged images, and exposes individual layers as a `psd://` virtual storage path. PSD parsing/encoding core is split out into [psdparse](https://github.com/wamsoft/psdparse) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-08-19.
* [KrkrzPack](https://github.com/crskycode/KrkrzPack) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2021-02-28 - Creates archives for the KirikiriZ engine.
* [krdevui](https://github.com/krkrz/krdevui) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2015-06-25 - Kirikiri development-time tools: an archiver for building/inspecting XP3 archives, a loop tuner, and other engine dev utilities.
* [csvParser](https://github.com/crskycode/csvParser) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2021-08-18 - Kirikiri CSV data-file parser plugin, with KirikiriZ support.
* [fcf-editor](https://github.com/dorobo-hamster/fcf-editor) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2015-03-15 - Editor for FCF flowchart files used by the TypeMoon-modified version of Kirikiri to manage scene flow. See also [Hintay's fork](https://github.com/Hintay/fcf-editor) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2017-09-02 with a fix for loading multiple flag operations.
* [SDBManager](https://github.com/marcussacana/SDBManager) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2020-12-25 - Editor for the older Kirikiri SDB file format.
* [wic](https://github.com/krkrz/wic) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2017-12-24 - Kirikiri plugin adding GIF, ICO, and TIFF image read support (plus TIFF write) via the Windows Imaging Component.
* [KrkrDump-Hasher](https://github.com/MLChinoo/KrkrDump-Hasher) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2025-07-30 - Companion hashing utility for KrkrDump, computing the hashes needed to identify Kirikiri engine script functions.
* [TjsParser](https://github.com/MLChinoo/TjsParser) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-07-30 - C# parser for Kirikiri/KRKRZ TJS2 plaintext scripts, producing a strongly-typed AST/JSON output; also parses the `KBAD100` binary Dictionary/Array data format and detects whether a given file is TJS2100 bytecode, plaintext, or KBAD100 binary.
* [serde\_tjs](https://github.com/lifegpc/serde_tjs) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-11-20 - Rust Serde serialization/deserialization library for TJS2 data structures.

### ONScripter

*Visual novel engine (NScripter-compatible) used by many freeware/doujin visual novels.*

* [OnscripterYuri](https://github.com/YuriSizuku/OnscripterYuri) ⭐ 844 | 🐛 17 | 🌐 C++ | 📅 2026-06-23 - Enhanced ONScripter engine port, running original ONScripter/NScripter game data across many platforms, with a focus on web (Emscripten/WASM).
* [nscript.dat-tool](https://github.com/danmig06/nscript.dat-tool) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2026-01-27 - Extraction/repacking tool for the `nscript.dat` script format used by NScripter/ONScripter-family engines.
* [OpenARC](https://github.com/Nyarstot/OpenARC) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2024-08-04 - Decoder/encoder for the .arc archive format used by the ONScripter visual novel engine, based on the archive codebase from ONScripter-EN.

### Light.vn

*Visual novel engine (lightvn.net).*

* [Light.vnTools](https://github.com/bungaku-moe/Light.vnTools) ⭐ 27 | 🐛 0 | 🌐 C# | 📅 2025-09-25 - Unpack/decrypt and repack/encrypt tool for games made with the Light.vn visual novel engine (.vndat/.mcdat files).

### C,system Engine

*Visual novel engine ("C,system") by Cyberworks, used in various Japanese visual novels.*

* [CSystemTools](https://github.com/arcusmaximus/CSystemTools) ⚠️ Archived - Script and image unpacking/repacking tool for the Cyberworks "C,system" visual novel engine (Arc00-Arc09.dat index/content files); images convert automatically to/from PNG. See also [VNTranslationTools](https://github.com/arcusmaximus/VNTranslationTools) ⚠️ Archived for translating the extracted scenario scripts.
* [betterfpk](https://github.com/Anonym271/betterfpk) ⭐ 9 | 🐛 1 | 🌐 C++ | 📅 2025-07-14 - Cyberworks "C,system" FPK archive tool with ZLC compression support, tested with TsuyokissNext.
* [SystemCScriptManager](https://github.com/marcussacana/SystemCScriptManager) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2021-03-12 - DLL library for building custom string editors for the Cyberworks "C,system" engine's scripts.
* [SystemCTools](https://github.com/lunaswd/SystemCTools) ⭐ 4 | 🐛 0 | 📅 2023-09-06 - Additional tools for the Cyberworks "C,system" visual novel engine.

### CatSystem2

*Visual novel engine ("CatSystem2") by CSware, used in various Japanese visual novels.*

* [TriggersTools.CatSystem2](https://github.com/trigger-segfault/TriggersTools.CatSystem2) ⭐ 78 | 🐛 6 | 🌐 C# | 📅 2019-03-28 - .NET library for extracting from and working with CatSystem2 visual novel engine files: decrypts/extracts KIF int archives, extracts HG-2/HG-3 images, and decompiles CST/FES/ANM scripts into a modifiable, recompilable state.
* [CatSceneEditor](https://github.com/marcussacana/CatSceneEditor) ⭐ 45 | 🐛 1 | 🌐 C# | 📅 2023-09-02 - Scene/script editor (CSE) for the CatSystem2 visual novel engine.
* [FelineSystem2](https://github.com/kokseen1/FelineSystem2) ⭐ 39 | 🐛 17 | 🌐 C++ | 📅 2023-06-01 - Open-source remake of the CatSystem2 visual novel engine, reading original game script and asset data.
* [CatSystem2-Simple-Translating-Tools](https://github.com/Wolverator/CatSystem2-Simple-Translating-Tools) ⭐ 32 | 🐛 3 | 🌐 Python | 📅 2024-10-20 - Single-click tools to extract movies, images, and text from CatSystem2 games into an editable state and pack them back.
* [catsystem-py](https://github.com/trigger-segfault/catsystem-py) ⭐ 26 | 🐛 1 | 🌐 Python | 📅 2022-02-15 - Work-in-progress Python library, tools, and documentation created while reversing the CatSystem 1 and 2 VN engines.
* [GrisaiaExtractor](https://github.com/trigger-segfault/GrisaiaExtractor) ⭐ 14 | 🐛 4 | 🌐 C# | 📅 2019-01-20 - Ripping tool (primarily for images) for the Grisaia series, which uses CatSystem2's KIFINT archive and HG3 image formats.
* [unPAK](https://github.com/NameSubjecttoChange/unPAK) ⭐ 9 | 🐛 1 | 🌐 C# | 📅 2019-11-04 - Packer/unpacker for `.PAK` files from the PS Vita port of CatSystem2.
* [GrisaiaSpriteViewer](https://github.com/trigger-segfault/GrisaiaSpriteViewer) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2020-05-10 - Sprite viewer and saver for character sprites extracted from the Grisaia series.
* [CatSystem2Tool](https://github.com/akiWagashi/CatSystem2Tool) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-08-28 - Unpacks and repacks CatSystem2 engine `.int` archives.

### Propeller Engine

*Visual novel engine ("Propeller") used by a handful of Japanese visual novels.*

* [propeller-tools](https://github.com/vn-tools/propeller-tools) ⚠️ Archived - Fan-translation toolkit for the Propeller engine (tested on Sukimazakura to Uso no Machi): MPK archive packer/unpacker, MSC script (de)compiler, and MGR image container packer/unpacker (archived).

### Whale Engine

*Visual novel engine ("Whale") used by a handful of Japanese visual novels.*

* [whale-tools](https://github.com/vn-tools/whale-tools) ⚠️ Archived - Fan-translation toolkit for Whale-engine games (tested on Tsujidou-san no Junai Road): repacks the engine's .dat script/asset archives (archived).

### AaruSystem Engine

*Visual novel engine ("AaruSystem") used in various Japanese visual novels.*

* [AaruSystemTools](https://github.com/crskycode/AaruSystemTools) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-04-27 - Extracts and repacks AaruSystem engine resource packs (`.FL4` archives).

### ADVSYS3 Engine

*Visual novel engine ("ADVSYS3") used in various Japanese visual novels.*

* [ADVSYS3-ENGINE-TOOLS](https://github.com/HOKORISAMA/ADVSYS3-ENGINE-TOOLS) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-10-14 - Extraction/repacking tools for ADVSYS3 engine archives and scripts.

### AILSystem Engine

*Visual novel engine ("AILSystem") used in various Japanese visual novels.*

* [AILSOFT-AIL-Engine-Tools](https://github.com/HOKORISAMA/AILSOFT-AIL-Engine-Tools) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2024-12-28 - Extracts/repacks AIL engine `Sall`-format resource archives, and disassembles/reassembles the engine's compiled scripts.
* [AIL\_Tools](https://github.com/crskycode/AIL_Tools) ⭐ 5 | 🐛 1 | 🌐 C# | 📅 2025-06-08 - Extracts and repacks AILSystem engine resource packs (`.DAT`/`.SNL` archives).

### Artemis Engine

*Visual novel engine ("Artemis") used in various Japanese visual novels.*

* [pfs\_upk](https://github.com/nextgal/pfs_upk) ⭐ 102 | 🐛 4 | 🌐 C++ | 📅 2023-06-29 - Simple unpacker/packer for Artemis engine `.pfs` archives.
* [pfs-rs](https://github.com/sakarie9/pfs-rs) ⭐ 41 | 🐛 0 | 🌐 Rust | 📅 2026-03-30 - Unpacker and packer for Artemis engine `.pfs` archives, written in Rust.
* [Artemis\_Pack\_Tool](https://github.com/crskycode/Artemis_Pack_Tool) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2022-07-31 - Creates Artemis engine `.pfs` archive files.
* [artemis\_ast](https://github.com/xmoezzz/artemis_ast) ⭐ 13 | 🐛 1 | 🌐 Rust | 📅 2023-09-13 - Parser/compiler for Artemis engine `.ast` script bytecode.

### AVG32

*Visual novel engine ("AVG32") used in various Japanese visual novels.*

* [adieu](https://github.com/Ruin0x11/adieu) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2021-02-07 - Bytecode parser and disassembler for the AVG32 visual novel engine.

### AVGEngine V2 / GxEngine V3

*Visual novel engine ("AVGEngine V2"/"GxEngine V3") used in various Japanese visual novels.*

* [AVGEngineV2\_Tool](https://github.com/akiWagashi/AVGEngineV2_Tool) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2024-10-15 - Extraction/repacking tool for AVGEngine V2/GxEngine V3 visual novel engine files.

### Bishop Engine

*Visual novel engine ("Bishop") used in various Japanese visual novels.*

* [BSXScript\_Tool](https://github.com/crskycode/BSXScript_Tool) ⭐ 24 | 🐛 2 | 🌐 C# | 📅 2022-07-31 - Export/import tool for `BSXScript 3.0` script files used by the Bishop engine.
* [Bishop\_BSG\_Tool](https://github.com/crskycode/Bishop_BSG_Tool) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2025-08-06 - Converts PNG images to BSG (BSS-Graphics) UI graphics files for the Bishop engine.

### Circus (Mes Engine)

*Visual novel engine ("Mes") used by Circus, Ivory, and other Japanese visual novel developers.*

* [MesTextTool](https://github.com/cokkeijigen/MesTextTool) ⭐ 34 | 🐛 0 | 🌐 C++ | 📅 2026-09-04 - Script text export/import tool for the Circus "Mes" engine.

### CIS Engine

*Visual novel engine ("CIS") used in various Japanese visual novels.*

* [CIS\_Tools](https://github.com/crskycode/CIS_Tools) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-04-27 - Extracts and repacks CIS engine resource packs (extensionless `data`, `data2`, `data3`, ... files).

### DDSystem

*Visual novel engine ("DDSystem"/DDPSystem) used in various Japanese visual novels.*

* [DDSystem](https://github.com/vagmr/DDSystem) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2025-03-28 - GUI and CLI packer/unpacker for the engine's `DDP2` and `DDP3` archive formats.

### Debonosu Works Engine

*Visual novel engine used by Debonosu Works.*

* [DebonosuWorks\_Tools](https://github.com/Karaik/DebonosuWorks_Tools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-12-17 - Lists, extracts, repacks, and decompiles Debonosu Works engine `.pak` archives.
* [Debonosu\_Works\_Script\_tools](https://github.com/HOKORISAMA/Debonosu_Works_Script_tools) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2025-01-02 - Script extraction/repacking tool for the Debonosu Works engine.

### Edoire

*Unity-based visual novel engine ("Edoire") used in various Japanese visual novels.*

* [EdoireTools](https://github.com/crskycode/EdoireTools) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2026-02-12 - Extracts and repacks Edoire engine resource packs (`.arc` archives with `@ARCH000` header).

### elf / Silky's

*Visual novel engine used by elf and its "Silky's" branded games (predecessor to the later AI6WIN-based Silky Engine).*

* [elf-tools](https://github.com/nunuhara/elf-tools) ⭐ 34 | 🐛 0 | 🌐 C | 📅 2026-07-20 - Tools for viewing and editing file formats used in elf and Silky's games.

### EntisGLS

*Visual novel engine ("EntisGLS") used in various Japanese visual novels.*

* [EntisGLS\_Tools (CSX Tools)](https://github.com/crskycode/EntisGLS_Tools) ⭐ 34 | 🐛 0 | 🌐 C# | 📅 2026-03-17 - Script text export/import tool for EntisGLS `.csx` script files; CSXTool targets 1.x engine versions and CSXToolPlus targets 2.x-3.x.

### FamilyAdvSystem Engine

*Visual novel engine ("FamilyAdvSystem") used in various Japanese visual novels.*

* [CSAF\_Tool](https://github.com/akiWagashi/CSAF_Tool) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-08-24 - Extracts resources from CSAF archives (signature `0x43 0x53 0x41 0x46`) of the FamilyAdvSystem visual novel engine, created based on a GARbro issue.

### Famous Writer

*Visual novel engine ("Famous Writer") used in various Japanese gal games.*

* [gakuen\_handsome](https://github.com/lennylxx/gakuen_handsome) ⭐ 3 | 🐛 3 | 🌐 C++ | 📅 2017-12-28 - Reverse engineering of the FWD binary archive format used by Famous Writer, documenting the header/entry-offset table layout and script checksum calculation, created for a Chinese fan translation of Gakuen Handsome (学園ハンサム).

### FFA System Engine

*Visual novel engine ("FFA System") used in various Japanese visual novels.*

* [FFA-SYSTEM-Tools](https://github.com/HOKORISAMA/FFA-SYSTEM-Tools) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-05-16 - Extraction/repacking tools for FFA System engine archives and scripts.
* [BlackPackageImageTool](https://github.com/HOKORISAMA/BlackPackageImageTool) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-01-01 - Converts FFA System engine `.bp`/Black Package image files to/from PNG.

### FVP Engine

*Visual novel engine ("FVP") used in various Japanese visual novels.*

* [rfvp](https://github.com/xmoezzz/rfvp) ⭐ 131 | 🐛 2 | 🌐 Rust | 📅 2026-08-21 - Non-official Rust reimplementation of the FVP engine and IDE, running games directly from their original `.hcb` script/asset files, with a debug HUD, custom-font support, and UTF-8/GBK translated-text encoding switching.
* [fvp](https://github.com/akerou/fvp) ⭐ 42 | 🐛 0 | 🌐 C++ | 📅 2015-07-03 - All-in-one tool for FVP-engine games by FAVORITE, covering script/archive extraction and repacking.
* [ShinkuToolset](https://github.com/xmoezzz/ShinkuToolset) ⭐ 39 | 🐛 0 | 🌐 Lua | 📅 2024-04-28 - Translation toolset for FVP-engine games by FAVORITE.
* [fvp-unpacker](https://github.com/Nikaidou-Shinku/fvp-unpacker) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-01-12 - Unpacks FVP `.bin` archives, with image extraction and tachie (立ち絵) layer composition support.
* [fvp-rs](https://github.com/lxl66566/fvp-rs) ⭐ 0 | 🐛 2 | 🌐 Rust | 📅 2026-03-01 - Rust library and CLI for packing and unpacking FVP engine `.bin` archives, mainly used for the engine's audio archives.

### GSIWin

*Visual novel engine ("GSIWin") used in various Japanese visual novels.*

* [FGSIWinTool](https://github.com/crskycode/FGSIWinTool) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2024-03-22 - Script text export/import tool for newer, UTF-8-based GSIWin engine script versions.
* [GSIWinReTool](https://github.com/crskycode/GSIWinReTool) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2024-04-08 - Script text export/import tool for older, Shift-JIS-based GSIWin engine script versions.

### GsPack4

*Visual novel engine ("GsPack4"/"Scw4") used in various Japanese visual novels.*

* [GsPack4\_Scw4\_Script\_tools](https://github.com/Aoi-Namiki/GsPack4_Scw4_Script_tools) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-01-05 - Tools for GsPack4 archives and Scw4 script files.

### GXC Engine

*Visual novel engine ("GXC") used in various Japanese visual novels.*

* [GXC\_engine\_tools](https://github.com/Karaik/GXC_engine_tools) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-12-11 - Decrypts, inspects, edits, and rebuilds GXC engine `.sce` script files.

### InnocentGrey

*Visual novel engine used by InnocentGrey's games.*

* [FlowerScript](https://github.com/shimamura-sakura/FlowerScript) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2024-04-30 - Assembler/disassembler for InnocentGrey's script format.

### Kaguya

*ADV engine ("Kaguya") used in various Japanese visual novels.*

* [Kaguya\_Tool](https://github.com/crskycode/Kaguya_Tool) ⭐ 54 | 🐛 2 | 🌐 C# | 📅 2024-03-09 - Toolset for the Kaguya ADV engine: MsgTool exports/imports text from `message.dat`, and Link6\_Tool creates LINK6 archive files.

### Kurumi Engine

*Visual novel engine ("Kurumi") used in various Japanese visual novels.*

* [KurumiEngineTools](https://github.com/HOKORISAMA/KurumiEngineTools) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-10-23 - Extraction/repacking tools for Kurumi engine archives and scripts.

### Liar-soft / raiL-soft

*Visual novel engine used by Liar-soft and raiL-soft, tested mainly with Albatross Log.*

* [gscScriptCompAndDecompiler](https://github.com/TesterTesterov/gscScriptCompAndDecompiler) ⭐ 33 | 🐛 1 | 🌐 Python | 📅 2020-08-08 - Decompiles, compiles, and rebuilds codeX RScript `.gsc` scripts (the engine's actual bytecode, as opposed to RaiLTools' plain-text conversion), with Russian and English UI.
* [RaiLTools](https://github.com/EusthEnoptEron/RaiLTools) ⭐ 26 | 🐛 2 | 🌐 C# | 📅 2020-04-02 - .NET library for Liar-soft's/raiL-soft's engine: reads/writes `.xfl` archives and converts `.gsc` scenario files to/from plain text.

### LiLiM / Sugar Engine

*Visual novel engine (`.aos` archives) used by LiLiM, LiLiM Sugar, and Princess Sugar visual novels.*

* [AosTools](https://github.com/Lasriel/AosTools) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2025-03-27 - Tools for working with `.aos` archives used by LiLiM/Sugar-engine visual novels.

### LiveMaker

*Visual novel engine ("LiveMaker") used by many Japanese visual novels.*

* [pylivemaker](https://github.com/pmrowla/pylivemaker) ⭐ 89 | 🐛 36 | 🌐 Python | 📅 2026-08-31 - Python package for manipulating LiveMaker 3/LiveNovel game resources: extracts files from a LiveMaker `.exe`/`.dat`, dumps LSB files to readable text/XML, extracts and recompiles LiveNovel LNS scripts from LSB files, and patches modified LSB files back into the `.exe`/`.dat`.

### LucaSystem

*ADV engine ("LUCA System"/ProtoDB) used by Key/Visual Art's visual novels (AIR, CLANNAD, Kanon, Little Busters!, Summer Pockets, Harmonia, LOOPERS, LUNARiA, Planetarian, and others).*

* [LuckSystem](https://github.com/wetor/LuckSystem) ⭐ 84 | 🐛 12 | 🌐 Go | 📅 2026-07-08 - Decompiler/compiler for LUCA System (ProtoDB) engine script files, with PAK archive and font extraction/repacking. Successor to the same author's archived [LucaSystemTools](https://github.com/wetor/LucaSystemTools) ⚠️ Archived.
* [lbee-restoration](https://github.com/Danar435/lbee-restoration) ⭐ 42 | 🐛 2 | 🌐 Python | 📅 2026-07-09 - Patch restoring the original 4:3 assets, UI, uncensored CGs, and opening movie in the Steam port of Little Busters! English Edition, which reformats the original LUCA System game data for widescreen.
* [lbee-utils](https://github.com/G2-Games/lbee-utils) ⭐ 26 | 🐛 7 | 🌐 Rust | 📅 2026-08-12 - Collection of utilities for exporting and importing assets from LUCA System engine games.
* [SPRB-ENX](https://github.com/masagrator/SPRB-ENX) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2023-07-02 - English translation mod for the Nintendo Switch release of Summer Pockets Reflection Blue, assembling a translated `SCRIPT2.PAK` and converting textures to the console's native compressed format with a LuckSystem-based script.
* [kanon-restoration](https://github.com/Danar435/kanon-restoration) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2026-07-09 - Patch restoring the original 4:3 aspect ratio, UI, uncensored CGs, and opening movie in the Steam port of Kanon, which reformats the original LUCA System game data for widescreen.
* [LB\_repack](https://github.com/thedanill/LB_repack) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2024-08-25 - Assembler/disassembler for LUCA System script opcodes and packer/unpacker for the `SCRIPT.PAK` archive, targeting both the PC and Nintendo Switch versions of Little Busters! English Edition.
* [air-restoration](https://github.com/Danar435/air-restoration) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-07-12 - Work-in-progress patch restoring the original 4:3 in-game assets in the Steam port of AIR, which is based on the LUCA System engine.

### Lucifen

*Visual novel engine ("Lucifen") used in various Japanese visual novels.*

* [Lucifen-Tools](https://github.com/UBTL/Lucifen-Tools) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-09-17 - Tools for extracting and working with visual novels running on the Lucifen engine.

### Majiro

*Visual novel engine ("Majiro") used in various Japanese visual novels.*

* [MajiroTools](https://github.com/AtomCrafty/MajiroTools) ⭐ 43 | 🐛 0 | 🌐 C# | 📅 2024-03-29 - Disassembler/toolset for Majiro engine `.mjo` script files, with `.arc` archive and `.rct`/`.rc8` image support and an accompanying wiki documenting the engine's internals. Developed in cooperation with trigger-segfault, who made key format discoveries and wrote the companion [majiro-py](https://github.com/trigger-segfault/majiro-py) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2023-08-14 tools.
* [MajiroStringEditor](https://github.com/marcussacana/MajiroStringEditor) ⭐ 17 | 🐛 0 | 🌐 C# | 📅 2021-03-12 - Editor for exporting and importing strings from Majiro engine script files.

### Malie

*Visual novel engine ("Malie") used in various Japanese visual novels.*

* [Malie\_Script\_Tool](https://github.com/crskycode/Malie_Script_Tool) ⭐ 19 | 🐛 0 | 🌐 C# | 📅 2026-03-17 - FreeMalie engine script disassembler; exports and imports text from Malie engine script files.
* [MalieScriptEditor](https://github.com/Gertram/MalieScriptEditor) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2025-07-05 - Editor for Malie engine script files.
* [MalieDatPacker](https://github.com/Gertram/MalieDatPacker) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2025-07-05 - Packer/unpacker for Malie engine `.dat` archive files.
* [Malie-exe-patcher\_python-code](https://github.com/sechsKatze/Malie-exe-patcher_python-code) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-03-31 - Universal patcher for Malie engine executables that safely injects `EXEC.bin` by creating a new section instead of overwriting the resource section; compatible with Karin Entertainment games.

### Marble Engine

*Visual novel engine ("Marble") used in various Japanese visual novels.*

* [MARBLE-ENGINE-TOOL-KIT](https://github.com/HOKORISAMA/MARBLE-ENGINE-TOOL-KIT) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-08-07 - Packs/unpacks Marble Engine `.mbl` resource archives, including script files (with per-game key lookup via GARbro) and `.prs` image conversion to/from PNG.

### NekoGameSDK

*Visual novel engine SDK ("NekoGameSDK") used in various Japanese visual novels.*

* [NekoGameSDK\_PackTool](https://github.com/crskycode/NekoGameSDK_PackTool) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2022-10-17 - Creates NekoGameSDK engine `.pak` archives (`NEKOPACK4A` signature).
* [nekosdk\_tools](https://github.com/adsf0427/nekosdk_tools) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2024-05-21 - Additional extraction/repacking tools for NekoGameSDK engine files.

### NeXAS

*ADV engine ("NeXAS") used in various Japanese visual novels.*

* [NexasPackEdit](https://github.com/pkuislm/NexasPackEdit) ⭐ 29 | 🐛 0 | 🌐 C | 📅 2022-03-23 - Simple tool to unpack and repack the NeXAS engine's resource archives.
* [NeXAS\_DX](https://github.com/Karaik/NeXAS_DX) ⭐ 24 | 🐛 1 | 🌐 Java | 📅 2026-08-23 - JavaFX GUI for converting NeXAS engine game data (GIGA/戯画/Entergram) to and from JSON files.
* [Aquarium\_tools](https://github.com/kdw-code/Aquarium_tools) ⭐ 24 | 🐛 5 | 🌐 Python | 📅 2026-05-10 - String dumper/importer for Nintendo Switch NeXAS engine `binu8`/`datu8` files, based on [Niflheim](https://github.com/Yggdrasill-Moe/Niflheim) ⭐ 217 | 🐛 3 | 🌐 C | 📅 2023-08-28's NeXAS module.
* [GIGA\_NeXAS](https://github.com/akiWagashi/GIGA_NeXAS) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2024-12-23 - Unpacker/repacker for the GIGA-variant NeXAS engine's resource archives.
* [NeXAS\_Tool](https://github.com/crskycode/NeXAS_Tool) ⭐ 11 | 🐛 1 | 🌐 C# | 📅 2023-10-29 - Config and script tools for newer versions of the NeXAS ADV engine.
* [nexas-datu8](https://github.com/minirop/nexas-datu8) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-08-22 - Decompiler for NeXAS engine `datu8`-format archives.
* [NeXAS\_SPM\_VIEWER](https://github.com/Karaik/NeXAS_SPM_VIEWER) ⭐ 1 | 🐛 1 | 🌐 Java | 📅 2026-06-13 - Viewer for GIGA/戯画/Entergram NeXAS engine `.spm` image/animation files.
* [map\_format\_explorer](https://github.com/Aserain-Nodid/map_format_explorer) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-05-13 - GUI analyzer for NeXAS engine `.map` binary format (BSDX v0.90 and BHE v1.00), with tile visualization, JSON serialization/deserialization, and version conversion.

### PJADV Engine

*Visual novel engine ("PJADV") used in various Japanese visual novels.*

* [RxPJADV](https://github.com/ZQF-ReVN/RxPJADV) ⚠️ Archived - Toolset for PJADV engine `textdata.bin` and `scenario.dat` files.

### RioShiina

*Visual novel engine ("RioShiina") used in various Japanese visual novels.*

* [RioShiinaTools](https://github.com/julixian/RioShiinaTools) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2026-03-21 - Extraction/repacking tools for the RioShiina visual novel engine.

### rUGP (AGES Player)

*Visual novel engine ("rUGP"/AGES Player) used in various Japanese visual novels.*

* [rUGP-Fuck](https://github.com/cssxsh/rUGP-Fuck) ⭐ 21 | 🐛 0 | 🌐 C++ | 📅 2025-12-15 - Extraction/repacking tools for the rUGP (AGES Player) visual novel engine.
* [deoptimizeobs](https://github.com/tsdko/deoptimizeobs) ⭐ 6 | 🐛 1 | 🌐 C | 📅 2022-09-12 - Tools and documentation for the `oor` (COptimizedObs/OptimizedObsforR) sound container format used by the rUGP/AGES engine.

### Siglus

*Visual novel engine ("Siglus") by Key, successor to RealLive, used in several Key visual novels including Rewrite.*

* [SiglusExtract](https://github.com/xmoezzz/SiglusExtract) ⭐ 369 | 🐛 11 | 🌐 C | 📅 2026-06-05 - Extracts almost all resources used by SiglusEngine and repacks some of them for translation.
* [SiglusSceneManager](https://github.com/marcussacana/SiglusSceneManager) ⭐ 78 | 🐛 0 | 🌐 C# | 📅 2021-04-29 - Scene/script manager for the Siglus visual novel engine.
* [siglus\_rs](https://github.com/xmoezzz/siglus_rs) ⭐ 69 | 🐛 3 | 🌐 Rust | 📅 2026-09-03 - Unofficial Rust reimplementation and multi-platform port of SiglusEngine (Windows, Linux, macOS, iOS, Android, WebAssembly), for research purposes.
  * See also [siglus\_static\_key\_tool](https://github.com/xmoezzz/siglus_static_key_tool) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-08-15, a companion Rust CLI for statically recovering a game's SiglusEngine secondary resource-decryption key.
* [SiglusSceneScriptUtility](https://github.com/Jirehlov/SiglusSceneScriptUtility) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-09-05 - Extracts Siglus `Scene.pck` archives to editable `.ss` SceneScript files and recompiles them, aiming to reproduce the engine's original compilation as exactly as possible.
  * See also [siglus-ssu-vscode](https://github.com/Jirehlov/siglus-ssu-vscode) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-04, a VS Code extension providing an LSP-backed editor (diagnostics, completion, hover, go-to-definition, textmap-aware syntax highlighting) for `.ss`/`.inc` SceneScript files, built on the above.
* [SiglusEngine](https://github.com/Tnt6n2/SiglusEngine) ⭐ 21 | 🐛 0 | 📅 2023-06-09 - Leaked full source code of VisualArt's proprietary SiglusEngine (pre-2021 syscall version); useful as a reference for the reimplementation/extraction tools above.
* [SiglusTranslationToolkit](https://github.com/renanc1332/SiglusTranslationToolkit) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2020-10-15 - Toolkit for extracting and repacking Siglus engine `dbs`/`omv`/`Scene.pck`/`Gameexe.dat` files for translation.
* [omvdecoder](https://github.com/xmoezzz/omvdecoder) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2025-09-30 - Decoder for SiglusEngine's `.omv` video format, written in Rust.
* [SiglusTranslate](https://github.com/HOKORISAMA/SiglusTranslate) ⭐ 0 | 🐛 0 | 📅 2021-03-19 - All-in-one automated tool for SiglusEngine text extraction, machine translation, and repacking.

### Silky Engine (AI6WIN)

*Visual novel engine ("Silky's"/AI6WIN) used in various Japanese visual novels.*

* [SilkyArcTool](https://github.com/TesterTesterov/SilkyArcTool) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2021-12-28 - Packs and unpacks Silky Engine archives, with Russian and English UI. See also [SilkyArcTool-rs](https://github.com/lxl66566/SilkyArcTool-rs) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-09-01, a Rust port with bug fixes and improvements.
* [AI6WINScriptTool](https://github.com/TesterTesterov/AI6WINScriptTool) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2022-12-25 - Disassembler and assembler for AI6WIN engine `.mes` script files. See also [AI5WINScriptTool](https://github.com/TesterTesterov/AI5WINScriptTool) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2023-05-31 for the earlier AI5WIN engine, and [mesScriptAsseAndDisassembler](https://github.com/TesterTesterov/mesScriptAsseAndDisassembler) ⭐ 33 | 🐛 1 | 🌐 Python | 📅 2022-02-01 for the original (pre-AI5WIN/AI6WIN) Silky Engine `.mes` scripts.
* [AI6WINArcTool](https://github.com/TesterTesterov/AI6WINArcTool) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2023-03-08 - Packs and unpacks AI6WIN engine `.arc` archives, with Russian and English UI.

### SLG System

*Visual novel engine ("SLG System") used in various Japanese visual novels.*

* [SLGSystemScriptTool](https://github.com/TesterTesterov/SLGSystemScriptTool) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2021-07-21 - GUI tool for (de)compiling and (de/en)crypting (with key-finding support) SLG System engine scripts, with Russian and English UI.

### SofthouseChara Aoi

*Visual novel engine ("SofthouseChara Aoi") used in various Japanese visual novels.*

* [SofthouseChara-Aoi-Tools](https://github.com/UBTL/SofthouseChara-Aoi-Tools) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2025-09-17 - Tools for working with SofthouseChara Aoi engine games (each game needs its own Box/VFS settings adjustments).

### Softpal

*Visual novel engine ("Softpal") used in various Japanese visual novels.*

* [SoftPal-Tool](https://github.com/luoyily/SoftPal-Tool) ⭐ 33 | 🐛 1 | 🌐 Python | 📅 2024-06-22 - Script disassembly and editing tool for the SoftPal visual novel engine.
* [sena-rs](https://github.com/xmoezzz/sena-rs) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-06-29 - Cross-platform Rust reimplementation of the SoftPAL engine, for the game Koikake.
* [SoftpalTool](https://github.com/akiWagashi/SoftpalTool) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2025-10-05 - Resource processing tool for the Softpal visual novel engine.

### Sogna Engine

*Visual novel engine ("Sogna") used in various Japanese visual novels.*

* [SOGNA\_TOOLS](https://github.com/HOKORISAMA/SOGNA_TOOLS) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-12-04 - Extraction/repacking tools for Sogna engine archive and image formats.

### Tactics ADV/Script Engine

*ADV/script engine ("Tactics") used in various Japanese visual novels.*

* [Tactics\_Script\_Tool](https://github.com/crskycode/Tactics_Script_Tool) ⭐ 10 | 🐛 2 | 🌐 C# | 📅 2022-08-31 - Export/import tool for `VisualCode` script files used by the Tactics ADV/Script engine.
* [atxImageTool](https://github.com/hiroshil/atxImageTool) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-12-01 - Converts `.atx` textures from *ONE ~~Kagayaku Kisetsu e~~* (Tactics) and merges them into CG images.

### Tanuki Soft / Kaeru Soft (BCS)

*Visual novel engine (`.tac`/BCS archives) used by Tanuki Soft, Kaeru Soft, and Rune visual novels.*

* [BcsExtractor](https://github.com/nel1391/BcsExtractor) ⭐ 44 | 🐛 4 | 🌐 C# | 📅 2022-04-18 - Extracts scripts from Tanuki Soft and Kaeru Soft visual novels.
* [Tlib-Engine](https://github.com/Cosetto/Tlib-Engine) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-05-24 - Unpack/pack tool for Tanukisoft's `.tac` archive format.

### Tmr-Hiro ADV System

*ADV engine ("Tmr-Hiro") used in various Japanese visual novels.*

* [TmrHiro\_Tool](https://github.com/crskycode/TmrHiro_Tool) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2022-07-31 - Hack/extraction tool for the Tmr-Hiro ADV System, tested on [Kyonyuu Onna Senshi Dogeza Saimin](https://vndb.org/v26531).
* [croCKer](https://github.com/TheVNConnoisseur/croCKer) ⭐ 2 | 🐛 2 | 🌐 C# | 📅 2024-12-11 - Reads and writes `.SRP` script and `.VAR` variable files used by Tmr-Hiro ADV System games (mostly Marigold-produced titles).

### TS System

*Visual novel engine ("TS System"), used by Tropical Kiss and related titles.*

* [ts-system-tools](https://github.com/Anonym271/ts-system-tools) ⭐ 8 | 🐛 1 | 🌐 C++ | 📅 2026-02-22 - Collection of handmade tools for the TS System visual novel engine.

### Valkyria's Engine

*Visual novel engine ("Valkyria's Engine") used in various Japanese visual novels.*

* [RxValkyria](https://github.com/ZQF-ReVN/RxValkyria) ⚠️ Archived - Toolset for Valkyria's Engine `.sdt`, `.dat`, and `.mg2` files.

### WildBug

*Visual novel engine ("WildBug") used in various Japanese visual novels.*

* [WildBugTools](https://github.com/crskycode/WildBugTools) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2026-04-27 - Extracts and repacks WildBug engine resource packs (`.WBP` archives, `ARCFORM4` header).

### WillPlus/AdvHD

*Visual novel engine ("WillPlus"/"AdvHD") used in various Japanese visual novels.*

* [WillPlusManager](https://github.com/marcussacana/WillPlusManager) ⭐ 42 | 🐛 1 | 🌐 C# | 📅 2019-09-02 - Editor for WillPlus/AdvHD script and package files.
* [advhd\_ws2\_tools](https://github.com/DarthFly/advhd_ws2_tools) ⭐ 40 | 🐛 1 | 🌐 PHP | 📅 2026-08-22 - Extracts formatted scripts from AdvHD `.arc` archives and compiled `.ws2` (WillPlus) code, converts them to editable text, and repacks them byte-for-byte.
  * Games: If My Heart Had Wings (Flight Diary), LoveKami -Healing Harem-, A Sky Full of Stars, and (with possible adjustments) other MoeNovel/Nightmare Project/WillPlus titles.
* [AdvHD2.1\_WS2\_Toolkit](https://github.com/Lite0812/AdvHD2.1_WS2_Toolkit) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-03-27 - Export/import tool for AdvHD 2.1's `.ws2` script files, rewritten to handle the version's switch from Shift-JIS to UTF-16LE string encoding.
* [ws2Parse](https://github.com/pkuislm/ws2Parse) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2023-06-13 - Export/import tool for WillPlus/AdvHD compiled `.ws2` script files.

### Xuse / Eternal

*Visual novel engine ("Xuse"/"Eternal") used in various Japanese visual novels.*

* [XuseExplorer](https://github.com/Leticiel/XuseExplorer) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2026-04-16 - Extraction/repacking tool for Xuse-engine visual novel files.

### Yuka System

*Visual novel engine ("Yuka System") used by HookSoft, Smee, PeasSoft, feng, and other Japanese visual novel developers.*

* [yukatool](https://github.com/AtomCrafty/yukatool) ⭐ 37 | 🐛 1 | 🌐 C# | 📅 2022-06-22 - Original all-in-one command-line toolset for the Yuka System visual novel engine (archive, script, and graphics extraction/repacking), superseded by yukatool2.
* [yukatool2](https://github.com/AtomCrafty/yukatool2) ⭐ 25 | 🐛 0 | 🌐 C# | 📅 2025-06-21 - Toolset (CLI and GUI) for the Yuka System engine, rewritten from the ground up over the original yukatool to be faster and more maintainable.

### YU-RIS

*Visual novel engine ("YU-RIS") used in various Japanese visual novels.*

* [RxYuris](https://github.com/ZQF-ReVN/RxYuris) ⚠️ Archived - Toolset for YU-RIS engine `.ypf` archives and `.ybn` script files.
* [YPF\_Tool](https://github.com/crskycode/YPF_Tool) ⭐ 21 | 🐛 1 | 🌐 C# | 📅 2022-07-31 - Creates YU-RIS `.ypf` archive files.
* [yuri](https://github.com/shimamura-sakura/yuri) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2026-08-20 - Parallel, incremental decompiler and compiler for the YU-RIS engine.
* [YPF-Manager](https://github.com/Xorboth/YPF-Manager) ⭐ 19 | 🐛 0 | 🌐 C# | 📅 2021-07-17 - GUI tool to pack, unpack, and manage YU-RIS `.ypf` archives. See also [lxl66566's fork](https://github.com/lxl66566/YPF-Manager) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-08-04 with prebuilt executables.
* [YuRis\_Tool](https://github.com/crskycode/YuRis_Tool) ⭐ 11 | 🐛 0 | 🌐 C# | 📅 2024-12-20 - Analyzer/decompiler for YU-RIS script formats (YSCM, YSLB, YSTL, YSVR, YSTB).
* [extYuRis](https://github.com/CodeSpoof/extYuRis) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2023-04-19 - Extraction tool for YU-RIS `.ybn` script files.
* [Yuris\_YDG\_Tool](https://github.com/Lite0812/Yuris_YDG_Tool) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-04-04 - Batch converter between PNG and YU-RIS `.ydg` font bitmap files.

### Glulx VM (Interactive Fiction)

*Virtual machine format for parser-based interactive fiction, designed by Andrew Plotkin as a successor to the Z-machine; the standard compilation target for Inform 7.*

* [Quixe](https://github.com/erkyrath/quixe) ⭐ 173 | 🐛 26 | 🌐 JavaScript | 📅 2025-09-01 - Pure-JavaScript interpreter for the Glulx interactive-fiction virtual machine, playing .ulx/.gblorb game files directly in the browser with no server component.
* [Glulxe](https://github.com/erkyrath/glulxe) ⭐ 126 | 🐛 6 | 🌐 C | 📅 2026-05-05 - Reference interpreter for the Glulx virtual machine, written by its designer Andrew Plotkin.
* [Git](https://github.com/DavidKinder/Git) ⭐ 57 | 🐛 3 | 🌐 C | 📅 2026-08-23 - Fast interpreter for the Glulx interactive-fiction virtual machine, playing .ulx/.gblorb game files; roughly 5x faster than Glulxe and about twice as fast as Frotz on equivalent Inform-compiled stories.
* [IF Archive Specs](https://github.com/iftechfoundation/ifarchive-if-specs) ⭐ 27 | 🐛 9 | 🌐 Python | 📅 2026-05-30 - Official specification documents for the Glk display API, the Glulx virtual machine, and the Blorb resource-container format used by Z-machine/Glulx interactive fiction.
* [if-decompiler](https://github.com/curiousdannii/if-decompiler) ⭐ 22 | 🐛 9 | 🌐 Rust | 📅 2021-07-11 - Decompiles Glulx story files back into C source code (Glulxtoc/IF-Decompiler), for recovering original game logic from compiled .ulx files.
* [Windows-Glulxe](https://github.com/DavidKinder/Windows-Glulxe) ⭐ 12 | 🐛 0 | 🌐 HTML | 📅 2026-08-23 - Windows front-end for Andrew Plotkin's Glulxe reference interpreter combined with Windows Glk, playing Glulx .ulx/.gblorb game files.
* [Zag](https://github.com/Banbury/zag) ⭐ 10 | 🐛 4 | 🌐 Java | 📅 2020-01-19 - Actively maintained fork of Andrew Plotkin's Zag Glulx interpreter (Python), updated to support Glulx spec version 3; recommended over the original repo by its own author.
* [glulx-llvm](https://github.com/dfremont/glulx-llvm) ⭐ 10 | 🐛 2 | 🌐 C | 📅 2021-11-14 - Experimental LLVM backend targeting the Glulx interactive-fiction virtual machine, allowing C and other LLVM-frontend languages to compile to Glulx .ulx bytecode.
* [babel-tool](https://github.com/iftechfoundation/babel-tool) ⭐ 10 | 🐛 2 | 🌐 HTML | 📅 2026-03-01 - Reference implementation of the Treaty of Babel: a multi-format C API and CLI suite (babel, babel-get, babel-list, ifiction-aggregate, etc.) for extracting metadata/cover art from interactive-fiction story files, identifying their VM format and IFID, and bundling story files with metadata into the Blorb resource-container format.
* [mrifk](https://github.com/wertercatt/mrifk) ⭐ 6 | 🐛 0 | 🌐 Haskell | 📅 2025-09-11 - Decompiler and disassembler for the Glulx virtual machine, reconstructing readable Inform-6-style disassembly and source listings from compiled .ulx story files.

### Z-machine VM (Interactive Fiction)

*Virtual machine format used by Infocom's parser-based text adventures (Zork, Enchanter, etc.) and still a common compilation target for modern works written in Inform 6/7; predecessor to Glulx.*

#### Interpreters & Players

* [Parchment](https://github.com/curiousdannii/parchment) ⭐ 486 | 🐛 41 | 🌐 TypeScript | 📅 2026-08-23 - The actively maintained successor to Andrew Plotkin's original Parchment web interactive-fiction player, running Z-machine and Glulx games in the browser via WASM-compiled interpreters (through the Emglken/Glk bridge).
* [Gargoyle](https://github.com/garglk/garglk) ⭐ 426 | 🐛 50 | 🌐 C++ | 📅 2026-09-05 - Cross-platform multi-format interactive-fiction player supporting Z-machine, Glulx, TADS, Hugo, and other IF virtual machine formats.
* [Infocom Z-code Interpreters](https://github.com/erkyrath/infocom-zcode-terps) ⭐ 366 | 🐛 0 | 🌐 Assembly | 📅 2023-11-23 - Historical collection of Infocom's original Z-machine interpreters for 1980s home computers, mostly as 6502/Z-80 assembly source.
* [Lectrote](https://github.com/erkyrath/lectrote) ⭐ 270 | 🐛 49 | 🌐 JavaScript | 📅 2025-10-04 - Electron-based interactive fiction interpreter, playing Z-code and Glulx games.
* [encrusted](https://github.com/DeMille/encrusted) ⭐ 152 | 🐛 15 | 🌐 Rust | 📅 2022-06-20 - Z-machine interpreter written in Rust for classic Infocom-era text adventures like Zork, compiling to WebAssembly for browser play.
* [mojozork](https://github.com/icculus/mojozork) ⭐ 148 | 🐛 6 | 🌐 C | 📅 2026-09-03 - Simple Z-machine interpreter implemented in a single C file, with an experimental online-multiplayer mode for playing classic Infocom Z-code story files together.
* [Windows-Frotz](https://github.com/DavidKinder/Windows-Frotz) ⭐ 117 | 🐛 6 | 🌐 C | 📅 2026-08-24 - Windows front-end for the Frotz Z-machine interpreter core, playing Infocom and other Z-code game files on Windows.
* [ifvms.js](https://github.com/curiousdannii/ifvms.js) ⭐ 99 | 🐛 13 | 🌐 JavaScript | 📅 2025-07-12 - Suite of pure-JavaScript interactive-fiction virtual machine interpreters (Z-machine and Glulx) for browser-based play.
* [Zorkduino](https://github.com/rossumur/Zorkduino) ⭐ 59 | 🐛 4 | 🌐 C++ | 📅 2014-05-22 - Z-machine interpreter for Arduino, playing classic Infocom Z-code games on a TV.
* [Fabularium](https://github.com/tccowper/fabularium) ⭐ 51 | 🐛 10 | 🌐 C++ | 📅 2019-10-07 - Multi-format interactive-fiction player for Android, bundling Z-machine, Glulx, Hugo, TADS, and other IF virtual-machine interpreters into a single app; the mobile counterpart to Gargoyle.
* [Twisty](https://github.com/sussman/twisty) ⭐ 39 | 🐛 48 | 🌐 C | 📅 2017-07-09 - Text-adventure interpreter for Android, playing both Z-machine and Glulx game files.
* [Viola](https://github.com/DFillmore/viola) ⭐ 30 | 🐛 18 | 🌐 Python | 📅 2024-05-06 - Z-Machine interpreter written in Python.
* [Gnusto-Frotz-Tops20](https://github.com/athornton/gnusto-frotz-tops20) ⭐ 12 | 🐛 1 | 🌐 Perl | 📅 2020-02-07 - Port of the Frotz Z-machine interpreter to the TOPS-20 operating system, playing Infocom game files.
* [Fizmo](https://github.com/erkyrath/fizmo) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2022-12-01 - C Z-machine interpreter for POSIX systems, playing Infocom and other Z-machine game files (all versions except 6). See also [IosFizmo](https://github.com/erkyrath/iosfizmo) ⭐ 49 | 🐛 2 | 🌐 Objective-C | 📅 2022-12-02, an iOS port.
* [zmach](https://github.com/kmill/zmach) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-13 - Z-machine interpreter that dynamically recompiles Z-code (version 5 story files) to JavaScript.
* [Discoggin](https://github.com/iftechfoundation/discoggin) ⭐ 6 | 🐛 13 | 🌐 Python | 📅 2025-07-05 - Discord bot that plays parser and choice-based interactive fiction directly in a Discord channel, supporting Z-code (.z1-.z8/.zblorb), Glulx (.ulx/.gblorb), Ink, and YarnSpinner game files, with persisted per-channel save sessions.
* [HugoJS](https://github.com/juhana/hugojs) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2022-04-26 - Online interpreter for Hugo, another parser-based interactive-fiction virtual-machine format, running compiled Hugo game files in the browser.
* [Frotz](https://gitlab.com/DavidGriffith/frotz) - The original portable Frotz Z-machine interpreter core, written by Stefan Jokisch and extended by David Griffith since 1997; development moved from GitHub to GitLab, and it underlies many derivative interpreters (Windows-Frotz, Gnusto-Frotz-Tops20, etc.).

#### Authoring & Compiler Tools

* [Inform 7](https://github.com/ganelson/inform) ⭐ 1,641 | 🐛 9 | 🌐 C | 📅 2026-06-24 - Core distribution of the Inform 7 natural-language interactive fiction authoring system, compiling through Inform 6 to Z-code or Glulx bytecode.
* [Inform 6](https://github.com/DavidKinder/Inform6) ⭐ 234 | 🐛 21 | 🌐 C | 📅 2026-04-27 - Compiler for the Inform 6 language, producing Z-machine (.z3/.z5/.z8) story files and, as the code generator behind Inform 7, Glulx (.ulx) game files.
* [language-inform7](https://github.com/iftechfoundation/language-inform7) ⭐ 2 | 🐛 0 | 📅 2022-07-02 - Language grammar definition for Inform 7, the natural-language authoring system that compiles to Z-machine/Glulx story files.

#### Story File Tools, Disassemblers & Archives

* [zork-1978-01](https://github.com/MITDDC/zork-1978-01) ⭐ 70 | 🐛 1 | 🌐 Roff | 📅 2022-08-10 - Source code for a January 1978 version of Zork, predating Infocom's founding; an early Z-machine-era snapshot of the game's development at MIT.
* [Inform Mapper](https://github.com/attilathedud/inform_mapper) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-19 - Interactive web graphing application for Z-machine story files (.z1-.z8), parsing a game's object tree to visualize rooms, objects, and their parent/sibling/containment relations. The actively maintained successor to the author's own [ZTree](https://github.com/attilathedud/ZTree) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2017-10-24.
* [ztools](https://github.com/erkyrath/ztools) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-01-23 - Classic Infocom Z-machine toolkit (txd disassembler, infodump story-file dumper, and related utilities) for inspecting Z-code game files.
* [Infocom Historical Source Archive](https://github.com/historicalsource) - Leaked/preserved original ZIL (Zork Implementation Language) source code for most of Infocom's text-adventure catalog, each compiling to the original Z-machine (.z3/.z5) story-file format; includes several unreleased/unfinished titles.
  * Games: Zork I, Zork II, Zork III (plus the 1977 mainframe original, Solid-Gold editions, and 1982/1987/1988 Sampler minizork variants), Zork Zero, Enchanter, Sorcerer, Spellbreaker, Deadline, Suspect, Suspended, Starcross, Infidel, The Witness, Ballyhoo, Border Zone, Bureaucracy, Cutthroats, Hollywood Hijinx, The Hitchhiker's Guide to the Galaxy (plus Solid-Gold edition), Journey, Leather Goddesses of Phobos (plus Gold edition), Moonmist, Nord and Bert Couldn't Make Head or Tail of It, Planetfall (plus Gold edition), Plundered Hearts, Seastalker, Sherlock: The Riddle of the Crown Jewels, James Clavell's Shogun, Stationfall, Trinity, Wishbringer (plus Gold edition), A Mind Forever Voyaging, Beyond Zork, Arthur: The Quest for Excalibur, The Lurking Horror, the 1984 Infocom Sampler, and unreleased/unfinished titles (Checkpoint, The Restaurant at the End of the Universe, a German-language Zork translation, James Cameron's The Abyss).

#### Glk Display API & Libraries

* [Glk API reference implementations](https://github.com/erkyrath/cheapglk) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2025-06-05 - Reference implementations of Glk, the display API most Z-machine/Glulx interpreters use: [CheapGlk](https://github.com/erkyrath/cheapglk) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2025-06-05 (headless/minimal), [GlkTerm](https://github.com/erkyrath/glkterm) ⭐ 18 | 🐛 9 | 🌐 C | 📅 2021-07-08 (curses), [RemGlk](https://github.com/erkyrath/remglk) ⭐ 28 | 🐛 13 | 🌐 C | 📅 2025-06-12 (remote-procedure-call/JSON), and [XGlk](https://github.com/erkyrath/xglk) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2021-06-26 (X11, unmaintained since 2000).
* [Windows Glk](https://github.com/DavidKinder/Windows-Glk) ⭐ 15 | 🐛 3 | 🌐 C++ | 📅 2026-08-16 - Windows implementation of Andrew Plotkin's Glk display-API specification, used by many Z-code/Glulx interpreters.

### Magnetic Scrolls VM (Interactive Fiction)

*Custom virtual machine format used by Magnetic Scrolls' text adventures (The Pawn, Guild of Thieves, Wonderland, etc.), a UK studio whose parser games rivaled Infocom's in the 1980s.*

* [Magnetic](https://github.com/DavidKinder/Magnetic) ⭐ 21 | 🐛 1 | 🌐 C | 📅 2026-02-12 - Interpreter for the Magnetic Scrolls text-adventure games (1985-1991) by the UK studio of the same name, playing the original .mag story files; written by Niclas Karlsson with additional code by David Kinder.

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
* [Starlane](https://github.com/awlck/starlane) ⭐ 0 | 🐛 1 | 🌐 C++ | 📅 2026-08-31 - C++ reimplementation of the ADRIFT 5 interactive-fiction engine, loading and playing original .taf ADRIFT game files with Qt, console, and Glk frontends outside the closed-source Windows runner.

### Alan VM (Interactive Fiction)

*Text-adventure authoring language designed by Thomas Nilsson, compiling to its own bytecode format read by the Alan interpreter.*

* [Alan](https://github.com/alan-if/alan) ⭐ 19 | 🐛 12 | 🌐 Assembly | 📅 2026-09-04 - Official compiler and interpreter for the Alan interactive-fiction authoring language, playing the original Alan game-data format.

### Twine (Interactive Fiction)

*Hypertext/choice-based interactive fiction tool; Twine stories are HTML files embedding Twee-format passage data, run by a story-format-specific JavaScript runtime (Harlowe, SugarCube, Chapbook, etc.).*

* [twine-specs](https://github.com/iftechfoundation/twine-specs) ⭐ 102 | 🐛 5 | 📅 2024-07-04 - Format specifications for Twine, covering the Twee passage-map format, the HTML story-archive format, and the story-format JavaScript API.

### Yarn Spinner (Dialogue Middleware)

*Engine-agnostic dialogue scripting system used by many indie and commercial games; Yarn scripts compile to a bytecode/JSON format executed at runtime.*

* [Yarn Spinner](https://github.com/YarnSpinnerTool/YarnSpinner) ⭐ 2,834 | 🐛 3 | 🌐 C# | 📅 2026-08-11 - Core compiler and engine-agnostic runtime for Yarn Spinner, compiling `.yarn` dialogue scripts to a bytecode/JSON format consumed by game engines (Unity, Godot, etc.). See also [YSRun-Single](https://github.com/erkyrath/YSRun-Single) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2025-07-02, a single-turn GlkOte wrapper for running the compiled dialogue JSON from the command line.

### Rawthrills G7 Engine

* [G7Reader](https://github.com/Surasia/G7Reader) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2024-06-29 - Small utility to read Rawthrills G7 Engine archive files.

### Marmalade SDK

* [dzip-rs](https://github.com/LambdaEd1th/dzip-rs) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-08-20 - Pure-Rust library and CLI for reading, extracting, creating, and inspecting Dzip resource archives used by Marmalade SDK games, compatible with the original dzip.exe (split volumes, DZ/Bzip/LZMA compression).

### OpenSpace

* [openspace-ps2-extractor](https://github.com/byvar/openspace-ps2-extractor) ⭐ 7 | 🐛 1 | 🌐 Java | 📅 2018-09-17 - Extractor for OpenSpace PS2 archive files.
* [BinarySerializer.OpenSpace](https://github.com/BinarySerializer/BinarySerializer.OpenSpace) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2026-02-26 - BinarySerializer extension library for serializing OpenSpace game formats.

### LithTech Engine

*Engine used in No One Lives Forever, F.E.A.R., Condemned, Blood 2, Shogo, and other Monolith games. See also [Monolith Productions](#monolith-productions) for game-specific tools.*

* [lithtech](https://github.com/jsj2008/lithtech) ⭐ 340 | 🐛 0 | 🌐 C++ | 📅 2015-09-01 - Source code release for the LithTech engine, used by titles including F.E.A.R., No One Lives Forever, Aliens versus Predator 2, and Tron 2.0. See also [Katana-Steel's fork](https://github.com/Katana-Steel/lithtech) ⭐ 101 | 🐛 9 | 🌐 C++ | 📅 2026-07-28 with a modernized cross-platform CMake build (GitHub Actions + GitLab CI).
* [io\_scene\_jupex](https://github.com/Five-Damned-Dollarz/io_scene_jupex) ⭐ 21 | 🐛 5 | 🌐 Python | 📅 2024-11-15 - Blender addon for importing LithTech Jupiter EX world/map files (.world). Supports games built on the Jupiter EX engine (F.E.A.R., Condemned, No One Lives Forever 2).
* [io\_scene\_lithtech (haekb)](https://github.com/haekb/io_scene_lithtech) ⭐ 20 | 🐛 9 | 🌐 Python | 📅 2021-11-15 - Blender addon for importing LithTech model and animation files. Supports ABC (LithTech 1/2 era, used in Blood 2, NOLF, Shogo) and LTB formats.
  * See also [Five-Damned-Dollarz's fork](https://github.com/Five-Damned-Dollarz/io_scene_lithtech) ⭐ 11 | 🐛 6 | 🌐 Python | 📅 2025-10-23 with additional model support.
* [io\_scene\_modl](https://github.com/cmbasnett/io_scene_modl) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2018-06-20 - Blender addon for importing and exporting .modl model files from LithTech Jupiter Engine games.
* [msLTBImporter](https://github.com/crskycode/msLTBImporter) ⭐ 13 | 🐛 0 | 🌐 C++ | 📅 2021-10-20 - MilkShape 3D plugin for importing LithTech LTB model files.
* [godot-dat-reader](https://github.com/haekb/godot-dat-reader) ⭐ 10 | 🐛 1 | 🌐 GDScript | 📅 2021-10-03 - Godot 3.2 importer for LithTech DAT world/level files.
* [godot-abc-reader](https://github.com/haekb/godot-abc-reader) ⭐ 8 | 🐛 0 | 🌐 GDScript | 📅 2021-08-04 - Godot 3.2 importer for LithTech ABC model files used in Blood 2, No One Lives Forever, and Shogo.
* [godot-dtx-reader](https://github.com/haekb/godot-dtx-reader) ⭐ 6 | 🐛 0 | 🌐 GDScript | 📅 2020-11-22 - Godot 3.2 importer for LithTech DTX texture files used across LithTech 1/2/Jupiter engine games.
* [lpsdecoder](https://github.com/haekb/lpsdecoder) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2019-12-27 - Extracts and converts PS2 LithTech LPS archive format.
* [LithTech\_DTX\_Convertor](https://github.com/Kelthic/LithTech_DTX_Convertor) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-14 - Lightweight converter for LithTech engine DTX texture files to DDS format.

### Adventure Game Studio (AGS)

* [AGSUnpacker](https://github.com/adm244/AGSUnpacker) ⭐ 44 | 🐛 3 | 🌐 C# | 📅 2026-08-21 - Unpacker/packer for compiled Adventure Game Studio (AGS) 2.x–3.x game resources.
  * See also [Ghidra-ReAGS](https://github.com/adm244/Ghidra-ReAGS) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-06-08 for AGS script (scom3) decompilation via Ghidra.
  * Formats: executable (.exe), archives (.ags, .xxx), sprites (.spr), rooms (.crm), scripts (.scom3, .dta), translation files (.trs, .tra).
  * Features: asset extraction, sprite unpack/repack, room background preview/replace, translation file generation and compilation, string injection from translation files.
* [ags2\_decomp](https://github.com/adm244/ags2_decomp) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-08-21 - Matching decompilation of Adventure Game Studio 2.x runtime engine for reverse engineering and software preservation.
* [Ghidra-ReAGS Quick Start](https://github.com/selloa/ghidra-reags-quickstart) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-05-29 - Beginner-friendly guide for extracting Adventure Game Studio scripts with AGSUnpacker and decompiling them in Ghidra using the ReAGS extension, with a live walkthrough site.
* [ags-sprite-extractor](https://github.com/selloa/ags-sprite-extractor) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-27 - Sprite extraction tool for Adventure Game Studio games.

### BioWare Aurora Engine

*Used in Neverwinter Nights, Star Wars: Knights of the Old Republic, Jade Empire, and other BioWare titles.*

* [xoreos](https://github.com/xoreos/xoreos) ⭐ 1,169 | 🐛 37 | 🌐 C++ | 📅 2026-09-04 - Open-source reimplementation of BioWare's Aurora engine and its derivatives, targeting full portability of all Aurora-based games.
  * Games: Neverwinter Nights, Neverwinter Nights 2, Knights of the Old Republic, KotOR II: The Sith Lords, Jade Empire, Sonic Chronicles: The Dark Brotherhood, The Witcher, Dragon Age: Origins, Dragon Age II.
  * Status: resource management, many file format parsers, partial in-game graphics and area rendering (spectator mode) — gameplay not yet implemented.
* [nwscript-wasm](https://github.com/KobaltBlu/nwscript-wasm) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-13 - WebAssembly port of the NWScript compiler (from niv/neverwinter.nim), compiling .nss scripts to .ncs bytecode entirely in-browser, with a bundled NCS disassembler.
  * Ecosystem: [nwscript-workbench-vscode-ext](https://github.com/KobaltBlu/nwscript-workbench-vscode-ext) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-14 (VS Code extension for desktop and web with engine-aware IntelliSense and an NCS Inspector for disassembly/hex/asm views), [nwscript-language-definitions](https://github.com/KobaltBlu/nwscript-language-definitions) ⭐ 0 | 🐛 0 | 🌐 NWScript | 📅 2026-08-14 (canonical nwscript.nss definitions per game: Jade Empire, KotOR, KotOR II, Neverwinter Nights + expansions/Enhanced Edition, Neverwinter Nights 2, The Witcher).

### Clickteam Fusion

* [Nebula](https://github.com/AITYunivers/NebulaFD) ⭐ 217 | 🐛 2 | 🌐 C# | 📅 2026-07-28 - Actively developed, reimagined decompiler for Clickteam Fusion 2.5 games, successor to [fnmwolf's Anaconda decompiler](https://github.com/fnmwolf/Anaconda) ⭐ 123 | 🐛 11 | 🌐 C++ | 📅 2025-02-06.
* [CTFAK2.0](https://github.com/CTFAK/CTFAK2.0) ⚠️ Archived - Decompiler and asset dumper for games built with Clickteam Fusion 2.5 (archived; superseded by CTFAK3). Reads MFA-like internal structures and outputs assets via a plugin system.
* [Anaconda](https://github.com/fnmwolf/Anaconda) ⭐ 123 | 🐛 11 | 🌐 C++ | 📅 2025-02-06 - Decompiler for Clickteam Fusion 2.5 games, by fnmwolf, ClickNinYT, 1987Kostya, Blue Nova, and Mathias Kærlev; superseded by Nebula above.
* [insect\_hazard\_viewer (CFAB)](https://github.com/coreynguyen/insect_hazard_viewer) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-01-03 - Reverse-engineering tool for Clickteam Fusion games that scans a compiled executable's memory to locate, decode, and extract assets without a decompiler, handling the engine's DAT image format (Planar Alpha, Chroma Keying) and Stub Archive (scripts, DLLs, music). Built while reversing Insect Hazard.

### Dark Engine

*Used in Thief: The Dark Project, Thief 2: The Metal Age, and System Shock 2 (Looking Glass Studios).*

* [openDarkEngine](https://github.com/volca02/openDarkEngine) ⭐ 170 | 🐛 9 | 🌐 C++ | 📅 2018-05-14 - Open-source multiplatform reimplementation of the Dark Engine, reading original Thief and System Shock 2 game data (level, mesh, and DAT resource formats).
* [AngelLoader](https://github.com/FenPhoenix/AngelLoader) ⭐ 70 | 🐛 9 | 🌐 C# | 📅 2026-09-03 - Standalone fan mission loader/manager for the original Thief trilogy, System Shock 2, and The Dark Mod, installing and organizing Dark Engine FM archives (zip/7z) with readme/screenshot extraction and metadata handling.
* [de-specs](https://github.com/JarrodDoyle/de-specs) ⭐ 2 | 🐛 0 | 🌐 Max | 📅 2025-03-09 - [ImHex](https://imhex.werwolv.net/) pattern files for parsing Dark Engine file formats used in Thief and System Shock 2.
  * Formats: .MIS (mission), .GAM (game data), .COW (world geometry); further formats planned.
* [7-Zip Speed Optimizer](https://github.com/FenPhoenix/7-Zip-Speed-Optimizer) ⚠️ Archived - Repackages Thief/System Shock 2/Dark Mod fan mission .7z archives so FM loaders (AngelLoader, FMSel) can scan them up to 70x faster, while retaining 7z's compression advantage.
* [KCModelEditor](https://github.com/JarrodDoyle/KCModelEditor) ⭐ 1 | 🐛 8 | 🌐 C# | 📅 2026-07-19 - GUI tooling for browsing and editing Dark Engine model files, written in C# using the Godot engine.

### SCI Engine (Sierra)

*Sierra On-Line's Script Creation Interpreter, used in King's Quest, Space Quest, Police Quest, Leisure Suit Larry, Gabriel Knight, and many other Sierra titles.*

* [SCICompanion](https://github.com/icefallgames/SCICompanion) ⭐ 87 | 🐛 14 | 🌐 C++ | 📅 2021-04-28 - Full-featured IDE for creating and editing Sierra SCI engine games (SCI0 through SCI1.1). Supports editing scripts, rooms, sounds, views, fonts, pics, cursors, messages, and palettes. Official site: [scicompanion.com](https://scicompanion.com).
* [Sierra softlock analyzer](https://github.com/katiahayati/lucasartsifier) ⭐ 49 | 🐛 1 | 🌐 Python | 📅 2026-08-25 - Static analysis tool that decompiles a Sierra SCI game and abstract-interprets the decompiled scripts into a graph of guarded room transitions, used to find softlocks in 30-year-old adventure games.
* [NAGI](https://github.com/sonneveld/nagi) ⭐ 42 | 🐛 4 | 🌐 C | 📅 2022-05-14 - Reimplementation of Sierra's AGI (Adventure Game Interpreter) engine, parsing and executing original AGI game resource files.
* [FOSS SCI Drivers](https://github.com/roybaer/foss_sci_drivers) ⭐ 24 | 🐛 1 | 🌐 Assembly | 📅 2021-08-13 - From-scratch open-source drivers for Sierra's SCI (Creative Interpreter) engine, covering archive, audio, and editor support.
* [AGILE](https://github.com/lanceewing/agile) ⭐ 20 | 🐛 1 | 🌐 C# | 📅 2026-02-05 - AGI (Adventure Game Interpreter) engine reimplementation in C#, parsing and executing original Sierra AGI game resource files. See also the [AGILE-GDX](https://github.com/lanceewing/agile-gdx) ⭐ 51 | 🐛 3 | 🌐 Java | 📅 2025-08-23 (Java/libGDX, targeting HTML5/Desktop/Android) and [AGILE-JS](https://github.com/lanceewing/agile-js) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2019-03-25 (JavaScript) ports.
* [sci-tools](https://github.com/sluicebox/sci-tools) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2026-06-30 - Collection of reverse engineering tools for Sierra's SCI engine.
* [SCI2AGI](https://github.com/jhhoward/SCI2AGI) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2024-11-24 - Converts Sierra SCI engine resources (PIC, VIEW, and others) to the earlier AGI engine's format.
* [jagi](https://github.com/lanceewing/jagi) ⭐ 5 | 🐛 1 | 🌐 Java | 📅 2022-10-24 - Fork of an existing Java AGI engine, exploring the older AGI v1 resource/data format.
* [PICEDIT](https://github.com/lanceewing/picedit) ⭐ 4 | 🐛 0 | 🌐 Java | 📅 2022-11-12 - Editor for AGI PIC resource files, recreating the picture-drawing tool once used to create pictures for original and fan-made AGI games.

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

* [Ruffle](https://github.com/ruffle-rs/ruffle) ⭐ 18,496 | 🐛 5,628 | 🌐 Rust | 📅 2026-09-05 - Flash Player emulator written in Rust that parses and executes SWF files and ActionScript bytecode, used to preserve and play thousands of Flash-based web games.
* [Swivel](https://github.com/Herschel/Swivel) ⭐ 227 | 🐛 27 | 🌐 Haxe | 📅 2026-03-28 - Converts Adobe Flash SWF files to video, for archiving or sharing Flash-based games and animations.
* [rust-flash-lso](https://github.com/ruffle-rs/rust-flash-lso) ⭐ 20 | 🐛 6 | 🌐 Rust | 📅 2026-08-27 - Rust parser/encoder for Adobe Flash Local Shared Object (.sol) save files and the underlying AMF0/AMF3 serialization formats used by Flash games.

### Godot

* [gdsdecomp](https://github.com/GDRETools/gdsdecomp) ⭐ 4,160 | 🐛 38 | 🌐 C++ | 📅 2026-08-16 - Godot reverse engineering toolkit for game file format recovery, GDScript bytecode decompilation, and PCK archive extraction (Godot 2.x, 3.x, 4.x).
* [GodotPCKExplorer](https://github.com/DmitriySalnikov/GodotPCKExplorer) ⭐ 540 | 🐛 7 | 🌐 C# | 📅 2026-06-13 - GUI and CLI tool for exploring, extracting, creating, and merging Godot Engine `.pck` package files, with support for encrypted packs.
* [gdke](https://github.com/char-ptr/gdke) ⭐ 232 | 🐛 11 | 🌐 TypeScript | 📅 2024-09-05 - External GUI tool to extract the AES encryption key from Godot game binaries (3.x/4.x) without needing to run or patch the target executable. Builds on the same author's earlier [godot-key-extract](https://github.com/char-ptr/godot-key-extract) ⚠️ Archived, a CLI tool for the same technique.
* [godotdec](https://github.com/Bioruebe/godotdec) ⭐ 228 | 🐛 4 | 🌐 C# | 📅 2024-03-16 - Unpacker for Godot Engine `.pck` package files.
* [godotpwcrack](https://github.com/johndoe31415/godotpwcrack) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-04-15 - Brute-force cracker for Godot's encrypted GDEC files (identified by a `GDEC` magic), with an accompanying write-up on reverse-engineering the AES key derivation via GDB (breaking on `mbedtls_aes_setkey_dec` and `_File::open_encrypted_pass`).

### HaxeFlixel

* [flxanimate](https://github.com/Dot-Stuff/flxanimate) ⭐ 73 | 🐛 5 | 🌐 Haxe | 📅 2026-01-04 - Plays back Adobe Animate texture atlas exports (used widely by Friday Night Funkin' and its mods) in HaxeFlixel.
* [BetterTextureAtlas](https://github.com/Dot-Stuff/BetterTextureAtlas) ⭐ 58 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-31 - Adobe Animate extension that enhances Texture Atlas exports, extending the animation file format with extra data (blend modes, baked filters) for use by players like flxanimate.

### PICO-8 (Lexaloffle Games)

* [fake-08](https://github.com/jtothebell/fake-08) ⭐ 866 | 🐛 61 | 🌐 C++ | 📅 2026-06-13 - PICO-8 cartridge (P8/P8.PNG) player/emulator for homebrew game consoles (3DS, Vita, Switch, and more).
* [picotool](https://github.com/dansanderson/picotool) ⭐ 406 | 🐛 55 | 🌐 Python | 📅 2024-02-03 - Tools and Python libraries for manipulating PICO-8 cartridge files (P8/P8.PNG), the fantasy console's combined code/graphics/sound/music format.
* [pico8utils](https://github.com/josefnpat/pico8utils) ⭐ 55 | 🐛 1 | 🌐 Lua | 📅 2018-08-22 - Lua/luajit scripts to extract and inject PICO-8 `.p8` cartridge Lua code and spritesheet graphics (`pico2lua`, `pico2png`, `png2pico`).
* [lexaloffle](https://github.com/dansanderson/lexaloffle) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2022-09-15 - Official Lexaloffle-released C routines for the two proprietary compression methods (legacy `:c:`, newer `pxa`) used to pack the Lua code region of PICO-8 P8PNG cartridges.

## 🔧 Middleware & SDKs

*Game development middleware, libraries, and SDK-provided formats used across multiple titles and platforms.*

### Fast3d/F3dex (N64)

*SGI's microcode format for defining 3D graphics on the Nintendo 64. Used in [Super Mario 64](#super-mario-64), [Paper Mario 64](#paper-mario-64), [Banjo-Kazooie](#rare), and many other N64 titles.*

* [noclip.website (Banjo)](https://github.com/magcius/noclip.website/blob/main/src/BanjoKazooie/f3dex.ts) ⭐ 4,251 | 🐛 86 | 🌐 TypeScript | 📅 2026-08-26 - F3DEX implementation for Banjo-Kazooie viewer.
* [RT64](https://github.com/rt64/rt64) ⭐ 1,587 | 🐛 89 | 🌐 C++ | 📅 2026-09-03 - N64 graphics renderer implementing the RDP/F3D microcode family with enhancements (widescreen, higher resolutions, ray tracing) for emulators and native ports.
* [fast64](https://github.com/Fast-64/fast64) ⭐ 532 | 🐛 76 | 🌐 Python | 📅 2026-09-01 - Blender plugin for exporting F3D display lists for N64 decompilation projects (Super Mario 64, Ocarina of Time).
* [MeltyTool (F3dzex2)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/F3dzex2) ⭐ 206 | 🐛 60 | 🌐 C# | 📅 2026-09-05 - F3DZEX2 format support.
* [n64-fast3d-engine](https://github.com/Emill/n64-fast3d-engine) ⭐ 146 | 🐛 7 | 🌐 C++ | 📅 2022-03-09 - N64 Fast3D engine implementation.
* [F3DEX3](https://github.com/HackerN64/F3DEX3) ⭐ 144 | 🐛 1 | 🌐 C | 📅 2026-07-19 - Modern, heavily rewritten F3D-family microcode for N64 romhacks; rewrites vertex/lighting code from scratch for higher performance, adds new visual features (simultaneous vertex colors + normals, ambient occlusion), and improves accuracy over F3DEX2.
* [n64rawgfx](https://github.com/Octocontrabass/n64rawgfx) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2013-11-22 - Exports and imports uncompressed ("raw") N64 graphics (RGBA, CI, IA, I formats) to/from BMP files, e.g. for Super Mario 64 texture editing.
* [F3DEX2Decoder](https://github.com/Mr-Wiseguy/F3DEX2Decoder) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2022-02-20 - Decoder for F3DEX2 display lists.
* [F3D2F3DEX](https://github.com/Trenavix/F3D2F3DEX) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2018-12-15 - Converter between F3D variants.
* [pigment64](https://github.com/decompals/pigment64) ⭐ 4 | 🐛 3 | 🌐 Rust | 📅 2025-12-29 - Rust library for converting N64 image data (Intensity, IA, CI, RGBA formats) between native and PNG formats, used by N64 decompilation projects.
* [Hack64 Fast3D Commands](https://hack64.net/wiki/doku.php?id=super_mario_64:fast3d_display_list_commands) - Documentation for Fast3D display list commands.
* [CloudModding F3DZEX2](https://wiki.cloudmodding.com/oot/F3DZEX2) - Documentation for F3DZEX2 format.

### Granite SDK

*Texture streaming middleware (.gts/.gtp files) used across multiple titles.*

* [GraniteTextureReader](https://github.com/Nenkai/GraniteTextureReader) ⭐ 25 | 🐛 2 | 🌐 C# | 📅 2026-07-13 - Texture reader/extractor for Granite SDK files (.gts/.gtp).

### Havok

*Physics and animation middleware used in hundreds of games across all platforms.*

* [HavokLib](https://github.com/PredatorCZ/HavokLib) ⭐ 94 | 🐛 5 | 🌐 C++ | 📅 2026-03-06 - C++ library for reading, converting, and upgrading/downgrading Havok physics packfiles across versions (5.0.0-2017).
* [MapEditor](https://github.com/BF3RM/MapEditor) ⭐ 79 | 🐛 59 | 🌐 TypeScript | 📅 2026-09-02 - Realtime map editor mod for Venice Unleashed (Battlefield 3).
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

* [noclip.website (JSYSTEM)](https://github.com/magcius/noclip.website/tree/main/src/Common/JSYSTEM) ⭐ 4,251 | 🐛 86 | 🌐 TypeScript | 📅 2026-08-26 - In-browser viewer for JSYSTEM formats.
* [aurora](https://github.com/encounter/aurora) ⭐ 485 | 🐛 11 | 🌐 C++ | 📅 2026-09-04 - Source-level GameCube & Wii GX graphics compatibility layer, used by decompilation and static-recompilation projects to run original GC/Wii rendering code on modern backends (Dawn/WebGPU).
* [MeltyTool (JSystem)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/JSystem) ⭐ 206 | 🐛 60 | 🌐 C# | 📅 2026-09-05 - JSystem format viewer/exporter.
* [GCFT](https://github.com/LagoLunatic/GCFT) ⭐ 164 | 🐛 3 | 🌐 Python | 📅 2026-08-11 - GUI multitool for viewing and modifying common GameCube file formats, built on the gclib library above. See also the author's fast Python compression/format libraries: [PyFastYaz0Yay0](https://github.com/LagoLunatic/PyFastYaz0Yay0) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2025-10-04 (Yaz0/Yay0) and [PyFastBTI](https://github.com/LagoLunatic/PyFastBTI) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2025-02-28 (BTI textures).
* [RiiStudio](https://github.com/snailspeed3/RiiStudio) ⭐ 112 | 🐛 27 | 🌐 C++ | 📅 2025-08-04 - Modern editor for J3D models.
* [SuperBMD](https://github.com/Sage-of-Mirrors/SuperBMD) ⭐ 42 | 🐛 16 | 🌐 C# | 📅 2022-12-08 - BMD/BDL model converter for GameCube/Wii games.
* [WiiExplorer](https://github.com/SuperHackio/WiiExplorer) ⭐ 38 | 🐛 0 | 🌐 C# | 📅 2026-04-23 - Wii filesystem explorer.
* [J3D-Model-Viewer](https://github.com/LordNed/J3D-Model-Viewer) ⭐ 19 | 🐛 1 | 🌐 C# | 📅 2018-01-29 - Viewer for J3D models.
* [ARCTool](https://github.com/tpwrules/ARCTool) ⚠️ Archived - Python script to extract RARC, Yaz0, and U8 archives.
* [Hack.io](https://github.com/SuperHackio/Hack.io) ⭐ 16 | 🐛 1 | 🌐 C# | 📅 2026-07-21 - Libraries for J3D Era formats.
* [picori](https://github.com/Julgodis/picori) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2023-10-24 - Picori (ピッコル) is a library for decompilation, modding, and rom-hacking with focus on GameCube and Wii games.
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
* [BMS-Analyzer](https://github.com/3e2j/BMS-Analyzer) ⚠️ Archived - Nintendo Wii/Gamecube BMS to MIDI converter
* [rarc-rs](https://github.com/gcnhax/rarc-rs) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2018-05-17 - Rust library for RARC archives.
* [GCFontTool](https://github.com/Sage-of-Mirrors/GCFontTool) ⭐ 4 | 🐛 4 | 🌐 C# | 📅 2022-12-08 - GameCube font tool.
* [RarcPack](https://github.com/Sage-of-Mirrors/RarcPack) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2015-10-30 - RARC archive packer.
* [atirut.bdl](https://github.com/atirutw/atirut.bdl) ⭐ 4 | 🐛 0 | 🌐 GDScript | 📅 2023-04-29 - JSYSTEM BMD/BDL model importer for Godot Engine.
* [Rain336/JSystem](https://github.com/Rain336/JSystem) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2023-04-03 - Rust libraries for parsing Nintendo Wii/GameCube file formats.
  * Formats: BCSV, RARC, U8.
* [jampacked](https://github.com/XAYRGA/jampacked) ⭐ 3 | 🐛 1 | 🌐 C# | 📅 2021-09-05 - BAA unpacker for JSYSTEM games.
* [chutools](https://github.com/TwilitRealm/chutools) ⭐ 2 | 🐛 1 | 🌐 C# | 📅 2026-08-31 - Collection of tools for JAudio audio assets in Nintendo games, an updated version of XAYRGA's JAMTools.
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
* [ffl](https://github.com/aboood40091/ffl) ⭐ 28 | 🐛 1 | 🌐 C++ | 📅 2026-03-12 - Decompilation of FFL (Face Library), the successor to RFL used for Mii avatars on Wii U, 3DS, and Switch.
* [RFL](https://github.com/koopthekoopa/RFL) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2026-05-30 - Decompilation of the Revolution Face Library (RFL), Nintendo's Mii avatar library for the Wii.
* [mii2studio](https://github.com/JimKatz/mii2studio) ⭐ 2 | 🐛 0 | 📅 2020-10-31 - Command-line tool converting Mii data between Wii, 3DS, Wii U, Miitomo, and Switch formats, outputting files loadable by Nintendo's Mii Studio and PNG renders via Nintendo's rendering API.

### Katana Engine (Koei Tecmo)

*Koei Tecmo's in-house engine and asset formats (G1M models, G1T texture archives, G1A/G2A skeletal animations), used across Team Ninja, Omega Force, and Gust titles as well as several external collaborations.*

* [Project-G1M](https://github.com/Joschuka/Project-G1M) ⭐ 91 | 🐛 13 | 🌐 C++ | 📅 2026-02-09 - Native C++ Noesis plugin for G1M model, G1T texture, and G1A/G2A skeletal animation files. Used across Nioh, Dead or Alive 5/6, the Warriors series (Dynasty/Samurai Warriors, Hyrule Warriors, Fire Emblem Warriors), Atelier, Toukiden, Fire Emblem: Three Houses, and Persona 5 Scramble. Supersedes the same author's Python-based [fmt\_g1m](https://github.com/Joschuka/fmt_g1m) ⚠️ Archived.

### M3G (Mobile 3D Graphics API)

*Java Mobile 3D Graphics API (JSR-184) used by many J2ME mobile games in the 2000s.*

* [M3G2FBX](https://github.com/RaduMC/M3G2FBX) ⭐ 17 | 🐛 0 | 🌐 C# | 📅 2015-12-07 - Command-line M3G model converter, for Real Racing 3, NFS: Most Wanted, and NFS: No Limits.
* [m3gcore](https://github.com/toaarnio/m3gcore) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2012-08-07 - Core engine implementation (in C) of the M3G (JSR-184) API, originally developed at Nokia Research Center and later released as open source through the Symbian Foundation.
* [M3G-Blender-Exporter](https://github.com/3dcinetv/M3G-Blender-Exporter) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2026-07-10 - Modern M3G (.m3g, JSR-184) exporter for Blender 3.6, implementing a byte-accurate full mobile 3D scene graph.
* [desktop-m3g](https://github.com/vadosnaprimer/desktop-m3g) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2015-12-23 - Free C++ implementation of the M3G 1.1 (JSR-184) API for Linux and Android, with Java and Ruby bindings and a separate M3G-Reader-Writer library for reading/writing the .m3g format.
* [Juinness](https://github.com/BaalNetbek/Juinness) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2025-03-09 - Converts arbitrary 3D models into M3G models.

### Murder Engine

*[Murder Engine](https://github.com/isadorasophia/murder) ⭐ 3,319 | 🐛 16 | 🌐 C# | 📅 2026-09-03, a 2D game engine/framework used by several indie titles.*

* [murder-unpack](https://github.com/yuna0x0/murder-unpack) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-13 - Reverse-engineers exported Murder Engine games back into editor-openable projects.
  * Features: C# decompilation of managed single-file bundles, sprite extraction from texture atlases, dialogue (.gum) export, localization CSV export, per-game engine-version fingerprinting, asset repacking.

### NETLizard (J2ME Game Engine)

* [netlizard](https://github.com/glKarin/netlizard) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2023-04-26 - Parser utility and Qt4 GUI tool for NETLizard 3D J2ME game resource files (models, textures, fonts, text, sprites), reversed from decompiled Java source.
* [NETLizard\_idTech4](https://github.com/glKarin/NETLizard_idTech4) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2025-12-15 - Converter from NETLizard 3D J2ME game resource files to idTech4 format.

### Nebula Engine

*The Nebula Device/Nebula2 engine, used by Project Nomads and other early-2000s titles.*

* [nebula2-assets-extractor](https://github.com/vinceh121/nebula2-assets-extractor) ⭐ 9 | 🐛 6 | 🌐 Java | 📅 2026-05-03 - Extracts and converts asset packs for the Nebula Device 2 engine.
  * Formats: NPK0 archives, NTX1 textures, NOB0 scripts, NVX1 models, NAX0 animations (read, and read/write for most).
  * Features: NVX-to-OBJ/glTF conversion, NTX-to-image and image-to-NTX conversion, NOB script decompilation, NPK packing/unpacking.

### MikuMikuDance

*Freeware animation program and its associated model and motion formats (.pmx, .pmd, .vmd).*

* [MMD Tools](https://github.com/MMD-Blender/blender_mmd_tools) ⭐ 3,235 | 🐛 13 | 🌐 Python | 📅 2026-09-02 - Blender add-on for importing/exporting MikuMikuDance assets. Supports physics, bone constraints, and motion/pose data.
* [MMD Tools Append](https://github.com/MMD-Blender/blender_mmd_tools_append) ⭐ 646 | 🐛 18 | 🌐 Python | 📅 2026-08-17 - Companion extension for MMD Tools that provides material/scene controls, lighting presets, and Rigify helpers.
* [saba](https://github.com/benikabocha/saba) ⭐ 507 | 🐛 20 | 🌐 C++ | 📅 2023-09-21 - C++ library and viewer for loading and playing MikuMikuDance PMD/PMX models, VMD motion, and VPD pose data, with OpenGL/DirectX 11/Vulkan example viewers.
* [MikuMikuLibrary](https://github.com/blueskythlikesclouds/MikuMikuLibrary) ⭐ 244 | 🐛 11 | 🌐 C# | 📅 2026-04-22 - Library for working with MikuMikuDance formats.

### Cal3D

*Cal3D, an open-source skeletal-based 3D character animation library used by several early-2000s indie games.*

* [Cal3d-Noesis](https://github.com/ExIfDev/Cal3d-Noesis) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-03-27 - Noesis addon for Cal3D models and animations.

### Spine (2D Skeletal Animation Middleware)

* [Spine Skeleton Data Converter](https://github.com/wang606/SpineSkeletonDataConverter) ⭐ 394 | 🐛 7 | 🌐 C++ | 📅 2026-07-19 - Command-line converter between Spine skeleton `.skel` (binary) and `.json` formats, with automatic version detection and cross-version conversion across Spine 3.5 through 4.2.
* [Live2d-SpineViewer](https://github.com/promised-bytes/Live2d-SpineViewer) ⭐ 66 | 🐛 2 | 📅 2025-03-30 - Combined viewer for Live2D and Spine 2D skeletal animation assets.
  * Formats: Live2D `.moc`/`.moc3` (with `.moc.bytes` support), Spine `.skel`/`.json`/`.atlas` across versions 2.1 through 4.2, plus `.lpk`/`.wpk` archive packages.
  * Features: Texture atlas slicing and premultiplied-alpha (PMA) handling.
* [spine2d](https://github.com/Latias94/spine2d) ⭐ 14 | 🐛 0 | 🌐 Rust | 📅 2026-08-03 - Experimental, pure Rust (unofficial) runtime for Spine 4.3, parsing skeleton/atlas data without FFI bindings to the official spine-c/spine-cpp runtimes; renderer-agnostic core with wgpu and Bevy integrations.
* [Spine-Asset-Py](https://github.com/isHarryh/Spine-Asset-Py) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-07-01 - Python library for parsing Spine skeletal animation asset files (`.skel`/`.atlas`).
* [Spine Magic Builder](https://github.com/Randombirdnoise/Spine_Magic_Builder) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - Windows toolkit for reconstructing scattered or mislabeled Spine skeleton/atlas/texture assets by scanning a directory tree at the byte level and matching candidates, with a GUI picker for visual validation against SpineViewer.

### RenderWare

*Cross-platform 3D engine and middleware developed by Criterion Games. Powering the Grand Theft Auto trilogy (III, Vice City, San San Andreas), Burnout series, and many other titles.*

* [librw](https://github.com/aap/librw) ⭐ 809 | 🐛 50 | 🌐 C++ | 📅 2026-08-26 - Re-implementation of the RenderWare Graphics engine.
* [DragonFF](https://github.com/Parik27/DragonFF) ⭐ 518 | 🐛 77 | 🌐 Python | 📅 2026-08-30 - Blender add-on for RenderWare `.dff` models, `.txd` textures, `.col` collisions, and `.ipl` map data.
* [gtaRenderHook](https://github.com/petrgeorgievsky/gtaRenderHook) ⭐ 277 | 🐛 15 | 🌐 C++ | 📅 2026-06-14 - Rendering hook/reimplementation for Grand Theft Auto: San Andreas, reading the original game's RenderWare model, texture, and world data.
* [RenderWare3Docs](https://github.com/electronicarts/RenderWare3Docs) ⭐ 218 | 🐛 0 | 📅 2017-02-28 - Official Electronic Arts release of RenderWare Graphics 3 white papers and user guides, covering the engine's file formats and APIs.
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

* [CriPakTools](https://github.com/esperknight/CriPakTools) ⭐ 251 | 🐛 10 | 🌐 C# | 📅 2018-05-20 - Tools for extracting and repacking CRI CPK archives used in many Japanese games.
* [WannaCRI](https://github.com/donmai-me/WannaCRI) ⭐ 186 | 🐛 13 | 🌐 Python | 📅 2025-11-02 - Python library and CLI for extracting and creating CRI USM video files (VP9/H.264, encrypted and unencrypted) with embedded HCA audio.
* [SonicAudioTools](https://github.com/blueskythlikesclouds/SonicAudioTools) ⭐ 167 | 🐛 2 | 🌐 C# | 📅 2024-01-16 - Toolset for modifying CRIWARE file formats.
  * Features: ACB Editor, ACB Finder (link AWB to ACB), ACB Injector, CPK Unpacker.
  * Formats: .acb, .awb, .cpk, .adx, .adx2, .csb.
* [CriPakTools (GUI)](https://github.com/wmltogether/CriPakTools) ⭐ 139 | 🐛 0 | 🌐 C# | 📅 2019-09-20 - GUI version of CriPakTools with additional features including Shift-JIS support, 2GB+ CPK support for PS3, batch mode, compression support, and improved CPK header handling.
* [HCADecoder](https://github.com/Nyagamon/HCADecoder) ⭐ 139 | 🐛 4 | 🌐 C++ | 📅 2018-01-23 - Original decoder for CRI's HCA (ADX2) audio format, the canonical reference implementation other HCA tools are based on.
* [CriTools](https://github.com/kohos/CriTools) ⭐ 123 | 🐛 4 | 🌐 JavaScript | 📅 2020-08-23 - JavaScript tools for extracting audio from CRIWARE game files (ADX/HCA from CPK archives).
* [CriCodecs](https://github.com/Youjose/CriCodecs) ⭐ 108 | 🐛 1 | 🌐 C++ | 📅 2026-08-25 - Python frontend for CRI codec tools.
* [ACE](https://github.com/LazyBone152/ACE) ⭐ 89 | 🐛 0 | 📅 2023-12-25 - GUI tool (Audio Cue Editor) for editing and previewing CRIWARE ACB/AWB files.
* [UsmToolkit](https://github.com/Rikux3/UsmToolkit) ⚠️ Archived - Converts CRI USM video files into user-friendly formats, using ffmpeg and vgmstream. See also [UsmToolkitHandler](https://github.com/KojoBailey/UsmToolkitHandler) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2025-11-04, a companion tool that speeds up the conversion process.
* [CriFsV2Lib](https://github.com/Sewer56/CriFsV2Lib) ⭐ 45 | 🐛 5 | 🌐 C# | 📅 2024-02-03 - Library for working with CRI FileSystem V2 archives.
* [hca](https://github.com/Ishotihadus/hca) ⭐ 22 | 🐛 1 | 🌐 C | 📅 2023-04-24 - Efficient, high-quality decoder for CRI's HCA (ADX2) audio format used by many CRIWARE-based games.
* [AfsLib](https://github.com/Sewer56/AfsLib) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2025-12-07 - Simple, relatively fast library for reading and writing CRIWare AFS archives.
* [cri-archive-lib](https://github.com/rirurin/cri-archive-lib) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-09-05 - Rust library for reading and writing CRI CPK archives.
* [AfsBatch](https://github.com/tge-was-taken/AfsBatch) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2019-11-12 - Batch AFS packer. Packs each subdirectory in a given directory into an AFS file of the same name.
* [GoldWave\_HcaFile](https://github.com/esterTion/GoldWave_HcaFile) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2024-09-06 - HCA/ACB playback and export plugin for the GoldWave audio editor.
* [Universal-CPK-Mod-Installer](https://github.com/PTKay/Universal-CPK-Mod-Installer) ⭐ 2 | 🐛 0 | 🌐 Batchfile | 📅 2020-07-18 - Universal installer for CPK mod files.

### PSB (Persistent Serialized Binary)

*Serialized data/archive format used by many Japanese visual novel and mobile game engines (M2/Emote, CatSystem2, and others).*

* [FreeMote](https://github.com/UlyssesWu/FreeMote) ⭐ 511 | 🐛 3 | 🌐 C# | 📅 2026-09-01 - Toolset and managed library for EMT/PSB (M2 Packaged Struct Binary) files used by many Japanese visual novels and mobile games.
  * Tools: PsbDecompile/PsBuild (decompile PSB to JSON + resources and recompile), EmtConvert (convert PSB between engine/platform variants), FreeMote Viewer (renders unencrypted PSB).
  * Formats: PSB, PSZ, MDF, PIMG, SCN, MMO, EMTBYTES, MTN, DPAK.
* [psbfile](https://github.com/number201724/psbfile) ⭐ 72 | 🐛 0 | 🌐 C | 📅 2022-07-02 - Decompiler and rebuilder for the galgame PSB file format.
* [FreeMote-SDK](https://github.com/Project-AZUSA/FreeMote-SDK) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2020-05-24 - SDK for "Special Emote" engines that take pure (unencrypted) PSB files as input, working around M2 Emote's per-version key isolation.
* [emote-psb-rs](https://github.com/storycraft/emote-psb-rs) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-03-20 - Rust library and CLI for parsing, decoding and encoding M2 Emote PSB files.

### XNA

*Microsoft XNA Framework model format used in various Xbox 360 and PC games.*

* [FNA](https://github.com/FNA-XNA/FNA) ⭐ 3,038 | 🐛 68 | 🌐 C# | 📅 2026-09-02 - Accuracy-focused reimplementation of the XNA4 framework for modern platforms, reading original .xnb content files; widely used to port XNA-based games (Terraria, Bastion, Fez, and others).
* [blender\_xna](https://github.com/REDxEYE/blender_xna) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2023-05-30 - Blender import plugin for XNA model formats.
* [XNA-Noesis-Importer](https://github.com/ExIfDev/XNA-Noesis-Importer) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-11-18 - Noesis script to import Microsoft XNA, MonoGame, and FNA model files (.xnb).
* [xnb](https://github.com/Lekuruu/xnb) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-08-10 - Python library for reading XNA .xnb content files, currently deserializing Texture2D entries with the BGRA surface format.

### Sappy (GBA Audio)

*SDK-provided formats for the Game Boy Advance sound engine. Used in [Pokémon Gen III](#gen-iii) and many other GBA titles.*

* [agbplay](https://github.com/ipatix/agbplay) ⭐ 154 | 🐛 6 | 🌐 C++ | 📅 2026-09-03 - Music player and music ripper for GBA.
* [gba-mus-ripper](https://github.com/berg8793/gba-mus-ripper) ⭐ 37 | 🐛 2 | 🌐 C++ | 📅 2020-09-12 - GBA music ripper.
* [wav2agb](https://github.com/ipatix/wav2agb) ⭐ 33 | 🐛 0 | 🌐 C++ | 📅 2025-08-30 - Converts standard WAV files to GBA-compatible assembly (`.s`) sample data for the m4a sound engine.
  * See also [se2m4a](https://github.com/laqieer/se2m4a) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-10-13, a companion tool converting sound effects to m4a-compatible assembly source.
* [saptapper](https://github.com/loveemu/saptapper) ⭐ 32 | 🐛 2 | 🌐 C++ | 📅 2026-05-18 - Automated GSF ripper for Game Boy Advance games using the Sappy driver. Extracts music from GBA ROMs automatically.
* [engine-software-gba-tools](https://github.com/lunasorcery/engine-software-gba-tools) ⚠️ Archived - Tools for interacting with music data in GBA games that use the Engine Software (developer) replayer.
* [m4a2s](https://github.com/ipatix/m4a2s) ⭐ 24 | 🐛 0 | 🌐 C# | 📅 2020-07-16 - Extracts music and sound data from GBA games using the mp2k/m4a sound driver, outputting assembly source for sequences, voicegroups, and samples while preserving pointer links via auto-generated global names.
* [Sappy (Touched)](https://github.com/Touched/Sappy) ⭐ 20 | 🐛 0 | 🌐 Visual Basic | 📅 2015-05-14 - Fork with additional features.
* [gba-audio-extractor](https://github.com/DenSinH/gba-audio-extractor) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2024-03-26 - Tool for extracting audio from GBA ROMs.
* [gsfopt](https://github.com/loveemu/gsfopt) ⭐ 9 | 🐛 3 | 🌐 C++ | 📅 2021-06-01 - GSF (GBA Sound Format) optimizer tool. Optimizes GSF sets by removing unused code/data, converts minigsfs/gsflibs to single GSF files, and includes timing functionality for auto-tagging.
* [shinen-gax-python](https://github.com/beanieaxolotl/shinen-gax-python) ⭐ 8 | 🐛 7 | 🌐 Python | 📅 2026-01-09 - Python tools for Shin'en Multimedia's GAX Sound Engine used in Game Boy Advance games. Includes conversion, unpacking, waveform dumping, and song rendering tools. Also supports NAX Sound Engine format.
* [deadbeef\_GSFdecoder](https://github.com/joshbarrass/deadbeef_GSFdecoder) ⭐ 4 | 🐛 7 | 🌐 C | 📅 2024-02-14 - GSF decoder plugin for DeaDBeeF media player. Enables playback of GSF (GBA Sound Format) files in DeaDBeeF, based on viogsf/VBA-M.
* [sappy](https://github.com/maddievision/sappy) ⭐ 3 | 🐛 0 | 🌐 Visual Basic 6.0 | 📅 2025-09-06 - GBA sound tool.
* [SapPy](https://github.com/mayhaps-perchance/SapPy) ⚠️ Archived - Python-based GBA sound tool.
* [gba-audio-tools](https://github.com/mudassarzahid/gba-audio-tools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-10 - Tools for extracting and converting Game Boy Advance Sappy-driven audio.
* [wav28ad](https://github.com/laqieer/wav28ad) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2024-12-23 - Converts WAV files to the `.8ad` ADPCM sample format used by GBA homebrew sound engines, per [pineight's 8ad format notes](https://pineight.com/gba/#8ad).

### RAD Game Tools

*Middleware provider (Bink video, Granny 3D, Miles Sound System) used in hundreds of games across all platforms.*

* [Granny Converter Library](https://github.com/Anohros/GrannyConverterLibrary) ⭐ 33 | 🐛 3 | 🌐 C++ | 📅 2026-07-26 - C++ library for converting Granny2 (.gr2) models and animations to FBX format.
* [opengr2](https://github.com/arves100/opengr2) ⭐ 16 | 🐛 3 | 🌐 C | 📅 2022-05-31 - Open source Granny2 (.gr2) input/output library and tools, with accompanying file format documentation.
* [Knit](https://github.com/neptuwunium/Knit) ⚠️ Archived - Fully managed C# reader for Granny 2 files used in many games.
* [opengr2-rs](https://github.com/NoFr1ends/opengr2-rs) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2023-09-03 - Open source Rust parser for Granny2 (.gr2) files.
* [GR2Toolkit](https://github.com/REDxEYE/GR2Toolkit) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-11-11 - Toolkit for working with Granny 3D (GR2) model format files.
* [piggy](https://github.com/Pyogenics/piggy) ⭐ 3 | 🐛 6 | 🌐 C | 📅 2026-04-15 - Portable decompilation of RAD Game Tools' Iggy Game UI middleware library, aiming to provide an open-source drop-in replacement (originally targeting Minecraft: Legacy Console Edition).
* [opengr2-bevy](https://github.com/NoFr1ends/opengr2-bevy) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2024-06-28 - Bevy engine file loader for Granny2 (.gr2) files, built on opengr2-rs.
* [bonkdec](https://github.com/Helco/bonkdec) ⭐ 0 | 🐛 3 | 🌐 C# | 📅 2022-07-07 - Permissive Bink video decoder library in C#.

### Virtools

* [VirtoolsUnpacker](https://github.com/Hiro420/VirtoolsUnpacker) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2026-02-11 - C# rewrite of Luigi Auriemma's Virtools file unpacker, for extracting Virtools-packed game files.

### Nintendo SDKs & Hardware

*Formats and tools generic to Nintendo consoles or SDKs.*

#### Switch

* [Goldleaf](https://github.com/XorTroll/Goldleaf) ⭐ 3,033 | 🐛 90 | 🌐 C | 📅 2026-08-20 - Multi-purpose homebrew tool for the Nintendo Switch, browsing/installing NSP and NCA titles and inspecting the filesystem.
* [nsz](https://github.com/nicoboss/nsz) ⭐ 2,356 | 🐛 36 | 🌐 Python | 📅 2026-08-23 - Homebrew-compatible NSP/XCI compressor and decompressor for Nintendo Switch game dumps.
* [NSC\_BUILDER](https://github.com/julesontheroad/NSC_BUILDER) ⭐ 2,041 | 🐛 25 | 🌐 Python | 📅 2026-03-01 - Batch-oriented Nintendo Switch NSP/XCI tool for cleaning titlerights encryption and building multicontent NSP/XCI/NSZ/XCZ files.
* [nxdumptool](https://github.com/DarkMatterCore/nxdumptool) ⭐ 1,288 | 🐛 19 | 🌐 C | 📅 2026-08-04 - Generates XCI, NSP, HFS0, ExeFS, and RomFS dumps from Nintendo Switch gamecards and installed titles.
* [nut](https://github.com/blawar/nut) ⭐ 1,269 | 🐛 76 | 🌐 Python | 📅 2026-01-19 - Multi-purpose utility to organize, manage, and install Nintendo Switch NSP, NSZ, XCI and XCZ files, with USB/network install serving for Tinfoil.
* [hactool](https://github.com/SciresM/hactool) ⭐ 1,180 | 🐛 30 | 🌐 C | 📅 2023-12-04 - Tool to view information about, decrypt, and extract Nintendo Switch file formats including NCA, XCI, PFS0, HFS0, RomFS, ExeFS, save data, and more.
* [NX-Shell](https://github.com/joel16/NX-Shell) ⭐ 1,082 | 🐛 18 | 🌐 C | 📅 2022-12-10 - Multi-purpose file manager homebrew for the Nintendo Switch, browsing and previewing images, audio, and archives on the filesystem.
* [nstool](https://github.com/jakcron/nstool) ⭐ 541 | 🐛 14 | 🌐 C++ | 📅 2024-10-14 - General purpose tool to read and extract Nintendo Switch file formats (NSO, NRO, NCA, etc.).
* [SimpleModManager](https://github.com/nadrino/SimpleModManager) ⭐ 463 | 🐛 21 | 🌐 C++ | 📅 2026-02-23 - Homebrew mod manager for the Nintendo Switch (Atmosphere CFW), organizing LayeredFS mod overlay folders per game title ID.
* [XCI-Explorer](https://github.com/StudentBlake/XCI-Explorer) ⭐ 451 | 🐛 21 | 🌐 C# | 📅 2024-03-08 - Tool for viewing contents of Nintendo Switch XCI and NSP files. Features include viewing metadata, exploring partitions, checking NCA hashes, extracting NCA, and modifying certificates.
* [NxFileViewer](https://github.com/Myster-Tee/NxFileViewer) ⭐ 342 | 🐛 13 | 🌐 C# | 📅 2025-10-08 - GUI viewer for the contents of Nintendo Switch container files.
* [TegraRcmSmash](https://github.com/rajkosto/TegraRcmSmash) ⭐ 164 | 🐛 4 | 🌐 C++ | 📅 2018-06-21 - C++ reimplementation of fusee-launcher for Nintendo Switch RCM payloads.
* [exefs\_patches](https://github.com/misson20000/exefs_patches) ⭐ 130 | 🐛 6 | 📅 2025-08-03 - ExeFS patching tool for Nintendo Switch.
* [goldbricks](https://github.com/blawar/goldbricks) ⭐ 115 | 🐛 2 | 🌐 C | 📅 2019-11-09 - Homebrew Nintendo Switch client for installing NSP packages via USB, GDrive or a nut server.
* [HACGUI](https://github.com/shadowninja108/HACGUI) ⭐ 72 | 🐛 2 | 🌐 C# | 📅 2020-04-06 - A comprehensive interface for extracting Nintendo Switch contents, deriving keys, and mounting filesystems (NAND, RomFS, Save).
* [hac2l](https://github.com/Atmosphere-NX/hac2l) ⭐ 56 | 🐛 3 | 🌐 C++ | 📅 2024-10-31 - Modern rewrite of hactool for viewing, decrypting, and extracting Nintendo Switch file formats, especially NCA (Nintendo Content Archive).
* [Fuse-Nx](https://github.com/averne/Fuse-Nx) ⭐ 36 | 🐛 0 | 🌐 C++ | 📅 2025-02-07 - FUSE driver (and supporting tools) for mounting various Nintendo Switch file formats as a browsable filesystem.
* [ghidra-nn-stuff](https://github.com/averne/ghidra-nn-stuff) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2026-07-10 - Collection of Ghidra tools and data for reverse engineering Nintendo Switch sysmodule binaries.
* [switch-libpulsar](https://github.com/p-sam/switch-libpulsar) ⭐ 12 | 🐛 0 | 🌐 C | 📅 2021-08-01 - Switch homebrew library to load, parse, and play sounds from BFSAR (binary sound archive) files and related audio file formats.
* [nxtik](https://github.com/jam1garner/nxtik) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2024-08-09 - Library and tool for parsing Nintendo Switch .tik (ticket) files.
* [switch-reversing](https://github.com/SciresM/switch-reversing) ⭐ 10 | 🐛 0 | 📅 2024-10-08 - Reverse engineering resources for Nintendo Switch.
* [mkbktr](https://github.com/rschlaikjer/mkbktr) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2024-11-27 - Generates BKTR update packages for Nintendo Switch titles.
* [LegacySwitchLibraries](https://github.com/KillzXGaming/LegacySwitchLibraries) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2026-05-21 - Switch file format libraries for Switch Toolbox and other programs.
* [shader-compiler-rs](https://github.com/DCNick3/shader-compiler-rs) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2025-06-22 - Recompiles binary Maxwell shaders (as found in Nintendo Switch executables) to GLSL.
* [nx-archive](https://github.com/RyouVC/nx-archive) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2025-03-27 - Rust library for reading and writing Nintendo Switch package archive formats.
* [frhop](https://github.com/SmartBoy84/frhop) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2025-07-06 - Lightweight utility to serve Nintendo Switch archives over USB for installation.
* [nxo-parser](https://github.com/jam1garner/nxo-parser) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2020-12-30 - Rust parsers for Nintendo Switch executable formats (NSO/NRO).
* [hac-rs](https://github.com/DCNick3/hac-rs) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2023-07-14 - Rust library for reading some of the file formats used by the Nintendo Switch operating system.

#### iQue Player

* [iQueTool](https://github.com/emoose/iQueTool) ⭐ 17 | 🐛 1 | 🌐 C# | 📅 2018-12-03 - File manipulator for iQue Player (神游机) file formats.
* [iQuePlayer-SecureKernel](https://github.com/decompals/iQuePlayer-SecureKernel) ⭐ 5 | 🐛 2 | 🌐 C | 📅 2025-04-27 - Reverse engineering of the iQue Player Secure Kernel (SK).
* [iQuePlayer-BootROM](https://github.com/decompals/iQuePlayer-BootROM) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2024-04-01 - Matching decompilation of the iQue Player (Chinese N64 variant) Boot ROM.
* [iQuePlayer-SystemApp](https://github.com/decompals/iQuePlayer-SystemApp) ⭐ 3 | 🐛 1 | 🌐 C++ | 📅 2026-01-12 - Reverse engineering of the iQue Player System App (SA).

#### Wii U

* [noclip.website (Wii U Transfer Tool)](https://github.com/magcius/noclip.website/tree/main/src/rres) ⭐ 4,251 | 🐛 86 | 🌐 TypeScript | 📅 2026-08-26 - In-browser viewer for the Wii U Transfer Tool's scenes, reading the app's NW4R/BRRES assets.
* [wfs-tools](https://github.com/koolkdev/wfs-tools) ⭐ 93 | 🐛 12 | 🌐 C++ | 📅 2026-03-01 - Command-line tools for the Wii U WFS filesystem, built on wfslib. See also [wfs-tools-web](https://github.com/koolkdev/wfs-tools-web) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-16, a web-based version powered by WebAssembly.
* [wudump](https://github.com/FIX94/wudump) ⭐ 78 | 🐛 14 | 🌐 C | 📅 2022-02-15 - Dumps raw images from a Wii U game disc. See also [disc2app](https://github.com/koolkdev/disc2app) ⭐ 58 | 🐛 1 | 🌐 C | 📅 2020-12-05, a fork that extracts decrypted .app/.h3/.tmd/.cert/.tik content instead of a raw dump.
* [WiiUTools](https://github.com/NWPlayer123/WiiUTools) ⭐ 70 | 🐛 3 | 🌐 Python | 📅 2016-07-01 - Collection of Python utilities for working with Wii U file formats including IPK packages, RPX executables, SARC archives, and texture editing (TexHaxU/TexHaxU2).
* [saviine](https://github.com/Maschell/saviine) ⭐ 70 | 🐛 9 | 🌐 C | 📅 2020-07-28 - Dumps and injects Wii U save data, for use with the Homebrew Launcher.
* [Cafe-Shader-Studio](https://github.com/KillzXGaming/Cafe-Shader-Studio) ⭐ 62 | 🐛 14 | 🌐 C# | 📅 2023-04-12 - Shader editor and viewer for Wii U games.
* [wiiu-things](https://github.com/ihaveamac/wiiu-things) ⭐ 61 | 🐛 3 | 🌐 Python | 📅 2024-05-27 - Scripts and notes documenting the Wii U FST (filesystem table) format layout.
* [wfslib](https://github.com/koolkdev/wfslib) ⭐ 55 | 🐛 7 | 🌐 C++ | 📅 2026-08-01 - WFS (WiiU File System) library and tools.
* [fuse-wiiu](https://github.com/Maschell/fuse-wiiu) ⭐ 49 | 🐛 1 | 🌐 Java | 📅 2022-02-01 - FUSE filesystem for extracting data from Wii U titles in various formats.
* [nusserver](https://github.com/ihaveamac/nusserver) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2018-01-16 - Custom Nintendo Update Server (NUS) implementation, companion to nuspacker/nustool.
* [nuspacker](https://github.com/ihaveamac/nuspacker) ⭐ 41 | 🐛 4 | 🌐 Java | 📅 2017-11-13 - Packs files into an installable Wii U content format (NUS package).
* [JNUSLib](https://github.com/Maschell/JNUSLib) ⭐ 25 | 🐛 9 | 🌐 Java | 📅 2022-02-01 - Java library for handling Wii U NUS content (.app, tmd, tik, cert files) from local files, the NUS server, or .woomy/.wud/.wux/.wumad images, with decryption, extraction, and .wud-to-.wux compression.
* [WiiUZip](https://github.com/jam1garner/WiiUZip) ⭐ 19 | 🐛 2 | 🌐 C# | 📅 2017-08-01 - Archive manager for Wii U filetypes.
* [wiiuqt](https://github.com/koolkdev/wiiuqt) ⭐ 16 | 🐛 1 | 🌐 C++ | 📅 2017-03-24 - Qt-based Wii U NAND tools, built alongside koolkdev's wfs-tools.
* [GTX-Extractor](https://github.com/Gota7/GTX-Extractor) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2017-07-22 - Wii U GX2 texture extraction tool. Converts GTX texture files to DDS format for use in modding and asset extraction.

#### 3DS

##### Container & ROM Formats (CXI/CFA/CCI/CIA/NCCH/RomFS)

* [3dsconv](https://github.com/ihaveamac/3dsconv) ⭐ 639 | 🐛 8 | 🌐 Python | 📅 2024-08-13 - Python script converting Nintendo 3DS CCI (.cci/.3ds) cart images to the CIA format, with support for decrypted, NCCH-encrypted, and zerokey-encrypted images.
* [Project\_CTR](https://github.com/3DSGuy/Project_CTR) ⭐ 575 | 🐛 21 | 🌐 C | 📅 2026-06-14 - A collection of custom Nintendo 3DS tools.
  * [ctrtool](https://github.com/3DSGuy/Project_CTR/tree/master/ctrtool) ⭐ 575 | 🐛 21 | 🌐 C | 📅 2026-06-14 - Read/extract 3DS file formats (CXI, CFA, CCI, CIA).
  * [makerom](https://github.com/3DSGuy/Project_CTR/tree/master/makerom) ⭐ 575 | 🐛 21 | 🌐 C | 📅 2026-06-14 - Create 3DS file formats.
* [3DS-rom-tools](https://github.com/ihaveamac/3DS-rom-tools) ⭐ 440 | 🐛 2 | 🌐 Python | 📅 2023-03-17 - Tools and guides for working with Nintendo 3DS game/application formats (.3ds, .cci, .app, .cxi, .cfa, .cia).
* [3dstool](https://github.com/dnasdw/3dstool) ⭐ 414 | 🐛 2 | 🌐 C | 📅 2026-01-24 - All-in-one tool for extracting and creating 3DS file formats.
  * Formats: CIA, CCI, NCCH, NCSD.
* [NDecrypt](https://github.com/SabreTools/NDecrypt) ⭐ 87 | 🐛 2 | 🌐 C# | 📅 2026-08-31 - Encryption/decryption utility for Nintendo cartridge images, supporting Nintendo DS, DSi, 3DS, and New 3DS cartridge formats.
* [braindump](https://github.com/neobrain/braindump) ⚠️ Archived - Early homebrew tool for dumping 3DS game cartridges and eShop titles. Archived, but has no already-listed direct successor for this specific niche.
* [pyctr](https://github.com/ihaveamac/pyctr) ⭐ 41 | 🐛 35 | 🌐 Python | 📅 2026-07-10 - Python library for reading Nintendo 3DS file formats (NCCH, ExeFS, RomFS, CIA, and more), used by several other 3DS tools.
* [RomFS-Builder](https://github.com/SciresM/RomFS-Builder) ⭐ 35 | 🐛 1 | 🌐 C# | 📅 2017-07-08 - Program to convert a folder in Windows into a 3DS RomFS binary. For use with makerom.
* [3dsconv-c](https://github.com/soarqin/3dsconv-c) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2019-11-18 - C port of ihaveamac's 3dsconv, converting Nintendo 3DS CCI cart images to CIA format.
* [rofs\_dumper](https://github.com/PabloMK7/rofs_dumper) ⭐ 10 | 🐛 2 | 🌐 C++ | 📅 2024-12-09 - Dumps very early Nintendo 3DS ROFS containers.

##### Encryption, Keys, Save Data, Titles & CDN

* [custom-install](https://github.com/ihaveamac/custom-install) ⭐ 914 | 🐛 34 | 🌐 Python | 📅 2026-06-05 - Installs a CIA title directly to an SD card for the Nintendo 3DS without needing to run an installer on-console.
* [faketik](https://github.com/ihaveamac/faketik) ⭐ 112 | 🐛 0 | 🌐 Makefile | 📅 2025-10-03 - Generates and installs fake Nintendo 3DS ticket (.tik) files to make missing titles re-appear.
* [save3ds](https://github.com/wwylele/save3ds) ⭐ 79 | 🐛 5 | 🌐 Rust | 📅 2026-08-01 - Extract/import/FUSE tool for the Nintendo 3DS common save format (DISA/DIFF), covering save data, extdata, and the title database. Upstream of ihaveamac's save3ds fork.
* [3ds-save-tool](https://github.com/wwylele/3ds-save-tool) ⭐ 60 | 🐛 2 | 🌐 Python | 📅 2025-01-05 - Tools for parsing and extracting files from Nintendo 3DS save (DISA) and extdata (DIFF) containers.
* [ctrcdnfetch](https://github.com/luigoalma/ctrcdnfetch) ⭐ 53 | 🐛 3 | 🌐 C++ | 📅 2022-03-06 - Downloads title content from the Nintendo CDN for the 3DS without requiring a console, working around post-11.8 server-side checks.
* [3dscrypto-tools](https://github.com/yellows8/3dscrypto-tools) ⭐ 29 | 🐛 0 | 🌐 C | 📅 2020-06-03 - Nintendo 3DS crypto tools: decrypt NCCH, CDN titles/tickets, save images, SpotPass/BOSS containers, and New3DS FIRM ARM9 sections.
* [otptool](https://github.com/SciresM/otptool) ⭐ 27 | 🐛 3 | 🌐 C | 📅 2021-10-19 - Tool for Nintendo OTP (One-Time Programmable) files.
* [eshop-analysis](https://github.com/d0k3/eshop-analysis) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2021-02-28 - Python script to analyze and parse Nintendo 3DS eShop title-list data.
* [HomeMenuEditor3DS](https://github.com/mrissaoussama/HomeMenuEditor3DS) ⭐ 20 | 🐛 0 | 🌐 C# | 📅 2025-06-01 - Tool for editing the Nintendo 3DS Home Menu layout database, moving/organizing/renaming titles and folders.
* [CECTool](https://github.com/FlagBrew/CECTool) ⭐ 15 | 🐛 3 | 🌐 C++ | 📅 2019-08-03 - Proof-of-concept tool for injecting data into the 3DS's CEC (StreetPass) message format.
* [rebuild-title-database](https://github.com/ihaveamac/rebuild-title-database) ⭐ 14 | 🐛 3 | 🌐 Python | 📅 2024-04-08 - Script to rebuild the contents of a Nintendo 3DS title.db Title Database, working alongside save3ds\_fuse.
* [cmd-gen](https://github.com/ihaveamac/cmd-gen) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2019-06-07 - Experimental script to generate CMD files for Nintendo 3DS SD titles.
* [save-data-copy-tool](https://github.com/ihaveamac/save-data-copy-tool) ⭐ 8 | 🐛 2 | 🌐 Makefile | 📅 2025-08-16 - Copies Nintendo 3DS save data between gamecard and digital versions of the same game.
* [dumptik](https://github.com/ihaveamac/dumptik) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2019-01-22 - Dumps all ticket (.tik) files from a Nintendo 3DS console.
* [save-crypto-finder](https://github.com/ihaveamac/save-crypto-finder) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-04-13 - Determines which titles a collection of encrypted Nintendo 3DS save files belong to, using boot9 and movable.sed.
* [firmswap](https://github.com/ihaveamac/firmswap) ⚠️ Archived - Python implementation of the hardmod downgrade for Nintendo 3DS, working directly with FIRM partition data.
* [search-3ds](https://github.com/ihaveamac/search-3ds) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2017-08-13 - Searches the contents of encrypted/decrypted files used on the Nintendo 3DS system.
* [restore-overwritten-secureinfo](https://github.com/ihaveamac/restore-overwritten-secureinfo) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2024-12-14 - Restores a Nintendo 3DS console's SecureInfo\_A/B file from inspect.log data.
* [gen-title-info-entry](https://github.com/ihaveamac/gen-title-info-entry) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2019-05-31 - Experimental script to generate the Title Info Entry structure used in a Nintendo 3DS title.db.
* [3ds-snes-sc](https://github.com/foohyfooh/3ds-snes-sc) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2023-11-20 - Converts save data between the 3DS Virtual Console SNES format and the standard .SRM format used by SNES emulators.

##### Graphics, Models, Textures & Fonts (CTPK/BCH/CGFX/BCLIM)

* [Ohana3DS-Rebirth](https://github.com/gdkchan/Ohana3DS-Rebirth) ⭐ 210 | 🐛 47 | 🌐 C# | 📅 2022-09-17 - Tool to view, extract, and replace models, textures, and animations from decrypted 3DS ROMs (BCH, CGFX).
* [3DS Data Tools](https://github.com/ObsidianX/3dstools) ⭐ 62 | 🐛 16 | 🌐 Python | 📅 2023-07-30 - Suite of Python tools for extracting and packing resources found in Nintendo 3DS games.
  * Formats: MSBT (message text extraction/repacking, with color-code handling), SARC (archive extraction/creation with ZLIB compression), BFFNT (font atlas to/from PNG+JSON manifest), BFLIM (texture to/from PNG, with swizzle support).
* [tex3ds](https://github.com/devkitPro/tex3ds) ⭐ 56 | 🐛 11 | 🌐 C++ | 📅 2024-10-13 - Converts images into the Nintendo 3DS homebrew `.t3x` texture format (and BCFNT fonts via the bundled mkbcfnt), with atlas, cubemap, skybox, mipmap, and compression options.
* [pycgfx](https://github.com/skyfloogle/pycgfx) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2025-06-02 - Program for converting glTF models into the Nintendo 3DS's CGFX format.
* [png2bclim](https://github.com/kwsch/png2bclim) ⭐ 23 | 🐛 0 | 🌐 C# | 📅 2015-11-22 - Converter between PNG and the Nintendo BCLIM texture format.
* [bchtool](https://github.com/dnasdw/bchtool) ⭐ 13 | 🐛 1 | 🌐 C++ | 📅 2019-03-02 - Tool for exporting and importing BCH model files used in Nintendo 3DS games.
* [txobtool](https://github.com/dnasdw/txobtool) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2019-05-25 - Tool for exporting and importing CGFX graphics files used in Nintendo 3DS games.
* [ctpktool](https://github.com/dnasdw/ctpktool) ⭐ 10 | 🐛 2 | 🌐 C++ | 📅 2019-07-09 - Tool for exporting/importing CTPK texture package files used in Nintendo 3DS games.
* [splashtool](https://github.com/profi200/splashtool) ⭐ 10 | 🐛 1 | 🌐 C++ | 📅 2017-12-25 - Generates Nintendo 3DS splash screen files in a custom format, with support for compression and common pixel formats.
* [BcmdlImporter](https://github.com/KillzXGaming/BcmdlImporter) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2022-07-16 - Tool to import DAE, FBX, and OBJ models into Nintendo 3DS BCMDL (CGFX-based) format without external libraries or toolkits.
* [bclimtool](https://github.com/dnasdw/bclimtool) ⭐ 6 | 🐛 1 | 🌐 C++ | 📅 2018-07-27 - Tool for decoding and encoding the Nintendo BCLIM texture format.
* [apk-tools](https://github.com/wrongbaud/3ds-apk-tools) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2017-06-04 - Python tools and a 010 Editor template for unpacking and repacking APK texture archive files found in various Nintendo 3DS game ROMs.
* [bclyt-stuff](https://github.com/Stary2001/bclyt-stuff) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2017-12-31 - Research and tools for the Nintendo BCLYT layout format, used across 3DS, Wii U, and Switch UI layouts.
* [3DS-Font](https://github.com/JayFoxRox/3ds-font) ⭐ 3 | 🐛 1 | 🌐 C | 📅 2016-09-02 - Extracts and recreates Nintendo 3DS shared BCFNT font files, for use in the Citra emulator or homebrew projects.
* [3ds-bannertool](https://github.com/ihaveamac/3ds-bannertool) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2024-11-30 - Tool for creating Nintendo 3DS banners; fork of carstene1ns/3ds-bannertool adding Windows Unicode fixes and a CMake build system.
* [NSMBHD Wiki (BCRES)](https://nsmbhd.net/wiki/BCRES/) - BCRES format documentation for 3DS games.

##### Homebrew, CFW & Mod Tools

* [Checkpoint](https://github.com/BernardoGiordano/Checkpoint) ⭐ 3,068 | 🐛 30 | 🌐 C++ | 📅 2026-08-30 - Fast and simple homebrew save management framework for 3DS and Switch.
* [GodMode9](https://github.com/d0k3/GodMode9) ⭐ 2,623 | 🐛 29 | 🌐 C | 📅 2026-08-01 - Full access file browser and manager for Nintendo 3DS handling game file formats and system files.
* [Anemone3DS](https://github.com/astronautlevel2/Anemone3DS) ⭐ 1,146 | 🐛 33 | 🌐 C | 📅 2026-08-18 - Theme and splashscreen manager for the Nintendo 3DS, handling BCSTM audio and theme/splash archive formats.
* [libctru](https://github.com/devkitPro/libctru) ⭐ 957 | 🐛 37 | 🌐 C | 📅 2026-02-19 - Reverse-engineered Nintendo 3DS system library (CTRULib) exposing OS/hardware services (filesystem, graphics, audio, networking) to homebrew, forming the base library underlying GodMode9, Checkpoint, and most other 3DS homebrew tools listed above.
* [Magikoopa](https://github.com/RicBent/Magikoopa) ⭐ 53 | 🐛 2 | 🌐 C++ | 📅 2019-06-29 - Compiles custom C code for Nintendo 3DS games and injects it into existing code.bin files, patching the exheader accordingly.
* [Lasagna](https://github.com/BernardoGiordano/Lasagna) ⭐ 47 | 🐛 4 | 🌐 C++ | 📅 2018-01-30 - LayeredFS patch manager for Luma3DS, organizing romfs/exefs mod overlay folder structures.
* [crotools](https://github.com/shinyquagsire23/crotools) ⭐ 14 | 🐛 1 | 🌐 C++ | 📅 2022-09-27 - Collection of tools for the Nintendo 3DS CRO/CRR shared-library binary format.
* [videoinject](https://github.com/ihaveamac/videoinject) ⚠️ Archived - Tool for injecting/creating Nintendo 3DS moflex video files.
* [layeredFS](https://github.com/ihaveamac/layeredFS) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2016-03-11 - LayeredFS mod for OSX/Linux/UNIX, modified to work from a decompressed code.bin instead of exefs.bin.

#### GameCube & Wii

##### Disc Images, Filesystem & Memory Card Formats

* [nod](https://github.com/encounter/nod) ⭐ 63 | 🐛 15 | 🌐 Rust | 📅 2026-07-17 - Rust library for reading and writing Nintendo Optical Disc images (GameCube and Wii). Includes nodtool CLI for extraction, conversion, and verification.
  * Formats: ISO (GCM), WIA/RVZ, WBFS, CISO, NFS (Wii U VC), GCZ, TGC.
* [pyisotools](https://github.com/JoshuaMKW/pyisotools) ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2025-10-17 - Python library for working with GameCube ISOs (GCM).
* [GCReLink](https://github.com/Cuyler36/GCReLink) ⚠️ Archived - Tool for unpacking and repacking GameCube and Wii relocatable modules (REL files).
* [triforce-header-patcher](https://github.com/FIX94/triforce-header-patcher) ⭐ 16 | 🐛 1 | 🌐 C | 📅 2021-10-28 - Verifies Triforce arcade disc images and patches in the correct headers.
* [triforce-nand-iso-extract](https://github.com/FIX94/triforce-nand-iso-extract) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2017-09-13 - Converts Triforce (Namco/Sega/Nintendo GameCube-based arcade board) NAND images to ISO files.
* [gc-gcm](https://github.com/jam1garner/gc-gcm) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2021-02-10 - Tool for GameCube GCM file format.
* [LibGCM](https://github.com/Sage-of-Mirrors/LibGCM) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2017-03-26 - Library for GameCube memory card formats.
* [gci-bt](https://github.com/jam1garner/gci-bt) ⭐ 1 | 🐛 0 | 📅 2019-12-24 - GameCube GCI file tool with Bluetooth support.

##### Executables, Code Injection & Modding

* [Kamek](https://github.com/Treeki/Kamek) ⭐ 94 | 🐛 6 | 🌐 C# | 📅 2026-06-09 - Code injection engine for GameCube and Wii games, compiling and linking custom C++ code against the original DOL/REL executables.
* [GeckoLoader](https://github.com/JoshuaMKW/GeckoLoader) ⭐ 44 | 🐛 3 | 🌐 Python | 📅 2024-02-11 - Extends the available code space for Gecko codes on Wii/GameCube games, allowing thousands of lines of Gecko code per game.
* [ida-wii-loaders](https://github.com/heinermann/ida-wii-loaders) ⭐ 30 | 🐛 10 | 🌐 C++ | 📅 2014-05-17 - IDA Pro loader plugins for the GameCube/Wii REL (relocatable module) and DOL executable file formats.
* [HopperPPC-Plugin](https://github.com/Sappharad/HopperPPC-Plugin) ⭐ 23 | 🐛 1 | 🌐 Objective-C | 📅 2018-06-29 - GameCube/Wii .DOL loader and PowerPC (Gecko) disassembly plugin for the Hopper Disassembler.
* [Kuribo](https://github.com/DotKuribo/Kuribo) ⭐ 23 | 🐛 0 | 🌐 C++ | 📅 2024-08-24 - Embedded Wii Channel mod loader, installing mods from an SD card. Loads its own .kxe executable format (supporting GCC, Clang, and CodeWarrior) as well as legacy Kamek .kmk executables.
* [mapdas](https://github.com/intns/mapdas) ⭐ 20 | 🐛 2 | 🌐 C# | 📅 2021-12-15 - Tools for working with Metrowerks symbol map (.map) and Gekko/Dolphin executable (.dol) files.
* [GekkoAssembler](https://github.com/CryZe/GekkoAssembler) ⚠️ Archived - Assembles Gekko Assembly to Action Replay or Gecko Cheat Code format. Used for GameCube and Wii game modding.
* [gc-c-kit](https://github.com/RenolY2/gc-c-kit) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2020-01-12 - Toolkit for compiling C code using devkitppc and injecting it into a GameCube Executable (DOL). Can be adapted to different GC games.
* [geckocode-libs](https://github.com/JoshuaMKW/geckocode-libs) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-05-18 - Python library for parsing and editing Gecko Codes for the Wii/GCN.
* [dolreader](https://github.com/RenolY2/dolreader) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2021-07-08 - Reader for GameCube/Wii DOL executable format.

##### SDK, System Libraries & Decompilations

* [gc-ipl](https://github.com/ogamespec/gc-ipl) ⭐ 57 | 🐛 1 | 🌐 C | 📅 2023-07-23 - Open source reimplementation of the GameCube IPL (boot ROM).
* [dolsdk2001](https://github.com/doldecomp/dolsdk2001) ⭐ 28 | 🐛 2 | 🌐 C | 📅 2025-09-18 - Decompilation of the 5-23-2001 version of the Dolphin (GameCube) SDK libraries.
* [WiiTools](https://github.com/Megazig/WiiTools) ⭐ 26 | 🐛 1 | 🌐 C++ | 📅 2013-10-08 - Tools for Wii reverse engineering and function identification to help hacking Wii games.
* [open\_rvl](https://github.com/kiwi515/open_rvl) ⚠️ Archived - Decompilation of the RVL SDK (Nintendo's Wii operating system libraries), archived but a reference for the Wii's system-level formats.
* [Kaitai-Files](https://github.com/RiiConnect24/Kaitai-Files) ⭐ 19 | 🐛 0 | 🌐 Kaitai Struct | 📅 2024-02-03 - Kaitai Struct definitions documenting proprietary Wii file formats, including WiiConnect24 channel data (e.g. the Forecast Channel), compilable into parsers for any Kaitai-supported language.
* [wii-shop-channel](https://github.com/vabold/wii-shop-channel) ⭐ 13 | 🐛 5 | 🌐 C | 📅 2025-11-28 - Decompilation of the Wii Shop Channel, reading an existing WAD dump of the channel.
* [EGG](https://github.com/vabold/EGG) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-04-15 - Decompilation of Nintendo's EGG library, a Wii-era in-house engine used across multiple first-party Wii games.
* [cgrr-gamecube](https://github.com/sopoforic/cgrr-gamecube) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2015-06-13 - Tools for GameCube file formats.
* [Chihuahua](https://github.com/Sage-of-Mirrors/Chihuahua) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2018-10-18 - Tool for GameCube/Wii file formats.

##### Emulation, Audio, Video & Wii Channel Tools

* [Dolphin](https://github.com/dolphin-emu/dolphin) ⭐ 15,482 | 🐛 466 | 🌐 C++ | 📅 2026-09-04 - GameCube and Wii emulator that parses and implements support for GameCube/Wii disc and asset file formats.
* [noclip.website (Wii Banners)](https://github.com/magcius/noclip.website/tree/main/src/Common/NW4R/lyt) ⭐ 4,251 | 🐛 86 | 🌐 TypeScript | 📅 2026-08-26 - Renderer for NW4R LYT UI layouts, used to play back animated Wii channel banners from `banner.bin` archives. Parses BRLYT layouts, BRLAN animations, and NW4R bitmap fonts.
* [FunKii](https://github.com/AuroraWright/FunKii) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2019-08-10 - Command-line downloader for Wii content from the Nintendo CDN, packaging titles into installable WAD files (including DLC handling).
* [libansnd](https://github.com/Oaisus/libansnd) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2026-02-04 - Audio library for Wii and GameCube homebrew with support for ADPCM audio decoding and arbitrary resampling. Supports up to 48 simultaneous voices with hardware ADPCM decoding.
* [DTMEditor](https://github.com/lioncash/DTMEditor) ⚠️ Archived - GUI editor for Dolphin emulator DTM tool-assisted-speedrun movie files.
* [DTMText](https://github.com/heinermann/DTMText) ⚠️ Archived - Converts Dolphin emulator DTM tool-assisted-speedrun movie files to and from a human-editable text format, to support diffing/version-controlling TAS inputs (GameCube, single controller only).

#### Nintendo DS / DSi

* [Tinke](https://github.com/pleonex/tinke) ⚠️ Archived - Viewer, converter, and editor for Nintendo DS file formats (images, text, sounds, fonts, textures), extensible via .NET plugins. Deprecated by its author; see [TinkeDSi](https://github.com/R-YaTian/TinkeDSi) ⭐ 78 | 🐛 7 | 🌐 C# | 📅 2026-07-27 below for an actively maintained continuation with DSi support.
* [apicula](https://github.com/scurest/apicula) ⭐ 227 | 🐛 20 | 🌐 Rust | 📅 2025-01-21 - Converter for Nintendo DS .nsbmd 3D model format.
* [apicula/wiki/FILETYPES](https://github.com/scurest/apicula/wiki/FILETYPES) ⭐ 227 | 🐛 20 | 🌐 Rust | 📅 2025-01-21 - Documentation for Nintendo DS file types.
* [NTRGhidra](https://github.com/pedro-javierf/NTRGhidra) ⭐ 224 | 🐛 4 | 🌐 Java | 📅 2026-03-24 - Ghidra plugin for Nintendo DS.
* [TinkeDSi](https://github.com/R-YaTian/TinkeDSi) ⭐ 78 | 🐛 7 | 🌐 C# | 📅 2026-07-27 - Viewer and extractor for Nintendo DS/DSi file formats.
* [Flipnote-Encoder](https://github.com/RinLovesYou/Flipnote-Encoder) ⭐ 67 | 🐛 10 | 📅 2021-05-14 - Cross-platform Flipnote Studio (Nintendo DSi) encoder and signer, producing valid .ppm files.
* [sdatxtract](https://github.com/oreo639/sdatxtract) ⭐ 39 | 🐛 0 | 🌐 C | 📅 2021-02-06 - Command-line Nintendo DS Sound DATa (SDAT) extraction utility.
* [Ekona](https://github.com/SceneGate/Ekona) ⚠️ Archived - Nintendo DS file format library.
* [Hatenatools](https://github.com/pbsds/Hatenatools) ⚠️ Archived - Python tools for Flipnote Studio (Nintendo DSi) file formats. Supports reading and writing .ppm (Flipnote files), .tmb (thumbnail files), .ugo (user data), and .ntft (image files). Can extract metadata, frames, and audio from Flipnote files.
* [narchive](https://github.com/nickworonekin/narchive) ⭐ 23 | 🐛 1 | 🌐 C# | 📅 2019-04-28 - Tool for extracting and creating NARC archives used in DS games.
* [NitroSDK](https://github.com/ntrtwl/NitroSDK) ⭐ 15 | 🐛 1 | 🌐 C | 📅 2026-08-17 - Official Nintendo DS SDK.
* [nitro-fs](https://github.com/DanielPXL/nitro-fs) ⭐ 14 | 🐛 0 | 🌐 TypeScript | 📅 2024-03-14 - Nintendo DS filesystem tools.
* [nitro-g3d-tools](https://github.com/Ermelber/nitro-g3d-tools) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2020-08-17 - Tools for Nintendo DS 3D graphics.
* [NintendoNitro4DotNet](https://github.com/henke37/NintendoNitro4DotNet) ⭐ 12 | 🐛 0 | 🌐 C# | 📅 2022-11-20 - .NET libraries for working with file formats in Nintendo DS games.
* [Nds4j](https://github.com/turtleisaac/Nds4j) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2026-09-03 - Java library for Nintendo DS formats.
* [NitroModel ConverterGUI](https://github.com/TheGameratorT/NitroModel_ConverterGUI) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2019-11-23 - Converts between Nintendo DS Nitro model formats (NSBMD/NSBTX from ASS/IMD).
* [NDWCSHAP\_Generator](https://github.com/Lesserkuma/NDWCSHAP_Generator) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2024-01-17 - Generates a Nintendo DS Wi-Fi Connection-style (NDWCSHAP) wireless access point that any Nintendo DS, DSi, or 3DS will auto-connect to, for local wireless testing without official infrastructure.
* [nitroefx](https://github.com/Fexty12573/nitroefx) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2026-06-29 - Nintendo DS effect tools.
* [nitrogfx](https://github.com/red031000/nitrogfx) ⭐ 8 | 🐛 4 | 🌐 C | 📅 2026-08-07 - Nintendo DS graphics tools.
* [DSDLP\_Assembler](https://github.com/Lesserkuma/DSDLP_Assembler) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2026-06-26 - Assembles captured Wi-Fi packets, Nintendo Channel DLC files, and melonDS save states into DS Download Play binaries, complementing dlpdump above.
* [narc](https://github.com/lhearachel/narc) ⚠️ Archived - NARC archive tool for Nintendo DS.
* [nitrog3d](https://github.com/red031000/nitrog3d) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-11-12 - Nintendo DS 3D tools.
* [NitroSharp](https://github.com/PlatinumMaster/NitroSharp) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2023-05-31 - Nintendo DS file format library.
* [NitroSystem](https://github.com/ntrtwl/NitroSystem) ⭐ 2 | 🐛 1 | 🌐 C | 📅 2026-02-26 - Nintendo DS system library.
* [NitroEffectMaker](https://github.com/HaroohiePals/NitroEffectMaker) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2025-08-22 - Effect editor for Nintendo DS.
* [nitromods](https://github.com/TheGag96/nitromods) ⭐ 1 | 🐛 0 | 🌐 D | 📅 2025-06-08 - Project management tool for modding DS games: unpacks ROM filesystems, installs a custom overlay, compiles/assembles mod code (ASM, C, or D), and repacks everything into a new ROM. Supports Pokémon Diamond/Pearl/Platinum, HeartGold/SoulSilver, and Animal Crossing: Wild World.
* [dlpdump](https://github.com/Lesserkuma/dlpdump) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-06-28 - Nintendo DS homebrew project for preserving DS Download Play content in a verifiable way, dumping the Wi-Fi packets a DS Download Play host broadcasts.
* [DSlash](https://github.com/ElementW/dslash) ⭐ 0 | 🐛 1 | 🌐 C | 📅 2015-03-22 - Nintendo DS ROM viewing/extraction tool based on ndstrim (GitHub mirror of the original Google Code project).
* [Nitro Files](https://wiki.vg-resource.com/Nitro_Files) - Documentation for Nintendo DS file formats.
* [REGames Editor](https://www.reddit.com/r/REGames/comments/12o004k/a_friend_and_i_made_a_full_editor_for_a_nintendo/) - Full-featured editor for Nintendo DS games.

#### Nintendo 64

* [N64Recomp](https://github.com/N64Recomp/N64Recomp) ⭐ 8,112 | 🐛 57 | 🌐 C++ | 📅 2026-05-27 - Tool to statically recompile N64 games into native executables. Converts N64 binaries into C code that can be compiled for any platform.
* [sdk-tools (decomp)](https://github.com/n64decomp/sdk-tools) ⭐ 145 | 🐛 0 | 🌐 C | 📅 2021-07-07 - Decompilation of the Nintendo 64 SDK's developer tools, complementing ultralib above.
* [glankk/n64](https://github.com/glankk/n64) ⭐ 115 | 🐛 4 | 🌐 C | 📅 2026-06-16 - Collection of N64 development tools.
  * Tools: `gfxdis` (F3DEX2 display list disassembler/decompiler), `gru` (Lua environment for manipulating raw binaries, N64 ROMs, Zelda64 file systems, UPS patches, and GameShark codes), `grc` (resource compiler for linkable N64 texture objects), `ed64rdb`/`gs` (remote debugging and GameShark upload utilities).
* [UltraCIC](https://github.com/mikeryan/UltraCIC) ⭐ 103 | 🐛 1 | 🌐 Assembly | 📅 2018-08-19 - Reverse-engineered clone of the Nintendo 64 CIC lockout/authentication chip.
* [ido-static-recomp](https://github.com/decompals/ido-static-recomp) ⭐ 81 | 🐛 10 | 🌐 C++ | 📅 2025-07-05 - Static recompilation of the SGI IDO 5.3/7.1 C compilers for modern platforms, letting N64 decompilation projects rebuild with the original toolchain to verify byte-matching output.
* [ultralib](https://github.com/decompals/ultralib) ⭐ 67 | 🐛 11 | 🌐 C | 📅 2026-04-19 - Reverse engineering and matching decompilation of libultra (the N64 SDK), supporting multiple IDO/GCC compiler and library versions.
* [gzinject](https://github.com/krimtonz/gzinject) ⭐ 26 | 🐛 4 | 🌐 C | 📅 2024-03-13 - WAD editing utility primarily used for patching N64 Virtual Console emulators and replacing the embedded ROM, with a documented patch file format.
* [N64-IPL](https://github.com/decompals/N64-IPL) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2024-03-13 - Matching disassemblies of the N64 boot code (IPL1, IPL2, and IPL3).
* [n64soundtools](https://github.com/jsdf/n64soundtools) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2024-01-02 - Node.js reimplementation of the N64 SDK's SGI sound tools (sbc sequence bank compiler and related utilities) for building N64 homebrew audio data.
* [AudiobankToC](https://github.com/sauraen/AudiobankToC) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2022-01-03 - Scripts for converting between N64 Audiobank bank files and C code. Matches on binary -> C -> binary for banks in OoT.
* [ipl3checksum](https://github.com/Decompollaborate/ipl3checksum) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-01-17 - Python and Rust library to calculate the IPL3 (boot code) checksum for N64 ROMs, used to validate/patch ROMs in decompilation and recompilation workflows.
* [ultra64](https://github.com/marijnvdwerf/ultra64) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-02 - Detects libultra (N64 SDK) library function signatures embedded in N64 ROM binaries.
* [ido-rs](https://github.com/EllipticEllipsis/ido-rs) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2023-06-19 - Rust programs for handling SGI IDO compiler data formats (st, ucode, binasm), complementing ido-static-recomp above in N64 decompilation toolchains.
* [n64os-info](https://github.com/akopetsch/n64os-info) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-05-17 - Reverse-engineered and documented version history of the official Nintendo 64 OS (libultra, microcode, headers, release notes), based on SDK discs and leaks, complementing ultralib above.
* [seq64](https://github.com/gheskett/seq64) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2024-02-11 - Full-featured editor for Nintendo 64 music sequencing (Audioseq format). Supports Super Mario 64, Mario Kart 64, and The Legend of Zelda: Ocarina of Time.
* [n64-mr-backup-z64-python](https://github.com/gufranco/n64-mr-backup-z64-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Builds verified Mr. Backup Z64 Zip100 disk images from an N64 ROM collection: 8.3 naming, FAT16 layout, provably minimal disk count, and byte-reproducible output; ships no ROMs, only hashes to identify them.

#### SNES / NES

* [jamulator](https://github.com/andrewrk/jamulator) ⭐ 624 | 🐛 2 | 🌐 Go | 📅 2013-06-07 - Early static recompiler converting NES ROMs into native executables via LLVM (unmaintained, historically notable predecessor to upernes/nesrecomp).
* [bsnes-plus](https://github.com/devinacker/bsnes-plus) ⭐ 362 | 🐛 101 | 🌐 C++ | 📅 2025-03-22 - Debug-oriented fork of bsnes with a tracer, memory/VRAM viewers, and breakpoints, widely used for SNES ROM hacking and reverse engineering.
* [DiztinGUIsh](https://github.com/DizTools/DiztinGUIsh) ⭐ 338 | 🐛 54 | 🌐 C# | 📅 2026-08-09 - Super NES ROM disassembler with tracelog capture/analysis and a focus on collaborative workflow; exports .asm files that reassemble back into the original binary.
* [asar](https://github.com/RPGHacker/asar) ⭐ 255 | 🐛 94 | 🌐 C++ | 📅 2026-08-20 - SNES assembler for applying patches to existing ROM images or building new ones from scratch; the long-standing standard assembler used across SNES ROM hacking projects.
* [SuperFamiconv](https://github.com/Optiroc/SuperFamiconv) ⭐ 190 | 🐛 21 | 🌐 C++ | 📅 2026-09-04 - Command-line tool to convert graphics to Super Nintendo format.
* [nesrecomp](https://github.com/mstan/nesrecomp) ⭐ 93 | 🐛 1 | 🌐 C | 📅 2026-08-14 - Static recompiler ecosystem for NES games (part of the R.A.I.D. community), converting 6502 ROM code into portable native code, similar in approach to upernes and GB Recompiled above.
* [Dispel](https://github.com/pelrun/Dispel) ⭐ 84 | 🐛 3 | 🌐 C | 📅 2023-02-09 - Disassembler for 65816/SNES ROM images.
* [SatellaWave](https://github.com/LuigiBlood/sat_wave) ⭐ 73 | 🐛 9 | 🌐 C# | 📅 2025-04-11 - Satellaview (BS-X) server manager/tool exporting broadcast satellite data as BSX-\*.bin files playable in bsnes-plus and snes9x, covering channels including Derby Stallion 96.
* [snes-assembly-book](https://github.com/Ersanio/snes-assembly-book) ⭐ 46 | 🐛 0 | 📅 2026-09-03 - 65c816 assembly guide covering opcodes and the inner workings of the SNES, aimed at ROM hacking and reverse engineering.
* [upernes](https://github.com/mandraga/upernes) ⭐ 38 | 🐛 1 | 🌐 Assembly | 📅 2025-06-20 - NES to Super NES recompiler; disassembles NES ROMs and converts 6502 code to SNES 65C816 assembly with hardware emulation.
* [NES-Sprite-Editor](https://github.com/eonarheim/NES-Sprite-Editor) ⭐ 37 | 🐛 0 | 🌐 JavaScript | 📅 2024-01-03 - Simple sprite editor for NES games.
* [M1TE2](https://github.com/nesdoug/M1TE2) ⭐ 31 | 🐛 4 | 🌐 C# | 📅 2025-11-24 - SNES Mode 1 Tile Editor for generating, editing, and arranging SNES tiles and tilemaps (2bpp/4bpp) with palette support. Designed for Mode 1 but works with any mode needing 2bpp or 4bpp graphics.
* [go-nes](https://github.com/zorchenhimer/go-nes) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2024-05-16 - Go library and CLI utilities for NES ROM and CHR data: unpacking/repacking iNES ROMs into PRG/CHR banks, converting between CHR tiles and PNG/bitmap, metatile and font conversion, and ROM usage-map visualization.
* [BSFlashManager](https://github.com/devinacker/BSFlashManager) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2020-02-23 - Tool for managing BS-X / Satellaview memory pack flash cartridges for the SNES, reading and writing the Satellaview's flash memory format.
* [noiSNESs\_Brr\_Finder](https://github.com/noisecross/noiSNESs_Brr_Finder) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2018-10-19 - Statistically analyzes SPC dumps and SNES ROM images to rip embedded BRR (Bit Rate Reduction) sound sample data, exporting to WAV or raw BRR; builds on techniques from SNESSOR and BRRTools while filtering out false-positive matches.
* [snes-tile-tool](https://github.com/fo-fo/snes-tile-tool) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2016-07-26 - SNES tile graphics conversion tool.
* [nintendulatordx](https://github.com/fo-fo/nintendulatordx) ⭐ 6 | 🐛 1 | 🌐 C | 📅 2015-07-12 - Modified version of the Nintendulator NES emulator adding source-level debugging capabilities for NES ROM reverse engineering.
* [snesify](https://github.com/furrykef/snesify) ⭐ 6 | 🐛 0 | 🌐 Assembly | 📅 2022-12-19 - Converts images into SNES-native tile graphics formats (2bpp/4bpp/8bpp), including a custom "scan16" 16-colors-per-scanline format that transfers to VRAM in half the time and space of 8bpp while looking better than 4bpp; used to make the large animations in the SNES port of Five Nights at Freddy's possible.
* [nes-header-info](https://github.com/infval/nes-header-info) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2022-02-24 - Tool for parsing and displaying iNES/NES 2.0 header information from NES ROM files.
* [snes-sdd1-python](https://github.com/gufranco/snes-sdd1-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Python reimplementation of the SNES S-DD1 compression coprocessor (used by Star Ocean and Street Fighter Alpha 2), checked against the snes9x reference decoder across 4,000 golden test vectors.
  * Same author also publishes patchers that rebuild [Street Fighter Alpha 2/Zero 2](https://github.com/gufranco/street-fighter-alpha-2-nochip) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-09-02 and [two Star Ocean rebuilds](https://github.com/gufranco/star-ocean-nochip-fix) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-09-02 as plain ROMs with the S-DD1 requirement designed out of the header, built from your own cartridge dump.
* [snes-driver-python](https://github.com/gufranco/snes-driver-python) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-09-02 - Recovers the command protocol a SNES cartridge uses to talk to its coprocessor, read directly out of the cartridge's own driver code; checked against 42 real cartridges.
* [snes-st-python](https://github.com/gufranco/snes-st-python) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-09-02 - Emulator for the Seta ST010/ST011 navigation coprocessors used in SNES racing cartridges, settled against their own reference implementation.
* [snes-rtc-python](https://github.com/gufranco/snes-rtc-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Emulator for the two real-time-clock coprocessors used in SNES cartridges (S-RTC), held to the chips' own reference implementations.
* [snes-obc1-python](https://github.com/gufranco/snes-obc1-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Emulator for the OBC1 sprite-remapper coprocessor carried by one SNES cartridge, validated byte-for-byte against its own reference across every addressing state.
* [snes-dsp-python](https://github.com/gufranco/snes-dsp-python) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-09-02 - Emulator for the SNES DSP-1/2/3/4 coprocessor family (built on the [nec-upd7725-96050-python](https://github.com/gufranco/nec-upd7725-96050-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 core), running the microcode dump you supply rather than a from-scratch reimplementation of it.
* [sony-s-dsp-python](https://github.com/gufranco/sony-s-dsp-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Sony S-DSP audio-unit model for the SNES sound engine, cross-checked sample-for-sample against register configurations taken from real SPC music dumps.
* [sony-spc700-python](https://github.com/gufranco/sony-spc700-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Cycle-accurate SPC700 CPU interpreter for the SNES's audio processor (all 256 opcodes), validated against the SingleStepTests conformance corpus.
* [snes-spc7110-python](https://github.com/gufranco/snes-spc7110-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Python reimplementation of the SNES SPC7110 decompression coprocessor (all three of its modes), checked against the chip's own reference implementation over 102,400 bytes of generated streams.
* [snes-graphics-python](https://github.com/gufranco/snes-graphics-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - Encoder/decoder for the Super Nintendo's tile, tilemap, and palette graphics formats, validated bit-exact against the hardware's own behavior.
* [snes-mapper-python](https://github.com/gufranco/snes-mapper-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-02 - SNES cartridge memory map and DMA engine in Python, resolving every header-declared layout to its address-space mapping; checked against 5,145 real cartridges.
* [snes-rom-image-python](https://github.com/gufranco/snes-rom-image-python) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-09-02 - Python library treating a SNES cartridge dump as a file rather than an address space: strips copier stubs, joins split ROM sets, identifies a dump by digest, and rewrites the header to drop a declared coprocessor with the checksum recomputed across every mirror; validated against 7,317 real cartridges.

#### Game Boy / GBA

##### ROM Tools, Disassemblers & Format Libraries

* [HexManiacAdvance](https://github.com/haven1433/HexManiacAdvance) ⭐ 472 | 🐛 16 | 🌐 C# | 📅 2026-08-30 - Hex editor for Game Boy Advance ROMs with scripting support.
* [GB Recompiled](https://github.com/arcanite24/gb-recompiled) ⭐ 428 | 🐛 6 | 🌐 Python | 📅 2026-08-05 - Static recompiler for Game Boy and Game Boy Color ROMs that translates LR35902 assembly directly to portable C code.
* [mgbdis](https://github.com/mattcurrie/mgbdis) ⭐ 324 | 🐛 14 | 🌐 Assembly | 📅 2026-07-31 - Game Boy ROM disassembler with RGBDS-compatible output.
* [GhidraGBA](https://github.com/SiD3W4y/GhidraGBA) ⭐ 128 | 🐛 2 | 🌐 Java | 📅 2021-12-13 - Game Boy Advance ROM loader for Ghidra.
* [gba\_explorer](https://github.com/attilathedud/gba_explorer) ⭐ 100 | 🐛 2 | 🌐 Vue | 📅 2018-12-12 - Explorer for Game Boy Advance ROMs, browsing and extracting embedded text, graphics, and sound data.
* [windfish](https://github.com/jverkoey/windfish) ⭐ 84 | 🐛 43 | 🌐 Assembly | 📅 2021-02-14 - Tracing disassembler and UI for Game Boy ROMs, integrated with SameBoy for emulation and debugging.
* [gba-ghidra-loader](https://github.com/pudii/gba-ghidra-loader) ⭐ 83 | 🐛 0 | 🌐 Java | 📅 2026-02-09 - Game Boy Advance ROM loader for Ghidra, targeting modern Ghidra versions.
* [gbadisasm](https://github.com/camthesaxman/gbadisasm) ⭐ 71 | 🐛 0 | 🌐 C | 📅 2022-02-14 - Game Boy Advance ROM disassembler.
* [gvasm](https://github.com/velipso/gvasm) ⭐ 70 | 🐛 10 | 🌐 TypeScript | 📅 2024-12-07 - Assembler and disassembler designed specifically for Game Boy Advance homebrew.
* [luvdis](https://github.com/aarant/luvdis) ⭐ 53 | 🐛 5 | 🌐 Python | 📅 2021-06-29 - Pure-Python Game Boy Advance disassembler.
* [gameboy-rom-parser](https://github.com/MarkMcCaskey/gameboy-rom-parser) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2023-07-06 - Rust parser for (Super) Game Boy (Color) ROM headers.
* [UnkrawerterGBA](https://github.com/MCJack123/UnkrawerterGBA) ⭐ 36 | 🐛 3 | 🌐 C++ | 📅 2022-03-05 - Game Boy Advance ROM extractor and converter for games using the Krawall sound engine. Exports audio as XM or S3M module files. Supports automatic detection of instrument/sample lists and modules, direct rip mode for lossless extraction, and can be used as a library.
  * See also [krawall](https://github.com/sebknzl/krawall) ⭐ 69 | 🐛 2 | 🌐 C | 📅 2014-10-01, the original XM/S3M player engine source used by these games.
* [super-game-boy-border-injector](https://github.com/marcrobledo/super-game-boy-border-injector) ⭐ 36 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-02 - Injects a custom Super Game Boy border into (almost) any Game Boy ROM, complementing the border-converter above.
* [ezgba](https://github.com/langest/ezgba) ⭐ 36 | 🐛 2 | 🌐 C++ | 📅 2023-12-28 - Applies SRAM, IPS, and EZ4 patches to Game Boy Advance ROMs.
* [Tilemap-Creator](https://github.com/erandis-vol/Tilemap-Creator) ⭐ 31 | 🐛 3 | 🌐 C# | 📅 2021-12-14 - Tileset and tilemap editor for the Game Boy Advance.
* [gba-tileeditor](https://github.com/IanFinlayson/gba-tileeditor) ⭐ 30 | 🐛 0 | 🌐 C | 📅 2024-07-17 - Simple tile editor for the Game Boy Advance.
* [ida\_gba\_stuff](https://github.com/laqieer/ida_gba_stuff) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-06-07 - IDA Pro scripts and loaders useful when reverse engineering GBA games.
* [bnGB](https://github.com/icecr4ck/bnGB) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2020-11-17 - Binary Ninja loader and architecture plugin for Game Boy ROMs, enabling GB/GBC disassembly and analysis directly within Binary Ninja.
* [gba-recomp](https://github.com/JRickey/gba-recomp) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-06-18 - Static recompilation tool and runtime for Game Boy Advance ROMs.
* [gba\_dumper](https://github.com/attilathedud/gba_dumper) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2017-08-23 - Set of utilities for text modifications in GBA ROMs. Since GBA games use homebrew text encodings rather than ASCII, streamlines building a translation table from search matches, dumping translated ROM text, and re-injecting edited strings.
* [gba-lz77](https://github.com/lunasorcery/gba-lz77) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2019-12-09 - LZ77 compressor/decompressor producing byte-identical output to the GBA's LZ77 implementation, verified against LEGO Island 2 (GBA).
* [super-game-boy-border-converter](https://github.com/marcrobledo/super-game-boy-border-converter) ⭐ 14 | 🐛 2 | 🌐 JavaScript | 📅 2026-07-03 - Converts a 256x224 PNG image into Super Game Boy border SNES tile data.
* [GBA-IDA-Pseudo-Terminal](https://github.com/LanHikari22/GBA-IDA-Pseudo-Terminal) ⭐ 12 | 🐛 13 | 🌐 Python | 📅 2019-12-31 - IDAPython tools aiding analysis, disassembly, and data extraction, tailored for the GBA architecture.
* [gba\_lib\_func\_sig](https://github.com/laqieer/gba_lib_func_sig) ⭐ 9 | 🐛 0 | 🌐 Max | 📅 2019-02-09 - Game Boy Advance library function signature database for reverse engineering, used to identify known compiler/SDK library functions embedded in GBA ROMs.
* [gba-disasm-decomp-tools](https://github.com/laqieer/gba-disasm-decomp-tools) ⭐ 9 | 🐛 0 | 🌐 Dockerfile | 📅 2026-06-10 - Bootstraps a disassembly or decompilation project for a Game Boy Advance game, scaffolding the toolchain and directory structure.
* [gba-reversing-notes](https://github.com/Dhole/gba-reversing-notes) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2019-04-09 - Notes on reverse engineering GBA ROMs.
* [cgrr-gameboy](https://github.com/sopoforic/cgrr-gameboy) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2015-06-05 - Tools for Game Boy file formats.
* [gfx2agb](https://github.com/felixjones/gfx2agb) ⭐ 7 | 🐛 2 | 🌐 C++ | 📅 2026-05-29 - Graphics converter for the Game Boy Advance, converting images to Mode 3/4/5 bitmap and palette data with configurable gamma, dithering, and output stride direction.
* [gba\_opening\_movie](https://github.com/laqieer/gba_opening_movie) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-09-29 - Guide and reference implementation for inserting a custom AVI-converted opening movie into a Fire Emblem GBA ROM.
* [Un-GameBoy](https://github.com/xvillaneau/python-ungameboy) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2020-11-02 - Interactive terminal-based tool for reverse-engineering Game Boy and Game Boy Color ROMs, with disassembly, labeling, and navigation features.
* [gba-mapper](https://github.com/JRickey/gba-mapper) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-06-13 - LLM-driven automated disassembly and mapping toolkit for GBA ROM images.
* [SLaDe-AGBCC](https://github.com/JRickey/SLaDe-AGBCC) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-06-12 - Neural GBA decompiler experiment targeting AGBCC-compiled code.
* [GBRE](https://github.com/native-gb/gbre) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-21 - Research and interoperability toolkit for analyzing user-supplied Game Boy ROMs and building native reimplementations, providing ROM-range data modeling, source-map generation, HTML coverage maps, and emulator-trace/evidence tooling.

##### Hardware & Die-Level Reverse Engineering

* [metroboy](https://github.com/aappleby/metroboy) ⭐ 1,170 | 🐛 4 | 🌐 C++ | 📅 2025-02-23 - Repository of gate-level simulators and reverse-engineering tools for the original Game Boy hardware.
* [gbrom-tutorial](https://github.com/travisgoodspeed/gbrom-tutorial) ⭐ 1,165 | 🐛 0 | 📅 2026-08-17 - Tutorial for extracting the Game Boy boot ROM from die photographs.
* [FlashGBX](https://github.com/Lesserkuma/FlashGBX) ⭐ 860 | 🐛 37 | 🌐 Python | 📅 2026-08-29 - Cross-platform (Windows/Linux/macOS) tool to read and write Game Boy and Game Boy Advance cartridge ROM and save data, including RTC registers, via GBxCart RW, GBFlash, Joey Jr, and Game Bub hardware.
  * Features: Wide support for cartridge memory mappers and reproduction/flash cartridges, flash chip identification, decoding and extraction of Game Boy Camera photos from save data, and ROM dump report generation for game preservation.
* [gb-schematics](https://github.com/Gekkio/gb-schematics) ⭐ 698 | 🐛 0 | 📅 2024-05-18 - Reverse engineered Game Boy-related hardware schematics.
* [maskromtool](https://github.com/travisgoodspeed/maskromtool) ⭐ 395 | 🐛 30 | 🌐 C++ | 📅 2026-08-14 - CAD tool for extracting bits from mask ROM die photographs, used to recover boot ROM and other on-die data.
* [ems-qart](https://github.com/rbino/ems-qart) ⭐ 203 | 🐛 16 | 🌐 C++ | 📅 2024-06-03 - Cross-platform Qt application to read and write ROM and SRAM save data on EMS 64M USB Game Boy flash cartridges. See also [ems-flasher](https://github.com/mikeryan/ems-flasher) ⭐ 98 | 🐛 5 | 🌐 C | 📅 2017-12-13, the original command-line flasher for the same hardware.
* [gba-auto-batteryless-patcher](https://github.com/metroid-maniac/gba-auto-batteryless-patcher) ⭐ 130 | 🐛 12 | 🌐 C | 📅 2023-05-31 - Patches a GBA ROM for batteryless saving on bootleg cartridges containing SRAM but no battery, flushing save data a few seconds after an in-game save or on a button-trigger.
* [GBA\_MultiMenu](https://github.com/Lesserkuma/GBA_MultiMenu) ⭐ 113 | 🐛 4 | 🌐 C | 📅 2026-07-06 - Menu program and ROM-compilation builder for Game Boy Advance bootleg cartridges equipped with a multi-game mapper, supporting several common mapper chips and per-game save slot configuration. Compatible with cartridges dumped/flashed via FlashGBX above.
* [gameboy-audio-dumper](https://github.com/FIX94/gameboy-audio-dumper) ⭐ 68 | 🐛 3 | 🌐 C | 📅 2022-08-02 - Dumps Game Boy ROMs and save files over an analog audio connection.
* [dmg-schematics](https://github.com/msinger/dmg-schematics) ⭐ 48 | 🐛 2 | 🌐 KiCad Schematic | 📅 2026-08-21 - Reverse engineered schematics of the Game Boy's DMG-CPU B chip, including the SM83 CPU core. Successor to the archived DMG-CPU-Inside project.
* [gba-cartridge](https://github.com/jojolebarjos/gba-cartridge) ⭐ 36 | 🐛 0 | 🌐 Makefile | 📅 2022-05-10 - Experiments documenting how Game Boy Advance cartridges work.
* [libsavgba](https://github.com/laqieer/libsavgba) ⭐ 32 | 🐛 1 | 🌐 Makefile | 📅 2024-12-24 - Library to access various backup media (SRAM, flash, EEPROM) in GBA cartridges. Successor to the archived [libgbabackup](https://github.com/laqieer/libgbabackup) ⚠️ Archived.
* [ags\_aging (decomp)](https://github.com/Normmatt/ags_aging) ⭐ 14 | 🐛 1 | 🌐 C | 📅 2020-03-06 - Decompilation of the AGS Aging Cartridge 7.0, a Nintendo diagnostic/burn-in test cartridge for Game Boy Advance hardware.
  * See also [AGSTests](https://github.com/DenSinH/AGSTests) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2021-02-11, a (semi-)decompilation consolidating the AGS test programs in one central place.
* [nds-slot2](https://github.com/IvanVeloz/nds-slot2) ⭐ 10 | 🐛 0 | 📅 2026-05-07 - Nintendo DS slot-2 (GBA slot) reverse engineering documentation.
* [gba-cartridge (repro RE)](https://github.com/tolik518/gba-cartridge) ⭐ 8 | 🐛 0 | 📅 2024-01-21 - Reverse engineering attempt of a Chinese repro Game Boy Advance cartridge.
* [ninmonitorroms](https://github.com/0xabad1dea/ninmonitorroms) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2020-07-25 - Recovered Game Boy debug monitor ROMs, partial ROM images pulled from an official Nintendo Game Boy emulator.

##### Game Boy Camera & Printer

* [arduino-gameboy-printer-emulator](https://github.com/mofosyne/arduino-gameboy-printer-emulator) ⭐ 366 | 🐛 3 | 🌐 C++ | 📅 2026-05-13 - Arduino-based Game Boy Printer emulator that captures the raw serial protocol between a Game Boy/GBC/GBA and the printer, decoding print jobs into images. See also [GameboyPrinterSniffer](https://github.com/mofosyne/GameboyPrinterSniffer) ⭐ 9 | 🐛 0 | 🌐 C++ | 📅 2022-06-21, a standalone packet sniffer for the same protocol.
* [NeoGB-Printer](https://github.com/zenaror/NeoGB-Printer) ⭐ 167 | 🐛 1 | 🌐 C | 📅 2024-08-23 - Open-source, standalone ESP32-based Game Boy Printer emulator 100% compatible with all 110 officially released compatible games, saving printed images as BMP. Co-developed with the author of arduino-gameboy-printer-emulator above.
* [The TinyGB Printer](https://github.com/Raphael-Boichot/The-TinyGB-Printer) ⭐ 101 | 🐛 0 | 🌐 C | 📅 2026-08-19 - Raspberry Pi Pico-based Game Boy Printer emulator storing decoded print jobs directly as PNG images on an SD card, battery powered for portability.
  * See also the same author's earlier [GameboyPrinterPaperSimulation](https://github.com/Raphael-Boichot/GameboyPrinterPaperSimulation) ⭐ 83 | 🐛 0 | 🌐 C++ | 📅 2026-09-01 (simulates physical/e-paper printout look from the decoded data) and [PC-to-Game-Boy-Printer-interface](https://github.com/Raphael-Boichot/PC-to-Game-Boy-Printer-interface) ⭐ 14 | 🐛 0 | 🌐 MATLAB | 📅 2025-06-04 (bridges a PC to a real Game Boy Printer, encoding images into Game Boy tile format), both since folded into this project.
  * Built on mofosyne's arduino-gameboy-printer-emulator protocol parser above; described by its author as a Pico "demake" of NeoGB-Printer above.
* [gbcam-rev-engineer](https://github.com/AntonioND/gbcam-rev-engineer) ⚠️ Archived - Tools used to reverse engineer the Game Boy Camera's sensor and communication protocol using an Arduino UNO.
* [wifi-gbp-emulator](https://github.com/HerrZatacke/wifi-gbp-emulator) ⭐ 78 | 🐛 1 | 🌐 C++ | 📅 2026-04-10 - ESP8266-based Game Boy Printer emulator that exposes received print job data over a WiFi connection instead of local storage.
* [gb-printer-web](https://github.com/HerrZatacke/gb-printer-web) ⭐ 76 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-02 - Web app for organizing, editing, and sharing Game Boy Camera photos.
* [gbpxl](https://github.com/xx0x/gbpxl) ⭐ 61 | 🐛 2 | 🌐 C | 📅 2022-09-08 - Game Boy Printer XL: transparent interface bridging the Game Boy Camera/Printer protocol to ESC/POS-compatible thermal receipt printers. See also [cristofercruz's fork](https://github.com/cristofercruz/gbpxl) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2024-03-05 with multi-tone printing support.
* [gbcamextract](https://github.com/jkbenaim/gbcamextract) ⭐ 53 | 🐛 0 | 🌐 C | 📅 2022-05-08 - Extracts photos from Game Boy Camera / Pocket Camera save files, including the Hello Kitty camera variant.
* [GBCamera-Android-Manager](https://github.com/Mraulio/GBCamera-Android-Manager) ⭐ 42 | 🐛 1 | 🌐 Java | 📅 2026-04-30 - Android app to manage a Game Boy Camera photo gallery, communicating over USB serial with an Arduino Printer Emulator or GBxCart RW to pull images.
* [game-boy-camera-manager](https://github.com/marcrobledo/game-boy-camera-manager) ⭐ 24 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-25 - Tool for managing Game Boy Camera data, including both save (SRAM) photos and ROM contents.
* [gb-link-printer](https://github.com/stacksmashing/gb-link-printer) ⭐ 23 | 🐛 3 | 🌐 C | 📅 2022-01-20 - Firmware turning a GB-Link-Adapter into a Game Boy Printer emulator, allowing photos to be downloaded straight from the browser.
* [gbpinter\_dump2image\_py](https://github.com/lennartba/gbpinter_dump2image_py) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2020-05-20 - Python script batch-converting raw Game Boy Camera image dumps into PNG files.
* [GameBEye](https://github.com/mtouzot/GameBEye) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-07-28 - Python library for processing Game Boy Camera images.
* [gameboycameralib](https://github.com/KodeMunkie/gameboycameralib) ⭐ 6 | 🐛 1 | 🌐 Java | 📅 2024-10-04 - Java library encoding, decoding, injecting, and extracting Game Boy Camera 2BPP images as PNGs or BufferedImages to/from Game Boy Camera save files.
* [gbp-decode](https://github.com/HerrZatacke/gbp-decode) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2024-05-16 - Set of functions to decode Game Boy Printer print job data.

##### Mobile Adapter GB

* [libmobile](https://github.com/REONTeam/libmobile) ⭐ 43 | 🐛 7 | 🌐 C | 📅 2026-03-17 - Reimplementation of the Mobile Adapter GB protocol used by Pokémon Crystal, Mario Golf, Mario Tennis, and other Game Boy/GBC games for early-2000s online connectivity, enabling connections to custom replacement game servers. See also [ArduinoAdapterGB](https://github.com/REONTeam/ArduinoAdapterGB) ⚠️ Archived for a real-hardware emulation of the same physical adapter.

#### Cross-Platform Formats & Archives

##### Archive & Container Formats

* [ninfs](https://github.com/ihaveamac/ninfs) ⭐ 536 | 🐛 29 | 🌐 Python | 📅 2026-09-05 - FUSE filesystem tool to mount Nintendo 3DS and Switch container/filesystem formats (CCI, CDN, CIA, NAND, NCA, RomFS, SD, etc.) for direct file browsing.
* [Nintendo-File-Formats](https://github.com/kinnay/Nintendo-File-Formats) ⭐ 108 | 🐛 2 | 🌐 Markdown | 📅 2026-08-12 - Documentation for Wii U and Switch file formats.
* [3DSkit](https://github.com/Tyulis/3DSkit) ⭐ 79 | 🐛 11 | 🌐 Python | 📅 2024-08-25 - Tool to extract and repack many file formats found on Nintendo DS, DSi, 3DS, Wii U, and Switch.
* [oead](https://github.com/zeldamods/oead) ⭐ 47 | 🐛 10 | 🌐 C++ | 📅 2026-08-01 - Library for recent Nintendo EAD first-party formats (BOTW/TOTK-era SARC, Yaz0, AAMP, BYML, and more), with Rust core and Python bindings. See also [cs-oead](https://github.com/EPD-Libraries/cs-oead) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2026-08-04 for a C# wrapper.
* [GARCTool](https://github.com/kwsch/GARCTool) ⭐ 23 | 🐛 1 | 🌐 C# | 📅 2022-02-24 - Nintendo 3DS GARC (un)packing tool with support for repacking compressed files, complementing GARC-Unpack above.
* [darctool](https://github.com/dnasdw/darctool) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2022-10-02 - Tool for extracting and creating DARC archive files used in Nintendo games.
* [sarc](https://github.com/jam1garner/sarc) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2022-12-22 - Rust library for reading and writing Nintendo SARC and SZS (yaz0 compressed SARC) archive formats.
* [sarctool](https://github.com/jam1garner/sarctool) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2022-12-22 - Command-line tool for working with Nintendo SARC archive files.
* [Jungle](https://github.com/kinnay/Jungle) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - Accurate parser/encoder for various Nintendo file formats.
* [GARC-Unpack](https://github.com/vgmoose/GARC-Unpack) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2016-10-20 - Unpacker for Nintendo GARC archive format.
* [Lzarc-Tool](https://github.com/Fuzzy2319/Lzarc-Tool) ⭐ 4 | 🐛 2 | 🌐 C# | 📅 2026-04-02 - Tool for LZARC compressed archive format.
* [rust\_lzss](https://github.com/silentdragonz/rust_lzss) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2018-05-13 - Rust library implementing Nintendo's LZSS decompression, used across many Nintendo game formats.
* [lzarc](https://github.com/jam1garner/lzarc) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2021-05-03 - Rust library and CLI for working with LZARC compressed archives used in Paper Mario Color Splash.
* [SarcLibrary](https://github.com/EPD-Libraries/SarcLibrary) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2026-08-18 - Modern C# reader/writer for Nintendo SEAD/SEPD SARC archives.
* [sarc-extract](https://github.com/RenolY2/sarc-extract) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2015-07-31 - Extractor for SARC archive format.
* [zbic](https://github.com/kinnay/zbic) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-08-13 - Python package implementing the ZBIC compression algorithm used on Nintendo Switch.
* [Nintendo-File-Samples](https://github.com/kinnay/Nintendo-File-Samples) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-16 - Test set of Nintendo file format samples covering various edge cases, for validating tools against.

##### Text, Message & Localization (MSBT/LMS)

* [MSBTConverter](https://github.com/KillzXGaming/MSBTConverter) ⭐ 11 | 🐛 2 | 🌐 C# | 📅 2024-09-27 - Tool to convert Nintendo MSBT text files to YAML and back.
* [MessageStudio](https://github.com/EPD-Libraries/MessageStudio) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2026-01-10 - Modern C# implementation of Nintendo MessageStudio (LMS) text file formats.
* [msbt2sheets](https://github.com/CaXaPeK/msbt2sheets) ⭐ 5 | 🐛 1 | 🌐 C# | 📅 2025-06-06 - Converter for MSBT files to spreadsheet format.
* [CLMS](https://github.com/Trippixyz/CLMS) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2024-08-19 - C# library for Nintendo LMS (Message Studio) text format files (MSBT, MSBP, MSBF).
* [umsbt\_cmd\_extractor](https://github.com/efimandreev0/umsbt_cmd_extractor) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-01-05 - Command extractor for UMSBT files.
* [PyMsyt](https://github.com/NiceneNerd/PyMsyt) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2021-05-07 - Python library wrapping MSYT for editing Nintendo MSBT text files, used across Breath of the Wild and other Nintendo games.
* [MSBTEditor](https://github.com/efimandreev0/MSBTEditor) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2025-04-12 - MSBT text extractor/replacer for .msbt and .umsbt LE-files.

##### Models, Textures, Fonts & Rendering

* [BFRES-Viewer](https://github.com/KillzXGaming/BFRES-Viewer) ⭐ 52 | 🐛 1 | 🌐 C# | 📅 2018-05-07 - Viewer for Nintendo BFRES model format files.
* [NintyFont](https://github.com/hadashisora/NintyFont) ⭐ 49 | 🐛 6 | 🌐 C++ | 📅 2023-06-23 - Nintendo binary font editor
* [BFRES-Tool](https://github.com/aboood40091/BFRES-Tool) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2018-12-18 - Tool for working with Nintendo BFRES files.
* [3dsfont](https://github.com/dnasdw/3dsfont) ⭐ 36 | 🐛 0 | 🌐 C++ | 📅 2019-07-08 - Toolkit for Nintendo BCFNT and BFFNT font files (3DS, Wii U, Switch).
* [BFRES-Extractor](https://github.com/LordNed/BFRES-Extractor) ⭐ 33 | 🐛 1 | 🌐 C++ | 📅 2022-03-03 - Extractor for Nintendo BFRES format files.
* [SSBHLib](https://github.com/Ploaj/SSBHLib) ⭐ 29 | 🐛 31 | 🌐 C# | 📅 2022-12-08 - Library for reading and writing Nintendo SSBH rendering format files (used by Super Smash Bros. Ultimate and other Switch games).
* [nutexb](https://github.com/jam1garner/nutexb) ⭐ 15 | 🐛 2 | 🌐 Rust | 📅 2026-07-04 - Rust library for working with Namco Nutexb textures, found in Smash Ultimate and other Switch games.
* [KCollisionLibrary](https://github.com/KillzXGaming/KCollisionLibrary) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2022-05-14 - Library for reading and editing Nintendo KCL collision file binaries used by various games.
* [BFRES-Shader-Maker](https://github.com/KillzXGaming/BFRES-Shader-Maker) ⭐ 11 | 🐛 2 | 🌐 C# | 📅 2026-08-30 - Tool for building BFSHA/BNSH shader binaries from scratch using a given BFRES and GLSL code.
* [ssbh\_lib](https://github.com/ultimate-research/ssbh_lib) ⭐ 11 | 🐛 28 | 🌐 Rust | 📅 2026-09-04 - Rust library for reading and writing Nintendo SSBH rendering format files (used by Super Smash Bros. Ultimate and other Switch games).
* [IONET](https://github.com/Ploaj/IONET) ⭐ 7 | 🐛 1 | 🌐 C# | 📅 2022-08-11 - .NET library for reading and writing several 3D model formats into a common object model.
* [img2nutexb](https://github.com/jam1garner/img2nutexb) ⭐ 6 | 🐛 1 | 🌐 Rust | 📅 2021-05-29 - Converts standard images (PNG, JPG, GIF, DDS, TGA, TIFF, ICO, BMP) to Nutexb, the Namco texture format used in Smash Ultimate and other Switch games.
* [BFRES-Model-Importer](https://github.com/KillzXGaming/BFRES-Model-Importer) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2018-05-18 - Script for injecting and replacing models in Nintendo BFRES files (Switch and Wii U), maintaining and extending smb123w64gb's original work.
* [TSCBReader](https://github.com/Sage-of-Mirrors/TSCBReader) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2017-03-28 - Reader for TSCB format files.
* [bntx](https://github.com/jam1garner/bntx) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-01-04 - Rust library for working with Nintendo BNTX textures.
* [NintenTools.Bfres (smb123w64gb)](https://github.com/smb123w64gb/NintenTools.Bfres) ⭐ 3 | 🐛 0 | 🌐 C# | 📅 2017-07-05 - .NET library for reading, writing, and modifying the Nintendo BFRES graphics archive format (Wii U); the original work later extended by KillzXGaming's BFRES-Model-Importer above.
* [img2bntx](https://github.com/jam1garner/img2bntx) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-06-20 - Converts standard images to Nintendo BNTX texture format.
* [BFRES-to-FBX-Converter](https://github.com/jdperos/BFRES-to-FBX-Converter) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2021-01-10 - Windows tool to convert Nintendo BFRES model files to FBX, built on the FBX SDK.
* [BntxLibrary](https://github.com/EPD-Libraries/BntxLibrary) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2025-08-01 - Simple C# IO library for the Nintendo BNTX texture format.
* [BfresToCast](https://github.com/CosmicDreamsOfCode/BfresToCast) ⭐ 0 | 🐛 2 | 🌐 C# | 📅 2026-01-22 - Console tool to extract models and textures from Nintendo BFRES container files to the Cast format.
* [Syroot.NintenTools.Bfres](https://gitlab.com/Syroot/NintenTools) - Library for reading/writing Nintendo BFRES model format (Wii U).

##### Scripting, Parameters & Game Data

* [msclang](https://github.com/jam1garner/msclang) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2020-05-10 - Custom C-to-MSC-bytecode compiler; MSC is the bytecode format used by Super Smash Bros. for Wii U for character logic.
* [mscdec](https://github.com/jam1garner/mscdec) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2020-11-06 - Decompiler that converts MSC bytecode (Super Smash Bros. for Wii U) back to C.
* [BymlLibrary](https://github.com/EPD-Libraries/BymlLibrary) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2024-06-28 - Modern C# library for reading/writing Nintendo BYML (Binary YAML) files, versions 2-7, including Tears of the Kingdom's v7 nodes.
* [pymsc](https://github.com/jam1garner/pymsc) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2020-08-14 - Python library for MSC format files.
* [aamp2xml](https://github.com/jam1garner/aamp2xml) ⭐ 6 | 🐛 0 | 🌐 C# | 📅 2017-05-14 - Converter for Nintendo AAMP parameter archive files (used across Breath of the Wild and other Nintendo EAD games) to/from XML.
* [KMP-Expander](https://github.com/Ermelber/KMP-Expander) ⭐ 3 | 🐛 2 | 🌐 C# | 📅 2022-03-09 - Expander for KMP format files.
* [asb](https://github.com/EPD-Libraries/asb) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2023-06-06 - Base library for parsing and recompiling Nintendo ASB (Animation State Binary) and AINB files.
* [RstbLibrary](https://github.com/EPD-Libraries/RstbLibrary) ⭐ 2 | 🐛 0 | 🌐 C# | 📅 2024-04-06 - C# IO library for Nintendo Resource Size Table (RSTB/RESTBL) files.
* [msc-debugger](https://github.com/jam1garner/msc-debugger) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2018-03-13 - Debugger for MSC bytecode files, the scripting format used in Super Smash Bros. for Wii U character logic.
* [AampLibrary](https://github.com/KillzXGaming/AampLibrary) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-07-23 - Library for editing v1 and v2 Nintendo AAMP parameter archive files.
* [AinbLibrary](https://github.com/EPD-Libraries/AinbLibrary) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2024-10-25 - C# library for Nintendo AINB (AI Node Binary) files.
* [txtg](https://github.com/EPD-Libraries/txtg) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2023-05-15 - Experimental parser for the Nintendo TexToGo (TXTG) file format.

##### Audio

* [AudioToolkit](https://github.com/EPD-Libraries/AudioToolkit) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-02-29 - IO library for file formats in Nintendo's nw::snd/nn::atk (NintendoWare) audio namespace.
* [AalSharp](https://github.com/EPD-Libraries/AalSharp) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-08-27 - C# IO library for BARS and other Nintendo AAL audio resource file formats.

##### amiibo (NFC Tag Data)

* [Amiibo](https://github.com/AmiiboDB/Amiibo) ⭐ 2,222 | 🐛 28 | 🌐 Python | 📅 2025-03-21 - Database of amiibo `.bin`/`.nfc` NFC tag dumps.
* [emuiibo](https://github.com/XorTroll/emuiibo) ⭐ 1,399 | 🐛 30 | 🌐 C++ | 📅 2026-04-05 - Virtual amiibo (amiibo emulation) system for Nintendo Switch, evolved from ogniK5377's switch-nfp-mitm.
* [AmiiboAPI](https://github.com/N3evin/AmiiboAPI) ⚠️ Archived - RESTful API and database of amiibo NFC tag data.
* [amiitool.net](https://github.com/ca1e/amiitool.net) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2024-08-18 - C# port of amiitool, for decrypting/encrypting Nintendo amiibo NFC tag dumps.
* [GameCubeToolkit](https://github.com/Vertridge/GameCubeToolkit) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-03-22 - Toolkit for reading and editing GameCube-related files.

### Sharp X68000 SDKs & Hardware

* [mdxtools](https://github.com/vampirefrog/mdxtools) ⭐ 91 | 🐛 22 | 🌐 C | 📅 2026-07-15 - Collection of tools for handling the MDX music format used on the Sharp X68000.
* [x68k2amiga](https://github.com/hitchhikr/x68k2amiga) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2026-03-02 - Amiga program to convert Sharp X68000 executable files (and various X68000 data formats) to Amiga executables for subsequent reversing.
* [x68000\_converters](https://github.com/hitchhikr/x68000_converters) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2024-11-30 - Set of Python scripts to convert various Sharp X68000 file formats (including ADPCM audio samples) to more usable states.
* [wav2adpcm](https://github.com/tantanGH/wav2adpcm) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-01-07 - Converts WAV PCM audio into the Sharp X68000's native ADPCM sound format.
* [png2xsp](https://github.com/Mikejmoffitt/png2xsp) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2025-03-12 - Converts PNG spritesheets into the Sharp X68000's XSP sprite library data format.
* [furnace\_z68](https://github.com/hitchhikr/furnace_z68) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-08-08 - Modification of the Furnace chiptune tracker adding X68000 .z68 music export and an ASM replay routine.

### PlayStation SDKs & Hardware

*Formats and tools generic to PlayStation consoles/SDKs, not tied to a specific game.*

* [Vita3K](https://github.com/Vita3K/Vita3K) ⭐ 5,684 | 🐛 206 | 🌐 C++ | 📅 2026-09-04 - Experimental HLE PlayStation Vita emulator for Windows, Linux, macOS, and Android, running original PS Vita game data. See also [nckstwrt's fork](https://github.com/nckstwrt/Vita3K-Plus) ⭐ 128 | 🐛 19 | 🌐 C++ | 📅 2026-09-04 with extensive per-game compatibility fixes for 30+ commercial titles.
* [vita2hos](https://github.com/xerpi/vita2hos) ⭐ 1,256 | 🐛 4 | 🌐 C | 📅 2025-06-07 - PlayStation Vita to Horizon OS (Nintendo Switch OS) translation layer (not an emulator), parsing Vita's executable format to run titles under Switch's OS.
* [PSn00bSDK](https://github.com/Lameguy64/PSn00bSDK) ⭐ 1,120 | 🐛 28 | 🌐 C | 📅 2025-01-28 - Open source SDK for PS1 homebrew development, defining the toolchain and native formats used by the author's TIMedit, img2tim, and smxtool below.
* [PicoMemcard](https://github.com/dangiu/PicoMemcard) ⭐ 683 | 🐛 39 | 🌐 C | 📅 2024-08-01 - Emulates a PlayStation 1 memory card (or controller) using a Raspberry Pi Pico, reading/writing real memory card data over the console's controller port. See also [MrPalloncini's fork](https://github.com/MrPalloncini/PicoMemcard) ⭐ 32 | 🐛 9 | 🌐 C | 📅 2024-08-01 with GameID support, and [alex-free's fork](https://github.com/alex-free/PicoMemcard) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2025-09-24 adding compatibility with the Tonyhax/FreePSXBoot soft-mod exploit.
* [qcma](https://github.com/codestation/qcma) ⭐ 666 | 🐛 4 | 🌐 C++ | 📅 2026-08-17 - Cross-platform, open-source alternative to Sony's Content Manager Assistant for transferring content to/from the PS Vita.
* [memcardrex](https://github.com/ShendoXT/memcardrex) ⚠️ Archived - Advanced PlayStation 1 memory card editor for managing save files with support for multiple formats.
* [DirectPackageInstaller](https://github.com/marcussacana/DirectPackageInstaller) ⭐ 443 | 🐛 17 | 🌐 C# | 📅 2026-06-28 - Tool to preview and send PKG files directly to a PS4 or PS5 over the network, supporting three different transfer methods.
* [uofw](https://github.com/uofw/uofw) ⭐ 438 | 🐛 35 | 🌐 C | 📅 2026-02-11 - The Unofficial Official FirmWare, a complete reverse engineering project for the latest PSP firmware.
* [LibOrbisPkg](https://github.com/maxton/LibOrbisPkg) ⭐ 362 | 🐛 21 | 🌐 C# | 📅 2023-10-24 - Library, GUI, and CLI for creating, inspecting, and modifying PS4 PKG, SFO, PFS, and related package/filesystem formats.
* [mkpsxiso](https://github.com/Lameguy64/mkpsxiso) ⭐ 334 | 🐛 3 | 🌐 C++ | 📅 2026-07-09 - ISO disc image maker written specifically for PlayStation homebrew development. Tool to build and extract PlayStation 1 CD images from XML. Modern cross-platform replacement for BUILDCD from PsyQ SDK. Supports mixed-mode CD-XA with audio/video streams.
* [ps3recomp](https://github.com/sp00nznet/ps3recomp) ⭐ 302 | 🐛 6 | 🌐 C | 📅 2026-09-04 - Static recompilation runtime libraries for PlayStation 3 titles.
* [pkg2zip](https://github.com/lusid1/pkg2zip) ⭐ 282 | 🐛 1 | 🌐 C | 📅 2026-08-04 - Decrypts PlayStation Vita PKG files and repackages their contents (apps, DLC, patches, themes, PSM, PSX, PSP) into zip archives.
* [psvimgtools](https://github.com/yifanlu/psvimgtools) ⭐ 210 | 🐛 1 | 🌐 C | 📅 2017-02-28 - Decrypts PlayStation Vita CMA backup images.
* [psximager](https://github.com/cebix/psximager) ⭐ 210 | 🐛 3 | 🌐 C++ | 📅 2024-08-15 - Tools for dumping and mastering PlayStation 1 ("PSX") CD-ROM images.
* [Playstation-4-Save-Mounter](https://github.com/ChendoChap/Playstation-4-Save-Mounter) ⭐ 158 | 🐛 6 | 🌐 C# | 📅 2019-05-21 - Mounts PS4 save data with read/write access via ps4debug, for decrypting, replacing, sharing, and exporting save files. See also [n0llptr's fork](https://github.com/n0llptr/Playstation-5-Save-Mounter) ⭐ 77 | 🐛 5 | 🌐 C | 📅 2026-08-14, which adds PS5 save mounting support.
* [MkPFS](https://github.com/PSBrew/MkPFS) ⭐ 152 | 🐛 7 | 🌐 Python | 📅 2026-09-03 - Command-line tool and Python library (PyPI-packaged, with GUI) for building, verifying, inspecting, browsing, and extracting PlayStation FileSystem (PFS) disk images (.ffpfs, .ffpfsc, .pfs, .dat, .exfat, .bin), including PKG/FPKG inner-PFS generation for PS4/PS5.
* [psvpfstools](https://github.com/motoharu-gosuto/psvpfstools) ⭐ 147 | 🐛 24 | 🌐 C++ | 📅 2022-02-06 - Set of tools to decrypt the PFS (PlayStation File System) filesystem layer used on PS Vita.
* [pspdecrypt](https://github.com/John-K/pspdecrypt) ⭐ 136 | 🐛 20 | 🌐 C | 📅 2024-06-07 - Simple tool to decrypt PSP binaries.
* [pkg\_pfs\_tool](https://github.com/flatz/pkg_pfs_tool) ⭐ 104 | 🐛 2 | 🌐 C | 📅 2023-09-08 - PKG/PFS unpacker for PS4, extracting package and filesystem contents.
* [ps4-cfw-toolkit](https://github.com/Al-Azif/ps4-cfw-toolkit) ⭐ 103 | 🐛 0 | 🌐 C++ | 📅 2022-12-26 - Decrypts and encrypts various PlayStation 4 firmware files.
* [ps5-app-dumper](https://github.com/EchoStretch/ps5-app-dumper) ⭐ 94 | 🐛 6 | 🌐 C | 📅 2026-07-28 - PS5 payload that dumps installed application files from the console's mounted \`p
* [libcrypt-patcher](https://github.com/alex-free/libcrypt-patcher) ⭐ 91 | 🐛 8 | 🌐 C | 📅 2026-01-30 - All-in-one patcher for PS1 disc images protected by Sony's LibCrypt anti-piracy scheme, removing the protection directly from the CD image.
* [VitaMTP](https://github.com/yifanlu/VitaMTP) ⚠️ Archived - Library implementing the PS Vita's USB MTP-based content transfer protocol, used by qcma and similar tools. Archived.
* [psxavenc](https://github.com/WonderfulToolchain/psxavenc) ⚠️ Archived - PS1 audio/video encoding tool; converts standard audio/video into the PlayStation 1's native STR/SPU/XA formats.
* [PlayStation 1 VST Instruments](https://github.com/BodbDearg/PlayStation1Vsts) ⭐ 83 | 🐛 3 | 🌐 C | 📅 2023-10-01 - VST instruments replicating the PS1 SPU sound chip for music production: an ADPCM sampler that plays back original PS1 .VAG samples with authentic ADSR/interpolation behavior, plus a matching SPU reverb module. Built from the SPU emulation code in the same author's PsyDoom.
* [dynlib](https://github.com/aerosoul94/dynlib) ⭐ 70 | 🐛 2 | 🌐 C | 📅 2018-03-01 - IDA Pro plugin to aid PS4 user mode ELF reverse engineering. Loads PS4-specific DYNLIBDATA segment, resolves obfuscated symbol NIDs to label imports/exports, loads symbol table, and patches relocations.
* [KELFBinder](https://github.com/israpps/KELFBinder) ⭐ 69 | 🐛 4 | 🌐 C | 📅 2026-04-01 - DVD Player and System Updates manager for the PS2, building and patching the console's signed KELF (kernel-ELF) files.
* [img2tim](https://github.com/Lameguy64/img2tim) ⭐ 66 | 🐛 5 | 🌐 C++ | 📅 2024-07-19 - Converts standard images to the PlayStation 1 TIM texture format.
* [ps5-pup-decrypt](https://github.com/zecoxao/ps5-pup-decrypt) ⭐ 62 | 🐛 0 | 🌐 C | 📅 2025-07-25 - Decrypts PS5 PUP (firmware update package) files by directing an exploited PS5 console to decrypt them itself.
* [Memory Card Annihilator](https://github.com/ffgriever-pl/Memory-Card-Annihilator) ⭐ 61 | 🐛 6 | 🌐 C | 📅 2025-04-26 - PS2 memory card management tool with native exFAT filesystem support, covering ProtoKernel PS2 consoles (SCPH-10000/15000) and separate builds for Arcade, Developer, and Prototype memory card hardware variants.
* [psp-ghidra-scripts](https://github.com/pspdev/psp-ghidra-scripts) ⭐ 56 | 🐛 4 | 🌐 Python | 📅 2025-11-25 - Collection of scripts to aid in reverse engineering PSP binaries in Ghidra.
* [LibOrbisPkg](https://github.com/OpenOrbis/LibOrbisPkg) ⭐ 56 | 🐛 8 | 🌐 C# | 📅 2026-08-22 - Library, GUI, and CLI tools for creating, inspecting, and modifying PlayStation 4 PKG, SFO, PFS, and related filetypes. Open-source alternative to Sony SDK tools.
* [Save-Transfer-Wizard](https://github.com/rajeshca911/Save-Transfer-Wizard) ⭐ 52 | 🐛 0 | 🌐 Visual Basic .NET | 📅 2025-04-22 - Windows GUI tool for transferring, decrypting, and browsing PS5 save data over FTP.
* [psvcd](https://github.com/motoharu-gosuto/psvcd) ⭐ 51 | 🐛 1 | 🌐 C++ | 📅 2017-09-16 - Documents research into hardware-dumping PS Vita game cartridges (PlayStation Vita Cartridge Dump).
* [ps4-pkg-manager](https://github.com/hippie68/ps4-pkg-manager) ⭐ 48 | 🐛 0 | 🌐 Java | 📅 2025-12-09 - Light-weight, cross-platform desktop application to manage large collections of PS4 PKG files.
* [Ps2IsoTools](https://github.com/Finzenku/Ps2IsoTools) ⭐ 48 | 🐛 2 | 🌐 C# | 📅 2024-10-13 - Tools to read, build, and edit PS2 ISO images that use the UDF filesystem.
* [ps4-pup\_unpack](https://github.com/idc/ps4-pup_unpack) ⭐ 45 | 🐛 0 | 🌐 C# | 📅 2017-12-12 - PS4 PUP (firmware/system update package) unpacking tool.
* [pkgrip](https://github.com/qwikrazor87/pkgrip) ⭐ 42 | 🐛 4 | 🌐 C | 📅 2023-09-26 - Fast Linux tool for decrypting PS3/PSP PKG files.
* [TIMedit](https://github.com/Lameguy64/TIMedit) ⭐ 42 | 🐛 8 | 🌐 C++ | 📅 2024-08-06 - Graphical converter and management tool for PlayStation 1 TIM texture files.
* [aprip](https://github.com/alex-free/aprip) ⭐ 39 | 🐛 3 | 🌐 C | 📅 2024-05-29 - Generator for PS1 Anti-Piracy Protection bypass patches, analyzing a disc image's specific protection implementation to produce a working bypass.
* [psp-media-engine-cracking-the-unknown](https://github.com/mcidclan/psp-media-engine-cracking-the-unknown) ⭐ 36 | 🐛 0 | 🌐 Assembly | 📅 2026-08-14 - Research documentation on the PSP's Media Engine, covering its Virtual Mobile Engine (VME), specialized move instructions, bitstream/context handling, local DMACs, VLD unit, and H.264 decoder.
* [sfo](https://github.com/hippie68/sfo) ⭐ 33 | 🐛 3 | 🌐 C | 📅 2022-01-05 - Fast C program that reads a file to print or modify its SFO parameters. Can be used for automation or to build param.sfo files from scratch. Also available as .exe file for Windows command line.
* [psio-helper](https://github.com/ncirocco/psio-helper) ⭐ 32 | 🐛 4 | 🌐 Go | 📅 2020-05-17 - Cross-platform Go tool that prepares PS1 CUE/BIN disc images for use with the PSIO optical drive emulator cartridge.
* [create-fself](https://github.com/OpenOrbis/create-fself) ⭐ 29 | 🐛 1 | 🌐 Go | 📅 2026-01-04 - Takes PC-compatible ELFs and generates fake SELF files that run on the PlayStation 4.
* [pkgrename](https://github.com/hippie68/pkgrename) ⭐ 28 | 🐛 2 | 🌐 C | 📅 2025-12-16 - Renames PS4 PKG files based on param.sfo information, online search, and predefined patterns.
* [ps3-ckit](https://github.com/tge-was-taken/ps3-ckit) ⭐ 24 | 🐛 0 | 🌐 C | 📅 2021-09-06 - PS3 C code injection framework. Toolkit for running arbitrary C code in games, hooking existing functions, and inserting custom functionality.
* [psx\_psyq\_signatures](https://github.com/lab313ru/psx_psyq_signatures) ⭐ 20 | 🐛 0 | 🌐 C | 📅 2022-01-08 - Signatures for PlayStation 1 PsyQ SDK LIB/OBJ files in JSON form, for identifying statically-linked SDK code in PS1 binaries. See also [psx\_psyq\_flair](https://github.com/lab313ru/psx_psyq_flair) ⭐ 9 | 🐛 0 | 🌐 Max | 📅 2019-11-30, the same signatures in IDA FLAIR format.
* [PsxVram-SDL](https://github.com/romhack/PsxVram-SDL) ⭐ 19 | 🐛 1 | 🌐 C | 📅 2022-08-06 - PlayStation 1 VRAM viewer.
* [nploader](https://github.com/codestation/nploader) ⭐ 19 | 🐛 1 | 🌐 C | 📅 2024-09-30 - PSP plugin for directly reading and loading DLC content in decrypted EDAT/PGD/SPRX form.
* [smxtool](https://github.com/Lameguy64/smxtool) ⭐ 17 | 🐛 1 | 🌐 C++ | 📅 2021-11-22 - Editing tool for PlayStation RSD and SMX model data formats. See also [Blender-RSD-Plugin](https://github.com/Lameguy64/Blender-RSD-Plugin) ⭐ 37 | 🐛 2 | 🌐 Python | 📅 2017-11-23, a Blender plugin for exporting models in the PlayStation SDK RSD format.
* [kirk](https://github.com/ProximaV/kirk) ⭐ 16 | 🐛 0 | 🌐 C++ | 📅 2024-08-17 - IDA Pro processor module for the PSP's KIRK crypto engine.
* [psx-undither](https://github.com/alex-free/psx-undither) ⭐ 16 | 🐛 1 | 🌐 C | 📅 2024-07-31 - Disables the dithering effect in PS1 games, either by patching the CD image directly or by generating GameShark codes from a DuckStation RAM dump.
* [PS4-Package-Assessor-Java](https://github.com/Cryptogenic/PS4-Package-Assessor-Java) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2016-08-06 - Java tool that evaluates PS3/PS4 .PKG files and displays information about them in a clean manner.
* [PS5-SELF-Decrypter](https://github.com/EchoStretch/PS5-SELF-Decrypter) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2025-11-11 - PS5 payload that uses kernel arbitrary read/write to decrypt Signed ELF (SELF) binaries from the filesystem and dump the plaintext ELFs to a USB drive.
* [edcre](https://github.com/alex-free/edcre) ⭐ 14 | 🐛 1 | 🌐 C++ | 📅 2025-03-21 - Regenerates EDC/ECC data for PS1/PS2 CD images (BIN+CUE) after the image has been edited, so patched discs still pass integrity checks.
* [psexe2rom](https://github.com/alex-free/psexe2rom) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2026-01-28 - Converts PS1 executables (PS-EXE) into flashable GameShark-compatible ROM files.
* [DTP-T1000-Pre-IPL-dumper](https://github.com/mathieulh/DTP-T1000-Pre-IPL-dumper) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2024-01-12 - Dumps the PSP's Pre-IPL loader segment from kbooti/bootdispi boot files.
* [PSPLibDoc](https://github.com/Spenon-dev/PSPLibDoc) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2024-06-02 - Documents symbols (NIDs) of PSP modules across firmware versions, with tools to load PSPLibDoc XML, PSP export (.exp), and PPSSPP HLE source files.
* [ps4-pkg-compatibility-checker](https://github.com/hippie68/ps4-pkg-compatibility-checker) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2023-09-06 - GUI tool with drag-and-drop that checks PKG checksums to determine whether PS4 game and update PKG files are compatible ("married").
* [PS2-ECC-Memory-Card-Converter](https://github.com/ffgriever-pl/PS2-ECC-Memory-Card-Converter) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2025-03-09 - Converts PS2 memory card images between ECC and non-ECC binary formats, including images created by Memory Card Annihilator, for use with PCSX2 and vice versa.
* [ECCScan](https://github.com/Terraonion-dev/ECCScan) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2020-11-17 - PS1 EDC/ECC scanner and fixer for raw CD dumps (mode 2, 2352 bytes/sector); checks and repairs Error Detection/Correction Code mismatches, complementing the check-only edccchk tool.
* [pops2cue](https://github.com/bucanero/pops2cue) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2026-01-13 - Reverse-engineered (via Ghidra disassembly) reconstruction of POPS2CUE and CUE2POPS, Sony's original tools for converting PS2/PS3 "POPS" PS-one Classics packages to and from CUE+BIN disc images.
* [psp-arc-sdk](https://github.com/galaxyhaxz/psp-arc-sdk) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2021-02-16 - Tools for building and extracting the DES-CBC encrypted .arc format updates found within early PSP SDKs.
* [MemCardPro-ASM](https://github.com/Cybdyn-Systems/MemCardPro-ASM) ⭐ 5 | 🐛 0 | 🌐 Assembly | 📅 2024-05-19 - 8BitMods MemCard Pro firmware library/object source, written in MIPS R3000 assembly, for the PS1 hardware memory-card-emulation device.
* [SGXDataBuilder](https://github.com/Nenkai/SGXDataBuilder) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2026-06-28 - Creates and builds Sony SGX/SGXD Audio Banks from standard audio formats. Used in various PSP and PS3 games including Gran Turismo 5/6, LocoRoco Cocoreccho, Ape Escape Move, and more.
  * Formats: sgd/sgh/sgb (output), WAV/AC3 (input).
* [ps2-tim2-tool](https://github.com/PS2HomeDeveloper/ps2-tim2-tool) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-09-04 - Tool for working with the PS2 TIM2 texture format, used across many PS2 titles.
* [PSY-Q SDK Version Finder](https://github.com/jdperos/psyq-version-finder) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2026-03-02 - GUI tool for PS1 decompilation projects that identifies which Sony PSY-Q SDK version(s) a binary was built with, via color-coded byte-level signature diffing across 10+ SDK releases.
* [LibreFios](https://github.com/neptuwunium/LibreFios) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2024-09-04 - PSARC library in C# for working with PlayStation PSARC archive format.
* [lib-enigma](https://github.com/alex-free/lib-enigma) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2026-05-05 - C library for patching and identifying PS1/PS2 CD images; spiritual successor to (and supersedes) the author's earlier lib-ppf and lib-ps-cd-id libraries.
* [mymc](https://github.com/uyjulian/mymc) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-01-10 - Utility for working with PlayStation 2 memory card images (PCSX2 format). Supports importing/exporting save games in MAX Drive (.max) and EMS (.psu) formats, viewing memory card contents, creating new memory card images, and adding/extracting individual files. Includes GUI and command-line interfaces.
* [AteliELF](https://github.com/Hakanaou/AteliELF) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-28 - Python ELF reverse engineering and patching toolchain for PowerPC64 Big Endian binaries (Cell Broadband Engine), originally built for PS3 game text extraction/reinsertion; also has partial PS Vita and PS2 support.
  * Features: text detection (English/Japanese heuristics, CP932/Shift-JIS), pointer resolution (direct and PPC `lis`/`addic` split-pointer patterns), bin-packing string reinsertion with automatic pointer/phdr updates, EBOOT decrypt/re-encrypt integration, DeepL/Google Translate hookup, Tkinter GUI.
* [mipsasm (cakehonolulu fork)](https://github.com/cakehonolulu/mipsasm) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-07-08 - MIPS assembler targeting the PS2 Emotion Engine and IOP; fork of [imaandrew/mipsasm](https://github.com/imaandrew/mipsasm) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2023-10-02 (originally targeting the N64) retargeted for PS2.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-05._
