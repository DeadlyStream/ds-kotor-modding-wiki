# 2DA

_Bioware File Format Docs:_

> A 2da file is a plain-text file that describes a 2-dimensional array of data.
>  
> In BioWare's games, 2da files serve many purposes, and are often crucial to the proper functioning of the game and tools. They describe many aspects of the rules and game engine.
> Although 2da files are plain text files, they are structured according to a set of rules that must be followed in order for the game and tools to read them correctly.

# Archives

There are 2 archive formats used:

## KEY + BIF

_Bioware File Format Docs:_

> BioWare's games and tools make use of a very large number of files that are packed into a group of files having the .bif extension. The contents of the .bif files are described by one or more files having the .key extension

## ERF/MOD/HAK/RIM

_Bioware File Format Docs:_

> The Encapsulated Resource File (ERF) format is one of BioWare's methods of packing multiple files into a single file so that they may be treated as a single unit. In this regard, it is similar to .zip, .tar, or .rar. BioWare Aurora Engine/Toolset files that use the ERF format include the following: .erf, .hak, .mod, and .nwm.

# BIK

> Proprietary video format developed by RAD Game Tools; used for playing movie clips in video games on both PCs and console systems; allows standard video to be highly compressed while optimizing video quality for the target platform.

# GFF

_Bioware File Format Docs:_

> The Generic File Format (GFF) is an all-purpose generic format used to store data in BioWare games. It is designed to make it easy to add or remove fields and data structures while still maintaining backward and forward compatibility in reading old or new versions of a file format._
> 
> The following file types within a module are all in GFF:
> * Module info file (ifo)
> * Area-related files: area file (are), game object instances and dynamic area properties (git), game instance comments (gic)
> * Object Blueprints: creature (utc), door (utd), encounter (ute), item (uti), placeable (utp), sound (uts), store (utm), trigger (utt), waypoint (utw)
> * Conversation files (dlg)
> * Journal file (jrl)
> * Faction file (fac)
> * Palette file (itp)
> * Plot Wizard files: plot instance/plot manager file (ptm), plot wizard blueprint (ptt)
> 
> The following files created by the game are also GFF:
> Character/Creature File (bic)

# Layouts

# LIP

# Models

## MDL

## MDX

# Scripts

> NWScript is the scripting language used to control behavior of objects, items, NPCs and other aspects of modules in NWN. It is a programming language specific to the NWN game.
> 
> NWScript is based upon the C programming language and contains most of the C language syntax. NWScript does not support arrays, nor the Standard C library, such as printing to the screen, file I/O, nor system calls. These limitations are of little consequence to the NWN game, as an existing library of functions and functionality is provided with the game.

## NSS
> A plain text file which can be compiled into byte code (NCS) that the engine can execute.

## NCS

> A binary file generated from script source (NSS) that the Odyssey engine can execute.

# Textures

## DDS (Direct Draw Surface)

>A DDS file is a raster image saved in the DirectDraw Surface (DDS) container format. It can store compressed and uncompressed pixel formats and is often used for texturing video game unit models.

## TGA (Targa)

> TGA refers to a raster graphics file format created by Truevision Inc. This format had been used as the native format for TARGA and VISTA graphic cards for IBM PC’s to support Truecolor display.

## TPC/TXB

> Images in the game source are stored in the .TPC or .TXB format, along with additional embedded rendering information.

## TXI

> A text file with rendering information for how to render an associated DDS/TGA file with the same name. If used with a TPC/TXB file, the embedded rendering information will be overridden.

# TLK

_Bioware File Format Docs:_

> BioWare's games are released in multiple languages, so it is necessary for game text to be different depending on the language of the user.
>
> The talk table file, called dialog.tlk (and dialogf.tlk, containing feminine strings for certain languages), contains all the strings that the game will display to the user and which therefore need to be translated. Keeping all user-visible strings in the talk table makes it easier to produce multiple language versions of the game, because all the other game data files (with the exception of voice-over sound files) can remain the same between all language versions of the game. Using the talk table also has the advantage of reducing the amount of disk space required to store the game, since text for only one language is included.
