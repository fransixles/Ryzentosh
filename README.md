# AMD Ryzen Hackintosh

[![MacOS version](https://img.shields.io/badge/macOS-10.15.7%2019H1311-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/macOS-11.5%20Beta%2020G5033c-informational.svg)](https://www.apple.com/macos)\
[![OpenCore version](https://img.shields.io/badge/OpenCore-0.7.0-informational.svg)](https://github.com/acidanthera/OpenCorePkg)\
[![GitHub](https://img.shields.io/github/license/sileshn/Ryzentosh?style=flat-square)](https://github.com/sileshn/Ryzentosh/blob/master/LICENSE)

# Disclaimer
Use at your own risk. I take no responsiblity if your rig explodes. Create unique SMBios values for your rig. Don't copy ones shown in the config.plist!!!

[![Screenshot-2021-06-03-at-7-14-20-AM.png](https://i.postimg.cc/Y0ZT6B4k/Screenshot-2021-06-03-at-7-14-20-AM.png)](https://postimg.cc/N28NtV7P) [![Screenshot-2021-06-17-at-2-35-03-PM.png](https://i.postimg.cc/02g5H5G1/Screenshot-2021-06-17-at-2-35-03-PM.png)](https://postimg.cc/Sjrpnhtg)

## Specification

| Component        | Model                                  |
| ---------------- | -------------------------------------- |
| CPU              | AMD Ryzen 7 2700                       |
| MotherBoard      | MSI Pro VDH Max                        |
| OS Disk          | Kingston 240gb SSD                     |
| RAM              | 2x 8gb Corsair Vengeance Pro 16GB Ram  |
| GPU              | Nvidia GT710 2gb                       |
| Cooler    	     | Cooler master hyper 410r               |

## Working

* iCloud
* Bluetooth
* Ethernet
* Wifi
* iServices

## Not Working ( only ones I have tried, there may be more )

* Drm related stuff ( Apple TV )

## Patches, Drivers & Kexts

* [Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla)
* [OpenRuntime](https://github.com/acidanthera/OpenCorePkg)
* [OpenCanopy](https://github.com/acidanthera/OpenCorePkg)
* [OpenHfsPlus](https://github.com/acidanthera/OpenCorePkg) 
* [Lilu](https://github.com/acidanthera/Lilu)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
* [AppleALC](https://github.com/acidanthera/AppleALC)
* [AppleMCEReporterDisabler](https://github.com/acidanthera/OpenCorePkg)
* [AirportBrcmFixup](https://github.com/acidanthera/airportbrcmfixup/releases)
* [BrcmFirmwareData](https://github.com/acidanthera/BrcmPatchRAM)
* [BrcmPatchRAM3](https://github.com/acidanthera/BrcmPatchRAM)
* [BrcmBluetoothInjector](https://github.com/acidanthera/BrcmPatchRAM)
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
* [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
* [RestrictEvents](https://github.com/acidanthera/RestrictEvents)

## Bootloader

I use OpenCore to triple boot Manjaro, Windows10 and MacOSX.

[![13114808.png](https://i.postimg.cc/KvSKv6bG/13114808.png)](https://postimg.cc/Dm6fxYmH)

## Credits and links

* [OpenCore Desktop Guide](https://github.com/dortania/OpenCore-Desktop-Guide)
* [Hackintool](https://www.hackintosh-forum.de/forum/thread/38316-hackintool-ehemals-intel-fb-patcher/)
* [OC Builder](https://github.com/Pavo-IM/ocbuilder)
* [OC Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/)
