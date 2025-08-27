---
title: Rock Band 3 Pro Guitars
sidebar: controllers_sidebar
permalink: ctrls_protar_midi
folder: instruments
tags: [midi, protars, english]
summary: "How to connect and configure Rock Band 3 Pro Guitars on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/midi.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rbprotar.png" alt="Controller" title="Controller"></div>

## NOTES
<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/rpcs3nomap.png" alt="Do not map this controller!" title="Do not map!"></div>
<div align="center"> <b>Do NOT map this instrument via the "Pads" menu!</b></div>

* RPCN Menus (for sending or accepting online invites) will cause a softlock. You will need an alternative input method to navigate these menus, such as a typing keyboard or a gamepad.
* This is meant for players that have their PRO Guitars connected via a MIDI to USB interface.

## SYSEX Notice

**You need a MIDI to USB Interface that has SYSEX support!** Consult your MIDI to USB interface's manual or manufacturer for more details.

| Verified <br> MIDI to USB interfaces |
|:------------------:|
| **CME** <br> C2MIDI Pro |
| **CME** <br> U2MIDI Pro |
| **Focusrite** <br> Scarlett (4i4 and higher) [3rd Gen] |
| **M-Audio** <br> Midisport Uno |
| **MOTU** <br> M2/M4 |
| **Roland** <br> UM-ONE mk2 |
| **SSL** <br> +2 MKII |

## Instructions

To connect your Rock Band 3 Pro Guitar, you will need to connect to the MIDI port on the bottom.

>![A picture of a Rock Band 3 Mustang Pro Guitar, showing a 5-DIN MIDI output highlighted in blue with a dotted white outline.](https://rb3pc.milohax.org/images/midi/midimustang.png "Rock Band Mustang Pro Guitar")  

>![A picture of a Rock Band 3 Squier Stratocaster Pro Guitar showing a 5-DIN MIDI output highlighted in blue with a dotted white outline.](https://rb3pc.milohax.org/images/midi/midisquier.png "Rock Band Squier Stratocaster Pro Guitar")  

**To connect it to your computer, you will need a MIDI to USB interface**.

Here's an example of a MIDI to USB interface. Most will come with an LED indicator to show activity. **To check that you've plugged it in correctly, you should see "MIDI In" blinking when you press a key**. 

>![A picture of a MIDI to USB interface.](https://rb3pc.milohax.org/images/midi/miditousb.png "MIDI to USB interface")  

**If you have an audio interface, you may already have a way to plug in MIDI** to your computer, as some audio interfaces come with MIDI inputs. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](https://rb3pc.milohax.org/images/midi/midifs.png "Focusrite Scarlett MIDI in/out") 

Once again, you need [[a MIDI to USB Interface that has SYSEX support]](#sysex-notice)

Find whichever way is the most convenient for you then connect your Rock Band Pro Guitar to your computer.

![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://rb3pc.milohax.org/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline.](https://rb3pc.milohax.org/images/cust/iog.png "I/O")

* ![A tan square with a solid outline](https://rb3pc.milohax.org/images/cust/smalltan.png "Tan Square") :
	* 🎸 **Change your “Emulated MIDI type” from “Keyboard” to “Guitar (17 Frets)” if you have a Mustang Pro Guitar, or “Guitar (22 Frets)” if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it.**

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Implementation by [[Dark]](https://dark.ski/)