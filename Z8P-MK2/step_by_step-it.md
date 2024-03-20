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
# Z8P-MK2 Guida passo passo
Se sei un principiante con le stampanti 3D, con così tanta documentazione da leggere, potresti non sapere da dove cominciare. Non preoccuparti, entreremo nei dettagli di questi documenti passo dopo passo.     
In una parola, ciò che devi fare include i 4 passaggi seguenti: **Installa la macchina >> Stampa del file di prova >> Taglia il tuo file 3D >> Stampa il tuo file 3D**.     
Innanzitutto ti consigliamo di [:arrow_down: **scaricare tutti i documenti**][USER_GUIDE] e salvarli sul tuo computer e aggiungere questa pagina web ai preferiti del tuo browser.
## Passaggio 1. Installare la macchina e il cablaggio
- **Installazione**. Fare riferimento a [:book: **guida all'installazione**][INSTALLATION_GUIDE] e [ :clapper: **tutorial video all'installazione**][INSTALL_VIDEO] per installare la macchina.
- **Cablaggio**. Il processo di cablaggio consiste sostanzialmente nell'inserire la spina nella presa corrispondente. Ciò a cui devi prestare attenzione è assicurarti che la spina sia completamente inserita nella presa. Soprattutto per quelle prese a 2 PIN che a volte fanno uno scarso contatto. :warning: Quando si collega la testina di stampa (gruppo hotend), fare riferimento attentamente alle immagini nella guida all'installazione e prestare attenzione a distinguere sia il colore dei connettori che il colore dei fili.
## Passaggio 2. Accendi la macchina ed esegui semplicemente un test e una verifica
- **Accensione**. Prima di accendere l'alimentazione CA, verificare se l'impostazione del selettore dell'alimentazione 110 V/220 V è impostata sulla posizione corretta ([**fare riferimento a questa immagine**][IMG_ACSWITCH]). Quindi puoi [**accendere la macchina**][POWER_ON].       :warning: Si prega di notare che la macchina è dotata di 2 interruttori di alimentazione, uno è ***interruttore CA*** (l'interruttore rosso sul retro della scatola di controllo, vicino alla presa di alimentazione CA) e un altro è ***interruttore CC ***(un interruttore a pulsante rotondo in metallo sul lato destro della scatola di controllo), è necessario prima accendere l'interruttore CA, quindi premere e **tenere premuto l'interruttore CC per circa 5 secondi** (rilasciare finché la vite LCD mostrare il LOGO ZONESTAR) per accendere la macchina.
- **Basta provare**. Dopo l'accensione, è possibile utilizzare il menu sullo schermo LCD ([**Descrizione menu LCD**][LCD_MENU]) per verificare se la macchina può funzionare normalmente, procedendo come segue:
   - **Prepara>>Ritorno automatico>>Home tutto**. Questo passaggio serve a far ritornare la testina di stampa della macchina nella posizione di origine.
   - **Preparazione>>Temperatura>>Preriscaldamento PLA**. Questo passaggio consiste nel controllare l'hot end e che il letto caldo possa essere riscaldato normalmente. In questo passaggio, quando la temperatura dell'ugello supera i 60 gradi, dovresti vedere una ventola sul **lato destro** della testina di stampa (hot end) che gira, questa ventola è chiamata "ventola di raffreddamento dell'hot end".
   - **Preparazione>>Temperatura>>VENTOLA**. Premere la manopola e impostare la velocità della ventola su 255, la ventola sul **lato sinistro in alto** dovrebbe girare.
     Dopo aver eseguito i 3 passaggi precedenti, una volta accertato che la macchina funziona normalmente, è possibile procedere con i passaggi seguenti. Se si riscontra che qualche parte non funziona correttamente, ricontrollare il cablaggio o eseguire un "test automatico dell'elettronica" per verificare. (fare riferimento a [:clapper: **tutorial video sul test automatico della macchina**][AUTOTEST_VIDEO]).
## Passaggio 3. Livellare il letto
Prima di stampare il file di prova, è necessario eseguire un semplice livellamento del letto per impostare l'altezza tra l'ugello e il letto (piattaforma di stampa), in modo che il filamento possa aderire bene al letto durante la stampa. Per farlo, fai riferimento a [**livellare il letto**][LEVEL_BED].
## Passaggio 4. Stampa del modello 3D di prova
Le stampanti 3D FDM possono riconoscere solo i file gcode, dobbiamo copiare i file gcode sulla scheda SD, quindi inserire la scheda SD nello slot per scheda SD della stampante 3D, quindi utilizzare lo schermo LCD per iniziare a stampare.
:warning: Anche se hai familiarità con le stampanti 3D, si consiglia di stampare almeno un modello di prova a 4 colori per confermare che la macchina funzioni normalmente.
- **4.1 Stampare un file di prova a un colore**
   - **Prepara il file gcode**. [:arrow_down: **scarica il file zip xyz_cube**][XYZ_CUBE] e decomprimilo sul PC, quindi copia il **xyz_cube.gcode** sulla scheda SD. Collegare la scheda SD alla presa SD della macchina.
   - **Caricare il filamento**. Fare riferimento a [:book: **qui**][LOAD_FILAMENT] per caricare tutti e 4 i filamenti negli estrusori e nell'hot end.
     ***:warning: per l'hotend M4V6, è necessario caricare 4 filamenti sull'hotend anche se si stampano stampe 3D a un colore.***
   - **Stampa da scheda SD**. Sposta l'elemento sull'elemento **Stampa** sullo schermo LCD, fai clic sulla manopola e scegli il file **xyz_cube.gcode**, fai clic sulla manopola per avviare la stampa.
   - **Regolazione fine dell'altezza dell'ugello**. Attendi che l'ugello e il piano caldo siano riscaldati e osserva la distanza dall'ugello al letto durante la stampa del primo strato, se è troppo largo o troppo vicino, fai doppio clic sulla manopola dello schermo LCD per aprire un menu **"babystep"** , quindi ruotare la manopola per regolare con precisione la distanza dall'ugello al piano.
   - **Attendere il completamento della stampa**.
- **4.2 Stampare un file di prova a 4 colori**
   - **Prepara il file gcode**. [:arrow_down: **scarica il file zip M4_4CTest**][M4_4CTEST] e decomprimilo sul PC, quindi copia il **M4_4CTest.gcode** sulla scheda SD. Collegare la scheda SD alla presa SD della macchina.
   - **Caricare i filamenti**. Fare riferimento a [:book: **qui**][LOAD_FILAMENT] per caricare tutti e 4 i filamenti negli estrusori e nell'hot end.
   - **Stampa da scheda SD**. Spostare l'elemento sull'elemento **Stampa** sullo schermo LCD, fare clic sulla manopola e scegliere il file **M4_4CTest.gcode**, fare clic sulla manopola per avviare la stampa.
   - **Regolazione fine dell'altezza dell'ugello**. Attendi che l'ugello e il piano caldo siano riscaldati e osserva la distanza dall'ugello al letto durante la stampa del primo strato, se è troppo largo o troppo vicino, fai doppio clic sulla manopola dello schermo LCD per aprire un menu **"babystep"** , quindi ruotare la manopola per regolare con precisione la distanza dall'ugello al letto.
   - **Attendere il completamento della stampa**.
## Passaggio 5. Affettare il tuo modello 3D
- Prima di stampare i tuoi modelli 3D, devi convertire il file del modello 3D (un file in formato stl/obj/AMF che [scaricato da Internet](#download_it) o disegnato da te) in un file gcode, salva questo file gcode sulla scheda SD, quindi collega la scheda SD alla stampante 3D.
   :pushpin: **Il processo di conversione di un modello 3D in un file gcode è chiamato *slicing***.
- Innanzitutto devi scaricare il software di slicing e installarlo sul tuo computer, quindi impostare i parametri della tua macchina nel software di slicing o caricare il file di preimpostazione della tua macchina impostato dal produttore della stampante 3D.
- Successivamente, è necessario eseguire il software di affettatura e potrebbe anche essere necessario impostare alcune impostazioni di affettatura in base alle caratteristiche del file del modello 3D e quindi eseguire l'affettatura.
   :pushpin: Il software di slicing consigliato è **PrusaSlicer**, per come scaricare, installare e utilizzare **PrusaSlicer**, fare riferimento alla [***Guida allo slicing***][SLICING_GUIDE].
#### <a id="download_it"> :page_with_curl: Famosi siti web per il download gratuito di modelli 3D </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Passaggio 6. Stampa il tuo modello 3D
Dopo averlo affettato, copia il file gcode generato sulla scheda SD e quindi stampalo seguendo il [**passaggio 4**](#passaggio-4-stampa-del-modello-3d-di-prova).
## Passaggio 7. Per utilizzare le funzionalità avanzate
Dopo aver compreso appieno tutte le operazioni di base, è possibile provare alcune funzioni avanzate di questa macchina.
Per ulteriori dettagli, fare riferimento alla [**Guida all'uso delle funzionalità avanzate**][ADVANCE_FEATURES].

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