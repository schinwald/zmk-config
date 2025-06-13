# ZMK Configuration

### Instructions

1. Use the zmk keymap editor to create a keymap for your keyboard and hit save (this will trigger a build in ci/cd)
2. After the build is complete, download the latest artifact from the actions tab
3. Double click the reset button on your left keyboard (a blue light _should_ be flashing on the nice!nano)
4. Plug your left keyboard into your computer and a firmware folder should open automatically
5. Open the artifact and move the left UF2 file into your keyboard's firmware folder (this should flash the firmware on the keyboard and eject the drive)
6. Unplug your left keyboard
7. Double click the reset button on your right keyboard (a blue lights _should_ be flashing on the nice!nano)
8. Plug your right keyboard into your computer and a firmware folder should open automatically
9. Open the artifact and move the right UF2 file into your keyboard's firmware folder (this should flash the firmware on the keyboard and eject the drive)

Done! :tada:

> This should update your keyboard with the latest firmware
