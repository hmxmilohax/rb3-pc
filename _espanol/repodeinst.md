---
title: Extra - Repositorio de Instrumentos
author: Carl Mylo
date: 2000-11-01
category: Espanol
layout: post
---

# ¿Qué es esto?

Un repositorio de perfiles de RPCS3 preconstruidos para ayudar a jugadores nuevos de Rock Band 3. Estos archivos se pueden instalar con un simple "arrastrar y soltar" para mayoría de personas.

# Como Usar:
Antes de empezar, **si tienes configuraciones de control en `config\input_configs\BLUS30463`, crea copias de seguridad porque estos perfiles van a sobreescribir.**

1. Baja el archivo .7z para instrumento que quieres usar
2. Extrae el archivo .7z.
3. Arrastra la carpeta `config` a la carpeta donde tienes RPCS3.

![Una animación de alguien arrastrando el perfil para las guitarras de Rock Band para Wii a su carpeta de RPCS3.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/instrepoinstall.gif "Instalando un perfil del Repo de Instrumentos")

La mayoría del tiempo, estos perfiles jalan sin configuración adicional. Por si acaso no, haz click derecho a Rock Band 3 y luego a "Change Custom Gamepad Configuration" (Cambiar configuración de controles personalizada). En este menú, cambia el control que estás usando en "Devices" (Dispositivo), al lado del botón de "Refresh" (Actualizar) hasta que empiece a jalar. Puedes cambiar esto mientras el juego esté abierto.

Estos perfiles están hechos para solo un instrumento. Puedes usar las páginas de los instrumentos para referir. También se pueden combinar perfiles si editas los archivos con un programa como "Notepad++" o "SublimeText."

Para hacer esto, necesitas abrir `Default.yml` y selecciona todo desde línea 2 hasta línea 86 para los perfiles que quieres combinar.
Págalo entre:
* Línea 88 a 172 para Jugador 2
* Línea 174 a 258 para Jugador 3
* Línea 260 a 344 para Jugador 4
* Línea 346 a 430 para Jugador 5
* Línea 432 a 516 para Jugador 6
* Línea 518 a 602 para Jugador 7

# Lista de Instrumentos:

## Baterías:
* [[Baterías MIDI]](https://hmxmilohax.github.io/rb3-pc/instrumentos/misc/mididrums) - Sin perfil/Solo para info. Requiere una batería con un Snare/Tarola, Bombo/Kick, 3 Platillos (Hi-Hat, Ride/Ritmo, Crash/Remate), y 3 Toms (Alto, bajo, piso). Puede ser conectados por USB o por un adaptador de MIDI a USB.
* [[Baterías con Roll Limitless]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Roll%20Limitless%20Drums.7z) - Requiere una batería con un Snare/Tarola, Bombo/Kick, 3 Platillos (Hi-Hat, Ride/Ritmo, Crash/Remate), y 3 Toms (Alto, bajo, piso). La batería necesita una salida MIDI.
	* Requiere [[configuración adicional]](https://hmxmilohax.github.io/rb3-pc/instrumentos/misc/rolllimitless)
* [[Baterías de Rock Band para Xbox 360]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Rock%20Band%20Drums.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/rbdrms)
* [[Baterías con adaptador MIDI PRO de Rock Band para Xbox 360]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20MIDI%20Pro%20Adapter%20Drums.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/mpa)
* [[Baterías de Guitar Hero para Xbox 360]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Guitar%20Hero%20Drums.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/ghdrms)
* [[Baterías de Guitar Hero para PlayStation 3]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PS3%20Guitar%20Hero%20Drums.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/ps3/ghdrms)
* [[Baterías de Rock Band para Wii]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Rock%20Band%20Drums.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/wii/rbdrms)
* [[Baterías de Guitar Hero para Wii]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Guitar%20Hero%20Drums.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/wii/ghdrms)

## Guitarras:
* [[Guitarras de Rock Band para Xbox 360]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Rock%20Band%20Guitar.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/rbgtrs)
* [[Guitarras de Rock Band para Wii]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Rock%20Band%20Guitars.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/wii/rbgtrs)
* [[Guitarras de Rock Band 4/Fortnite Festival para Xbox One/Xbox Series]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20One%20Rock%20Band%20Guitar.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/rb4gtrs)
	* Requiere [[configuración adicional]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/rb4gtrs)
* [[Guitarras Les Paul de Guitar Hero para Xbox 360]](https://github.com/hmxmilohax/rb3-pc/blob/main/instrument-repo/Xbox%20360%20Guitar%20Hero%20Les%20Paul.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/ghlp)
* [[Guitarras Les Paul de Guitar Hero para Wii (con adaptador de Raphnet)]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20%5BRaphnet%5D.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/wii/raphlp)
* [[Guitarras de Guitar Hero para Wii (Ardwiino PI Pico)]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Wii%20Guitar%20Hero%20Les%20Paul%20%5BPi%20Pico%5D.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/misc/picolp)
* [[Guitarras Xplorer de Guitar Hero para Xbox 360]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Guitar%20Hero%20Xplorer.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/xplorer)
	* Requiere [[configuración adicional]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/xplorer)
* [[Guitarras "Genericaster" de Guitar Hero (World Tour y despues) para PlayStation 3]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PS3%20Guitar%20Hero%20Genericaster.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/ps3/ghwttar)
* [[Guitarras "Genericaster" de Guitar Hero (World Tour y despues) para Xbox 360 ]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/Xbox%20360%20Guitar%20Hero%20Genericaster%20Guitar.7z) - [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/ghwttar)
* [[Guitarras SG de Guitar Hero para PlayStation 2]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PS2%20Guitar%20Hero%20SG%20Guitar.7z) - **REQUIERE UN ADAPTADOR SPECIFICO**. [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/misc/ps2sg)
* [[Guitarras Les Paul de Guitar Hero para PlayStation 3]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PS3%20Guitar%20Hero%20Les%20Paul%20Guitar.7z) - **NO SE RECOMIENDA USAR ESTA GUITARRA**. [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/ps3/ghlp)
* [[Guitarra de Guitar Hero World Tour para PC/Mac]](https://github.com/hmxmilohax/rb3-pc/raw/main/instrument-repo/PC-Mac%20Guitar%20Hero%20World%20Tour%20Genericaster.7z) - **NO SE RECOMIENDA USAR ESTA GUITARRA**. [[Más información]](https://hmxmilohax.github.io/rb3-pc/instrumentos/misc/pcghwt)

## Mandos/Padtar:
* [[DualShock 3/Sixaxis para PlayStation 3]](https://hmxmilohax.github.io/rb3-pc/instrumentos/ps3/ds3) - Sin perfil/Solo para info.
* [[Control de Xbox One/Series]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/xb1pad) - Sin perfil/Solo para info.
* [[Teclado de PC]](https://hmxmilohax.github.io/rb3-pc/instrumentos/misc/pckeyboard) - Sin perfil/Solo para info.

## Pianos:
* [[Teclados MIDI]](https://hmxmilohax.github.io/rb3-pc/instrumentos/misc/midikeys) - Sin perfil/Solo para info.
* [[Teclados de Rock Band para PlayStation 3]](https://hmxmilohax.github.io/rb3-pc/instrumentos/ps3/rbkeys) - Sin perfil/Solo para info.
* [[Teclados de Rock Band para Xbox 360]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/rbkeys) - Sin perfil/Solo para info.
* [[Teclados de Rock Band para Wii]](https://hmxmilohax.github.io/rb3-pc/instrumentos/wii/rbkeys) - Sin perfil/Solo para info.

## Guitarras Pro:
* [[Guitarras PRO de Rock Band 3 para PlayStation 3]](https://hmxmilohax.github.io/rb3-pc/instrumentos/ps3/protar) - Sin perfil/Solo para info.
* [[Guitarras PRO de Rock Band 3 para Xbox 360]](https://hmxmilohax.github.io/rb3-pc/instrumentos/xbox/protar) - Sin perfil/Solo para info.
* [[Guitarras PRO de Rock Band 3 para Wii]](https://hmxmilohax.github.io/rb3-pc/instrumentos/wii/protar) - Sin perfil/Solo para info.

## RECHAZADOS:

* Rock Band Guitars (versiones de PS3)
	* Funcionan sin configuración.
* Rock Band Drums (versiones de PS3)
	* Funcionan sin configuración.

## CRÉDITOS:

* [[TheNathannator]](https://github.com/TheNathannator) [[PlasticBand GitHub]](https://github.com/TheNathannator/PlasticBand) por documentación de instrumentos tremenda.
* [[Jnack]](https://www.youtube.com/@jnackmclain)
* [[Linos]](https://www.youtube.com/@LinosMelendi)
* [[KrazzyKlown]](https://www.youtube.com/@KrazzyKlown)
* [[gonakil1ya]](https://linktr.ee/Gonakil1ya)
* [[GamerPerson22]](https://www.youtube.com/channel/UCC5SlXPlnlGwBG7w6mvfx8g)
* [Derd]
* [Uzny]
* [16bitblastprocessing]
* [heartworthbreaking]
* [[cas]](https://www.youtube.com/channel/UCw2JKh7_Zt65kjENqjnvm_g)
* [[scott0852]](https://twitter.com/scott0852)
* [[SlothDemon]](https://www.youtube.com/@SlothDemon1991)
* [[Clone Hero Wiki]](https://wiki.clonehero.net/)
