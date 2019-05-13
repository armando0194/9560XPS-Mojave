# Dell XPS15 9560 Mojave Hackintosh

> Dell XPS15 9560 Hackintosh Clover Config.

## Configuration

- CPU：Intel I7 7700HQ
- RAM：32G(16G\*2 G Skill Intl) 2400MHz DDR4
- HardDisk：PM961 NVMe SAMSUNG 512GB
- WIFI：DW1560
- Screen：4K(touch)

## What's not Working

1. Fingerprint sensor
2. Discrete graphic card
3. SD Card Reader
5. Intel Wi-Fi Killer 1535

## BIOS Settings:
A. General
- System Information
    1. Check that Video Memory is already 64MB (scroll down to the bottom)​
- Advanced Boot Options (all off)

B. System Configuration
- SATA Operation (AHCI)
    1. Will break Windows boot​
- Drives (all on)
- SMART Reporting (on)
- USB Configuration (all on)
- Dell Type-C Dock Configuration (on)
- Thunderbolt Adapter Configuration (all on, no security)
- USB PowerShare (on)
- Audio (all on)
- Keyboard Illumination (whatever; this gets overridden by the F10 key)
- Touchscreen (on)
- Miscellaneous Devices (all on except SD Card Read-Only Mode)​

C. Security
- CPU XD (on)​

D. Secure Boot
- Secure Boot Enable (disabled)​

E. Intel Software Guard Extensions
- Intel SGX Enable (Software-Controlled)​

F. Performance
- (Everything on/enabled)​

G. Power Management
- USB Wake Support
    1. (USB Wake Support = off)
    2. (Wake on Dell USB-C Dock = on)​
- Wake on WLAN (off)
- Block Sleep (off)​

H. Virtualization Support
- (Everything on)​
​