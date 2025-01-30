---
title: Guitarras de Guitar Hero para Nintendo Wii (WiitarThing)
sidebar: controllers_es_sidebar
permalink: ctrls_ghwtr_wii_es
folder: instrumentos
tags: [wii-es, guitarras, espanol]
summary: "Como configurar guitarras de Guitar Hero con WiitarThing para Wii en RPCS3."
toc: false
---

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/plat/wii.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/cont/rcmgtrswii.png" alt="Control" title="Control"></div>

## NOTAS:

* Si quieres usar este instrumento, necesitas instalar [[**WiitarThing**]](https://github.com/Meowmaritus/WiitarThing){:target="_blank"} y sus dependencias.
* Esta configuración **requiere un receptor de Bluetooth para conectarse.** Si no computadora no tiene un adaptador de Bluetooth, no va a funcionar.
    * Es recomendado que modifiques tu guitarra para ser cableada con una solución como el [[Kit RGB DIY SIN SOLDADURA para controladores Guitar Hero de RetroCultMods]](https://www.etsy.com/mx/listing/1505287559/kit-rgb-diy-sin-soldadura-para){:target="_blank"}.
* El sensor de ladeo (Tilt) no funciona correctamente.
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://carlmylo.github.io/docu-rpcs3/ctrls_pads_es){:target="_blank"}.

## Información de Control:

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Guitar Hero |

## Mapeo:

Por defecto, XInput ya tiene mayoría de las cosas configuradas correctamente. Solo tienes que ajustar esto:

¡**BORRA ESTOS BOTONES** o tus solos de guitarra van a auto-rasguear (auto-strum)!  
Usa el click derecho para borrar botones.

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----------:|
| L2 | ![Gatillo Izquierdo](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/lt.png "Gatillo Izquierdo") | Botón de solos |

¡**Cambia esto** o los trastes amarillos y azules estarán invertidos!

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----------:|
| Square (Cuadro) | ![Botón Y](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/y.png "Botón Y") | ![Traste Amarillo](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/yf.png "Traste Amarillo") | 
| Triangle (Triangulo) | ![Botón X](https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/360/x.png "Botón X") | ![Traste Azul](https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/bf.png "Traste Azul") |

Instrumentos de Guitar Hero **son problemáticas para mapear. Si tratas de asignar un botón y todo sale con “U+”, haz click en “Filter Noise” (filtrar ruido)** en el lado izquierdo abajo de la ventana de configuración **y luego intenta mapear otra vez**.

<div align="center"> <img src="https://carlmylo.github.io/docu-rpcs3/images/instruments/maps/gtrwiiwtarmapping.png" alt="Mapeo" title="Mapeo"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mapeo-avanzado">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="mapeo-avanzado" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<h4 id="profile">Perfil</h4>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Xbox%20360%20Guitar%20Hero%20Guitar.7z" target="_blank">[Bajar Perfil]</a></p>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Guitarra</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Cross (Cruz)</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/gf.png" alt="Traste Verde" title="Traste Verde"></td>
</tr>
<tr>
<td align="center">Circle (Circulo)</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/rf.png" alt="Traste Rojo" title="Traste Rojo"></td>
</tr>
<tr>
<td align="center">Square (Cuadro)</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/yf.png" alt="Traste Amarillo" title="Traste Amarillo"></td>
</tr>
<tr>
<td align="center">Triangle (Triangulo)</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/bf.png" alt="Traste Azul" title="Traste Azul"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/of.png" alt="Traste Naranja" title="Traste Naranja"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Arriba</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbu.png" alt="Rasgueo para arriba" title="Rasgueo para arriba"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Abajo</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/sbd.png" alt="Rasgueo para abajo" title="Rasgueo para abajo"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Izquierda</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpl.png" alt="D-Pad (Cruceta): Izquierda" title="D-Pad (Cruceta): Izquierda"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Derecha</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/dpr.png" alt="D-Pad (Cruceta): Derecha" title="D-Pad (Cruceta): Derecha"></td>
</tr>
<tr>
<td align="center">Palanca Derecha: <br> Izq./Der.</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/wb.png" alt="Palanca de whammy" title="Palanca de whammy"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png" alt="Ladeo" title="Ladeo Vertical"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/gtrs/ts.png" alt="Ladeo" title="Ladeo Horizontal"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/wii/plu.png" alt="Botón + (Mas)" title="Botón + (Mas)"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/wii/back.png" alt="min" title="Botón - (Menos)"></td>
</tr>
<tr>
<td align="center">Botón PS</td>
<td align="center"><img src="https://carlmylo.github.io/docu-rpcs3/images/btns/ctrls/wii/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Regresar a la lista de instrumentos]](https://carlmylo.github.io/docu-rpcs3/ctrls_es#lista-de-instrumentos)

Mapeado por [diogodiogo2]