# HP ProBook 6470b EFI Sonoma Official Nightly Builds

## EFI for MacOS Sonoma on HP ProBook 6470b (2012) 🎉

I am thrilled to share my successful Hackintosh project on my 2012 HP ProBook 6470b! Running MacOS Sonoma without a hitch, this old machine has been revitalized and is performing exceptionally well. Below are the specs and details of the setup:

## 🖥️ System Specifications:

- 💻 **CPU Type:** Mobile DualCore Intel Core i5-3320M, 3100 MHz (31 x 100)
- 🔧 **Motherboard Chipset:** Intel Panther Point HM76, Intel Ivy Bridge
- 🎨 **Video Adapter:** Intel(R) HD Graphics 4000 (2112 MB)

🔊 **Audio Adapter:**
- IDT 92HD81B1X @ Intel Panther Point PCH - High Definition Audio Controller [C1]
- Intel Panther Point HDMI @ Intel Panther Point PCH - High Definition Audio Controller [C1]

🌐 **Network Adapter:**
- Intel(R) 82579V Gigabit Network Connection
- Intel(R) Centrino(R) Advanced-N 6205

🔥 **FireWire Controller:** JMicron JMB380 PCI-E 1394a OHCI FireWire Controller and Memory Card Host Controller

🔌 **USB Device:**
- Broadcom 20702 Bluetooth 4.0 Adapter
- HP HD Webcam [Fixed]

💽 **IDE Controller:**
- Standard SATA AHCI Controller
- JMicron PCIe SD/MMC Host Controller

## ⚙️ Performance and Stability:

Despite its age, the HP ProBook 6470b runs MacOS Sonoma seamlessly. Here are some highlights of the performance:

- **Graphics:** The Intel HD Graphics 4000 handles the macOS interface smoothly, providing a good user experience without any graphical glitches.
- **Audio:** Both audio adapters work perfectly, ensuring crisp and clear sound whether using the built-in speakers or external devices.
- **Network:** Wired and wireless connections are stable and reliable, courtesy of the Intel network adapters.
- **Bluetooth & USB:** The Broadcom Bluetooth adapter and various USB devices function without issues, ensuring full peripheral compatibility.

## 🛠️ Installation Process:

The installation was straightforward, thanks to the robust EFI configuration and available guides. Key steps included:

- 💾 **Creating a Bootable USB Installer:** Used a Mac or another Hackintosh to create a bootable USB with MacOS Sonoma.
- 🔧 **Configuring the BIOS:** Ensured BIOS settings were optimized for macOS compatibility (e.g., disabling Secure Boot, enabling AHCI).
- 📁 **EFI Folder Configuration:** Placed the necessary kexts, drivers, and configuration files in the EFI folder.
- 💻 **Installing MacOS:** Booted from the USB installer, formatted the drive to APFS, and installed MacOS Sonoma.
- 🛠️ **Post-Installation Tweaks:** Applied post-installation tweaks to ensure all hardware components were recognized and functional.

## 🗂️ EFI Configuration and Support:

I am excited to announce that I will be **providing nightly builds for the EFI folders**, ensuring they are up-to-date and optimized for the best performance. Additionally, **I will be offering support to assist with any issues or questions you may have**.

### Here's a snapshot of the key components in my EFI folder:

**Bootloader:** OpenCore (version X.X.X)

**Essential Kexts:**
- Lilu.kext
- WhateverGreen.kext
- AppleALC.kext
- IntelMausi.kext
- AirportBrcmFixup.kext
- USBInjectAll.kext
- VirtualSMC.kext

**Drivers:**
- OpenRuntime.efi
- HfsPlus.efi

**Configuration File:** A meticulously edited config.plist to match the system specifications and optimize performance.

## ✅ What's Working:

- 🛜 Wi-Fi
- 📶 Bluetooth
- 📤 Airdrop
- 🎥 HDMI
- 🎵 AUDIO
- 🌐 Ethernet
- 🔥 FireWire
- 💳 Express Cards
- 🔒 Close/Open lid
- 💡 Laptop Backlight
- 🖥️ Multiple Displays
- 📺 VGA Output port
- 🔌 USB2.0
- 🔋 USB3.0
- 🎛️ PS2 TouchPad
- 🔋 Battery? (I have no battery to test, but you can expect it should be working properly)
- 🌙 Hibernation? (Sometimes, please test and report)

## ⚠️ Known Issues:
- About to be updated...
- ⚠️ More issues? You tell me...

## 🙏 Acknowledgements:

This project wouldn't have been possible without the incredible work of the Hackintosh community. Special thanks to the developers and contributors of the tools and kexts used in this project:

- OpenCore: For the powerful bootloader.
- Lilu.kext: Essential for patching macOS.
- WhateverGreen.kext: For fixing graphics issues.
- AppleALC.kext: For enabling audio support.
- IntelMausi.kext: For network compatibility.
- AirportBrcmFixup.kext: For Wi-Fi and Bluetooth functionality.
- USBInjectAll.kext: For USB support.
- VirtualSMC.kext: For hardware monitoring.

Your dedication and hard work have made it possible to bring macOS to non-Apple hardware. Thank you!

## Images


![Springboard/Launchpad](https://i.imgur.com/d4bOP7B.png)

> Springboard/Launchpad

![LCD Brightness working](https://i.imgur.com/Lh9JMGG.png)

> LCD Brightness working

![About Mac](https://i.imgur.com/dvCqIUA.png)

> About Mac


## 💖 Donations:

If you find this project helpful and would like to support its ongoing development, consider making a [donation](http://paypal.me/AlienSK "donation"). Your contributions will help cover the costs of maintaining and improving the EFI configurations, as well as providing support. Every little bit helps and is greatly appreciated.

## END
