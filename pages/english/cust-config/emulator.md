---
title: "Custom Configuration: Emulator"
sidebar: english_sidebar
permalink: custom_config_emu
folder: english
tags: [custom-config, english]
summary: "What to change for Rock Band 3 under the Emulator tab in RPCS3's Custom Configuration."
series: "Custom Configuration"
weight: 8
---

![A screenshot of Rock Band 3's Emulator custom settings, showing "Show trophy popups", "Show RPCN popups", "Show shader compilation hint", "Show PPU compilation hint", "Show mouse and keyboard toggle hint", "Start games in fullscreen mode", and "Use native user interface" highlighted in tan with a solid outline.](https://carlmylo.github.io/rb3-pc/images/cust/emulator.png "Emulator")

You can leave this as is if you want, but I would consider changing the following options:
* ![A tan square with a solid outline.](https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png "Tan Square") **Optional tweaks**: 
	* **"`Show trophy popups`"** - Mimics the way Trophy notifications appear on the PS3.
	* **"`Show RPCN popups`"** - Shows a message on the top left whenever you or your friends connect to RPCN.
	* **"`Show shader compilation hint`"** - This creates a popup whenever RPCS3 is compiling shaders. When you run PS3 games, it has to compile shaders to "translate" the graphics from a PS3 format to a format your PC can work with. **The game will stutter when this happens**. **This happens on ALL computer systems. When it finishes** compiling an effect, **it will usually never happen again**. **The best way to deal with this is** just **to** **play the game** as it will quickly go away. You can also use Rock Band 3 Deluxe's Autoplay modifier to let it go through a few songs in party shuffle and let it compile a decent amount of shaders.
	* **"`Show PPU compilation hint`"** - This creates a popup whenever RPCS3 is compiling units for the PPU. This only comes up when launching the game when using suggested settings.
	* **"`Show mouse and keyboard toggle hint`"** - Shows a message on the top left whenever the keyboard is being used in the native interface, such as the virtual keyboard that comes up when naming things.
	* **"`Start games in Fullscreen mode`"** - Switches to Fullscreen when you start Rock Band 3.
	* **"`Use Native Interface`"** - If you disable this, it will remove the pretty displays RPCS3 adds, including notifications and game startup background. It will instead use old school pop-ups. This can also fix a problem with instrument controllers soft locking the game when the keyboard comes up.

<br/>

{% include custom/series_custom_config_next.html %}

{% include links.html %}