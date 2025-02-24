---
title: Guitarra Riffmaster con Adafruit Feather
sidebar: controllers_es_sidebar
permalink: ctrls_mod_riffada_es
folder: instrumentos
tags: [modeado, guitarras, espanol]
summary: "Como configurar tu guitarra de Riffmaster conectada con una Adafruit Feather en RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/plat/santroller.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/cont/riffmastercontroller.png" alt="Control" title="Control"></div>

## NOTAS

* **¡Esto es specificamente para la Riffmaster con** [**[Adafruit Feather RP2040 con puerto de USB tipo A de entrada]**](https://www.adafruit.com/product/5723)**!** Verifica que si compraste una [[Adafruit Feather RP2040 **con puerto de USB tipo A de entrada**]](https://www.adafruit.com/product/5723).
* Puedes conectar una la Riffmaster de Xbox pero mejor deberías usar [[RB4InstrumentMapper]](https://carlmylo.github.io/rb3-pc/ctrls_rb4gtr_xbox_es).

## Información de Control

| Handlers | Devices |
|:--------:|:-------:|
| XInput | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Guitar | Rock Band |

## Configuración:

Descarga la versión actual de Santroller.

[![Una captura de la pagina de descarga de Githubs para Santroller, con el cursor sobre el instalador de Windows.](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/feather/dlsan.png)](https://github.com/Santroller/Santroller/releases "SantrollerConfigurator")

After downloading Santroller, open "SantrollerConfigurator".

Después de descargar y instalando Santroller, ábrelo.

![Una captura de el escritorio, con el cursor sobre SantrollerConfigurator.](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/feather/opensan.png "SantrollerConfigurator")

Presiona y sostén el botón "Boot" en tu Adafruit Feather RP2040 si la estas conectando a tu computadora por la primera vez.

![Una imagen de una Adafruit Feather RP2040. Un botón nombrado "Boot" esta circulado en rojo, blanco y negro.](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/feather/bootada.jpg "Adafruit Feather RP2040 con puerto de USB tipo A de entrada")

En Santroller, cambia el "`Tipo de Entrada`" a "`Adaptador USB`." El "`Dispositivo Seleccionado`" debe de estar en "`Raspberry Pi Pico`." Haz click en "`Configurar`" después de confirmar y dale un momento para que inicie.

![Una captura de Santroller, con el cursor sobre "Adaptador USB" para la derecha de "Tipo de Entrada."](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/feather/sanusbes.png "SantrollerConfigurator")

After you've loaded into the configuration page, scroll down to the "`Presets`" section and click to expand it. Once expanded, click on "`Import Settings from File`"

Cuando la pagina de configuración cargue, ve para abajo donde esta la sección de "`Preestablecidos`" y haz click en "`Importar Ajustes de Archivo`."  
Para ayudar con esto, un perfil hecho por la comunidad (gracias a Jnack) fue creado. Cargalo con la opcion de "`Importar Ajustes de Archivo`"  

[[Descarga el perfil `.picoconfig` aquí]](https://carlmylo.github.io/rb3-pc/downloads/instrument-repo/RiffmasterFeather.picoconfig).

![Una captura de Santroller, en la sección de "Preestablecidos" con el cursor sobre "Importar Ajustes de Archivo."](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/feather/sanpreloades.png "Preestablecidos")

After loading the preset, **MAKE SURE YOU CLICK ON "`Save Settings`" before closing the program or you will lose progress!**

!Despues de cargar el archivo `.picoconfig`, **ASEGÚRATE DE HACER CLICK EN "`Guardar Ajustes`" ANTES DE CERRAR EL PROGRAMA O PERDERÁS TUS CAMBIOS!**

![Una captura de Santroller, con el cursor sobre Guardar Ajustes.](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/feather/sansavees.png "Santroller")

## Mapeo

Por defecto, XInput tiene mayoría de las cosas configuradas correctamente. Solo necesitas ajustar esto:

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----------:|
| R1 | ![Palanca izquierda](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/rs.png "Palanca izquierda") | ![Ladeo](https://carlmylo.github.io/rb3-pc/images/btns/gtrs/ts.gif "Ladeo") | 
| L2 | ![Palanca derecha presionada](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/rsc.png "Palanca derecha presionada") | ![Botón de solos](https://carlmylo.github.io/rb3-pc/images/btns/gtrs/solo.png "Botón de solos") | 
| Left Stick: <br> Abajo | ![Gatillo Izquierdo](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/lt.png "Gatillo Izquierdo") | ![Switch de efectos](https://carlmylo.github.io/rb3-pc/images/btns/gtrs/fx.png "Switch de efectos") |

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mapeo-avanzado">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="mapeo-avanzado" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Guitarra</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/gf.png" alt="Traste Verde" title="Traste Verde"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/rf.png" alt="Traste Rojo" title="Traste Rojo"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/yf.png" alt="Traste Amarillo" title="Traste Amarillo"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/bf.png" alt="Traste Azul" title="Traste Azul"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/of.png" alt="Traste Naranja" title="Traste Naranja"></td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/sbu.png" alt="Rasgueo para arriba" title="Rasgueo para arriba"></td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/sbd.png" alt="Rasgueo para abajo" title="Rasgueo para abajo"></td>
</tr>
<tr>
<td align="center">D-Pad: Left</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/dpl.png" alt="D-Pad (Cruceta): Izquierda" title="D-Pad (Cruceta): Izquierda"></td>
</tr>
<tr>
<td align="center">D-Pad: Right</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/dpr.png" alt="D-Pad (Cruceta): Derecha" title="D-Pad (Cruceta): Derecha"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Left/Right</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/wb.png" alt="Palanca de whammy" title="Palanca de whammy"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Up/Down</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/fx.png" alt="Switch de efectos" title="Switch de efectos"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/solo.png" alt="Botón de solos" title="Botón de solos"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/gtrs/ts.gif" alt="Ladeo" title="Ladeo"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/start.png" alt="Botón + (Mas)" title="Start"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/back.png" alt="Botón - (Menos)" title="Back"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

## Notas adicionales:

El archivo `.picoconfig` cambia unas cosas para tener una experiencia mejor con la Riffmaster de PS4.  

- El botón de "Boot" en la Adafruit Feather va funcionar como el botón de guía/Home si lo presionas y el botón de guía/Home en la Riffmaster apaga la guitarra.

- D-Pad (Cruceta): Izquierda y el botón de Select están invertidos. Esto es porque la configuración, por defecto, la Riffmaster de PlayStation tiene activación de Sobrecarga en D-Pad (Cruceta) Izquierda y es muy incomodo

Si no quieres tener estos cambios, haz click en `Remover` en `D-pad Derecho` y `Botón Select.`

![Una captura de Santroller. Hay círculos sobre "D-pad Derecho" y Botón Select.](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/feather/sanremes.png "SantrollerConfigurator")

Después de eso, va a la sección de "`Entradas de Host por USB`" y Habilita `D-pad Derecho` y el `Botón Select.`

![Una captura de Santroller, en la sección de "Entradas de Host por USB". Hay círculos sobre los botones deshabilitados.](https://carlmylo.github.io/rb3-pc/images/instruments/xtra/feather/sanhostines.png "Entradas de Host por USB")

## Perfil:

[[Descargar Perfil]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Feather%20Riffmaster.7z)

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/maps/360rbgtrsmapping.png" alt="Mapeo" title="Mapeo"></div>

### Modo Passthrough

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>Por ahora, RPCS3 no tiene soporte de "hotplugging" (cambio en caliente). Esto significa que vas a tener que tener la guitarra conectada antes de abrir RPCS3. El modo Passthrough te deja conectar la guitarra sin tener que mapear nada pero, como RPCS3 no tiene soporte de "hotplugging" (PS3/Emulador), tendrás que iniciar el juego dos veces. Por esto, no es recomendable usar modo Passthrough. </b> {{include.content}}</div>

[[Regresar a la lista de instrumentos]](https://carlmylo.github.io/rb3-pc/ctrls_es#lista-de-instrumentos)

Investigación por [jnackmclain](https://github.com/jnackmclain)