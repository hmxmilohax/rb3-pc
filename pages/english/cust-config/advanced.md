---
title: "Custom Configuration: Advanced"
sidebar: english_sidebar
permalink: custom_config_adv
folder: english
tags: [custom-config, english]
summary: "What to change for Rock Band 3 under the Advanced tab in RPCS3's Custom Configuration."
series: "Custom Configuration"
weight: 7
---

![A screenshot of Rock Band 3's Advanced custom settings, highlighting "Driver Wake-Up Delay" (20µ) in green with a dashed outline, "Exclusive Fullscreen Mode, and "Maximum Number of SPURS Threads" highlighted in blue with a dotted outline, and "Debug Console Mode" highlighted in tan with a solid outline.](https://carlmylo.github.io/rb3-pc/images/cust/advanced.png "Advanced")

* ![A green square with a dashed outline.](https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Change "`Driver Wake-up Delay`" to "20µ"** to avoid crashing after a few songs. Increase it to "40µ" if the issue persists. If it keeps happening, keep increasing it by increments of 20.

* ![A blue square with a dotted outline.](https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png "Tan Square") **Depending on your computer**: 
	* **Change "`Maximum Number of SPURS Threads`"** - May improve performance on older systems with less cores and threads [[like 4th gen Intel i5 CPUs with 4 cores and 4 threads]](https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005).

* ![A tan square with a solid outline.](https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png "Tan Square") **Strongly Suggested**: 
	* **Enable "`Debug Console Mode`"** - Enabling this and "Large Heap" in Rock Band 3 Deluxe will allow Rock Band 3  to have more memory. This means more songs (up to 16000) and increased stability. Everyone should enable this! [[Click here for more information.]](https://carlmylo.github.io/rb3-pc/memory){:target="_blank"}
	* **Change "`Exclusive Fullscreen Mode`" to "`Prefer borderless fullscreen`"** to prevent potential crashes and audio desync when changing from Rock Band 3 to another program while in fullscreen.

<br/>

{% include custom/series_custom_config_next.html %}

{% include links.html %}