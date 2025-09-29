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
| Guitar | Rock Band |

### PC - Mode 8:
* Esta es la configuración recomendado y viene defecto con esta guitarra.

<div class="alert alert-info"><i class="fa fa-info-circle"></i> <b>¡Asegúrate que tu guitarra y el receptor de la guitarra estén actualizados!</b> {{include.content}}</div>

#### Configuración de la app de CRKD:

![Una captura de la aplicación de CRKD. La guitarra esta configurada para PC y esta puesta en Mode 8.](https://rb3pc.milohax.org/images/instruments/xtra/crkdlp/pcm81.jpg "CRKD CTRL")

![La segunda pagina de la aplicación de CRKD.](https://rb3pc.milohax.org/images/instruments/xtra/crkdlp/pcm82.jpg "CRKD CTRL")

#### Mapeo

Por defecto, XInput ya tiene mayoría de las cosas configuradas correctamente. Solo tienes que ajustar esto:

* ¡**Cambia esto** o los trastes amarillos y azules estarán invertidos!

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----    ------:|
| R1 | ![Palanca izquierda](https://rb3pc.milohax.org/images/btns/ctrls/360/rs.png "Palanca izquierda") | ![Ladeo](https://rb3pc.milohax.org/images/btns/gtrs/ts.gif "Ladeo") | 

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrcrkdlpmapping.png" alt="Mapeo" title="Mapeo"></div>

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

<!-- Mode 1 Start -->
<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mode-one">Mode 1</a>
                            </h4>
                        </div>
                        <div id="how-to-use-profiles" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul>
<h2 id="información-de-control">Información de Control</h2>

<table>
<thead>
<tr>
<th align="center">Handlers</th>
<th align="center">Devices</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">XInput</td>
<td align="center">XInput Pad</td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th align="center">Device Class</th>
<th align="center">Device Subtype</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">Guitar</td>
<td align="center">Guitar Hero</td>
</tr>
</tbody>
</table><h3 id="pc-mode-modo-de-pc">“PC Mode” (Modo de PC):</h3>
<ul>
<li>Esta es la configuración recomendado y viene defecto con esta guitarra.</li>
</ul>
<h4 id="configuración-de-la-app-de-crkd">Configuración de la app de CRKD:</h4>
<p><img src="https://rb3pc.milohax.org/images/instruments/xtra/crkdlp/default.jpg" alt="Una captura de la aplicación de CRKD. La guitarra esta configurada para PC y esta puesta en Mode 1, cual es la configuración por defecto. Disable DPad esta desactivado." title="CRKD CTRL"></p>
<h4 id="mapeo">Mapeo</h4>
<p>Por defecto, XInput ya tiene mayoría de las cosas configuradas correctamente. Solo tienes que ajustar esto:</p>
<ul>
<li>¡<strong>BORRA ESTOS BOTONES</strong> o tus solos de guitarra van a auto-rasguear (auto-strum)!<br>
Usa el click derecho para borrar botones.</li>
</ul>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>XInput</strong></th>
<th align="center"><strong>Guitarra</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">L2</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/lt.png" alt="Gatillo Izquierdo" title="Gatillo Izquierdo"></td>
<td align="center">Botón de solos</td>
</tr>
</tbody>
</table><ul>
<li>¡<strong>Cambia esto</strong> o los trastes amarillos y azules estarán invertidos!
<ul>
<li>Para la palanca de whammy, sosten ALT y haz click izquierdo en Right Stick: Left y luego en Right Stick: Right para mapear el rango negativo y positivo.</li>
</ul>
</li>
</ul>
<p>| <strong>RPCS3</strong> | <strong>XInput</strong> | <strong>Guitarra</strong> |<br>
|:--------:|:-----------:|:-----    ------:|<br>
| Square | <img src="https://rb3pc.milohax.org/images/btns/ctrls/360/y.png" alt="Botón Y" title="Botón Y"> | <img src="https://rb3pc.milohax.org/images/btns/gtrs/yf.png" alt="Traste Amarillo" title="Traste Amarillo"> |<br>
| Triangle | <img src="https://rb3pc.milohax.org/images/btns/ctrls/360/x.png" alt="Botón X" title="Botón X"> | <img src="https://rb3pc.milohax.org/images/btns/gtrs/bf.png" alt="Traste Azul" title="Traste Azul"> |<br>
| R1 | <img src="https://rb3pc.milohax.org/images/btns/ctrls/360/back.png" alt="Back" title="Back"> | <img src="https://rb3pc.milohax.org/images/btns/gtrs/ts.gif" alt="Tilt" title="Tilt"> |<br>
| Right Stick: <br> Left/Right | <img src="https://rb3pc.milohax.org/images/btns/ctrls/360/lt.png" alt="Gatillo Izquierdo" title="Gatillo Izquierdo"> | <img src="https://rb3pc.milohax.org/images/btns/gtrs/wb.png" alt="Palanca de whammy" title="Palanca de whammy"> |</p>
<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/gtrcrkdlp1mapping.png" alt="Mapeo" title="Mapeo"></div>
<h2 id="perfil">Perfil</h2>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/CRKD%20Les%20Paul%20M1%20Guitar.7z">[Descargar Perfil]</a></p>

</ul>
                            </div>
                        </div>
                    </div>
</div>
<!-- Mode 1 End -->

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Investigado por [[gonakil1ya]](https://gonakillya.neocities.org){:target="_blank"}
