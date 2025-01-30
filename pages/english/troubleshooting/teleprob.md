---
title: Teleporting Items
sidebar: english_sidebar
permalink: trbl_teleprob
folder: english
tags: [troubleshooting, english]
summary: "How to deal with the visual glitches in Rock Band 3."
---

You can eliminate 99% of the teleportation bugs by installing a community made patch. First, download the [[`rb3_ps3_guitar_glitch_fix.7z` archive]](https://github.com/hmxmilohax/rock-band-3-deluxe/raw/main/dependencies/ps3_patcher/rb3_ps3_guitar_glitch_fix.7z).

![The rb3_ps3_guitar_glitch_fix.7z archive in a browser's download tray.](https://carlmylo.github.io/docu-rpcs3/images/trbl/teleprob/patchfldr.png "rb3_ps3_guitar_glitch_fix.7z")

Extract the `rb3_ps3_guitar_glitch_fix.7z` archive. Move this window to the right and leave it open.

![rb3_ps3_guitar_glitch_fix.7z being extracted.](https://carlmylo.github.io/docu-rpcs3/images/trbl/teleprob/patchextr.png "rb3_ps3_guitar_glitch_fix.7z")

Next, go to where your game's disc folder is located.  
The quickest way to get there is to right click Rock Band 3 in RPCS3 and go to `Open Folder > Open Disc Game Folder`. Move this window to the left.

![A RPCS3 with Open Disc Game Folder, within the Open Folder menu, highlighted and with a cursor over it.](https://carlmylo.github.io/docu-rpcs3/images/trbl/teleprob/patchgames.png "RPCS3")

After that:
1. Go into `PS3_GAME > USRDIR` on the left window.  
2. On the right window, go into the `rb3_ps3_guitar_glitch_fix` folder you extracted. 
3. You should see `gen` in both file browser windows.
4. Drag the `gen` folder from the right `rb3_ps3_guitar_glitch_fix` folder to the left `USRDIR` folder.  
5. Click `Replace the file in the destination` when prompted.

![A GIF of the files within the gen folder being replaced.](https://carlmylo.github.io/docu-rpcs3/images/trbl/teleprob/patchrepl.gif "Replacing gen folder")

That's it!