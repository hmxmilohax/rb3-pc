---
title: Roll Limitless Drums
sidebar: controllers_sidebar
permalink: ctrls_mod_rldrums
folder: instruments
tags: [drums, modded, midi, english]
summary: "How to connect and configure a drum kit connected with a Roll Limitless on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/midi.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rolllimitlesscontroller.png" alt="Controller" title="Controller"></div>

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-to-map-pads">How do I map my drums?</a>
                            </h4>
                        </div>
                        <div id="how-to-map-pads" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<p><strong>Click on the Pads icon at the top of RPCS3</strong>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3pad.png" alt="A screenshot of RPCS3, showing the cursor over the Pads menu." title="Pads"></p>
<p>It’s suggested to create a new configuration by clicking <code>Add Configuration</code> at the top right of the <code>Pads</code> window.<br>
This is so you can change configuration profiles in case you want to play games that don’t use instruments.<br>
<img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofadd.png" alt="A screenshot of the top right of RPCS3's Pads window. &quot;Add Configuration&quot; is being clicked on by the mouse cursor." title="Add Configuration"></p>
<p>Follow the instructions and/or match the assignments below.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/padlegend.png" alt="A picture showing how the instrument page and RPCS3 can be used as a mapping reference." title="Mapping the Rock Band Hofner"></p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Map End -->

## NOTES

* This controller requires advanced configuration.
* Velocity sensitivity doesn't seem to work.

### Additional Setup:
1. Put the Roll Limitless Adapter in firmware updating mode. To do this, press and hold the rectangular button on the top of the adapter, near the micro USB port.  
![A picture of a Roll Limitless adapter, showing the firmware button circled in red.](https://rb3pc.milohax.org/images/instruments/xtra/rolllimitless/fwbutton.png "Roll Limitless Firmware button")
2. While still holding the button, plug it into your computer. If done successfully, the Roll Limitless will show up as a removable drive.
3. [[Download the latest "Universal" firmware for the Roll Limitless from the official website]](https://rolllimitless.com/firmwares/).
4. Place the firmware file on the Roll Limitless device while it's in firmware updating mode (showing up as a removable drive). When it completes, safely remove the device.
5. Plug the Roll Limitless adapter back into your computer while holding down the round Start button.  
![A picture of a Roll Limitless adapter, showing the start button circled in red.](https://rb3pc.milohax.org/images/instruments/xtra/rolllimitless/startbutton.png "Roll Limitless Start button")
6. Verify that Windows has detected the Roll Limitless adapter by searching for `joy.cpl` in the Start menu.  
![A screenshot of Windows showing the search results of joy.cpl.](https://rb3pc.milohax.org/images/instruments/xtra/gen/joycpl.png "Set up USB game controllers")
7. If it shows up, it's ready to go. If not, make sure you're plugging it in while holding down the round Start button.

## Mapping

| **RPCS3** | **Drums** |
|:---------:|:---------:|
| Cross | ![Green Pad](https://rb3pc.milohax.org/images/btns/drms/rb/gp.png "Green Pad") |
| Circle | ![Red Pad](https://rb3pc.milohax.org/images/btns/drms/rb/rp.png "Red Pad") |
| Square | ![Blue Pad](https://rb3pc.milohax.org/images/btns/drms/rb/bp.png "Blue Pad") |
| Triangle | ![Yellow Pad](https://rb3pc.milohax.org/images/btns/drms/rb/yp.png "Yellow Pad") |
| L1 | ![Foot Pedal](https://rb3pc.milohax.org/images/btns/drms/rb/kp.png "Foot Pedal") |
| D-Pad | ![D-Pad](https://rb3pc.milohax.org/images/btns/ctrls/xbox/dp.png "D-Pad") |
| R1 | ![Second Foot Pedal](https://rb3pc.milohax.org/images/btns/drms/rb/kp.png "Second Foot Pedal") |
| R3 | Cymbal Modifier |
| D-Pad: Up | Yellow Cymbal Modifier |
| D-Pad: Down | Blue Cymbal Modifier |
| L3 | Pad Modifier |

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Roll%20Limitless%20Drums.7z)

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

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/modrldrmsmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Mapped by Uzny