# Acer-Swift-3-Hackintosh

## Only tested for Network Recovery boot!

This repository contains my EFI folder for booting macOS.

-   Opencore Version: 0.90

The EFI folder here was used to boot macOS Big Sur on the following system:

-   Laptop Model: Acer Swift 3 SF314-41
-   CPU: AMD Ryzen 3500U
-   Graphics:  AMD Radeon RX Vega 8

To use this EFI folder, simply copy all contents to a USB drive and boot from it. You may need to make modifications for your specific hardware configuration.

---

**Note:** 
 - Edit your SMBIOS values (MLB, ROM, Serial Number, UUID).
 - **Only Network Recovery functionality is tested,** remove GenericUSBXHCI kext after installation.
---
**Warning:**  Distributing macOS or modified macOS installers/images/folders is against the  macOS End User License  Agreement. This repo only contains EFI boot files and no  macOS system files.
