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
## Guide de l'utilisateur de la mise à niveau automatique du lit
#### :warning: Veuillez noter :
1. Veuillez vérifier si vous avez réglé la colonne excentrique sur la machine comme mentionné dans le manuel d'installation. Pour garantir que le produit ne sera pas endommagé pendant le transport, nous ajustons la colonne excentrique dans une position relativement lâche en usine. Vous devez les ajuster, en particulier la colonne excentrique du support du lit chaud, pour vous assurer que le lit chaud ne subit pas de secousses importantes. Pour plus de détails, veuillez vous référer à [cette page][ECCENTRIC].
2. Veuillez faire attention à vérifier la position d'installation du dispositif de nivellement. Le bas du capteur doit être **2 à 3 mm** plus haut que la buse. PS : Si vous avez **mis à niveau un autocollant de ressorts PEI**, il devrait être **4 à 5 mm** plus haut que la buse.
![](./install.jpg)
3. Lorsque vous effectuez le nivellement automatique du lit, veuillez suivre ces étapes étape par étape : **[Niveau des coins](#step1)>>[Décalage Z de la sonde de capture](#step2)>>[Niveau du lit](#step3)** .
4. Lors de l'impression du premier objet après le nivellement automatique du lit, vous devez ajuster le décalage Z lors de l'impression de la première couche * (le curseur pointe vers le menu Tune, puis appuyez deux fois sur le bouton pour faire apparaître un menu **Babystep** , observez la hauteur entre la buse et le lit chauffant et tournez le bouton pour régler à la position appropriée)*. Une fois le réglage terminé, vous n’avez plus besoin de procéder à d’autres réglages lors de l’impression suivante.
5. Une fois que vous avez réglé manuellement les vis qui fixaient le lit chauffant, remplacé une extrémité chaude, réinstallé le capteur de nivellement ou d'autres actions pouvant entraîner des modifications de la valeur du ** « Décalage de la sonde Z » **, vous devez répéter toutes les étapes de nivellement du lit. encore.

-----
### <a id="step1"> :one: Coins de niveau</a>
:loudspeaker: La fonction de nivellement automatique du lit est utilisée pour corriger le décalage relatif des différentes positions sur le lit chauffant à la hauteur de l'axe Z, et non la valeur absolue. Avant d'exécuter le nivellement automatique du lit, vous devez effectuer des **Coins de niveau** pour que la machine obtienne une valeur absolue correcte du point de départ de l'axe Z (c'est ce qu'on appelle le **Point zéro absolu de l'axe Z** de la machine). Étapes comme ci-dessous :
##### Étape 1 : Allumez l'imprimante 3D, puis faites « Préparer>>Auto Home>>Home All » sur le MENU LCD, attendez que le hotend aille en position HOME.
##### Étape 2 : Serrez les écrous à main sous le lit pour faire descendre le lit jusqu'à la position la plus basse (Fig. 1).
##### Étape 3 : Effectuez « Préparer>> Nivellement du lit>> Point 1 » sur le panneau de commande (Fig. 2), la buse ira jusqu'aux coins du lit, desserrez les écrous à main sous le foyer (Fig. 3) et laissez la buse toucher presque le foyer (Fig. 4). Continuez à faire « Point 2/3/4 » jusqu'à ce que les 4 coins soient nivelés.
##### Étape 4 : Répétez l'étape 3 et faites 2 à 3 tours, jusqu'à ce que les quatre coins soient à la même hauteur.
![](1.png)

### <a id="step2"> :two: Décalage Z de la sonde de capture</a>
Effectuez **Préparer>> Nivellement du lit>>Attraper le décalage Z** pour obtenir le **Décalage Z de la sonde** avant de procéder au nivellement automatique du lit.
###### ![](3.png)
:warning: effectuez ***Contrôle>> Configure>> Mise à niveau automatique*** pour activer la **fonction de mise à niveau automatique du lit** si vous n'avez pas vu ce menu.
###### ![](2.png)
:warning: Si le capteur de nivellement du lit ne peut pas sonder le foyer avant le déclenchement de Z ENDSTOP, il affichera « échec de la sonde » sur l'écran LCD. La raison peut être parce que : un : La position d'installation du capteur de nivellement du lit est trop haute, le ② capteur de nivellement du lit ne se connecte pas bien au tableau de commande ou même le ③ capteur de nivellement du lit est grillé.
##### :pushpin: Qu'est-ce que le « Décalage Z de la sonde » ?
**Probe Z Offset** indique que lorsque le capteur a détecté le lit chaud, la distance entre la buse et le point zéro absolu de l'axe Z.
Si le capteur est installé correctement, la buse est toujours au-dessus du lit chaud lorsque le capteur a détecté le lit chaud, donc le **Décalage Z de la sonde** est toujours une valeur négative. Étant donné que la distance de détection de chaque capteur PL-08N est différente et que la hauteur d'installation réelle du PL-08N est également différente, le **Décalage Z de la sonde** de chaque machine est également différent.

### <a id="step3"> :three: Nivellement du lit </a>
Après avoir terminé les étapes ci-dessus, nous disposons d’un capteur fiable pour mesurer la surface du foyer et déjà définir tous ses paramètres. Nous avons maintenant besoin de la machine pour effectuer une mesure complète de la surface du lit chaud, afin d'obtenir une fiche technique de la hauteur du lit chaud sur la surface.
Effectuer **Préparer>> Nivellement du lit>>Niveau automatique**
###### ![](4.png)
Une fois la mesure effectuée, l'état de la mise à niveau automatique dans le menu Mise à niveau passera de **--NA---** à **Activé**.

### :four: Vérification
Vous pouvez maintenant essayer d'imprimer un fichier de test pour vérifier le résultat de la mise à niveau automatique du lit. Étapes comme ci-dessous :
1. Copiez **[level_test_310.gcode :arrow_down:](./level_test_310.zip)** sur la carte SD et imprimez-le à partir de la carte SD (Fig 1).
2. Une fois l'impression lancée, double-cliquez (cliquez deux fois en une seconde) sur le bouton pour ouvrir le menu de décalage Baby Z (Fig. 2).
3. Tournez le bouton pour affiner la hauteur de la buse, laissez le filament très bien collé sur le foyer (Fig. 3).
4. Regardez le résultat de l'impression (Fig. 4).
###### ![](5.png)

-----
### Mise à niveau automatique active après la réinitialisation de l'imprimante
La fonction de mise à niveau automatique sera automatiquement désactivée lors de la réinitialisation de l'imprimante, vous pouvez l'activer manuellement à partir de l'écran LCD.
- **Étape 1. Menu>>Préparer>>Accueil automatique**
- **Étape 2. Mouvement>> Contrôle>>Configurer>>Active autolevel: ON**
REMARQUE : Après avoir effectué ces 2 étapes, l'imprimante appliquera les paramètres de correction de nivellement stockés au dernier « niveau du lit ».
###### ![](6.png)

### Mise à niveau automatique du lit avant chaque impression
Si vous souhaitez que l'imprimante effectue un nivellement automatique du lit pour chaque impression, vous devez ajouter une commande "G29" dans le "Démarrer le Gcode" des paramètres de l'imprimante du logiciel de découpage.
###### ![](7.png)
##### :pushpin: Veuillez noter
1. L'utilisation de G29 remplace uniquement la fonctionnalité de l'étape 3, vous devez donc également effectuer manuellement les étapes 1 et 2.
2. Une fois que vous avez réglé manuellement les vis qui fixent le lit chauffant, remplacé une extrémité chaude, réglé la hauteur du capteur de nivellement et d'autres actions susceptibles de modifier la valeur du « Décalage de la sonde Z », vous devez également répéter les étapes 1 et étapes 2 manuellement.

[ECCENTRIC]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide#8-tune-the-eccentric-columns