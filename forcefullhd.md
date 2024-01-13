We'll be forcing Rock Band 3 to run in full HD (1920x1080). Please be aware that this requires more graphical power so if you experience degraded performance, undo these changes.

Please note that this mostly affects post processing, shadows, and aliasing with venue FPS set below 30.

Here is a comparison. Rock Band 3 was targeting 1080p with "Resolution Scale" adjusted to match.

![A screenshot Rock Band 3, with the left screenshot showing severe aliasing labeled 720p, and a cleaner screenshot labeled 1080p.](images/xtra/fullhd/comparison.png "Comparison")

There are two ways to do this. We'll go over the easy way first.

### The Easy Way:

Click on "View" > "Game Categories" and then enable "Game Data."

![A screenshot RPCS3, with the user's cursor hovering over Game Data](images/xtra/fullhd/gamedataon.png "Game Data")


When the new entries show up, right click on Rock Band 3's Game Data entry. Notice that the "Supported Resolutions" for it are unknown, which tricks RPCS3 into letting you set a higher resolution.

![A screenshot RPCS3, with the user's cursor hovering over "Change Custom Configuration", which popped up from right clicking Rock Band 3's PS3 Game Data entry.](images/xtra/fullhd/gamedataconf.png "Game Data")

In the GPU tab of the Custom Configuration Window, change "Default Resolution" to 1920x1080 then click "Apply."  

![A screenshot Rock Band 3's Custom Configuration settings in the GPU tab, with the user's cursor hovering over "1920x080".](images/xtra/fullhd/gpu1080.png "Game Data")

### The "Hard" Way:

In RPCS3, right click on Rock Band 3 and click on "Open Custom Config Folder."  

![A screenshot RPCS3, with the user's cursor hovering over "Open Custom Config Folder", which popped up from right clicking Rock Band 3's Disc Game entry.](images/xtra/fullhd/confrc.png "Game Data")

Now open the `config_BLUS30463.yml` file with your default text editor like Notepad, SublimeText, or Notepad++.

![A screenshot Windows Explorer, with the user's cursor hovering over "Edit in Notepad", which popped up from right clicking config_BLUS30463.yml.](images/xtra/fullhd/ymlopen.png "config_BLUS30463.yml")

In your text editor, search for "`Resolution:`".  

![A screenshot of Notepad with config_BLUS30463.yml open. There's a search popup with "Resolution" searched with a result found.](images/xtra/fullhd/ymledit.png "config_BLUS30463.yml")

When you find it, change "`1280x720`" to "`1920x1080`" and save the file.

![A screenshot of Notepad with config_BLUS30463.yml open. Resolution has been changed from 1280x720 to 1920x1080.](images/xtra/fullhd/ymleditpost.png "config_BLUS30463.yml")

### Conclusion:

That's it. Just note that any time you change anything on the GPU tab, it might reset back to 1280x720 so you'll have to do this again.