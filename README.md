
# Lenovo IdeaPad 330S-15IKB (81F5) | OpenCore EFI Configuration

## ⚠️ Read before continuing
This does not serve as a comprehensive guide. It is strongly advised to consult [Dortania's guide](https://dortania.github.io/OpenCore-Install-Guide/) for instructions before taking any actions. I cannot be held accountable for any potential harm or consequences. The OpenCore configuration provided here is specifically tailored to my particular hardware setup. Therefore, it is recommended to utilize it solely as a point of reference or if you possess identical or similar hardware

## 💻 Hardware

| **Part** | **Description**                         |
| ------------ | ------------------------------------- |
| **CPU**      | 2.2GHz Intel Core i3-8130U            |
| **GPU**      | Intel UHD 620 + Radeon 535 (Disabled) |
| **RAM**      | 8GB (4GB non-removable) 2400MHz DDR4  |
| **SSD**      | 512GB Kingston SATA SSD               |
| **Display**  | 15,6" 1920x1080  LCD non-touch display|
| **Wi-Fi/BT** | Intel Dual Band Wireless-AC 3165      |
| **Ethernet** | Realtek RTL8111                       |
| **Audio**    | Realtek ALC230                        |
| **Input**    | PS2 Keyboard & ELAN TrackPad          |

##  ⚙️ BIOS Configuration

Mandatory changes:

- Security / Intel Platform Trust Technology - Disabled
- Security / Intel SGX - Disabled
- Security / Secure Boot - Disabled
- Boot / Boot Mode - UEFI

Optional changes:

 - Configuration / One Key Battery - Disabled (Because it's annoying 😒)
 - Exit / OS Optimized Defaults - Disable
 - Configuration / Graphic Device - UMA Only (Set if you have graphic issues)

## More to be added...
