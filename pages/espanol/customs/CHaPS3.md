---
title: "Convirtiendo customs para Clone Hero/YARG a formato de PS3/RPCS3"
sidebar: customses_sidebar
permalink: customs_CHtoPS3_es
folder: espanol
tags: [customs-es, espanol]
summary: "Como convertir canciones de Clone Hero/YARG a PS3/RPCS3"
series: "Convirtiendo Customs"
weight: 3
toc: false
---

<span style="font-size:x-large;">ADVERTENCIA - LEE ESTO ANTES DE TODO</span>

¡Solo has esto como **último recurso** y si las canciones que quieres solo existen para juegos que son clones (Clone Hero/YARG). Si la canción originalmente existió en un formato para Rock Band (de manera oficial o por custom), **usa esa versión antes de todo y lee la guía principal**.

Toma esto en cuenta porque **si no lo haces, la canción va a perder muchos datos**, como:
* Incompatibilidad con mejoras/actualizaciones por Rock Band 3 Deluxe
	* Armonías, teclado, guitarra/bajo PRO e arreglos de canciones para canciones que no las tenían
* Su identidad propia para poder jugar en linea y tener tableros de calificaciones
* Animaciones propias y "lipsync" serán perdidos

Si lo haces como quiera, **no te podemos ayudar con ningún problema** causado por ignorar esta advertencia.
**!No digas que no te advertimos!**


#### 1.
Después de descargar las canciones que quieras usar, entra a Onyx y elige `Batch recompile`.  
![Una captura de la pantalla principal de Onyx. A cursor hovers over "Batch recompile."](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatch.png "Onyx Console")

#### 2.
Arriba de la pantalla de "Batch Recompile", haz click en `Edit` y luego `Preferences`.  
![A screenshot of Onyx's Batch Recompile. The "Edit" menu has been expanded and "Preferences" is selected.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefs.png "Batch Recompile")

#### 3.
Entra a la pestaña de `Rock Band`. 
Cambia a `Magma optional`.  
![A screenshot of Onyx's Preferences window. Under the "Rock Band" tab, "Magma optional" is selected.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefsrb.png "Batch Recompile")

#### 4.
Te dara una advertencia.  
Haz click en `OK`.  
![A screenshot of a warning from Onyx. It warns that disabling Magma will crash Rock Band.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchwarn.png "Magma Warning")

#### 5.
Cambia a la pestaña de `Audio`. 
Baja a la barra de `OGG Vorbis quality` a `3.00`.  
Después, haz click en `Save`.  
![A screenshot of Onyx's Preferences window. Under the "Audio" tab, "Magma optional" is selected.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchprefsaud.png "Batch Recompile")

#### 6.
Arrastra la(s) carpeta(s) que contiene(n) las canciones que quieres convertir a la pantalla de `Batch recompile`.  
![A GIF of customs in Clone Hero format being dragged and dropped into the "Songs" tab of Onyx's Batch Recompile.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchdrag.gif "Batch Recompile")


#### 7.
Cambia a la pestaña de `RB3`.  
*(Opcional)* Muchas charts hechas para Clone Hero solo tienen una parte de guitarra. Es posible duplicar las partes para que mas personas puedan jugar la canción al mismo tiempo. Haz click en `Default part configuration`.
* `Fill empty parts with first guitar, then drums` - Llena partes vacías con guitarra y luego batería
* `Copy guitar to bass/keys/drums` - Copia guitarra a bajo/teclado/batería
* `Copy drums/dance to guitar/bass/keys` - Copia batería/coreografía a guitarra/bajo/teclado
![A screenshot of Onyx's Batch Recompile window. Under the "RB3" tab, "Fill empty parts with first guitar, then drums" is selected.](https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchparts.png "Batch Recompile")


#### 8.
Para terminar, haz click en `Create PS3 PKG files` o en `Create PS3/RPCS3 folders`.  
* `Create PS3/RPCS3 folders` compila las canciones a un carpeta sin crear un archivo PKG. Esta opción es recomendada si usas RPCS3 o un PS3 con FTP. Es **mucho mas** rápido que hacer PKGs.
* `Create PS3 PKG files` compila un archivo PKG. Esto solo es recomendado si tienes un PS3 con cual tienes que usar una memoria USB para agregar canciones.
<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#folders" data-toggle="tab">Create PS3/RPCS3 folders</a></li>
    <li><a href="#pkg" data-toggle="tab">Create PS3 PKG files</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="folders">
<p><img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchfolders.png" alt="A screenshot of Onyx's Batch Recompile window. Under the &quot;RB3&quot; tab, &quot;Create PS3/RPCS3 folders&quot; is selected." title="Batch Recompile"></p>
<h4 id="section">9.</h4>
<p>Ve a donde tienes tu carpeta de <code>dev_hdd0</code>. Usualmente está en la carpeta de RPCS3.<br>
Si vas a instalar el paquete a un PS3 por FTP, elije cualquier carpeta que te conviene mas.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/savefolder.png" alt="Una captura de un explorador de archivos. A location is set and El cursor esta sobre &quot;Select Folder.&quot;" title="Select Folder"></p>
<h4 id="section-1">10.</h4>
<p>Cuando termines, tendrás las canciones en la carpeta, listas para jugar, si estas en emulador.<br>
Si estas en PS3, tendrás que copiar la carpeta por FTP a <code>dev_hdd0/game/BLUS30463/USRDIR</code>.
Hasta puedes actualizar tu colección musical mientras estés dentro del juego con RB3DX. Dentro de Rock Band 3, ve a:<br>
<code>Opciones &gt; Extras &gt; Actualizar Colección Musical</code> para cargar las canciones nuevas.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchfinish.png" alt="A screenshot of Onyx's Batch Recompile Task tab. It is showing an in-progress conversion." title="Batch Recompile"></p>

</div>
<div role="tabpanel" class="tab-pane" id="pkg">
<p><img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchpkg.png" alt="A screenshot of Onyx's Batch Recompile window. Under the &quot;RB3&quot; tab, &quot;Create PS3/RPCS3 folders&quot; is selected." title="Batch Recompile"></p>
<h4 id="section">9.</h4>
<p>Elige una carpeta para poner el archivo PKG file y dale un nombre.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/savepkgfolder.png" alt="Una captura de un explorador de archivos. A location is set and El cursor esta sobre &quot;Select Folder.&quot;" title="Select Folder"></p>
<h4 id="section-1">10.</h4>
<p>Se crearan archivos PKG cuando termine.<br>
Puedes instalar estos archivos como otros archivos PKG.<br>
<img src="https://carlmylo.github.io/rb3-pc/images/xtra/customs/onyxbatchfinish.png" alt="A screenshot of Onyx's Batch Recompile Task tab. It is showing an in-progress conversion." title="Batch Recompile"></p>

</div>
</div>

{% include custom/series_customses_next.html %}

{% include links.html %}