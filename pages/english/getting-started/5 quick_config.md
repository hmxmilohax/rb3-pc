---
title: Quick Configuration
sidebar: english_sidebar
tags: [getting-started, english]
summary: "The central page for Quick Configurations for RPCS3."
permalink: gs_quick_config
toc: false
folder: english
series: "Getting Started"
weight: 5
---
## Quick Configuration Profiles

Now that the game is in the library, we'll download some files to adjust RPCS3 for the best experience.  
Below are the quick configuration files. Download a whichever is best for your computer.  

* [[Recommended settings]](https://rb3pc.milohax.org/downloads/customconfigs/recommended.zip){:target="_blank"} - These are the settings used for the recommended specs listed in [[requirements]](https://rb3pc.milohax.org/gs_reqs#a-computer){:target="_blank"}.
* [[Minimum settings]](https://rb3pc.milohax.org/downloads/customconfigs/minimum.zip){:target="_blank"} - These are the settings used for the minimum specs listed in [[requirements]](https://rb3pc.milohax.org/gs_reqs#a-computer){:target="_blank"}.

## Applying A Profile
To use these, **click on the settings you want to download then extract the ZIP archives in the folder where you extracted RPCS3**. It should combine folders automatically if you did it right.  
In the GIF example below, the "Recommended" requirements settings archive (recommended.zip) was downloaded and its contents were moved into RPCS3's folder.

![A GIF of "config" and "dev_hdd0" from "recommended.zip" being moved into its proper location in RPCS3's folder.](https://rb3pc.milohax.org/images/cust/quickconf.gif "Recommended.zip")

The only things left to do are:
* **[[setting up your instruments and controllers]](https://rb3pc.milohax.org/ctrls){:target="_blank"}**
* **[[setting up a microphone to sing with]](https://rb3pc.milohax.org/gs_mics){:target="_blank"}**
* **[[creating an RPCN account to play online and use leaderboards]](https://rb3pc.milohax.org/rpcn_intro){:target="_blank"}**

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#affectedsettings">Affected Settings</a>
                            </h4>
                        </div>
                        <div id="affectedsettings" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <p>If you need any more information about what these settings are changing:</p>
<h3 id="recommended">Recommended</h3>
<ul>
<li><strong>CPU</strong>:
<ul>
<li>SPU Block Size: Mega</li>
</ul>
</li>
<li><strong>GPU</strong>:
<ul>
<li>Write Color Buffers</li>
<li>Framelimit: Off</li>
<li>Resolution Scale: 150% (1920x1080)</li>
<li>Anisotropic Filter: 16x</li>
<li>ZCULL Accuracy: Relaxed (Fastest)</li>
<li>VSync Enabled</li>
</ul>
</li>
<li><strong>Audio</strong>:
<ul>
<li>Audio Buffer Duration: 32 ms</li>
</ul>
</li>
<li><strong>Network</strong>:
<ul>
<li>Network Status: Connected</li>
<li>IP Hosts/Switches: <code>rb3ps3live.hmxservices.com=45.33.44.103</code></li>
<li>PSN Status: RPCN</li>
<li>Enable UPNP: On</li>
</ul>
</li>
<li><strong>Advanced</strong>:
<ul>
<li>Debug Console Mode: On</li>
<li>Exclusive Fullscreen Mode: Prefer Borderless fullscreen</li>
<li>Driver Wake-Up Delay: 20 µs</li>
</ul>
</li>
<li><strong>Emulator</strong>:
<ul>
<li>Show trophy popups: Off</li>
</ul>
</li>
</ul>
<h3 id="minimum">Minimum</h3>
<ul>
<li><strong>CPU</strong>:
<ul>
<li>SPU Block Size: Mega</li>
<li>Preferred SPU Threads: 2</li>
</ul>
</li>
<li><strong>GPU</strong>:
<ul>
<li>Write Color Buffers</li>
<li>Framelimit: Off</li>
<li>ZCULL Accuracy: Relaxed (Fastest)</li>
</ul>
</li>
<li><strong>Audio</strong>:
<ul>
<li>Audio Buffer Duration: 100 ms</li>
</ul>
</li>
<li><strong>Network</strong>:
<ul>
<li>Network Status: Connected</li>
<li>IP Hosts/Switches: <code>rb3ps3live.hmxservices.com=45.33.44.103</code></li>
<li>PSN Status: RPCN</li>
<li>Enable UPNP: On</li>
</ul>
</li>
<li><strong>Advanced</strong>:
<ul>
<li>Debug Console Mode: On</li>
<li>Exclusive Fullscreen Mode: Prefer Borderless fullscreen</li>
<li>Driver Wake-Up Delay: 40 µs</li>
</ul>
</li>
<li><strong>Emulator</strong>:
<ul>
<li>Show trophy popups: Off</li>
</ul>
</li>
</ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

## Experimental Low End Configuration
* [[Potato Settings]](https://rb3pc.milohax.org/downloads/customconfigs/potato.zip){:target="_blank"} - The same as the minimum configuration but using OpenGL, meant for computers with integrated graphics. Double this up with black backgrounds and your potato might boot Rock Band 3 on RPCS3. **This is not recommended!**

{% include custom/series_getting_started_next.html %}

{% include links.html %}