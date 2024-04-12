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
# Risoluzione dei problemi Z8P

-----
## Riferimento
Per individuare e risolvere il problema del prodotto, potrebbe essere necessario utilizzare la funzione di test automatico, aprire la scatola di controllo per controllare il cablaggio o regolare la corrente di azionamento del mortore, utilizzare un "test di scambio" per controllare un componente elettronico, ecc. .. Qui elenchiamo queste guide, immagini e video tutorial come riferimento.
### Cablaggio
- [:art: Come aprire la casella di controllo](./pic/OpenControlBox.png)
- [:art: Cablaggio sulla scheda di controllo](./pic/Z8P_wiring.png)

### Test automatico dei componenti elettronici
Z8P ha integrato un programma di test automatico dell'elettronica. È possibile utilizzare questo programma per determinare da dove proviene il problema quando qualsiasi componente elettronico riscontra un problema. Per avviare questo programma è necessario aprire il menu "**Info**" e ruotare la manopola per puntare sulla voce "**Data: xx-xx-xx**", quindi premere la manopola cinque volte.
#### Videotutorial
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### Informazioni sul "test di scambio"
Quando scopriamo che c'è un problema funzionale nella macchina e la causa del problema ha molteplici possibilità (più parti possono causare lo stesso problema), abbiamo l'opportunità di utilizzare il cosiddetto "**test di scambio** " per individuare la causa del problema nel più breve tempo possibile.
Ad esempio, se il motore dell'asse Z sinistro non funziona, il problema potrebbe derivare dal cablaggio, dal motore passo-passo, dal cavo del motore, dal modulo di azionamento del motore sulla scheda di controllo o dalla scheda di controllo. Poiché nella macchina sono presenti due set di sistemi di azionamento dell'asse Z - sistemi di azionamento Z sinistro e sistema di azionamento Z destro - che sono identici, possiamo scambiare le stesse parti/componenti/cavo sui lati sinistro e destro uno per uno per confermare da dove viene il problema.
Le parti della macchina che possono effettuare il test di scambio includono:
- Motore X/Y e finecorsa.
- Motore ZL/ZR e finecorsa
- 4 set di motori estrusore
- Riscaldatore a cartuccia e sensore di temperatura del letto caldo e dell'hot end.

-----
## Contenuti
- **[La macchina non può avviarsi](./Issue_of_startup/readme.md)**
- **[L'hot-end è bloccato/intasato](./Issue_mix_color_hotend_clogged/readme.md)**
- **[Problema di riscaldamento](./Issue_heating/readme.md)**
- **[Spegnimento automatico durante la stampa da scheda SD](./Issue_auto_shut_down/readme.md)**
- **[Come risolvere il problema del blocco dell'estrusore](./Issue_extruder_blocked/readme.md)**
- **[Come risolvere il problema di scarico insufficiente dell'estrusore](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Si blocca durante la connessione USB a Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[La stampante effettua la pausa automatica durante la stampa dalla scheda SD](./Issue_auto_pause/readme.md)**
- **[Problema relativo alla scheda SD non letta](./Issue_not_read_sdcard/readme.md)**
- **[Problema relativo alla manopola dello schermo LCD](#dwinscreen)**

----
## Altri riferimenti
- **[44 problemi comuni di stampa 3D](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[Tutti i problemi e le soluzioni (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">Problema relativo alla manopola dello schermo LCD</a>
Se trovi che la manopola dello schermo LCD è bloccata, puoi fare clic su [:regalo: questo link](https://www.aliexpress.com/item/3256805596235491.html) per acquistare una tastiera sostitutiva. Se il tuo prodotto è nel periodo di garanzia (entro 12 mesi dalla data di ricezione del pacco), contattaci dopo aver effettuato l'ordine e ti forniremo il servizio post-vendita.
Come sostituire la tastiera dello schermo LCD, guarda il video tutorial:
- Per la versione con saldatura (precedente), fare riferimento a [:clapper: questo video](https://youtu.be/Xwfczp3nLOY).
- Per la versione FPC (più recente), fare riferimento a [:clapper: questo video](https://youtu.be/z9E6glRZRIQ).
####
![](./pic/keypad.jpg)

-----
## :email: Se non riesci a trovare una soluzione per risolvere il tuo problema dopo aver letto le FAQ, contatta il nostro team di supporto tecnico: support@zonestar3d.com.