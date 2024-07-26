---
title: RetroCultMods V3 Wii Adapter
author: Carl Mylo
date: 
category: Instruments
layout: post
---

<div align="center"> <img src="https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/plat/santroller.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/cont/wiilpcontroller.png" alt="Controller" title="Controller"></div>

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

In the start screen, select your Device. It will usually show up as `Raspberry Pi Pico`.
After that, select `"Wii Adapter"`` as your Device Type.
Then finally, set Device Variant to "RCM Wii Guitar Adapter - Default". **You don't need Auth, Slider, or Joystick** support.

After that, click on Erase and configure and wait for the progress bar to finish.

When it finishes, click on Configure.

In Controller Settings, set your configuration to the following:
* Swap Switch Face Buttons: (Depends on your guitar)
* Windows Controller Mode: HID Game Controller
* Slider Bar: (Depends on your guitar)
* Tilt: Enabled

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Wii Extension Inputs and calibrate it.

**MAKE SURE YOU CLICK ON `"WRITE SETTINGS"` before closing the program or you will lose progress!**


## Mappings

* **To map everything correctly, you will need to first map Whammy Down, which is Right Stick: Left in RPCS3. It should show up as X-. After mapping it, click `"Filter Noise"` and map the rest.**

| **RPCS3**          | **Controller** |
|:------------------:|:---------------------:|
| Cross | ![Green Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Blue Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/bf.png "Blue Fret") |
| Triangle | ![Yellow Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/yf.png "Yellow Fret") |
| L1 | ![Orange Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/sbd.png "Strumbar Down") |
| Right Stick: <br/> Left/Right | ![Whammy Bar](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/wb.png "Whammy Bar") |
| R1 | ![Tilt](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/ts.png "Tilt") |
| Start | ![Plus](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/wii/plu.png "Plus") |
| Select | ![Minus](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/wii/min.png "Minus") |
| PS Button | ![Home](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/home.png "Home") |


### Passthrough Mode

> ##### WARNING
>
> _As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently **not** recommended._
{: .block-warning  }

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20%5BPi%20Pico%5D.7z)

<div align="center"> <img src="https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/maps/picolpmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption)