---
title: Installation
author: Carl Mylo
date: 1000-02-01
category: English
layout: post
---

Before starting the installation process, **make sure your drivers and operating system are up to date**.

## Downloads

**Let's start by downloading 7-Zip**, which will open the compressed .7z archives most of these downloads will be stored inside of. **If you already have 7-Zip** or an alternative installed, you can **skip to the next steps.**

[**[Click here to go to 7-Zip's download page]**](https://www.7-zip.org/download.html).

[![A screenshot of 7-zip.org's download page, with a cursor hovering over the 64 bit .exe installer.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/7zip.png)](https://www.7-zip.org/download.html "7-zip.org/download")

**Now**, **let's** go ahead and **install Microsoft Visual C++ 2019 Redistributable**, which is required by RPCS3. You probably already have this, but it doesn't hurt to double check.

[**[Click here to download Microsoft Visual C++ 2019 Redistributable]**](https://aka.ms/vs/17/release/vc_redist.x64.exe)

**Once it finishes downloading**, open it up and **install it**.  

[![A screenshot of Microsoft Visual C++ 2019 Redistributable's installer prompting the user to accept the license terms and conditions and to install.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/mvcpp.png)](https://aka.ms/vs/17/release/vc_redist.x64.exe "Microsoft Visual C++ 2015-22 Redistributable (x64) 14.3833130")

**Next**, let's **download RPCS3**.

[**[Click here to go to RPCS3's download site]**](https://rpcs3.net/download).

Scroll down a bit and download the Windows version.

[![A screenshot of RPCS3's download website, with a cursor hovering over the download button for the Windows version.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3dl.png)](https://rpcs3.net/download "RPCS3 - Download")

**Once it downloads, extract the .7zip file.**  
![A screenshot of the right click menu from Windows Explorer highlighting "Extract files..." from the 7-Zip category.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/extractrpcs3.png "Extract Files")

I would strongly suggest extracting the files into “C:\\Games\\RPCS3” or a separate internal drive to avoid permissions issues. Also, untick the box that will create a sub-directory, as shown highlighted in the picture. 

**Avoid installing to and running from an external drive or from a synced folder (Dropbox, OneDrive, etc.)**, as this usually leads to an unstable experience.  
![A screenshot of the Extract window from 7-zip. It shows the "Extract to" as C:\Games\RPCS3 and the box below it unchecked.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/extractdir.png "Extract")

Once that's extracted, [**[download the PlayStation 3 system software from Sony's website]**](https://www.playstation.com/en-us/support/hardware/ps3/system-software/). **Scroll down** until you get **to** “**Update using a computer**”, **click that** to expand, **then click on “Download PS3 Update.**”  
  
_**If you're using a Chromium-based browser like Chrome or Edge, MAKE SURE YOU RIGHT-CLICK AND “Save link as,” or your download MAY become stuck.**_

Once again, the picture below links to the download page.
[![A screenshot of Sony's "How to update PS3 console system software" page with the "Update using a computer" subcategory expanded.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/fwpage.png)](https://www.playstation.com/en-us/support/hardware/ps3/system-software/ "How to update PS3 console system software")

## Initializing

Now, **go to the folder where you extracted RPCS3.** Keep this folder open in the background. **Open up RPCS3**. **Tick "I have read the Quickstart guide" and "Do not show again", then click "Continue."**  
![A screenshot of RPCS3 welcoming the user to RPCS3, with the mouse cursor hovering over "Continue."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3init.png "Welcome to RPCS3")


**Drag** the **PS3UPDAT.PUP** file you just downloaded from Sony's website **into RPCS3**. 

![A GIF of PS3UPDAT.PUP being dragged into RPCS3.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3fwdnd.gif "PST3UPDAT.PUP")

**Click "Yes"** when the firmware installer prompts you.  
![A screenshot of RPCS3's Firmware Installer asking the user if they want to install the firmware named "PS3UPDAT.PUP."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/fwinstall.png "RPCS3 Firmware Installer")

**Let it install.**  
![A screenshot of RPCS3's Firmware Installer in the middle of installing firmware version 4.90.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3fw.png "RPCS3 Firmware Installer progress")

**When it finishes, click "OK."**  
![A screenshot of RPCS3's Firmware Installer after a successful install of PS3 firmware and LLE modules.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3fwdone.png "Success!")

It will start compiling modules to load the PS3 XMB into the emulator, which may take a few minutes. **You can either let it do its thing or close it.**  
![A screenshot of RPCS3 compiling PPU modules with a progress bar at 1/8th completion.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3fwcomp.png "Compiling PPU modules...")

Next, **open a new file browser window and go to the folder where you have your copy of Rock Band 3 stored and drag the folder into RPCS3's "games" folder**. Again, you're on your own when it comes to finding a copy. [[I used “PS3 Disc Dumper” for this because it's the easiest way]](https://youtu.be/mRxSKxoYt_g).

![A GIF of the dumped folder of Rock Band 3 being dragged into RPCS3's "games" folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3rb3dnd.gif "Rock Band 3 [BLUS30463]")

After dragging it in, click "Refresh" in RPCS3. This should make Rock Band 3 appear in your library.  

![A GIF of "Refresh" being clicked in RPCS3, which updates it to display Rock Band 3 in the game list.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3refresh.gif "Rock Band 3 [BLUS30463]")

Rock Band 3 is now in your game library in RPCS3, but it's not quite ready yet. Next, go get [**[*Rock Band 3 Deluxe*]**](https://rb3dx.neocities.org/).

This is a must-have mod, which also fixes some critical bugs RPCS3 has with Rock Band 3. On top of that, it adds [**[many great features]**](https://rb3dx.neocities.org/features).

[**[Click here to download Rock Band 3 Deluxe]**](https://nightly.link/hmxmilohax/rock-band-3-deluxe/workflows/build/main/RB3DX-PS3.zip).

[![Rock Band 3 Deluxe's .zip archive in Edge's download tray.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rb3dxdl.png)](https://nightly.link/hmxmilohax/rock-band-3-deluxe/workflows/build/main/RB3DX-PS3.zip "RB3DX-PS3.zip")

**When it's finished downloading, extract the archive**.  

![Rock Band 3 Deluxe's .zip being extracted with 7-Zip.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rb3dxext.png "RB3DX-PS3.zip")

**When it finishes extracting, drag the PKG file into RPCS3 and click "Yes"** on the prompt, just like you did earlier with the PS3UPDAT.PUP file.  

![A GIF of Rock Band 3 Deluxe's PKG file being dragged into RPCS3.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3rb3dxdnd.gif "Rock Band 3 Deluxe PKG file")

![A screenshot of RPCS3's Decrypter/ Installer asking if the user wants to install the Rock Band 3 Deluxe package file.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3pkg.png "PKG Decrypter/ Installer")

If it installed successfully, you should see that the Rock Band 3 icon has changed.

![A screenshot of RPCS3's game library, showing an updated icon for Rock Band 3. It's now using the Rock Band 3 Deluxe icon.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/inst/rpcs3rb3dxicon.png "RPCS3 Game List")

You can also rename the game in the list to "Rock Band 3 Deluxe" if you wish. To do this, right-click on "Rock Band 3" and select "Rename In Game List."