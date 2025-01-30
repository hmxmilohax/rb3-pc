---
title: MIDI Keyboard
sidebar: controllers_sidebar
permalink: ctrls_keys_midi
folder: instruments
tags: [midi, english]
summary: "How to connect and configure a MIDI Keyboard on RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/midi.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/midikeyscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* There is no binding file.
* **Do NOT map this instrument via Gamepad Configuration.**
* It is suggested to have a keyboard with **at least 37 keys** or 25 keys and 11 drum pads.
* Your MIDI keyboard needs to:
	* **be set to MIDI Channel 1.**
	* **have modultation and pitch controls.**
	* optionally have a sustain pedal
* Requires the latest version of [[RPCS3]](https://rpcs3.net/download)
* RPCN Menus (for sending or accepting online invites) will cause a softlock. You will need an alternative input method to navigate these menus, such as a typing keyboard or a gamepad.

## Instructions

**If your keyboard has a USB port**, all you need to do is **plug it into your computer**.  

>![A picture of a MIDI controller's back, showing a USB port and a sustain pedal](https://carlmylo.github.io/docu-rpcs3/images/midi/usbkeys.png "USB Keyboard")  

**If your keyboard only has a MIDI output, you will need a MIDI to USB interface**.

>![A picture of a MIDI controller's back, showing a 5-DIN MIDI input and output highlighted in yellow with a solid white outline, and multiple pedal inputs.](https://carlmylo.github.io/docu-rpcs3/images/midi/midikeys.png "MIDI Keyboard")  

Here's an example of a MIDI to USB interface. Most will come with an LED indicator to show activity. **To check that you've plugged it in correctly, you should see "MIDI In" blinking when you press a key**. 

>![A picture of a MIDI to USB interface.](https://carlmylo.github.io/docu-rpcs3/images/midi/miditousb.png "MIDI to USB interface")  

**If you have an audio interface, you may already have a way to plug in MIDI** to your computer, as some audio interfaces come with MIDI inputs. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](https://carlmylo.github.io/docu-rpcs3/images/midi/midifs.png "Focusrite Scarlett MIDI in/out") 

Find whichever way is the most convenient for you then connect your MIDI Keyboard to your computer.

After that, **right click on Rock Band 3** in RPCS3, then click on “**Change Custom Configuration**”.  

![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://carlmylo.github.io/docu-rpcs3/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline.](https://carlmylo.github.io/docu-rpcs3/images/cust/iok.png "I/O")

* ![A tan square with a solid outline](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Tan Square") : 
	* 🎹 Keyboard Players: Leave your “Emulated MIDI type” on “Keyboard” and select your keyboard or MIDI interface in the drop-down menu next to it.

### Mapping

MIDI Keyboards have fixed bindings and cannot be changed within RPCS3.

![A picture of a 37 key keyboard, showing the second octave mapped to PlayStation buttons, C3 to E3 under a red color, F3 to B3 under a yellow color, C4 to E4 under a blue color, F4 to B4 under a green color, and C5 under an orange color.](https://carlmylo.github.io/docu-rpcs3/images/midi/keysctrl.png "MIDI Keyboard Reference")

| **Note#** | **Note** | **Note (Yamaha)** | **Button** |
|:-------:|:--------:|:-----------------:|:----------:|
| #36 | C2 | C1 | ![Select](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/sel.png "Select") |
| #38 | D2 | D1 | ![D-Pad Left](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dl.png "D-Pad Left") |
| #40 | E2 | E1 | ![D-Pad Right](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dr.png "D-Pad Right") |
| #41 | F2 | F1 | ![D-Pad Up](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/du.png "D-Pad Up") |
| #43 | G2 | G1 | ![D-Pad Down](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dd.png "D-Pad Down") |
| #45 | A2 | A1 | Deploy Overdrive |
| #37 | C#2 | C#1 | ![Triangle](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/t.png "Triangle") |
| #39 | D#2 | D#1 | ![Square](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/s.png "Square") |
| #42 | F#2 | F#1 | ![Circle](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/o.png "Circle") |
| #44 | G#2 | G#1 | ![Cross](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/x.png "Cross") |
| #46 | A#2 | A#1 | ![Start](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/sta.png "Start") |
| Pitch Bend | Pitch Bend | Pitch Bend | Whammy/Touch Strip |
| CC#1 | Modwheel | Modwheel | Deploy Overdrive |
| CC#64 | Sustain | Sustain | Deploy Overdrive |

#### 25 Key Keyboards

Keyboards with less than 25 keys will have to shift octaves when switching between the game keys and the game buttons.

![A GIF of a MIDI keyboard. When the octave down button is activated, a yellow highlight, showing which notes are being used, shifts down to C2 to C4. When the octave down button is deactivated, it shifts back up to C3 to C5.](https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midikeysoctshift.gif "Octave Shifting") 

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#using-a-computer-keyboard-along-with-a-25-key-keyboard">Using a computer keyboard along with a 25 key keyboard</a>
                            </h4>
                        </div>
                        <div id="using-a-computer-keyboard-along-with-a-25-key-keyboard" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <ul>
<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>This requires advanced setup!</b> {{include.content}}</div>
<p>You can use your regular computer keyboard and convert its key presses to the MIDI notes that correspond to the game buttons in case you want to avoid swapping octaves constantly.<br>
First, <a href="https://www.tobias-erichsen.de/software/loopmidi.html">[download loopMIDI]</a>.</p>
<p><a href="https://www.tobias-erichsen.de/software/loopmidi.html" title="Tobias Erichsen - loopMIDI"><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlloopMIDIdl.png" alt="A screenshot of loopMIDI's download page."></a></p>
<p>Install loopMIDI. <strong>Launch it after it finishes.</strong></p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlloopMIDIinst.png" alt="A screenshot of loopMIDI's installer." title="loopMIDI Setup"></p>
<p>Add two new ports by clicking on the <code>+</code> button in the bottom. You should name the ports, too. They’ve been named “Pro Keys” and “Gamepad” in this example.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlloopMIDIaddport.png" alt="A screenshot of loopMIDI, with a mouse cursor over the Plus symbol for &quot;Add Port&quot;. Additionally, &quot;New port name&quot; is highlighted in blue with a dotted outline, with &quot;Pro Keys&quot; typed out in the text field." title="loopMIDI"></p>
<p>Now, <a href="https://freepiano.tiwb.com/en/">[the <code>.zip</code> archive that contains the win64 version of FreePiano]</a>.</p>
<p><a href="https://freepiano.tiwb.com/en" title="FreePiano - Advanced virtual MIDI keyboard"><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnodl.png" alt="A screenshot of FreePiano's download page."></a></p>
<p>Extract the <code>.zip</code> archive somewhere you can easily find it. It was extracted to <code>C:\Games\freepiano</code> in this example.</p>
<p>Go to where you extracted FreePiano and run the <code>freepiano</code> executable.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnodir.png" alt="A screenshot showing the FreePiano executable highlighted." title="freepiano.exe"></p>
<p>Assign the keys to your liking as shown in the <a href="#mapping"><strong>[#mapping]</strong></a> section above.</p>
<p>There is also a premade profile if you’d like, which you can <a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/rb3gamekeys.map"><strong>[download here]</strong></a>.</p>
<p>To use the preset, place the <code>rb3gamekeys.map</code> file in the <code>keymap</code> folder located where you extracted FreePiano.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnopreset.png" alt="A screenshot of the profile, named rb3gamekeys.map, in the keymap folder, highlighted." title="keymap"></p>
<p>Select <code>rb3gamekeys.map</code> in the “Keymap” dropdown button to load the premade profile. Likewise, if you made your own profile or edited the premade profile, you can click on <strong>Save</strong> to save your profile.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnoselpres.png" alt="A screenshot of FreePiano, with the rb3gamekeys.map profile selected." title="rb3gamekeys.map"></p>
<p>The premade profile is mapped like this:</p>

<table>
<thead>
<tr>
<th align="center"><strong>Key</strong></th>
<th align="center"><strong>Action</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Enter</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/sta.png" alt="Start" title="Start"></td>
</tr>
<tr>
<td align="center">Shift</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/sel.png" alt="Select" title="Select"></td>
</tr>
<tr>
<td align="center">Up</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/du.png" alt="D-Pad Up" title="D-Pad Up"></td>
</tr>
<tr>
<td align="center">Down</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dd.png" alt="D-Pad Down" title="D-Pad Down"></td>
</tr>
<tr>
<td align="center">Left</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dl.png" alt="D-Pad Left" title="D-Pad Left"></td>
</tr>
<tr>
<td align="center">Right</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/dr.png" alt="D-Pad Right" title="D-Pad Right"></td>
</tr>
<tr>
<td align="center">A</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/x.png" alt="Cross" title="Cross"></td>
</tr>
<tr>
<td align="center">S</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/o.png" alt="Circle" title="Circle"></td>
</tr>
<tr>
<td align="center">D</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/s.png" alt="Square" title="Square"></td>
</tr>
<tr>
<td align="center">F</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/ps3/t.png" alt="Triangle" title="Triangle"></td>
</tr>
</tbody>
</table><p>Once you are done mapping, click on “Instrument” at the top of Freepiano’s window and select the “Gamepad” MIDI output, which you made with loopMIDI earlier.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnoout.png" alt="A screenshot of FreePiano's Instrument dropdown menu, with &quot;Gamepad MIDI&quot; selected." title="Gamepad"></p>
<p>It’s suggested you enable “Background input mode”, located within the “Options” tab which is accessed by pressing the Wrench icon in the top right side of FreePiano.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlfreepnoback.png" alt="A screenshot of FreePiano, with the &quot;Background input mode&quot; enabled." title="Background input mode"></p>
<p>Now, <a href="http://www.midiox.com/moxdown.htm">[download MIDI-OX]</a>.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlmidioxdl.png" alt="A screenshot of MIDI-OX's website, with the proper download highlighted in blue with a dotted outline." title="MIDI-OX 7.0.2"></p>
<p>Install MIDI-OX.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlmidioxinst.png" alt="A screenshot of MIDI-OX's installer." title="MIDI-OX Setup Wizard"></p>
<p>Open MIDI-OX then navigate to <strong>Options &gt; MIDI Devices</strong></p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlmidioxopts.png" alt="A screenshot of MIDI-OX, with the mouse hovering over the MIDI Devices menu, under the Options menu." title="Options > Midi Devices"></p>
<p>In the MIDI Devices Menu, select your keyboard and the port you made in loopMIDI (“Gamepad”) for FreePiano in the MIDI Inputs section.<br>
Select the other port you made in loopMIDI (“Pro Keys”) in the MIDI Outputs. This will combine both MIDI inputs into a single output.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlmidioxcombo.png" alt="A screenshot of MIDI-OX's MIDI Devices, with a keyboard and the Gamepad selected in the MIDI Inputs section and Pro Keys selected in the MIDI Outputs section." title="MIDI Devices"></p>
<p>Finally, in RPCS3, go to Rock Band 3’s Custom Configuration then go to the I/O tab. Select the port that you selected as your output in MIDI-OX (“Pro Keys”).</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/xtra/midi/midictrlrpcs3.png" alt="A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline. It is set to &quot;Keyboard - Pro Keys 3&quot;" title="Settings: [BLUS30463] Rock Band 3"></p>
<p>That’s it. Remember to close all <strong>three different programs</strong> when you’re not using them because they may cause issues with certain shortcuts on Windows.<br>
You will have to reopen these programs every time you want to play.</p>


</ul>.
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Back to Controllers]](https://carlmylo.github.io/docu-rpcs3/ctrls#instrument-list)

Implementation by [[Dark]](https://dark.ski/)
