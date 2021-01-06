# [BIOS Index](/ASRockWiki/beta_bios/beta_bios.md) - Back to the index

# What is AGESA?

AGESA stands for "AMD Generic Encapsulated System Architecture" which is the basic framework for initializing AMD processors in the Power-On-Self-Test (POST) phase after the system is switched on. The mainboard manufacturers develop their firmware based on this (alias BIOS alias UEFI), but always based on an AGESA version published by AMD.

# PinnaclePi 1.0.0.2 - Combo-AM4 1.0.0.6

| AGESA Version | Changes | Additional Informations |                    
|:--------------|:--------|:------------------------|
|PinnaclePi-AM4 1.0.0.2 | - Sprectre V2 Protection | None |
|PinnaclePi-AM4 1.0.0.2a | - Fix Powermanagement “Raven Ridge”-APU | None |
|PinnaclePi-AM4 1.0.0.6 | - Support till Ryzen 2000 | Enabled Athlon 200GE Overlocking(?)
|Combo-AM4 0.0.7.2 | - Support for Picasso and provisional for Matisse | Partial problems with PBO / SMT
|Combo-AM4 1.0.0.1 | - Full support for Matisse | None |
|Combo-AM4 1.0.0.2 | - Better RAM & Multiplier support | None |
|Combo-AM4 1.0.0.3 | - Performance improvement for Ryzen 9<br> - Improved compatibility with DDR4-3000 and higher | Problems with Core-Boost
|Combo-AM4 1.0.0.3a | - Improvement of the core boost(?) | All functions only with 32 MB BIOS
|Combo-AM4 1.0.0.3ab | - Improvement of the core boost(?)<br>- Fix for M2.SSD | None |
|Combo-AM4 1.0.0.3aba | - Fix the random numbers for systemd and Destiny 2 | None |
|Combo-AM4 1.0.0.3abb | - Fix the random numbers for systemd<br>- "Event 17, WHEA-Logger" warnings in the Windows Event Log removed | None |
|Combo-AM4 1.0.0.3abba | - Boost 25-50 MHz higher<br>- Activity filter for light workloads | None |
|Combo-AM4 1.0.0.4b | - Eco Mode - Setting a lower TDP class via Ryzen Master<br>- X570 mainboards: Improved stability and compatibility with add-in devices<br>- Improvements to the interoperability of PCIe, USB, SATA and device reset functions<br>- Additional improvements to PCIe device support and stability<br>- Improved system stability when changing the ACPI states<br>- Shorter boot times (depending on the motherboard)<br>- Improvements when using the best CPU cores<br>- Further boost improvements for the Ryzen 9 3900X | None  |
|Combo-AM4 1.0.0.5 | - Fixes a bug in the PCI lane configuration of the AMD Ryzen 3 PRO 2100GE<br>- Fixes a sporadic virtual memory error in combination with Realtek onboard LAN <br>- Improved POST with memory modules based on Micron DDR4-3200 chips<br>- Optimized PCIe firmware for improved stability and compatibility | None  |
|Combo-AM4 1.0.0.6 | - CCX Overclocking<br>- Fix for SMM Callout Privilege Escalation (CVE-2020–12890)<br>- Support for Ryzen 3000XT | None   |

# Combo-AM4v2Pi 1.0.0.0 - Combo-AM4v2Pi 1.0.0.2

| AGESA Version | Changes | Additional Informations |                    
|:--------------|:--------|:------------------------|
|Combo-AM4v2Pi 1.0.0.0 | - Initial BIOS for B550 Motherboards<br>- CPU support only Matisse and younger | None |
|Combo-AM4v2Pi 1.0.0.1 | - No Changelog available | None |
|Combo-AM4v2Pi 1.0.0.2 | - Fix for SMM Callout Privilege Escalation (CVE-2020–12890)<br>- Support for Ryzen 3000XT | None |
|Combo-AM4v2Pi 1.0.8.0a | - Early support for Ryzen 5000 | None |
|Combo-AM4v2Pi 1.0.8.1 | - Better memory overclocking ability<br>- Mitigating the problem of waking up from S3 hibernation<br>- Fixed a RAID problem on the B550 platform<br>- Now supports the UMA setting for Ryzen ™ 4000 G-Series (Renoir) processors | None |
|Combo-AM4v2Pi 1.1.0.0 | - Support for Ryzen 5000 with Zen 3 (“Vermeer”) | None |


# Notice
Every changelog is more or less unofficial as AMD does not publish informations for every AGESA.

# Source

[Planet3DNow!](https://planet3dnow.de)