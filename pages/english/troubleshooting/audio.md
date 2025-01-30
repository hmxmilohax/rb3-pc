---
title: Audio
sidebar: english_sidebar
permalink: trbl_audio
folder: english
tags: [troubleshooting, english]
summary: "How to deal with common audio issues."
toc: false
---

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mic-echo">There's a distracting echo when playing vocals.</a>
                            </h4>
                        </div>
                        <div id="mic-echo" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<li>Lower the <strong>Audio Buffer Duration</strong> slider in the <a href="https://carlmylo.github.io/docu-rpcs3/custom_config_aud" target="_blank">[Audio tab when setting up a Custom Configuration]</a> for Rock Band 3.</li>
<li>Deactivate pitch correction in Rock Band 3.
<ul>
<li>To do this, go to <code>Menu &gt; Options &gt; Vocal Options &gt; Pitch Correction</code></li>
</ul>
</li>
</ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                                        <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mic-isnt-working">My microphone is not working.</a>
                            </h4>
                        </div>
                        <div id="mic-isnt-working" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<li><a href="https://www.majorgeeks.com/content/page/how_to_rename_your_sound_input_or_output_devices.html" target="_blank">[Rename your microphone]</a> to something else like “Mic 1” in Windows’ settings. Accents may cause issues with RPCS3.</li>
<li>Make sure you’re setting the microphone in Rock Band 3’s Custom Configuration and not RPCS3’s Global Custom Configuration.
<ul>
<li><img src="https://carlmylo.github.io/docu-rpcs3/images/trbl/audio/custnotglobal.png" alt="A screenshot of RPCS3's right click menu, showing &quot;Change Custom Configuration highlighted" title="RPCS3"></li>
</ul>
</li>
</ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->