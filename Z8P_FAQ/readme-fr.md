## <a id="choose-language">:globe_with_meridians: Choisissez la langue</a>
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
# Dépannage Z8P

-----
## Référence
Afin de trouver et de résoudre les problèmes du produit, vous pouvez avoir besoin d'utiliser la fonction de test automatique, d'ouvrir la bo?te de contr?le pour vérifier les cables ou de régler le courant du moteur, d'utiliser un "test d'échange" pour vérifier un composant électronique, etc.. Ici, nous listons ces guides, images et tutoriels vidéo pour vous référencer.
### Cablage
- [:art: Comment ouvrir la bo?te de contr?le](./pic/OpenControlBox.png)
- [:art: Cablage sur la carte de contr?le](./pic/Z8P_wiring.png)

### Test automatique des composants électroniques
Le Z8P a un programme de test automatique des composants électroniques intégré. Vous pouvez utiliser ce programme pour déterminer d'où vient le problème lorsqu'un composant électronique rencontre un problème. Pour démarrer ce programme, vous devez ouvrir le menu "**Info**" et tourner la poignée pour pointer sur l'élément "**Date: xx-xx-xx**", puis appuyez sur la poignée cinq fois.
#### Tutoriel vidéo
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### à propos du "test d'échange"
Lorsque nous trouvons qu'il y a un problème fonctionnel dans la machine, et que la cause du problème a plusieurs possibilités (plusieurs pièces peuvent causer le même problème), nous avons l'opportunité d'utiliser le soi-disant "test d'échange" pour localiser la cause du problème le plus t?t possible.
Par exemple, si le moteur de l'axe Z gauche ne fonctionne pas, le problème peut provenir des cables, du moteur pas à pas, du cable du moteur, du module de commande du moteur sur la carte de contr?le ou de la carte de contr?le. Parce qu'il y a deux ensembles de systèmes de commande de l'axe Z dans la machine - système de commande de l'axe Z gauche et droit - qui sont identiques, nous pouvons échanger les mêmes pièces/composants/cables des c?tés gauche et droit un par un pour confirmer d'où vient le problème.
Les pièces dans la machine qui peuvent effectuer le test d'échange incluent:
- Moteur X/Y et interrupteur de limite.
- Moteur ZL/ZR et interrupteur de limite
- 4 ensembles de moteurs d'extrudeur
- Réchauffeur à cartouches et capteur de température du lit chauffant et de la hotend.

-----
## Contenus
- **[La machine ne peut pas démarrer](./Issue_of_startup/readme.md)**
- **[Problème de homing](./Issue_of_Homing/readme.md)**
- **[Problème de chauffage](./Issue_heating/readme.md)**
- **[Arrêt automatique lors de l'impression à partir de la carte SD](./Issue_auto_shut_down/readme.md)**
- **[Comment résoudre le problème de blocage de l'extrémité/extrudeur](./Issue_extruder_blocked/readme.md)**
- **[Comment résoudre le problème d'évacuation insuffisante de l'extrudeur](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Crash lors de la connexion USB dans Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[La imprimante s'arrête automatiquement lors de l'impression à partir de la carte SD](./Issue_auto_pause/readme.md)**
- **[Problème de lecture de la carte SD](./Issue_not_read_sdcard/readme.md)**
- **[Problème du bouton de l'écran LCD](#dwinscreen)**

----
## Autres références
- **[44 Problèmes courants d'impression 3D](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[Tous les problèmes et solutions (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">Problème du bouton de l'écran LCD</a>
Si vous trouvez que le bouton de l'écran LCD est bloqué, vous pouvez cliquer sur [:gift: ce lien](https://www.aliexpress.com/item/3256805596235491.html) pour acheter un clavier de remplacement. Si votre produit est dans la période de garantie (dans les 12 mois à partir de la date de réception du paquet), veuillez nous contacter après avoir passé la commande et nous vous fournirons un service après-vente.
Comment remplacer le clavier de l'écran LCD, s'il vous pla?t regarder le tutoriel vidéo:
- Pour la version de soudage (plus ancienne), veuillez vous référer à [:clapper: cette vidéo](https://youtu.be/Xwfczp3nLOY).   
- Pour la version FPC (plus récente), veuillez vous référer à [:clapper: cette vidéo](https://youtu.be/z9E6glRZRIQ).  
####
![](./pic/keypad.jpg)

-----
## :email: Si vous ne trouvez pas de solution pour résoudre votre problème après avoir lu la FAQ, veuillez contacter notre équipe de support technique : support@zonestar3d.com .