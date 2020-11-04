# **Hackintosh-ASUS-A455LB**

Hackintosh **macOS Big Sur 11.0.1 Beta** (20B5012d) | ASUS A455LB | Dual Boot with **Windows 10 Pro**

<img src="img/Screen Shot 2020-11-04 at 7.00.49 PM.png" alt="macOS Big Sur 1" align="center">

---

**Download EFI**

- Terminal : \$ `git clone hhttps://github.com/RidhaAF/Hackintosh-ASUS-A455LB.git`

---

**Specs :**

- **Processor :** Intel Core i5-5200U @2.2GHz up to 2.7Ghz | Broadwell
- **IGPU :** Intel HD Graphics 5500
- **dGPU :** NVIDIA GeForce 940M 2GB
- **RAM :** 8GB DDR3L 1600MHz | @4GB Dual Channel
- **Storage :** SSD 240GB + HDD 1TB
- **Wi-Fi :** Qualcomm Atheros AR9565 and Bluetooth
- **Audio :** Conexant CX20751/2
- **Ethernet :** Realtek RTL8168GU/8111GU
- **Touchpad :** Focaltech PS2 Interface
- **Boot Mode :** UEFI GPT
- **Screen Size :** 14"
- **Display Resolution :** HD (1366 x 768)
- OS **Version :** [macOS Big Sur 11.0.1 Beta (20B5012d)](https://github.com/corpnewt/gibMacOS)
- **Bootloader :** [OpenCore 0.6.3](https://github.com/acidanthera/OpenCorePkg/releases)

---

**Working :**

- QE/CI of Intel HD Graphics 5500 (1536MB) | **ig-platform-id** : 06002616 + SMBIOS MBP12.1 ([Lilu](https://github.com/acidanthera/Lilu/releases), [WhateverGreen](https://github.com/acidanthera/whatevergreen/releases))
- Restart, Sleep and Shutdown
- Internal Speaker, Headphone and Internal Microphone | with layout-id 21 ([AppleALC](https://github.com/acidanthera/applealc/releases), [Lilu](https://github.com/acidanthera/Lilu/releases), SSDT-IRQFix)
- Touchpad with Gestures | (ApplePS2SmartTouchPad)
- Brightness | (SSDT-PNLF)
- FN + Brightness Button Up/Down | ([AsusSMC](https://github.com/hieplpvip/AsusSMC/releases) + DSDT)
- Ethernet | ([RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases))
- Wi-Fi | (AirPortAtheros40, [HS80211Family](https://www.insanelymac.com/forum/files/file/1008-io80211family-modif/))
- Bluetooth | (Turn on in Windows, then restart and boot to macOS)
- HDMI Out
- Battery Indicator | ([VirtualSMC](https://github.com/acidanthera/virtualsmc/releases), SMCBatteryManager)
- All USB Port (USB 3.0, USB 2.0)
- iMessage | (Use Real Serial Number of MacBook Pro)
- Webcam
- Etc..

---

**Not Working :**

- NVIDIA GeForce 940M (NVIDIA Optimus/Switchable is not supported by Hackintosh)
- Etc..

---

**Not Tested :**

- HDMI Audio
- VGA Port
- SD Card Port

---

**BIOS Configuration**

|                  Bios Config                  |       Setting        |
| :-------------------------------------------: | :------------------: |
|            Security -> Secure Boot            |       Disabled       |
|             Intel Virtualization              |       Disabled       |
|                     VT-d                      |       Disabled       |
| Graphics Configuration -> DVMT Pre-Allocation |         64M          |
|    USB Configuration -> XHCI Pre-Boot Mode    | Smart Auto / Enabled |
|                   SATA Mode                   |         AHCI         |
|              Boot -> Launch CSM               |       Disabled       |

---

**Tutorial**

[OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

---

**Special Thanks and Credits to :**

[Apple](https://www.apple.com) | [OpenCore](https://github.com/acidanthera/OpenCorePkg) | [Corpnewt](https://github.com/corpnewt/gibMacOS) | [Acidanthera](https://github.com/acidanthera) | [Rehabman](https://github.com/RehabMan/Laptop-DSDT-Patch) | [Mieze](https://github.com/Mieze/RTL8111_driver_for_OS_X) | [InsanelyMac](https://www.insanelymac.com/forum) | [Andresha](https://github.com/andreszerocross) | <b>and Other Developers</b> who aren't mentioned.

---

<img src="img/Screen Shot 2020-11-04 at 7.01.16 PM.png" alt="macOS Big Sur 2" align="center">

<img src="img/Screen Shot 2020-11-04 at 8.06.30 PM.png" alt="macOS Big Sur 3" align="center">

<img src="img/Screen Shot 2020-11-04 at 8.38.53 PM.png" alt="macOS Big Sur 4" align="center">

<img src="img/Screen Shot 2020-11-04 at 8.10.19 PM.png" alt="macOS Big Sur 5" align="center">

<img src="img/Screen Shot 2020-11-04 at 8.13.34 PM.png" alt="macOS Big Sur 6" align="center">

<img src="img/Screen Shot 2020-11-04 at 8.14.05 PM.png" alt="macOS Big Sur 7" align="center">

<img src="img/Screen Shot 2020-11-04 at 8.15.29 PM.png" alt="macOS Big Sur 8" align="center">
