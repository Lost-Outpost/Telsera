<img src="X" target="_blank">

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/149944">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="PAGEFILE.md">Pagefile Setup</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="HELP.md">Help</a> .
</p>

---

# Configuration

- [Optional Tweaks](#optional-tweaks)
  - [Character Presets](#character-presets)
- [ENB](#ENB)

### Character Presets

Telsera includes a mod containing a premade folder structure for character presets that you either create yourself or download from others. You can copy presets you download into the designated folder. 

The presets mod is here:

![telsera-character-presets](https://i.imgur.com/p6M8AOG.png)

You can select this mod, right-click it, and then select "Open in Explorer" to see the presets directory, which will be at this location:

Example: Telsera\mods\[NoDelete] User-Made Racemenu Presets (SEE README)\SKSE\Plugins\CharGen\Presets\X

!telsera-character-presets-folder](https://i.imgur.com/x1n5llZ.png)

When you make your presets in Racemenu they will be located in the Overwrite folder after you exit the game. 

!telsera-character-overwrite-folder](https://i.imgur.com/wSJ4MIQ.png)

You can select Overwrite, right-click it, and then select "Open in Explorer" to see the presets directory (same location as above in the SKSE folder). Find the file(s) titled insertpresetnamehere.jslot, copy or cut the file, and paste into the [NoDelete] User-Made Racemenu Presets (SEE README)\SKSE\Plugins\CharGen\Presets\X folder. You have now saved your preset, and it will be safe from auto-deletion next time you update the list. The [NoDelete] portion tells Wabbajack to ignore said folder.

## ENB

> :ledger: You should only ever enable exactly one ENB preset at a time.

Changing ENB presets is not officially supported. If you'd like to make adjustments to the ENB included in Telsera, the keybinds are the following:

X

![Exe List](https://i.imgur.com/XNerPaT.png)

## Performance Guide

- Try turning off any ENB that might be enabled and switching to the available reshade preset; Reshade - Davinci Reshade.
- If switching off the ENB, disable everything in the ENB OPTIONS category.
