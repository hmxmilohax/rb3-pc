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

<span style="font-size:x-large;">Should you decide to ignore the disclaimer and proceed, you will be **refused any support** from the MiloHax Discord if you run into any issues.
**YOU HAVE BEEN WARNED!**</span>

#### 1.
After downloading the charts you want, open Onyx and select `Batch recompile`.  
![A screenshot of Onyx's main screen. A cursor hovers over "Batch recompile."](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatch.png "Onyx Console")

#### 2.
At the top of the Batch Recompile window, click on `Edit` then `Preferences`.  
![A screenshot of Onyx's Batch Recompile. The "Edit" menu has been expanded and "Preferences" is selected.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefs.png "Batch Recompile")

#### 3.
Switch to the `Rock Band` tab. 
Change to `Magma optional`.  
![A screenshot of Onyx's Preferences window. Under the "Rock Band" tab, "Magma optional" is selected.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefsrb.png "Batch Recompile")

#### 4.
You will be warned about this.  
Click `OK`.  
![A screenshot of a warning from Onyx. It warns that disabling Magma will crash Rock Band.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchwarn.png "Magma Warning")

#### 5.
Switch to the `Audio` tab. 
Lower the `OGG Vorbis quality` to `3.00`.  
After that, click on `Save`.  
![A screenshot of Onyx's Preferences window. Under the "Audio" tab, "Magma optional" is selected.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefsaud.png "Batch Recompile")

#### 6.
Drag and drop the folder(s) containing the songs you want to convert into the `Batch recompile` window.  
![A GIF of customs in Clone Hero format being dragged and dropped into the "Songs" tab of Onyx's Batch Recompile.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchdrag.gif "Batch Recompile")

#### 7.
Switch to the `RB3` tab.  
*(Optional)* Most Clone Hero songs only have Guitar charted. You may wish to copy it over to other instruments such as Bass/Keys to allow more people to play it at the same time.  
![A screenshot of Onyx's Batch Recompile window. Under the "RB3" tab, "Fill empty parts with first guitar, then drums" is selected.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchparts.png "Batch Recompile")

#### 8.
To finish, select either `Create PS3 PKG files` or `Create PS3/RPCS3 folders`.  
* `Create PS3/RPCS3 folders` is recommended for RPCS3 users and PS3 users who know how to use FTP. It is **much** faster than PKG creation.
* `Create PS3 PKG files` is only recommended for PS3 users who can only use USB flash drives to add more songs.

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#folders" data-toggle="tab">Create PS3/RPCS3 folders</a></li>
    <li><a href="#pkg" data-toggle="tab">Create PS3 PKG files</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="folders">
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

</div>
<div role="tabpanel" class="tab-pane" id="pkg">
<p><img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchpkg.png" alt="A screenshot of Onyx's Batch Recompile window. Under the &quot;RB3&quot; tab, &quot;Create PS3/RPCS3 folders&quot; is selected." title="Batch Recompile"></p>
<h4 id="section">9.</h4>
<p>Select where you would like to save the PKG file(s) and give it(them) a name.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/savepkgfolder.png" alt="A screenshot of a file browser window. A location is set and the cursor is over &quot;Select Folder.&quot;" title="Select Folder"></p>
<h4 id="section-1">10.</h4>
<p>It should successfully convert and a PKG file(s) will be created, ready to install.<br>
Simply install it(them) like any other PKG.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchfinish.png" alt="A screenshot of Onyx's Batch Recompile Task tab. It is showing an in-progress conversion." title="Batch Recompile"></p>

</div>
</div>

{% include custom/series_customs_next.html %}

{% include links.html %}