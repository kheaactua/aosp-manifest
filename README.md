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
