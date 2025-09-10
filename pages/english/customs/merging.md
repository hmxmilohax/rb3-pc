---
title: "Merging Song Folders"
sidebar: customs_sidebar
permalink: customs_merging
folder: english
tags: [customs, english]
summary: "How to merge multiple song folders to reduce startup time."
series: "Converting Customs"
weight: 4
toc: false
---

Over time, you might amass a large amount of customs folders. This is a problem since, the more folders you have, the longer Rock Band 3 takes to count your songs.  
![A screenshot of Rock Band 3 loading downloaded content. It is loading 94 packages.](https://rb3pc.milohax.org/images/xtra/customs/rb3merge.png "RPCS3")  



Ideally, you should put as many songs as possible into a pack to load things efficiently.  
![A screenshot of Rock Band 3 loading downloaded content. It is loading 48 packages.](https://rb3pc.milohax.org/images/xtra/customs/rb3mergeafter.png "RPCS3")  



Thanks to Onyx, you can do this easily! It is basically the same as the earlier as [[the Xbox 360 CON to PS3/RPCS3 format tutorial]](https://rb3pc.milohax.org/customs_360toPS3).  
Before starting, keep in mind that you will temporarily need to have the original separated packs and the merged pack installed.  
Make sure you have enough space!

#### 1.
Open a file browser and navigate to where your customs are installed.  
This is normally within `dev_hdd0\game\BLUS30463\USRDIR\`.  
For PS3, you will have to transfer the folder you want to combine to your computer for processing, which may take a while.  
If you're on RPCS3, you can get there quickly by right clicking Rock Band 3 within RPCS3 then `Open Folder > Open Game Data Folder`.  
![A RPCS3 with Open Game Data Folder, within the Open Folder menu, highlighted and with a cursor over it.](https://rb3pc.milohax.org/images/xtra/customs/rpcs3gamedata.png "RPCS3")

#### 2.
Now, open Onyx Music Game Toolkit and click `Quick convert/pack`.  
![A screenshot of Onyx's main screen. A cursor hovers over "Quick convert/pack."](https://rb3pc.milohax.org/images/xtra/customs/onyxhomequick.png "Onyx Console")

#### 3.
Stay on the `RB quick convert + pack creator` tab.  
Drag and drop the folders you want to merge or click on `Add Rock Band Song` to select them.  
![A GIF of folders of customs being dragged and dropped into the "RB quick convert + pack creator" tab of Onyx.](https://rb3pc.milohax.org/images/xtra/customs/onyxdraganddropmerge.gif "Quick Convert")

It is also recommended to enable `Author to DTA tag` at the bottom right.  
![A screenshot of Onyx's Quick Convert screen. "Author to DTA" is highlighted and has a cursor over it.](https://rb3pc.milohax.org/images/xtra/customs/onyxauthormerge.png "Quick Convert")

#### 4.
Below the first row of gray buttons, click the first menu and select `Make Packs`.  
`Make Songs` is useless in this context since it will create loose folders.  
![A screenshot of Onyx's Quick Convert screen. "Make songs: produced a single file for each song" has been clicked and the cursor is over "Make packs: combine songs up to a maximum file size."](https://rb3pc.milohax.org/images/xtra/customs/onyxmakepacksmerge.png "Quick Convert")

#### 5.
At the bottom left:
* Choose between keeping `Encrypt .mid.edat` enabled or disabled.
  * You should **only keep this on if you're sharing a package**. Rock Band 3 Deluxe users don't need activated. It's much faster with it disabled.
* Select between either `PKG (PS3)` or `Folders (PS3)`.  
  * `Folders (PS3)` is recommended for **RPCS3 users and PS3 users** who know how to use FTP. It is **much** faster than PKG creation and can bypass the 4GB (4000 MiB) max pack size.
  * `PKG (PS3)` is only recommended for PS3 users who can only use USB flash drives to add more songs.

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#folders" data-toggle="tab">Folders (PS3)</a></li>
    <li><a href="#pkg" data-toggle="tab">PKG (PS3)</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="folders">
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxoutfoldermerge.png" alt="A screenshot of Onyx's Quick Convert screen. The cursor is selecting &quot;Folders (PS3)&quot; and &quot;Encrypted .mid.edat&quot; has been enabled." title="Quick Convert">
<h4>6.</h4>
<p><em>(Optional but highly recommended)</em><br>
By default, Onyx will generate a folder with a name based on the first (or only) song in the pack, like <code>OxxxxxSongName</code>.<br>
It's suggested to enter a custom name. Simply change <code>Combine into one new USRDIR subfolder per pack</code> to <code>Custom USRDIR subfolder</code>.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxfoldernamerpcs3merge.png" alt="A screenshot of Onyx's Quick Convert screen. The cursor is selecting &quot;Custom USRDIR subfolder&quot; where &quot;Keep original USRDIR subfolders&quot; once was." title="Quick Convert"></p>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxnamepack.png" alt="A screenshot of Onyx's USRDIR naming popup. The pack has been named &quot;my_custom_pack.&quot;" title="Quick Convert">
<h4>7.</h4>
<p><em>(Optional but highly recommended)</em><br>
Since you'll be installing things as loose folders and files, you can easily bypass the 4000 MiB (or 4GB) folder limit. You can use this to pack extra dense folders!<br>
Simply change the number at the bottom left to something absurdly high like <code>99999</code><br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxmakepackfilesize.png" alt="A screenshot of Onyx's Quick Convert screen. &quot;Max Pack Size (MiB)&quot; has been set to &quot;99999&quot;." title="Quick Convert"></p>
<h4>8.</h4>
<p>At the bottom, select the big button labeled <code>Make pack</code> (or <code>Start</code> if you used the <code>Make Songs</code> option.)<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxmakepackrpcs3merge.png" alt="A screenshot of Onyx's Quick Convert screen. The cursor is over &quot;Make 1 pack.&quot;" title="Quick Convert"></p>
<p>Navigate to your RPCS3 folder and select the <code>dev_hdd0</code> folder.<br>
If you're going to be installing to a PS3 via FTP, select the most convenient folder.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/savefolder.png" alt="A screenshot of a file browser window. &quot;dev_hdd0&quot; is selected and the cursor is over &quot;Select folder.&quot;" title="Select Folder"></p>
<p>It should successfully convert and auto-install into your RPCS3 directory, ready to play.<br>
If using RB3DX, you can even do this while the game is running. Within RB3, select:<br>
<code>Options &gt; Extras &gt; Refresh Library</code> to reload your song list.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxcreatedrpcs3merge.png" alt="A screenshot of Onyx's USRDIR naming popup. The pack has been named &quot;my_custom_pack.&quot;" title="Quick Convert"></p>

</div>
<div role="tabpanel" class="tab-pane" id="pkg">
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxoutpkgmerge.png" alt="A screenshot of Onyx's Quick Convert screen. The cursor is selecting &quot;PS3 (PS3)&quot; and &quot;Encrypted .mid.edat&quot; has been enabled." title="Quick Convert">
<h4>6.</h4>
<p><em>(Optional but highly recommended)</em><br>
By default, Onyx will generate a PKG that outputs a folder with a name based on the first (or only) song in the pack, like <code>OxxxxxSongName</code>.<br>
It's suggested to enter a custom name. Simply change <code>Combine into one new USRDIR subfolder per pack</code> to <code>Custom USRDIR subfolder</code>.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxfoldernamepkgmerge.png" alt="A screenshot of Onyx's Quick Convert screen. The cursor is selecting &quot;Custom USRDIR subfolder&quot; where &quot;Keep original USRDIR subfolders&quot; once was." title="Quick Convert"></p>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxnamepack.png" alt="A screenshot of Onyx's USRDIR naming popup. The pack has been named &quot;my_custom_pack.&quot;" title="Quick Convert">
<h4>7.</h4>
<p>At the bottom, select the big button labeled <code>Make pack</code>.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxmakepackpkgmerge.png" alt="A screenshot of Onyx's Quick Convert screen. The cursor is over &quot;Make 1 pack.&quot;" title="Quick Convert"></p>
<p>Select where you would like to save the PKG file and give it a name.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/savepkg.png" alt="A screenshot of a file browser window. The file name has been set to &quot;my_custom_pack&quot;" title="Select Folder"></p>
<p>It should successfully convert and a PKG file will be created, ready to install.<br>
Simply install it like any other PKG.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxcreatedpkgmerge.png" alt="A screenshot of Onyx's USRDIR naming popup. The pack has been named &quot;my_custom_pack.&quot;" title="Quick Convert"></p>

</div>
</div>

{% include custom/series_customs_next.html %}

{% include links.html %}