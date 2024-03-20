## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](../../lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme.md)
[![](../../lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-es.md)
[![](../../lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-pt.md)
[![](../../lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-fr.md)
[![](../../lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-de.md)
[![](../../lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-it.md)
[![](../../lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-ru.md)
[![](../../lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-jp.md)
[![](../../lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-kr.md)
<!-- [![](../../lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-ar.md) -->

----
## Guida per l'utente del livellamento automatico del letto
#### :warning: Nota:
1. Verificare di aver regolato la colonna eccentrica sulla macchina come indicato nel manuale di installazione. Per garantire che il prodotto non venga danneggiato durante il trasporto, regoliamo in fabbrica la colonna eccentrica in una posizione relativamente allentata. È necessario regolarli, in particolare la colonna eccentrica della staffa del letto caldo, per garantire che il letto caldo non subisca scosse significative. Per i dettagli, fare riferimento a [questa pagina] [ECCENTRIC].
2. Prestare attenzione al controllo della posizione di installazione del dispositivo di livellamento. La parte inferiore del sensore deve essere **2 ~ 3 mm** più alta dell'ugello. PS: Se **hai aggiornato un adesivo per molle PEI**, dovrebbe essere **4~5mm** più alto dell'ugello.
![](./install.jpg)
3. Quando si esegue il livellamento automatico del letto, seguire questi passaggi passo dopo passo: **[Livella angoli](#step1)>>[Cattura offset Z sonda](#step2)>>[Livellamento letto](#step3)** .
4. Quando si stampa il primo oggetto dopo il livellamento automatico del piano, è necessario regolare l'offset Z quando si stampa il primo strato *(il cursore punta al menu Regola, quindi premere due volte la manopola per far apparire il menu **Babystep** , osservare l'altezza tra l'ugello e il letto caldo e ruotare la manopola per regolare nella posizione appropriata)*. Una volta completata la regolazione, non è necessario apportare ulteriori regolazioni durante la stampa successiva.
5. Dopo aver regolato manualmente le viti che fissavano il piano riscaldato, sostituito un hot end, reinstallato il sensore di livellamento o altre azioni che potrebbero causare modifiche al valore di **Z Probe Offset**, è necessario ripetere nuovamente tutti i passaggi di livellamento del letto.

-----
### <a id="step1"> :one: Livella angoli</a>
:loudspeaker: La funzione di livellamento automatico del letto viene utilizzata per correggere l'offset relativo di diverse posizioni sul letto caldo all'altezza dell'asse Z, non il valore assoluto. Prima di eseguire il livellamento automatico del piano, è necessario eseguire **Livella angoli** per fare in modo che la macchina ottenga un valore assoluto corretto del punto iniziale dell'asse Z (il cosiddetto **punto zero assoluto dell'asse Z** della macchina). Passaggi come di seguito:
##### Passaggio 1: accendere la stampante 3D e quindi eseguire "Prepara >> Auto Home >> Home All" sul MENU LCD, attendere che l'hotend raggiunga la posizione HOME.
##### Passaggio 2: Stringere i dadi a mano sotto il letto per abbassare il letto nella posizione più bassa (Fig. 1).
##### Passaggio 3: eseguire "Prepara >> Livellamento del letto >> Punto 1" sul pannello di controllo (Fig 2), l'ugello andrà agli angoli del letto, allentare i dadi a mano sotto il piano caldo (Fig 3) e lasciare che l'ugello quasi tocchi il piano caldo (Fig 4). Continua a fare il “Punto 2/3/4” finché tutti e 4 gli angoli non saranno stati livellati.
##### Passaggio 4: ripeti il passaggio 3 ed esegui 2 ~ 3 giri, fino a quando tutti e quattro gli angoli sono alla stessa altezza.
![](1.png)

### <a id="step2"> :two: Cattura l'offset Z della sonda</a>
Eseguire **Prepare>>Bed Leveling>>Catch Z-Offset** per ottenere l'**Offset Z della sonda** prima di eseguire il livellamento automatico del letto.
###### ![](3.png)
:warning: Esegui ***Control>>Configure>> Auto Leveling*** per attivare la **funzione di livellamento automatico del letto** se non hai visto questo menu.
###### ![](2.png)
:warning: Se il sensore di livellamento del letto non riesce a sondare il letto caldo prima che venga attivato Z ENDSTOP, verrà visualizzato "sondaggio fallito" sullo schermo LCD. Il motivo potrebbe essere perché: :uno: La posizione di installazione del sensore di livellamento del letto è troppo alta, il ②sensore di livellamento del letto non si collega bene con la scheda di controllo o addirittura il ③sensore di livellamento del letto è bruciato.
##### :pushpin: Cos'è l'"Offset Z della sonda"?
**Z Probe Offset** indica che quando il sensore ha rilevato il letto caldo, la distanza tra l'ugello e il punto zero assoluto dell'asse Z.
Se il sensore è installato correttamente, l'ugello è sempre sopra il letto caldo quando il sensore rileva il letto caldo, quindi **Z Probe Offset** è sempre un valore negativo. Poiché la distanza di rilevamento di ciascun sensore PL-08N è diversa e anche l'effettiva altezza di installazione del PL-08N è diversa, anche l'**Z Probe Offset** di ciascuna macchina è diverso.

### <a id="step3"> :three: Livellamento del letto </a>
Dopo aver completato i passaggi precedenti, disponiamo di un sensore affidabile per misurare la superficie del focolaio e già impostarne tutti i parametri. Ora è necessario che la macchina effettui una misurazione completa della superficie del letto caldo, in modo da ottenere una scheda tecnica dell'altezza del letto caldo sulla superficie.
Esegui **Prepare>>Bed Leveling>>Auto Leveling**
###### ![](4.png)
Al termine della misurazione, lo stato del livellamento automatico nel menu Livellamento cambierà da **-NA-** a **Actived**.

### :four: Verifica
Ora puoi provare a stampare un file di prova per verificare il risultato del livellamento automatico del letto. Passaggi come di seguito:
1. Copia **[level_test_310.gcode :arrow_down:](./level_test_310.zip)** sulla scheda SD e stampalo dalla scheda SD (Fig 1).
2. Una volta avviata la stampa, fare doppio clic (fare clic due volte in un secondo) sulla manopola per aprire il menu offset Baby Z (Fig 2).
3. Ruotare la manopola per regolare con precisione l'altezza dell'ugello, lasciare incollare molto bene il filamento sul piano caldo (Fig 3).
4. Guarda il risultato della stampa (Fig 4).
###### ![](5.png)

-----
### Livellamento automatico attivo dopo il ripristino della stampante
La funzione di livellamento automatico verrà disattivata automaticamente al ripristino della stampante, è possibile attivarla manualmente dallo schermo LCD.
- **Passaggio 1. Menu>>Prepare>>Auto Home**
- **Passaggio 2. Motion>> Control>>Configure>>Active autolevel: ON**
NOTA: Dopo aver eseguito questi 2 passaggi, la stampante applicherà i parametri di correzione del livellamento memorizzati nell'ultimo "livello del letto".
###### ![](6.png)

### Livellamento automatico del piano prima di ogni stampa
Se si desidera che la stampante esegua il livellamento automatico del letto per ogni stampa, è necessario aggiungere un comando "G29" in "Avvia Gcode" delle impostazioni della stampante del software di slicing.
###### ![](7.png)
##### :pushpin: Nota
1. L'utilizzo di G29 sostituisce solo la funzionalità del passaggio 3, quindi è necessario completare manualmente anche i passaggi 1 e 2.
2. Dopo aver regolato manualmente le viti che fissavano il piano riscaldato, sostituito un hot end, regolato l'altezza del sensore di livellamento e altre azioni che potrebbero causare modifiche al valore di "Z Probe Offset", è necessario ripetere anche i passaggi 1 e passaggi 2 manualmente.


----
[ECCENTRIC]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide#8-tune-the-eccentric-columns