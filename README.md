![Header](https://github.com/StandartOS/.github/raw/main/standart.svg)

# standartOS Project
a android based on AOSP Pure.

# Getting Started
---------------
To get started with the Stand|artOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

Minimum Build Requirements : Linux OS with 8 core or more and 32 GB RAM (Swap Memory if RAM is not enough).

### Sync source ###
To initialize your local repository, use command:

```bash
repo init --depth=1 -u https://github.com/StandartOS/manifest -b udc_qpr1 --git-lfs
```

Then sync up:

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```

### Build source ###
Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch standart_$devicecodename-buildtype
```

Start compilation

```bash
make bacon
```

### Credits ###
 * [**AOSP**](https://android.googlesource.com)
 * [**AOSPA**](https://github.com/AOSPA)
 * [**CAF**](https://source.codeaurora.org)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**Evolution X**](https://github.com/Evolution-X)
 * [**HentaiOS**](https://github.com/hentaiOS)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**StatixOS**](https://github.com/StatiXOS)
 * [**PixelOS**](https://github.com/PixelOS-AOSP)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**RisingOS**](https://github.com/RisingTechOSS)
 * [**Project Kaleidoscope**](https://github.com/Project-Kaleidoscope)
 
 * And tons of other ROMs not mentioned above