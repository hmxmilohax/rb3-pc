---
title: "Configuración Personalizada: Emulator"
sidebar: espanol_sidebar
permalink: custom_config_emu_es
folder: espanol
tags: [conf-pers, espanol]
summary: "Que cambiar bajo la pestaña de Emulator dentro de la configuración personalizada de RPCS3"
series: "Configuración Personalizada"
weight: 9
---

![Una captura de la configuración personalizada del emulador de Rock Band 3, mostrando "Show trophy popups", "Show PPU compilation hint", "Show Shader Compilation hint", "Start Games in fullscreen mode", y "Use native user interface." resaltados en cuadros bronceados con contornos solidos.](https://rb3pc.milohax.org/images/cust/emulator.png "Emulator")

Puedes dejar esto como quieras, pero consideraría ajustar estas opciones:

* ![Un cuadro bronceado con un contorno solido.](https://rb3pc.milohax.org/images/cust/smalltan.png "Cuadro bronceado") **Opcional**: 
	* **"Show trophy popups"** (Enseñar notificaciones de trofeos) - Simula la notificación de trofeos de la PS3. Personalmente desactivo esto ya que el juego tiene sus propias notificaciones.
	* **"Show PPU compilation hint"** (Enseñar notificaciones de PPUs compilándose) - Esto crea una notificación cuando RPCS3 esta compilando unidades del PPU. Esto solo sale si tienes la opción "Recompiler (LLVM)" activada en la pestaña de CPU.
	* **"Show shader compilation hint"** (Enseñar notificaciones de shaders compilándose) - Esto crea una notificación cuando RPCS3 esta compilando shaders. Ya sea si lo dejas activado o no ya es cosa tuya, pero debo decirte que esto es importante. Cuando ejecutas juegos de PS3, tiene que compilar shaders para "trasladar" los Gráficas de una PS3 a un formato que tu PC pueda usar. **El juego seguirá trabándose mientras esto pase** . **Esto pasa en TODOS las PC's.** Cuando termine de compilar un efecto, **esto usualmente ya no vuelve a pasar otra vez**. **La mejor forma de lidiar con esto es** simplemente **jugar al juego normalmente** y luego se ira rápidamente. También puedes activar el modo de "Autoplay" y dejar que el juego toque unas canciones hasta que pare de trabarse tanto.
	* **"Start games in Fullscreen mode"** (Empezar juego en pantalla llena) - Obviamente solo cambia el modo de pantalla completa cuando inicias Rock Band 3. Personalmente yo activo esto.
	* **"Use Native Interface"** (Usar interfaz nativa) - Desactivar esto hará que se remuevan todas las notificaciones de RPCS3 mientras estás jugando, incluyendo el teclado y fondo mientra el juego cargue. En su lugar, verás una interfaz más antigua. Antes ayudaba antes porque RPCS3 se trababa cuando estabas nombrando algo en el juego con un controlador instrumento. Esto ya no es necesario pero la interfaz nativa si causa problemas con rendimiento en ciertas computadores en los momentos raros que sale.

<br/>

{% include custom/series_conf_pers_next.html %}

{% include links.html %}