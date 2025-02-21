---
title: "Configuración Personalizada: CPU"
sidebar: espanol_sidebar
permalink: custom_config_cpu_es
folder: espanol
tags: [conf-pers, espanol]
summary: "Que cambiar bajo la pestaña de CPU dentro de la configuración personalizada de RPCS3"
series: "Configuración Personalizada"
weight: 2
---

![Una captura de la configuración personalizada de CPU para Rock Band 3, mostrando SPU Block Size, Thread Scheduler y Preferred SPU Threads resaltados en cuadros azules con contornos punteados.](https://carlmylo.github.io/rb3-pc/images/cust/cpu.png "CPU")

* ![Un cuadro azul con contorno punteado.](https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png "Cuadro azul") **Rendimiento mejorado, dependiendo en tu sistema**: 
	* **Cambia el "`SPU Block Size`"** (Tamaño de bloques del SPU) **a "`Mega`"** - Junta hilos de SPU para ser más pequeños, requiriendo menos núcleos/hilos. También tardara menos tiempo para iniciar el juego, dependiendo en tu sistema.
	* **Cambia el "`Preferred SPU Threads`"** (Hilos preferidos del SPU) **a "`1`", "`2`", "`3`", or "`4`"** - Puede ayudar a prevenir inestabilidades causadas por sobrecargas de la CPU. **Empieza con "`4`" y bájalo si no mejora**.
	- **Cambia "`Thread Scheduler`" (Programador de hilos) a "`RPCS3 Scheduler`"** (Programador RPCS3) **o "`RPCS3 Alternative Scheduler`"** (Programador alternativo RPCS3). - **¡SOLO PARA CPUs CON MÁS DE 12 HILOS!** Esto puede ayudar con la distribución de procesos para ayudar con rendimiento.

<br/>

{% include custom/series_conf_pers_next.html %}

{% include links.html %}