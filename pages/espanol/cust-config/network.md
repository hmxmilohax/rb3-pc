---
title: "Configuración Personalizada: Network"
sidebar: espanol_sidebar
permalink: custom_config_net_es
folder: espanol
tags: [conf-pers, espanol]
summary: "Que cambiar bajo la pestaña de Network dentro de la configuración personalizada de RPCS3"
series: "Configuración Personalizada"
weight: 7
---

![Una captura de la configuración personalizada de Red de Rock Band 3, mostrando "Network Status (Connected)" resaltado en un cuadro verde con una línea discontinua, "IP/Hosts switches" (rb3ps3live.hmxservices.com=45.33.44.103), "PSN Status" (RPCN) y "Enable UPNP" (no marcado) resaltado en azul claro.](https://carlmylo.github.io/rb3-pc/images/cust/network.png "Network")

* ![Un cuadro verde con una línea discontinua.](https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Cambia "`Network Status`"** (estado de red) **a "`Connected`"** (conectado) **como en la imagen. Si la dejas en "`Disconnected`"** (desconectado), **el juego se congelara mientras navegas por la biblioteca de canciones.**

* ![Un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png "Cuadro bronceado") **Para jugar en linea**: 
	* Activa **"`Enable UPNP`"** (activar UPnP) o **reenvía el puerto 9103 (UDP) en tu cortafuegos. No actives UPNP mientras reenvías el puerto** porque esto puede causar crasheos.
	* Para jugar Rock Band 3 en linea, agrega la direccion IP de Rock Band Enhanced.
		* Cambia "`IP/Hosts switches`" a `rb3ps3live.hmxservices.com=45.33.44.103`

<br/>

{% include custom/series_conf_pers_next.html %}

{% include links.html %}