---
title: "Deleting songs from packs"
sidebar: customs_sidebar
permalink: customs_deleting
folder: english
tags: [customs, english]
summary: "How to delete individual songs from a pack."
series: "Converting Customs"
weight: 5
---

Rock Band 3 can delete a song in-game. However, if a song is part of a pack, it'll delete that entire pack as well.  
![A screenshot from Rock Band 3, warning the user that they're about to delete many songs from the library.](https://rb3pc.milohax.org/images/xtra/customs/rb3delwarn.png "Delete song")

The best way to remove a song from a pack is through Nautilus' "Quick Pack Editor."

1\. Open Nautilus and select `Quick Pack Editor`.  
![A screenshot of Nautilus. A cursor hovers over "Quick Pack Editor."](https://rb3pc.milohax.org/images/xtra/customs/nautilushomepack.png "Nautilus")

2\. Open a file browser window and navigate to the pack folder that contains the song you want to remove and look for the `songs.dta` file.  
It will usually be in `dev_hdd0\game\BLUS30463\USRDIR\[PACKNAME]\songs`).
![A screenshot of a file browser window. "songs.dta" is selected.](https://rb3pc.milohax.org/images/xtra/customs/findfolder.png "songs")

3\. Drag the `songs.dta` file into the `Quick Pack Editor`.  
Select the songs you want to remove then click `Remove selected`.  
When you're done, click `Save` to lock your changes in.  
![A GIF of a "songs.dta" file being dragged and dropped into Nautilus' Quick Pack Editor.](https://rb3pc.milohax.org/images/xtra/customs/nautiluspackdrag.gif "Quick Pack Editor")

4.\. Even though the song is deleted from the `songs.dta` file, they will still take up space.  
You have to delete the song's corresponding folder as well.  
![A screenshot of a file browser window. Multiple songs are selected and the cursor hovers over a popup menu option that says "Delete."](https://rb3pc.milohax.org/images/xtra/customs/packdelfolder.png "songs")

{% include custom/series_customs_next.html %}

{% include links.html %}