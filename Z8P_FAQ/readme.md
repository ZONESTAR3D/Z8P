### :globe_with_meridians: Choose Language (Translated by google)
[![](../lanpic/ES.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=es)
[![](../lanpic/PT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=pt)
[![](../lanpic/FR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=fr)
[![](../lanpic/DE.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=de)
[![](../lanpic/IT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=it)
[![](../lanpic/SW.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=sv)
[![](../lanpic/PL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=pl)
[![](../lanpic/DK.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=da)
[![](../lanpic/CZ.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=cs)
[![](../lanpic/HR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=hr)
[![](../lanpic/RO.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=ro)
[![](../lanpic/SK.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=sk)

[![](../lanpic/RU.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=ru)
[![](../lanpic/JP.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=ja)
[![](../lanpic/KR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=ko)
[![](../lanpic/ID.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=id)
[![](../lanpic/TH.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=th)
[![](../lanpic/VN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=vi)
[![](../lanpic/IL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=iw)
[![](../lanpic/SA.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=ar)
[![](../lanpic/TR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=tr)
[![](../lanpic/GR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=el)
[![](../lanpic/BR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=pt)
[![](../lanpic/CN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P?_x_tr_sl=en&_x_tr_tl=zh-CN)

-----
# Z8P Troubleshootings Guide

-----
## Reference
In order to find and solve the problem of the product, you may need to use the automatic test function, open the control box to check the wiring or tune the mortor drive current, use a "swap test" to check an electronic component, etc.. Here we list these guides, pictures and video tutorial for you reference.
### Wiring
- [:art: How to open the control box](./pic/OpenControlBox.png)
- [:art: Wiring on control board](./pic/Z8P_wiring.png)

### Electronics parts auto testing
Z8P has builted-in an electronics automatic testing program. You can use this program to determine where the problem comes from when any electronic component encounters a problem. To start this program, you need to open the "**Info**" menu and rotate the knob to point to the "**Date: xx-xx-xx**" item, and then press the knob five times.      
For details, please refer to the [:clapper:**video tutorial**](https://youtu.be/iSsuy2ePWw8).

### About "swap test"
When we find that there is a functional problem in the machine, and the cause of the problem has multiple possibilities (multiple parts may cause to the same problem), we have the opportunity to use the so-called "**swap test**" to locate the cause of the problem as soon as possible.    
For example, if the left Z-axis motor does not work, the problem may come from the wiring, stepper motor, motor cable, the motor drive module on the control board or the control board. Because there are two sets of Z-axis drive systems in the machine - left Z drive systems nd right Z drive system - which are identical, we can exchange the same parts/components/wire on the left and right sides one by one to confirm where the  problem comes from.    
The parts in the machine that can carry out the exchange test include:
- X/Y motor and limit switch.
- ZL/ZR motor and limit switch
- 4 sets of extruder motors
- Cartridge heater and temperature sensor of hot bed and hot end.

-----
## Contents
- [**The machine can't start up**](./Issue_of_startup/readme.md)
- [**Heating issue**](./Issue_heating/readme.md)
- [**Auto shut down when printing from SD card**](./Issue_auto_shut_down/readme.md)
- [**Hot end is blocked/clogged**](./Issue_mix_color_hotend_clogged/reame.md)
- [**How to fix Extruder insufficient discharge issue**](./Issue_of_Extruder_insufficient_discharge/readme.md)
- [**Crash when connecting USB in Cura**](./issue_of_connect_USB_in_Cura/readme.md)
<!-- - [**Homing issue**](./Issue_of_Homing/readme.md) -->
<!-- - [**Stepping motor(s) can not work properly**](./Issue_of_stepping_motor/readme.md) -->
<!-- - [**Not read SD card issue**](./Issue_not_read_sdcard/readme.md) -->
<!-- - [**Auto pause when printing from SD card**](./Issue_auto_pause/readme.md) -->

-----
## Poor printing quality issue
- **[44 Common 3D Print Problems](https://www.3dsourced.com/rigid-ink/ultimate-3d-printing-troubleshooting-guide) @3dsourced**
- **[All Problems & Solutions](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/) @all3DP**

-----
## :email: If you can't find a solution to solve your problem after readed the FAQ , please contact our technical support team : support@zonestar3d.com .


