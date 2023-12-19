<!-- ### :globe_with_meridians: Choose Language (Translated by google)
[![](../../lanpic/ES.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=es)
[![](../../lanpic/PT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=pt)
[![](../../lanpic/FR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=fr)
[![](../../lanpic/DE.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=de)
[![](../../lanpic/IT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=it)
[![](../../lanpic/SW.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=sv)
[![](../../lanpic/PL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=pl)
[![](../../lanpic/DK.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=da)
[![](../../lanpic/CZ.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=cs)
[![](../../lanpic/HR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=hr)
[![](../../lanpic/RO.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=ro)
[![](../../lanpic/SK.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=sk)

[![](../../lanpic/RU.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=ru)
[![](../../lanpic/JP.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=ja)
[![](../../lanpic/KR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=ko)
[![](../../lanpic/ID.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=id)
[![](../../lanpic/TH.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=th)
[![](../../lanpic/VN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=vi)
[![](../../lanpic/IL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=iw)
[![](../../lanpic/SA.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=ar)
[![](../../lanpic/TR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=tr)
[![](../../lanpic/GR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=el)
[![](../../lanpic/BR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=pt)
[![](../../lanpic/CN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_auto_shut_down?_x_tr_sl=en&_x_tr_tl=zh-CN)

----- -->
## The printer auto shut down when printing from SD card
- Open the control box and check the wire to connect to the AC power socket, these wire may not connect very well.
- Check the AC power switch on the AC power cord socket, if the switch doesn't work well, try to bypass it and try again.
![](BypassSwitch.jpg)
- Upload the newest firmware to the control board and try again.
**[:arrow_down:Download the newest firmware](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P)**   
:warning: Please confirm the model of your machine before downloading firmware.
- Remove the SD card extend cable and plug the SD card in to the SD card socket of the machine directly and try again.   
- Format the SD card (Must be FAT32) and copy only one gcode file to SD card and try again.
- Replace a new SD card (<=32G, format to FAT32) and try again.
- Print another gcode file and try again.
- Turn off the **PowerLoss Recovery** feature and try again (***Control>>Configre>>PowerLoss Recovery***).

### If you have tried all above steps and the question can't be fixed, please contact our technical support team : support@zonestar3d.com.