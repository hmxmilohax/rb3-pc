Versión Video (no actualizada):  
[![Una mini-imagen de la versión vídeo de esta guía.](images/xtra/vidthumb.jpg)](https://www.youtube.com/watch?v=sramU-Xdhrs "How to play Rock Band 3 on PC (with RPCS3) - YouTube")

<br/>

>##### ADVERTENCIA:
<sub>_Esta guía **no** te va a dar links para descargar el juego ni el DLC. Ninguno de los servidores de Discord mencionades tampoco te los va a dar. Haga su propia copia o busque ayuda en Google. **La piratería es ilegal y atrae a los abogados de Tim Sweeney!**._
<br/>

1. [_Requisitos_](#requisitos)
2. [_Instalación_](#installation)
3. [__Configuración__](#configuration)
4. [_Controladores (guitarras, baterías, y gamepads de RB o GH))_](#controllers)
5. [_Cuenta de usuario_](#user-account)
6. [_RPCN_](#rpcn-account)
7. [_Configuración Customizada_](#custom-configuration)
8. [_CPU_](#cpu)
9. [_GPU_](#gpu)
10. [_Audio_](#audio)
11. [_E/S (guitarras Pro y teclados con cable USB/MIDI)_](#io)
12. [_Red_](#network)
13. [_Avanzado_](#advanced)
14. [_Emulador_](#emulator)
15. [_Guitarras y teclados inalámbricos PS3 Mustang Pro con receptores_](##wireless-ps3-mustang-pro-guitar-and-ps3-rock-band-3-keyboard-with-dongle)
16. [_Soluciónes de problemas_](#troubleshooting)
17. [_Conclusión_](#conclusion)

<br/>

# REQUISITOS:

Necesitarás:
* _Una copia de Rock Band 3 para PS3 en tu compu. (Idealmente BLUS-30463)_
* _11.12 GBs de espacio mínimo. (145.66 GBs para **todo** el contenido oficial desde RB1 hasta RB3, incluyendo DLC, RBN y exportes.)_
* _Un control instrumento. Puedes usar:_
	*   _Cualquier guitarra de Rock Band y Guitar Hero (PS3, PS4, Wii, X360)_
	*   _Cualquier batería de Rock Band y Guitar Hero (PS3, PS4, Wii, X360)_
	*   _Cualquier instrumento MIDI compatible junto con el adaptador MIDI Pro Rock Band 3 (solo la versión de PS3)_<sup>a
	*   _Teclado Rock Band 3 (solo la versión de PS3 con receptor propio) _<sup>a b
	*   _Guitarra PRO de Rock Band 3 Fender Mustang \[**Inalámbrica**\] (solo la versión de PS3 con receptor propio)_<sup>a
	*   _Guitarra PRO de Rock Band 3 Fender Mustang \[**Con cable**\] (versiónes de PS3, Wii, X360 con adaptador de MIDI a USB)_
	*   _Guitarra PRO Rock Band 3 Squier Stratocaster (versiónes de PS3, Wii, X360 con adaptador de MIDI a USB)_
	*   _Cualquier teclado MIDI (**con 37 teclas a lo mínimo** conectado por USB o por adaptador MIDI a USB)_<sup>b c
	*   _Batería MIDI (conectado por USB o por adaptador MIDI a USB y los programas MidiDrumHero and VJoy)_<sup>d
	*   _Cualquier micrófono detectado por tu compu (el juego se puede controlado con la mayoría de mandos o con el teclado cuando juegas como vocalista)_
*   _Una computadora_
	* Esta guía ha sido probada con especificaciones tan bajas como los CPUs Intel Core i5-4460, Intel Core i5-6500, Intel Core i7-3770, AMD Ryzen 2600, y AMD Ryzen 3 3200G. También se ha probado en GPU tan bajas como NVIDIA GeForce GT 730, NVIDIA GTX 1650 y AMD Radeon RX 550. Eso que se sugiere 16 GB de RAM, funciona bien con 8 GB de RAM. Técnicamente, se puede usar un SteamDeck para jugar, pero eso está muy complejo para incluir en esta guía.
    Puedes ver [la página de RPCS3 para sus especificaciones sugeridas](https://rpcs3.net/quickstart) pero están exageradas para este juego.
*   _[7zip](https://www.7-zip.org/download.html) (o WinRAR si te odias a ti mismo)_

<sup>a</sup> <sub>Los instrumentos y receptores de Rock Band para el Wii se pueden convertir a PS3, pero eso es demasiado complejo para incluir en esta guía. Google es tu amigo.</sub>  
<sup>b</sup> <sub>Es posible conectar teclados con MIDI que tengan menos de 37 teclas, pero no es lo ideal, asi que no está recomendado en esta guía.</sub>  
<sup>c</sup> <sub>Ciertos teclados MIDI, especialmente los de Yamaha, pueden darte problemas por su implementación de MIDI. El equipo de RPCS3 conoce a este problema y se está trabajando en una solución.</sub>  
<sup>d</sup> <sub>Así que no hay instrucciones para configurarlas. Si tienes uno y te gustaría ayudar enviar capturas la configuración, mandame un mensaje por el Milohax Discord.</sub>

<br/>

# INSTALACIÓN:

Vamos a descargar una versión anterior de RPCS3 porque funciona mejor en este momento. Eso que está guía es para Windows, he incluido a Linux y Mac OS en caso de que quieras probar esta versión en esos sistemas operativos. Para los curiosos, esta es la última versión de RPCS3 antes de la inclusión de QT6, que tiene muchos problemas.

| [![Logo de Microsoft Windows](images/inst/windows.png)](https://github.com/RPCS3/rpcs3-binaries-win/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_win64.7z "Versión Windows") | [![Mascota de Linux, Tux ](images/inst/linux.png)](https://github.com/RPCS3/rpcs3-binaries-linux/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_linux64.AppImage "Versión Linux") | [![Logo de Apple Computers](images/inst/mac.png)](https://github.com/RPCS3/rpcs3-binaries-mac/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_macos.dmg "Versión Mac OS") |
|---|---|---|

**Cuando se descargue, extrae el archivo .7zip..**  
![A screenshot of the the right click menu from Windows exploring highlighting "Extract files..." from the 7-Zip category.](images/inst/extract.png "Extract Files")

Recomiendo extraer los archivos a “C:\\Games\\RPCS3” o otro disco interno para evitar problemas con permisos. También desactiva la opcion que creará el subdirectorio como en la imagen. No lo instales en un disco externo, porque puede causar problemas feos.  
![A screenshot of the Extract window from 7-zip. It shows the "Extract to" as C:\Games\RPCS3 and the box below it unchecked.](images/inst/extractdir.png "Extract")

Once that’s extracted, [**download the PlayStation 3 system software from Sony’s website**](https://www.playstation.com/en-us/support/hardware/ps3/system-software/). **Scroll down** until you get to “**Update using a computer**”, **click that** to expand, then **click on “Download PS3 Update.**”  
  
_**If you’re on a Chromium based browser like Chrome or Edge, MAKE SURE YOU RIGHT CLICK AND “Save link as”, or it MAY become stuck.**_

Once again, the picture below links to the download page.
[![A screenshot of Sony's "How to update PS3 console system software" page with the "Update using a computer" subcategory expanded.](images/inst/fwpage.png)](https://www.playstation.com/en-us/support/hardware/ps3/system-software/ "How to update PS3 console system software")


Now **open up RPCS3**, and **drag** the **PS3UPDAT.PUP** you just downloaded from Sony’s website **into RPCS3** **then click Yes**.  
![A screenshot of RPCS3's Firmware Installer asking the user if they want to install the firmware named "PS3UPDAT.PUP".](images/inst/fwinstall.png "RPCS3 Firmware Installer")

**Let it install.**  
![A screenshot of RPCS3's Firmware Installer in the middle of installing firmware version 4.90.](images/inst/rpcs3fw.png "RPCS3 Firmware Installer progress")

**When it finishes, click OK**  
![A screenshot of RPCS3's Firmware Installer after a successful install of PS3 firmware and LLE modules.](images/inst/rpcs3fwdone.png "Success!")

It will start compiling modules, which may take a few minutes. **Let it do its thing.**  
![A screenshot of RPCS3 compiling PPU modules with a progress bar at 1/8th completion.](images/inst/rpcs3fwcomp.png "Compiling PPU modules...")

Next, **go to the folder where you have your copy of Rock Band 3 stored and drag the folder into RPCS3**. Again, you're on your own here. [I used “PS3 Disc Dumper” for this because it’s the easiest way.](https://youtu.be/mRxSKxoYt_g)
![A GIF of the dumped folder of Rock Band 3 being dragged into RPCS3, which updates RPCS3 to display Rock Band 3 in the game list.](images/inst/rpcs3rb3dnd.gif "Rock Band 3 [BLUS30463]")

Rock Band 3 is now in your game library in RPCS3, however it’s out of date. Let’s fix that. **You will need to download the update PKG file** which is linked below. This directly links to Sony’s official download. You may get security warnings as Sony’s update server lacks HTTPS.  
[\[CLICK HERE TO DOWNLOAD ROCK BAND 3 UPDATE PKG\]](http://b0.ww.np.dl.playstation.net/tppkg/np/BLUS30463/BLUS30463_T4/e52d21c696ed0fcf/UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg)

The filename will look something like this:

[![Rock Band 3's PKG update in Edge's download tray.](images/inst/rb3pe.png)](http://b0.ww.np.dl.playstation.net/tppkg/np/BLUS30463/BLUS30463_T4/e52d21c696ed0fcf/UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg "UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg")

When that’s finished, **drag the update file into RPCS3 and click Yes**, just like you did earlier with the PS3UPDAT.PUP file.  
![A screenshot of RPCS3's Decrypter/ Installer asking if the user wants to install the Rock Band 3 update package file.](images/inst/rpcs3pkg.png "PKG Decrypter/ Installer")

<br/>

# CONFIGURATION:

*IF YOU HAVE CHANGED SETTINGS FOR RPCS3, SET THEM BACK TO DEFAULT FOR ROCK BAND 3 BEFORE FOLLOWING THIS TUTORIAL!*

<br/>

## CONTROLLERS:

**This is for standard (five fret guitars, RB/GH drums) controllers.**  
Pro Guitars, or Keyboards are set up later.

Right click “Rock Band 3” and click on **“Create Custom Gamepad Configuration”**

![A screenshot of RPCS3's right click menu, showing "Create Custom Gamepad Configuration" highlighted](images/conf/rpcs3pad.png "Create Custom Gamepad Configuration")

* If you are planning on plugging in multiple instruments, _you must make profiles for each of them_.
* PS3 standard guitar and drum controllers _should_ be plug and play. If, for some reason, they’re not, you will need to bind them as detailed below. 
* If you’re using PS3, PS4, or Wii controllers, set the “Handlers” option to “MMJoyStick.” 
* If you’re using Xbox controllers, set the “Handlers” option to “XInput”

Below are the buttons you should map in RPCS3’s Gamepad Settings. **[\[You can also check RPCS3’s website for reference as well\]](https://wiki.rpcs3.net/index.php?title=Help:Peripherals_and_accessories#Configuring_Instruments).**

**If your controller isn’t being detected, hit “Refresh”. If that doesn’t solve it, restart RPCS3.**

When you’re finished, **remember to click “Save”.**

  
**Guitar**:  
Make sure you **set “Device Class” to “Guitar”.**

Switch the dropdown menu next to it to"Rock Band" if you’re using a Rock Band guitar or leave it on “Guitar Hero” if you’re using a Guitar Hero guitar.  
**Some guitar controllers** (most notably Guitar Hero controllers) **misbehave and refuse to map** sometimes. If you try mapping a button and get “U+”, try pressing “**Filter Noise**” the bottom left of the controller configuration.

| **RPCS3**          | **Rock Band Guitars** | **Guitar Hero Guitars** |
|:------------------:|:---------------------:|:-----------------------:|
| Cross | ![Green Fret](images/btns/gtrs/gf.png "Green Fret") | ![Green Fret](images/btns/gtrs/gf.png "Green Fret") |
| Circle | ![Red Fret](images/btns/gtrs/rf.png "Red Fret") | ![Red Fret](images/btns/gtrs/rf.png "Red Fret") |
| Square | ![Blue Fret](images/btns/gtrs/bf.png "Blue Fret") | ![Yellow Fret](images/btns/gtrs/yf.png "Yellow Fret") |
| Triangle | ![Yellow Fret](images/btns/gtrs/yf.png "Yellow Fret") | ![Blue Fret](images/btns/gtrs/bf.png "Blue Fret") |
| L1 | ![Orange Fret](images/btns/gtrs/of.png "Orange Fret") | ![Orange Fret](images/btns/gtrs/of.png "Orange Fret") |
| D-Pad: Up | ![Strumbar Up](images/btns/gtrs/sbu.png "Strumbar Up") | ![Strumbar Up](images/btns/gtrs/sbu.png "Strumbar Up") |
| D-Pad: Down | ![Strumbar Down](images/btns/gtrs/sbd.png "Strumbar Down") | ![Strumbar Down](images/btns/gtrs/sbd.png "Strumbar Down") |
| Right Stick: Right | ![Whammy Bar](images/btns/gtrs/wb.png "Whammy Bar") | ![Whammy Bar](images/btns/gtrs/wb.png "Whammy Bar") |
| L2 | ![Effects Switch](images/btns/gtrs/fx.png "Effects Switch") | |
| R1 | ![Tilt](images/btns/gtrs/ts.png "Tilt") | Does not work |


**Drums**:

Make sure you **set “Device Class” to “Drum”.**

Switch the dropdown menu next to it to"Rock Band" if you’re using Rock Band drums, “Rock Band Pro” if you’re using Rock Band Drums with Pro expansions, or leave it on “Guitar Hero” if you’re using Guitar Hero drums.

| **RPCS3**    | **Rock Band Drums** | **Rock Band Pro Drums** | **Guitar Hero Drums** |
|:--------:|:---------------:|:-------------------:|:-----------------:|
| Cross | ![Green Pad](images/btns/drms/rb/gp.png "Green Pad") | ![Green Pad](images/btns/drms/rb/gp.png "Green Pad") | ![Green Pad](images/btns/drms/gh/gp.png "Green Pad") |
| Circle | ![Red Pad](images/btns/drms/rb/rp.png "Red Pad") | ![Red Pad](images/btns/drms/rb/rp.png "Red Pad") | ![Red Pad](images/btns/drms/gh/rp.png "Red Pad") |
| Square | ![Blue Pad](images/btns/drms/rb/bp.png "Blue Pad") | ![Blue Pad](images/btns/drms/rb/bp.png "Blue Pad") | ![Blue Pad](images/btns/drms/gh/bp.png "Blue Pad") |
| Triangle | ![Yellow Pad](images/btns/drms/rb/yp.png "Yellow Pad") | ![Yellow Pad](images/btns/drms/rb/yp.png "Yellow Pad") | ![Yellow Cymbal](images/btns/drms/gh/yc.png "Yellow Cymbal") |
| L1 | ![Foot Pedal](images/btns/drms/rb/kp.png "Foot Pedal") | ![Foot Pedal](images/btns/drms/rb/kp.png "Foot Pedal") | ![Foot Pedal](images/btns/drms/gh/kp.png "Foot Pedal") |
| D-Pad | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") |
| R1 |  | ![Second Foot Pedal](images/btns/drms/rb/kp.png "Second Foot Pedal") | ![Orange Cymbal](images/btns/drms/gh/oc.png "Orange Cymbal") |
| R3 |  | Cymbal Modifier | |
| L3 |  | Pad Modifier | |


**Vocals**:  
Vocals use regular controllers. If you're using a PS4 controller, switch to DS4. If you're using an Xbox One controller, switch to XInput. You don't have to remap anything. You can also use a typing keyboard and use this guide as reference to change the mapping to your liking.

| **PlayStation (DS4)** | **Xbox One (XInput)** | **Use**                         | **Alt Use**         |
|:---------------------:|:---------------------:|:-------------------------------:|:-------------------:|
| ![Left Stick](images/btns/ctrls/ps4/ls.png "Left Stick") | ![Left Stick](images/btns/ctrls/xbox/ls.png "Left Stick") | Navigation |
| ![D-Pad](images/btns/ctrls/ps4/dp.png "D-Pad") | ![Left Stick](images/btns/ctrls/xbox/dp.png "D-Pad") | Navigation |
| ![Cross Button](images/btns/ctrls/ps4/x.png "Cross Button") | ![A Button](images/btns/ctrls/xbox/a.png "A Button") | Select                          |
| ![Circle Button](images/btns/ctrls/ps4/o.png "Circle Button") | ![B Button](images/btns/ctrls/xbox/b.png "B Button") | Back                            | Mic 3 Volume (Song) |
| ![Square Button](images/btns/ctrls/ps4/s.png "Square Button") | ![X Button](images/btns/ctrls/xbox/x.png "X Button") | Mic 1 Volume (Song) |
| ![Triangle Button](images/btns/ctrls/ps4/t.png "Triangle Button") | ![Y Button](images/btns/ctrls/xbox/y.png "Y Button") | View More Info (Library)        | Mic 2 Volume (Song) |
| ![Options Button](images/btns/ctrls/ps4/opt.png "Options Button") | ![Options Button](images/btns/ctrls/xbox/opt.png "Options Button") | Options                         | Pause (Song)        |
| ![Share Button](images/btns/ctrls/ps4/shr.png "Share Button") | ![View Button](images/btns/ctrls/xbox/viw.png "View Button") | Filters (Library)               | Overdrive (Song)    |
| ![L1 Button](images/btns/ctrls/ps4/l1.png "L1 Button") | ![Left Bumper](images/btns/ctrls/xbox/lb.png "Left Bumper") | Guide Part Selection (Practice) |
| ![L2 Trigger](images/btns/ctrls/ps4/l2.png "L2 Trigger") | ![Left Trigger](images/btns/ctrls/xbox/lt.png "Left Trigger") | Vocal Part Selection (Practice) |
| ![R1 Button](images/btns/ctrls/ps4/r1.png "R1 Button") | ![Right Bumper](images/btns/ctrls/xbox/rb.png "Right Bumper") | Vocal Track Volume (Song)       |
| ![R2 Trigger](images/btns/ctrls/ps4/r2.png "R2 Trigger") | ![Right Trigger](images/btns/ctrls/xbox/rt.png "Right Trigger") | Pitch Correction (Song)         |

  

As an example, here’s what a _Wii The Beatles: Rock Band Hofner_ controller looks like when it’s set up. Note the "Handlers" being set to "MMJoystick" and "Devices" being set to the correct Joystick number. Also note that, since it's a Rock Band guitar controler, "Device Class" is set to 'Guitar" and the box next to that is set to "Rock Band".
![A screenshot of RPCS3's Gamepad Settings with a Hofner](images/conf/rpcs3padexm.png "Gamepad Settings with a Wii The Beatles: Rock Band Hofner guitar controller")

<br/>

## Cuenta de Usuario:
En RPCS3,ve a **Manage > User Accounts**  
![RPCS3 showing "User Accounts" option under the "Manage" menu.](images/conf/rpcs3user.png "RPCS3: User Accounts")

Una vez que estes ahi,dale click en el Nombre de usuario Predeterminado (00000001 - User) y Luego click en **“Rename user”** y cambialo al nombre que quieras y luego lo cierras.
![RPCS3's "User Manager", showing the default username.](images/conf/rpcs3rename.png "RPCS3: User Accounts")

<br/>

## Cuenta de RPCN

Si no quieres jugar Online, [puedes saltarte esta parte.](#custom-configuration)

Ve a **Configuration > RPCN**
![A screenshot of RPCS3's Configuration with "RPCN" highlighted](images/rpcn/rpcn.png "RPCS3: RPCN")

Da click en “**Account**”:  
![A screenshot of RPCS3's RPCN menu with "Account" highlighted](images/rpcn/rpcnpopup.png "RPCN")

Click en “**Create Account**”:  
![A screenshot of RPCS3's RPCN: Account menu with "Create Account" highlighted](images/rpcn/account.png "RPCN: Account")

Pon un **Nombre de Usuario** Y **Contraseña**:  
![A screenshot of RPCS3's RPCN: Username menu with a username set and "OK" highlighted](images/rpcn/user.png "RPCN: User")  
![A screenshot of RPCS3's RPCN: Password menu with an obscured password set (twice for verification) and "OK" highlighted](images/rpcn/password.png "RPCN: Password")  

Se mostrara una ventana pidiendo un **Correo Electronico** para asi recibir un **Token de Verificacion**:  
![A screenshot of RPCS3's RPCN: Email menu with an email (twice for verification) set and "OK" highlighted](images/rpcn/email.png "RPCN: Email")  

**Click en “Ok”** y ve a la bandeja de entrada de tu correo electronico. Puede que tengas que esperar un par de minutos para que llegue el correo. Si todavia sigues esperando,checa la pestaña de **"Spam"**. El Email se llama **“Your token for RPCN.” Copy the token**:

![A screenshot of an email labeled "Your Token for RPCN" with a token below what username it's for](images/rpcn/emailtoken.png "Your token for RPCN")

**Pega el token** a RPCS3 Y presiona Ok:  
![A screenshot RPCS3 telling the user an account was successfully created.](images/rpcn/created.png "RPCN: Username")

<br/>

# CUSTOM CONFIGURATION:

**Right click on Rock Band 3** in RPCS3, then click on “**Create Custom Configuration**”  
![A screenshot of RPCS3's right click menu, showing "Create Custom Configuration" highlighted](images/cust/rpcs3customconfig.png "Create Custom Gamepad Configuration")

This may seem overwhelming due to the sheer number of options but I have color coded stuff that will need adjustment. Everything not colored should be on default options.

| COLOR | MEANING |
|---|---|
| ![A yellow square.](images/cust/bigyellow.png "Yellow Square") | *REQUIRED* |
| ![A green square.](images/cust/biggreen.png "Green Square") | Low performance fixes |
| ![A pink square.](images/cust/bigpink.png "Pink Square") | Adjust depending on PC, or leave it alone |
| ![A teal square.](images/cust/bigteal.png "Teal Square") | Optional |

We’ll go tab by tab, starting with:

<br/>

## CPU


![A screenshot of Rock Band 3's CPU custom settings, showing SPU XFloat Accuracy, SPU Block Size, and Preferred SPU Threads highlighted in green.](images/cust/cpu.png "CPU")
* ![A green square.](images/cust/smallgreen.png "Green Square") **For low end CPUs** (older 4 core/4 threads chips): 
	* **Change "SPU Block Size" to "Mega"** - Ties smaller SPU compiled together, which requires less cores/threads.
	* **Change "Preferred SPU Threads" to "1"** - Limiting to 1 thread helps prevent stutter caused by CPU overloads.
	* **AS A LAST RESORT** **"SPU XFloat Accuracy" to "Relaxed"** - Changing this will gain a few frames but **will break practice mode!**

<br/>

## GPU
![A screenshot of Rock Band 3's GPU  custom settings, showing Write Color Settings highlighted in yellow, ZCULL Accuracy highlighted in green, Resolution Scale, Resolution Scale Threshold, Frame Limit, and Shader Quality highlighted in pink, and VSync highlighted in teal.](images/cust/gpu.png "GPU")
* ![A yellow square.](images/cust/smallyellow.png "Yellow Square") REQUIRED: 
	* **Enable "Write Color Buffers"** - Fixes 99% of the issues with characters having glitched textures.
* ![A green square.](images/cust/smallgreen.png "Green Square") For low end GPUs: 
	* Change "ZCULL Accuracy" to "Relaxed" - Slight performance improvement which may cause graphical anomalies.
* ![A pink square.](images/cust/smallpink.png "Pink Square") Tweak depending on computer: 
	* Change "Frame Limit" to "Off" to use enable uncapped framerate (may introduce jitter), set to 60 if you want a locked 60 FPS framerate (redundant with 60 Hz Vblank). **It is suggested to use your graphics card's driver settings for frame rate capping, or software like MSI Afterburner.**
	* Adjust "Shader Quality" depending on your system. Low and Medium will drastically reduce quality, Auto will use suggested RPCS3's setting, and High is the best option. Ultra looks similar to high.
	* Adjust "Resolution Scale" to taste. Lower for a performance gains at a drastic cost in quality. Increase for sharper graphics.
	* Adjust "Resolution Scale Threshold" depending on "Resolution Scale" above. Set the number to whatever percent you increased your resolution (i.e. for 1920x1080, which is 150%, you'd calculate what 150% of 16 is, which would be 24.
* ![A teal square.](images/cust/smallteal.png "Teal Square") OPTIONAL: 
	* Enable "VSync" - Reduces screen tearing and may lead to a more stable framerate. Increases latency slightly.

<br/>

## Audio
![A screenshot of Rock Band 3's Audio custom settings, showing Enable Buffering highlighted in yellow, Audio Out highlighted in green, Audio Buffer highlighted in pink, and Microphone Settings, Microphone Type (Standard), Mic1, Mic2, Mic3, and Mic4 highlighted in teal.](images/cust/audio.png "Audio")
* ![A yellow square.](images/cust/smallyellow.png "Yellow Square") REQUIRED: 
	* **Enable "Enable Buffering"** - Absolutely required by Rock Band 3. It should be enabled by default but if it's disabled, reenable it.
* ![A green square.](images/cust/smallgreen.png "Green Square") For Windows users: 
	* **Change "Audio Out" to XAudio2"** - Can help with with latency.
* ![A pink square.](images/cust/smallpink.png "Pink Square") Tweak depending on computer: 
	* Adjust "Audio Buffer Duration" depending on system. **Lower values mean less latency but more CPU** required to keep stable audio. **Higher values mean more stable audio due to less CPU stress**. This can be changed while the game is running but **will require re-calibrating** in Rock Band 3's system settings.
* ![A teal square.](images/cust/smallteal.png "Teal Square") For Vocalists: 
	* Select an input device in "Mic1", "Mic2", and "Mic3" for vocals. If not playing vocals, they will be used for voice chat.

<br/>

## I/O
This section is **for people playing with a Keyboard or a Pro Guitar**
* **If you’re not playing with a wired Pro Guitar or a USB/MIDI keyboard,** [**skip** over **this section**.](#network)  
* **If you’re playing with a PS3 Rock Band 3 Keyboard or wireless PS3 Mustang Pro Guitar,** [**skip** over **this section**.](#network)  

**If your keyboard has a USB port**, all you need to do is **plug it into your computer**.  
![A picture of a MIDI controller's back, showing a USB port and a sustain pedal](images/midi/usbkeys.png "USB Keyboard")  


**If your keyboard only has a MIDI output**, you will need **a MIDI to USB interface**.
![A picture of a MIDI controller's back, showing a 5-DIN MIDI input and output, and multiple pedal inputs.](images/midi/midikeys.png "MIDI Keyboard")  

**The same applies to Rock Band 3 Pro Guitars** as they only have MIDI outputs.
![A picture of a Rock Band 3 Fender Mustang Pro Guitar, showing a 5-DIN MIDI output.](images/midi/midiprotar.png "Mustang Pro Guitar MIDI Output")  

Here’s an example of a MIDI to USB interface. Most will come with a indicator LED to show activity. To check that you plugged it in correctly, **you should see “MIDI In” blinking when you press a key**.  
![A picture of a MIDI to USB interface.](images/midi/miditousb.png "MIDI to USB interface")  


Do note that **some audio interfaces have MIDI inputs**, so if you have one, you may already have a way to plug in MIDI to your computer. For example, this Scarlett has MIDI connections in the back.  
>![A picture of a Focusrite Scarlett's rear, showing a USB port, and 5-DIN MIDI input and output.](images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  


**If everything's connected**, let's go ahead and **focus on RPCS3's I/O tab.**  
![A screenshot of Rock Band 3's I/O custom settings, showing Emulated MIDI Devices, device type, and device selection highlighted in teal.](images/cust/io.png "I/O")
* ![A teal square.](images/cust/smallteal.png "Teal Square"): 
	* 🎹 Keyboard Players: **Leave your "Emulated MIDI type" on "Keyboard" and select your your keyboard in the drop down menu next to it, or MIDI interface, depending on your connection**.
	* 🎸 Pro Guitar Players: **Change your "Emulated MIDI type" from "Keyboard" to "Guitar (17 Frets)" if you have a Mustang Pro Guitar, or "Guitar (22 Frets)" if you have a Squier Pro Guitar, then set your MIDI interface in the drop down menu next to it, or MIDI interface, depending on your connection**.
  
 **If your instrument isn’t detected in the drop down menu, save your configuration so far and restart RPCS3.**  
  
As **keyboards don’t have PS3 buttons, the first octave is** reserved **for mapped keys**. Use this picture as reference. I **strongly** suggest putting artist tape, masking tape, or painter’s tape on your keyboard and drawing the buttons for reference.
![A picture of a 37 key keyboard, showing the second octave mapped to PlayStation buttons, C3 to E3 under a red color, F3 to B3 under a yellow color, C4 to E4 under a blue color, F4 to B4 under a green color, and C5 under an orange color.](images/midi/keysctrl.png "MIDI Keyboard Reference")  

<br/>

## Red
![A screenshot of Rock Band 3's Network custom settings, showing Network Status (Connected) highlighted in yellow, IP/Hosts switches (rb3ps3live.hmxservices.com=45.33.48.123), PSN Status (RPCN), and Enable UPNP (not checked) highlighted in teal.](images/cust/network.png "Network")
* ![A yellow square.](images/cust/smallyellow.png "Yellow Square") REQUERIDO: 
	* **Cambia el Network Status a “Connected” como se remarca en la imagen. Si se deja en “Disconnected”, el juego se congelara temporalmente mientras navegas por la Biblioteca de Canciones.**
* ![A teal square.](images/cust/smallteal.png "Teal Square") Para el Multijugador: 
	* Activa **"Enable UPNP"** o ** Redirecciona el puerto 9103 (UDP) en tu firewall. No actives el UPNP mientas redireccionas el puerto** ya que esto puede causar crasheos.
	* **Unete al \[[Servidor de RBEnhanced](https://discord.gg/6rRUWXPYwb)\]**y**ve al**canal de**[\[#gocentral-connecting\]](https://discord.com/channels/953085263008129064/1076031372185042984)**. **Sigue las Instrucciones para RPCS3**. Aunque la imagen de abajo include detalles, esto esta sujeto a cambios, y siempre **referirte al \[[Servidor de Discord de RBEnhanced](https://discord.gg/6rRUWXPYwb)\]para** esta **informacion**. Mientas estas ahi puedes organizar sesiones con otros jugadores.

<br/>

## ADVANCED
![A screenshot of Rock Band 3's Advanced custom settings, showing "Exclusive Fullscreen Mode (Automatic (Default)), and Driver Wake-Up Delay (1µ) in green.](images/cust/advanced.png "Advanced")
* ![A green square.](images/cust/smallgreen.png "Green Square"): 
	* **Change "Exclusive Fullscreen Mode" to "Prefer borderless fullscreen"** to prevent potential crashes and desync when changing program focus constantly.
	* Change "Driver Wake-up Delay" to "20µ" if you experience rare freezing after a few songs. Increase to "40µ" if it still happens.
* ![A teal square.](images/cust/smallteal.png "Teal Square"): 
	* Adjust VBlank Frequency if you want a higher internal framerate. This can make it easier to hit notes, but can cause graphical instability and connection issues while online. It's best left alone.

<br/>

## EMULADOR
![A screenshot of Rock Band 3's Emulator custom settings, showing "Show trophy popups", "Show PPU compilation hint", "Show Shader Compilation hint", "Start Games in fullscreen mode", "Use native user interface".](images/cust/emulator.png "Emulator")
Puedes dejar esto como quieras, pero yo consideraria cambiar las siguientes opciones:
* ![A teal square.](images/cust/smallteal.png "Teal Square") Cambios Opcionales: 
	* “Show trophy popups” - Simula la notificacion de trofeos de la PS3. Personamente desactivo esto ya que el juego tiene sus propias notificaciones.
	* “Show PPU compilation hint” - Esto crea una notificacion cuando RPCS3 esta compilando los shaders PPU. Esto solo sale si tienes la opcion "Recompiler (LLVM)" activada en la pestaña de CPU.
	* “Show shader compilation hint” - Esto crea una notificacion cuando RPCS3 esta compilando Shaders. Ya sea si lo dejas activado o no ya es cosa tuya, pero debo decirte que esto es importante. Cuando ejecutas juegos de PS3, tiene que compilar shaders para "trasladar" los graficos de una PS3 a un formato que tu PC pueda usar. **El juego seguirá trabandose mientras esto pase** . **Esto Pasa en TODOS los PC's.** Cuando termine de compilar un efecto, **esto usualmente ya no vuelve a pasar otra vez**. **La mejor forma de lidiar con esto es** simplemente **jugar al juego normalmente** y luego se ira rapidamente
	* “Start games in Fullscreen mode” - Obviamente solo cambia el modo de Pantalla Completa cuando inicias Rock Band 3. Personalmente yo activo esto.
	* “Use Native Interface” - Desactivar esto hara que se remuevan todas las notificaciones de RPCS3 mienras el juego es ejecutado.



Y con eso termina la parte dificil.

<br/>

#### Wireless PS3 Mustang Pro Guitar and PS3 Rock Band 3 Keyboard with dongle

If you’re not playing with a PS3 Mustang Pro Guitar and PS3 Keyboard with their respective dongles, [skip over this section.](#troubleshooting)

To start with, **close out RPCS3** **and plug in the instrument’s dongle** to your computer.

Now, [**\[go to Zadig’s website\]**](https://zadig.akeo.ie/) and **download the latest version.** **Open it** up.

Click on **Options** then **List All Devices**  
![A screenshot of Zadig showing "List All Devices" under "Options" highlighted.](images/pass/zadiglistall.png "Zadig: Options: List All Devices")

You should now see devices listed. **Switch it to your Rock Band 3 Pro Instrument**. In this example, we’re using the Mustang Pro Guitar, which shows up as “Harmonix RB3 Mustang Guitar for PlayStation® 3”.  
![A screenshot of Zadig showing "Harmonix RB3 Mustang Guitar for PlayStation® 3" highlighted in the devices listed.](images/pass/zadigsel.png "Zadig: Harmonix RB3 Mustang Guitar for PlayStation® 3")

After selecting the right device, you should see the option to replace the driver. **MAKE SURE YOU ARE REPLACING THE DRIVER ONLY FOR THE PRO GUITAR/KEYBOARD.** Click Replace Driver.  
![A screenshot of Zadig with "Replace Driver" highlighted.](images/pass/zadigreplace.png "Zadig: Replace Driver")

A warning will appear. **Again, make sure you have selected your RB3 Pro Guitar or keyboard instrument.** After you have made sure, click “**Yes**”  
![A screenshot of Zadig warning the user that they're about to modify a system driver, with "Yes" highlighted](images/pass/zadigreplace.png "Zadig: Warning - System Driver")

It will then install the driver. As the program says, it may take a few minutes.  
![A screenshot of Zadig in the middle of a driver install.](images/pass/zadigprogress.png "Zadig: Installing Driver...")


If everything goes well, you will get this message:  
![A screenshot of Zadig telling the user that the driver was installed successfully with "Close" highlighted.](images/pass/zadigdone.png "Zadig: Success")

**Close Zadig** and, **with the dongle** still **connected**, **open up RPCS3** and **open Rock Band 3**.

Turn your controller on and you should see it automatically assign a player number.
![A picture of a Mustang Pro Guitar with the second player LED lit up.](images/pass/protaron.png "Fender Mustang Pro Guitar: Player 2")

Likewise, in Rock Band 3, you will see the instrument ready to join.  
![A screenshot of Rock Band 3 with a Pro Guitar ready to join.](images/pass/rb3player.png "Rock Band 3: Pro Guitar ready to join")

<br/>

## TROUBLESHOOTING


*   **_Audio Entrecortado_**

	* [![A video thumbnail that reads "Click here for audio example."](images/xtra/badaudio.png)](https://www.youtube.com/watch?v=UoCMEQbNThs&t=20s "Rock Band 3 Deluxe - Low-End Low-Buffer Autoplay - YouTube")
	* Aumenta el "Audio Buffer Duration" como se menciona en [la pestaña de Audio de la Configuracion Personalizada de Rock Band 3] (#Audio) hasta que el Audio Entrecortado se detenga. 100 ms es un buen comienzo para computadoras de bajo rendimiento.

*   **_Problemas Generales de Rendimiento_**
	*   Regresa y Lee los“**EXTRA**” Mensajes de la [Seccion de Configuracion Personalizada](#configuration).
	*   Instala [RB3 Deluxe](https://github.com/hmxmilohax/rock-band-3-deluxe/tree/main#playstation-3) y deshabilita los Efectos de Post Procesado en el apartado "Deluxe Settings"

*   **_El juego no se llena en toda la_****_pantalla_**
	*   Activa la Opcion "Overscan" en el Menu de Opciones de RB3.

*   **_El juego tiene retrao de Audio o Notas_**
	*   Ejecuta la calibracion en el menu de ajustes de Sistema de Rock Band 3 si no lo has hecho. Deshabilita la opcion "Dolby Digital" en el mismo menu.
	
*   **_No puedo usar la Calibracion Automatica_**
	*   La calibracion automatica solo funciona con las guitarras de PS3 via Traspaso/Conexion Directa .

*   **_El juego se Traba al ponerle Nombre a un Personaje_**
	*   Esto es un problema de RPCS3. Puedes solucionarlo cambiando el los efectos con el Interruptor de Efectos en una Guitarra de RB. De lo contrario,cambiando tu controlador de Entrada en "[Crear una Configuracion Personalizada para El Mando](#controllers)" a "Teclado" y luego regresarlo a donde lo tenias originalmente lo arregla. Esto deberia funcionar mientras el juego se esta ejecutando..

*   **_Los Instrumentos o Accesorios de los Personajes flotan o los traspasan_**
	*   Actualmente no hay ninguna solucion para esto. Si Experimentas esto, [Por favor reportar tus descubrimientos en el Github de RPCS3.](https://github.com/RPCS3/rpcs3/issues/8408)

*   **_Al navegar por la biblioteca hay pausas largas_**
	*   En ese caso,olvidaste poner el "Network Status" a "Connected" en la [Pestaña "Network" al hacer la Configuracion Personalizada](#network) para Rock Band 3.

*   **_My PS3 instrument controller shows up as two_**
	*   You did [controller configuration](#controllers) for a PS3 controller, which usually isn’t needed due to passthrough. Just unbind the controller and it should be fine.
	
*   **_[Pro Bateria] Golpear dos platillos se registra como un tambor_**
	*   Este es un bug conocido de Rock Band 3 llamado "Glitch de los Platilos Dobles". Lastimosamente no se la solucion ya que no juego la Bateria. Por favor sientete libre de preguntar en el servidor de Discord de MiloHax.

*   **_\[ONLINE\] No puedo encontrar al Tercer o Cuarto jugador_**
	*   En la Configuracion Personalizada de Rock Band 3, [ve a la pestaña de Network](#network) y asegurate de tener activado la opcion "Enable UPNP". Si por alguna razon no puedes activar el UPNP, tendras que redireccionar el puerto 9103 (UDP) en tu firewall. **No actives el UPNP mientras estas redireccionando el puerto** ya que esto puede causar crasheos.
	
*   **_\[ONLINE\] Al tratar de conectar a GoCentral el juego se queda en "Registering Account_**
	*   Puede que hayas perdido la conexion a RPCN o GoCentral y tendras que reiniciar el Juego. Si continuas teniendo esto luego de haber reiniciado, ve al menu de arriba en RPCS3 a, "Configuration" > "RPCN" > "Account" > "Test Account" luego reinicia el juego para forzar una reconexion.

*   **_“Segui todos los pasos y todavia tengo crasheos/mal rendimiento”_**
	*   Revisa nuevamente para asegurarte de que has seguido cada paso correctamente. Esta guía ha sido probada y ha demostrado funcionar para muchas personas con diferentes tipos de hardware. Si estás absolutamente seguro de haber seguido cada paso correctamente, es muy probable que el archivo del juego que tienes esté dañado en un 90%, que haya un 9% de posibilidades de que tu computadora se haya quedado sin espacio en disco, y un 1% de que sea skill issue.

<br/>

## CONCLUSION

Eso es todo! Ahora (Con un poco de suerte) tienes un set-up funcional para jugar Rock Band 3 en Tu Computadora. Mientras estas aca, porque no te unes a algunas comunidades que estan ayudando a mantener viva la Comunidad de Rock Band?

**Rock Band 3 Deluxe/Milohax:** 

[![Rock Band 3 Deluxe Logo](images/xtra/rb3dx.gif)](https://github.com/hmxmilohax/rock-band-3-deluxe#readme "Rock Band 3 Deluxe")

Desarroladores del imprescindible Mod Rock Band 3 Deluxe que no puedo recomendar lo suficiente.**[\[Descarga Aqui.\]](https://github.com/hmxmilohax/rock-band-3-deluxe#readme)**Además de agregar muchas características de calidad de vida como arranques más rápidos, escenarios a 60 fps y carga automática de contenido descargable, **también incluye RB3_Plus, que agrega Pro Keys adicionales y Pro Guitar/Bass a canciones que no las tenían.****¡Si tienes un instrumento Pro, esto es imprescindible!** Además de esto, hay varias opciones de personalización visual, como el uso de Apariencias de Rock Bands más antiguos (y más nuevos) e incluso de Guitar Hero.[You can**\[join Milohax’s Discord here\]**](https://discord.gg/xrba4CjdNC).

*
**RBEnhanced:**

[![RBEnhanced Logo](images/xtra/rbe.png "RBEnhanced")

Desarrolladores del Increible mod RBEnhanced el cual solamente existe para Xbox 360 y Wii. Los mismos desarrolladores tambien ayudan y mantienen el servidor de GoCentral el cual es la unica manera de jugar Rock Band 3 en linea en Xbox,PS3 y Wii por el Momento. Puedes[**\[unirte al servidor de RBEnhanced Aqui\]**](https://discord.gg/6rRUWXPYwb).

Agradecimientos especiales a:

*   [DarkRTA](https://www.youtube.com/@darkrta), [Linos](https://www.youtube.com/@LinosMelendi), [Jnack](https://www.youtube.com/@jnackmclain), [Hughtobasic](https://www.youtube.com/@thisisRK), [ihatecompvir](https://www.youtube.com/@ihatecompvir1591), and [LysiX](https://www.youtube.com/@LysiX) por informacion tecnica sobre RPCS3 y Rock Band 3.
*   qfoxb, [SlothDemon](https://www.youtube.com/@SlothDemon1991), [Jnack](https://www.youtube.com/@jnackmclain) (el cual hizo pruebas por casi 20 horas en autoplay lmao), knvtva, y 1osks por reportar resultados.
*   RPCS3 Wiki por tener una cantidad decente de informacion sobre los Controladores y los Traspasos Via USB.


<div align="center">

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

</div>
