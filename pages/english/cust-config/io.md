---
title: "Custom Configuration: I/O"
sidebar: english_sidebar
permalink: custom_config_io
folder: english
tags: [custom-config, english]
summary: "What to change for Rock Band 3 under the CPU tab in RPCS3's Custom Configuration."
series: "Custom Configuration"
weight: 5
---

**This section is for people playing with USB/MIDI Keyboards, Pro Guitars, or MIDI Drums!**
* **If you're not playing with a wired Pro Guitar, Pro Drums, or a USB/MIDI keyboard,** [[**skip** over **this section**].](https://carlmylo.github.io/rb3-pc/custom_config_net)  
* **If you're playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar,** [[**skip** over **this section**].](https://carlmylo.github.io/rb3-pc/custom_config_net)  

**Make sure your MIDI instrument is connected.** After that, let's go ahead and **focus on RPCS3's I/O tab.**
**YOU MAY HAVE TO MAKE THE WINDOW WIDER TO READ THE OPTIONS!**
![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, device selection, and Keep Pads Connected highlighted in tan with a solid outline, and Pad Handler Mode highlighted in blue with a dotted outline.](https://carlmylo.github.io/rb3-pc/images/cust/io.png "I/O")

* ![A blue square with a dotted outline.](https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png "Tan Square") **Performance Tweaks**: 
	* **Change "Pad Handler Mode" to "Multi-threaded"** - May help with thread distribution, leading to more even performance. Your mileage may vary.

* ![A tan square with a solid outline.](https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png "Tan Square") **Recommended**: 
	* 🎹 **MIDI Keyboard Players: Leave your "Emulated MIDI type" on "Keyboard" and select your keyboard or MIDI interface in the drop-down menu next to it**.
	* 🎸 **MIDI Pro Guitar Players: Change your "Emulated MIDI type" from "Keyboard" to "Guitar (17 Frets)" if you have a Mustang Pro Guitar, or "Guitar (22 Frets)" if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it**.
	* 🥁 **MIDI Pro Drums Players: Change your "Emulated MIDI type" from "Keyboard" to "Drums", then select your Electronic MIDI Drum Kit or MIDI to USB interface in the drop-down menu next to it**.
	* **Enable "Keep Pads Connected"** - This can help fix a problem with instrument controllers soft-locking the game when RPCS3 interfaces, such as the RPCN invites, come up.

Revisit the [[Controllers page]](https://carlmylo.github.io/rb3-pc/ctrls) if you need help.

<br/>

{% include custom/series_custom_config_next.html %}

{% include links.html %}