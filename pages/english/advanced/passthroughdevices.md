---
title: Passthrough Devices
sidebar: english_sidebar
permalink: adv_passthrough
folder: english
tags: [advanced, english]
summary: "How to add set up passthrough devices for RPCS3."
toc: false
---

If you're playing with a RB3 Mustang Guitar for PlayStation 3 or a RB3 Keyboard PlayStation 3 with their respective dongles, or if you're using a MIDI PRO Adapter you can connect and play them like on console after a simple setup.

To begin with, make sure you have the correct dongle or the MIDI PRO Adapter.

| **Mustang Guitar<br>Dongle** | **Wireless Keyboard<br>Dongle** | **MIDI PRO Adapter<br>(Each Mode)** |
|:------------------:|:---------------------:|:---------------------:|
| ![Dongle for the RB3 Mustang Guitar](https://rb3pc.milohax.org/images/btns/ctrls/ps3/recprotar.png "Dongle for the RB3 Mustang Guitar") | ![Dongle for the RB3 Wireless Keyboard](https://rb3pc.milohax.org/images/btns/ctrls/ps3/reckeys.png "Dongle for the RB3 Wireless Keyboard") | ![MIDI PRO Adapter](https://rb3pc.milohax.org/images/btns/ctrls/ps3/recmpa.png "MIDI PRO Adapter")

**Please note that you will need to repeat this process three times for each mode on the MIDI PRO Adapter!**

After making sure you have the correct dongle or MIDI PRO Adapter, **close out RPCS3 and plug in the instrument's dongle or MIDI PRO Adapter** to your computer.

Now, [**\[go to Zadig's website\]**](https://zadig.akeo.ie/){:target="_blank"} and **download the latest version, then open it** up.

Click on **Options** then **List All Devices**.  
![A screenshot of Zadig showing "List All Devices" under "Options" highlighted.](https://rb3pc.milohax.org/images/pass/zadiglistall.png "Zadig: Options: List All Devices")

You should now see devices listed. **Switch it to your Rock Band 3 Pro Instrument**. In this example, we're using the Mustang Pro Guitar, which shows up as "Harmonix RB3 Mustang Guitar for PlayStation® 3".  
![A screenshot of Zadig showing "Harmonix RB3 Mustang Guitar for PlayStation® 3" highlighted in the devices listed.](https://rb3pc.milohax.org/images/pass/zadigsel.png "Zadig: Harmonix RB3 Mustang Guitar for PlayStation® 3")

**After selecting the right device, you should see the option to replace the driver. _MAKE SURE YOU ARE REPLACING THE DRIVER ONLY FOR THE PRO GUITAR/KEYBOARD/MIDI PRO ADAPTER!!_** Click Replace Driver.  
![A screenshot of Zadig with "Replace Driver" highlighted.](https://rb3pc.milohax.org/images/pass/zadigreplace.png "Zadig: Replace Driver")

A warning will appear. **Again, make sure you have selected your RB3 Pro instrument's receiver or adapter.** After you have made sure, **click** "**Yes**."  
![A screenshot of Zadig warning the user that they're about to modify a system driver, with "Yes" highlighted](https://rb3pc.milohax.org/images/pass/zadigreplace.png "Zadig: Warning - System Driver")

It will then install the driver. As the program says, it may take a few minutes.  
![A screenshot of Zadig in the middle of a driver install.](https://rb3pc.milohax.org/images/pass/zadigprogress.png "Zadig: Installing Driver...")


If everything goes well, you will get this message:  
![A screenshot of Zadig telling the user that the driver was installed successfully with "Close" highlighted.](https://rb3pc.milohax.org/images/pass/zadigdone.png "Zadig: Success")

**Close Zadig** and, **with the dongle or MIDI PRO Adapter** still **connected**, **open up RPCS3** and **open Rock Band 3**.

Turn your controller on and you should see it automatically assign a player number.  
![A picture of a Mustang Pro Guitar with the second player LED lit up.](https://rb3pc.milohax.org/images/pass/protaron.png "Fender Mustang Pro Guitar: Player 2")

Likewise, in Rock Band 3, you will see the instrument ready to join.  
![A screenshot of Rock Band 3 with a Pro Guitar ready to join.](https://rb3pc.milohax.org/images/pass/rb3player.png "Rock Band 3: Pro Guitar ready to join")

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>RPCN Menus (for sending or accepting online invites) will cause a softlock. You will need an alternative input method to navigate these menus, such as a typing keyboard or a gamepad.</b> {{include.content}}</div>

{% include callout.html content="<sup>a</sup> Connecting **three or more PlayStation 3 Rock Band instruments** (drums, keyboards, guitars) may cause issues with instrument detection. This **only** happens with PlayStation 3 Rock Band instruments and only if they're all plugged in at the same time." type="warning" %} 


{% include links.html %}