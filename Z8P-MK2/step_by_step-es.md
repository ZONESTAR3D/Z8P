[USER_GUIDE]: https://downgit.github.io/#/home?url=https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2
[INSTALLATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/readme.md
[INSTALL_VIDEO]: https://youtu.be/-oieO7U0LCc
[IMG_ACSWITCH]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/1-Installation_Guide/pic/selectAC.png
[POWER_ON]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#power-on
[VIDEO_POWER_ON]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/pic/PowerOn.gif
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[LEVEL_BED]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#level-the-bed
[XYZ_CUBE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/xyz_cube.zip
[LOAD_FILAMENT]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments
[M4_4CTEST]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip
[SLICING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md
[AUTOTEST_VIDEO]: https://youtu.be/iSsuy2ePWw8
[ADVANCE_FEATURES]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#advance-features
[Z8P_FAQ]: (https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ)

----
## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-kr.md)
<!-- [![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-ar.md) -->

----
# Guía paso a paso de Z8P-MK2 
Si eres un principiante con las impresoras 3D y tienes tanta documentación para leer, es posible que no sepas por dónde empezar. No se preocupe, entraremos en los detalles de estos documentos a continuación paso a paso.     
En una palabra, lo que debe hacer incluye los siguientes 4 pasos: **Instalar la máquina >> Imprimir el archivo de prueba >> Cortar su propio archivo 3D >> Imprimir su archivo 3D**.     
En primer lugar, te recomendamos que [:arrow_down: **descargues todos los documentos**][USER_GUIDE], los guardes en tu ordenador y añadas esta página web a los favoritos de tu navegador.

## <a id="step1">Paso 1. Instale la máquina y el cableado </a>
- **Instalación**. Consulte el [:book: **guía de instalación**][INSTALLATION_GUIDE] y [:clapper: **videotutorial de instalación**][INSTALL_VIDEO] para instalar la máquina.
- **Alambrado**. El proceso de cableado consiste básicamente en introducir el enchufe en el enchufe correspondiente. Lo que debe prestar atención es asegurarse de que el enchufe esté completamente insertado en el enchufe. Especialmente para esos enchufes de 2PIN que a veces hacen mal contacto.      
:warning: Al cablear el cabezal de impresión (ensamblaje del hotend), consulte atentamente las imágenes de la guía de instalación y preste atención para distinguir tanto el color de los conectores como el color de los cables.

## <a id="step2">Paso 2. Encienda el maiche y haga una prueba y verificación sencillas. </a>
- **Encendido**. Antes de encender la alimentación de CA, verifique si la configuración del interruptor selector de fuente de alimentación de 110V/220V está en la posición correcta ([**consulte esta imagen**][IMG_ACSWITCH]). Y luego podrá [**encender la máquina**][POWER_ON]. :warning: Tenga en cuenta que la máquina tiene 2 interruptores de alimentación, uno es ***interruptor de CA*** (el interruptor rojo en la parte posterior de la caja de control, cerca de la toma de corriente de CA) y otro es ***interruptor de CC ***(un interruptor de botón redondo de metal en el lado derecho de la caja de control), primero debe encender el interruptor de CA y luego presionar y **mantener presionado el interruptor de CC unos 5 segundos** (suelte hasta que el tornillo LCD muestra el LOGOTIPO de ZONESTAR) para encender la máquina.
- **Simplemente prueba**. Después del encendido, puede operar el menú en la pantalla LCD ([**Descripción del menú LCD**][LCD_MENU]) para verificar si la máquina puede funcionar normalmente, siguiendo los pasos a continuación:
   - **Preparar>>Inicio automático>>Inicio todo**. Este paso es para hacer que el cabezal de impresión de la máquina regrese a la posición original.
   - **Preparar>>Temperatura>>Precalentar PLA**. Este paso es para verificar que el extremo caliente y la cama caliente se puedan calentar normalmente. En este paso, cuando la temperatura de la boquilla supera los 60 grados, debería ver girar un ventilador en el **lado derecho** del cabezal de impresión (extremo caliente), este ventilador se llama "ventilador de enfriamiento del extremo caliente".
   - **Preparar>>Temperatura>>VENTILADOR**. Presione la perilla y ajuste la velocidad del ventilador a 255, el ventilador del **lado izquierdo hacia arriba** debería girar.
     Después de realizar los 3 pasos anteriores, básicamente se determina que la máquina está funcionando normalmente, puede continuar con los siguientes pasos. Si descubre que alguna pieza no funciona correctamente, verifique nuevamente el cableado o realice una "prueba automática de electrónica" para verificar. (consulte[:clapper: **tutorial en vídeo sobre pruebas automáticas de máquinas**][AUTOTEST_VIDEO]).

## <a id="step3">Paso 3. Nivela la cama </a>
[![](https://img.youtube.com/vi/R3RfGnxx8hY/0.jpg)](https://www.youtube.com/watch?v=R3RfGnxx8hY)     
Antes de imprimir el archivo de prueba, debe realizar una simple nivelación de la cama para establecer la altura entre la boquilla y la cama (plataforma de impresión), de modo que el filamento se pueda adherir bien a la cama al imprimir. Consulta [**nivelar la cama**][LEVEL_BED] para hacerlo.

## <a id="step4">Paso 4. Imprimir modelo 3D de prueba </a>
Las impresoras FDM 3D solo pueden reconocer archivos gcode, necesitamos copiar los archivos gcode a la tarjeta SD y luego insertar la tarjeta SD en la ranura para tarjetas SD de la impresora 3D y luego operar la pantalla LCD para comenzar a imprimir.
:warning: Incluso si está familiarizado con las impresoras 3D, se recomienda imprimir al menos un modelo de prueba de 4 colores para confirmar que la máquina funciona normalmente. 
- **4.1 Imprimir un archivo de prueba de un color**     
[![](https://img.youtube.com/vi/ITHbO9VxTMo/0.jpg)](https://www.youtube.com/watch?v=ITHbO9VxTMo)
   - **Preparar archivo gcode**. [:arrow_down: **descargue el archivo zip xyz_cube**][XYZ_CUBE], descomprímalo en la PC y luego copie el **xyz_cube.gcode** a la tarjeta SD. Conecte la tarjeta SD al conector SD de la máquina.
   - **Cargar filamento**. Consulte [:book: **aquí**][LOAD_FILAMENT] para cargar los 4 filamentos en los extrusores y el hot end.
     ***:warning: para el hotend M4V6, debes cargar 4 filamentos en el hotend incluso si imprimes impresiones en 3D de un solo color.***
   - **Imprimir desde tarjeta SD**. Mueva el elemento al elemento **Imprimir** en la pantalla LCD, haga clic en la perilla y elija el archivo **xyz_cube.gcode**, haga clic en la perilla para comenzar a imprimir.
   - **Ajuste la altura de la boquilla**. Espere a que la boquilla y la cama se calienten y observe la distancia desde la boquilla hasta la cama al imprimir la primera capa. Si está demasiado gruesa o demasiado cerca, haga doble clic en la perilla de la pantalla LCD para abrir un menú **"babystep"** y luego gire la perilla para ajustar con precisión la distancia desde la boquilla hasta la cama.
   - **Esperar a que termine la impresión**.
- **4.2 Imprimir un archivo de prueba de 4 colores**    
[![](https://img.youtube.com/vi/CA8pWOuJYmE/0.jpg)](https://www.youtube.com/watch?v=CA8pWOuJYmE)
   - **Preparar archivo gcode**. [:arrow_down: **descargue el archivo zip M4_4CTest**][M4_4CTEST] y descomprímalo en la PC, y luego copie el **M4_4CTest.gcode** a la tarjeta SD. Conecte la tarjeta SD al conector SD de la máquina.
   - **Cargar filamentos**. Consulte [:book: **aquí**][LOAD_FILAMENT] para cargar los 4 filamentos en las extrusoras y el extremo caliente.
   - **Imprimir desde tarjeta SD**. Mueva el elemento al elemento **Imprimir** en la pantalla LCD, haga clic en la perilla y elija el archivo **M4_4CTest.gcode**, haga clic en la perilla para comenzar a imprimir.
   - **Ajuste la altura de la boquilla**. Espere a que la boquilla y la cama se calienten y observe la distancia desde la boquilla hasta la cama al imprimir la primera capa. Si está demasiado gruesa o demasiado cerca, haga doble clic en la perilla de la pantalla LCD para abrir un menú **"babystep"** y luego gire la perilla para ajustar con precisión la distancia desde la boquilla hasta la cama.
   - **Esperar a que termine la impresión**.

## <a id="step5">Paso 5. Cortar tu propio modelo 3D </a>
- Antes de imprimir sus propios modelos 3D, necesita convertir el archivo del modelo 3D (un archivo de formato stl/obj/AMF que [descargó de Internet](#download) o lo dibujó usted mismo) a un archivo gcode, guarde este archivo gcode a la tarjeta SD y luego conecte la tarjeta SD a su impresora 3D.     
   :pushpin: **El proceso de convertir un modelo 3D en un archivo gcode se llama *rebanado***.
- En primer lugar, debe descargar el software de corte e instalarlo en su computadora, y configurar los parámetros de su máquina en el software de corte o cargar el archivo preestablecido de su máquina configurado por el fabricante de la impresora 3D.
- A continuación, debe ejecutar el software de corte y es posible que también deba establecer alguna configuración de corte de acuerdo con las características de su archivo de modelo 3D y luego realizar el corte.     
   :pushpin: El software de corte recomendado es **PrusaSlicer**. Para saber cómo descargarlo, instalarlo y utilizar **PrusaSlicer**, consulte la [***Guía de corte***][SLICING_GUIDE].

## <a id="step6">Paso 6. Imprime tu propio modelo 3D </a>
Después de cortarlo, copie el archivo gcode generado en la tarjeta SD y luego imprímalo siguiendo el [**paso 4**](#step4).

## <a id="step7">Paso 7. Para utilizar funciones avanzadas </a>
Una vez que comprenda completamente todas las operaciones básicas, podrá probar algunas funciones avanzadas de esta máquina.
Para obtener más información, consulte la [**Guía de uso de funciones avanzadas**][ADVANCE_FEATURES].

----
#### <a id="download"> :page_with_curl: sitios web famosos de descarga gratuita de modelos 3D </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   

----