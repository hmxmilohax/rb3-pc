---
title: "Converting Clone Hero/YARG songs to Rock Band 3"
sidebar: customs_sidebar
permalink: customs_CHtoPS3
folder: english
tags: [customs, english]
summary: "How to convert Clone Hero/YARG songs to PS3/RPCS3 Format"
series: "Converting Customs"
weight: 3
toc: false
---

<span style="font-size:x-large;">DISCLAIMER - READ BEFORE CONTINUING</span>

Do this as a **last resort** if the charts you want to convert were specifically made for PC clone games (Clone Hero/YARG). If the chart originally existed in RB format, whether it be official DLC or customs, **get that first and follow the main guide at the top!**

**Failure to do so will result in lost metadata** associated with the original song package, including:
* Incompatibility with any song upgrades in RB3DX
	* Keys, Pro Guitar, Harmonies, & chart fixes to legacy RB songs that didn't have them
* Incompatibility with online play and leaderboards
* Animation data such as character lipsync will be lost

Should you decide to ignore the disclaimer and proceed, you will be **refused any support** from the MiloHax Discord if you run into any issues.
**YOU HAVE BEEN WARNED!**

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#you-better-read-it">I have read the disclaimer. Let me at it!</a>
                            </h4>
                        </div>
                        <div id="you-better-read-it" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<h4 id="section">1.</h4>
<p>After downloading the charts you want, open Onyx and select <code>Batch recompile</code>.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatch.png" alt="A screenshot of Onyx's main screen. A cursor hovers over &quot;Batch recompile.&quot;" title="Onyx Console"></p>
<h4 id="section-1">2.</h4>
<p>At the top of the Batch Recompile window, click on <code>Edit</code> then <code>Preferences</code>.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefs.png" alt="A screenshot of Onyx's Batch Recompile. The &quot;Edit&quot; menu has been expanded and &quot;Preferences&quot; is selected." title="Batch Recompile"></p>
<h4 id="section-2">3.</h4>
<p>Switch to the <code>Rock Band</code> tab.<br>
Change to <code>Magma optional</code>.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefsrb.png" alt="A screenshot of Onyx's Preferences window. Under the &quot;Rock Band&quot; tab, &quot;Magma optional&quot; is selected." title="Batch Recompile"></p>
<h4 id="section-3">4.</h4>
<p>You will be warned about this.<br>
Click <code>OK</code>.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchwarn.png" alt="A screenshot of a warning from Onyx. It warns that disabling Magma will crash Rock Band." title="Magma Warning"></p>
<h4 id="section-4">5.</h4>
<p>Switch to the <code>Audio</code> tab.<br>
Lower the <code>OGG Vorbis quality</code> to <code>3.00</code>.<br>
After that, click on <code>Save</code>.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefsaud.png" alt="A screenshot of Onyx's Preferences window. Under the &quot;Audio&quot; tab, &quot;Magma optional&quot; is selected." title="Batch Recompile"></p>
<h4 id="section-5">6.</h4>
<p>Drag and drop the folder(s) containing the songs you want to convert into the <code>Batch recompile</code> window.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchdrag.gif" alt="A GIF of customs in Clone Hero format being dragged and dropped into the &quot;Songs&quot; tab of Onyx's Batch Recompile." title="Batch Recompile"></p>
<h4 id="section-6">7.</h4>
<p>Switch to the <code>RB3</code> tab.<br>
<em>(Optional)</em> Most Clone Hero songs only have Guitar charted. You may wish to copy it over to other instruments such as Bass/Keys to allow more people to play it at the same time.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchparts.png" alt="A screenshot of Onyx's Batch Recompile window. Under the &quot;RB3&quot; tab, &quot;Fill empty parts with first guitar, then drums&quot; is selected." title="Batch Recompile"></p>
<h4 id="section-7">8.</h4>
<p>To finish, select either <code>Create PS3 PKG files</code> or <code>Create PS3/RPCS3 folders</code>.</p>
<ul>
<li><code>Create PS3/RPCS3 folders</code> is recommended for RPCS3 users and PS3 users who know how to use FTP. It is <strong>much</strong> faster than PKG creation.</li>
<li><code>Create PS3 PKG files</code> is only recommended for PS3 users who can only use USB flash drives to add more songs.</li>
</ul>
<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#folders">Create PS3/RPCS3 folders</a></li>
    <li><a href="#pkg">Create PS3 PKG files</a></li>
</ul>
  <div class="tab-content">
<div class="tab-pane active" id="folders">
<p><img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchfolders.png" alt="A screenshot of Onyx's Batch Recompile window. Under the &quot;RB3&quot; tab, &quot;Create PS3/RPCS3 folders&quot; is selected." title="Batch Recompile"></p>
<h4 id="section">9.</h4>
<p>Navigate to your RPCS3 folder and select the <code>dev_hdd0</code> folder.<br>
If you're going to be installing to a PS3 via FTP, select the most convenient folder.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/savefolder.png" alt="A screenshot of a file browser window. A location is set and the cursor is over &quot;Select Folder.&quot;" title="Select Folder"></p>
<h4 id="section-1">10.</h4>
<p>It should successfully convert and auto-install into your RPCS3 directory, ready to play.<br>
If using RB3DX, you can even do this while the game is running. Within RB3, select:<br>
<code>Options &gt; Extras &gt; Refresh Library</code> to reload your song list.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchfinish.png" alt="A screenshot of Onyx's Batch Recompile Task tab. It is showing an in-progress conversion." title="Batch Recompile"></p>
</div></div>
<div class="tab-pane" id="pkg">
<p><img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchpkg.png" alt="A screenshot of Onyx's Batch Recompile window. Under the &quot;RB3&quot; tab, &quot;Create PS3/RPCS3 folders&quot; is selected." title="Batch Recompile"></p>
<h4 id="section">9.</h4>
<p>Select where you would like to save the PKG file(s) and give it(them) a name.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/savepkgfolder.png" alt="A screenshot of a file browser window. A location is set and the cursor is over &quot;Select Folder.&quot;" title="Select Folder"></p>
<h4 id="section-1">10.</h4>
<p>It should successfully convert and a PKG file(s) will be created, ready to install.<br>
Simply install it(them) like any other PKG.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchfinish.png" alt="A screenshot of Onyx's Batch Recompile Task tab. It is showing an in-progress conversion." title="Batch Recompile"></p>
</div>
</ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

{% include custom/series_customs_next.html %}

{% include links.html %}