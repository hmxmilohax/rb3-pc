---
title: "Les Paul por CRKD (Multi-platforma)"
sidebar: controllers_es_sidebar
permalink: ctrls_crkdgtr_lp_mp_es
folder: instrumentos
tags: [guitarras, pc-es, espanol]
summary: "Como configurar tu Les Paul por CRKD en RPCS3 (versión multiplat)."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/crkd.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/crkdlpcontroller.png" alt="Control" title="Control"></div>

## NOTAS

* Guitarras CRKD Les Pauls pueden ser conectadas por USB o su propio receptor receptor inalámbrico o Bluetooth. Para Bluetooth, necesitas un receptor de Bluetooth para tu computadora.
	* Receptor inalámbrico o cable de USB son los métodos recomendados.
* Para cambiar la configuración de tu guitarra, necesitas usar la aplicación de CRKD en tu teléfono (iOS/Android).
* Esta pagina sera actualizada cuando salgan actualizaciones de firmware y tengamos mas información.

<!-- Map Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#como-mapear-pads">¿Como configuro mi mando?</a>
                            </h4>
                        </div>
                        <div id="como-mapear-pads" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<p><strong>Haz click en el icono de Pads hacia arriba de RPCS3</strong>.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/rpcs3pad.png" alt="Una captura de RPCS3, mostrando el cursor sobre el icono de Pads." title="Pads"></p>
<p>Sigue las instrucciones y/o copia el mapeo de la lista para tu mando.</p>
<p><img src="https://rb3pc.milohax.org/images/instruments/gamepadlegend.png" alt="Una imagen mostrando como puedes usar una pagina de instrumentos para configurar a RPCS3." title="Mapeando un mando"></p>
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

### "PC Mode" (Modo de PC):
* Esta es la configuración recomendado y viene defecto con esta guitarra.

#### Configuración de la app de CRKD:

![Una captura de la aplicación de CRKD. La guitarra esta configurada para PC y esta puesta en Mode 1, cual es la configuración por defecto. Disable DPad esta desactivado.](https://rb3pc.milohax.org/images/instruments/xtra/crkdlp/default.jpg "CRKD CTRL")

#### Mapeo

Por defecto, XInput ya tiene mayoría de las cosas configuradas correctamente. Solo tienes que ajustar esto:

* ¡**BORRA ESTOS BOTONES** o tus solos de guitarra van a auto-rasguear (auto-strum)!  
Usa el click derecho para borrar botones.

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----------:|
| L2 | ![Gatillo Izquierdo](https://rb3pc.milohax.org/images/btns/ctrls/360/lt.png "Gatillo Izquierdo") | Botón de solos |

* ¡**Cambia esto** o los trastes amarillos y azules estarán invertidos!
	* Para la palanca de whammy, sosten ALT y haz click izquierdo en Right Stick: Left y luego en Right Stick: Right para mapear el rango negativo y positivo.

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----    ------:|
| Square | ![Botón Y](https://rb3pc.milohax.org/images/btns/ctrls/360/y.png "Botón Y") | ![Traste Amarillo](https://rb3pc.milohax.org/images/btns/gtrs/yf.png "Traste Amarillo") | 
| Triangle | ![Botón X](https://rb3pc.milohax.org/images/btns/ctrls/360/x.png "Botón X") | ![Traste Azul](https://rb3pc.milohax.org/images/btns/gtrs/bf.png "Traste Azul") |
| R1 | ![Back](https://rb3pc.milohax.org/images/btns/ctrls/360/back.png "Back") | ![Tilt](https://rb3pc.milohax.org/images/btns/gtrs/ts.gif "Tilt") |
| Right Stick: <br/> Left/Right | ![Gatillo Izquierdo](https://rb3pc.milohax.org/images/btns/ctrls/360/lt.png "Gatillo Izquierdo") | ![Palanca de whammy](https://rb3pc.milohax.org/images/btns/gtrs/wb.png "Palanca de whammy") |

## Perfil

[[Descargar Perfil]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/CRKD%20Les%20Paul%20Guitar.7z){:target="_blank"}

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

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrcrkdlpmapping.png" alt="Mapeo" title="Mapeo"></div>

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Investigado por [[gonakil1ya]](https://gonakillya.neocities.org){:target="_blank"}
