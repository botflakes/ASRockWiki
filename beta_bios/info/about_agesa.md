<h1> > AGESA Changelog </h1>

<h2> What is AGESA? </h2>

<p>AGESA stands for "AMD Generic Encapsulated System Architecture" which is the basic framework for initializing AMD processors in the Power-On-Self-Test (POST) phase after the system is switched on. The mainboard manufacturers develop their firmware based on this (alias BIOS alias UEFI), but always based on an AGESA version published by AMD.</p>

<h2> PinnaclePi 1.0.0.2 - Combo-AM4 1.0.0.6 </h2>

<table class="customTable">
    <colgroup>
        <col width="300">
        <col width="800">
        <col width="300">
    </colgroup>
    <tbody>
        <tr>
            <th>AGESA Version</th>
            <th>Changes</th>
            <th>Additional Information</th>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.2</td>
            <td>- Sprectre V2 Protection</td>
            <td>None</td>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.2 Patch A</td>
            <td>- Fix Powermanagement “Raven Ridge”-APU </td>
            <td>None</td>
        </tr>
        <tr>
            <td>PinnaclePi-AM4 1.0.0.6</td>
            <td>- Support till Ryzen 2000<br>- Enabled Athlon 200GE Overlocking(?)</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 0.0.7.2</td>
            <td>- Support for Picasso and provisional for Matisse</td>
            <td>Partial problems with PBO / SMT</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.1</td>
            <td>- Full support for Matisse</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.2</td>
            <td>- Better RAM & Multiplier support</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3</td>
            <td>- Performance improvement for Ryzen 9<br>- Improved compatibility with DDR4-3000 and higher</td>
            <td>Problems with Core-Boost</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3a</td>
            <td>- Improvement of the core boost(?)</td>
            <td>All functions only with 32 MB BIOS</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3ab</td>
            <td>- Improvement of the core boost(?)<br>- Fix for M2.SSD</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3aba</td>
            <td>- Fix the random numbers for systemd and Destiny 2</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3abb</td>
            <td>- Fix the random numbers for systemd<br>- "Event 17, WHEA-Logger" warnings in the Windows Event Log removed</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.3abba</td>
            <td>- Boost 25-50 MHz higher<br>- Activity filter for light workloads</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.4b</td>
            <td>- Eco Mode - Setting a lower TDP class via Ryzen Master<br>- X570 mainboards: Improved stability and compatibility with add-in devices<br>- Improvements to the interoperability of PCIe, USB, SATA and device reset functions<br>- Additional improvements to PCIe device support and stability<br>- Improved system stability when changing the ACPI states<br>- Shorter boot times (depending on the motherboard)<br>- Improvements when using the best CPU cores<br>- Further boost improvements for the Ryzen 9 3900X</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.5</td>
            <td>- Fixes a bug in the PCI lane configuration of the AMD Ryzen 3 PRO 2100GE<br>- Fixes a sporadic virtual memory error in combination with Realtek onboard LAN<br>- Improved POST with memory modules based on Micron DDR4-3200 chips<br>- Optimized PCIe firmware for improved stability and compatibility</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4 1.0.0.6</td>
            <td>- CCX Overclocking<br>- Fix for SMM Callout Privilege Escalation (CVE-2020–12890)<br>- Support for Ryzen 3000XT</td>
            <td>None</td>
        </tr>
    </tbody>
</table>

<h2> Combo-AM4v2Pi 1.0.0.0 - Combo-AM4v2Pi 1.1.9.0 </h2>

<table class="customTable">
    <colgroup>
        <col width="300">
        <col width="800">
        <col width="300">
    </colgroup>
    <tbody>
        <tr>
            <th>AGESA Version</th>
            <th>Changes</th>
            <th>Additional Information</th>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.0.0</td>
            <td>- Initial BIOS for B550 Motherboards<br>- CPU support only Matisse and younger</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.0.1</td>
            <td>- No Changelog available</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.0.2</td>
            <td>- Fix for SMM Callout Privilege Escalation (CVE-2020–12890)<br>- Support for Ryzen 3000XT</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.8.0a</td>
            <td>- Early Support for Ryzen 5000</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.0.8.1</td>
            <td>- Better memory compatibility<br>- Better memory overclocking ability<br>- Mitigating the problem of waking up from S3 hibernation<br>- Fixed a RAID problem on the B550 platform<br>- Now supports the UMA setting for Ryzen ™ 4000 G-Series (Renoir) processors</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.0.0</td>
            <td>- Support for Ryzen 5000 with Zen 3 (“Vermeer”)</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.8.0</td>
            <td>- Introduces Precision Boost Overdrive 2 (PBO 2)<br>- Adds core undervolting for Ryzen 5000<br>- Adds Curve Optimizer for Undervolting and Overclocking</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.8.1</td>
            <td>- Support for Vermeer A0/B0 stepping and Cezanne A0 stepping</td>
            <td>None</td>
        </tr>
        <tr>
            <td>Combo-AM4v2Pi 1.1.9.0</td>
            <td>- Adds Win10 s0i3 support<br>- Stability tuning for 1800-2000MHz FCLK (OC)<br>- Support for passive X570 motherboards<br>- General stability improvements</td>
            <td>None</td>
        </tr>
    </tbody>
</table>

<h2> Notice </h2>
Every changelog is more or less unofficial as AMD does not publish informations for every AGESA.

<h2> Source </h2>

<img src="https://www.countryflags.io/de/shiny/16.png"> <a class="flag-text" href="https://planet3dnow.de" target="_blank">Planet3dNow!</a>