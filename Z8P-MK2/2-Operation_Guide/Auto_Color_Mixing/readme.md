### Choose Language (Translated by google)
[![](../../../lanpic/ES.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=es)
[![](../../../lanpic/FR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=fr)
[![](../../../lanpic/PT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=pt)
[![](../../../lanpic/DE.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=de)
[![](../../../lanpic/IT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=it)
[![](../../../lanpic/PL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=pl)
[![](../../../lanpic/RU.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=ru)
[![](../../../lanpic/BR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=pt)
[![](../../../lanpic/GR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=el)

[![](../../../lanpic/JP.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=ja)
[![](../../../lanpic/KR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=ko)
[![](../../../lanpic/ID.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=id)
[![](../../../lanpic/TH.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=th)
[![](../../../lanpic/VN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=vi)
[![](../../../lanpic/IL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=iw)
[![](../../../lanpic/SA.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=ar)
[![](../../../lanpic/TR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=tr)
[![](../../../lanpic/CN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Color_Mixing/readme.md?_x_tr_sl=en&_x_tr_tl=zh-CN)


----
# Auto Color Mixing Feature User Guide
## Change printing color by adjust mixing rate    
+ Start to print a singel color gcode file from SD card.
+ Wait until the print start to print, set on the LCD menu.  
+ **Tune>>Mixer>>Current V-TOOL:** Set the vtool to 0.   
+ **Tune>>Mixer>>Mix>>Extruder1~4(M4):** Arbitrarily adjust the percentage of extruder 1 ~ 4, the range is 0 ~ 100.  
+ **Tune>>Mixer>>Mix>>Comit:** Redistribute the percentage of all extruders in proportion and send it to the current vtool. The current vtool value changes color.
After setting up, on the ideal menu shows Current **VTOOL = 0**
![](1.jpg)

## Auto gradient mixing
![](2.jpg)
+ Start to print a singel color gcode file from SD card.  
+ Wait until the print start to print, set on the LCD menu.  
+ **Tune>>Mixer>>Gradient:OFF>>**
  + **Start Z:** set the start Z heigth(such as:0mm)      
  + **End Z:** set the END Z heigth(such as:200mm)     
  + **Start V-tool:** set the start V-tool(such as:0)        
  + **End V-tool:** set the end V-tool(such as:1)  

After set **Start Z** isn’t equal to **End Z**, and **Start V-tool** isn’t equal to **End V-tool**, the LCD will shows **Gradient : ON**.      
![](3.jpg)

### :star2:Realize gradient mixing by modifing gcode file
You can also add a M166 command into the "start G-code" of the machine setting when slicing, so it can automatically work when print from SD card.   
> 
	Descitpion of M166 command
	M166: Start a gradient mix  
	S[bool] - Enable / disable gradients
	A[float] - Starting Z for the gradient
	Z[float] - Ending Z for the gradient.
	I[index] - V-Tool to use as the starting mix.
	J[index] - V-Tool to use as the ending mix.
	
	For example: M166 S1 A0 Z200 I0 J1
	S1->Enable gradient mix 
	A0->startZ is 0mm 
	Z200-> EndZ is 200mm 
	I0 -> Start V-tool is 0 
	J1 -> End Vtool is 1

## Auto random mixing
![](4.jpg)
+ Start to print a singel color gcode file from SD card.  
+ Wait until the print start to print, set on the LCD menu. 
+ **Tune>>Mixer>>Random Mix: OFF>>**
	+ **Start Z:** set the start Z heigth(such as:0mm) End Z: set the end Z heigth(such as:200mm)    
	+ **Height:** set interval distance(such as:10mm), when printing heigth changed beyond this value, the mixing ratio be changed once.    
	+ **Extruders:** set the number of extruders with random variation(such as:4) 

After set Start Z isn’t equal to the End Z, the LCD will shows **Random : ON**.
![](5.jpg)

### :star2: Realize Random mixing by modifing gcode file
You can also add a M167 command into the "start G-code" of the machine setting when slicing, so it can automatically work when print from SD card.  
> 
	Descitpion of M167 command.
	M167: Start a random mix.
	S[bool] - Enable / disable random mix.
	A[float] - Starting Z for the random.
	Z[float] - Ending Z for the random.
	H[float] - Minimum height of changing mixing rate.
	E[int] - how many extruders used on random mixing.

	For example: M167 S1 A0 Z100 H0.2 E3
	S1->Enable Random mix 
	A0->start Z heigth is 0mm 
	Z100->End Z heigth is 100mm 
	H0.2->change color every 0.2mm
	E3->3 extruders (Extruder#1 to Extruder#3) will be used