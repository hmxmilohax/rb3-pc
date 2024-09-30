---
title: Discord Rich Presence
sidebar: english_sidebar
permalink: adv_discordrp
folder: english
tags: [advanced, english]
summary: "How to add set up Rich Presence for Discord with Rock Band 3 Deluxe."
toc: false
---

Want to show off to others what song you're in or just want to share the love of Rock Band 3 Deluxe?  
You can do this with the Rich Presence script made for Rock Band 3 Deluxe.  
![A screenshot of a blank Discord profile showing that they're playing Rock Band 3 Deluxe and in Bodhisattva by Steely Dan on drums.](https://rb3pc.milohax.org/images/xtra/rpc/discordrp.png "Discord Rich Presence")

## Initial Setup

First, we're going to disable RPCS3's presence because it will conflict and look weird.

Click the `Config` button.  
![A screenshot of RPCS3 with the cursor hovering over "Config"](https://rb3pc.milohax.org/images/xtra/rpc/rpcs3config.png "RPCS3")

Under the `GUI` tab, disable `Use Discord Rich Presence` .  
![A screenshot of RPCS3 with the "Use Discord Rich Presence" checkbox disabled.](https://rb3pc.milohax.org/images/xtra/rpc/rpcs3drpoff.png "RPCS3: Settings")

Now, you'll need to download the latest version of [[Python 3]](https://www.python.org/downloads/){:target="_blank"}.

[[Click here to go to the download page for Python 3]](https://www.python.org/downloads/){:target="_blank"}.

![A screenshot of Python download website. A cursor hovers over "Download Python 3.12.6.](https://rb3pc.milohax.org/images/xtra/rpc/pydl.png "Python 3.12.6")

Once it finishes downloading, open the installer.  
In the installer:
1. Click `Add python.exe to PATH`
2. Click `Install now`  
![A screenshot of Python's installer. "Add python.exe to PATH" and "Install now" are highlighted in tan with a dotted black outline.](https://rb3pc.milohax.org/images/xtra/rpc/pyinstall.png "Python 3.12.6")

After that finishes downloading, download [[`dx_config_default.ini`]](https://raw.github.com/hmxmilohax/rock-band-3-deluxe/develop/scripts/dx_config_default.ini) and [[`dx_discordrp.py`]](https://raw.github.com/hmxmilohax/rock-band-3-deluxe/develop/scripts/dx_discordrp.py).

* [[Click here to download `dx_config_default.ini`]](https://raw.github.com/hmxmilohax/rock-band-3-deluxe/develop/scripts/dx_config_default.ini)

* [[Click here to download `dx_discordrp.py`]](https://raw.github.com/hmxmilohax/rock-band-3-deluxe/develop/scripts/dx_discordrp.py)

![A screenshot of "dx_config_default.ini" and "dx_discordrp.py" in a browser's downloads.](https://rb3pc.milohax.org/images/xtra/rpc/rpcdl.png "Python 3.12.6")

Put them in a folder of your preference. Since you'll need to launch this every time you want to do this, it should in an easy to reach spot.

Once in the folder, make a copy of `dx_config_default` and rename it `dx_config`.  
![A GIF of a copy of "dx_config_default" being created then being renamed to "dx_config".](https://rb3pc.milohax.org/images/xtra/rpc/inicopy.gif "Creating a copy")

Open the `dx_config` file you just renamed.

Remove the `#` from the line with `rpcs3_path`  
Put the folder where `/dev_hdd0/` is within quotes. This is usually the same folder as your RPCS3 installation.  
If you followed the suggestion to put RPCS3 in `C:\Games`, you simply have to remove the `#` and nothing else.  
![A screenshot of "dx_config_default.ini" and "dx_discordrp.py" in a browser's downloads.](https://rb3pc.milohax.org/images/xtra/rpc/iniedit.png "dx_config.ini")

Save your changes and close the file out.

## Usage

In the address bar at the top of your file browser window, type in `cmd` then press the Enter key.
![A screenshot of a file browser window with "cmd" typed into the address bar.](https://rb3pc.milohax.org/images/xtra/rpc/cmdopen.png "Windows Explorer")

Once the command line window opens up, type in `py dx_discord.py` and press the Enter key.

If you did everything right, it should show that it has connected to Discord RPC successfully and that it's updating presence.  
![A screenshot of a Windows command line, with it running the Discord Rich Presence script.](https://rb3pc.milohax.org/images/xtra/rpc/iniedit.png "cmd.exe")

That's it! Remember to close it out after you're done and to repeat this when you want to open this up again.

{% include links.html %}



