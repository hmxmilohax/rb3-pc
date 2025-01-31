---
title: Common
sidebar: english_sidebar
permalink: trbl_common
folder: english
tags: [troubleshooting, english]
summary: "How to deal with common issues."
toc: false
---

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#bugged-textures">My character has bugged textures/graphics.</a>
                            </h4>
                        </div>
                        <div id="bugged-textures" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul><p><img src="https://carlmylo.github.io/rb3-pc/images/trbl/common/wcb.png" alt="A screenshot of Rock Band 3, with a character displaying severe texture issues." title="Graphical issues"></p>
<p>You did not follow the guide and did not <a href="https://carlmylo.github.io/rb3-pc/custom_config#custom-configuration" target="_blank"><strong>[enable Write Color Buffers in the GPU section]</strong></a>.</p>
<p><img src="https://carlmylo.github.io/rb3-pc/images/trbl/common/wcbon.png" alt="A screenshot of Rock Band 3's GPU custom settings, highlighting Write Color Settings highlighted in green with a dotted outline." title="GPU"></p></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#flying-instruments">My character's items are teleporting.</a>
                            </h4>
                        </div>
                        <div id="flying-instruments" class="panel-collapse collapse">
                            <div class="panel-body">
<ul><p><img src="https://carlmylo.github.io/rb3-pc/images/trbl/common/flyinst.png" alt="A screenshot of Rock Band 3, with a character's hat teleporting off of his head."><br>
This is an issue that happens on real hardware (PS3) but is MUCH worse on RPCS3.<br>
Thankfully, there is a patch to fix all of this!<br>
<a href="https://carlmylo.github.io/rb3-pc/trbl_teleprob" target="_blank">[Click here for more information]</a>.</p></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#online-i-crash-when-joining-sessionssearching-for-players">[Online] I crash when joining sessions/searching for players.</a>
                            </h4>
                        </div>
                        <div id="online-i-crash-when-joining-sessionssearching-for-players" class="panel-collapse collapse">
                            <div class="panel-body">
<ul><p>Your router may have issues with RPCS3’s UPNP feature. Go to Rock Band 3’s Custom Configuration <a href="https://carlmylo.github.io/rb3-pc/custom_config_net" target="_blank">[Network section]</a>, and disable “Enable UPNP.”</p>
<p>You will need to <a href="https://www.noip.com/support/knowledgebase/general-port-forwarding-guide" target="_blank">[to set up port forwarding in your router's control panel]</a>.</p></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#my-game-feels-off">My game feels off.</a>
                            </h4>
                        </div>
                        <div id="my-game-feels-off" class="panel-collapse collapse">
                            <div class="panel-body">
<ul><p>Calibrate your game in Rock Band 3’s System Settings. Disable “Dolby Digital” if it’s enabled as well.<br>
You can access the system menu by going to:<br>
<code>Menu &gt; Options &gt; System Settings</code></p></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#my-audio-is-stutteringchoppy">My audio is stuttering/choppy.</a>
                            </h4>
                        </div>
                        <div id="my-audio-is-stutteringchoppy" class="panel-collapse collapse">
                            <div class="panel-body">
<ul><p><iframe src="https://www.youtube.com/embed/UoCMEQbNThs" width="420" height="315">&#10;</iframe><br> 
Increase “Audio Buffer Duration” as mentioned in <a href="https://carlmylo.github.io/rb3-pc/custom_config#configuration" target="_blank">[the Audio tab of Rock Band 3’s Custom Configuration]</a> until the stuttering stops. 100 ms is a great starting point for low end computers.<br>
Alternatively, you can check the general performance issues section right below this.</p></ul>
                            </div></div></div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#general-performance-issues">General performance issues</a>
                            </h4>
                        </div>
                        <div id="general-performance-issues" class="panel-collapse collapse">
                            <div class="panel-body">
<ul>
<li>Set your computer to the <a href="https://help.ableton.com/hc/en-us/articles/115000211304-Using-the-High-performance-power-plan-Windows-" target="_blank">[High Performance power plan]</a>.</li>
<li>Go back to the <a href="https://carlmylo.github.io/rb3-pc/custom_config#custom-configuration" target="_blank">[Custom Configuration setup section]</a> and apply suggested low performance tweaks.</li>
<li>Disable Post Effects in Deluxe Settings.
<ul>
<li><code>Menu &gt; Options &gt; Deluxe Settings &gt; Graphics</code></li>
</ul>
</li>
<li>If your motherboard has a Realtek audio chip (most computers), try <a href="https://www.realtek.com/Download/List?cate_id=593&menu_id=298" target="_blank">[installing the latest driver]</a>. This is a <a href="https://github.com/RPCS3/rpcs3/issues/14648" target="_blank">[known issue]</a> where using the default “High Definition Audio” driver doesn’t use all threads.</li>
<li>Close out the dedicated Discord client and open it up in your browser or on your phone. You can also try an alternative Discord client <a href="https://github.com/Vencord/Vesktop" target="_blank">[like Vesktop]</a>, but I claim no responsibility for your Discord account.</li></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

{% include links.html %}