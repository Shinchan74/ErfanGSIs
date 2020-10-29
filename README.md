# ErfanGSIs Tool - Hitsuki Edition

This repository is a fork of the ErfanGSIs Tool with numerous changes/improvements!

Find GSIs made using this tool on the Telegram channel [@TrebleExperience](https://t.me/TrebleExperience)

### How to download

```bash
git clone --recurse-submodules https://github.com/Treble-Experience/ErfanGSIs-Hitsuki.git ErfanGSIs 
cd ErfanGSIs
```

### Setting up requirements

```bash
bash setup.sh
```

## Usage

```bash
./url2GSI.sh <Firmware link> <Firmware type> [Other args]
[--help|-h|-?] [--ab|-b] [--aonly|-a] [--mounted|-m] [--cleanup|-c]
        Firmware link: Firmware download link or local path
        Firmware type: Firmware mode
        --ab: Build only AB
        --aonly: Build only A-Only
        --cleanup: Cleanup downloaded firmware
        --help: To show this info
```

### Supported firmware types

```bash
Supported types on Android 9:
Nubia, Moto, OneUI, MIUI, OxygenOS, ZenUI, Generic, Flyme, Pixel, ColorOS, ZUI, Xperia, RazerUI, VOS, RogUI

Supported types on Android 10:
MIUI, OxygenOS, Generic, Pixel, JoyUI, Moto, ZenUI, ZUI, Flyme, ColorOS, VOS, OneUI, RogUI, Nubia

Supported types on Android 11:
Generic, Pixel, MIUI, OxygenOS, OneUI
```
