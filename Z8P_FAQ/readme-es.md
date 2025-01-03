## <a id="choose-language">:globe_with_meridians: Elige idioma</a>
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

----
# Solución de problemas de Z8P

-----
## Referencia
Para encontrar y resolver problemas del producto, puede que necesites utilizar la función de prueba automática, abrir el caja de control para verificar los cables o ajustar la corriente del motor, usar una "prueba de intercambio" para verificar un componente electrónico, etc.. Aquí enlistamos estas guías, imágenes y tutoriales de video para tu referencia.
### Cableado
- [:art: Cómo abrir el caja de control](./pic/OpenControlBox.png)
- [:art: Cableado en el tablero de control](./pic/Z8P_wiring.png)

### Prueba automática de componentes electrónicos
El Z8P tiene un programa de prueba automática de componentes electrónicos incorporado. Puedes utilizar este programa para determinar de dónde viene el problema cuando cualquier componente electrónico tiene un problema. Para iniciar este programa, necesitas abrir el menú "**Info**" y girar el botón para apuntar al ítem "**Fecha: xx-xx-xx**", y luego presionar el botón cinco veces.
#### Video tutorial
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### Acerca de la "prueba de intercambio"
Cuando encontramos que hay un problema funcional en la máquina, y la causa del problema tiene múltiples posibilidades (múltiples partes pueden causar el mismo problema), tenemos la oportunidad de usar la llamada "**prueba de intercambio**" para localizar la causa del problema lo antes posible.
Por ejemplo, si el motor del eje Z izquierdo no funciona, el problema puede venir del cableado, motor paso a paso, cable del motor, el módulo de conducción del motor en el tablero de control o el tablero de control. Debido a que hay dos conjuntos de sistemas de conducción del eje Z en la máquina - sistema de conducción del eje Z izquierdo y derecho - que son idénticos, podemos intercambiar las mismas partes/componentes/ cables en los lados izquierdo y derecho uno por uno para confirmar de dónde viene el problema.
Las partes en la máquina que pueden realizar la prueba de intercambio incluyen:
- Motor X/Y y interruptor de límite.
- Motor ZL/ZR y interruptor de límite
- 4 conjuntos de motores extrusores
- Calentador de cartucho y sensor de temperatura de la cama caliente y el extremo caliente.

-----
## Contenidos
- **[La máquina no se puede encender](./Issue_of_startup/readme.md)**
- **[Problema de homing](./Issue_of_Homing/readme.md)**
- **[Problema de calentamiento](./Issue_heating/readme.md)**
- **[Apagar automáticamente al imprimir desde tarjeta SD](./Issue_auto_shut_down/readme.md)**
- **[Cómo arreglar el bloqueo del extrusor/extremidad caliente](./Issue_extruder_blocked/readme.md)**
- **[Cómo arreglar el problema de descarga insuficiente del extrusor](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Choque al conectar USB en Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[La impresora se detiene automáticamente al imprimir desde tarjeta SD](./Issue_auto_pause/readme.md)**
- **[Problema de no leer tarjeta SD](./Issue_not_read_sdcard/readme.md)**
- **[Problema del botón del pantalla LCD](#dwinscreen)**

----
## Otras referencias
- **[44 problemas comunes de impresión 3D](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[Todavía problemas y soluciones (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">Problema del botón del pantalla LCD</a>
Si encuentras que el botón del pantalla LCD está atascado, puedes hacer clic en [:gift: este enlace](https://www.aliexpress.com/item/3256805596235491.html) para comprar un reemplazo del teclado. Si tu producto está dentro del período de garantía (dentro de los 12 meses a partir de la fecha de recepción del paquete), por favor contactanos después de realizar el pedido y te proporcionaremos servicio post-venta.
Cómo reemplazar el teclado del pantalla LCD, por favor mira el video tutorial:
- Para la versión de soldadura (más antigua), por favor consulta [:clapper: este video](https://youtu.be/Xwfczp3nLOY).   
- Para la versión FPC (más nueva), por favor consulta [:clapper: este video](https://youtu.be/z9E6glRZRIQ).  
####
![](./pic/keypad.jpg)

-----
## :email: Si no puedes encontrar una solución para tu problema después de leer las preguntas frecuentes, por favor contacta a nuestro equipo de soporte técnico : support@zonestar3d.com .
