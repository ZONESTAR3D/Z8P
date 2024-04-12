## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![]( /EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme.md)
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
# Z8P-Fehlerbehebung

-----
## Referenz
Um das Problem des Produkts zu finden und zu lösen, müssen Sie möglicherweise die automatische Testfunktion verwenden, den Steuerkasten öffnen, um die Verkabelung zu überprüfen oder den Motorantriebsstrom abzustimmen, einen „Austauschtest“ verwenden, um eine elektronische Komponente zu überprüfen usw .. Hier listen wir diese Anleitungen, Bilder und Video-Tutorials als Referenz auf.
### Verkabelung
- [:art: So öffnen Sie die Kontrollbox](./pic/OpenControlBox.png)
- [:art: Verkabelung auf der Steuerplatine](./pic/Z8P_wiring.png)

### Autotest von Elektronikteilen
Z8P verfügt über ein integriertes automatisches Testprogramm für die Elektronik. Mit diesem Programm können Sie feststellen, woher das Problem kommt, wenn bei einer elektronischen Komponente ein Problem auftritt. Um dieses Programm zu starten, müssen Sie das Menü „**Info**“ öffnen und den Knopf drehen, um auf den Eintrag „**Datum: xx-xx-xx**“ zu zeigen, und dann den Knopf fünfmal drücken.
#### Videoanleitung
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### Über „Swap-Test“
Wenn wir feststellen, dass ein Funktionsproblem in der Maschine vorliegt und die Ursache des Problems mehrere Möglichkeiten hat (mehrere Teile können das gleiche Problem verursachen), haben wir die Möglichkeit, den sogenannten „**Swap-Test**“ zu verwenden. „um die Ursache des Problems so schnell wie möglich zu lokalisieren.
Wenn beispielsweise der linke Z-Achsen-Motor nicht funktioniert, kann das Problem an der Verkabelung, dem Schrittmotor, dem Motorkabel, dem Motorantriebsmodul auf der Steuerplatine oder der Steuerplatine liegen. Da es in der Maschine zwei Sätze von Z-Achsen-Antriebssystemen gibt – das linke Z-Antriebssystem und das rechte Z-Antriebssystem –, die identisch sind, können wir zur Bestätigung die gleichen Teile/Komponenten/Drähte auf der linken und rechten Seite einzeln austauschen woher das Problem kommt.
Zu den Teilen der Maschine, die den Austauschtest durchführen können, gehören:
- X/Y-Motor und Endschalter.
- ZL/ZR-Motor und Endschalter
- 4 Sätze Extrudermotoren
- Heizpatrone und Temperatursensor für Heißbett und Heißende.

-----
## Inhalt
- **[Die Maschine kann nicht gestartet werden](./Issue_of_startup/readme.md)**
- **[Heißes Ende ist blockiert/verstopft](./Issue_mix_color_hotend_clogged/readme.md)**
- **[Heizungsproblem](./Issue_heating/readme.md)**
- **[Automatisches Herunterfahren beim Drucken von der SD-Karte](./Issue_auto_shut_down/readme.md)**
- **[So beheben Sie das Extruder-Blockproblem](./Issue_extruder_blocked/readme.md)**
- **[So beheben Sie das Problem mit der unzureichenden Entladung des Extruders](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Absturz beim Anschließen von USB in Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[Die automatische Pause des Druckers beim Drucken von der SD-Karte](./Issue_auto_pause/readme.md)**
- **[Problem mit nicht gelesener SD-Karte](./Issue_not_read_sdcard/readme.md)**
- **[Problem mit dem LCD-Bildschirmknopf](#dwinscreen)**

----
## Andere Referenzen
- **[44 häufige 3D-Druckprobleme](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[Alle Probleme und Lösungen (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">Problem mit dem LCD-Bildschirmknopf</a>
Wenn Sie feststellen, dass der Knopf des LCD-Bildschirms festsitzt, können Sie auf [:Geschenk: diesen Link](https://www.aliexpress.com/item/3256805596235491.html) klicken, um eine Ersatztastatur zu erwerben. Wenn sich Ihr Produkt innerhalb der Garantiezeit befindet (innerhalb von 12 Monaten ab Erhalt des Pakets), kontaktieren Sie uns bitte nach der Bestellung und wir bieten Ihnen einen Kundendienst.
Wie Sie die Tastatur des LCD-Bildschirms austauschen, sehen Sie sich bitte das Video-Tutorial an:
- Die Schweißversion (älter) finden Sie in [:clapper: diesem Video](https://youtu.be/Xwfczp3nLOY).
- Informationen zur FPC-Version (neuer) finden Sie in [:clapper: diesem Video](https://youtu.be/z9E6glRZRIQ).
####
![](./pic/keypad.jpg)

-----
## :email: Wenn Sie nach dem Lesen der FAQ keine Lösung für Ihr Problem finden, wenden Sie sich bitte an unser technisches Support-Team: support@zonestar3d.com.