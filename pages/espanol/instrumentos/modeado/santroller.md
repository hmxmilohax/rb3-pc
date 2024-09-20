---
title: Santroller Powered Custom Guitars
sidebar: controllers_es_sidebar
permalink: ctrls_mod_santroller_es
folder: instrumentos
tags: [modeado, espanol]
summary: "How to connect and configure Xbox 360 Wireless keyboards (MIDI) on RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/santroller.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rcmgtrs.png" alt="Control" title="Control"></div>

## NOTAS:

* **Please note that your Santroller Configurator may have different settings, depending on how your guitar was modded.** If you purchased your guitar pre-modded, contact the seller for more information.

## Información de Control:

| Handlers | Devices |
|:--------:|:-------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Guitar | Rock Band |

## Setup

If you haven't initlized your controller yet, start up Santroller.

In the start screen, select your Device. This will depend on what device your modded guitar has. In the tutorial screenshots, it was a "`Raspberry Pi Pico`".
After that, click on Configure.

![A screenshot of Santroller's first screen. "Selected Device" is set to Raspberry Pi Pico.](https://rb3pc.milohax.org/images/instruments/xtra/san/initsan.png "initsan")

In Controller Settings, set your configuration to the following:
* Emulation Type: Controller
* Controller Type: Rock Band Guitar
* Swap Switch Face Buttons: (Depends on your guitar)
* Windows Controller Mode: HID Game Controller
* Use USB Passthrough with RPCS3: Disabled
* Ladeo: Enabled

![A screenshot of Santroller's Controller Settings. The settings reflect exactly what is above.](https://rb3pc.milohax.org/images/instruments/xtra/san/consetsan.png "Santroller: Controller Settings")

It's also suggested you calibrate your Whammy to have the best experience. Scroll down to the Whammy section and calibrate it.

**MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

![A screenshot of RetroCultMods Programming Tool. The cursor is hovering over "Save Settings".](https://rb3pc.milohax.org/images/instruments/xtra/san/savesan.png "RetroCultMods Programming Tool")

## Mapeo:

* **To map everything correctly, you will need to first map Whammy Down, which is Right Stick: Left in RPCS3. It should show up as X-. After mapping it, click `"Filter Noise"` and map the rest.**

| **RPCS3**          | **Control** |
|:------------------:|:---------------------:|
| Cross (Cruz) | ![Traste Verde](https://rb3pc.milohax.org/images/btns/gtrs/gf.png "Traste Verde") |
| Circle (Circulo) | ![Traste Rojo](https://rb3pc.milohax.org/images/btns/gtrs/rf.png "Traste Rojo") |
| Square (Cuadro) | ![Traste Azul](https://rb3pc.milohax.org/images/btns/gtrs/bf.png "Traste Azul") |
| Triangle (Triangulo) | ![Traste Amarillo](https://rb3pc.milohax.org/images/btns/gtrs/yf.png "Traste Amarillo") |
| L1 | ![Traste Naranja](https://rb3pc.milohax.org/images/btns/gtrs/of.png "Traste Naranja") |
| D-Pad (Cruceta): Arriba | ![Rasgueo para arriba](https://rb3pc.milohax.org/images/btns/gtrs/sbu.png "Rasgueo para arriba") |
| D-Pad (Cruceta): Abajo | ![Rasgueo para abajo](https://rb3pc.milohax.org/images/btns/gtrs/sbd.png "Rasgueo para abajo") |
| D-Pad (Cruceta): Izquierda | ![D-Pad (Cruceta): Izquierda](https://rb3pc.milohax.org/images/btns/gtrs/dpl.png "D-Pad (Cruceta): Izquierda") |
| D-Pad (Cruceta): Derecha | ![D-Pad (Cruceta): Derecha](https://rb3pc.milohax.org/images/btns/gtrs/dpr.png "D-Pad (Cruceta): Derecha") |
| Palanca Derecha: <br/> Izq./Der. | ![Palanca de whammy](https://rb3pc.milohax.org/images/btns/gtrs/wb.png "Palanca de whammy") |
| Boton R1 | ![Ladeo](https://rb3pc.milohax.org/images/btns/gtrs/ts.png "Ladeo") |
| Start | ![Start](https://rb3pc.milohax.org/images/btns/ctrls/360/start.png "Start") |
| Select | ![Back](https://rb3pc.milohax.org/images/btns/ctrls/360/back.png "Back") |
| Botón PS | ![Home](https://rb3pc.milohax.org/images/btns/gtrs/home.png "Home") |

### Passthrough Mode

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>As of writing this, RPCS3 does not support hotplugging, which means you cannot plug your guitar in AFTER starting RPCS3. Passthrough Mode lets you use your guitar without needing to bind anything but due to the lack of hotplugging (PS3/Emulator preset), you need to start the game up twice. Therefore, this mode is currently not recommended. </b> {{include.content}}</div>

## Perfil

[[Bajar Perfil]](https://github.com/carlmylo/docu-rpcs3/raw/refs/heads/gh-pages/downloads/instrument-repo/RetroCultMods%20Solderless%20Kit.7z)

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/rcmslmapping.png" alt="Mapeo" title="Mapeo"></div>

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Investigación por [[Lynxeption]](https://www.youtube.com/@Lynxeption).  
Special thanks to [[@amphobius]](https://twitter.com/amphobius) for additional pictures.