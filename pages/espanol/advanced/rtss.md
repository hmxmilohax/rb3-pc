---
title: Suavizar fotogramas con RTSS
sidebar: espanol_sidebar
permalink: adv_rtss_es
folder: espanol
tags: [avanzado, espanol]
summary: "Como agregar mas canciones Rock Band 3."
toc: false
---

Rock Band 3 es un juego en cual se requiere tener FPS fluidas. Cada vez que hay un tirón o inestabilidad, la pista de notas se vera rara, cual puede causar distracciones. Aveces, el limitador de fotogramas de RPCS3 no ayuda con esto. Para arreglar esto, puedes usar Rivatuner Statistics Server (o RTSS).

## Configuración Inicial:

Para que todo funcione bien, primero debes de cambiar unas cosas en RPCS3.

Primero, **haz click derecho en Rock Band 3** en RPCS3, luego presiona “**Change Custom Configuration**” (Cambiar Configuración Personalizada)  
![Una captura del menú de clic derecho de RPCS3, mostrando "Change Custom Configuration" (Cambiar configuración personalizada) resaltado.](https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

En la pestaña de GPU:
* Cambia "`Framelimit`" a "`Off`"
* Desactiva la opción de "`VSync`" si la tienes activada.  

![Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando "VSync" y "VSync" en un cuadro azul con contorno punteado.](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/rpcs3disable.png "GPU")

¡Recuerda de hacer click en "`Apply`" y luego "`Save custom configuration`" después de hacer ajustes!  
Cuando termines, cierra RPCS3.

Ahora, ve al [[sitio de descarga para Rivatuner Statistics Server.]](https://www.guru3d.com/download/rtss-rivatuner-statistics-server-download/).  
Haz click aquí para ir al [[sitio de descarga para Rivatuner Statistics Server.]](https://www.guru3d.com/download/rtss-rivatuner-statistics-server-download/)  
![Una captura del sitio de descarga para Rivatuner Statistics Server. El cursor esta sobre  "Download Version 7.3.6 Final."](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/rtssdl.png "Guru3D RTSS Rivatuner Statistics Server Download 7.3.6 Final")


Se va descargar un archivo `.zip` después de un poco tiempo.  
![Una captura con el archivo .zip de RTSS que contiene el instalador.](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/rtssdlbrowseres.png "[Guru3D.com]-RTSS.zip")

Cuando termine de descargar, abre el instalador dentro del archivo `.zip` y instálalo.
![Una captura del instalador de RTSS, en la ultima pagina.](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/install6.png "[Guru3D.com]-RTSS.zip")

Ve al menú de Inicio y busca "`RivaTuner Statistics Server`" o "`RTSS`" para abrir la aplicación.  
![Una captura del menu de Inicio buscando "RivaTuner Statistics Server".](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/rtssstartes.png "Start search")


Cuando se abra RTSS, estaras en el perfil `Global` por defecto.  
En este perfil:
* Cambia "`Application detection level`" a `None`.
* Cambia "`Show On-Screen Display`" a `Off`.  

![Una captura de RivaTuner Statistics Server, resaltando "Show On-Screen Display", "Application detection level" y "Add" en un cuadro azul con contorno punteado.](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/rtssglobal.png "Rivatuner Statistics Server: Global")

Después de esos dos ajustes, haz click en "`Add`".  
Un explorador de archivos se va abrir. Localiza tu carpeta de RPCS3 y elige la aplicación de `rpcs3`.  
![Una captura de un explorar de archivos con el titulo "Abrir." RPCS3 esta seleccionado y esta abajo de un cursor.](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/rtssaddrpcs3.png "Abrir")

Cuando agregues a RPCS3, estarás en el perfil de `rpcs3.exe`.
En este perfil:
* Cambia "`Application detection level`" to `Low`.
* Haz click derecho en "`Framerate limit`" y seleciona el monitor que estés usando.
	* Alternativamente, puedes hacer click en el numero y entrar un FPS specifico o elegir el limite de frecuencia de actualización variable.  
![Una captura de RTSS, resaltando "Application detection level" y "Framerate limit" en un cuadro azul con contorno punteado. "Framerate limit" tiene un menú despegable con el cursor sobre un monitor.](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/rtssrpcs3.png "Rivatuner Statistics Server: rpcs3.exe")

## Uso:

Después de la configuración inicial, solo tienes que abrir RTSS para tener FPS fluidas y suaves.  
Si quieres hacerlo mas fácil todavía, puedes activar la opción de "Start with Windows" (Abrir con Windows) en RTSS para que abra cuando se encienda tu compu.

Para tener la mejor experiencia con RTSS, desactiva VSync en el menú de gráficas dentro de Rock Band 3 Deluxe:
* `Menú > Opciones > Configuración Deluxe > Gráficos > VSync`  
![Una captura del menú de Gráficos dentro de Deluxe. VSync esta seleccionada y desactivada.](https://carlmylo.github.io/rb3-pc/images/xtra/rtss/rb3vsynces.png "VSync: Desactivado")

{% include links.html %}