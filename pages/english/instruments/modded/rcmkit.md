---
title: RetroCultMods Kit Guitars
sidebar: controllers_sidebar
permalink: ctrls_mod_rcmgtr
folder: instruments
tags: [guitars, modded, english]
summary: "How to connect and configure your guitar modded with a kit from RCM on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/rcm.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/rcmgtrs.png" alt="Controller" title="Controller"></div>

## NOTES

* **This page is specifically for guitars using modded kits made by [[RetroCultMods]](https://shop.retrocultmods.com/)!** Check your receipt from either the [[RetroCultMods' own website]](https://www.etsy.com/shop/RetroCultMods) or [[Etsy]] to verify that you indeed have a guitar using a mod kit from RetroCultMods.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Setup

If you haven't initialized your controller yet, start up RetroCultMod's Programming Tool.

In the start screen, select your `Device`. It will show up as "`Raspberry Pi Pico`".  
After that, select your `Device Type` depending on which RetroCultMod product you have.  
Then finally, set `Device Variant`. **`Default` is fine**! Rock Band 3 on RPCS3 doesn't need need Auth, Slider, or Joystick support.  
After that, click on `Erase and configure` and wait for the progress bar to finish.

In this example, a [[RetroCultMods Solderless Kit]](https://shop.retrocultmods.com/products/solderless-diy-rgb-kit-for-guitar-hero-controllers-by-retrocultmods) was used.

![A screenshot of RetroCultMods Programming Tool. "Selected Device" is set to Raspberry Pi Pico, "Device Type" is set to "Zeroboard SL (Solderless Kit)", and Device Variant is set to "Zeroboard SL - Default."](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/rcm/initsl.png "RetroCultMods Programming Tool")

After that, or if you already have an initialized controller, click on `Configure`.

![A screenshot of RetroCultMods Programming Tool. "Selected Device" is set to "Zeroboard SL - Default" and the mouse is hovering over "Configure."](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/rcm/seldevsl.png "RetroCultMods Programming Tool")

In Controller Settings, set your configuration to the following:
* Swap Switch Face Buttons: (Depends on your guitar)
* Windows Controller Mode: XInput
* Use USB Passthrough with RPCS3: Disabled
* Map Select D-Pad Left on Xbox One/Series: Disabled
* Tilt: Enabled
* Map joystick to Dpad: Enabled

![A screenshot of RetroCultMods Programming Tool. The settings reflect exactly what is above.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/rcm/conset.png "RetroCultMods Programming Tool")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Whammy section and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of RetroCultMods Programming Tool. The cursor is hovering over "Save Settings".](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/rcm/savesl.png "RetroCultMods Programming Tool")

## Mappings

By default, XInput has most things bound correctly. You only need to remap the following:

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| R1 | ![Right Stick](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/rs.png "Right Stick") | ![Tilt](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png "Tilt") | 

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#advanced-mapping">Advanced Mapping</a>
                            </h4>
                        </div>
                        <div id="advanced-mapping" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Guitar</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/gf.png" alt="Green Fret" title="Green Fret"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/rf.png" alt="Red Fret" title="Red Fret"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/of.png" alt="Orange Fret" title="Orange Fret"></td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbu.png" alt="Strumbar Up" title="Strumbar Up"></td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbd.png" alt="Strumbar Down" title="Strumbar Down"></td>
</tr>
<tr>
<td align="center">D-Pad: Left</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpl.png" alt="D-Pad: Left" title="D-Pad: Left"></td>
</tr>
<tr>
<td align="center">D-Pad: Right</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpr.png" alt="D-Pad: Right" title="D-Pad: Right"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Left/Right</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/wb.png" alt="Whammy Bar" title="Whammy Bar"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Up <em>or</em> Down</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/fx.png" alt="Effects Switch" title="Effects Switch"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/solo.png" alt="Solo Buttons" title="Solo Buttons"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png" alt="Tilt" title="Tilt"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/start.png" alt="Plus" title="Start"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/back.png" alt="Minus" title="Back"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/RCM%20Kit%20Guitar.7z){:target="_blank"}

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/modrcmkitgtrmapping.png" alt="Mapping" title="Mapping"></div>

### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

[[Back to Controllers]](https://carlmylo.github.io/docu-rpcs3/ctrls#instrument-list)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption).  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures