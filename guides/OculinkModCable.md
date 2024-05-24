---
layout: default
title: Modified OCuLink Cable for PCIe Devices
#parent: Guides
---

{: .important }
> This Guide was written by our Community Member u/Calpulz. 

{: .warning }
> We're not responsible for any damage that may happen to your board!
> Only follow this guide if you understand the risks and are confident in doing it!

## Intro

For the past few weeks, I have been trying to get PCIe devices such as GPU, HBA, WiFi Cards, etc to work through my Asrock Rack X570D4I-2T OCuLink port.

I am building a custom ITX server and require more SATA drives then the 8 this motherboard supports. So I want to run a HBA through the OCuLink port using a OCuLink to PCIe x16 adapter board (x4 bandwidth).

However after trying various different cables and adapters, nothing worked through the motherboards OCuLink port apart from a cable mentioned numerous times on diferent forms. Supermicro 55cm OCuLink to U.2 PCIE with Power Cable (CBL-SAST-0956).

So I purchased one along with some adapters to find out whats different about this cable from Supermicro. I then modified a standard OCuLink cable so that it works with the motherboard and PCIe x16 adapter board.

* Motherboard: Asrock Rack X570D4I-2T  
* CPU: Ryzen 9 5900x

## Problem Overview

PCIe devices failing to recognize or function when connected through an OCuLink port on the motherboard using a standard OCuLink x4 cable (male to male, SFF-8611 to SFF-8611).

However, when using a specialized Supermicro cable designed for U.2 SSDs (OCuLink to U.2) along with a series of adapter boards, PCIe devices are detected and operate correctly.

### Detailed Setup and Symptoms

* Non-Working Setup Using Standard OCuLink Cable: Connecting PCIe devices through an OCuLink x4 cable directly to an OCuLink to PCIe x16 slot adapter results in failure of device recognition or operation.

* Working Setup Using Supermicro Cable: Using a Supermicro cable (OCuLink to U.2) and a series of adapters (U.2 to M.2, M.2 to OCuLink), then reconnecting to a standard OCuLink cable to the PCIe x16 adapter, the devices work correctly. This setup essentially replicates a male-to-male OCuLink cable using multiple adapters.