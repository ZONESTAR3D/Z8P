[USER_GUIDE]: https://downgit.github.io/#/home?url=https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2
[INSTALLATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/readme.md
[INSTALL_VIDEO]: https://youtu.be/-oieO7U0LCc
[IMG_ACSWITCH]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/1-Installation_Guide/pic/selectAC.png
[POWER_ON]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#power-on
[VIDEO_POWER_ON]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/pic/PowerOn.gif
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[LEVEL_BED]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#level-the-bed
[XYZ_CUBE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/xyz_cube.zip
[LOAD_FILAMENT]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments
[M4_4CTEST]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip
[SLICING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md
[AUTOTEST_VIDEO]: https://youtu.be/iSsuy2ePWw8
[ADVANCE_FEATURES]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#advance-features
[Z8P_FAQ]: (https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ)

----
## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/rstep_by_stepeadme-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-kr.md)
<!-- [![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-ar.md) -->

-----
# Guide étape par étape du Z8P-MK2 
Si vous débutez avec les imprimantes 3D, avec autant de documentation à lire, vous ne savez peut-être pas par où commencer. Ne vous inquiétez pas, nous entrerons dans les détails de ces documents étape par étape.      
En un mot, ce que vous devez faire comprend les 4 étapes ci-dessous: **Installer la machine >> Impression du fichier de test >> Découper votre propre fichier 3D >> Imprimer votre fichier 3D**.       
Tout d'abord, nous vous recommandons de [:arrow_down: **télécharger tous les documents**][USER_GUIDE] et de les enregistrer sur votre ordinateur, puis d'ajouter cette page Web aux favoris de votre navigateur.

## <a id="step1">Étape 1. Installez la machine et le câblage </a>
- **Installation**. Reportez-vous au [:book: **guide d'installation**][INSTALLATION_GUIDE] et au [:clapper: **tutoriel vidéo d'installation**][INSTALL_VIDEO] pour installer la machine.
- **Câblage**. Le processus de câblage consiste essentiellement à insérer la fiche dans la prise correspondante. Ce à quoi vous devez faire attention, c'est vous assurer que la fiche est complètement insérée dans la prise. Surtout pour ces prises 2PIN qui font parfois un mauvais contact. :warning: Lorsque vous câblez la tête d'impression (ensemble hotend), veuillez vous référer attentivement aux images du guide d'installation et faire attention à distinguer à la fois la couleur des connecteurs et la couleur des fils.

## <a id="step2">Étape 2. Allumez la maiche et effectuez simplement un test et une vérification </a>
- **Allumer**. Avant de mettre sous tension, veuillez vérifier si le réglage du sélecteur d'alimentation 110 V/220 V est réglé sur la bonne position ([**se référer à cette image**][IMG_ACSWITCH]). Et puis vous pouvez [**allumer la machine**][POWER_ON]. :warning: Veuillez noter que la machine dispose de 2 interrupteurs d'alimentation, l'un est un ***interrupteur AC*** (l'interrupteur rouge à l'arrière du boîtier de commande, près de la prise d'alimentation AC) et un autre est un ***interrupteur DC. *** (un bouton-poussoir rond en métal sur le côté droit du boîtier de commande), vous devez d'abord allumer l'interrupteur CA, puis appuyer et **maintenir l'interrupteur CC pendant environ 5 secondes ** (relâchez jusqu'à ce que la vis LCD afficher le logo ZONESTAR) pour allumer la machine.
- **Testez simplement**. Après la mise sous tension, vous pouvez utiliser le menu sur l'écran LCD ([**Description du menu LCD**][LCD_MENU]) pour vérifier si la machine peut fonctionner normalement, en suivant les étapes ci-dessous:
   - **Préparer>>Auto Home>>Home All**. Cette étape consiste à faire revenir la tête d'impression de la machine à sa position d'origine.
   - **Préparer>>Température>>Préchauffer le PLA**. Cette étape consiste à vérifier l'extrémité chaude et le lit chaud peut être chauffé normalement. Dans cette étape, lorsque la température de la buse dépasse 60 degrés, vous devriez voir un ventilateur sur le **côté droit** de la tête d'impression (extrémité chaude) tourner, ce ventilateur est appelé « ventilateur de refroidissement de l'extrémité chaude ».
   - **Préparation>>Température>>VENTILATEUR**. Appuyez sur le bouton et réglez la vitesse du ventilateur sur 255, le ventilateur situé **côté gauche vers le haut** devrait tourner.
     Après avoir effectué les 3 étapes ci-dessus, il est essentiellement déterminé que la machine fonctionne normalement, vous pouvez procéder aux étapes suivantes. Si vous constatez qu'une pièce ne fonctionne pas correctement, veuillez vérifier le câblage ou effectuer un « test automatique de l'électronique » pour vérifier. (reportez-vous à[ :clapper: **tutoriel vidéo de test automatique de la machine**][AUTOTEST_VIDEO]).

## <a id="step3">Étape 3. Nivelez le lit </a>
[![](https://img.youtube.com/vi/R3RfGnxx8hY/0.jpg)](https://www.youtube.com/watch?v=R3RfGnxx8hY)        
Avant d'imprimer le fichier de test, vous devez effectuer un simple nivellement du lit pour régler la hauteur entre la buse et le lit (plateforme d'impression), afin que le filament puisse bien coller sur le lit lors de l'impression. Veuillez vous référer à [**niveler le lit**][LEVEL_BED] pour le faire.

## <a id="step4">Étape 4. Imprimer le modèle 3D de test </a>
Les imprimantes 3D FDM ne peuvent reconnaître que les fichiers gcode, nous devons copier les fichiers gcode sur la carte SD, puis insérer la carte SD dans la fente pour carte SD de l'imprimante 3D, puis utiliser l'écran LCD pour commencer à imprimer.
:warning: Même si vous êtes familier avec les imprimantes 3D, il est recommandé d'imprimer au moins un modèle de test en 4 couleurs pour confirmer que la machine fonctionne normalement.
- **4.1 Imprimer un fichier de test d'une couleur**     
[![](https://img.youtube.com/vi/ITHbO9VxTMo/0.jpg)](https://www.youtube.com/watch?v=ITHbO9VxTMo)
   - **Préparer le fichier gcode**. [:arrow_down: **téléchargez le fichier zip xyz_cube**][XYZ_CUBE] et décompressez-le sur PC, puis copiez le **xyz_cube.gcode** sur la carte SD. Branchez la carte SD sur la prise SD de la machine.
   - **Charger le filament**. Reportez-vous à [:book: **here**][LOAD_FILAMENT] pour charger les 4 filaments dans les extrudeuses et la partie chaude.
     ***:warning: pour le hotend M4V6, vous devez charger 4 filaments sur le hotend même si vous imprimez des impressions 3D d'une seule couleur.***
   - **Imprimer depuis la carte SD**. Déplacez l'élément vers l'élément **Imprimer** sur l'écran LCD, cliquez sur le bouton et choisissez le fichier **xyz_cube.gcode**, cliquez sur le bouton pour lancer l'impression.
   - **Régler finement la hauteur de la buse**. Attendez que la buse et le foyer soient chauffés, et surveillez la distance entre la buse et le lit lors de l'impression de la première couche, si elle est trop grasse ou trop proche, double-cliquez sur le bouton de l'écran LCD pour ouvrir un menu **"babystep"** , puis tournez le bouton pour affiner la distance entre la buse et le lit.
   - **Attendez la fin de l'impression**.
- **4.2 Imprimer un fichier de test en 4 couleurs**     
[![](https://img.youtube.com/vi/CA8pWOuJYmE/0.jpg)](https://www.youtube.com/watch?v=CA8pWOuJYmE)
   - **Préparer le fichier gcode**. [:arrow_down: **téléchargez le fichier zip M4_4CTest**][M4_4CTEST] et décompressez-le sur PC, puis copiez le **M4_4CTest.gcode** sur la carte SD. Branchez la carte SD sur la prise SD de la machine.
   - **Charger les filaments**. Reportez-vous à [:book: **here**][LOAD_FILAMENT] pour charger les 4 filaments dans les extrudeuses et l'extrémité chaude.
   - **Imprimer depuis la carte SD**. Déplacez l'élément vers l'élément **Imprimer** sur l'écran LCD, cliquez sur le bouton et choisissez le fichier **M4_4CTest.gcode**, cliquez sur le bouton pour lancer l'impression.
   - **Régler finement la hauteur de la buse**. Attendez que la buse et le foyer soient chauffés, et surveillez la distance entre la buse et le lit lors de l'impression de la première couche, si elle est trop grasse ou trop proche, double-cliquez sur le bouton de l'écran LCD pour ouvrir un menu **"babystep"** , puis tournez le bouton pour affiner la distance entre la buse et le lit.
   - **Attendez la fin de l'impression**.

## <a id="step5">Étape 5. Découper votre propre modèle 3D </a>
- Avant d'imprimer vos propres modèles 3D, vous devez convertir le fichier de modèle 3D (un fichier au format stl/obj/AMF qui [téléchargé depuis Internet](#download) ou dessiné par vous-même) en un fichier gcode, enregistrez ce fichier gcode sur la carte SD, puis branchez la carte SD sur votre imprimante 3D.     
   :pushpin: **Le processus de conversion d'un modèle 3D en fichier Gcode est appelé *slicing***.
- Tout d'abord, vous devez télécharger le logiciel de découpage et l'installer sur votre ordinateur, puis définir les paramètres de votre machine dans le logiciel de découpage ou charger le fichier prédéfini de votre machine défini par le fabricant de l'imprimante 3D.
- Ensuite, vous devez exécuter le logiciel de découpage, et vous devrez peut-être également définir certains paramètres de découpage en fonction des caractéristiques de votre fichier de modèle 3D, puis effectuer le découpage.     
   :pushpin: Le logiciel de découpage recommandé est **PrusaSlicer**. Pour savoir comment télécharger, installer et utiliser **PrusaSlicer**, veuillez vous référer au [***Slicing Guide***][SLICING_GUIDE].

## <a id="step6">Étape 6. Imprimer votre propre modèle 3D </a>
Une fois découpé, copiez le fichier gcode généré sur la carte SD, puis imprimez-le en suivant la [**étape 4**](#step4).

## <a id="step7">Étape 7. Pour utiliser les fonctionnalités avancées </a>
Après avoir parfaitement compris toutes les opérations de base, vous pouvez essayer certaines fonctions avancées de cette machine.
Pour plus de détails, veuillez consulter le [**Guide d'utilisation des fonctionnalités avancées**][ADVANCE_FEATURES].

----
#### <a id="download"> :page_with_curl: Célèbres sites de téléchargement de modèles 3D gratuits </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   

----
