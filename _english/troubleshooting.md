---
title: Troubleshooting
author: Carl Mylo
date: 1000-08-01
category: English
layout: post
---

*   **_Stuttering audio_**

	* [![A video thumbnail that reads "Click here for audio example."](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/xtra/badaudio.png)](https://www.youtube.com/watch?v=UoCMEQbNThs&t=20s "Rock Band 3 Deluxe - Low-End Low-Buffer Autoplay - YouTube")
	* Increase “Audio Buffer Duration” as mentioned in [[the Audio tab of Rock Band 3's Custom Configuration]](https://carlmylo.github.io/rb3-pc/english/customconfiguration#audio) until the stuttering stops. 100 ms is a great starting point for low end computers.

*   **_General performance issues_**
	*	Set your computer to the [[High Performance power plan]](https://help.ableton.com/hc/en-us/articles/115000211304-Using-the-High-performance-power-plan-Windows-).
	*   Go back to the [[Custom Configuration setup section]](https://carlmylo.github.io/rb3-pc/english/customconfiguration#changing-a-custom-configuration) and apply suggested low performance tweaks.
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
	*   This seems to vary by controller. Try using the whammy or effects switch if you have it. I'd also suggest doing any sort of character customization on a typing keyboard or a regular game controller as some instrument controllers don't have enough buttons to use the on-screen keyboard. You can also try disabling the Native Interface as mentioned in [[the Emulator section of Custom Configuration]](https://carlmylo.github.io/rb3-pc/english/customconfiguration#emulator).

*   **_"Scrolling through the library has long pauses."_**
	*   You didn't read the guide and did not set the “Network Status” to “Connected” in the [[Network tab when setting up the Custom Configuration]](https://carlmylo.github.io/rb3-pc/english/customconfiguration#network) for Rock Band 3.

*   **_"My PS3 Rock Band instrument controller shows up as two controllers."_**
	*   You did [[controller configuration]](#controllers) for a PS3 Rock Band controller, which usually isn't needed due to passthrough. Just unbind the controller and it should be fine.

*   **_[Rock Band 3 Deluxe] "I crash in the intro video."_**
	*   You have incompatible Rock Band 3 Deluxe files. You need to go to Rock Band 3's game directory in `dev_hdd0\game\BLUS30463\USRDIR` and delete every `.dta` file aside from `dx_high_memory.dta`.
		* If you still have this issue, redownload Rock Band 3 Deluxe as Github sometimes doesn't download correctly.
	
*   **_[Pro Drums] "Hitting two cymbals registers as a tom."_**
	*   This is an infamous Rock Band 3 bug called the "double cymbal glitch" and plagues all versions of Rock Band 3, even console versions. You can try to slightly [[flam]](https://en.wikipedia.org/wiki/Drum_rudiment#Flam) the two inputs to get around this.

*   **_\[ONLINE\] "I cannot find a 3rd or 4th player when searching."_**
	*   Port 9103 is blocked. You can either enable UPNP in Rock Band 3's [[Network]](https://carlmylo.github.io/rb3-pc/english/customconfiguration#network) configuration or manually forward port 9103 (UDP) in your firewall. **Don't enable UPNP while port forwarding** as this can cause crashes.
	*	Rock Band 3 online lobbies can only have 2 slots of Guitar/Bass/Keys, one Drums slot, and one Vocal slot. If you want to bypass this, go to 
	Options > Deluxe Settings > Advanced > Controller > Change Controller Type

*   **_\[ONLINE\] "I crash when searching for players with UPNP enabled."_**
	*   Your router may have issues with RPCS3's UPNP feature. Go to Rock Band 3's Custom Configuration [[Network section]](https://carlmylo.github.io/rb3-pc/english/customconfiguration#network), and disable "Enable UPNP." You will need to [[search how to port forward in your router]](https://www.noip.com/support/knowledgebase/general-port-forwarding-guide).

*   **_\[ONLINE\] "I'm stuck on “Registering Account” when trying to connect to online servers."_**
	*   You may have lost connection to RPCN  and will have to restart the game. If you continue to get this after restart, close out Rock Band 3, go to the top menu in RPCS3, “Configuration” > “RPCN” > “Account” > “Test Account” then restart the game to force a reconnection.
 
*   **_\[ONLINE\] "I keep disconnecting constantly while playing online."_**
	*   Double check to make sure your connection is stable. Try connecting via Ethernet cable if possible. If you have increased your VBlank past 60 Hz, set it back to 60 Hz. Aside from that, there's not much that can be done aside from getting better internet.

*   **_“I followed every step and my game is crashing/performing horribly!”_**
	*   Double check to make sure you meet the requirements and have followed every step correctly. This guide has been thoroughly tested and has been proven to work by many people with varying degrees of hardware. If you are absolutely sure you followed every step correctly, it is 90% likely that the dump of the game you have is bad, a 9% chance your computer ran out of disk space or doesn't meet the minimum specs, and 1% chance it's a skill issue. If you wish, contact me on [**[the Milohax discord]**](https://rb3dx.neocities.org/discord) for advice.

*	**_"You didn't mention changing (SETTING) in the guide. It helped my performance."_**
	* [[Open an issue]](https://github.com/carlmylo/rb3-pc/issues/new) with your suggestions or contact me on [**[the Milohax discord]**](https://rb3dx.neocities.org/discord) with your findings. If it checks out, I'll probably add it to this guide.