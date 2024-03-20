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

-----
# Z8P-MK2 Schritt-für-Schritt-Anleitung
Wenn Sie ein Anfänger im Umgang mit 3D-Druckern sind und so viel Dokumentation zu lesen haben, wissen Sie möglicherweise nicht, wo Sie anfangen sollen. Keine Sorge, wir gehen im nächsten Schritt Schritt für Schritt auf die Details dieser Dokumente ein.     
Kurz gesagt, was Sie tun müssen, umfasst die folgenden 4 Schritte: **Installieren Sie die Maschine >> Drucken Sie die Testdatei >> Schneiden Sie Ihre eigene 3D-Datei >> Drucken Sie Ihre 3D-Datei**.     
Zunächst empfehlen wir Ihnen, [:arrow_down: **alle Dokumente herunterzuladen**][USER_GUIDE], sie auf Ihrem Computer zu speichern und diese Webseite zu den Favoriten Ihres Browsers hinzuzufügen.
## Schritt 1. Installieren Sie die Maschine und die Verkabelung
- **Installation**. Informationen zur Installation der Maschine finden Sie im [:book: **Installationshandbuch**][INSTALLATION_GUIDE] und im [ :clapper: **Installationsvideo-Tutorial**][INSTALL_VIDEO].
- **Verkabelung**. Der Verkabelungsprozess besteht im Wesentlichen darin, den Stecker in die entsprechende Steckdose einzustecken. Sie müssen darauf achten, dass der Stecker vollständig in die Steckdose eingesteckt ist. Besonders für die 2PIN-Buchsen, die manchmal einen schlechten Kontakt herstellen. :warning: Wenn Sie den Druckkopf verkabeln (Hotend-Montage), sehen Sie sich bitte sorgfältig die Bilder in der Installationsanleitung an und achten Sie darauf, sowohl die Farbe der Anschlüsse als auch die Farbe der Drähte zu unterscheiden.
## Schritt 2. Schalten Sie die Maiche ein und führen Sie einen einfachen Test und eine Überprüfung durch
- **Ein**. Bevor Sie den Wechselstrom einschalten, prüfen Sie bitte, ob die Einstellung des 110-V-/220-V-Stromversorgungswahlschalters auf die richtige Position eingestellt ist ([**siehe dieses Bild**][IMG_ACSWITCH]). Und dann können Sie [**die Maschine einschalten**][POWER_ON]. :warning: Bitte beachten Sie, dass die Maschine über zwei Netzschalter verfügt, einer ist ein ***AC-Schalter*** (der rote Schalter auf der Rückseite des Steuerkastens, in der Nähe der AC-Steckdose) und der andere ist ein ***DC-Schalter*** (ein runder Druckknopfschalter aus Metall auf der rechten Seite des Steuerkastens), Sie müssen zuerst den Wechselstromschalter einschalten und dann **den Gleichstromschalter etwa 5 Sekunden lang gedrückt halten** (lassen Sie ihn los, bis die LCD-Schraube einrastet ZONESTAR-LOGO anzeigen), um das Gerät einzuschalten.
- **Einfach testen**. Nach dem Einschalten können Sie das Menü auf dem LCD-Bildschirm ([**Beschreibung des LCD-Menüs**][LCD_MENU]) bedienen, um zu überprüfen, ob das Gerät normal funktioniert. Führen Sie dazu die folgenden Schritte aus:
   - **Vorbereiten>>Auto Home>>Home All**. Dieser Schritt dient dazu, den Druckkopf des Geräts in die Ausgangsposition zurückzubringen.
   - **Vorbereiten>>Temperatur>>PLA vorheizen**. In diesem Schritt wird überprüft, ob das heiße Ende normal beheizt werden kann. Wenn in diesem Schritt die Temperatur der Düse 60 Grad übersteigt, sollten Sie sehen, wie sich ein Lüfter auf der **rechten Seite** des Druckkopfs (Hot-End) dreht. Dieser Lüfter wird als „Hot-End-Kühlventilator�?bezeichnet.
   - **Vorbereiten>>Temperatur>>LÜFTER**. Drücken Sie den Knopf und stellen Sie die Lüftergeschwindigkeit auf 255 ein. Der Lüfter auf der **linken Seite oben** sollte sich drehen.
     Nachdem Sie die oben genannten drei Schritte ausgeführt haben und grundsätzlich festgestellt haben, dass die Maschine normal funktioniert, können Sie mit den folgenden Schritten fortfahren. Wenn Sie feststellen, dass ein Teil nicht ordnungsgemäß funktioniert, überprüfen Sie bitte die Verkabelung noch einmal oder führen Sie zur Überprüfung einen „Automatischen Elektroniktest�?durch. (Siehe [ :clapper: **Video-Tutorial zum automatischen Testen von Maschinen**][AUTOTEST_VIDEO]).
## Schritt 3. Richten Sie das Bett aus
Bevor Sie die Testdatei drucken, müssen Sie eine einfache Bettnivellierung durchführen, um die Höhe zwischen der Düse und dem Bett (Druckplattform) einzustellen, damit das Filament beim Drucken gut auf dem Bett haften kann. Bitte lesen Sie hierzu [**das Bett nivellieren**][LEVEL_BED].
## Schritt 4. Test-3D-Modell drucken
FDM-3D-Drucker können nur Gcode-Dateien erkennen. Wir müssen die Gcode-Dateien auf die SD-Karte kopieren, dann die SD-Karte in den SD-Kartensteckplatz des 3D-Druckers einlegen und dann den LCD-Bildschirm bedienen, um mit dem Drucken zu beginnen.
:warning: Auch wenn Sie mit 3D-Druckern vertraut sind, wird empfohlen, mindestens ein 4-Farben-Testmodell zu drucken, um zu bestätigen, dass die Maschine normal funktioniert.
- **4.1 Eine einfarbige Testdatei drucken**
   - **Gcode-Datei vorbereiten**. [:arrow_down: **xyz_cube zip-Datei herunterladen**][XYZ_CUBE] und auf dem PC entpacken und dann den **xyz_cube.gcode** auf die SD-Karte kopieren. Stecken Sie die SD-Karte in den SD-Anschluss des Geräts.
   - **Filament laden**. Siehe [:book: **hier**][LOAD_FILAMENT], um alle 4 Filamente in die Extruder und das heiße Ende zu laden.
     ***:warning: Für das M4V6-Hotend müssen Sie 4 Filamente in das Hotend laden, auch wenn Sie einfarbige 3D-Drucke drucken.***
   - **Drucken von SD-Karte**. Bewegen Sie das Element auf dem LCD-Bildschirm zum Element **Drucken**, klicken Sie auf den Knopf und wählen Sie die Datei **xyz_cube.gcode** aus. Klicken Sie auf den Knopf, um den Druck zu starten.
   - **Düsenhöhe fein einstellen**. Warten Sie, bis die Düse und das Heizbett erhitzt sind, und achten Sie beim Drucken der ersten Schicht auf den Abstand von der Düse zum Bett. Wenn diese zu dick oder zu nah ist, doppelklicken Sie auf den Knopf des LCD-Bildschirms, um ein **"Babystep"**-Menü zu öffnen , und drehen Sie dann den Knopf, um den Abstand von der Düse zum Bett fein einzustellen.
   - **Warten Sie, bis der Druckvorgang abgeschlossen ist**.
- **4.2 Drucken einer 4-Farben-Testdatei**
   - **Gcode-Datei vorbereiten**. [:arrow_down: **M4_4CTest-Zip-Datei herunterladen**][M4_4CTEST] und auf dem PC entpacken und dann den **M4_4CTest.gcode** auf die SD-Karte kopieren. Stecken Sie die SD-Karte in den SD-Anschluss des Geräts.
   - **Filamente laden**. Siehe [:book: **hier**][LOAD_FILAMENT], um alle 4 Filamente in die Extruder und das heiße Ende zu laden.
   - **Drucken von SD-Karte**. Bewegen Sie das Element auf dem LCD-Bildschirm zum Element **Drucken**, klicken Sie auf den Knopf und wählen Sie die Datei **M4_4CTest.gcode** aus. Klicken Sie auf den Knopf, um den Druck zu starten.
   - **Düsenhöhe fein einstellen**. Warten Sie, bis die Düse und das Heizbett erhitzt sind, und achten Sie beim Drucken der ersten Schicht auf den Abstand von der Düse zum Bett. Wenn diese zu dick oder zu nah ist, doppelklicken Sie auf den Knopf des LCD-Bildschirms, um ein **"Babystep"**-Menü zu öffnen , und drehen Sie dann den Knopf, um den Abstand von der Düse zum Bett fein einzustellen.
   - **Warten Sie, bis der Druckvorgang abgeschlossen ist**.
## Schritt 5. Schneiden Sie Ihr eigenes 3D-Modell
- Bevor Sie Ihre eigenen 3D-Modelle drucken, müssen Sie die 3D-Modelldatei (eine Datei im stl/obj/AMF-Format, die Sie [aus dem Internet heruntergeladen haben](#download_de) oder die Sie selbst gezeichnet haben) in eine Gcode-Datei konvertieren und diese Gcode-Datei speichern auf die SD-Karte und schließen Sie die SD-Karte dann an Ihren 3D-Drucker an.     
   :pushpin: **Der Prozess der Konvertierung eines 3D-Modells in eine Gcode-Datei wird *Slicing*** genannt.
- Zuerst müssen Sie die Slicing-Software herunterladen und auf Ihrem Computer installieren und die Parameter Ihrer Maschine in der Slicing-Software einstellen oder die voreingestellte Datei Ihrer Maschine laden, die vom Hersteller des 3D-Druckers festgelegt wurde.
- Als nächstes müssen Sie die Slicing-Software ausführen und möglicherweise auch einige Slicing-Einstellungen entsprechend den Eigenschaften Ihrer 3D-Modelldatei festlegen und dann das Slicing durchführen.     
   :pushpin: Die empfohlene Slicing-Software ist **PrusaSlicer**. Informationen zum Herunterladen, Installieren und Verwenden von **PrusaSlicer** finden Sie in der [***Slicing-Anleitung***][SLICING_GUIDE].
#### <a id="download_de"> :page_with_curl: Berühmte kostenlose Websites zum Herunterladen von 3D-Modellen </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Schritt 6. Drucken Sie Ihr eigenes 3D-Modell
Kopieren Sie nach dem Slicen die generierte Gcode-Datei auf die SD-Karte und drucken Sie sie dann gemäß [**Schritt 4**](#schritt-4-test-3d-modell-drucken) aus.
## Schritt 7. So nutzen Sie erweiterte Funktionen
Nachdem Sie alle grundlegenden Vorgänge vollständig verstanden haben, können Sie einige erweiterte Funktionen dieses Geräts ausprobieren.
Einzelheiten finden Sie im [**Benutzerhandbuch für erweiterte Funktionen**][ADVANCE_FEATURES].

-----
[USER_GUIDE]: https://downgit.github.io/#/home?url=https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2
[INSTALLATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/readme.md
[INSTALL_VIDEO]: https://youtu.be/-oieO7U0LCc
[IMG_ACSWITCH]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/1-Installation_Guide/pic/selectAC.png
[POWER_ON]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#power-on
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[LEVEL_BED]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#level-the-bed
[XYZ_CUBE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/xyz_cube.zip
[LOAD_FILAMENT]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments
[M4_4CTEST]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip
[SLICING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md
[AUTOTEST_VIDEO]: https://youtu.be/iSsuy2ePWw8
[ADVANCE_FEATURES]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#advance-features