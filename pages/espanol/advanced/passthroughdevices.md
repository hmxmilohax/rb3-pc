---
title: Conexión Directa
sidebar: espanol_sidebar
permalink: adv_passthrough_es
folder: espanol
tags: [avanzado, espanol]
summary: "Como configurar controles para tener conexión directa para RPCS3."
toc: false
---

Jugando con un Teclado o Guitarra Pro (Mustang) con sus receptores de PlayStation 3 es fácil. Igualmente si tienes un adaptador MIDI PRO para PlayStation 3. Solo requiere una configuración simple. Después de hacer esto, se pueden usar en el emulador. Esto es gracias Passthrough (conexión directa).

Para empezar, asegúrate que tengas el recibidor correcto para tu instrumento o el adaptador MIDI PRO.

| **Receptor para la<br>guitarra Mustang** | **Receptor para el<br>teclado inalámbrico** | **Adaptador MIDI PRO<br>(Cada modo)** |
|:------------------:|:---------------------:|:---------------------:|
| ![Receptor para la guitarra Mustang](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/recprotar.png "Receptor para la guitarra Mustang") | ![Receptor para el teclado inalámbrico](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/reckeys.png "Receptor para el teclado inalámbrico") | ![Adaptador MIDI PRO](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/ps3/recmpa.png "Adaptador MIDI PRO") |

**¡Toma en cuenta que tienes que repetir este proceso tres veces para cada "modo" del adaptador MIDI PRO!**

Después de comprobar que tengas el receptor o adaptador MIDI PRO correcto, **cierra RPCS3 y conecta el receptor del instrumento o adaptador MIDI PRO** a tu computadora.

## Instalando

Primero, [**\[ve al sitio de Zadig\]**](https://zadig.akeo.ie/){:target="_blank"} y **descárgalo**. Cuando termine de bajar, **ábrelo**.
[![Una captura de la pagina de Zadig](https://carlmylo.github.io/rb3-pc/images/pass/zadigdles.png)](https://zadig.akeo.ie/ "Bajar a Zadig")

Haz click en **Options** (Opciones) y luego en **List All Devices** (Listar todos los dispositivos).  
![Una captura de Zadig mostrando "Listar todos los dispositivos" resaltado bajo "Opciones".](https://carlmylo.github.io/rb3-pc/images/pass/zadiglistall.png "Zadig: Opciones: Listar todos los dispositivos")

Deberías ver una lista de dispositivos ahora. **Selecciona tu Instrumento Pro de Rock Band 3**. En este ejemplo, estamos utilizando la Guitarra Mustang Pro, que aparece como "Harmonix RB3 Mustang Guitar for PlayStation® 3".  
![Una captura de Zadig mostrando "Harmonix RB3 Mustang Guitar for PlayStation® 3" resaltado en la lista de dispositivos.](https://carlmylo.github.io/rb3-pc/images/pass/zadigsel.png "Zadig: Harmonix RB3 Mustang Guitar for PlayStation® 3")

Después de seleccionar el dispositivo correcto, deberías ver la opción para reemplazar el controlador. **ASEGÚRATE DE QUE SOLO ESTÁS REEMPLAZANDO EL CONTROLADOR DEL INSTRUMENTO PRO DE ROCK BAND 3**. **Haz click en "Replace Driver" (Reemplazar controlador)**.  
![Una captura de Zadig con "Reemplazar controlador" resaltado.](https://carlmylo.github.io/rb3-pc/images/pass/zadigreplace.png "Zadig: Reemplazar controlador")

Va a parecer una advertencia. **Otra vez, asegúrate de haber seleccionado el receptor/adaptador de tu instrumento Pro de Rock Band 3.** Después de haberlo verificado, haz click en "**Yes**" (Sí).  
![Una captura de Zadig advirtiendo al usuario que está a punto de modificar un controlador del sistema, con "Sí" resaltado](https://carlmylo.github.io/rb3-pc/images/pass/zadigreplace.png "Zadig: Advertencia - Controlador del sistema")

Luego, se instalará el controlador. Como dice el programa, esto puede llevar algunos minutos.  
![Una captura de Zadig en medio de una instalación de controladores.](https://carlmylo.github.io/rb3-pc/images/pass/zadigprogress.png "Zadig: Instalando controlador...")

Si todo sale bien, verás este mensaje:  
![Una captura de Zadig que indica al usuario que el controlador se instaló correctamente, con "Cerrar" resaltado.](https://carlmylo.github.io/rb3-pc/images/pass/zadigdone.png "Zadig: Éxito")

**Cierra Zadig** y, con el receptor/adaptador todavía conectado, **abre RPCS3** y **abre Rock Band 3**.

Enciende tu controlador y deberías ver que automáticamente se le asigna un número de jugador.
![Una imagen de una Guitarra Mustang Pro con el LED del segundo jugador encendido.](https://carlmylo.github.io/rb3-pc/images/pass/protaron.png "Guitarra Mustang Pro de Fender: Jugador 2")

Del mismo modo, en Rock Band 3, verás el instrumento listo para unirse.  
![Una captura de Rock Band 3 con una Guitarra Pro lista para unirse.](https://carlmylo.github.io/rb3-pc/images/pass/rb3player.png "Rock Band 3: Guitarra Pro lista para unirse")

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como un teclado de PC o un mando estándar.</b> {{include.content}}</div>

[[Haz click para instrucciones para configurar un mando o teclado.]](https://carlmylo.github.io/rb3-pc/ctrls_es#mandos){:target="_blank"}

## Desinstalando

Aplicando un controlador de Zadig restringirá a aplicaciones que usen Passthrough. Lo bueno es que es fácil revertir esto.

Abre el menú de Inicio y busca el `Administrador de dispositivos`.

![Una captura del menú de Inicio con un resultado de "Administrador de dispositivos".](https://carlmylo.github.io/rb3-pc/images/pass/startdevmanes.png "Administrador de dispositivos")

Baja a la categoría de `Dispositivos de bus seria universal (USB)` y haz click para expandirla.  
Haz click en el instrumento a cual le modificaste el controlador con Zadig y luego a `Desinstalar dispositivo`.  
En el ejemplo abajo, se uso la Guitarra Pro (`Harmonix RB3 Mustang Guitar for PlayStation 3®`).

![Una captura del Administrador de dispositivos, con un menú despegable abierto. El cursor esta sobre "Desinstalar dispositivo."](https://carlmylo.github.io/rb3-pc/images/pass/devmanes.png "Administrador de dispositivos")

En la pantalla que se abre, asegúrate de hacer click en `Intenta quitar el controlador para este dispositivo.`  
Después de eso, haz click en `Desinstalar` y eso es todo.  

![Una captura de la pantalla para Desinstalar el dispositivo. "Intenta quitar el controlador para este dispositivo" esta activado y el cursor esta sobre "Desinstalar."](https://carlmylo.github.io/rb3-pc/images/pass/devmanunes.png "Administrador de dispositivos")

Cuando desconectes y vuelvas a conectar el instrumento, regresara al controlador original.

{% include links.html %}