## I/O
**This section is for people playing with USB/MIDI Keyboards, Pro Guitars, or MIDI Drums!**
* **If you're not playing with a wired Pro Guitar, Pro Drums, or a USB/MIDI keyboard,** [[**skip** over **this section**].](#network)  
* **If you're playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar,** [[**skip** over **this section**].](#network)  

**If your keyboard has a USB port**, all you need to do is **plug it into your computer**.  
![A picture of a MIDI controller's back, showing a USB port and a sustain pedal](images/midi/usbkeys.png "USB Keyboard")  


**If your keyboard only has a MIDI output, you will need a MIDI to USB interface**.
![A picture of a MIDI controller's back, showing a 5-DIN MIDI input and output highlighted in yellow with a solid white outline, and multiple pedal inputs.](images/midi/midikeys.png "MIDI Keyboard")  

**The same applies to Rock Band 3 Pro Guitars** as they only have MIDI outputs.
![A picture of a Rock Band 3 Fender Mustang Pro Guitar, showing a 5-DIN MIDI output.](images/midi/midiprotar.png "Mustang Pro Guitar MIDI Output")  

Here's an example of a MIDI to USB interface. Most will come with an LED indicator to show activity. **To check that you've plugged it in correctly, you should see “MIDI In” blinking when you press a key**.  
![A picture of a MIDI to USB interface.](images/midi/miditousb.png "MIDI to USB interface")  


**If you have an audio interface, you may already have a way to plug in MIDI** to your computer, as some audio interfaces come with MIDI inputs. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  


**If everything's connected**, let's go ahead and **focus on RPCS3's I/O tab.**
**YOU MAY HAVE TO MAKE THE WINDOW WIDER TO READ THE OPTIONS!**
![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in tan with a solid outline, and Pad Handler Mode highlighted in blue with a dotted outline.](images/cust/io.png "I/O")
* ![A tan square with a solid outline.](images/cust/smalltan.png "Tan Square") **For third party Keyboard and wired Pro Guitar players**: 
	* 🎹 **Keyboard Players: Leave your "Emulated MIDI type" on "Keyboard" and select your keyboard or MIDI interface in the drop-down menu next to it.**.
	* 🎸 **Pro Guitar Players: Change your "Emulated MIDI type" from "Keyboard" to "Guitar (17 Frets)" if you have a Mustang Pro Guitar, or "Guitar (22 Frets)" if you have a Squier Pro Guitar, then select your MIDI to USB interface in the drop-down menu next to it**.
	* 🎸 🥁 **Pro Drums Players: Change your "Emulated MIDI type" from "Keyboard" to "Drums", then select your MIDI Electronic Drum Kit or MIDI to USB interface in the drop-down menu next to it**.

Visit the instrument repo if you're using a [[Xbox 360]](https://github.com/carlmylo/rb3-pc/tree/main/instrument-repo/Xbox%20360%20Rock%20Band%203%20Keyboard#readme) or a [[Nintendo Wii]](https://github.com/carlmylo/rb3-pc/tree/main/instrument-repo/Wii%20Rock%20Band%20Keyboard#readme) Rock Band 3 Keyboard connected via MIDI to USB. Also visit the instrument repo if you're on a [[MIDI Drum Kit]](https://github.com/carlmylo/rb3-pc/tree/main/instrument-repo/MIDI%20Drums#readme) and wish to adjust mappings.

* ![A blue square with a dotted outline.](images/cust/smallblue.png "Blue Square") **Tweak depending on CPU**: 
	* **Change "Pad Handler Mode" to "Multi-threaded"** if you have a CPU **with more than 12 threads.**
  
 **If your instrument isn't detected in the drop-down menu, click on "Save custom configuration", close the Custom Configuration window, then right click on Rock Band 3 to reopen it. If that doesn't work, restart RPCS3.**  
  
As **keyboards don't have PS3 buttons, the first octave is** reserved **for mapped keys**. Use the picture below as a reference. I **strongly** suggest putting labels on your keyboard to remind you of what each key does along with color ranges. **The** keyboard's **pitch knob should be mapped to the touch strip and modulation wheel and sustain pedal should be mapped to Overdrive deployment.**
![A picture of a 37 key keyboard, showing the second octave mapped to PlayStation buttons, C3 to E3 under a red color, F3 to B3 under a yellow color, C4 to E4 under a blue color, F4 to B4 under a green color, and C5 under an orange color.](images/midi/keysctrl.png "MIDI Keyboard Reference")