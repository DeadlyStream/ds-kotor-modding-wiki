Modding Tools
===========

This is a list of the most commonly used/most important tools for modding KOTOR.


## General Links ##

[Deadly Stream's Modding Tool Downloads](https://deadlystream.com/files/category/17-modding-tools/)



[StarWarsKnights.com's Modding Tool Downloads](http://www.starwarsknights.com/tools.php)



[Internet Archive](https://archive.org/), which you may need to access many links for modding KOTOR.



## Admin ##

These are tools that let you extract and edit game files. They're needed for putting assets into the game, though generally they don't handle the creation of assets - that's covered in the sections below.



### [KOTOR Tool](https://deadlystream.com/topic/1949-downloadkotor-tool/) by Fred Tetra ###

The swiss-army knife of KOTOR modding, and the first thing any KOTOR modder needs. View and extract all game file types. Also includes a built-in GFF Editor, 2DA Editor, Script Editor and DLG Editor (K1 only) which are all serviceable. 



### [KOTOR Toolset](https://deadlystream.com/files/file/767-kotor-toolset/) by Fair Strides ###

Design levels for KOTOR. The Toolset has a map editor with a preview of the area you're editing and comes with built-in editors for associated objects like creatures, placeables, doors, and sounds.



### [K-GFF](http://www.starwarsknights.com/mtools/kgff_131.zip) by tk102 ###

Edit files saved with BioWare's Generic File Format. This covers a broad range of game files - everything from characters to stores to triggers to journal entries. ARE, DLG, GIT, GUI, IFO, JRL, PTH, RES, UTC, UTD, UTE, UTM, UTI, UTP, UTT, UTS, UTW are all examples of GFF files.



### gff2xml & xml2gff, [xoreos tools](https://github.com/xoreos/xoreos-tools) ###

Convert GFF files to XML format and back again.



### [2DA Editor](http://www.starwarsknights.com/mtools/kgff_131.zip) by VarsityPuppet ###

2DA Editor can edit any 2-Dimensional Array (2DA) file. 2DA is a fancy term for a spreadsheet and a lot of critical files are 2DAs because spreadsheets are handy - things like character appearances, player classes, and item types. 2DA Editor has a few nifty features that KOTOR Tool's editor lacks, like filtering search terms and copy/pasting cells.



### Convert2da, a [xoreos tool](https://github.com/xoreos/xoreos-tools) ###

Convert 2DA files to ASCII or CSV format, and back again.



### [ERFEdit](https://deadlystream.com/files/file/499-erfedit/) by stoffe (update by Fair Strides) ###

Pack and unpack the ERF and RIM archive formats, including the related MOD, SAV, and HAK formats. ERFEdit can extract resources from any of these files or create them. If you're editing an area or creating your own, you'll want to use ERFEdit to package all its contents in a .mod file for release.



### [JRLEdit](https://deadlystream.com/files/file/473-jrledit-journal-editing-tool/) by Fair Strides ###

Edit quests and journal entries. JRLEdit has a user-friendly interface with a list of all quests in the game and a dropdown menu for each journal entry in each quest.



## Compatibility ##

These tools help ensure that mods will actually work for other people with different setups.



### [TSL Patcher](https://deadlystream.com/files/file/1039-tsl-patcher-tlked-and-accessories/) by stoffe (update by Fair Strides) ###

Make your mod compatible with other mods. TSLPatcher can patch TLK, 2DA, SSF, and GFF files to make specific changes to files - that way, different mods can make different changes to the same files and still remain compatible. If your mod edits a critical file like appearance.2da, you'll need to make an installer with TSLPatcher so people can use your mod along with all the other mods that edit the same file. TSLPatcher comes with the additional program ChangeEdit, which can set up the instructions for a mod installer.



### [Language Converter for DLG/UTI/UTC/MOD Files](https://deadlystream.com/files/file/718-language-converter-for-dlgutiutcmod-files/) by tk102 ###

Text strings in the game have different language identifiers, and the game will only display text for the language it's running. The Language Converter will add the necessary language identifiers so that mods written in another language will have their text properly display for your game's language.



## Models ##

These are tools for editing 3D art assets - the realm of MDL, MDX, ASCII, and DWK/PWK/WOK files.



### [MDLOps](https://deadlystream.com/files/file/779-mdlops/) by Chuck Chargin Jr. (updates by Torlack, JdNoa, Fair Strides, VarsityPuppet, and ndix UR) ###

Convert model files from the binary MDL/MDX format to an ASCII format that modeling programs can read, and back again. The Renamer and Replacer functions can also make certain edits directly to binary MDL/MDX models without having to decompile.



### [MDLEdit](https://deadlystream.com/files/file/1150-mdledit/) by bead-v ###

Convert model files from the binary MDL/MDX format to an ASCII format that modeling programs can read, and back again. MDLEdit is an alternative to MDLOps in that both do mostly the same stuff, but perform their calculations differently and have different interfaces. MDLEdit is also able to make certain edits to binary MDL/MDX models without having to decompile, like changing texture names, enabling bump maps, and editing controller values for things like alpha and self illumination.



### [KOTORMax](https://deadlystream.com/files/file/1151-kotormax/) by bead-v (based on NWMax by Joco) ###

Import and export ASCII models with 3ds Max and Gmax.



### [KOTORBlender](https://deadlystream.com/files/file/889-kotorblender/) by Symmetric, Purifier, and ndix UR ###

Import and export ASCII models with Blender.



## Textures ##

These are tools for editing 2D art assets - the realm of TPC, TGA, TXI, and DDS files



### [tga2tpc](https://deadlystream.com/files/file/1152-tga2tpc/) by ndix UR ###

Convert TGA files (and associated TXI data) to TPC files. This is necessary if you want to use normal maps, as the game will only read them in TPC format.



### [KOTOR Stuff](https://deadlystream.com/files/file/1128-kotor-stuff/) by ApanLoon ###

Extract textures. KOTOR Stuff can read TXI data from a TPC file and convert everything in it as individual PNG files, like different faces of a cube map or different frames in an animation. It can also convert back to TPC and extract files from BIF and ERF archives.



### xoreostex2tga, a [xoreos tool](https://github.com/xoreos/xoreos-tools) ###

Convert textures from TPC format to TGA/TXI for editing.



### [TGA to DDS Converter](https://deadlystream.com/files/file/536-bioware-tga-to-dds-converter/) by BioWare ###

Convert TGA files to DDS files that are KOTOR-readable.



### [Texture Tools](https://developer.nvidia.com/nvidia-texture-tools-adobe-photoshop) for Adobe Photoshop by NVIDIA ###

These scripts and plug-ins for Photoshop can make normal maps, cube maps, and mipmaps, and allow Photoshop to edit DDS files.



## Scripting ##

These are tools that let you work with the game's programming language. If you want to spawn characters or other objects, give the player a reward for completing a quest, or create a new Force power, you'll need a script. KOTOR uses its own programming language, NWScript, which is very similar to C# and Java.



### [NWNSCOMP Port for KOTOR Script Compiler](http://www.starwarsknights.com/mtools/nwnnsscomp_st.zip) by Torlack, stoffe, and tk102 ###

Compile scripts from NSS text format to the NCS format for KOTOR.



### [DeNCS](http://www.starwarsknights.com/mtools/DeNCS.zip) by JdNoa and Dashus ###

Decompile scripts from NCS to NSS format so you can read and edit them.



### ncsdis & ncsdecomp, [xoreos tools](https://github.com/xoreos/xoreos-tools) ###

Disassemble or decompile NWScript bytecode.



### [KOTOR Scripting Tool](https://deadlystream.com/files/file/191-kotor-scripting-tool/) by Blue ###

Write scripts for KOTOR. You can write them in any text editor, but the Scripting Tool has a more user-friendly interface.



### [Odessey++](https://deadlystream.com/files/file/1395-odyssey/) by JCarter426 ###

User-defined language with autocompletion for Notepad++. Designed to make writing scripts for KOTOR a more user-friendly experience for those that do use a text editor.



## Dialogue & Cutscenes ##

Whenever you talk to an NPC, or use a computer terminal, or see anything letterboxed with fancy cinematic black bars, a DLG file is at work. This section of tools covers editing the DLG format itself and other elements that come into play for dialogues and cutscenes, such as cameras and lip files.



### [TalkEd](http://www.starwarsknights.com/mtools/TalkEd104b.rar) by stoffe ###

Edit a game's dialog.tlk file, which contains every line of text in the game. This isn't needed for most dialogue editing but every line of dialogue, every item description, every journal entry can be changed by editing the TLK file - anything with text. Some things do require dialog.tlk entries, such as feat and Force power descriptions.



### [DLGEditor](http://www.starwarsknights.com/mtools/dlgconv_11.rar) by tk102 ###

Edit the DLG format used for dialogues and cutscenes. DLGEditor can edit any dialogue file from either game.



### tlk2xml & xml2tlk, [xoreos tools](https://github.com/xoreos/xoreos-tools) ###

Convert dialog.tlk to XML format and back again.



### [LipSynchEditor](http://www.starwarsknights.com/mtools/LipSynchEditor.zip) by JdNoa ###

Edit the LIP format so characters will have lip flap when they talk. LipSynchEditor can edit LIP files, create new ones from scratch, and import PHN files to convert them to LIP.



### [CSLU Toolkit](https://deadlystream.com/files/file/1414-cslu-toolkit-no-online-licensing/) by Center for Spoken Language Understanding (license courtesy Jenko) ###

Generates PHN files from audio. May be used in conjunction with LipSynchEditor to make lip flap.



### [AniCam](http://www.starwarsknights.com/mtools/AniCamB3.zip) by JdNoa ###

Create animated camera models for cutscenes. AniCam's interface is a spreadsheet - you enter the coordinates for the camera at each specific time and then AniCam will create a camera that moves between those points. It has an interpolation option - calculating points between the points you give it - to improve the camera path.



### [AnimatedCameraDataCreator](https://deadlystream.com/topic/5092-animatedcameradatacreator/) by bead-v ###

Create animated camera models for cutscenes, in a different way. AC⚡DC uses fancy Bézier curves that allow for smooth camera paths. It uses a graph interface, so you get somewhat of a preview of your camera path.



### [K1 dialog.tlk file](http://www.starwarsknights.com/mtools/KotOR_TLKFile.zip) by BioWare ###

This is the unedited English dialog.tlk file from Star Wars: Knights of the Old Republic. Certain modding tools require this file in order to run, so if you don't have the game installed you can download the dialog.tlk file and point the tools to it so they'll run.



### [K2 dialog.tlk file](http://www.starwarsknights.com/mtools/TSL_TLKFile.zip) by Obsidian ###

This is the unedited English dialog.tlk file from Star Wars: Knights of the Old Republic II - The Sith Lords. Certain modding tools require this file in order to run, so if you don't have the game installed you can download the dialog.tlk file and point the tools to it so they'll run.



## Audio & Video ##

These are tools that deal with the game's audio and video formats - either converting stuff from the game to a more common media format, or getting media you have into the game.



### [Miles Sound System](https://web.archive.org/web/20070703062308/http://www.radgametools.com/down/MilesSndSys/MilesT32.exe) by RAD Game Tools ###

Play and convert the game voice and music files. Your typical media player probably won't be able to play the format they're saved in, but Miles will, and it can also convert between formats.



### [Soundset File Editor](http://www.starwarsknights.com/mtools/SSFEdit.rar) by stoffe ###

Edit or create soundsets - the lines characters bark when in combat or performing certain tasks, like picking locks or setting mines. "Time to rumble!" "You have left me an opening!" "Pure pazaak!" "I will be your doom!" That stuff.



### ssf2xml & xml2ssf, [xoreos tools](https://github.com/xoreos/xoreos-tools) ###

Convert soundsets from SSF to XML format and back again.



### [Bink Video](http://www.radgametools.com/bnkdown.htm) by RAD Game Tools ###

Play and convert the game movies. Pre-rendered cinematics are saved in the proprietary BIK format, so if you want to view or edit them outside the game, you'll have to convert to a more common format first. Bink Video can convert from BIK to a variety of video formats, and can also convert a variety of video formats to BIK if you want to add a movie to the game.



## xoreos ##

[xoreos](https://xoreos.org/) is an ongoing project to reimplement BioWare's Aurora engine and all its derivatives, including the KOTOR Odyssey engine. A number of handy tools have been developed for the project. Many additional tools may be found in their [tools repository](https://github.com/xoreos/xoreos-tools]xoreos).



## And the Rest ##

Other useful links go here.



### [KOTOR SaveGame Editor](https://deadlystream.com/files/file/503-kotor-savegame-editor/) by tk102 (update by Fair Strides) ###

Edit your saves to do things like add items, give your characters feats and Force powers, edit global variables, and remove the "cheat enabled" flag.



### [GLIntercept](https://deadlystream.com/files/file/860-glintercept-freecam-in-kotor/) by Damian Trebilco ###

Mess around with the camera in-game. Like the Xbox freecam, but with more hacking.



### Whereami Armband by Darth333, tk102, and glovemaster([English](http://www.starwarsknights.com/mtools/whereami206.zip), [French](http://www.starwarsknights.com/mtools/whereami205fr.rar)) ###

Get the coordinates of your current location, since the whereami cheat isn't helpful in K2. The log will also output the tags of nearby objects, and there's an option to open the nearest door.



### Toolbox by JCarter426 ([K1](https://deadlystream.com/files/file/1239-jcs-toolbox-for-k1/), K2 TBA) ###

Change party members whenever you want, open and close doors, play animations, delete objects, warp, teleport, and do various other things that come in handy for developing and testing mods.



## Legacy Tools ##

These are tools that have been superseded by other tools on the list. Their functionality was once useful, but is either built into newer tools or isn't needed anymore thanks to updates. They're listed here for legacy support to prevent confusion. Older tutorials will no doubt mention many of these tools.



### [NWMax](https://neverwintervault.org/project/nwn1/other/tool/nwmax-8) by Joco ###

The model importer for Neverwinter Nights, what KOTORMax is based on.



### [HeadFixer](https://deadlystream.com/files/file/770-kotortsl-headfixer/) by VarsityPuppet ###

Heads compiled with older versions of MDLOps would not animate. HeadFixer adds that missing data to head models. This function is built into MDLEdit and newer versions of MDLOps.



### [K-Aurora](https://deadlystream.com/files/file/703-kaurora/) by MagnusII ###

Older versions of MDLOps didn't have walkmesh support for areas. KAurora can convert from WOK to ASCII for and back for editing and it can also edit the room links of WOK files. All walkmesh functionality is now supported by KOTORMax, KOTORBlender, MDLOps, and MDLEdit.



### [WalkSwitch](https://deadlystream.com/files/file/475-walkswitch-collision-map-editor/) by Fair Strides ###

It can change the material type of a walkable surface without having to decompile the model. It can't change walk to non-walk or non-walk to walk, however. Walkmesh materials are now integrated into KOTORMax & KOTORBlender.