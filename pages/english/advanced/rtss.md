---
title: Fix Frame Pacing with RTSS
sidebar: english_sidebar
permalink: adv_rtss
folder: english
tags: [advanced, english]
summary: "How to improve Frame Pacing in Rock Band 3 with RTSS."
toc: false
---

Rock Band 3 is a game that benefits from having a smooth frame rate as judder can make it distracting to read the note track. RPCS3's frame limiter sometimes isn't up to the task. To fix this, you'll need to Rivatuner Statistics Server (or RTSS).

## Initial Setup:

For this to work correctly, you'll first need to change some things in RPCS3.

First, **right click on Rock Band 3** in RPCS3, then click on "**Change Custom Configuration**".  
![A screenshot of RPCS3's right click menu, showing "Change Custom Configuration" highlighted](https://rb3pc.milohax.org/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

In the GPU tab:
* Set "`Framelimit`" to "`Off`"
* Set "`VSync`" to "`Off`"  

![A screenshot of Rock Band 3's GPU custom settings, highlighting Framelimit and VSync in blue with a dotted outline.](https://rb3pc.milohax.org/images/xtra/rtss/rpcs3disable.png "GPU")

Don't forget to click "`Apply`" and "`Save custom configuration`" after.  
When you're done, close out RPCS3.

Now, go to [[Rivatuner Statistics Server's download page.]](https://www.guru3d.com/download/rtss-rivatuner-statistics-server-download/).  
Click here to go to [[Rivatuner Statistics Server's download page.]](https://www.guru3d.com/download/rtss-rivatuner-statistics-server-download/)  
![A screenshot of RTSS' download website. The cursor is hovering "Download Version 7.3.6 Final"](https://rb3pc.milohax.org/images/xtra/rtss/rtssdl.png "Guru3D RTSS Rivatuner Statistics Server Download 7.3.6 Final")

It should start downloading a `.zip` archive shortly after.  
![A screenshot of RTSS' .zip folder that contains the installer.](https://rb3pc.milohax.org/images/xtra/rtss/rtssdlbrowser.png "[Guru3D.com]-RTSS.zip")

When it finishes downloading, open the installer and install RTSS. 
![A screenshot of RTSS' installer on the last page.](https://rb3pc.milohax.org/images/xtra/rtss/install6.png "[Guru3D.com]-RTSS.zip")

Go the Start menu and search for `RivaTuner Statistics Server` or `RTSS`. Both should give you the app. Open it.  
![A screenshot of the Start Menu, with "RivaTuner Statistics Server" in the search results.](https://rb3pc.milohax.org/images/xtra/rtss/rtssstart.png "Start search")

When RTSS opens, you will be on the `Global` profile by default.  
In this profile:
* Set `Application detection level` to `None`.
* Set `Show On-Screen Display` to `Off`.  

![A screenshot of RivaTuner Statistics Server, showing "Show On-Screen Display", "Application detection level", and "Add" highlighted in blue with a dotted outline.](https://rb3pc.milohax.org/images/xtra/rtss/rtssglobal.png "Rivatuner Statistics Server: Global")

After those two adjustments, click on `Add`.  
A file browser window will open. Find where you have RPCS3 located and select the `rpcs3` application.
![A screenshot of a file browser titled "Open". RPCS3 is selected and a cursor is over it.](https://rb3pc.milohax.org/images/xtra/rtss/rtssaddrpcs3.png "Open")

When you add RPCS3, you'll be on the `rpcs3.exe` profile.
In this profile:
* Set `Application detection level` to `Low`.
* Right click `Framerate limit` and set it to whatever display you're displaying RPCS3 on.
	* Alternatively you can click on the number and set it to a specific framerate or set it to the VRR cap of your display.
![A screenshot of RivaTuner Statistics Server, showing "Application detection level" and "Framerate limit" highlighted in blue with a dotted outline. "Framerate limit" has a popout menu with the cursor over a display.](https://rb3pc.milohax.org/images/xtra/rtss/rtssrpcs3.png "Rivatuner Statistics Server: rpcs3.exe")

## Usage:

After setting up RTSS, you can now just open it up whenever you want to limit your framerate without having judder!  
If you're feeling lazy, you can even have it set to Start with Windows so you never have to do this manually.

For the best results, turn VSync off in Rock Band 3 through Deluxe's Graphics options menu:
* `Menu > Options > Deluxe Settings > Graphics > VSync`  
![A screenshot of Rock Band 3 Deluxe's Graphics menu. VSync is selected and set to off](https://rb3pc.milohax.org/images/xtra/rtss/rb3vsync.png "VSync: Off")

{% include links.html %}