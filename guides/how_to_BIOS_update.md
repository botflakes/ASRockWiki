# > How to: Update the BIOS

# Introduction

Before we start on how to update the BIOS, there is some information about BIOS/UEFI. You can skip it if you want but it's worth reading.

# What is a BIOS?

A BIOS or Basic Input/Output System is a firmware used to perform hardware initialization during the boot (start of the PC).
It also provides runtime services for OS's (Operating Systems) and programs. The BIOS is always pre-installed on the Motherboard and it's
the first software to run when powered on.

The BIOS in modern PCs initializes and tests the hardware components, and loads a boot loader from a mass storage device which then initializes an operating system.
Back in the days, a BIOS was stored in a ROM chip on the PC motherboard and the only option to update it was, to remove the chip and use other hardware to update it.
In the current era, BIOSes are also stored on a chip on the Motherboard but it's a flash memory so it can be updated without removing the chip itself.
This is especially useful to let the user update the bios on their own which can add new or more features and also fixes bugs. The only risk the user has to take is that 
if a BIOS Update fails, due to power outage right in the middle of the update process, that the motherboard is bricked which means the flash memory on the motherboard wasn't
written completely with the new BIOS which currupted it. There are methods which can prevent that like using a UPS. There are also methods which can recover the BIOS or rewrite it again
with tools like a EEPROM Programmer or even BIOS Flashback. Some motherboards do have a dual bios which the user can fall back to.
Current motherboards are shipped with an UEFI BIOS (Unified Extensible Firmware Interface) which is the successor of the legacy PC BIOS. It aims to address the legacy BIOS technical limitation.
If you want to learn more about BIOS or the successor UEFI, click [here](https://en.wikipedia.org/wiki/BIOS) or [here](https://en.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface)

Every BIOS/ UEFI (BIOS is the more general term so dont get confused) is based on a special software code. AMD for example names this AGESA or (AMD Generic Encapsulated SoftwareArchitecture) and is used to perform the platform initialization on mainboards using their AMD64 architecture. As part of the BIOS of such mainboards, AGESA is responsible for the initialization of the processor cores, memory, and the HyperTransport controller and more.

# Is there anything I need to know before I update?

Yes there are some few things. A BIOS Update, especially on AMDs AM4 Platforms like A320, B350, X370, B450, X470, A520, B550 and X570, can drop support for certain CPUs.
To make sure, read the yellow text ASRock provides in the description box with each release of a BIOS. If you are still unsure, you can make a post on the subreddit or join our community [Discord](https://discord.com/invite/rFrMpxV) or ask the technical support to help you.

Mostly the support for Zen or Ryzen 1000 Series CPUs was dropped with the latest BIOS versions with AMD AGESA Combo-AM4 V2 1.1.0.0. B550 never supported them same goes for Ryzen2000 Series CPUs and 1000 Series was also not supported on X570.

Some X570/ B550 motherboards require to update the BIOS in a special way when the system is currently using a Pinnacle Ridge or Picasso based CPU. Either trough BIOS Flashback(when available) or through DOS. 
A guide for that is usually linked in the description box of the BIOS update then.

# What do I need to perform a BIOS update?

The traditional method:

As for an ASRock motherboard you only need the following:

- The BIOS file you want to flash
- A USB drive formatted in FAT32 with a size of, at least, 32MB

The BIOS file can be downloaded on the specific support page of your board [[OVERVIEW]](https://www.asrock.com/mb/index.asp#AllProduct) under "Support > BIOS".
Its packed into a .zip container and needs to be unzipped or extracted onto the USB drive. There's mostly only one file in the .zip [[EXAMPLE]](https://cdn.botflakes.de/subreddit/asrock/wiki_images/bios_example_1.png).
Just drag and drop this file in the root directory of your USB drive like so [[EXAMPLE]](https://cdn.botflakes.de/subreddit/asrock/wiki_images/bios_example_2.png). It can also be in a directory.
Now all you need is to restart the PC and spam DEL while the PC is rebooting. This will get you into the BIOS and from there you are able to update the BIOS by using the "InstantFlash" option.
A window will pop up where you can select the BIOS file you downloaded and placed on the USB drive. The BIOS will ask you if you are sure to update the BIOS. 
Click yes and wait a bit till it says that the BIOS Update was successful. Click ok and the PC should restart on its own.

Now you are done. Make sure that you apply your settings again like XMP and what not because the BIOS update reverts everything back to the default state.

The BIOS Flashback method:

- Download the latest BIOS from the specific ASRock motherboard support page
- Extract the file and copy it onto your USB drive to the root directory (the first thing you see when you click on the USB drive).
- Rename the file to "creative.rom"
- Make sure the 24 pin power connector is connected
- Turn on the PSU (Dont start the PC!!!)
- Plug in the USB drive into the USB BIOS Flashback port (see manual when not marked)
- Press the BIOS Flashback button for at least 3 seconds. The LED starts to blink.
- Wait until the LED stops blinking, indicating that BIOS flashing has been completed.
    
*If the LED light turns solid green, this means that the BIOS Flashback is not operating properly. Please make sure that you plug the USB drive to the USB BIOS Flashback port.

# BIOS Update FAQ

## I do have BIOS Flashback but no CPU! What now?

The BIOS Flashback method:

- Download the latest BIOS from the specific ASRock motherboard support page
- Extract the file and copy it onto your USB drive to the root directory (the first thing you see when you click on the USB drive).
- Rename the file to "creative.rom"
- Make sure the 24 pin power connector is connected
- Turn on the PSU (Dont start the PC!!!)
- Plug in the USB drive into the USB BIOS Flashback port (see manual when not marked)
- Press the BIOS Flashback button for at least 3 seconds. The LED starts to blink.
- Wait until the LED stops blinking, indicating that BIOS flashing has been completed.
    
*If the LED light turns solid green, this means that the BIOS Flashback is not operating properly. Please make sure that you plug the USB drive to the USB BIOS Flashback port.

That also applies when you currently have a Pinnacle Ridge CPU!

## I do have a Pinnacle Ridge CPU and want 5000 Series CPU Support! What now?

It depends a bit on the motherboard. ASRock gives always a good description to their BIOS releases. 

Generally speaking, if your motherboard does have BIOS Flashback, use the BIOS Flashback method.
If your board doesnt have such function, always read the yellow text in the BIOS description on your motherboard support page!

## Why do I have to update the BIOS via shell on my motherboard?

The 32MB BIOS is split into 2 regions. One region serves Zen2 and newer. The other is for Zen+.

Instant Flash can only update the active region.
If, for example, you boot with a Matisse CPU then the region for Zen2 and newer is active, and this can be updated via Instant Flash.
But if you boot with a Pinnacle Ridge CPU then only the region for Zen+ can be updated via Instant Flash.

In order to update the region for Zen2 and newer while the region for Zen+ is the active one, the tool that runs in the EFI shell must be used.

## PC turned off during BIOS update or doesnt reboot at all anymore

If your PC turns off turing BIOS update, that means that your board is bricked. There are few things you could try to revive it.

- If your Motherboard has BIOS Flashback, try to flash the BIOS again with it. How to perform a BIOS update via BIOS Flashback see the manual of your Motherboard.

There is also a "trick" which does work on some Motherboards which have AMI BIOS. 

- Download the BIOS you tried to flash unto a USB Drive (dont drag it into a folder! It needs to be just on the USB Drive)
- Rename it to AMIBOOT.ROM
- Hold "CTRL" + "HOME" while turing the power on.
- Continue to hold the both keys down until you notice that the PC is reading from the USB device. (Make sure no other USB Drives are connected)
- Release both keys. A beep code speaker can be useful as the AMIBIOS issues a series of beeps that indicates that the system BIOS ROM file is being updated. There will most likely a progress dialog displayed on the screen after the file has been loaded.
- When the flash ROM has successfully been programmed, the computer will reboot. Please do not interrupt the BIOS flash process until it has fully completed. 