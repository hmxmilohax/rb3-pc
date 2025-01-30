---
title: RetroCultMods V3 Adapter Guitars
sidebar: controllers_sidebar
permalink: ctrls_mod_rcmv3
folder: instruments
tags: [guitars, modded, english]
summary: "How to connect and configure a guitar connected via V3 Wii/USB Adapter RCM on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/plat/rcm.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/cont/rcmgtrswii.png" alt="Controller" title="Controller"></div>

## NOTES

* **This is specifically for the** [**[V3 Wii/USB Adapter WITH TILT by RetroCultMods]**](https://shop.retrocultmods.com/products/v3-wii-adapter-for-clone-hero-and-rb4-rock-band-4)**!** Please consult your sales receipt to confirm that it is indeed a V3 Wii/USB Guitar Adapter WITH TILT by RetroCultMods.
	* You can use this page for reference for V1 and V2 Wii Adapters, but you won't have tilt.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Setup

If you haven't initlized your V3 Adapter yet, start up RetroCultMod's Programming Tool.

In the start screen, select your Device. It will usually show up as "`Raspberry Pi Pico`".  
After that, select "`Wii Adapter`" or "`USB Adapter`" as your `Device Type` depending on what you have connected.  
Then finally, set `Device Variant` to `RCM Wii Guitar Adapter - Default`. Rock Band 3 on RPCS3 doesn't need need Auth, Slider, or Joystick support.  
After that, click on `Erase and configure` and wait for the progress bar to finish.

![A screenshot of RetroCultMods Programming Tool. "Selected Device" is set to Raspberry Pi Pico, "Device Type" is set to "Wii Adapter", and Device Variant is set to "RCM Wii Guitar Adapter - Default."](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/rcm/initv3.png "RetroCultMods Programming Tool")

After that, or if you already have an initialized controller, click on `Configure`.

![A screenshot of RetroCultMods Programming Tool. "Selected Device" is set to "RCM Wii Guitar Adapter - Default" and the mouse is hovering over "Configure."](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/rcm/seldevv3.png "RetroCultMods Programming Tool")

In Controller Settings, set your configuration to the following:
* Swap Switch Face Buttons: (Depends on your guitar)
* Windows Controller Mode: XInput
* Use USB Passthrough with RPCS3: Disabled
* Map Select D-Pad Left on Xbox One/Series: Disabled
* Tilt: Enabled
* Map joystick to Dpad: Enabled

![A screenshot of RetroCultMods Programming Tool. The settings reflect exactly what is above.](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/rcm/conset.png "RetroCultMods Programming Tool")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the `Wii Extension Inputs` and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Setting"`" before closing the program or you will lose progress!**

![A screenshot of RetroCultMods Programming Tool. The cursor is hovering over "Save Settings".](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/rcm/savev3.png "RetroCultMods Programming Tool")

## Mappings

By default, XInput has most things bound correctly. You only need to remap the following:

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| R1 | ![Right Stick](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/rs.png "Right Stick") | ![Tilt](https://carlmylo.github.io/rb3-pc/images/btns/gtrs/ts.png "Tilt") | 

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
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/gf.png" alt="Green Fret" title="Green Fret"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/rf.png" alt="Red Fret" title="Red Fret"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/of.png" alt="Orange Fret" title="Orange Fret"></td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/sbu.png" alt="Strumbar Up" title="Strumbar Up"></td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/sbd.png" alt="Strumbar Down" title="Strumbar Down"></td>
</tr>
<tr>
<td align="center">D-Pad: Left</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/dpl.png" alt="D-Pad: Left" title="D-Pad: Left"></td>
</tr>
<tr>
<td align="center">D-Pad: Right</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/dpr.png" alt="D-Pad: Right" title="D-Pad: Right"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Left/Right</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/wb.png" alt="Whammy Bar" title="Whammy Bar"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Up <em>or</em> Down</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/fx.png" alt="Effects Switch" title="Effects Switch"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/solo.png" alt="Solo Buttons" title="Solo Buttons"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/ts.png" alt="Tilt" title="Tilt"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/start.png" alt="Plus" title="Start"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/back.png" alt="Minus" title="Back"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/home.png" alt="Home" title="Home"></td>
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

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/RCM%20V3%20Adapter%20Guitar.7z){:target="_blank"}

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/maps/modrcmv3gtrmapping.png" alt="Mapping" title="Mapping"></div>

### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

[[Back to Controllers]](https://carlmylo.github.io/rb3-pc/ctrls#instrument-list)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption)  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures