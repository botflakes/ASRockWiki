---
layout: default
title: AGESA
parent: Guides
---

## AGESA Changelog

### What is AGESA?

AGESA stands for "AMD Generic Encapsulated System Architecture" which is the basic framework for initializing AMD processors in the Power-On-Self-Test (POST) phase after the system is switched on. The mainboard manufacturers develop their firmware based on this (alias BIOS alias UEFI), but always based on an AGESA version published by AMD.

### SummitPi-AM4 1.0.0.4 - Patch A - Combo-AM4 1.0.0.6

<table style="table-layout:fixed;width:100%;color:#fff;margin-left:auto;margin-right:auto;font-size:14px;">
    <colgroup>
        <col width="300">
        <col width="400">
        <col width="150">
        <col width="100">
    </colgroup>
    <tbody>
        <tr>
            <th>AGESA Version</th>
            <th>Changes</th>
            <th>SMU Version</th>
            <th>Supported On</th>
        </tr>
        <tr>
            <td>SummitPi-AM4 1.0.0.4 - Patch A</td>
            <td>No information yet</td>
            <td style="text-align:end">Summit Ridge = 25.70.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>SummitPi-AM4 1.0.0.6</td>
            <td>No information yet</td>
            <td style="text-align:end">Summit Ridge = 25.77.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>SummitPi-AM4 1.0.0.6 - Patch A</td>
            <td>No information yet</td>
            <td style="text-align:center;font-size:20px!important;font-weight:900">?</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>SummitPi-AM4 1.0.0.6 - Patch B</td>
            <td>No information yet</td>
            <td style="text-align:end">Summit Ridge = 25.82.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.0 - Patch A</td>
            <td>No information yet</td>
            <td style="text-align:end">Summit Ridge = 25.83.0<br>Pinnacle Ridge = 43.10.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.1 - Patch A</td>
            <td>No information yet</td>
            <td style="text-align:end">Summit Ridge = 25.83.0<br>Pinnacle Ridge = 43.14.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.2</td>
            <td>- Sprectre V2 Protection</td>
            <td style="text-align:end">Summit Ridge = 25.83.0<br>Pinnacle Ridge = 43.16.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.2 - Patch A</td>
            <td>- Fix Powermanagement "Raven Ridge"-APU </td>
            <td style="text-align:end">Summit Ridge = 25.83.0 | 25.83.0<br>Pinnacle Ridge = 43.18.0 | 43.20.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.4 - Patch C</td>
            <td>No information yet</td>
            <td style="text-align:end">Summit Ridge = 25.84.0<br>Pinnacle Ridge = 43.20.0<br>Raven Ridge = 30.72.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.6</td>
            <td>- Support till Ryzen 2000<br>- Enabled Athlon 200GE Overlocking(?)</td>
            <td style="text-align:end">Summit Ridge = 25.84.0<br>Pinnacle Ridge = 43.20.0<br>Raven Ridge = 30.78.0</td>
            <td style="text-align:center">A320<br>B350<br>X370</td>
        </tr>
        <tr>
            <td>Combo-AM4 0.0.7.0</td>
            <td>No information yet</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 0.0.7.2</td>
            <td>- Support for Picasso and provisional for Matisse</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 0.0.7.2 - Patch A</td>
            <td>- Support for Picasso and provisional for Matisse</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.1</td>
            <td>- Full support for Matisse</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.2</td>
            <td>- Better RAM & Multiplier support</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3</td>
            <td>- Performance improvement for Ryzen 9<br>- Improved compatibility with DDR4-3000 and higher</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3 - Patch A</td>
            <td>- Improvement of the core boost(?)</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3 - Patch AB</td>
            <td>- Improvement of the core boost(?)<br>- Fix for M2.SSD</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3 - Patch ABA</td>
            <td>- Fix the random numbers for systemd and Destiny 2</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3 - Patch ABB</td>
            <td>- Fix the random numbers for systemd<br>- "Event 17, WHEA-Logger" warnings in the Windows Event Log removed</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3 - Patch ABBA</td>
            <td>- Boost 25-50 MHz higher<br>- Activity filter for light workloads</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.4 - Patch B</td>
            <td>- Eco Mode - Setting a lower TDP class via Ryzen Master<br>- X570 mainboards: Improved stability and compatibility with add-in devices<br>- Improvements to the interoperability of PCIe, USB, SATA and device reset functions<br>- Additional improvements to PCIe device support and stability<br>- Improved system stability when changing the ACPI states<br>- Shorter boot times (depending on the motherboard)<br>- Improvements when using the best CPU cores<br>- Further boost improvements for the Ryzen 9 3900X</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.5</td>
            <td>- Fixes a bug in the PCI lane configuration of the AMD Ryzen 3 PRO 2100GE<br>- Fixes a sporadic virtual memory error in combination with Realtek onboard LAN<br>- Improved POST with memory modules based on Micron DDR4-3200 chips<br>- Optimized PCIe firmware for improved stability and compatibility</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.6</td>
            <td>- CCX Overclocking<br>- Fix for SMM Callout Privilege Escalation (CVE-2020–12890)<br>- Support for Ryzen 3000XT</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">A320<br>B350<br>X370<br>B450<br>X470</td>
        </tr>
    </tbody>
</table>

### Combo-AM4v2Pi 1.0.0.0 - Combo-AM4v2Pi 1.2.0.2

<table style="table-layout:fixed;width:100%;color:#fff;margin-left:auto;margin-right:auto;font-size:14px;">
    <colgroup>
        <col width="300">
        <col width="400">
        <col width="150">
        <col width="100">
    </colgroup>
    <tbody>
        <tr>
            <th>AGESA Version</th>
            <th>Changes</th>
            <th>SMU Version</th>
            <th>Supported On</th>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.0.0</td>
            <td>- Initial BIOS for B550 Motherboards<br>- CPU support only Matisse and younger</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.0.1</td>
            <td>No information yet</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.0.2</td>
            <td>- Fix for SMM Callout Privilege Escalation (CVE-2020–12890)<br>- Support for Ryzen 3000XT</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.8.0 - Patch A</td>
            <td>- Early Support for Ryzen 5000</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.8.1</td>
            <td>- Better memory compatibility<br>- Better memory overclocking ability<br>- Mitigating the problem of waking up from S3 hibernation<br>- Fixed a RAID problem on the B550 platform<br>- Now supports the UMA setting for Ryzen ™ 4000 G-Series (Renoir) processors</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.0.0</td>
            <td>- Support for Ryzen 5000 with Zen 3 (“Vermeer”)<br>- Smart Access Memory<br>- General performance improvements for many types of workloads<br>- Improved support for loading and applying overclocked memory profile<br>- Improved BIOS overclocking robustness<br>- Improved USB hotplug detection<br>- Improved SATA device detection on select SATA ports<br>- Adds support for Eco Mode for automatic TDP reduction (AMD Ryzen Master)</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.0.0 - Patch B</td>
            <td>No Information</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.0.0 - Patch C</td>
            <td>No Information</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.0.0 - Patch D</td>
            <td>- New Curve Optimizer OC feature enabled<br>- Support for Ryzen 5000 Series on 400 Series mobos<br>- General stability improvements</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>        
        <tr>
            <td>Combo-AM4v2Pi 1.1.8.0</td>
            <td>- Introduces Precision Boost Overdrive 2 (PBO 2)<br>- Adds core undervolting for Ryzen 5000<br>- Adds Curve Optimizer for Undervolting and Overclocking</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.8.1</td>
            <td>- Support for Vermeer A0/B0 stepping and Cezanne A0 stepping</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.9.0</td>
            <td>- Adds Win10 s0i3 support<br>- Stability tuning for 1800-2000MHz FCLK (OC)<br>- Support for passive X570 motherboards<br>- General stability improvements</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.0</td>
            <td>- RAID Driver Update<br>- Support for PCIe ReBAR (GPU/driver support req'd)<br>- Stability updates<br>- Fix for 5600X/5800X telemetry in Ryzen Master (req's RM 2.6.1.X)<br>- SMU 56.44.00<br>- Improved Curve Optimizer<br>- Improved dLDO (digitally controlled low drop out)<br>- WHEA fix when FCLK is 1900<br>- Minor Bugfixes<br>- Code Cleanup<br>- Optimized and support AMD Ryzen 5000 series processors<br>- Optimized Resizable BAR (Re-Size BAR) function with NVidia Graphics cards<br>- Improved AM4 processor compatibility</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.1</td>
            <td>- Fix: False SMART errors on Hynix NVMe<br>- Fix: Intermittent SSD detection for M.2 SATA devices<br>- Improve L3$ bandwidth in AIDA64<br>- Improve stability if user disables cores on 5600X/5800X with AMD Ryzen Master</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.1 - Patch A</td>
            <td>- Improved USB compatibility</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.2</td>
            <td>- Fix: USB port dropout<br>- Fix: USB 2.0 audio crackling (e.g., DAC/AMP combos)<br>- USB/PCIe Gen 4 exclusion</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.3 - Patch A</td>
            <td>- Better Ryzen CPU Performance<br>- Better System Performance</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.3 - Patch B</td>
            <td>- Fixes all USB Issues (according to AMD)<br>- Extented support for Ryzen 5000G APUs(Cezanne)<br>- Added support for Ryzen 5000 CPUs (Vermeer B2 Stepping)</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.3 - Patch C</td>
            <td>No information yet</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.4</td>
            <td>No information yet</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.4 - Patch A</td>
            <td>No information yet</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.5</td>
            <td>No information yet</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.2.0.6</td>
            <td>No information yet</td>
            <td style="text-align:end"></td>
            <td style="text-align:center">B450<br>X470<br>A520<br>B550<br>X570<br></td>
        </tr>
    </tbody>
</table>

### Notice
Every changelog is more or less unofficial as AMD does not publish informations for every AGESA

### Sources
<img src="/asrockwiki/assets/images/flags/de.png"> <a class="flag-text" href="http://planet3dnow.de" target="_blank">- Planet3dNow!</a><br>
<img src="/asrockwiki/assets/images/flags/de.png"> <a class="flag-text" href="https://www.hardwareluxx.de/community/members/reous.55847/" target="_blank">- Reous @Hardwareluxx Forum</a>