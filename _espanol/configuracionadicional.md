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
> _Si bajaste y estas usando [[un perfil de la Configuración Rápida,]](https://hmxmilohax.github.io/rb3-pc/espanol/configuracionrapida/) ya tienes esto activado y no necesitas hacer nada_
{: .block-warning  }

> ##### PELIGRO
>
> _Necesitas [[activar Debug Console Mode en la pestaña "Advanced" en la configuración personalizada para Rock Band 3]](https://hmxmilohax.github.io/rb3-pc/espanol/configuracionpersonalizada/#advanced). **Si no haces esto, tu juego va a parar de funcionar.**_
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

## AshCentral: Códigos Privados

### Intro

Versión Vídeo de esta sección subtitulada en Español:  
[![Una mini-imagen de la versión vídeo de esta sección de la guía.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/vidthumb.png)](https://youtu.be/pfEUYhzw1ds "Rock Band 3 Multiplayer with Room Codes! [RPCS3] - YouTube")

**Códigos privados solo son útiles para crear sesiones privadas con jugadores en consola. Si quieres invitar alguien que juega en emulador, usa la opción de "Invitar a Amigos" dentro del menú de "Jugar en AshCentral"!**

### Preparaciones para usar códigos privados en AshCentral:

Para usar el sistema de códigos de sala en AshCentral, **asegúrate que RPCS3 este configurado para conectar a AshCentral**. **Entra al** [[**Discord de Milohax**]](https://rb3dx.neocities.org/discord) y **ve al canal** de **[\[#ashcentral-status\]](https://discord.com/channels/961352072140324924/1153056600030973992)**.

**Copia la información a RPCS3 como dicho en la sección** [**[network]**](https://hmxmilohax.github.io/rb3-pc/espanol/configuracionpersonalizada/#network) (red) **de la guia**.

Cuando hagas eso, [**[ve al sitio de AshCentral, GoCentral.Rocks]**](https://gocentral.rocks/) **para registrar una cuenta**.

[![Captura del sitio web de AshCentral, GoCentral.Rocks, con la opción "Register" de la subsección "Account" resaltada.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/splash.png)](https://gocentral.rocks/ "GoCentral")

**Registra** (Register) **tu cuenta.**

[![Captura del sitio web de AshCentral, GoCentral.Rocks, en la subpágina de registro, con "Register" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/register.png)](https://gocentral.rocks/register "GoCentral - Register")

Cuando registres tu cuenta, **entra tus datos para entrar a la cuenta**.

[![Captura del sitio web de AshCentral, GoCentral.Rocks, en la subpágina de inicio de sesión, con "Login" resaltado](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/login.png)](https://gocentral.rocks/login "GoCentral - Login")

Te va a regresar a la pagina principal. **Se va ver tu usuario en el rincón derecho de arriba. Mueve el cursor arriba de tu nombre y luego haz clic en "Settings"** (Ajustes).

[![Captura del sitio web de AshCentral, GoCentral.Rocks, con la opción "Settings" de la subsección del nombre de usuario resaltada.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/splashsettings.png)](https://gocentral.rocks/settings "GoCentral")

**En la pagina de "Settings" vas a ver una opcion llamada "Link Account"** (Connectar Cuenta). **Hazle clic**.

[![Captura del sitio web de AshCentral, GoCentral.Rocks, en la subpágina de información de la cuenta, con "Link Account" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/settings.png)](https://gocentral.rocks/link "GoCentral")

Te va a llevar a una pagina donde vas a entrar el código para conectar tu cuenta con el juego. Deja esta pagina abierta. **Deja a esta pagina abierta**.

[![Captura del sitio web de AshCentral, GoCentral.Rocks, en la subpágina de vinculación de cuentas, con "Link" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/link.png)](https://gocentral.rocks/link "GoCentral")

**Abre Rock Band 3**.

Cuando cargue el menú principal, **entra a las "Opciones"**

![Captura de Rock Band 3, con Opciones resaltadas.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/optionses.png "Rock Band 3: Options")

**Ve a "Extras".**

![Captura de Rock Band 3, con "Extras" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/extrases.png "Rock Band 3: Extras")

**Ve a "Código de Activación de Cuenta"**.

![Captura de Rock Band 3, con "Código de Activación de Cuenta" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/accountlinkingcodees.png "Rock Band 3: Código de Activación de Cuenta")

**Te va dar un código**.

![Captura de Rock Band 3, con un código para entrar en gocentral.rocks.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/codees.png "Rock Band 3: Code Here")

Ahora, **copia el código en la pagina, y haz clic a "Link"** (Conectar). **Despues, reinicia Rock Band 3**.

![Captura de pantalla del sitio web de AshCentral, GoCentral.Rocks, en la subpágina de vinculación de cuentas, con "Link" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/link.png "GoCentral - Link Account")

Te va a regresar a la pagina principal. **Se va ver tu usuario en el rincón derecho de arriba. Mueve el cursor arriba de tu nombre y luego haz clic en "Settings"** (Ajustes).

[![Captura del sitio web de AshCentral, GoCentral.Rocks, con la opción "Settings" de la subsección del nombre de usuario resaltada.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/splashsettings.png)](https://gocentral.rocks/settings "GoCentral")

Si hiciste todo bien, **la pagina de va enseñar el usuario de tu cuenta RPCN, que estas usando RPCS3, Band Name (nombre de banda), y fans.**

![Captura del sitio web de AshCentral, GoCentral.Rocks, en la subpágina de información de la cuenta, con nuevos detalles.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/linked.png "GoCentral - Settings")

Si no vez nada nuevo, no entraste el código correcto. Las letras de Rock Band 3 pueden ser un poco difícil para leer así que aveces se necesita tratar otra vez. 

Ahora, vamos a ver como crear o entrar a sesiones.

**Abre Rock Band 3** (si no esta abierto).

**En la pagina principal de AshCentral, haz clic a "Join Game"** (Entrar a juego).

[![Captura de pantalla del sitio web de AshCentral, GoCentral.Rocks, con la opción "Join Game" resaltada.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/joingame.png)](https://gocentral.rocks/sessions "GoCentral")

**Antes de crear o entrar a una sesión, necesitas tienes que presionar en "Jugar en AshCentral" en el menu de Rock Band 3.**

![Captura de pantalla de Rock Band 3, con "Play on AshCentral" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/ashcentrales.png "Rock Band 3: Play on AshCentral")


### Creando Sesiones:

**Haz click en "Host Session"** en GoCentral.Rocks.
[![Captura de pantalla del sitio web de AshCentral, GoCentral.Rocks, en la subpágina "Join Game", con "Host Session" resaltado..](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/hostsession.png)](https://gocentral.rocks/sessions/ "GoCentral - Host Session")

Te dará un código. **Pasa este código a todos los que quieres invitar.**

[![Captura de pantalla del sitio web de AshCentral, GoCentral.Rocks, en la subpágina "Host Session", con un código de sesión y una reloj contando para abajo.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/hostroom.png)](https://gocentral.rocks/sessions/host "GoCentral - Host Session")

Ahora, **en Rock Band 3, entra a Jugar, Partida Rápida, y "Buscar Jugadores En AshCentral"**.

![Captura de pantalla de Rock Band 3, con "Buscar Jugadores En AshCentral" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/findashcentralplayerses.png "Rock Band 3: Buscar Jugadores En AshCentral")

Ahora debes de ver que se conecten los que fueron invitados.

![Captura de pantalla de Rock Band 3, en un cuarto en linea.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/hostlobbyes.png "Rock Band 3: Buscando jugadores en AshCentral")

### Entrando a Sesiones:

**Haz clic en "Join Session"** (Unirse a sesión) en GoCentral.Rocks.
[![Captura de pantalla del sitio web de AshCentral, GoCentral.Rocks, en la subpágina "Join Game", con "Join Session" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/joinsession.png)](https://gocentral.rocks/sessions/ "GoCentral - Join Session")

**Entra el codigo que te mandaron**.

[![Captura de pantalla del sitio web de AshCentral, GoCentral.Rocks, en la subpágina "Join Session", pidiendo al usuario un código de sesión.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/joinroom.png)](https://gocentral.rocks/sessions/join "GoCentral - Join Session")

Ahora, **en Rock Band 3, entra a Jugar, Partida Rápida, y "Buscar Jugadores En AshCentral"** (Encontrar jugadores en AshCentral).

![Captura de pantalla de Rock Band 3, con "Buscar Jugadores En AshCentral" resaltado.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/findashcentralplayerses.png "Rock Band 3: Buscar Jugadores En AshCentral")

Te vas a conectar a la session donde fuiste invitado.

![Captura de pantalla de Rock Band 3, en un cuarto en linea.](https://raw.githubusercontent.com/hmxmilohax/rb3-pc/main/assets/images/ash/joinlobbyes.png "Rock Band 3: Buscando jugadores en AshCentral...")

Acuérdate, necesitas que presionar "Play on AshCentral" en Rock Band 3 antes de que te unas o creas una sesiona en GoCentral.Rocks.