
# Lenovo IdeaPad 330S-15IKB (81F5) | OpenCore EFI Configuration

## ⚠️ Read before continuing

This does not serve as a comprehensive guide. It is strongly advised to consult [Dortania's guide](https://dortania.github.io/OpenCore-Install-Guide/) for instructions before taking any actions. I cannot be held accountable for any potential harm or consequences. The OpenCore configuration provided here is specifically tailored to my particular hardware setup. Therefore, it is recommended to utilize it solely as a point of reference or if you possess identical or similar hardware.

If the internals of your laptop differ from my configuration even the slightest bit, don't be surprised if something doesn't work. The best thing to do is to follow the official guide and build your very own EFI folder by using this repository as inspiration.

I'm not responsible for any loss of files, laptop or hardware damage, etc. Every change you make to your device is solely your responsibility. Make sure you do your research and have basic experience handling bootloaders and operating systems before continuing.

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

## 🍎 macOS Compatibility
Due to the limitations of the manufacturer-shipped Intel wireless card, the maximum macOS version that can be installed on the device without changing the internals and having everything work *out of the box* is *macOS Version 11 (Big Sur)*.

Theoretically, this EFI configuration should work perfectly fine on higher macOS versions if the wireless card is swapped for something that macOS supports natively.


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
