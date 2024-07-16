# Configuration:

<br/>

## Controllers:

**This section is for standard guitar controls, standard drums, and Xbox 360/Wii Pro Drums.**  
Pro Guitars and/or Keyboards are set up later.

If you're playing with a single instrument controller, consider the [[Instrument Repo]](instrument-repo#readme) which has easy drag and drop profiles for various rhythm game instruments.

If not, keep reading.

**Right click on “Rock Band 3” and select “Create Custom Gamepad Configuration”**

![A screenshot of RPCS3's right click menu, showing "Create Custom Gamepad Configuration" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/conf/rpcs3pad.png "Create Custom Gamepad Configuration")

* If you are planning on plugging in multiple instruments, _you must set them on different ports_ (Player 1, Player 2, etc).
* PS3 guitar, drum controllers, and MIDI Pro Adapters **for the Rock Band series** are plug and play and require no additional setup.

**If your controller isn't being detected, click “Refresh”. If that doesn't solve it, restart RPCS3.**

Once you've finished configuring, **remember to click “Save”.**

Below are the buttons you should map in RPCS3's Gamepad Settings.
  
### Guitars:

* If you're using PS2 (Guitar Hero), PS3 (Guitar Hero), or Wii guitars, set the “Handlers” option to “MMJoyStick.” 
* If you're using Xbox 360 guitar controllers, set the “Handlers” option to “XInput.”

Make sure you **set “Device Class” to “Guitar”.**

**Switch the drop-down menu, next to "Device Class", to "Rock Band" if you're using a Rock Band guitar or leave it on “Guitar Hero” if you're using a Guitar Hero guitar**. 
 
**Some guitar controllers** (most notably Guitar Hero controllers) misbehave and **refuse to map sometimes. If you try mapping a button and get “U+”, click “Filter Noise"** at the bottom left of the controller configuration window **then try mapping**.

| **RPCS3**          | **Rock Band Guitars** | **Guitar Hero Guitars** |
|:------------------:|:---------------------:|:-----------------------:|
| Cross | ![Green Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/gf.png "Green Fret") | ![Green Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/rf.png "Red Fret") | ![Red Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Blue Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/bf.png "Blue Fret") | ![Yellow Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/yf.png "Yellow Fret") |
| Triangle | ![Yellow Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/yf.png "Yellow Fret") | ![Blue Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/bf.png "Blue Fret") |
| L1 | ![Orange Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/of.png "Orange Fret") | ![Orange Fret](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/sbu.png "Strumbar Up") | ![Strumbar Up](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/sbd.png "Strumbar Down") | ![Strumbar Down](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/sbd.png "Strumbar Down") |
| D-Pad: Left | ![D-Pad: Left](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/dpl.png "D-Pad: Left") |
| D-Pad: Right | ![D-Pad: Right](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/dpr.png "D-Pad: Right") |
| Right Stick: <br/> Left/Right <br/> (ignore Left on RB Wii guitars on Linux) | ![Whammy Bar](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/wb.png "Whammy Bar") | ![Whammy Bar](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/wb.png "Whammy Bar") |
| Right Stick: <br/> Up/Down <br/> (PS3/Wii guitars only) | ![Effects Switch](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/fx.png "Effects Switch") | |
| L2 <br/> (Xbox 360 guitars only) | ![Effects Switch](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/fx.png "Effects Switch") | |
| L2 <br/> (PS3/Wii guitars only) | ![Solo Buttons](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/solo.png "Solo Buttons") | |
| L3 <br/> (Xbox 360 guitars only) | ![Solo Buttons](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/solo.png "Solo Buttons") | |
| R1 | ![Tilt](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/gtrs/ts.png "Tilt") | Does not work |


### Drums:

Make sure you **set “Device Class” to “Drum”.**

* If you're using PS3 (Guitar Hero), Wii, or Xbox 360 drum controllers, set the “Handlers” option to “MMJoyStick.”
* If you're using a Xbox 360 MIDI Pro Adapter for drums, set the "Handlers" option to "XInput."

**Switch the drop-down menu next to it to "Rock Band Pro" if you're using Rock Band drums or Rock Band Drums with Pro expansions. Do **NOT** use the regular "Rock Band" type. Leave it on “Guitar Hero” if you're using Guitar Hero drums.**

| **RPCS3**    | **Rock Band Drums** | **Guitar Hero Drums** |
|:--------:|:-------------------:|:-----------------:|
| Cross | ![Green Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/gp.png "Green Pad") | ![Green Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/gh/gp.png "Green Pad") |
| Circle | ![Red Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/rp.png "Red Pad") | ![Red Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/gh/rp.png "Red Pad") |
| Square | ![Blue Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/bp.png "Blue Pad") | ![Blue Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/gh/bp.png "Blue Pad") |
| Triangle | ![Yellow Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/yp.png "Yellow Pad") | ![Yellow Cymbal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/gh/yc.png "Yellow Cymbal") |
| L1 | ![Foot Pedal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/kp.png "Foot Pedal") | ![Foot Pedal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/gh/kp.png "Foot Pedal") |
| D-Pad | ![D-Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/dp.png "D-Pad") | ![D-Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/dp.png "D-Pad") |
| R1 | ![Second Foot Pedal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/kp.png "Second Foot Pedal") | ![Orange Cymbal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/gh/oc.png "Orange Cymbal") |
| R3 | Cymbal Modifier | |
| L3 | Pad Modifier | |


### Vocals: 

*For vocals*, you can *use regular controllers*. If you're using an actual PS3 controller, switch "Handlers" to DS3. If you're using a PS4 controller (DualShock 4), switch "Handlers" to DS4. If you're using an Xbox 360, Xbox One, or Xbox Series controller, switch "Handlers" to XInput. There's no need to remap anything. Alternatively, you can use a typing keyboard and refer to this guide to customize the mapping according to your preferences. [[DualShock 3 controllers]](https://wiki.rpcs3.net/index.php?title=Help:Controller_Configuration#Using_DualShock_3_controller) and [[DualShock 4 controllers]](https://wiki.rpcs3.net/index.php?title=Help:Controller_Configuration#Using_DualShock_4_controller) may require additional setup.

| **PlayStation (DS4)** | **Xbox One (XInput)** | **Use**                         | **Alt Use**         |
|:---------------------:|:---------------------:|:-------------------------------:|:-------------------:|
| ![Left Stick](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/ls.png "Left Stick") | ![Left Stick](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/ls.png "Left Stick") | Navigation |
| ![D-Pad](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/dp.png "D-Pad") | ![Left Stick](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/dp.png "D-Pad") | Navigation |
| ![Cross Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/x.png "Cross Button") | ![A Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/a.png "A Button") | Select                          |
| ![Circle Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/o.png "Circle Button") | ![B Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/b.png "B Button") | Back                            | Mic 3 Volume (Song) |
| ![Square Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/s.png "Square Button") | ![X Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/x.png "X Button") | Mic 1 Volume (Song) |
| ![Triangle Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/t.png "Triangle Button") | ![Y Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/y.png "Y Button") | View More Info (Library)        | Mic 2 Volume (Song) |
| ![Options Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/opt.png "Options Button") | ![Options Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/opt.png "Options Button") | Options                         | Pause (Song)        |
| ![Share Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/shr.png "Share Button") | ![View Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/viw.png "View Button") | Filters (Library)               | Overdrive (Song)    |
| ![L1 Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/l1.png "L1 Button") | ![Left Bumper](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/lb.png "Left Bumper") | Guide Part Selection (Practice) |
| ![L2 Trigger](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/l2.png "L2 Trigger") | ![Left Trigger](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/lt.png "Left Trigger") | Vocal Part Selection (Practice) |
| ![R1 Button](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/r1.png "R1 Button") | ![Right Bumper](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/rb.png "Right Bumper") | Vocal Track Volume (Song)       |
| ![R2 Trigger](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/ps4/r2.png "R2 Trigger") | ![Right Trigger](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/ctrls/xbox/rt.png "Right Trigger") | Pitch Correction (Song)         |

  

Here's what a _The Beatles: Rock Band Höfner_ Wii controller looks like when it's set up. Note that "Handlers" is set to "MMJoystick" and "Devices" is set to the correct Joystick number. Since it's a Rock Band guitar controller, "Device Class" is also set to "Guitar" and the box next to that is set to "Rock Band."
![A screenshot of RPCS3's Gamepad Settings with a Höfner](instrument-repo/Wii%20Rock%20Band%20Guitars/mapping.png "Gamepad Settings with a Wii The Beatles: Rock Band Höfner guitar controller")

<br/>

## User Account:
In RPCS3, go to **Manage > User Accounts** 
![RPCS3 showing "User Accounts" option under the "Manage" menu.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/conf/rpcs3user.png "RPCS3: User Accounts")

Once you're there, **click on the default username (00000001 - User) and then click “Rename User”.** 

![RPCS3's "User Manager", showing the default username.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/conf/rpcs3rename.png "RPCS3: User Accounts")

**Now change it** to whatever you want, then close it out.  

![RPCS3's "Rename User", showing the user changing the name.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/conf/rpcs3namepanel.png "RPCS3: Rename User")

<br/>

## RPCN:

If you don't want to play online, [[you can skip to the next part]](#quick-configuration).

Go to **Configuration > RPCN**
![A screenshot of RPCS3's Configuration with "RPCN" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/rpcn.png "RPCS3: RPCN")

Click on “**Account**”:  
![A screenshot of RPCS3's RPCN menu with "Account" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/rpcnpopup.png "RPCN")

Click “**Create Account**”:  
![A screenshot of RPCS3's RPCN: Account menu with "Create Account" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/account.png "RPCN: Account")

Enter a **username** and **password**:  
![A screenshot of RPCS3's RPCN: Username menu with a username set and "OK" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/user.png "RPCN: User")  
![A screenshot of RPCS3's RPCN: Password menu with an obscured password set (twice for verification) and "OK" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/password.png "RPCN: Password")  

You will be prompted for an **email address** so you can receive a **verification token**:  
![A screenshot of RPCS3's RPCN: Email menu with an email (twice for verification) set and "OK" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/email.png "RPCN: Email")  

You will next be asked to confirm your account's creation. **Click “Yes”**.

![A screenshot of RPCS3's RPCN: Account Creation popup, asking the user if they're ready to create their account, with "Yes" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/confirm.png "RPCN: Account Creation")

Now go to your email inbox to check for your verification token. You may have to wait a few minutes to get it. If you're still waiting, check your spam inbox. The email will be called **“Your token for RPCN.”  
Copy the token**:

![A screenshot of an email labeled "Your Token for RPCN" with a token below what username it's for](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/emailtoken.png "Your token for RPCN")

**Paste the token** into RPCS3 and click OK:  
![A screenshot RPCS3 telling the user an account was successfully created. They are also prompted for the verification token to reset their password in the future.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/rpcn/created.png "RPCN: Username")

<br/>

# Quick Configuration:
These files are meant for those that just want to play with minimal setup. It is still strongly suggested that you do [[custom configuration]](https://github.com/hmxmilohax/rb3-pc/tree/main#custom-configuration) to tweak to what's best for your computer.  
[[**Rock Band 3 Deluxe must be installed**]](https://rb3dx.neocities.org/) but if it's not already installed, you're not reading this guide and should go back and read it.  

Players who want to use [[microphones]](#audio), [[Wired Pro Guitar and USB/MIDI Keyboards]](#io), [[Electronic Drum Kits]](#io), or [[PS3 Mustang guitars or RB3 Keyboards with dongles]](#passthrough-devices) will still need to configure those.

* [[Recommended settings]](https://github.com/hmxmilohax/rb3-pc/raw/main/config/customconfig/recommended.zip) - These are the settings used for the recommended specs listed in [[requirements]](#requirements).
* [[Minimum settings]](https://github.com/hmxmilohax/rb3-pc/raw/main/config/customconfig/minimum.zip) - These are the settings used for the minimum specs listed in [[requirements]](#requirements).


To use these, **click on the settings you want to download then extract the ZIP archives in the folder where you extracted RPCS3**. It should combine folders automatically if you did it right.  
In the GIF example below, the "Recommended" requirements settings archive (recommended.zip) was downloaded and its contents were moved into RPCS3's folder.

![A GIF of "config" and "dev_hdd0" from "recommended.zip" being moved into its proper location in RPCS3's folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/quickconf.gif "Recommended.zip")

For more info on these settings, [[check the Readme for the settings repository]](https://github.com/hmxmilohax/rb3-pc/tree/main/config/customconfig#about).

<br/>

# Custom Configuration:

**Right click on Rock Band 3** in RPCS3, then click on “**Create Custom Configuration From Default Settings**”.  
![A screenshot of RPCS3's right click menu, showing "Create Custom Configuration From Default Settings" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/rpcs3customconfig.png "Create Custom Configuration From Default Settings")

This may seem overwhelming because of the sheer number of options, but I have color-coded the settings that require adjustment. Anything not colored should be left alone.

| COLOR | MEANING |
|---|---|
| ![A green square with a dashed outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/biggreen.png "Green Square") | **REQUIRED** |
| ![A blue square with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/bigblue.png "Blue Square") | **Performance Tweaks** |
| ![A tan square with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/bigtan.png "Tan Square") | **Recommended** |

We'll go tab by tab, starting with:

<br/>

## CPU


![A screenshot of Rock Band 3's CPU custom settings, showing SPU XFloat Accuracy, SPU Block Size, Preferred SPU Threads, and Thread Scheduler highlighted in blue with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/cpu.png "CPU")
* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Tan Square") **Improved performance, depending on machine**: 
	* **Change "SPU Block Size" to "Mega"** - Ties smaller SPU compiled together, which requiring fewer cores/threads. Drastically speeds up game startup time on certain machines.
	* **Change "Preferred SPU Threads" to "1", "2", "3", or "4"** - May help prevent stutter caused by CPU overloads on systems with fewer cores/threads. **Start at 4 and lower it one by one until it improves**.
	* **Change "Thread Scheduler" to "RPCS3 Scheduler", or "RPCS3 Alternative Scheduler"** - **FOR CPUs WITH 12+ THREADS ONLY!** May help with thread distribution to prevent microstutters.

<br/>

## GPU
![A screenshot of Rock Band 3's GPU custom settings, highlighting Write Color Settings highlighted in green with a dotted outline, Framelimit, Anisotropic Filter, ZCull Accuracy, Output Scaling and VSync highlighted in blue with a dotted outline, and "Default Resolution" highlighted in tan with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/gpu.png "GPU")
* ![A green square with a dashed outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Enable "Write Color Buffers"** - Characters will have severe graphical bugs without this.
* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Blue Square") **Tweak depending on graphics card**: 
	* **Enable "VSync"** - Reduces screen tearing and may lead to a more stable framerate. Slightly increases input latency. **Do not enable this with the frame limiter**.
	* **Change "Frame Limit"** 
		* Set it to "Off" to use higher VBlank Frequencies, which may introduce jitter, **or if you're using VSync.**
		* Set it to 60 if you want a locked 60 FPS framerate (redundant with 60 Hz Vblank). 
		* Auto will use default RPCS3 settings.
		* It is suggested to use your graphics driver's settings or software like MSI Afterburner to cap your framerate instead.
		* Adjusting the frame rate to be higher than 60 exponentially uses more resources, so this is not recommended for low end machines.
		* Be aware that framerates higher than 60 may cause the vocal pitch detection to behave incorrectly.
	* **Change "ZCULL Accuracy" to "Relaxed"** - Provides a slight performance improvement but may cause graphical anomalies in very rare situations.
	* **Adjust "Resolution Scale"** to preference and to what your computer can handle. Increase for sharper graphics at the cost of higher GPU requirements. This forces the game to run at this resolution. Lowering this below 100% isn't worth it as it won't give much, if any, framerate gains.
	* **Adjust "Output Scaling"** to preference and to what your computer can handle. This affects how the game is "blown up" in size when fitting to your monitor's native resolution. Helpful for those keeping Resolution Scale (mentioned above) at 100% and playing on a monitor larger than 1280x720.
		* "Nearest" is completely unfiltered and gives you raw unmodified image. This can cause the game to look pixelated.
		* "Bilinear" uses smoothing to scale the image up. This may cause the game to look blurry. This can cause the game to look blurry.
		* FidelityFX Super Resolution (FSR) uses complicated math to sharpen and enhance the image when it gets blown up to your monitor's resolution. This can create odd artifacts in some instances.
			* You can use "RCAS Sharpening Strength" below to adjust the strength of its effect.
	* ![A tan square with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Tan Square") **For high-end GPUs and advanced users**: 
		* **Change "Default Resolution" to "1920x1080"**. While Rock Band 3 officially caps out at 720p, 1080p can be forced on by manually editing the configuration file or editing the game data configuration. Please refer to [the relevant guide on how to do this and what benefits there are](forcefullhd.md) after finishing up with everything else.


<br/>

## Audio
![A screenshot of Rock Band 3's Audio custom settings, highlighting Enable Buffering in green with a dashed outline, Audio Buffer and Audio Out highlighted in blue with a dotted outline, and Microphone Settings, Microphone Type (Standard), Mic1, Mic2, Mic3, and Mic4 highlighted in tan with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/audio.png "Audio")
* ![A green square with a dashed outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Enable "Enable Buffering"** - Absolutely required by Rock Band 3. It should be enabled by default but if it's disabled, re-enable it. You should set your global settings to default while you're at it because you should've done that to begin with.
* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Blue Square") **Tweak depending on audio hardware and CPU**: 
	* **Adjust "Audio Buffer Duration"** depending on system.
		* Lower values give you less audio latency but use more CPU.
		* Higher values give you more audio latency but use less CPU.
		* Vocalists are affected the most by this, as a higher latency creates a distracting echo. Instrument players can use calibration to compensate regardless of audio buffer setting.
		* You can change this while the game is running, but it will require re-calibrating in Rock Band 3's system settings.
	* **Change "Audio Out" to "XAudio2"** - This is only recommended for users on extremely low end machines as it causes weird audio problems overtime. Experiment with this setting to make sure it actually helps on your end. **Most users should stay on Cubeb!**
* ![A tan square with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Tan Square") **For Vocalists**: 
	* **Set Microphone type to Standard or Rocksmith**. Standard will allow you to use mics for voice chat and singing. Rocksmith will only work for singing.
	* **Select an input device in "Mic1", "Mic2", and "Mic3"** for vocals. If not playing vocals, Mic1 will be used for voice chat.
	* Once again, keep in mind that playing with framerates higher than 60 may cause issues with vocal detection.

<br/>

## I/O
**This section is for people playing with USB/MIDI Keyboards, Pro Guitars, or MIDI Drums!**
* **If you're not playing with a wired Pro Guitar, Pro Drums, or a USB/MIDI keyboard,** [[**skip** over **this section**].](#network)  
* **If you're playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar,** [[**skip** over **this section**].](#network)  

**If your keyboard has a USB port**, all you need to do is **plug it into your computer**.  
![A picture of a MIDI controller's back, showing a USB port and a sustain pedal](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/usbkeys.png "USB Keyboard")  


**If your keyboard only has a MIDI output, you will need a MIDI to USB interface**.
![A picture of a MIDI controller's back, showing a 5-DIN MIDI input and output highlighted in yellow with a solid white outline, and multiple pedal inputs.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/midikeys.png "MIDI Keyboard")  

**The same applies to Rock Band 3 Pro Guitars** as they only have MIDI outputs.
![A picture of a Rock Band 3 Fender Mustang Pro Guitar, showing a 5-DIN MIDI output.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/midiprotar.png "Mustang Pro Guitar MIDI Output")  

Here's an example of a MIDI to USB interface. Most will come with an LED indicator to show activity. **To check that you've plugged it in correctly, you should see “MIDI In” blinking when you press a key**.  
![A picture of a MIDI to USB interface.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/miditousb.png "MIDI to USB interface")  


**If you have an audio interface, you may already have a way to plug in MIDI** to your computer, as some audio interfaces come with MIDI inputs. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  


**If everything's connected**, let's go ahead and **focus on RPCS3's I/O tab.**
**YOU MAY HAVE TO MAKE THE WINDOW WIDER TO READ THE OPTIONS!**
![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline, and Pad Handler Mode highlighted in blue with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/io.png "I/O")
* ![A tan square with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Tan Square") **For third party Keyboard and wired Pro Guitar players**: 
	* 🎹 **Keyboard Players: Leave your "Emulated MIDI type" on "Keyboard" and select your keyboard or MIDI interface in the drop-down menu next to it.**.
	* 🎸 **Pro Guitar Players: Change your "Emulated MIDI type" from "Keyboard" to "Guitar (17 Frets)" if you have a Mustang Pro Guitar, or "Guitar (22 Frets)" if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it**.
	* 🎸 🥁 **Pro Drums Players: Change your "Emulated MIDI type" from "Keyboard" to "Drums", then select your MIDI Electronic Drum Kit or MIDI to USB interface in the drop-down menu next to it**.

Visit the instrument repo if you're using a [[Xbox 360]](https://github.com/hmxmilohax/rb3-pc/tree/main/instrument-repo/Xbox%20360%20Rock%20Band%203%20Keyboard#readme) or a [[Nintendo Wii]](https://github.com/hmxmilohax/rb3-pc/tree/main/instrument-repo/Wii%20Rock%20Band%20Keyboard#readme) Rock Band 3 Keyboard connected via MIDI to USB. Also visit the instrument repo if you're on a [[MIDI Drum Kit]](https://github.com/hmxmilohax/rb3-pc/tree/main/instrument-repo/MIDI%20Drums#readme) and wish to adjust mappings.

* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Blue Square") **Tweak depending on CPU**: 
	* **Change "Pad Handler Mode" to "Multi-threaded"** if you have a CPU **with more than 12 threads.**
  
 **If your instrument isn't detected in the drop-down menu, click on "Save custom configuration", close the Custom Configuration window, then right click on Rock Band 3 to reopen it. If that doesn't work, restart RPCS3.**  
  
As **keyboards don't have PS3 buttons, the first octave is** reserved **for mapped keys**. Use the picture below as a reference. I **strongly** suggest putting labels on your keyboard to remind you of what each key does along with color ranges. **The** keyboard's **pitch knob should be mapped to the touch strip and modulation wheel and sustain pedal should be mapped to Overdrive deployment.**
![A picture of a 37 key keyboard, showing the second octave mapped to PlayStation buttons, C3 to E3 under a red color, F3 to B3 under a yellow color, C4 to E4 under a blue color, F4 to B4 under a green color, and C5 under an orange color.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/keysctrl.png "MIDI Keyboard Reference")  

<br/>

## Network
![A screenshot of Rock Band 3's Network custom settings, highlighting Network Status (Connected) in green with a dashed outline, IP/Hosts switches (rb3ps3live.hmxservices.com=45.33.48.123), PSN Status (RPCN), and Enable UPNP (not checked) highlighted in tan with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/network.png "Network")
* ![A green square with a dashed outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Change the Network Status to “Connected” as highlighted in the picture. If left on “Disconnected,” the game will temporarily freeze when browsing the song library.**
* ![A tan square with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Tan Square") **For online multiplayer**: 
	* Tick **"Enable UPNP"** or **forward port 9103 (UDP) in your firewall**.
		* **Don't enable UPNP while port forwarding** as this can cause crashes.
	* As of writing this, there's one Rock Band 3 multiplayer servers to connect to. You can easily switch between them.
		* For RBEnhanced GoCentral: Join the [[RBEnhanced Discord server]](https://discord.gg/6rRUWXPYwb) and go to the [[#gocentral-connecting]](https://discord.com/channels/953085263008129064/1076031372185042984) channel. Follow the instructions for RPCS3.  

<br/>

## Advanced
![A screenshot of Rock Band 3's Advanced custom settings, highlighting Driver Wake-Up Delay (1µ) in green with a dashed outline, "Exclusive Fullscreen Mode, VBlank Frequency, and Maximum Number of SPURS Threads highlighted in blue with a dotted outline, and Debug Console Mode highlighted in tan with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/advanced.png "Advanced")
* ![A green square with a dashed outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Change "Driver Wake-up Delay" to "20µ"** to avoid crashing after a few songs. Increase it to "40µ" if the issue persists.
* ![A blue square with a dotted outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Tan Square") **Depending on your computer**: 
	* **Adjust VBlank Frequency** if you want a higher internal framerate. This can make it easier to hit notes but may cause graphical instability and connection issues while online. **It's best left alone** and not recommended to go above 75 Hz if adjusting it for online play. Increasing it exponentially uses more CPU and GPU.
		* Once again, having a higher VBlank can cause issues with vocal detection.
	* **Change "Maximum Number of SPURS Threads"** - May improve performance on systems with less cores and threads [[like 4th gen Intel i5 CPUs with 4 cores and 4 threads]](https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005).
* ![A tan square with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Tan Square") **Strongly Suggested**: 
	* **Enable "Debug Console Mode"** - With Rock Band 3 Deluxe installed, and "Large Heap" enabled in its settings, along with this option enabled, you can take advantage of higher memory access, leading to longer sessions with longer songs and increased stability. If your computer is within the minimum (or higher) requirements, there's no reason you shouldn't enable this.
	* **Change "Exclusive Fullscreen Mode" to "Prefer borderless fullscreen"** to prevent potential crashes and audio desync when changing from Rock Band 3 to another program while in fullscreen.
	

<br/>

## Emulator
![A screenshot of Rock Band 3's Emulator custom settings, showing "Show trophy popups", "Show PPU compilation hint", "Show Shader Compilation hint", "Start Games in fullscreen mode", "Use native user interface."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/emulator.png "Emulator")
You can leave this as is if you want, but I would consider changing the following options:
* ![A tan square with a solid outline.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Tan Square") **Optional tweaks**: 
	* **“Show trophy popups”** - Mimics the way Trophy notifications appear on the PS3. I personally disable this as the game has its own pop-ups.
	* **“Show PPU compilation hint”** - This creates a popup whenever RPCS3 is compiling units for the PPU. This only comes up once as the "Recompiler (LLVM)" setting in the CPU tab does this when launching the game.
	* **“Show shader compilation hint”** - This creates a popup whenever RPCS3 is compiling shaders. Whether you leave it on or not is up to you, but I should tell you what this means as it is important. When you run PS3 games, it has to compile shaders to “translate” the graphics from a PS3 format to a format your PC can work with. **The game will** appear to **stutter when this happens**. **This happens on ALL computer systems. When it finishes** compiling an effect, **it will usually never happen again**. **The best way to deal with this is** just **to** **play the game** as it will quickly go away. You can also use Rock Band 3 Deluxe's Autoplay modifier to let it go through a few songs in party shuffle and let it compile a decent amount of shaders.
	* **“Start games in Fullscreen mode”** - Switches to Fullscreen when you start Rock Band 3.
	* **“Use Native Interface”** - Removes the pretty displays RPCS3 adds, including notifications and game startup background. It will instead use old school pop-ups for keyboard prompts. This can also fix a problem with instrument controllers using MMJoystick soft locking the game when the keyboard comes up. The native interface also seems to cause slight frame rate drops.
    

**After all of that, remember to click "Apply" then "Save custom configuration"**

If everything seems to be working, **I'd also strongly suggest changing RPCS3's log to only display fatal errors** as it gets flooded by excess messages otherwise.

To do this, **right click in RPCS3's log at the bottom and then left click on "Fatal"**.

![A screenshot of RPCS3's log being right clicked and showing that it has been switched to only log "Fatal" errors.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/logging.png "RPCS3 Fatal Logging")

That's the difficult part over with.

<br/>


# Passthrough Devices: 

**If you're not playing with a PS3 Mustang Pro Guitar or a PS3 Keyboard with their respective dongles**, [[**skip over this section**]](#troubleshooting).

To start with, **close out RPCS3** **and plug in the instrument's dongle** to your computer.

Now, [**\[go to Zadig's website\]**](https://zadig.akeo.ie/) and **download the latest version, then open it** up.

Click on **Options** then **List All Devices**.  
![A screenshot of Zadig showing "List All Devices" under "Options" highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/pass/zadiglistall.png "Zadig: Options: List All Devices")

You should now see devices listed. **Switch it to your Rock Band 3 Pro Instrument**. In this example, we're using the Mustang Pro Guitar, which shows up as “Harmonix RB3 Mustang Guitar for PlayStation® 3”.  
![A screenshot of Zadig showing "Harmonix RB3 Mustang Guitar for PlayStation® 3" highlighted in the devices listed.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/pass/zadigsel.png "Zadig: Harmonix RB3 Mustang Guitar for PlayStation® 3")

**After selecting the right device, you should see the option to replace the driver. _MAKE SURE YOU ARE REPLACING THE DRIVER ONLY FOR THE PRO GUITAR/KEYBOARD!!_** Click Replace Driver.  
![A screenshot of Zadig with "Replace Driver" highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/pass/zadigreplace.png "Zadig: Replace Driver")

A warning will appear. **Again, make sure you have selected your RB3 Pro Guitar or keyboard instrument.** After you have made sure, **click** “**Yes**.”  
![A screenshot of Zadig warning the user that they're about to modify a system driver, with "Yes" highlighted](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/pass/zadigreplace.png "Zadig: Warning - System Driver")

It will then install the driver. As the program says, it may take a few minutes.  
![A screenshot of Zadig in the middle of a driver install.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/pass/zadigprogress.png "Zadig: Installing Driver...")


If everything goes well, you will get this message:  
![A screenshot of Zadig telling the user that the driver was installed successfully with "Close" highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/pass/zadigdone.png "Zadig: Success")

**Close Zadig** and, **with the dongle** still **connected**, **open up RPCS3** and **open Rock Band 3**.

Turn your controller on and you should see it automatically assign a player number.  
![A picture of a Mustang Pro Guitar with the second player LED lit up.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/pass/protaron.png "Fender Mustang Pro Guitar: Player 2")

Likewise, in Rock Band 3, you will see the instrument ready to join.  
![A screenshot of Rock Band 3 with a Pro Guitar ready to join.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/pass/rb3player.png "Rock Band 3: Pro Guitar ready to join")

<br/>

# Troubleshooting:


*   **_Stuttering audio_**

	* [![A video thumbnail that reads "Click here for audio example."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/badaudio.png)](https://www.youtube.com/watch?v=UoCMEQbNThs&t=20s "Rock Band 3 Deluxe - Low-End Low-Buffer Autoplay - YouTube")
	* Increase “Audio Buffer Duration” as mentioned in [[the Audio tab of Rock Band 3's Custom Configuration]](#audio) until the stuttering stops. 100 ms is a great starting point for low end computers.

*   **_General performance issues_**
	*	Set your computer to the [[High Performance power plan]](https://help.ableton.com/hc/en-us/articles/115000211304-Using-the-High-performance-power-plan-Windows-).
	*   Go back to the [[Custom Configuration setup section]](#custom-configuration) and apply suggested low performance tweaks.
	*   Install [[Rock Band 3 Deluxe]](https://rb3dx.neocities.org/) and disable Post Effects in Deluxe Settings.
	*	If you motherboard has a Realtek audio, try [[installing the latest driver]](https://realtek-download.com/download-hd/). This is a [[known issue]](https://github.com/RPCS3/rpcs3/issues/14648) where using the default "High Definition Audio" driver doesn't use all threads.
	*	Close out the dedicated Discord client and open it up in your browser or on your phone. You can also try an alternative Discord client [[like Vesktop]](https://github.com/Vencord/Vesktop), but I claim no responsibility for your Discord account.

*   **_"Characters have glitchy flying instruments and accessories."_**
	*   There is currently no fix for this. If you experience this, [[please report your findings on RPCS3's GitHub].](https://github.com/RPCS3/rpcs3/issues/8408)

*   **_"My game doesn't fill the screen."_**
	*   Enable "Overscan" in Rock Band 3's System Settings.

*   **_"My game feels off."_**
	*   Run Calibration in Rock Band 3's System Settings if you haven't for some reason. Disable “Dolby Digital” if you enabled it in the same menu.

*   **_"My game crashes when practicing on regular guitar/bass."_**
	*   You didn't read the guide and did not install Rock Band 3 Deluxe, which fixes this.

*   **_"I cannot use Automatic Calibration in System Settings."_**
	*   Automatic Calibration only works for PS3 Rock Band guitar/bass controllers with passthrough.

*   **_"My game gets stuck when naming a character or band."_**
	*   This seems to vary by controller. Try using the whammy or effects switch if you have it. I'd also suggest doing any sort of character customization on a typing keyboard or a regular game controller as some instrument controllers don't have enough buttons to use the on-screen keyboard. You can also try disabling the Native Interface as mentioned in [[the Emulator section of Custom Configuration]](#emulator).

*   **_"Scrolling through the library has long pauses."_**
	*   You didn't read the guide and did not set the “Network Status” to “Connected” in the [[Network tab when setting up the Custom Configuration]](#network) for Rock Band 3.

*   **_"My PS3 Rock Band instrument controller shows up as two controllers."_**
	*   You did [[controller configuration]](#controllers) for a PS3 Rock Band controller, which usually isn't needed due to passthrough. Just unbind the controller and it should be fine.

*   **_[Rock Band 3 Deluxe] "I crash in the intro video."_**
	*   You have incompatible Rock Band 3 Deluxe files. You need to go to Rock Band 3's game directory in `dev_hdd0\game\BLUS30463\USRDIR` and delete every `.dta` file aside from `dx_high_memory.dta`.
		* If you still have this issue, redownload Rock Band 3 Deluxe as Github sometimes doesn't download correctly.
	
*   **_[Pro Drums] "Hitting two cymbals registers as a tom."_**
	*   This is an infamous Rock Band 3 bug called the "double cymbal glitch" and plagues all versions of Rock Band 3, even console versions. You can try to slightly [[flam]](https://en.wikipedia.org/wiki/Drum_rudiment#Flam) the two inputs to get around this.

*   **_\[ONLINE\] "I cannot find a 3rd or 4th player when searching."_**
	*   Port 9103 is blocked. You can either enable UPNP in Rock Band 3's [[Network]](#network) configuration or manually forward port 9103 (UDP) in your firewall. **Don't enable UPNP while port forwarding** as this can cause crashes.
	*	Rock Band 3 online lobbies can only have 2 slots of Guitar/Bass/Keys, one Drums slot, and one Vocal slot. If you want to bypass this, go to 
	Options > Deluxe Settings > Advanced > Controller > Change Controller Type

*   **_\[ONLINE\] "I crash when searching for players with UPNP enabled."_**
	*   Your router may have issues with RPCS3's UPNP feature. Go to Rock Band 3's Custom Configuration [[Network section]](#network), and disable "Enable UPNP." You will need to [[search how to port forward in your router]](https://www.noip.com/support/knowledgebase/general-port-forwarding-guide).

*   **_\[ONLINE\] "I'm stuck on “Registering Account” when trying to connect to online servers."_**
	*   You may have lost connection to RPCN  and will have to restart the game. If you continue to get this after restart, close out Rock Band 3, go to the top menu in RPCS3, “Configuration” > “RPCN” > “Account” > “Test Account” then restart the game to force a reconnection.
 
*   **_\[ONLINE\] "I keep disconnecting constantly while playing online."_**
	*   Double check to make sure your connection is stable. Try connecting via Ethernet cable if possible. If you have increased your VBlank past 60 Hz, set it back to 60 Hz. Aside from that, there's not much that can be done aside from getting better internet.

*   **_“I followed every step and my game is crashing/performing horribly!”_**
	*   Double check to make sure you meet the requirements and have followed every step correctly. This guide has been thoroughly tested and has been proven to work by many people with varying degrees of hardware. If you are absolutely sure you followed every step correctly, it is 90% likely that the dump of the game you have is bad, a 9% chance your computer ran out of disk space or doesn't meet the minimum specs, and 1% chance it's a skill issue. If you wish, contact me on [**[the Milohax discord]**](https://rb3dx.neocities.org/discord) for advice.

*	**_"You didn't mention changing (SETTING) in the guide. It helped my performance."_**
	* [[Open an issue]](https://github.com/hmxmilohax/rb3-pc/issues/new) with your suggestions or contact me on [**[the Milohax discord]**](https://rb3dx.neocities.org/discord) with your findings. If it checks out, I'll probably add it to this guide.

<br/>

# Conclusion:

That's it! You now (hopefully) have set up Rock Band 3 on your PC. While you're here, why not join some communities that are helping keep the Rock Band community alive?

<div align="center">

**Rock Band 3 Deluxe/Milohax:** 

[![Rock Band 3 Deluxe Logo](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/rb3dx.gif)](https://rb3dx.neocities.org/ "Rock Band 3 Deluxe")

</div>

Milohax are the developers of the must-have Rock Band 3 Deluxe mod that I cannot recommend enough. **[\[Download here\]](https://rb3dx.neocities.org/)**. On top of [[the many features it adds]](https://rb3dx.neocities.org/features), they also have developed mods for [Guitar Hero 1](https://github.com/Milohax-archive/Guitar-Hero-Deluxe), [Guitar Hero 2 (both the Xbox 360](https://github.com/hmxmilohax/Guitar-Hero-II-Deluxe-360) and [PS2 version](https://github.com/Milohax-archive/Guitar-Hero-Deluxe)s), [Dance Central 1](https://github.com/hmxmilohax/dance-central-1-deluxe), [Dance Central 3](https://github.com/hmxmilohax/dance-central-3-deluxe), [Rock Band 1](https://github.com/hmxmilohax/rock-band-1-deluxe), [Rock Band 2](https://github.com/hmxmilohax/rock-band-2-deluxe), [Lego Rock Band](https://github.com/Milohax-archive/lego-rock-band-deluxe), [Green Day Rock Band](https://github.com/Milohax-archive/greenday-rock-band-deluxe), [Rock Band Blitz](https://github.com/Milohax-archive/rock-band-blitz-deluxe), and [The Beatles: Rock Band](https://github.com/Milohax-archive/beatles-rock-band-deluxe) 

[You can **\[join the amazing Milohax Discord here\]**](https://rb3dx.neocities.org/discord).

<div align="center">

**RBEnhanced:**

[![RBEnhanced Logo](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/rbe.png)](https://rb3e.rbenhanced.rocks/ "RBEnhanced")

</div>

Developers of the amazing RBEnhanced mod that currently only exists for Xbox 360 and Wii. The same developers also help run and maintain the GoCentral server that is the original online revival server for Rock Band 3. Without this, this game would be more or less dead and the entire online portion of this guide wouldn't exist.

You can [**\[join RBEnhanced's Discord here\]**](https://discord.gg/6rRUWXPYwb).

Special thanks to:

*   [Dark](https://dark.ski/), [Linos](https://www.youtube.com/@LinosMelendi), [Jnack](https://www.youtube.com/@jnackmclain), [Hughtobasic](https://www.youtube.com/@thisisRK), [ihatecompvir](https://www.youtube.com/@ihatecompvir1591), and [LysiX](https://www.youtube.com/@LysiX) for technical information regarding RPCS3 and/or Rock Band 3.
*   [qfoxb](https://github.com/qfoxb), [SlothDemon](https://www.youtube.com/@SlothDemon1991), [Jnack](https://www.youtube.com/@jnackmclain) (tested for nearly 50 hours lmao), [knvtva](https://github.com/knvtva), and 1osks for testing and reporting results.
*   SlothDemon1991, gonakil1ya, GamerPerson22, Vex, Trish, ItzSlicedcorn/Vivian, and Linos for helping set up scenarios for tutorial pictures.
*   RPCS3 Wiki for initial information on controllers and USB passthrough.
*   [TheNathannator's](https://github.com/TheNathannator) [PlasticBand GitHub](https://github.com/TheNathannator/PlasticBand) for even better documentation on controllers.


<div align="center">

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

</div>
