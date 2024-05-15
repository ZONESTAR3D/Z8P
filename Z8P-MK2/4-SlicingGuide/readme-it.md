## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](../lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md)
[![](../lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-es.md)
[![](../lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-pt.md)
[![](../lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-fr.md)
[![](../lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-de.md)
[![](../lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-it.md)
[![](../lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-ru.md)
[![](../lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-jp.md)
[![](../lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-kr.md)
<!-- [![](../lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-ar.md) -->

----
# Manuale di installazione e utente PrusaSlicer
Innanzitutto, le stampanti 3D FDM possono elaborare solo file gcode, mentre i formati standard per i file grafici 3D sono solitamente stl, obj e amf ecc. Prima di stampare file di modello 3D sulla stampante 3D FDM, è necessario convertire i file grafici 3D in file gcode sul computer, questo processo si chiama ***"slicing"***. Il software che supporta la conversione di file grafici 3D in file gcode è chiamato software di slicing.
PrusaSlicer è uno dei software di slicing più popolari al giorno d'oggi, particolarmente adatto per stampanti 3D multicolori (multi estrusore). Consigliamo di utilizzare il software di slicing PrusaSlicer per generare file gcode.

----
## :book: Contenuto
1. **[Scarica PrusaSlicer](#a1)**
2. **[Esegui PrusaSlicer e scegli la stampante](#a2)**
3. **[Scegli le preimpostazioni di sistema](#a3)**
4. **[Affettare il modello 3D a un colore](#a4)**
5. **[Affettare il modello 3D multicolore](#a5)**

## <a id="a1">1. Scarica PrusaSlicer</a>
:clapper: [**Come scaricare e installare il software di slicing**](https://youtu.be/SgyXD-kQIeo)
### ![](./pic/win.png) Per Windows
#### Fai clic su [:arrow_down:**here**](https://github.com/ZONESTAR3D/Slicing-Guide/releases/tag/PrusaSlicer2.4.2) per scaricare il software PrusaSlicer e salvarlo sul tuo PC.
![](./pic/download.gif)
#### Quindi decomprimi il file scaricato sul tuo PC o laptop
![](./pic/unzip.png)
### ![](./pic/macos.png) Per Macos o Linux
- [Scarica il software PrusaSlicer con i profili zonestar](https://github.com/ZONESTAR3D/Slicing-Guide/releases/tag/2.4.2)

## <a id="a2">2. Esegui PrusaSlicer e scegli la stampante </a>
#### 2.1 Trova PrsuaSlicer.exe e fai clic su di esso per eseguirlo
![](./pic/run1.png)  
#### 2.2 Scegli la tua stampante, "Altri fornitori>>Zonestar FFF>>modello della tua stampante>>finitura"
![](./pic/run2.png)

## <a id="a3">3. Scegli le preimpostazioni di sistema</a>
Scegli le preimpostazioni di sistema in base alla stampante, all'hotend e ai colori che desideri stampare:   
![](./pic/run3.png)    
- Se devi stampare un modello 3D a un colore, scegli ***Z8 + One Color***.
- Se stampi un modello 3D multicolore, scegli ***Z8 + M4 HOTEND***.

## <a id="a4">4. Affettare un colore</a>
:clapper: [**Guida al taglio - per la stampa a un colore**](https://youtu.be/g-YSgV44Rik)
#### 4.1 scegli le preimpostazioni della stampante *Z8 + Un colore*
![](./pic/slicing1C-1.png)
#### 4.2 caricare il file del modello 3D (file stl/obj/AMF ecc.)
![](./pic/slicing1C-2.png)
#### 4.3 Scegliere il tipo di filamento di stampa
![](./pic/slicing1C-3.png)
#### 4.4 Se necessario, puoi ridimensionare, tagliare, ruotare il modello 3d
![](./pic/slicing1C-4.png)
#### 4.5 Definire le impostazioni di stampa: altezza dello strato, velocità di stampa, supporto, riempimento, ecc.
![](./pic/slicing1C-5.png)    
Potrebbe essere necessario impostare questi parametri in base alla forma del modello e ai requisiti di qualità di stampa. Per alcuni modelli, l'oggetto non può nemmeno essere stampato con successo se le impostazioni non sono corrette. Per i dettagli fare riferimento a:
- [**Presentazione PrusaSlicer**](https://www.prusa3d.com/page/prusaslicer_424/)
- [**Manuale utente Slic3r**](https://manual.slic3r.org/)
#### 4.6 Affettare
![](./pic/slicing1C-6.png)
#### 4.7 Visualizza in anteprima il risultato suddiviso (file gcode), quindi salvalo nel file gcode sul tuo PC e quindi copialo sulla scheda SD
![](./pic/slicing1C-7.png)

## <a id="a5">5. Affettare multicolore </a>
- :clapper: [**Guida al taglio - per la stampa a più colori**](https://youtu.be/AIKrszmxvE4)
#### 5.1 scegli le preimpostazioni della stampante *hotend Z8 + M4*
![](./pic/slicingM4-1.png)
#### 5.2 caricare i file del modello 3D (file stl/obj/AMF ecc.)
![](./pic/slicingM4-2.png) ![](./pic/slicingM4-21.png)
##### :memo: Di solito, il modello diviso è necessario per stampare multicolore, ovvero un modello 3D è stato diviso in più file STL in base ai colori e questi file utilizzano la stessa posizione delle coordinate di origine in modo che possano essere uniti correttamente.
##### :star2: PrusaSlicer ha una nuova funzionalità molto potente. Può [dipingere il colore sul modello 3D](https://youtu.be/Yx4fKDRGEJ4), con questa funzione puoi convertire un modello 3D a un colore in un modello 3D a più colori.
#### 5.3 Scegliere il tipo di filamento di stampa - PLA e impostare il colore del filamento
![](./pic/slicingM4-3.png)
#### 5.4 Assegnare gli estrusori a parti diverse
![](./pic/slicingM4-4.png)
#### 5.5 Se necessario, puoi ridimensionare, tagliare, ruotare il modello 3d
![](./pic/slicingM4-5.png)
#### 5.6 Definire le impostazioni di stampa: altezza dello strato, velocità di stampa, supporto, riempimento, ecc.
![](./pic/slicingM4-6.png)    
È necessario impostare questi parametri in base alla forma del modello e ai requisiti di qualità di stampa. Anche per alcuni modelli, la stampa non può essere completata normalmente senza supporto. Per i dettagli fare riferimento a:
- [**Presentazione PrusaSlicer**](https://www.prusa3d.com/page/prusaslicer_424/)
- [**Manuale utente Slic3r**](https://manual.slic3r.org/)   
:warning: Tieni presente che *Retrazione quando lo strumento è disabilitato* deve essere impostato su 0.  
![](./pic/slicingM4-7.jpg)
#### 5.7 Impostare i parametri per la torre di pulizia
##### Potresti notare che nella figura tagliata apparirà un quadrato, chiamato "Wipe tower" in PrusaSlicer. Poiché per la stampante multicolore, quando si cambia estrusore, ci sono ancora i filamenti del colore precedente all'interno dell'hotend, è necessario pulirli prima di stampare un altro colore.    
![](./pic/slicingM4-71.png)
##### Per ottenere un migliore effetto pulente e ridurre al minimo lo spreco di filamento, possiamo impostare la quantità di spurgo del colore in base ai diversi colori. Si prega di prestare attenzione alla tabella seguente, le colonne mostrano il colore del filamento dell'ultimo estrusore stampato e le righe mostrano il colore del filamento del successivo estrusore da stampare.
##### Quando passiamo dall'estrusore con filamento di colore più chiaro all'estrusore con materiali di consumo di colore più scuro, possiamo impostare una cancellazione dell'estrusione più piccola. Al contrario, quando passiamo dall'estrusore con materiali di consumo di colore più scuro all'estrusore con filamento di colore più scuro, dobbiamo impostare una cancellazione dell'estrusione più piccola
![](./pic/slicingM4-72.png)
#### 5.8 Affettare
![](./pic/slicingM4-8.png)
#### 5.9 Visualizza in anteprima il risultato suddiviso (file gcode), quindi salvalo nel file gcode sul tuo PC e quindi copialo sulla scheda SD
![](./pic/slicingM4-9.png)

