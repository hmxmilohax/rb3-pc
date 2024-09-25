---
title: Quick Configuration
sidebar: english_sidebar
tags: [getting-started, english]
summary: "The central page for Quick Configurations for RPCS3."
permalink: gs_quick_config
toc: false
folder: english
series: "Getting Started"
weight: 6
---

These files are meant for those that just want to play with minimal setup. It is still strongly suggested that you do [[custom configuration]](https://rb3pc.milohax.org/custom_config){:target="_blank"} to tweak to what's best for your computer.  
[[**Rock Band 3 Deluxe must be installed**]](https://rb3pc.milohax.org/gs_init#rock-band-3-deluxe){:target="_blank"} but if it's not already installed, you're not reading this guide and should go back and read it.  

## Quick Configuration Profiles

Below are the quick configuration files. Download whichever is best for your computer.

* [[Recommended settings]](https://rb3pc.milohax.org/downloads/customconfigs/recommended.zip){:target="_blank"} - These are the settings used for the recommended specs listed in [[requirements]](https://rb3pc.milohax.org/gs_reqs#a-computer){:target="_blank"}.
* [[Minimum settings]](https://rb3pc.milohax.org/downloads/customconfigs/minimum.zip){:target="_blank"} - These are the settings used for the minimum specs listed in [[requirements]](https://rb3pc.milohax.org/gs_reqs#a-computer){:target="_blank"}.

## How to
To use these, **click on the settings you want to download then extract the ZIP archives in the folder where you extracted RPCS3**. It should combine folders automatically if you did it right.  
In the GIF example below, the "Recommended" requirements settings archive (recommended.zip) was downloaded and its contents were moved into RPCS3's folder.

![A GIF of "config" and "dev_hdd0" from "recommended.zip" being moved into its proper location in RPCS3's folder.](https://rb3pc.milohax.org/images/cust/quickconf.gif "Recommended.zip")

You will still have to set up [[your instruments and controllers]](https://rb3pc.milohax.org/ctrls){:target="_blank"}. Players who want to use [[microphones]](https://rb3pc.milohax.org/custom_config_aud){:target="_blank"} or [[PS3 Mustang guitars or RB3 Keyboards with dongles]](https://rb3pc.milohax.org/adv_passthrough){:target="_blank"}  will still need to configure those.

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
<li>IP Hosts/Switches: Configured for RBEnhanced</li>
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
<li>DNS: Configured for RBEnhanced</li>
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

{% include custom/series_getting_started_next.html %}

{% include links.html %}