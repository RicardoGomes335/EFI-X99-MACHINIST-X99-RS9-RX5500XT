# EFI-X99-MACHINIST-X99-RS9-RX5500XT

EFi Machinist X99-RS9 with OpenCore 0.9.66

Supports Hackintosh Monterey version 12.3.1 up to Sonoma 14.1.1

Platform: LGA 2011-3 | Intel Xeon V3

Motherboard: MACHINIST X99-RS9

CPU: Intel Xeon E5-2660 v3, 2600 MHz (10C/20T)

GPU: AMD Radeon RX5500XT (8 GB)

Audio: Realtek ALC662 (Fixed)

SMBIOS: iMacPro1,1

macOS: Sonoma 14.1.1

Opencore: 0.9.6

Disable on Bios

Fast Boot

Secure Boot

Serial/COM Port

Parallel Port

VT-d (can be enabled if you set DisableIoMapper to YES)

Compatibility Support Module (CSM).

Thunderbolt(For initial install, as Thunderbolt can cause issues if not setup correctly)

Intel SGX

Intel Platform Trust

CFG Lock (MSR 0xE2 write protection)

This must be off, if you can't find the option then ENABLE AppleXcpmCfgLock.

Your hack will not boot with CFG-Lock enabled.

For 10.10 and older, you'll need to ENABLE AppleCpuPmCfgLock as well.

============================================================================================

Enable on Bios

VT-x

Above 4G decoding.

This must be on, if you can't find the option then add npci=0x2000 to boot-args.

Do not have both this option and npci on boot-args enabled at the same time.

Hyper-Threading

Execute Disable Bit

EHCI/XHCI Hand-off

OS type: Windows 8.1/10/11 UEFI Mode

SATA Mode: AHCI

============================================================================================

<img src="https://github.com/RicardoGomes335/EFI-X99-MACHINIST-X99-RS9-RX5500XT.git/assets/img/sonoma.png">
