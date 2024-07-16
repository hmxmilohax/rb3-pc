---
title: Extra - Ajustes Adicionales
author: Carl Mylo
date: 2000-11-02
category: English
layout: post
---

# Guías Adicionales

## Añadir mas memoria a Rock Band 3

### Intro

Vamos a darle mas memoria a Rock Band 3 en RPCS3. Esto esta muy recomendando porque ayuda la estabilidad y también sube el limite de canciones hasta 16000.

> ##### ADVERTENCIA
>
> _Si bajaste y estas usando [[un perfil de la Configuración Rápida,]](https://rb3pc.milohax.org/espanol/configuracionrapida/) ya tienes esto activado y no necesitas hacer nada_
{: .block-warning  }

> ##### PELIGRO
>
> _Necesitas [[activar Debug Console Mode en la pestaña "Advanced" en la configuración personalizada para Rock Band 3]](https://rb3pc.milohax.org/espanol/configuracionpersonalizada/#advanced). **Si no haces esto, tu juego va a parar de funcionar.**_
{: .block-danger  }

### Como Hacerlo

* Primero, vas a necesitar [[bajar el archivo que activa memoria adicional. Haz click aquí para bajarlo.]](https://github.com/hmxmilohax/rb3-pc/raw/main/config/customconfig/memory.zip)

**Después de bajar el archivo, extrae los contenidos en muevelos a la carpeta donde esta RPCS3. Las carpetas se combinaran si lo hiciste bien.**

El ejemplo abajo enseña, la carpeta `devhdd_0` del archivo (memory.zip) fue extraída y sus contenidos fueron movidos a la carpeta de RPCS3.

![Una animacion de "dev_hdd0" de "memory.zip" siendo arrastrado a la carpeta de RPCS3.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/cust/himem.gif "Recommended.zip")


# ZONA DE PELIGRO

## Intro

> ##### PELIGRO
>
> _Abajo están ajustes adicionales para personas avanzadas. **¡Estas son cosas que mayoría de las personas no necesitan hacer!** Procede con precaución!_
{: .block-danger  }


## Mover Archivos del Juego

### Intro:

Si los archivos de Rock Band 3 están tomando mucho espacio en tu disco primario, puedes moverlos a otro disco mientras el emulador se quede en tu disco primario.

Antes de empezar, cierra RPCS3.

Primero, crea una carpeta donde vas a mover esta carpeta.

En las capturas, yo nombre la carpeta "RPCS3 Directory" (Directorio de RPCS3).

![Una captura de la carpeta creada, que se llama "RPCS3 Directory."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirfolder.png "RPCS3 Directory")

Ahora, en la carpeta donde esta RPCS3, corta estas carpetas:
* dev_bdvd
* dev_flash
* dev_flash2
* dev_flash3
* dev_hdd0
* dev_hdd1
* dev_usb000
* games

![Una captura de las carpetas siendo cortadas.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dircut.png "Cut (CTRL+X")

Pega las carpetas en la carpeta que creaste.

![Una animación de las carpetas que fueron cortadas siendo pegadas en la carpeta "RPCS3 Directory."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirpaste.gif "RPCS3 Directory")

Cuando termine de mover los archivos, abre RPCS3.

Haz click en **Manage** (Administrar) **>** **Virtual File System** (Sistema de archivos virtual.)


![Una captura de RPCS3, con el cursor sobre "Virtual File System", en la categoría de "Manage."](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirrpcs3.png "RPCS3 Directory")

En la pantalla de Virtual File System, haz click en símbolo `+` hacia la parte inferior derecha.

![Una captura de Virtual File System, con el cursor sobre el símbolo +.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirvfsadd.png "Virtual File System")

Busca la carpeta que creaste, seleccionala, y haz click a "Select Folder" (Elegir Carpeta).

![Una captura con la carpeta creada siendo seleccionada.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirfoldersel.png "RPCS3 Directory")

Finalmente, haz click en "Save" (Guardar).

![Una captura de Virtual File System, con la carpeta creada en la lista de EmulatorDir.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/xtra/dir/dirvfssave.png "RPCS3 Directory")

Eso es todo!