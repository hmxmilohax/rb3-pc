---
title: Custom Configuration
author: Carl Mylo
date: 1000-05-01
category: English_Configuration
layout: post
---

While Quick Configuration should work in most cases, some users might want to squeeze more fidelity or performance out of their game or prefer setting everything up themselves. This involves creating or editing a Custom Configuration for Rock Band 3.

## Creating a Custom Configuration

**Right click on Rock Band 3** in RPCS3, then click on “**Create Custom Configuration From Default Settings**”.  
![A screenshot of RPCS3's right click menu, showing "Create Custom Configuration From Default Settings" highlighted](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/rpcs3customconfig.png "Create Custom Configuration From Default Settings")

## Changing a Custom Configuration

**Right click on Rock Band 3** in RPCS3, then click on “**Change Custom Configuration**”.  
![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/rpcs3customconfigchange.png "Create Custom Configuration From Default Settings")

This may seem overwhelming because of the sheer number of options, but I have color-coded the settings that require adjustment. Anything not colored should be left alone.

| COLOR | MEANING |
|---|---|
| ![A green square with a dashed outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/biggreen.png "Green Square") | **REQUIRED** |
| ![A blue square with a dotted outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/bigblue.png "Blue Square") | **Performance Tweaks** |
| ![A tan square with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/bigtan.png "Tan Square") | **Recommended** |

We'll go tab by tab, starting with:

<br/>

## CPU

![A screenshot of Rock Band 3's CPU custom settings, showing SPU XFloat Accuracy, SPU Block Size, Preferred SPU Threads, and Thread Scheduler highlighted in blue with a dotted outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/cpu.png "CPU")

* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Tan Square") **Improved performance, depending on machine**: 
	* **Change "SPU Block Size" to "Mega"** - Ties smaller SPU compiled together, which requiring fewer cores/threads. Drastically speeds up game startup time on certain machines.
	* **Change "Preferred SPU Threads" to "1", "2", "3", or "4"** - May help prevent stutter caused by CPU overloads on systems with fewer cores/threads. **Start at 4 and lower it one by one until it improves**.
	* **Change "Thread Scheduler" to "RPCS3 Scheduler", or "RPCS3 Alternative Scheduler"** - **FOR CPUs WITH 12+ THREADS ONLY!** May help with thread distribution to prevent microstutters.

<br/>

## GPU

![A screenshot of Rock Band 3's GPU custom settings, highlighting Write Color Settings highlighted in green with a dotted outline, Framelimit, Anisotropic Filter, ZCull Accuracy, Output Scaling and VSync highlighted in blue with a dotted outline, and "Default Resolution" highlighted in tan with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/gpu.png "GPU")

* ![A green square with a dashed outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Enable "Write Color Buffers"** - Characters will have severe graphical bugs without this.

* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Blue Square") **Tweak depending on graphics card**: 
	* **Enable "VSync"** - Reduces screen tearing and may lead to a more stable framerate. Slightly increases input latency. **Do not enable this with the frame limiter**.
	* **Change "Frame Limit"** 
		* Set it to "Off" to use higher VBlank Frequencies, which may introduce jitter, **or if you're using VSync.**
		* Set it to 60 if you want a locked 60 FPS framerate (redundant with 60 Hz Vblank). 
		* Auto will use default RPCS3 settings.
		* It is suggested to use your graphics driver's settings or software like MSI Afterburner to cap your framerate instead.
		* Adjusting the frame rate to be higher than 60 exponentially uses more resources, so this is not recommended for low end machines.
		* Be aware that framerates higher than 60 may cause the vocal pitch detection to behave incorrectly.
	* **Change "ZCULL Accuracy" to "Relaxed"** - Provides a slight performance improvement but may cause graphical anomalies in very rare situations.
	* **Adjust "Resolution Scale"** to preference and to what your computer can handle. Increase for sharper graphics at the cost of higher GPU requirements. This forces the game to run at this resolution. Lowering this below 100% isn't worth it as it won't give much, if any, framerate gains.
	* **Adjust "Output Scaling"** to preference and to what your computer can handle. This affects how the game is "blown up" in size when fitting to your monitor's native resolution. Helpful for those keeping Resolution Scale (mentioned above) at 100% and playing on a monitor larger than 1280x720.
		* "Nearest" is completely unfiltered and gives you raw unmodified image. This can cause the game to look pixelated.
		* "Bilinear" uses smoothing to scale the image up. This may cause the game to look blurry. This can cause the game to look blurry.
		* FidelityFX Super Resolution (FSR) uses complicated math to sharpen and enhance the image when it gets blown up to your monitor's resolution. This can create odd artifacts in some instances.
			* You can use "RCAS Sharpening Strength" below to adjust the strength of its effect.

	* ![A tan square with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Tan Square") **For high-end GPUs and advanced users**: 
		* **Change "Default Resolution" to "1920x1080"**. While Rock Band 3 officially caps out at 720p, 1080p can be forced on by manually editing the configuration file or editing the game data configuration. Please refer to [the relevant guide on how to do this and what benefits there are](forcefullhd.md) after finishing up with everything else.

<br/>

## Audio

![A screenshot of Rock Band 3's Audio custom settings, highlighting Enable Buffering in green with a dashed outline, Audio Buffer and Audio Out highlighted in blue with a dotted outline, and Microphone Settings, Microphone Type (Standard), Mic1, Mic2, Mic3, and Mic4 highlighted in tan with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/audio.png "Audio")

* ![A green square with a dashed outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Enable "Enable Buffering"** - Absolutely required by Rock Band 3. It should be enabled by default but if it's disabled, re-enable it. You should set your global settings to default while you're at it because you should've done that to begin with.

* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Blue Square") **Tweak depending on audio hardware and CPU**: 
	* **Adjust "Audio Buffer Duration"** depending on system.
		* Lower values give you less audio latency but use more CPU.
		* Higher values give you more audio latency but use less CPU.
		* Vocalists are affected the most by this, as a higher latency creates a distracting echo. Instrument players can use calibration to compensate regardless of audio buffer setting.
		* You can change this while the game is running, but it will require re-calibrating in Rock Band 3's system settings.
	* **Change "Audio Out" to "XAudio2"** - This is only recommended for users on extremely low end machines as it causes weird audio problems overtime. Experiment with this setting to make sure it actually helps on your end. **Most users should stay on Cubeb!**

* ![A tan square with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Tan Square") **For Vocalists**: 
	* **Set Microphone type to Standard or Rocksmith**.
	* **Select an input device in "Mic1", "Mic2", and "Mic3"** for vocals. If not playing vocals, Mic1 will be used for voice chat.
	* Once again, keep in mind that playing with framerates higher than 60 may cause issues with vocal detection.

<br/>

## I/O

**This section is for people playing with USB/MIDI Keyboards, Pro Guitars, or MIDI Drums!**
* **If you're not playing with a wired Pro Guitar, Pro Drums, or a USB/MIDI keyboard,** [[**skip** over **this section**].](#network)  
* **If you're playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar,** [[**skip** over **this section**].](#network)  

**If your keyboard has a USB port**, all you need to do is **plug it into your computer**.  
![A picture of a MIDI controller's back, showing a USB port and a sustain pedal](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/usbkeys.png "USB Keyboard")  


**If your keyboard only has a MIDI output, you will need a MIDI to USB interface**.
![A picture of a MIDI controller's back, showing a 5-DIN MIDI input and output highlighted in yellow with a solid white outline, and multiple pedal inputs.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/midikeys.png "MIDI Keyboard")  

**The same applies to Rock Band 3 Pro Guitars** as they only have MIDI outputs.
![A picture of a Rock Band 3 Fender Mustang Pro Guitar, showing a 5-DIN MIDI output.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/midiprotar.png "Mustang Pro Guitar MIDI Output")  

Here's an example of a MIDI to USB interface. Most will come with an LED indicator to show activity. **To check that you've plugged it in correctly, you should see “MIDI In” blinking when you press a key**.  
![A picture of a MIDI to USB interface.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/miditousb.png "MIDI to USB interface")  


**If you have an audio interface, you may already have a way to plug in MIDI** to your computer, as some audio interfaces come with MIDI inputs. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  


**If everything's connected**, let's go ahead and **focus on RPCS3's I/O tab.**
**YOU MAY HAVE TO MAKE THE WINDOW WIDER TO READ THE OPTIONS!**
![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline, and Pad Handler Mode highlighted in blue with a dotted outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/io.png "I/O")
* ![A tan square with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Tan Square") **For third party Keyboard and wired Pro Guitar players**: 
	* 🎹 **Keyboard Players: Leave your "Emulated MIDI type" on "Keyboard" and select your keyboard or MIDI interface in the drop-down menu next to it.**.
	* 🎸 **Pro Guitar Players: Change your "Emulated MIDI type" from "Keyboard" to "Guitar (17 Frets)" if you have a Mustang Pro Guitar, or "Guitar (22 Frets)" if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it**.
	* 🎸 🥁 **Pro Drums Players: Change your "Emulated MIDI type" from "Keyboard" to "Drums", then select your MIDI Electronic Drum Kit or MIDI to USB interface in the drop-down menu next to it**.

Visit the instrument repo if you're using a [[Xbox 360]](https://github.com/carlmylo/rb3-pc/tree/main/instrument-repo/Xbox%20360%20Rock%20Band%203%20Keyboard#readme) or a [[Nintendo Wii]](https://github.com/carlmylo/rb3-pc/tree/main/instrument-repo/Wii%20Rock%20Band%20Keyboard#readme) Rock Band 3 Keyboard connected via MIDI to USB. Also visit the instrument repo if you're on a [[MIDI Drum Kit]](https://github.com/carlmylo/rb3-pc/tree/main/instrument-repo/MIDI%20Drums#readme) and wish to adjust mappings.

* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Blue Square") **Tweak depending on CPU**: 
	* **Change "Pad Handler Mode" to "Multi-threaded"** if you have a CPU **with more than 12 threads.**
  
 **If your instrument isn't detected in the drop-down menu, click on "Save custom configuration", close the Custom Configuration window, then right click on Rock Band 3 to reopen it. If that doesn't work, restart RPCS3.**  
  
As **keyboards don't have PS3 buttons, the first octave is** reserved **for mapped keys**. Use the picture below as a reference. I **strongly** suggest putting labels on your keyboard to remind you of what each key does along with color ranges. **The** keyboard's **pitch knob should be mapped to the touch strip and modulation wheel and sustain pedal should be mapped to Overdrive deployment.**
![A picture of a 37 key keyboard, showing the second octave mapped to PlayStation buttons, C3 to E3 under a red color, F3 to B3 under a yellow color, C4 to E4 under a blue color, F4 to B4 under a green color, and C5 under an orange color.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/keysctrl.png "MIDI Keyboard Reference")

<br/>

## Network
![A screenshot of Rock Band 3's Network custom settings, highlighting Network Status (Connected) in green with a dashed outline, IP/Hosts switches (rb3ps3live.hmxservices.com=45.33.48.123), PSN Status (RPCN), and Enable UPNP (not checked) highlighted in tan with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/network.png "Network")

* ![A green square with a dashed outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Change the Network Status to “Connected” as highlighted in the picture. If left on “Disconnected,” the game will temporarily freeze when browsing the song library.**

* ![A tan square with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Tan Square") **For online multiplayer**: 
	* You can tick **"Enable UPNP"** or **forward port 9103 (UDP) in your firewall**.
	* As of writing this, there are two Rock Band 3 multiplayer servers to connect to. You can easily switch between them.
		* **For AshCentral: Join the** [[**Milohax Discord server**]](https://rb3dx.neocities.org/discord) and **go to** the **[\[#ashcentral-status\]](https://discord.com/channels/961352072140324924/1153056600030973992)** channel. **Copy the information for RPCS3**. **This is the recommended server** due to having more features and frequent updates.  
		* For RBEnhanced GoCentral: Join the [[RBEnhanced Discord server]](https://discord.gg/6rRUWXPYwb) and go to the [[#gocentral-connecting]](https://discord.com/channels/953085263008129064/1076031372185042984) channel. Follow the instructions for RPCS3.  



<br/>

## Advanced

![A screenshot of Rock Band 3's Advanced custom settings, highlighting Driver Wake-Up Delay (1µ) in green with a dashed outline, "Exclusive Fullscreen Mode, VBlank Frequency, and Maximum Number of SPURS Threads highlighted in blue with a dotted outline, and Debug Console Mode highlighted in tan with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/advanced.png "Advanced")

* ![A green square with a dashed outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Change "Driver Wake-up Delay" to "20µ"** to avoid crashing after a few songs. Increase it to "40µ" if the issue persists.

* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Tan Square") **Depending on your computer**: 
	* **Adjust VBlank Frequency** if you want a higher internal framerate. This can make it easier to hit notes but may cause graphical instability and connection issues while online. **It's best left alone** and not recommended to go above 75 Hz if adjusting it for online play. Increasing it exponentially uses more CPU and GPU.
		* Once again, having a higher VBlank can cause issues with vocal detection.
	* **Change "Maximum Number of SPURS Threads"** - May improve performance on systems with less cores and threads [[like 4th gen Intel i5 CPUs with 4 cores and 4 threads]](https://github.com/carlmylo/rb3-pc/issues/12#issue-1955946005).

* ![A tan square with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Tan Square") **Strongly Suggested**: 
	* **Enable "Debug Console Mode"** - With Rock Band 3 Deluxe installed, and "Large Heap" enabled in its settings, along with this option enabled, you can take advantage of higher memory access, leading to longer sessions with longer songs and increased stability. If your computer is within the minimum (or higher) requirements, there's no reason you shouldn't enable this.
	* **Change "Exclusive Fullscreen Mode" to "Prefer borderless fullscreen"** to prevent potential crashes and audio desync when changing from Rock Band 3 to another program while in fullscreen.

<br/>

## Emulator

![A screenshot of Rock Band 3's Emulator custom settings, showing "Show trophy popups", "Show PPU compilation hint", "Show Shader Compilation hint", "Start Games in fullscreen mode", "Use native user interface."](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/emulator.png "Emulator")

You can leave this as is if you want, but I would consider changing the following options:
* ![A tan square with a solid outline.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Tan Square") **Optional tweaks**: 
	* **“Show trophy popups”** - Mimics the way Trophy notifications appear on the PS3. I personally disable this as the game has its own pop-ups.
	* **“Show PPU compilation hint”** - This creates a popup whenever RPCS3 is compiling units for the PPU. This only comes up once as the "Recompiler (LLVM)" setting in the CPU tab does this when launching the game.
	* **“Show shader compilation hint”** - This creates a popup whenever RPCS3 is compiling shaders. Whether you leave it on or not is up to you, but I should tell you what this means as it is important. When you run PS3 games, it has to compile shaders to “translate” the graphics from a PS3 format to a format your PC can work with. **The game will** appear to **stutter when this happens**. **This happens on ALL computer systems. When it finishes** compiling an effect, **it will usually never happen again**. **The best way to deal with this is** just **to** **play the game** as it will quickly go away. You can also use Rock Band 3 Deluxe's Autoplay modifier to let it go through a few songs in party shuffle and let it compile a decent amount of shaders.
	* **“Start games in Fullscreen mode”** - Switches to Fullscreen when you start Rock Band 3.
	* **“Use Native Interface”** - Removes the pretty displays RPCS3 adds, including notifications and game startup background. It will instead use old school pop-ups for keyboard prompts. This can also fix a problem with instrument controllers using MMJoystick soft locking the game when the keyboard comes up. The native interface also seems to cause slight frame rate drops.

<br/>

## Conclusion

**After all of that, remember to click "Apply" then "Save custom configuration"**

If everything seems to be working, **I'd also strongly suggest changing RPCS3's log to only display fatal errors** as it gets flooded by excess messages otherwise.

To do this, **right click in RPCS3's log at the bottom and then left click on "Fatal"**.

![A screenshot of RPCS3's log being right clicked and showing that it has been switched to only log "Fatal" errors.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/logging.png "RPCS3 Fatal Logging")

That's the difficult part over with.