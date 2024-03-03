---
title: Extra - Instrument Repo
author: Carl Mylo
date: 1000-10-01
category: English
layout: post
---

# What is this?

A repository of premade controller profiles for RPCS3 to help newcomers to Rock Band 3. These files should be simple drag and drop configurations for controllers.

# How to install:
Before you install, **if you have any bindings in `config\input_configs\BLUS30463`, you should back them up because they will be overwritten.**

1. Download the .7z file in the folder for the instrument(s) you want to use.
2. Extract the .7z file.
3. Drag the `config` folder into the folder you have RPCS3 in.

![A GIF of a user dragging the Wii Rock Band Guitar configuration into their RPCS3 folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/instrepoinstall.gif "Installing a configuration from the Instrument Repo")

Most of the time, these controller profiles should work out of the box but if they don't, try changing the controller listed in "`Devices`", next to the "`Refresh`" button until it receives an input. You can edit this while the game is running.

The profiles are formatted for single players. If you need to use a combination of various controllers for local multiplayer or want to quickly swap between multiple instruments, you can try the guide below for manually [[#mapping]](#mapping) additional controllers.

Alternatively, you can combine multiple files if you know your way around text editors like Notepad++ or Sublime Text.
Select everything from line 2 to the end of line 86 in the `Default.yml` file of the instrument you want to add, then copy it. 
Paste it into:
* Line 88 to 172 for Player 2
* Line 174 to 258 for Player 3
* Line 260 to 344 for Player 4
* Line 346 to 430 for Player 5
* Line 432 to 516 for Player 6
* Line 518 to 602 for Player 7

# Instrument List:

## Drums:
* [[MIDI Drums]](https://hmxmilohax.github.io/rb3-pc/instruments/misc/mididrums) - Does not include a profile but does have instructions. Requires a drum kit with at least one kick drum, one snare drum, one hi-hat, two cymbals, and three toms. Can have either MIDI to USB or USB outputs.
* [[Roll Limitless]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Roll%20Limitless%20Drums.7z) - Requires a drum kit with at least one kick drum, one snare drum, one hi-hat, two cymbals, and three toms. Must have a MIDI output.
	* Requires [[additional configuration]](https://hmxmilohax.github.io/rb3-pc/instruments/misc/rolllimitless)
* [[Xbox 360 Rock Band Drums]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Rock%20Band%20Drums.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/rbdrms)
* [[Xbox 360 Rock Band MIDI Pro Adapter Drums]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20MIDI%20Pro%20Adapter%20Drums.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/mpa)
* [[Xbox 360 Guitar Hero Drums]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Guitar%20Hero%20Drums.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/ghdrms)
* [[PS3 Guitar Hero Drums]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PS3%20Guitar%20Hero%20Drums.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/ps3/ghdrms)
* [[Wii Rock Band Drums]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Rock%20Band%20Drums.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/wii/rbdrms)
* [[Wii Guitar Hero Drums]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Guitar%20Hero%20Drums.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/wii/ghdrms)

## Guitars:
* [[Xbox 360 Rock Band Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Rock%20Band%20Guitar.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/rbgtrs)
* [[Wii Rock Band Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Rock%20Band%20Guitars.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/wii/rbgtrs)
* [[Xbox One Rock Band Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20One%20Rock%20Band%20Guitar.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/rb4gtrs)
	* Requires [[additional configuration]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/rb4gtrs)
* [[Xbox 360 Guitar Hero Les Paul Guitars]](https://github.com/hmxmilohax/rb3-pc/blob/main/instrument-repo/Xbox%20360%20Guitar%20Hero%20Les%20Paul.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/ghlp)
* [[Wii Guitar Hero Les Paul (Raphnet) Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20%5BRaphnet%5D.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/wii/raphlp)
* [[Wii Guitar Hero Les Paul (PI Pico) Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20%5BPi%20Pico%5D.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/misc/picolp)
* [[Xbox 360 Guitar Hero Xplorer Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Guitar%20Hero%20Xplorer.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/xplorer)
	* Requires [[additional configuration]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/xplorer)
* [[PS3 Guitar Hero Genericaster Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PS3%20Guitar%20Hero%20Genericaster.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/ps3/ghwttar)
* [[Xbox 360 Guitar Hero Genericaster Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Guitar%20Hero%20Genericaster%20Guitar.7z) - [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/ghwttar)
* [[PS2 Guitar Hero SG Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PS2%20Guitar%20Hero%20SG%20Guitar.7z) - **Requires a specific adapter**. [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/misc/ps2sg)
* [[PS3 Guitar Hero Les Paul]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PS3%20Guitar%20Hero%20Les%20Paul%20Guitar.7z) - **Not a recommended controller**. [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/ps3/ghlp)
* [[PC-Mac Guitar Hero World Tour Genericaster Guitars]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PC-Mac%20Guitar%20Hero%20World%20Tour%20Genericaster.7z) - **Not a recommended controller**. [[Notes]](https://hmxmilohax.github.io/rb3-pc/instruments/misc/pcghwt)
* [[PS3 Dualshock 3 Controller (Padtar)]](https://hmxmilohax.github.io/rb3-pc/instruments/ps3/ds3) - Does not include a profile but does have instructions.
* [[Xbox Controller (Padtar)]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/xb1pad) - Does not include a profile but does have instructions.
* [[PC Keyboard (Padtar)]](https://hmxmilohax.github.io/rb3-pc/instruments/misc/pckeyboard) - Does not include a profile but does have instructions.

## Keyboards:
* [[PS3 Rock Band 3 Keyboard]](https://hmxmilohax.github.io/rb3-pc/instruments/ps3/rbkeys) - Does not include a profile but does have instructions.
* [[Xbox 360 Rock Band 3 Keyboard]](https://hmxmilohax.github.io/rb3-pc/instruments/xbox/rbkeys) - Does not include a profile but does have instructions.
* [[Wii Rock Band 3 Keyboard]](https://hmxmilohax.github.io/rb3-pc/instruments/wii/rbkeys) - Does not include a profile but does have instructions.

# Missing Instruments:

## TODO:
* [TODO] Xbox One/Xbox Series S/X Rock Band 4 Drums
* [TODO] Wii Rock Band MIDI Pro Adapter Drums
* [TODO] Wii Guitar Hero Genericaster Guitar
* [TODO] PS2 Guitar Hero Kramer Striker
* [TODO] Arduino Drums

If you own any of these instruments and wish to help, please contact Carl Mylo on the [[Milohax Discord server]](https://rb3dx.neocities.org/downloads.html) for information.

## REJECTED:

* Rock Band 3 Fender Mustang Pro Guitar
	* PS3 version works via passthrough (Zadig), and PS3, X360, and Wii versions work via a MIDI to USB interface with the Emulated Midi Device in RPCS3 in the I/O tab.
* Rock Band 3 Squier Stratocaster Pro Guitar
	* PS3 version works via passthrough (Zadig), and PS3, X360, and Wii versions work via a MIDI to USB interface with the Emulated Midi Device in RPCS3 in the I/O tab.
* Rock Band Guitars (PS3 Versions)
	* They work via passthrough natively.
* Rock Band Drums (PS3 Versions)
	* They work via passthrough natively.
* Rock Band 4 Drum Kit (PS4 Version)
	* Bluetooth latency is unacceptable.
	* Pro Cymbals refuse to work due to the format they're in.
* Rock Band 4 Guitar Controllers (PS4 Version)
	* Bluetooth latency is unacceptable.
	* Pro Cymbals refuse to work due to the format they're in.

## CREDITS:

* [[TheNathannator's]](https://github.com/TheNathannator) [[PlasticBand GitHub]](https://github.com/TheNathannator/PlasticBand) for outstanding documentation on controllers.
* [[Jnack]](https://www.youtube.com/@jnackmclain) - Xbox 360 Xplorer, Xbox 360 MIDI Pro Adapter profiles
* [[Linos]](https://www.youtube.com/@LinosMelendi) - MIDI Drums, Keyboards research 
* [[KrazzyKlown]](https://www.youtube.com/@KrazzyKlown) - Xbox 360 Xplorer profile
* [[gonakil1ya]](https://linktr.ee/Gonakil1ya) - Xbox One Rock Band 4 Guitars, Xbox 360 Rock Band Drum Kit, Xbox 360 Rock Band Guitar, Xbox 360 Guitar Hero Les Paul, Xbox 360 Guitar Hero Genericaster profiles
* [[GamerPerson22]](https://www.youtube.com/channel/UCC5SlXPlnlGwBG7w6mvfx8g) - Wii Les Paul Raphnet, Xbox 360 Guitar Hero Drums, PS3 Guitar Hero Drums, PS3 Guitar Hero Genericaster, Wii Guitar Hero Drums profiles
* [Derd] - PS3 Guitar Hero World Tour, PC-Mac Guitar Hero World Tour Genericaster profiles
* [Uzny] - Roll Limitless profile
* [16bitblastprocessing] - PS3 Guitar Hero Les Paul
* [heartworthbreaking] - Wii Guitar Hero Ardwiino PI Pico Guitar profile
* [[cas]](https://www.youtube.com/channel/UCw2JKh7_Zt65kjENqjnvm_g) - PS2 Guitar Hero SG Guitar profile
* [[scott0852]](https://twitter.com/scott0852) - Wii Rock Band Drums
* [[SlothDemon]](https://www.youtube.com/@SlothDemon1991) - Padtar research
* [[Clone Hero Wiki]](https://wiki.clonehero.net/) - Instrument pictures.
