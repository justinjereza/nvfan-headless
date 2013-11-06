NVFAN-HEADLESS
==============

This script provides manual fan control for nVidia video cards on headless Linux machines. It has been tested on Debian 7 (wheezy) using v319.37 nVidia drivers. By default, it expects the nvfan-headless, xorg.conf, and default-edid.bin (EDID of a Dell U2410 monitor) files to be located in /opt/nvfan-headless.

Executing nvfan-headless without any parameters will set the fan speed to 75%. Running it as "nvfan-headless 85" will set the fan speed to 85%. Running "nvfan-headless stop" will disable manual speed control and print GPU status.

DEPENDENCIES
------------
* xinit
* libgtk2.0-0

ACKNOWLEDGEMENTS
----------------
This script is inspired by a script written by Axel Kohlmeyer documented at https://sites.google.com/site/akohlmey/random-hacks/nvidia-gpu-coolness.