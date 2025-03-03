---
title: Guitarras de Guitar Hero para Nintendo Wii (WiitarThing)
sidebar: controllers_es_sidebar
permalink: ctrls_ghwtrgtr_wii_es
folder: instrumentos
tags: [wii-es, guitarras, espanol]
summary: "Como configurar guitarras de Guitar Hero con WiitarThing para Wii en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/wii.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/wiighgtrscontroller.png" alt="Control" title="Control"></div>

## NOTAS

* Necesitas instalar [[**WiitarThing**]](https://github.com/TheNathannator/WiitarThing){:target="_blank"} y sus dependencias.
* Esta configuración **requiere un receptor de Bluetooth para conectarse.** Si no computadora no tiene un adaptador de Bluetooth, no va a funcionar.
    * Es recomendado que conviertas tu guitarra para ser cableada con una solución como el [[adaptador V3 por RetroCultMods]](https://www.etsy.com//listing/1536358024){:target="_blank"}, un [[KIT REVIVAL de RetroCultMods]](https://www.etsy.com/listing/1830743563){:target="_blank"} [[Kit RGB DIY de RetroCultMods]](https://www.etsy.com/listing/1505287559){:target="_blank"}.
* **El sensor de ladeo (Tilt) no funciona correctamente.**
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://rb3pc.milohax.org/ctrls#gamepads_es){:target="_blank"}.

## Configuración Inicial

1. Después de instalar [[WiitarThing]](https://github.com/TheNathannator/WiitarThing/releases){:target="_blank"} con [[ViGEmBus]](https://github.com/nefarius/ViGEmBus/releases){:target="_blank"}, abre WiitarThing.

2. Presiona el botón de **`[SYNC]`** en la parte izquierda hacia arriba.  
![Una captura de WiitarThing con el cursor sobre el botón rojo de "SYNC".](https://rb3pc.milohax.org/images/instruments/xtra/wiitar/wiitarsyncbut.png "WiitarThing v2.7.0.5")

3. Presiona el botón rojo de `SYNC` atras de tu control de Wii<sup>a</sup> o presiona `1+2`<sup>b</sup> al mismo tiempo. Es posible que necesitaras intentar esto varias veces.  
<sup>a</sup>  
![Un control de Wii con los botones de 1 y 2 siendo resaltado.](https://rb3pc.milohax.org/images/instruments/xtra/wiitar/wiimotesync12.gif "Control de Wii")  
<sup>b</sup>  
![Un control de Wii con el botón de "SYNC" de atrás siendo resaltado.](https://rb3pc.milohax.org/images/instruments/xtra/wiitar/wiimotesyncbut.gif "Control de Wii")  

4. Cuando se sincronice, haz click en **`[CONNECT]`**.  
![Una captura de WiitarThing con el cursor sobre el botón rojo de "CONNECT".](https://rb3pc.milohax.org/images/instruments/xtra/wiitar/wiitarconnectbut.png "WiitarThing v2.7.0.5")

5. Abre el menú de `Pads` en RPCS3.

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
| Guitar | Guitar Hero |

## Mapeo

Instrumentos de Guitar Hero **son problemáticas para mapear. Si tratas de asignar un botón y todo sale con “U+”, haz click en “Filter Noise” (filtrar ruido)** en el lado izquierdo abajo de la ventana de configuración **y luego intenta mapear otra vez**.

Por defecto, XInput ya tiene mayoría de las cosas configuradas correctamente. Solo tienes que ajustar esto:

¡**BORRA ESTOS BOTONES** o tus solos de guitarra van a auto-rasguear (auto-strum)!  
Usa el click derecho para borrar botones.

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----------:|
| L2 | ![Gatillo Izquierdo](https://rb3pc.milohax.org/images/btns/ctrls/360/lt.png "Gatillo Izquierdo") | Botón de solos |

¡**Cambia esto** o los trastes amarillos y azules estarán invertidos!

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----------:|
| Square | ![Botón Y](https://rb3pc.milohax.org/images/btns/ctrls/360/y.png "Botón Y") | ![Traste Amarillo](https://rb3pc.milohax.org/images/btns/gtrs/yf.png "Traste Amarillo") | 
| Triangle | ![Botón X](https://rb3pc.milohax.org/images/btns/ctrls/360/x.png "Botón X") | ![Traste Azul](https://rb3pc.milohax.org/images/btns/gtrs/bf.png "Traste Azul") |


<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrwiiwtarmapping.png" alt="Mapeo" title="Mapeo"></div>

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mapeo-avanzado">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="mapeo-avanzado" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<h4 id="perfil">Perfil</h4>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Xbox%20360%20Guitar%20Hero%20Guitar.7z">[Descargar Perfil]</a></p>
<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>Esto no se recomienda si estas usando mas de un instrumento a la vez. </b> {{include.content}}</div>
<p>Después de descargar el perfil,</p>
<ol>
<li>Extrae el archivo .7z.</li>
<li>Arrastra la carpeta "<code>input configs</code>" a la carpeta "<code>configs</code>" en la carpeta donde tienes RPCS3.</li>
</ol>
<p><img src="https://rb3pc.milohax.org/images/instruments/instrepoinstall.gif" alt="Una animación de alguien arrastrando el perfil para las guitarras de Rock Band para Wii a su carpeta de RPCS3." title="Instalando un perfil del Repo de Instrumentos"></p>
<p>Después de eso, puedes seleccionar el perfil en el menú de "<code>Pads</code>".</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofile.png" alt="Una captura de Gamepad Settings dentro de RPCS3, con el cursor sobre un perfil." title="Gamepad Settings"></p>
<p>La mayoría del tiempo, estos perfiles jalan sin configuración adicional. Por si acaso no, trata de cambiar el control en "<code>Devices</code>", al lado del botón de "<code>Refresh</code>" hasta que funcione. Puedes cambiar esto mientras el juego esté abierto.</p>
<h4 id="configuracion">Configuración</h4>
<table>
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
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/gf.png" alt="Traste Verde" title="Traste Verde"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/rf.png" alt="Traste Rojo" title="Traste Rojo"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/yf.png" alt="Traste Amarillo" title="Traste Amarillo"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/bf.png" alt="Traste Azul" title="Traste Azul"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/of.png" alt="Traste Naranja" title="Traste Naranja"></td>
</tr>
<tr>
<td align="center">D-Pad: Up</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/sbu.png" alt="Rasgueo para arriba" title="Rasgueo para arriba"></td>
</tr>
<tr>
<td align="center">D-Pad: Down</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/sbd.png" alt="Rasgueo para abajo" title="Rasgueo para abajo"></td>
</tr>
<tr>
<td align="center">D-Pad: Left</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/dpl.png" alt="D-Pad (Cruceta): Izquierda" title="D-Pad (Cruceta): Izquierda"></td>
</tr>
<tr>
<td align="center">D-Pad: Right</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/dpr.png" alt="D-Pad (Cruceta): Derecha" title="D-Pad (Cruceta): Derecha"></td>
</tr>
<tr>
<td align="center">Right Stick: <br> Left/Right</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/wb.png" alt="Palanca de whammy" title="Palanca de whammy"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/ts.gif" alt="Ladeo" title="Ladeo Vertical"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/ts.gif" alt="Ladeo" title="Ladeo Horizontal"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/wii/plu.png" alt="Botón + (Mas)" title="Botón + (Mas)"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/wii/back.png" alt="min" title="Botón - (Menos)"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/wii/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Mapeado por [[gonakil1ya]](https://linktr.ee/Gonakil1ya){:target="_blank"}