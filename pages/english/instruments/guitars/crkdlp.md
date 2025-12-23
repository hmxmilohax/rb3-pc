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
* The guitar subtype is set to Rock Band which means tilt will work but flanger FX WILL BE FORCED

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
| Guitar | Rock Band |

### PC - Mode 8
* This is the recommended mode to set your guitar to.

<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>Make sure your guitar and receiver are on the latest firmware!</b> {{include.content}}</div>

#### CRKD App Setup

![The first page of the CRKD CTRL application. The guitar is configured for PC and it's set to Mode 8.](https://rb3pc.milohax.org/images/instruments/xtra/crkdlp/pcm81.png "CRKD CTRL")  

![The second page of the CRKD CTRL application.](https://rb3pc.milohax.org/images/instruments/xtra/crkdlp/pcm82.png "CRKD CTRL")  

#### Mapping

By default, XInput has most things bound correctly. You only need to remap the following:

* **Map** the following:

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| R1 | ![Right Stick](https://rb3pc.milohax.org/images/btns/ctrls/360/rs.png "Right Stick") | ![Tilt](https://rb3pc.milohax.org/images/btns/gtrs/ts.gif "Tilt") | 

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

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrcrkdlp8mapping.png" alt="Mapping" title="Mapping"></div>

<!-- Mode 1 Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mode-one">Mode 1</a>
                            </h4>
                        </div>
                        <div id="how-to-use-profiles" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<h4 id="pad-information">Pad Information</h4>

<table>
<thead>
<tr>
<th align="center">Handlers</th>
<th align="center">Devices</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">XInput</td>
<td align="center">XInput Pad</td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th align="center">Device Class</th>
<th align="center">Device Subtype</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Guitar</td>
<td align="center">Guitar Hero</td>
</tr>
</tbody>
</table><h3 id="pc-mode">PC Mode</h3>
<ul>
<li>This is the recommended mode to set your guitar to.</li>
</ul>
<h4 id="crkd-app-setup">CRKD App Setup</h4>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/crkdlp/default.jpg" alt="A screenshot of the CRKD CTRL application. The guitar is configured for PC and it's set to Mode 1, which is the default mapping. Disable DPad is Off." title="CRKD CTRL"></p>
<h4 id="mapping">Mapping</h4>
<p>By default, XInput has most things bound correctly. You only need to remap the following:</p>
<ul>
<li><strong>UNMAP THE FOLLOWING</strong> or guitar solos will auto-strum and the effects selector will constantly be moving!
<ul>
<li>Use Right Click to unmap a button.</li>
</ul>
</li>
</ul>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Guitar</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">L2</td>
<td align="center">Solo Modifier</td>
</tr>
</tbody>
</table><ul>
<li><strong>Map</strong> the following:
<ul>
<li>For the whammy bar, hold ALT then left click on Right Stick: Left then Right Stick: Right to set negative and positive ranges.</li>
</ul>
</li>
</ul>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>XInput</strong></th>
<th align="center"><strong>Guitar</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/y.png" alt="Y Button" title="Y Button"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/x.png" alt="X Button" title="X Button"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/back.png" alt="Back" title="Back"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/ts.gif" alt="Tilt" title="Tilt"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Left/Right</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/lt.png" alt="Left Trigger" title="Left Trigger"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/wb.png" alt="Whammy Bar" title="Whammy Bar"></td>
</tr>
</tbody>
</table><h2 id="profile">Profile</h2>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/CRKD%20Les%20Paul%20M1%20Guitar.7z">[Download Profile]</a></p>
<p><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrcrkdlp1mapping.png" alt="Mapping" title="Mapping"></div></p>

</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Mode 1 End -->

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Research by [[gonakil1ya]](https://gonakillya.neocities.org){:target="_blank"}
