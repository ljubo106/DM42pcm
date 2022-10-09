#### 2022-07-04 DM43pcm-3.22.9

- Update to DM42-3.22 / free42 v3.0.15b


#### 2022-07-04 DM43pcm-3.21.9

- Added PCM firmware mode setup menu to turn PCM functionality on/off and to control shift functionality
- Merged number of fixes and improvements from the latest thomasokken/free42 repository
  - Special cases for pure real and pure imag in math_sqrt()
  - More accurate complex ACOS and ACOSH
  - Complex sqrt could have wrong sign in certain cases
  - Latest y^x implementation
  - Fixed Phloat::floor()


#### 2022-01-29 DM42pcm-3.21.8

- Update to DM42-3.21 / free42 v3.0.9


#### 2021-09-04 DM42pcm-3.20.8

- Update to DM42-3.20 / free42 v3.0.5


#### 2021-08-08 DM42pcm-3.20.8b

- Adding RCOMPLX and PCOMPLX from thomasokken repository


#### 2021-07-03 DM42pcm-3.20.8a

- Persistent menu is not shifted if LCLBL is active.
- Alpha release


#### 2021-07-03 DM42pcm-3.20.7b

- Fixed typo in 'L4STK fix' area.
- Beta release


#### 2021-07-03 DM42pcm-3.20.7a

- Merged 'Fixed bug in pivoting logic for complex LU decomposition' and 'L4STK fix' from thomasokken repository
- Alpha release


#### 2021-05-21 DM42pcm-3.19.7

- Fixed crash when pressing shift during show command.


#### 2021-05-16 DM42pcm-3.19.6

- Added F3 key bindings: Plain F3 to start "DM42F3" user program and shift-F3 to toggle the persistent custom menu functionality


#### 2021-05-15 DM42pcm-3.19.5

- Update to DM42-3.19 / free42 v3.0.3


#### 2021-05-01 DM42pcm-3.18.5

- Update to DM42-3.18 / free42 v3.0.2
- exitall is now returning to custom menu
- Improved behavior for alpha menu
- Improved shifted persistent custom menu handling
- Fixed memory leak in parameterized comparisons (taken from https://github.com/thomasokken/free42)


#### 2021-04-07 DM42pcm-3.18b2.4

- Added about screeen to comply with SwissMicros ask - see [SwissMicros "Third
  Party firmware builds" forum description](https://forum.swissmicros.com/viewforum.php?f=15)
- Fixed LNSTK issue (see https://github.com/thomasokken/free42 )
- New version numbering


#### 2021-03-21 DM42-3.17-2.5.20p3

- Fixed issue with flashing garbage text when pressing "EXIT"
- Fixed nasty bug in the new complexpool logic (see
  https://github.com/thomasokken/free42 )


#### 2021-03-21 DM42-3.17-2.5.20p2

- Fixed bug with SHOW function


#### 2021-03-20 DM42-3.17-2.5.20pc

- Added support for (temporary) shifted custom menu
