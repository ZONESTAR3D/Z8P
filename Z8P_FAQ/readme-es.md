## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-kr.md)
[![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-ar.md)

-----
# Z8P Solución de problemas

-----
## Referencia
Para encontrar y resolver el problema del producto, es posible que necesite utilizar la función de prueba automática, abrir la caja de control para comprobar el cableado o ajustar la corriente del variador del mortor, utilizar una "prueba de intercambio" para comprobar un componente electrónico, etc. .. Aquí enumeramos estas guías, imágenes y videos tutoriales para su referencia.
### Alambrado
- [:art: Cómo abrir el cuadro de control](./pic/OpenControlBox.png)
- [:art: Cableado en el tablero de control](./pic/Z8P_wiring.png)

### Pruebas automáticas de piezas electrónicas
Z8P tiene incorporado un programa de prueba automática de electrónica. Puede utilizar este programa para determinar de dónde viene el problema cuando cualquier componente electrónico encuentra un problema. Para iniciar este programa, debe abrir el menú "**Info**" y girar la perilla para señalar el elemento "**Fecha: xx-xx-xx**" y luego presionar la perilla cinco veces.
#### Vídeotutorial
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)


### Acerca de la "prueba de intercambio"
Cuando encontramos que hay un problema funcional en la máquina y la causa del problema tiene múltiples posibilidades (varias partes pueden causar el mismo problema), tenemos la oportunidad de utilizar la llamada "**prueba de intercambio** " para localizar la causa del problema lo antes posible.
Por ejemplo, si el motor del eje Z izquierdo no funciona, el problema puede provenir del cableado, del motor paso a paso, del cable del motor, del módulo de accionamiento del motor en el tablero de control o del tablero de control. Debido a que hay dos conjuntos de sistemas de transmisión del eje Z en la máquina (sistemas de transmisión Z izquierdo y sistema de transmisión Z derecho) que son idénticos, podemos intercambiar las mismas piezas/componentes/cables en los lados izquierdo y derecho uno por uno para confirmar. de donde viene el problema.
Las piezas de la máquina que pueden realizar la prueba de intercambio incluyen:
- Motor X/Y y final de carrera.
- Motor ZL/ZR y final de carrera
- 4 juegos de motores de extrusora
- Calentador de cartucho y sensor de temperatura de cama caliente y hot end.

-----
## Contenidos
- **[La máquina no puede iniciarse](./Issue_of_startup/readme.md)**
- **[El extremo caliente está bloqueado/obstruido](./Issue_mix_color_hotend_clogged/readme.md)**
- **[Problema de calefacción](./Issue_heating/readme.md)**
- **[Apagado automático al imprimir desde una tarjeta SD](./Issue_auto_shut_down/readme.md)**
- **[Cómo solucionar el problema del bloqueo del extrusor](./Issue_extruder_blocked/readme.md)**
- **[Cómo solucionar el problema de descarga insuficiente del extrusor](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Falla al conectar USB en Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[La impresora se pausa automáticamente al imprimir desde una tarjeta SD](./Issue_auto_pause/readme.md)**
- **[Problema de tarjeta SD no leída](./Issue_not_read_sdcard/readme.md)**
- **[Problema con la perilla de la pantalla LCD](#dwinscreen)**

----
## Otras referencias
- **[44 problemas comunes de impresión 3D](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[Todos los problemas y soluciones (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">Problema con la perilla de la pantalla LCD</a>
Si descubre que la perilla de la pantalla LCD está atascada, puede hacer clic en [:gift: este enlace](https://www.aliexpress.com/item/3256805596235491.html) para comprar un teclado de repuesto. Si su producto se encuentra dentro del período de garantía (dentro de los 12 meses a partir de la fecha de recepción del paquete), comuníquese con nosotros después de realizar el pedido y le brindaremos el servicio posventa.
Cómo reemplazar el teclado de la pantalla LCD, mire el video tutorial:
- Para la versión de soldadura (anterior), consulte [:clapper: este video](https://youtu.be/Xwfczp3nLOY).
- Para la versión FPC (más reciente), consulte [:clapper: este video](https://youtu.be/z9E6glRZRIQ).
####
![](./pic/keypad.jpg)

-----
## :email: Si no puede encontrar una solución para resolver su problema después de leer las preguntas frecuentes, comuníquese con nuestro equipo de soporte técnico: support@zonestar3d.com.


