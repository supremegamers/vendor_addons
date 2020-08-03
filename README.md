# Addons for Project Sakura

This Contains, 
1. LAWNCHAIR
2. OPLAUNCHER Port by Skulshady
3. FOD resources from CrDroid

All credits to the respective teams and ShapeShiftOS for the implementation.

To build OPLauncher instead of Lawnchair you need to set the ```LAWNCHAIR_OPTOUT``` flag to true in your device makefile. Similarly to build the FOD resources you need to add the following flags to your device.mk
```
EXTRA_FOD_ANIMATIONS := true
TARGET_HAS_FOD := true
```
