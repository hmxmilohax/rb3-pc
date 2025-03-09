---
title: RetroCultMods V3 Adapter Guitars
sidebar: controllers_sidebar
permalink: ctrls_modgtr_rcmv3
folder: instruments
tags: [guitars, modded, english]
summary: "How to connect and configure a guitar connected via V3 Wii/USB Adapter RCM on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/rcm.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/wiighgtrscontroller.png" alt="Controller" title="Controller"></div>

## NOTES
<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/rpcs3nomap.png" alt="Do not map this controller!" title="Do not map!"></div>
<div align="center"> <b>Do NOT map this instrument via the "Pads" menu!</b></div>

* **This is specifically for the** [**[V3 Wii/USB Adapter WITH TILT by RetroCultMods]**](https://shop.retrocultmods.com/products/v3-wii-adapter-for-clone-hero-and-rb4-rock-band-4){:target="_blank"}**!** Please consult your sales receipt to confirm that it is indeed a V3 Wii/USB Guitar Adapter WITH TILT by RetroCultMods.
    * You can use this page for reference for V1 and V2 Wii Adapters, but you won't have tilt.

## Setup

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>Before starting, make sure you stop Rock Band 3's emulation in RPCS3.</b> {{include.content}}</div>

Before starting, be sure to [[download the latest version of RCM Programming Tool]](https://retrocultmods.com/programming-tool/){:target="_blank"}.

Start up up RCM Programming Tool.

In the start screen, select your Device. It will usually show up as "`V3 Adapter - Guitar (PS2/Emulation)`".  
After that, click on "`Configure`" and wait for the progress bar to finish.

![A screenshot of RCM Programming Tool's first screen. "`Selected Device`" is set to Raspberry Pi Pico and Input Type is set to "Directly Wired".](https://rb3pc.milohax.org/images/instruments/xtra/rcm/seldevv3.png "RCM Programming Tool: Initialize")

In "`Controller Settings`", change the following:
* Enable "`Use USB Passthrough with RPCS3`"

![A screenshot of RCM Programming Tool's Controller Settings. The settings reflect exactly what is above.](https://rb3pc.milohax.org/images/instruments/xtra/rcm/conset.png "RCM Programming Tool: Controller Settings")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Whammy section and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of RCM Programming Tool. The cursor is hovering over "Save Settings".](https://rb3pc.milohax.org/images/instruments/xtra/rcm/savev3.png "RCM Programming Tool")

When you're done, close RCM Programming Tool.

You can now launch Rock Band 3!

<div markdown="span" class="alert alert-danger" role="alert"><i class="fa fa-exclamation-circle"></i> <b>Make sure RCM Programming Tool is closed before starting Rock Band 3!!! Having RCM Programming Tool open while launching Rock Band 3 will cause passthrough to fail, which means your guitar will not connect!!! </b> {{include.content}}</div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption), [[gonakil1ya]](https://linktr.ee/Gonakil1ya){:target="_blank"}, and [[SquidBoy425 (Team Oceanman)]](https://www.youtube.com/@teamOceanman343/videos){:target="_blank"}.  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures.