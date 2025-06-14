<img src="https://i.imgur.com/kW90Y5Y.png" target="_blank">

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

- [ENB Settings](#ENB)
- [Character Presets](#character-presets)
- [OStim Standalone](#OStim-SA)
- [Smaller OStim Navigation Menu](#OStim-Navi)


## ENB Settings

You should only ever enable exactly one ENB preset at a time. Changing ENB presets is not officially supported, but if you'd like to make adjustments to the ENB included in Telsera, the keybinds are the following:

 <kbd>F11</kbd> - Opens up the ENB menu (press again to close). 
 
 NOTE - It's recommended to ALSO PRESS  <kbd>'</kbd> to bring up Skyrim's console as well, so then while you configure your settings in the main menu, your character isn't punching the air everytime you click.

<kbd>;</kbd> - Enables the depth-of-field effect. 

 <kbd>F7</kbd> - Enables the FPS overlay effect. 

 <kbd>Home</kbd> - Disables the ENB. 

### Character Presets

Telsera includes a mod containing a premade folder structure for character presets that you either create yourself or download from others. You can copy presets you download into the designated folder. 

The presets mod is here:

![telsera-character-presets](https://i.imgur.com/p6M8AOG.png)

You can select this mod, right-click it, and then select "Open in Explorer" to see the presets directory, which will be at this location:

Example: Telsera\mods\[NoDelete] User-Made Racemenu Presets (SEE README)\SKSE\Plugins\CharGen\Presets\X

![telsera-character-presets-folder](https://i.imgur.com/x1n5llZ.png)

When you make your presets in Racemenu they will be located in the Overwrite folder after you exit the game. 

![telsera-character-overwrite-folder](https://i.imgur.com/wSJ4MIQ.png)

You can select Overwrite, right-click it, and then select "Open in Explorer" to see the presets directory (same location as above in the SKSE folder). Find the file(s) titled insertpresetnamehere.jslot, copy or cut the file, and paste into the [NoDelete] User-Made Racemenu Presets (SEE README)\SKSE\Plugins\CharGen\Presets\X folder. You have now saved your preset, and it will be safe from auto-deletion next time you update the list. The [NoDelete] portion tells Wabbajack to ignore said folder.

## OStim Standalone

To navigation to the control setup of OStim SA, head to the Mod Configuration tab on the pause menu.

![telsera-ostim-menu-navi](https://i.imgur.com/CyERQE1.png)

Once you find the entry titled OStim Standalone, click the Controls tab on the left. Here you'll find all the keybinds for Telsera's setup.

![telsera-ostim-menu-mcm](https://i.imgur.com/tL9fvkR.png)

They are different than OStim SA's default setup, as this is what I'm personally accustomed to, but in the picture above under Navigation Keys, you can tick the checkbox to reset the controls to their default state. I realize everyone has their preference when it comes to keybinds, so feel free to change them to whatever is easiest for you!

## Smaller OStim Navigation Menu

If you find that while in-game the menu screen for OStim's navigation pane is too big for your liking, don't worry, you're in luck! Navigate to the mod titled Smaller Scene Menu For OStim Standalone (SEE README) under the Optional Mods section of the list. 

![telsera-smaller-ostim-menu](https://i.imgur.com/XTUqhGZ.png)

You can select that mod entry, right-click it, and then select "Open in Explorer" to see the directory. Find the file titled ui_settings.json, right-click it, and select COPY.

![telsera-smaller-ostim-menu-copy](https://i.imgur.com/ehhznIP.png)

Now we're going to navigate to the paste location. Head to the following: C:\Users\YourName\Documents\My Games\Skyrim Special Edition\OStim\X. You will find a similar file titled the same thing: ui_settings.json. We're going to PASTE the new .json and REPLACE the one in the OStim folder. 

![telsera-smaller-ostim-menu-paste](https://i.imgur.com/b4T2ln4.png)

... and you're done! Next time you go in-game, the menu will be slightly smaller to accomendate viewing better.
