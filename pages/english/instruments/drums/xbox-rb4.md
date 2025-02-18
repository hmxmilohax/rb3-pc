---
title: "Xbox One Rock Band 4 Drums"
sidebar: controllers_sidebar
permalink: ctrls_rb4drums_xbox
folder: instruments
tags: [xbox-one, drums, english]
summary: "How to setup Xbox One Rock Band drums on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/plat/xbx.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/cont/rbdrmscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* Requires installing and running [[**RB4InstrummentMapper**]](https://github.com/TheNathannator/RB4InstrumentMapper/){:target="_blank"} along with its dependencies.
* **Linux** users can install [[`xone` kernel drivers]](https://github.com/dlundqvist/xone) to use Xbox One peripherals.
* You need a Microsoft Xbox Wireless Adapter to connect these drums to your computer.  
    ![Microsoft Xbox Wireless Adapter for Windows 10](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/xbox/receiver.png "Microsoft Xbox Wireless Adapter for Windows 10")  
* Works **with or without** the Pro Cymbal expansions.
    * Make sure to configure which cymbals are connected within Rock Band 3.
        * `Menu > Options > Drum Options`
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
|:--------:|:-------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Drums | Rock Band Pro |

## Additional Setup

Please refer to RB4InstrumentMapper's documentation.  
[[Click here to go there]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.md){:target="_blank"}.

## Mapping

### Controller Emulation Mode: ViGEmBus (RPCS3 compatibility)

This is the recommended mode and should not require any mapping. You simply need to assign the Handler, Device, and Device Class/Type.

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/maps/drmsxomapping.png" alt="Mapping" title="Mapping"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#controller-emulation-mode-vigembus">Advanced Mapping</a>
                            </h4>
                        </div>
                        <div id="controller-emulation-mode-vigembus" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Xbox%20Rock%20Band%20Drums.7z">[Download Profile]</a></p>
<p>This is not suggested as it requires lots of manual mapping. You should instead use <strong>ViGEmBus (RPCS3 compatibility)</strong>.</p>
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
<h4 id="profile">Bindings</h4>
<p>By default, XInput has most things bound correctly. You only need to remap the following:</p>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>XInput</strong></th>
<th align="center"><strong>Drums</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/lsc.png" alt="Left Stick Click" title="Left Stick Click"></td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/kp.png" alt="Second Foot Pedal" title="Second Foot Pedal"></td>
</tr>
<tr>
<td align="center">L3</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/rsc.png" alt="Right Stick Click" title="Right Stick Click"></td>
<td align="center">Pad Modifier</td>
</tr>
<tr>
<td align="center">R3</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/rb.png" alt="Right Bumper" title="Right Bumper"></td>
<td align="center">Cymbal Modifier</td>
</tr>
</tbody>
</table><h3 id="advanced-mapping">Advanced Mapping</h3>
<ul>
<li>Rock Band Drums send multiple button presses out at once. For example, a Red pad will send “<code>B</code>” and “<code>Right Stick Click</code>” (which translates to “<code>Circle</code>” and “<code>L3</code>”.) Keep in mind these are needed to the emulator to tell your cymbals apart.
<ul>
<li>It’s strongly suggested to bind an Xbox controller like the Mapping screenshot below then swapping the Device to your Xbox 360 Rock Band Drums.</li>
</ul>
</li>
<li>To bind multiple buttons to one RPCS3 button, hold Shift then click on the RPCS3 button you want to assign multiple buttons to.</li>
</ul>
<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Drums</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/gp.png" alt="Green Pad" title="Green Pad"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/rp.png" alt="Red Pad" title="Red Pad"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/bp.png" alt="Blue Pad" title="Blue Pad"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/yp.png" alt="Yellow Pad" title="Yellow Pad"></td>
</tr>
<tr>
<td align="center">R3</td>
<td align="center">Cymbal Modifier</td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center">Yellow Cymbal Modifier</td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center">Blue Cymbal Modifier</td>
</tr>
<tr>
<td align="center">L3</td>
<td align="center">Pad Modifier</td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/kp.png" alt="Foot Pedal" title="Foot Pedal"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/kp.png" alt="Second Foot Pedal" title="Second Foot Pedal"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/a.png" alt="A Button" title="A Button"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/b.png" alt="B Button" title="B Button"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/x.png" alt="X Button" title="X Button"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/y.png" alt="Y Button" title="Y Button"></td>
</tr>
<tr>
<td align="center">D-Pad</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/xbox/dp.png" alt="D-Pad" title="D-Pad"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/drms/rb/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
<p><div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/maps/drmsxboxrbmapping.png" alt="Mapping" title="Mapping"></div></p>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Back to Controllers]](https://carlmylo.github.io/rb3-pc/ctrls#instrument-list)

Mapped by [[gonakil1ya]](https://linktr.ee/Gonakil1ya)