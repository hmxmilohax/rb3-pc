---
title: "Configuración Personalizada: GPU"
sidebar: espanol_sidebar
permalink: custom_config_gpu_es
folder: espanol
tags: [conf-pers, espanol]
summary: "Que cambiar bajo la pestaña de GPU dentro de la configuración personalizada de RPCS3"
series: "Configuración Personalizada"
weight: 3
---

![Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando "Write Color Settings" en un cuadro verde con una línea discontinua, "ZCULL Accuracy", "Resolution Scale", "Anisotropic Filtering", "Anti-Alising", "Framelimit", "Output Scaling" y "VSync" resaltados en un cuadro azul con contorno punteado.](https://carlmylo.github.io/docu-rpcs3/images/cust/gpu.png "GPU")

* ![Un cuadro verde con una línea discontinua.](https://carlmylo.github.io/docu-rpcs3/images/cust/smallgreen.png "Cuadro verde") **REQUERIDO**: 
	* **Activa "Write Color Buffers"** (Ingresar búferes de colores) - Los personajes tendrán rendimiento corrupto sin esta opción

* ![Un cuadro azul con contorno punteado.](https://carlmylo.github.io/docu-rpcs3/images/cust/smallblue.png "Cuadro azul") **Dependiendo en tu PC**: 
	* **Activa "VSync"** (Sincronización vertical) - Reduce el efecto de rasgado de pantalla y da fotogramas mas estables. Incrementa la latencia ligeramente. **No uses esto con "Frame Limit" activado!**
	* **Cambia "Frame Limit"** (Limite de fotogramas):
		* A "Off" (Desactivado) si quieres tener fotogramas altas (VBlank Frequency). Esto puede introducir agitación en el rendimiento del juego. Usa esta opción si tienes VSync activada.
		* A "60" si quieres fotogramas limitadas a 60 FPS (redundante con Vblank de 60 Hz).
		* "Auto" va usar lo predeterminado de RPCS3.
		* Es sugerido utilizar la configuración de tu tarjeta de gráficas para limitar la fotogramas o utilizar un programa como MSI Afterburner.
		* Aumentando las fotogramas sobre 60 utiliza muchos más recursos. No es recomendado para sistemas de gama baja.
		* Fotogramas sobre 60 pueden causar problemas con la detección de vocales.
		* Esta sugerido que desactives VSync dentro de Rock Band 3 Deluxe: `Menú > Opciones > Configuración Deluxe > Gráficos > VSync`
	* **Cambia "ZCULL Accuracy"** (Precisión de ZCull) a "Relaxed" (Relajada) - Mejora el rendimiento un poco pero puede causar anomalías gráficas.
	* **Ajusta "Anisotropic Filter"** (Filtro anisotrópico) a tu gusto y a lo que puede tu computadora. Ayuda con texturas. No debe de afectar el rendimiento tanto.
	* **Ajusta "Resolution Scale"** (Nivel de resolución) a tu gusto y a lo que puede tu computadora. Auméntala para obtener gráficos más nítidos.
	* **Cambia "Output Scaling"** a tu gusto y a lo que puede tu computadora. Esto afecta cómo se va "estirar" la imagen para llegar a la resolución de tu pantalla usando diferentes métodos de interpolación. Puede ayudar a los que tienen su nivel de resolución (mencionado arriba) en 100%.
		* "Nearest" (aproximación) es la interpolación mas cruda. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en pixelización.
		* Bilinear (bilineal) es interpolación mas suave. Si la resolución del juego no es exacta a la de tu pantalla, puede resultar en una imagen borrosa.
		* FidelityFX Super Resolution (FSR) usa calculaciones complejas para mejorar la imagen cuando se estira a la resolución de tu pantalla. Raramente, puede causar anormalidades en la imagen.
			* Puedes usar "RCAS Sharpening Strength" (fuerza de enfoque) abajo para ajustar cuanta fuerza tiene el efecto.

<br/>

{% include custom/series_conf_pers_next.html %}

{% include links.html %}