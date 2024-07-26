---
title: Quick Configuration
author: Carl Mylo
date: 1000-04-01
category: English_Configuration
layout: post
---

# About

These files are meant for those that just want to play with minimal setup. It is still strongly suggested that you do [[custom configuration]](https://github.com/hmxmilohax/rb3-pc/tree/main#custom-configuration) to tweak to what's best for your computer.  
[[**Rock Band 3 Deluxe must be installed**]](https://rb3dx.neocities.org/) but if it's not already installed, you're not reading this guide and should go back and read it.  

Players who want to use [[microphones]](https://rb3pc.milohax.org/english/customconfiguration#audio), [[Wired Pro Guitar and USB/MIDI Keyboards]](https://rb3pc.milohax.org/english/customconfiguration#io), [[Electronic Drum Kits]](https://rb3pc.milohax.org/english/customconfiguration#io), or [[PS3 Mustang guitars or RB3 Keyboards with dongles]](https://rb3pc.milohax.org/english/passthroughdevices/) will still need to configure those.

* [[Recommended settings]](https://github.com/hmxmilohax/rb3-pc/raw/main/config/customconfig/recommended.zip) - These are the settings used for the recommended specs listed in [[requirements]](https://rb3pc.milohax.org/english/requirements/).
* [[Minimum settings]](https://github.com/hmxmilohax/rb3-pc/raw/main/config/customconfig/minimum.zip) - These are the settings used for the minimum specs listed in [[requirements]](https://rb3pc.milohax.org/english/requirements/).

# Using
To use these, **click on the settings you want to download then extract the ZIP archives in the folder where you extracted RPCS3**. It should combine folders automatically if you did it right.  
In the GIF example below, the "Recommended" requirements settings archive (recommended.zip) was downloaded and its contents were moved into RPCS3's folder.

![A GIF of "config" and "dev_hdd0" from "recommended.zip" being moved into its proper location in RPCS3's folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/quickconf.gif "Recommended.zip")

# Affected Settings
If you need any more information about what these settings are changing:

### Recommended

* **CPU**:
	* SPU Block Size: Mega
* **GPU**:
	* Write Color Buffers
	* Framelimit: Off
	* Resolution Scale: 150% (1920x1080)
	* Anisotropic Filter: 16x
	* ZCULL Accuracy: Relaxed (Fastest)
	* VSync Enabled
* **Audio**:
		- Audio Buffer Duration: 32 ms
* **Network**:
	* Network Status: Connected
	* DNS: Configured for RBEnhanced
	* Enable UPNP: On
* **Advanced**:
	* Debug Console Mode: On
	* Exclusive Fullscreen Mode: Prefer Borderless fullscreen
	* Driver Wake-Up Delay: 20 µs
* **Emulator**:
	* Show trophy popups: Off

## Minimum

* **CPU**:
	* SPU Block Size: Mega
	* Preferred SPU Threads: 2
* **GPU**:
	* Write Color Buffers
	* Framelimit: Off
	* ZCULL Accuracy: Relaxed (Fastest)
* **Audio**:
	* Audio Buffer Duration: 100 ms
* **Network**:
	* Network Status: Connected
	* DNS: Configured for RBEnhanced
	* Enable UPNP: On
* **Advanced**:
	* Debug Console Mode: On
	* Exclusive Fullscreen Mode: Prefer Borderless fullscreen
	* Driver Wake-Up Delay: 40 µs
* **Emulator**:
	* Show trophy popups: Off