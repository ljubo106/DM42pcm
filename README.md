## DM42 Persistent Custom Menu firmware mod

Slightly changed Free42 code making the custom menu the system base menu.
For DM42 that behavior makes sense as DM42 has dedicated custom keys - for
me this change greatly increases usability of the DM42.

Download: https://github.com/ljubo106/DM42pcm/releases

See https://www.swissmicros.com for firmware update instructions.

**This firmware mod is neither provided by nor supported by SwissMicros.**

### Firmware mod functionality

* Custom menu is the base menu - custom commands are (almost) always directly accessible
  * In some cases custom menu will not be displayed - simple press at "Exit" will bring it back
* Shift is temporary switching to the "upper" custom menu - those commands are just an additional click away
* Shift-CUSTOM activates default DM42 F-Button functionality (also making possible to turn persistent custom menu off)
* In the Prgm mode Exit will exit custom menu - makes easy to access up and down arrows
* Entering other menus will of course exit Custom menu
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
