## Bed Auto leveling User Guide
#### :warning: Please note:
1. Please check if you have adjusted the eccentric column on the machine as mentioned in the installation manual. To ensure that the product will not be damaged during transportation, we adjust the eccentric column to a relatively loose position at the factory. You need to adjust them, especially the eccentric column of the hot bed bracket, to ensure that the hot bed does not have significant shaking. For details, please refer to [this page](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide#8-tune-the-eccentric-columns).
2. Please pay attention to checking the installation position of the leveling device. The bottom of the sensor should be **2 ~ 3mm** higher than the nozzle.  PS: If you **upgraded a PEI springs sticker**, it should be **4~5mm** higher than the nozzle.
![](./install.jpg)
3. When doing bed auto leveling, please follow these steps step by step: **[Level Corners](#1️⃣-level-corners)>>[Catch Probe Z offset](#2️⃣-catch-probe-z-offset)>>[Bed Leveling](#3️⃣-bed-leveling)**.
4. When printing the first object after did bed automatic leveling, you need to adjust the Z offset when printing the first layer *(the cursor points to the Tune menu, then press the knob twice to pop up a **Babystep** menu, observe the height between the nozzle and the hot bed, and rotate the knob to adjust to the appropriate position)*. Once the adjustment is completed, you do not need to make any further adjustments during the next printing.
5. Once you manually adjust the screws which fixed the heat bed, replace a hot end, reinstalled the leveling sensor or other actions that may cause changes the value of **"Z Probe Offset"**, you must repeat all bed leveling steps again.

-----
### :one: Level Corners
:loudspeaker: The automatic bed leveling function is used to correct the relative offset of different positions on the hot bed at the Z-axis height, not the absolute value. Before executing Bed Auto Leveling, you must perform **Level Corners** to make the machine obtain a correct absolute value of the starting point of Z axis (it is so called **Z axis absolute zero point** of the machine). Steps as below:    
##### Step 1: Power on the 3d printer and then do “Prepare>>Auto Home>>Home All” on LCD MENU, wait the hotend go to the HOME position. 
##### Step 2: Tighten the hand nuts under the bed to move down the bed to the lowest position (Fig 1).
##### Step 3: Do “Prepare>> Bed leveling>> Point 1” on control panel(Fig 2), the nozzle will go to the corners of the bed, loosen the hand nuts under the hotbed (Fig 3) and let the nozzle almost touch the hotbed (Fig 4). Continue to do “Point 2/3/4” until all of the 4 corners has been leveled.
##### Step 4: Repeat Step 3 and do 2 ~ 3 rounds, until all of the four corners at the same height.  
![](1.png)    

### :two: Catch Probe Z offset
Do **Prepare>> Bed Leveling>>Catch Z-Offset** to get the **Probe Z Offset** before doing bed auto leveling.   
![](3.png)
:warning: Do ***Control>> Configure>> Auto Leveling*** to turn on **bed auto leveling feature** if you didn't see this menu.
![](2.png)
:warning: If the bed leveling sensor can't probing the hotbed before Z ENDSTOP is triggered, it will shows "probing fail" on LCD screen. The reason maybe because: :one: The installation postion of bed leveling sensor is too height, ②bed leveling sensor don't connect well with control board or even ③bed leveling sensor is burn out.
##### :pushpin: What is "Probe Z Offset"?
**"Probe Z Offset"** indicates that when the sensor sensed the hot bed, the distance between the nozzle and the Z axis absolute zero point.      
If the sensor is installed correctly, the nozzle is always above the hot bed when the sensor sensed the hot bed, so **Probe Z Offset** is always a negative value. Since the sensing distance of each PL-08N sensor is different, and the actual installation height of PL-08N is also different, the **Probe Z Offset** of each machine is different too.     

### :three: Bed Leveling
After completing the above steps, we have a reliable sensor to measure the hotbed surface and already set all its parameters. Now we need the machine to make a comprehensive measurement of the surface of the hot bed, so as to get a data sheet of the hot bed height on the surface.   
Do **Prepare>> Bed Leveling>>Auto Leveling** 
![](4.png)    
After measure done, the state of Auto leveling on Leveling menu will change from **--NA---** to **Actived**. 

### :four: Verification  
Now you can try to print a test file to verfiy the bed auto leveling result. Steps as below:   
1. Copy **[level_test_310.gcode :arrow_down:](./level_test_310.zip)** to SD card and print it from SD card (Fig 1).
2. When printing started, double click (click twice in one second) the knob to open Baby Z offset menu (Fig 2).
3. Rotate the knob to fine tune the nozzle height, let the filament pasted on the hotbed very well (Fig 3).
4. Watch the print result(Fig 4).
![](5.png)  

-----
### Active auto leveling after the printer reset
Auto leveling feature will be disable automatically when the printer reset, you can turn it on manually from LCD screen.
- **Step 1. Menu>>Prepare>> Auto Home**
- **Step 2. Motion>> Control>> Configure>>Active autolevel: ON**
NOTE: After do these 2 steps, the printer will apply stored leveling correction parameters in the last “bed level”.
![](6.png)  

### Auto leveling the bed before each printing
If you want the printer do bed auto leveling for each printing, you need to add a "G29" command in the "Start Gcode" of printer settings of the slicing software.     
![](7.png)      
##### :pushpin: Please Note
1. Using G29 only replaces the functionality in step 3, so you also need to manually complete steps 1 and steps 2.
2. Once you manually adjust the screws which fixed the heat bed, replace a hot end, adjust the Leveling sensor height, and other actions that may cause changes the value of "Z Probe Offset", you also need to repeat the steps 1 and steps 2 manually.

