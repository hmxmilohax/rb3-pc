---
title: "Custom Configuration"
sidebar: english_sidebar
permalink: custom_config
folder: english
toc: false
tags: [custom-config, english]
summary: "What to change for Rock Band 3 in RPCS3's Custom Configuration."
---

While a Quick Configuration should work in most cases, some things require additional settings, like microphones and MIDI instruments. This involves creating or editing a Custom Configuration for Rock Band 3.

<ul id="confeditTabs" class="nav nav-tabs">
    <li class="active"><a href="#changecustomconfig" data-toggle="tab">Changing a Custom Configuration</a></li>
    <li><a href="#createcustomconfig" data-toggle="tab">Creating a Custom Configuration</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="changecustomconfig">
<p>If you're editing a Custom Configuration (like the one you installed from Quick Configuration), <strong>right click on Rock Band 3</strong> in RPCS3, then click on “<strong>Change Custom Configuration</strong>”.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfigchange.png" alt="A screenshot of RPCS3's right click menu, showing &quot;Change Custom Configuration&quot; highlighted" title="Create Custom Configuration From Default Settings"></p></div>

<div role="tabpanel" class="tab-pane" id="createcustomconfig">
<p>If you don't have a Custom Configuration yet, <strong>right click on Rock Band 3</strong> in RPCS3, then click on “<strong>Create Custom Configuration From Default Settings</strong>”.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfig.png" alt="A screenshot of RPCS3's right click menu, showing &quot;Create Custom Configuration From Default Settings&quot; highlighted" title="Create Custom Configuration From Default Settings"></p></div>
</div>
<br/>

**Don't forget to click "Apply" then "Save custom configuration" after adjusting settings!**  
Keep in mind that you'll have to restart the game for most of these settings.  
![A screenshot of Rock Band 3's Custom Configuration within RPCS3 with a mouse hovering over "Save custom configuration".](https://carlmylo.github.io/rb3-pc/images/cust/save.png "Settings: [BLUS30463] Rock Band 3")

## Color Guide

This may seem overwhelming because of the sheer number of options, but I have color-coded the settings that require adjustment. Anything not colored **should be left on defaults**.

| COLOR | MEANING |
|---|---|
| ![A green square with a dashed outline.](https://carlmylo.github.io/rb3-pc/images/cust/biggreen.png "Green Square") | **REQUIRED** |
| ![A blue square with a dotted outline.](https://carlmylo.github.io/rb3-pc/images/cust/bigblue.png "Blue Square") | **Performance Tweaks** |
| ![A tan square with a solid outline.](https://carlmylo.github.io/rb3-pc/images/cust/bigtan.png "Tan Square") | **Recommended** |

<br/>

## Custom Configuration

<ul id="configTabs" class="nav nav-tabs">
    <li class="active"><a href="#cpu" data-toggle="tab">CPU</a></li>
    <li><a href="#gpu" data-toggle="tab">GPU</a></li>
    <li><a href="#audio" data-toggle="tab">Audio</a></li>
    <li><a href="#io" data-toggle="tab">I/O</a></li>
    <li><a href="#network" data-toggle="tab">Network</a></li>
    <li><a href="#advanced" data-toggle="tab">Advanced</a></li>
    <li><a href="#emulator" data-toggle="tab">Emulator</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="cpu">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/cpu.png" alt="A screenshot of Rock Band 3's CPU custom settings, showing SPU XFloat Accuracy, SPU Block Size, Preferred SPU Threads, and Thread Scheduler highlighted in blue with a dotted outline." title="CPU"></p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Tan Square"> <strong>Improved performance, depending on machine</strong>:
<ul>
<li><strong>Change “SPU Block Size” to “Mega”</strong> - Ties smaller SPU compiled together, which can help machines with fewer cores/threads. Drastically speeds up game startup time on certain machines.</li>
<li><strong>Change “Preferred SPU Threads” to “1”, “2”, “3”, or “4”</strong> - May help prevent stutter caused by CPU overloads on systems with fewer cores/threads. <strong>Start at 4 and lower it one by one until it improves</strong>.</li>
<li><strong>Change “Thread Scheduler” to “RPCS3 Scheduler”, or “RPCS3 Alternative Scheduler”</strong> - <strong>FOR CPUs WITH 12+ THREADS ONLY!</strong> May help with thread distribution to prevent microstutters.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="gpu">
    <p><img src="https://carlmylo.github.io/rb3-pc/images/cust/gpu.png" alt="A screenshot of Rock Band 3's GPU custom settings, highlighting Write Color Settings highlighted in green with a dotted outline, Framelimit, Anisotropic Filter, ZCull Accuracy, Output Scaling and VSync highlighted in blue with a dotted outline." title="GPU"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="A green square with a dashed outline." title="Green Square"> <strong>REQUIRED</strong>:</p>
<ul>
<li><strong>Enable “Write Color Buffers”</strong> - Characters will have severe graphical bugs without this.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Blue Square"> <strong>Tweak depending on graphics card</strong>:</p>
<ul>
<li><strong>Enable “VSync”</strong> - Reduces screen tearing and may lead to a more stable framerate. Slightly increases input latency. <strong>Do not enable this with the frame limiter</strong>.</li>
<li><strong>Change "Framelimit"</strong>
<ul>
<li>Set it to “Off” to have framerates above 60 <strong>or if you're using VSync.</strong></li>
<li>"Display" will use use your monitor's refresh rate.</li>
<li>Adjusting the frame rate to be higher than 60 exponentially uses more resources, so this is not recommended for low end machines.</li>
<li>Be aware that framerates higher than 60 may cause the vocal pitch detection to behave incorrectly.</li>
<li>It's suggested to set "Framelimit" to "Off" and enable VSync in this GPU tab and to disable VSync within Rock Band 3 Deluxe's menus in <br> <code>Menu &gt; Options &gt; Deluxe Settings &gt; Graphics &gt; VSync</code></li>
</ul>
</li>
<li><strong>Change “ZCULL Accuracy” to “Relaxed”</strong> - Provides a slight performance improvement but may cause graphical anomalies in very rare situations.</li>
<li><strong>Adjust “Anistropic Filter”</strong> to depending on what your GPU can handle. Increase for better texture filtering. Performance impact should be negligible.</li>
<li><strong>Adjust “Resolution Scale”</strong> to preference and to what your computer can handle. Increase for sharper graphics at the cost of higher GPU requirements. This forces the game to run at this resolution. Lowering this below 100% isn't worth it as it won't give much, if any, framerate gains.</li>
<li><strong>Adjust “Output Scaling”</strong> to preference and to what your computer can handle. This affects how the game is “blown up” in size when fitting to your monitor's native resolution. Helpful for those keeping Resolution Scale (mentioned above) at 100% while playing on a monitor larger than 1280x720.
<ul>
<li>“Nearest” is completely unfiltered and gives you a raw unmodified image. This can cause the game to look pixelated.</li>
<li>“Bilinear” uses smoothing to scale the image up. This may cause the game to look blurry.</li>
<li>FidelityFX Super Resolution (FSR) uses complicated math to sharpen and enhance the image when it gets blown up to your monitor's resolution. This can create odd artifacts in some instances.
<ul>
<li>You can use “RCAS Sharpening Strength” below to adjust the strength of its effect.</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="audio">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/audio.png" alt="A screenshot of Rock Band 3's Audio custom settings, highlighting Enable Buffering in green with a dashed outline, Audio Buffer and Audio Out highlighted in blue with a dotted outline, and Microphone Settings, Microphone Type (Standard), Mic1, Mic2, Mic3, and Mic4 highlighted in tan with a solid outline." title="Audio"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Blue Square"> <strong>Tweak depending on audio hardware and CPU</strong>:</p>
<ul>
<li><strong>Adjust “Audio Buffer Duration”</strong> depending on system. Ideally you want this as low as possible.
<ul>
<li>Lower values give you less audio latency but use more CPU.</li>
<li>Higher values give you more audio latency but use less CPU.</li>
<li>Vocalists are affected the most by this, as a higher latency creates a distracting echo. Instrument players can use calibration to compensate regardless of audio buffer setting.</li>
<li>You can change this while the game is running, but it will require re-calibrating in Rock Band 3’s system settings.</li>
</ul>
</li>
<li><strong>Change “Audio Out” to “XAudio2” in extremely rare circumstances</strong> - <strong>Most users should stay on Cubeb</strong>, a few users have experienced better performance with XAudio2. Only do this if you absolutely need to!</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>For Vocalists</strong>:</p>
<ul>
<li><strong>Set Microphone type to Standard or Rocksmith</strong>.</li>
<li><strong>Select an input device in “Mic1”, “Mic2”, and “Mic3”</strong> for vocals. If not playing vocals, Mic1 will be used for voice chat.</li>
<li>Once again, keep in mind that playing with framerates higher than 60 may cause issues with vocal detection.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="io">
<p><strong>This section is for people playing with USB/MIDI Keyboards, Pro Guitars, or MIDI Drums!</strong></p>
<ul>
<li><strong>If you're not playing with a wired Pro Guitar, Pro Drums, or a USB/MIDI keyboard, you can skip this section.</strong></li>
<li><strong>If you're playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar,</strong> visit the <a href="https://carlmylo.github.io/rb3-pc/adv_passthrough" target="_blank"> <strong>[[Passthrough Devices]]</strong></a> section. </li>
</ul>
<p><strong>Make sure your MIDI instrument is connected.</strong> After that, let's go ahead and <strong>focus on RPCS3’s I/O tab.</strong><br>
<strong>YOU MAY HAVE TO MAKE THE WINDOW WIDER TO READ THE OPTIONS!</strong><br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/io.png" alt="A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline, and Pad Handler Mode highlighted in blue with a dotted outline." title="I/O"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Blue Square"> <strong>Performance Tweaks</strong>:</p>
<ul>
<li><p><strong>Change “Pad Handler Mode” to “Multi-threaded”</strong> - May help with thread distribution, leading to more even performance. Your mileage may vary.</p>
</li>
</ul>
</li>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>Recommended</strong>:
<ul>
<li>🎹 <strong>MIDI Keyboard Players: Leave your “Emulated MIDI type” on “Keyboard” and select your keyboard or MIDI interface in the drop-down menu next to it</strong>.</li>
<li>🎸 <strong>MIDI Pro Guitar Players: Change your “Emulated MIDI type” from “Keyboard” to “Guitar (17 Frets)” if you have a Mustang Pro Guitar, or “Guitar (22 Frets)” if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it</strong>.</li>
<li>🥁 <strong>MIDI Pro Drums Players: Change your “Emulated MIDI type” from “Keyboard” to “Drums”, then select your Electronic MIDI Drum Kit or MIDI to USB interface in the drop-down menu next to it</strong>.</li>
<li><p><strong>Enable “Keep Pads Connected”</strong> - This can help fix a problem with instrument controllers soft-locking the game when RPCS3 interfaces, such as the RPCN invites, come up.</p></li>
</ul>
</li>
</ul>
<p>Revisit the <a href="https://carlmylo.github.io/rb3-pc/ctrls" target="_blank">[Controllers page]</a> if you need help.</p>
</div>
<div role="tabpanel" class="tab-pane" id="network">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/network.png" alt="A screenshot of Rock Band 3's Network custom settings, highlighting Network Status (Connected) in green with a dashed outline, IP/Hosts switches (set to rb3ps3live.hmxservices.com=45.33.44.103), PSN Status (RPCN), and Enable UPNP (not checked) highlighted in tan with a solid outline." title="Network"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="A green square with a dashed outline." title="Green Square"> <strong>REQUIRED</strong>:</p>
<ul>
<li><strong>Change the Network Status to “Connected” as highlighted in the picture. If left on “Disconnected,” the game will temporarily freeze when browsing the song library.</strong></li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>For online</strong>:</p>
<ul>
<li>You can tick <strong>“Enable UPNP”</strong> or <strong>forward port 9103 (UDP) in your firewall</strong>.</li>
<li>Add Rock Band Enhanced's Server IP.
<ul>
<li>Set IP/Hosts switches to <code>rb3ps3live.hmxservices.com=45.33.44.103</code>.</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="advanced">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/advanced.png" alt="A screenshot of Rock Band 3's Advanced custom settings, highlighting Driver Wake-Up Delay (1µ) in green with a dashed outline, &quot;Exclusive Fullscreen Mode, VBlank Frequency, and Maximum Number of SPURS Threads highlighted in blue with a dotted outline, and Debug Console Mode highlighted in tan with a solid outline." title="Advanced"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="A green square with a dashed outline." title="Green Square"> <strong>REQUIRED</strong>:</p>
<ul>
<li><strong>Change “Driver Wake-up Delay” to “20µ”</strong> to avoid crashing after a few songs. Increase it to “40µ” if the issue persists. If it keeps happening, keep increasing it by increments of 20.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Tan Square"> <strong>Depending on your computer</strong>:</p>
<ul>
<li><strong>Change “Maximum Number of SPURS Threads”</strong> - May improve performance on older systems with less cores and threads <a href="https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005" target="_blank">[like 4th gen Intel i5 CPUs with 4 cores and 4 threads]</a>.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>Strongly Suggested</strong>:</p>
<ul>
<li><strong>Enable “Debug Console Mode”</strong> - Enabling this and “Large Heap” in Rock Band 3 Deluxe will allow Rock Band 3  to have more memory. This means more songs (up to 16000) and increased stability. Everyone should enable this! <a href="https://carlmylo.github.io/rb3-pc/memory" target="_blank">[Click here for more information.]</a></li>
<li><strong>Change “Exclusive Fullscreen Mode” to “Prefer borderless fullscreen”</strong> to prevent potential crashes and audio desync when changing from Rock Band 3 to another program while in fullscreen.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="emulator">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/emulator.png" alt="A screenshot of Rock Band 3's Emulator custom settings, showing &quot;Show trophy popups&quot;, &quot;Show PPU compilation hint&quot;, &quot;Show Shader Compilation hint&quot;, &quot;Start Games in fullscreen mode&quot;, &quot;Use native user interface.&quot;" title="Emulator"></p>
<p>You can leave this as is if you want, but I would consider changing the following options:</p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>Optional tweaks</strong>:
<ul>
<li><strong>"Show trophy popups"</strong> - Mimics the way Trophy notifications appear on the PS3. I personally disable this as the game has its own pop-ups.</li>
<li><strong>"Show PPU compilation hint"</strong> - This creates a popup whenever RPCS3 is compiling units for the PPU. This only comes up once as the “Recompiler (LLVM)” setting in the CPU tab does this when launching the game.</li>
<li><strong>"Show shader compilation hint"</strong> - This creates a popup whenever RPCS3 is compiling shaders. Whether you leave it on or not is up to you, but I should tell you what this means as it is important. When you run PS3 games, it has to compile shaders to “translate” the graphics from a PS3 format to a format your PC can work with. <strong>The game will</strong> appear to <strong>stutter when this happens</strong>. <strong>This happens on ALL computer systems. When it finishes</strong> compiling an effect, <strong>it will usually never happen again</strong>. <strong>The best way to deal with this is</strong> just <strong>to</strong> <strong>play the game</strong> as it will quickly go away. You can also use Rock Band 3 Deluxe's Autoplay modifier to let it go through a few songs in party shuffle and let it compile a decent amount of shaders.</li>
<li><strong>"Start games in Fullscreen mode"</strong> - Switches to Fullscreen when you start Rock Band 3.</li>
<li><strong>"Use Native Interface"</strong> - Removes the pretty displays RPCS3 adds, including notifications and game startup background. It will instead use old school pop-ups. This can also fix a problem with instrument controllers soft locking the game when the keyboard comes up. The native interface also seems to cause slight frame rate drops.</li>
</ul>
</li>
</ul>
</div>
</div>


{% include links.html %}