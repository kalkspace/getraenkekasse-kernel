# Getraenkekasse Kernel

Unfortunately a special kernel is needed (and no - DKMS is not enough) to make the touchscreen work.

This enables the touchscreen module and adds configuration for the touchscreen.
During boot it will require additional firmware.

## Firmware

The firmware can be found here: https://github.com/m0ppers/gsl-firmware/tree/saphir-winpad-10-1/firmware/saphir/winpad_10_1

`firmware.fw` should be copied to `/lib/firmware/silead/gsl1680-saphir-media-winpad-10.fw` on the tablet.
