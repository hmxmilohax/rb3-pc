---
title: Adaptador de Guitarra V3 por RetroCultMods
sidebar: controllers_es_sidebar
permalink: ctrls_mod_rcmv3_es
folder: instrumentos
tags: [modeado, guitarras, espanol]
summary: "Como configurar tu guitarra conectada con un adaptador de Guitarra V3 por RetroCultMods en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/rcm.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rcmgtrswii.png" alt="Control" title="Control"></div>

## NOTAS:

* **¡Esta pagina es específicamente para el** [**[Adaptador de guitarra V3 por RetroCultMods]**](https://www.etsy.com/listing/1536358024/)**!** Verifica que tu recibo de venta fue de [[el sitio propio de RetroCultMods]](https://shop.retrocultmods.com/) o [[su tienda de Etsy]](https://www.etsy.com/shop/RetroCultMods).
	* Puedes usar esta pagina con los adaptadores V1 y V2 Wii pero no tendrás ladeo (tilt).

## Información de Control:

| Handlers | Devices |
|:------------------:|:---------------------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------------:|:---------------------:|
| Guitar | Rock Band |

## Configuración:

Si todavía no has iniciado tu adaptador V3, inicia la herramienta de RetroCultMods para Programar.

En la pantalla de inicio, elije el Dispositivo. Va ser una `Raspberry Pi Pico`  
Después, elije "`Wii Adapter`" or "`USB Adapter`" en `Device Type` dependiendo de que cual puerto estes usando.  
Finalmente, elije el `Device Variant`. **¡`Default` esta bien!** Rock Band 3 en RPCS3 no necesita funciones de "Auth", "Slider" o de "Joystick."
Ya que elegiste las opciones correctas, haz click en `Erase and configure` y deja que termine el proceso.

![Una captura de la herramienta de RetroCultMods para Programar. "Dispositivo Seleccionado" esta en Raspberry Pi Pico, "Device Type" esta en "Wii Adapter" y "Device Variant" esta puesto en "RCM Wii Guitar Adapter - Default."](https://rb3pc.milohax.org/images/instruments/xtra/rcm/initv3es.png "RetroCultMods: Herramienta de Programación")

Después de que termine, o si ya tienes un control iniciado, haz click en `Configurar`.

![Una captura de la herramienta de RetroCultMods para Programar. "Dispositivo Seleccionado" esta en "RCM Wii Guitar Adapter - Default" y el cursor esta sobre "Configurar."](https://rb3pc.milohax.org/images/instruments/xtra/rcm/seldevv3es.png "RetroCultMods: Herramienta de Programación")

En Ajustes de Control, cambia la configuración a esto:
* Cambiar Botones de Cara: (Depende de tu guitarra)
* Modo de Control en Windows: XInput
* Usar 'Passthrough' por USB con RPCS3: Deshabilitado
* Mapear Select al D-Pad Izquierdo en Xbox One/Series: Deshabilitado
* Inclinación: Habilitado
* Mapear Joystick a Dpad: Habilitado

![Una captura de los Ajustes de Control, dentro de la herramienta de programación.](https://rb3pc.milohax.org/images/instruments/xtra/rcm/consetes.png "RetroCultMods: Herramienta de Programación")

Es sugerido que también calibres tu palanca de whammy. Esta mas para abajo en la herramienta de programación.

**!ASEGÚRATE DE HACER CLICK EN "`Guardar Ajustes`" ANTES DE CERRAR EL PROGRAMA O PERDERÁS TUS CAMBIOS!**

![Una captura de la herramienta de programación para RetroCultMods, con el cursor sobre Guardar Ajustes](https://rb3pc.milohax.org/images/instruments/xtra/rcm/savev3es.png "RetroCultMods: Herramienta de Programación")

## Mapeo:

Por defecto, XInput tiene mayoría de las cosas configuradas correctamente. Solo necesitas ajustar esto:

| **RPCS3** | **XInput** | **Guitarra** |
|:--------:|:-----------:|:-----------:|
| Boton R1 | ![Right Stick](https://rb3pc.milohax.org/images/btns/ctrls/360/rs.png "Right Stick") | ![Ladeo](https://rb3pc.milohax.org/images/btns/gtrs/ts.png "Ladeo") | 

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mapeo-avanzado">Mapeo avanzado</a>
                            </h4>
                        </div>
                        <div id="mapeo-avanzado" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">

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
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/gf.png" alt="Traste Verde" title="Traste Verde"></td>
</tr>
<tr>
<td align="center">Circle (Circulo)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/rf.png" alt="Traste Rojo" title="Traste Rojo"></td>
</tr>
<tr>
<td align="center">Square (Cuadro)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/yf.png" alt="Traste Amarillo" title="Traste Amarillo"></td>
</tr>
<tr>
<td align="center">Triangle (Triangulo)</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/bf.png" alt="Traste Azul" title="Traste Azul"></td>
</tr>
<tr>
<td align="center">L1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/of.png" alt="Traste Naranja" title="Traste Naranja"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Arriba</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/sbu.png" alt="Rasgueo para arriba" title="Rasgueo para arriba"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Abajo</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/sbd.png" alt="Rasgueo para abajo" title="Rasgueo para abajo"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Izquierda</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/dpl.png" alt="D-Pad (Cruceta): Izquierda" title="D-Pad (Cruceta): Izquierda"></td>
</tr>
<tr>
<td align="center">D-Pad (Cruceta): Derecha</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/dpr.png" alt="D-Pad (Cruceta): Derecha" title="D-Pad (Cruceta): Derecha"></td>
</tr>
<tr>
<td align="center">Palanca Derecha: <br> Izq./Der.</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/wb.png" alt="Palanca de whammy" title="Palanca de whammy"></td>
</tr>
<tr>
<td align="center">Palanca Derecha: <br> Arriba <em>o</em> abajo</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/fx.png" alt="Switch de efectos" title="Switch de efectos"></td>
</tr>
<tr>
<td align="center">L2</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/solo.png" alt="Botón de solos" title="Botón de solos"></td>
</tr>
<tr>
<td align="center">Botón R1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/gtrs/ts.png" alt="Ladeo" title="Ladeo"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/start.png" alt="Start" title="Start"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/back.png" alt="Back" title="Back"></td>
</tr>
<tr>
<td align="center">Botón PS</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/360/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

## Perfil:

[[Bajar Perfil]](https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/RCM%20V3%20Adapter%20Guitar.7z){:target="_blank"}

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/modrcmv3gtrmapping.png" alt="Mapeo" title="Mapeo"></div>

### Modo Passthrough

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>Por ahora, RPCS3 no tiene soporte de "hotplugging" (cambio en caliente). Esto significa que vas a tener que tener la guitarra conectada antes de abrir RPCS3. El modo Passthrough te deja conectar la guitarra sin tener que mapear nada pero, como RPCS3 no tiene soporte de "hotplugging" (PS3/Emulador), tendrás que iniciar el juego dos veces. Por esto, no es recomendable usar modo Passthrough. </b> {{include.content}}</div>

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Investigación por [[Lynxeption]](https://www.youtube.com/@Lynxeption)  
Gracias a [[@amphobius]](https://twitter.com/amphobius) por capturas adcionales.