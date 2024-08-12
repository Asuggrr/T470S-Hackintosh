# T470S-Hackintosh
This is not a guide, but rather my work with my first hackintosh on a T470s.
The formating of this repo is copied from https://github.com/Elemiel-K/Opencore-T470s while being edited to reflect my changes and methodology



Currently running Mac OS Ventura

Hardware:

    Make and Model: Lenovo Thinkpad T470s
    Processor and Chipset: Intel Core i5 6300u / Intel Skylake 100 series chipset
    Graphics: Intel HD 520
    Monitor: 1080p 
    Storage: Samsung 980 Pro NVMe 1 TB SSD
    RAM: 8 GB DDR4
    1 x PS/2 Trackpad + Trackpoint
    1 x PS/2 Keyboard
    1 x USB 3.0 card reader
    3 x USB 3.0 type a ports
    1 x TB3/USB C port
    1 x HDMI port
    1 x 3.5mm mic/headphone jack
    Wifi+BT: Intel AX210

Currently functioning:

    All basic functions including sleep/wake and boot without error including iCloud Services
    Trackpoint and Trackpad with gesture support and Keypad buttons function as well
    SD Cardreader @ usb 3.0 speeds
    USB type A ports with USB 3.0 and USB 2.0 support
    BT 5 + Wifi 6


BIOS Settings

    Config
        USB UEFI Bios Support -> Enabled
        Keyboard Mouse
            Trackpoint -> Enabled
            Trackpad -> Enabled
        Display
            Total Graphics Memory -> 512 MB
            Boot Time Extension -> Disabled
        Thunderbolt 2
            Wake by TB3 -> Disabled
            Support in Preboot Env -> Enabled
    Security
        Fingerprint
            Predesktop Auth -> Disabled
            Security Mode -> Normal
        Security Chip
            TPM 2.0
            Security Chip -> Disabled/All
        Memory Protection -> Enabled
        Virtualization
            Intel Virtualization -> Enabled
            Intel VT -d -> Disabled
        I/O port access -> Enable All
        Secure Boot -> Disabled
        Intel SGX -> Disabled
        Device Guard -> Disabled
    Startup
        UEFI/Legacy -> UEFI only
        CSM Support -> No




Credits:

  Opencore Dortania Install Guide
    https://dortania.github.io/OpenCore-Install-Guide/

  Opencore Hotpatching Guide
    https://github.com/jsassu20/OpenCore-HotPatching-Guide

  Elemiel-K T470s Hackintosh Repo
    https://github.com/Elemiel-K/Opencore-T470s
