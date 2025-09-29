---
title: "Batería de Rock Band 4 para Xbox One"
sidebar: controllers_es_sidebar
permalink: ctrls_rb4drums_xbox_es
folder: instrumentos
tags: [xbox-one-es, baterias, espanol]
summary: "Como configurar tu batería de Rock Band 4 para Xbox One en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/xbx.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rb4drmscontroller.png" alt="Control" title="Control"></div>

## NOTAS
* Requiere que descargues y instales [[**RB4InstrummentMapper**]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.es.md/){:target="_blank"} con ViGEmBus.
* Usuarios de **Linux** pueden instalar los [[controladores de kernel de `xone`]](https://github.com/dlundqvist/xone) para usar periféricos de Xbox One. Toma nota que esta pagina y sus instrucciones están en Ingles.
* Estas baterias requieren un Adaptador de Xbox inalámbrico para Windows.  
    ![Adaptador inalámbrico para Windows](https://rb3pc.milohax.org/images/btns/ctrls/xbox/receiver.png "Adaptador inalámbrico para Windows")  
* Funciona **con o sin** platillos PRO.
    * Recuerda configurar cuales platillos tienes conectados dentro de Rock Band 3.
        * `Menu > Opciones > Opciones de Batería`
* La detección de velocidad (intensidad) no funciona.
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://rb3pc.milohax.org/ctrls#gamepads_es){:target="_blank"}.

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>¿Tienes problemas conectando tu instrumento para Xbox One?</b> {{include.content}}</div>

1. Ve a `Inicio` > `Configuración`  > `Aplicaciones` > `Aplicaciones instaladas`  
2. Busca `Microsoft GameInput` y desinstala la versión mas actual.  
Toma en cuenta que se puede reinstalar después de un reinicio. Estamos buscando soluciones mejores.  

![Microsoft GameInput en la lista de aplicaciones instaladas, siendo mala y rompiendo instrumentos.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/gameinput.png "Aplicaciones instaladas")  

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#como-mapear-pads">¿Como configuro mi batería?</a>
                            </h4>
                        </div>
                        <div id="como-mapear-pads" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<p><strong>Haz click en el icono de Pads hacia arriba de RPCS3</strong>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3pad.png" alt="Una captura de RPCS3, mostrando el cursor sobre el icono de Pads." title="Pads"></p>
<p>Recomendamos crear una configuración nueva con el botón de <code>Add Configuration</code> hacia arriba y a la derecha de pantalla de <code>Pads</code>.<br>
Esto es por si juegas otros juegos en RPCS3 que no usen instrumentos.<br>
<img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofadd.png" alt="A screenshot of the top right of RPCS3's Pads window. &quot;Add Configuration&quot; is being clicked on by the mouse cursor." title="Add Configuration"></p>
<p>Sigue las instrucciones y/o copia el mapeo de la lista para tu instrumento.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/padlegend.png" alt="Una imagen mostrando como puedes usar una pagina de instrumentos para configurar a RPCS3." title="Mapeando la Höfner de Rock Band"></p>
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
| Drums | Rock Band Pro |

### Configuración Adicional:

Por favor lee la documentación de RB4InstrumentMapper.  
[[Haz click aquí para leerla]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.es.md){:target="_blank"}.

## Mapeo

### Controller Emulation Mode: ViGEmBus (RPCS3 compatibility)

Este es el modo recomendado porque no requiere configuración adicional. Solo requiere que elijes la información de control correcta (Handler, Device y Device Class/Type).

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmsxomapping.png" alt="Mapeo" title="Mapeo"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mapeo-avanzado">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="mapeo-avanzado" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<p>Esto no es recomendado porque requiere muchos ajustes manuales. Deberías usar el modo <strong>ViGEmBus (RPCS3 compatibility)</strong>.</p>
<h4 id="perfil">Perfil</h4>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Xbox%20Rock%20Band%20Drums.7z">[Descargar Perfil]</a></p>
<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>Esto no se recomienda si estas usando mas de un instrumento a la vez. </b> {{include.content}}</div>
<p>Después de descargar el perfil,</p>
<ol>
<li>Extrae el archivo .7z.</li>
<li>Arrastra la carpeta "<code>input configs</code>" a la carpeta "<code>configs</code>" en la carpeta donde tienes RPCS3.</li>
</ol>
<p><img src="https://rb3pc.milohax.org/images/instruments/instrepoinstall.gif" alt="Una animación de alguien arrastrando el perfil para las guitarras de Rock Band para Wii a su carpeta de RPCS3." title="Instalando un perfil del Repo de Instrumentos"></p>
<p>Después de eso, puedes seleccionar el perfil en el menú de "<code>Pads</code>".</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofile.png" alt="Una captura de Gamepad Settings dentro de RPCS3, con el cursor sobre un perfil." title="Gamepad Settings"></p>
<p>La mayoría del tiempo, estos perfiles funcionan sin configuración adicional. Por si acaso no, trata de cambiar el control en "<code>Devices</code>", al lado del botón de "<code>Refresh</code>" hasta que funcione. Puedes cambiar esto mientras el juego esté abierto.</p>
<h4 id="configuracion">Configuración</h4>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Batería</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/gp.png" alt="Parche Verde" title="Parche Verde"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/rp.png" alt="Parche Rojo" title="Parche Rojo"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/bp.png" alt="Parche Azul" title="Parche Azul"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/yp.png" alt="Parche Amarillo" title="Parche Amarillo"></td>
</tr>
<tr>
<td align="center">R3</td>
<td align="center">Modificador de Platillos</td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center">Modificador de Platillo Amarillo</td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center">Modificador de Platillo Azul</td>
</tr>
<tr>
<td align="center">L3</td>
<td align="center">Modificador de Parches</td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Pedal/Kick" title="Pedal/Kick"></td>
</tr>
<tr>
<td align="center">R1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Segundo Pedal/Kick" title="Segundo Pedal/Kick"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/a.png" alt="Botón A" title="Botón A"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/b.png" alt="Botón B" title="Botón B"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/x.png" alt="Botón X" title="Botón X"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/y.png" alt="Botón Y" title="Botón Y"></td>
</tr>
<tr>
<td align="center">D-Pad</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/xbox/dp.png" alt="D-Pad (Cruceta)" title="D-Pad (Cruceta)"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
<p><div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmsxboxrbmapping.png" alt="Mapeo" title="Mapeo"></div></p>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Mapeado por [[gonakil1ya]](https://gonakillya.neocities.org)
