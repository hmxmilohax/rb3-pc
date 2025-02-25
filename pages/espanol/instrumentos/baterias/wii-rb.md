---
title: Batería de Rock Band para Nintendo Wii
sidebar: controllers_es_sidebar
permalink: ctrls_rbdrums_wii_es
folder: instrumentos
tags: [wii-es, baterias, espanol]
summary: "Como configurar tu batería de Rock Band para Nintendo Wii en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/wii.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/wiirbdrmscontroller.png" alt="Control" title="Control"></div>

## NOTAS

* Funciona **con o sin** platillos PRO.
	* Recuerda configurar cuales platillos tienes conectados dentro de Rock Band 3.
		* `Menu > Opciones > Opciones de Batería`
* La detección de velocidad (intensidad) no funciona.

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

## Información de Controls

| Handlers | Devices |
|:--------:|:-------:|
| MMJoystick | Joystick |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Drums | Rock Band Pro |

## Mapeo

* Baterías de Rock Band mandan mas de un botón a la vez. Toma en cuenta que esto se requiere para que funcionen los platillos correctamente.
* Para mapear mas de una cosa por botón, sostén el Shift (Mayús) y haz click al botón a cual le quieras agregar mas de una cosa.

| **RPCS3**    | **Batería de Rock Band** |
|:--------:|:-------------------:|
| Cross | ![Parche Verde](https://rb3pc.milohax.org/images/btns/drms/rb/gp.png "Parche Verde") |
| Circle | ![Parche Rojo](https://rb3pc.milohax.org/images/btns/drms/rb/rp.png "Parche Rojo") |
| Square | ![Parche Azul](https://rb3pc.milohax.org/images/btns/drms/rb/bp.png "Parche Azul") |
| Triangle | ![Parche Amarillo](https://rb3pc.milohax.org/images/btns/drms/rb/yp.png "Parche Amarillo") |
| R3 | Modificador de Platillos |
| D-Pad: Up | Modificador de Platillo Amarillo |
| D-Pad: Down | Modificador de Platillo Azul |
| L3 | Modificador de Parches |
| L1 | ![Pedal/Kick](https://rb3pc.milohax.org/images/btns/drms/rb/kp.png "Pedal/Kick") |
| R1 | ![Segundo Pedal/Kick](https://rb3pc.milohax.org/images/btns/drms/rb/kp.png "Segundo Pedal/Kick") |
| Cross | ![Botón A](https://rb3pc.milohax.org/images/btns/ctrls/wii/a.png "Botón A") |
| Circle | ![Botón B](https://rb3pc.milohax.org/images/btns/ctrls/wii/b.png "Botón B") |
| Square | ![Botón 1](https://rb3pc.milohax.org/images/btns/ctrls/wii/1.png "Botón 1") |
| Triangle | ![Botón 2](https://rb3pc.milohax.org/images/btns/ctrls/wii/2.png "Botón 2") |
| D-Pad | ![D-Pad (Cruceta)](https://rb3pc.milohax.org/images/btns/ctrls/wii/dpad.png "D-Pad (Cruceta)") |
| PS Button | ![Home](https://rb3pc.milohax.org/images/btns/drms/rb/home.png "Home") |
| Start | ![Botón + (Mas)](https://rb3pc.milohax.org/images/btns/ctrls/wii/plu.png "Botón + (Mas)") |
| Select | ![Botón - (Menos)](https://rb3pc.milohax.org/images/btns/ctrls/wii/min.png "Botón - (Menos)") |

## Perfil

[[Descargar Perfil]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Wii%20Rock%20Band%20Drums.7z)

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

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmswiirbmapping.png" alt="Mapeo" title="Mapeo"></div>

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Mapeado por [[scott0852]](https://twitter.com/scott0852){:target="_blank"}