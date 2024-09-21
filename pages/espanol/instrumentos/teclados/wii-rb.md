---
title: Teclado de Rock Band 3 para Nintendo Wii
sidebar: controllers_es_sidebar
permalink: ctrls_keys_wii_es
folder: instrumentos
tags: [wii-es, midi-es, teclados, espanol]
summary: "Como conectar y configurar teclados de RB3 (en modo MIDI) para Wii en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/wii.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/wiirbkeyscontroller.png" alt="Control" title="Control"></div>

## NOTAS:

* No existe un perfil para este instrumento.
* **NO mapeés este instrumento por el menú de "Pads".**
* Los botones del teclado no van a funcionar normalmente porque esta en modo MIDI.
* Se puede conectar un pedal de sostén para activar sobrecarga.
* Se requiere una versión de [[RPCS3 actual]](https://rpcs3.net/download).
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden causar que el juego se quede atorado. Es recomendado tener otra manera de controlar estos menos, como [[un teclado de PC o un mando estándar]](https://rb3pc.milohax.org/ctrls_pads_es){:target="_blank"}.

## Instrucciones:

No puedes usar este teclado con el receptor, asi que vas a a necesitar conectar el teclado de Rock Band 3 por el puerto de MIDI que esta en el lado.

>![Una foto del teclado de Rock Band 3, con un puerto de MIDI estilo DIN de cinco pines resaltado en un cuadro azul con contorno punteado.](https://rb3pc.milohax.org/images/midi/rbkeys.png "Teclado de Rock Band 3")  

**Para conectarlo a tu computadora, necesitarás un convertidor/interfaz de MIDI a USB**.

Aquí esta un ejemplo de un adaptador de MIDI a USB. Mayoría tiene una luz LED integrada para mostrar activad. **Para verificar que esta todo enchufado correctamente, debes de ver "MIDI In" parpadeando cuando le toques una nota**.

>![Una imagen de una interfaz de MIDI a USB.](https://rb3pc.milohax.org/images/midi/miditousb.png "Interfaz de MIDI a USB")  

**Si tienes una interfaz de audio, puede ser que ya tengas un puerto de MIDI** para tu computadora, ya que unas interfaces tienen puertos de MIDIs integrados. Por ejemplo, esta Scarlett tiene conexiones MIDI por detrás.    
>![Una imagen del posterior de una Focusrite Scarlett, mostrando un puerto de USB y un salida/entrada MIDI por puerto DIN de cinco pines.](https://rb3pc.milohax.org/images/midi/midifs.png "Salida/Entrada MIDI de Focusrite Scarlett") 

Decide cual manera es mas conveniente para ti y conecta tu teclado de Rock Band 3 a tu computadora.

Después de eso, **haz click derecho en Rock Band 3** en RPCS3 y luego en **"Change Custom Configuration"** (Cambiar configuración personalizada).  

![Una captura del menú de clic derecho de RPCS3, mostrando "Change Custom Configuration" (Cambiar configuración personalizada) resaltado.](https://rb3pc.milohax.org/images/cust/rpcs3customconfigchange.png "Change Custom Configuration")

![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando "Emulated MIDI Devices", tipo de dispositivo y selección de dispositivos resaltados en cuadros bronceados con contornos sólidos.](https://rb3pc.milohax.org/images/cust/io.png "I/O")

* ![Un cuadro bronceado con un contorno solido.](https://rb3pc.milohax.org/images/cust/smalltan.png "Un cuadrado bronceado.") : 
	* 🎹 **Deja tu “Emulated MIDI type”** (Tipo de MIDI emulado) **en “Keyboard”** (teclado) **y selecciona tu teclado o interfaz MIDI en el menú desplegable junto a él**.

### Información Adicional::

Los botones del teclado no van a funcionar como funcionan cuando esta conectado a su consola propia. Por eso vas a tener que cambiar de octava para accessar los botones de control.

Puedes cambiar de octava con los botones de `1` y `B`.

![Una animación de un teclado de Rock Band 3. Cuando se presiona el botón que seria 1, un resaltado amarillo, que muestra el rango de notas activas, cambia a C2-C4. Cuando se presiona el botón que seria B, cambia a C3-C5.](https://rb3pc.milohax.org/images/instruments/xtra/midi/rbkeysoctshift.gif "Cambio de octava") 

| **Nota** | **Botón** |
|:--------:|:-------------------:|
| C2 | ![Select](https://rb3pc.milohax.org/images/btns/ctrls/ps3/sel.png "Select") |
| D2 | ![D-Pad (Cruceta) Izquierda](https://rb3pc.milohax.org/images/btns/ctrls/ps3/dl.png "D-Pad (Cruceta) Izquierda") |
| E2 | ![D-Pad (Cruceta) Derecha](https://rb3pc.milohax.org/images/btns/ctrls/ps3/dr.png "D-Pad (Cruceta) Derecha") |
| F2 | ![D-Pad (Cruceta) Arriba](https://rb3pc.milohax.org/images/btns/ctrls/ps3/du.png "D-Pad (Cruceta) Arriba") |
| G2 | ![D-Pad (Cruceta) Abajo](https://rb3pc.milohax.org/images/btns/ctrls/ps3/dd.png "D-Pad (Cruceta) Abajo") |
| A2 | Sobrecarga |
| C#2 | ![Triangle (Triangulo)](https://rb3pc.milohax.org/images/btns/ctrls/ps3/t.png "Triangle (Triangulo)") |
| D#2 | ![Square (Cuadro)](https://rb3pc.milohax.org/images/btns/ctrls/ps3/s.png "Square (Cuadro)") |
| F#2 | ![Circle (Circulo)](https://rb3pc.milohax.org/images/btns/ctrls/ps3/o.png "Circle (Circulo)") |
| G#2 | ![Cross (Cruz)](https://rb3pc.milohax.org/images/btns/ctrls/ps3/x.png "Cross (Cruz)") |
| A#2 | ![Start](https://rb3pc.milohax.org/images/btns/ctrls/ps3/sta.png "Start") |
| Perilla de modulación | Sobrecarga |
| Sostén | Sobrecarga |
| Perilla de Pitch | Franja Táctil |

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#teclado-midi-y-compu">Usando un teclado de computadora al lado de un teclado MIDI</a>
                            </h4>
                        </div>
                        <div id="teclado-midi-y-compu" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <ul>
<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>¡Esto requiere configuración avanzada!</b> {{include.content}}</div>
<p>Puedes usar tu teclado de computadora y convertir las teclas a notas MIDI que corresponden a los botones del juego. Esto es para que cambies de octava tan seguido.<br>
First, <a href="https://www.tobias-erichsen.de/software/loopmidi.html">[descarga loopMIDI]</a>.</p>
<p><a href="https://www.tobias-erichsen.de/software/loopmidi.html" title="Tobias Erichsen - loopMIDI"><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlloopMIDIdl.png" alt="Una captura de la pagina de descarga de loopMIDI."></a></p>
<p>Instala loopMIDI. <strong>Ábrelo cuando termine de instalar.</strong></p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlloopMIDIinst.png" alt="Una captura del instalador de loopMIDI." title="loopMIDI Setup"></p>
<p>Usa el botón de <code>+</code> abajo para agregar dos puertos nuevos. Nombra los puertos. En este ejemplo, los nombre "Pro Keys" y "Gamepad".</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlloopMIDIaddport.png" alt="Una captura de loopMIDI, con el cursor sobre el botón + que agrega mas puertos. También, &quot;New port name&quot; esta resaltado en azul con &quot;Pro Keys&quot; escrito en el cuadro de texto." title="loopMIDI"></p>
<p>Ahora, descarga <a href="https://freepiano.tiwb.com/en/">[el archivo <code>.zip</code> de FreePiano que tiene la versión de win64.]</a>.</p>
<p><a href="https://freepiano.tiwb.com/en" title="FreePiano - Advanced virtual MIDI keyboard"><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlfreepnodl.png" alt="Una captura de la pagina de descargas de FreePiano."></a></p>
<p>Extrae el archivo <code>.zip</code> donde puedas encontrarlo fácilmente. En este ejemplo, fue extraído a <code>C:\Games\freepiano</code>.</p>
<p>Ve a donde extrajiste el archivo <code>.zip</code> y abre la aplicación de freepiano.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlfreepnodir.png" alt="Una captura con la aplicación de freepiano resaltada." title="freepiano.exe"></p>
<p>Puedes configurar las teclas a tu gusto usando la sección de <a href="#mapeo"><strong>[#mapeo]</strong></a> hacia arriba.</p>
<p>También existe un perfil pre-hecho que puedes <a href="https://github.com/carlmylo/docu-rpcs3/raw/refs/heads/gh-pages/downloads/instrument-repo/rb3gamekeys.map"><strong>[descargar aquí]</strong></a>.</p>
<p>Para usar el perfil, coloca el archivo <code>rb3gamekeys.map</code> en la carpeta llamada <code>keymap</code> donde esta la aplicación de freepiano.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlfreepnopreset.png" alt="Una captura del perfil llamado rb3gamekeys.map resaltado, dentro de la carpeta llamada keymap.." title="keymap"></p>
<p>Selecciona el archivo <code>rb3gamekeys.map</code> en el menú despegable de "Keymap" para cargar el perfil. También, si existe creaste tu propio perfil o editaste el perfil pre-hecho, puedes hacer click en <strong>Save</strong> para guardarlo.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlfreepnoselpres.png" alt="Una captura de FreePiano con el perfil de rb3gamekeys.map seleccionado." title="rb3gamekeys.map"></p>
<p>El perfil pre-hecho esta configurado así:</p>

<table>
<thead>
<tr>
<th align="center"><strong>Tecla</strong></th>
<th align="center"><strong>Acción</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Entrar</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/sta.png" alt="Start" title="Start"></td>
</tr>
<tr>
<td align="center">Shift (Mayús) Izquierdo</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/sel.png" alt="Select" title="Select"></td>
</tr>
<tr>
<td align="center">Arriba</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/du.png" alt="D-Pad (Cruceta) Arriba" title="D-Pad (Cruceta) Arriba"></td>
</tr>
<tr>
<td align="center">Abajo</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/dd.png" alt="D-Pad (Cruceta) Abajo" title="D-Pad (Cruceta) Abajo"></td>
</tr>
<tr>
<td align="center">Izquierda</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/dl.png" alt="D-Pad (Cruceta) Izquierda" title="D-Pad (Cruceta) Izquierda"></td>
</tr>
<tr>
<td align="center">Derecha</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/dr.png" alt="D-Pad (Cruceta) Derecha" title="D-Pad (Cruceta) Derecha"></td>
</tr>
<tr>
<td align="center">A</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/x.png" alt="Cross (Cruz)" title="Cross (Cruz)"></td>
</tr>
<tr>
<td align="center">S</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/o.png" alt="Circle (Circulo)" title="Circle (Circulo)"></td>
</tr>
<tr>
<td align="center">D</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/s.png" alt="Square (Cuadro)" title="Square (Cuadro)"></td>
</tr>
<tr>
<td align="center">F</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps3/t.png" alt="Triangle (Triangulo)" title="Triangle (Triangulo)"></td>
</tr>
</tbody>
</table><p>Cuando termines de mapear, haz click en "Instrument" en la parte de arriba de la pantalla FreePiano y selecciona la salida MIDI "Gamepad", que creaste con loopMIDI anteriormente.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlfreepnoout.png" alt="Una captura de el menú despegable de Instrumento dentro de Freepiano, con &quot;Gamepad MIDI&quot; seleccionado." title="Gamepad"></p>
<p>Es recomendado que actives "Background input mode", dentro la pestaña de "Options". Se puede acceder con el icono de llave.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlfreepnoback.png" alt="Una captura de FreePiano, con la opción de &quot;Background input mode&quot; activada." title="Background input mode"></p>
<p>Ahora, <a href="http://www.midiox.com/moxdown.htm">[descarga MIDI-OX]</a>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlmidioxdl.png" alt="Una captura del sitio de MIDI-OX, con en enlace correcto resaltado en un cuadro azul con contorno punteado." title="MIDI-OX 7.0.2"></p>
<p>Instala MIDI-OX.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlmidioxinst.png" alt="Una captura del instalador de MIDI-OX." title="MIDI-OX Setup Wizard"></p>
<p>Abre MIDI-OX y ve a <strong>Options &gt; MIDI Devices</strong></p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlmidioxopts.png" alt="Una captura de MIDI-OX, con el cursor sobre el menú despegable de Options, en MIDI Devices." title="Options > Midi Devices"></p>
<p>En el menú de "MIDI Devices", elije tu teclado y el puerto que creaste con loopMIDI ("Gamepad") para FreePiano en la sección de "MIDI Inputs.".<br>
Selecciona el otro puerto que creaste en loopMIDI ("Pro Keys") en la sección de "MIDI Outputs." Esto combinara las entradas de MIDI a una sola salida.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlmidioxcombo.png" alt="Una captura de MIDI Devices dentro de MIDI-OX, que muestra un teclado y el puerto de Gamepad seleccionado en la sección de MIDI Inputs y Pro Keys seleccionada en la sección de MIDI Outputs." title="MIDI Devices"></p>
<p>Finalmente, ve a la configuración personalizada de Rock Band 3 dentro de RPCS3 y entra a la pestaña de I/O. Selecciona el puerto que seleccionaste como la salida en MIDI-OX ("Pro Keys").</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/midi/midictrlrpcs3.png" alt="Una capture de loa configuración personalizada de Rock Band 3, dentro de la pestaña de I/O. En la sección de Emulated MIDI Devices, el tipo de instrumento y instrumento seleccionado están resaltados en cuadros bronceados con contornos sólidos. Esta puesto en &quot;Keyboard - Pro Keys 3&quot;" title="Settings: [BLUS30463] Rock Band 3"></p>
<p>Eso es todo. Recuerda que tienes que cerrar <strong>los tres programas distintos</strong> cuando no los estés usando, porque pueden causar problemas con los atajos de Windows.<br>
Tienes que abrirlos cada vez que quieras jugar.</p>


</ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Investigación por [[Linos]](https://www.youtube.com/@LinosMelendi)