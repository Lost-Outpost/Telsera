<img src="https://i.imgur.com/kW90Y5Y.png" target="_blank">

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/149944">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="PAGEFILE.md">Pagefile</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="HELP.md">Help</a>
</p>

---

# Installation

- [Introduction](#introduction)
  - [List Contents](#list-contents)
  - [Computer Specs](#computer-specs)
  - [Community](#community)
  - [Skyrim: Anniversary Edition (AE)](#skyrim-anniversary-edition-ae)
- [Installation](#installation-1)
  - [Pre-Install](#pre-install)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Library](#steam-library)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
    - [Problems with Wabbajack](#problems-with-wabbajack)
    - [Pagefile in prevention of memory crashes](#pagefile-in-prevention-of-memory-crashes)
- [Final Stretch](#final-stretch)
  - [Updating](#updating)
  - [Issues](#issues)
  - [Credits](#credits)

# Introduction

Telsera is a **not-safe-for-work (NSFW)** modlist designed for **Skyrim Special Edition** with the **Anniversary Edition upgrade**. The legal age restriction may differ depending on your country of residence. Where I reside, adult actions are prohibited to those **at LEAST 18 years of age**. Please use discretion while playing, as there is nudity, graphic visuals, and sexual acts present within the pack. **YOU HAVE BEEN WARNED!**

The vision behind Telsera is primarily focused on performance-friendly visuals while retaining a consistent, stable, and engaging environment, as well as gameplay and mature narratives that don't stray too far from the game itself. Contents from the AE upgrade have been reintegrated, repurposed, or rebalanced depending on the creation. More information surrounding these changes can be found below.

## List Contents

You can view the individual contents of the modlist [here via Load Order Library](https://loadorderlibrary.com/lists/telsera-a-nsfw-wabbajack-list-for-ae). As for a summary of various features, check out the [Gameplay Changes](GAMEPLAY.md) page. The installation size for this pack is about **120 GB**, while the downloads size is **77 GB**. 

## Computer Specs

I designed v1.0.0+ of Telsera around the following hardware settings:

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/c9RZWWM.png "FoamsSpecsPreviewExample")
  
</details>

Throughout the months of early beta testing, these were my specs:

<details>
  <summary>Spoiler warning - click here to expand.</summary>


![alt text](https://i.imgur.com/jnNhFc5.png "FoamsOldSpecsPreviewExample")

</details>

## Community

Support is offered in [The Lost Outpost](https://discord.gg/WF66mMu) server and in the [Issues](https://github.com/Lost-Outpost/telsera/issues) section of the Telsera GitHub.

## Skyrim: Anniversary Edition (AE)

**This list requires the PAID Anniversary Edition upgrade.** 
You must download _**ALL**_ the Creation Club content before installing Telsera. This can be done by going launching Skyrim SE via Steam, going to the main menu screen, and selecting Download All when automatically prompted. If you do not see a prompt box, try verifying your local files via Steam, then try the same steps again.

**Make sure your game is fully up to date in Steam.** 
The version number should say _**1.6.1170**_. You can check to see if your version is the most up to date by locating SkyrimSE.exe via your Steam folder (ie. C:\Steam\steamapps\common\Skyrim Special Edition), right-clicking the .exe file, select Properties, swap from General to the Details tab in the small pop-up window, and the number will be listed under File Version. An example image can be found below. Everything will be automatically patched by Wabbajack, however, it requires the latest game files.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/UAXOe7t.png "SkyrimSE.exeVersionPreviewExample")
  
</details>

Downgraded versions of Skyrim SE **WILL NOT WORK** with this pack.

# Installation

Installation is handled through [Wabbajack](https://www.wabbajack.org/#/) with a one-click install of the modlist. There are some pre-installation steps that must be followed for first-time users, so please pay attention to those. You may have to rerun the installer a few times!

## Pre-Install

These steps are only needed if you aare installing Telsera for the first time. If you are updating, feel free to jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

This package is required for Mod Organizer 2 (MO2) and you can download it from [Microsoft](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170). You will need **BOTH the X64 and X86 versions** under "Visual Studio 2015, 2017, 2019, and 2022." A preview image can be found blow.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/WKIr5Q2.png "MicrosoftVisualCPreviewExample")
  
</details>

### Steam Library

If you have your Steam library in Program Files, please read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) in order to put it somewhere else. Locations such as Documents, Downloads, Desktop, or OneDrive are **NOT** fine. The best location would be **`C:\SteamLibrary`** if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive." If you're low on space, please note you **CAN** do two separate locations: one for Telsera's Installation folder, and one for the Downloads folder. How I personally have the pack setup is the Install on my C:\ drive, while the Download folder is on my SSD's  E:\ drive.

### Set the Game language to English

The entire modlist is designed to be played in English. The installation process may fail upon running Wabbajack if you do not do so ahead of time. Steps consist of clicking Steam on the top left of your Steam inferface app window, select Settings (Steam Settings), select Interface, and click English in the top box. A preview can be seen below.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/jOajp49.png "SteamSettingEnglishPreviewExample")
  
</details>

### Steam Updates

To prevent any mishaps when Todd Howard decides to drop another Skyrim update our way, we're going to turn off automatic updates for Skyrim SE. In Steam under the Library section on the left side, right-click The Elder Scrolls V: Skyrim Special Edition, then click Properties. Switch to the Updates tab, and at the top under 'Automatic Updates' switch the option to 'Only update this game when I launch it'. Exit out of the pop-up box once you're done.

### Clean Skyrim

I highly recommend uninstalling Skyrim Special Edition _through Steam_, deleting the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents inside it. Reinstall the game via Steam afterward, then be sure to start the game to see the main menu screen. This will ensure any settings files needed by Wabbajack are created in the Skyrim directory.

## Using Wabbajack

### Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`. Grab the latest release of Wabbajack from [here](https://www.wabbajack.org/) and place the `Wabbajack.exe` file in the _working folder_. An example image can be found below.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/ePEWCNs.png "WabbajackFolderPreviewExample")
  
</details>

### Downloading and Installing

To find the Telsera via Wabbajack's UI, open Wabbajack.exe, and on the left side, select Browse Lists.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/JbmWTE8.png "WabbajackUIPreviewExample")
  
</details>

Along the left side, **be sure to tick the boxes Non-features AND NSFW**. If you don't, you won't find Telsera!

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/sz1FJXU.png "WabbajackUI2PreviewExample")
  
</details>

Once you find the thumbnail titled "Telsera" (can also search for it directly in the searchbar), you should see the following buttons along the bottom left. Download & Install is the one you want to click.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/fWfWLwC.png "WabbajackUI3PreviewExample")
  
</details>

The full download and installation process can take **a while** depending on your system specs. Go outside for a walk, head to bed for some sleep, or sit back with some popcorn while you wait! If you run into any error messages, you may need to run the installer a few times over to get past it. If you're still having trouble, drop us a line in the Lost Outpost Discord server, and we'll try to help. <3

## Using MO2

1. Once Wabbajack is finished, go into the folder where you installed Telsera. You'll see an executable called ModOrganizer.exe. Launch it to get to the next step.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/zKaM26a.png "MO2PreviewExample")
  
</details>

2. Once the program opens, look to the top right section and you should see a button that says Run.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

![alt text](https://i.imgur.com/Kg2AwzQ.png "MO2RunPreviewExample")
  
</details>

3. Click Run and you'll be set to play! It may take a while to open, so please be patient.

4. **Do not click on the "Unlock" button that pops up once the game is running.** 

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. **Wabbajack will continue where it left off so you lose no progress.** Seriously, simply retrying the Wabbajack download fixes most problems.

**Unable to download "Curios":**

Please see the steps [here in the FAQ](https://github.com/Lost-Outpost/Telsera/blob/main/HELP.md#im-getting-the-following-error-via-wabbajack-unable-to-download-curios-files-what-should-i-do).

**Could not download x**:

If a mod updates and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist. Some files are known to be problematic, it is likely those are the ones that failed. You can download them manually from their source and place the archives **AS IS** in the downloads folder.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Pagefile in the prevention of memory crashes

Bigger Skyrim modlists need a lot of memory, and when there is not enough available, it may fail to allocate more. To fix this, you'll want to have a bigger <a href="PAGEFILE.md" target="_blank">pagefile</a>. **PLEASE DO NOT SKIP THIS STEP!**

# Final Stretch

## Updating

If Telsera receives an update, please check the [changelog](CHANGELOG.md)! Information about the versioning numbers can be found on the linked page regarding what is save-safe and what is not.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the mdlist will be deleted. **Your saves will be kept**, but please check each update changelog to see if the update is save-compatible. Your downloads folder will not be touched! Updating is like installing. You only have to make sure that you select the same path in the Wabbajack UI.

## Issues

If you find an issue, please provide details in the [Telsera Github](https://github.com/Lost-Outpost/telsera/issues) OR on [The Lost Outpost](https://discord.gg/WF66mMu) support forum (be sure to select Telsera as a tag!) to have discussions with other members. 

## Credits

[Arcanaeum - A Lightweight Modlist](https://www.nexusmods.com/skyrimspecialedition/mods/125198) --- by Guitarninja2
Used as a baseline to build Telsera from.

[Wabbajack](https://www.wabbajack.org/) --- by Halgari and the Wabbajack Development Team
Core functionality.

Lost Outpost Discord Server [https://discord.gg/WF66mMu](https://discord.gg/WF66mMu) --- by GreatPadinski
Host Discord for troubleshooting, development updates, etc.

[DerrylHopkins﻿](https://next.nexusmods.com/profile/DerrylHopkins)
Many thanks for the tips and advice regarding content resolution!
