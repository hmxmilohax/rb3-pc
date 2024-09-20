---
title: "Xbox One Rock Band 4 Drums"
sidebar: controllers_sidebar
permalink: ctrls_rb4drums_xbox
folder: instruments
tags: [xbox-one, drums, english]
summary: "How to setup Xbox One Rock Band drums on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/xbx.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rbdrmscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* Requires installing and running [[**RB4InstrummentMapper**]](https://github.com/TheNathannator/RB4InstrumentMapper/){:target="_blank"} along with its dependencies.
* Works with or without the Pro Cymbal expansions.
	* Make sure to tell the game which cymbals are connected in the Drum Options menu.
* Velocity sensitivity doesn't seem to work.
* RPCN Menus (for sending or accepting online invites) may cause a softlock. You may need an alternative input method to navigate these menus, such as [[a typing keyboard or a gamepad]](https://rb3pc.milohax.org/ctrls_pads){:target="_blank"}.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Drums | Rock Band Pro |

## Additional Setup

Please refer to RB4InstrumentMapper's documentation.  
[[Click here to go there]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.md){:target="_blank"}.

## Mapping

### Controller Emulation Mode: ViGEmBus (RPCS3 compatibility)

This is the recommended mode and should not require any mapping. You simply need to assign the Handler, Device, and Device Class/Type.

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmsxomapping.png" alt="Mapping" title="Mapping"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#controller-emulation-mode-vigembus">Advanced Mapping</a>
                            </h4>
                        </div>
                        <div id="controller-emulation-mode-vigembus" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<p><a href="https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/downloads/instrument-repo/Xbox%20Rock%20Band%20Drums.7z">[Download Profile]</a></p>
<p>This is not suggested as it requires lots of manual mapping. You should instead use <strong>ViGEmBus (RPCS3 compatibility)</strong>.</p>
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
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/lsc.png" alt="Left Stick Click" title="Left Stick Click"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Second Foot Pedal" title="Second Foot Pedal"></td>
</tr>
<tr>
<td align="center">L3</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/rsc.png" alt="Right Stick Click" title="Right Stick Click"></td>
<td align="center">Pad Modifier</td>
</tr>
<tr>
<td align="center">R3</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/rb.png" alt="Right Bumper" title="Right Bumper"></td>
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
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/gp.png" alt="Green Pad" title="Green Pad"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/rp.png" alt="Red Pad" title="Red Pad"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/bp.png" alt="Blue Pad" title="Blue Pad"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/yp.png" alt="Yellow Pad" title="Yellow Pad"></td>
</tr>
<tr>
<td align="center">R3</td>
<td align="center">Cymbal Modifier</td>
</tr>
<tr>
<td align="center">L3</td>
<td align="center">Pad Modifier</td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Foot Pedal" title="Foot Pedal"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Second Foot Pedal" title="Second Foot Pedal"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/a.png" alt="A Button" title="A Button"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/b.png" alt="B Button" title="B Button"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/x.png" alt="X Button" title="X Button"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/y.png" alt="Y Button" title="Y Button"></td>
</tr>
<tr>
<td align="center">D-Pad</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/xbox/dp.png" alt="D-Pad" title="D-Pad"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
<p><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmsxboxrbmapping.png" alt="Mapping" title="Mapping"></div></p>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Back to Drums]](https://rb3pc.milohax.org/ctrls_drums)

Mapped by [[gonakil1ya]](https://linktr.ee/Gonakil1ya)