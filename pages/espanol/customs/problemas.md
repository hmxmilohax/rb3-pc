---
title: "Problemas y Soluciones"
sidebar: customses_sidebar
permalink: customs_troubleshooting_es
folder: espanol
tags: [customs-es, espanol]
summary: "Como resolver problemas comúnes con customs."
series: "Convirtiendo Customs"
weight: 6
---

## Canciones no salen en línea / Puntajes no se guardan
Rock Band 3 solo puede guardar puntajes para canciones con IDs que contienen números y nada mas. Si una canción tiene letras en el ID, el juego va a tener que crear un ID nuevo cada vez que inicies.  
Esto significa que tus puntajes se perderán todo el tiempo.

Igualmente, tendrás problemas jugando en línea con customs por la misma razón. Si el ID tiene letras, la canción va a aparecer en tu biblioteca en gris.

![A screenshot of Rock Band 3, showing songs with a darker color as they are disabled.](https://rb3pc.milohax.org/images/trbl/online/missingsonges.png "Rock Band 3: Missing Songs Example")

Puedes resolver este problema con Nautilus.

### Arreglar los IDs antes de instalar

1\. Abre Nautilus y elije `Batch DTA Processor`.   
![Una captura de Nautilus. El cursor esta sobre "Batch Processor."](https://rb3pc.milohax.org/images/xtra/customs/nautilushomebatchproc.png "Nautilus")

2\. Arrastra cualquier archivo CON de tu carpeta a Nautilus y **asegúrate que `Automatically change alphanumeric song IDs` esté activado.**  
Haz click en `Begin` para procesar todos los archivos CON seleccionados.  
Cuando termine, cierra `Batch Processor`.  
![Una animación de Nautilus' Batch DTA Processor. Las canciones son arrastradas a la pantalla y luego empiezan a hacer procesadas después de presionar "Begin."](https://rb3pc.milohax.org/images/xtra/customs/nautilusbatchfix.gif "Batch DTA Processor")

3\. Cuando termine, puedes cerrar `Batch Processor` y continuar con la cuarta parte del [[tutorial principal]](https://rb3pc.milohax.org/customs_360toPS3_es#4){:target="_blank"}.

### Arreglando IDs de customs que ya están instaladas

1\. Abre Nautilus y elije `PS3 Converter`.  
![Una captura de Nautilus. El cursor esta sobre "PS3 Converter."](https://rb3pc.milohax.org/images/xtra/customs/nautilushomeps3.png "Nautilus")

2\. Arriba de la pantalla de `PS3 Converter`, ve a:  
`Numeric ID Options > Batch replace song IDs`  
![A screenshot of Nautilus's PS3 Converter. A cursor hovers over "Batch replace song IDs" under the "Numeric ID Options" menu.](https://rb3pc.milohax.org/images/xtra/customs/nautilusps3batchid.png "PS3 Converter")

3\. En PS3 o RPCS3, entra a la carpeta de la canción/paquete que tenga un ID incorrecto (usualmente es `dev_hdd0\game\BLUS30463\USRDIR\[SONGNAME]\songs`).  
Busca el archivo que se llama `songs.dta` dentro de la carpeta. 
![Una captura de un explorador de archivos. "dev_hdd0" is selected and El cursor esta sobre "Open".](https://rb3pc.milohax.org/images/xtra/customs/nautilusps3batchselectes.png "Select DTA file to edit")


4\. Espera que termine de procesar las canciones de la carpeta. Cuando termine, puedes compartir el archivo `songs.dta` con tus amigos para finalmente poder jugar las canciones juntos.  
![A screenshot of Nautilus's PS3 Converter. It has just finished replacing custom songs without numeric IDs.](https://rb3pc.milohax.org/images/xtra/customs/nautilusps3batchdone.png "PS3 Converter")


## Canciones se traban al final
A veces, algunas canciones se pueden quedar trabadas al final, repitiendo el último segundo de la canción sin fin.  
* **¡Necesitas el archivo CON original para arreglar este problema!**
* **¡No metas canciones que no tengan este problema, porque el sonido de la canción va ser procesado otra vez y va perder un poco de calidad!**

1\. Abre Nautilus y ve a `PS3 Converter`.  
![A screenshot of Nautilus. A cursor hovers over "PS3 Converter."](https://rb3pc.milohax.org/images/xtra/customs/nautilushomeps3.png "Nautilus")

2\. Arriba de la pantalla de `PS3 Converter`, ve a:  
`Tools > Batch fix looping songs`  
![A screenshot of Nautilus's PS3 Converter. A cursor hovers over "Batch fix looping songs" under the "Tools" menu.](https://rb3pc.milohax.org/images/xtra/customs/nautilusps3batchloop.png "PS3 Converter")

3\. Va la carpeta donde esta el CON con problemas y selecciona la carpeta.  
Espera que termine.  
![A screenshot of Nautilus's PS3 Converter. It is in the process of fixing a looping file.](https://rb3pc.milohax.org/images/xtra/customs/nautilusps3batchloopproc.png "PS3 Converter")

4\. Cuando termine, Ya puedes continuar a la cuarta parte del[[tutorial principal]](https://rb3pc.milohax.org/customs_360toPS3_es#4){:target="_blank"}.

## PS3: Canciones grises

Por defecto, el control paterno del PlayStation 3 esta en nivel 9.  
Esto no te va dejar tocar canciones que tienen el dato de "Sin Calificación", y aparecerán grises. 
![A screenshot of Rock Band 3's song library. It shows as greyed out song.](https://rb3pc.milohax.org/images/xtra/customs/ps3grey.png "Rock Band 3: Grey Songs")

Si elijes una de estas canciones, el juego va a crashear.
Para arreglar esto, cambia el `Control paterno` a `No` en:  
XMB: [ **Ajustes** ] -> [ **Ajustes de seguridad** ] -> [ **Control paterno** ] -> [ **No** ]  
![A screenshot of the parental control menu in PlayStation 3's XMB home menu. The level is set to "Off".](https://rb3pc.milohax.org/images/xtra/customs/ps3parentales.png "Parental Control")

## Canciones siguen atoradas cargando

En casos raros, algunas canciones tendrán problemas cargando, aún si seguiste todos los pasos anteriores.  

Esto se puede arreglar con la opcion de `Batch Cryptor` en Nautilus.  
Toma en cuenta que vas a necesitar la version "1.1 Beta" de Rock Band 3 Deluxe si estas en PS3.  

1\. Abre Nautilus y elije `Batch Cryptor`.  
![A screenshot of Nautilus. A cursor hovers over "Batch Cryptor."](https://rb3pc.milohax.org/images/xtra/customs/nautilushomecrypt.png "Nautilus")

2\. Cambia a la opcion de `Decrypt` abajo de la pantalla.  
![A screenshot of Batch Cryptor. The mode has been switched to "Decrypt."](https://rb3pc.milohax.org/images/xtra/customs/nautiluscryptdecrypt.png "Batch Cryptor")

3\. Si juegas en PS3 o RPCS3, ve a la carpeta donde está la canción que quieres arreglar.  
Usualmente va estar en `dev_hdd0\game\BLUS30463\USRDIR\[NOMBRE_DE_PAQUETE]\songs\[CANCION_CON_PROBLEMAS]`).  
Va a haber un archivo `.mogg` en la carpeta de la canción.  
![Una captura de un explorador de archivos. A mogg file is selected.](https://rb3pc.milohax.org/images/xtra/customs/findmogg.png "MOGG File")

4\. Arrastra el archivo `.mogg` en la pantalla de `Batch Cryptor` y haz click en `Begin`.  
![A GIF of a .mogg file being dropped into "Batch Cryptor" the being decrypted.](https://rb3pc.milohax.org/images/xtra/customs/nautiluscryptdecryptmogg.gif "Quick Convert")

5\. Una carpeta llamada `decrypted` va a aparecer cuando termine.  
Entra a la carpeta de `decrypted` y corta el archivo `.mogg` adentro.  
Regresa una carpeta para atrás y pega el archivo `.mogg`, remplazando el original.  
![A GIF of a .mogg file within the "decrypted" folder being cut then pasted in the folder before it. It replaces the old .mogg file.](https://rb3pc.milohax.org/images/xtra/customs/moggreplace.gif "Quick Convert")

{% include custom/series_customses_next.html %}

{% include links.html %}