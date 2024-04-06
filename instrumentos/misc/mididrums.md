---
title: Batería MIDI
author: Carl Mylo
date: 
category: Instrumentos
layout: post
---

## NOTAS:

* No existe un perfil.
* Requiere una batería MIDI conectada por USB o por adaptador MIDI a USB.
	* **Tu batería MIDI necesita estar en canal de MIDI 10 y mapeado a modo "GM".**  Esto esta por defecto en mayoría de las baterías.
* Se requiere una version de [[RPCS3 actual]](https://rpcs3.net/download)
* By defecto:
	* START: Cierra la Hi-Hat tres veces rápidamente y luego pégale a la caja (snare).
	* SELECT: Cierra la Hi-Hat tres veces rápidamente y luego pégale a el aro de la caja (snare rim)
	* Atajo para escocer canciones: Cierra la Hi-Hat tres veces rápidamente y pégale al bombo (kick) con el pedal.**

## Instrucciones:

**Haz click derecho en Rock Band 3** en RPCS3, luego presiona "**Create Custom Configuration From Default Settings**" (Crear configuración personalizada basada en la configuración por defecto.)  

![Una captura del menú de clic derecho de RPCS3, mostrando "Change Custom Configuration" (Cambiar configuración personalizada) resaltado](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando "Emulated MIDI Devices", tipo de dispositivo y selección de dispositivos resaltados en cuadros bronceados con contornos sólidos.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/iod.png "I/O")
* ![Un cuadrado bronceado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Cuadrado bronceado"): : 
	* 🥁 **Cambia tu "Emulated MIDI type" (Tipo de MIDI emulado) de "Keyboard" (teclado) a "Drums" (batería), y selecciona tu batería o interfaz MIDI en el menú desplegable junto a él**.

### Configuración Adicional:

Puedes ajustar una variedad de opciones en el archivo `rb3drums.yml`, que esta colocado en la carpeta llamada `config` que esta donde tienes RPCS3. Necesitas empezar el juego una vez con tu batería MIDI configurada en la pestaña de I/O para que RPCS3 cree el archivo. Cualquier cambio a este archivo requiere que reinicies el juego.

### Remapeando:
Si tu batería tiene partes que necesitan ser configuradas, puedes usar `Midi id to note override: ""` para corregir notas.
* Para hacer esto:
	* Ve al sitio [[MIDI Monitor]](https://www.midimonitor.com/)
	* Toca la parte que quieres re-configurar para encontrar su el numero de nota MIDI ("Note #[number]").

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
* Quieres usar tu Hi-Hat cerrado para amarillo y Hi-Hat abierta para azul.
	* `Midi id to note override: "46=Ride"`

En `rb3drums.yml`, vas a encontrar `Combo Start`, `Combo Select`, `Combo Toggle Hold Kick`, que te van ayudar a configurar los que necesitas tocar para activar el botón START, SELECT, y el atajo para escocer canciones, respectivamente.

### Mapeando:

| **Numero de nota MIDI** | **Parte de batería** | **In-Game Action** |
|:--------:|:-------------------:|:-----------------:|
| **38**, 31, 34, 37, 39, 40 | Snare/Tarola | ![Tambor Rojo](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/rp.png "Tambor Rojo") |
| **48**, 50 | Tom Alto | ![Tambor Amarillo](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/yp.png "Tambor Amarillo") |
| **45**, 50 | Tom Bajo | ![Tambor Azul](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/bp.png "Tambor Azul") |
| **41**, 43 | Tom de piso | ![Tambor Verde](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/gp.png "Tambor Verde") |
| **22**, 26, 42, 46, 54 | Hi-Hat/Contras | ![Platillo Amarillo](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/yc.png "Platillo Amarillo") |
| **51**, 53, 56, 59 | Platillo Ride/de Ritmo | ![Platillo Azul](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/bc.png "Platillo Azul") |
| **49**, 52, 55, 57 | Platillo Crash/Remate | ![Platillo Verde](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/gc.png "Platillo Verde") |
| **33**, 35, 36 | Pedal/Kick | ![Pedal/Kick](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/btns/drms/rb/kp.png "Pedal/Kick") |
| **44** | Pedal de Hi-Hat | Pedal de Hi-Hat |
| **CC#4 (Control de pie)** | Posición del pedal de Hi-Hat | Deja cerrar/abrir el Hi-Hat |

![Plataforma](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/midi.png "Plataforma") 

![Control](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/instruments/mididrumscontroller.png "Control") 

[[Regresar al Repo de Instrumentos]](https://hmxmilohax.github.io/rb3-pc/english/instrumentrepo/#instrument-list)


Investigado por [[Linos]](https://www.youtube.com/@LinosMelendi)