---
title: "Custom Configuration: Audio"
sidebar: english_sidebar
permalink: custom_config_aud
folder: english
tags: [custom-config, english]
summary: "What to change for Rock Band 3 under the CPU tab in RPCS3's Custom Configuration."
series: "Custom Configuration"
weight: 4
---

![A screenshot of Rock Band 3's Audio custom settings, highlighting Enable Buffering in green with a dashed outline, Audio Buffer and Audio Out highlighted in blue with a dotted outline, and Microphone Settings, Microphone Type (Standard), Mic1, Mic2, Mic3, and Mic4 highlighted in tan with a solid outline.](https://rb3pc.milohax.org/images/cust/audio.png "Audio")

* ![A blue square with a dotted outline.](https://rb3pc.milohax.org/images/cust/smallblue.png "Blue Square") **Tweak depending on audio hardware and CPU**: 
	* **Adjust "Audio Buffer Duration"** depending on system.
		* Lower values give you less audio latency but use more CPU.
		* Higher values give you more audio latency but use less CPU.
		* Vocalists are affected the most by this, as a higher latency creates a distracting echo. Instrument players can use calibration to compensate regardless of audio buffer setting.
		* You can change this while the game is running, but it will require re-calibrating in Rock Band 3's system settings.
	* **Change "Audio Out" to "XAudio2"** - While **most users should stay on Cubeb**, a couple of people have experienced better performance with XAudio2. Your milage may vary.

* ![A tan square with a solid outline.](https://rb3pc.milohax.org/images/cust/smalltan.png "Tan Square") **For Vocalists**: 
	* **Set Microphone type to Standard or Rocksmith**.
	* **Select an input device in "Mic1", "Mic2", and "Mic3"** for vocals. If not playing vocals, Mic1 will be used for voice chat.
	* Once again, keep in mind that playing with framerates higher than 60 may cause issues with vocal detection.

<br/>

{% include custom/series_custom_config_next.html %}

{% include links.html %}