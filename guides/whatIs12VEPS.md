---
layout: default
title: What is 12V EPS?
parent: Guides
---
## What is 12V EPS?

***

12V EPS is the main and only source for your CPU (Central Processing Unit) to get power. The Power comes obviously from the main source, the PSU (Power Supply Unit). 

12V is, as you may know, way to much for a CPU. This is where VRM or Voltage Regulator Modules came in. These little chunks which are mainly under the big aluminium heatsinks around your CPU-Socket. They need the Heatsinks because they can get very hot. 

<p style="text-align: center;"><img src="../../assets/images/wiki/12VEPS/taichi_vrm.jpg"/></p>
<p style="text-align:center;font-size:10px">(X470 Taichi (Ultimate) VRMs - source tweaktown.com)</p>



But that’s not the reason I write this. It seems that many people, especially new pc builders, are overwhelmed when they see something like this on their brand new motherboard:

<p style="text-align: center;"><img src="../../assets/images/wiki/12VEPS/8+4Pin_EPS.png"/></p>
<p style="text-align:center;font-size:10px">(8+4 Pin EPS 12V - credit u/CornFlakes1991)</p>

A 8+4 Pin 12V EPS connector. 
Usually pretty straight forward. Most PSU cables are labeled. The CPU Power connectors are either labeled with EPS or CPU. Most modern PSUs have a 4+4 Pin which would go into the 8 Pin EPS. Some PSUs have a single 8 Pin and a Single 4 Pin. Others Have a Single 8 Pin and a 4+4 Pin

<p style="text-align: center;"><img src="../../assets/images/wiki/12VEPS/4+4Pin_EPS_example.jpg"/></p>
<p style="text-align:center;font-size:10px">(4+4 Pin 12V EPS - source mindfactory.de)</p>
But what if your PSU only has a 4+4 Pin EPS cable? What do I have to do? Do I need a new PSU?

Simply. No. Just put the 4+4 Pin into the 8 Pin and you are good to go.

Wait CornFlakes! What’s with the extra 4 Pin next to the 8 Pin? Good question, also very simple to answer.
You don’t need it. Kind of. If your PSU does have a 4+4 Pin and a Single 4 Pin EPS connect them all to 8 and 4 Pin. The optional 4 Pin is to smooth out the power (Energy can be dirty, that's not a joke) and is mostly just needed if you do Overclocking with LN2 (Liquid Nitrogen). But if your PSUs support it, plug it in. It can’t hurt your System.

But what if your PSU only has a single 4 Pin? You may have guessed it, also very simple. Just Put it in the first 4 Pins on your 8 Pin. 

Most modern Motherboards come with at least an 8 Pin EPS. Older Motherboards were using a single 4 Pin EPS. Which was enough back in the days, today's CPUs are much more complex.

<p style="text-align: center;"><img src="../../assets/images/wiki/12VEPS/4Pin_ATX.png"/></p>
<p style="text-align:center;font-size:10px">(4 Pin EPS 12V - credit u/CornFlakes1991)</p>

I recommend buying a new PSU anyway when your existing one has only a single 4 Pin. It’s outdated and you can run into issues such as system instability or random crashes. 
Also, you were able to buy a new system. Why cheaping out on a PSU?

***

Below of this guide you will find all the EPS standards which exist to the day of writing.

<p style="text-align: center;"><img src="../../assets/images/wiki/12VEPS/4Pin_ATX.png"/></p>
<p style="text-align:center;font-size:10px">(4 Pin EPS 12V - credit u/CornFlakes1991)</p>
<p style="text-align: center;">4 Pin ATX introduced with the ATX standard. Deprecated. Can deliver up 192W</p>


<p style="text-align: center;"><img src="../../assets/images/wiki/12VEPS/8Pin_EPS.png"/></p>
<p style="text-align:center;font-size:10px">(8 Pin EPS 12V - credit u/CornFlakes1991)</p>
<p style="text-align: center;">Successor of the 4 Pin as CPU’s needed more power under full load. Can deliver up to 384W</p>


<p style="text-align: center;"><img src="../../assets/images/wiki/12VEPS/8+4Pin_EPS.png"/></p>
<p style="text-align:center;font-size:10px">(8+4 Pin EPS 12V - credit u/CornFlakes1991)</p>
<p style="text-align: center;">8+4 Pin EPS. Can deliver 384W + optional 192W. Useful for overclocking and for smoothing power.</p>

 
<p style="text-align: center;"><img src="../../assets/images/wiki/12VEPS/8+8Pin_EPS.png"/></p>
<p style="text-align:center;font-size:10px">(8+8 Pin EPS 12V - credit u/CornFlakes1991)</p>
<p style="text-align: center;">8+8 Pin EPS. Totally overkill for the average user. Can deliver up to 784W if both connectors are connected. Useful for heavy overclocking with LN2 or Liquid Helium.</p>