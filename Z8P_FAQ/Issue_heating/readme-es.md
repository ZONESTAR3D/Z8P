## <a id="choose-language">:globe_with_meridians: Choose language</a>
[![](../lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme.md)
[![](../lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-es.md)
[![](../lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-pt.md)
[![](../lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-fr.md)
[![](../lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-de.md)
[![](../lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-it.md)
[![](../lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-ru.md)
[![](../lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-jp.md)
[![](../lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-kr.md)
[![](../lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-ar.md)

-----
# Problemas de calefacción
## Antes de comprobar
1. Asegúrese de que la temperatura ambiente sea superior a 15 ℃.
2. Si la cama caliente o el extremo caliente (boquilla) todavía están calientes, espere a que se enfríen.
3. Encienda la alimentación y observe la "barra de estado" en la pantalla LCD.
##### ![](./LCD_screen.jpg)
>
     1: temperatura del extremo caliente 2: temperatura del punto caliente
Normalmente, la temperatura mostrada del extremo caliente y de la cama caliente debe ser aproximadamente la temperatura ambiente.
Si la temperatura ambiente actual es inferior a 15 ℃ pero la temperatura actual del extremo caliente y de la cama caliente muestra 0 ℃, verifique primero la versión del firmware.

## Contenidos
- **[Problema del extremo caliente](#a)**
   - **[El extremo caliente siempre muestra 0 ℃](#a1)**
   - **[El extremo caliente siempre muestra una ronda de 100 ℃](#a2)**
   - **[La temperatura del extremo caliente no aumenta](#a3)**
   - **[El extremo caliente no se puede calentar a la temperatura establecida](#14)**
   - **[Problema de fuga del extremo caliente](#a5)**
- **[Problema de la cama caliente](#b)**
   - **[La cama caliente siempre muestra 0 ℃](#b1)**
   - **[Problema con la temperatura máxima de la cama caliente](#b2)**
   - **[La temperatura de la cama caliente no aumenta](#b3)**
   - **[La cama caliente se puede calentar a más de 100 ℃](#b4)**

-----
## <a id="a">Problema del extremo caliente</a>
### <a id="a1">El extremo caliente siempre muestra 0 ℃</a>
##### ![](hotend_min_temperature.jpg)
Si la temperatura actual del hot end muestra 0 grados, puede haber dos razones:
1. Verifique que el cable del sensor de temperatura del extremo caliente esté bien conectado.
2. Si tanto la corriente del hotend como la base calefactora muestran 0 grados y la temperatura ambiente actual es inferior a 20 ℃, intente cargar el firmware más reciente e inténtelo nuevamente.      
:pushpin: **PISTA**: Z8PM4Pro-MK2 y Z8PM4Pro-MK2A utilizan diferentes versiones de placas base. Si su firmware actualizado no coincide con la versión de la placa base, habrá errores importantes en los resultados de la medición de temperatura.

### <a id="a2">El extremo caliente siempre muestra una ronda de 100 ℃ </a>
Si la temperatura del extremo caliente siempre muestra una temperatura alta (aproximadamente 100 ℃) pero la boquilla en realidad está fría, entonces es muy probable que haya conectado el sensor de temperatura del extremo caliente al ventilador por error, preste atención. para comprobar el cableado del hot end.
- **Para Z8P-MK2, verifique el cable de extensión del extremo caliente**
##### ![](./Hotend_wiring.jpg)
- **Compruebe el lado del tablero de control**
##### ![](../pic/Z8P_wiring.png)

### <a id="a3">La temperatura del extremo caliente no aumenta </a>
- Comprobar si el conector del calentador está bien enchufado.
- Utilice un multímetro para medir la resistencia del calentador; la resistencia debe ser de unos 10 ohmios. De lo contrario, el calentador se quema.
##### ![](./measure.jpg)
- Abra la caja de control y verifique si el cable del calentador está bien conectado al tablero de control.
##### ![](./WireOfheater.jpg)
- [:link: Abre la caja de control](../How_to_open_the_control_box.jpg) y comprueba si el LED4 se encenderá al calentar el hotend.
##### <a id="led"> ![](LEDs.jpg) </a>

### <a id="a4">El extremo caliente no se puede calentar a la temperatura establecida </a>
Si la temperatura del hotend aumenta, pero no se puede alcanzar la temperatura establecida. La pantalla LCD mostrará **fallo de calentamiento del extremo caliente** después de un período de tiempo.
##### ![](./hotend_heating_fail.jpg)
- **Si el hotend no se puede calentar a más de 150 ℃:** Verifique el sensor de temperatura en el costado del hotend, es posible que se caiga del bloque térmico. ***En este caso, el extremo caliente normalmente no se calentará a más de 150 ℃.***
<!-- ![](sensorhotenddrop.jpg) -->
- **Si el hot end se puede calentar a más de 220 ℃, pero es inestable**, consulte el [siguiente paso](#a5)

### <a id="a5">Problema de fuga del extremo caliente </a>
La temperatura del extremo caliente es inestable, a veces muestra un problema de "fuga".
##### ![](./runaway.jpg)
   - Verifique la instalación del VENTILADOR de enfriamiento, si sopla hacia adentro de la carcasa, cámbielo a soplado hacia afuera.
##### ![](./coolingfan.jpg)
   - Haga una vez ***Control>>Restaurar valores predeterminados"*** y luego vuelva a calentar.
#### Sintonización automática de PID
Si realizó los dos pasos anteriores pero la pregunta no se puede resolver, siga los siguientes pasos: ***Control>>Configre>>Hotend PID>>PID auto tune: 200 {200 para imprimir PLA o 240 para imprimir PETG/ ABS}*** y espere hasta que termine. [:movie_camera: **Videotutorial**](./PID_Auto_Tune.gif).

-----
## <a id="b">Problema de la cama caliente </a>
### <a id="b1">La cama caliente siempre muestra 0 ℃ </a>
##### ![](hotbed_min_temperature.jpg) ![](./Hotbed_wiring.jpg)
Si la temperatura actual de la cama caliente es de 0 grados, puede deberse a dos motivos:
1. Verifique que el cable del sensor de temperatura de la cama caliente esté bien conectado.
2. Si tanto la corriente del hotend como la base calefactora muestran 0 grados y la temperatura ambiente actual es inferior a 20 ℃, intente cargar el firmware más reciente e inténtelo nuevamente.

### <a id="b2">Problema con la temperatura máxima de la cama caliente </a>
Cuando encuentre, la pantalla LCD muestra la pantalla "HEATBED Err.: temperatura máxima".
##### ![](./hotbed_max_temperature.jpg)
- Desconecte el cable del sensor de temperatura del hotbed y apague y encienda la máquina nuevamente, si no vuelve a mostrar esta pantalla, reemplace un nuevo sensor de temperatura.
- Abra la caja de control y desconecte el cable del sensor de temperatura del tablero de control, luego apague y encienda la máquina nuevamente, si se reparó, reemplace un nuevo sensor de temperatura. Si no se solucionó, reemplace un nuevo tablero de control.

### <a id="b3">La temperatura de la cama caliente no aumenta </a>
- Verifique si [:point_up: el cable de alimentación de la cama caliente](#b1) estaba bien conectado.
- Abra la caja de control y verifique ([:point_right:Picture](../pic/OpenControlBox.png)) si el cable de alimentación de la cama caliente se conecta bien con el tablero de control.   
![](./heatbed_power.jpg)
- Abra la caja de control y verifique ([:point_right:Picture](../pic/OpenControlBox.png)) si el [:point_up: LED3](#led) se encenderá al calentar la cama caliente; de lo contrario, significa que el MOSFET de la placa de control está dañado y necesita ser reemplazado.

### <a id="b4">La cama caliente se puede calentar a más de 100 ℃ </a>
- No acerque la salida del ventilador o del aire acondicionado hacia la máquina.
- Si la temperatura de la habitación es baja (<15℃), intente envolver la máquina.

--------
## Contacta con nuestro equipo de soporte
:email: Si no puede encontrar una solución para resolver su problema después de leer las preguntas frecuentes, comuníquese con nuestro equipo de soporte técnico: support@zonestar3d.com.