## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](./readme.md)
[![](./lanpic/ES.png)](./readme-es.md)
[![](./lanpic/PT.png)](./readme-pt.md)
[![](./lanpic/FR.png)](./readme-fr.md)
[![](./lanpic/DE.png)](./readme-de.md)
[![](./lanpic/IT.png)](./readme-it.md)
[![](./lanpic/RU.png)](./readme-ru.md)
[![](./lanpic/JP.png)](./readme-jp.md)
[![](./lanpic/KR.png)](./readme-kr.md)
<!-- [![](./lanpic/SA.png)](./readme-ar.md) -->

------
# Z8P-Mk2 Guía del usuario 
## :warning: ATENCIÓN POR FAVOR
### :loudspeaker: antes de usar la máquina, lea [:book:"Precauciones para usar M4V6"](https://github.com/ZONESTAR3D/Upgrade-kit-guide/blob/main/HOTEND/M4/M4_V6/M4V6_Precaution.md) cuidadosamente.
### :loudspeaker: Debe cargar 4 filamentos en el hotend M4V6 simultáneamente, el funcionamiento incorrecto puede bloquear el hotend de mezcla de colores. Si el bloqueo del extremo caliente es causado por una operación incorrecta, no está cubierto por la garantía. Para saber cómo cargar filamentos, consulte [:book: esta guía](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filaments).
### :loudspeaker: Si es principiante en el uso de impresoras 3D, lea atentamente el [:book: Guía paso a paso][step_by_step_guide] y siga la guía para hacerlo paso a paso. Si tiene experiencia con impresoras 3D, lea también brevemente el [:book: Guía paso a paso][step_by_step_guide] al menos y asegúrese de saber cómo cargar el filamento en el extremo caliente M4.

### [:clapper: Ver video tutorial](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)
Creamos muchos tutoriales en vídeo para esta máquina, haga clic en [:clapper:**aquí**](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial) para verlos.

### :file_folder: [1.Guía de instalación][INSTALLATION]
- **[:book: Guía de instalación][INSTALLATION]**
- **[:blue_book: Archivo PDF de la Guía de instalación y uso rápido](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/Z8PMK2_Installation_and_quick_use_guide.pdf)**
- **[:clapper: Videotutorial de instalación](https://youtu.be/-oieO7U0LCc)**
- **[:book: descripción del menú de la pantalla LCD][LCD_MENU]**
- **[:art: Bloque de cableado](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PMK2_Wiring_Block.jpg)**
- **[:art: Diagrama de cableado](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PM4-MK2_Wiring_Diagram.jpg)**

### :file_folder: [2.Guía de operación][Operation_Guide]
- **[:book: Guía de funcionamiento básico][Operation_Guide]**
- **[:book: Guía del usuario del hotend M4V6 Mix Color][M4V6_Guide]**
- **Funciones avanzadas**
   - **[Apagado automático :book:][auto_shutdown] [:clapper:](https://youtu.be/SJLpmJL-tG4)**
   - **[Impresión de mezcla de colores :book:][mix_color]**
   - **[Nivelación automática de la cama :book:][auto_leveling] [:clapper:](https://youtu.be/Zoyl6PybsUk)**
   - **[Recuperación de pérdida de energía :clapper:](https://youtu.be/f-PpasByiiE)**
   - **[Retracción automática :book:][Auto_Retraction]**
- **[:book: Imprimir desde PC][PrintFromPC]**
  
### :file_folder: [3.Imprimir archivos de prueba Gcode][Test_gcode]
#### :arrow_down: [Descargar archivo gcode de prueba][Test_gcode]
#### :pencil: ¿Qué es el código G en la impresión 3D?
El código G es información o instrucciones que la impresora 3D requiere para imprimir un objeto tridimensional, es el lenguaje que la impresora 3D puede entender. El código G lo genera su software de corte, traduciendo un archivo de modelado 3D estándar, como un archivo STL, al código que su impresora 3D específica comprenderá.
:page_with_curl: [**Referencia 1**](https://beginner3dprinting.com/what-is-g-code-in-3d-printing/) :page_with_curl: [**Referencia 2**](https:/ /www.reprap.org/wiki/G-code)

### :file_folder: [4.Guía de corte][Slicing_Guide_Z8P]
#### :arrow_down: [Descargue el software silcer y lea la guía de corte][Slicing_Guide_Z8P]
#### :pencil: ¿Qué es el corte en impresión 3D?
Slicing es un software que todo el mundo utiliza al crear objetos y productos en una impresora 3D. El software le da a la impresora un camino a seguir. El software de corte toma su imagen y la convierte en códigos G que su impresora 3D puede entender. Estos códigos G son un tipo de instrucción sobre cómo la impresora necesita imprimir su diseño.:page_with_curl: [**Referencia 1**](https://loveandrobots.com/what-is-slicing-in-3d-printing/ ) :page_with_curl: [**Referencia 2**](https://en.wikipedia.org/wiki/Slicer_(3D_printing))

### :file_folder: [5. Imprimir piezas stl][PrintParts]
#### :arrow_down: [Descargar archivos stl de piezas de impresión][PrintParts]

### :link: [6.Firmware](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2)
- **[:arrow_down: archivo bin de firmware](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2).**
- **[:arrow_down: Código fuente del firmware](https://github.com/ZONESTAR3D/source-code-for-3d-printer).**
#### :pencil: ¿Qué es el archivo bin y el código fuente?
> **Archivo bin de firmware** es la memoria exacta que se escribe en la memoria flash integrada.
> **El código fuente del firmware** es la parte central del firmware. Todo el firmware se puede considerar como submódulos diferentes. Está dividido en muchos subarchivos. Estos archivos se denominan archivos fuente. Y todos los archivos del programa se denominan archivo fuente o código fuente. Ahora nuestro código fuente de firmware se basa en [**marlin**](https://www.marlinfw.org).

### 7.Solución de problemas
- :book: [**Solución de problemas para Z8P**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/readme.md)

### Funciones actualizables
- **Etiqueta adhesiva de la base térmica PEI Springs:+1:**     
La pegatina para cama caliente PEI Spring Steel Sheet es más duradera que la pegatina original para cama caliente. Con la cama caliente lisa de un solo lado hacia arriba, también puede hacer que la parte inferior de la impresión sea más suave. **[:gift: Comprar](http://bit.ly/3GbI9Sr) / [:gift: Comprar](https://bit.ly/3VkmXOi)**     
- **Extrusora de doble engranaje:+1:**    
El extrusor de doble engranaje puede aumentar significativamente la fuerza para empujar/tirar del filamento, reduciendo en gran medida la probabilidad de defectos de impresión y fallas de impresión causadas por el deslizamiento del filamento en el extrusor.**[:book: Guía del usuario](https://bit.ly/UM_BMG)** **[:gift: Comprar](https://bit.ly/46Vyd9H) / [:gift: Comprar](https://bit.ly/AE_4xBMG)**
- **pegatina de cama de calentamiento de resorte pei :+1:**       
Las pegatinas de cama caliente de chapa de acero de resorte Pei son más duraderas que las pegatinas de cama caliente originales. La cama caliente lisa de un solo lado se enfrenta hacia arriba, lo que también puede hacer que la parte inferior del estampado sea más suave. **[:gift: compra](http://bit.ly/3GbI9Sr) / [:gift: compra](https://bit.ly/3VkmXOi)**
- **Sensor de filamento agotado :+1:**    
Al actualizar este artículo, podrá controlar de forma remota su impresora 3D. **[:book: Guía del usuario][guide_FROD]** [:gift:Comprar](https://www.aliexpress.com/item/4001309957376.html)
- **Módulo de control inalámbrico WiFi :+1:**    
Al actualizar este artículo, podrá controlar de forma remota su impresora 3D. **[:book: Guía del usuario][guide_WIFI]** [:gift:Comprar](https://www.aliexpress.com/item/1005002378551489.html)
- **Hotend sin mezcla de colores :+1:**
Al actualizar este elemento, el tamaño de la torre de color principal para imprimir modelos multicolores es mucho más pequeño. **[:book: Guía del usuario][guide_E4]** [:gift:Comprar](https://www.aliexpress.com/item/1005002951777699.html)
- **Extrusora de accionamiento directo :+1:**    
Al actualizar este proyecto, podrá imprimir materiales flexibles (como el filamento de TPU). **[:book: Guía del usuario][guide_DDE]** [:gift:Comprar](https://www.aliexpress.com/item/1005002847644867.html)
- **Motor láser**    
Al actualizar este artículo, puede convertir su impresora 3D en una simple máquina de grabado láser. Los módulos láser de mayor potencia pueden mejorar la velocidad de grabado o soportar materiales con un punto de fusión más alto. **[:book: Guía del usuario][guide_Laser]** [:gift:Comprar](https://www.aliexpress.com/item/1005004908160260.html)

-----
[step_by_step_guide]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md
[INSTALLATION]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide
[Operation_Guide]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide
[M4V6_Guide]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/M4%20%204-IN-1-OUT%20Mixing%20Color%20Hotend/M4_V6
[Test_gcode]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode
[Slicing_Guide_Z8P]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide
[PrintParts]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/5-PrintParts/
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[mix_color]: https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color
[auto_leveling]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling
[auto_shutdown]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Shut_Down
[Auto_Retraction]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Retraction
[PrintFromPC]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/PrintFromPC
[guide_FROD]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[guide_WIFI]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[guide_E4]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/E4%204-IN-1-OUT%20Non-Mixing%20Color%20Hotend
[guide_DDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Direct_Drive_Extrruder
[guide_Laser]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Laser_Engraving
