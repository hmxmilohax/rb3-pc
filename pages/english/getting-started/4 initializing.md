---
title: Initializing
sidebar: english_sidebar
tags: [getting-started, english]
summary: "What to do with the stuff you downloaded in the previous page."
permalink: gs_init
folder: english
series: "Getting Started"
weight: 4
---

Now, **go to the folder where you extracted RPCS3.** Keep this folder open in the background. **Open up RPCS3**.  
**Tick**:
* "Create desktop shortcut"
* "Create Start Menu shortcut"
* "I have read the Quickstart guide"
* "Do not show again"  

**Disable**:
* "Show at startup"  

After that, **click "Continue."**  
![A screenshot of RPCS3 welcoming the user to RPCS3, with the mouse cursor hovering over "Continue."](https://carlmylo.github.io/rb3-pc/images/install/rpcs3init.png "Welcome to RPCS3")

## Firmware

**Drag** the **PS3UPDAT.PUP** file you just downloaded from Sony's website **into RPCS3**. 

![A GIF of PS3UPDAT.PUP being dragged into RPCS3.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3fwdnd.gif "PST3UPDAT.PUP")

**Click "Yes"** when the firmware installer prompts you.  
![A screenshot of RPCS3's Firmware Installer asking the user if they want to install the firmware named "PS3UPDAT.PUP."](https://carlmylo.github.io/rb3-pc/images/install/fwinstall.png "RPCS3 Firmware Installer")

**Let it install.**  
![A screenshot of RPCS3's Firmware Installer in the middle of installing firmware version 4.90.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3fw.png "RPCS3 Firmware Installer progress")

**When it finishes, click "OK."**  
![A screenshot of RPCS3's Firmware Installer after a successful install of PS3 firmware and LLE modules.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3fwdone.png "Success!")

It will start compiling modules to load the PS3 XMB into the emulator, which may take a few minutes. **You can either let it do its thing or close it.**  
![A screenshot of RPCS3 compiling PPU modules with a progress bar at 1/8th completion.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3fwcomp.png "Compiling PPU modules...")

## Rock Band 3 + Instrument patch

Next, **open a new file browser window. Now go to the folder where you have your copy of Rock Band 3 stored and drag the folder into RPCS3's "games" folder**. Again, you're on your own when it comes to finding a copy. [[I used "PS3 Disc Dumper" for this because it's the easiest way]](https://youtu.be/mRxSKxoYt_g){:target="_blank"}.

![A GIF of the dumped folder of Rock Band 3 being dragged into RPCS3's "games" folder.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3rb3dnd.gif "Rock Band 3 [BLUS30463]")

After dragging it in, click "Refresh" in RPCS3.

![A GIF of "Refresh" being clicked in RPCS3, which updates it to display Rock Band 3 in the game list.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3refresh.gif "Rock Band 3 [BLUS30463]")

## Teleport Patch

We'll now be installing a community made patch to remove distracting visual glitches. These happen on real PS3 hardware as well, but are worse on emulator.  
![A screenshot of Rock Band 3, with a character's hat teleporting off of his head.](https://carlmylo.github.io/rb3-pc/images/trbl/common/flyinst.png)

First, download the [[`rb3_ps3_guitar_glitch_fix.7z` archive]](https://github.com/hmxmilohax/rock-band-3-deluxe/raw/main/dependencies/ps3_patcher/rb3_ps3_guitar_glitch_fix.7z).

![The rb3_ps3_guitar_glitch_fix.7z archive in a browser's download tray.](https://carlmylo.github.io/rb3-pc/images/trbl/teleprob/patchfldr.png "rb3_ps3_guitar_glitch_fix.7z")

Extract the `rb3_ps3_guitar_glitch_fix.7z` archive. Move this window to the right and leave it open.

![rb3_ps3_guitar_glitch_fix.7z being extracted.](https://carlmylo.github.io/rb3-pc/images/trbl/teleprob/patchextr.png "rb3_ps3_guitar_glitch_fix.7z")

Next, go to where your game's disc folder is located.  
The quickest way to get there is to right click Rock Band 3 in RPCS3 and go to `Open Folder > Open Disc Game Folder`. Move this window to the left.

![A RPCS3 with Open Disc Game Folder, within the Open Folder menu, highlighted and with a cursor over it.](https://carlmylo.github.io/rb3-pc/images/trbl/teleprob/patchgames.png "RPCS3")

After that:
1. Go into `PS3_GAME > USRDIR` on the left window.  
2. On the right window, go into the `rb3_ps3_guitar_glitch_fix` folder you extracted. 
3. You should see `gen` in both file browser windows.
4. Drag the `gen` folder from the right `rb3_ps3_guitar_glitch_fix` folder to the left `USRDIR` folder.  
5. Click `Replace the file in the destination` when prompted.

![A GIF of the files within the gen folder being replaced.](https://carlmylo.github.io/rb3-pc/images/trbl/teleprob/patchrepl.gif "Replacing gen folder")

## Rock Band 3 Deluxe

Finally, let's [**[*Rock Band 3 Deluxe*]**](https://rb3dx.milohax.org/){:target="_blank"}.

This is a must-have mod, which also fixes some critical bugs RPCS3 has with Rock Band 3. On top of that, it adds [**[many great features]**](https://rb3dx.milohax.org/features){:target="_blank"}.

[**[Click here to download Rock Band 3 Deluxe]**](https://rb3dx.milohax.org/downloads){:target="_blank"}.

[![Rock Band 3 Deluxe's .zip archive in Edge's download tray.](https://carlmylo.github.io/rb3-pc/images/install/rb3dxdl.png)](https://rb3dx.milohax.org/downloads "RB3DX-PS3.zip")

**When it's finished downloading, extract the archive**.  

![Rock Band 3 Deluxe's .zip being extracted with 7-Zip.](https://carlmylo.github.io/rb3-pc/images/install/rb3dxext.png "RB3DX-PS3.zip")

**When it finishes extracting, drag the PKG file into RPCS3 and click "Yes"** on the prompt, just like you did earlier with the PS3UPDAT.PUP file.  

![A GIF of Rock Band 3 Deluxe's PKG file being dragged into RPCS3.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3rb3dxdnd.gif "Rock Band 3 Deluxe PKG file")

![A screenshot of RPCS3's Decrypter/ Installer asking if the user wants to install the Rock Band 3 Deluxe package file.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3pkg.png "PKG Decrypter/ Installer")

If it installed successfully, you should see that the Rock Band 3 icon has changed.

![A screenshot of RPCS3's game library, showing an updated icon for Rock Band 3. It's now using the Rock Band 3 Deluxe icon.](https://carlmylo.github.io/rb3-pc/images/install/rpcs3rb3dxicon.png "RPCS3 Game List")

You can also rename the game in the list to "Rock Band 3 Deluxe" if you wish. To do this, right-click on "Rock Band 3" and select "Rename In Game List."

{% include custom/series_getting_started_next.html %}

{% include links.html %}