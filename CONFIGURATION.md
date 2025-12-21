<img src="https://i.imgur.com/kW90Y5Y.png" target="_blank">

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/149944">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="PAGEFILE.md">Pagefile Setup</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="HELP.md">Help</a>
</p>

---

# Configuration

- [Hotkeys](#Hotkeys)
- [OStim SA Hotkeys](#OStim-SA-Hotkeys)
- [ENB Settings](#ENB-Settings)
- [Smaller OStim Navigation Menu](#Smaller-OStim-Navigation-Menu)
- [OStim in 1stPerson](#ostim-in-1stperson)
- [High Poly Head Setup](#High-Poly-Head-Setup)
- [Character Presets](#Character-Presets)

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

## OStim SA Hotkeys

Here are the primary notes:

<kbd>directional up arrow</kbd> - Long hold press. Starts a scene. A pop-up menu will appear asking if you'd like to add any additional NPCs. Select None if you'd like to initiate a solo scene.

<kbd>Numpad8</kbd> - While in the navigation menu when a scene has started, this will move your selector upward.

<kbd>Numpad4</kbd> - While in the navigation menu when a scene has started, this will move your selector to the left.

<kbd>Numpad6</kbd> - While in the navigation menu when a scene has started, this will move your selector to the right.

<kbd>Numpad5</kbd> - While in the navigation menu when a scene has started, this will move your selector downward.

<kbd>Numpad7</kbd> - Accepts a selection choice, or "Yes" to a navigation pane (ie. Yes to move to the next animation set).

<kbd>NumpadPeriod</kbd> - Ends a scene. If you're outdoors, the grass may take a moment to reload.

<kbd>Numpad/</kbd> or <kbd>MouseScrollWheel</kbd> - Swaps player perspective from 3rdPerson to 1stPerson (or vice-versa).

Want to change the default keybind setup for OStim? Images on how to do so are provided under the spoiler.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

To navigation to the control setup of OStim SA, head to the Mod Configuration tab on the pause menu.

![telsera-ostim-menu-navi](https://i.imgur.com/CyERQE1.png)

Once you find the entry titled OStim Standalone, click the Controls tab on the left. Here you'll find all the keybinds for Telsera's setup.

![telsera-ostim-menu-mcm](https://i.imgur.com/tL9fvkR.png)

The keybinds in the images above are different than OStim SA's default setup, just a heads up. I changed mine, and I realize everyone has their preference when it comes to keybinds, so feel free to change them to whatever is easiest for you. 

</details>

## ENB Settings

If you'd like to make adjustments to the ENB included in Telsera, the keybinds are the following:

<kbd>F11</kbd> - Opens up the ENB menu (press again to close). 
 
NOTE - It's recommended to ALSO PRESS  <kbd>'</kbd> to bring up Skyrim's console as well, so then while you configure your settings in the main menu, your character isn't punching the air everytime you click.

<kbd>;</kbd> - Enables the depth-of-field effect. 

<kbd>F7</kbd> - Enables the FPS overlay effect. 

<kbd>Home</kbd> - Disables the ENB. 

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

## OStim in 1stPerson

Telsera uses [Improved Camera](https://www.nexusmods.com/skyrimspecialedition/mods/93962), which allows for various 3rdPerson actions to be performed from the 1stPerson perspective. As mentioned earlier in the guide, 1stPerson can be accessed via <kbd>Numpad/</kbd> or <kbd>MouseScrollWheel</kbd> during OStim scenes. 

Under the Optional Mods category in Telsera's instance of MO2, there's a file titled **"Improved Camera Config - FOV 90 for 1stPerson OStim Scenes (SEE README)"** that is turned OFF by default. This file basically locks the field-of-view at 90 while you play, so you're able to experience intimacy scenes in 1stPerson with better viewing pleasure. The downside to this is that it'll be LOCKED at 90, so if you go to manually change your field-of-view via the console or whatnot after you end a scene, it'll snap back to 90 until you set the file back to disabled.

If you plan on experimenting with OStim scenes in 1stPerson, or don't mind the restriction lock, feel free to enable the optional config file at any time. If you change your mind later on, it'll be safe to disable mid-playthrough. Flexibility is key!

## High Poly Head Setup

As of version 2.0.0, Telsera now contains the mod, High Poly Head. It will **not be automatically applied** to your character, as there's **a slider you need to move during character creation, first!** The steps to do so can be found in the spoiler below.

<details>
  <summary>Spoiler warning - click here to expand.</summary>

Once you go into Racemenu during character creation, you'll notice a search bar up at the top left-ish side. Type, "**facepart**" without quotations, and a single slider should appear. 

- insert image here WIP -

Using your cursor, drag the slider to the **right**, and boom, your character will now have a High Poly Head! To exit the search functionality, clear the searchbar via backspace once you've selected the box with the facepart text.

- insert image here WIP -

</details>

**BONUS** - There are several mods titled, "For HPH - Unplayable Facial Parts - xyz" under the Optional mods separator. Tick those boxes to enable them before you go in-game **if you are going to High Poly Head on your player character**. They are handy, ease of creation mods that will remove the various excess low poly vanilla headparts, such as brows and scars, from being visible in Racemenu. You will **still need to move the facepart slider over** to enable High Poly Head! I'm hoping in the future I can automate the process, but in the meantime, here we are...

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
