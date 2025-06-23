---
title: Santroller Powered Keyboards
sidebar: controllers_sidebar
permalink: ctrls_modkeys_san
folder: instruments
tags: [modded, midi, keyboards, english]
summary: "How to connect and configure your keyboards using Santroller on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/santroller.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/sancontroller.png" alt="Controller" title="Controller"></div>

## NOTES
<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/rpcs3nomap.png" alt="Do not map this controller!" title="Do not map!"></div>
<div align="center"> <b>Do NOT map this instrument via the "Pads" menu!</b></div>

* **Please note that your Santroller Configurator may have different settings, depending on how your keyboard is connected.** If you purchased an premade adapter, contact the seller for more information.
	* Xbox 360 Wireless Keyboards **require an Xbox 360 Wireless Gaming Receiver for Windows to connect to your computer.**  
	![Xbox 360 Wireless Gaming Receiver for Windows](https://rb3pc.milohax.org/images/btns/ctrls/360/receiver.png "Xbox 360 Wireless Gaming Receiver for Windows")
	* Nintendo Wii Wireless Keyboards **require their respective dongle**.  
	![Nintendo Wii Wireless Receiver](https://rb3pc.milohax.org/images/btns/ctrls/wii/reckeys.png "Nintendo Wii Wireless Keyboard Receiver")  

## Setup

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>Before starting, make sure you stop Rock Band 3's emulation in RPCS3.</b> {{include.content}}</div>

Be sure to [[download the latest version of Santroller]](https://github.com/santroller/santroller/releases/latest){:target="_blank"}.

After that, start up Santroller.

In the start screen, select your "`Device to program`", "`Connection Method`", and "`Device to Emulate`". This will usually be "`Raspberry Pi Pico`", "`USB Adapter`", and "`Pro Keys`"  respectively.  
After selecting your options, click on `Configure`.

![A screenshot of Santroller's first screen. "Selected Device" is set to Raspberry Pi Pico and Input Type is set to "Directly Wired".](https://rb3pc.milohax.org/images/instruments/xtra/san/initkeys.png "Santroller: Initialize")

In "`Controller Settings`", change the following:
* Set "`Device to Emulate`" to "`Pro Keys`"
* Enable "`Use USB Passthrough with RPCS3`"

![A screenshot of Santroller's Controller Settings. The settings reflect exactly what is above.](https://rb3pc.milohax.org/images/instruments/xtra/san/consetkeys.png "Santroller: Controller Settings")

**MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of Santroller. The cursor is hovering over "Save Settings".](https://rb3pc.milohax.org/images/instruments/xtra/san/savesan.png "Santroller")

When you're done, close Santroller.

You can now launch Rock Band 3!

<div markdown="span" class="alert alert-danger" role="alert"><i class="fa fa-exclamation-circle"></i> <b>Make sure Santroller is closed before starting Rock Band 3!!! Having Santroller open while launching Rock Band 3 will cause passthrough to fail, which means your keyboard will not connect!!! </b> {{include.content}}</div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption){:target="_blank"}, [[gonakil1ya]](https://gonakillya.neocities.org){:target="_blank"}, and [[SquidBoy425 (Team Oceanman)]](https://www.youtube.com/@teamOceanman343/videos){:target="_blank"}.  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures.
