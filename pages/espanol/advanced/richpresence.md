---
title: Estado de la actividad para Discord
sidebar: espanol_sidebar
permalink: adv_discordrp_es
folder: espanol
tags: [avanzado, espanol]
summary: "Como compartir tu actividad en Rock Band 3 por Discord."
toc: false
---

¿Quieres mostrar a tus amigos cual canción estas tocando?  
Puedes hacer esto con un archivo Python hecho para Rock Band 3.  
![Una captura de Discord, mostrando que esta jugando Rock Band 3 Deluxe.](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/discordrpes.png "Actividad de Discord")

## Configuración Inicial:

Primero, vamos a desactivar la actividad reciente para Discord de RPCS3.

Abre RPCS3 y haz click el botón de `Config`.  
![Una captura de RPCS3 con el cursor sobre "Config".](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/rpcs3config.png "RPCS3")


En la pestaña de `GUI`, desactiva `Use Discord Rich Presence` (Mostrar actividad reciente en Discord).  
![Una captura de RPCS3 con la opción de "Use Discord Rich Presence" desactivada.](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/rpcs3drpoff.png "RPCS3: Settings")

Ahora, necesitas bajar la versión mas actual de [[Python 3]](https://www.python.org/downloads/){:target="_blank"}.

[[Haz click aquí para ir a la pagina de Python 3]](https://www.python.org/downloads/){:target="_blank"}.

Haz click en el botón amarillo de "Download Python [versión]".  
[![Una captura de la pagina de descarga para Python. El cursor esta sobre "Download Python 3.12.6".](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/pydl.png)](https://www.python.org/downloads/ "Python 3.12.6"){:target="_blank"}

Cuando termine, abre el instalador.  
En el instalador:  
1. Activa `Add python.exe to PATH` (Agregar python.exe a RUTA)
2. Haz click en `Install now` (Instalar ahora)  
![Una captura del instalador de Python. "Add python.exe to PATH" y "Install now" resaltados en cuadros bronceados con contornos sólidos.](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/pyinstall.png "Python 3.12.6")

Después de Python termine de instalarse, necesitas descargar el archivo `dx_discordrp.py`.

[[Haz click derecho aquí y selecciona "Guardar vínculo como" para descargar `dx_discordrp.py`]](https://raw.github.com/hmxmilohax/rock-band-3-deluxe/develop/scripts/dx_discordrp.py).

![Una captura de un usuario haciendo click derecho en "dx_discordrp.py" y luego teniendo el cursor sobre "Guardar vínculo como".](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/drpdles.png "Guardar vínculo como")

![Una captura de "dx_discordrp.py" en la bandeja de descargar.](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/rpcdles.png "dx_discordrp.py")

Mete el archivo en una carpeta donde puedas encontrarlo fácilmente. Vas a tener que abrir este archivo cada vez que quieras activar esta opción.

Ve a la carpeta donde pusiste el archivo y, en la barra de direcciones arriba del explorador de archivos, escribe `cmd` y luego presiona la tecla de Enter.  
![Una captura del explorador de archivos con "cmd" escrito en la barra de direcciones.](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/cmdopen.png "Windows Explorer")

Se va abrir el símbolo del sistema. Escribe este comando y presiona la tecla de Enter:  
`pip install requests pypresence pylast`  
![Una captura del símbolo del sistema ejecutando el comando de "pip install requests pypresence pylast".](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/cmdpip.png "cmd.exe")

Después de ese proceso, escribe: 
`py dx_discordrp.py`  
en el símbolo del sistema y presiona la tecla de Enter.

Te va a preguntar que quieres configurar.  
Presiona `1` y presiona la tecla de Enter.  
![Una captura del símbolo del sistema ejecutando "py dx_discordrp.py." El archivo pregunta cual sistema quiere elegir.](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/cmddrp.png "cmd.exe")

Después de eso, te va a preguntar por la carpeta de RPCS3.  
Arrastra la carpeta de RPCS3 al símbolo del sistema y presiona la tecla de Enter.  
**¡Si la dirección tiene comillas, bórralos!**  

Nuevamente, te preguntara si quieres configurar el IP de un Xbox.  
Presiona `2` y luego la tecla de Enter.  

Automáticamente va empezar a actualizar tu actividad en Discord hasta que cierres el símbolo del sistema..  
![Una GIF del símbolo del sistema ejecutando "py dx_discordrp.py." El archivo pregunta donde esta la carpeta de RPCS3.](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/cmdinit.gif "cmd.exe")

## Usando:

Después de la configuración inicial, no vas a tener abrir archivo.

So tienes que hacer click doble en el archivo `dx_discordrp.py`.  

![Una captura del explorador de archivos con el cursor sobre el archivo de "dx_discordrp.py."](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/pyopen.png "Explorador de archivos")

Si hiciste todo correcto, debe de decirte que se conecto a Discord (Connected to Discord RPC successfully) y va a actualizar tu actividad.  
![Una captura del símbolo del sistema ejecutando "py dx_discordrp.py."](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/pyrun.png "cmd.exe")

¡Eso es todo! Recuerda cerrar el símbolo del sistema cuando termines y abrirlo cuando quieras jugar.

Si el archivo no abre correctamente, verifica que tengas Python como la aplicación predeterminada para archivos `.py`.  
![Una captura mostrando cual aplicación predeterminada esta configurada para abrir archivos .py](https://carlmylo.github.io/docu-rpcs3/images/xtra/rpc/pydefaultes.png "Aplicación predeterminada para archivos .py")

Si estas en el [[Discord de Milohax]](https://discord.gg/milohax), puedes usar el comando de `!actividad` para ver información, como estadísticas de "Wrapped/Tu año en Rock Band" y como configurarla para Xbox 360.

{% include links.html %}