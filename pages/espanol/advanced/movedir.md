---
title: Mover Archivos del Juego
sidebar: espanol_sidebar
permalink: adv_movedir_es
folder: espanol
tags: [avanzado, espanol]
summary: "Como mover los archivos de Rock Band 3 a otro lugar, fuera de donde esta el emulador."
toc: false
---

<div markdown="span" class="alert alert-danger" role="alert"><i class="fa fa-exclamation-circle"></i> <b>Esto es algo para usuarios avanzados. **¡Se puede romper to juego!** ¡Procede con precaución! </b> {{include.content}}</div>

Si los archivos de Rock Band 3 están tomando mucho espacio en tu disco primario, puedes moverlos a otro disco mientras el emulador se quede en tu disco primario.

Antes de empezar, cierra RPCS3.

Primero, crea una carpeta donde vas a mover esta carpeta.

En las capturas, yo nombre la carpeta "RPCS3 Directory" (Directorio de RPCS3).

![Una captura de la carpeta creada, que se llama "RPCS3 Directory."](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirfolder.png "RPCS3 Directory")

Ahora, en la carpeta donde esta RPCS3, corta estas carpetas:
* `dev_bdvd`
* `dev_flash`
* `dev_flash2`
* `dev_flash3`
* `dev_hdd0`
* `dev_hdd1`
* `dev_usb000`
* `games`

![Una captura de las carpetas siendo cortadas.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dircut.png "Cut (CTRL+X")

Pega las carpetas en la carpeta que creaste.

![Una animación de las carpetas que fueron cortadas siendo pegadas en la carpeta "RPCS3 Directory."](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirpaste.gif "RPCS3 Directory")

Cuando termine de mover los archivos, abre RPCS3.

Haz click en `Manage > Virtual File System` (Administrar > Sistema de archivos virtual)


![Una captura de RPCS3, con el cursor sobre "Virtual File System", en la categoría de "Manage."](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirrpcs3.png "RPCS3 Directory")

En la pantalla de Virtual File System, haz click en símbolo `+` hacia la parte inferior derecha.

![Una captura de Virtual File System, con el cursor sobre el símbolo +.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirvfsadd.png "Virtual File System")

Busca la carpeta que creaste, selecciónala, y haz click a "`Select Folder`" (Elegir Carpeta).

![Una captura con la carpeta creada siendo seleccionada.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirfoldersel.png "RPCS3 Directory")

Finalmente, haz click en "`Save`" (Guardar).

![Una captura de Virtual File System, con la carpeta creada en la lista de EmulatorDir.](https://carlmylo.github.io/rb3-pc/images/xtra/dir/dirvfssave.png "RPCS3 Directory")

¡Eso es todo!

{% include links.html %}