---
title: Nintendo Wii Guitar Hero Guitars (WiitarThing)
sidebar: controllers_sidebar
permalink: ctrls_ghwtr_wii
folder: instruments
tags: [wii, guitars, english]
summary: "How to setup Nintendo Wii Guitar Hero guitars on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/plat/wii.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/cont/rcmgtrswii.png" alt="Controller" title="Controller"></div>

## NOTES

* Requires installing and running [[**WiitarThing**]](https://github.com/Meowmaritus/WiitarThing){:target="_blank"} along with its dependencies.
* This configuration **requires connecting wirelessly via Bluetooth**. You need a Bluetooth receiver to connect to your computer.
    * It's suggested to mod your guitar into a wired one with a solution like [[RetroCultMods' Solderless DIY RGB Kit]](https://www.etsy.com/listing/1505287559/solderless-diy-rgb-kit-for-guitar-hero){:target="_blank"}.
* **Tilt is busted on this controller!**
    * It's suggested to mod your guitar into a wired one with a solution like [[RetroCultMods' Solderless DIY RGB Kit]](https://www.etsy.com/listing/1505287559/solderless-diy-rgb-kit-for-guitar-hero){:target="_blank"}.
* RPCN Menus (for sending or accepting online invites) may cause a softlock. You may need an alternative input method to navigate these menus, such as [[a typing keyboard or a gamepad]](https://carlmylo.github.io/rb3-pc/ctrls_pads){:target="_blank"}.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Guitar Hero |

## Mapping

By default, XInput has most things bound correctly. You only need to adjust the following:

**UNMAP THE FOLLOWING** or guitar solos will auto-strum!  
Use Right Click to unmap a button.

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| L2 | ![Left Trigger](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/lt.png "Left Trigger") | Solo Modifier |

**Change the following** or blue and yellow frets will be inverted!

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| Square | ![Y Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/y.png "Y Button") | ![Yellow Fret](https://carlmylo.github.io/rb3-pc/images/btns/gtrs/yf.png "Yellow Fret") | 
| Triangle | ![X Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/x.png "X Button") | ![Blue Fret](https://carlmylo.github.io/rb3-pc/images/btns/gtrs/bf.png "Blue Fret") |

Guitar Hero controllers tend to misbehave and **refuse to map sometimes. If you try mapping a button and always get "U+" or something similar, click "Filter Noise"** at the bottom left of the controller configuration window **then try mapping**.

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/maps/gtrwiiwtarmapping.png" alt="Mapping" title="Mapping"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#advanced-mapping">Advanced Mapping</a>
                            </h4>
                        </div>
                        <div id="advanced-mapping" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<h4 id="profile">Profile</h4>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Xbox%20360%20Guitar%20Hero%20Guitar.7z">[Download Profile]</a></p>

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
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/ts.png" alt="Tilt" title="Tilt Vertical"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/ts.png" alt="Tilt" title="Tilt Horizontal"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/plu.png" alt="Plus" title="Plus"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/back.png" alt="min" title="Minus"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Back to Controllers]](https://carlmylo.github.io/rb3-pc/ctrls#instrument-list)

Mapped by [diogodiogo2]