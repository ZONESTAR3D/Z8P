## How to clean the blocked M4V6 hotend

-----
## :warning: ATTENTION :warning:
**You need to load all the 4 filaments to the hotend whether printing one or multi color 3d prints, incorrect operationa may block the mix color hotend. If the hot end blockage caused by incorrect operation, it is not covered by the warranty. 
For how to load filaments, please refer to [:book:this guide](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filaments) or the [:movie_camera:video tutorial](https://youtu.be/-47yB95uIxI)**    
There are some reasons that may cause the hoend to be blocked, please check the list one by one to ensure that you have noticed these matters when printing and slicing.
### The nozzle are too close to the print platform when printing the first layer.
If the nozzle is too close to the hot bed when printing the first layer, the filament may not be ejected. If this is maintained for a long time, it may cause the filament in the hot end to be over-compressed and cause blockage (often blocked at the entrance of hotend). When printing the first layer, pay attention to the distance between the nozzle and the hot bed. If necessary, open the "BabyStep" menu to adjust the nozzle height.
### Check "Switch Retraction Distance" settings in the slicing software
For 4-IN-1-OUT mix color hotend, the **"Extruder switching retraction length"** MUST be set to 0. For example, set **“Nozzle Switch Retraction Distance”** to 0 in Cura Slicer and set **"Retraction when tool is disable"** in PrusaSlicer.  
![](./1.jpg) ![](./2.jpg)
### Filaments loading
:pushpin: When loading the filament to the hotend, please ensure that the filaments enter the bottom of the hot end.    
:pushpin: You need to load all the 4 filaments to the hot end whether printing one or multi color 3d prints.
### Defective nozzle  
The nozzle may also be partially clogged. If you find the filament flowed out from the nozzle is thinner than normal, the nozzle may be partially clogged, please replace a new nozzle directly.  

------
## How to clean the clogged M4V6 hot end
### Step 1: Take down the nozzle from the hotend.
**[:movie_camera:How to replace a nozzle](https://youtu.be/L5VRyEbsJvM).**
### Step 2: load all 4 filaments to the hot end, and ensure that the filaments enter the bottom of the hot end.
### Step 3: Feed filaments into the hot end.
- ***Prepare>>Filament>>Preheat nozzle: 230***, wait the nozzle reached 230 degree.
- ***Prepare>>Filament>>extruder: all***
- ***Prepare>>Filament>>slowly load***, you may need to do many times, until all 4 filament can be extruded.
You can also directly rotate the gear of the extruders to feed filaments, but you should rotate the gears of four extruders simultaneously (that is, do not rotate the gears of the same extruder more than one turn each time). 
If you find that the filament is slipping on the gear of the extruder, you can:
    - Increase the pressure of the extruder or 
    - Take down the PTFE tube from the fittings of the hotend and push the filaments into the hotend by hand directly.
### Step 4: Install the nozzle back to the hot end
### Step 5: Extrude filament one by one
- ***Prepare>>Filament>>extruder: 1***
- ***Prepare>>Filament>>extruder: slowly load***, until you see the corresponding color filament of extruder #1 is flowing out from the nozzle.
- ***Prepare>>Filament>>extruder: 2***
- ***Prepare>>Filament>>extruder: slowly load***, until you see the corresponding color filament of extruder #2 is flowing out from the nozzle.
- ***Prepare>>Filament>>extruder: 3***
- ***Prepare>>Filament>>extruder: slowly load***, until you see the corresponding color filament of extruder #3 is flowing out from the nozzle.
- ***Prepare>>Filament>>extruder: 4***
- ***Prepare>>Filament>>extruder: slowly load***, until you see the corresponding color filament of extruder #3 is flowing out from the nozzle.

### If the hot end cannot be cleaned by doing the above steps, or the hot end is still easily clogged after cleaning, you need to replace the nozzle or replace the "inner PTFE tubes"
**[:movie_camera:How to replace a nozzle](https://youtu.be/L5VRyEbsJvM).**
**[:book:How to replace the inner PTFE tubes](https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/M4%20%204-IN-1-OUT%20Mixing%20Color%20Hotend/M4_V6#how-to-replace-of-the-inner-ptfe-guide).**

--------
## :email: If you can't find a solution to solve your problem after readed the FAQ , please contact our technical support team : support@zonestar3d.com .



