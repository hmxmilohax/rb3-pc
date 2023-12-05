Versión Vídeo (no actualizada):  
[![Una mini-imagen de la versión vídeo de esta guía.](images/xtra/vidthumb.jpg)](https://www.youtube.com/watch?v=sramU-Xdhrs "How to play Rock Band 3 on PC (with RPCS3) - YouTube")

<br/>

>##### Advertencia:
<sub>_Esta guía **no** te va a dar links para descargar el juego ni el DLC. Ninguno de los servidores de Discord mencionados tampoco te los va a dar. Haz tu propia copia o busque ayuda en Google. **La piratería es ilegal y atrae a los abogados de Tim Sweeney!**._
<br/>

1. [_[Requisitos]_](#requisitos)
2. [_[Instalación]_](#instalación)
3. [_[Configuración]_](#configuración)
4. [_[Desactivar Actualizaciones]_](#desactivar-actualizaciones)
5. [_[Controladores (guitarras, baterías de RB o GH y controles)]_](#controladores)
6. [_[Cuenta de usuario]_](#cuenta-de-usuario)
7. [_[RPCN]_](#rpcn)
8. [_[Configuración Rápida]_](#configuración-rápida)
8. [_[Configuración Personalizada]_](#configuración-personalizada)
10. [_[CPU]_](#cpu)
11. [_[GPU]_](#gpu)
12. [_[Audio]_](#audio)
13. [_[I/O (guitarras Pro y teclados con cable USB/MIDI)]_](#io)
14. [_[Network]_](#network)
15. [_[Advanced]_](#advanced)
16. [_[Emulator]_](#emulator)
17. [_[Guitarras Mustang PRO y teclados inalámbricos de PS3 con receptores]_](#guitarras-mustang-pro-y-teclados-inalámbricos-de-ps3-con-receptores)
18. [_[Soluciones de problemas]_](#soluciones-de-problemas)
19. [_[Conclusión]_](#conclusión)

<br/>

# Requisitos:

Necesitarás:
* _Una copia de Rock Band 3 para PS3 en tu computadora. (Idealmente BLUS-30463)_
* _Un instrumento. Puedes usar:_
	*   _Cualquier guitarra de Rock Band y Guitar Hero (PS3, PS4, Wii, X360)_
	*   _Cualquier batería de Rock Band y Guitar Hero (PS3, PS4, Wii, X360)_
	*   _Cualquier instrumento con salida MIDI compatible con el adaptador MIDI Pro de Rock Band 3 (solo la versión de PS3)_<sup>a
	*   _Cualquier batería electrónica con salida MIDI con el adaptador MIDI Pro de Rock Band 3 (PS3, Wii, X360)_
	*   _Teclado inalámbrico Rock Band 3 (solo la versión de PS3 con receptor propio)_<sup>a b
	*   _Guitarra PRO de Rock Band 3 Fender Mustang \[**Inalámbrica**\] (solo la versión de PS3 con receptor propio)_<sup>a
	*   _Guitarra PRO de Rock Band 3 Fender Mustang \[**Con cable**\] (PS3, Wii, X360 con adaptador de MIDI a USB)_
	*   _Guitarra PRO Rock Band 3 Squier Stratocaster (PS3, Wii, X360 con adaptador de MIDI a USB)_
	*   _Cualquier teclado MIDI (**con 37 teclas a lo mínimo** conectado por USB o por adaptador MIDI a USB)_<sup>b c
	*   _Batería MIDI (conectado por USB o por adaptador MIDI a USB y los programas MidiDrumHero and VJoy)_<sup>d
	*   _Cualquier micrófono detectado por tu computadora (el juego se puede controlar con la mayoría de mandos o con el teclado cuando juegas como vocalista)_
*   _Una computadora_
	* Mínimo:
		* SO: Windows 10
		* Procesador: Intel Core i5-4460 (o equivalente con una puntuación de CPUMark de 4872 y AVX2)
		* Memoria: 8 GBs
		* Gráficos: GeForce GT 730 2GB (o equivalente)
 		* Almacenamiento: 11.2 GBs (5400 RPM HDD)
   		* Notas adicionales: La configuración más básica. Tendrás resolución de 720p sin efectos adicionales, latencia de audio de 130 ms, y frecuencia de actualización de 60 Hz, con posibles inestabilidades en el rendimiento.
	* Recomendado:
		* SO: Windows 10
		* Procesador: AMD Ryzen 5 2600 (o equivalente)
		* Memoria: 16 GBs
		* Gráficos: NVIDIA GeForce GTX 1650 (o equivalente)
 		* Notas: 145.66 GBs para **todo** el contenido oficial lanzado desde RB1 hasta RB3, incluyendo DLC, RBN y expansiones (en un SSD).
 		* Notas adicionales: Excelente rendimiento. 1080p con todos los efectos, audio de 100 ms (o menos), y 75 Hz (o mas).
	* Puedes verificar [[la página de requisitos de RPCS3 aquí]](https://rpcs3.net/quickstart), aunque estan exagerado para este juego.
 
*   _[[7zip]](https://7zip-es.updatestar.com/) (o WinRAR si odias tu vida)_

<sup>a</sup> <sub>Los instrumentos y receptores de Rock Band para el Wii se pueden convertir a PS3, pero eso es demasíado complejo para incluir en esta guía. Google es tu amigo.</sub>  
<sup>b</sup> <sub>Es posible conectar teclados con MIDI que tengan menos de 37 teclas, pero no es lo ideal, así que no está recomendado en esta guía.</sub>  
<sup>c</sup> <sub>Algunos teclados MIDI, especialmente los de Yamaha, pueden tener problemas por su implementación de MIDI. [[Estos teclados requieren la versión nueva de RPCS3]](https://rpcs3.net/download).</sub>   
<sup>d</sup> <sub>No tengo una batería, así que no hay instrucciones para configurarlas. Si tienes una y te gustaría ayudar, mándame un mensaje por el Discord de Milohax con capturas de la configuración.</sub>

<br/>

# Instalación:

Vamos a descargar una versión anterior de RPCS3 porque es mejor para Rock Band 3. Aunque esta guía es para Windows, también puse un link para Linux por si deseas probarlo en esos sistemas.<sup>c  
<sup>c</sup> <sub>Algunos teclados MIDI, especialmente los de Yamaha, pueden tener problemas por su implementación de MIDI. [[Estos teclados requieren la versión nueva de RPCS3]](https://rpcs3.net/download).</sub>  

| [![Logo de Microsoft Windows](images/inst/windows.png)](https://github.com/RPCS3/rpcs3-binaries-win/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_win64.7z "Versión para Windows") | [![Mascota Tux de Linux](images/inst/linux.png)](https://github.com/RPCS3/rpcs3-binaries-linux/releases/download/build-9b3a878c189e4e688b6025de0d0ff659116dcade/rpcs3-v0.0.28-15417-9b3a878c_linux64.AppImage "Versión para Linux") |
|---|---|

**Cuando se descargue, extrae el archivo .7zip.**  
![Una captura del menú contextual de Windows destacando "Extract files..." (Extraer archivos...) en la categoría de 7-Zip.](images/inst/extract.png "Extract Files (Extraer archivos)")

Recomiendo que extraigas los archivos en "C:\\Juegos\\RPCS3" o en una unidad interna separada para evitar problemas de permisos. También desactiva la opción que creará un subdirectorio, como en la imagen.

**Evita instalar Rock Band 3 en un disco externo**, por que mayoría no tienen suficiente poder para correr el juego.  
![Una captura de la ventana de extracción de 7-zip. Muestra "Extract to" (Extrae archivos...) como C:\Games\RPCS3 y el cuadro debajo de ella desmarcada.](images/inst/extractdir.png "Extract")

Cuando se extraiga, [**[descarga el software del sistema de PlayStation 3 de el sitio de Sony]**](https://www.playstation.com/support/hardware/ps3/system-software/). **Mira un poco abajo en la página** hasta que llegues a "**Actualizar mediante una computadora**", haz click en eso para expandirlo y luego haz click en "**Descargar actualización de PS3**".

_**Si estás utilizando un navegador Chromium como Chrome o Edge, ASEGÚRATE DE HACER click DERECHO Y "Guardar enlace como..." o tu descarga PUEDE FALLAR.**_

Como antes, la imagen de abajo va directa a la página de descarga.
[![Una captura de la página "Cómo actualizar el software del sistema de la consola PS3" de Sony con la subcategoría "Actualización por computadora" expandida.](images/inst/fwpage.png)](https://www.playstation.com/support/hardware/ps3/system-software/ "Cómo actualizar el software del sistema de la consola PS3")

Ahora, **abre RPCS3**. **Marca a "I have read the Quickstart guide"** (He leído la guía de inicio rápido) **, "Do not show again" (No volver a mostrar), y, por fin, haz clic en "Continue"** (Continuar).  
![Una captura de pantalla de RPCS3 dando la bienvenida al usuario.](images/inst/rpcs3init.png "Welcome to RPCS3 (Bienvenido a RPCS3)")

Como se mencionó antes, esta es una versión anterior de RPCS3, y te fastidiar sobre esto.
**Asegúrate hacer clic en "No" en esta advertencia.**
![Una captura alertando al usuario que RPCS3 tiene una actualización disponible.](images/inst/rpcs3updwrn.png "Update Available (Actualización disponible)")


Ahora, **abre RPCS3** y **arrastra el archivo PS3UPDAT.PUP que acabas de descargar del sitio de Sony a RPCS3** y luego haz click en "Yes" (Si).  
![[Una captura del instalador de software del sistema de RPCS3 preguntándole al usuario si quiere instalar la software del sistema llamado "PS3UPDAT.PUP".]](images/inst/fwinstall.png "RPCS3 Firmware Installer (Instalador de software del sistema de RPCS3)")

**Déjalo instalar.**  
![Una captura del instalador del software del sistema de RPCS3 después de una instalación exitosa del software del sistema y los módulos LLE.](images/inst/rpcs3fw.png "RPCS3 Firmware Installer (Instalador de software del sistema de RPCS3) en acción")

**Cuando termine, haz click en "OK"**  
![Una captura del instalador de firmware de RPCS3 después de una exitosa instalación del firmware de PS3 y los módulos LLE.](images/inst/rpcs3fwdone.png "Success (Completo)!")

Comenzará a compilar módulos. Va a tardar unos minutos. **Deja que haga su trabajo.**  
![Una captura de RPCS3 compilando módulos PPU con una barra de progreso en 1/8 de finalización.](images/inst/rpcs3fwcomp.png "Compiling PPU modules... (Compilando módulos de PPU...)")

Después, **ve a la carpeta donde tienes tu copia de Rock Band 3 y arrastra la carpeta a RPCS3**. Pon esta carpeta en un lugar donde no la vas a borrar por accidente, porque la necesitas. De nuevo, no puedo darte una link por las reglas de este sitio. [[Yo usé "PS3 Disc Dumper" porque es la manera más fácil.]](https://youtu.be/gwjRJLHEV7U)
![Un GIF de la carpeta de Rock Band 3 siendo arrastrada a RPCS3, lo que actualiza RPCS3 para mostrar Rock Band 3 en la lista de juegos.](images/inst/rpcs3rb3dnd.gif "Rock Band 3 [BLUS30463]")

Ahora que Rock Band 3 está en tu biblioteca en RPCS3, necesita ser actualizado. **Necesitas descargar el archivo PKG con la actualización**. La link de abajo va a bajar directamente del servidor de Sony. Es posible que recibas advertencias de seguridad porque el servidor de Sony no utiliza HTTPS.  
[**[¡CLICK AQUÍ PARA DESCARGAR EL PKG DE ACTUALIZACIÓN DE ROCK BAND 3!]**](http://b0.ww.np.dl.playstation.net/tppkg/np/BLUS30463/BLUS30463_T4/e52d21c696ed0fcf/UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg)

El nombre de archivo sera algo así:

[![Actualización PKG de Rock Band 3 en la bandeja de descarga de Edge.](images/inst/rb3pe.png)](http://b0.ww.np.dl.playstation.net/tppkg/np/BLUS30463/BLUS30463_T4/e52d21c696ed0fcf/UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg "UP8802-BLUS30463_00-ROCKBAND3PATCH05-A0105-V0100-PE.pkg")

Cuando se baje, **arrastra el archivo a RPCS3 y haz click en "Yes" (Si)**, como con el archivo PS3UPDAT.PUP.  
![Una captura de Decrypter/Installer de RPCS3 preguntando si el usuario desea instalar el archivo de paquete de actualización de Rock Band 3.](images/inst/rpcs3pkg.png "PKG Decrypter/ Installer (Descifrador/Instalador)")

<br/>


# Configuración:

*SI HAS CAMBIADO LA CONFIGURACION DE RPCS3, RESTAURA TODO A LO PREDETERMINADO ANTES DE SEGUIR ESTA GUIA.*

<br/>

## Desactivar Actualizaciones:

Dado que las versiones actuales de RPCS3 funcionan peor para Rock Band 3 y otros juegos musicales, **se sugiere quedarse en una versión más un poco vieja y desactivar actualizaciones**.
Para hacer esto, mira la barra de menú de RPCS3, luego **haz clic en Configuration > GUI** (Configuración > GUI).  
![Una captura de pantalla del menú de clic derecho de RPCS3, mostrando "GUI" en el menú de Configuración resaltado](images/conf/rpcs3gui.png "RPCS3 > Configuration > GUI")

**En el menú "Check for updates on startup"** (Buscar actualizaciones en inicio), **cámbialo a "No", luego haz clic en "Apply"** (Aplicar) **y luego en "Save"** (Guardar).  
![Una captura de pantalla del menú de clic derecho de RPCS3, mostrando "Crear configuración personalizada de controlador de juego" resaltado](images/conf/rpcs3disupd.png "RPCS3 > Configuración > GUI")


## Controladores:

**Esta sección es para controladores regulares (guitarras de cinco botones RB/GH, baterías RB/GH).**  
Las guitarras Pro y/o teclados piano se configuran más adelante.

**Haz click con el botón derecho en "Rock Band 3" y selecciona "Create Custom Gamepad Configuration"** (Crear configuración de controladores personalizada)

![Una captura del menú contextual de RPCS3, mostrando "Create Custom Gamepad Configuration" resaltado](images/conf/rpcs3pad.png "Create Custom Gamepad Configuration")

* Si planeas conectar varios instrumentos, _debes configurarlos en diferentes puertos (Port)_.
* Las guitarras y baterías estándar de PS3 _deberían_ funcionar directamente. Si no, sigue las instrucciones de asígnación que se detallan a continuación. 
* Si estás utilizando guitarras de PS3, PS4, o Wii, configura la opción "Handlers" (Manipuladores) en "MMJoystick (Controlador)". 
* Si estás utilizando guitarras de Xbox 360, configura la opción "Handlers" (Manipuladores) en "XInput".
* Si estás utilizando baterías de PS3, PS4, Wii, o Xbox 360, configura la opción "Handlers" (Manipuladores) en "MMJoystick (Controlador)".

Abajo esta una guía de como asígnar los botones en RPCS3.

**Si tu controlador no se detecta, haz click en "Refresh" (Actualizar). Si eso no soluciona el problema, reinicia RPCS3.**

Una vez que hayas terminado de configurar, **recuerda hacer click en "Save" (Guardar).**

  
**Guitarra**:  
**Asegúrate que "Device Class" (Clase de controlador) este en "Guitar".**

**Cambia el menú desplegable junto a él a "Rock Band" si estás usando una guitarra de Rock Band o déjalo en "Guitar Hero" si estás usando una guitarra de Guitar Hero**. 
 
**Algunas guitarras** (especialmente las de Guitar Hero) aveces tienen problemas y **no quieren asígnar botones. Si tratas de asígnar un botón y todo sale con "U+", haz click en "Filter Noise"** en la parte inferior izquierda de la ventana de configuración **y luego intenta asígnar nuevamente**.

| **RPCS3**          | **Guitarras Rock Band** | **Guitarras Guitar Hero** |
|:------------------:|:---------------------:|:-----------------------:|
| Cross (Cruz) | ![Botón Verde](images/btns/gtrs/gf.png "Botón Verde") | ![Botón Verde](images/btns/gtrs/gf.png "Botón Verde") |
| Circle (Circulo) | ![Botón Rojo](images/btns/gtrs/rf.png "Botón Rojo") | ![Botón Rojo](images/btns/gtrs/rf.png "Botón Rojo") |
| Square (Cuadro) | ![Botón Azul](images/btns/gtrs/bf.png "Botón Azul") | ![Botón Amarillo](images/btns/gtrs/yf.png "Botón Amarillo") |
| Triangle (Triangulo) | ![Botón Amarillo](images/btns/gtrs/yf.png "Botón Amarillo") | ![Botón Azul](images/btns/gtrs/bf.png "Botón Azul") |
| L1 | ![Botón Naranja](images/btns/gtrs/of.png "Botón Naranja") | ![Botón Naranja](images/btns/gtrs/of.png "Botón Naranja") |
| D-Pad: Up (Arriba) | ![Rasguear Arriba](images/btns/gtrs/sbu.png "Rasguear Arriba") | ![Rasguear Arriba](images/btns/gtrs/sbu.png "Rasguear Arriba") |
| D-Pad: Down (Abajo) | ![Rasguear Abajo](images/btns/gtrs/sbd.png "Rasguear Abajo") | ![Rasguear Abajo](images/btns/gtrs/sbd.png "Rasguear Abajo") |
| Right Stick: <br/> Left+Right (Izquierda+derecha) | ![Palanca de trémolo/Whammy](images/btns/gtrs/wb.png "Palanca de trémolo/Whammy") | ![Palanca de trémolo/Whammy](images/btns/gtrs/wb.png "Palanca de trémolo/Whammy") |
| Right Stick: <br/> Up/Down (Arriba/Abajo) <br/> (Para guitarras de PS3/PS4/Wii) | ![Switch de Efectos](images/btns/gtrs/fx.png "Switch de Efectos") | |
| L2 <br/> (Para guitarras de Xbox 360) | ![Switch de Efectos](images/btns/gtrs/fx.png "Switch de Efectos") | |
| R1 | ![Ladear](images/btns/gtrs/ts.png "Ladear") | No funciona |

**Batería**:

**Asegúrate que "Device Class" (Clase de controlador) este en "Drums" (Batería).**

**Cambia el menú desplegable junto a él a "Rock Band" si estás usando baterías de Rock Band, "Rock Band Pro" si estás utilizando baterías de Rock Band con expansiones Pro, o déjalo en "Guitar Hero" si estás usando baterías de Guitar Hero.**

Si estás utilizando un adaptor de MIDI PRO para 360 con un kit de batería, por favor consulta [**\[el discord de Milohax\]**](https://discord.gg/xrba4CjdNC) para obtener la configuración porque saben mas de esto.

| **RPCS3**    | **Batería Rock Band** | **Batería Rock Band Pro** | **Batería Guitar Hero** |
|:--------:|:---------------:|:-------------------:|:-----------------:|
| Cross (Cruz) | ![Parche Verde](images/btns/drms/rb/gp.png "Parche Verde") | ![Parche Verde](images/btns/drms/rb/gp.png "Parche Verde") | ![Parche Verde](images/btns/drms/gh/gp.png "Parche Verde") |
| Circle (Circulo) | ![Parche Rojo](images/btns/drms/rb/rp.png "Parche Rojo") | ![Parche Rojo](images/btns/drms/rb/rp.png "Parche Rojo") | ![Parche Rojo](images/btns/drms/gh/rp.png "Parche Rojo") |
| Square (Cuadro) | ![Parche Azul](images/btns/drms/rb/bp.png "Parche Azul") | ![Parche Azul](images/btns/drms/rb/bp.png "Parche Azul") | ![Parche Azul](images/btns/drms/gh/bp.png "Parche Azul") |
| Triangle (Triangulo) | ![Parche Amarillo](images/btns/drms/rb/yp.png "Parche Amarillo") | ![Parche Amarillo](images/btns/drms/rb/yp.png "Parche Amarillo") | ![Címbalo Amarillo](images/btns/drms/gh/yc.png "Címbalo Amarillo") |
| L1 | ![Pedal](images/btns/drms/rb/kp.png "Pedal") | ![Pedal](images/btns/drms/rb/kp.png "Pedal") | ![Pedal](images/btns/drms/gh/kp.png "Pedal") |
| D-Pad | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") | ![D-Pad](images/btns/ctrls/xbox/dp.png "D-Pad") |
| R1 |  | ![Segundo Pedal](images/btns/drms/rb/kp.png "Segundo Pedal") | ![Címbalo Naranja](images/btns/drms/gh/oc.png "Címbalo Naranja") |
| R3 |  | Modificador de Címbalos | |
| L3 |  | Modificador de Pads | |


**Vocales**:  
*Para vocales*, puedes *utilizar controladores regulares*. Si estás usando un control de PS4, cambia "Handlers" (Manipuladores) a "DS4". Si estás usando un control de Xbox One, cambia "Handlers" (Manipuladores) a XInput. No es necesario cambiar otra cosa. También puedes usar tu teclado. Usa esta guía como referencia.


| **PlayStation (DS4)** | **Xbox One (XInput)** | **Uso**                         | **Uso Alternativo**        |
|:---------------------:|:---------------------:|:-------------------------------:|:-------------------:|
| ![Palanca Izquierda](images/btns/ctrls/ps4/ls.png "Palanca Izquierda") | ![Palanca Izquierda](images/btns/ctrls/xbox/ls.png "Palanca Izquierda") | Navegación |
| ![D-Pad](images/btns/ctrls/ps4/dp.png "D-Pad") | ![Palanca Izquierda](images/btns/ctrls/xbox/dp.png "D-Pad") | Navegación |
| ![Botón Cruz](images/btns/ctrls/ps4/x.png "Botón Cruz") | ![Botón A](images/btns/ctrls/xbox/a.png "Botón A") | Seleccionar                          |
| ![Botón Círculo](images/btns/ctrls/ps4/o.png "Botón Círculo") | ![Botón B](images/btns/ctrls/xbox/b.png "Botón B") | Atrás                            | Volumen micro 3 (Canción) |
| ![Botón Cuadrado](images/btns/ctrls/ps4/s.png "Botón Cuadrado") | ![Botón X](images/btns/ctrls/xbox/x.png "Botón X") | Volumen micro 1 (Canción) |
| ![Botón Triángulo](images/btns/ctrls/ps4/t.png "Botón Triángulo") | ![Botón Y](images/btns/ctrls/xbox/y.png "Botón Y") | Ver Más Información (Biblioteca)        | Volumen micro 2 (Canción) |
| ![Botón Opciones](images/btns/ctrls/ps4/opt.png "Botón Opciones") | ![Botón Opciones](images/btns/ctrls/xbox/opt.png "Botón Opciones") | Opciones                         | Pausa (Canción)        |
| ![Botón Compartir](images/btns/ctrls/ps4/shr.png "Botón Compartir") | ![Botón Vista](images/btns/ctrls/xbox/viw.png "Botón Vista") | Filtros (Biblioteca)               | Éxtasís (Canción)    |
| ![Botón L1](images/btns/ctrls/ps4/l1.png "Botón L1") | ![Botón Bumper Izquierdo](images/btns/ctrls/xbox/lb.png "Botón Bumper Izquierdo") | Selección de Parte de Guía (Práctica) |
| ![Gatillo L2](images/btns/ctrls/ps4/l2.png "Gatillo L2") | ![Gatillo Izquierdo](images/btns/ctrls/xbox/lt.png "Gatillo Izquierdo") | Selección de Parte Vocal (Práctica) |
| ![Botón R1](images/btns/ctrls/ps4/r1.png "Botón R1") | ![Botón Bumper Derecho](images/btns/ctrls/xbox/rb.png "Botón Bumper Derecho") | Volumen de Pista Vocal (Canción)       |
| ![Gatillo R2](images/btns/ctrls/ps4/r2.png "Gatillo R2") | ![Gatillo Derecho](images/btns/ctrls/xbox/rt.png "Gatillo Derecho") | Corrección de Tono (Canción)         |


  

Abajo esta una guitarra _Höfner de The Beatles: Rock Band para el Wii_ configurada como un ejemplo. Mira como "Handlers" (Manipuladores) está configurado en "MMJoystick (Controlador)" y "Devices" (Controladores) esta en el número de Joystick (Controlador) correcto. Como la guitarra es de Rock Band, "Device Class" (Clase de controlador) en Guitar" y la casílla junto a eso se configura en "Rock Band".
![Una captura de Gamepad Settings de RPCS3 con un controlador Höfner de Wii The Beatles: Rock Band](images/conf/rpcs3padexm.png "Gamepad Settings con un controlador de guitarra Höfner de Wii The Beatles: Rock Band")


<br/>

## Cuenta De Usuario:
En RPCS3, ve a **Manage > User Accounts** (Administrar > Cuentas de usuario)  
![RPCS3 mostrando "User Accounts" abajo del menú de "Manage".](images/conf/rpcs3user.png "RPCS3: User Accounts")

Una vez que estés ahí, dale click en el nombre de usuario predeterminado (00000001 - User) y luego click en **"Rename user"** (Renombrar usuario) y cámbialo al nombre que quieras y luego haz click en "Close" (Cerrar).  
!["User Manager" de RPCS3, mostrando usuario predeterminado.](images/conf/rpcs3rename.png "RPCS3: User Accounts")

<br/>

## RPCN:
Si no quieres jugar en linea, [[puedes avanzar a la siguiente sección.]](#configuración-rápida)

Ve a **Configuration > RPCN** (Configuración > RPCN)
![Una captura de la configuración de RPCS3 con "RPCN" resaltado](images/rpcn/rpcn.png "RPCS3: RPCN")

Haz click en "**Account**":  
![Una captura de la configuración de RPCS3 con "Account" resaltado](images/rpcn/rpcnpopup.png "RPCN")

Haz click en "**Create Account**" (Cuenta):  
![Una captura de la configuración de RPCS3 con "RPCN" resaltado](images/rpcn/account.png "RPCN: Account")

Pon un **Nombre de Usuario (Username)** y **Contraseña (Password)**:    
![Una captura del menú de nombre de usuario con un nombre de usuario configurado y "OK" resaltado](images/rpcn/user.png "RPCN: User")  
![Una captura del menú de contraseña con una contraseña oculta configurada (dos veces para verificación) y "OK" resaltado](images/rpcn/password.png "RPCN: Password")  

Se mostrara una ventana pidiendo un **Email** para así recibir un **codigo de verificación** (verification token):  
![Una captura del menú de Email con un Email (dos veces para verificación) configurado y "OK" resaltado](images/rpcn/email.png "RPCN: Email")  

**Click en "OK"** y ve a la bandeja de entrada de tu Email. Puede que tengas que esperar un par de minutos para que llegue el correo. Si todavia sigues esperando, checa la pestaña de **"Spam"**. El Email se llama **"Your token for RPCN"** (Tu código para RPCN). **Copia los números y letras abajo de "Your token for username [tu usuario] is:"** (Tu codigo para [tu usuario] es):

![Una captura del mensaje Email con la etiqueta "Your token for RPCN" (Tu codigo para RPCN) con un token debajo del nombre de usuario para el que es.](images/rpcn/emailtoken.png "Your token for RPCN (Tu codigo para RPCN)")

**Pega el token** a RPCS3 Y presiona "OK":  
![A screenshot RPCS3 telling the user an account was successfully created.](images/rpcn/created.png "RPCN: Username")

<br/>

# Configuración Rápida:
Estos archivos son para personas que quieren jugar sin hacer tanta configuración. Como quiera recomiendo que hagas una [[configuración personalizada]](#configuración-personalizada) para ajustar todo a lo mejor que pueda tu computadora.  
**DEBES de tener** [[**Rock Band 3 Deluxe instalado**]](https://github.com/hmxmilohax/rock-band-3-deluxe#-installing-on-rpcs3) no funciona a su máximo potencial.

Para usar estos archivos, **haz click en las configuraciones que deseas descargar y luego extrae los archivos en la carpeta donde esta RPCS3**. Las carpetas se combinaran si hiciste bien.
Los jugadores que deseen utilizar [[micrófonos]](https://github.com/carlmylo/rb3-pc/tree/español-win#audio), [[guitarras Pro con cable, teclados USB/MIDI]](https://github.com/carlmylo/rb3-pc/#io), o [[guitarras PS3 Mustang o teclados RB3 con receptores]](https://github.com/carlmylo/rb3-pc/#wireless-ps3-mustang-pro-guitar-and-ps3-rock-band-3-keyboard-with-receptor) todavía requieren configuración adicional.

* [[Configuración recomendada]](https://github.com/carlmylo/rb3-pc/raw/español-win/config/customconfig/recommended.zip) - Esta configuración es para computadoras que son igual (o mejor) que [los requisitos recomendados](#requisitos).
* [[Configuración mínima]](https://github.com/carlmylo/rb3-pc/raw/español-win/config/customconfig/minimum.zip) - Esta configuración es para computadoras que son igual (o mejor) que [los requisitos mínimos](#requisitos).

Para obtener más información sobre estas configuraciones, [[consulta la pagina de configuraciones rápidas]](https://github.com/carlmylo/rb3-pc/tree/español-win/config/customconfig#about).

<br/>


# Configuración Personalizada:
**Haz click derecho en Rock Band 3** en RPCS3, luego presiona "**Create Custom Configuration**" (Crear configuración personalizada)  
![Una captura del menú de clic derecho de RPCS3, mostrando "Create Custom Configuration" resaltado](images/cust/rpcs3customconfig.png "Create Custom Configuration")

Esto puede parecer abrumador debido a la gran cantidad de opciones, pero he codificado por colores las cosas que requerirán ciertos ajustes. Todo lo que no esté coloreado debe estar en las opciones predeterminadas.

| COLOR | SIGNIFICADO |
|---|---|
| ![Un cuadro amarillo.](images/cust/bigyellow.png "Cuadro amarillo") | *REQUERIDO* |
| ![Un cuadro verde.](images/cust/biggreen.png "Cuadro verde") | Para PC's gama baja |
| ![Un cuadro rosa.](images/cust/bigpink.png "Cuadro rosa") | Dependiente de tu PC |
| ![Un cuadro azul verde.](images/cust/bigteal.png "Cuadro azul verde") | Opcional |

Iremos pestaña por pestaña, así que comencemos con:

<br/>

## CPU


![Una captura de la configuración personalizada de CPU para Rock Band 3, mostrando SPU XFloat Accuracy, SPU Block Size y Preferred SPU Threads resaltados en verde.](images/cust/cpu.png "CPU")
* ![Un cuadro verde.](images/cust/smallgreen.png "Cuadro Verde") **Para PC's Gama Baja** (4 Nucleos/4 Chips de Hilos): 
	* **Cambia el "SPU Block Size"** (Tamaño de bloques del SPU) **a "Mega"** - Para juntar hilos de SPU a ser más pequeños , requiriendo menos núcleos/hilos.
	* **Cambia el "Preferred SPU Threads"** (Hilos preferidos del SPU) **a "1", "2", "3", or "4"** - Puede ayudar a prevenir inestabilidades causadas por sobrecargas de la CPU. Empieza con 4 y bájalo si no mejora.
	* **COMO ULTIMA ALTERNATIVA** **Cambia el "SPU XFloat Accuracy"** (Precisión de Flotante x del SPU) **a "Relaxed"** (Relajada) - Cambiar eso hará que tengas un par de fotogramas pero, **romperá el modo de practica!**

<br/>

## GPU
![Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando "Write Color Settings" en amarillo, "ZCULL Accuracy" en verde, "Resolution Scale", "Resolution Scale Threshold", "Frame Limit" y "Shader Quality" en rosa, y "VSync" en azul verde.](images/cust/gpu.png "GPU")
* ![Un cuadro amarillo.](images/cust/smallyellow.png "Cuadro Amarillo") REQUERIDO: 
	* **Activa "Write Color Buffers"** (Ingresar búferes de colores) - Arregla el 99% de los problemas con los personajes teniendo texturas con problemas.
* ![Un cuadro verde.](images/cust/smallgreen.png "Cuadro Verde") Para GPU's gama baja: 
	* Cambia "ZCULL Accuracy (Precisión de ZCull)" a "Relaxed" (Relajada) - Mejora el rendimiento ligeramente pero puede causar anomalías gráficas.
* ![Un cuadro rosa.](images/cust/smallpink.png "Cuadro Rosa") Dependiendo de tu GPU: 
	* Cambia "Frame Limit (Limite de fotogramas)" a "Off" para tener fotogramas ilimitadas (puede introducir agitación en el rendimiento del juego), en 60 si quieres fotogramas bloqueadas en 60 FPS (redundante con Vblank de 60 Hz). **Es sugerido utilizar la configuración de tu tarjeta de gráficas para limitar la fotogramas o utilizar un programa como MSI Afterburner.**
	* Ajusta "Shader Quality" (Calidad de Shaders) dependiendo de tu sistema. "Low" (Bajo) y "Medium" (Medio) reducirá la calidad drásticamente, "Auto" usará la configuración sugerida por RPCS3, y "High" (Alto) es la mejor opción. "Ultra" se ve similar a Alta.
	* Ajusta "Resolution Scale" (Nivel de resolución) a tu gusto. Bájalo para obtener mas rendimiento a costa de una drástica pérdida de calidad. Auméntala para obtener gráficos más nítidos.
	* Ajusta el "Resolution Scale Threshold" (Límite de nivel de resolución) dependiendo de la "Resolution Scale" de arriba. Usa el número de porcentaje con el que aumentaste tu resolución (por ejemplo, para 1920x1080, que es un 150%, calcularías cuál es el 150% de 16, lo que sería 24).
* ![Un cuadro azul verde.](images/cust/smallteal.png "Cuadro Azul Verde") OPCIONAL: 
	* Activa "VSync (Sincronización vertical)" - Reduce el efecto de rasgado de pantalla y da fotogramas mas estables. Incrementa la latencia ligeramente.


<br/>

## Audio
![Una captura de la configuración personalizada de audio de Rock Band 3, que muestra "Habilitar almacenamiento en búfer" resaltado en amarillo, "Salida de audio" resaltado en verde, "Búfer de audio" resaltado en rosa, y Configuración de micrófono, Tipo de micrófono (Estándar), Mic1, Mic2, Mic3 y Mic4 resaltados en verde azulado.](images/cust/audio.png "Audio")
* ![Un cuadro amarillo.](images/cust/smallyellow.png "Cuadro Amarillo") REQUERIDO: 
	* **Activa "Enable Buffering"** (Activar Búfer) - Absolutamente requerido para Rock Band 3. Debería estar activado por defecto, pero si no, actívalo de vuelta.
* ![Un cuadro rosa.](images/cust/smallpink.png "Cuadro Rosa") Ajuste dependiendo de tu PC: 
	* Ajusta el "Audio Buffer Duration" (duración de búferes de audio) dependiendo de tu sistema. 
		* **Valores bajos significan menos latencia pero mas CPU** requerido para mantener audio estable.
		* **Valores altos significan mas latencia pero audio mas estable debido a menos forzamiento de la CPU**.
		* Los que juegan vocales son los más afectados por esto porque latencia alta crea un eco. Los jugadores de instrumentos pueden usar la calibración para compensar.
		* Esto se puede cambiar mientras el juego esta abierto pero **requiere recalibración** en los ajustes del sistema de Rock Band 3.
* ![Un cuadro azul verde.](images/cust/smallteal.png "Cuadro Azul Verde") Para Vocalistas: 
	* Selecciona tu micrófonos en "Mic1", "Mic2" y "Mic3" para las voces. Si no estas jugando vocales, se usaran para el chat de voz.

<br/>

## I/O
**Esta sección es para teclados USB/MIDI o guitarras Pro con cable.**
* **Si no estás jugando con una guitarra Pro con cable o un teclado USB/MIDI,** [[puedes avanzar a la siguiente sección.]](#network)  
* **Si estás jugando con un Teclado Rock Band 3 para PS3 o una Guitarra Pro Mustang para PS3 inalámbrica,** [[puedes avanzar a la siguiente sección.]](#network)  

**Si tu teclado tiene salida USB**, solo necesitas **conectarlo a tu computadora**.  
![Una imagen atrás de un controlador MIDI, mostrando un puerto USB y un pedal de sostenido.](images/midi/usbkeys.png "Teclado USB")  


**Si tu teclado solo tiene una salida MIDI, necesitarás un convertidor de MIDI a USB**.
![Una imagen atrás de un controlador MIDI, mostrando una salida y entrada MIDI de 5 pines y múltiples entradas de pedal.](images/midi/midikeys.png "Teclado MIDI")  

**Lo mismo se aplica a las guitarras Pro**, porque solo tienen salidas MIDI.
![Una imagen de una guitarra Pro Fender Mustang Rock Band 3, mostrando una salida MIDI de 5 pines.](images/midi/midiprotar.png "Guitarra Pro Mustang MIDI")  

Aquí tienes un ejemplo de un convertidor de MIDI a USB. La mayoría vendrán con una luz para mostrar actividad. **Para probar que lo has conectado correctamente, deberías ver que "MIDI In" parpadea cuando presionas una tecla**.  
![Una imagen de una interfaz MIDI a USB.](images/midi/miditousb.png "Interfaz MIDI a USB")  


**Si tienes una interfaz de audio, es posible que ya tengas una forma de conectar MIDI** a tu computadora, ya que algunas interfaces de audio tienen entradas MIDI. Por ejemplo, esta Scarlett tiene conexiones MIDI atrás.  
>![Una imagen atrás de una Scarlett de Focusrite, mostrando un puerto USB y entradas y salidas MIDI de 5 pines.](images/midi/midifs.png "Focusrite Scarlett MIDI in/out")  


**Si todo está conectado**, **mira la pestaña I/O de RPCS3**.  
![Una captura de la configuración personalizada de I/O de Rock Band 3, mostrando ""Emulated MIDI Devices", "tipo de dispositivo" y selección de dispositivo resaltados en azul claro.](images/cust/io.png "I/O")
* ![Un cuadrado azul claro.](images/cust/smallteal.png "Cuadrado Azul Claro"): 
	* 🎹 **Jugadores de teclado: Deja tu "Emulated MIDI type" (Tipo de MIDI emulado) en "Keyboard" (teclado) y selecciona tu teclado o interfaz MIDI en el menú desplegable junto a él**.
	* 🎸 **Jugadores de Guitarra Pro: Cambia tu "Emulated MIDI type" (Tipo de MIDI emulado) de "Keyboard" (teclado) a "Guitar (17 Frets)"** (guitarra (17 trastes)) **si tienes una guitarra Pro Mustang, o "Guitar (22 Frets)"** (guitarra (22 trastes)) **si tienes una guitarra Pro Squier, luego selecciona tu interfaz MIDI a USB en el menú desplegable junto a él**.
  
 **Si RPCS3 no detecta tu instrumento, haz click en "Save custom configuration"** (Grabar configuración personalizada), **cierra la ventana de "Create Custom Configuration"** (Crear configuración personalizada) **y luego haz click con el botón derecho en Rock Band 3 para volver a abrirla. Si eso no funciona, reinicia RPCS3.**  
  
**Teclados no tienen botones de PS3, así que el primer octavo esta emulando botones de PS3**. Utiliza la siguiente imagen como referencia. **Te recomiendo poner etiquetas o algo así en tu teclado para recordarte qué hace cada tecla junto con rangos de colores**.
![Una imagen de un teclado de 37 teclas, mostrando el segundo octavo mapeado a los botones de PlayStation, C3 a E3 bajo un color rojo, F3 a B3 bajo un color amarillo, C4 a E4 bajo un color azul, F4 a B4 bajo un color verde y C5 bajo un color naranja.](images/midi/keysctrl.png "Referencia del Teclado MIDI")  

<br/>


## Network
![Una captura de la configuración personalizada de Red de Rock Band 3, mostrando el estado de la red (Conectado) resaltado en amarillo, los interruptores de IP/Hosts (rb3ps3live.hmxservices.com=45.33.48.123), el estado de PSN (RPCN) y "Enable UPNP" (no marcado) resaltado en azul claro.](images/cust/network.png "Network")
* ![Un cuadro amarillo.](images/cust/smallyellow.png "Cuadro Amarillo") REQUERIDO: 
	* **Cambia Network Status** (estado de red) **a "Connected"** (conectado) **como se remarca en la imagen. Si la dejas en "Disconnected" (desconectado), el juego se congelara mientras navegas por la biblioteca de canciones.**
* ![Un cuadro azul verde.](images/cust/smallteal.png "Cuadro Azul Verde") Para el Multijugador: 
	* Activa **"Enable UPNP"** (activar UPnP) o **reenvía el puerto 9103 (UDP) en tu cortafuegos. No actives UPNP mientras reenvías el puerto** ya que esto puede causar crasheos.
	* **Unete al \[[Servidor de RBEnhanced](https://discord.gg/6rRUWXPYwb)\] y ve al canal [\[#gocentral-connecting\]](https://discord.com/channels/953085263008129064/1076031372185042984)**. **Sigue las Instrucciones para RPCS3**. Aunque la imagen de arriba incluye detalles, esto puede cambiar a cualquier minuto. Siempre **referirte al \[[Servidor de Discord de RBEnhanced](https://discord.gg/6rRUWXPYwb)\] para** esta **información**. Mientras estas ahí puedes organizar sesiones con otros jugadores.

<br/>


## Advanced
![Una captura de la configuración personalizada avanzada de Rock Band 3, que muestra "Modo de pantalla completa exclusiva (Automático (Predeterminado)) y Retardo de activación del controlador (1µ) en verde.](images/cust/advanced.png "Advanced")
* ![Un cuadro verde.](images/cust/smallgreen.png "Cuadro Verde"): 
	* **Cambia el "Exclusive Fullscreen Mode"** (Modo de exclusividad de pantalla llena) **a "Prefer borderless fullscreen"** (preferir pantalla llena sin bordos) para prevenir posibles crasheos o desincronización al cambiar la prioridad del programa.
	* **Cambia el "Driver Wake-up Delay"** (Retraso de activacion de controlador) **a "20µ" si experimentas algunos congelamientos luego de algunas canciones. Incrementalo a "40µ" si sigue pasando.** 
* ![Un cuadro azul verde.](images/cust/smallteal.png "Cuadro Azul Verde"): 
	* **Ajusta el "VBlank Frequency"** (intervalo vertical) **si quieres unos fotogramas internos altos. Esto puede hacer que atinar las notas sea mas facil, pero puede causar inestabilidad gráfica o problemas de conexión en linea. Es mejor dejarlo tal como esta.**
* ![Un cuadro rosa.](images/cust/smallpink.png "Cuadro Rosa") Ajuste dependiendo de tu PC: 
	* **Activa "Debug Console Mode"** (Modo de consola de depuración) **con Rock Band 3 Deluxe instalado, para aumentar acceso a mas memoria. Esto ayudar a tener sesiones mas largas y mejor estabilidad.**

<br/>

## Emulator
![Una captura de la configuración personalizada del emulador de Rock Band 3, que muestra "Mostrar ventanas emergentes de trofeos", "Mostrar sugerencia de compilación de PPU", "Mostrar sugerencia de compilación de sombreadores", "Iniciar juegos en modo pantalla completa", "Usar interfaz de usuario nativa".](images/cust/emulator.png "Emulator")
Puedes dejar esto como quieras, pero yo consideraria cambiar las siguientes opciones:
* ![Un cuadro azul verde.](images/cust/smallteal.png "Cuadro Azul Verde") Cambios Opcionales: 
	* **"Show trophy popups"** - Simula la notificacion de trofeos de la PS3. Personamente desactivo esto ya que el juego tiene sus propias notificaciones.
	* **"Show PPU compilation hint"** - Esto crea una notificacion cuando RPCS3 esta compilando unidades del PPU. Esto solo sale si tienes la opción "Recompiler (LLVM)" activada en la pestaña de CPU.
	* "Show shader compilation hint" - Esto crea una notificación cuando RPCS3 esta compilando shaders. Ya sea si lo dejas activado o no ya es cosa tuya, pero debo decirte que esto es importante. Cuando ejecutas juegos de PS3, tiene que compilar shaders para "trasladar" los gráficos de una PS3 a un formato que tu PC pueda usar. **El juego seguirá trabándose mientras esto pase** . **Esto Pasa en TODOS los PC's.** Cuando termine de compilar un efecto, **esto usualmente ya no vuelve a pasar otra vez**. **La mejor forma de lidiar con esto es** simplemente **jugar al juego normalmente** y luego se ira rápidamente. Tambien puedes activar el modo de "Autoplay" y dejar que el juego toque unas canciones hasta que pare de trabarse tanto.
	* "Start games in Fullscreen mode" - Obviamente solo cambia el modo de pantalla completa cuando inicias Rock Band 3. Personalmente yo activo esto.
	* "Use Native Interface" - Desactivar esto hara que se remuevan todas las notificaciones de RPCS3 mientras estás  jugando, incluyendo el teclado. En su lugar, verás una interfaz más antigua.



Y con eso termina la parte difícil.

<br/>

# Guitarras Mustang PRO y Teclados inalámbricos de PS3 con Receptores

Si no estás utilizando una Guitarra Mustang Pro de PS3 y un Teclado Rock Band 3 de PS3 con sus receptores respectivos, [[puedes avanzar a la siguiente sección.]](#guitarras-mustang-pro-y-teclados-inalámbricos-de-ps3-con-receptores)

Para comenzar, **cierra RPCS3** y conecta el receptor del instrumento a tu computadora.

Ahora, [**\[ve al sitio de Zadig\]**](https://zadig.akeo.ie/) y **descárgalo**. Cuando termine de bajar, **ábrelo**.
[![Una captura de la pagina de Zadig](images/pass/zadigdl.png)](https://zadig.akeo.ie/ "Bajar a Zadig")


Haz click en **Options** (Opciones) y luego en **List All Devices** (Listar dispositivos).  
![Una captura de Zadig mostrando "Listar todos los dispositivos" resaltado bajo "Opciones".](images/pass/zadiglistall.png "Zadig: Opciones: Listar todos los dispositivos")

Deberías ver una lista de dispositivos ahora. **Selecciona tu Instrumento Pro de Rock Band 3**. En este ejemplo, estamos utilizando la Guitarra Mustang Pro, que aparece como "Harmonix RB3 Mustang Guitar for PlayStation® 3".  
![Una captura de Zadig mostrando "Harmonix RB3 Mustang Guitar for PlayStation® 3" resaltado en la lista de dispositivos.](images/pass/zadigsel.png "Zadig: Harmonix RB3 Mustang Guitar for PlayStation® 3")

Después de seleccionar el dispositivo correcto, deberías ver la opción para reemplazar el controlador. **ASEGÚRATE DE QUE SOLO ESTÁS REEMPLAZANDO EL CONTROLADOR DEL INSTRUMENTO PRO DE ROCK BAND 3**. **Haz click en "Replace Driver" (Reemplazar controlador)**.  
![Una captura de Zadig con "Reemplazar controlador" resaltado.](images/pass/zadigreplace.png "Zadig: Reemplazar controlador")

Aparecerá una advertencia. **Nuevamente, asegúrate de haber seleccionado tu Guitarra Mustang Pro o teclado de Rock Band 3.** Después de haberlo verificado, haz click en "**Yes**" (Sí).  
![Una captura de Zadig advirtiendo al usuario que está a punto de modificar un controlador del sistema, con "Sí" resaltado](images/pass/zadigreplace.png "Zadig: Advertencia - Controlador del sistema")

Luego, se instalará el controlador. Como dice el programa, esto puede llevar algunos minutos.  
![Una captura de Zadig en medio de una instalación de controladores.](images/pass/zadigprogress.png "Zadig: Instalando controlador...")

Si todo sale bien, verás este mensaje:  
![Una captura de Zadig que indica al usuario que el controlador se instaló correctamente, con "Cerrar" resaltado.](images/pass/zadigdone.png "Zadig: Éxito")

**Cierra Zadig** y, con el receptor todavía conectado, **abre RPCS3** y **abre Rock Band 3**.

Enciende tu controlador y deberías ver que automáticamente se le asigna un número de jugador.
![Una imagen de una Guitarra Mustang Pro con el LED del segundo jugador encendido.](images/pass/protaron.png "Guitarra Mustang Pro de Fender: Jugador 2")

Del mismo modo, en Rock Band 3, verás el instrumento listo para unirse.  
![Una captura de Rock Band 3 con una Guitarra Pro lista para unirse.](images/pass/rb3player.png "Rock Band 3: Guitarra Pro lista para unirse")

<br/>

## Soluciones De Problemas


*   **_Audio Entrecortado_**

	* [![A video thumbnail that reads "click here for audio example."](images/xtra/badaudio.png)](https://www.youtube.com/watch?v=UoCMEQbNThs&t=20s "Rock Band 3 Deluxe - Low-End Low-Buffer Autoplay - YouTube")
	* Aumenta el "Audio Buffer Duration" como se menciona en [[la pestaña de Audio de la configuración personalizada]](#Audio) hasta que el Audio Entrecortado se detenga. 100 ms es un buen comienzo para computadoras de baja gama.

*   **_Problemas Generales de Rendimiento_**
	* Cambia el plan de energía de tu computadora a "Máximo rendimiento"
	*   Regresa y Lee las sugerencias para PCs de gama baja en la [[sección de configuración personalizada]](#cpu).
	*   Instala [[Rock Band 3 Deluxe](https://github.com/hmxmilohax/rock-band-3-deluxe/tree/main#playstation-3) y deshabilita efectos adicionales en el apartado "Deluxe Settings"

*   **_El juego no se llena en toda la pantalla_**
	*   Activa la opción "Tamaño" en las opciones de RB3.

*   **_El juego tiene retraso de Audio o Notas_**
	*   Entra a calibración en el menú de opciones de RB3 si no lo has hecho. Deshabilita la opción "Dolby Digital" en el mismo menú.

*   **_El juego crashea cuando practico en guitarra/bajo regular_**
	*   Este es un error conocido que todavía no tiene solución.
	
*   **_No puedo usar la Calibración Automática_**
	*   La calibración automática solo funciona con las guitarras de PS3 en directo.

*   **_El juego se traba al ponerle nombre a un personaje_**
	*   Esto es un problema conocido de RPCS3. Puedes solucionarlo cambiando moviendo el switch de efectos en una Guitarra de RB. Es sugerido usar un control regular para crear personajes y nombrar cosas. De lo contrario, cambiando tu controlador de entrada en "[[crear configuración de controladores personalizada]](#controladores)" a "Keyboard" (teclado) y luego regresarlo a donde lo tenias originalmente lo arregla. Esto se puede hacer mientras el juego se esta ejecutando.

*   **_Los instrumentos o accesorios de los personajes flotan o los traspasan_**
	*   Actualmente no hay ninguna solución para esto. Si te pasa esto esto, [[por favor reporta tus descubrimientos en el GitHub de RPCS3.]](https://github.com/RPCS3/rpcs3/issues/8408)

*   **_Al navegar por la biblioteca hay pausas largas_**
	*   En ese caso, olvidaste poner el "Network Status" a "Connected" en la [[pestaña "Network" al hacer la configuración personalizada]](#network) para Rock Band 3.

*   **_Instrumentos de PS3 se detectan como dos_**
	*   Creaste una [[configuración de controladores personalizada]](#controladores) para un control de PS3, que usualmente no se necesita. Desborra la configuración del controlado y todo debe de estar bien.

- **_[Rock Band 3 Deluxe] Crasheo en el video de introducción_**
  * Tienes archivos de una version vieja. Ve a la carpeta del juego en `dev_hdd0\game\BLUS30463\USRDIR` y desborra todos los archivos con extensión `.dta`, excepto a `dx_high_memory.dta`.

	
*   **_[Bateria Pro] Golpear dos platillos se registra como un tambor_**
	*   Este es un problema conocido de Rock Band 3. Lastimosamente no se la solución ya que no juego la batería. Por favor siéntete pregunta en el servidor de Discord de MiloHax.

*   **_\[ONLINE\] No puedo encontrar al tercer o cuarto jugador_**
	*   En la Configuracion Personalizada de Rock Band 3, [[ve a la pestaña de "Network" de de configuración personalizada]](#network) y asegurate de tener activado la opción "Enable UPNP". Si por alguna razón no puedes activar el UPNP, tendrás que redireccionar el puerto 9103 (UDP) en tu cortafuegos . **No actives el UPNP mientras estas redireccionando el puerto** ya que esto puede causar crasheos.

*   **_\[ONLINE\] Crasheo cuando busco jugadores**
  - Si tienes UPNP prendido en la Configuración Personalizada de Rock Band 3 [[sección de Network]](#network), deberás desactivarlo y [[buscar cómo configurar el reenvío de puertos en tu enrutador]]([https://www.noip.com/support/knowledgebase/general-port-forwarding-guide](https://es.wikihow.com/configurar-el-reenv%C3%ADo-de-puertos-en-un-router)).
	
*   **_\[ONLINE\] Al tratar de conectar a GoCentral el juego se queda en "Registering Account_**
	*   Puede que hayas perdido la conexión a RPCN o GoCentral y tendrás que reiniciar el Juego. Si continuas teniendo esto luego de haber reiniciado, ve al menú de arriba en RPCS3 a, "Configuration" > "RPCN" > "Account" > "Test Account" luego reinicia el juego para forzar una reconexión.

*   **_\[ONLINE\] Me sigo descontando mientras juego en linea_**
	*   Chequea que no estés bajando algo y que tu conexión al internet no este sobrecargada. Si cambiaste tu VBlank a mas de 60 Hz, bájalo de vuelta a 60 Hz. Además, necesitas tener una conexión estable tanto con RPCN y los servidores de GoCentral.

*   **_"Seguí todos los pasos y todavía tengo crasheos/mal rendimiento"_**
	*   Revisa nuevamente para asegurarte de que has seguido cada paso correctamente. Esta guía ha sido probada y ha demostrado funcionar para muchas personas con diferentes tipos de hardware. Si estás absolutamente seguro de haber seguido cada paso correctamente, es muy probable que el archivo del juego que tienes esté dañado en un 90%, que haya un 9% de posibilidades de que tu computadora se haya quedado sin espacio en disco, y un 1% que la chingaste.

<br/>

# Conclusión

Eso es todo! Ahora (Con un poco de suerte) tienes un manera funcional para jugar Rock Band 3 en Tu computadora. Mientras estas acá, porque no te unes a algunas comunidades que están ayudando a mantener viva la Comunidad de Rock Band?

<div align="center">

**Rock Band 3 Deluxe/Milohax:** 

[![Rock Band 3 Deluxe Logo](images/xtra/rb3dx.gif)](https://github.com/hmxmilohax/rock-band-3-deluxe#readme "Rock Band 3 Deluxe")

</div>

Desarroladores del imprescindible Mod Rock Band 3 Deluxe que no puedo recomendar lo suficiente. [\[Descarga Aqui.\]](https://github.com/hmxmilohax/rock-band-3-deluxe#readme) Además de agregar muchas características de calidad de vida como arranques más rápidos, escenarios a 60 fps y carga automática de contenido descargable, **también incluye RB3_Plus, que agrega Pro Keys adicionales y Pro Guitar/Bass a canciones que no las tenían.** **¡Si tienes un instrumento Pro, esto es imprescindible!** Además de esto, hay varias opciones de personalización visual, como el uso de Apariencias de Rock Bands más antiguos (y más nuevos) e incluso de Guitar Hero. [Puedes \[Unirte al servidor de MiloHax\]](https://discord.gg/xrba4CjdNC).


<div align="center">

**RBEnhanced:**

[![RBEnhanced Logo](images/xtra/rbe.png)](https://rb3e.rbenhanced.rocks/ "RBEnhanced")

</div>

Desarrolladores del Increible mod RBEnhanced el cual solamente existe para Xbox 360 y Wii. Los mismos desarrolladores también ayudan y mantienen el servidor de GoCentral el cual es la única manera de jugar Rock Band 3 en linea en Xbox,PS3 y Wii por el Momento. Puedes [**\[unirte al servidor de RBEnhanced Aqui\]**](https://discord.gg/6rRUWXPYwb).

Agradecimientos especiales a:

*	[SlothDemon](https://www.youtube.com/@SlothDemon1991) por ayudar a traducir esta guía y ayudarme a recordar como escribir Español.
*   [DarkRTA](https://www.youtube.com/@darkrta), [Linos](https://www.youtube.com/@LinosMelendi), [Jnack](https://www.youtube.com/@jnackmclain), [Hughtobasíc](https://www.youtube.com/@thisisRK), [ihatecompvir](https://www.youtube.com/@ihatecompvir1591), and [LysiX](https://www.youtube.com/@LysiX) por informacion tecnica sobre RPCS3 y Rock Band 3.
*   qfoxb, [SlothDemon](https://www.youtube.com/@SlothDemon1991), [Jnack](https://www.youtube.com/@jnackmclain) (el cual hizo pruebas por 40 horas xd), knvtva, y 1osks por reportar resultados.
*   RPCS3 Wiki por tener una cantidad decente de información sobre los Controladores y los Traspasos Via USB.
*   [TheNathannator](https://github.com/TheNathannator) por su [GitHub de PlasticBand](https://github.com/TheNathannator/PlasticBand) por mejor documentación de controladores.


<div align="center">

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

</div>
