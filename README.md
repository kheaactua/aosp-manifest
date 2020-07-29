# Overview

Manifest to load changes to AOSP 10.0.0r_9 done during training.

# Usage

```sh
repo init -u https://github.com/kheaactua/aosp-manifest.git -b ioctl --partial-clone
repo sync
```

Running `hidl-gen`.  [Instructions](https://source.android.com/devices/architecture/hidl-cpp)
```
LOC=hardware/interfaces/opersys/2.0/default
PACKAGE=android.hardware.opersys@2.0; LOC=hardware/interfaces/opersys/2.0/default;
hidl-gen -o $LOC -Lc++-impl -randroid.hardware:hardware/interfaces $PACKAGE
```

# Changes

Links below are compare links showing the changes made in training

- [frameworks/base](https://gitlab.com/khea_actua/aosp-frameworks-base/-/compare/android-10.0.0_r9...ioctl): <https://gitlab.com/khea_actua/aosp-frameworks-base/-/compare/android-10.0.0_r9...ioctl>
- [build/make](https://github.com/kheaactua/aosp-build-make/compare/android-10.0.0_r9...ioctl): <https://github.com/kheaactua/aosp-build-make/compare/android-10.0.0_r9...ioctl>
- [device/generic/goldfish](https://github.com/kheaactua/aosp-device-generic-goldfish/compare/android-10.0.0_r9...ioctl): <https://github.com/kheaactua/aosp-device-generic-goldfish/compare/android-10.0.0_r9...ioctl>
- [hardware/interfaces](https://github.com/kheaactua/aosp-hardware-interfaces/compare/android-10.0.0_r9...ioctl): <https://github.com/kheaactua/aosp-hardware-interfaces/compare/android-10.0.0_r9...ioctl>
- [hardware-libhardware](https://github.com/kheaactua/aosp-hardware-libhardware/compare/android-10.0.0_r9...ioctl): <https://github.com/kheaactua/aosp-hardware-libhardware/compare/android-10.0.0_r9...ioctl>
- [system/sepolicy](https://github.com/kheaactua/aosp-system-sepolicy/compare/android-10.0.0_r9...ioctl): <https://github.com/kheaactua/aosp-system-sepolicy/compare/android-10.0.0_r9...ioctl>
