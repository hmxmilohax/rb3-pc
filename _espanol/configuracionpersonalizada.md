---
title: Configuración Personalizada
author: Carl Mylo
date: 2000-06-01
category: Español
layout: post
---

Aunque la configuración rápida es buena para la mayoría de las personas, algunos prefieren hacer sus propios ajustes para sacar el máximo rendimiento de su configuración. Esto involucra crear una configuración personalizada para Rock Band 3.

## Creando una configuración personalizada

Si no tienes una configuración personalizada, **haz click derecho en Rock Band 3** en RPCS3, luego presiona "**Create Custom Configuration From Default Settings**" (Crear configuración personalizada basada en la configuración por defecto)  
![Una captura del menú de clic derecho de RPCS3, mostrando "Create Custom Configuration From Default Settings" resaltado](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/rpcs3customconfig.png "Create Custom Configuration From Default Settings")

## Cambiando una configuración personalizada

Si quieres cambiar una configuración personalizada, **haz click derecho en Rock Band 3** en RPCS3, luego presiona "**Change Custom Configuration**" (Cambiar Configuración Personalizada)
![Una captura del menú de clic derecho de RPCS3, mostrando "Change Custom Configuration" (Cambiar configuración personalizada) resaltado](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

Esto puede parecer demasiado difícil por la gran cantidad de opciones, pero he coloreado las cosas que vas a ajustar. Todo lo que no esté coloreado debe estar en las opciones predeterminadas.

| COLOR | SIGNIFICADO |
|---|---|
| ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/biggreen.png "Cuadro verde") | **REQUERIDO** |
| ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/bigblue.png "Cuadro azul") | **Para Rendimiento** |
| ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/bigtan.png "Cuadro bronceado") | **Recomendado** |

Iremos pestaña por pestaña, comenzando con:

<br/>

## CPU


![Una captura de la configuración personalizada de CPU para Rock Band 3, mostrando SPU XFloat Accuracy, Thread Scheduler, SPU Block Size, y Preferred SPU Threads resaltados en cuadros azules con contornos punteados.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/cpu.png "CPU")

* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Cuadro azul") **Rendimiento mejorado, dependiendo en tu sistema**: 
	* **Cambia el "SPU Block Size"** (Tamaño de bloques del SPU) **a "Mega"** - Para juntar hilos de SPU a ser más pequeños, requiriendo menos núcleos/hilos. También tardara menos tiempo para iniciar el juego, dependiendo en tu sistema.
	* **Cambia el "Preferred SPU Threads"** (Hilos preferidos del SPU) **a "1", "2", "3", or "4"** - Puede ayudar a prevenir inestabilidades causadas por sobrecargas de la CPU. **Empieza con 4 y bájalo si no mejora**.
	- **Cambia "Thread Scheduler" (Programador de hilos) a "Programador RPCS3" (RPCS3 Scheduler) o "RPCS3 Alternative Scheduler" (Programador alternativo RPCS3)**. - **¡SOLO PARA CPUs CON MÁS DE 12 HILOS!** Esto puede ayudar con la distribución de procesos para ayudar con rendimiento.

<br/>

## GPU
![Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando "Write Color Settings" en un cuadro verde con una línea discontinua, "ZCULL Accuracy", "Resolution Scale", "Resolution Scale Threshold", "Anti-Alising", "Frame Limit" y "Shader Quality", "VSync" resaltados en un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/gpu.png "GPU")

* ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Activa "Write Color Buffers"** (Ingresar búferes de colores) - Los personajes tendrán rendimiento corrupto sin esta opción

* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* **Activa "VSync"** (Sincronización vertical) - Reduce el efecto de rasgado de pantalla y da fotogramas mas estables. Incrementa la latencia ligeramente. **No uses esto con "Frame Limit" activado!**
	* **Cambia "Frame Limit"** (Limite de fotogramas):
		* A "Off" (Desactivado) si quieres tener fotogramas altas (VBlank Frequency). Esto puede introducir agitación en el rendimiento del juego. Usa esta opción si tienes VSync activada.
		* A "60" si quieres fotogramas limitadas a 60 FPS (redundante con Vblank de 60 Hz).
		* "Auto" va usar lo predeterminado de RPCS3.
		* Es sugerido utilizar la configuración de tu tarjeta de gráficas para limitar la fotogramas o utilizar un programa como MSI Afterburner.
		* Aumentando las fotogramas sobre 60 utiliza muchos más recursos. No es recomendado para sistemas de gama baja.
		* Fotogramas sobre 60 pueden causar problemas con la detección de vocales.
	* **Cambia "ZCULL Accuracy"** (Precisión de ZCull) a "Relaxed" (Relajada) - Mejora el rendimiento un poco pero puede causar anomalías gráficas.
	* **Ajusta "Resolution Scale"** (Nivel de resolución) a tu gusto y a lo que puede tu computadora. Auméntala para obtener gráficos más nítidos.
	* **Cambia "Output Scaling"** a tu gusto y a lo que puede tu computadora. Esto afecta cómo se va “estirar” la imagen para llegar a la resolución de tu pantalla usando diferentes métodos de interpolación. Puede ayudar a los que tienen su nivel de resolución (mencionado arriba) en 100%.
		* "Nearest" (aproximación) es la interpolación mas cruda. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en pixelización.
		* Bilinear (bilineal) es interpolación mas suave. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en una imagen borrosa.
		* FidelityFX Super Resolution (FSR) usa calculaciones complejas para mejorar la imagen cuando se estira a la resolución de tu pantalla. Raramente, puede causar anormalidades en la imagen.
			* Puedes usar "RCAS Sharpening Strength" (fuerza de enfoque) abajo para ajustar cuanta fuerza tiene el efecto.
	
	* ![Un cuadro bronceado con contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Cuadro bronceado") **Para GPUs de alto poder y usuarios avanzados.**: 
		* **Cambia "Default Resolution"** (Resolución Predeterminada) **a "1920x1080"**. Oficialmente, Rock Band 3 esta limitado a 1280x720, pero se puede ajustar manualmente para correr en una resolución mas alta. Si quieres mas información, [mira esta pagina](forcefullhd_es.md) después de terminar con las configuración principal.


<br/>

## **Audio**

![Una captura de la configuración personalizada de audio de Rock Band 3, que muestra "Enable Buffering" resaltado en un cuadro verde con una línea discontinua, "Audio Out" y "Audio Buffer Duration" resaltados en cuadros azules con contornos punteados, y "Microphone Settings", "Microphone Type: Standard", Mic1, Mic2, Mic3 y Mic4 resaltados en un cuadro bronceado con contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/audio.png "Audio")

* ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Activa "Enable Buffering"** (Activar Búfer) - Absolutamente requerido para Rock Band 3. Debería estar activado por defecto, pero si no, actívalo.

* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* Ajusta el "Audio Buffer Duration" (duración de búferes de audio) dependiendo de tu sistema. 
		* Valores bajos resultan en menos latencia pero más consumo de CPU.
		* Valores altos resultan en más latencia pero menos consumo de CPU.
		* Los que juegan vocales son los más afectados por esto porque latencia alta crea un eco. Los jugadores de instrumentos pueden usar la calibración para compensar.
		* Esto se puede cambiar mientras el juego esta abierto pero **requiere recalibración** en los ajustes del sistema de Rock Band 3.
	* **Cambia "Audio Out"** (Salida de audio) a **"XAudio2"** - **No mas se recomienda cambiar esto para computadoras de baja gama**. Prueba si hace una diferencia porque cambiando a XAudio2 puede causar problemas con sonido.

* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Cuadro bronceado") **Para Vocalistas**: 
	* **Cambia "Microphone type"** (tipo de micrófono) **a "Standard" o "Rocksmith"**. "Standard" dejara que tu micrófono se pueda usar para cantar y la chat de voz. "Rocksmith" solo te dejara cantar.
	* Selecciona tu micrófonos en "Mic1", "Mic2" y "Mic3" para las voces. Si no estas jugando vocales, Mic 1 se usara para el chat de voz.
	* Otra vez, tener fotogramas sobre 60 puede causar problemas con la detección de vocales y con la conexión para jugar en linea.

<br/>

## I/O

**Esta sección es para teclados USB/MIDI o guitarras Pro con cable.**
* **Si no estás jugando con una guitarra Pro con cable o un teclado USB/MIDI,** [[puedes avanzar a la siguiente sección.]](#system)  
* **Si estás jugando con un Teclado Rock Band 3 para PS3 o una Guitarra Pro Mustang para PS3 inalámbrica,** [[puedes avanzar a la siguiente sección.]](#system)  

### Intro

**Si tu teclado tiene salida USB**, solo necesitas **conectarlo a tu computadora**.  
![Una imagen atrás de un controlador MIDI, mostrando un puerto USB y un pedal de sostenido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/usbkeys.png "Teclado USB")  


**Si tu teclado solo tiene una salida MIDI, necesitarás un convertidor de MIDI a USB**.
![Una imagen atrás de un controlador MIDI, mostrando una salida y entrada MIDI de 5 pines y múltiples entradas de pedal.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/midikeys.png "Teclado MIDI")  

**Lo mismo se aplica a las guitarras Pro**, porque solo tienen salidas MIDI. La única diferencia es que **requieren un convertidor de MIDI a USB que pueda aceptar señales SYSEX.**
![Una imagen de una guitarra Pro Fender Mustang Rock Band 3, mostrando una salida MIDI de 5 pines.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/midiprotar.png "Guitarra Pro Mustang MIDI")  

Aquí tienes un ejemplo de un convertidor de MIDI a USB. La mayoría vendrán con una luz para mostrar actividad. **Para probar que lo has conectado correctamente, deberías ver que "MIDI In" parpadea cuando presionas una tecla**.  
![Una imagen de una interfaz MIDI a USB.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/miditousb.png "Interfaz MIDI a USB")  


**Si tienes una interfaz de audio, es posible que ya tengas una forma de conectar MIDI** a tu computadora, ya que algunas interfaces de audio tienen entradas MIDI. Por ejemplo, esta Scarlett tiene conexiones MIDI atrás.  
>![Una imagen atrás de una Scarlett de Focusrite, mostrando un puerto USB y entradas y salidas MIDI de 5 pines.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  


**Si todo está conectado**, **mira la pestaña I/O de RPCS3**.  
![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando "Emulated MIDI Devices", tipo de dispositivo y selección de dispositivos resaltados en cuadros bronceados con contornos solidos, y "Pad Handler Mode" en un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/io.png "I/O")

* ![Un cuadrado bronceado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Cuadrado bronceado"): **Para jugadores de teclado y guitarra Pro**:
	* 🎹 **Jugadores de teclado: Deja tu "Emulated MIDI type" (Tipo de MIDI emulado) en "Keyboard" (teclado) y selecciona tu teclado o interfaz MIDI en el menú desplegable junto a él**.
	* 🎸 **Jugadores de Guitarra Pro: Cambia tu "Emulated MIDI type" (Tipo de MIDI emulado) de "Keyboard" (teclado) a "Guitar (17 Frets)"** (guitarra (17 trastes)) **si tienes una guitarra Pro Mustang, o "Guitar (22 Frets)"** (guitarra (22 trastes)) **si tienes una guitarra Pro Squier, luego selecciona tu interfaz MIDI a USB en el menú desplegable junto a él**.
	* 🥁 **Jugadores de Batería: Cambia tu "Emulated MIDI type" (Tipo de MIDI emulado) de "Keyboard" (teclado) a "Drums" (batería), y selecciona tu batería o interfaz MIDI en el menú desplegable junto a él**.
* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Cuadro azul") **Ajuste dependiendo de tu PC**: 
	* **Cambia "Pad Handler Mode"** (Modo de manejar controladores) **a "Multi-threaded"** si tienes una CPU con mas de 12 hilos/núcleos.
  
 **Si RPCS3 no detecta tu instrumento, haz click en "Save custom configuration"** (Grabar configuración personalizada), **cierra la ventana de "Create Custom Configuration"** (Crear configuración personalizada) **y luego haz click con el botón derecho en Rock Band 3 para volver a abrirla. Si eso no funciona, reinicia RPCS3.**  
  
### Notas para Guitarras PRO:

Como he dicho antes, las Guitarras Pro deben servir sin configuración adicional con que **tu convertidor de MIDI a USB pueda aceptar señales SYSEX**. **Recomiendo el M-Audio Midisport Uno porque se ha verificado que funciona.**

### Notas para teclados MIDI:

**Los teclados no tienen botones de PS3, así que la primera octava está emulando botones de PS3**. Utiliza la siguiente imagen como referencia. **Te recomiendo poner etiquetas o algo así en tu teclado para recordarte qué hace cada tecla junto con rangos de colores**.
![Una imagen de un teclado de 37 teclas, mostrando el segundo octavo mapeado a los botones de PlayStation, C3 a E3 bajo un color rojo, F3 a B3 bajo un color amarillo, C4 a E4 bajo un color azul, F4 a B4 bajo un color verde y C5 bajo un color naranja.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/midi/keysctrl.png "Referencia del Teclado MIDI")

### Notas para baterías MIDI:

Tu batería MIDI necesita estar en canal de MIDI 10 y mapeado a modo "GM". Esto esta por defecto en mayoría de las baterías.

Puedes ajustar una variedad de opciones en el archivo `rb3drums.yml` file, que esta colocado en la carpeta llamada `config` que esta donde tienes RPCS3. Necesitas empezar el juego una vez con tu batería MIDI configurada en la pestaña de I/O para que RPCS3 cree el archivo. Cualquier cambio a este archivo requiere que reinicies el juego.

Las baterías MIDI no tienen botones de PS3, así que:
* START: Cierra la Hi-Hat tres veces rápidamente y luego pégale a la caja (snare).
* SELECT: Cierra la Hi-Hat tres veces rápidamente y luego pégale a el aro de la caja (snare rim)
* Atajo para escocer canciones: Cierra la Hi-Hat tres veces rápidamente y pégale al bombo (kick) con el pedal.**
Si tu batería tiene partes que necesitan ser configuradas, puedes usar `Midi id to note override: ""` para corregir notas.
* Para hacer esto:
	* Ve al sitio [[MIDI Monitor]](https://www.midimonitor.com/)
	* Toca la parte que quieres re-configurar para encontrar su el numero de nota MIDI ("Note #[number]").

El archivo usa estos nombres para notas:

`Kick`  
`HihatPedal`  
`Snare`  
`SnareRim`  
`HiTom`  
`LowTom`  
`FloorTom`  
`HihatWithPedalUp`  
`Hihat`  
`Ride`  
`Crash`


Ejemplos de cambios comunes:
* El platillo azul esta configurado a `Note #51` y el platillo verde esta configurado a `Note #49` pero tu batería los tiene al revés.
	* `Midi id to note override: "49=Ride,51=Crash"` va a reversar los platillos para que estén sean mejor para Rock Band 3.
* Quieres usar tu Hi-Hat cerrado para amarillo y Hi-Hat abierta para azul.
	* `Midi id to note override: "46=Ride"`

En `rb3drums.yml`, vas a encontrar `Combo Start`, `Combo Select`, `Combo Toggle Hold Kick`, que te van ayudar a configurar los que necesitas tocar para activar el boton START, SELECT, y el atajo para escocer canciones, respectivamente.

<br/>


## System
![Una captura de la configuración personalizada del sistema de Rock Band 3, mostrando el lenguaje de consola (Console Language) y tipo de teclado (Keyboard Type) resaltados en cafe con una linea blanca solida.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/system.png "System")

* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Cuadro bronceado") **Para cambiar el lenguaje del juego**: 
	* Cambia **Console Language** (Lenguaje de Sistema) a **Spanish** (Español) para cambiar el idioma de Rock Band 3 de Ingles a Español.
	* Cambia **Keyboard Type** (Tipo de teclado) a **Spanish Keyboard** (Teclado Español) para cambiar el teclado virtual de Ingles a Español.

<br/>


## Network
![Una captura de la configuración personalizada de Red de Rock Band 3, mostrando el estado de la red (Conectado) resaltado en un cuadro verde con una línea discontinua, DNS (78.141.231.152), los interruptores de IP/Hosts, el estado de PSN (RPCN) y "Enable UPNP" (no marcado) resaltado en azul claro.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/network.png "Network")

* ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Cambia Network Status** (estado de red) **a "Connected"** (conectado) **como en la imagen. Si la dejas en "Disconnected"** (desconectado), **el juego se congelara mientras navegas por la biblioteca de canciones.**

* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Cuadro bronceado") **Para jugar en linea**: 
	* Activa **"Enable UPNP"** (activar UPnP) o **reenvía el puerto 9103 (UDP) en tu cortafuegos. No actives UPNP mientras reenvías el puerto** porque esto puede causar crasheos.
	* En este tiempo, existen dos servidores para jugar Rock Band 3 a los que te puedes conectar. Cambiando a cual te conectas es muy facil.
		* **Para AshCentral: Unete al** [**[Discord de Milohax]**](https://rb3dx.neocities.org/discord) y **ve al canal** de **[\[#ashcentral-status\]](https://discord.com/channels/961352072140324924/1153056600030973992)**. **Copia la informacion para RPCS3.** Este es el servidor recomendado porque tiene actualizaciones mas frecuentes y mas funciones.
		* Para el servidor de RBEnhanced: Únete al \[[Discord de RBEnhanced](https://discord.gg/6rRUWXPYwb)\] y ve al canal [\[#gocentral-connecting\]](https://discord.com/channels/953085263008129064/1076031372185042984). **Sigue las Instrucciones para RPCS3**.

<br/>


## Advanced
![Una captura de la configuración personalizada avanzada, con "Driver Wake-Up Delay (1µ)" resaltado en un cuadro verde con una línea discontinua, "Exclusive Fullscreen Mode", "VBlank Frequency" y "Maximum Number of SPURS Threads" resaltados en cuadros azules con contornos punteados, y "Debug Console Mode" resaltado en un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/advanced.png "Advanced")

* ![Un cuadro verde con una línea discontinua.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Cambia el "Driver Wake-up Delay"** (Retraso de activacion de controlador) **a "20µ" si tu juego se congela luego de algunas canciones. Subelo a "40µ" si sigue pasando.** Si todavía sigue pasando (muy raro),  subele en incrementos de 20 cada vez.

* ![Un cuadro azul con contorno punteado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* **Ajusta el "VBlank Frequency"** (intervalo vertical) **si quieres unos fotogramas internos altos. Esto puede hacer que atinar las notas sea mas facil, pero puede causar inestabilidad gráfica o problemas de conexión en linea. Es mejor dejarlo tal como esta.**
		* Otra vez, tener fotogramas mas altas que 60 puede causar problemas con la detección de vocales.
	* **Cambia a "Maximum Number of SPURS Threads"** (Máximo numero de hilos de SPURS) - Puede ayudar el rendimiento de computadoras con CPU de 4 núcleos/hilos, como [[CPUs de Intel i5 de la cuarta generación]](https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005).

* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Cuadro bronceado"): **Recomendado**:
	* **Activa "Debug Console Mode"** (Modo de consola saca-errores) - Con esto activado al lado de la función "Large Heap" de Rock Band 3 Deluxe, fácilmente puedes darle mas memoria a Rock Band 3. Esto ayuda con la estabilidad y te deja instalar hasta 16000 canciones. Es recomendado que todos tengan esto activado. [[Haz click aquí para mas información.]](https://hmxmilohax.github.io/rb3-pc/espanol/configuracionadicional#añadir-mas-memoria-a-Rock-Band-3)
	* **Cambia el "Exclusive Fullscreen Mode"** (Modo de exclusividad de pantalla llena) **a "Prefer borderless fullscreen"** (preferir pantalla llena sin bordos) para prevenir posibles crasheos o desincronización al cambiar la prioridad del programa.

<br/>

## Emulator
![Una captura de la configuración personalizada del emulador de Rock Band 3, mostrando "Show trophy popups", "Show PPU compilation hint", "Show Shader Compilation hint", "Start Games in fullscreen mode", y "Use native user interface." resaltados en cuadros bronceados con contornos solidos.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/emulator.png "Emulator")

Puedes dejar esto como quieras, pero consideraría cambiar las siguientes opciones:

* ![Un cuadro bronceado con un contorno solido.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/smalltan.png "Cuadro bronceado") **Opcional**: 
	* **"Show trophy popups"** (Enseñar notificaciones de trofeos) - Simula la notificación de trofeos de la PS3. Personalmente desactivo esto ya que el juego tiene sus propias notificaciones.
	* **"Show PPU compilation hint"** (Enseñar notificaciones de PPUs compilándose) - Esto crea una notificación cuando RPCS3 esta compilando unidades del PPU. Esto solo sale si tienes la opción "Recompiler (LLVM)" activada en la pestaña de CPU.
	* **"Show shader compilation hint"** (Enseñar notificaciones de shaders compilándose) - Esto crea una notificación cuando RPCS3 esta compilando shaders. Ya sea si lo dejas activado o no ya es cosa tuya, pero debo decirte que esto es importante. Cuando ejecutas juegos de PS3, tiene que compilar shaders para "trasladar" los Gráficas de una PS3 a un formato que tu PC pueda usar. **El juego seguirá trabándose mientras esto pase** . **Esto Pasa en TODOS los PC's.** Cuando termine de compilar un efecto, **esto usualmente ya no vuelve a pasar otra vez**. **La mejor forma de lidiar con esto es** simplemente **jugar al juego normalmente** y luego se ira rápidamente. También puedes activar el modo de "Autoplay" y dejar que el juego toque unas canciones hasta que pare de trabarse tanto.
	* **"Start games in Fullscreen mode"** (Empezar juego en pantalla llena) - Obviamente solo cambia el modo de pantalla completa cuando inicias Rock Band 3. Personalmente yo activo esto.
	* **"Use Native Interface"** (Usar interfaz nativa) - Desactivar esto hará que se remuevan todas las notificaciones de RPCS3 mientras estás jugando, incluyendo el teclado y fondo mientra el juego cargue. En su lugar, verás una interfaz más antigua. Antes ayudaba antes porque RPCS3 se trababa cuando estabas nombrando algo en el juego con un controlador instrumento. Esto ya no es necesario pero la interfaz nativa si causa problemas con rendimiento en ciertas computadores en los momentos raros que sale

**Después de todo eso, recuerda hacer clic en "Apply"** (aplicar) **y luego en "Save custom configuration"** (Guardar configuración personalizada).

Si todo parece que este funcionando bien, **sugiero cambiar cuales cosas RPCS3 registre un su historial**. Se satura muy fácil en el modo por defecto.

Para hacer esto, **haz clic derecho en el registro historial en la parte de abajo en RPCS3 y luego clic izquierdo en "Fatal"**.

![Una captura de RPCS3 ensenando que solo va a registrar errores fatales.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/logging.png "RPCS3 Fatal Logging")


Y con eso termina la parte difícil.
