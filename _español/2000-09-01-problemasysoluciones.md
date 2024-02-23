---
title: Problemas y Soluciones
author: Carl Mylo
date: 2000-09-01
category: Español
layout: post
---

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
