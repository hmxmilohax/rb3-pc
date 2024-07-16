---
title: Extra - Advanced Stuff
author: Carl Mylo
date: 1000-10-02
category: English
layout: post
---

# Extra Guides

## Add more memory to Rock Band 3

### Intro

We'll be adding increased memory support to Rock Band 3 on RPCS3. This is strongly suggested and allows for better stability as well top of increasing the song limit up to 16000.

> ##### WARNING
>
> _If you downloaded and are using a [[Quick Configurations profile,]](https://rb3pc.milohax.org/english/quickconfiguration/) this is already active and you don't need to do this._
{: .block-warning  }

> ##### DANGER
>
> _You need to [[enable Debug Console Mode in the Advanced Custom Configuration tab for Rock Band 3]](https://rb3pc.milohax.org/english/customconfiguration#advanced). **Not doing this will cause your game to crash immediately after adding this file.**_
{: .block-danger  }

### How To

* First, you'll need to [[download the file to enable increased memory support. Click here to download it]](https://github.com/hmxmilohax/rb3-pc/raw/main/config/customconfig/memory.zip)

**After downloading the .zip file, extract its contents and move them to RPCS3's folder. It should combine folders automatically if you did it right.**

In the GIF example below, the `devhdd_0` folder from the archive (memory.zip) was extracted and its contents were moved into RPCS3's folder.

![A GIF of "dev_hdd0" from "memory.zip" being moved into its proper location in RPCS3's folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/himem.gif "memory.zip")

That's it! Enjoy the increased stability and extra song space!


## How to properly add customs to Rock Band 3

[[Click here to be taken to the definitive guide on how to add customs to your installation of Rock Band 3.]](https://docs.google.com/document/d/1YwGNT1oPUgfek-p3sLCZv4b-PsO8Yv9eobx5fV6W2vQ/)

# Danger Zone

## Intro

> ##### DANGER
>
> _Below are tweaks and adjustments that are meant for advanced users only. **Your game and installation may break!** Proceed with caution!_
{: .block-danger  }

## Add custom textures to Rock Band 3 Deluxe

### How To

[[Click here to be taken to the definitive guide on how to add custom textures to Rock Band 3 Deluxe.]](https://docs.google.com/document/d/1ELUI8Q2W7PH9tdugeKnsjhqa-IH3T-oy6uGTDY_8z30/)


## Move Game Files

### Intro:

If Rock Band 3's files are taking up too much space on your main drive, you can move them to a different drive while keeping RPCS3 itself on your main drive.

Make sure RPCS3 is closed before starting this.

First, create a folder where all of this stuff will be moved to.

I'll be naming the folder "RPCS3 Directory" in this tutorial.

![A screenshot of the folder created, which is named "RPCS3 Directory" in this tutorial.) en la categoría de 7-Zip.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirfolder.png "RPCS3 Directory")

Now, back in the folder RPCS3 is in, cut the following folders:
* dev_bdvd
* dev_flash
* dev_flash2
* dev_flash3
* dev_hdd0
* dev_hdd1
* dev_usb000
* games

![A screenshot of the folders listed being cut.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dircut.png "Cut (CTRL+X")

Paste them inside of the folder you created.

![A GIF of the folders that were cut being pasted into the "RPCS3 Directory" folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirpaste.gif "RPCS3 Directory")

When it finishes pasting, reopen RPCS3.

Click on Manage > Virtual File System

![A screenshot of RPCS3, with the user hovering over "Virtual File System", under the "Manage" category.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirrpcs3.png "RPCS3 Directory")

In the Virtual File System window, click on the `+` symbol near the bottom right.

![A screenshot of RPCS3's Virtual File System Menu, showing the cursor hovering over the plus symbol at the bottom.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirvfsadd.png "Virtual File System")

Go to the folder you created, click on it, and then click on "Select Folder."

![A screenshot of RPCS3's "Choose a directory" window, selecting the created folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirfoldersel.png "RPCS3 Directory")

Finally, click "Save".

![A screenshot of RPCS3's "Choose a directory" window, selecting the created folder.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirvfssave.png "RPCS3 Directory")

That's it!