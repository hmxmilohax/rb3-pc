`Last Updated: 2023-08-22T03:56:56+00:00`

Video Version:  
[![Video Version](images\video_thumbnail.jpg "Video Version")](https://www.youtube.com/watch?v=sramU-Xdhrs)

>##### WARNING:
<sub>_This tutorial will **not** provide you with a download to the game or DLC. None of the Discord servers listed will provide you with them, either. Make a backup of your own copy or Google for help. **Piracy is illegal and attracts Tim Sweeny’s lawyers**._

1. [_Requirements_](#reqs)
2. [_Installation_](#install)
3. [_Configuration_](#config)
4. [_Controllers (RB/GH Guitars, Drums, and Gamepads)_](#ctrl)
5. [_User Account_](#useraccount)
6. [_RPCN_](#rpcn)
7. [_Custom Configuration_](#custconfig)
8. [_CPU_](#cpu)
9. [_GPU_](#gpu)
10. [_Audio_](#audio)
11. [_I/O (Wired Pro Guitars and USB/MIDI Keyboards)_](#io)
12. [_Network_](#network)
13. [_Advanced_](#adv)
14. [_Emulator_](#emu)
15. [_Wireless PS3 Mustang Pro Guitars and Keyboards with Dongles_](#prodong)
16. [_Troubleshooting_](#trsht)
17. [_Conclusion_](#end)

>## Requirements:
You will need:
* _A ripped copy of Rock Band 3 for the PS3. (Ideally BLUS-30463)_
* _11.12 GBs of space minimum. (145.66 GBs for _everything_ released from RB1 to RB3, including DLC, RBN, and exports)_
* _An instrument controller. You can use:_
	*   _Any Rock Band and Guitar Hero Guitar (PS3, PS4, Wii, X360)_
	*   _Any Rock Band and Guitar Hero Drums (PS3, PS4, Wii, X360)_
	*   _Rock Band 3 Keyboard (PS3 version via dongle only)_<sup>a
	*   _Rock Band 3 Fender Mustang PRO-Guitars \[**Wirelessly**\] (PS3 version via dongle only)_<sup>a
	*   _Rock Band 3 Fender Mustang PRO-Guitars \[**Wired**\] (PS3, Wii, X360 via MIDI to USB adapter)_
	*   _Rock Band 3 Squier Stratocaster PRO-Guitars (PS3, Wii, X360 via via MIDI to USB adapter)_
	*   _Any MIDI Keyboards (**37 keys minimum** via USB or MIDI to USB adapter)_
	*   _MIDI Drumkits (via USB or MIDI to USB adapter with MidiDrumHero and VJoy)_<sup>b
	*   _Microphones (game can be controlled with most game controllers or typing keyboard when playing as a vocalist)_
*   _A computer (or SteamDeck)_
	* This guide has been tested on specs as low as Intel Core i5-4460, Intel Core i5-6500, Intel Core i7-3770, and AMD Ryzen 3 3200G CPUs. It has also been tested on GPUs as low as Nvidia GTX 1650, AMD Radeon RX 550. Although we suggest 16 GBs of RAM, it has worked on 8 GBs of RAM.  
    You can check [RPCS3’s page for suggested specifications \[here\]](https://rpcs3.net/quickstart).
*   _7zip (or WinRAR if you hate yourself)_
	*   [\[Download 7zip here.\]](https://www.7-zip.org/download.html) I strongly suggest the 64-bit versions.

<sup>a</sup> <sub>Wii instrument controllers and dongles can be converted for PS3, but this is past the scope of this tutorial. Google is your friend.</sub>  
<sup>b</sup> <sub>I don’t have a MIDI Drumkit so there is no set up tutorial for this. Apologies. If you have one and would like to help by sending in screenshots of the setup process, please contact me on the Milohax Discord.</sub>

>## Requirements:
We’ll be downloading an older version of RPCS3 as it performs better in our case. Although this guide is Windows-centric, I have linked Linux and Mac OS just in case you want to try it on those operating systems. For those curious (nerds), this is the last RPCS3 build before the QT6 merge which has various problems.

| [![](https://i.imgur.com/QxZQUBE.png)](https://github.com/RPCS3/rpcs3-binaries-win/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_win64.7z "Windows Version") | [![](https://i.imgur.com/vtdlfBz.png)](https://github.com/RPCS3/rpcs3-binaries-linux/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_linux64.AppImage "Linux Version") | [![](https://i.imgur.com/BHKadwK.png)](https://github.com/RPCS3/rpcs3-binaries-mac/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_macos.dmg "Mac OS Version") |
|---|---|---|

Once it downloads, extract the .7zip file  
![](https://i.imgur.com/EB23Jdt.png)

I would strongly suggest extracting the files into “C:\\Games\\RPCS3” or a separate internal drive to avoid permissions issues. Avoid installing and running from an external drive as it can cause massive issues.  
![](https://i.imgur.com/sSyavMf.png)

Once that’s extracted, [download the PlayStation 3 system software from Sony’s website](https://www.playstation.com/en-us/support/hardware/ps3/system-software/). **Scroll down** until you get to “**Update using a computer**”, **click that** to expand, then click on “**Download PS3 Update.**”  
  
_**If you’re on a Chromium based browser like Chrome or Edge, MAKE SURE YOU RIGHT CLICK AND “Save link as”, or it MAY become stuck.**_

_**Once again, the picture below links to the download page.[![](https://i.imgur.com/F4DxXRf.png)](https://www.playstation.com/en-us/support/hardware/ps3/system-software/)**_

Now **open up RPCS3**, and **drag** the **PS3UPDAT.PUP** you just downloaded from Sony’s website **into RPCS3** **then click Yes**.  
![](https://i.imgur.com/63i6uQk.png)

It will start compiling modules, which may take a few minutes. Let it do its thing.  
![](https://i.imgur.com/JucJcoD.png)

Next, go to the folder where you have your copy of Rock Band 3 stored and drag the folder into RPCS3. Again, I can’t help you get a copy of this game for free. [\[I used “PS3 Disc Dumper” for this because it’s the easiest way\].](https://youtu.be/mRxSKxoYt_g)![](https://64.media.tumblr.com/b2ffe59eac1d72cf734d3f5227b49c6e/tumblr_inline_rqjjsyw1uD1qj7v3b_500.gif)

Rock Band 3 is now in your game library in RPCS3, however you may notice that it’s out of date (depending on your copy of the game.) Let’s fix that. You will need to download the update PKG file which is linked below. This directly links to Sony’s official download. You may get a security warning as Sony’s update server lacks HTTPS.  
[\[CLICK HERE TO DOWNLOAD ROCK BAND 3 UPDATE PKG\]](http://b0.ww.np.dl.playstation.net/tppkg/np/BLUS30463/BLUS30463_T4/e52d21c696ed0fcf/UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg)

The filename will look something like this:

![](https://i.imgur.com/mOegzoX.png)

When that’s finished, drag the update file into RPCS3 and click Yes, just like you did earlier with the PS3UPDAT.PUP file.  
![](https://i.imgur.com/43mEOg8.png)
>## _CONFIGURATION_:
_**EXTRA: IF YOU HAVE CHANGED SETTINGS FOR RPCS3, SET THEM BACK TO DEFAULT FOR ROCK BAND 3 BEFORE FOLLOWING THIS TUTORIAL!**_

> _**CONTROLLERS**_

**This is for standard (five fret guitars, RB/GH drums) controllers.  
Pro Guitars, or Keyboards are set up later.**

Right click “Rock Band 3” and click on **“Create Custom Gamepad Configuration”**

![](https://i.imgur.com/fB48xPq.png)

**If you are planning on plugging in multiple instruments, you must make profiles for each of them.**

**\- PS3 standard guitar and drum controllers _should_ be plug and play. If, for some reason, they’re not, you will need to bind them as detailed below.  
****\- If you’re using PS3, PS4, or Wii controllers**, **set** the “**Handlers**” option **to** “**MMJoyStick**.”  
**\- If you’re using Xbox controllers**, **set** the “**Handlers**” option **to** “**XInput**”

Below are the buttons you should map in RPCS3’s Gamepad Settings. **[\[You can also check RPCS3’s website for reference as well\]](https://wiki.rpcs3.net/index.php?title=Help:Peripherals_and_accessories#Configuring_Instruments).**

**If your controller isn’t being detected, hit “Refresh”. If that doesn’t solve it, restart RPCS3.**

When you’re finished, **remember to click “Save”.**

  
**Guitar**:  
Make sure you **set “Device Class” to “Guitar”.**

Switch the dropdown menu next to it to"Rock Band" if you’re using a Rock Band guitar or leave it on “Guitar Hero” if you’re using a Guitar Hero guitar.  
**Some guitar controllers** (most notably Guitar Hero controllers) **misbehave and refuse to map** sometimes. If you try mapping a button and get “U+”, try pressing “**Filter Noise**” the bottom left of the controller configuration.

| **RPCS3**          | **Rock Band Guitars** | **Guitar Hero Guitars** |
|:------------------:|:---------------------:|:-----------------------:|
| Cross              |                       |                         |
| Circle             |                       |                         |
| Square             |                       |                         |
| Triangle           |                       |                         |
| L1                 |                       |                         |
| D-Pad: Up          |                       |                         |
| D-Pad: Down        |                       |                         |
| Right Stick: Right |                       |                         |
| L2                 |                       |
| R1                 |                       | Does not work in RB3    |


**Drums**:

Make sure you **set “Device Class” to “Drum”.**

Switch the dropdown menu next to it to"Rock Band" if you’re using Rock Band drums, “Rock Band Pro” if you’re using Rock Band Drums with Pro expansions, or leave it on “Guitar Hero” if you’re using Guitar Hero drums.

| **RPCS3**    | **Rock Band Drums** | **Rock Band Pro Drums** | **Guitar Hero Drums** |
|:--------:|:---------------:|:-------------------:|:-----------------:|
| Cross    |                 |                     |                   |
| Circle   |                 |                     |                   |
| Square   |                 |                     |                   |
| Triangle |                 |                     |                   |
| L1       |                 |                     |                   |
| D-Pad    |                 |                     |                   |
| R1       |                 |                     |
| R3       | Cymbal Modifier |
| L3       | Pad Modifier    |


**Vocals**:  
Here is the button guide when set to XInput (Xbox One controller) or DS4 (PS4 Controller) modes. You can also use a typing keyboard and use this guide as reference to change the mapping to your liking.

| **PlayStation (DS4)** | **Xbox One (XInput)** | **Use**                         | **Alt Use**         |
|:---------------------:|:---------------------:|:-------------------------------:|:-------------------:|
|                       |                       | Navigation                      |
|                       |                       | Navigation                      |
|                       |                       | Select                          |
|                       |                       | Back                            | Mic 3 Volume (Song) |
|                       |                       | Rating (Library)                | Mic 1 Volume (Song) |
|                       |                       | View More Info (Library)        | Mic 2 Volume (Song) |
|                       |                       | Options                         | Pause (Song)        |
|                       |                       | Filters (Library)               | Overdrive (Song)    |
|                       |                       | Vocal Track Volume (Song)       |
|                       |                       | Pitch Correction (Song)         |
|                       |                       | Guide Part Selection (Practice) |
|                       |                       | Vocal Part Selection (Practice) |

  

As an example, here’s what a _Wii The Beatles: Rock Band Hofner_ controller looks like when it’s setup:  
![A screenshot of RPCS3's Gamepad Settings](https://i.imgur.com/fCXUYkB.png "A screenshot of RPCS3's Gamepad Settings")