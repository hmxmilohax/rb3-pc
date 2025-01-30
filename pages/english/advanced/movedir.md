---
title: Move Game Files
sidebar: english_sidebar
permalink: adv_movedir
folder: english
tags: [advanced, english]
summary: "How to move Rock Band 3's files to a different location than the emulator."
toc: false
---

<div markdown="span" class="alert alert-danger" role="alert"><i class="fa fa-exclamation-circle"></i> <b>This is meant for advanced users only. **Your game and installation may break!** Proceed with caution! </b> {{include.content}}</div>

If Rock Band 3's files are taking up too much space on your main drive, you can move them to a different drive while keeping RPCS3 itself on your main drive.

Make sure RPCS3 is closed before starting this.

First, create a folder where all of this stuff will be moved to.

I'll be naming the folder "RPCS3 Directory" in this tutorial.

![A screenshot of the folder created, which is named "RPCS3 Directory" in this tutorial.) en la categoría de 7-Zip.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirfolder.png "RPCS3 Directory")

Now, back in the folder RPCS3 is in, cut the following folders:
* `dev_bdvd`
* `dev_flash`
* `dev_flash2`
* `dev_flash3`
* `dev_hdd0`
* `dev_hdd1`
* `dev_usb000`
* `games`

![A screenshot of the folders listed being cut.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dircut.png "Cut (CTRL+X")

Paste them inside of the folder you created.

![A GIF of the folders that were cut being pasted into the "RPCS3 Directory" folder.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirpaste.gif "RPCS3 Directory")

When it finishes pasting, reopen RPCS3.

Click on `Manage > Virtual File System`

![A screenshot of RPCS3, with the user hovering over "Virtual File System", under the "Manage" category.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirrpcs3.png "RPCS3 Directory")

In the Virtual File System window, click on the `+` symbol near the bottom right.

![A screenshot of RPCS3's Virtual File System Menu, showing the cursor hovering over the plus symbol at the bottom.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirvfsadd.png "Virtual File System")

Go to the folder you created, click on it, and then click on "`Select Folder`."

![A screenshot of RPCS3's "Choose a directory" window, selecting the created folder.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirfoldersel.png "RPCS3 Directory")

Finally, click "`Save`".

![A screenshot of RPCS3's "Choose a directory" window, selecting the created folder.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirvfssave.png "RPCS3 Directory")

That's it!

{% include links.html %}