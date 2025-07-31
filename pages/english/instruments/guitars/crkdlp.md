---
title: "CRKD Les Paul (Multiplatform)"
sidebar: controllers_sidebar
permalink: ctrls_crkdgtr_lp_mp
folder: instruments
tags: [guitars, pc, english]
summary: "How to connect and configure CRKD Les Paul on RPCS3 (multiplat edition)."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/crkd.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/crkdlpcontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* CRKD Les Paul guitars can be connected wirelessly via its respective dongle, Bluetooth, and wired via USB. For Bluetooth, you need a Bluetooth receiver to connect to your computer.
	* Dongle or wired USB are the recommended methods.
* To rebind your guitar, use the CRKD app on your phone (iOS/Android).
* This page will be updated as firmware updates release and we have more information.

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-to-map-pads">How do I set up gamepad up?</a>
                            </h4>
                        </div>
                        <div id="how-to-map-pads" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<p><strong>Click on the Pads icon at the top of RPCS3</strong>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3pad.png" alt="A screenshot of RPCS3, showing the cursor over the Pads menu." title="Pads"></p>
<p>Follow the instructions and/or match the assignments below.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/gamepadlegend.png" alt="A picture showing how the instrument page and RPCS3 can be used as a mapping reference." title="Mapping an Xbox Controller"></p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Map End -->

#### Pad Information

| Handlers | Devices |
|:--------:|:-------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Guitar | Guitar Hero |

### PC Mode
* This is the recommended mode to set your guitar to.

#### CRKD App Setup

![A screenshot of the CRKD CTRL application. The guitar is configured for PC and it's set to Mode 1, which is the default mapping. Disable DPad is Off.](https://rb3pc.milohax.org/images/instruments/xtra/doohickey/default.jpg "CRKD CTRL")

#### Mapping

By default, XInput has most things bound correctly. You only need to remap the following:

* **UNMAP THE FOLLOWING** or guitar solos will auto-strum and the effects selector will constantly be moving!  
    * Use Right Click to unmap a button.

| **RPCS3** | **Guitar** |
|:--------:|:-----------:|
| L2 | Solo Modifier |

* **Map** the following:
	* For the whammy bar, hold ALT then left click on Right Stick: Left then Right Stick: Right to set negative and positive ranges.

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| Square | ![Y Button](https://rb3pc.milohax.org/images/btns/ctrls/360/y.png "Y Button") | ![Yellow Fret](https://rb3pc.milohax.org/images/btns/gtrs/yf.png "Yellow Fret") | 
| Triangle | ![X Button](https://rb3pc.milohax.org/images/btns/ctrls/360/x.png "X Button") | ![Blue Fret](https://rb3pc.milohax.org/images/btns/gtrs/bf.png "Blue Fret") |
| R1 | ![Back](https://rb3pc.milohax.org/images/btns/ctrls/360/back.png "Back") | ![Tilt](https://rb3pc.milohax.org/images/btns/gtrs/ts.gif "Tilt") |
| Right Stick: <br/> Left/Right | ![Left Trigger](https://rb3pc.milohax.org/images/btns/ctrls/360/lt.png "Left Trigger") | ![Whammy Bar](https://rb3pc.milohax.org/images/btns/gtrs/wb.png "Whammy Bar") |

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/CRKD%20Les%20Paul%20Guitar.7z){:target="_blank"}

<!-- Profile Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-to-use-profiles">How do I use profiles?</a>
                            </h4>
                        </div>
                        <div id="how-to-use-profiles" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>This is not recommended if you're using multiple controllers at once. </b> {{include.content}}</div>
<p>After downloading the profile,</p>
<ol>
<li>Extract the .7z file.</li>
<li>Drag the <code>input configs</code> folder into the <code>configs</code> folder where you have RPCS3 in.</li>
</ol>
<p><img src="https://rb3pc.milohax.org/images/instruments/instrepoinstall.gif" alt="A GIF of a user dragging the Wii Rock Band Guitar configuration into their RPCS3 folder." title="Installing a configuration from the Instrument Repo"></p>
<p>After that, you can select the profile in the <strong>“Pads”</strong> menu.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofile.png" alt="A screenshot of RPCS3's Gamepad Settings, showing the cursor over a profile." title="Gamepad Settings"></p>
<p>Most of the time, these controller profiles should work out of the box. If they don’t, try changing the controller listed in “<code>Devices</code>”, next to the “<code>Refresh</code>” button until it receives an input. You can edit this while the game is running.</p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Profiles End -->

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrcrkdlpmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Research by [[gonakil1ya]](https://gonakillya.neocities.org){:target="_blank"}
