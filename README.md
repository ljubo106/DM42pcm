[![Latest Release](http://img.shields.io/github/release/ljubo106/DM42pcm?label=download)](http://github.com/ljubo106/DM42pcm/releases)
[![GitHub release (by tag)](https://img.shields.io/github/downloads/ljubo106/DM42pcm/DM42pcm-3.23.9/total?label=downloads%20v3.23.9)](http://github.com/ljubo106/DM42pcm/releases)
[![GitHub Downloads](http://img.shields.io/github/downloads/ljubo106/DM42pcm/total?label=downloads)](http://github.com/ljubo106/DM42pcm/releases)


## DM42 Persistent Custom Menu firmware mod

The DM42 calculator (https://www.swissmicros.com/product/dm42) features dedicated custom menu keys (F-Buttons). However, the default functions assigned to these keys (such as help and font manipulation) are not frequently used. In contrast, functions, programs, or variables assigned to custom keys are only accessible after activating the custom menu with the Shift-Custom key sequence.

This firmware mod implements a persistent custom menu, making it permanently visible and accessible. The custom menu logic is inverted, so the custom menu is always visible. To temporarily exit it, you need to press Shift-Custom.

Download: https://github.com/ljubo106/DM42pcm/releases

For firmware update instructions, visit https://www.swissmicros.com

**This firmware mod is neither provided by nor supported by SwissMicros.**


### Firmware mod functionality

* The custom menu is always visible and directly accessible
  * In rare cases where the custom menu is not displayed, simply press “Exit” to bring it back
* Shift-CUSTOM activates the default DM42 F-Buttons functionality
  * F3 key functionality:
    * F3 starts the “DM42F3” user program
    * Shift-F3 toggles the persistent custom menu functionality
* In Prgm mode, pressing Exit will exit the custom menu, enabling direct access to the up and down arrows
* Enter the DM42 “Setup” / “PCM firmware mod” menu to:
  * Turn PCM functionality on and off
  * Configure how the Shift button changes persistent custom menus


### Code

Project consist of 3 repositories:

* This one to release binaries and keep readme and changelog
* https://github.com/ljubo106/DM42PGM
  * Fork of https://github.com/swissmicros/DM42PGM
* https://github.com/ljubo106/DM42free42
  * Fork of https://github.com/swissmicros/free42
    * Fork of https://github.com/thomasokken/free42


-Ljubo
