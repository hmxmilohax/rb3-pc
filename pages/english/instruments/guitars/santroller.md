---
title: Santroller Powered Guitars
sidebar: controllers_sidebar
permalink: ctrls_modgtr_san
folder: instruments
tags: [guitars, modded, english]
summary: "How to connect and configure your guitar using Santroller on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/santroller.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/sancontroller.png" alt="Controller" title="Controller"></div>

## NOTES
<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/rpcs3nomap.png" alt="Do not map this controller!" title="Do not map!"></div>
<div align="center"> <b>Do NOT map this instrument via the "Pads" menu!</b></div>

* **Please note that your Santroller Configurator may have different settings, depending on how your guitar was modded.** If you purchased your guitar pre-modded, contact the seller for more information.

## Setup

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>Before starting, make sure you stop Rock Band 3's emulation in RPCS3.</b> {{include.content}}</div>

If you haven't initialized your controller yet, start up Santroller.

Be sure to [[download the latest version of Santroller]](https://github.com/santroller/santroller/releases/latest){:target="_blank"}.

In the start screen, select your "`Device to program`", "`Connection Method`", and "`Device to Emulate`". This will depend on what device you're using for your drums. In the tutorial screenshots, it was a "`Raspberry Pi Pico`", "`USB Adapter`", and "`Rock Band Guitar`"  respectively.  
After selecting your options, click on `Configure`.

![A screenshot of Santroller's first screen. "Selected Device" is set to Raspberry Pi Pico and Input Type is set to "Directly Wired".](https://rb3pc.milohax.org/images/instruments/xtra/san/initgtr.png "Santroller: Initialize")

In `Controller Settings`, change the following:
* Set `Device to Emulate` to `Rock Band Guitar`
* Enable `Use USB Passthrough with RPCS3`

![A screenshot of Santroller's Controller Settings. The settings reflect exactly what is above.](https://rb3pc.milohax.org/images/instruments/xtra/san/consetgtr.png "Santroller: Controller Settings")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Whammy section and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of Santroller. The cursor is hovering over "Save Settings".](https://rb3pc.milohax.org/images/instruments/xtra/san/savesan.png "Santroller")

When you're done, close Santroller.

You can now launch Rock Band 3!

<div markdown="span" class="alert alert-danger" role="alert"><i class="fa fa-exclamation-circle"></i> <b>Make sure Santroller is closed before starting Rock Band 3!!! Having Santroller open while launching Rock Band 3 will cause passthrough to fail, which means your guitar will not connect!!! </b> {{include.content}}</div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption){:target="_blank"}, [[gonakil1ya]](https://linktr.ee/Gonakil1ya){:target="_blank"}, and [[SquidBoy425 (Team Oceanman)]](https://www.youtube.com/@teamOceanman343/videos){:target="_blank"}.  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures.