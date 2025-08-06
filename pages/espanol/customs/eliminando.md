---
title: "Eliminando canciones de paquetes"
sidebar: customses_sidebar
permalink: customs_deleting_es
folder: espanol
tags: [customs-es, espanol]
summary: "Como eliminar canciones de un paquete."
series: "Convirtiendo Customs"
weight: 5
---

Rock Band 3 puede borrar canciones dentro del juego, pero si la canción es parte de un paquete, también va a borrar el resto del paquete.  
![A screenshot from Rock Band 3, warning the user that they're about to delete many songs from the library.](https://rb3pc.milohax.org/images/xtra/customs/rb3delwarnes.png "Delete song")

La mejor manera de arreglar esto es usando el "Quick Pack Editor"

1\. Abre Nautilus y elije `Quick Pack Editor`.  
![A screenshot of Nautilus. A cursor hovers over "Quick Pack Editor."](https://rb3pc.milohax.org/images/xtra/customs/nautilushomepack.png "Nautilus")

2\. Abre un explorador de archivos y entra a la carpeta del paquete que tiene la canción que quieras eliminar. Encuentra el archivo `songs.dta`.  
(Usualmente va estar en `dev_hdd0\game\BLUS30463\USRDIR\[PACKNAME]\songs`).
![Una captura de un explorador de archivos. "songs.dta" is selected.](https://rb3pc.milohax.org/images/xtra/customs/findfolder.png "songs")

3\. Arrastra y suelta el archivo `songs.dta` dentro de la carpeta en la pantalla de `Quick Pack Editor`.  
Selecciona la(s) canción(es) que quieres borrar y haz click en `Remove selected`.  
Cuando termines, haz click en `Save` para guardar tus cambios.  
![A GIF of a "songs.dta" file being dragged and dropped into Nautilus' Quick Pack Editor.](https://rb3pc.milohax.org/images/xtra/customs/nautiluspackdrag.gif "Quick Pack Editor")

4.\. Eso que borraste las canciones del archivo `songs.dta` y el juego no las detecta, van a seguir tomando espacio.  
Tienes que borrar sus carpetas también.  
![Una captura de un explorador de archivos. Multiple songs are selected and the cursor hovers over a popup menu option that says "Delete."](https://rb3pc.milohax.org/images/xtra/customs/packdelfolderes.png "songs")

{% include custom/series_customses_next.html %}

{% include links.html %}