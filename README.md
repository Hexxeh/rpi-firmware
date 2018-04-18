rpi-firmware
============

Firmware files for the Raspberry Pi. These are mirrored in a separate repo from [the official one](https://github.com/raspberrypi/firmware), because for updating the firmware, we're only interested in the files in the boot folder of the official repo. Git doesn't provide a way to clone only a single subfolder of a repo, and downloading the entire repo including the sample code and VC libs would take too long.

If the boot firmware files are split off into a seperate repo, then the tool could be pointed at that repo instead of this one, as long as the firmware files are in the root of the repo.
