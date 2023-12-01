## ABOUT:
These are meant for users that quickly want to just start playing with minimal setup. It is still strongly suggested that you do [[custom configuration]](https://github.com/carlmylo/rb3-pc/tree/main#custom-configuration) to tweak to your computer's optimal settings.  
You *MUST* have [[Rock Band 3 Deluxe installed]](https://github.com/hmxmilohax/rock-band-3-deluxe#-installing-on-rpcs3) otherwise these will not work to their full potential.  

To use these, click on the settings you want to download then extract the ZIP archives in the folder where you extracted RPCS3. It should combine folders automatically if you did it right.

If you're on build 0.0.28-15417 of RPCS3, [[use the older version of this page]](https://github.com/carlmylo/rb3-pc/blob/main/config/customconfig/_old#readme)

</br>

### [[Recommended settings]](https://github.com/carlmylo/rb3-pc/raw/main/config/customconfig/recommended.zip)
These are the settings used for the *recommended* specs.

These files:
* Set SPU Block Size to "Mega"
* Set Anisotropic Filtering to "16x", enable "Write Color Buffers" and "VSync", increase Resolution Scale to 150% (1920x1080), and increase Resolution Scale Threshold to 24x24.
* Decrease Audio Buffer Duration to "60 ms."
* Sets Pad Handler Mode to "Multi-threaded" and disables all extra I/O settings.
* Set Network Status to "Connected", configure RPCS3 for AshCentral, connect to RPCN, and enable UPNP
* Enable "Debug Console Mode", Set Exclusive Fullscreen Mode to "Prefer borderless fullscreen", and Driver Wake-Up Delay to "20 µs"
* Enable "Large Heap", set Venue FPS to "60", disable "Camera Shake", "Depth of Field", and enables "HD Characters."

### [[Minimum settings]](https://github.com/carlmylo/rb3-pc/raw/main/config/customconfig/minimum.zip)
These are the settings used for the *minimum* specs.

These files:
* Set SPU Block Size to "Mega" and Preferred SPU Threads to "2"
* Disable Anti-aliasing, enable "Write Color Buffers", set ZCULL Accuracy to "Relaxed (Fastest)", and Shader Quality to "Low"
* Sets the Audio Out to "XAudio2" and increase Audio Buffer Duration to "100 ms"
* Set Network Status to "Connected", configure RPCS3 for GoCentral, connect to RPCN, and enable UPNP
* Enable "Debug Console Mode", Set Exclusive Fullscreen Mode to "Prefer borderless fullscreen", and Driver Wake-Up Delay to "40 µs"
* Disable post-processing and various in-game effects, and set the game to only load smaller venues.


</br>


## User settings
These are settings used and confirmed working by Milohax Community members.

### [[Sloth settings]](https://github.com/carlmylo/rb3-pc/blob/main/config/customconfig/slothsettings.zip)
These are used daily on an AMD Ryzen 2600 CPU, a NVIDIA GT 730 (2GB) GPU, 8 GBs of RAM.

### [[Carl settings]](https://github.com/carlmylo/rb3-pc/blob/main/config/customconfig/carlsettings.zip)
These settings are strictly here for me to download due to constant emulator resets due to writing tutorials. These are used daily on an AMD Ryzen 3900x CPU, a NVIDIA GTX 1660 GPU, 32 GBs of 3600 MHz RAM, a Samsung 980 Pro 2 M.2 PCIe x4 NVME SSD, and Focusrite Scarlett 18i20 interface. I'm strictly keeping these here for my use and suggest you use the recommended specs instead.  
These files include an extra folder and file (\GuiConfigsCurrentSettings.ini) to enable a specific setting to fix issues with Turing microarchitecture GPUs.

These files:
* Set Anisotropic Filtering to "16x", enable "Write Color Buffers" and "VSync", increase Resolution Scale to 150% (1920x1080), and increase Resolution Scale Threshold to 24x24.
* Decrease Audio Buffer Duration to "60 ms"
* Configure the Emulated MIDI Devices to a 17 Fret Protar and a Keyboard
* Sets Pad Handler Mode to "Multi-threaded"
* Set Network Status to "Connected", configure RPCS3 for GoCentral, connect to RPCN, and enable UPNP
* Enable "Debug Console Mode", Set Exclusive Fullscreen Mode to "Prefer borderless fullscreen", and Driver Wake-Up Delay to "20 µs"
* Disable "Show trophy popups", "Show PPU Compilation Hint", "Show shader compilation hint", "Use native user interface"
* Enables Debug Mode for "High-Precision Z Buffer"
* Set Venue FPS to "60", enable "High Memory Mode", disable "Motion Blur", "Camera Shake", and "Depth of Field", and sets a custom theme.

### [[Extremely low spec settings]](https://github.com/carlmylo/rb3-pc/blob/main/config/customconfig/extremelylowspec.zip)
These are *emergency low-spec settings* for a laptop running an AMD E2-1800 APU (1.70 GHz) and 16 GBs of RAM. *This is an extremely not optimal experience and these settings are only here as an experiment.*

These files:
* Disable Anti-aliasing, set ZCULL Accuracy to "Relaxed (Fastest)", Shader Quality to "Low", the Renderer to "OpenGL", and reduce resolution to the point where it may be hard to read busy charts
* Set Network Status to "Connected", configure RPCS3 for GoCentral, connect to RPCN, and enable UPNP
* Set Exclusive Fullscreen Mode to "Prefer borderless fullscreen", and Driver Wake-Up Delay to "40 µs"
* Removes venues and menu backgrounds via DX.dta
