---
title: Instalación
author: Carl Mylo
date: 2000-03-01
category: Español
layout: post
---

Antes de empezar con la instalación, **asegúrate que tus controladores y sistema operativo estén actualizados.**

## Descargas

**Empezamos descargando 7-Zip**, que es lo que necesitas para abrir mayoría de los archivos que bajamos en esta guía. **Si ya tienes 7-Zip** o una alternativa instalada, **puedes seguir adelante**.

[**[Haz clic aquí para ir a la página de descarga de 7-Zip]**](https://7zip-es.updatestar.com/).

[![Una captura de la pagina para descargar 7-Zip, con el cursor sobre el instalador .exe de 64 bits.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/7zipes.png)](https://7zip-es.updatestar.com/ "7zip-es.updatestar.com")

**Ahora**, **vamos a instalar Microsoft Visual C++ 2019 Redistributable**, porque es necesario para RPCS3. Mayoría ya lo tienen, pero no está malo estar seguro.

[**[Haz clic aquí para descargar Microsoft Visual C++ 2019 Redistributable]**](https://aka.ms/vs/17/release/vc_redist.x64.exe).

**Cuando se descargue**, ábrelo y instálalo (Install). 

[![Una Captura del instalador del Microsoft Visual C++ 2019 Redistributable, con las condiciones y opción para instalar.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/mvcpp.png)](https://aka.ms/vs/17/release/vc_redist.x64.exe "Microsoft Visual C++ 2015-22 Redistributable (x64) 14.3833130")

Después, vamos descargar RPCS3.

[**[Haz clic aquí para ir al sitio de descarga de RPCS3]**](https://rpcs3.net/download).

Baja un poco y descarga la versión para Windows.

[![Una captura del sitio de descarga para RPCS3, con el cursor en la versión de Windows.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3dl.png)](https://rpcs3.net/download "RPCS3 - Download")

**Cuando se descargue, extrae el archivo .7zip.**  

![Una captura del menú contextual de Windows con el cursor en "Extraer ficheros...") en la categoría de 7-Zip.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/extractrpcs3es.png "Extraer ficheros...")

Recomiendo que extraigas todo a "C:\\Juegos\\RPCS3" o en un disco interno adicional para evitar problemas de permisos. También desactiva la opción para crear un subdirectorio, como en la imagen.

**Evita instalar y lanzar Rock Band 3 de un disco externo o una carpeta sincronizada (Dropbox, OneDrive, etc.)**, por que pueden causar inestabilidad y otros problemas.  

![Una captura de la ventana de extracción de 7-zip. Muestra "Extract to" (Extrae archivos...) como C:\Games\RPCS3 y el cuadro debajo de ella desmarcada.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/extractdires.png "Extract")

Cuando se extraiga, [**[descarga el software del sistema de PlayStation 3 de el sitio de Sony]**](https://www.playstation.com/support/hardware/ps3/system-software/). **Mira un poco abajo en la página** hasta que llegues a "**Actualizar por computadora**", haz click en eso para expandirlo y luego haz click en "**Descargar la actualización de la PS3**".

_**Si estás utilizando un navegador Chromium como Chrome o Edge, ASEGÚRATE DE HACER click DERECHO Y "Guardar enlace como..." o tu descarga PUEDE FALLAR.**_

Como antes, la imagen de abajo va directa a la página de descarga.
[![Una captura de la página "Cómo actualizar el software del sistema de la consola PS3" de Sony con la subcategoría "Actualización por computadora" expandida.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/fwpagees.png)](https://www.playstation.com/support/hardware/ps3/system-software/ "Cómo actualizar el software del sistema de la consola PS3")

## Iniciando

Ahora, **ve a la carpeta donde extrajiste a RPCS3 y ábrelo**. Deja a esta carpeta abierta en el fondo. **Marca a "I have read the Quickstart guide"** (He leído la guía de inicio rápido) **, "Do not show again" (No volver a mostrar) y, por fin, haz clic en "Continue"** (Continuar).  
![Una captura de pantalla de RPCS3 dando la bienvenida al usuario.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3init.png "Welcome to RPCS3 (Bienvenido a RPCS3)")


**Arrastra el archivo PS3UPDAT.PUP** que acabas de descargar del sitio de Sony **a RPCS3**.

![Una GIF de PS3UPDAT.PUP siendo instalado en RPCS3.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3fwdnd.gif "PST3UPDAT.PUP")

**Haz click en "Yes" (Si)** cuando el programa te pregunta si quieres instalar el archivo.  
![[Una captura del instalador de software del sistema de RPCS3 preguntándole al usuario si quiere instalar la software del sistema llamado "PS3UPDAT.PUP".]](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/fwinstall.png "RPCS3 Firmware Installer (Instalador de software del sistema de RPCS3)")

**Déjalo instalar.**  
![Una captura del instalador del software del sistema de RPCS3 después de una instalación exitosa del software del sistema y los módulos LLE.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3fw.png "RPCS3 Firmware Installer (Instalador de software del sistema de RPCS3) en acción")

**Cuando termine, haz click en "OK"**  
![Una captura del instalador de firmware de RPCS3 después de una exitosa instalación del firmware de PS3 y los módulos LLE.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3fwdone.png "Success (Completo)!")

Comenzará a compilar módulos para cargar la XMB de PS3 en el emulador. Esto puede tardar unos minutos. **Puedes dejar que haga su trabajo o puedes cerrarlo.**  
![Una captura de RPCS3 compilando módulos PPU con una barra de progreso en 1/8 de finalización.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3fwcomp.png "Compiling PPU modules... (Compilando módulos de PPU...)")

Después, **en una pantalla de archivos nueva, ve a la carpeta donde tienes tu copia de Rock Band 3 y muévela a un lado. Arrastra la carpeta de Rock Band 3 a la carpeta llamada "games" adentro de la carpeta de RPCS3**. De nuevo, no puedo darte una link por las reglas de este sitio. [[Yo usé "PS3 Disc Dumper" porque es la manera más fácil.]](https://youtu.be/gwjRJLHEV7U)  
![Un GIF de la carpeta de Rock Band 3 siendo arrastrada a RPCS3, lo que actualiza RPCS3 para mostrar Rock Band 3 en la lista de juegos.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3rb3dnd.gif "Rock Band 3 [BLUS30463]")

Después de mover la carpeta de Rock Band 3, haz clic en "Refresh" (actualizar) en RPCS3 para actualizar tu biblioteca en RPCS3. Rock Band 3 debe de aparecer en tu biblioteca de juegos.

![A GIF of "Refresh" being clicked in RPCS3, which updates it to display Rock Band 3 in the game list.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3refresh.gif "Rock Band 3 [BLUS30463]")

**Ahora, vamos a descargar a** [**[Rock Band 3 Deluxe]**](https://rb3dx.neocities.org/).

Rock Band 3 Deluxe es una modificación que arregla problemas critícales con Rock Band 3 en RPCS3. También incluye [**[muchas funciones para mejorar tu juego]**](https://rb3dx.neocities.org/features).


[**[Haz clic aqui para bajar Rock Band 3 Deluxe]**](https://nightly.link/hmxmilohax/rock-band-3-deluxe/workflows/build/main/RB3DX-PS3.zip).

[![Carpeta .zip de Rock Band 3 Deluxe en la bandeja de descarga de Edge.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rb3dxdles.png)](https://nightly.link/hmxmilohax/rock-band-3-deluxe/workflows/build/main/RB3DX-PS3.zip "RB3DX-PS3.zip")


Cuando se baje, **extrae el archivo**.

![Una captura del menú contextual de Windows con el cursor en "Extraer ficheros...") en la categoría de 7-Zip.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rb3dxextes.png "Extraer ficheros...")



**Cuando termine de extraer, arrastra el archivo PKG a RPCS3 y haz click en "Yes" (Si)**, como con el archivo PS3UPDAT.PUP.  

![Una GIF de el archivo PKG siendo arrastrato en RPCS3.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3rb3dxdnd.gif "Rock Band 3 Deluxe PKG")

![Una captura de Decrypter/Installer de RPCS3 preguntando si el usuario desea instalar el archivo de paquete de Rock Band 3 Deluxe.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3pkg.png "PKG Decrypter/ Installer (Descifrador/Instalador)")

Si se instala correctamente, el icono de Rock Band 3 va a cambiar.

![Una captura de la librería de RPCS3, enseñando el icono de Rock Band 3 usando un icono nuevo de Rock Band 3 Deluxe.](https://raw.githubusercontent.com/carlmylo/rb3-pc/TheGreatSplit/assets/images/inst/rpcs3rb3dxicon.png "RPCS3 Game List")

Puedes renombrar el juego a "Rock Band 3 Deluxe" si quieres. Solo necesitas hacer click derecho en "Rock Band 3" y selecciona a "Rename in Gamelist" (Renombrar en lista de juegos).