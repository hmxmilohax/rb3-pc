Video Version (Outdated):  
[![A thumbnail of the video version of this tutorial.](images/xtra/vidthumb.jpg)](https://www.youtube.com/watch?v=sramU-Xdhrs "How to play Rock Band 3 on PC (with RPCS3) - YouTube")

<br/>

>##### WARNING:
<sub>_This tutorial will **not** provide you with a download to the game or DLC. None of the Discord servers listed will provide you with them, either. Make a backup of your own copy or Google for help. **Piracy is illegal and attracts Tim Sweeney's lawyers**._
<br/>

1. [_Requirements_](#Requirements)
2. [_Installation_](#INSTALLATION)
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

<br/>

# REQUIREMENTS:

You will need:
* _A ripped copy of Rock Band 3 for the PS3. (Ideally BLUS-30463)_
* _11.12 GBs of space minimum. (145.66 GBs for **all** officially released content dating from RB1 to RB3, including DLC, RBN, and exports)_
* _An instrument controller. You can use:_
	*   _Any Rock Band and Guitar Hero Guitar (PS3, PS4, Wii, X360)_
	*   _Any Rock Band and Guitar Hero Drums (PS3, PS4, Wii, X360)_
	*   _Rock Band 3 Keyboard (PS3 version via dongle only)_<sup>a b
	*   _Rock Band 3 Fender Mustang PRO-Guitars \[**Wireless**\] (PS3 version via dongle only)_<sup>a
	*   _Rock Band 3 Fender Mustang PRO-Guitars \[**Wired**\] (PS3, Wii, X360 via MIDI to USB adapter)_
	*   _Rock Band 3 Squier Stratocaster PRO-Guitars (PS3, Wii, X360 via via MIDI to USB adapter)_
	*   _Any MIDI Keyboards (**37 keys minimum** via USB or MIDI to USB adapter)_<sup>b c
	*   _MIDI Drumkits (via USB or MIDI to USB adapter with MidiDrumHero and VJoy)_<sup>d
	*   _Microphones (game can be controlled with most game controllers or typing keyboard when playing as a vocalist)_
*   _A computer_
	* This guide has been tested on specs as low as Intel Core i5-4460, Intel Core i5-6500, Intel Core i7-3770, and AMD Ryzen 3 3200G CPUs. It has also been tested on GPUs as low as NVIDIA GTX 1650, AMD Radeon RX 550. Although we suggest 16 GBs of RAM, it has worked on 8 GBs of RAM. This game also technically run on a SteamDeck but that's beyond the scope of this tutorial. 
    You can check [RPCS3’s page for suggested specifications here](https://rpcs3.net/quickstart).
*   _[7zip](https://www.7-zip.org/download.html) (or WinRAR if you hate yourself)_

<sup>a</sup> <sub>Wii Rock Band instrument controllers and dongles can be converted for PS3, but this is beyond the scope of this tutorial. Google is your friend.</sub>  
<sup>b</sup> <sub>Connecting keyboards via MIDI with less than 37 keys is possible but not ideal so are therefore exempt from this tutorial.</sub>  
<sup>c</sup> <sub>Certain MIDI keyboards, notably Yamaha ones, may exhibit problems due to their MIDI implementation. This is known and a solution is being worked on.</sub>  
<sup>d</sup> <sub>I don’t have a MIDI Drumkit so there is no set up tutorial for this. Apologies. If you have one and would like to help by sending in screenshots of the setup process, please contact me on the Milohax Discord.</sub>

<br/>

# INSTALLATION:

We’ll be downloading an older version of RPCS3 as it performs better at the moment. Although this guide is Windows-centric, I have linked Linux and Mac OS just in case you want to try it on those operating systems. For those curious (nerds), this is the last RPCS3 build before the QT6 merge which has various problems.

| [![Microsoft Windows' logo](images/inst/windows.png)](https://github.com/RPCS3/rpcs3-binaries-win/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_win64.7z "Windows Version") | [![Linux's Tux Mascot](images/inst/linux.png)](https://github.com/RPCS3/rpcs3-binaries-linux/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_linux64.AppImage "Linux Version") | [![Apple Computers' logo](images/inst/mac.png)](https://github.com/RPCS3/rpcs3-binaries-mac/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_macos.dmg "Mac OS Version") |
|---|---|---|

**Once it downloads, extract the .7zip file.**  
![A screenshot of the the right click menu from Windows exploring highlighting "Extract files..." from the 7-Zip category.](images/inst/extract.png "Extract Files")

I would strongly suggest extracting the files into “C:\\Games\\RPCS3” or a separate internal drive to avoid  permissions issues. I'd also untick the box that will create the massive sub-directory as shown highlighted in the picture. Avoid installing and running from an external drive as it can cause massive issues.  
![A screenshot of the Extract window from 7-zip. It shows the "Extract to" as C:\Games\RPCS3 and the box below it unchecked.](images/inst/extractdir.png "Extract")

Once that’s extracted, [**download the PlayStation 3 system software from Sony’s website**](https://www.playstation.com/en-us/support/hardware/ps3/system-software/). **Scroll down** until you get to “**Update using a computer**”, **click that** to expand, then **click on “Download PS3 Update.**”  
  
_**If you’re on a Chromium based browser like Chrome or Edge, MAKE SURE YOU RIGHT CLICK AND “Save link as”, or it MAY become stuck.**_

Once again, the picture below links to the download page.
[![A screenshot of Sony's "How to update PS3 console system software" page with the "Update using a computer" subcategory expanded.](images/inst/fwpage.png)](https://www.playstation.com/en-us/support/hardware/ps3/system-software/ "How to update PS3 console system software")


Now **open up RPCS3**, and **drag** the **PS3UPDAT.PUP** you just downloaded from Sony’s website **into RPCS3** **then click Yes**.  
![A screenshot of RPCS3's Firmware Installer asking the user if they want to install the firmware named "PS3UPDAT.PUP".](images/inst/fwinstall.png "RPCS3 Firmware Installer")

**Let it install.**  
![A screenshot of RPCS3's Firmware Installer in the middle of installing firmware version 4.90.](images/inst/rpcs3fw.png "RPCS3 Firmware Installer")

**When it finishes, click OK**  
![A screenshot of RPCS3's Firmware Installer after a successful install of PS3 firmware and LLE modules.](images/inst/rpcs3fwdone.png "Success!")

It will start compiling modules, which may take a few minutes. **Let it do its thing.**  
![A screenshot of RPCS3 compiling PPU modules with a progress bar at 1/8th completion.](images/inst/rpcs3fwcomp.png "Compiling PPU modules...")

Next, **go to the folder where you have your copy of Rock Band 3 stored and drag the folder into RPCS3**. Again, you're on your own here. [I used “PS3 Disc Dumper” for this because it’s the easiest way.](https://youtu.be/mRxSKxoYt_g)
![A GIF of the dumped folder of Rock Band 3 being dragged into RPCS3, which updates RPCS3 to display Rock Band 3 in the game list.](images/inst/rpcs3rb3dnd.gif "Rock Band 3 [BLUS30463]")

Rock Band 3 is now in your game library in RPCS3, however it’s out of date. Let’s fix that. **You will need to download the update PKG file** which is linked below. This directly links to Sony’s official download. You may get security warnings as Sony’s update server lacks HTTPS.  
[\[CLICK HERE TO DOWNLOAD ROCK BAND 3 UPDATE PKG\]](http://b0.ww.np.dl.playstation.net/tppkg/np/BLUS30463/BLUS30463_T4/e52d21c696ed0fcf/UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg)

The filename will look something like this:

[![Rock Band 3's PKG update in Edge's download tray.](images/inst/rb3pe.png)](http://b0.ww.np.dl.playstation.net/tppkg/np/BLUS30463/BLUS30463_T4/e52d21c696ed0fcf/UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg "UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg")

When that’s finished, drag the update file into RPCS3 and click Yes, just like you did earlier with the PS3UPDAT.PUP file.  
![A screenshot of RPCS3's Decrypter/ Installer asking if the user wants to install the Rock Band 3 update package file.](images/inst/rpcs3pkg.png "PKG Decrypter/ Installer")

<br/>

# CONFIGURATION:

_*IF YOU HAVE CHANGED SETTINGS FOR RPCS3, SET THEM BACK TO DEFAULT FOR ROCK BAND 3 BEFORE FOLLOWING THIS TUTORIAL!*_

<br/>

## CONTROLLERS:

**This is for standard (five fret guitars, RB/GH drums) controllers.  
Pro Guitars, or Keyboards are set up later.**

Right click “Rock Band 3” and click on **“Create Custom Gamepad Configuration”**

![A screenshot of RPCS3's right click menu, showing "Create Custom Gamepad Configuration" highlighted](images/conf/rpcs3pad.png "Create Custom Gamepad Configuration")

* If you are planning on plugging in multiple instruments, you must make profiles for each of them.
* PS3 standard guitar and drum controllers _should_ be plug and play. If, for some reason, they’re not, you will need to bind them as detailed below. 
* If you’re using PS3, PS4, or Wii controllers, set the “Handlers” option to “MMJoyStick.” 
* If you’re using Xbox controllers, set the “Handlers” option to “XInput”

Below are the buttons you should map in RPCS3’s Gamepad Settings. **[\[You can also check RPCS3’s website for reference as well\]](https://wiki.rpcs3.net/index.php?title=Help:Peripherals_and_accessories#Configuring_Instruments).**

**If your controller isn’t being detected, hit “Refresh”. If that doesn’t solve it, restart RPCS3.**

When you’re finished, **remember to click “Save”.**

  
**Guitar**:  
Make sure you **set “Device Class” to “Guitar”.**

Switch the dropdown menu next to it to"Rock Band" if you’re using a Rock Band guitar or leave it on “Guitar Hero” if you’re using a Guitar Hero guitar.  
**Some guitar controllers** (most notably Guitar Hero controllers) **misbehave and refuse to map** sometimes. If you try mapping a button and get “U+”, try pressing “**Filter Noise**” the bottom left of the controller configuration.

| **RPCS3**          | **Rock Band Guitars** | **Guitar Hero Guitars** |
|:------------------:|:---------------------:|:-----------------------:|
| Cross | ![Green Fret](images/btns/gtrs/gf.png "Green Fret") | ![Green Fret](images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](images/btns/gtrs/rf.png "Red Fret") | ![Red Fret](images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Blue Fret](images/btns/gtrs/bf.png "Blue Fret") | ![Yellow Fret](images/btns/gtrs/yf.png "Yellow Fret") |
| Triangle | ![Yellow Fret](images/btns/gtrs/yf.png "Yellow Fret") | ![Blue Fret](images/btns/gtrs/bf.png "Blue Fret") |
| L1 | ![Orange Fret](images/btns/gtrs/of.png "Orange Fret") | ![Orange Fret](images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](images/btns/gtrs/sbu.png "Strumbar Up") | ![Strumbar Up](images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](images/btns/gtrs/sbd.png "Strumbar Down") | ![Strumbar Down](images/btns/gtrs/sbd.png "Strumbar Down") |
| Right Stick: Right | ![Whammy Bar](images/btns/gtrs/wb.png "Whammy Bar") | ![Whammy Bar](images/btns/gtrs/wb.png "Whammy Bar") |
| L2 | ![Effects Switch](images/btns/gtrs/fx.png "Effects Switch") | |
| R1 | ![Tilt](images/btns/gtrs/ts.png "Tilt") | Does not work |


**Drums**:

Make sure you **set “Device Class” to “Drum”.**

Switch the dropdown menu next to it to"Rock Band" if you’re using Rock Band drums, “Rock Band Pro” if you’re using Rock Band Drums with Pro expansions, or leave it on “Guitar Hero” if you’re using Guitar Hero drums.

| **RPCS3**    | **Rock Band Drums** | **Rock Band Pro Drums** | **Guitar Hero Drums** |
|:--------:|:---------------:|:-------------------:|:-----------------:|
| Cross | ![Green Pad](images/btns/drms/rb/gp.png "Green Pad") | ![Green Pad](images/btns/drms/rb/gp.png "Green Pad") | ![Green Pad](images/btns/drms/gh/gp.png "Green Pad") |
| Circle | ![Red Pad](images/btns/drms/rb/rp.png "Red Pad") | ![Red Pad](images/btns/drms/rb/rp.png "Red Pad") | ![Red Pad](images/btns/drms/gh/rp.png "Red Pad") |
| Square | ![Blue Pad](images/btns/drms/rb/bp.png "Blue Pad") | ![Blue Pad](images/btns/drms/rb/bp.png "Blue Pad") | ![Blue Pad](images/btns/drms/gh/bp.png "Blue Pad") |
| Triangle | ![Yellow Pad](images/btns/drms/rb/yp.png "Yellow Pad") | ![Yellow Pad](images/btns/drms/rb/yp.png "Yellow Pad") | ![Yellow Cymbal](images/btns/drms/gh/yc.png "Yellow Cymbal") |
| L1 | ![Foot Pedal](images/btns/drms/rb/kp.png "Foot Pedal") | ![Foot Pedal](images/btns/drms/rb/kp.png "Foot Pedal") | ![Foot Pedal](images/btns/drms/gh/kp.png "Foot Pedal") |
| D-Pad | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") |
| R1 |  | ![Second Foot Pedal](images/btns/drms/rb/kp.png "Second Foot Pedal") | ![Orange Cymbal](images/btns/drms/gh/oc.png "Orange Cymbal") |
| R3 |  | Cymbal Modifier | |
| L3 |  | Pad Modifier | |


**Vocals**:  
Vocals use regular controllers. If you're using a PS4 controller, switch to DS4. If you're using an Xbox One controller, switch to XInput. You don't have to remap anything. You can also use a typing keyboard and use this guide as reference to change the mapping to your liking.

| **PlayStation (DS4)** | **Xbox One (XInput)** | **Use**                         | **Alt Use**         |
|:---------------------:|:---------------------:|:-------------------------------:|:-------------------:|
| ![Left Stick](images/btns/ctrls/ps4/ls.png) | ![Left Stick](images/btns/ctrls/xbox/ls.png) | Navigation |
| ![Left Stick](images/btns/ctrls/ps4/dp.png) | ![Left Stick](images/btns/ctrls/xbox/dp.png) | Navigation |
| ![Cross Button](images/btns/ctrls/ps4/x.png) | ![A Button](images/btns/ctrls/xbox/a.png) | Select                          |
| ![Circle Button](images/btns/ctrls/ps4/o.png) | ![B Button](images/btns/ctrls/xbox/b.png) | Back                            | Mic 3 Volume (Song) |
| ![Square Button](images/btns/ctrls/ps4/s.png) | ![X Button](images/btns/ctrls/xbox/x.png) | Mic 1 Volume (Song) |
| ![Triangle Button](images/btns/ctrls/ps4/t.png) | ![Y Button](images/btns/ctrls/xbox/y.png) | View More Info (Library)        | Mic 2 Volume (Song) |
| ![Options Button](images/btns/ctrls/ps4/opt.png) | ![Options Button](images/btns/ctrls/xbox/opt.png) | Options                         | Pause (Song)        |
| ![Share Button](images/btns/ctrls/ps4/shr.png) | ![View Button](images/btns/ctrls/xbox/viw.png) | Filters (Library)               | Overdrive (Song)    |
| ![L1 Button](images/btns/ctrls/ps4/l1.png) | ![Left Bumper](images/btns/ctrls/xbox/lb.png) | Guide Part Selection (Practice) |
| ![L2 Trigger](images/btns/ctrls/ps4/l2.png) | ![Left Trigger](images/btns/ctrls/xbox/lt.png) | Vocal Part Selection (Practice) |
| ![R1 Button](images/btns/ctrls/ps4/r1.png) | ![Right Bumper](images/btns/ctrls/xbox/rb.png) | Vocal Track Volume (Song)       |
| ![R2 Trigger](images/btns/ctrls/ps4/r2.png) | ![Right Trigger](images/btns/ctrls/xbox/rt.png) | Pitch Correction (Song)         |

  

As an example, here’s what a _Wii The Beatles: Rock Band Hofner_ controller looks like when it’s setup. Note the "Handlers" being set to "MMJoystick" and "Devices" being set to the correct Joystick number.
![A screenshot of RPCS3's Gamepad Settings with a Hofner](images/conf/rpcs3padexm.png "Gamepad Settings with a Wii The Beatles:Rock Band Hofner ")

<br/>

## USER ACCOUNT:
In RPCS3, go to **Manage > User Accounts**  
![RPCS3 showing "User Accounts" option under the "Manage" menu.](images/conf/rpcs3user.png "RPCS3: User Accounts")

Once you’re there, click on the default username (00000001 - User) and then click **“Rename user”** and change it to whatever you want, then close it out.  
![RPCS3's "User Manager", showing the default username.](images/conf/rpcs3rename.png "RPCS3: User Accounts")

<br/>

## RPCN ACCOUNT

**If you don’t want to play online, you can skip this** part.

Go to **Configuration > RPCN**
![A screenshot of RPCS3's Configuration with "RPCN" highlighted](images/rpcn/rpcn.png "RPCS3: RPCN")

Click on “**Account**”:  
![A screenshot of RPCS3's RPCN menu with "Account" highlighted](images/rpcn/rpcnpopup.png "RPCN")

Click “**Create Account**”:  
![A screenshot of RPCS3's RPCN: Account menu with "Create Account" highlighted](images/rpcn/account.png "RPCN: Account")

Enter a **username** and **password**:  
![A screenshot of RPCS3's RPCN: Username menu with a username set and "OK" highlighted](images/rpcn/user.png "RPCN: User")  
![A screenshot of RPCS3's RPCN: Password menu with an obscured password set (twice for verification) and "OK" highlighted](images/rpcn/password.png "RPCN: Password")  

You will be prompted for an **email address** so you can receive a **verification token**:  
![A screenshot of RPCS3's RPCN: Email menu with an email (twice for verification) set and "OK" highlighted](images/rpcn/email.png "RPCN: Email")  

**Click “Yes”** and go to your email inbox. You may have to wait a few minutes to get it. If you’re still waiting, check your spam inbox. The email will be called **“Your token for RPCN.” Copy the token**:

![A screenshot of an email labeled "Your Token for RPCN" with a token below what username it's for](images/rpcn/emailtoken.png "Your token for RPCN")

**Paste the token** into RPCS3 and click OK:  
![A screenshot RPCS3 telling the user an account was successfully created.](images/rpcn/created.png "RPCN: Username")

<br/>

# CUSTOM CONFIGURATION:

**Right click on Rock Band 3** in RPCS3, then click on “**Create Custom Configuration**”  
![A screenshot of RPCS3's right click menu, showing "Create Custom Configuration" highlighted](images/cust/rpcs3customconfig.png "Create Custom Gamepad Configuration")

This may seem overwhelming due to the sheer number of options but I have color coded stuff that will need adjustment. Everything not colored should be on default options.

| COLOR | MEANING |
|---|---|
| ![A yellow square.](images/cust/bigyellow.png "Yellow Square") | *REQUIRED* |
| ![A green square.](images/cust/biggreen.png "Green Square") | Low performance fixes |
| ![A pink square.](images/cust/bigpink.png "Pink Square") | Adjust depending on PC, or leave it alone |
| ![A teal square.](images/cust/bigteal.png "Teal Square") | Optional |

We’ll go tab by tab, starting with:

<br/>
## CPU


![A screenshot of Rock Band 3's CPU custom settings, showing SPU XFloat Accuracy, SPU Block Size, and Preferred SPU Threads highlighted in green.](images/cust/cpu.png "CPU")
* ![A green square.](images/cust/smallgreen.png "Green Square") For low end CPUs (older 4 core/4 threads chips): 
	* Change "SPU Block Size" to "Mega" - Ties smaller SPU compiled together, which requires less cores/threads.
	* Change "Preferred SPU Threads" to "1" - Limiting to 1 thread helps prevent stutter caused by CPU overloads.
	* **AS A LAST RESORT** "SPU XFloat Accuracy" to "Relaxed" - Changing this will gain a few frames but **will break practice mode!**

<br/>

## GPU
![A screenshot of Rock Band 3's GPU  custom settings, showing Write Color Settings highlighted in yellow, ZCULL Accuracy highlighted in green, Resolution Scale, Resolution Scale Threshold, Frame Limit, and Shader Quality highlighted in pink, and VSync highlighted in teal.](images/cust/gpu.png "GPU")
* ![A yellow square.](images/cust/smallyellow.png "Yellow Square") REQUIRED: 
	* Enable "Write Color Buffers" - Fixes 99% of the issues with characters not having textures.
* ![A green square.](images/cust/smallgreen.png "Green Square") For low end GPUs: 
	* Change "ZCULL Accuracy" to "Relaxed" - Slight performance improvement which may cause graphical anomalies.
* ![A pink square.](images/cust/smallpink.png "Pink Square") Tweak depending on computer: 
	* Change "Frame Limit" to "Off" to use enable uncapped framerate (may introduce jitter), set to 60 if you want a locked 60 FPS framerate (redundant with 60 Hz Vblank).
	* Adjust "Shader Quality" depending on your system. Low and Medium will drastically reduce quality, Auto will use suggested RPCS3's setting, and High is the best option. Ultra looks similar to high.
	* Adjust "Resolution Scale" to taste. Lower for a performance gains at a drastic cost in quality. Increase for sharper graphics.
	* Adjust "Resolution Scale Threshold" depending on "Resolution Scale" above. Set the number to whatever percent you increased your resolution (i.e. for 1920x1080, which is 150%, you'd calculate what 150% of 16 is, which would be 24.
	> * ![A teal square.](images/cust/smallteal.png "Teal Square") OPTIONAL: 
	* Enable "VSync" - Reduces screen tearing and may lead to a more stable framerate. Increases latency slightly.

<br/>

## Audio
![A screenshot of Rock Band 3's Audio custom settings, showing Enable Buffering highlighted in yellow, Audio Out highlighted in green, Audio Buffer highlighted in pink, and Microphone Settings, Microphone Type (Standard), Mic1, Mic2, Mic3, and Mic4 highlighted in teal.](images/cust/audio.png "Audio")
* ![A yellow square.](images/cust/smallyellow.png "Yellow Square") REQUIRED: 
	* Enable "Enable Buffering" - Absolutely required by Rock Band 3. It should be enabled by default but if it's disabled, reenable it.
* ![A green square.](images/cust/smallgreen.png "Green Square") For Windows users: 
	* Change "Audio Out" to XAudio2" - Can help with with latency.
* ![A pink square.](images/cust/smallpink.png "Pink Square") Tweak depending on computer: 
	* Adjust "Audio Buffer Duration" depending on system. Lower values mean less latency but more CPU required to keep stable audio. Higher values mean more stable audio due to less CPU stress. This can be changed while the game is running but will require re-calibrating in Rock Band 3's system settings.
* ![A teal square.](images/cust/smallteal.png "Teal Square") For Vocalists: 
	* Select an input device in "Mic1", "Mic2", and "Mic3" for vocals. If not playing vocals, they will be used for voice chat.

<br/>

#I/O
This section is for people playing with a Keyboard or a Pro Guitar
* If you’re not playing with a wired Pro Guitar or a USB/MIDI keyboard**, **skip** over **this section**.  
* If you’re playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar**, **skip** over **this section**.  

*If your keyboard has a USB port**, all you need to do is **plug it into your computer**.  
![A picture of a MIDI controller's back, showing a USB port and a sustain pedal](images/midi/usbkeys.png "USB Keyboard")  


*If your keyboard only has a MIDI output**, you will need **a MIDI to USB interface**.
![A picture of a MIDI controller's back, showing a 5-DIN MIDI input and output, and multiple pedal inputs.](images/midi/midikeys.png "MIDI Keyboard")  

*The same applies to Rock Band 3 Pro Guitars** as they only have MIDI outputs.
![A picture of a Rock Band 3 Fender Mustang Pro Guitar, showing a 5-DIN MIDI output.](images/midi/midiprotar.png "Mustang Pro Guitar MIDI Output")  

Here’s an example of a MIDI to USB interface. Most will come with a indicator LED to show activity. To check that you plugged it in correctly, **you should see “MIDI In” blinking when you press a key**.  
![A picture of a MIDI to USB interface.](images/midi/miditousb.png "MIDI to USB interface")  


Do note that **some audio interfaces have MIDI inputs**, so if you have one, you may already have a way to plug in MIDI to your computer. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  


If everything's connected, let's go ahead and focus on RPCS3's I/O tab.  
![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in teal.](images/cust/io.png "I/O")
* ![A teal square.](images/cust/smallteal.png "Teal Square"): 
	* Keyboard Players: Leave your "Emulated MIDI type on "Keyboard and select your your keyboard in the drop down menu next to it, or MIDI interface, depending on your connection.
	* Pro Guitar Players: Change your "Emulated MIDI type from "Keyboard" to "Guitar (17 Frets)" if you have a Mustang Pro Guitar, or "Guitar (22 Frets)" if you have a Squier Pro Guitar, then set your MIDI interface in the drop down menu next to it, or MIDI interface, depending on your connection.
  
 **If your instrument isn’t detected in the drop down menu, save your configuration so far and restart RPCS3.**  
  
 As **keyboards don’t have** **PS3 buttons**, **the first octave is** reserved **for mapped keys**. Use this picture as reference. I **strongly** suggest putting artist tape, masking tape, or painter’s tape on your keyboard and drawing the buttons for reference.
 >![A picture of a 37 key keyboard, showing the second octave mapped to PlayStation buttons, C3 to E3 under a red color, F3 to B3 under a yellow color, C4 to E4 under a blue color, F4 to B4 under a green color, and C5 under an orange color.](images/midi/keysctrl.png "MIDI Keyboard Reference")  

<br/>

## NETWORK
![A screenshot of Rock Band 3's Network custom settings, showing Network Status (Connected) highlighted in yellow, IP/Hosts switches (rb3ps3live.hmxservices.com=45.33.48.123), PSN Status (RPCN), and Enable UPNP (not checked) highlighted in teal.](images/cust/network.png "Network")
* ![A yellow square.](images/cust/smallyellow.png "Yellow Square") REQUIRED: 
	* Change the Network Status to “Connected” as highlighted in the picture. If left on “Disconnected”, the game will freeze temporarily when browsing the song library.
* ![A teal square.](images/cust/smallteal.png "Teal Square") For online multiplayer: 
	* Join the \[[RBEnhanced Discord server](https://discord.gg/6rRUWXPYwb)\]** and **go to** the **[\[#gocentral-connecting\]](https://discord.com/channels/953085263008129064/1076031372185042984)** channel. **Follow the instructions for RPCS3**. Although the picture below includes details, this is subject to change, and you should **always refer to the \[[RBEnhanced Discord](https://discord.gg/6rRUWXPYwb)\] for** this **information**. While you’re there, you can also organize sessions with other players.  

## ADVANCED
![A screenshot of Rock Band 3's Advanced custom settings, showing "Exclusive Fullscreen Mode (Automatic (Default)), and Driver Wake-Up Delay (1µ) in green.](images/cust/advanced.png "Advanced")
* ![A green square.](images/cust/smallgreen.png "Green Square"): 
	* Change "Exclusive Fullscreen Mode" to "Prefer borderless fullscreen" to prevent potential crashes and desync when changing program focus constantly.
	* Change "Driver Wake-up Delay" to "20µ" if you experience rare freezing after a few songs. Increase to "40µ" if it still happens.
* ![A teal square.](images/cust/smallteal.png "Teal Square"): 
	* Adjust VBlank Frequency if you want a higher internal framerate. This can make it easier to hit notes, but can cause graphical instability and connection issues while online. It's best left alone.


## EMULATOR**
![A screenshot of Rock Band 3's Emulator custom settings, showing "Show trophy popups", "Show PPU compilation hint", "Show Shader Compilation hint", "Start Games in fullscreen mode", "Use native user interface".](images/cust/emulator.png "Emulator")
You can leave this as is if you want, but I would consider changing the following options:
* ![A teal square.](images/cust/smallteal.png "Teal Square") Optional tweaks: 
	* “Show trophy popups” - Mimics the way Trophy notifications appeared on the PS3. I personally disable this as the game has its own pop-ups.
	* “Show PPU compilation hint” - This creates a popup whenever RPCS3 is compiling units for the PPU. This only comes up once as "Recompiler (LLVM)" in the CPU tab does this when launching the game.
	* “Show shader compilation hint” - This creates a popup whenever RPCS3 is compiling shaders. Whether you leave it on or not is up to you, but I should tell you what this means as it is important. When you run PS3 games, it has to compile shaders to “translate” the graphics from a PS3 format to a format your PC can work with. **The game will** appear to **stutter when this happens**. **This happens on ALL computer systems. When it finishes** compiling an effect, **it will usually never happen again**. **The** **best way to deal with this is** just **to** **play the game** as it will quickly go away.
	* “Start games in Fullscreen mode” - Obviously just switches to Fullscreen when you start Rock Band 3. I personally enable this.  
	* “Use Native Interface” - Disabling this will remove RPCS3 notifications entirely while the game is launched.
    

![](https://i.imgur.com/57y43gN.png)

> _**Wireless PS3 Mustang Pro Guitar and PS3 Rock Band 3 Keyboard with dongle**_

**If you’re not playing with a PS3 Mustang Pro Guitar and PS3 Keyboard with their respective dongles, skip** over **this section.**

To start with, **close out RPCS3** **and plug in the instrument’s dongle** to your computer.

Now, [**\[go to Zadig’s website\]**](https://zadig.akeo.ie/) and **download the latest version.** **Open it** up.

Click on **Options** then **List All Devices  
![](https://i.imgur.com/570PDgY.png)**

You should now see devices listed. **Switch it to your Rock Band 3 Pro Instrument**. In this example, we’re using the Mustang Pro Guitar, which shows up as “Harmonix RB3 Mustang Guitar for PlayStation® 3”.  
![](https://i.imgur.com/hnMHcuG.png)

After selecting the right device, you should see the option to replace the driver. **MAKE SURE YOU ARE REPLACING THE DRIVER ONLY FOR THE PRO GUITAR/KEYBOARD.** Click Replace Driver.  
[![](https://i.imgur.com/fYHveYg.png)](https://imgur.com/fYHveYg)

A warning will appear. **Again, make sure you have selected your RB3 Pro Guitar or keyboard instrument.** After you have made sure, click “**Yes”  
![](https://i.imgur.com/9U0nl2H.png)**

It will then install the driver. As the program says, it may take a few minutes.  
[![](https://i.imgur.com/p280nGq.png)](https://imgur.com/p280nGq)

If everything goes well, you will get this message:  
  
![](https://i.imgur.com/AvGHA05.png)

**Close Zadig** and, **with the dongle** still **connected**, **open up RPCS3** and **open Rock Band 3**.

Turn your controller on and you should see it automatically assign a player number.

![](https://i.imgur.com/7htptfw.png)

Likewise, in Rock Band 3, you will see the instrument ready to join.  
![](https://i.imgur.com/GbI6yYp.png)

> _**TROUBLESHOOTING**_

*   **_Stuttering Audio_**

*   
*   Increase “Audio Buffer Duration” as mentioned in [the Audio tab of Rock Band 3’s Custom Configuration](https://im.carlmylo.com/stream/rockband3#audio) until the stuttering stops. 100 ms is a great starting point for low end computers.

*   **_General performance issues_**
	*   Go back and read the “**EXTRA**” messages in the [Custom Configuration setup section](https://im.carlmylo.com/stream/rockband3#cpu).

*   **_Game doesn’t fill the_** **_screen_**
	*   Enable Overscan in Rock Band 3’s System Settings

*   **_Game is delayed_**
	*   Run Calibration in Rock Band 3’s System Settings if you haven’t for some reason. Disable “Dolby Digital” if you enabled it in the same menu.

*   **_Cannot use Automatic Calibration in System Settings_**
	*   Automatic Calibration only works for PS3 guitar controllers via passthrough.

*   **_Game gets stuck when naming a character_**
	*   This is an RPCS3 issue. You can fix it by changing the effects switch on a RB guitar controller. Otherwise, changing your controller’s Input Handler in “[Create Custom Gamepad Configuration](https://im.carlmylo.com/stream/rockband3#ctrl)” to “Keyboard” then back to whatever you had originally fixes it. This should work while the game is running.

*   **_Characters have flying instruments and accessories_**
	*   There is currently no fix for this. If you experience this, [please report your findings on RPCS3’s Github.](https://github.com/RPCS3/rpcs3/issues/8408)

*   **_Scrolling through library has long pauses_**
	*   You forgot to set the “Network Status” to “Connected” in the [Network tab when setting up the Custom Configuration](https://im.carlmylo.com/stream/rockband3#network) for Rock Band 3.

*   **_My PS3 instrument controller shows up as two_**
	*   You did [controller configuration](https://im.carlmylo.com/stream/rockband3#ctrl) for a PS3 controller, which usually isn’t needed due to passthrough. Just unbind the controller and it should be fine.

*   **_\[ONLINE\] Cannot find a 3rd or 4th player_**
	*   In Rock Band 3’s Custom Configuration, [go to the network tab](https://im.carlmylo.com/stream/rockband3#network) and make sure “Enable UPNP” is enabled. If for some reason you can’t do UPNP, you will need to forward port 9103 (UDP) in your firewall. **Don’t** **enable UPNP while port forwarding** as this can cause crashes.

*   **_\[ONLINE\] Stuck on “Registering Account” when trying to connect to GoCentral_**
	*   You may have lost connection to RPCN or GoCentral and will have to restart the game. If you continue to get this after restart, go to the top menu in RPCS3, “Configuration” > “RPCN” > “Account” > “Test Account” then restart the game to force a reconnection.

*   **_“I followed every step and my game is still crashing”_**
	*   Double check to make sure you have followed every step correctly. This guide has been tested and has been proven to work for plenty of people with varying degrees of hardware. If you are absolutely sure you followed every step correctly, it is 90% likely that the dump of the game you have is bad, and 9% chance your computer ran out of disk space, and 1% chance it’s a skill issue.

> _**CONCLUSION**_

That’s it! You now (hopefully) have a functional setup to play Rock Band 3 on your PC. While you’re here, why not join some communities that are helping keep the Rock Band community alive?

*   **Rock Band 3 Deluxe/Milohax:** [![Rock Band 3 Deluxe Logo](https://i.imgur.com/bJ9x8k8.gif)](https://github.com/hmxmilohax/rock-band-3-deluxe#readme "Rock Band 3 Deluxe")Developers of the must-have RB3DX mod that I cannot recommend enough. **[\[Download and setup instructions here.\]](https://github.com/hmxmilohax/rock-band-3-deluxe)** On top of adding many of quality-of-life features like faster bootups, 60fps venues, and automatic DLC loading, **it also includes RB3\_Plus, which adds extra Pro Keys and Pro Guitar/Bass to songs that didn’t have them.** **If you have a Pro instrument, this is a must have**! On top of this, there are various visual customization options, like using themes from older (and newer) Rock Bands and even Guitar Hero. [You can **\[join Milohax’s Discord here\]**](https://discord.gg/xrba4CjdNC).
*   **RBEnhanced:  
    **[![RBEnhanced Logo](https://i.imgur.com/DM9nTA8.png)](https://discord.gg/6rRUWXPYwb)Developers of the amazing RBEnhanced mod that currently only exists for Xbox 360 and Wii. The same developers also help run and maintain the GoCentral server that is the only way to play Rock Band 3 on PS3 online at the moment. As of writing this, there is an active offshoot that has crossplay with Wii and PS3 players. You can [**\[join RBEnhanced’s Discord here\]**](https://discord.gg/6rRUWXPYwb).

Special thanks to:

*   [DarkRTA](https://www.youtube.com/@darkrta), [Linos](https://www.youtube.com/@LinosMelendi), [Jnack](https://www.youtube.com/@jnackmclain), [Hughtobasic](https://www.youtube.com/@thisisRK), [ihatecompvir](https://www.youtube.com/@ihatecompvir1591), and [LysiX](https://www.youtube.com/@LysiX) for technical information regarding RPCS3 and Rock Band 3.
*   qfoxb, [SlothDemon](https://www.youtube.com/@SlothDemon1991), [Jnack](https://www.youtube.com/@jnackmclain) (tested for nearly 20 hours via autoplay lmao), knvtva, and 1osks for reporting results.
*   RPCS3 Wiki for having pretty decent information on controllers and USB passthrough.

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).