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

# Help

Feel free to hop on the Discord support forum channel, as support is primarily offered in [The Lost Outpost](https://discord.gg/WF66mMu).

**NOTE** - Currently a work-in-progress. My plan is to revamp this entire page into sections (ie. UI, SFW Gameplay, NSFW Gameplay, common install errors, etc.). Please be patient with me in the meantime!

## Frequently Asked Questions - FAQ

### I'm unable to download 'Curios' files when running Wabbajack. What should I do?

1. Navigate to your Steam Skyrim Data folder
2. Within the data folder, delete the 2 curios files "ccbgssse037-curios.bsa" and "ccbgssse037-curios.esl"
3. Launch Skyrim through Steam and click the Creations button on the main menu
4. Find and download the Rare Curios CC files (will have an icon saying "Owned" on it)
5. Exit the game
6. Rerun the Wabbajack installer

### Can I add or remove X, Y, Z mod after I install?

That's up to you, but typically anything outside of enabling/disabling any of the Optional Mods falls under **Wabbajack Rule 11: you will void any help or support given if you run into issues.** 

### Why are NPCs missing their bodies? Missing textures? Chaos??

Did you press the Unlock button via MO2's interface after you launched Telsera? If so, simply exit out of the game, then relaunch. Next time you relaunch, **DO NOT PRESS THE UNLOCK BUTTON**! That completely borks the game! If you didn't press the button, you may need to re-run the Wabbajack installer once again in case the installation process was borked. If you're STILL having issues, please reach out on LostOutpost, Nexus, or the Issues tab here, and we'll see what we can do.

### Can I play the vanilla opening intro scene in this pack?

Yes! Telsera uses <a href="https://www.nexusmods.com/skyrimspecialedition/mods/63953">Optional Quick Start</a> as it's alternative start mod. You have the choice between going through the vanilla intro, or skipping it entirely by starting off near the cave's exit area. You will receive a prompt on if you'd like to escape with Hadvar or Ralof. JUST BEWARE the vanilla intro may be buggy! In my testing it worked fine, but this is Skyrim after all!

### What difficulty is recommended to play Telsera at?

That's completely up to you! **The default is set to Adept**, however, it boils down to your own preference in the end. Steps on how to adjust the difficulty can be found in the <a href="https://github.com/Lost-Outpost/Telsera/blob/main/GAMEPLAY.md#difficulty-and-survival-mode">Gameplay Guide</a> section of the readme!

### What are the controls for OStim in Telsera?

You can find them here in the <a href="https://github.com/Lost-Outpost/Telsera/blob/main/CONFIGURATION.md#OStim-SA-Hotkeys">Configuration Section</a> of the readme.

### My Field Of View (FOV) is now super zoomed in after an OStim scene. How do I fix it?

Open the console via <kbd>'</kbd>. Type the following: <kbd>fov 90</kbd> and you will be set! press <kbd>'</kbd> again to close the console.

### Help! My character's dick has texture mismatching! What do I do?

This can happen if you used the keybind to customize your character's genitals, and you picked one of the "TRX Futanari" options. Unfortunately, as of Telsera's v1.2.0 release and forward, there is no mod to blend the texture setups for **Argonians** and **Khajiit** characters. I did my best to do custom blends for humans and elves, and the seams for those folks should be minimal.

### How to I change the Field Of View (FOV) permanently?

We'll want to double-click the mod, **OStim Improved Camera Configuration - Foamimi's Settings** under the User Interface separator on the left side of MO2. Under the INI Files tab in the pop-up window, in the text box area, scroll down until you see the section with **[FOV]** written. You should see various lines underneath **; Settings for changing fov**. Depending on if you're only changing 1st person, 3rd person, or both, you'll need to change the 90.0 (default) to whatever you prefer. Just note, **you'll have to do these steps for BOTH available ini files**. 

Another thing to keep in mind is if you're using the **Improved Camera Config - FOV 90 for 1stPerson OStim Scenes** mod under the Optional Mods separator, then you'll need to manually adjust those values, instead. 

### Why is my stamina depleting as I jump, sneak, or swim?

That would be caused by the combat mod <a href="https://www.nexusmods.com/skyrimspecialedition/mods/34549">Blade and Blunt</a>. This is a purposeful mechanic to increase the difficulty through resource management and planning. I'd recommend looking over Blade and Blunt's modpage for more information.

### How to I mark my follower as Essential so they don't accidentally die during combat?

In-game, pause, and head to the **MCM for Simple Follower Extension AE**. If you have your follower currently following you (before death lol) then you should be able to click on their name, and set their NPC status from None, to Protected, or to Essential.

### Is there support for ultrawide setups?

No, I'm sorry. :(

### Is there a default config I need to set for using a controller?

If you the pause the game after you've made your character, go under the System tab and click Settings. Be sure to tick the box for controller use. I personally don't have a controller, so I've never played Skyrim with one/have done any testing, so it'll be up to you to navigate the controller binds.
