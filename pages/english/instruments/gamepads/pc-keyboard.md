---
title: PC Keyboard
sidebar: controllers_sidebar
permalink: ctrls_pad_pckeys
folder: instruments
tags: [pc, gamepads, english]
summary: "How to setup PC Keyboards on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/pc.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/pckeyboardcontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* To bind multiple keys to one button, hold Shift then click on the button you want to assign multiple keys to.
* **You will need to set the "Stick Multiplier" and "Stick Interpolation" for Left and Right to `0.90` for whammy to function correctly.**
* To play Guitar/Bass/Keys/Drums parts on a Controller (Padtar), you will need Rock Band 3 Deluxe.
	- You can also rebind your controller within Deluxe.  
	`Menu > Options > Deluxe Settings > Advanced > Controller > Pad Button Remap`

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-to-map-pads">How do I map my keyboard?</a>
                            </h4>
                        </div>
                        <div id="how-to-map-pads" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<p><strong>Click on the Pads icon at the top of RPCS3</strong>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3pad.png" alt="A screenshot of RPCS3, showing the cursor over the Pads menu." title="Pads"></p>
<p>It’s suggested to create a new configuration by clicking <code>Add Configuration</code> at the top right of the <code>Pads</code> window.<br>
This is so you can change configuration profiles in case you want to play other games.<br>
<img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofadd.png" alt="A screenshot of the top right of RPCS3's Pads window. &quot;Add Configuration&quot; is being clicked on by the mouse cursor." title="Add Configuration"></p>
<p>Follow the instructions and/or match the assignments below.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/padlegend.png" alt="A picture showing how the instrument page and RPCS3 can be used as a mapping reference." title="Mapping the Rock Band Hofner"></p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Map End -->

## Bindings

<ul id="configTabs" class="nav nav-tabs">
    <li class="active"><a href="#default-binds" data-toggle="tab">Default</a></li>
    <li><a href="#fortnitefest" data-toggle="tab">Autostrum</a></li>
    <li><a href="#fortnitepro" data-toggle="tab">Manual Strum</a></li>
    <li><a href="#linos-binds" data-toggle="tab">Linos Binds</a></li>
    <li><a href="#ashunprodrums" data-toggle="tab">Ashun Pro Drums</a></li>
</ul>
  <div class="tab-content">
<!-- first tab start -->
<div role="tabpanel" class="tab-pane active" id="default-binds">
<!-- tab content start -->
<h3 id="default-mapping">Default Mapping</h3>
<p>These are the default keyboard mappings that come with RPCS3.</p>
<ul>
<li>This profile is <strong>strictly</strong> for menus and for vocalists that lack a proper controller.</li>
</ul>
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
<td align="center">Keyboard</td>
<td align="center">Keyboard</td>
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
<td align="center">Standard (Pad)</td>
<td align="center">PS3 Controller</td>
</tr>
</tbody>
</table><h4 id="bindings">Bindings</h4>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Keyboard</strong></th>
<th align="center"><strong>Alt Use 1</strong></th>
<th align="center"><strong>Alt Use 2</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross</td>
<td align="center"><code>X</code></td>
<td align="center">Select</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><code>C</code></td>
<td align="center">Back</td>
<td align="center">Mic 3 Volume (Song)</td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><code>Z</code></td>
<td align="center">Mic 1 Volume (Song)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><code>V</code></td>
<td align="center">View More Info (Library)</td>
<td align="center">Mic 2 Volume (Song)</td>
</tr>
<tr>
<td align="center">D-Pad</td>
<td align="center"><code>Up</code>, <code>Down</code>, <code>Left</code>, and <code>Right</code></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Left Stick</td>
<td align="center"><code>W</code>, <code>A</code>, <code>S</code>, and <code>D</code></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><code>Return</code></td>
<td align="center">Options</td>
<td align="center">Pause (Song)</td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><code>Space</code></td>
<td align="center">Overdrive</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><code>Q</code></td>
<td align="center">Guide Part Selection (Practice)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><code>R</code></td>
<td align="center">Vocal Part Selection (Practice)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><code>E</code></td>
<td align="center">Vocal Track Volume (Song)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">R2</td>
<td align="center"><code>T</code></td>
<td align="center">Pitch Correction (Song)</td>
<td align="center"></td>
</tr>
</tbody>
</table><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/padpckbdefmapping.png" alt="Mapping" title="Mapping"></div>
<!-- tab content end -->
</div>
<!-- first tab end -->
<!-- next tab start -->
<div role="tabpanel" class="tab-pane" id="fortnitefest">
<!-- tab content start -->
<h3 id="autostrum">Autostrum</h3>
<p>A profile heavily inspired by Fortnite Festival’s keyboard scheme. Modified by lunalawl.</p>
<ul>
<li>This profile does not require strumming.</li>
<li>To bind multiple keys to one button, hold Shift then click on the button you want to assign multiple keys to.</li>
</ul>
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
<td align="center">Keyboard</td>
<td align="center">Keyboard</td>
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
<td align="center">Standard (Pad)</td>
<td align="center">PS3 Controller</td>
</tr>
</tbody>
</table><h4 id="bindings">Bindings</h4>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Keyboard</strong></th>
<th align="center"><strong>Guitars/Bass/Keys</strong></th>
<th align="center"><strong>Alt Use 1</strong></th>
<th align="center"><strong>Alt Use 2</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">L1</td>
<td align="center"><code>F</code>, and <code>Q</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/gf.png" alt="Green Fret" title="Green Fret"></td>
<td align="center">Guide Part Selection (Practice)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><code>D</code>, and <code>R</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/rf.png" alt="Red Fret" title="Red Fret"></td>
<td align="center">Vocal Part Selection (Practice)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><code>E</code>, and <code>J</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
<td align="center">Vocal Track Volume (Song)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">R2</td>
<td align="center"><code>K</code>, and <code>T</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
<td align="center">Pitch Correction (Song)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><code>L</code>, and <code>X</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/of.png" alt="Orange Fret" title="Orange Fret"></td>
<td align="center">Select</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><code>C</code></td>
<td align="center"></td>
<td align="center">Back</td>
<td align="center">Mic 3 Volume (Song)</td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><code>Z</code></td>
<td align="center"></td>
<td align="center">Mic 1 Volume (Song)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><code>V</code></td>
<td align="center"></td>
<td align="center">View More Info (Library)</td>
<td align="center">Mic 2 Volume (Song)</td>
</tr>
<tr>
<td align="center">Left Stick: Up</td>
<td align="center"><code>W</code>, and <code>Left Shift</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/wb.png" alt="Whammy Bar" title="Whammy Bar"></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Left Stick: Left</td>
<td align="center"><code>A</code></td>
<td align="center"></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Left Stick: Down</td>
<td align="center"><code>S</code></td>
<td align="center"></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Left Stick: Right</td>
<td align="center"><code>D</code></td>
<td align="center"></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><code>Up</code></td>
<td align="center">Navigation</td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><code>Return</code></td>
<td align="center"></td>
<td align="center">Options</td>
<td align="center">Pause (Song)</td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><code>Space</code></td>
<td align="center">Overdrive</td>
<td align="center"></td>
<td align="center">Pause (Song)</td>
</tr>
</tbody>
</table><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/padpckbfnfmapping.png" alt="Mapping" title="Mapping"></div>
<!-- tab content end -->
</div>
<!-- end tab start -->
<!-- next tab start -->
<div role="tabpanel" class="tab-pane" id="fortnitepro">
<!-- tab content start -->
<h3 id="manual-strum-guitarsbasskeys">Manual Strum Guitars/Bass/Keys</h3>
<p>A profile inspired by both Fortnite Festival’s Pro bindings and Frets on Fire. Modified by Doom05 to work a bit better with Rock Band 3.</p>
<ul>
<li>This profile requires strumming. While holding a fret, press the strum buttons.</li>
<li>To bind multiple keys to one button, hold Shift then click on the button you want to assign multiple keys to.</li>
</ul>
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
<td align="center">Keyboard</td>
<td align="center">Keyboard</td>
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
</table><h4 id="bindings">Bindings</h4>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Keyboard</strong></th>
<th align="center"><strong>Guitars/Bass/Keys</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross</td>
<td align="center"><code>1</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/gf.png" alt="Green Fret" title="Green Fret"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><code>2</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/rf.png" alt="Red Fret" title="Red Fret"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><code>3</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><code>4</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><code>5</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/of.png" alt="Orange Fret" title="Orange Fret"></td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><code>L</code>, and <code>Up Arrow</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/sbu.png" alt="Strumbar Up" title="Strumbar Up"></td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><code>P</code>, and <code>Left Arrow</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/sbd.png" alt="Strumbar Down" title="Strumbar Down"></td>
</tr>
<tr>
<td align="center"><code>W</code></td>
<td align="center">D-Pad: Up</td>
<td align="center">Navigation</td>
</tr>
<tr>
<td align="center"><code>A</code></td>
<td align="center">D-Pad: Left</td>
<td align="center">Navigation</td>
</tr>
<tr>
<td align="center"><code>S</code></td>
<td align="center">D-Pad: Down</td>
<td align="center">Navigation</td>
</tr>
<tr>
<td align="center"><code>D</code></td>
<td align="center">D-Pad: Right</td>
<td align="center">Navigation</td>
</tr>
<tr>
<td align="center">Right Stick: Right</td>
<td align="center"><code>;</code>, and <code>Down Arrow</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/wb.png" alt="Whammy Bar" title="Whammy Bar"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><code>'</code>, and <code>Right Arrow</code></td>
<td align="center">Overdrive</td>
</tr>
</tbody>
</table><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/padpckbfnfpromapping.png" alt="Mapping" title="Mapping"></div>
<!-- tab content end -->
</div>
<!-- end tab start -->
<!-- next tab start -->
<div role="tabpanel" class="tab-pane" id="linos-binds">
<!-- tab content start -->
<h3 id="linos-profile">Linos’ Profile</h3>
<p>A profile used by MiloHax’s favorite keyboard player. Has plenty of alt-keys for acceptable drumming as well as guitar playing.</p>
<ul>
<li>This profile does not require strumming.</li>
<li>To bind multiple keys to one button, hold Shift then click on the button you want to assign multiple keys to.</li>
</ul>
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
<td align="center">Keyboard</td>
<td align="center">Keyboard</td>
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
<td align="center">Standard (Pad)</td>
<td align="center">PS3 Controller</td>
</tr>
</tbody>
</table><h4 id="bindings">Bindings</h4>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Keyboard</strong></th>
<th align="center"><strong>Guitars/Bass/Keys</strong></th>
<th align="center"><strong>Drums</strong></th>
<th align="center"><strong>Alt Use 1</strong></th>
<th align="center"><strong>Alt Use 2</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">L1</td>
<td align="center"><code>2</code>, <code>8</code>, <code>A</code>, and <code>W</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/gf.png" alt="Green Fret" title="Green Fret"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/rp.png" alt="Red Pad" title="Red Pad"></td>
<td align="center">Guide Part Selection (Practice)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><code>1</code>, <code>7</code>, <code>Q</code>, and <code>SPACE</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/rf.png" alt="Red Fret" title="Red Fret"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Foot Pedal" title="Foot Pedal"></td>
<td align="center">Vocal Part Selection (Practice)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><code>3</code>, <code>9</code>, <code>E</code>, and <code>S</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/yf.png" alt="Yellow Fret" title="Yellow Fret"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/yp.png" alt="Yellow Pad" title="Yellow Pad"></td>
<td align="center">Vocal Track Volume (Song)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">R2</td>
<td align="center"><code>0</code>, <code>4</code>, <code>D</code>, and <code>R</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/bf.png" alt="Blue Fret" title="Blue Fret"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/bp.png" alt="Blue Pad" title="Blue Pad"></td>
<td align="center">Pitch Correction (Song)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><code>-</code>, <code>5</code>, <code>F</code>, and <code>T</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/of.png" alt="Orange Fret" title="Orange Fret"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/gp.png" alt="Green Pad" title="Green Pad"></td>
<td align="center">Select</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><code>C</code></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">Back</td>
<td align="center">Mic 3 Volume (Song)</td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><code>Z</code></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">Mic 1 Volume (Song)</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><code>V</code></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">View More Info (Library)</td>
<td align="center">Mic 2 Volume (Song)</td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><code>Up</code></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">D-Pad: Left</td>
<td align="center"><code>Left</code></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><code>Down</code></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">D-Pad: Right</td>
<td align="center"><code>Right</code></td>
<td align="center"></td>
<td align="center"></td>
<td align="center">Navigation</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><code>Shift Right</code></td>
<td align="center">Overdrive</td>
<td align="center">Overdrive</td>
<td align="center">Filters (Library)</td>
<td align="center"></td>
</tr>
</tbody>
</table><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/padpckbghmapping.png" alt="Mapping" title="Mapping"></div>
<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/padpckbghdrmsmapping.png" alt="Mapping" title="Mapping"></div>
<!-- tab content end -->
</div>
<!-- end tab start -->
<div role="tabpanel" class="tab-pane" id="ashunprodrums">
<!-- tab content start -->
<h3 id="ashun-pro-drums">Ashun Pro Drums</h3>
<p>A profile used by our favorite Colombian key-drummer, Ashun. Scientists are still questioning how anyone could use this profile.</p>
<ul>
<li>To bind multiple keys to one button, hold Shift then click on the button you want to assign multiple keys to.</li>
<li>If you don’t bind all modifiers, <strong>you</strong> will have dropped notes.</li>
</ul>
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
<td align="center">Keyboard</td>
<td align="center">Keyboard</td>
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
<td align="center">Drum</td>
<td align="center">Rock Band Pro</td>
</tr>
</tbody>
</table><h4 id="bindings">Bindings</h4>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Keyboard</strong></th>
<th align="center"><strong>Drums</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Circle</td>
<td align="center"><code>A</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/rp.png" alt="Red Pad" title="Red Pad"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><code>S</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/yp.png" alt="Yellow Pad" title="Yellow Pad"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><code>O</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/bp.png" alt="Blue Pad" title="Blue Pad"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><code>P</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/gp.png" alt="Green Pad" title="Green Pad"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><code>W</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/yc.png" alt="Yellow Cymbal" title="Yellow Cymbal"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><code>0</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/bc.png" alt="Blue Cymbal" title="Blue Cymbal"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><code>-</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/gc.png" alt="Green Cymbal" title="Green Cymbal"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><code>,</code> and <code>Space</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Foot Pedal" title="Foot Pedal"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><code>C</code></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Foot Pedal" title="Foot Pedal"></td>
</tr>
<tr>
<td align="center">L3</td>
<td align="center"><code>A</code>, <code>O</code>, <code>P</code>, and <code>S</code></td>
<td align="center">Pad Modifier</td>
</tr>
<tr>
<td align="center">R3</td>
<td align="center"><code>W</code>, <code>0</code>, and <code>-</code></td>
<td align="center">Cymbal Modifier</td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><code>W</code></td>
<td align="center">Yellow Cymbal Modifier</td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><code>0</code></td>
<td align="center">Blue Cymbal Modifier</td>
</tr>
</tbody>
</table><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/padpckbpdrmsmapping.png" alt="Mapping" title="Mapping"></div>
</div>
</div>

## Profiles

[[Download Profiles]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/PC%20Keyboard.7z)

<!-- Profiles Start -->
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

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Research by [[Linos]](https://www.youtube.com/@LinosMelendi)

Alternative mapping schemes by [[lunalawl]](https://github.com/lunalawl), [[Doom05]](https://www.youtube.com/channel/UCZBzTTsPrK_gXF0ZvHkR3jA), and [[Ashun]](https://www.twitch.tv/ashun_)