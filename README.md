# Hackintosh OpenCore for macOS Sequoia
## i5-13400F | RX 6750 XT | MSI PRO B760-P

### SMBIOS: MacPro7,1

---

### Summary

This is an OpenCore EFI configuration for a Hackintosh running macOS Sequoia on the following hardware:

- **CPU**: Intel Core i5-13400F
- **GPU**: AMD Radeon RX 6750 XT
- **Motherboard**: MSI PRO B760-P DDR4
- **Wi-Fi**: Working via **HeliPort**
- **Bluetooth**: **Not working**
- **SMBIOS**: MacPro7,1
- **macOS Version**: Sequoia

---

### Features

✅ macOS Sequoia bootable  
✅ Full GPU acceleration (RX 6750 XT)  
✅ Audio working  
✅ Ethernet working  
✅ Wi-Fi working via HeliPort  
❌ Bluetooth not working  

---

### Notes

- **HeliPort** + **itlwm.kext** is used for Wi-Fi functionality.
- Bluetooth currently unsupported due to compatibility issues with the internal module.
- Recommended SMBIOS: **MacPro7,1** for best support with Sequoia.
- Secure Boot is disabled.
- Serial numbers and UUIDs must be customized before use.

---

### Credits

- [OpenCore](https://github.com/acidanthera/OpenCorePkg)  
- [itlwm + HeliPort](https://github.com/OpenIntelWireless/HeliPort)  
- Dortania's OpenCore Install Guide

---

### Disclaimer

This EFI is shared for educational purposes only. Use at your own risk.
