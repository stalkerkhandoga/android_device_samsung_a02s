# Samsung Galaxy A02s 

 - SM-A025G
 - A02qnaeea
 - armv8l
 - 32-bit Arm Binder64

Qualcomm Snapdragon 450 SDM450
 - AArch64 
 - 8 Cores
 - 4x 1.80GHz  Cortex-A53
 - 4x 1.80GHz   Cortex-A53

Qualcomm Adreno506 GPU, 
3GB RAM, 
4900MAH Battery, 
Dual Sim, 
NFC, 
32GB internal storage, 
Upto 1TB Micro SD. 

## RECOVERY DEVICE TREE

Device tree initially created via [TWRPDTG](https://github.com/SebaUbuntu/TWRP-device-tree-generator) 
With some big Samsung related edits thanks to [mohammad92's A11 Device Tree](https://github.com/JustForkin/android_device_samsung_a11q) 

## TWRP BUILD

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_a02q-eng
make recoveryimage
```
