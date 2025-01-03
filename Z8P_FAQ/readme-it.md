## <a id="choose-language">:globe_with_meridians: Scegli lingua</a>
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
# Risoluzione dei problemi Z8P

-----
## Riferimento
Per trovare e risolvere i problemi del prodotto, potreste aver bisogno di utilizzare la funzione di test automatico, aprire la scatola di controllo per controllare i cavi o regolare la corrente del motore, utilizzare un "test di scambio" per verificare un componente elettronico, ecc. Ecc. Qui elenchiamo queste guide, immagini e tutorial video per il vostro riferimento.
### Cablaggio
- [:art: Come aprire la scatola di controllo](./pic/OpenControlBox.png)
- [:art: Cablaggio sulla scheda di controllo](./pic/Z8P_wiring.png)

### Test automatico dei componenti elettronici
Il Z8P ha un programma di test automatico dei componenti elettronici incorporato. è possibile utilizzare questo programma per determinare l'origine del problema quando un componente elettronico ha un problema. Per avviare questo programma, è necessario aprire il menu "**Info**" e ruotare il pomello per puntare all'elemento "**Data: xx-xx-xx**", quindi premere il pomello cinque volte.
#### Video tutorial
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### Sul "test di scambio"
Quando scopriamo che c'è un problema funzionale nella macchina e la causa del problema ha diverse possibilità (diversi pezzi possono causare lo stesso problema), abbiamo l'opportunità di utilizzare il cosiddetto "test di scambio" per localizzare la causa del problema il prima possibile.
Ad esempio, se il motore dell'asse Z sinistro non funziona, il problema può provenire dai cavi, dal motore a passoni, dal cavo del motore, dal modulo di comando del motore sulla scheda di controllo o dalla scheda di controllo stessa. Poiché ci sono due sistemi di comando dell'asse Z nella macchina - sistema di comando dell'asse Z sinistro e destro - che sono identici, possiamo scambiare le stesse parti/componenti/cavi sui lati sinistro e destro uno dopo l'altro per confermare l'origine del problema.
Le parti nella macchina che possono effettuare il test di scambio includono:
- Motore X/Y e interruptore di limite.
- Motore ZL/ZR e interruptore di limite
- 4 set di motori estrusori
- Calore di cartuccia e sensore di temperatura del letto caldo e dell'hotend.

-----
## Contenuti
- **[La macchina non si può avviare](./Issue_of_startup/readme.md)**
- **[Problema di homing](./Issue_of_Homing/readme.md)**
- **[Problema di riscaldamento](./Issue_heating/readme.md)**
- **[Spegnimento automatico quando si stampa da scheda SD](./Issue_auto_shut_down/readme.md)**
- **[Come risolvere il problema di blocco dell'hotend/estrusore](./Issue_extruder_blocked/readme.md)**
- **[Come risolvere il problema di scarico insufficiente dell'estrusore](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Crash quando si collega USB in Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[La stampante si interrompe automaticamente quando si stampa da scheda SD](./Issue_auto_pause/readme.md)**
- **[Problema di lettura della scheda SD](./Issue_not_read_sdcard/readme.md)**
- **[Problema del pulsante dello schermo LCD](#dwinscreen)**

----
## Altre referenze
- **[44 problemi comuni di stampa 3D](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[Tutti i problemi e soluzioni (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">Problema del pulsante dello schermo LCD</a>
Se scoprite che il pulsante dello schermo LCD è bloccato, potete fare clic su [:gift: questo link](https://www.aliexpress.com/item/3256805596235491.html) per acquistare una tastiera di sostituzione. Se il vostro prodotto è nel periodo di garanzia (entro 12 mesi dalla data di ricezione del pacchetto), si prega di contattarci dopo aver effettuato l'ordine e vi forniremo il servizio post-vendita.
Come sostituire la tastiera dello schermo LCD, si prega di guardare il tutorial video:
- Per la versione di saldatura (più vecchia), si prega di fare riferimento a [:clapper: questo video](https://youtu.be/Xwfczp3nLOY).   
- Per la versione FPC (più nuova), si prega di fare riferimento a [:clapper: questo video](https://youtu.be/z9E6glRZRIQ).  
####
![](./pic/keypad.jpg)

-----
## :email: Se non trovate una soluzione per il vostro problema dopo aver letto le domande frequenti, si prega di contattare il nostro team di supporto tecnico: support@zonestar3d.com .

你可以将上述内容复制到一个文本编辑器中，并将其保存为一个`.md`文件。如果你需要将文本转换为PDF或其他格式，你可以使用在线转换工具或本地应用程序来实现这一点。
