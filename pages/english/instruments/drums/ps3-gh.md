---
title: PlayStation 3 Guitar Hero Drums
sidebar: controllers_sidebar
permalink: ctrls_ghdrums_ps3
folder: instruments
tags: [ps3, drums, english]
summary: "How to setup PS3 Guitar Hero drums on RPCS3."
toc: false
---


<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/plat/ps3.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/cont/ghdrmscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* Velocity sensitivity doesn't seem to work.
* Gem colors do not match the pads.
* RPCN Menus (for sending or accepting online invites) may cause a softlock. You may need an alternative input method to navigate these menus, such as [[a typing keyboard or a gamepad]](https://carlmylo.github.io/rb3-pc/ctrls#gamepads){:target="_blank"}.

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
<p><img src="https://carlmylo.github.io/rb3-pc/images/instruments/rpcs3pad.png" alt="A screenshot of RPCS3, showing the cursor over the Pads menu." title="Pads"></p>
<p>It’s suggested to create a new configuration by clicking <code>Add Configuration</code> at the top right of the <code>Pads</code> window.<br>
This is so you can change configuration profiles in case you want to play games that don’t use instruments.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/instruments/rpcs3padprofadd.png" alt="A screenshot of the top right of RPCS3's Pads window. &quot;Add Configuration&quot; is being clicked on by the mouse cursor." title="Add Configuration"></p>
<p>Follow the instructions and/or match the assignments below.</p>
<p><img src="https://carlmylo.github.io/rb3-pc/images/instruments/padlegend.png" alt="A picture showing how the instrument page and RPCS3 can be used as a mapping reference." title="Mapping the Rock Band Hofner"></p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Map End -->

## Pad Information

| Handlers | Devices |
|:---------:|:------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Drums | Guitar Hero |

## Mapping

* Guitar Hero controllers tend to misbehave and **refuse to map sometimes. If you try mapping a button and always get "U+" or something similar, click "Filter Noise"** at the bottom left of the controller configuration window **then try mapping**.

| **RPCS3** | **Guitar Hero Drums** |
|:--------:|:-----------------:|
| Cross | ![Green Pad](https://carlmylo.github.io/rb3-pc/images/btns/drms/gh/gp.png "Green Pad") |
| Circle | ![Red Pad](https://carlmylo.github.io/rb3-pc/images/btns/drms/gh/rp.png "Red Pad") |
| Square | ![Blue Pad](https://carlmylo.github.io/rb3-pc/images/btns/drms/gh/bp.png "Blue Pad") |
| Triangle | ![Yellow Cymbal](https://carlmylo.github.io/rb3-pc/images/btns/drms/gh/yc.png "Yellow Cymbal") |
| R1 | ![Orange Cymbal](https://carlmylo.github.io/rb3-pc/images/btns/drms/gh/oc.png "Orange Cymbal") |
| L1 | ![Foot Pedal](https://carlmylo.github.io/rb3-pc/images/btns/drms/gh/kp.png "Foot Pedal") |
| Cross | ![Cross Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/x.png "Cross Button") |
| Circle | ![Circle Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/o.png "Circle Button") |
| Square | ![Square Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/s.png "Square Button") |
| Triangle | ![Triangle Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/t.png "Triangle Button") |
| D-Pad | ![D-Pad](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/dp.png "D-Pad") |
| Left Stick | ![Left Stick](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/ls.png "Left Stick") |
| Start | ![Start Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/sta.png "Start Button") |
| Select | ![Select Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/sel.png "Select Button") |
| PS Button | ![Home Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/home.png "Home Button") |

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/PS3%20Guitar%20Hero%20Drums.7z){:target="_blank"}

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
<p><img src="https://carlmylo.github.io/rb3-pc/images/instruments/instrepoinstall.gif" alt="A GIF of a user dragging the Wii Rock Band Guitar configuration into their RPCS3 folder." title="Installing a configuration from the Instrument Repo"></p>
<p>After that, you can select the profile in the <strong>“Pads”</strong> menu.</p>
<p><img src="https://carlmylo.github.io/rb3-pc/images/instruments/rpcs3padprofile.png" alt="A screenshot of RPCS3's Gamepad Settings, showing the cursor over a profile." title="Gamepad Settings"></p>
<p>Most of the time, these controller profiles should work out of the box. If they don’t, try changing the controller listed in “<code>Devices</code>”, next to the “<code>Refresh</code>” button until it receives an input. You can edit this while the game is running.</p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Profiles End -->

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/maps/drmsps3ghmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://carlmylo.github.io/rb3-pc/ctrls#instrument-list)

Mapped by [[GamerPerson22]](https://www.youtube.com/channel/UCC5SlXPlnlGwBG7w6mvfx8g){:target="_blank"}