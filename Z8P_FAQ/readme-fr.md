## <a id="choose-language">:globe_with_meridians: Choose language </a>
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
Afin de trouver et de résoudre le problème du produit, vous devrez peut-être utiliser la fonction de test automatique, ouvrir le boîtier de commande pour vérifier le câblage ou régler le courant d'entraînement du mortier, utiliser un « test d'échange » pour vérifier un composant électronique, etc. .. Nous répertorions ici ces guides, images et didacticiels vidéo pour votre référence.
### Câblage
- [:art: Comment ouvrir la boîte de contrôle](./pic/OpenControlBox.png)
- [:art: Câblage sur la carte de contrôle](./pic/Z8P_wiring.png)

### Tests automatiques de pièces électroniques
Le Z8P intègre un programme de test automatique de l'électronique. Vous pouvez utiliser ce programme pour déterminer d'où vient le problème lorsqu'un composant électronique rencontre un problème. Pour démarrer ce programme, vous devez ouvrir le menu « **Info** » et tourner le bouton pour pointer sur l'élément « **Date : xx-xx-xx** », puis appuyer cinq fois sur le bouton.
#### Didacticiel vidéo
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### À propos du "test d'échange"
Lorsque nous constatons qu'il y a un problème fonctionnel dans la machine et que la cause du problème a de multiples possibilités (plusieurs pièces peuvent provoquer le même problème), nous avons la possibilité d'utiliser ce que l'on appelle le "**test d'échange** " pour localiser la cause du problème le plus rapidement possible.
Par exemple, si le moteur de l'axe Z gauche ne fonctionne pas, le problème peut provenir du câblage, du moteur pas à pas, du câble moteur, du module d'entraînement du moteur sur la carte de commande ou de la carte de commande. Comme il existe deux ensembles de systèmes d'entraînement de l'axe Z dans la machine - les systèmes d'entraînement Z gauche et le système d'entraînement Z droit - qui sont identiques, nous pouvons échanger les mêmes pièces/composants/fils sur les côtés gauche et droit une par une pour confirmer. d'où vient le problème.
Les pièces de la machine qui peuvent effectuer le test d'échange comprennent :
- Moteur X/Y et fin de course.
- Moteur ZL/ZR et fin de course
- 4 jeux de moteurs d'extrudeuse
- Cartouche chauffante et capteur de température du lit chaud et de l'extrémité chaude.

-----
## Contenu
- **[La machine ne démarre pas](./Issue_of_startup/readme.md)**
- **[La hot end est bloquée/bouchée](./Issue_mix_color_hotend_clogged/readme.md)**
- **[Problème de chauffage](./Issue_heating/readme.md)**
- **[Arrêt automatique lors de l'impression à partir d'une carte SD](./Issue_auto_shut_down/readme.md)**
- **[Comment résoudre le problème de blocage de l'extrudeuse](./Issue_extruder_blocked/readme.md)**
- **[Comment résoudre le problème de décharge insuffisante de l'extrudeuse](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Crash lors de la connexion USB dans Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[La pause automatique de l'imprimante lors de l'impression à partir d'une carte SD](./Issue_auto_pause/readme.md)**
- **[Problème de carte SD non lu](./Issue_not_read_sdcard/readme.md)**
- **[Problème de bouton d'écran LCD](#dwinscreen)**

----
## Autres références
- **[44 problèmes d'impression 3D courants](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[Tous les problèmes et solutions (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">Problème de bouton de l'écran LCD</a>
Si vous constatez que le bouton de l'écran LCD est bloqué, vous pouvez cliquer sur [:gift: this link](https://www.aliexpress.com/item/3256805596235491.html) pour acheter un clavier de remplacement. Si votre produit est sous garantie (dans les 12 mois à compter de la date de réception du colis), veuillez nous contacter après avoir passé la commande et nous vous fournirons un service après-vente.
Comment remplacer le clavier de l'écran LCD, veuillez regarder le didacticiel vidéo :
- Pour la version de soudage (ancienne), veuillez vous référer à [:clapper: this video](https://youtu.be/Xwfczp3nLOY).
- Pour la version FPC (plus récente), veuillez vous référer à [:clapper: this video](https://youtu.be/z9E6glRZRIQ).
####
![](./pic/keypad.jpg)

-----
## :email: Si vous ne trouvez pas de solution pour résoudre votre problème après avoir lu la FAQ, veuillez contacter notre équipe d'assistance technique : support@zonestar3d.com.