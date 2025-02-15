---
title: Nintendo Wii Rock Band MIDI Pro Adapter Drums
sidebar: controllers_sidebar
permalink: ctrls_mpadrums_wii
folder: instruments
tags: [wii, drums, english]
summary: "How to setup drums connected via a Wii MPA on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/plat/wii.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/cont/wiimpacontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* Make sure to configure which cymbals are connected within Rock Band 3.
	* `Menu > Options > Drum Options`
* Velocity sensitivity doesn't seem to work.
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

## Pad Informations

| Handlers | Devices |
|:------------------:|:---------------------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Drums | Rock Band Pro |

## Mapping

* Rock Band Drums send multiple button presses out at once. Keep in mind these are needed to the emulator to tell your cymbals apart.
	* It's strongly suggested to bind an Xbox controller like the Mapping screenshot below then swapping the Device to your Xbox 360 Rock Band Drums.
* To bind multiple buttons to one RPCS3 button, hold Shift then click on the RPCS3 button you want to assign multiple buttons to.

| **RPCS3**    | **Rock Band Drums** |
|:--------:|:-------------------:|
| Cross | ![Green Pad](https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/gp.png "Green Pad") |
| Circle | ![Red Pad](https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/rp.png "Red Pad") |
| Square | ![Blue Pad](https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/bp.png "Blue Pad") |
| Triangle | ![Yellow Pad](https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/yp.png "Yellow Pad") |
| R3 | Cymbal Modifier |
| L3 | Pad Modifier |
| L1 | ![Foot Pedal](https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/kp.png "Foot Pedal") |
| R1 | ![Second Foot Pedal](https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/kp.png "Second Foot Pedal") |
| Cross | ![A Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/a.png "A Button") |
| Circle | ![B Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/b.png "B Button") |
| Square | ![1 Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/1.png "1 Button") |
| Triangle | ![2 Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/2.png "2 Button") |
| D-Pad | ![D-Pad](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/dpad.png "D-Pad") |
| PS Button | ![Home](https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/home.png "Home") |
| Start | ![Plus Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/plu.png "Plus Button") |
| Select | ![Minus Button](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/wii/min.png "Minus Button") |

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Wii%20Rock%20Band%20Drums.7z)

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

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/maps/drmswiirbmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://carlmylo.github.io/rb3-pc/ctrls#instrument-list)

Mapped by [[scott0852]](https://twitter.com/scott0852){:target="_blank"}