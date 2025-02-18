---
title: "Guitarras de Rock Band 4/Fortnite Festival para Xbox One"
sidebar: controllers_es_sidebar
permalink: ctrls_rb4gtr_xbox_es
folder: instrumentos
tags: [xbox-one-es, guitarras, espanol]
summary: "Como configurar tu guitarra de Rock Band 4/Fortnite Festival para Xbox One con RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/plat/xbx.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/cont/rb4gtrscontroller.png" alt="Control" title="Control"></div>

## NOTAS

* Requiere que descargues y instales [[**RB4InstrummentMapper**]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.es.md/){:target="_blank"} con ViGEmBus.
* Usuarios de **Linux** pueden instalar los [[controladores de kernel de `xone`]](https://github.com/dlundqvist/xone) para usar periféricos de Xbox One. Toma nota que esta pagina y sus instrucciones están en Ingles.
* Este perfil funciona con la Fender Stratocaster, Fender Jaguar y la PDP Riffmaster para Xbox One.
	* La Fender Stratocaster y la Fender Jaguar requieren un Adaptador inalámbrico para Windows.  
	![Adaptador inalámbrico para Windows](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/xbox/receiver.png "Adaptador inalámbrico para Windows")  
	* La PDP Riffmaster requiere su receptor propio.  
	![Receptor de PDP Riffmaster](https://carlmylo.github.io/rb3-pc/images/btns/ctrls/xbox/riffrec.png "Receptor de PDP Riffmaster")  
* Si tienes una Fender Jaugar, es posible que vas a necesitar instalar una [[actualización de firmware]](https://bit.ly/2UHzonU){:target="_blank"} para conectarla al receptor. [[Haz click aqui para mas información.]](https://bit.ly/2UHzonU){:target="_blank"}.
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://carlmylo.github.io/rb3-pc/ctrls#gamepads_es){:target="_blank"}.

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#como-mapear-pads">¿Como configuro mi guitarra?</a>
                            </h4>
                        </div>
                        <div id="como-mapear-pads" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<p><strong>Haz click en el icono de Pads hacia arriba de RPCS3</strong>.</p>
<p><img src="https://carlmylo.github.io/rb3-pc/images/instruments/rpcs3pad.png" alt="Una captura de RPCS3, mostrando el cursor sobre el icono de Pads." title="Pads"></p>
<p>Recomendamos crear una configuración nueva con el botón de <code>Add Configuration</code> hacia arriba y a la derecha de pantalla de <code>Pads</code>.<br>
Esto es por si juegas otros juegos en RPCS3 que no usen instrumentos.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/instruments/rpcs3padprofadd.png" alt="A screenshot of the top right of RPCS3's Pads window. &quot;Add Configuration&quot; is being clicked on by the mouse cursor." title="Add Configuration"></p>
<p>Sigue las instrucciones y/o copia el mapeo de la lista para tu instrumento.</p>
<p><img src="https://carlmylo.github.io/rb3-pc/images/instruments/padlegend.png" alt="Una imagen mostrando como puedes usar una pagina de instrumentos para configurar a RPCS3." title="Mapeando la Höfner de Rock Band"></p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Map End -->

## Información de Control

| Handlers | Devices |
|:--------:|:-------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Guitar | Rock Band |

### Configuración Adicional:

Por favor lee la documentación de RB4InstrumentMapper.  
[[Haz click aquí para leerla]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.es.md){:target="_blank"}.

## Mapeo

### Controller Emulation Mode: ViGEmBus (RPCS3 compatibility)

Este es el modo recomendado porque no requiere configuración adicional. Solo requiere que elijes la información de control correcta (Handler, Device y Device Class/Type).

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mapeo-avanzado">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="advanced-mapping" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<h4 id="perfil">Perfil</h4>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Xbox%20Rock%20Band%20Guitar.7z">[Descargar Perfil]</a></p>
<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>Esto no se recomienda si estas usando mas de un instrumento a la vez. </b> {{include.content}}</div>
<p>Después de descargar el perfil,</p>
<ol>
<li>Extrae el archivo .7z.</li>
<li>Arrastra la carpeta "<code>input configs</code>" a la carpeta "<code>configs</code>" en la carpeta donde tienes RPCS3.</li>
</ol>
<p><img src="https://carlmylo.github.io/rb3-pc/images/instruments/instrepoinstall.gif" alt="Una animación de alguien arrastrando el perfil para las guitarras de Rock Band para Wii a su carpeta de RPCS3." title="Instalando un perfil del Repo de Instrumentos"></p>
<p>Después de eso, puedes seleccionar el perfil en el menú de "<code>Pads</code>".</p>
<p><img src="https://carlmylo.github.io/rb3-pc/images/instruments/rpcs3padprofile.png" alt="Una captura de Gamepad Settings dentro de RPCS3, con el cursor sobre un perfil." title="Gamepad Settings"></p>
<p>La mayoría del tiempo, estos perfiles jalan sin configuración adicional. Por si acaso no, trata de cambiar el control en "<code>Devices</code>", al lado del botón de "<code>Refresh</code>" hasta que funcione. Puedes cambiar esto mientras el juego esté abierto.</p>
<h4 id="configuracion">Configuración</h4>
<p>El switch de efectos solo puede ser configurado con la mitad de arriba o de abajo. Recomendamos la mitad de abajo para poder desactivar los efectos.</p>

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
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/start.png" alt="Start" title="Start"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/back.png" alt="Back" title="Back"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://carlmylo.github.io/rb3-pc/images/btns/ctrls/360/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
<p><div align="center"> <img src="https://carlmylo.github.io/rb3-pc/images/instruments/maps/gtrxboxrbmapping.png" alt="Mapeo" title="Mapeo"></div></p>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Regresar a la lista de instrumentos]](https://carlmylo.github.io/rb3-pc/ctrls_es#lista-de-instrumentos)

Mapeado por [[gonakil1ya]](https://linktr.ee/Gonakil1ya){:target="_blank"}