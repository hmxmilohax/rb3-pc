---
title: "PlayStation 4 Rock Band 4 Drums"
sidebar: controllers_sidebar
permalink: ctrls_rb4drums_ps4
folder: instruments
tags: [ps4, drums, english]
summary: "How to setup PS4 Rock Band drums on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/ps4.png" alt="Platform" title="Platform"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rb4drmscontroller.png" alt="Controller" title="Controller"></div>

## NOTES

* Requires installing and running the latest [Minatsuki](https://github.com/yanagiragi/Minatsuki/archive/refs/heads/main.zip) and [Minatsuki-Pro-Drums-Plus](https://github.com/stefman69/Minatsuki-Pro-Drums-Plus) files.
* You need a Bluetooth receiver to connect these drums to your computer.
    * Latency may be an issue depending on your Bluetooth receiver. This may make it difficult to calibrate.
* Works **with or without** the Pro Cymbal expansions.
    * Make sure to configure which cymbals are connected within Rock Band 3.
        * `Menu > Options > Drum Options`
* RPCN Menus (for sending or accepting online invites) may cause a softlock. You may need an alternative input method to navigate these menus, such as [[a typing keyboard or a gamepad]](https://rb3pc.milohax.org/ctrls#gamepads){:target="_blank"}.

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-to-map-pads">How do I map my drums?</a>
                            </h4>
                        </div>
                        <div id="how-to-map-pads" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<p><strong>Click on the Pads icon at the top of RPCS3</strong>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3pad.png" alt="A screenshot of RPCS3, showing the cursor over the Pads menu." title="Pads"></p>
<p>It’s suggested to create a new configuration by clicking <code>Add Configuration</code> at the top right of the <code>Pads</code> window.<br>
This is so you can change configuration profiles in case you want to play games that don’t use instruments.<br>
<img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofadd.png" alt="A screenshot of the top right of RPCS3's Pads window. &quot;Add Configuration&quot; is being clicked on by the mouse cursor." title="Add Configuration"></p>
<p>Follow the instructions and/or match the assignments below.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/padlegend.png" alt="A picture showing how the instrument page and RPCS3 can be used as a mapping reference." title="Mapping the Rock Band Hofner"></p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Map End -->

## Pad Information

| Handlers | Devices |
|:--------:|:-------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Drums | Rock Band Pro |

### Initial Setup
First, we're going to download the latest version of [[Python 3]](https://www.python.org/downloads/){:target="_blank"}.

[[Click here to go to the download page for Python 3]](https://www.python.org/downloads/){:target="_blank"}.

![A screenshot of Python download website. A cursor hovers over "Download Python 3.12.6.](https://rb3pc.milohax.org/images/xtra/rpc/pydl.png "Python 3.12.6")

Once it finishes downloading, open the installer.  
In the installer:  
* Activate `Add python.exe to PATH`
* Click `Install now`  
![A screenshot of Python's installer. "Add python.exe to PATH" and "Install now" are highlighted in tan with a dotted black outline.](https://rb3pc.milohax.org/images/xtra/rpc/pyinstall.png "Python 3.12.6")

Now, go to [[Minatsuki's Github page]](https://github.com/yanagiragi/Minatsuki) and download the code ZIP.

![A screenshot of Minatsuki's Github page. The green "Code" button was clicked and the cursor is over the "Download ZIP" option.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina1.png "Github: Minatsuki")

Extract the `.zip` file into a folder.  
Now go to [[Minatsuki-Pro-Drums-Plus' Github page]](https://github.com/stefman69/Minatsuki-Pro-Drums-Plus) and download the code ZIP.

![A screenshot of Minatsuki-Pro-Drums-Plus' Github page. The green "Code" button was clicked and the cursor is over the "Download ZIP" option.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina2.png "Github: Minatsuki-Pro-Drums-Plus")

Combine Minatsuki-Pro-Drums-Plus' files with the Minatsuki files.  
After that, click on the address bar at the top and type in `cmd` then press Enter.

![A screenshot of a folder that contains the combined files of Minatsuki and Minatsuki-Pro-Drums-Plus. The address bar has been clicked and it says "cmd".](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina3.png "Explorer: Minatsuki")

In the command line, type in in `pip install -r requirements.txt` then press Enter.

![A screenshot of a Windows command line. The command 'pip install -r requirements.txt' was typed in and entered and it downloaded.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina4.png "cmd: pywinusb")

After it installs, type in `pip install vgamepad` then press Enter.

![A screenshot of a Windows command line. The command 'pip install vgamepad' was typed in and entered and it downloaded.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina5.png "cmd: vgamepad")

You may have to install ViGEm Bus. You can download that from [[here]](https://vigembusdriver.com/download/).

### Usage
Synchronize your drums to your computer's Bluetooth receiver.

![A screenshot of a Windows' Bluetooth devices. It shows a Mad Catz Rock Band 4 Drum Set.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/ps41.png "Bluetooth devices")

Double click the `main_xinput.py` file.

![A screenshot of a Windows Explorer. It shows the cursor over 'main_xinput.py' and it is highlighted.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/ps42.png "main_xinput")

When the command line window opens, type in the number of your drum kit and press Enter. Sometimes, it might show up as multiple inputs but it's fine. Just pick one.

![A screenshot of a command line running the 'main_xinput.py' script. It the Rock Band 4 kit drum kit along with other controllers in the selection. The Rock Band kit's number was selected and Enter was pressed.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/ps43.png "main_xinput")

Minimize this command line window. Make sure it stays running in the background.





## Mapping

You simply need to assign the Handler, Device, and Device Class/Type.

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmsxomapping.png" alt="Mapping" title="Mapping"></div>


<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseOne">"I refuse to use Python"</a>
                            </h4>
                        </div>
                        <div id="collapseOne" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <p>If you refuse to set up Python, you won’t have access to cymbals and it will provide an overall worse experience.</p>
<h2 id="pad-information">Pad Information</h2>
<table>
<thead>
<tr>
<th align="center">Handlers</th>
<th align="center">Devices</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">MMJoystick</td>
<td align="center">Joystick</td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th align="center">Device Class</th>
<th align="center">Device Subtype</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Drums</td>
<td align="center">Rock Band Pro</td>
</tr>
</tbody>
</table><h2 id="mapping">Mapping</h2>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Rock Band Drums</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/gp.png" alt="Green Pad" title="Green Pad"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/rp.png" alt="Red Pad" title="Red Pad"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/bp.png" alt="Blue Pad" title="Blue Pad"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/yp.png" alt="Yellow Pad" title="Yellow Pad"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Foot Pedal" title="Foot Pedal"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/x.png" alt="Cross Button" title="Cross Button"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/o.png" alt="Circle Button" title="Circle Button"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/s.png" alt="Square Button" title="Square Button"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/t.png" alt="Triangle Button" title="Triangle Button"></td>
</tr>
<tr>
<td align="center">D-Pad</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/dp.png" alt="D-Pad" title="D-Pad"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/opt.png" alt="Options Button" title="Options Button"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/shr.png" alt="Share Button" title="Share Button"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table><h2 id="profile">Profile</h2>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/PS4%20Rock%20Band%20Drums.7z">[Download Profile]</a></p>
                            </div>
                        </div>
                    <!-- /.panel -->
</div>
</div>

[[Back to Controllers]](https://rb3pc.milohax.org/ctrls#instrument-list)

Mapped by [[gonakil1ya]](https://gonakillya.neocities.org){:target="_blank"}
