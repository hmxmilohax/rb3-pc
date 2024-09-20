---
title: "Batería de Rock Band 4 para Xbox One"
sidebar: controllers_es_sidebar
permalink: ctrls_rb4drums_xbox_es
folder: instrumentos
tags: [xbox-one, baterias, espanol]
summary: "Como configurar tu batería de Rock Band 4 para Xbox One con RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/xbx.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rbdrmscontroller.png" alt="Control" title="Control"></div>

## NOTAS:
* Requiere que descargues y instales [[**RB4InstrummentMapper**]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.es.md/){:target="_blank"} con ViGEmBus.
* Estas baterias requieren un Adaptador inalámbrico para Windows.  
    ![Adaptador inalámbrico para Windows](https://rb3pc.milohax.org/images/btns/ctrls/xbox/receiver.png "Adaptador inalámbrico para Windows")  
* Funciona **con o sin** platillos PRO.
    * Recuerda configurar cuales platillos tienes conectados dentro de Rock Band 3.
        * `Menu > Opciones > Opciones de Batería`
* La detección de velocidad (intensidad) no funciona.
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://rb3pc.milohax.org/ctrls_pads_es){:target="_blank"}.


## Información de Control:

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Drums | Rock Band Pro |

### Configuración Adicional:

Por favor lee la documentación de RB4InstrumentMapper.  
[[Haz click aquí para leerla]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.es.md){:target="_blank"}.

## Mapeo:

### Controller Emulation Mode: ViGEmBus (RPCS3 compatibility)

Este es el modo recomendado porque no requiere configuración adicional. Solo requiere que elijes la información de control correcta (Handler, Device y Device Class/Type).

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmsxomapping.png" alt="Mapeo" title="Mapeo"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#controller-emulation-mode-vigembus">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="controller-emulation-mode-vigembus" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<p><a href="https://github.com/carlmylo/docu-rpcs3/raw/gh-pages/downloads/instrument-repo/Xbox%20Rock%20Band%20Drums.7z" target="_blank">[Bajar Perfil]</a></p>
<p>Esto no es recomendado porque requiere muchos ajustes manuales. Deberías usar el modo <strong>ViGEmBus (RPCS3 compatibility)</strong>.</p>
<p>Por defecto, XInput tiene mayoría de las cosas configuradas correctamente. Solo necesitas ajustar esto:</p>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>XInput</strong></th>
<th align="center"><strong>Batería</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Boton R1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/lsc.png" alt="Palanca izquierda presionada" title="Palanca izquierda presionada"></td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Segundo Pedal/Kick" title="Segundo Pedal/Kick"></td>
</tr>
<tr>
<td align="center">L3</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/rsc.png" alt="Palanca derecha presionada" title="Palanca derecha presionada"></td>
<td align="center">Modificador de Parches</td>
</tr>
<tr>
<td align="center">R3</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/rb.png" alt="Botón Bumper Derecho" title="Botón Bumper Derecho"></td>
<td align="center">Modificador de Platillos</td>
</tr>
</tbody>
</table><h3 id="mapeo-avanzado">Mapeo Avanzado</h3>
<ul>
<li>Baterías de Rock Band mandan mas de un botón a la vez. Por ejemplo, el Parche Rojo manda "<code>B</code>" y "<code>Palanca izquierda presionada</code>" (que para el emulador es "<code>Circle</code>" y “<code>L3</code>”.) Toma en cuenta que esto se requiere para que funcionen los platillos correctamente.
<ul>
<li>Recomendamos que uses un mando de Xbox para mapear todo y después que cambies el XInput Device a tu batería de Rock Band para Xbox 360.</li>
</ul>
</li>
<li>Para mapear mas de una cosa por botón, sostén el Shift (Mayús) y haz click al botón a cual le quieras agregar mas de una cosa.</li>
</ul>
<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Batería</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross (Cruz)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/gp.png" alt="Parche Verde" title="Parche Verde"></td>
</tr>
<tr>
<td align="center">Circle (Circulo)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/rp.png" alt="Parche Rojo" title="Parche Rojo"></td>
</tr>
<tr>
<td align="center">Square (Cuadro)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/bp.png" alt="Parche Azul" title="Parche Azul"></td>
</tr>
<tr>
<td align="center">Triangle (Triangulo)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/yp.png" alt="Parche Amarillo" title="Parche Amarillo"></td>
</tr>
<tr>
<td align="center">R3</td>
<td align="center">Modificador de Platillos</td>
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
<td align="center">Boton R1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Segundo Pedal/Kick" title="Segundo Pedal/Kick"></td>
</tr>
<tr>
<td align="center">Cross (Cruz)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/a.png" alt="Botón A" title="Botón A"></td>
</tr>
<tr>
<td align="center">Circle (Circulo)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/b.png" alt="Botón B" title="Botón B"></td>
</tr>
<tr>
<td align="center">Square (Cuadro)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/x.png" alt="Botón X" title="Botón X"></td>
</tr>
<tr>
<td align="center">Triangle (Triangulo)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/y.png" alt="Botón Y" title="Botón Y"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/xbox/dp.png" alt="D-Pad (Cruceta)" title="D-Pad (Cruceta)"></td>
</tr>
<tr>
<td align="center">Botón PS</td>
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

[[Regresar a baterías]](https://rb3pc.milohax.org/ctrls_drums)

Mapeado por [[gonakil1ya]](https://linktr.ee/Gonakil1ya)