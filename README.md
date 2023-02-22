# Dell Precision T5810 OpenCore
 OpenCore for the Dell Precision T5810
 
# OS

- macOS Big Sur 11.6.4 & Windows 10 Pro

# Hardware

- Xeon E5-1640v4
- AMD Radeon RX 560 2GB
- 32GB DDR4R
- TP-Link Broadcom Wireless
- 500GB SATA SSD
- BIOS A33

# What Works

- CPU & GPU Power Management 
- VDA Encode/Decode
- Sleep and Wake
- Audio
- Ethernet & WiFi

# Notes

This is a working config for a Dell Precision T5810. Please note that based on your GPU some modifications may be needed. This repository needs some modifications to be updated to macOS Monterey, which will come in a future update. We are utilizing the iMacPro SMBIOS, but MacPro7,1 would also be appropriate with the addition of the RestrictEvents.kext extension.

Thanks especially to @BillDH2k for research and testing for macOS 12+ and XCPM.
