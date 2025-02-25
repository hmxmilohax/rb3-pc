---
title: Riffmaster (via Adafruit Feather) Guitar
sidebar: controllers_sidebar
permalink: ctrls_mod_riffada
folder: instruments
tags: [guitars, modded, english]
summary: "How to set up a PS4 Riffmaster connected with a Feather on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/santroller.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/riffmastercontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* **This is specifically for the** [**[Adafruit Feather RP2040 with USB Type A Host]**](https://www.adafruit.com/product/5723)**!** Please consult your sales receipt to confirm that it is indeed an [[Adafruit Feather RP2040 **with USB Type A Host**]](https://www.adafruit.com/product/5723).
* While you can use the Xbox One Riffmaster too but you should just use [[RB4InstrumentMapper]](https://rb3pc.milohax.org/ctrls_rb4gtr_xbox) for that instead.

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-to-map-pads">How do I map my guitar?</a>
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
| XInput | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Guitar | Rock Band |

## Setup

Download the latest version of Santroller.

[![A screenshot of Santroller's Github download page, hovering over the Windows installer.](https://rb3pc.milohax.org/images/instruments/xtra/feather/dlsan.png)](https://github.com/Santroller/Santroller/releases "SantrollerConfigurator")

After downloading Santroller, open "SantrollerConfigurator".

![A screenshot of a cursor hovering over SantrollerConfigurator on a user's desktop](https://rb3pc.milohax.org/images/instruments/xtra/feather/opensan.png "SantrollerConfigurator")

Hold the "Boot" button on your Adafruit Feather RP2040 with USB Type A Host if you're plugging it into your computer for the first time.

![A picture of an Adafruit Feather RP2040. A button labeled "Boot" is circled in white, red, and black.](https://rb3pc.milohax.org/images/instruments/xtra/feather/bootada.jpg "Adafruit Feather RP2040 with USB Type A Host")

In SantrollerConfigurator, set "`Input Type`" to "`USB Adapter`." The Adafruit Feather RP2040 with USB Type A Host should be detected as "`Raspberry Pi Pico`." Click "`Configure`" after doing this.

![A screenshot of SantrollerConfigurator, with a cursor hovering over "USB Adapter," next to "Input Type."](https://rb3pc.milohax.org/images/instruments/xtra/feather/sanusb.png "SantrollerConfigurator")

Give it a moment to program initial configuration. When prompted, click on "`Configure`" again.
![A screenshot of SantrollerConfigurator, with a cursor hovering over "USB Adapter," next to "Input Type."](https://rb3pc.milohax.org/images/instruments/xtra/feather/sanconf.png "SantrollerConfigurator")

After you've loaded into the configuration page, scroll down to the "`Presets`" section and click to expand it. Once expanded, click on "`Import Settings from File`"

A community made preset exists (courtesy of jnack) to help speed things up. Load it up via the "Import Settings from File" option.  
[[Download the picoconfig preset here]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/RiffmasterFeather.picoconfig)

![A screenshot of SantrollerConfigurator, with a cursor hovering over "Import Settings from File" under the "Presets" configuration.](https://rb3pc.milohax.org/images/instruments/xtra/feather/sanpreload.png "Presets")

After loading the preset, **MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of Santroller. The cursor is hovering over "Save Settings".](https://rb3pc.milohax.org/images/instruments/xtra/feather/sansave.png "Santroller")

## Mapping

By default, XInput has most things bound correctly. You only need to remap the following:

| **RPCS3** | **XInput** | **Guitar** |
|:--------:|:-----------:|:-----------:|
| R1 | ![Right Stick](https://rb3pc.milohax.org/images/btns/ctrls/360/rs.png "Right Stick") | ![Tilt](https://rb3pc.milohax.org/images/btns/gtrs/ts.gif "Tilt") | 
| L2 | ![Right Stick Click](https://rb3pc.milohax.org/images/btns/ctrls/360/rsc.png "Right Stick Click") | ![Solo Buttons](https://rb3pc.milohax.org/images/btns/gtrs/solo.png "Solo Buttons") | 
| Right Stick: <br> Down | ![Left Trigger](https://rb3pc.milohax.org/images/btns/ctrls/360/lt.png "Left Trigger") | ![Effects Switch](https://rb3pc.milohax.org/images/btns/gtrs/fx.png "Effects Switch") |

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
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Xbox%20Rock%20Band%20Drums.7z">[Download Profile]</a></p>
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
<h4 id="profile">Bindings</h4>
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
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/gf.png" alt="Green Fret" title="Green Fret"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/rf.png" alt="Red Fret" title="Red Fret"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/of.png" alt="Orange Fret" title="Orange Fret"></td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/sbu.png" alt="Strumbar Up" title="Strumbar Up"></td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/sbd.png" alt="Strumbar Down" title="Strumbar Down"></td>
</tr>
<tr>
<td align="center">D-Pad: Left</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/dpl.png" alt="D-Pad: Left" title="D-Pad: Left"></td>
</tr>
<tr>
<td align="center">D-Pad: Right</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/dpr.png" alt="D-Pad: Right" title="D-Pad: Right"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Left/Right</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/wb.png" alt="Whammy Bar" title="Whammy Bar"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Up <em>or</em> Down</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/fx.png" alt="Effects Switch" title="Effects Switch"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/solo.png" alt="Solo Buttons" title="Solo Buttons"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/ts.gif" alt="Tilt" title="Tilt"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/start.png" alt="Plus" title="Start"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/back.png" alt="Minus" title="Back"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

## Additional Notes
The picoconfig preset binds a few things for a better experience with a PS4 Riffmaster.  
- The "Boot" button on the Adafruit Feather RP2040 with USB Type A Host will act as a guide button as pressing and holding the guide button on the Riffmaster shuts it off.
- D-Pad: Left and Select are swapped as the PlayStation Riffmaster. This is because, by default, the PlayStation Riffmaster has Overdrive activation bound to D-Pad Left which is very uncomfortable.

If you wish to remove these tweaks, click the "`Remove`" next to the D-pad Left and Back buttons at the bottom of Santroller Configurator.

![A screenshot of SantrollerConfigurator, scrolled to the bottom. There are circles over the "Remove" buttons next to Back and D-pad Left.](https://rb3pc.milohax.org/images/instruments/xtra/feather/sanrem.png "SantrollerConfigurator")

After that, go to the "`Usb Host Inputs`" section and enable the original buttons again.

![A screenshot of SantrollerConfigurator, in the "Usb Host Inputs" section. There are circles over the disabled Back and D-pad Left buttons, showing them as disabled.](https://rb3pc.milohax.org/images/instruments/xtra/feather/sanhostin.png "Usb Host Inputs")

## Profile

[[Download Profile]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Feather%20Riffmaster.7z)

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/modfeatherriffmapping.png" alt="Mapping" title="Mapping"></div>

### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Research by [jnackmclain](https://github.com/jnackmclain)