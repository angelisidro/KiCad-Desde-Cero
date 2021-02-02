![](/img/back.png)

# ¿Donde descargar KiCad?

Usted puede descargar KiCad desde la pagina oficial de KiCad, recuerde que es una herramienta EDA Open Source.

[Descargue KiCad aquí][KiCad_Link]

[KiCad_Link]: https://kicad.org/download/

Esta guia fue realizada para el sistema operativo Windows 10, si usted utiliza otro sistema operativo puede sufrir algunos cambios en algunos comandos utilizados mas adelante.

Para la descarga debemos seguir los siguientes pasos:

1. Seleccionar nuestro sistema operativo, en este caso ***Windows***.
2. Encontraremos información de nuestra descarga, debemos seleccionar una versión correspondiente al sistema operativo que tenemos instalado en nuestra computadora, en mi caso utilizare la versión ***64-bit***->***CERN - Switzerland***.
	- Cuando nuestra descarga este lista, vamos a instalar nuestro software.
	- Procedemos a realizar todos los pasos necesarios para instalar, seleccionando la carpeta donde se realizara la instalación entre otros pasos a seleccionar.
3. Necesitaremos aproximadamente 5.8GB de espacio libre para nuestra instalación.
4. Cuando el asistente de instalación este listo, podemos proceder a utilizar nuestra herramienta.

# Bienvenidos a KiCad

Abriremos nuestra herramienta y esta nos generara una ventana como esta

![](/img/kicadInicio.PNG)

Importante en esta ventana encontraremos todas las opciones que tendremos habilitadas mientras trabajamos un proyecto.

## Creando un proyecto

Lo primero que debemos hacer es crear un proyecto, en el encontraremos todos los archivos necesarios para realizar una PCB (Printed Circuit Board).

Para iniciar debemos seguir los siguientes pasos: 

1. ***File*** -> ***New*** -> ***Project***.
	-	También podemos utilizar el shortcut ***CTRL + N***.

2.  Luego nos desplegara una nueva ventana en la cual nosotros seleccionaremos la carpeta en la cual queremos almacenar nuestro proyecto, en esa carpeta encontraremos archivos como esquematicos, librerias de proyecto y archivos para PCB, entre otros esto se encontrara en la esquina sueperior izquierda.

3.	Al crear el proyecto automaticamente se nos crean dos archivos:
	-	***nombre.kicad_pcb***
	-	***nombre.sch***<br/>


![](/img/img1.PNG)

## Circuito Esquemático

Como sabemos un circuito esquemático es una representación pictografica de los dispositivos que conforman un diseño de dispositivos, generalmente los diseñadores de hardware e ingenieros entienden este tipo de representación. 

Nosotros vamos a seleccionar en nuestro proyecto la siguiente opción ***nombre.sch***, vamos a ver que se genera una nueva ventana que luce así

![](/img/img2.PNG)

Dentro de esta hoja nosotros colocaremos nuestro circuito esquemático, pero antes nosotros iremos a colocar algunos datos con información nuestra y del diseño que estamos realizando, para ello seguiremos los siguientes pasos:

1.	***File***->***Page Settings***.
2.	Seleccionamos en la opción ***Size*** -> ***USLetter 8.5x11in*** esto hace referencia a una hoja tamaño carta en Guatemala.
3.	Seleccionamos en la opción ***Orientation*** -> ***Landscape***.
4.	Finalmente llenaremos algunos campos con nuestros datos y datos del diseño que estaremos realizando.

![](/img/img3.PNG)

5. Notaremos que el resultado de llenar los campos anteriores sera el siguiente, con esto nosotros ya tendriamos identificado lo que es nuestro diagrama esquemático.<br/>

![](/img/img4.PNG)

### Nuestro circuito oscilador

Estaremos trabajando un circuito oscilador realizado con transistores, resistores, capacitores y Led's. Sera un circuito completamente sensillo el cual nos permitira adquirir las habilidades necesarias para poder hacer nuestra primera PCB en KiCad.

![](/img/esquematico.PNG)

### Agregando simbolos al esquemático 

Para agregar simbolos esquemáticos utilizaremos la herramienta ***Place Symbol*** , con ello nos mostrara todos los simbolos esquemáticos que tenemos disponibles para implementar en nuestro proyecto.
![](/img/cSymbol1.PNG)

![](/img/cSymbol.PNG)

Con esto nosotros colocaremos todos los simbolos que aparecen en el circuito proporcionado y estaremos listos para hacer las conexiones correspondientes al mismo. Para interconectar todos los simbolos esquemáticos nosotros utilizaremos la herramienta ***Place Wire*** luce así ![](/img/wire.PNG), nosotros también podemos utilizar lo que son ***Label*** para evitarnos el que nuestro diagrama esquemático se vea muy saturado o lleno de lineas ![](/img/label.PNG) a continuación podemos ver como luce una etiqueta en nuestro diagrama ![](/img/eLabel.PNG)