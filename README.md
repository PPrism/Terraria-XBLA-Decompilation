# **---COMING SOON---**
# **PLEASE SUPPORT THE OFFICIAL RELEASES OF TERRARIA**
+ Without assets from the official 'old-gen' console releases, this decompilation project will not run.

+ You can get the official release of Terraria with content compatible with this project from:
  * [Xbox Marketplace (X360 Version)](https://marketplace.xbox.com/Product/Terraria-Xbox-360-Edition/66acd000-77fe-1000-9115-d8025841128f)
  * [PlayStation Store (PS3 Version)](https://store.playstation.com/en-au/product/EP4040-NPEB01270_00-TERRARIA00000002)
  * *Yea its been discontinued in most places due to its age, but still try and get either the physical or digital Xbox 360 or PS3 releases.*
+ You can also support the devs in today's age by buying the other releases or their merchandise from:
  * [The Terraria Website](https://terraria.org/store)

Despite being based on the XBLA version, either 'old-gen' console version published by 505 Games (including initial versions for the PS4/XBOne) will work, but you **must** buy or officially download it for the assets.

## **DO NOT USE THIS PROJECT AS A MEANS TO PIRATE TERRARIA.**
This project is not intended to act as a free substitute for the official versions of Terraria; This project was made with love and care for the source material and was created for purely educational purposes, and would not exist without the work of the marvelous people at Re-Logic, 505 Games, and Engine Software.

If you want to transfer your save from the official Xbox 360 versions, as long as the version is in alignment, you should be able to drop it in the SavedGames folder once extracted!

# Additional Enhancements
* Ability to run all released milestone versions of the game. Including: **1.00** (Console initial release), **1.01** (Console Improvement of PC 1.1.2), **1.03** (Console Improvement of PC 1.2.1.2) & **1.09** (Final 'Old-gen' update / Console Improvement of PC 1.2.4.1).
* Added variable screen sizing and other user options.
  * Included are some optional gameplay tweaks (Toggleable by the Settings.ini file).
  * This also includes the re-implementation of some debug gameplay features (FPS Counter, 'Always active' GPS features)
* Added an achievement system built off the original version.
* World Backups; Just a precaution for playing versions which could have the worlds become filled with dirt upon save corruption.
* Codebase is now built on a hybrid of FNA and MonoGame, with base networking provided by Lidgren.Network.
* If you were fortunate enough to buy the PC Collector's Edition of the game back when it was being sold and installed it on the system that you play the decompilation on, new characters will be given some cabbage :)
* Care has been taken to ensure that if provided the XNA framework (Made for the Xbox 360), the auxillary XNA.XDK dependency, and an Xbox 360 Development Kit, you should still be able to run the initial version's code without too much hassle.

# How to Build
* See the instructions I have made [here](https://github.com/PPrism/Terraria-XBLA-Decompilation/blob/main/)
* For compilation, some configuration symbols are available upon building with Visual Studio 2022.

## List of configuration symbols
* `USE_ORIGINAL_CODE`: *This requires an official Xbox 360 SDK.* If defined, the code will function on an official XDK setup. No additions are available if this is defined and only the initial version will be playable.
* `VERSION_INITIAL`: Whether or not to build the first release of Terraria on the Xbox 360. This is the closest equivalent to Version 1.1.2 for the PC version.
* `VERSION_101`: Whether or not to build the 1.01 release of Terraria on the Xbox 360. This is akin to Version 1.1.2 for the PC version, but with some new and PC version 1.2 additions.
* `VERSION_103`: Whether or not to build the 1.03 release of Terraria on the Xbox 360. This is the closest equivalent to Version 1.2.1.2 for the PC version.
* `VERSION_FINAL`: Whether or not to build the final release (1.09) of Terraria on the Xbox 360. This is the closest equivalent to Version 1.2.4.1 for the PC version.
* `IS_PATCHED`: Whether or not to enable the patch to fix a world generation bug and applies some back-end changes. Only applicable if `VERSION_INITIAL` is defined. Be warned, as without the patch, end-game armor can spawn in gold chests.

# FAQ
### Q: What to do if I have a suggestion/bug report/improvement for the project? 
A: Feel free to make an issue or pull request, and I'll review it as soon as I can.

### Q: Why does the game start in Trial Mode? How do I disable it?
A: It's just a little thing for some legal protection and to not promote piracy. I didn't make this project so it would straight-up give the full game on install by default. You can change it in the settings file.

### Q: How do I change the username used?
A: In the `Game` category of the Settings.ini file, change the value attached to the `Gamertag` key to whatever username you want.

### Q: How do I exit or enter full-screen mode?
A: Press 'F' on the keyboard at any time following the Engine Software logo to go into full-screen. You can also start-up in full-screen by turning on the respective setting in the Settings.ini file.

### Q: Only the 1.1 releases are playable, how do I get the 1.2 content?
A: 1.03 and 1.09 (1.2 versions) content will come in a later update to the decompilation due to the data being more complex to recreate/decompile. Stay tuned!

### Q: How can I contact you for some urgent reason? 
A: Got details on my profile page.
