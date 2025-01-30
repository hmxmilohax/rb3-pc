---
title: Comunes
sidebar: espanol_sidebar
permalink: trbl_common_es
folder: espanol
tags: [resolviendo-problemas, espanol]
summary: "Como resolver problemas de sonido comunes."
toc: false
---

<div class="panel-group" id="accordion">
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#tex-malas">Los personajes tiene gráficas corruptas.</a>
                            </h4>
                        </div>
                        <div id="tex-malas" class="panel-collapse collapse noCrossRef">
                            <div class="panel-body">
<ul><p><img src="https://carlmylo.github.io/docu-rpcs3/images/trbl/common/wcb.png" alt="Una captura de Rock Band 3, con un personaje que tiene texturas corruptas." title="Graphical issues"></p>
<p>No leíste la guía y no <a href="https://carlmylo.github.io/docu-rpcs3/custom_config_gpu_es" target="_blank"><strong>[activaste Write Color Buffers en la pestaña de la configuración de GPU]</strong></a>.</p>
<p><img src="https://carlmylo.github.io/docu-rpcs3/images/trbl/common/wcbon.png" alt="Una captura de la configuración personalizada de la GPU de Rock Band 3, resaltando Write Color Settings en un cuadro verde con una línea discontinua." title="GPU"></p></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#flying-instruments">Los accesorios de mi personaje están volando.</a>
                            </h4>
                        </div>
                        <div id="flying-instruments" class="panel-collapse collapse">
                            <div class="panel-body">
<ul><p><img src="https://carlmylo.github.io/docu-rpcs3/images/trbl/common/flyinst.png" alt="Una captura de Rock Band 3 con un personaje que tiene problemas con sus accessorios."><br>
Esto pasa en PlayStation 3 pero es peor en RPCS3.<br>
Existe un parche que arregla las guitarras y una lista de todo los accesorios que tienen problemas.<br>
<a href="https://carlmylo.github.io/docu-rpcs3/trbl_teleprob_es" target="_blank">[Haz click para mas información.]</a></p></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#online-crasheos-de-puerto">[Internet] Mi juego crashea cuando busco a/me invitan jugadores.</a>
                            </h4>
                        </div>
                        <div id="online-crasheos-de-puerto" class="panel-collapse collapse">
                            <div class="panel-body">
<ul><p>Tu rúter tiene problemas con UPNP. Ve a la <a href="https://carlmylo.github.io/docu-rpcs3/custom_config_net_es" target="_blank">[pestaña de Network en la configuración personalizada de Rock Band 3]</a>, y desactiva “Enable UPNP.” Vas a necesitar investigar como <a href="https://es.wikihow.com/configurar-el-reenv%C3%ADo-de-puertos-en-un-router" target="_blank">[reenviar los puertos en tu rúter]]</a>.</p></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#se-siente-raro">No se siente bien el juego.</a>
                            </h4>
                        </div>
                        <div id="se-siente-raro" class="panel-collapse collapse">
                            <div class="panel-body">
<ul><p>Necesitas calibrar tu juego. También desactiva “Dolby Digital” si esta activado.<br>
Puedes ajustar esto en:<br>
<code>Menú &gt; Opciones &gt; Ajustes Del Sistema</code></p></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#sonido-feo">Mi juego se escucha feo.</a>
                            </h4>
                        </div>
                        <div id="sonido-feo" class="panel-collapse collapse">
                            <div class="panel-body">
<ul><p><iframe src="https://www.youtube.com/embed/UoCMEQbNThs" width="420" height="315">&#10;</iframe><br> 
Aumenta “Audio Buffer Duration” como mencionado en <a href="https://carlmylo.github.io/docu-rpcs3/custom_config_aud_es" target="_blank">[la pestaña de Audio en la configuración de Rock Band 3]</a> hasta que se escuche mejor el juego. Si tienes una computadora de baja gama, empieza con 100 ms y bajale hasta lo que puedas.<br>
Alternativamente, puedes ver la sección de problemas comunes de rendimiento abajo.</p></ul>
                            </div></div></div>
                    <!-- /.panel -->
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <h4 class="panel-title">
                                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#mal-rendimiento">Problemas de rendimiento comunes</a>
                            </h4>
                        </div>
                        <div id="mal-rendimiento" class="panel-collapse collapse">
                            <div class="panel-body">
<ul>
<li>Activa <a href="https://help.ableton.com/hc/es/articles/115000211304-Utilizar-el-plan-de-energ%C3%ADa-de-alto-rendimiento-Windows" target="_blank">[el plan de energía de alto rendimiento]</a>.</li>
<li>Regresa a la <a href="https://carlmylo.github.io/docu-rpcs3/custom_config_es#configuraci%C3%B3n-personalizada" target="_blank">[sección de configuración personalizada]</a> y trata la los ajustes recomendados para computadoras de baja gama.</li>
<li>Desactiva los efectos en la configuración de Deluxe.
<ul>
<li><code>Menú &gt; Opciones &gt; Configuración Deluxe &gt; Gráficos</code></li>
</ul>
</li>
<li>Si tu placa base tiene un chip de Realtek (mayoría de las computadoras), trata <a href="https://www.realtek.com/Download/List?cate_id=593&menu_id=298" target="_blank">[descargar el controlador actual]</a>. Esto es un <a href="https://github.com/RPCS3/rpcs3/issues/14648" target="_blank">[problema]</a> causado por usar el controlador integrado de Microsoft llamado “Sonido de Alta Definición.” Este controlador no usa todos los hilos del procesador.</li>
<li>Cierra el cliente de Discord y ábrelo en tu navegador o tu celular. También puedes usar un cliente alternativo <a href="https://github.com/Vencord/Vesktop" target="_blank">[como Vesktop]</a>, pero no somos responsables por tu cuenta de Discord.</li></ul>
                            </div>
                        </div>
                    </div>
                    <!-- /.panel -->
</div>
<!-- /.panel-group -->

{% include links.html %}