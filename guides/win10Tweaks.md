# NOT FINISHED YET!!! DO NOT USE!!!

Please do not use yet as I did not test it myself yet
---



Windows 10 is a great OS and by default more the suitable for gaming.  
However, you can still get some performance out of your Hardware by changing or creating some registry keys and values.  

Some default settings hidden in the registry actually reserving resources for other stuff.  
With the following settings and registry tweaks we will change that.

Make sure that you at least write down the default values of all already created DWORD's so you can return to "default" if you encounter issues which you actually shouldn't.

# Disable Nagling
***

Go to:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\Interfaces{NIC-id}`  

For the `{NIC-id}`, look for the one with your IP address listed. Under this `{NIC-id}` key, create the following DWORD's with these values:
(without the quotation marks)

```
Name "TcpAckFrequency" | Value "1"
Name "TCPNoDelay"      | Value "1"
Name "TcpDelAckTicks"  | Value "0"
```
# Disable Network-Throttling
***

Go to:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Multimedia\SystemProfile`

Create a DWORD (without the quotation marks)

```
Name "NetworkThrottlingIndex" | Value "ffffffff"
```
# Tweak System-Responsiveness
***

Got to:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Multimedia\SystemProfile`

Create a DWORD (without the quotation marks)

```
Name "SystemResponsiveness" | Value "0"
```
# Tweak Priority and GPU Priority for Gaming
***

Got to:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Multimedia\SystemProfile\Tasks\Games`

and change the follwing values:

```
"GPU Priority"          to "8"
"Priority"              to "6"
"Scheduling Category"   to "High"
"SFIO Priority"         to "High"
```

# Turn off LargeSystemCache
***

Go to:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management`

and change the following value:

```
"LargeSystemCache"      to "0"
```
# Disable HPET
***

Make sure you disable the "High Precision Event Timer" (HPET) in Windows. Most modern Motherboards give you either the option to enable it in the BIOS.  
If you dont have such an option in the BIOS, it's enabled by default. You want it to be enabled by the motherboard but disabled in Windows. 
To do this, do the following:

```
1. Open a CMD with admin rights
2. Type "bcdedit /deletevalue useplatformclock" and hit enter. If you get a error message no worries, it just means it was already disabled.
3. Restart your System
```
# Disable Synthetic Timers
***

To disable Synthetic Timers do the following:

```
1. Open a CMD with admin rights
2. Type "bcdedit /set useplatformtick yes" and hit enter.
3. Restart your System
```

# Disable Dynamic Ticks
***

To disable Dynamic Ticks do the follwing:

```
1. Open a CMD with admin rights
2. Type "bcdedit /set disabledynamictick yes" and hit enter.
3. Restart your System
```

***

# Thats all for now!
