---
title: "Gibson SG de Guitar Hero para PlayStation 2"
sidebar: controllers_es_sidebar
permalink: ctrls_ghsggtr_ps2_es
folder: instrumentos
tags: [ps2-es, guitarras, espanol]
summary: "Como configurar SGs de Guitar Hero para PS2 en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/ps2.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/ps2sgcontroller.png" alt="Control" title="Control"></div>

## NOTAS

* Verificamos esto solo con el adaptador "OSTENT PS1 PS2 To PC USB 2.0 Control Adapter Converter For Sony PS2 Wired Control" (Numero de modelo/SKU: 014800). Otros adaptadores pueden tener problemas.
* Es posible [[usar X360CE]](https://www.x360ce.com/){:target="_blank"} para forzar que adaptadores problemáticos funcionen.
* El sensor de ladeo (Tilt) no funciona correctamente.
    * Es recomendado que modifiques tu guitarra para ser cableada con una solución como el [[Kit RGB DIY SIN SOLDADURA para controladores Guitar Hero de RetroCultMods]](https://www.etsy.com/mx/listing/1505287559/kit-rgb-diy-sin-soldadura-para).
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://rb3pc.milohax.org/ctrls#gamepads_es){:target="_blank"}.

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
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Guitar | Guitar Hero |

## Mapeo

¡**BORRA ESTOS BOTONES** o tus solos de guitarra van a auto-rasguear (auto-strum)!  
Usa el click derecho para borrar botones.

| **RPCS3** | **Guitarra** |
|:--------:|:-----------:|
| L2 | Botón de solos |

**Mapea** esto:

* Es posible que necesites usar "Filter Noise" para mapear, depende a tu suerte. Aveces, al adaptador dice que estas sosteniendo la D-Pad (Cruceta).
* El sensor de ladeo (tilt) puede ser configurado pero es muy complicado. Vas a necesitar experimentar con el botón de "Filter Noise" (filtrar ruido) hasta que pesque el sensor de ladeo correctamente. Es recomendado no hacer esto y que actives sobrecarga con el botón.
	* Para mapear mas de una cosa por botón, sostén el Shift (Mayús) y haz click al botón a cual le quieras agregar mas de una cosa.

| **RPCS3** | **Guitarra** |
|:------------------:|:---------------------:|
| Cross | ![Traste Verde](https://rb3pc.milohax.org/images/btns/gtrs/gf.png "Traste Verde") |
| Circle | ![Traste Rojo](https://rb3pc.milohax.org/images/btns/gtrs/rf.png "Traste Rojo") |
| Square | ![Traste Amarillo](https://rb3pc.milohax.org/images/btns/gtrs/yf.png "Traste Amarillo") |
| Triangle | ![Traste Azul](https://rb3pc.milohax.org/images/btns/gtrs/bf.png "Traste Azul") |
| L1 | ![Traste Naranja](https://rb3pc.milohax.org/images/btns/gtrs/of.png "Traste Naranja") |
| D-Pad: Up | ![Rasgueo para arriba](https://rb3pc.milohax.org/images/btns/gtrs/sbu.png "Rasgueo para arriba") |
| D-Pad: Down | ![Rasgueo para abajo](https://rb3pc.milohax.org/images/btns/gtrs/sbd.png "Rasgueo para abajo") |
| Right Stick: Up | ![Rasgueo para arriba](https://rb3pc.milohax.org/images/btns/gtrs/sbu.png "Rasgueo para arriba") |
| Right Stick: Down | ![Rasgueo para abajo](https://rb3pc.milohax.org/images/btns/gtrs/sbd.png "Rasgueo para abajo") |
| Right Stick: <br/> Left/Right | ![Palanca de whammy](https://rb3pc.milohax.org/images/btns/gtrs/wb.png "Palanca de whammy") |
| Select (No es recomendado) | ![Ladeo](https://rb3pc.milohax.org/images/btns/gtrs/ts.gif "Ladeo Vertical") |
| Start | ![Start](https://rb3pc.milohax.org/images/btns/ctrls/ps3/sta.png "Start") |
| Select | ![Select](https://rb3pc.milohax.org/images/btns/ctrls/ps3/sel.png "Select") |

## Perfil

[[Descargar Perfil]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/PS2%20Guitar%20Hero%20SG%20Guitar.7z){:target="_blank"}

<!-- Profile Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#como-uso-perfiles">¿Como uso perfiles?</a>
                            </h4>
                        </div>
                        <div id="como-uso-perfiles" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>Esto no se recomienda si estas conectando mas de un instrumento a la vez. </b> {{include.content}}</div>
<p>Después de descargar el perfil,</p>
<ol>
<li>Extrae el archivo .7z.</li>
<li>Arrastra la carpeta <code>input configs</code> a la carpeta <code>configs</code> en la carpeta donde tienes RPCS3.</li>
</ol>
<p><img src="https://rb3pc.milohax.org/images/instruments/instrepoinstall.gif" alt="Una animación de alguien arrastrando el perfil para las guitarras de Rock Band para Wii a su carpeta de RPCS3." title="Instalando un perfil del Repo de Instrumentos"></p>
<p>Después de eso, puedes seleccionar el perfil en el menú de <code>Pads</code>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3padprofile.png" alt="Una captura de Gamepad Settings dentro de RPCS3, con el cursor sobre un perfil." title="Gamepad Settings"></p>
<p>La mayoría del tiempo, estos perfiles funcionan sin necesitar configuración adicional. Por si acaso no, cambia el control en <code>Devices</code>, al lado del botón de <code>Refresh</code> hasta que funcione. Puedes cambiar esto mientras el juego esté abierto.</p>
</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Profiles End -->

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrps2ghsgmapping.png" alt="Mapeo" title="Mapeo"></div>

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Mapeado por [noom]
