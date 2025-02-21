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
<p>Si quieres cambiar una configuración personalizada, <strong>haz click derecho en Rock Band 3</strong> en RPCS3, luego presiona “<strong><code>Change Custom Configuration</code></strong>” (Cambiar Configuración Personalizada)<br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfigchange.png" alt="Una captura del menú de clic derecho de RPCS3, mostrando &quot;Change Custom Configuration&quot; (Cambiar configuración personalizada) resaltado" title="Change Custom Configuration"></p></div>
<div role="tabpanel" class="tab-pane" id="createcustomconfig">
<p>Si no tienes una configuración personalizada, <strong>haz click derecho en Rock Band 3</strong> en RPCS3, luego presiona “<strong><code>Create Custom Configuration From Default Settings</code></strong>” (Crear configuración personalizada basada en la configuración por defecto)<br>
<img src="https://carlmylo.github.io/rb3-pc/images/cust/rpcs3customconfig.png" alt="Una captura del menú de clic derecho de RPCS3, mostrando &quot;Create Custom Configuration From Default Settings&quot; resaltado" title="Create Custom Configuration From Default Settings"></p></div>
</div>

**¡Recuerda de hacer click en "`Apply`"** (Aplicar) **y luego "`Save custom configuration`"** (Guardar configuración personalizada) **después de hacer ajustes!**
Toma en cuenta que vas a necesitar reiniciar el juego para aplicar mayoría de estos ajustes.  
![Una captura de la configuración personalizada de Rock Band 3 dentro de RPCS3 con el ratón sobre "Save custom configuration".](https://carlmylo.github.io/rb3-pc/images/cust/save.png "Settings: [BLUS30463] Rock Band 3")

## Guía de Colores

Para hacer todo mas facil, todos los ajustes han sido colorados.
**Todo lo que no esté coloreado debe estar en las opciones predeterminadas.**

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
<!-- CPU Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/cpu.png" alt="Una captura de la configuración personalizada de CPU para Rock Band 3, mostrando SPU Block Size, Thread Scheduler y Preferred SPU Threads resaltados en cuadros azules con contornos punteados." title="CPU"></p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Rendimiento mejorado, dependiendo en tu sistema</strong>:
<ul>
<li><strong>Cambia el “<code>SPU Block Size</code>”</strong> (Tamaño de bloques del SPU) <strong>a “<code>Mega</code>”</strong> - Junta hilos de SPU para ser más pequeños, requiriendo menos núcleos/hilos. También tardara menos tiempo para iniciar el juego, dependiendo en tu sistema.</li>
<li><strong>Cambia el “<code>Preferred SPU Threads</code>”</strong> (Hilos preferidos del SPU) <strong>a “<code>1</code>”, “<code>2</code>”, “<code>3</code>”, or “<code>4</code>”</strong> - Puede ayudar a prevenir inestabilidades causadas por sobrecargas de la CPU. <strong>Empieza con “<code>4</code>” y bájalo si no mejora</strong>.</li>
</ul>
<ul>
<li><strong>Cambia “<code>Thread Scheduler</code>” (Programador de hilos) a “<code>RPCS3 Scheduler</code>”</strong> (Programador RPCS3) <strong>o “<code>RPCS3 Alternative Scheduler</code>”</strong> (Programador alternativo RPCS3). - <strong>¡SOLO PARA CPUs CON MÁS DE 12 HILOS!</strong> Esto puede ayudar con la distribución de procesos para ayudar con rendimiento.</li>
</ul>
</li>
</ul>
<!-- CPU End -->
</div>
<div role="tabpanel" class="tab-pane" id="gpu">
<!-- GPU Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/gpu.png" alt="Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando &quot;Write Color Buffers&quot; en un cuadro verde con una línea discontinua, &quot;Framelimit&quot;, &quot;Anisotropic Filter&quot;, &quot;ZCull Accuracy&quot;, &quot;Output Scaling&quot; y &quot;VSync&quot; resaltados en un cuadro azul con contorno punteado." title="GPU"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="Un cuadro verde con una línea discontinua." title="Cuadro verde"> <strong>REQUERIDO</strong>:</p>
<ul>
<li><strong>Activa “<code>Write Color Buffers</code>”</strong> (Ingresar búferes de colores) - Los personajes tendrán rendimiento corrupto sin esta opción</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Dependiendo en tu PC</strong>:</p>
<ul>
<li><strong>Activa “<code>VSync</code>”</strong> (Sincronización vertical) - Reduce el efecto de rasgado de pantalla y da fotogramas mas estables. Incrementa la latencia ligeramente. <strong>No uses esto con “Frame Limit” activado!</strong></li>
<li><strong>Cambia “<code>Framelimit</code>”</strong> (Limite de fotogramas):
<ul>
<li>Déjalo en “<code>Auto</code>” para que RPCS3 seleccioné la tasa de fotogramas.</li>
<li>“<code>Off</code>” (Desactivado) es recomendado si estas usando “<code>VSync</code>” o estas usando un limitador de fotogramas externo.</li>
<li>“<code>120</code>” es recomendado si estas usando un monitor de 144Hz (o mas.)</li>
<li><strong>¡NO ELIJAS fotogramas bajo de “<code>60</code>”!</strong></li>
<li>Aumentando las fotogramas sobre “<code>60</code>” utiliza más recursos. No es recomendado para sistemas de gama baja.</li>
<li>Esta sugerido que desactives “VSync” dentro de Rock Band 3 Deluxe: <code>Menú &gt; Opciones &gt; Configuración Deluxe &gt; Gráficos &gt; VSync</code></li>
</ul>
</li>
<li><strong>Cambia “<code>ZCULL Accuracy</code>”</strong> (Precisión de ZCull) a “<code>Relaxed</code>” (Relajada) - Mejora el rendimiento pero causa que objetos se vean raros en ángulos de cámara distantes.</li>
<li><strong>Ajusta “<code>Anisotropic Filter</code>”</strong> (Filtro anisotrópico) para que las texturas se miren mas nítidas. No debe de afectar el rendimiento tanto.</li>
<li><strong>Ajusta “<code>Resolution Scale</code>”</strong> (Nivel de resolución) a tu gusto y a lo que puede tu computadora. Auméntala para obtener gráficos más nítidos. El juego usara esta resolución. Resoluciones bajo de 100% no ayudan con rendimiento.</li>
<li><strong>Cambia “<code>Output Scaling</code>”</strong> a tu gusto y a lo que puede tu computadora. Esto afecta cómo se va “estirar” la imagen para llegar a la resolución de tu pantalla usando diferentes métodos de interpolación. Puede ayudar a los que tienen su nivel de resolución (mencionado arriba) en 100%.
<ul>
<li>“<code>Nearest</code>” (aproximación) es la interpolación mas cruda. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en pixelización.</li>
<li>“<code>Bilinear</code>” (bilineal) es interpolación mas suave. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en una imagen borrosa.</li>
<li>“<code>FidelityFX Super Resolution</code>” (FSR) usa un algoritmo complejo para mejorar la imagen cuando se estira a la resolución de tu pantalla. Raramente, puede causar anormalidades en la imagen.
<ul>
<li>Puedes usar “<code>RCAS Sharpening Strength</code>” (fuerza de enfoque) abajo para ajustar cuanta fuerza tiene el efecto.</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
<!-- GPU End -->
</div>
<div role="tabpanel" class="tab-pane" id="audio">
<!-- Audio Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/audio.png" alt="Una captura de la configuración personalizada de audio de Rock Band 3, que muestra &quot;Audio Out&quot; y &quot;Audio Buffer Duration&quot; resaltados en cuadros azules con contornos punteados, y &quot;Microphone Settings&quot;, &quot;Microphone Type&quot; (&quot;Standard&quot;), &quot;Mic1&quot;, &quot;Mic2&quot;, &quot;Mic3&quot; y &quot;Mic4&quot; resaltados en un cuadro bronceado con contorno solido." title="Audio"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Dependiendo en tu PC</strong>:</p>
<ul>
<li><strong>Ajusta “<code>Audio Buffer Duration</code>”</strong> (duración de búferes de audio) depende de tu sistema.
<ul>
<li>Bájale lo mas que puedas antes de que empiezas a escuchar errores con el sonido. Empieza con <code>32 ms</code> y ajusta de ahí.</li>
<li>Valores bajos resultan en menos latencia pero más consumo de CPU.</li>
<li>Valores altos resultan en más latencia pero menos consumo de CPU.</li>
<li>Vocalistas son los más afectados por esto porque latencia alta crea un eco. Los jugadores de instrumentos pueden usar la calibración para compensar.</li>
<li>Esto se puede cambiar mientras el juego esta abierto pero <strong>requiere recalibración</strong> en los ajustes del sistema de Rock Band 3.</li>
</ul>
</li>
<li><strong>Cambia “<code>Audio Out</code>”</strong> (Salida de audio) a <strong>“<code>XAudio2</code>”</strong> - En ocasiones raras, puede ayudar. <strong>Mayoría de las personas deben de quedarse en “<code>Cubeb</code>”</strong>. Prueba si hace una diferencia porque cambiando a XAudio2 puede causar problemas con el sonido.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Para Vocalistas</strong>:</p>
<ul>
<li><strong>Cambia “<code>Microphone type</code>”</strong> (tipo de micrófono) <strong>a “<code>Standard</code>” o “<code>Rocksmith</code>”</strong>.</li>
<li>Selecciona tu micrófonos en “<code>Mic1</code>”, “<code>Mic2</code>” y “<code>Mic3</code>” para las voces. Si no estas jugando vocales, “<code>Mic1</code>” se usara para el chat de voz.</li>
</ul>
</li>
</ul>
<!-- Audio End -->
</div>
<div role="tabpanel" class="tab-pane" id="io">
<!-- IO Start -->
<p><strong>Asegúrate que tu instrumento de MIDI este conectado.</strong><br>
<strong>Haz la ventana mas grande si no puedes leer las opciones.</strong></p>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/io.png" alt="Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando &quot;Emulated MIDI Devices&quot;, &quot;device type&quot; y &quot;device selection&quot; resaltados en cuadros bronceados con contornos solidos, y &quot;Pad Handler Mode&quot; y &quot;Keep Pads Connected&quot; en un cuadro azul con contorno punteado." title="I/O"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Ajuste dependiendo de tu PC</strong>:</p>
<ul>
<li><strong>Cambia “<code>Pad Handler Mode</code>”</strong> (Modo de manejar controladores) <strong>a “<code>Multi-threaded</code>”</strong> si tienes una CPU con mas de 12 hilos/núcleos.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadrado bronceado." title="Cuadrado bronceado">: <strong>Para jugadores de teclados MIDI, guitarra Pro, y baterías MIDI</strong>:</p>
<ul>
<li>🎹 <strong><a href="https://carlmylo.github.io/rb3-pc/ctrls_keys_midi_es" target="_blank">[Jugadores de teclado]</a>: Deja el “<code>Emulated MIDI type</code>” (Tipo de MIDI emulado) en “<code>Keyboard</code>” (teclado) y selecciona tu teclado o interfaz MIDI en el menú desplegable junto a él</strong>.</li>
<li>🎸 <strong><a href="(https://carlmylo.github.io/rb3-pc/ctrls_protar_midi)%7B:target=%22_blank%22%7D" target="_blank">[Jugadores de Guitarra Pro]</a>: Cambia el “<code>Emulated MIDI type</code>” (Tipo de MIDI emulado) de “<code>Keyboard</code>” (teclado) a “<code>Guitar (17 Frets)</code>”</strong> (guitarra (17 trastes)) <strong>si tienes una guitarra Pro Mustang, o “<code>Guitar (22 Frets)</code>”</strong> (guitarra (22 trastes)) <strong>si tienes una guitarra Pro Squier, luego selecciona tu interfaz MIDI a USB en el menú desplegable junto a él</strong>.</li>
<li>🥁 <strong><a href="https://carlmylo.github.io/rb3-pc/ctrls_drums_midi" target="_blank">[Jugadores con Baterías MIDI]</a>: Cambia el “<code>Emulated MIDI type</code>” (Tipo de MIDI emulado) de “<code>Keyboard</code>” (teclado) a “<code>Drums</code>” (batería), y selecciona tu batería o interfaz MIDI en el menú desplegable junto a él</strong>.</li>
<li>Si necesitas mas ayuda, dale otra visita a la <a href="https://carlmylo.github.io/rb3-pc/ctrls_es" target="_blank">[pagina de instrumentos]</a>.</li>
</ul>
</li>
</ul>
<!-- IO End -->
</div>
<div role="tabpanel" class="tab-pane" id="system">
<!-- System Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/system.png" alt="Una captura de la configuración personalizada del sistema de Rock Band 3, mostrando &quot;Console Language&quot; y &quot;Keyboard Type&quot; resaltados en cafe con una linea blanca solida." title="System"></p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Para cambiar el lenguaje del juego</strong>:
<ul>
<li>Cambia <strong><code>Console Language</code></strong> (Idioma del Sistema) a <strong>“<code>Spanish</code>”</strong> (Español) para cambiar el idioma de Rock Band 3 de Ingles a Español.</li>
<li>Cambia <strong><code>Keyboard Type</code></strong> (Tipo de teclado) a <strong>“<code>Spanish Keyboard</code>”</strong> (Teclado Español) para cambiar el teclado virtual de Ingles a Español.</li>
</ul>
</li>
</ul>
<!-- System End -->
</div>
<div role="tabpanel" class="tab-pane" id="network">
<!-- Network Start -->
![Una captura de la configuración personalizada de Red de Rock Band 3, mostrando "Network Status (Connected)" resaltado en un cuadro verde con una línea discontinua, "IP/Hosts switches" (rb3ps3live.hmxservices.com=45.33.44.103), "PSN Status" (RPCN) y "Enable UPNP" (no marcado) resaltado en azul claro.](https://carlmylo.github.io/rb3-pc/images/cust/network.png "Network")

* ![Un cuadro verde con una línea discontinua.](https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
    * **Cambia "`Network Status`"** (estado de red) **a "`Connected`"** (conectado) **como en la imagen. Si la dejas en "`Disconnected`"** (desconectado), **el juego se congelara mientras navegas por la biblioteca de canciones.**

* ![Un cuadro bronceado con un contorno solido.](https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png "Cuadro bronceado") **Para jugar en linea**: 
    * Activa **"`Enable UPNP`"** (activar UPnP) o **reenvía el puerto 9103 (UDP) en tu cortafuegos. No actives UPNP mientras reenvías el puerto** porque esto puede causar crasheos.
    * Para jugar Rock Band 3 en linea, agrega la direccion IP de Rock Band Enhanced.
        * Cambia "`IP/Hosts switches`" a `rb3ps3live.hmxservices.com=45.33.44.103`
<!-- Network End -->
</div>
<div role="tabpanel" class="tab-pane" id="advanced">
<!-- Advanced Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/advanced.png" alt="Una captura de la configuración personalizada avanzada, con &quot;Driver Wake-Up Delay (20µ)&quot; resaltado en un cuadro verde con una línea discontinua, &quot;Exclusive Fullscreen Mode&quot; y &quot;Maximum Number of SPURS Threads&quot; resaltados en cuadros azules con contornos punteados, y &quot;Debug Console Mode&quot; resaltado en un cuadro bronceado con un contorno solido." title="Advanced"></p>
<ul>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallgreen.png" alt="Un cuadro verde con una línea discontinua." title="Cuadro verde"> <strong>REQUERIDO</strong>:</p>
<ul>
<li><strong>Cambia el “<code>Driver Wake-up Delay</code>”</strong> (Retraso de activación de controlador) <strong>a “20µ” si tu juego se congela luego de algunas canciones. Subelo a “40µ” si sigue pasando.</strong> Si todavía sigue pasando (muy raro),  auméntalo en incrementos de 20µ.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smallblue.png" alt="Un cuadro azul con contorno punteado." title="Cuadro azul"> <strong>Dependiendo en tu PC</strong>:</p>
<ul>
<li><strong>Cambia a “<code>Maximum Number of SPURS Threads</code>”</strong> (Máximo numero de hilos de SPURS) - Puede ayudar el rendimiento de computadoras con CPU de 4 núcleos/hilos, como <a href="https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005" target="_blank">[CPUs de Intel i5 de la cuarta generación]</a>.</li>
</ul>
</li>
<li>
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado">: <strong>Recomendado</strong>:</p>
<ul>
<li><strong>Activa “<code>Debug Console Mode</code>”</strong> (Modo de depuración) - Activa esto y usa el archivo de alta memoria de Deluxe para darle mas memoria a Rock Band 3. Esto ayuda con la estabilidad y te deja instalar hasta 16000 canciones. Es recomendado que todos tengan esto activado. <a href="https://carlmylo.github.io/rb3-pc/memory_es" target="_blank">[Haz click aquí para mas información.]</a></li>
<li><strong>Cambia el “<code>Exclusive Fullscreen Mode</code>”</strong> (Modo de exclusividad de pantalla llena) <strong>a “<code>Prefer borderless fullscreen</code>”</strong> (preferir pantalla llena sin bordos) para prevenir posibles crasheos o desincronización al cambiar la prioridad del programa.</li>
</ul>
</li>
</ul>
<!-- Advanced End -->
</div>
<div role="tabpanel" class="tab-pane" id="emulator">
<!-- Emulator Start -->
<p><img src="https://carlmylo.github.io/rb3-pc/images/cust/emulator.png" alt="Una captura de la configuración personalizada del emulador de Rock Band 3, mostrando &quot;Show trophy popups&quot;, &quot;Show RPCN popups&quot;, &quot;Show shader compilation hint&quot;, &quot;Show PPU compilation hint&quot;, &quot;Show mouse and keyboard toggle hint&quot;, &quot;Start games in fullscreen mode&quot; y &quot;Use native user interface&quot; resaltados en cuadros bronceados con contornos solidos." title="Emulator"></p>
<p>Puedes dejar esto como quieras, pero consideraría ajustar estas opciones:</p>
<ul>
<li><img src="https://carlmylo.github.io/rb3-pc/images/cust/smalltan.png" alt="Un cuadro bronceado con un contorno solido." title="Cuadro bronceado"> <strong>Opcional</strong>:
<ul>
<li><strong>"<code>Show trophy popups</code>"</strong> (Mostrar notificaciones de trofeos) - Simula la notificación de trofeos de la PS3.</li>
<li><strong>"<code>Show RPCN popups</code>"</strong> (Notificaciones de RPCN) - Esto muestra notificaciones cuando tu o tus amigos inicien sesión en linea por RPCN.</li>
<li><strong>"<code>Show shader compilation hint</code>"</strong> (Mostrar notificaciones de shaders compilándose) - Esto muestra una notificación cuando RPCS3 esta compilando shaders. Cuando juegas en RPCS3, tiene que compilar shaders para “trasladar” los Gráficas de una PS3 a un formato que tu PC pueda usar. <strong>El juego seguirá trabándose mientras esto pase</strong> . <strong>Esto pasa en TODOS las PC’s.</strong> Cuando termine de compilar un efecto, <strong>esto usualmente ya no vuelve a pasar otra vez</strong>. <strong>La mejor forma de lidiar con esto es</strong> simplemente <strong>jugar al juego normalmente</strong> y luego se ira rápidamente. También puedes activar el modo de “Autoplay” y dejar que el juego toque unas canciones hasta que pare de trabarse tanto.</li>
<li><strong>"<code>Show PPU compilation hint</code>"</strong> (Mostrar notificaciones de PPUs compilándose) - Esto muestra una notificación cuando RPCS3 esta compilando unidades del PPU. Esto solo sale al inicio si tu configuración esta correcta.</li>
<li><strong>"<code>Show mouse and keyboard toggle hint</code>"</strong> (Mostrar notificaciones al cambiar a ratón y teclado) - Esto muestra notificaciones cuando cambias entre usar el teclado para el juego o para escribir en el teclado virtual dentro del juego.</li>
<li><strong>"<code>Start games in Fullscreen mode</code>"</strong> (Empezar juego en pantalla llena) - Activa esto para que RPCS3 cambie al modo de pantalla completa cuando inicies Rock Band 3.</li>
<li><strong>"<code>Use Native Interface</code>"</strong> (Usar interfaz nativa) - Si desactivas esto,  hará que se remuevan todas las notificaciones de RPCS3 mientras estás jugando, incluyendo el teclado y fondo mientra el juego cargue. En su lugar, verás una interfaz más antigua. Ayudar si el juego se trababa cuando estés nombrando algo con ciertos instrumentos.</li>
</ul>
</li>
</ul>
<!-- Emulator End -->
</div>
</div>


{% include links.html %}