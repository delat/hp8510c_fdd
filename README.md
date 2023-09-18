# HP8510C FDD Image Repository

Welcome to the HP8510C FDD Image Repository! This repository is dedicated to preserving and sharing FDD (Floppy Disk Drive) images tailored for the HP8510C, a remarkable vintage machine that continues to serve its users.

## Description

This repository is dedicated to the storage of FDD (Floppy Disk Drive) images specifically designed for the HP8510C, a robust but aging machine. The HP8510C relies on a 3.5" floppy drive for the retrieval and storage of results and firmware. While it can work with MSDOS-formatted floppies for data, firmware updates require the use of LIF-formatted floppies. In the modern era, obtaining and using traditional 3.5" floppies can be highly inconvenient, given their scarcity and the rarity of PCs equipped with floppy disk drives. Even USB FDD drives often lack support for custom FDD formats like LIF, which are essential for the HP8510C.

Consequently, the most practical way to operate the HP8510C is by installing an FDD emulator equipped with a USB drive. Personally, I have found the GoTek 435 with an OLED screen to be an good choice for this purpose.

## Getting Started

1. Install GOTEK FDD emulator instead of the original FDD drive.
2. (Optionally) Update firmware of your FDD emulator to the lasted or tested from the [section](#tested-configuration).
3. Format your USB drive to FAT32 for compatibility with FDD emulator.
4. Copy all files from the repository to the USB drive and install it the emulator.
5. You can select the proper FDD image using the FDD emulator knob.

## Firmware installation

1. If you have runned firmware you need to exit to the monitor. Press: [SYSTEM] -> [MORE] -> [SERVICE FUNCTION] -> [TEST MENU]
2. In monitor main screen enter: 19 -> [=MARKER]
3. Using arrow keys select the proper firmware file.
4. To load firmware press [LOAD FILE]
5. Wait for file loading.
6. Unit will restart and run the new firmware after the finishing.

## Tested configuration

* This files tested with GoTek 435 emulator with [FlashFloppy](https://github.com/keirf/flashfloppy) firmware v3.41
* HP 8510C Monitor C.02.16

## FDD images

| Image file name | Description | Format |
| --------- | ----------- | ------ |
| PG_8510C.hfe | Contains two VNA firmware: v6.54 and v7.16 | LIF |
| PG_8530A.hfe | Contains two receiver firmware: v1.64 and v1.66 | LIF |

## LIF FDD format used by HP8510C

* Modulation: MFM
* Number of track: 80
* Number os side: 2
* Sector per track: 32
* Sector ID start: 1
* Interleave: 1
* Skew: 0
* Sector size: 256
* Bitrate: 500kBit/s
* RPM: 300

## Contributing

I welcome contributions from the HP8510C community. If you have FDD images, other firmware, or useful tips and tricks to share, please feel free to submit your contributions. Together, we can ensure the HP8510C continues to thrive in the modern era.

## Firmware Copyright Notice

**Important**: Firmware images provided in this repository are the intellectual property of Keysight Technologies (formerly Agilent Technologies, formerly Hewlett-Packard) or their respective copyright holders. They are made available here solely for the purpose of preserving and facilitating the use of HP8510C machines, and their use should strictly adhere to applicable copyright laws.

* Firmware images contained in this repository are provided with the understanding that they will only be used with legally obtained HP8510C devices.

* Users are responsible for ensuring that their use of Keysight firmware images complies with Keysight Technologies' terms of use and copyright policies.

* Redistribution, commercial use, or any other activities that infringe upon Keysight's copyrights are strictly prohibited.

By downloading or using firmware images from this repository, you acknowledge and agree to respect Keysight Technologies' intellectual property rights and adhere to all relevant copyright laws and regulations.

**Notice**: If you believe that any content in this repository violates copyright laws or Keysight Technologies' terms of use, please notify me immediately. I am committed to promptly addressing any violations and taking appropriate actions, including the removal of infringing content.

Please note that this repository and its maintainers do not assume any liability for the misuse of firmware images or any legal consequences resulting from their use.
