We'll be moving RPCS3's virtual file system to a separate folder to make switching between versions easier. This way, you won't have to install the same content twice.

**This is intended for advanced users.**

Make sure RPCS3 is closed before starting this.

First, create a folder where all of this stuff will be moved to.

I'll be naming the folder "RPCS3 Directory" in this tutorial.

![A screenshot of the folder created, which is named "RPCS3 Directory" in this tutorial.) en la categoría de 7-Zip.](images/xtra/dir/dirfolder.png "RPCS3 Directory")

Now, back in the folder RPCS3 is in, cut the following folders:
* dev_bdvd
* dev_flash
* dev_flash2
* dev_flash3
* dev_hdd0
* dev_hdd1
* dev_usb000
* games

![A screenshot of the folders listed being cut.) en la categoría de 7-Zip.](images/xtra/dir/dircut.png "Cut (CTRL+X")

Paste them inside of the folder you created.

![A GIF of the folders that were cut being pasted into the "RPCS3 Directory" folder.](images/xtra/dir/dirpaste.gif "RPCS3 Directory")

When it finishes pasting, reopen RPCS3.

Click on Manage > Virtual File System

![A screenshot of the folder created, which is named "RPCS3 Directory" in this tutorial.) en la categoría de 7-Zip.](images/xtra/dir/dirrpcs3.png "RPCS3 Directory")

Then, click on the `+` symbol at the bottom.

![A screenshot of RPCS3's Virtual File System Menu, showing the cursor hovering over the plus symbol at the bottom.](images/xtra/dir/dirvfsadd.png "Virtual File System")

Go to the folder you created, click on it, and then click on "Select Folder."

![A screenshot of RPCS3's "Choose a directory" window, selecting the created folder.](images/xtra/dir/dirfoldersel.png "RPCS3 Directory")

Finally, click "Save".

![A screenshot of RPCS3's "Choose a directory" window, selecting the created folder.](images/xtra/dir/dirvfssave.png "RPCS3 Directory")

That's it!

You may have to re-add some games (by drag and dropping the folders) into RPCS3 after this but everything should work like it did before.