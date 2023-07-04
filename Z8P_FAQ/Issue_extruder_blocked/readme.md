### :globe_with_meridians: Choose Language (Translated by google)
[![](../../lanpic/ES.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=es)
[![](../../lanpic/PT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=pt)
[![](../../lanpic/FR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=fr)
[![](../../lanpic/DE.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=de)
[![](../../lanpic/IT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=it)
[![](../../lanpic/SW.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=sv)
[![](../../lanpic/PL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=pl)
[![](../../lanpic/DK.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=da)
[![](../../lanpic/CZ.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=cs)
[![](../../lanpic/HR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=hr)
[![](../../lanpic/RO.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=ro)
[![](../../lanpic/SK.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=sk)

[![](../../lanpic/RU.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=ru)
[![](../../lanpic/JP.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=ja)
[![](../../lanpic/KR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=ko)
[![](../../lanpic/ID.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=id)
[![](../../lanpic/TH.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=th)
[![](../../lanpic/VN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=vi)
[![](../../lanpic/IL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=iw)
[![](../../lanpic/SA.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=ar)
[![](../../lanpic/TR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=tr)
[![](../../lanpic/GR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=el)
[![](../../lanpic/BR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=pt)
[![](../../lanpic/CN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/Issue_extruder_blocked?_x_tr_sl=en&_x_tr_tl=zh-CN)

-----
## Extruder(s) blocked and unable to print [for Z8PM4Pro-MK2]
### Reason:
The problem may come from the extruder(s), the PTFE tube connecting the extruders to the hot end (print head), or the hot end (print head). 
### Check steps:
To confirm where the problem originated, please following the below steps to check, assuming Extruder#2 is blocked:
#### 1. Swap the PTFE tubes connected to Extruder#2 and another extruder on the extruders side, and then print the test file [:arrow_down:M4_4CTest.gcode](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip).    
![](./1.jpg)
##### 1.1 If there is still an issue with Extruder#2, it indicates that the problem is from extruder. Usually, this may be related to the assembly of the extruder. Please refer to [:clapper:this video tutorial](https://youtu.be/Bo478rUPcxo) to disassemble and reassemble the extruder.    
##### 1.2 If the problem shifts to another extruder, it indicates that the problem is from the hot end or PTFE tube. Please refer to step 2.    

#### 2. Swap the PTFE tubes connected to Extruder#2 and another extruder (on the hot end side), and then print the test file  [:arrow_down:M4_4CTest.gcode](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip).    
![](./2.jpg)
##### 2.1 If there is still a problem with Extruder#2, it indicates that the problem is from the PTFE tube. You can check whether the 2 ends of the PTFE tube are deformed, it will result in excessive resistance (you can manually insert fine wires to check). Usually, the deformation of PTFE pipes occurs at the 2 ends, you can cut off a bit and continue to use it.    
##### 2.2 If the problem shifts to another extruder, it indicates that the problem is from the hot end (the channel that connected to Extruder#2). Please refer to step 3.    

#### 3. Check the hot end.
##### 3.1 Remove the PTFE from the fitting and then check if there are any broken filaments stuck inside the four fitting wires connecting the hot end.
##### 3.2 Check the PTFE tubes connected inside the hot end to see if the length of their extension from the hot end is basically the same. If there are different, first heat the nozzle to 260 degrees, then push the PTFE tubes down as much as possible to the bottom of the hot end.
![](./3.jpg)
##### 3.3 Refer to [this guide](../Issue_mix_color_hotend_clogged/Clean_clogged_M4V6.md) to clean the hotend.

--------
## :email: If you can't find a solution to solve your problem after readed the FAQ , please contact our technical support team : support@zonestar3d.com .