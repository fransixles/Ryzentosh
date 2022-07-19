# AMD Ryzen Hackintosh

[![MacOS version](https://img.shields.io/badge/Catalina-10.15.7-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Bigsur-11.6.7-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Monterey-12.5-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Ventura-13.0%20beta3-informational.svg)](https://www.apple.com/macos) \
[![OpenCore version](https://img.shields.io/badge/OpenCore-0.8.2-informational.svg)](https://github.com/acidanthera/OpenCorePkg)\
[![GitHub](https://img.shields.io/github/license/sileshn/Ryzentosh?style=flat-square)](https://github.com/sileshn/Ryzentosh/blob/master/LICENSE)

## Important information
This EFI supports only MacOS versions catalina(10.15) and higher. Your system will not boot if you use this on Mojave and High Sierra.

<a href="https://postimg.cc/WdzvYsny" target="_blank"><img src="https://i.postimg.cc/WdzvYsny/Screenshot-2022-07-13-at-11-29-46-AM.png" alt="Screenshot-2022-07-13-at-11-29-46-AM"/></a> <a href='http://postimg.cc/9rpXNM6K' target='_blank'><img src='https://i.postimg.cc/9rpXNM6K/Screenshot-2022-05-17-at-6.png' border='0' alt='Screenshot-2022-05-17-at-6'/></a> <a href='https://postimg.cc/k6HZtw7T' target='_blank'><img src='https://i.postimg.cc/k6HZtw7T/Screen-Shot-2022-07-13-at-1-46-18-AM.png' border='0' alt='Screen-Shot-2022-07-13-at-1-46-18-AM'/></a> <a href="https://postimg.cc/hzvZ5CWn" target="_blank"><img src="https://i.postimg.cc/hzvZ5CWn/Screenshot-2022-07-12-at-5-51-34-AM.png" alt="Screenshot-2022-07-12-at-5-51-34-AM"/></a>

## Disclaimer
Use at your own risk. I take no responsiblity if your rig explodes. Create unique SMBios values for your rig. Don't copy ones shown in the config.plist!!!

## Specification

| Component        | Model                                              |
| ---------------- | ---------------------------------------------------|
| CPU              | AMD Ryzen 5 3600                                   |
| MotherBoard      | Gigabyte B450 Aorus Elite                          |
| Wifi/Bluetooth   | Asus AX3000 Dual Band PCI-E WiFi 6 / Bluetooth 5.0 |
| OS Disk          | Gigabyte NVME GP-GSM2NE3256GNTD 256gb              |
| RAM              | 4x 8gb Corsair Vengeance Pro 32GB Ram              |
| GPU              | AMD Radeon RX570 4gb                               |
| Cooler    	   | Arctic Freezer A35 A-RGB          		            |

## Working

* iCloud
* Bluetooth
* Ethernet
* Wifi
* iServices & drm

## Not Working ( only ones I have tried, there may be more )

* Sleep ( on Monterey )
* Sidecar

## Patches, Drivers & Kexts

* [AppleALC](https://github.com/acidanthera/AppleALC)
* [AppleMCEReporterDisabler](https://github.com/acidanthera/bugtracker/files/3703498/AppleMCEReporterDisabler.kext.zip)
* [BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM)
* [Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla) ( Newer universal patches introduced in [this](https://github.com/sileshn/Ryzentosh/commit/adcb87fa003a0e77afaded014984a00ecb07b775) commit requires you to update the core count of your processor. For more information on this subject, click [here](https://github.com/AMD-OSX/AMD_Vanilla#read-me-first).)
* [Lilu](https://github.com/acidanthera/Lilu)
* [OpenCore](https://github.com/acidanthera/OpenCorePkg)
* [OpenIntelWireless](https://github.com/OpenIntelWireless)
* [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
* [RestrictEvents](https://github.com/acidanthera/RestrictEvents)
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen)

## Bootloader

I use OpenCore to multiboot Manjaro, Windows(10&11) and MacOS(Catalina, BigSur, Monterey & Ventura)

[![13060127.png](https://i.postimg.cc/nLFcQJvB/13060127.png)](https://postimg.cc/CR2VW9rx)

## Credits and links

* [OpenCore install guide](https://dortania.github.io/OpenCore-Install-Guide)
* [Hackintool](https://www.hackintosh-forum.de/forum/thread/38316-hackintool-ehemals-intel-fb-patcher)
* [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
* [OpenCore-Legacy-Patcher guide](https://dortania.github.io/OpenCore-Legacy-Patcher)
