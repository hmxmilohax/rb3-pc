---
title: "Batería de Rock Band 4 para PlayStation 4"
sidebar: controllers_es_sidebar
permalink: ctrls_rb4drums_ps4_es
folder: instrumentos
tags: [ps4-es, baterias, espanol]
summary: "Como configurar tu batería de Rock Band 4 para PS4 en RPCS3."
toc: false
---

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/plat/ps4.png" alt="Sistema" title="Sistema"></div>

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/cont/rb4drmscontroller.png" alt="Control" title="Control"></div>

## NOTAS
* Requiere que descargues y uses los archivos de [[Minatsuki]](https://github.com/TheNathannator/RB4InstrumentMapper/blob/main/README.es.md/){:target="_blank"} y [[Minatsuki-Pro-Drums-Plus]](https://github.com/stefman69/Minatsuki-Pro-Drums-Plus). Toma nota que esta pagina y sus instrucciones están en Ingles.
* Estas baterías requieren un receptor de Bluetooth.
    * La latencia puede ser un problema dependiendo de tu receptor de Bluetooth. Puede ser difícil encontrar una calibración buena.
* Funciona **con o sin** platillos PRO.
    * Recuerda configurar cuales platillos tienes conectados dentro de Rock Band 3.
        * `Menu > Opciones > Opciones de Batería`
* La detección de velocidad (intensidad) no funciona.
* Menús de RPCN (para aceptar y mandar invitaciones para jugar en linea) pueden dejar el juego atorado. Recomendamos que tengas otra manera de controlar estos menús, como [[un teclado de PC o un mando estándar]](https://rb3pc.milohax.org/ctrls#gamepads_es){:target="_blank"}.

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

Si no quieres usar Python, los platillos no funcionaran y tendrás una experiencia peor.

## Información de Control

| Handlers | Devices |
|:--------:|:-------:|
| XInput | XInput Pad |

| Device Class | Device Subtype |
|:------------:|:--------------:|
| Drums | Rock Band Pro |

### Configuración Inicial
Primero, vamos a descargar la versión mas actual de [[Python 3]](https://www.python.org/downloads/){:target="_blank"}.

[[Haz click aquí para ir a la pagina de Python 3]](https://www.python.org/downloads/){:target="_blank"}.

Haz click en el botón amarillo de "Download Python [versión]".  
[![Una captura de la pagina de descarga para Python. El cursor esta sobre "Download Python 3.12.6".](https://rb3pc.milohax.org/images/xtra/rpc/pydl.png)](https://www.python.org/downloads/ "Python 3.12.6"){:target="_blank"}

Cuando termine, abre el instalador.  
En el instalador:  
1. Activa `Add python.exe to PATH` (Agregar python.exe a RUTA)
2. Haz click en `Install now` (Instalar ahora)  
![Una captura del instalador de Python. "Add python.exe to PATH" y "Install now" resaltados en cuadros bronceados con contornos sólidos.](https://rb3pc.milohax.org/images/xtra/rpc/pyinstall.png "Python 3.12.6")

Ahora, ve al [[Github de Minatsuki]](https://github.com/yanagiragi/Minatsuki){:target="_blank"} y descarga el ZIP que contiene el código.

[![Una captura de la pagina de Minatsuki. El botón de "Code" fue presionado y el cursor esta sobre la opción de "Download ZIP".](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina1.png)](https://github.com/yanagiragi/Minatsuki/archive/refs/heads/main.zip "Github: Minatsuki"){:target="_blank"}

Extrae el archivo `.zip` a una carpeta.  
Cuando hagas eso, ve al [[Github de Minatsuki-Pro-Drums-Plus]](https://github.com/stefman69/Minatsuki-Pro-Drums-Plus){:target="_blank"} y descarga el ZIP que contiene el código.

[![Una captura de la pagina de Minatsuki-Pro-Drums-Plus' El botón de "Code" fue presionado y el cursor esta sobre la opción de "Download ZIP".](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina2.png)](https://github.com/stefman69/Minatsuki-Pro-Drums-Plus/archive/refs/heads/main.zip "Github: Minatsuki-Pro-Drums-Plus"){:target="_blank"}

Combina los archivos de Minatsuki-Pro-Drums-Plus con los archivos de Minatsuki.  
Después de eso, haz click arriba en la barra de direcciones del Explorador de archivos y escribe `cmd`. Presiona Enter.

![Una captura de una carpeta que tiene los archivos de Minatsuki y Minatsuki-Pro-Drums-Plus combinados. La barra de direcciones dice "cmd".](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina3.png "Explorador: Minatsuki")

En el intérprete de comandos, escribe `pip install -r requirements.txt` y presiona Enter.

![Una captura del intérprete de comandos de Windows. El comando de 'pip install -r requirements.txt' fue escrito y se descargaron los requisitos.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina4.png "cmd: pywinusb")

Después de que se instale eso, escribe `pip install vgamepad` y presiona Enter.

![Una captura del intérprete de comandos de Windows. El comando de 'pip install vgamepad' fue escrito y se descargo.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/mina5.png "cmd: vgamepad")

Puede ser que también necesitas instalar ViGEm Bus. Puedes descargar esto de [[aquí]](https://vigembusdriver.com/download/){:target="_blank"}.

### Uso
Sincroniza tu batería al receptor de Bluetooth de tu computadora.

![Una captura del menu de Windows para dispositivos de Bluetooth. Muestra una batería de Mad Catz para Rock Band 4.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/ps41.png "Bluetooth devices")

Haz doble click en el archivos de `main_xinput.py`.

![Una captura de una carpeta que tiene los archivos de Minatsuki y Minatsuki-Pro-Drums-Plus combinados. El cursor esta sobre el archivo de 'main_xinput.py' y esta elegido.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/ps42.png "main_xinput")

Cuando se abra el intérprete de comandos, escribe el numero de tu batería y presiona Enter. Aveces, la batería sale varias veces pero no hay problema. Solo elige una y presiona Enter.

![Una captura del intérprete de comandos de Windows con la script de 'main_xinput.py' abierta. Muestra la batería de Rock Band 4 y otros controles. Un numero de la batería esta escrito y Enter fue presionado.](https://rb3pc.milohax.org/images/instruments/xtra/rb4/ps43.png "main_xinput")

Minimiza este programa. Asegúrate que se quede abierto mientras estas jugando.

## Mapeo

Solo necesitas elegir la información de control correcta (Handler, Device y Device Class/Type).

<div align="center"> <img src="https://rb3pc.milohax.org/images/instruments/maps/drmsxomapping.png" alt="Mapeo" title="Mapeo"></div>


<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseOne">"No quiero usar Python"</a>
                            </h4>
                        </div>
                        <div id="collapseOne" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
                                <p>Si no quieres usar Python, los platillos no funcionaran y tendrás una experiencia peor.</p>
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
<td align="center">MMJoystick</td>
<td align="center">Joystick</td>
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
<td align="center">Drums</td>
<td align="center">Rock Band Pro</td>
</tr>
</tbody>
</table><h2 id="mapeo">Mapeo</h2>

<table>
<thead>
<tr>
<th align="center"><strong>RPCS3</strong></th>
<th align="center"><strong>Batería de Rock Band</strong></th>
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
<td align="center">L1</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/kp.png" alt="Pedal/Kick" title="Pedal/Kick"></td>
</tr>
<tr>
<td align="center">Cross</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/x.png" alt="Botón Cross (Cruz)" title="Botón Cross (Cruz)"></td>
</tr>
<tr>
<td align="center">Circle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/o.png" alt="Botón Circle (Circulo)" title="Botón Circle (Circulo)"></td>
</tr>
<tr>
<td align="center">Square</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/s.png" alt="Botón Square (Cuadro)" title="Botón Square (Cuadro)"></td>
</tr>
<tr>
<td align="center">Triangle</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/t.png" alt="Botón Triangle (Triangulo)" title="Botón Triangle (Triangulo)"></td>
</tr>
<tr>
<td align="center">D-Pad</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/dp.png" alt="D-Pad (Cruceta)" title="D-Pad (Cruceta)"></td>
</tr>
<tr>
<td align="center">Start</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/opt.png" alt="Botón de Options" title="Botón de Options"></td>
</tr>
<tr>
<td align="center">Select</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/ctrls/ps4/shr.png" alt="Botón de Share" title="Botón de Share"></td>
</tr>
<tr>
<td align="center">PS Button</td>
<td align="center"><img src="https://rb3pc.milohax.org/images/btns/drms/rb/home.png" alt="Home" title="Home"></td>
</tr>
</tbody>
</table><h2 id="perfil">Perfil</h2>
<p><a href="https://github.com/hmxmilohax/rb3-pc/raw/refs/heads/main/downloads/instrument-repo/PS4%20Rock%20Band%20Drums.7z">[Descargar Perfil]</a></p>
                            </div>
                        </div>
                    <!-- /.panel -->
</div>
</div>

[[Regresar a la lista de instrumentos]](https://rb3pc.milohax.org/ctrls_es#lista-de-instrumentos)

Mapeado por [[gonakil1ya]](https://gonakillya.neocities.org){:target="_blank"}
