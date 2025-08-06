---
title: "Combinando Carpetas de Customs"
sidebar: customses_sidebar
permalink: customs_merging_es
folder: espanol
tags: [customs-es, espanol]
summary: "Como combinar carpetas de canciones para iniciar el juego mas rápido."
series: "Convirtiendo Customs"
weight: 4
toc: false
---

Con el paso del tiempo, puede que tengas un montón de carpetas de customs. Esto es un problema, ya que Rock Band 3 carga por carpeta y mientras más carpetas tengas, más tardará en cargar el juego.  
![Una captura de Rock Band 3 cargando descargas de contenido. Esta cargando 94 descargas.](https://rb3pc.milohax.org/images/xtra/customs/rb3mergees.png "RPCS3")  



Idealmente, deberías empaquetar la mayor cantidad de canciones posibles en un solo pack para que Rock Band 3 cargue más rápido.  
![Una captura de Rock Band 3 cargando descargas de contenido. Esta cargando 48 descargas.](https://rb3pc.milohax.org/images/xtra/customs/rb3mergeafteres.png "RPCS3")  



Gracias a la herramienta Onyx, esto es fácil. El proceso es casi igual a [[la guía de convertir archivos de Xbox 360 a RPCS3/PS3]](https://rb3pc.milohax.org/customs_360toPS3_es).  
Antes de empezar, toma en cuenta que necesitas tener espacio libre no solo para las carpetas originales, si no la carpeta combinada **temporalmente**.  
¡Asegúrate que tengas suficiente espacio!

#### 1.
Abre un explorador de archivos y entra a la carpeta donde están instaladas tus customs.  
Usualmente, esto es `dev_hdd0\game\BLUS30463\USRDIR\`.  
Si estas en PS3, vas a tener que transferir las carpetas que quieres combinar. Esto puede tomar un rato.  
Si estas en RPCS3, puedes llegar ahí rápidamente haciendo un click derecho en Rock Band 3 y después en `Open Folder > Open Game Data Folder`.  
![Una captura de RPCS3, con el cursor sobre Open Game Data Folder, dentro del menú despegable de Open Folder.](https://rb3pc.milohax.org/images/xtra/customs/rpcs3gamedata.png "RPCS3")

#### 2.
Ahora, abre Onyx y haz click en `Quick convert/pack`.  
![Una captura de la pantalla principal de Onyx. El cursor esta sobre "Quick convert/pack."](https://rb3pc.milohax.org/images/xtra/customs/onyxhomequick.png "Onyx Console")

#### 3.
Quédate en la pestaña de `RB quick convert + pack creator`.  
Ahora, arrastra las carpetas que quieres combinar. También puedes usar `Add Rock Band Song` para elegirlas.  
![Una animación de carpetas de customs siendo arrastradas a la pestaña de "RB quick convert + pack creator" dentro de Onyx.](https://rb3pc.milohax.org/images/xtra/customs/onyxdraganddropmerge.gif "Quick Convert")

Es recomendado que actives la opción de `Author to DTA tag` abajo a la derecha.  
![Una captura de la pantalla de Quick Convert dentro de Onyx. El cursor esta sobre "Author to DTA" y esta resaltado.](https://rb3pc.milohax.org/images/xtra/customs/onyxauthormerge.png "Quick Convert")

#### 4.
Abajo de la primera línea de botones grises, haz click en el primer menú y luego en `Make Packs`.  
`Make Songs` no sirve en este contexto porque solo va a crear mas carpetas sueltas.  
![Una captura de la pantalla de Quick Convert dentro de Onyx. El cursor presiono "Make songs: produced a single file for each song" y despues elije "Make packs: combine songs up to a maximum file size."](https://rb3pc.milohax.org/images/xtra/customs/onyxmakepacksmergees.png "Quick Convert")

#### 5.
Abajo a la izquierda, asegúrate que `Encrypt .mid.edat` este activado, y elije entre `PKG (PS3)` o `Folders (PS3)`. 
* `Folders (PS3)` compila las canciones a un carpeta sin crear un archivo PKG. Esta opción es recomendada si usas RPCS3 o un PS3 con FTP. Es **mucho mas** rápido que hacer PKGs. También puedes crear carpetas mas grandes que 4 GBs.
* `PKG (PS3)` compila un archivo PKG. Esto solo es recomendado si tienes un PS3 con cual tienes que usar una memoria USB para agregar canciones.

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#folders" data-toggle="tab">Folders (PS3)</a></li>
    <li><a href="#pkg" data-toggle="tab">PKG (PS3)</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="folders">
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxoutfoldermergees.png" alt="Una captura de la pantalla de Quick Convert dentro de Onyx. El cursor esta sobre &quot;Folders (PS3)&quot; y &quot;Encrypted .mid.edat&quot; esta activado." title="Quick Convert">
<h4>6.</h4>
<p><em>(Opcional pero recomendado)</em><br>
Por defecto, Onyx va a generar una carpeta con un nombre basado en la primera (o unica) canción en el paquete, como <code>OxxxxxSongName</code>.<br>
Es recomendando usar un nombre personalizado. Simplemente, cambia la opción de <code>Combine into one new USRDIR subfolder per pack</code> a la de <code>Custom USRDIR subfolder</code> y entra el nombre que tu quieras.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxfoldernamerpcs3mergees.png" alt="Una captura de la pantalla de Quick Convert dentro de Onyx. El cursor esta sobre &quot;Custom USRDIR subfolder&quot; en vez de &quot;Keep original USRDIR subfolders&quot;." title="Quick Convert"></p>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxnamepackes.png" alt="Una captura de Onyx con su pantalla de nombrar el paquete. El paquete fue nombrado &quot;paquete_de_customs.&quot;" title="Quick Convert"></p>
<h4>7.</h4>
<p><em>(Opcional pero recomendado)</em><br>
Como estas creando una carpeta con archivos sueltos, puedes tener carpetas mas grandes que el tamaño que viene por defecto en Onyx (4000 MiB o 4.1 GBs). Puedes usar esto para crear carpetas mas grandes que 4GB.<br>
Simplemente, entra cualquier en la parte abajo a la izquierda.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxmakepackfilesizees.png" alt="Una captura de la pantalla de Quick Convert dentro de Onyx. &quot;Max Pack Size (MiB)&quot; esta puesto en &quot;99999&quot;." title="Quick Convert"></p>
<h4>8.</h4>
<p>Abajo va ver un un botón verde que dice <code>Make pack</code> o <code>Start</code> si elegiste la opción de <code>Make Songs</code><br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxmakepackrpcs3mergees.png" alt="Una captura de la pantalla de Quick Convert dentro de Onyx. El cursor esta sobre &quot;Make 1 pack.&quot;" title="Quick Convert">
<p>Ve a donde tienes tu carpeta de <code>dev_hdd0</code>. Usualmente está en la carpeta de RPCS3.<br>
Si vas a instalar el paquete a un PS3 por FTP, elije cualquier carpeta que te conviene mas.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/savefolderes.png" alt="Una captura de un explorador de archivos. La carpeta de &quot;dev_hdd0&quot; esta elegida y el cursor esta sobre &quot;Select folder.&quot;" title="Select Folder"></p>
<p>Cuando termines, tendrás las canciones en la carpeta, listas para jugar, si estas en emulador.<br>
Si estas en PS3, tendrás que copiar la carpeta por FTP a <code>dev_hdd0/game/BLUS30463/USRDIR</code>.
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxcreatedrpcs3mergees.png" alt="Una captura de Onyx con su pantalla de nombrar el paquete. The pack has been named &quot;my_custom_pack.&quot;" title="Quick Convert"></p>

</div>
<div role="tabpanel" class="tab-pane" id="pkg">
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxoutpkgmergees.png" alt="Una captura de la pantalla de Quick Convert dentro de Onyx. The cursor is selecting &quot;PS3 (PS3)&quot; and &quot;Encrypted .mid.edat&quot; has been enabled." title="Quick Convert">
<h4>6.</h4>
<p><em>(Opcional pero recomendado)</em><br>
Con estos métodos, el PKG va crear una carpeta con un nombre generado automáticamente. Por defecto, va a salir como <code>OxxxxxSongName</code>, con <code>SongName</code> siendo el nombre de la primera canción.<br>
Recomendamos cambiar la opción de <code>Combine into one new USRDIR subfolder per pack</code> por la de <code>Custom USRDIR subfolder</code> y ponerle el nombre que tu quieras.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxfoldernamepkgmergees.png" alt="Una captura de la pantalla de Quick Convert dentro de Onyx. El cursor esta sobre &quot;Custom USRDIR subfolder&quot; en vez de &quot;Keep original USRDIR subfolders&quot;." title="Quick Convert"></p>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxnamepackes.png" alt="Una captura de Onyx con su pantalla de nombrar el paquete. The pack has been named &quot;my_custom_pack.&quot;" title="Quick Convert">
<h4>7.</h4>
<p>Abajo va ver un un botón verde que dice <code>Make pack</code>.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxmakepackpkgmergees.png" alt="Una captura de la pantalla de Quick Convert dentro de Onyx. El cursor esta sobre &quot;Make 1 pack.&quot;" title="Quick Convert"></p>
<p>Elige una carpeta para poner el archivo PKG file y dale un nombre.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/savepkges.png" alt="Una captura de un explorador de archivos. The file name has been set to &quot;my_custom_pack&quot;" title="Select Folder"></p>
<p>Se creara un archivo PKG cuando termine.<br>
Puedes instalar este archivo como cualquier otro PKG.<br>
<img src="https://rb3pc.milohax.org/images/xtra/customs/onyxcreatedpkgmergees.png" alt="Una captura de Onyx con su pantalla de nombrar el paquete. The pack has been named &quot;my_custom_pack.&quot;" title="Quick Convert"></p>

</div>
</div>

{% include custom/series_customses_next.html %}

{% include links.html %}