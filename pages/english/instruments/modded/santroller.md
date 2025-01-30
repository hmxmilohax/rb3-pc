---
title: Santroller Powered Custom Guitars
sidebar: controllers_sidebar
permalink: ctrls_mod_santroller
folder: instruments
tags: [guitars, modded, english]
summary: "How to connect and configure your guitar using Santroller on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/santroller.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/rcmgtrs.png" alt="Controller" title="Controller"></div>

## NOTES

* **Please note that your Santroller Configurator may have different settings, depending on how your guitar was modded.** If you purchased your guitar pre-modded, contact the seller for more information.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Setup

If you haven't initialized your controller yet, start up Santroller.

In the start screen, select your Device and Input Type. This will depend on what device your modded guitar has. In the tutorial screenshots, it was a "`Raspberry Pi Pico`" and "`Directly Wired`" respectively.
After it finishes, click on `Configure`.

![A screenshot of Santroller's first screen. "Selected Device" is set to Raspberry Pi Pico and Input Type is set to "Directly Wired".](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/san/initsan.png "Santroller: Initialize")

In Controller Settings, set your configuration to the following:
* Emulation Type: Controller
* Controller Type: Rock Band Guitar
* Swap Switch Face Buttons: (Depends on your guitar)
* Windows Controller Mode: XInput
* Use USB Passthrough with RPCS3: Disabled
* Map Select D-Pad Left on Xbox One/Series: Disabled
* Tilt: Enabled
* Map joystick to Dpad: Enabled

![A screenshot of Santroller's Controller Settings. The settings reflect exactly what is above.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/san/consetsan.png "Santroller: Controller Settings")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Whammy section and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of Santroller. The cursor is hovering over "Save Settings".](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/san/savesan.png "Santroller")

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

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Santroller%20Guitar.7z){:target="_blank"}

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/modsangtrmapping.png" alt="Mapping" title="Mapping"></div>

### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

[[Back to Controllers]](https://carlmylo.github.io/docu-rpcs3/ctrls#instrument-list)

Research by [[Lynxeption]](https://www.youtube.com/@Lynxeption).  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures.