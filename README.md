# Whitefox-Keyboard
Custom KLL files and DFU.bin file for Whitefox.  

# Summary
This was written using a fork of [kiibohd/controller](https://github.com/kiibohd/controller).  You can see my fork [here](https://github.com/JBonifacio/controller).  This uses the whitefox.bash file provided in this repo.


The KLL files are forked from [kiibohd/kll](https://github.com/kiibohd/kll).  You can see my branch [here](https://github.com/JBonifacio/kll).

# Installing Firmware
You can see all the documentation on the dfu utility [here](https://github.com/kiibohd/controller/wiki/Loading-DFU-Firmware).
1. Install the DFU utility with `brew install dfu-util`.
2. Using the button on the back of the whitefox, set the keyboard on DFU flash mode.
3. Install the firmware with `dfu-util -D kiibohd.dfu.bin`.
