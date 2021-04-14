# Realtek Audio Guide

Hey r/ASRock Community,

because the Realtek Audio Drivers are heavily outdated on most support pages of our boards and some experienced issues with it, I thought that, this would be a good opportunity to tell you which driver I’m using on my X470 Taichi based system.

I’m using the [Unofficial Generic Driver Package](https://github.com/pal1000/Realtek-UAD-generic/releases) from GitHub user “pal10000” as he tents to update his driver package very frequently.

The setup process is pretty simple but you need to prepare some things:  
***(The following is from a standpoint that you already installed the audio drivers which ASRock provides on the specific support page of your motherboard)***

* **Get rid of any official Realtek Audio Drivers!**  
To do this you can use Revo Uninstaller [\[Download\]](https://www.revouninstaller.com/revo-uninstaller-free-download/) as it deletes all leftovers and also deletes the specific registry keys. It’s free and there is also a portable version so you don’t need to install it.
* After you downloaded it, unzip it and start it. If you can find any Realtek Audio Driver, uninstall it. If not, nice you can proceed with step 4.
* If you uninstalled the Realtek Audio Driver, **reboot your system!**
* So let’s start with installing the Unofficial Generic Driver Package from pal1000. [\[Download\]](https://github.com/pal1000/Realtek-UAD-generic/releases) the driver package and unzip it. After that, go into the unzipped folder. There should be a folder named like “Realtek-UAD-generic”
* In this folder there is a file called “setup.cmd” - Make a right click on it and start it as administrator. You should now see a command line window like this: [\[EXAMPLE\]](https://i.botflakes.de/vKahCH.png)
* It will ask you now if you want to manage updates, codecs etc all by yourself. We press “n” and hit enter
* Now it checks if any audio driver is currently running and if so stops it and deletes it.
* It will ask you then if you want to install it. To confirm this, press “y” and hit enter.
* It will ask us a couple of times to a hit a random key (Just hit enter). This will happen multiple times. In my case 6 times. We'll do that.
* If all was successful you can now download the Realtek Audio Console from the Microsoft Store [\[Download\]](https://www.microsoft.com/en-us/p/realtek-audio-control/9p2b8mcsvpln?activetab=pivot:overviewtab)
* When the download and installation is finished, **reboot your system**.
* After rebooting there can be a window asking you if you want to exec the Realtek process. Uncheck the box and hit exec.

Congratulations! You installed the Unofficial Generic Driver Package. You can now start the Realtek Audio Console to set the settings you want.

**You want to uninstall the driver package again?**

No problem, start the setup again, press a key to continue, press "n" and "enter". At the point where it ask you if you want to install it, simply hit “n” and press enter. Done.

**Information**

*This guide can also be applied on other manufacturers motherboards with Realtek based sound!*

&#x200B;

***Are you already a member of our Discord server? If not consider to join us*** [https://discord.gg/rFrMpxV](https://discord.gg/rFrMpxV)

# Windows asking permission to run Realtek service every boot

If you are having that issue, do the following

![image](https://user-images.githubusercontent.com/65948403/114341805-32776b80-9b78-11eb-8040-527790664c71.png)

Trying to **Unblock** it causes errors like:

* Too many requests from a semaphore, or
* Assertion failed, and finally
* Access is denied

**Solution -**

1. Change owner of **RtkAudUService64.exe** to **Everyone** (its set to **SYSTEM** before), press **OK**.
2. Give all permissions to **Everyone** (by default only **Read & Execute** and **Read** permission is there).
3. That **Unblock** thing should have disappeared, but if it is still there check **Unblock** and press **OK**.
4. Remove all extra permissions given to **Everyone** (step 2).
5. Change back the owner to **SYSTEM**.
6. Restart your device, you shouldn't get that prompt

I think, most probably it is due to the original **RtkAudUService64.exe** in your driver package not being unblocked, or something in the script isn't working properly