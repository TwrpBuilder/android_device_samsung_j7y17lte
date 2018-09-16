# TWRP device tree for Samsung J7 2017 aka j7y17lte
Kernel source available at 
https://github.com/ananjaser1211/Helios_7870
```
export CROSS_COMPILE=../toolchains/aarch64-linux-android-4.9/bin/aarch64-linux-android-
make clean

export ARCH=arm64
export ANDROID_MAJOR_VERSION=o
export LOCALVERSION=-twrp

make ARCH=arm64 j7y17lte_eur_open_defconfig
make ARCH=arm64 -j128
```
