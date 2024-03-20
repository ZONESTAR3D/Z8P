## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](../lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md)
[![](../lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-es.md)
[![](../lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-pt.md)
[![](../lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-fr.md)
[![](../lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-de.md)
[![](../lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-it.md)
[![](../lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-ru.md)
[![](../lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-jp.md)
[![](../lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-kr.md)
<!-- [![](../lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme-ar.md) -->

-----
# Z8P-MK2 Bedienungsanleitung
## Ein- und Ausschalten
#### :warning: ACHTUNG! :warning:
##### STELLEN SIE SICHER, DASS DER AC-SPANNUNGSWAHLSCHALTER AUF DIE RICHTIGE POSITION STEHT!
![](./pic/selectAC.jpg)     
### EIN
#### [:clapper: Video-Tutorial](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/pic/PowerOn.gif)
![](./pic/poweron.png)
1. Netzkabel einstecken
2. Schalten Sie den Netzschalter ein.
3. Halten Sie die Gleichstromtaste etwa 5 Sekunden lang gedrückt
4. Warten Sie, bis auf dem LCD das Logo angezeigt wird, und lassen Sie dann den Gleichstromschalter los
### AUSSCHALTEN
#### [:clapper: Video-Tutorial](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/pic/poweroff.gif)
![](./pic/poweroff.png)
Führen Sie „Vorbereiten>>Ausschalten“ auf dem LCD-Bildschirm aus, warten Sie, bis sich der LCD-Bildschirm ausschaltet, und schalten Sie dann den Netzschalter aus.

## [LCD-Menü und Bedienung][LCD_MENU]
![](./pic/LCDScreen.png)
1. **Titelleiste:** Zeigt das aktuelle Menü an
2. **Menüleiste:** Zeigt steuerbetriebsbezogene Menüelemente an
3. **Statusleiste:** Zeigt den aktuellen wichtigen Status des Druckers an, einschließlich Informationen zu Temperatur, Druckgeschwindigkeit und Z-Höhe
4. **Steuergriff:** Steuern Sie den Drucker. Es handelt sich um eine Walze, die gedreht oder gedrückt werden kann.
   - **Rotation:** Wählen Sie den nächsten/vorherigen Menüpunkt aus oder ändern Sie den Einstellungswert.
   - **Klicken Sie auf:** Rufen Sie das nächste Menü auf / Führen Sie den aktuellen Befehl aus / Bestätigen Sie den geänderten Wert.
5. **Drucken von der SD-Karte:** Wählen Sie die Gcode-Datei von der SD-Karte und drucken Sie sie aus.
6. **Vorbereiten zum Drucken:** Vorheizen, Referenzieren, Bewegen der Achse, Laden/Entladen des Filaments, Nivellieren des Heizbetts, Ausschalten usw. werden vor dem Drucken verwendet.
7. **Maschine einrichten:** Betriebsparameter einstellen, erweiterte Funktionen aktivieren/deaktivieren.
8. **Informationen zur Maschine:**: Zeigen Sie die Firmware-Version und Hardwarekonfigurationsinformationen der Maschine an.
#### Informationen zur LCD-Menübeschreibung finden Sie in der [:point_right:**DWIN-LCD-Bildschirmmenübeschreibung**][LCD_MENU].

## Bereiten Sie den Druck vor
### Richten Sie das Bett aus
Vor dem Drucken müssen Sie den Abstand zwischen der Düse und der Heißbettfolie auf einen geeigneten Wert einstellen, damit das geschmolzene Filament gut auf der Heißbettfolie geklebt werden kann. Dieser Vorgang wird auch „Niveaubett“ genannt. Wenn die Düse zu weit vom Bett entfernt ist, kann das Filament nicht am heißen Bett haften. Wenn der Abstand zu gering ist, werden Bettfolie und Düse beschädigt oder sogar das heiße Ende blockiert.
##### [:clapper: Schritt 1: ](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/pic/HomeAll.gif) Schalten Sie den 3D-Drucker ein und Führen Sie dann „Vorbereiten >> Auto Home >> Home All“ im LCD-MENÜ aus und warten Sie, bis das Hotend in die HOME-Position geht.
##### Schritt 2: Ziehen Sie die Handmuttern unter dem Bett fest, um das Bett in die unterste Position zu bewegen (Abb. 1).
##### [:clapper: Schritt 3:](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/pic/Level_corners.gif) Führen Sie „Bett vorbereiten“ aus Nivellierung>> Punkt 1“ auf dem Bedienfeld (Abb. 2), die Düse geht zu den Ecken des Bettes, lösen Sie die Handmuttern unter dem Brutbett (Abb. 3) und lassen Sie die Düse das Brutbett fast berühren (Abb. 4). Fahren Sie mit „Punkt 2/3/4“ fort, bis alle vier Ecken geebnet sind.
##### Schritt 4: Wiederholen Sie Schritt 3 und machen Sie 2–3 Runden, bis alle vier Ecken auf der gleichen Höhe sind.
![](./pic/levelbed.png)

### Filamente laden
#### [:clapper: Video-Tutorial](https://youtu.be/-47yB95uIxI)
Dieser Drucker ist mit vier Extrudern und einem 4-IN-1-OUT-Farbmisch-Hot-End ausgestattet. Die Extruder und das Hot End sind durch eine Filamentführung (PTFE-Schlauch) verbunden. :warning:**Vor dem Drucken müssen Sie alle 4 Filamente in die Extruder laden und sie unten in das heiße Ende einführen.**
##### Schritt 1. Führen Sie auf dem Bedienfeld „Vorbereiten>>Auto Home>>Home All“ und dann „Vorbereiten>>Temperatur>> PLA vorheizen“ aus und warten Sie, bis die Düsentemperatur 190 °C erreicht hat (Abb. 1).
##### Schritt 2. Schneiden Sie den Kopf des Filaments mit einer Diagonalzange ab (Abb. 2), drücken Sie dann auf den Griff des Extruders Nr. 1 und führen Sie das Filament ein. Drücken Sie das Filament, bis Sie das Filament im PTFE sehen können Anleitung (Abb. 3). Drehen Sie das Zahnrad von Extruder Nr. 1 (Abb. 4) und beobachten Sie das Filament, bis es unten in das heiße Ende gelangt.
##### Schritt 3. Verwenden Sie die gleiche Methode wie in Schritt 2, um die Filamente in Extruder Nr. 2 bis Extruder Nr. 4 zu laden, und beobachten Sie die Filamente, bis sie die Unterseite des heißen Endes erreichen.
##### Schritt 4. Drehen Sie das Zahnrad von Extruder Nr. 1 bis Extruder Nr. 4 langsam nacheinander und beobachten Sie die Düse, bis Sie sehen können, wie das Filament aus der Düse herausfließt (Abb. 5).
#### :warning: Das Menü „Schnelles Laden“ kann nur verwendet werden, wenn das Filament vom Extruder zum heißen Ende geladen wird. Sobald das Filament in das heiße Ende gelangt ist, verwenden Sie das Menü „Langsames Laden“, aber nicht „Schnelles Laden“.
![](./pic/loadfilament.png)

## Von SD-Karte drucken
[:clapper: Video-Tutorial](https://youtu.be/ITHbO9VxTMo)
#### Schritt 1. Stecken Sie die SD-Karte in den SD-Kartensteckplatz am Drucker (Abb. 1).
##### :pushpin: Z8PM4Pro-MK2A hat an der Seite des Geräts einen SD-Kartensteckplatz hinzugefügt, der den Zugriff auf die SD-Karte bequemer macht.
:warning: Bitte beachten Sie, dass Sie beim Drucken nur eine davon auswählen können (SD-Karte an der Seite oder Micro-SD-Karte an der Vorderseite).       
![](./pic/MK2A_SD.jpg)
#### Schritt 2. Klicken Sie auf dem Bedienfeld auf „Drucken“ und wählen Sie „Test gcode\xyz_cube.gcode“ (Abb. 2). Klicken Sie auf den Knopf, um den Druck zu starten.
#### Schritt 3. Warten Sie, bis das Hotend und das Hotbed die eingestellte Temperatur erreicht haben (Abb. 3), die Düse kehrt zur Ursprungsposition zurück und bewegt sich dann über die Druckplattform und extrudiert das Filament mit einer Pinzette Entfernen Sie den Ausflussfaden (Abb. 4).
#### Schritt 4. Wenn sich die Düse zum heißen Bett bewegt hat und mit dem Drucken beginnt, doppelklicken Sie auf den Knopf auf dem Bedienfeld, um das Menü „Kleine Schritte Z“ zu öffnen (Abb. 5). Drehen Sie den Knopf langsam, um die Höhe fein einzustellen Achten Sie bei der Druckplattform auf den Abstand von der Düse zum Bett, bis der Abstand gut passt (Abb. 6). Warten Sie, bis der Druckvorgang abgeschlossen ist. Sie erhalten dann Ihre ersten Arbeiten (Abb. 7).
#### Schritt 5. Warten Sie, bis das Heizbett abgekühlt ist (<= 25 Grad) (Abb. 8) und nehmen Sie dann das gedruckte Objekt vom Heizbett ab (Abb. 9).
![](./pic/firstprint.png)

## Erweiterte Funktionen
:warning: Schalten Sie diese Funktionen erst ein, wenn Sie genau wissen, wie Sie sie verwenden.
### [Funktion zum Mischen von Farben][MIX_COLOR]
Dieser Drucker ist mit 4 Extrudern und einem 4-IN-1-OUT-Mischfarben-Hot-End ausgestattet und kann nicht nur 3D-Dateien mit bis zu 16 Farben drucken, sondern auch im 3D-Modus mit einer einzelnen Farbe ein 3D-Modell mit Farbverlauf drucken. Einzelheiten finden Sie im [**:point_right:Mixing Color Feature User Guide**][MIX_COLOR].

### [Automatische Bettnivellierung][AUTO_LEVELING]
Dieser Drucker ist mit einem Bettnivellierungssensor PL-08N ausgestattet. Mit diesem Sensor können Sie die Unebenheiten des heißen Bettes korrigieren.
Einzelheiten finden Sie im [**:point_right: Benutzerhandbuch zur automatischen Bettnivellierungsfunktion**][AUTO_LEVELING].

### [Automatisches Herunterfahren][AUTO_SHUTDOWN]
#### [:clapper: **Video-Tutorial**](https://youtu.be/SJLpmJL-tG4).
Der 3D-Druck dauert normalerweise lange und Sie befinden sich möglicherweise nicht in der Nähe der Maschine, wenn der Druckvorgang abgeschlossen ist. Sie können den Drucker nach Abschluss des Druckvorgangs automatisch ausschalten lassen, um unnötigen Stromverbrauch zu vermeiden.

### [Wiederherstellung nach Stromausfall](https://youtu.be/f-PpasByiiE)
#### [:clapper: **Video-Tutorial**](https://youtu.be/f-PpasByiiE).
Beim Drucken von der SD-Karte und einem Stromausfall beginnt der Drucker nach dem erneuten Einschalten wieder mit dem Drucken ab der letzten Ebene, die vor dem Stromausfall gedruckt wurde.

### [Automatischer Rückzug][AUTO_RETRACTION]
Das Saitenproblem beim gemischtfarbigen Hotend ist oft schwerwiegender als das beim einfarbigen Hotend. Daher ist in der Firmware eine automatische Rückzugsfunktion eingestellt. Die Verwendung eines automatischen Rückzugs kann dieses Problem verbessern.
Einzelheiten finden Sie im [**:point_right: Benutzerhandbuch für die Funktion zum automatischen Einfahren**][AUTO_RETRACTION].

## Schneiden
Bei der Slicing-Software handelt es sich um eine Computersoftware, die in den meisten 3D-Druckverfahren zur Umwandlung eines 3D-Objektmodells in spezifische Anweisungen für den Drucker verwendet wird. Insbesondere die Konvertierung von einem Modell im STL-Format (Obj, Amf) in Druckerbefehle im G-Code-Format.
Diese Maschine kann eine Vielzahl von Slicing-Software verwenden, um das Slicing abzuschließen. Wir bieten Download-Adressen, Anweisungen und Video-Tutorials für gängige Slicing-Software.
Einzelheiten finden Sie unter [**:point_right: Slicing-Guide**][SLICING_GUIDE_Z8P].
#### :loudspeaker: HINWEIS
1. Slicing-Software ist nicht Teil dieses Geräts. Sie können Slicing-Software kostenlos aus dem Internet herunterladen.
2. Wenn Sie eine Farbe drucken, wählen Sie bitte die Maschine **“Z8 + One color”**. Wenn Sie mehrfarbig drucken, wählen Sie bitte die Maschine **“Z8 + M4 hot end”**.
3. Einige der Benutzerhandbücher und Video-Tutorials beziehen sich auf unsere Maschinen der Z9-Serie und sind vollständig auf Z8PM4 anwendbar.

----
## Steuerung per PC / Drucken vom PC
:warning: Wir empfehlen, von einer SD-Karte statt von einem PC zu drucken.
Wenn Sie beim ZPM4Pro-MK2 der Meinung sind, dass der Zugriff auf die SD-Karte (Einsetzen und Entfernen) schwierig ist, empfehlen wir den Kauf einer Mirco-SD-Kartenverlängerung ([**Verkaufslink**](https://www.aliexpress.com/item/3256805156643681.htm)).      
![](./pic/CardExtender.jpg)     
Wenn Sie vom PC aus drucken möchten, empfehlen wir die Verwendung der Software „Repetier-Host“. Informationen zum Herunterladen und Verwenden von Repetier-Host finden Sie im [**Benutzerhandbuch zum Drucken vom PC**][PRINTFROMPC].

-----
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[MIX_COLOR]: https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color
[AUTO_LEVELING]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling
[AUTO_SHUTDOWN]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Shut_Down
[AUTO_RETRACTION]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Retraction
[SLICING_GUIDE_Z8P]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide
[PRINTFROMPC]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/PrintFromPC

