---
title: "Configuración Personalizada: I/O"
sidebar: espanol_sidebar
permalink: custom_config_io_es
folder: espanol
tags: [conf-pers, espanol]
summary: "Que cambiar bajo la pestaña de I/O dentro de la configuración personalizada de RPCS3"
series: "Configuración Personalizada"
weight: 5
---

**Asegúrate que tu instrumento de MIDI este conectado.**
**Haz la ventana mas grande si no puedes leer las opciones.**

![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando "Emulated MIDI Devices", "device type" y "device selection" resaltados en cuadros bronceados con contornos solidos, y "Pad Handler Mode" y "Keep Pads Connected" en un cuadro azul con contorno punteado.](https://carlmylo.github.io/rb3-pc/images/cust/io.png "I/O")

* ![Un cuadro azul con contorno punteado.](https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png "Cuadro azul") **Ajuste dependiendo de tu PC**: 
	* **Cambia "`Pad Handler Mode`"** (Modo de manejar controladores) **a "`Multi-threaded`"** si tienes una CPU con mas de 12 hilos/núcleos.

* ![Un cuadrado bronceado.](https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png "Cuadrado bronceado"): **Para jugadores de teclados MIDI, guitarra Pro, y baterías MIDI**:
	* 🎹 **[[Jugadores de teclado]](https://carlmylo.github.io/rb3-pc/ctrls_keys_midi_es){:target="_blank"}: Deja el "`Emulated MIDI type`" (Tipo de MIDI emulado) en "`Keyboard`" (teclado) y selecciona tu teclado o interfaz MIDI en el menú desplegable junto a él**.
	* 🎸 **[[Jugadores de Guitarra Pro]]((https://carlmylo.github.io/rb3-pc/ctrls_protar_midi){:target="_blank"}): Cambia el "`Emulated MIDI type`" (Tipo de MIDI emulado) de "`Keyboard`" (teclado) a "`Guitar (17 Frets)`"** (guitarra (17 trastes)) **si tienes una guitarra Pro Mustang, o "`Guitar (22 Frets)`"** (guitarra (22 trastes)) **si tienes una guitarra Pro Squier, luego selecciona tu interfaz MIDI a USB en el menú desplegable junto a él**.
	* 🥁 **[[Jugadores con Baterías MIDI]](https://carlmylo.github.io/rb3-pc/ctrls_drums_midi){:target="_blank"}: Cambia el "`Emulated MIDI type`" (Tipo de MIDI emulado) de "`Keyboard`" (teclado) a "`Drums`" (batería), y selecciona tu batería o interfaz MIDI en el menú desplegable junto a él**.
	* Si necesitas mas ayuda, dale otra visita a la [[pagina de instrumentos]](https://carlmylo.github.io/rb3-pc/ctrls_es).

<br/>

{% include custom/series_conf_pers_next.html %}

{% include links.html %}