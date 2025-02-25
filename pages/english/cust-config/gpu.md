---
title: "Custom Configuration: GPU"
sidebar: english_sidebar
permalink: custom_config_gpu
folder: english
tags: [custom-config, english]
summary: "What to change for Rock Band 3 under the GPU tab in RPCS3's Custom Configuration."
series: "Custom Configuration"
weight: 3
---

![A screenshot of Rock Band 3's GPU custom settings, highlighting "Write Color Buffers" highlighted in green with a dotted outline, "Framelimit", "Anisotropic Filter", "ZCull Accuracy", "Output Scaling", and "VSync" highlighted in blue with a dotted outline.](https://rb3pc.milohax.org/images/cust/gpu.png "GPU")

* ![A green square with a dashed outline.](https://rb3pc.milohax.org/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Enable "Write Color Buffers"** - Characters will have severe graphical bugs without this.

* ![A blue square with a dotted outline.](https://rb3pc.milohax.org/images/cust/smallblue.png "Blue Square") **Adjust depending on graphics card**: 
	* **Enable "`VSync`"** - Reduces screen tearing and may lead to a more stable framerate. Slightly increases input latency. **Do not enable this with the frame limiter**.
	* **Change "`Framelimit`"**
		* Leave it on "`Auto`" to let RPCS3 set a frame rate.
		* Set it to "`Off`" **if you're using "`VSync`" or an external frame limiter**.
		* "`120`" is recommended if you're using a 144Hz (or higher) display.
		* **DO NOT** set it below "`60`"!
		* Setting the frame rate to be higher than "`60`" exponentially uses more resources, so this is not recommended for low end machines.
		* It's suggested to disable VSync within Rock Band 3 Deluxe itself in `Menu > Options > Deluxe Settings > Graphics > VSync`
	* **Change "`ZCULL Accuracy`" to "`Relaxed`"** - Provides a slight performance improvement at the cost of some accessories looking weird at distances.
	* **Adjust "`Anisotropic Filter`"** for better texture filtering. Just about every GPU should be able to handle "`x16`".
	* **Adjust "`Resolution Scale`"** to preference and to what your computer can handle. Increase for sharper graphics at the cost of higher GPU requirements. This forces the game to run at this resolution. Lowering this below 100% isn't worth it as it won't give much, if any, frame rate gains.
	* **Adjust "`Output Scaling`"** to preference and to what your computer can handle. This affects how the game is "blown up" in size when fitting to your monitor's native resolution. Helpful for those keeping "`Resolution Scale`" (mentioned above) at 100% while playing on a monitor larger than 1280x720.
		* "`Nearest`" is completely unfiltered and gives you a raw unmodified image. This can cause the game to look pixelated.
		* "`Bilinear`" uses smoothing to scale the image up. This may cause the game to look blurry.
		* "`FidelityFX Super Resolution`" (FSR) uses complicated math to sharpen and enhance the image when it gets blown up to your monitor's resolution. This can create odd artifacts in some instances.
			* You can use "`RCAS Sharpening Strength`" below to adjust the strength of its effect.

<br/>

{% include custom/series_custom_config_next.html %}

{% include links.html %}