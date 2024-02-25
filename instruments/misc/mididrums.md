---
title: MIDI Drums
author: Carl Mylo
date: 
category: Instruments
layout: post
---

## NOTES:

* Requires an electronic MIDI Drum Kit connected via USB or a MIDI to USB interface.
* Requires the latest version of [[RPCS3]](https://rpcs3.net/download)
* By default:
	* START: Hihat Pedal, Hihat Pedal, Hihat Pedal, Snare
	* SELECT: Hihat Pedal, Hihat Pedal, Hihat Pedal, Snare Rim
	* Song select shortcuts: Hihat Pedal, Hihat Pedal, Hihat Pedal, Kick

## Instructions:
**Right click on Rock Band 3** in RPCS3, then click on “**Change Custom Configuration**”.  

![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/pcs3customconfigchange.png "Change Custom Configuration")

![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/iod.png "I/O")
* ![A tan square with a solid outline](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Tan Square") : 
	* 🥁 **Change your "Emulated MIDI type" from "Keyboard" to "Drums", then select your MIDI Electronic Drum Kit or MIDI to USB interface in the drop-down menu next to it**.

### Additional Setup:

You can adjust a variety of options in the `rb3drums.yml` file, located within the `config` folder inside your RPCS3 installation folder.

#### Remapping
If your drum kits have incompatible mapping, you can remap using `Midi id to note override: ""` with the corrected notes.
* To do this:
	* Go to [MIDI Monitor](https://www.midimonitor.com/)
	* Play the pad you want to replace to find its MIDI Note number ("Note #[number]").

The file uses the following note names:

`Kick`  
`HihatPedal`  
`Snare`  
`SnareRim`  
`HiTom`  
`LowTom`  
`FloorTom`  
`HihatWithPedalUp`  
`Hihat`  
`Ride`  
`Crash`

Examples of common replacements:
* Blue cymbal is mapped to `Note #51` and Green cymbals is mapped to `Note #49` and you kit has these reversed.
	* `Midi id to note override: "49=Ride,51=Crash"` will reverse them to be closer to the game's layout
* You want to map to Open Hi-Hat to to Blue cymbal.
	* `Midi id to note override: "46=Ride"`

In `rb3drums.yml`, you will find `Combo Start`, `Combo Select`, `Combo Toggle Hold Kick`, which allow you to customize the combos to active their respective buttons.

Default Mapping:

| **MIDI Note#** | **Trigger Type** | **In-Game Action** |
|:--------:|:-------------------:|:-----------------:|
| **38**, 31, 34, 37, 39, 40 | Snare | ![Red Pad](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/btns/drms/rb/rp.png "Red Pad") |
| **48**, 50 | Hi-tom | ![Yellow Pad](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/btns/drms/rb/yp.png "Yellow Pad") |
| **45**, 50 | Low-tom | ![Blue Pad](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/btns/drms/rb/bp.png "Blue Pad") |
| **41**, 43 | Floor-tom | ![Green Pad](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/btns/drms/rb/gp.png "Green Pad") |
| **22**, 26, 42, 46, 54 | Hi-Hat Cymbal | ![Yellow Cymbal](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/btns/drms/rb/yc.png "Yellow Cymbal") |
| **51**, 53, 56, 59 | Ride Cymbal | ![Blue Cymbal](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/btns/drms/rb/bc.png "Blue Cymbal") |
| **49**, 52, 55, 57 | Crash Cymbal | ![Green Cymbal](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/btns/drms/rb/gc.png "Green Cymbal") |
| **33**, 35, 36 | Kick Pedal | ![Foot Pedal](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/btns/drms/rb/kp.png "Foot Pedal") |
| **44** | Hi-Hat Pedal | Hi-Hat Pedal |
| **CC#4 (Foot controller)** | Hi-Hat Pedal Position | Allows Hi-Hat pedal to be held closed |

![Platform](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/instruments/midi.png "Platform") 

![Controller](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/instruments/mididrumscontroller.png "Controller") 


Research by [[Linos]](https://www.youtube.com/@LinosMelendi)