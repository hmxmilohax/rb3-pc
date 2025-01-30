---
title: "Configuración Personalizada"
sidebar: espanol_sidebar
permalink: custom_config_es
folder: espanol
toc: false
tags: [conf-pers, espanol]
summary: "Como crear o editar una configuración personalizada de RPCS3"
---

Aunque la configuración rápida es buena para la mayoría de las personas, algunos prefieren hacer sus propios ajustes para sacar el máximo rendimiento de su configuración. Esto involucra crear una configuración personalizada para Rock Band 3.

<ul id="confeditTabs" class="nav nav-tabs">
    <li class="active"><a href="#changecustomconfig" data-toggle="tab">Cambiando una configuración personalizada</a></li>
    <li><a href="#createcustomconfig" data-toggle="tab">Creando una configuración personalizada</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="changecustomconfig">
<p>Si quieres cambiar una configuración personalizada, <strong>haz click derecho en Rock Band 3</strong> en RPCS3, luego presiona “<strong>Change Custom Configuration</strong>” (Cambiar Configuración Personalizada)<br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfigchange.png" alt="Una captura del menú de clic derecho de RPCS3, mostrando &quot;Change Custom Configuration&quot; (Cambiar configuración personalizada) resaltado" title="Change Custom Configuration"></p></div>
<div role="tabpanel" class="tab-pane" id="createcustomconfig">
<p>Si no tienes una configuración personalizada, <strong>haz click derecho en Rock Band 3</strong> en RPCS3, luego presiona “<strong>Create Custom Configuration From Default Settings</strong>” (Crear configuración personalizada basada en la configuración por defecto)<br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfig.png" alt="Una captura del menú de clic derecho de RPCS3, mostrando &quot;Create Custom Configuration From Default Settings&quot; resaltado" title="Create Custom Configuration From Default Settings"></p></div>
</div>

**¡Recuerda de hacer click en "Apply"** (Aplicar) **y luego "Save custom configuration"** (Guardar configuración personalizada) **después de hacer ajustes!**
Toma en cuenta que vas a necesitar reiniciar el juego para aplicar mayoría de estos ajustes.  
![Una captura de la configuración personalizada de Rock Band 3 dentro de RPCS3 con el ratón sobre "Save custom configuration".](https://carlmylo.github.io/rb3-pc/images/cust/save.png "Settings: [BLUS30463] Rock Band 3")

## Guía de Colores

Esto puede parecer demasiado difícil por la gran cantidad de opciones, pero he coloreado las cosas que vas a ajustar. Todo lo que no esté coloreado debe estar en las opciones predeterminadas.

| COLOR | SIGNIFICADO |
|---|---|
| ![Un cuadro verde con una línea discontinua.](https://carlmylo.github.io/rb3-pc/images/cust/biggreen.png "Cuadro verde") | **REQUERIDO** |
| ![Un cuadro azul con contorno punteado.](https://carlmylo.github.io/rb3-pc/images/cust/bigblue.png "Cuadro azul") | **Para Rendimiento** |
| ![Un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/rb3-pc/images/cust/bigtan.png "Cuadro bronceado") | **Recomendado** |

<br/>

## Configuración Personalizada

<ul id="configTabs" class="nav nav-tabs">
    <li class="active"><a href="#cpu" data-toggle="tab">CPU</a></li>
    <li><a href="#gpu" data-toggle="tab">GPU</a></li>
    <li><a href="#audio" data-toggle="tab">Audio</a></li>
    <li><a href="#io" data-toggle="tab">I/O</a></li>
    <li><a href="#system" data-toggle="tab">System</a></li>
    <li><a href="#network" data-toggle="tab">Network</a></li>
    <li><a href="#advanced" data-toggle="tab">Advanced</a></li>
    <li><a href="#emulator" data-toggle="tab">Emulator</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="cpu">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/cpu.png" alt="Una captura de la configuración personalizada de CPU para Rock Band 3, mostrando SPU XFloat Accuracy, Thread Scheduler, SPU Block Size, y Preferred SPU Threads resaltados en cuadros azules con contornos punteados." title="CPU"></p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Rendimiento mejorado, dependiendo en tu sistema</strong>:
<ul>
<li><strong>Cambia el "SPU Block Size"</strong> (Tamaño de bloques del SPU) <strong>a "Mega""</strong> - Para juntar hilos de SPU a ser más pequeños, requiriendo menos núcleos/hilos. También tardara menos tiempo para iniciar el juego, dependiendo en tu sistema.</li>
<li><strong>Cambia el "Preferred SPU Threads"</strong> (Hilos preferidos del SPU) <strong>a “1”, “2”, “3” o “4”</strong> - Puede ayudar a prevenir inestabilidades causadas por sobrecargas de la CPU. <strong>Empieza con 4 y bájalo si no mejora</strong>.</li>
<li><strong>Cambia "Thread Scheduler"</strong> (Programador de hilos) <strong>a “RPCS3 Scheduler”</strong> (RPCS3 Scheduler) <strong>o “RPCS3 Alternative Scheduler”</strong>(Programador alternativo RPCS3) - <strong>¡SOLO PARA CPUs CON MÁS DE 12 HILOS!</strong> Puede ayudar con la distribución de procesos para ayudar con rendimiento.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="gpu">
    <p><img src="https://carlmylo.github.io/rb3-pc/images/cust/gpu.png" alt="Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando Write Color Settings en un cuadro verde con una línea discontinua, ZCULL Accuracy, Resolution Scale, Anisotropic Filtering, Anti-Alising, Framelimit, Output Scaling y VSync resaltados en un cuadro azul con contorno punteado." title="GPU"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="Un cuadro verde con una línea discontinua." title="Cuadro verde"> <strong>REQUERIDO</strong>:</p>
<ul>
<li><strong>Activa "Write Color Buffers</strong> (Ingresar búferes de colores) - Los personajes tendrán rendimiento corrupto sin esta opción.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Dependiendo en tu PC</strong>:</p>
<ul>
<li><strong>Activa "VSync"</strong> (Sincronización vertical) - Reduce el efecto de rasgado de pantalla y da fotogramas mas estables. Incrementa la latencia pero casi no se puede sentir. <strong>¡No uses esto con "Frame Limit" activado!</strong></li>
<li><strong>Cambia "Frame Limit"</strong>(Limite de fotogramas):
<ul>
<li>A "Off" (Desactivado) si quieres tener fotogramas sobre 60. Esto puede introducir agitación en el rendimiento del juego. Usa esta opción si tienes VSync activada.</li>
<li>"Display" va usar la frecuencia de actualización de tu pantalla.</li>
<li>Aumentando las fotogramas sobre 60 utiliza muchos más recursos. No es recomendado para sistemas de gama baja.</li>
<li>Fotogramas sobre 60 pueden causar problemas con la detección de vocales.</li>
<li>Recomendamos que cambies "Framelimit" a "Off" y actives Vsync en esta pestaña y luego desactives VSync dentro del menú de Rock Band 3 Deluxe <br> <code>Menú &gt; Opciones &gt; Configuración Deluxe &gt; Gráficos &gt; VSync</code></li>
</ul>
</li>
<li><strong>Cambia "ZCULL Accuracy"</strong> (Precisión de ZCull) <strong>a "Relaxed"</strong> (Relajada) - Mejora el rendimiento un poco pero puede causar anomalías gráficas.</li>
<li><strong>Ajusta "Anisotropic Filter"</strong> (filtro anisotrópico) a tu gusto y a lo que puede tu computadora. Ayuda con texturas. No debe de afectar el rendimiento tanto.</li>
<li><strong>Ajusta "Resolution Scale"</strong> (Nivel de resolución) a tu gusto y a lo que puede tu computadora. Auméntala para obtener gráficos más nítidos.</li>
<li><strong>Cambia "Output Scaling"</strong> (Algoritmo de resolución) a tu gusto y a lo que puede tu computadora. Esto afecta cómo se va "estirar" la imagen para llegar a la resolución de tu pantalla usando diferentes métodos de interpolación. Puede ayudar a los que tienen su nivel de resolución (mencionado arriba) en 100%.
<ul>
<li>"Nearest" (aproximación) es la interpolación mas cruda. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en pixelización.</li>
<li>Bilinear (bilineal) es interpolación mas suave. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en una imagen borrosa.</li>
<li>FidelityFX Super Resolution (FSR) usa calculaciones complejas para mejorar la imagen cuando se estira a la resolución de tu pantalla. Raramente, puede causar anormalidades en la imagen.
<ul>
<li>Puedes usar "RCAS Sharpening Strength" (fuerza de enfoque) abajo para ajustar cuanta fuerza tiene el efecto.</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="audio">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/audio.png" alt="Una captura de la configuración personalizada de audio de Rock Band 3, que muestra Audio Out y Audio Buffer Duration resaltados en cuadros azules con contornos punteados, y Microphone Settings, Microphone Type: Standard, Mic1, Mic2, Mic3 y Mic4 resaltados en un cuadro bronceado con contorno solido" title="Audio"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Dependiendo en tu PC</strong>:</p>
<ul>
<li><strong>Ajusta el "Audio Buffer Duration"</strong> (duración de búferes de audio) dependiendo de tu sistema. Es mejor bajarlo lo mas posible.
<ul>
<li>Valores bajos resultan en menos latencia pero más consumo de CPU.</li>
<li>Valores altos resultan en más latencia pero menos consumo de CPU.</li>
<li>Vocalistas son los más afectados por esto porque latencia alta crea un eco. Los jugadores de instrumentos pueden usar la calibración para compensar.</li>
<li>Esto se puede cambiar mientras el juego esta abierto pero <strong>requiere recalibración</strong> en los ajustes del sistema de Rock Band 3.</li>
</ul>
</li>
<li><strong>Cambia "Audio Out"</strong> (Salida de audio) <strong>a “XAudio2”</strong> - En ocasiones raras, puede ayudar. <strong>Mayoría de las personas deben de quedarse en Cubeb</strong>. Prueba si hace una diferencia porque cambiando a XAudio2 puede causar problemas con el sonido</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Para Vocalistas</strong>:</p>
<ul>
<li><strong>Cambia "Microphone type"</strong> (tipo de micrófono) <strong>a "Standard" o "Rocksmith"</strong>.</li>
<li>Selecciona tu micrófonos en "Mic1", "Mic2" y "Mic3" para las voces. Si no estas jugando vocales, Mic 1 se usara para el chat de voz.</li>
<li>Otra vez, tener fotogramas sobre 60 puede causar problemas con la detección de vocales y con la conexión para jugar en linea.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="io">
<p><strong>Esta sección es para los que están usando teclados USB/MIDI, Guitarras Pro o Baterías MIDI.</strong></p>
<ul>
<li><strong>Si no estas usando un teclado USB/MIDI, Guitarra Pro o Batería MIDI, puedes brincar de esta sección.</strong></li>
<li><strong>Si estas usando un Teclado o Guitarra Pro (Mustang) de PlayStation 3 con sus receptores propios,</strong> mira la <a href="https://carlmylo.github.io/rb3-pc/adv_passthrough_es" target="_blank"><strong>[[pagina de conexiones directas]]</strong></a>. </li>
</ul>
<p><strong>Asegúrate que tu instrumento MIDI este conectado.</strong> Luego, puedes enfocarte en la <strong>pestaña de I/O en RPCS3.</strong><br>
<strong>Si no puedes leer unas opciones, haz la pantalla mas grande.</strong><br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/io.png" alt="Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando Emulated MIDI Devices, tipo de dispositivo y selección de dispositivos resaltados en cuadros bronceados con contornos solidos, y Pad Handler Mode en un cuadro azul con contorno punteado." title="I/O"></p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Para jugadores de teclados MIDI, guitarra Pro, y baterías MIDI</strong>:
<ul>
<li>🎹 <strong>Jugadores de teclado: Deja tu "Emulated MIDI type"</strong> (Tipo de MIDI emulado) <strong>en "Keyboard"</strong> (teclado) <strong>y selecciona tu teclado o interfaz MIDI en el menú desplegable junto a él</strong>.</li>
<li>🎸 <strong>Jugadores de Guitarra Pro: Cambia el "Emulated MIDI type"</strong> (Tipo de MIDI emulado) <strong>de "Keyboard"</strong> (teclado) <strong>a “Guitar (17 Frets)”</strong> (guitarra (22 trastes)) <strong>si tienes una guitarra Pro Mustang, o "Guitar (22 Frets)"</strong> (guitarra (22 trastes)) <strong>si tienes una guitarra Pro Squier, luego selecciona tu interfaz MIDI a USB en el menú desplegable junto a él</strong>.</li>
<li>🥁 <strong>Jugadores con Baterías MIDI: Cambia el "Emulated MIDI type"</strong> (Tipo de MIDI emulado) <strong>de "Keyboard"</strong> (teclado) <strong>a Drums”</strong> (Bateria), <strong>y selecciona tu batería o interfaz MIDI en el menú desplegable junto a él</strong>.</li>
</ul>
</li>
</ul>
<p>Si necesitas mas ayuda, dale otra visita a la <a href="https://carlmylo.github.io/rb3-pc/ctrls_es" target="_blank">[pagina de instrumentos]</a>.</p>
</div>
<div role="tabpanel" class="tab-pane" id="system">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/system.png" alt="Una captura de la configuración personalizada del sistema de Rock Band 3, mostrando Console Language y Keyboard Type resaltados en cafe con una linea blanca solida" title="System"></p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Para cambiar el lenguaje del juego</strong>:
<ul>
<li><strong>Cambia "Console Language"</strong> (Idioma del Sistema) <strong>a Spanish</strong> (Español) - Cambia el idioma de Rock Band 3 a Español</li>
<li><strong>Cambia "Keyboard Type"</strong> (Tipo de teclado) <strong>a "Spanish Keyboard"</strong> (Teclado Español) - Cambia el teclado virtual a Español.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="network">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/network.png" alt="Una captura de la configuración personalizada de Red de Rock Band 3, mostrando el estado de la red (Conectado) resaltado en un cuadro verde con una línea discontinua, IP/Hosts switches (rb3ps3live.hmxservices.com=45.33.44.103), el estado de PSN (RPCN) y Enable UPNP (no marcado) resaltado en azul claro." title="Network"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="Un cuadro verde con una línea discontinua." title="Cuadro verde"> <strong>REQUERIDO</strong>:</p>
<ul>
<li><strong>Cambia Network Status</strong> (estado de red) <strong>a "Connected"</strong> (conectado) <strong>como en la imagen. Si no haces esto, el juego se congelara mientras navegas la biblioteca de canciones.</strong></li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Para jugar en linea</strong>:</p>
<ul>
<li>Activa <strong>“Enable UPNP”</strong> (activar UPnP) <strong>o reenvía el puerto 9103 (UDP) en tu cortafuegos</strong> No actives UPNP mientras reenvías el puerto** porque esto puede causar crasheos.</li>
<li>Agrega la direccion IP de Rock Band Enhanced.
<ul>
<li>Cambia "IP/Hosts switches" a <code>rb3ps3live.hmxservices.com=45.33.44.103</code>.</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="advanced">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/advanced.png" alt="Una captura de la configuración personalizada avanzada, con Driver Wake-Up Delay (1µ) resaltado en un cuadro verde con una línea discontinua, Exclusive Fullscreen Mode, VBlank Frequency y Maximum Number of SPURS Threads resaltados en cuadros azules con contornos punteados, y Debug Console Mode resaltado en un cuadro bronceado con un contorno solido" title="Advanced"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="Un cuadro verde con una línea discontinua." title="Cuadro verde"> <strong>REQUERIDO</strong>:</p>
<ul>
<li><strong>Cambia el "Driver Wake-up Delay"</strong> (Retraso de activacion de controlador) <strong>a "20µ" si tu juego se congela luego de algunas canciones. Subelo a "40µ" si sigue pasando.</strong> Si todavía sigue pasando (muy raro),  subele en incrementos de 20 cada vez.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro bronceado"> <strong>Dependiendo en tu PC</strong>:</p>
<ul>
<li><strong>Cambia a "Maximum Number of SPURS Threads"</strong> (Máximo numero de hilos de SPURS) - Puede ayudar el rendimiento de computadoras con CPU de 4 núcleos/hilos, como <a href="https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005" target="_blank">[CPUs de Intel i5 de la cuarta generación]</a>.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Recomendado</strong>:</p>
<ul>
<li><strong>Activa "Debug Console Mode"</strong> (Modo de depuración) - Con esto activado al lado de la función "Large Heap" de Rock Band 3 Deluxe, fácilmente puedes darle mas memoria a Rock Band 3. Esto ayuda con la estabilidad y te deja instalar hasta 16000 canciones. Es recomendado que todos tengan esto activado. <a href="https://carlmylo.github.io/rb3-pc/adv_himem_es" target="_blank">[Haz click aquí para mas información.]</a></li>
<li><strong>Cambia el "Exclusive Fullscreen Mode</strong> (Modo de exclusividad de pantalla llena) <strong>a "Prefer borderless fullscreen"</strong> (preferir pantalla llena sin bordos) para prevenir posibles crasheos o desincronización al cambiar la prioridad del programa.</li>
</ul>
</li>
</ul>
</div>
<div role="tabpanel" class="tab-pane" id="emulator">
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/emulator.png" alt="Una captura de la configuración personalizada del emulador de Rock Band 3, mostrando Show trophy popups, Show PPU compilation hint, Show Shader Compilation hint, Start Games in fullscreen mode, y Use native user interface. resaltados en cuadros bronceados con contornos solidos" title="Emulator"></p>
<p>Puedes dejar esto como quieras, pero consideraría ajustar estas opciones:</p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Opcional</strong>:
<ul>
<li><strong>"Show trophy popups"</strong> - (Enseñar notificaciones de trofeos) - Simula la notificación de trofeos de la PS3. Personalmente desactivo esto ya que el juego tiene sus propias notificaciones.</li>
<li><strong>"Show PPU compilation hint"</strong> - (Enseñar notificaciones de PPUs compilándose) - Esto crea una notificación cuando RPCS3 esta compilando unidades del PPU. Esto solo sale si tienes la opción "Recompiler (LLVM)" activada en la pestaña de CPU.</li>
<li><strong>"Show shader compilation hint"</strong> - (Enseñar notificaciones de shaders compilándose) - Esto crea una notificación cuando RPCS3 esta compilando shaders. Ya sea si lo dejas activado o no ya es cosa tuya, pero debo decirte que esto es importante. Cuando ejecutas juegos de PS3, tiene que compilar shaders para "trasladar" los Gráficas de una PS3 a un formato que tu PC pueda usar. <strong>El juego seguirá trabándose mientras esto pase</strong> . <strong>Esto pasa en TODOS las PC's.</strong> Cuando termine de compilar un efecto <strong> esto usualmente ya no vuelve a pasar otra vez. La mejor forma de lidiar con esto es</strong> simplemente <strong>jugar al juego normalmente</strong> y luego se ira rápidamente. También puedes activar el modo de "Autoplay" y dejar que el juego toque unas canciones hasta que pare de trabarse tanto.</li>
<li><strong>"Start games in Fullscreen mode"</strong> (Empezar juego en pantalla llena) - Obviamente solo cambia el modo de pantalla completa cuando inicias Rock Band 3. Personalmente yo activo esto<./li>
<li><strong>"Use Native Interface"</strong> - (Usar interfaz nativa) - Desactivar esto hará que se remuevan todas las notificaciones de RPCS3 mientras estás jugando, incluyendo el teclado y fondo mientra el juego cargue. En su lugar, verás una interfaz más antigua. Antes ayudaba antes porque RPCS3 se trababa cuando estabas nombrando algo en el juego con un controlador instrumento. Esto ya no es necesario pero la interfaz nativa si causa problemas con rendimiento en ciertas computadores en los momentos raros que sale.</li>
</ul>
</li>
</ul>
</div>
</div>


{% include links.html %}