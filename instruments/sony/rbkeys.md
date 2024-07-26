---
title: PlayStation 3 Rock Band Wireless Keyboard
author: Carl Mylo
date: 
category: Instruments
layout: post
---

<div align="center"> <img src="https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/plat/ps3.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/cont/ps3rbkeyscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* It's strongly suggested you connect the keyboard with the dongle, if you have it. [[Click here for instructions on how to set that up.]](https://rb3pc.milohax.org/english/passthroughdevices/)
* **Do NOT map this instrument via Gamepad Configuration.**
* There is no binding file.
* This is meant for players that have the keyboards connected via a MIDI to USB interface.
* None of the controller buttons will work as intended as the keyboard will be in MIDI mode.
* Requires the latest version of [[RPCS3]](https://rpcs3.net/download)
* RPCN Menus (for sending or accepting online invites) will cause a softlock. You will need an alternative input method to navigate these menus, such as a typing keyboard or a gamepad.

## Instructions

**Right click on Rock Band 3** in RPCS3, then click on “**Change Custom Configuration**”.  

![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/io.png "I/O")

* ![A tan square with a solid outline](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Tan Square") :
	* 🎹 **Leave your "Emulated MIDI type" on "Keyboard" and select your MIDI interface in the drop-down menu next to it.**.

### Additional Information

Since the keyboard controller buttons don't function like they do when connected with a dongle, you will have to shift octaves to access the buttons on the keys.

You can shift octaves with the Square and Circle buttons.

![A GIF of a Rock Band 3 keyboard. When X (which is Square on PS3) is pressed, a yellow highlight, showing which notes are being used, shifts down to C to C4. When B (which is Circle on PS3) is pressed, it shifts up to C3 to C5.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/rbkeysoctshift.gif "Octave Shifting") 

#### Using a computer keyboard along with a 25 key keyboard.

If you insist on using a 25 key keyboard without drum pads, you can use your regular computer keyboard and convert its key presses to the MIDI notes that correspond to the game buttons.
First, [[download loopMIDI]](https://www.tobias-erichsen.de/software/loopmidi.html).

[![A screenshot of loopMIDI's download page.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlloopMIDIdl.png)](https://www.tobias-erichsen.de/software/loopmidi.html "Tobias Erichsen - loopMIDI")

Install loopMIDI. **Launch it after it finishes.**

![A screenshot of loopMIDI's installer.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlloopMIDIinst.png "loopMIDI Setup")

Add two new ports by clicking on the `+` button in the bottom. You should name the ports, too. They've been named "Pro Keys" and "Gamepad" in this example.

![A screenshot of loopMIDI, with a mouse cursor over the Plus symbol for "Add Port". Additionally, "New port name" is highlighted in blue with a dotted outline, with "Pro Keys" typed out in the text field.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlloopMIDIaddport.png "loopMIDI")

Now, [[the `.zip` archive that contains the win64 version of FreePiano]](https://freepiano.tiwb.com/en/).

[![A screenshot of FreePiano's download page.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlfreepnodl.png)](https://freepiano.tiwb.com/en "FreePiano - Advanced virtual MIDI keyboard")

Extract the `.zip` archive somewhere you can easily find it. It was extracted to `C:\Games\freepiano` in this example.

Go to where you extracted FreePiano and run the `freepiano` executable.

![A screenshot showing the FreePiano executable highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlfreepnodir.png "freepiano.exe")

Assign the keys to your liking as shown in the [**[#mapping]**](#mapping) section above.

There is also a premade profile if you'd like, which you can [**[download here]**](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/rb3gamekeys.map).

To use the preset, place the `rb3gamekeys.map` file in the `keymap` folder located where you extracted FreePiano.

![A screenshot of the profile, named rb3gamekeys.map, in the keymap folder, highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlfreepnopreset.png "keymap")

Select `rb3gamekeys.map` in the "Keymap" dropdown button to load the premade profile. Likewise, if you made your own profile or edited the premade profile, you can click on **Save** to save your profile.

![A screenshot of FreePiano, with the rb3gamekeys.map profile selected.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlfreepnoselpres.png "rb3gamekeys.map")

The premade profile is mapped like this:

| **Key** | **Action** |
|:--------:|:-------------------:|
| Enter | ![Start](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/sta.png "Start") |
| Shift | ![Select](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/sel.png "Select") |
| Up | ![D-Pad Up](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/du.png "D-Pad Up") |
| Down | ![D-Pad Down](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/dd.png "D-Pad Down") |
| Left | ![D-Pad Left](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/dl.png "D-Pad Left") |
| Right | ![D-Pad Right](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/dr.png "D-Pad Right") |
| A | ![Cross](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/x.png "Cross") |
| S | ![Circle](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/o.png "Circle") |
| D | ![Square](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/s.png "Square") |
| F | ![Triangle](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps3/t.png "Triangle") |


Once you are done mapping, click on "Instrument" at the top of Freepiano's window and select the "Gamepad" MIDI output, which you made with loopMIDI earlier.

![A screenshot of FreePiano's Instrument dropdown menu, with "Gamepad MIDI" selected.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlfreepnoout.png "Gamepad")

It's suggested you enable "Background input mode", located within the "Options" tab which is accessed by pressing the Wrench icon in the top right side of FreePiano.

![A screenshot of FreePiano, with the "Background input mode" enabled.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlfreepnoback.png "Background input mode")

Now, [[download MIDI-OX]](http://www.midiox.com/moxdown.htm).

![A screenshot of MIDI-OX's website, with the proper download highlighted in blue with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlmidioxdl.png "MIDI-OX 7.0.2")

Install MIDI-OX.

![A screenshot of MIDI-OX's installer.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlmidioxinst.png "MIDI-OX Setup Wizard")

Open MIDI-OX then navigate to **Options > MIDI Devices**

![A screenshot of MIDI-OX, with the mouse hovering over the MIDI Devices menu, under the Options menu.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlmidioxopts.png "Options > Midi Devices")

In the MIDI Devices Menu, select your keyboard and the port you made in loopMIDI ("Gamepad") for FreePiano in the MIDI Inputs section.
Select the other port you made in loopMIDI ("Pro Keys") in the MIDI Outputs. This will combine both MIDI inputs into a single output.

![A screenshot of MIDI-OX's MIDI Devices, with a keyboard and the Gamepad selected in the MIDI Inputs section and Pro Keys selected in the MIDI Outputs section.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlmidioxcombo.png "MIDI Devices")

Finally, in RPCS3, go to Rock Band 3's Custom Configuration then go to the I/O tab. Select the port that you selected as your output in MIDI-OX ("Pro Keys").

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline. It is set to "Keyboard - Pro Keys 3"](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midictrlrpcs3.png "Settings: [BLUS30463] Rock Band 3")

That's it. Remember to close all **three different programs** when you're not using them because they may cause issues with certain shortcuts on Windows.
You will have to reopen these programs every time you want to play.

[[Back to Controllers]](https://rb3pc.milohax.org/english/controllers/)

Research by [[Linos]](https://www.youtube.com/@LinosMelendi)