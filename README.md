# SHRP device tree for Samsung S10e aka beyond0lte

## Kernel source 
Available at https://github.com/corsicanu/android_kernel_samsung_universal9820

## How to build
1. Set up the build environment following instructions from [here](https://shrp.github.io/#/guide?id=build-shrp)
2. In the root folder of cloned repo you need to clone the device tree:
```bash
git clone -b android-9.0 https://github.com/SHRP-Devices/android_device_samsung_beyond0lte.git device/samsung/beyond0lte
```
3. To build:
```bash
export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_beyond0lte-eng && mka recoveryimage -j128
```

