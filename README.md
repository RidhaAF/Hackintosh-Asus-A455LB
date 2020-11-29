# **Hackintosh-Asus-A455LB**

Hackintosh **macOS Big Sur 11.0.1** (20B29) | **Asus A455LB** | Dual Boot with **Windows 10 Pro** 20H2

## <img src="img/Screen Shot 2020-11-29 at 7.58.01 AM.png" align="center">

---

**Download EFI**

- via Terminal : \$ `git clone https://github.com/RidhaAF/Hackintosh-Asus-A455LB.git` or [Click Here](https://github.com/RidhaAF/Hackintosh-Asus-A455LB/archive/master.zip)

---

**Specs :**

- **Processor :** Intel Core i5-5200U @2.2GHz up to 2.7Ghz | Broadwell
- **iGPU :** Intel HD Graphics 5500
- **dGPU :** NVIDIA GeForce 940M 2GB
- **RAM :** 8GB DDR3L 1600MHz | @4GB Dual Channel
- **Storage :** Apacer AS340 PANTHER 240GB SATA III SSD + HDD 1TB
- **Wi-Fi :** Qualcomm Atheros AR9565 and Bluetooth
- **Audio :** Conexant CX20751/2
- **Ethernet :** Realtek RTL8111GU
- **Touchpad :** Focaltech PS2 Interface
- **Boot Mode :** UEFI GPT
- **Screen Size :** 14"
- **Display Resolution :** HD (1366 x 768)
- **External Monitor Screen Size :** 22"
- **Display Resolution :** FHD (1920 x 1080)
- **OS Version :** [macOS Big Sur 11.0.1 (20B29)](https://github.com/corpnewt/gibMacOS)
- **Bootloader :** [OpenCore 0.6.3](https://github.com/acidanthera/OpenCorePkg/releases)

---

**Working :**

- QE/CI of Intel HD Graphics 5500 (1536MB) | **ig-platform-id** : 06002616 + SMBIOS MBP12,1 ([Lilu](https://github.com/acidanthera/Lilu/releases), [WhateverGreen](https://github.com/acidanthera/whatevergreen/releases))
- CPU Power Management (SSDT-PLUG)
- Restart, Sleep and Shutdown
- Internal Speaker, Headphone and Internal Microphone | with layout-id 21 ([AppleALC](https://github.com/acidanthera/applealc/releases), [Lilu](https://github.com/acidanthera/Lilu/releases), SSDT-IRQFix)
- Touchpad with Gestures | (ApplePS2SmartTouchPad)
- Brightness | (SSDT-PNLF)
- FN + Brightness Button Up/Down | ([AsusSMC](https://github.com/hieplpvip/AsusSMC/releases) + DSDT)
- Ethernet | ([RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases))
- Wi-Fi | (AirPortAtheros40, [HS80211Family](https://www.insanelymac.com/forum/files/file/1008-io80211family-modif/))
- Bluetooth | (Turn on in Windows setting, then restart and boot to macOS)
- HDMI Out (Video)
- Battery Indicator | ([VirtualSMC](https://github.com/acidanthera/virtualsmc/releases), SMCBatteryManager)
- All USB Port (USB 3.0, USB 2.0)
- iMessage | (Use Real Serial Number of MacBook Pro (Sync with SMBIOS))
- Webcam
- SD Card Reader
- Etc..

---

**Not Working :**

- NVIDIA GeForce 940M (NVIDIA Optimus/Switchable is not supported by Hackintosh)
- AirDrop (Wi-Fi not support)

---

**Not Tested :**

- HDMI Audio
- VGA Port

---

**BIOS Configuration**

|                  Bios Config                  |  Setting   |
| :-------------------------------------------: | :--------: |
|            Security -> Secure Boot            |  Disabled  |
|             Intel Virtualization              |  Enabled   |
|                     VT-d                      |  Enabled   |
| Graphics Configuration -> DVMT Pre-Allocation |    64M     |
|    USB Configuration -> XHCI Pre-Boot Mode    | Smart Auto |
|                   SATA Mode                   |    AHCI    |
|              Boot -> Launch CSM               |  Disabled  |

---

**Tutorial**

[OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

---

**Special Thanks and Credits to :**

[Apple](https://www.apple.com) | [OpenCore](https://github.com/acidanthera/OpenCorePkg) | [corpnewt](https://github.com/corpnewt/gibMacOS) | [doesprintfwork](https://github.com/doesprintfwork/MakeInstallmacOS) | [Acidanthera](https://github.com/acidanthera) | [RehabMan](https://github.com/RehabMan/Laptop-DSDT-Patch) | [Mieze](https://github.com/Mieze/RTL8111_driver_for_OS_X) | [InsanelyMac](https://www.insanelymac.com/forum) | [Andres ZeroCross](https://github.com/andreszerocross) | Other Developers.

---

## <img src="img/Screen Shot 2020-11-29 at 7.52.03 AM.png" align="center">

## <img src="img/Screen Shot 2020-11-29 at 7.53.50 AM (2).png" align="center">

## <img src="img/Screen Shot 2020-11-29 at 7.55.00 AM.png" align="center">

## <img src="img/Screen Shot 2020-11-29 at 7.55.43 AM.png" align="center">

## <img src="img/Screen Shot 2020-11-29 at 7.57.03 AM.png" align="center">

## <img src="img/Screen Shot 2020-11-29 at 7.57.28 AM.png" align="center">
