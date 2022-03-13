# Lenovo X270 | OpenCore | BigSur (11)
This repo contains the files and scripts to install macOS on the Lenovo X270 i3-6300 CPU

for Wifi to work you must install **[Heliport](https://github.com/OpenIntelWireless/HeliPort)** on the mac

# Laptop's Hardware
- <b>Model</b>: Thinkpad X270
- <b>CPU</b>: Intel(R) Core(TM) i3-6300U CPU
- <b>GPU</b>: Intel HD Graphics 520
- <b>RAM</b>: 8 GB 2133MHz DDR4
- <b>Screen</b>: 12,4" (1366x768)
- <b>Wi-Fi</b>: AC-8260
- <b>Camera</b>: 720p

# Bios settings

<b>Security</b>
- `Security Chip` **Disabled**
- `Memory Protection -> Execution Prevention` **Enabled**
- `Virtualization -> Intel Virtualization Technology` **Enabled**
- `Virtualization -> Intel VT-d Feature` **Enabled**
- `Anti-Theft -> Computrace -> Current Setting` **Disabled**
- `Secure Boot -> Secure Boot` **Disabled**
- `Intel SGX -> Intel SGX Control` **Disabled**
- `Device Guard` **Disabled**

<b>Startup</b>
- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No**

# What's Working?
- [x] Intel HD 520 Graphics (incuding graphics acceleration)
- [x] CPU Power Management
- [x] Battery
- [x] All USB ports
- [x] HDMI port (including HDMI Audio)
- [x] Intel Ethernet port
- [x] Realtek Audio (including headphones jack)
- [x] Internal camera
- [x] Touchpad click and gestures
- [x] Shutdown / Reboot
- [x] Keyboard (incuding all fn Keys)
- [x] Wi-Fi
- [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime and Netflix, and others)
- [x] Sleep / Wake (lid sleep and lid wake) (works for me you can try for yourself)

# What's not working ⚠️
- [x] Does not show battery percentage
- [x] Bluetooth