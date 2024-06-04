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
# Probleme mit der Heizung
## Vor der Überprüfung
1. Stellen Sie sicher, dass die Raumtemperatur über 15℃ liegt.
2. Wenn das heiße Bett oder das heiße Ende (Düse) noch heiß ist, warten Sie, bis es abgekühlt ist.
3. Schalten Sie das Gerät ein und beobachten Sie die „Statusleiste“ auf dem LCD-Display.
##### ![](./LCD_screen.jpg)
>
     1: Hot-End-Temperatur 2: Hot-Bed-Temperatur
Normalerweise sollte die angezeigte Temperatur des heißen Endes und des heißen Betts ungefähr der Raumtemperatur entsprechen.
Wenn die aktuelle Raumtemperatur unter 15 °C liegt, aber sowohl die aktuelle Temperatur des heißen Endes als auch des heißen Betts 0 °C anzeigt, überprüfen Sie zuerst die Firmware-Version.

## Inhalt
- **[Hot-End-Problem](#a)**
   - **[Heißes Ende zeigt immer 0℃ an](#a1)**
   - **[Heißes Ende zeigt immer rund 100℃ an](#a2)**
   - **[Temperatur am heißen Ende steigt nicht](#a3)**
   - **[Heißes Ende kann nicht auf die eingestellte Temperatur erhitzt werden](#14)**
   - **[Hot-End-Run-Away-Problem](#a5)**
- **[Problem mit heißem Bett](#b)**
   - **[Heißes Bett zeigt immer 0℃](#b1)**
   - **[Problem mit der maximalen Temperatur des heißen Bettes](#b2)**
   - **[Heißbetttemperatur steigt nicht](#b3)**
   - **[Heißes Bett kann auf über 100℃ erhitzt werden](#b4)**

-----
## <a id="a">Hot-End-Problem</a>
### <a id="a1">Heißes Ende zeigt immer 0 °C an</a>
##### ![](hotend_min_temperature.jpg)
Wenn die aktuelle Temperatur des Hotends 0 Grad anzeigt, kann das zwei Gründe haben:
1. Überprüfen Sie, ob das Temperatursensorkabel des heißen Endes richtig angeschlossen ist.
2. Wenn sowohl der Strom des Hotends als auch des Heizbetts 0 Grad anzeigt und die aktuelle Umgebungstemperatur unter 20 °C liegt, versuchen Sie bitte, die neueste Firmware hochzuladen, und versuchen Sie es erneut.     
:pushpin: **TIPP**: Z8PM4Pro-MK2 und Z8PM4Pro-MK2A verwenden unterschiedliche Versionen von Motherboards. Wenn Ihre aktualisierte Firmware nicht mit der Version des Motherboards übereinstimmt, kommt es zu erheblichen Fehlern in den Ergebnissen der Temperaturmessung.

### <a id="a2">Heißes Ende zeigt immer etwa 100 °C an </a>
Wenn die Temperatur des heißen Endes immer eine hohe Temperatur anzeigt (ca. 100℃), die Düse aber in Wirklichkeit kalt ist, dann ist es sehr wahrscheinlich, dass Sie versehentlich den Temperatursensor des heißen Endes an den Lüfter angeschlossen haben, bitte achten Sie darauf um die Verkabelung des Hotends zu überprüfen.
- **Überprüfen Sie bei Z8P-MK2 den Verlängerungsdraht des heißen Endes**
##### ![](./Hotend_wiring.jpg)
- **Überprüfen Sie die Steuerplatinenseite**
##### ![](../pic/Z8P_wiring.png)

### <a id="a3">Die Temperatur am heißen Ende steigt nicht </a>
- Überprüfen Sie, ob der Stecker des Heizgeräts richtig angeschlossen ist.
- Messen Sie den Widerstand der Heizung mit einem Multimeter. Der Widerstand sollte etwa 10 Ohm betragen. Wenn nicht, brennt die Heizung.
##### ![](./measure.jpg)
- Öffnen Sie den Steuerkasten und prüfen Sie, ob das Heizkabel richtig mit der Steuerplatine verbunden ist.
##### ![](./WireOfheater.jpg)
- [:link: Öffnen Sie die Steuerbox](../How_to_open_the_control_box.jpg) und prüfen Sie, ob die LED4 beim Erhitzen des Hotends aufleuchtet.
##### <a id="led"> ![](LEDs.jpg) </a>

### <a id="a4">Heißes Ende kann nicht auf die eingestellte Temperatur erhitzt werden </a>
Wenn die Hotend-Temperatur erhöht wird, die eingestellte Temperatur jedoch nicht erreicht werden kann. Auf dem LCD wird nach einer gewissen Zeit **Hot-End-Heizungsfehler** angezeigt.
##### ![](./hotend_heating_fail.jpg)
- **Wenn das Hotend nicht auf mehr als 150 °C erhitzt werden kann:** Überprüfen Sie den Temperatursensor an der Seite des Hotends. Möglicherweise ist er aus dem Wärmeblock herausgefallen. ***In diesem Fall wird das heiße Ende normalerweise nicht auf mehr als 150℃ erhitzt.***
<!-- ![](sensorhotenddrop.jpg) -->
- **Wenn das Hot-End auf mehr als 220 °C erhitzt werden kann, aber instabil ist**, lesen Sie bitte den [nächsten Schritt](#a5)

### <a id="a5">Hot-End-Run-Away-Problem </a>
Die Temperatur des heißen Endes ist instabil und zeigt manchmal ein „Durchgehen“-Problem.
##### ![](./runaway.jpg)
- Überprüfen Sie die Installation des Kühlventilators. Wenn er von innen in das Gehäuse geblasen wird, wechseln Sie bitte zu einem von außen geblasenen Lüfter.
##### ![](./coolingfan.jpg)
- Führen Sie einmal „Kontrolle>>Standardeinstellungen wiederherstellen***“ aus und erhitzen Sie dann erneut.
#### Automatische PID-Abstimmung
Wenn Sie die beiden oben genannten Schritte ausgeführt haben, die Frage jedoch nicht gelöst werden kann, führen Sie die folgenden Schritte aus: ***Steuerung>>Konfigurieren>>Hotend-PID>>PID-Auto-Tune: 200 {200 für den Druck von PLA oder 240 für den Druck von PETG/ ABS}*** und warten Sie, bis es fertig ist. [:movie_camera: **Video-Tutorial**](./PID_Auto_Tune.gif).

-----
## <a id="b">Problem mit heißem Bett </a>
### <a id="b1">Heißes Bett zeigt immer 0 °C an </a>
##### ![](hotbed_min_temperature.jpg) ![](./Hotbed_wiring.jpg)
Wenn die aktuelle Temperatur des heißen Bettes 0 Grad anzeigt, kann das zwei Gründe haben:
1. Überprüfen Sie, ob das Temperatursensorkabel des heißen Betts richtig angeschlossen ist.
2. Wenn sowohl der Strom des Hotends als auch des Heizbetts 0 Grad anzeigt und die aktuelle Umgebungstemperatur unter 20 °C liegt, versuchen Sie bitte, die neueste Firmware hochzuladen, und versuchen Sie es erneut.

### <a id="b2">Problem mit der maximalen Temperatur des heißen Bettes </a>
Wenn Sie feststellen, dass auf dem LCD-Bildschirm der Bildschirm „HEIZBETT-Fehler: maximale Temperatur“ angezeigt wird.
##### ![](./hotbed_max_temperature.jpg)
- Trennen Sie das Kabel des Heißbett-Temperatursensors und schalten Sie die Maschine aus und wieder ein. Wenn dieser Bildschirm nicht mehr angezeigt wird, ersetzen Sie einen neuen Temperatursensor.
- Öffnen Sie den Steuerkasten und trennen Sie das Kabel des Temperatursensors von der Steuerplatine. Schalten Sie dann die Maschine aus und wieder ein. Wenn das Problem behoben ist, ersetzen Sie einen neuen Temperatursensor. Wenn das Problem weiterhin besteht, ersetzen Sie die Steuerplatine durch eine neue.

### <a id="b3">Heißbetttemperatur steigt nicht </a>
- Überprüfen Sie, ob [:point_up: das Stromkabel des heißen Bettes](#b1) richtig angeschlossen ist.
- Öffnen Sie den Steuerkasten([:point_right:Picture](../pic/OpenControlBox.png)) und prüfen Sie, ob das Stromkabel des Heizbetts gut mit der Steuerplatine verbunden ist.
![](./heatbed_power.jpg)
- Öffnen Sie den Steuerkasten und prüfen Sie, ob die [:point_up: LED3](#led) beim Erhitzen des Heizbetts aufleuchtet. Wenn nicht, bedeutet dies, dass der MOSFET der Steuerplatine beschädigt ist und ersetzt werden muss.

### <a id="b4">Das heiße Bett kann auf über 100 ℃ erhitzt werden </a>
- Richten Sie den Ventilator oder den Auslass der Klimaanlage nicht auf die Maschine.
- Wenn die Raumtemperatur niedrig ist (<15℃), versuchen Sie, die Maschine einzuwickeln.

--------
## Kontaktieren Sie unser Support-Team
:email: Wenn Sie nach dem Lesen der FAQ keine Lösung für Ihr Problem finden, wenden Sie sich bitte an unser technisches Support-Team: support@zonestar3d.com.