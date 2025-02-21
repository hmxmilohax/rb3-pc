---
title: "Custom Configuration: CPU"
sidebar: english_sidebar
permalink: custom_config_cpu
folder: english
tags: [custom-config, english]
summary: "What to change for Rock Band 3 under the CPU tab in RPCS3's Custom Configuration."
series: "Custom Configuration"
weight: 2
---

![A screenshot of Rock Band 3's CPU custom settings, showing SPU Block Size, Preferred SPU Threads, and Thread Scheduler highlighted in blue with a dotted outline.](https://carlmylo.github.io/rb3-pc/images/cust/cpu.png "CPU")

* ![A blue square with a dotted outline.](https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png "Tan Square") **Improved performance, depending on machine**: 
	* **Change "`SPU Block Size`" to "`Mega`"** - Ties smaller SPU compiled together, which can help machines with fewer cores/threads. Drastically speeds up game startup time on certain machines.
	* **Change "`Preferred SPU Threads`" to "`1`", "`2`", "`3`", or "`4`"** - May help prevent stutter caused by CPU overloads on systems with fewer cores/threads. **Start at "`4`" and lower it one by one until it improves**.
	* **Change "`Thread Scheduler`" to "`RPCS3 Scheduler`", or "`RPCS3 Alternative Scheduler`"** - **FOR CPUs WITH 12+ THREADS ONLY!** May help with thread distribution to prevent microstutters.

<br/>

{% include custom/series_custom_config_next.html %}

{% include links.html %}