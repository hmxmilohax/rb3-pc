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
![A screenshot of a Discord profile showing that they're playing Rock Band 3 Deluxe.](https://rb3pc.milohax.org/images/xtra/rpc/discordrp.png "Discord Rich Presence")

## Initial Setup:

First, we're going to disable RPCS3's presence because it will conflict and look weird.

Open up RPCS3 then click on the `Config` button at the top.  
![A screenshot of RPCS3 with the cursor hovering over "Config"](https://rb3pc.milohax.org/images/xtra/rpc/rpcs3config.png "RPCS3")

Under the `GUI` tab, disable `Use Discord Rich Presence`.  
![A screenshot of RPCS3 with the "Use Discord Rich Presence" checkbox disabled.](https://rb3pc.milohax.org/images/xtra/rpc/rpcs3drpoff.png "RPCS3: Settings")

Now, you'll need to download the latest version of [[Python 3]](https://www.python.org/downloads/){:target="_blank"}.

[[Click here to go to the download page for Python 3]](https://www.python.org/downloads/){:target="_blank"}.

![A screenshot of Python download website. A cursor hovers over "Download Python 3.12.6.](https://rb3pc.milohax.org/images/xtra/rpc/pydl.png "Python 3.12.6")

Once it finishes downloading, open the installer.  
In the installer:  
1. Activate `Add python.exe to PATH`
2. Click `Install now`  
![A screenshot of Python's installer. "Add python.exe to PATH" and "Install now" are highlighted in tan with a dotted black outline.](https://rb3pc.milohax.org/images/xtra/rpc/pyinstall.png "Python 3.12.6")

After that finishes installing, you'll need to download the `dx_discordrp.py` script.

[[Right click here and then "Save link as" to download `dx_discordrp.py`]](https://raw.github.com/hmxmilohax/rock-band-3-deluxe/develop/scripts/dx_discordrp.py)

![A screenshot of a user right clicking on "dx_discordrp.py" then on hovering their cursor over "Save link as".](https://rb3pc.milohax.org/images/xtra/rpc/drpdl.png "Save link as")

![A screenshot of "dx_discordrp.py" in a browser's downloads.](https://rb3pc.milohax.org/images/xtra/rpc/rpcdl.png "Python 3.12.6")

Put it in a folder of your preference. Since you'll need to launch this every time you want to do this, it should in an easy to reach spot.

Go into the folder where you dropped the file and, in the address bar at the top of your file browser window, type in `cmd` then press the Enter key.  
![A screenshot of a file browser window with "cmd" typed into the address bar.](https://rb3pc.milohax.org/images/xtra/rpc/cmdopen.png "Windows Explorer")

Once the command line window opens up, type in:  
`pip install requests pypresence pylast`  
![A screenshot of a Windows command line, with it runing the "pip install requests pypresence pylast" command.](https://rb3pc.milohax.org/images/xtra/rpc/cmdpip.png "cmd.exe")

After it has successfully installed the dependencies, type in:  
`py dx_discordrp.py`  
into the command line and press the Enter key.  

It will ask you to setup a path or Xbox console IP.  
Type in `1` and press Enter (unless you want to set up a modded Xbox 360 along with this script).  
![A screenshot of a Windows command line, with it runing the "py dx_discordrp.py" script. It asks the user to select a platform.](https://rb3pc.milohax.org/images/xtra/rpc/cmddrp.png "cmd.exe")

After that, you will be asked to enter the path to your RPCS3 installation.  
Drag and drop the RPCS3 folder into the command window then press the Enter key.  
**If there are quotes around the path, remove them!**  

It will ask you once again if you want to set up an Xbox console IP.  
Press `2` then the Enter key if you're not interested.

It will start updating your presence and will continue to do so until you close it out.  
![A GIF of a Windows command line, with it runing the "py dx_discordrp.py" script. It asks the user to input the RPCS3 path.](https://rb3pc.milohax.org/images/xtra/rpc/cmdinit.gif "cmd.exe")

## Future Usage:

After the initial setup, you won't have to set up anything when you open the file again.

All you have to do is double click the `dx_discordrp.py` file.  
![A screenshot of a file browser window with "cmd" typed into the address bar.](https://rb3pc.milohax.org/images/xtra/rpc/pyopen.png "Windows Explorer")

If you did everything right, it should show that it has connected to Discord RPC successfully and that it's updating presence.  
![A screenshot of a Windows command line, with it running the Discord Rich Presence script.](https://rb3pc.milohax.org/images/xtra/rpc/pyrun.png "cmd.exe")

That's it! Remember to close it out after you're done and to repeat this when you want to open this up again.

If it doesn't open correctly, make sure that you've set Python as the default application for `.py` files.  
![A screenshot of a Windows' default application selection. Python is selected and the cursor is over "Set Default."](https://rb3pc.milohax.org/images/xtra/rpc/pyrun.png "cmd.exe")

If you're on [[the Milohax Discord]](https://discord.gg/milohax), you can use the `!richpresence` for more information, like getting a "Warped"/"Your Year in Review" stats and how to set it up for Xbox 360!

{% include links.html %}