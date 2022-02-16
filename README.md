# Monterey Gigabyte Z390 Aorus Master (OpenCore)

[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.8-blue.svg)](https://github.com/acidanthera/OpenCorePkg)
[![macOS-Stable](https://img.shields.io/badge/macOS-12.2.1-brightgreen.svg)](https://www.apple.com/macos/monterey)

![image](https://user-images.githubusercontent.com/3669931/154285639-4ccde821-0cf5-4f2f-aa5a-8cdb15ae88c2.png)



## My PC Build
<details>
  <summary><strong>Hardware</strong></summary>
  
  | Category          | Component                                                | Note                                                  |
  | ----------------- | -------------------------------------------------------  | ----------------------------------------------------- |
  | CPU               | Intel Core i9-9900K                                      |                                                       |
  | GPU               | Gigabyte Radeon RX 6900 XT Master GPU                    | Native support                                        |
  | Motherboard       | Gigabyte Z390 AORUS MASTER                               |                                                       |
  | Storage (macOS)   | Samsung 970 PRO SSD 512GB NVMe(`M2M` slot)               | Internal NVME                                         |
  | Storage (Windows) | Samsung 960 PRO SSD 512GB NVMe(`M2A` slot)               | Internal NVME                                         |
  | Memory            | GSkill F4-3200C14-16GTZR (4x16GB) 3600MHz CL14 DDR4      |                                                       |
  | CPU Cooler        | NZXT Kraken X73                                          |                                                       |
  | Power Supply      | Corsair RMX Series 80PLUS Gold 850W                      |                                                       |
  | Case              | NZXT S340 Red Cases                                      |                                                       |
  | Monitor           | Gigabyte 34 UWQHD Display Monitor G34WQC                 |                                                       |
  | LAN               | Intel® i219v GbE LAN                                     | I use LAN for network                                 |
  | Wifi & BT         | Intel® CNVi 802.11ac 2x2 Wave 2 WIFI & BT5  (on-board)   | I just use bluetooth for LG Speaker.                  |
  |                   | Include **Intel Wireless-AC 9560** module inside         |                                                       |
  |                   |                                                          |                                                       |
  |                   |                                                          |                                                       |
  
</details>

<details>

<summary><strong>Kernel extensions</strong></summary>
<br>

| Kext                   | Version        |
|:---------------------- | -------------- |
| Lilu                   | 1.6.0          |
| VirtualSMC             | 1.2.8          |
| WhateverGreen          | 1.5.7          |
| AppleALC               | 1.6.9          |
| IntelBluetoothFirmware | 2.1.0          |
| IntelMausi             | 1.0.7          |
| SMCProcessor           | 1.2.8          |
| SMCSuperIO             | 1.2.8          |
| USBPorts               | Manual         |
| Airportitlwm           | 2.1.0          |
| BlueToolFixup          | 2.6.1          |
| RadeonSensor           | 0.3.1          |


</details>

<details>
  <summary><strong>Working ✅ / Not Working ☑️</strong></summary>
  
  * ✅ Ethernet
  * ✅ Onboard Audio
  * ✅ iMessage
  * ✅ Sleep/Wake
  * ✅ Bluetooth & Wi-Fi
  * ☑️ Airdrop
  * ☑️ Handoff
  
</details>

# Resources

* [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
* [Wifi-Bluetooth](https://openintelwireless.github.io/General/Installation.html)
* [Dortania build-repo](https://github.com/dortania/build-repo/releases)

# Tools
* [Hackintool](https://github.com/headkaze/Hackintool)
* [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/)
* [Wifi-Bluetooth kext](https://github.com/OpenIntelWireless)

# Thanks
* Hanam824 - (https://github.com/Hanam824/Gigabyte-Z390-Aorus-Master-Hackintosh)
