---
title: "PlayStation 4 Rock Band 4 Drums"
sidebar: controllers_sidebar
permalink: ctrls_rb4drums_ps4
folder: instruments
tags: [ps4, drums, english]
summary: "How to setup PS4 Rock Band drums on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/ps4.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rb4drmscontroller.png" alt="Controller" title="Controller"></div>

## NOTES
<div markdown="span" class="alert alert-danger" role="alert"><i class="fa fa-exclamation-circle"></i> <b>Pro-Cymbals Expansion does not work!</b> {{include.content}}</div>

* Latency may be an issue depending on your Bluetooth receiver. This may make it difficult to calibrate.
* Velocity sensitivity doesn't seem to work.
* RPCN Menus (for sending or accepting online invites) may cause a softlock. You may need an alternative input method to navigate these menus, such as [[a typing keyboard or a gamepad]](https://rb3pc.milohax.org/ctrls#gamepads){:target="_blank"}.

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

## Pad Information

| Handlers | Devices |
|:--------:|:-------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------:|
| Drums | Rock Band Pro |

## Mapping

| **RPCS3**    | **Rock Band Drums** |
|:--------:|:-------------------:|
| Cross | ![Green Pad](https://rb3pc.milohax.org/images/btns/drms/rb/gp.png "Green Pad") |
| Circle | ![Red Pad](https://rb3pc.milohax.org/images/btns/drms/rb/rp.png "Red Pad") |
| Square | ![Blue Pad](https://rb3pc.milohax.org/images/btns/drms/rb/bp.png "Blue Pad") |
| Triangle | ![Yellow Pad](https://rb3pc.milohax.org/images/btns/drms/rb/yp.png "Yellow Pad") |
| L1 | ![Foot Pedal](https://rb3pc.milohax.org/images/btns/drms/rb/kp.png "Foot Pedal") |
| Cross | ![Cross Button](https://rb3pc.milohax.org/images/btns/ctrls/ps4/x.png "Cross Button") |
| Circle | ![Circle Button](https://rb3pc.milohax.org/images/btns/ctrls/ps4/o.png "Circle Button") |
| Square | ![Square Button](https://rb3pc.milohax.org/images/btns/ctrls/ps4/s.png "Square Button") |
| Triangle | ![Triangle Button](https://rb3pc.milohax.org/images/btns/ctrls/ps4/t.png "Triangle Button") |
| D-Pad | ![D-Pad](https://rb3pc.milohax.org/images/btns/ctrls/ps4/dp.png "D-Pad") |
| Start | ![Options Button](https://rb3pc.milohax.org/images/btns/ctrls/ps4/opt.png "Options Button") |
| Select | ![Share Button](https://rb3pc.milohax.org/images/btns/ctrls/ps4/shr.png "Share Button") |
| PS Button | ![Home](https://rb3pc.milohax.org/images/btns/drms/rb/home.png "Home") |

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/PS4%20Rock%20Band%20Drums.7z)

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

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmsps4rbmapping.png" alt="Mapping" title="Mapping"></div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Mapped by [[gonakil1ya]](https://linktr.ee/Gonakil1ya){:target="_blank"}