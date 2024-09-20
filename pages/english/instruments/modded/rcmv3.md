---
title: RetroCultMods V3 Wii Adapter Guitars
sidebar: controllers_sidebar
permalink: ctrls_mod_rcmv3
folder: instruments
tags: [xbox-360, midi, english]
summary: "How to connect and configure Xbox 360 Wireless keyboards (MIDI) on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/rcm.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rcmgtrswii.png" alt="Controller" title="Controller"></div>

## NOTES

* **This is specifically for the** [**[V3 Wii Guitar Adapter WITH TILT for Clone Hero and RB4 (Rock Band 4) by RetroCultMods]**](https://www.etsy.com/listing/1536358024/v3-wii-guitar-adapter-with-tilt-for)**!** Please consult your sales receipt to confirm that it is indeed a V3 Wii Guitar Adapter WITH TILT for Clone Hero and RB4 (Rock Band 4) by RetroCultMods.
	* You can use this page for reference for V1 and V2 Wii Adapters, but you won't have tilt.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Setup

If you haven't initlized your Wii Adapter yet, start up RetroCultMod's Programming Tool.

In the start screen, select your Device. It will usually show up as "`Raspberry Pi Pico`".
After that, select "`Wii Adapter`" as your Device Type.
Then finally, set Device Variant to "RCM Wii Guitar Adapter - Default". **You don't need Auth, Slider, or Joystick** support.

![A screenshot of RetroCultMods Programming Tool. "Selected Device" is set to Raspberry Pi Pico, "Device Type" is set to "Wii Adapter", and Device Variant is set to "RCM Wii Guitar Adapter - Default."](https://rb3pc.milohax.org/images/instruments/xtra/rcmpt/initv3.png "RetroCultMods Programming Tool")

After that, click on Erase and configure and wait for the progress bar to finish.

When it finishes, click on Configure.

![A screenshot of RetroCultMods Programming Tool. "Selected Device" is set to "RCM Wii Guitar Adapter - Default" and the mouse is hovering over "Configure."](https://rb3pc.milohax.org/images/instruments/xtra/rcmpt/seldevv3.png "RetroCultMods Programming Tool")

In Controller Settings, set your configuration to the following:
* Swap Switch Face Buttons: (Depends on your guitar)
* Windows Controller Mode: HID Game Controller
* Slider Bar: (Depends on your guitar)
* Tilt: Enabled

![A screenshot of RetroCultMods Programming Tool. The settings reflect exactly what is above.](https://rb3pc.milohax.org/images/instruments/xtra/rcmpt/consetsl.png "RetroCultMods Programming Tool")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Wii Extension Inputs and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Setting"`" before closing the program or you will lose progress!**

![A screenshot of RetroCultMods Programming Tool. The cursor is hovering over "Save Settings".](https://rb3pc.milohax.org/images/instruments/xtra/rcmpt/savev3.png "RetroCultMods Programming Tool")

## Mappings

* **To map everything correctly, you will need to first map Whammy Down, which is Right Stick: Left in RPCS3. It should show up as X-. After mapping it, click `"Filter Noise"` and map the rest.**

| **RPCS3**          | **Controller** |
|:------------------:|:---------------------:|
| Cross | ![Green Fret](https://rb3pc.milohax.org/images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](https://rb3pc.milohax.org/images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Blue Fret](https://rb3pc.milohax.org/images/btns/gtrs/bf.png "Blue Fret") |
| Triangle | ![Yellow Fret](https://rb3pc.milohax.org/images/btns/gtrs/yf.png "Yellow Fret") |
| L1 | ![Orange Fret](https://rb3pc.milohax.org/images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](https://rb3pc.milohax.org/images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](https://rb3pc.milohax.org/images/btns/gtrs/sbd.png "Strumbar Down") |
| Right Stick: <br/> Left/Right | ![Whammy Bar](https://rb3pc.milohax.org/images/btns/gtrs/wb.png "Whammy Bar") |
| R1 | ![Tilt](https://rb3pc.milohax.org/images/btns/gtrs/ts.png "Tilt") |
| Start | ![Plus](https://rb3pc.milohax.org/images/btns/ctrls/wii/plu.png "Plus") |
| Select | ![Minus](https://rb3pc.milohax.org/images/btns/ctrls/wii/min.png "Minus") |
| PS Button | ![Home](https://rb3pc.milohax.org/images/btns/gtrs/home.png "Home") |


### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

## Profile

[[Download Profile]](https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20%5BPi%20Pico%5D.7z)

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/picolpmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption)  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures