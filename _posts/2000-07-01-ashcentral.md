---
title: AshCentral
author: Carl Mylo
date: 2000-07-01
category: Español
layout: post
---

**ESTA PARTE ESTA BAJO RECONSTRUCCION!**

<br/>

# Conexión Directa

Si no estás utilizando una Guitarra Mustang Pro de PS3 y un Teclado Rock Band 3 de PS3 con sus receptores respectivos, [[puedes avanzar a la siguiente sección.]](#problemas-y-soluciones)

Para comenzar, **cierra RPCS3** y conecta el receptor del instrumento a tu computadora.

Ahora, [**\[ve al sitio de Zadig\]**](https://zadig.akeo.ie/) y **descárgalo**. Cuando termine de bajar, **ábrelo**.
[![Una captura de la pagina de Zadig](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/zadigdles.png)](https://zadig.akeo.ie/ "Bajar a Zadig")


Haz click en **Options** (Opciones) y luego en **List All Devices** (Listar dispositivos).  
![Una captura de Zadig mostrando "Listar todos los dispositivos" resaltado bajo "Opciones".](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/zadiglistall.png "Zadig: Opciones: Listar todos los dispositivos")

Deberías ver una lista de dispositivos ahora. **Selecciona tu Instrumento Pro de Rock Band 3**. En este ejemplo, estamos utilizando la Guitarra Mustang Pro, que aparece como "Harmonix RB3 Mustang Guitar for PlayStation® 3".  
![Una captura de Zadig mostrando "Harmonix RB3 Mustang Guitar for PlayStation® 3" resaltado en la lista de dispositivos.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/zadigsel.png "Zadig: Harmonix RB3 Mustang Guitar for PlayStation® 3")

Después de seleccionar el dispositivo correcto, deberías ver la opción para reemplazar el controlador. **ASEGÚRATE DE QUE SOLO ESTÁS REEMPLAZANDO EL CONTROLADOR DEL INSTRUMENTO PRO DE ROCK BAND 3**. **Haz click en "Replace Driver" (Reemplazar controlador)**.  
![Una captura de Zadig con "Reemplazar controlador" resaltado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/zadigreplace.png "Zadig: Reemplazar controlador")

Aparecerá una advertencia. **Nuevamente, asegúrate de haber seleccionado tu Guitarra Mustang Pro o teclado de Rock Band 3.** Después de haberlo verificado, haz click en "**Yes**" (Sí).  
![Una captura de Zadig advirtiendo al usuario que está a punto de modificar un controlador del sistema, con "Sí" resaltado](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/zadigreplace.png "Zadig: Advertencia - Controlador del sistema")

Luego, se instalará el controlador. Como dice el programa, esto puede llevar algunos minutos.  
![Una captura de Zadig en medio de una instalación de controladores.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/zadigprogress.png "Zadig: Instalando controlador...")

Si todo sale bien, verás este mensaje:  
![Una captura de Zadig que indica al usuario que el controlador se instaló correctamente, con "Cerrar" resaltado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/zadigdone.png "Zadig: Éxito")

**Cierra Zadig** y, con el receptor todavía conectado, **abre RPCS3** y **abre Rock Band 3**.

Enciende tu controlador y deberías ver que automáticamente se le asigna un número de jugador.
![Una imagen de una Guitarra Mustang Pro con el LED del segundo jugador encendido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/protaron.png "Guitarra Mustang Pro de Fender: Jugador 2")

Del mismo modo, en Rock Band 3, verás el instrumento listo para unirse.  
![Una captura de Rock Band 3 con una Guitarra Pro lista para unirse.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/pass/rb3player.png "Rock Band 3: Guitarra Pro lista para unirse")

<br/>

# Problemas y Soluciones


*   **_Audio Corrupto_**

	* [![Un miniretrato que dice "click here for audio example" (haz clic aqui por un ejemplo de sonido).](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/xtra/badaudio.png)](https://www.youtube.com/watch?v=UoCMEQbNThs&t=20s "Rock Band 3 Deluxe - Low-End Low-Buffer Autoplay - YouTube")
	* Aumenta el "Audio Buffer Duration" como se menciona en [[la pestaña de Audio de la configuración personalizada]](#Audio) hasta que el Audio Entrecortado se detenga. 100 ms es un buen comienzo para computadoras de baja gama.

*   **_Problemas generales de rendimiento_**
	* Cambia el plan de energía de tu computadora a "Máximo rendimiento"
	*   Regresa y Lee las sugerencias para PCs de gama baja en la [[sección de configuración personalizada]](#cpu).
	*   Instala [[Rock Band 3 Deluxe]](https://nightly.link/hmxmilohax/rock-band-3-deluxe/workflows/build/main/RB3DX-PS3.zip) y deshabilita efectos adicionales en el apartado "Deluxe Settings". Si no lo tienes, no seguiste la guía.
	*	Cierra el cliente de Discord y abre Discord en tu navegador o tu celular.

*   **_Los instrumentos o accesorios de los personajes flotan o los traspasan_**
	*   Actualmente no hay ninguna solución para esto. Si te pasa esto esto, [[por favor reporta tus descubrimientos en el GitHub de RPCS3.]](https://github.com/RPCS3/rpcs3/issues/8408)

*   **_El juego no se llena en toda la pantalla_**
	*   Activa la opción "Tamaño" en las opciones de RB3.

*   **_El juego tiene retraso de audio o notas_**
	*   Entra a calibración en el menú de opciones de RB3 si no lo has hecho. Deshabilita la opción "Dolby Digital" en el mismo menú.

*   **_El juego crashea cuando practico en guitarra/bajo regular_**
	*   No leíste la guía por weon y se te olvido instalar a Rock Band 3 Deluxe, porque Rock Band 3 Deluxe arregla esto.
	
*   **_No puedo usar la Calibración Automática_**
	*   La calibración automática solo funciona con las guitarras de PS3 con conexión directa.

*   **_El juego se traba al ponerle nombre a un personaje_**
	*   Esto no debe de pasar en las versiones nueva de RPCS3. Diciendo eso, como quiera sugiero que uses un control standard para cualquier personalización porque unos instrumentos no tienen los botones requeridos para escribir en el teclado virtual.

*   **_Navegando la biblioteca me da pausas largas_**
	*   Ctm. Se te olvido poner "Network Status" a "Connected" en la [[pestaña "Network" al hacer la configuración personalizada]](#network) para Rock Band 3, como te dijo la guía.

*   **_Instrumentos de PS3 se detectan como dos_**
	*   Creaste una [[configuración de controladores personalizada]](#controladores) para un control de PS3, que usualmente no se necesita. Desborra la configuración del controlado y todo debe de estar bien.

- **_[Rock Band 3 Deluxe] Crasheo en el video de introducción_**
  * Tienes archivos de Rock Band 3 Deluxe para una versión vieja. Ve a la carpeta del juego en `dev_hdd0\game\BLUS30463\USRDIR` y desborra todos los archivos con extensión `.dta`, excepto a `dx_high_memory.dta`.

*   **_[Bateria Pro] Golpear dos platillos se registra como un tambor_**
	*   Este es un problema conocido de Rock Band 3 que afecta todas las versiones, incluso las de consolas. Puedes comprar un Roll Limitless, que arregla esto. También puedes tocar estas cosas con un [[flam/mordente]](https://es.wikipedia.org/wiki/Rudimento#Terminolog%C3%ADa). Por favor siéntete pregunta en el [**[servidor de Discord de MiloHax]**](https://rb3dx.neocities.org/discord).

*   **_\[ONLINE\] No puedo encontrar al tercer o cuarto jugador_**
	*   En la configuración Personalizada de Rock Band 3, [[ve a la pestaña de "Network" de configuración personalizada]](#network) y asegúrate de tener activado la opción "Enable UPNP". Si por alguna razón no puedes activar el UPNP, tendrás que redireccionar el puerto 9103 (UDP) en tu cortafuegos . **No actives el UPNP mientras estas redireccionando el puerto** ya que esto puede causar crasheos.

*   **_\[ONLINE\] Crasheo cuando busco jugadores._**
  - Si tienes UPNP prendido en la Configuración Personalizada de Rock Band 3 [[sección de Network]](#network), deberás desactivarlo y [[buscar cómo configurar el reenvío de puertos en tu enrutador]]([https://www.noip.com/support/knowledgebase/general-port-forwarding-guide](https://es.wikihow.com/configurar-el-reenv%C3%ADo-de-puertos-en-un-router)).
	
*   **_\[ONLINE\] Al tratar de conectar a GoCentral el juego se queda en "Registering Account_**
	*   Puede que hayas perdido la conexión a RPCN o GoCentral y tendrás que reiniciar el Juego. Si continuas teniendo esto luego de haber reiniciado, ve al menú de arriba en RPCS3 a, "Configuration" > "RPCN" > "Account" > "Test Account" luego reinicia el juego para forzar una reconexión.

*   **_\[ONLINE\] Me sigo descontando mientras juego en linea_**
	*   Chequea que no estés bajando algo y que tu conexión al internet no este sobrecargada. Si cambiaste tu VBlank a mas de 60 Hz, bájalo de vuelta a 60 Hz. Además, necesitas tener una conexión estable tanto con RPCN y los servidores de GoCentral.

*   **_"Seguí todos los pasos y todavía tengo crasheos/mal rendimiento"_**
	*   Revisa nuevamente para asegurarte de que has seguido cada paso correctamente. Esta guía ha sido probada y ha demostrado funcionar para muchas personas con diferentes tipos de hardware. Si estás absolutamente seguro de haber seguido cada paso correctamente, es muy probable que el archivo del juego que tienes esté dañado en un 90%, que haya un 9% de posibilidades de que tu computadora se haya quedado sin espacio en disco, y un 1% que la chingaste. Si quieres, puedes mandarme un mensaje por [**[el servidor de Milohax]**](https://rb3dx.neocities.org/discord). Yo hablo Español.

*	**_"No mencionaste ajustando (opcion) en la guia, pero a mi me ayudo."_**
	* [[Abre un asunto nuevo]](https://github.com/carlmylo/rb3-pc/issues/new) o mandarme un mensaje por [**[el servidor de Milohax]**](https://rb3dx.neocities.org/discord) con tu sugerencia. Si es verdad, lo puedo incluir en la guía.

<br/>

# Conclusión

Eso es todo! Ahora (con un poco de suerte) tienes un manera funcional para jugar Rock Band 3 en tu computadora. Mientras estas acá, porque no te unes a algunas comunidades que están ayudando a mantener viva la Comunidad de Rock Band?

<div align="center">

**Rock Band 3 Deluxe/Milohax:** 

[![Rock Band 3 Deluxe Logo](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/xtra/rb3dx.gif)](https://rb3dx.neocities.org/ "Rock Band 3 Deluxe")

</div>

Milohax son los desarrolladores de Rock Band 3 Deluxe, que es esencial para jugar Rock Band 3. **[\[Descárgalo aquí\]](https://rb3dx.neocities.org/)**. Además de [[todas la funciones que agrega]](https://rb3dx.neocities.org/features), también han desarrollado mods para [Guitar Hero 1](https://github.com/Milohax-archive/Guitar-Hero-Deluxe), [Guitar Hero 2 (para Xbox 360](https://github.com/hmxmilohax/Guitar-Hero-II-Deluxe-360) y tambien [para el PS2](https://github.com/Milohax-archive/Guitar-Hero-Deluxe)s), [Dance Central 1](https://github.com/hmxmilohax/dance-central-1-deluxe), [Dance Central 3](https://github.com/hmxmilohax/dance-central-3-deluxe), [Rock Band 1](https://github.com/hmxmilohax/rock-band-1-deluxe), [Rock Band 2](https://github.com/hmxmilohax/rock-band-2-deluxe), [Lego Rock Band](https://github.com/Milohax-archive/lego-rock-band-deluxe), [Green Day Rock Band](https://github.com/Milohax-archive/greenday-rock-band-deluxe), [Rock Band Blitz](https://github.com/Milohax-archive/rock-band-blitz-deluxe) y [The Beatles: Rock Band](https://github.com/Milohax-archive/beatles-rock-band-deluxe). [Puedes \[unirte al servidor de MiloHax\]](https://rb3dx.neocities.org/discord) aqui.


<div align="center">

**RBEnhanced:**

[![RBEnhanced Logo](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/xtra/rbe.png)](https://rb3e.rbenhanced.rocks/ "RBEnhanced")

</div>

Desarrolladores del Increible mod RBEnhanced el cual solamente existe para Xbox 360 y Wii. Los mismos desarrolladores también ayudan y mantienen el servidor de GoCentral que fue la manera original de jugar Rock Band 3 en linea en Xbox, PS3, y Wii por el Momento. Puedes [**\[unirte al servidor de RBEnhanced Aqui\]**](https://discord.gg/6rRUWXPYwb).

Agradecimientos especiales a:

*	[SlothDemon](https://www.youtube.com/@SlothDemon1991) por ayudar a traducir esta guía y ayudarme a recordar como escribir Español.
*   [DarkRTA](https://www.youtube.com/@darkrta), [Linos](https://www.youtube.com/@LinosMelendi), [Jnack](https://www.youtube.com/@jnackmclain), [Hughtobasíc](https://www.youtube.com/@thisisRK), [ihatecompvir](https://www.youtube.com/@ihatecompvir1591), and [LysiX](https://www.youtube.com/@LysiX) por informacion tecnica sobre RPCS3 y Rock Band 3.
* [knvtva](https://github.com/knvtva) por crear y mantener a AshCentral, la mejor manera de jugar Rock Band 3 en linea.
*   qfoxb, [SlothDemon](https://www.youtube.com/@SlothDemon1991), [Jnack](https://www.youtube.com/@jnackmclain) (el cual hizo pruebas por 40 horas xd), knvtva, y 1osks por reportar resultados.
*   RPCS3 Wiki por tener una cantidad decente de información sobre los Controladores y los Traspasos Via USB.
*   [TheNathannator](https://github.com/TheNathannator) por su [GitHub de PlasticBand](https://github.com/TheNathannator/PlasticBand) por la mejor documentación de controladores.


<div align="center">

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

</div>
