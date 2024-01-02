## NOTES:

* This controller requires advanced configuration.
* Requires [[vJoy]](https://github.com/jshafer817/vJoy/releases)
* Requires [[MidiDrumHero]](https://github.com/ejj28/mididrumhero/releases/latest)
* Velocity sensitivity doesn't seem to work.
* Faster fills tend have dropped notes.

#### Additional Setup:

* [Follow the install process for MidiDrumHero](https://github.com/ejj28/mididrumhero)
* Map your drum kit in MidiDrum Hero.

An example MidiDrumhero mapping for an Alesis Nitro Mesh on default settings:
![MIDI Drum Hero](mididrumhero.png "MIDI Drum Hero") 


* Open "Configure vJoy" and:
	* Turn off everything udner "Axes" and "Force Feedback"
	* Change the number of buttons to "10"
	* Click "Apply" then "Reset All" when finished.
![vJoy](vjoy.png "vJoy") 
* For the mapping, here is the format:
	* Red pad = O + L3
	* Yellow Pad = Triangle + L3
	* Blue Pad = Square + L3
	* Green Pad = X + L3
	* Yellow Cymbal = Triangle + R3 + Up Dpad
	* Blue Cymbal = Square + R3 + Down Dpad
	* Green Cymbal = X + R3
	* Foot Pedal = L1
	* Hi-hat Pedal = R1
You want to Shift+Click to add extra bindings in the emulator.

If you want to map Start/Select for navigation, you can unmap R1 and use:
* Hi-Hat Pedal (with a high trigger velocity) to Start
* Hi-Hat Pedal (Lightly Pressed) + Hi-Hat to Select

<div align="center">

![Platform](platform.png "Platform") 

![Controller](controller.png "Controller") 

![Mapping](mapping.png "Mapping") 

</div>

Mapped by [[Linos]](https://www.youtube.com/@LinosMelendi)