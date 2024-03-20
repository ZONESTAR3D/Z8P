## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](./readme.md)
[![](./lanpic/ES.png)](./readme-es.md)
[![](./lanpic/PT.png)](./readme-pt.md)
[![](./lanpic/FR.png)](./readme-fr.md)
[![](./lanpic/DE.png)](./readme-de.md)
[![](./lanpic/IT.png)](./readme-it.md)
[![](./lanpic/RU.png)](./readme-ru.md)
[![](./lanpic/JP.png)](./readme-jp.md)
[![](./lanpic/KR.png)](./readme-kr.md)
<!-- [![](./lanpic/SA.png)](./readme-ar.md) -->

------
# Z8P-MK2 Guide de l'utilisateur du 
## :warning: ATTENTION S'IL VOUS PLAÎT
### :loudspeaker: Avant d'utiliser la machine, veuillez lire [:book:"Précautions d'utilisation de M4V6"](https://github.com/ZONESTAR3D/Upgrade-kit-guide/blob/main/HOTEND/M4/M4_V6/M4V6_Precaution.md) soigneusement.
### :loudspeaker: Il faut charger 4 filaments simultanément sur le hotend M4V6, un fonctionnement incorrect peut bloquer le hotend de mélange de couleurs. Si le blocage de l'extrémité chaude est dû à un fonctionnement incorrect, il n'est pas couvert par la garantie. Pour savoir comment charger les filaments, veuillez vous référer à [:book: this guide](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filaments).
### :loudspeaker: Si vous êtes débutant en imprimante 3D, veuillez lire attentivement le [:book: Guide pas à pas][step_by_step_guide], et suivre le guide pour procéder étape par étape. Si vous êtes expérimenté en imprimante 3D, veuillez également lire brièvement le [:book: Guide pas à pas][step_by_step_guide] au moins et assurez-vous que vous savez comment charger le filament sur l'extrémité chaude M4.

### [:clapper: Regarder le didacticiel vidéo](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)
Nous créons de nombreux didacticiels vidéo pour cette machine, veuillez cliquer sur [:clapper:**ici**](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial) pour les regarder.

### :file_folder: [1.Guide d'installation][INSTALLATION]
- **[:book: Guide d'installation][INSTALLATION]**
- **[:blue_book:Fichier PDF du guide d'installation et d'utilisation rapide](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/Z8PMK2_Installation_and_quick_use_guide.pdf)**
- **[:clapper: Tutoriel vidéo d'installation](https://youtu.be/-oieO7U0LCc)**
- **[:book: description du menu de l'écran LCD][LCD_MENU]**
- **[:art: Bloc de câblage](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PMK2_Wiring_Block.jpg)**
- **[:art: Schéma de câblage](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PM4-MK2_Wiring_Diagram.jpg)**
### :file_folder: [2.Operation Guide][Operation_Guide]
- **[:book: Guide des opérations de base][Operation_Guide]**
- **[:book: Guide de l'utilisateur du M4V6 Mix Color Hotend][M4V6_Guide]**
- **Fonctionnalités avancées**
   - **[Arrêt automatique :book:][auto_shutdown] [:clapper:](https://youtu.be/SJLpmJL-tG4)**
   - **[Mélange d'impression couleur :book:][mix_color]**
   - **[Niveau automatique du lit :book:][auto_leveling] [:clapper:](https://youtu.be/Zoyl6PybsUk)**
   - **[Récupération après perte de puissance :clapper:](https://youtu.be/f-PpasByiiE)**
   - **[Rétraction automatique:book:][Auto_Retraction]**
- **[:book: Imprimer depuis un PC][PrintFromPC]**
  
### :file_folder: [3.Imprimer les fichiers Gcode de test][Test_gcode]
#### :arrow_down: [Télécharger le fichier gcode de test][Test_gcode]
#### :pencil: Qu'est-ce que le G-code dans l'impression 3D ?
Le G-code est une information ou des instructions dont l'imprimante 3D a besoin pour imprimer un objet en 3 dimensions, c'est le langage que l'imprimante 3D peut comprendre. Le G Code est généré par votre logiciel de découpage, en traduisant un fichier de modélisation 3D standard tel qu'un fichier STL en code que votre imprimante 3D spécifique comprendra.
:page_with_curl: [**Référence 1**](https://beginner3dprinting.com/what-is-g-code-in-3d-printing/) :page_with_curl: [**Référence 2**](https://www.reprap.org/wiki/G-code)

#### :file_folder: [4.Slicing Guide][Slicing_Guide_Z8P]
#### :arrow_down: [Téléchargez le logiciel Silcer et lisez le guide de slicing][Slicing_Guide_Z8P]
#### :pencil: Qu'est-ce que le slicing dans l'impression 3D ?
Slicing est un logiciel que tout le monde utilise pour créer des objets et des produits sur une imprimante 3D. Le logiciel donne à l'imprimante un chemin à suivre. Le logiciel de découpage prend votre image et la convertit en codes G que votre imprimante 3D peut comprendre. Ces codes G sont un type d'instruction sur la façon dont l'imprimante doit imprimer votre conception. :page_with_curl: [**Référence 1**](https://loveandrobots.com/what-is-slicing-in-3d-printing/ ) :page_with_curl: [**Référence 2**](https://en.wikipedia.org/wiki/Slicer_(3D_printing))

### :file_folder: [5. Imprimer les pièces stl][PrintParts]
#### :arrow_down: [Télécharger les fichiers stl des pièces d'impression][PrintParts]

### :link: [6.Firmware](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2)
- **[:arrow_down: Fichier bin du micrologiciel](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2).**
- **[:arrow_down: Code source du micrologiciel](https://github.com/ZONESTAR3D/source-code-for-3d-printer).**
#### :pencil: Qu'est-ce que le fichier bin et le code source ?
> **Le fichier bin du micrologiciel** est la mémoire exacte qui est écrite sur la mémoire flash intégrée.
> **Le code source du micrologiciel** est la partie essentielle du micrologiciel. L'ensemble du micrologiciel peut être considéré comme différents sous-modules. Il est divisé en plusieurs sous-fichiers. Ces fichiers sont appelés fichiers sources. Et tous les fichiers du programme sont appelés fichier source ou code source. Désormais, le code source de notre firmware est basé sur [**marlin**](https://www.marlinfw.org).

### 7.Dépannage
- :book: [**Dépannage pour Z8P**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/readme.md)

### Fonctionnalités évolutives
- **Autocollant du lit chauffant PEI Springs :+1:**    
L'autocollant pour lit chaud en tôle d'acier PEI Spring est plus durable que l'autocollant original pour lit chaud. Avec le lit chaud lisse d'un seul côté orienté vers le haut, cela peut également rendre le bas de l'impression plus lisse. **[:gift: Acheter](http://bit.ly/3GbI9Sr) / [:gift: Acheter](https://bit.ly/3VkmXOi)**     
- **Extrudeuse à double engrenage :+1:**     
L'extrudeuse à double engrenage peut augmenter considérablement la force nécessaire pour pousser/tirer le filament, réduisant considérablement la probabilité de défauts d'impression et d'échecs d'impression causés par le glissement du filament sur l'extrudeuse.**[:book: Guide de l'utilisateur](https://bit.ly/UM_BMG)** **[:gift: Acheter ](https://bit.ly/46Vyd9H) / [:gift: Acheter](https://bit.ly/AE_4xBMG)**
- **Capteur d'épuisement du filament :+1:**   
En mettant à niveau cet article, vous pouvez contrôler à distance votre imprimante 3D. **[:book: Guide][guide_FROD]** [:gift: Acheter](https://www.aliexpress.com/item/4001309957376.html)
- **Module de contrôle sans fil WiFi :+1:**   
En mettant à niveau cet article, vous pouvez contrôler à distance votre imprimante 3D. **[:book: Guide][guide_WIFI]** [:gift: Acheter](https://www.aliexpress.com/item/1005002378551489.html)
- **Hotend de couleurs non mélangées :+1:**   
En mettant à niveau cet élément, la taille de la tour Color Prime pour l'impression de modèles multicolores est beaucoup plus petite. **[:book: Guide][guide_E4]** [:gift: Acheter](https://www.aliexpress.com/item/1005002951777699.html)
- **Extrudeuse à entraînement direct :+1:**   
En mettant à niveau ce projet, vous pouvez imprimer des matériaux flexibles (tels que le filament TPU). **[:book: Guide][guide_DDE]** [:gift: Acheter](https://www.aliexpress.com/item/1005002847644867.html)
- **Moteur laser**    
En mettant à niveau cet article, vous pouvez transformer votre imprimante 3D en une simple machine de gravure laser. Des modules laser de plus grande puissance peuvent améliorer la vitesse de gravure ou prendre en charge des matériaux ayant un point de fusion plus élevé. **[:book: Guide][guide_Laser]** [:gift: Acheter](https://www.aliexpress.com/item/1005004908160260.html)

-----
[step_by_step_guide]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md
[INSTALLATION]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide
[Operation_Guide]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide
[M4V6_Guide]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/M4%20%204-IN-1-OUT%20Mixing%20Color%20Hotend/M4_V6
[Test_gcode]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode
[Slicing_Guide_Z8P]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide
[PrintParts]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/5-PrintParts/
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[mix_color]: https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color
[auto_leveling]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling
[auto_shutdown]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Shut_Down
[Auto_Retraction]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Retraction
[PrintFromPC]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/PrintFromPC
[guide_FROD]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[guide_WIFI]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[guide_E4]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/E4%204-IN-1-OUT%20Non-Mixing%20Color%20Hotend
[guide_DDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Direct_Drive_Extrruder
[guide_Laser]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Laser_Engraving
