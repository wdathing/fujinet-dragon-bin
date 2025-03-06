# fujinet-dragon-bin

This is a temporary repo for hold fujinet dragon binaries.
This repo is public, but please don't share it as I cannot support too many testers before it's done.

in the top level is the EPROM image to use, I am not expecting this to change.
the current folder will contain the latest release.
.bin file - firmware for ESP32
.vdk - config tool disk image
fnconfig.ini - sample config file

place the .VDK and the fnconfig.ini in the root of the SD card.  You should pre-edit the ini file to have correct wifi parameters until the config program is fully working on dragon.

coco123-dragon.BIN contains the rom image for all the platforms... use dip switches to choose the image to load.OFF-OFF selects dragon, and this effects the ESP-32 code behaviour, enabling the dragon support.
