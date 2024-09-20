---
title: Santroller Powered Custom Guitars
sidebar: controllers_sidebar
permalink: ctrls_mod_santroller
folder: instruments
tags: [xbox-360, midi, english]
summary: "How to connect and configure Xbox 360 Wireless keyboards (MIDI) on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/santroller.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rcmgtrs.png" alt="Controller" title="Controller"></div>

## NOTES

* **Please note that your Santroller Configurator may have different settings, depending on how your guitar was modded.** If you purchased your guitar pre-modded, contact the seller for more information.

## Pad Information

| Handlers | Devices |
|:--------:|:-------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Guitar | Rock Band |

## Setup

If you haven't initlized your controller yet, start up Santroller.

In the start screen, select your Device. This will depend on what device your modded guitar has. In the tutorial screenshots, it was a "`Raspberry Pi Pico`".
After that, click on Configure.

![A screenshot of Santroller's first screen. "Selected Device" is set to Raspberry Pi Pico.](https://rb3pc.milohax.org/images/instruments/xtra/san/initsan.png "initsan")

In Controller Settings, set your configuration to the following:
* Emulation Type: Controller
* Controller Type: Rock Band Guitar
* Swap Switch Face Buttons: (Depends on your guitar)
* Windows Controller Mode: HID Game Controller
* Use USB Passthrough with RPCS3: Disabled
* Tilt: Enabled

![A screenshot of Santroller's Controller Settings. The settings reflect exactly what is above.](https://rb3pc.milohax.org/images/instruments/xtra/san/consetsan.png "Santroller: Controller Settings")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Whammy section and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of RetroCultMods Programming Tool. The cursor is hovering over "Save Settings".](https://rb3pc.milohax.org/images/instruments/xtra/san/savesan.png "RetroCultMods Programming Tool")

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
| D-Pad: Left | ![D-Pad: Left](https://rb3pc.milohax.org/images/btns/gtrs/dpl.png "D-Pad: Left") |
| D-Pad: Right | ![D-Pad: Right](https://rb3pc.milohax.org/images/btns/gtrs/dpr.png "D-Pad: Right") |
| Right Stick: <br/> Left/Right | ![Whammy Bar](https://rb3pc.milohax.org/images/btns/gtrs/wb.png "Whammy Bar") |
| R1 | ![Tilt](https://rb3pc.milohax.org/images/btns/gtrs/ts.png "Tilt") |
| Start | ![Start](https://rb3pc.milohax.org/images/btns/ctrls/360/start.png "Start") |
| Select | ![Back](https://rb3pc.milohax.org/images/btns/ctrls/360/back.png "Back") |
| PS Button | ![Home](https://rb3pc.milohax.org/images/btns/gtrs/home.png "Home") |

### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

## Profile

[[Download Profile]](https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/instrument-repo/RetroCultMods%20Solderless%20Kit.7z)

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/rcmslmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption).  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures.