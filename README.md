## DM42 Persistent Custom Menu firmware mod

DM42 calculator (https://www.swissmicros.com/product/dm42) has dedicated custom keys, however, the default functionality assigned to those keys (help, font manipulation, etc.) is not frequently used. On the other hand, user assigned functions are usually frequently needed but accessible only after activation of the custom menu with Shift-Custom key.

This firmware mod is implementing the persistent custom menu, making the custom menu permanently visible and accessible – the custom menu logic is inverted – custom menu is always visible and to temporarily exit it one need to press Shift-Custom. 

Download: https://github.com/ljubo106/DM42pcm/releases

See https://www.swissmicros.com for firmware update instructions.

**This firmware mod is neither provided by nor supported by SwissMicros.**

### Firmware mod functionality

* Custom commands are (almost) always directly accessible
  * In some cases custom menu will not be displayed - simple press at "Exit" will bring it back
* Shift is temporary switching to the "upper" custom menu - those commands are just an additional click away
* In the Prgm mode Exit will exit custom menu making access to up and down arrows easy
* Shift-CUSTOM activates default DM42 F-Buttons functionality (also making possible to turn persistent custom menu functionality off)
* F3 key functionality
  * F3 will start "DM42F3" user program
  * Shift-F3 is toggling persistent custom menu functionality

### Code
Project consist of 3 repositories:

* This one to release binaries and keep readme and changelog
* https://github.com/ljubo106/DM42PGM
  * Fork of https://github.com/swissmicros/DM42PGM
* https://github.com/ljubo106/free42
  * Fork of https://github.com/swissmicros/free42
    * Fork of https://github.com/thomasokken/free42

-Ljubo
