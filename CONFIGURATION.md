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

- [Hotkeys](#Hotkeys)
- [OStim Standalone](#OStim-Standalone)
- [Smaller OStim Navigation Menu](#Smaller-OStim-Navigation-Menu)
- [Character Presets](#Character-Presets)
- [ENB Settings](#ENB-Settings)

## Hotkeys

- <kbd>`</kbd> - Opens up Skyrim's console.

- <kbd>CTRL</kbd> - Toggles sneaking.

- <kbd>SHIFT</kbd> - Toggles sprinting.

- <kbd>E</kbd> - Use selected item in inventory, create item while crafting, or take item while browsing container.

  - **NOTE** - pressing <kbd>E</kbd> while selecting an instrument (drum, flute, lute) from your inventory will cause the player to play said instrument via [Skyrim's Got Talent - Improve As a Bard](https://www.nexusmods.com/skyrimspecialedition/mods/50357). Repetitious playing will level up your musical skillset!

- <kbd>F</kbd> - In inventory, favorite selected item.

- <kbd>R</kbd> - Drop selected item in inventory, or take all items from a container.

- <kbd>Q</kbd> - Opens up [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604) favorites menu.

- <kbd>Middle Mouse Button</kbd> - Locks on to enemies in [True Directional Movement](https://www.nexusmods.com/skyrimspecialedition/mods/51614).

- <kbd>Middle Mouse Wheel</kbd> - Switches targets in [True Directional Movement](https://www.nexusmods.com/skyrimspecialedition/mods/51614).

- <kbd>X</kbd> - Toggles compass visibility.

- <kbd>\\</kbd> - Toggles entire HUD visibility.

- <kbd>K</kbd> - Opens up The New Gentlemen's genital selector. Please see [here later in the Gameplay Guide]() for more information.

- <kbd>]</kbd> - Allows the user to change the weather on command from a menu selection.

- <kbd>[</kbd> - Opens a menu selection in relation to [AddItemMenu](https://www.nexusmods.com/skyrimspecialedition/mods/17563) to select certain armors, weapons, or items at will to add to your inventory.

## OStim Standalone

Here are the primary notes:

<kbd>-</kbd> - Long hold press. Starts a scene. A pop-up menu will appear asking if you'd like to add any additional NPCs. Select None if you'd like to initiate a solo scene.

<kbd>Up Arrow</kbd> - While in the navigation menu when a scene has started, this will move your selector upward.

<kbd>Left Arrow</kbd> - While in the navigation menu when a scene has started, this will move your selector to the left.

<kbd>Right Arrow</kbd> - While in the navigation menu when a scene has started, this will move your selector to the right.

<kbd>Down Arrow</kbd> - While in the navigation menu when a scene has started, this will move your selector downward.

<kbd>Y</kbd> - Accepts a selection choice, or "Yes" to a navigation pane (ie. Yes to move to the next animation set).

<kbd>Del</kbd> - Ends a scene. If you're outdoors, the grass may take a moment to reload.

Want to change the default keybind setup for OStim? Images on how to do so are provided under the spoiler.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

To navigation to the control setup of OStim SA, head to the Mod Configuration tab on the pause menu.

![telsera-ostim-menu-navi](https://i.imgur.com/CyERQE1.png)

Once you find the entry titled OStim Standalone, click the Controls tab on the left. Here you'll find all the keybinds for Telsera's setup.

![telsera-ostim-menu-mcm](https://i.imgur.com/tL9fvkR.png)

They are different than OStim SA's default setup, as this is what I'm personally accustomed to, but in the picture above under Navigation Keys, you can tick the checkbox on the bottom right of the MCM to reset the controls to their default state. I realize everyone has their preference when it comes to keybinds, so feel free to change them to whatever is easiest for you!

</details>

## Smaller OStim Navigation Menu

If you find that while in-game the menu screen for OStim's navigation pane is too big for your liking, don't worry, you're in luck! The information under the spoiler below will help.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

Navigate to the mod titled Smaller Scene Menu For OStim Standalone (SEE README) under the Optional Mods section of the list. 

![telsera-smaller-ostim-menu](https://i.imgur.com/XTUqhGZ.png)

You can select that mod entry, right-click it, and then select "Open in Explorer" to see the directory. Find the file titled ui_settings.json, right-click it, and select COPY.

![telsera-smaller-ostim-menu-copy](https://i.imgur.com/ehhznIP.png)

Now we're going to navigate to the paste location. Head to the following: C:\Users\YourName\Documents\My Games\Skyrim Special Edition\OStim\X. You will find a similar file titled the same thing: ui_settings.json. We're going to PASTE the new .json and REPLACE the one in the OStim folder. 

![telsera-smaller-ostim-menu-paste](https://i.imgur.com/b4T2ln4.png)

... and you're done! Next time you go in-game, the menu will be slightly smaller to accomendate viewing better.

</details>

## Character Presets

Telsera includes a mod containing a premade folder structure for character presets that you either create yourself or download from others. You can copy presets you download into the designated folder. 

<details>
  <summary>Spoiler warning - click here to expand.</summary>

The presets mod is here:

![telsera-character-presets](https://i.imgur.com/p6M8AOG.png)

You can select this mod, right-click it, and then select "Open in Explorer" to see the presets directory, which will be at this location:

Example: Telsera\mods\[NoDelete] User-Made Racemenu Presets (SEE README)\SKSE\Plugins\CharGen\Presets\X

![telsera-character-presets-folder](https://i.imgur.com/x1n5llZ.png)

When you make your presets in Racemenu they will be located in the Overwrite folder after you exit the game. 

![telsera-character-overwrite-folder](https://i.imgur.com/wSJ4MIQ.png)

You can select Overwrite, right-click it, and then select "Open in Explorer" to see the presets directory (same location as above in the SKSE folder). Find the file(s) titled insertpresetnamehere.jslot, copy or cut the file, and paste into the [NoDelete] User-Made Racemenu Presets (SEE README)\SKSE\Plugins\CharGen\Presets\X folder. You have now saved your preset, and it will be safe from auto-deletion next time you update the list. The [NoDelete] portion tells Wabbajack to ignore said folder.

</details>

## ENB Settings

If you'd like to make adjustments to the ENB included in Telsera, the keybinds are the following:

<kbd>F11</kbd> - Opens up the ENB menu (press again to close). 
 
NOTE - It's recommended to ALSO PRESS  <kbd>'</kbd> to bring up Skyrim's console as well, so then while you configure your settings in the main menu, your character isn't punching the air everytime you click.

<kbd>;</kbd> - Enables the depth-of-field effect. 

<kbd>F7</kbd> - Enables the FPS overlay effect. 

<kbd>Home</kbd> - Disables the ENB. 
