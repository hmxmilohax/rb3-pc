---
title: "Xbox One Rock Band 4/Fortnite Festival Guitars"
sidebar: controllers_sidebar
permalink: ctrls_rb4gtr_xbox
folder: instruments
tags: [xbox-one, guitars, english]
summary: "How to setup Xbox One Rock Band 4/Fortnite Festival guitars on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/xbx.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rb4gtrscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* Requires installing and running [[**RB4InstrummentMapper**]](https://github.com/TheNathannator/RB4InstrumentMapper/){:target="_blank"} along with its dependencies.
* This profile works for Xbox One Fender Stratocaster, Fender Jaguar, and PDP Riffmaster guitars.
	* Fender Stratocaster and Fender Jaguar guitars require a Microsoft Xbox Wireless Adapter.  
	![Microsoft Xbox Wireless Adapter for Windows 10](https://rb3pc.milohax.org/images/btns/ctrls/xbox/receiver.png "Microsoft Xbox Wireless Adapter for Windows 10")  
	* PDP Riffmaster guitars require their respective dongle.  
	![PDP Riffmaster Wireless Receiver](https://rb3pc.milohax.org/images/btns/ctrls/xbox/riffrec.png "PDP Riffmaster Wireless Receiver")  
* If you have a Jaguar guitar, you may need to install a [[firmware update]](https://bit.ly/2UHzonU){:target="_blank"} to connect it to the receiver. [[Click here for more information]](https://bit.ly/2UHzonU){:target="_blank"}.
* RPCN Menus (for sending or accepting online invites) may cause a softlock. You may need an alternative input method to navigate these menus, such as [[a typing keyboard or a gamepad]](https://rb3pc.milohax.org/ctrls_pads){:target="_blank"}.

## Pad Information

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Additional Setup

Please refer to RB4InstrumentMapper's documentation.  
[[Click here to go there]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.md){:target="_blank"}.

## Mapping:

### Controller Emulation Mode: ViGEmBus (RPCS3 compatibility)

This is the recommended mode and should not require any mapping. You simply need to assign the Handler, Device, and Device Class/Type.

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrxomapping.png" alt="Mapping" title="Mapping"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#controller-emulation-mode-vigembus">Advanced Mapping</a>
                            </h4>
                        </div>
                        <div id="controller-emulation-mode-vigembus" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<p><a href="https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/downloads/instrument-repo/Xbox%20Rock%20Band%20Guitar.7z">[Download Profile]</a></p>
<p>This is not suggested as it requires lots of manual mapping. You should instead use <strong>ViGEmBus (RPCS3 compatibility)</strong>.</p>
<p>The effects switch (pickup selector) was only able to be bound to the top half or the bottom half. The bottom half was chosen in the profile so it could be disabled.</p>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Controller</strong></th>
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
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/ts.png" alt="Tilt" title="Tilt"></td>
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
<p><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrxboxrbmapping.png" alt="Mapping" title="Mapping"></div></p>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Back to Guitars]](https://rb3pc.milohax.org/ctrls_guitar)

Mapped by [[gonakil1ya]](https://linktr.ee/Gonakil1ya){:target="_blank"}