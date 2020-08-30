# Mass Effect 3 Modding Notes

Collected notes on modding Mass Effect 3.

## Overview

The basic pinciple is copying mod files into the game's `CookedPCConsole` folder, which contains the final files that the game uses. While this may sound simple, a lot of care has to be taken when doing this, because Mass Effect 3 was not designed to be moddable.

## Mod installers and tools

  - [ME3Tweaks Mods manager](https://www.nexusmods.com/masseffect3/mods/373)* (Content mod installer)
  - [ALOT installer](https://www.nexusmods.com/masseffect3/mods/363)* (Texture pack installer)
  - [ME3Explorer](https://www.nexusmods.com/masseffect3/mods/409) (Specialized modder tool)
  - [Gibbed's save editor](https://www.nexusmods.com/masseffect3/mods/695) (Editing save games)

*: required

## Mod types and formats

Mods can generally be split into two categories:

  - Content mods (new missions, armor, etc)
  - Texture mods (updated or new textures, sounds, video)

Some mods come as loose files that have to be copied into the game folders, and others come as DLCs. DLCs are simply loose files bundled together, which makes them easier to install.

## Installing mods

Modding Mass Effect games can be considered a **one-time process**. Once the texture mods have been installed via ALOT, there is no going back to modify something, or add additional mods. The only way is to **start over entirely**, using a previous backup of the vanilla game (which can be done with the mods manager).

### Prerequisites

The initial process can take a long time - come prepared with a good book while you wait :)

  - Install the game and all applicable DLC (all official DLC + multiplayer DLC recommended)
  - Download the modding tools (Mod Manager + ALOT)
  - Start up Mod Manager, and do a game backup
  - Download the content mods you wish to use, into a content mods folder (when available, I recommend using the torrents)
  - Download ALOT into a separate folder, and use it to choose all the texture packs you wish to use

### RTFM. No kidding!

Modding Mass Effect is special in that it's not drag and drop modding like most games these days. If a mod author says to read the docs, it means you **really, really should**. Not following the instructions precisely can just as easily break the game, which can happen anytime in a playthrough.

### Install order

Mods must be installed in this exact order:

  - Install content mods via ME3Tweaks Mods manager (see individual mod guides below)
  - Install texture mods via ALOT installer
  - In the mod manager, go to `Tools` > `Binkw32 bypasses` (aka DLC patcher), and enable them
  - Play
  
### Problems & starting over

To start over, use the Mod Manager's restore backup feature: it will revert the game to its vanilla state. After this, repeat the installation process again, with any changes you believe necessary.

### TOCs, TOCing, Auto-TOCing

The game runs on the Unreal engine, which uses index files that contain a "Table of contents" of all files the game needs, and their respective sizes. When adding mods, this means the TOC files must be updated. This process is called Auto-TOCing in the mod manager.

NOTE: Auto-TOCing can be done anytime, it is a non-breaking operation. In general, you do not need to do this manually, since both the Mod Manager and ALOT have an Auto-TOC feature that is applied whenever necessary.

## Mods installation guide

This assumes all official DLCs are installed, including the collector's edition and multiplayer addons, and that all mods in this list are used.

I tested this exact configuration, and made one successful playthrough with it.

Install in the order shown here.

### MEHEM (aka ME3 Happy Ending Mod)

Modifies the ending to make it happier than the existing ending.

https://www.nexusmods.com/masseffect3/mods/66

  - Use the installer.

NOTE: Disregard the warnings in the installer (it says so in the wiki).
  
### Expanded Galaxy Mod

Adds a lot of content and improvements. The definitive must-have.

https://www.nexusmods.com/masseffect3/mods/350

  - Use the Mod Manager.
  - In the mod settings window, choose  the following:
      - `Mod settings` > `Quick Play Mode` > `ON`.
      - `Normandy` > `Cabin Invite Music` > `Cabin Music Player`.
      - `Normandy` > `Map Reapers` > `No Reapers`.
      - `Armors/Outfits` > Customize as you see fit.
  - Click `Finish`.
  
### Ark Mod

Adds some missions.

https://www.nexusmods.com/masseffect3/mods/678

  - Use the Mod Manager.

### Spectre Expansion

Extends the spectre terminal.

https://www.nexusmods.com/masseffect3/mods/634

  - Use the Mod Manager.

### ME3 Recalibrated

General fixes and improvements.

https://www.nexusmods.com/masseffect3/mods/411

  - Install v2.0 via the Mod Manager.
  - Open the v2.1 update ZIP.
      - Copy the contents to `DLC/DLC_MOD_ME3RE/CookedPCConsole`.

### BackOff

Improves romance aspects.

https://www.nexusmods.com/masseffect3/mods/412

  - Install the v1.0 via the Mod Manager.
  - Install the v1.0 BOPatches via the Mod Manager.
  - Open the v1.2 Update ZIP.
      - Copy contents of `BackOff` to `DLC/DLC_CON_BACKOFF/CookedPCConsole`.
      - Copy contents of `BOPatches/BW_LevDLC` to `DLC/DLC_CON_BOPATCHES/CookedPCConsole`.
      - Copy contents of `BOPatches/ME3Re_v2.0` to `DLC/DLC_CON_BOPATCHES/CookedPCConsole`.

### Tali romance mod

Install only when playing with a male Shepard. Also, must have romanced Tali in ME2.

https://www.nexusmods.com/masseffect3/mods/610

  - Use the Mod Manager.
  
### N7 Armour Mod [DISABLED]

**EDIT:** Disabled this, as it seemed to cause crashes. Also, some of the armors had hair clipping issues. Sometimes the hair would pop out of the hoodie. 

https://www.nexusmods.com/masseffect3/mods/431

  - Use the mod manager.

### Hair Mods as DLCs

https://www.nexusmods.com/masseffect3/mods/425

Note: It is best to choose the hair styles you want beforehand, because each style has to be activated separately in the Mod Manager. They are numbered, so the best is to make a list like this:

  - Abehce: 1, 4, 5
  - CS (aka Counting Stars): 1, 3, 4, 7
  - ELE: 1, 5, 6
  - Kani: 2, 3, 4, 5, 7, 8, 11
  - NIL (aka NameIsLooney): 3, 4, 6, 7, 13, 18, 20
     
### ALOT installation

  - Download all the texture packs listed in ALOT that you wish to install.
  - Download additional packs to a separate folder.
  - When ready, drag & drop all additional packs into the ALOT window.
  - Start the install.
  - After preparation, confirm the installation.

#### Different variations of officially listed packs

In some cases, you may wish to download an alternate version of the texture pack listed in ALOT, like a different color of an armor. In this case, download it and treat it as an additional texture pack. 

NOTE: Renaming the file you downloaded to match ALOT's filename will not work, as it uses file CRCs to ensure the right file is used.

Disregard ALOT's warning on missing texture packs when installing if you chose different variations.

### Ready to play

After these steps, the game is ready to play.

### Mission timings

To get the most out of this combination of mods, there is an optimal order to when you should run some missions:

  - _From Ashes_: after _Priority: Menae_
  - _Leviathan_: after _Priority: Rannoch_
  - _Omega_: after _Priority: Citadel II_
  - _Citadel_: after _Priority: Rannoch_
  - _Operation: Paladin_: after _Citadel_

This can be customized in the Expanded Galaxy Mod settings.

## Customizing character appearance

### Vanilla character codes

These codes can be used without any additional textures or headmorphs. They are some I collected online from various sources (femshep codes exclusively).

  - Rene - `741.1EH.C14.P8Q.F7C.7HE.N6K.6G1.DE5.8R7.2G6.415`
  - Alexis - `743.1AJ.E67.K8C.G76.15E.NIA.8G7.R95.8P7.6G6.475`
  - Nonducklips - `753.QBG.F17.F1K.FDE.1HL.1FD.411.IK6.519.6G5.525`
  - Clare - `141.F1D.G17.F21.FBI.19W.15E.711.KE6.4I7.626.316`
  - Mia - `733.1AL.L41.W1R.HL7.75J.3WF.111.P16.115.BG5.311`
  - Arastia - `733.1FI.G81.M19.UEH.87Q.7LI.511.M86.1A7.4G5.555`
  - Renegade - `143.BBC.K41.G1H.RB1.B4L.JJJ.111.ND6.6F3.B2B.875`
  - Unnamed 1 - `743.1GL.F12.861.EGE.17F.3IA.121.C96.193.6G5.576`
  - Unnamed 2 - `741.1EH.C12.W8Q.F7C.7HE.N6K.6G1.DE5.8R7.6G6.426`

### Using headmorphs

Headmorphs are files that contain a detailed 3D structure for the character's head. They can be installed into a savegame file using Gibbed's save editor. 

1. Start the save editor & open your save game file.
2. Go to the tab called `Appearance` > `Head Morph` > `Import from File`.
3. Select the target `.headmorph` file.
5. Click "Save", overwrite or create new file.

## Advanced appearance customization

The colors and textures for the character's head are defined in the savegames. Using Gibbed's save game editor, values can be changed directly. This allows much more customization possibilities as the ingame editor, as many settings are not accessible in the ingame editor.

To start editing the appearance:

1. Open a savegame with Gibbed's save editor.
2. Navigate to`Squad` > `Player` > `Appearance` > `Head Morph` > `Texture Parameters`.

### Eyes

  - Iris color: `EYE_Iris_Colour_Vector`
  - Eye shadow color: `HED_EyeShadow_Tint_Vector`
  - Eyelid shadow: `HED_Brow_Tint_Vector`

### Hair

Eyebrow color: `HED_Addn_Colour_Vector`

Texture Parameters
  - Hair color: `HED_Hair_Colour_Vector`
  - Hair glow color 1: `Highlight1Color` (used when light reflects off the hair)
  - Hair glow color 2: `Highlight2Color`

Scalar Parameters
  - Hair shine: `HAIR_Spec_Contribution_Scalar`
  - Hair shine desaturation: `HAIR_Shine_Desaturate_Scalar`
  - Highlight intensity 1: `Hightlight1Intensity`
  - Highlight intensity 2: `Hightlight2Intensity`

### Lips

Texture Parameters
  - Lip color: `HED_Lips_Tint_Vector`

Scalar Parameters
  - Lip gloss: `HED_Addn_Spec_Lips_Scalar`
  - Lip color intensity: `HED_Lips_Tint_Scalar`

Note: if nothing is selected in the texture parameters, lip intensity is for the default lip color.

### Blush

Texture Parameters 
  - Blush color: `HED_Blush_Vector`

Scalar Parameters
  - Blush intensity: `HED_Blush_Scalar` 

## Cheats

### Changing game settings

Many cheats are available by editing the game's main `Coalesced.bin` file, which contains a bundle of INI files that control many aspects of the game. There is an exhaustive list here:

https://gaming.stackexchange.com/questions/54867/how-can-i-edit-coalesced-bin-so-that-i-can-use-cheats-and-graphics-tweaks

### Reaper alertness and scan range tweaks

Open the console (default=TAB), and enter the following command:

```
set maxhighlightrange 800 | set sfxgalaxymapreaper m_fscandetectionrange 0 | set sfxgalaxymapreaper maxspeed 0 | set bioplanet m_fscandetectionrange 800 | set sfxinventorymanager fuelefficiency 0.0
```

This executes a list of commands (several commands can be separated with pipes, `|`), which do the following:

  - Increase scan range to the whole system
  - Make reaper ships immobile
  - Decrease reaper scan range to 0
  - Make the Normandy not consume any fuel
  - Increase the range of highlighting objects
  
These settings are reset after each mission - simply run the command again.

NOTE: It is also possible to turn off the Reapers in systems in the Extended Galaxy Mod settings.

### Creating executable batch / script files

Console commands can be assigned to a hotkey. For this, the key bindings must be modified manually using the game's `Coalesced.ini` file.

  - Save the list of commands to execute to a file `Mass Effect/Binaries/_disable-reaper-detection.txt`
  - Open `Mass Effect/BIOGame/CookedPCConsole/Coalesced.bin` in Coalesced editor
  - Go to `bioinput.ini` > `sfxgame` > `sfxgamemodedefault` > `bindings`
  - Add the following entry: `( Name="NumPadSeven", Command="exec _disable-reaper-detection.txt" )`
  
Now you can execute the commands of that file by pressing numpad 7.

NOTE: Did not work in my tests.

## Persuading the Illusive Man

To enable the persuasion options at the end, it is necessary to have a high enough total Paragon + Renegade points (any combination thereof), as well as pass all three persuasion options with the Illusive Man on Mars, Thessia and the Cerberus HQ.

## Lexicon / Dictionary

  - `ALOT`: Specialized mod manager for texture packs.
  - `Auto-TOCing`: Using an automated tool to update a TOC file (see TOC).
  - `BO`: The "Back Off" mod, which extends romance possibilities.
  - `Binkw32 bypasses`: DLL fix to allow modded videos.
  - `Character code`: Code that can be pasted into the character creator to reproduce specific settings.
  - `Coalesced.bin`: Settings file, for both the game itself or DLCs.
  - `CookedPCConsole`: Subfolder of the game in which all assets are stored (textures, videos, sound, etc).
  - `DLC Patcher`: See Binkw32 bypasses.
  - `EGM`: Expanded Galaxy Mod, one of the most popular ME3 mods.
  - `Gibbed's editor`: Save game editor by Gibbed.
  - `Headmorph`: File containing a custom 3D structure for a character's head.
  - `ME3Explorer`: Modder tool to view and modify game assets.
  - `ME3Tweaks`: The Mass Effect 3 mod manager, aka ME3Tweaks Mod Manager.
  - `ME3`: Mass Effect 3.
  - `MEHEM`: The "Mass Effect 3 Happy Ending Mod", a popular mod that modifies the game's ending.
  - `TOC`: "Table Of Contents" files containing lists of files the game needs to load assets.
  - `TOCing`: The action of updating a TOC file.  
