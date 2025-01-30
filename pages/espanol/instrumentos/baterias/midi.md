---
title: Batería MIDI
sidebar: controllers_es_sidebar
permalink: ctrls_drums_midi_es
folder: instrumentos
tags: [midi-es, baterias, espanol]
summary: "Como configurar una batería MIDI en RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/midi.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/mididrumscontroller.png" alt="Control" title="Control"></div>

## NOTAS:

* **NO mapeés este instrumento por el menú de "Pads".**
* Tu batería MIDI necesita:
	* **estar en canal de MIDI 10.**
	* **estar configurada a el mapeo de GM.**  
Esto debe de ser lo que viene por defecto con mayoría de las baterías MIDI. Consulta el manual de tu batería para estar seguro.
* D-Pad (Cruceta): Izquierda y D-Pad (Cruceta): Derecha no funcionan y no pueden ser usadas. Por esto, no vas a poder ajustar la velocidad de modo de practica o navegar por los entrenadores.
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) causan que el juego se quede atorado. Necesitas tener otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://carlmylo.github.io/docu-rpcs3/ctrls_pads_es){:target="_blank"}.

## Instrucciones:

**Si tu batería MIDI tiene un puerto de USB**, solo necesitas **conectarla a tu computadora**.  

>![Una imagen del cerebro de la batería MIDI, mostrando un puerto de USB](https://carlmylo.github.io/docu-rpcs3/images/midi/usbdrums.png "Batería de MIDI USB")  

**Si tu batería MIDI solo tiene una salida de MIDI, vas a necesitar un adaptador de MIDI a USB**.  

>![Una imagen del cerebro de la batería MIDI, mostrando un puerto MIDI estilo DIN de cinco pines.](https://carlmylo.github.io/docu-rpcs3/images/midi/mididrums.png "Batería de MIDI")  

Aquí esta un ejemplo de un adaptador de MIDI a USB. Mayoría tiene una luz LED integrada para mostrar activad. **Para verificar que esta todo enchufado correctamente, debes de ver "MIDI In" parpadeando cuando le pegues a un parche**. 

>![Una imagen de una interfaz de MIDI a USB.](https://carlmylo.github.io/docu-rpcs3/images/midi/miditousb.png "Interfaz de MIDI a USB")  

**Si tienes una interfaz de audio, puede ser que ya tengas un puerto de MIDI** para tu computadora, ya que unas interfaces tienen puertos de MIDIs integrados. Por ejemplo, esta Scarlett tiene conexiones MIDI por detrás.  

>![Una imagen del posterior de una Focusrite Scarlett, mostrando un puerto de USB y un salida/entrada MIDI por puerto DIN de cinco pines.](https://carlmylo.github.io/docu-rpcs3/images/midi/midifs.png "Salida/Entrada MIDI de Focusrite Scarlett") 

Decide cual manera es mas conveniente para ti y conecta tu batería MIDI a tu computadora.

Después de eso, **haz click derecho en Rock Band 3** en RPCS3 y luego en **"Change Custom Configuration"** (Cambiar configuración personalizada).  

![Una captura del menú de clic derecho de RPCS3, mostrando "Change Custom Configuration" (Cambiar configuración personalizada) resaltado.](https://carlmylo.github.io/docu-rpcs3/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

Entra la pestaña de I/O.  

![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando "Emulated MIDI Devices", tipo de dispositivo y selección de dispositivos resaltados en cuadros bronceados con contornos sólidos.](https://carlmylo.github.io/docu-rpcs3/images/cust/iod.png "I/O")
* ![Un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/docu-rpcs3/images/cust/smalltan.png "Un cuadrado bronceado.") : 
	* 🥁 **Cambia el "Emulated MIDI type"** (Tipo de MIDI emulado) **de "Keyboard"** (teclado) **a "Drums"** (batería), **y selecciona tu batería o interfaz MIDI en el menú desplegable junto a él**.

## Mapeo:
Mapeo Predeterminado:
* `START`: Cierra la Hi-Hat tres veces rápidamente y luego pégale a la snare (caja).
* `SELECT`: Cierra la Hi-Hat tres veces rápidamente y luego pégale a el snare rim (aro de la caja).
* Atajo para escocer canciones: Cierra la Hi-Hat tres veces rápidamente y pégale al kick (bombo) con el pedal.

| **Numero de nota MIDI** | **Parte de batería** | **Acción en Rock Band** |
|:--------:|:-------------------:|:-----------------:|
| **38**, 31, 34, 37, 39, 40 | Snare/Tarola | ![Parche Rojo](https://carlmylo.github.io/docu-rpcs3/images/btns/drms/rb/rp.png "Parche Rojo") |
| **48**, 50 | Tom Alto | ![Parche Amarillo](https://carlmylo.github.io/docu-rpcs3/images/btns/drms/rb/yp.png "Parche Amarillo") |
| **45**, 50 | Tom Bajo | ![Parche Azul](https://carlmylo.github.io/docu-rpcs3/images/btns/drms/rb/bp.png "Parche Azul") |
| **41**, 43 | Tom de piso | ![Parche Verde](https://carlmylo.github.io/docu-rpcs3/images/btns/drms/rb/gp.png "Parche Verde") |
| **22**, 26, 42, 46, 54 | Hi-Hat/Contras | ![Platillo Amarillo](https://carlmylo.github.io/docu-rpcs3/images/btns/drms/rb/yc.png "Platillo Amarillo") |
| **51**, 53, 56, 59 | Platillo Ride/de Ritmo | ![Platillo Azul](https://carlmylo.github.io/docu-rpcs3/images/btns/drms/rb/bc.png "Platillo Azul") |
| **49**, 52, 55, 57 | Platillo Crash/Remate | ![Platillo Verde](https://carlmylo.github.io/docu-rpcs3/images/btns/drms/rb/gc.png "Platillo Verde") |
| **33**, 35, 36 | Pedal/Kick | ![Pedal/Kick](https://carlmylo.github.io/docu-rpcs3/images/btns/drms/rb/kp.png "Pedal/Kick") |
| **44** | Pedal de Hi-Hat | Pedal de Hi-Hat |
| **CC#4 (Control de pie)** | Posición del pedal de Hi-Hat | Deja cerrar/abrir la Hi-Hat |

### Configuración Adicional:
Puedes ajustar varias cosas en el archivo `rb3drums.yml`, que esta colocado en la carpeta llamada `config` dentro de donde tienes RPCS3.
Abajo esta lo que hace cada opción.

| **Ajuste** | **Descripción** |
|:--------:|:-------------------:|
| `Pulse width ms: 30` | Duración (en ms) de cada nota en la batería. **Mejor déjala esto como esta**. |
| `Minimum velocity: 10` | La velocidad (intensidad) mínima para que una nota sea detectada. Cualquier nota con velocidad menos de este valor no va ser contada. Es como la sensibilidad de batería. |
| `Combo window in milliseconds: 2000` | Cuanto tiempo tienes para completar los combos de `START`, `SELECT` y el atajo para escocer canciones. Si no completas un combo dentro de este tiempo, sera ignorado. |
| `Stagger cymbal hits: true` | Si le pegas a dos platillos al mismo tiempo, uno va ser demorado por el tiempo que tiene puesto en `Pulse width ms`. **Mejor deja esto como esta**. |
| `Midi id to note override: ""` | Esto es para remapear lo que hace cada nota MIDI. Lee la sección de [[Remapeando]](#remapeando) para mas información. |
| `Combo Start: HihatPedal,HihatPedal,HihatPedal,Snare` | Este es el combo que emula el botón `START`. |
| `Combo Select: HihatPedal,HihatPedal,HihatPedal,SnareRim` | Este es el combo que emula el botón `SELECT`. |
| `Combo Toggle Hold Kick: HihatPedal,HihatPedal,HihatPedal,Kick` | Este es el combo que emula el atajo para escocer canciones. |
| `Midi CC status: 176` | El byte que determina el estatus. Puede ser notado como `0xB0`. **Mejor deja esto como esta**. |
| `Midi CC control number: 4` | El Control Continuado/Continous Controller (CC) que esta a cargo del pedal de Hi-Hat. **Mejor deja esto como esta**. |
| `Midi CC threshold: 64` | Esto es el punto medio del pedal de Hi-Hat, que separa si esta cerrado o abierto. |
| `Midi CC invert threshold: false` | Si lo cambias a `true`, invierte el punto de pedal mencionado arriba. |

#### Remapeando:
Si tu batería tiene partes que necesitan ser cambiadas, puedes usar `Midi id to note override: ""` para corregir notas.
* Para hacer esto:
	* Ve al sitio [MIDI Monitor](https://www.midimonitor.com/){:target="_blank"}
	* Toca la parte que quieres re-configurar para encontrar su numero de nota MIDI (`Note #[numero]`).

El archivo usa estos nombres para notas:

`Kick`  
`HihatPedal`  
`Snare`  
`SnareRim`  
`HiTom`  
`LowTom`  
`FloorTom`  
`HihatWithPedalUp`  
`Hihat`  
`Ride`  
`Crash`

Ejemplos de cambios comunes:
* El platillo azul esta configurado a `Note #51` y el platillo verde esta configurado a `Note #49` pero tu batería los tiene al revés.
	* `Midi id to note override: "49=Ride,51=Crash"` va a reversar los platillos para que estén sean mejor para Rock Band 3.
* Quieres usar tu Hi-Hat cerrada para amarillo y Hi-Hat abierta para azul.
	* `Midi id to note override: "46=Ride"`

[[Regresar a la lista de instrumentos]](https://carlmylo.github.io/docu-rpcs3/ctrls_es#lista-de-instrumentos)

Investigación por [[Linos]](https://www.youtube.com/@LinosMelendi){:target="_blank"}  
Implementado por [[nswarm]](https://github.com/nswarm){:target="_blank"}