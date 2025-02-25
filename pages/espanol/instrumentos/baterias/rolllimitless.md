---
title: Baterías con Roll Limitless
sidebar: controllers_es_sidebar
permalink: ctrls_mod_rldrums_es
folder: instrumentos
tags: [modeado, baterias, midi-es, espanol]
summary: "Como configurar tu batería con un Roll Limitless en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/midi.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rolllimitlesscontroller.png" alt="Control" title="Control"></div>

## NOTAS

* Este control requiere configuración avanzada.
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

#### Configuración adicional
1. Pon el adaptador Roll Limitless en modo de actualizar firmware. Necesitas presionar y sostener el botón rectangular que esta mas cercas al puerto de micro USB arriba del adaptador.  
![Una imagen del adaptador Roll Limitless, con el botón de firmware circulado en rojo.](https://rb3pc.milohax.org/images/instruments/xtra/rolllimitless/fwbutton.png "Botón de firmware Roll Limitless")
2. Sigue sosteniendo el botón mientras conectas el adaptador a tu computadora.
3. [[Descarga la firmware "Universal" actual desde el sitio oficial de Roll Limitless]](https://rolllimitless.com/firmwares/).
4. Coloca el archivo de firmware en el adaptador mientras esta en modo de actualizar (se mira como un disco extraíble.) Cuando termine de transferir, quita el adaptador de la computadora **seguramente**.
5. Conecta el adaptador de vuelta a la computadora pero, esta vez, presiona y sostén el botón de inicio redondo que esta mas cercas al puerto de USB A.  
![Una imagen del adaptador Roll Limitless, con el botón de inicio circulado en rojo.](https://rb3pc.milohax.org/images/instruments/xtra/rolllimitless/startbutton.png "Botón de inicio Roll Limitless")
6. Verifica que Windows detecto el adaptador Roll Limitless correctamente. La manera mas fácil es buscar "Mando" en el menú de Inicio y abrir este panel de control.  
![Una captura de Windows mostrando el panel de control para configurar dispositivos de juego USB.](https://rb3pc.milohax.org/images/instruments/xtra/gen/joycpl_es.png "Configurar dispositivos de juego USB")
7. Si no la detecto, asegúrate que presionaste y manteniste el Botón de inicio redondo en el adaptador sostenido y intenta otra vez.

## Mapeo

| **RPCS3** | **Batería** |
|:---------:|:---------------:|
| Cross | ![Parche Verde](https://rb3pc.milohax.org/images/btns/drms/rb/gp.png "Parche Verde") |
| Circle | ![Parche Rojo](https://rb3pc.milohax.org/images/btns/drms/rb/rp.png "Parche Rojo") |
| Square | ![Parche Azul](https://rb3pc.milohax.org/images/btns/drms/rb/bp.png "Parche Azul") |
| Triangle | ![Parche Amarillo](https://rb3pc.milohax.org/images/btns/drms/rb/yp.png "Parche Amarillo") |
| L1 | ![Pedal/Kick](https://rb3pc.milohax.org/images/btns/drms/rb/kp.png "Pedal/Kick") |
| D-Pad (Cruceta) | ![D-Pad (Cruceta)](https://rb3pc.milohax.org/images/btns/ctrls/xbox/dp.png "D-Pad (Cruceta)") |
| R1 | ![Segundo Pedal/Kick](https://rb3pc.milohax.org/images/btns/drms/rb/kp.png "Segundo Pedal/Kick") |
| R3 | Modificador de Platillos |
| L3 | Modificador de Parches |

## Perfil

[[Descargar Perfil]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/Roll%20Limitless%20Drums.7z)

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

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/modrldrmsmapping.png" alt="Mapeo" title="Mapeo"></div>

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Mapeado por Uzny