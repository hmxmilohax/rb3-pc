---
title: Guitarra Pro Fender Mustang de Rock Band 3 para Nintendo Wii
sidebar: controllers_es_sidebar
permalink: ctrls_protar_wii_es
folder: instrumentos
tags: [wii-es, midi-es, protarras, espanol]
summary: "Como configurar guitarras Fender Mustang Pro para Nintendo Wii en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/wii.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rbprotar.png" alt="Control" title="Control"></div>

## NOTAS
<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/rpcs3nomap.png" alt="¡NO mapeés este instrumento!" title="¡No uses Pads!"></div>
<div align="center"> <b>¡NO mapeés este instrumento por el menú de "Pads"!</b></div>

* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden causar que el juego se quede atorado. Es recomendado tener otra manera de controlar estos menos, como [[un teclado de PC o un mando estándar]](https://rb3pc.milohax.org/ctrls#gamepads_es){:target="_blank"}.
* Esto es para los jugadores que tienen sus guitarras PRO conectadas con una una interfaz de MIDI a USB.

## Advertencia de SYSEX

**¡Necesitas una interfaz de MIDI a USB que tome datos SYSEX!** Consulta el manual o el fabricante de tu interfaz para mas detalles.

| Interfaces de MIDI a USB <br> verificadas |
|:------------------:|
| **Focusrite** <br> Scarlett (4i4 o mejor) [Gen 3a] |
| **M-Audio** <br> Midisport Uno |
| **MOTU** <br> M2/M4 |
| **Roland** <br> UM-ONE mk2 |

## Instrucciones

Como no puedes conectar la guitarra con el receptor, necesitas conectarla con el puerto de MIDI por abajo.

>![Una imagen de una guitarra Mustang de Rock Band 3, con un puerto de MIDI estilo DIN con cinco pines resaltado en cuadro azul con contorno punteado.](https://rb3pc.milohax.org/images/midi/midimustang.png "Rock Band Mustang Pro Guitar")  

**Para conectarla a tu computadora, necesitarás un convertidor/interfaz de MIDI a USB**.

Aquí esta un ejemplo de un adaptador de MIDI a USB. Mayoría tiene una luz LED integrada para mostrar activad. **Para verificar que esta todo enchufado correctamente, debes de ver "MIDI In" parpadeando cuando le toques una nota**.

>![Una imagen de una interfaz de MIDI a USB.](https://rb3pc.milohax.org/images/midi/miditousb.png "Interfaz de MIDI a USB")  

**Si tienes una interfaz de audio, puede ser que ya tengas un puerto de MIDI** para tu computadora, ya que unas interfaces tienen puertos de MIDIs integrados. Por ejemplo, esta Scarlett tiene conexiones MIDI por detrás.

>![Una imagen del posterior de una Focusrite Scarlett, mostrando un puerto de USB y un salida/entrada MIDI por puerto DIN de cinco pines.](https://rb3pc.milohax.org/images/midi/midifs.png "Salida/Entrada MIDI de Focusrite Scarlett") 

Como fue dicho antes, necesitas [[una interfaz de MIDI a USB que toma datos de SYSEX]](#advertencia-de-sysex)

Decide cual manera es mas conveniente para ti y conecta tu guitarra pro a tu computadora.

Después de eso, **haz click derecho en Rock Band 3** en RPCS3, y luego en **"Change Custom Configuration"** (Cambiar configuración personalizada).  

![Una captura del menú de clic derecho de RPCS3, mostrando "Change Custom Configuration" (Cambiar configuración personalizada) resaltado.](https://rb3pc.milohax.org/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando "Emulated MIDI Devices", tipo de dispositivo y selección de dispositivos resaltados en cuadros bronceados con contornos sólidos.](https://rb3pc.milohax.org/images/cust/iog.png "I/O")

* ![Un cuadro bronceado con un contorno solido.](https://rb3pc.milohax.org/images/cust/smalltan.png "Un cuadrado bronceado.") :

	* 🎸 **Cambia tu "Emulated MIDI type"** (Tipo de MIDI emulado) **de "Keyboard"** (teclado) **a "Guitar (17 Frets)"** (guitarra (17 trastes)) **si tienes una guitarra Pro Mustang, o “Guitar (22 Frets)”** (guitarra (22 trastes)) **si tienes una guitarra Pro Squier, luego selecciona tu interfaz MIDI a USB en el menú desplegable junto a él.**


[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Implementado por [[Dark]](https://dark.ski/)