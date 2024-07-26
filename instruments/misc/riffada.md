---
title: Riffmaster (via Adafruit Feather)
author: Carl Mylo
date: 
category: Instruments
layout: post
---

<div align="center"> <img src="https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/plat/santroller.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/cont/riffmastercontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* **This is specifically for the** [**[Adafruit Feather RP2040 with USB Type A Host]**](https://www.adafruit.com/product/5723)**!** Please consult your sales receipt to confirm that it is indeed an [[Adafruit Feather RP2040 **with USB Type A Host**]](https://www.adafruit.com/product/5723).
* While you can use the Xbox One Riffmaster too but you should just use [[RB4InstrumentMapper]](https://carlmylo.github.io/rpcs3guidetesting/instruments/xbox/rb4gtrs) for that instead.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | Joystick |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Setup

Download the latest version of Santroller.

[![A screenshot of Santroller's Github download page, hovering over the Windows installer.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/xtra/feather/dlsan.png)](https://github.com/Santroller/Santroller/releases "SantrollerConfigurator")

After downloading Santroller, open "SantrollerConfigurator".

![A screenshot of a cursor hovering over SantrollerConfigurator on a user's desktop](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/xtra/feather/opensan.png "SantrollerConfigurator")

Hold the "Boot" button on your Adafruit Feather RP2040 with USB Type A Host if you're plugging it into your computer for the first time.

![A picture of an Adafruit Feather RP2040. A button labeled "Boot" is circled in white, red, and black.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/xtra/feather/bootada.jpg "Adafruit Feather RP2040 with USB Type A Host")

In SantrollerConfigurator, set "`Input Type`" to "`USB Adapter`." The Adafruit Feather RP2040 with USB Type A Host should be detected as "`Raspberry Pi Pico`." Click "`Configure`" after doing this.

![A screenshot of SantrollerConfigurator, with a cursor hovering over "USB Adapter," next to "Input Type."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/xtra/feather/sanusb.png "SantrollerConfigurator")

Give it a moment to program initial configuration. When prompted, click on "`Configure`" again.
![A screenshot of SantrollerConfigurator, with a cursor hovering over "USB Adapter," next to "Input Type."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/xtra/feather/sanconf.png "SantrollerConfigurator")

After you've loaded into the configuration page, scroll down to the "`Presets`" section and click to expand it. Once expanded, click on "`Import Settings from File`"

A community made preset exists (courtesy of jnack) to help speed things up. Load it up via the "Import Settings from File" option.  
[[Download the picoconfig preset here]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/RiffmasterFeather.picoconfig)

![A screenshot of SantrollerConfigurator, with a cursor hovering over "Import Settings from File" under the "Presets" configuration.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/xtra/feather/sanpreload.png "Presets")

After loading the preset, **MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

### Additional Notes
The picoconfig preset binds a few things for a better experience.
- The "Boot" button on the Adafruit Feather RP2040 with USB Type A Host will act as a guide button as pressing and holding the guide button on the Riffmaster shuts it off.
- D-Pad: Left and Select are swapped as the PlayStation Riffmaster. This is because, by default, the PlayStation Riffmaster has Overdrive activation bound to D-Pad Left which is very uncomfortable.

If you wish to remove these tweaks, click the "`Remove`" next to the D-pad Left and Back buttons at the bottom of Santroller Configurator.

![A screenshot of SantrollerConfigurator, scrolled to the bottom. There are circles over the "Remove" buttons next to Back and D-pad Left.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/xtra/feather/sanrem.png "SantrollerConfigurator")

After that, go to the "`Usb Host Inputs`" section and enable the original buttons again.

![A screenshot of SantrollerConfigurator, in the "Usb Host Inputs" section. There are circles over the disabled Back and D-pad Left buttons, showing them as disabled.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/xtra/feather/sanhostin.png "Usb Host Inputs")


## Mappings

| **RPCS3**          | **Controller** |
|:------------------:|:---------------------:|
| Cross | ![Green Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Yellow Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/yf.png "Yellow Fret") |
| Triangle | ![Blue Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/bf.png "Blue Fret") |
| L1 | ![Orange Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/sbd.png "Strumbar Down") |
| D-Pad: Left | ![D-Pad: Left](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/dpl.png "D-Pad: Left") |
| D-Pad: Right | ![D-Pad: Right](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/dpr.png "D-Pad: Right") |
| Right Stick: <br/> Left/Right | ![Whammy Bar](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/wb.png "Whammy Bar") |
| Right Stick: <br/> Up *or* Down | ![Effects Switch](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/fx.png "Effects Switch") |
| L2 | ![Solo Buttons](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/solo.png "Solo Buttons") |
| R1 | ![Tilt](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/ts.png "Tilt") |
| Start | ![Plus](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/360/start.png "Start") |
| Select | ![Minus](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/360/back.png "Back") |
| PS Button | ![Home](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/home.png "Home") |

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Feather%20Riffmaster.7z)

<div align="center"> <img src="https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/maps/360rbgtrsmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Research by [jnackmclain](https://github.com/jnackmclain)