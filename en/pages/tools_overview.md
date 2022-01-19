# Modding Tools

This is a list of the most commonly used/most important tools for modding KOTOR.

- - - -

## General Links

[Deadly Stream's Modding Tool Downloads](https://deadlystream.com/files/category/17-modding-tools/)

[StarWarsKnights.com's Modding Tool Downloads](https://web.archive.org/web/20181204145431/http://www.starwarsknights.com/tools.php) (Wayback Machine archive)

- - - -

## Asset Extraction and Management

These are tools that let you extract and edit game files. They're needed for putting assets into the game, though generally they don't handle the creation of assets - that's covered in the sections below.

### KOTOR Tool by Fred Tetra

The KOTOR can opener. View and extract all game file types. Also includes a built-in GFF Editor, 2DA Editor, Script Editor and DLG Editor (K1 only) which are all serviceable but it is ***strongly*** advised to avoid their use.

Download [here](https://deadlystream.com/topic/1949-downloadkotor-tool/).

###  K-GFF by tk102

Edit files saved with BioWare's Generic File Format. This covers a broad range of game files - everything from characters to stores to triggers to journal entries. ARE, DLG, GIT, GUI, IFO, JRL, PTH, RES, UTC, UTD, UTE, UTM, UTI, UTP, UTT, UTS, UTW are all examples of GFF files.

Download [here](https://web.archive.org/web/20160405094841/http://starwarsknights.com/mtools/kgff_131.zip)  (Wayback Machine archive).

### gff2xml / xml2gff by Xoreos

Convert GFF files to XML format and back again.

Download [Xoreos Tools](https://github.com/xoreos/xoreos-tools).

###  Convert2da by stoffe

Convert 2DA files to tab-delimited text format, and back again.

Download [here](https://web.archive.org/web/20160405034935/http://starwarsknights.com/mtools/Convert2da.rar) (Wayback Machine archive).

### convert2da by Xoreos

Convert 2DA files to ASCII or CSV format, and back again.

Download [Xoreos Tools](https://github.com/xoreos/xoreos-tools).

### 2DA Editor (alpha) by VarsityPuppet

2DA Editor can edit any 2-Dimensional Array (2DA) file. 2DA is a fancy term for a spreadsheet and a lot of critical files are 2DAs because spreadsheets are handy - things like character appearances, player classes, and item types. 2DA Editor has a few nifty features that KOTOR Tool's editor lacks, like filtering search terms and copy/pasting cells.

Download [here](https://deadlystream.com/files/file/1335-2da-editor-alpha/).

### ERFEdit by stoffe (updated by Fair Strides)

Pack and unpack the ERF and RIM archive formats, including the related MOD, SAV, and HAK formats. ERFEdit can extract resources from any of these files or create them. If you're editing an area or creating your own, you'll want to use ERFEdit to package all its contents in a .mod file for release.

Download [here](https://deadlystream.com/files/file/499-erfedit/).

### JRLEdit by Fair Strides

Edit quests and journal entries. JRLEdit has a user-friendly interface with a list of all quests in the game and a dropdown menu for each journal entry in each quest.

Download [here](https://deadlystream.com/files/file/473-jrledit-journal-editing-tool/).

- - - -

## Installation/Compatibility

These tools help ensure that mods will work for other people with different setups.

### TSLPatcher by stoffe (update by Fair Strides)

Make your mod installation compatible with other mods. TSLPatcher can patch TLK, 2DA, SSF, and GFF files to make specific changes rather than simple replacement. It can also slipstream files into MOD archives. That way, different mods can make different changes to the same files and still remain compatible. If your mod edits a critical file like appearance.2da, you'll need to make an installer with TSLPatcher so people can use your mod along with all the other mods that edit the same file. TSLPatcher comes with the additional programs ChangeEdit which can create the instructions for a mod installer, and TalkEd for creating TLK entries.

Download [here](https://deadlystream.com/files/file/1039-tsl-patcher-tlked-and-accessories/).

### Language Converter for DLG/UTI/UTC/MOD Files by tk102

Text strings in the game have different language identifiers, and the game will only display text for the language it's running. The Language Converter will add the necessary language identifiers so that mods written in another language will have their text properly display for your game's language.

Download [here](https://deadlystream.com/files/file/718-language-converter-for-dlgutiutcmod-files/).

- - - -

## Model Editing/Creation

These are the tools for editing 3D art assets.

### MDLEdit by bead-v

Convert model files from the binary MDL/MDX format to an ASCII format that KMax can read, and back again. MDLEdit is an alternative to MDLOps. Both functionally do the same thing, but perform their calculations differently and have different interfaces. MDLEdit is also able to make certain edits to models in the GUI, like changing texture names, enabling bump maps, and editing controller values for things like alpha and self illumination, without needing to export/edit an ASCII.

Download [here](https://deadlystream.com/topic/5735-mdledit-bug-reporting-thread/?do=findComment&comment=73932) (N.B. - linked beta version is the latest).

### MDLOps by Chuck Chargin Jr. (updates by Torlack, JdNoa, Fair Strides, VarsityPuppet, and ndix UR)

Convert model files from the binary MDL/MDX format to an ASCII format that modeling programs can read, and back again. The Renamer and Replacer functions can also make certain edits directly to binary MDL/MDX models without having to decompile.

Download [here](https://github.com/ndixUR/mdlops/releases) (N.B. - the version of MDLOps available on DS is outdated. The most recent version is available from ndix UR's Github repo linked here).

### KOTORMax by bead-v (based on NWMax by Joco) 

Import and export ASCII models with 3DS Max and GMax.

Download [here](https://deadlystream.com/files/file/1151-kotormax/).

### KotorBlender by seedhartha (forked from KotorBlender by ndix UR, in turn forked from NeverBlender)

Import and export models with Blender. The latest incarnation eschews the need for intermediary ASCIIs and imports/exports binary MDL/MDXs directly. Also works with more recent versions of Blender.

Download [here](https://deadlystream.com/files/file/1853-kotorblender-for-blender-293/).

- - - -

## Textures

These are tools for editing 2D art assets - the realm of TPC, TGA, TXI, and DDS files

### tga2tpc by ndix UR

Convert TGA files (and associated TXI data) to TPC files. This is necessary if you want to use normal maps, as the game will only read them in TPC format.

Download [here](https://deadlystream.com/files/file/1152-tga2tpc/).

### tpcview by ndix UR

TPC file viewer. Can also extract to TGA + TXI.

Download [here](https://deadlystream.com/files/file/1552-tpcview/).

### xoreostex2tga by Xoreos

Convert textures from TPC and other Aurora/Odyssey image formats to TGA for editing. Note that the TXB listed is for Jade Empire. For KOTOR Xbox (TXB) textures, use the TPC option.

N.B. - As of writing, xoreostex2tga fails to convert some textures and does not extract TXI data.

Download [Xoreos Tools](https://github.com/xoreos/xoreos-tools).

- - - -

## Scripting ##

These are tools that let you work with the game's programming language. If you want to spawn characters or other objects, give the player a reward for completing a quest, or create a new Force power, you'll need a script. KOTOR uses its own programming language, NWScript, which is very similar to C# and Java.


### NWNNSSComp by Torlack, stoffe, and tk102

A port of the NWN script compiler for KOTOR. Compile scripts from NSS text format to binary NCS.

N.B. - You ***must*** use the nwscript.nss from the version of the game you are targeting. TSL includes changed and added functions that are not compatible with K1.

Download [here](https://web.archive.org/web/20160405041814/http://starwarsknights.com/mtools/nwnnsscomp_st.zip) (Wayback Machine archive).

### DeNCS by JdNoa and Dashus

Decompile scripts from NCS to NSS format so you can read and edit them. Requires Java.

N.B. - You ***must*** use the nwscript.nss from the version of the game the script is from. TSL includes changed and added functions that are not compatible with K1.

Download [here](https://web.archive.org/web/20160405105949/http://starwarsknights.com/mtools/DeNCS.zip) (Wayback Machine archive).

### ncsdis / ncsdecomp by Xoreos

Disassemble NCS to plain text bytecode (ncsdis) or partially decompile to NSS (ncsdecomp). Typically the use of DeNCS is preferred, but for scripts that it cannot decomple, these tools provide a fallback to try and reverse engineer the original script.

Download [Xoreos Tools](https://github.com/xoreos/xoreos-tools).

### Odyssey++ by JCarter426

User-defined NWScript language with autocompletion for Notepad++. Designed to make writing scripts for KOTOR in N++ a more user-friendly experience.

Download [here](https://deadlystream.com/files/file/1395-odyssey/).

### KOTOR Scripting Tool by Blue

Write scripts for KOTOR. You can write them in any text editor, but the Scripting Tool has a more script-oriented interface.

Download [here](https://deadlystream.com/files/file/191-kotor-scripting-tool/).

- - - -

## Dialogue & Cutscenes

Whenever you talk to an NPC, use a computer terminal, or see any in-engine cutscene, a DLG file is at work. This section of tools covers editing the DLG format itself and other related elements, such as cameras and lip syncing.

### DLGEditor by tk102

Edit the DLG format used for dialogues and cutscenes. DLGEditor can edit any dialogue file from either game. This is the primary tool used when working with conversations/cutscenes.

Download [here](https://web.archive.org/web/20160405045305/http://starwarsknights.com/mtools/dlgeditor_232.zip) (Wayback Machine archive).

### tlk2xml / xml2tlk by Xoreos

Convert dialog.tlk to XML format and back again.

Download [Xoreos Tools](https://github.com/xoreos/xoreos-tools).

### CSLU Toolkit by Center for Spoken Language Understanding (license-free version courtesy of Jenko)

Generates PHN files from audio tracks. Used in conjunction with LipSynchEditor to produce LIP files.

Download [here](https://deadlystream.com/files/file/1414-cslu-toolkit-no-online-licensing/).

### LipSynchEditor by JdNoa

Edit LIP files, create new ones from scratch, and import PHN files to convert them to LIP. Requires Java.

Download [here](https://web.archive.org/web/20160405095233/http://starwarsknights.com/mtools/LipSynchEditor.zip) (Wayback Machine archive).

### AniCam by JdNoa

Create animated cameras for cutscenes. AniCam's interface is a spreadsheet - you enter the coordinates for the camera at each specific time and then AniCam will create a camera that moves between those points. It has an interpolation option to improve the camera path.

Download [here](https://web.archive.org/web/20160405040201/http://starwarsknights.com/mtools/AniCamB3.zip) (Wayback Machine archive).

### AnimatedCameraDataCreator by bead-v

Create animated cameras for cutscenes, in a different way. AC⚡DC uses fancy Bézier curves that allow for smooth camera paths. It uses a graph interface, so you get somewhat of a preview of your camera path.

More info [here](https://deadlystream.com/topic/5092-animatedcameradatacreator/) (appears to be unavilable for download).

- - - -

## Audio & Video ##

These are tools that deal with the game's audio and video formats - either converting stuff from the game to a more common media format, or getting media you have into the game.

### SithCodec by JCarter426

Remove and add the fake headers that various KOTOR audio files have. Most files are typically either MP3 with fake WAV headers, or WAV with fake MP3 headers. This is what causes most audio programs to encounter errors when trying to play them.

Download [here](https://deadlystream.com/files/file/1716-sithcodec/).

### Soundset (SSF) File Editor by stoffe

Edit or create soundsets - the lines characters bark when in combat or performing certain tasks, like picking locks or setting mines.

Download [here](https://web.archive.org/web/20160405095750/http://starwarsknights.com/mtools/SSFEdit.rar) (Wayback Machine archive).

### ssf2xml / xml2ssf by Xoreos

Convert soundsets SSFs to XML format and back again.

Download [Xoreos Tools](https://github.com/xoreos/xoreos-tools).

### Bink Video by RAD Game Tools

Pre-rendered cinematics are saved in the proprietary BIK format. Bink Video can convert from BIK to a variety of video formats, and can also convert a variety of video formats to BIK if you want to add a movie to the game. It also provides a player to play existing BIKs.

Download [here](http://www.radgametools.com/bnkdown.htm).

### Miles Sound System by RAD Game Tools

Play and convert the game voice and music files.

Download [here](https://web.archive.org/web/20070703062308/http://www.radgametools.com/down/MilesSndSys/MilesT32.exe) (Wayback Machine archive).

- - - -

## Alternative Game Engines

Not strictly tools, but these may become more relevant to mod creators in the future as the various projects mature and people start using them en masse.

### reone by seedhartha

A C++ reimplementation of the Odyssey engine. Arguably the most advanced and the most promising of the various engine projects.

Project repository [here](https://github.com/seedhartha/reone).

### Xoreos

A C++ reimplemention of BioWare's Aurora engine and all its derivatives, including KOTOR's Odyssey engine. Of primary interest to modders is the Xoreos Tools side-project, many of which have been mentioned above.

Project repository [Xoreos](https://github.com/xoreos/xoreos)

## KotOR.JS by Blue

A JavaScript reimplementation of the Odyssey engine, also including KotOR Forge, a modding suite.

Project repository [here](https://github.com/KobaltBlu/KotOR.js).

## Northern Lights by Lachjames

A Unity/C# reimplementation of the Odyssey engine, forked from KotOR-Unity and heavily modified. Also includes the KotOR Level Editor (KLE).

Project repository [here](https://github.com/lachjames/NorthernLights).

## KotOR-Unity by rwc4301

A conversion layer between the Odyssey engine and Unity. This project appears to be defunct.

Project repository [here](https://github.com/rwc4301/KotOR-Unity).

- - - -

## General Utilities

Miscellaneous tools that come in handy.

### K1 Utility Armbands by Star Admiral

For K1. Output the coordinates of your current location, and other information, to the feedback screen.

Download [here](https://www.gamefront.com/games/knights-of-the-old-republic/file/k1-utility-armbands).

### Whereami Armband by Darth333, tk102, and glovemaster

For TSL. Output the coordinates of your current location, and other information, to the feedback screen.

Download [here](https://web.archive.org/web/20160405041825/http://starwarsknights.com/mtools/whereami206.zip) (Wayback Machine archive).

### JC's Toolbox for K1 by JCarter426

Provides a range of utility functions that are useful for mod development/testing. Change party members, open and close doors, play animations, delete objects, warp, teleport, etc.

Download [here](https://deadlystream.com/files/file/1239-jcs-toolbox-for-k1/).

### KOTOR SaveGame Editor (KSE) by tk102 (update by Fair Strides)

Edits the saves for both games. Provides access to global variables, which is useful when testing mods.

Download [here](https://deadlystream.com/files/file/503-kotor-savegame-editor/).

### GLIntercept by Damian Trebilco

An OpenGL hijack that is primarily used for the freecam plugin, which allows unrestricted camera movement independent of the selected character (although it has rendering issues). Can be useful for capturing close-up screenshots.

Download preconfigured version [here](https://deadlystream.com/files/file/860-glintercept-freecam-in-kotor/) (Original repository [here](https://github.com/dtrebilco/glintercept)).

- - - -

## Legacy Tools

These are tools that have been superseded by other tools on the list and/or no longer function correctly. Their functionality was once useful, but is either built into newer tools or isn't needed anymore thanks to updates. They're listed here for legacy support to prevent confusion. Older tutorials will no doubt mention many of these tools.

### KOTOR Toolset by Fair Strides

The Toolset has a map editor with a preview of the area you're editing and comes with built-in editors for associated objects like creatures, placeables, doors, and sounds. Still retains some utility, but does not run on Windows 10/11.

Download [here](https://deadlystream.com/files/file/767-kotor-toolset/).

### NWMax by Joco

The model importer script for Neverwinter Nights. KOTORMax is the Odyssey-specific derivative.

Download [here](https://neverwintervault.org/project/nwn1/other/tool/nwmax-8).

### HeadFixer by VarsityPuppet

Heads compiled with older versions of MDLOps would not animate. HeadFixer adds that missing data to head models. This function is built into MDLEdit and MDLOps 1.0+.

Download [here](https://deadlystream.com/files/file/770-kotortsl-headfixer/).

### K-Aurora by MagnusII

Older versions of MDLOps didn't have walkmesh support for areas. KAurora can convert from WOK to ASCII for and back for editing and it can also edit the room links of WOK files. All walkmesh functionality is now supported by KOTORMax, KOTORBlender, MDLEdit, and MDLOps 1.0+. Not compatible with modern tools or the latest ASCII versions.

Download [here](https://deadlystream.com/files/file/703-kaurora/).

### WalkSwitch by Fair Strides

It can change the material type of a walkable surface without having to decompile the model. It can't change walk to non-walk or non-walk to walk, however. Walkmesh material editing is now integrated into KOTORMax & KOTORBlender.

Download [here](https://deadlystream.com/files/file/475-walkswitch-collision-map-editor/).
