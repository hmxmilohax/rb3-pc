---
title: Configuración Rápida
author: Carl Mylo
date: 2000-06-01
category: Español
layout: post
---

Estos archivos son para personas que quieren jugar sin hacer tanta configuración. Como quiera recomiendo que hagas una [[configuración personalizada]](#configuración-personalizada) para ajustar todo a lo mejor que pueda tu computadora.  
**DEBES de tener** [[**Rock Band 3 Deluxe instalado**]](https://rb3dx.neocities.org/install) o no funcionaran a su máximo potencial. Si no lo tienes instalado en este momento, también no estas leyendo la guía.

Los jugadores que desean utilizar [[micrófonos]](#audio), [[guitarras Pro con cable, teclados USB/MIDI]](#io), o [[guitarras PS3 Mustang o teclados RB3 con receptores]](#conexión-directa) todavía requieren configuración adicional.

* [[Configuración recomendada]](https://github.com/carlmylo/rb3-pc/raw/main/config/customconfig/recommended_es.zip) - Esta configuración es para computadoras que son igual (o mejor) que [los requisitos recomendados](#requisitos).
* [[Configuración mínima]](https://github.com/carlmylo/rb3-pc/raw/main/config/customconfig/minimum_es.zip) - Esta configuración es para computadoras que son igual (o mejor) que [los requisitos mínimos](#requisitos).

Para usar estos archivos, **haz click en las configuración que quieres bajar y luego extrae los archivos en la carpeta donde esta RPCS3**. Las carpetas se combinaran si lo hiciste bien.
El ejemplo abajo enseña la configuración recomendada (recommended.zip) siendo instalada.

![Una animacion de "config" y "dev_hdd0" de "recommended.zip" siendo arrastrado a la carpeta de RPCS3.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/quickconf.gif "Recommended.zip")

Para obtener más información sobre estas configuraciones, [[consulta la pagina de configuraciones rápidas]](https://github.com/carlmylo/rb3-pc/blob/main/config/customconfig/readme_es.md#informacion).

<br/>


# Configuración Personalizada:

**Haz click derecho en Rock Band 3** en RPCS3, luego presiona "**Create Custom Configuration From Default Settings**" (Create configuración personalizada basada en la configuración por defecto)  
![Una captura del menú de clic derecho de RPCS3, mostrando "Create Custom Configuration From Default Settings" resaltado](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/rpcs3customconfig.png "Create Custom Configuration From Default Settings")

Esto puede parecer demasiado difícil por la gran cantidad de opciones, pero he coloreado las cosas que vas a ajustar. Todo lo que no esté coloreado debe estar en las opciones predeterminadas.

| COLOR | SIGNIFICADO |
|---|---|
| ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/biggreen.png "Cuadro verde") | **REQUERIDO** |
| ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/bigblue.png "Cuadro azul") | **Para Rendimiento** |
| ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/bigtan.png "Cuadro bronceado") | **Recomendado** |

Iremos pestaña por pestaña, comenzando con:

<br/>

## CPU


![Una captura de la configuración personalizada de CPU para Rock Band 3, mostrando SPU XFloat Accuracy, Thread Scheduler, SPU Block Size, y Preferred SPU Threads resaltados en cuadros azules con contornos punteados.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/cpu.png "CPU")
* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Cuadro azul") **Rendimiento mejorado, dependiendo en tu sistema**: 
	* **Cambia el "SPU Block Size"** (Tamaño de bloques del SPU) **a "Mega"** - Para juntar hilos de SPU a ser más pequeños, requiriendo menos núcleos/hilos. También tardara menos tiempo para iniciar el juego, dependiendo en tu sistema.
	* **Cambia el "Preferred SPU Threads"** (Hilos preferidos del SPU) **a "1", "2", "3", or "4"** - Puede ayudar a prevenir inestabilidades causadas por sobrecargas de la CPU. **Empieza con 4 y bájalo si no mejora**.
	- **Cambia "Thread Scheduler" (Programador de hilos) a "Programador RPCS3" (RPCS3 Scheduler) o "RPCS3 Alternative Scheduler" (Programador alternativo RPCS3)**. - **¡SOLO PARA CPUs CON MÁS DE 12 HILOS!** Esto puede ayudar con la distribución de procesos para ayudar con rendimiento.
	* **SI NADA AYUDA, cambia el "SPU XFloat Accuracy"** (Precisión de Flotante x del SPU) **a "Relaxed"** (Relajada) - Cambiar eso ayuda un poco con rendimiento pero, **romperá el modo de practica!**

<br/>

## GPU
![Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando "Write Color Settings" en un cuadro verde con una línea discontinua, "ZCULL Accuracy", "Resolution Scale", "Resolution Scale Threshold", "Anti-Alising", "Frame Limit" y "Shader Quality", "VSync" resaltados en un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/gpu.png "GPU")
* ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Activa "Write Color Buffers"** (Ingresar búferes de colores) - Personajes tendrán rendimiento corrupto sin esta opción.
* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* **Activa "VSync"** (Sincronización vertical) - Reduce el efecto de rasgado de pantalla y da fotogramas mas estables. Incrementa la latencia ligeramente. **No uses esto con "Frame Limit" activado!**
	* **Cambia "Frame Limit"** (Limite de fotogramas):
		* A "Off" (Desactivado) si quieres tener fotogramas altas (VBlank Frequency). Esto puede introducir agitación en el rendimiento del juego. Usa esta opción si tienes VSync activada.
		* A "60" si quieres fotogramas limitadas a 60 FPS (redundante con Vblank de 60 Hz).
		* "Auto" va usar lo predeterminado de RPCS3.
		* Es sugerido utilizar la configuración de tu tarjeta de gráficas para limitar la fotogramas o utilizar un programa como MSI Afterburner.
		* Aumentando las fotogramas después de 60 utiliza muchos mas recursos. No es recomendado para sistemas de baja gama.
		* Fotogramas mas alta que 60 pueden causar problemas con la detección de vocales.
	* **Cambia "ZCULL Accuracy"** (Precisión de ZCull) a "Relaxed" (Relajada) - Mejora el rendimiento un poco pero puede causar anomalías gráficas.
	* **Ajusta "Resolution Scale"** (Nivel de resolución) a tu gusto y a lo que puede tu computadora. Auméntala para obtener Gráficas más nítidos.
	* **Cambia "Output Scaling"** a tu gusto y a lo que puede tu computadora. Esto afecta como se va "estirar" la imagen a tu para llegar a la resolución de tu pantalla usando diferente métodos de interpolación. Puede ayudar a los que tienen su nivel de resolución (mencionado arriba) en 100%.
		* "Nearest" (aproximación) es la interpolación mas cruda. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en pixelización.
		* Bilinear (bilineal) es interpolación mas suave. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en una imagen borrosa.
		* FidelityFX Super Resolution (FSR) usa calculaciones complejas para mejorar la imagen cuando se estira a la resolución de tu pantalla. Raramente, puede causar anormalidades en la imagen.
			* Puedes usar "RCAS Sharpening Strength" (fuerza de enfoque) abajo para ajustar cuanta fuerza tiene el efecto.
	* ![Un cuadro bronceado con contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Cuadro bronceado") **Para GPUs de alto poder y usuarios avanzados.**: 
		* **Cambia "Default Resolution"** (Resolución Predeterminada) **a "1920x1080"**. Oficialmente, Rock Band 3 esta limitado a 1280x720, pero se puede ajustar manualmente para correr en una resolución mas alta. Si quieres mas información, [mira esta pagina](forcefullhd_es.md) después de terminar con las configuración principal.


<br/>

## **Audio**
![Una captura de la configuración personalizada de audio de Rock Band 3, que muestra "Enable Buffering" resaltado en un cuadro verde con una línea discontinua, "Audio Out" y "Audio Buffer Duration" resaltados en cuadros azules con contornos punteados, y "Microphone Settings", "Microphone Type: Standard", Mic1, Mic2, Mic3 y Mic4 resaltados en un cuadro bronceado con contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/audio.png "Audio")
* ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Activa "Enable Buffering"** (Activar Búfer) - Absolutamente requerido para Rock Band 3. Debería estar activado por defecto, pero si no, actívalo.
* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* Ajusta el "Audio Buffer Duration" (duración de búferes de audio) dependiendo de tu sistema. 
		* Valores bajos resulta en menos latencia pero menos CPU
		* Valores altos resulta en mas latencia pero menos CPU.
		* Los que juegan vocales son los más afectados por esto porque latencia alta crea un eco. Los jugadores de instrumentos pueden usar la calibración para compensar.
		* Esto se puede cambiar mientras el juego esta abierto pero **requiere recalibración** en los ajustes del sistema de Rock Band 3.
	* **Cambia "Audio Out"** (Salida de audio) a **"XAudio2"** - **No mas se recomienda cambiar esto para computadoras de baja gama**. Prueba si hace una diferencia porque cambiando a XAudio2 puede causar problemas con sonido.
* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Cuadro bronceado") **Para Vocalistas**: 
	* **Cambia "Microphone type"** (tipo de micrófono) **a "Standard" o "Rocksmith"**. "Standard" dejara que tu micrófono se pueda usar para cantar y la chat de voz. "Rocksmith" solo te dejara cantar.
	* Selecciona tu micrófonos en "Mic1", "Mic2" y "Mic3" para las voces. Si no estas jugando vocales, Mic 1 se usara para el chat de voz.
	* Otra vez, tener fotogramas mas altas que 60 puede causar problemas con la detección de vocales.

<br/>

## I/O
**Esta sección es para teclados USB/MIDI o guitarras Pro con cable.**
* **Si no estás jugando con una guitarra Pro con cable o un teclado USB/MIDI,** [[puedes avanzar a la siguiente sección.]](#system)  
* **Si estás jugando con un Teclado Rock Band 3 para PS3 o una Guitarra Pro Mustang para PS3 inalámbrica,** [[puedes avanzar a la siguiente sección.]](#system)  

**Si tu teclado tiene salida USB**, solo necesitas **conectarlo a tu computadora**.  
![Una imagen atrás de un controlador MIDI, mostrando un puerto USB y un pedal de sostenido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/usbkeys.png "Teclado USB")  


**Si tu teclado solo tiene una salida MIDI, necesitarás un convertidor de MIDI a USB**.
![Una imagen atrás de un controlador MIDI, mostrando una salida y entrada MIDI de 5 pines y múltiples entradas de pedal.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/midikeys.png "Teclado MIDI")  

**Lo mismo se aplica a las guitarras Pro**, porque solo tienen salidas MIDI.
![Una imagen de una guitarra Pro Fender Mustang Rock Band 3, mostrando una salida MIDI de 5 pines.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/midiprotar.png "Guitarra Pro Mustang MIDI")  

Aquí tienes un ejemplo de un convertidor de MIDI a USB. La mayoría vendrán con una luz para mostrar actividad. **Para probar que lo has conectado correctamente, deberías ver que "MIDI In" parpadea cuando presionas una tecla**.  
![Una imagen de una interfaz MIDI a USB.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/miditousb.png "Interfaz MIDI a USB")  


**Si tienes una interfaz de audio, es posible que ya tengas una forma de conectar MIDI** a tu computadora, ya que algunas interfaces de audio tienen entradas MIDI. Por ejemplo, esta Scarlett tiene conexiones MIDI atrás.  
>![Una imagen atrás de una Scarlett de Focusrite, mostrando un puerto USB y entradas y salidas MIDI de 5 pines.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  


**Si todo está conectado**, **mira la pestaña I/O de RPCS3**.  
![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando "Emulated MIDI Devices", tipo de dispositivo y selección de dispositivos resaltados en cuadros bronceados con contornos solidos, y "Pad Handler Mode" en un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/io.png "I/O")
* ![Un cuadrado azul claro.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Cuadrado Azul Claro"): **Para jugadores de teclado y guitarra Pro**:
	* 🎹 **Jugadores de teclado: Deja tu "Emulated MIDI type" (Tipo de MIDI emulado) en "Keyboard" (teclado) y selecciona tu teclado o interfaz MIDI en el menú desplegable junto a él**.
	* 🎸 **Jugadores de Guitarra Pro: Cambia tu "Emulated MIDI type" (Tipo de MIDI emulado) de "Keyboard" (teclado) a "Guitar (17 Frets)"** (guitarra (17 trastes)) **si tienes una guitarra Pro Mustang, o "Guitar (22 Frets)"** (guitarra (22 trastes)) **si tienes una guitarra Pro Squier, luego selecciona tu interfaz MIDI a USB en el menú desplegable junto a él**.
* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Cuadro azul") **Ajuste dependiendo de tu PC**: 
	* **Cambia "Pad Handler Mode"** (Modo de manejar controladores) **a "Multi-threaded"** si tienes una CPU con mas de 12 hilos/núcleos.


  
 **Si RPCS3 no detecta tu instrumento, haz click en "Save custom configuration"** (Grabar configuración personalizada), **cierra la ventana de "Create Custom Configuration"** (Crear configuración personalizada) **y luego haz click con el botón derecho en Rock Band 3 para volver a abrirla. Si eso no funciona, reinicia RPCS3.**  
  
**Teclados no tienen botones de PS3, así que el primer octavo esta emulando botones de PS3**. Utiliza la siguiente imagen como referencia. **Te recomiendo poner etiquetas o algo así en tu teclado para recordarte qué hace cada tecla junto con rangos de colores**.
![Una imagen de un teclado de 37 teclas, mostrando el segundo octavo mapeado a los botones de PlayStation, C3 a E3 bajo un color rojo, F3 a B3 bajo un color amarillo, C4 a E4 bajo un color azul, F4 a B4 bajo un color verde y C5 bajo un color naranja.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/midi/keysctrl.png "Referencia del Teclado MIDI")  

<br/>


## System
![Una captura de la configuración personalizada del sistema de Rock Band 3, mostrando el lenguaje de consola (Console Language) y tipo de teclado (Keyboard Type) resaltados en cafe con una linea blanca solida.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/system.png "System")

* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Cuadro bronceado") **Para cambiar el lenguaje del juego**: 
	* Cambia **Console Language** (Lenguaje de Sistema) a **Spanish** (Español) para cambiar el idioma de Rock Band 3 de Ingles a Español.
	* Cambia **Keyboard Type** (Tipo de teclado) a **Spanish Keyboard** (Teclado Español) para cambiar el teclado virtual de Ingles a Español.

<br/>


## Network
![Una captura de la configuración personalizada de Red de Rock Band 3, mostrando el estado de la red (Conectado) resaltado en un cuadro verde con una línea discontinua, los interruptores de IP/Hosts (rb3ps3live.hmxservices.com=45.33.48.123), el estado de PSN (RPCN) y "Enable UPNP" (no marcado) resaltado en azul claro.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/network.png "Network")
* ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Cambia Network Status** (estado de red) **a "Connected"** (conectado) **como en la imagen. Si la dejas en "Disconnected"** (desconectado), **el juego se congelara mientras navegas por la biblioteca de canciones.**
* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Cuadro bronceado") **Para jugar en linea**: 
	* Activa **"Enable UPNP"** (activar UPnP) o **reenvía el puerto 9103 (UDP) en tu cortafuegos. No actives UPNP mientras reenvías el puerto** porque esto puede causar crasheos.
	* En este tiempo, existen dos servidores para jugar Rock Band 3 a los que te puedes conectar. Cambiando a cual te conectas es muy facil.
		* **Para AshCentral: Unete al** [**[Discord de Milohax]**](https://rb3dx.neocities.org/discord) y **ve al canal** de **[\[#ashcentral-status\]](https://discord.com/channels/961352072140324924/1153056600030973992)**. **Copia la informacion para RPCS3.** Este es el servidor recomendado porque tiene actualizaciones mas frecuentes y mas funciones.
		* Para el servidor de RBEnhanced: Únete al \[[Discord de RBEnhanced](https://discord.gg/6rRUWXPYwb)\] y ve al canal [\[#gocentral-connecting\]](https://discord.com/channels/953085263008129064/1076031372185042984). **Sigue las Instrucciones para RPCS3**.

<br/>


## Advanced
![Una captura de la configuración personalizada avanzada, con "Driver Wake-Up Delay (1µ)" resaltado en un cuadro verde con una línea discontinua, "Exclusive Fullscreen Mode", "VBlank Frequency" y "Maximum Number of SPURS Threads" resaltados en cuadros azules con contornos punteados, y "Debug Console Mode" resaltado en un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/advanced.png "Advanced")

* ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Cambia el "Driver Wake-up Delay"** (Retraso de activacion de controlador) **a "20µ" si tu juego se congela luego de algunas canciones. Subelo a "40µ" si sigue pasando.** 
* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* **Cambia el "Exclusive Fullscreen Mode"** (Modo de exclusividad de pantalla llena) **a "Prefer borderless fullscreen"** (preferir pantalla llena sin bordos) para prevenir posibles crasheos o desincronización al cambiar la prioridad del programa.
	* **Ajusta el "VBlank Frequency"** (intervalo vertical) **si quieres unos fotogramas internos altos. Esto puede hacer que atinar las notas sea mas facil, pero puede causar inestabilidad gráfica o problemas de conexión en linea. Es mejor dejarlo tal como esta.**
		* Otra vez, tener fotogramas mas altas que 60 puede causar problemas con la detección de vocales.
	* **Cambia a "Maximum Number of SPURS Threads"** (Máximo numero de hilos de SPURS) - Puede ayudar el rendimiento de computadoras con CPU de 4 núcleos/hilos, como [[CPUs de Intel i5 de la cuarta generación]](https://github.com/carlmylo/rb3-pc/issues/12#issue-1955946005).
* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Cuadro bronceado"): **Recomendado**:
	* **Activa "Debug Console Mode"** (Modo de consola saca-errores) - **Con Rock Band 3 Deluxe instalado, esto aumenta cuanta memoria Rock Band 3 puede usar. Esto va a ayudar tener sesiones mas largas. mejor estabilidad, mas tener mas canciones en tu librería de música.** Si tu computadora esta en el requisitos mínimos (o mejor), no hay razón para no activar esto.

<br/>

## Emulator
![Una captura de la configuración personalizada del emulador de Rock Band 3, mostrando "Show trophy popups", "Show PPU compilation hint", "Show Shader Compilation hint", "Start Games in fullscreen mode", y "Use native user interface." resaltados en cuadros bronceados con contornos solidos.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/emulator.png "Emulator")
Puedes dejar esto como quieras, pero consideraría cambiar las siguientes opciones:
* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/smalltan.png "Cuadro bronceado") **Opcional**: 
	* **"Show trophy popups"** (Enseñar notificaciones de trofeos) - Simula la notificación de trofeos de la PS3. Personalmente desactivo esto ya que el juego tiene sus propias notificaciones.
	* **"Show PPU compilation hint"** (Enseñar notificaciones de PPUs compilándose) - Esto crea una notificación cuando RPCS3 esta compilando unidades del PPU. Esto solo sale si tienes la opción "Recompiler (LLVM)" activada en la pestaña de CPU.
	* **"Show shader compilation hint"** (Enseñar notificaciones de shaders compilándose) - Esto crea una notificación cuando RPCS3 esta compilando shaders. Ya sea si lo dejas activado o no ya es cosa tuya, pero debo decirte que esto es importante. Cuando ejecutas juegos de PS3, tiene que compilar shaders para "trasladar" los Gráficas de una PS3 a un formato que tu PC pueda usar. **El juego seguirá trabándose mientras esto pase** . **Esto Pasa en TODOS los PC's.** Cuando termine de compilar un efecto, **esto usualmente ya no vuelve a pasar otra vez**. **La mejor forma de lidiar con esto es** simplemente **jugar al juego normalmente** y luego se ira rápidamente. También puedes activar el modo de "Autoplay" y dejar que el juego toque unas canciones hasta que pare de trabarse tanto.
	* **"Start games in Fullscreen mode"** (Empezar juego en pantalla llena) - Obviamente solo cambia el modo de pantalla completa cuando inicias Rock Band 3. Personalmente yo activo esto.
	* **"Use Native Interface"** (Usar interfaz nativa) - Desactivar esto hará que se remuevan todas las notificaciones de RPCS3 mientras estás jugando, incluyendo el teclado y fondo mientra el juego cargue. En su lugar, verás una interfaz más antigua. Antes ayudaba antes porque RPCS3 se trababa cuando estabas nombrando algo en el juego con un controlador instrumento. Esto ya no es necesario pero la interfaz nativa si causa problemas con rendimiento en ciertas computadores en los momentos raros que sale

**Después de todo eso, recuerda hacer clic en "Apply"** (aplicar) **y luego en "Save custom configuration"** (Guardar configuración personalizada).

Si todo parece que este funcionando bien, **sugiero cambiar cuales cosas RPCS3 registre un su historial**. Se satura muy fácil en el modo por defecto.

Para hacer esto, **haz clic derecho en el registro historial en la parte de abajo en RPCS3 y luego clic izquierdo en "Fatal"**.

![Una captura de RPCS3 ensenando que solo va a registrar errores fatales.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/cust/logging.png "RPCS3 Fatal Logging")


Y con eso termina la parte difícil.

<br/>

## AshCentral

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
