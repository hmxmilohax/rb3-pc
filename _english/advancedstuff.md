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
> _If you downloaded and are using a [[Quick Configurations profile,]](https://hmxmilohax.github.io/rb3-pc/english/quickconfiguration/) this is already active and you don't need to do this._
{: .block-warning  }

> ##### DANGER
>
> _You need to [[enable Debug Console Mode in the Advanced Custom Configuration tab for Rock Band 3]](https://hmxmilohax.github.io/rb3-pc/english/customconfiguration#advanced). **Not doing this will cause your game to crash immediately after adding this file.**_
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

## Force Full HD

### Intro

We'll be forcing Rock Band 3 to run in full HD (1920x1080). Please be aware that this requires more graphical power so if you experience degraded performance, undo these changes.

Please note that this mostly affects post processing, shadows, and aliasing with venue FPS set below 35. **Most people won't be able to tell the difference.**

Here is a comparison. Rock Band 3 was targeting 1080p with "Resolution Scale" adjusted to match, so both are outputting 1080p.

![A screenshot Rock Band 3, with the left screenshot showing severe aliasing labeled 720p, and a cleaner screenshot labeled 1080p.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/fullhd/comparison.png "Comparison")

There are two ways to do this. We'll go over the easy way first.

### The easy way

Click on "View" > "Game Categories" and then enable "Game Data."

![A screenshot RPCS3, with the user's cursor hovering over Game Data](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/fullhd/gamedataon.png "Game Data")


When the new entries show up, right click on Rock Band 3's Game Data entry. Notice that the "Supported Resolutions" for it are unknown, which tricks RPCS3 into letting you set a higher resolution.

![A screenshot RPCS3, with the user's cursor hovering over "Change Custom Configuration", which popped up from right clicking Rock Band 3's PS3 Game Data entry.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/fullhd/gamedataconf.png "Game Data")

In the GPU tab of the Custom Configuration Window, change "Default Resolution" to 1920x1080 then click "Apply."  

![A screenshot Rock Band 3's Custom Configuration settings in the GPU tab, with the user's cursor hovering over "1920x080".](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/fullhd/gpu1080.png "Game Data")

### The "hard" way

In RPCS3, right click on Rock Band 3 and click on "Open Custom Config Folder."  

![A screenshot RPCS3, with the user's cursor hovering over "Open Custom Config Folder", which popped up from right clicking Rock Band 3's Disc Game entry.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/fullhd/confrc.png "Game Data")

Now open the `config_BLUS30463.yml` file with your default text editor like Notepad, SublimeText, or Notepad++.

![A screenshot Windows Explorer, with the user's cursor hovering over "Edit in Notepad", which popped up from right clicking config_BLUS30463.yml.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/fullhd/ymlopen.png "config_BLUS30463.yml")

In your text editor, search for "`Resolution:`".  

![A screenshot of Notepad with config_BLUS30463.yml open. There's a search popup with "Resolution" searched with a result found.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/fullhd/ymledit.png "config_BLUS30463.yml")

When you find it, change "`1280x720`" to "`1920x1080`" and save the file.

![A screenshot of Notepad with config_BLUS30463.yml open. Resolution has been changed from 1280x720 to 1920x1080.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/fullhd/ymleditpost.png "config_BLUS30463.yml")

### Conclusion

That's it. Just note that any time you change anything on the GPU tab, it might reset back to 1280x720 so you'll have to do this again.

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

## AshCentral Room Codes

### Intro

Video Version:  
[![A thumbnail of the video version of this section of the tutorial.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/vidthumb.png)](https://youtu.be/pfEUYhzw1ds "Rock Band 3 Multiplayer with Room Codes! [RPCS3] - YouTube")

**Room Codes are only useful for setting up private lobbies with console players. If you're inviting someone who's on an emulator, use the "Invite Friend" option in the "Play on AshCentral" menu!**

### Setting up for room codes on AshCentral

To use the room code system on AshCentral, **make sure RPCS3 is set to connect to AshCentral**. **Join the** [[**Milohax Discord server**]](https://rb3dx.neocities.org/discord) and **go to** the **[\[#ashcentral-status\]](https://discord.com/channels/961352072140324924/1153056600030973992)** channel.

**Copy the information into RPCS3** like mentioned in the [**[network]**](https://hmxmilohax.github.io/rb3-pc/english/customconfiguration/#network) section of the guide.

Once you've done that, **go to** [**[AshCentral's website]**](https://gocentral.rocks/) **to register an account**.

[![A screenshot of AshCentral's website, GoCentral.Rocks, with the "Register" option from the "Account" subsection being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/splash.png)](https://gocentral.rocks/ "GoCentral")

**Register your account.**

[![A screenshot of AshCentral's website, GoCentral.Rocks, in the register subpage, with "Register" being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/register.png)](https://gocentral.rocks/register "GoCentral - Register")

**When you register your account**, you'll be prompted to **log in**. Do so.

[![A screenshot of AshCentral's website, GoCentral.Rocks, in the login subpage, with "Login" being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/login.png)](https://gocentral.rocks/login "GoCentral - Login")

You'll be taken back to the front page. **Under your account's name, you should see "Settings"**. Click on that.

[![A screenshot of AshCentral's website, GoCentral.Rocks, with the "Settings" option from the user name's subsection being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/splashsettings.png)](https://gocentral.rocks/settings "GoCentral")

**In the settings page, you'll see a "Link Account" option. Click on that.**

[![A screenshot of AshCentral's website, GoCentral.Rocks, in the account information subpage, with "Link Account" being moused over](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/settings.png)](https://gocentral.rocks/link "GoCentral")

This will take you to a page to type in an account linking code. **Leave this page open.**

[![A screenshot of AshCentral's website, GoCentral.Rocks, in the account linking subpage, with "Link" being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/link.png)](https://gocentral.rocks/link "GoCentral")

**Start up Rock Band 3**.

Once it launches, **go to the main options menu.**

![A screenshot of Rock Band 3, with Options being highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/options.png "Rock Band 3: Options")

**Go to the extras menu.**

![A screenshot of Rock Band 3, with extras being highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/extras.png "Rock Band 3: Extras")

**Go to "Account-linking code."**

![A screenshot of Rock Band 3, with "Account-Linking Code" being highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/accountlinkingcode.png "Rock Band 3: Account-Linking Code")

**You should see the code now.**

![A screenshot of Rock Band 3, telling the user to copy the code at the bottom into AshCentral.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/code.png "Rock Band 3: Code Here")

Now, **copy the code into Gocentral.Rocks, then click "Link." After that, restart Rock Band 3.**

![A screenshot of AshCentral's website, GoCentral.Rocks, in the account linking subpage, with "Link" being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/link.png "GoCentral - Link Account")

You'll be taken back to the front page. **Under your account's name, you should see "Settings"**. Click on that.

[![A screenshot of AshCentral's website, GoCentral.Rocks, with the "Settings" option from the user name's subsection being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/splashsettings.png)](https://gocentral.rocks/settings "GoCentral")

If you did everything correctly, **you should see more information for your account, including your account name, console, band name, and fans**.

![A screenshot of AshCentral's website, GoCentral.Rocks, in the account information subpage, showing new details under Rock Band 3 account.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/linked.png "GoCentral - Settings")

If the website didn't find anything, you may have mistyped the code. Rock Band 3's font may be a bit hard to read so you may have to try again.

Now, let's go over hosting or joining sessions.

**First, launch Rock Band 3** (if it's not already open).

**On the front page of AshCentral, click on "Join Game"**.

[![A screenshot of AshCentral's website, GoCentral.Rocks, with the "Join Game" being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/joingame.png)](https://gocentral.rocks/sessions "GoCentral")

**Before clicking either "Host Session" or "Join Session", make sure to press "Play on AshCentral" in Rock Band 3's options menu.**

![A screenshot of Rock Band 3, with "Play on AshCentral" being highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/ashcentral.png "Rock Band 3: Play on AshCentral")


### Hosting Sessions

**Click on "Host Session"** on GoCentral.Rocks.
[![A screenshot of AshCentral's website, GoCentral.Rocks, on the "Join Game" subpage, with "Host Session" being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/hostsession.png)](https://gocentral.rocks/sessions/ "GoCentral - Host Session")

You will get a code. **Send this code to those you want to join your session.**

[![A screenshot of AshCentral's website, GoCentral.Rocks, on the "Host Session" subpage, with a session code and a countdown displayed.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/hostroom.png)](https://gocentral.rocks/sessions/host "GoCentral - Host Session")

Now, **in Rock Band 3, go to "Play Now", then "Quickplay", then "Find AshCentral Players"**

![A screenshot of Rock Band 3, with "Find AshCentral Players" highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/findashcentralplayers.png "Rock Band 3: Find AshCentral Players")

You should see invited players connected to your lobby.
![A screenshot of Rock Band 3, in an online lobby.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/hostlobby.png "Rock Band 3: Find AshCentral Players")

### Joining Sessions

**Click on "Join Session"** on GoCentral.Rocks.
[![A screenshot of AshCentral's website, GoCentral.Rocks, on the "Join Game" subpage, with "Join Session" being moused over.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/joinsession.png)](https://gocentral.rocks/sessions/ "GoCentral - Join Session")

**Enter the session code you were sent.**

[![A screenshot of AshCentral's website, GoCentral.Rocks, on the "Join Session" subpage, asking the user for a session code.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/joinroom.png)](https://gocentral.rocks/sessions/join "GoCentral - Join Session")

Now, **in Rock Band 3, go to "Play Now", then "Quickplay", then "Find AshCentral Players"**

![A screenshot of Rock Band 3, with "Find AshCentral Players" highlighted.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/findashcentralplayers.png "Rock Band 3: Find AshCentral Players")

You should connect to the lobby you were invited to.
![A screenshot of Rock Band 3, in an online lobby.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/joinlobby.png "Rock Band 3: Finding AshCentral Players")

Again, **remember to press "Play on AshCentral" in Rock Band 3 before joining or hosting a session on GoCentral.Rocks.**