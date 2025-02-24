---
title: "Custom Configuration"
sidebar: english_sidebar
permalink: custom_config
folder: english
toc: false
tags: [custom-config, english]
summary: "What to change for Rock Band 3 in RPCS3's Custom Configuration."
---

This page is for advanced users that want to tweak RPCS3's Rock Band 3 Custom Configuration more than the average user. Some of this stuff can get very technical!

<ul id="confeditTabs" class="nav nav-tabs">
    <li class="active"><a href="#changecustomconfig" data-toggle="tab">Changing a Custom Configuration</a></li>
    <li><a href="#createcustomconfig" data-toggle="tab">Creating a Custom Configuration</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="changecustomconfig">
<p>If you're editing a Custom Configuration (like the one you installed from Quick Configuration), <strong>right click on Rock Band 3</strong> in RPCS3, then click on “<strong><code>Change Custom Configuration</code></strong>”.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfigchange.png" alt="A screenshot of RPCS3's right click menu, showing &quot;Change Custom Configuration&quot; highlighted" title="Create Custom Configuration From Default Settings"></p></div>

<div role="tabpanel" class="tab-pane" id="createcustomconfig">
<p>If you don't have a Custom Configuration yet, <strong>right click on Rock Band 3</strong> in RPCS3, then click on “<strong><code>Create Custom Configuration From Default Settings</code></strong>”.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfig.png" alt="A screenshot of RPCS3's right click menu, showing &quot;Create Custom Configuration From Default Settings&quot; highlighted" title="Create Custom Configuration From Default Settings"></p></div>
</div>
<br/>

**Don't forget to click "`Apply`" then "`Save custom configuration`" after adjusting settings!**  
Keep in mind that you'll have to restart the game for most of these settings.  
![A screenshot of Rock Band 3's Custom Configuration within RPCS3 with a mouse hovering over "Save custom configuration".](https://carlmylo.github.io/rb3-pc/images/cust/save.png "Settings: [BLUS30463] Rock Band 3")

## Color Guide

To make things easier, all configuration tweaks have been color coded.  
**Anything not colored should be left on defaults**.

| COLOR | MEANING |
|-------|---------|
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
<!-- CPU Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/cpu.png" alt="A screenshot of Rock Band 3's CPU custom settings, showing SPU Block Size, Preferred SPU Threads, and Thread Scheduler highlighted in blue with a dotted outline." title="CPU"></p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Tan Square"> <strong>Improved performance, depending on machine</strong>:
<ul>
<li><strong>Change “<code>SPU Block Size</code>” to “<code>Mega</code>”</strong> - Ties smaller SPU compiled together, which can help machines with fewer cores/threads. Drastically speeds up game startup time on certain machines.</li>
<li><strong>Change “<code>Preferred SPU Threads</code>” to “<code>1</code>”, “<code>2</code>”, “<code>3</code>”, or “<code>4</code>”</strong> - May help prevent stutter caused by CPU overloads on systems with fewer cores/threads. <strong>Start at “<code>4</code>” and lower it one by one until it improves</strong>.</li>
<li><strong>Change “<code>Thread Scheduler</code>” to “<code>RPCS3 Scheduler</code>”, or “<code>RPCS3 Alternative Scheduler</code>”</strong> - <strong>FOR CPUs WITH 12+ THREADS ONLY!</strong> May help with thread distribution to prevent microstutters.</li>
</ul>
</li>
</ul>
<!-- CPU End -->
</div>
<div role="tabpanel" class="tab-pane" id="gpu">
<!-- GPU Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/gpu.png" alt="A screenshot of Rock Band 3's GPU custom settings, highlighting &quot;Write Color Buffers&quot; highlighted in green with a dotted outline, &quot;Framelimit&quot;, &quot;Anisotropic Filter&quot;, &quot;ZCull Accuracy&quot;, &quot;Output Scaling&quot;, and &quot;VSync&quot; highlighted in blue with a dotted outline." title="GPU"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="A green square with a dashed outline." title="Green Square"> <strong>REQUIRED</strong>:</p>
<ul>
<li><strong>Enable “Write Color Buffers”</strong> - Characters will have severe graphical bugs without this.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Blue Square"> <strong>Adjust depending on graphics card</strong>:</p>
<ul>
<li><strong>Enable “<code>VSync</code>”</strong> - Reduces screen tearing and may lead to a more stable framerate. Slightly increases input latency. <strong>Do not enable this with the frame limiter</strong>.</li>
<li><strong>Change "<code>Framelimit</code>"</strong>
<ul>
<li>Leave it on “<code>Auto</code>” to let RPCS3 set a frame rate.</li>
<li>Set it to “<code>Off</code>” <strong>if you’re using “<code>VSync</code>” or an external frame limiter</strong>.</li>
<li>“<code>120</code>” is recommended if you’re using a 144Hz (or higher) display.</li>
<li><strong>DO NOT</strong> set it below “<code>60</code>”!</li>
<li>Setting the frame rate to be higher than “<code>60</code>” exponentially uses more resources, so this is not recommended for low end machines.</li>
<li>It’s suggested to disable VSync within Rock Band 3 Deluxe itself in <code>Menu &gt; Options &gt; Deluxe Settings &gt; Graphics &gt; VSync</code></li>
</ul>
</li>
<li><strong>Change “<code>ZCULL Accuracy</code>” to “<code>Relaxed</code>”</strong> - Provides a slight performance improvement at the cost of some accessories looking weird at distances.</li>
<li><strong>Adjust “<code>Anisotropic Filter</code>”</strong> for better texture filtering. Just about every GPU should be able to handle “<code>x16</code>”.</li>
<li><strong>Adjust “<code>Resolution Scale</code>”</strong> to preference and to what your computer can handle. Increase for sharper graphics at the cost of higher GPU requirements. This forces the game to run at this resolution. Lowering this below 100% isn’t worth it as it won’t give much, if any, frame rate gains.</li>
<li><strong>Adjust “<code>Output Scaling</code>”</strong> to preference and to what your computer can handle. This affects how the game is “blown up” in size when fitting to your monitor’s native resolution. Helpful for those keeping “<code>Resolution Scale</code>” (mentioned above) at 100% while playing on a monitor larger than 1280x720.
<ul>
<li>“<code>Nearest</code>” is completely unfiltered and gives you a raw unmodified image. This can cause the game to look pixelated.</li>
<li>“<code>Bilinear</code>” uses smoothing to scale the image up. This may cause the game to look blurry.</li>
<li>“<code>FidelityFX Super Resolution</code>” (FSR) uses complicated math to sharpen and enhance the image when it gets blown up to your monitor’s resolution. This can create odd artifacts in some instances.
<ul>
<li>You can use “<code>RCAS Sharpening Strength</code>” below to adjust the strength of its effect.</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
<!-- GPU End -->
</div>
<div role="tabpanel" class="tab-pane" id="audio">
<!-- Audio Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/audio.png" alt="A screenshot of Rock Band 3's Audio custom settings, highlighting &quot;Audio Buffer Duration&quot; and &quot;Audio Out&quot; highlighted in blue with a dotted outline, and &quot;Microphone Settings&quot;, &quot;Microphone Type&quot; (&quot;Standard&quot;), &quot;Mic1&quot;, &quot;Mic2&quot;, &quot;Mic3&quot;, and &quot;Mic4&quot; in tan with a solid outline." title="Audio"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Blue Square"> <strong>Tweak depending on audio hardware and CPU</strong>:</p>
<ul>
<li><strong>Adjust “<code>Audio Buffer Duration</code>”</strong> depending on system.
<ul>
<li>Set this as low as you can before you hear crackling. <code>32 ms</code> is a decent starting point.</li>
<li>Lower values give you less audio latency but use more CPU.</li>
<li>Higher values give you more audio latency but use less CPU.</li>
<li>Vocalists are affected the most by this, as a higher latency creates a distracting echo. Instrument players can use calibration to compensate regardless of audio buffer setting.</li>
<li>You can change this while the game is running, but it will require re-calibrating in Rock Band 3’s system settings.</li>
</ul>
</li>
<li><strong>Change “<code>Audio Out</code>” to “<code>XAudio2</code>”</strong> - While <strong>most users should stay on “<code>Cubeb</code>”</strong>, a couple of people have experienced better performance with XAudio2. Your milage may vary.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>For Vocalists</strong>:</p>
<ul>
<li><strong>Set “<code>Microphone Type</code>” to “<code>Standard</code>” or “<code>Rocksmith</code>”</strong>.</li>
<li><strong>Select an input device in “<code>Mic1</code>”, “<code>Mic2</code>”, and “<code>Mic3</code>”</strong> for vocals. If not playing vocals, “<code>Mic1</code>” will be used for voice chat.</li>
</ul>
</li>
</ul>
<!-- Audio End -->
</div>
<div role="tabpanel" class="tab-pane" id="io">
<!-- IO Start -->
<p><strong>Make sure your MIDI instrument is connected.</strong><br>
<strong>YOU MAY HAVE TO MAKE THE WINDOW WIDER TO READ THE OPTIONS!</strong></p>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/io.png" alt="A screenshot of Rock Band 3's I/O custom settings, showing &quot;Emulated MIDI Devices&quot;, &quot;device type&quot;, and &quot;device selection&quot; highlighted in tan with a solid outline, and &quot;Pad Handler Mode&quot; and &quot;Keep Pads Connected&quot; highlighted in blue with a dotted outline." title="I/O"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Tan Square"> <strong>Performance Tweaks</strong>:</p>
<ul>
<li><strong>Change “<code>Pad Handler Mode</code>” to “<code>Multi-threaded</code>”</strong> - May help with thread distribution, which improves performance.</li>
<li><strong>Enable “<code>Keep Pads Connected</code>”</strong> - This can help fix a problem with certain instrument controllers softlocking the game when RPCS3 interfaces, such as the RPCN invites, come up.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>Recommended</strong>:</p>
<ul>
<li>🎹 <strong><a href="https://carlmylo.github.io/rb3-pc/ctrls_keys_midi" target="_blank">[MIDI Keyboard Players]</a>: Leave your “<code>Emulated MIDI type</code>” on “<code>Keyboard</code>” and select your keyboard or MIDI interface in the drop-down menu next to it</strong>.</li>
<li>🎸 <strong><a href="https://carlmylo.github.io/rb3-pc/ctrls_protar_midi" target="_blank">[MIDI Pro Guitar Players]</a>: Change your “<code>Emulated MIDI type</code>” from “<code>Keyboard</code>” to “<code>Guitar (17 Frets)</code>” if you have a Mustang Pro Guitar, or “<code>Guitar (22 Frets)</code>” if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it</strong>.</li>
<li>🥁 <strong><a href="https://carlmylo.github.io/rb3-pc/ctrls_drums_midi" target="_blank">[MIDI Pro Drums Players]</a>: Change your “<code>Emulated MIDI type</code>” from “<code>Keyboard</code>” to “<code>Drums</code>”, then select your MIDI Drum Kit or MIDI to USB interface in the drop-down menu next to it</strong>.</li>
<li>Revisit the <a href="https://carlmylo.github.io/rb3-pc/ctrls" target="_blank">[Controllers page]</a> if you need help.</li>
</ul>
</li>
</ul>
<!-- IO End -->
</div>
<div role="tabpanel" class="tab-pane" id="network">
<!-- Network Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/network.png" alt="A screenshot of Rock Band 3's Network custom settings, highlighting &quot;Network Status (Connected)&quot; in green with a dashed outline, &quot;IP/Hosts switches&quot; (set to rb3ps3live.hmxservices.com=45.33.44.103), &quot;PSN Status&quot; (RPCN), and Enable UPNP (not checked) highlighted in tan with a solid outline." title="Network"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="A green square with a dashed outline." title="Green Square"> <strong>REQUIRED</strong>:</p>
<ul>
<li><strong>Change the “<code>Network Status</code>” to “<code>Connected</code>” as highlighted in the picture. If left on “<code>Disconnected</code>,” the game will temporarily freeze when browsing the song library.</strong></li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>For online multiplayer</strong>:</p>
<ul>
<li>You can tick <strong>“<code>Enable UPNP</code>”</strong> or <strong>forward port 9103 (UDP) in your firewall</strong>.</li>
<li>To play Rock Band 3 online, add Rock Band Enhanced’s Server IP.
<ul>
<li>Set “<code>IP/Hosts switches</code>” to <code>rb3ps3live.hmxservices.com=45.33.44.103</code></li>
</ul>
</li>
</ul>
</li>
</ul>
<!-- Network End -->
</div>
<div role="tabpanel" class="tab-pane" id="advanced">
<!-- Advanced Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/advanced.png" alt="A screenshot of Rock Band 3's Advanced custom settings, highlighting &quot;Driver Wake-Up Delay&quot; (20µ) in green with a dashed outline, &quot;Exclusive Fullscreen Mode, and &quot;Maximum Number of SPURS Threads&quot; highlighted in blue with a dotted outline, and &quot;Debug Console Mode&quot; highlighted in tan with a solid outline." title="Advanced"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="A green square with a dashed outline." title="Green Square"> <strong>REQUIRED</strong>:</p>
<ul>
<li><strong>Change “<code>Driver Wake-up Delay</code>” to “20µ”</strong> to avoid crashing after a few songs. Increase it to “40µ” if the issue persists. If it keeps happening, keep increasing it by increments of 20.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="A blue square with a dotted outline." title="Tan Square"> <strong>Depending on your computer</strong>:</p>
<ul>
<li><strong>Change “<code>Maximum Number of SPURS Threads</code>”</strong> - May improve performance on older systems with less cores and threads <a href="https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005" target="_blank">[like 4th gen Intel i5 CPUs with 4 cores and 4 threads]</a>.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>Strongly Suggested</strong>:</p>
<ul>
<li><strong>Enable “<code>Debug Console Mode</code>”</strong> - Enabling this and “Large Heap” in Rock Band 3 Deluxe will allow Rock Band 3  to have more memory. This means more songs (up to 16000) and increased stability. Everyone should enable this! <a href="https://carlmylo.github.io/rb3-pc/memory" target="_blank">[Click here for more information.]</a></li>
<li><strong>Change “<code>Exclusive Fullscreen Mode</code>” to “<code>Prefer borderless fullscreen</code>”</strong> to prevent potential crashes and audio desync when changing from Rock Band 3 to another program while in fullscreen.</li>
</ul>
</li>
</ul>
<!-- Advanced End -->
</div>
<div role="tabpanel" class="tab-pane" id="emulator">
<!-- Emulator Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/emulator.png" alt="A screenshot of Rock Band 3's Emulator custom settings, showing &quot;Show trophy popups&quot;, &quot;Show RPCN popups&quot;, &quot;Show shader compilation hint&quot;, &quot;Show PPU compilation hint&quot;, &quot;Show mouse and keyboard toggle hint&quot;, &quot;Start games in fullscreen mode&quot;, and &quot;Use native user interface&quot; highlighted in tan with a solid outline." title="Emulator"></p>
<p>You can leave this as is if you want, but I would consider changing the following options:</p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="A tan square with a solid outline." title="Tan Square"> <strong>Optional tweaks</strong>:
<ul>
<li><strong>"<code>Show trophy popups</code>"</strong> - Mimics the way Trophy notifications appear on the PS3.</li>
<li><strong>"<code>Show RPCN popups</code>"</strong> - Shows a message on the top left whenever you or your friends connect to RPCN.</li>
<li><strong>"<code>Show shader compilation hint</code>"</strong> - This creates a popup whenever RPCS3 is compiling shaders. When you run PS3 games, it has to compile shaders to “translate” the graphics from a PS3 format to a format your PC can work with. <strong>The game will stutter when this happens</strong>. <strong>This happens on ALL computer systems. When it finishes</strong> compiling an effect, <strong>it will usually never happen again</strong>. <strong>The best way to deal with this is</strong> just <strong>to</strong> <strong>play the game</strong> as it will quickly go away. You can also use Rock Band 3 Deluxe’s Autoplay modifier to let it go through a few songs in party shuffle and let it compile a decent amount of shaders.</li>
<li><strong>"<code>Show PPU compilation hint</code>"</strong> - This creates a popup whenever RPCS3 is compiling units for the PPU. This only comes up when launching the game when using suggested settings.</li>
<li><strong>"<code>Show mouse and keyboard toggle hint</code>"</strong> - Shows a message on the top left whenever the keyboard is being used in the native interface, such as the virtual keyboard that comes up when naming things.</li>
<li><strong>"<code>Start games in Fullscreen mode</code>"</strong> - Switches to Fullscreen when you start Rock Band 3.</li>
<li><strong>"<code>Use Native Interface</code>"</strong> - If you disable this, it will remove the pretty displays RPCS3 adds, including notifications and game startup background. It will instead use old school pop-ups. This can also fix a problem with instrument controllers soft locking the game when the keyboard comes up.</li>
</ul>
</li>
</ul>
<!-- Emulator End -->
</div>
</div>


{% include links.html %}