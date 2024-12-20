## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](../lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md)
[![](../lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-es.md)
[![](../lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-pt.md)
[![](../lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-fr.md)
[![](../lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-de.md)
[![](../lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-it.md)
[![](../lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-ru.md)
[![](../lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-jp.md)
[![](../lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-kr.md)
<!-- [![](../lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme-ar.md) -->

----
# PrusaSlicer Installation and User Manual
Firstly, FDM 3D printers can only process gcode files, while the standard formats for 3D graphics files are usually stl, obj and amf etc.. Before printing 3D model files on the FDM 3d printer, you need to convert 3D graphics files into gcode files on the computer, this process called ***"slicing"***. The software that supports converting 3D graphics files into gcode files is called slicing software.     
PrusaSlicer is one of the most popular slicing software nowadays, which is particularly suitable for multi color (multi extruder) 3D printers. We recommend using PrusaSlicer slicing software to generate gcode files.

----
## :book: Contents
1. **[Download PrusaSlicer](#a1)**
2. **[Run PrusaSlicer and choose the printer](#a2)**
3. **[Choose system presets](#a3)**
4. **[Slicing one color 3d model](#a4)**
5. **[Slicing multi-color 3d model](#a5)**

## <a id="a1">1. Download PrusaSlicer</a>
:clapper: [**How to download and install slicing software**](https://youtu.be/SgyXD-kQIeo)
### ![](./pic/win.png) For windows
#### Click [:arrow_down:**here**](https://github.com/ZONESTAR3D/Slicing-Guide/releases/tag/PrusaSlicer2.4.2) to download PrusaSlicer software and save it to you PC.
![](./pic/download.gif)   
#### And then unzip downloaded file to your PC or laptop  
![](./pic/unzip.png)   
### ![](./pic/macos.png) For Macos or linux
- [Download PrusaSlicer software with zonestar profiles](https://github.com/ZONESTAR3D/Slicing-Guide/releases/tag/2.4.2)

## <a id="a2">2. Run PrusaSlicer and choose the printer </a>
#### 2.1 Find the PrsuaSlicer.exe and click it to run
![](./pic/run1.png)
#### 2.2 Choose your printer, "Other Vendors>>Zonestar FFF>>your printer model>>finish"
![](./pic/run2.png)

## <a id="a3">3. Choose system presets</a>
Choose system presets according to your printer, hotend and the colors you want to print:   
![](./pic/run3.png)    
- If you need to print one color 3d model, choose **"Z8 + One Color"**.  
- If you print multi color 3d model, choose **"Z8 + M4 HOTEND"**.    

## <a id="a4">4. Slicing one color</a>
:clapper: [**Slicing guide - for one color printing**](https://youtu.be/g-YSgV44Rik)
#### 4.1 choose printer presets "Z8 + One Color"
![](./pic/slicing1C-1.png)
#### 4.2 load 3d model file (stl/obj/AMF file etc.)
![](./pic/slicing1C-2.png)
#### 4.3 Choose print filament type
![](./pic/slicing1C-3.png)
#### 4.4 If need, you can resize, cut, rotate the 3d model 
![](./pic/slicing1C-4.png)  
#### 4.5 Set the print settings: layer height, print speed, support, infill, etc.
![](./pic/slicing1C-5.png)  
You may need to set these parameters according to the shape of the model and your requirements for print quality. For some models, the object even cannot be printed successfully if the settings is incorrect. For details please refer to:
- [**PrusaSlicer introduction**](https://www.prusa3d.com/page/prusaslicer_424/)
- [**Slic3r User Manuual**](https://manual.slic3r.org/)
#### 4.6 Slicing
![](./pic/slicing1C-6.png)  
#### 4.7 Preview the sliced result (gcode file) and then save to gcode file to your PC and then copy to SD card
![](./pic/slicing1C-7.png)  

## <a id="a5">5. Slicing multi-color </a>
- :clapper: [**Slicing guide - for multi colors printing**](https://youtu.be/AIKrszmxvE4) 
#### 5.1 choose printer presets "Z8 + M4 hotend"
![](./pic/slicingM4-1.png)
#### 5.2 load 3d model files (stl/obj/AMF file etc.)
![](./pic/slicingM4-2.png) ![](./pic/slicingM4-21.png)
##### :memo: Usually, "split model" is inneed to print multi-color, that is, a 3d model has been split into multiple STL files according to colors, and these files use the same origin coordinate position so that they can be merged correctly.
##### :star2: PrusaSlicer has a very powerful new feature. It can [painting color to the 3d model](https://youtu.be/Yx4fKDRGEJ4), with this function, you can convert a one color 3d model to a muti color 3d model.
#### 5.3 Choose print filament type - PLA and set filament color
![](./pic/slicingM4-3.png)
#### 5.4 Assign extruders to different parts
![](./pic/slicingM4-4.png)
#### 5.5 If need, you can resize, cut, rotate the 3d model 
![](./pic/slicingM4-5.png)  
#### 5.6 Set the print settings: layer height, print speed, support, infill, etc.
![](./pic/slicingM4-6.png)  
You need to set these parameters according to the shape of the model and your requirements for print quality. Even for some models, printing cannot be completed normally without support. For details please refer to:
- [**PrusaSlicer introduction**](https://www.prusa3d.com/page/prusaslicer_424/)    
- [**Slic3r User Manuual**](https://manual.slic3r.org/)    
:warning: Please note that the "Retraction when tool is disabled" should be set to 0.    
![](./pic/slicingM4-7.jpg)  
#### 5.7 Set parameters for "wipe tower"
##### You may notice that a square square will appear in the sliced figure, which is called "Wipe tower" in PrusaSlicer. Because for the multi-color printer, while switching extruders, there are still the previous color filaments inside the hotend, it need to be clean before printing another color.   
![](./pic/slicingM4-71.png)    
##### In order to obtain better cleaning effect and minimize to waste filament, we can set the amount of color purge according to different colors. Please pay attention to the following table, the columns shows the filament color of the last extruder printed, and the rows shows the filament color of the next extruder to be printed.
##### When we change from the extruder with lighter color filament to the extruder with darker color consumables, we can set a smaller extrusion erasure. On the contrary, when we change from the extruder with darker color consumables to the extruder with darker color filament, we need to set a smaller extrusion erasure
![](./pic/slicingM4-72.png)  
#### 5.8 Slicing
![](./pic/slicingM4-8.png)  
#### 5.9 Preview the sliced result (gcode file) and then save to gcode file to your PC and then copy to SD card
![](./pic/slicingM4-9.png)  

