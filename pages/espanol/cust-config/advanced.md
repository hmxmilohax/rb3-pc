---
title: "Configuración Personalizada: Advanced"
sidebar: espanol_sidebar
permalink: custom_config_adv_es
folder: espanol
tags: [conf-pers, espanol]
summary: "Que cambiar bajo la pestaña de CPU dentro de la configuración personalizada de RPCS3"
series: "Configuración Personalizada"
weight: 8
---

![Una captura de la configuración personalizada avanzada, con "Driver Wake-Up Delay (1µ)" resaltado en un cuadro verde con una línea discontinua, "Exclusive Fullscreen Mode", "VBlank Frequency" y "Maximum Number of SPURS Threads" resaltados en cuadros azules con contornos punteados, y "Debug Console Mode" resaltado en un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/rb3-pc/images/cust/advanced.png "Advanced")

* ![Un cuadro verde con una línea discontinua.](https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Cambia el "Driver Wake-up Delay"** (Retraso de activacion de controlador) **a "20µ" si tu juego se congela luego de algunas canciones. Subelo a "40µ" si sigue pasando.** Si todavía sigue pasando (muy raro),  subele en incrementos de 20 cada vez.

* ![Un cuadro azul con contorno punteado.](https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* **Cambia a "Maximum Number of SPURS Threads"** (Máximo numero de hilos de SPURS) - Puede ayudar el rendimiento de computadoras con CPU de 4 núcleos/hilos, como [[CPUs de Intel i5 de la cuarta generación]](https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005){:target="_blank"}.

* ![Un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png "Cuadro bronceado"): **Recomendado**:
	* **Activa "Debug Console Mode"** (Modo de depuración) - Con esto activado al lado de la función "Large Heap" de Rock Band 3 Deluxe, fácilmente puedes darle mas memoria a Rock Band 3. Esto ayuda con la estabilidad y te deja instalar hasta 16000 canciones. Es recomendado que todos tengan esto activado. [[Haz click aquí para mas información.]](https://carlmylo.github.io/rb3-pc/adv_himem_es)
	* **Cambia el "Exclusive Fullscreen Mode"** (Modo de exclusividad de pantalla llena) **a "Prefer borderless fullscreen"** (preferir pantalla llena sin bordos) para prevenir posibles crasheos o desincronización al cambiar la prioridad del programa.

<br/>

{% include custom/series_conf_pers_next.html %}

{% include links.html %}