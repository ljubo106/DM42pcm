## DM42 Persistent Custom Menu firmware mod

DM42 calculator (https://www.swissmicros.com/product/dm42) has dedicated custom menu keys (F-Buttons), however, the default functionality assigned to those keys (help, font manipulation, etc.) is not frequently used. On the other hand, functions, programs or variables assigned to custom keys are accessible only after activation of the custom menu with the Shift-Custom key sequence.

This firmware mod is implementing persistent custom menu, making the custom menu permanently visible and accessible – custom menu logic is inverted – the custom menu is always visible and to temporary exit it one need to press Shift-Custom. 

Download: https://github.com/ljubo106/DM42pcm/releases

See https://www.swissmicros.com for firmware update instructions.

**This firmware mod is neither provided by nor supported by SwissMicros.**

### Firmware mod functionality

* Custom menu is always visible and directly accessible
  * In some rare cases the custom menu will not be displayed - simple press at "Exit" will bring it back
* Shift-CUSTOM activates default DM42 F-Buttons functionality
  * F3 key functionality
    * F3 will start "DM42F3" user program
    * Shift-F3 is toggling the persistent custom menu functionality
* In the Prgm mode Exit will exit the custom menu enabling direct access to the up and down arrows
* Enter DM42 "Setup" / "PCM firmware mod" menu to:
  * Turn PCM funcionality on and off
  * Configure how Shift button is changing perrsistent custom menus


### Code
Project consist of 3 repositories:

* This one to release binaries and keep readme and changelog
* https://github.com/ljubo106/DM42PGM
  * Fork of https://github.com/swissmicros/DM42PGM
* https://github.com/ljubo106/DM42free42
  * Fork of https://github.com/swissmicros/free42
    * Fork of https://github.com/thomasokken/free42

-Ljubo
