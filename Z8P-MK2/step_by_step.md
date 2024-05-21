[USER_GUIDE]: https://downgit.github.io/#/home?url=https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2
[INSTALLATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/readme.md
[INSTALL_VIDEO]: https://youtu.be/-oieO7U0LCc
[IMG_ACSWITCH]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/1-Installation_Guide/pic/selectAC.png
[POWER_ON]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#power-on
[VIDEO_POWER_ON]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/pic/PowerOn.gif
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[LEVEL_BED]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#level-the-bed
[XYZ_CUBE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/xyz_cube.zip
[LOAD_FILAMENT]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments
[M4_4CTEST]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip
[SLICING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md
[AUTOTEST_VIDEO]: https://youtu.be/iSsuy2ePWw8
[ADVANCE_FEATURES]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#advance-features
[Z8P_FAQ]: (https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ)

----
## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-kr.md)
<!-- [![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step-ar.md) -->

----
# Z8P-MK2 Step-by-Step Guide
If you are a beginner in 3D printer, you may not know how to start using the 3D printer. Don't worry, you just need to follow the steps in the manual below step by step and you will soon familiarize yourself with how to use it.


## <a id="step1">Step 1. Installion and Wiring </a>
Please refer to the [:book: **Installation Guide**][INSTALLATION_GUIDE] and [:clapper:**Installation Video Tutorials**][INSTALL_VIDEO] to install the machine and wiring.     
:warning: **When wiring, please be careful to ensure that the plug is fully inserted into the socket. When wiring the print head (hot end assembly), please refer to the pictures in the installation guide carefully and distinguish the color of the connectors.**

## <a id="step2">Step 2. Step 2. Power on the maiche for simple testing and verification </a>
- **Turn on the power**. Before turning on the AC power, check that the 110V/220V power selector switch is set to the correct position see ([**:art: this diagram**][IMG_ACSWITCH]). And then you can **[:book:turn on the power of machine][POWER_ON]([:clapper: video tutorial][VIDEO_POWER_ON])**.    
:warning: Please note that there are two power switches, one is the AC switch (the red switch on the back of the control box near the AC outlet) and the other is the DC switch (the round metal push button switch on the right side of the control box), you need to turn on the AC switch first and then **press and hold down the DC switch** for about 5 seconds (until the LCD screen shows the ZONESTAR LOGO) in order to turn on the machine.     
- **Test and verify**. After powering on the machine, please operate the knob on the LCD screen to perform some menu operations to verify that the machine is install and wiring properly: (For a detailed description of the menu functions of the display, please refer to [**:book: this link**][LCD_MENU])
  - **Prepare>>Auto Home>>Home All**. This step is to make the print head of the machine return to the origin position.
  - **Prepare>>Temperature>>Preheat PLA**. This step is to check the hot end and the hot bed can be heated normally. In this step, when the temperature of the nozzle exceeds 60 degrees, you should see a fan on the **right side** of the print head (hot end) spin up, this fan is called "hot end cooling fan". 
  - **Prepare>>Temperature>>FAN**. Press the knob and setting the fan speed to 255, the fan on the **left side up** should spin up.   
After did the above 3 steps, it is basically determined that the machine are working normally, you can proceed the following steps.     
:pushpin: If during the test you notice that any part is not working properly, recheck the wiring first. If the problem is not solved, please read the [**:book: Troubleshooting Manual**][Z8P_FAQ] to find a solution.

## <a id="step3">Step 3. Level the bed </a>
[![](https://img.youtube.com/vi/R3RfGnxx8hY/0.jpg)](https://www.youtube.com/watch?v=R3RfGnxx8hY)     
Before printing the test file, you need to do a simple bed leveling to set the height between the nozzle and the bed (printing platform), so that the filament can be sticked on the bed well when printing. Please refer to [**level the bed**][LEVEL_BED] to do it.

## <a id="step4">Step 4. Print test 3d model </a>
FDM 3D printers can only recognize gcode files, we need to copy the gcode files to the SD card, and then insert the SD card into the SD card slot of the 3D printer, and then operature the LCD screen to start to print.    
:warning: ***Even if you are familiar with 3D printers, it is recommended that you print at least one 4-color test model to confirm that the machine works normally.***    
- **4.1 Print a one color test file**     
[![](https://img.youtube.com/vi/ITHbO9VxTMo/0.jpg)](https://www.youtube.com/watch?v=ITHbO9VxTMo)
  - **Prepare gcode file**. [:arrow_down: **download xyz_cube zip file**][XYZ_CUBE] and unzip it on PC, and then copy the **xyz_cube.gcode** to SD card. Plug the SD card to the SD socket of machine.
  - **Load filament**. Refer to [:book: **here**][LOAD_FILAMENT] to load all 4 filaments to the extruders and hot end.     
    ***:warning: For M4V6 hotend, you need to load 4 filament to the hotend even you print one color 3d prints.*** 
  - **Print from SD card**. Move item to **Print** item on LCD screen and click the knob and choose **xyz_cube.gcode** file, click knob to start print.
  - **Fine tune nozzle height**. Wait the nozzle and hotbed heated, and watch the distance from the nozzle to the bed when printing the first layer, if it is too fat or too close, double click the knob of LCD screen to open a **"babystep"** menu, and then rotate the knob to fine tune the distance from the nozzle to the bed.
  - **Wait for printing finished**.
- **4.2 Print a 4 color test file**      
[![](https://img.youtube.com/vi/CA8pWOuJYmE/0.jpg)](https://www.youtube.com/watch?v=CA8pWOuJYmE)
  - **Prepare gcode file**. [:arrow_down: **download M4_4CTest.zip file**][M4_4CTEST] and unzip it on PC, and then copy the **M4_4CTest.gcode** to SD card. Plug the SD card to the SD socket of machine.
  - **Load filaments**. Refer to [:book: **here**][LOAD_FILAMENT] to load all 4 filaments to the extruders and the hot end.
  - **Print from SD card**. Move item to **Print** item on LCD screen and click the knob and choose **M4_4CTest.gcode** file, click knob to start print.
  - **Fine tune nozzle height**. Wait the nozzle and hotbed heated, and watch the distance from the nozzle to the bed when printing the first layer, if it is too fat or too close, double click the knob of LCD screen to open a **"babystep"** menu, and then rotate the knob to fine tune the distance from the nozzle to the bed.
  - **Wait for printing finished**.

## <a id="step5">Step 5. Slicing your own 3d model </a>
Before printing your own 3D models, you need to convert the 3d model file (a stl/obj/AMF file which [**downloaded from the internet**](#download) or drawing by yourself) to a gcode file, save this gcode file to SD card and then plug the SD card into the 3d printer. **The process to convert a 3D model into a gcode file is called "slicing"**.   
- **Step 5-1**: Download the slicing software and install it on your computer.   
- **Step 5-2**: Run the slicing software and set some slicing setting according to the characteristics of your 3D model and then do slicing.      
  :pushpin: **For how to download, install and use the slicing software, please refer to the [:point_right:here][SLICING_GUIDE]**.     

## <a id="step6">Step 6. Printing your own 3d model </a>
After sliced, copy the generated gcode file to the SD card and then print it following the [**step 4**](#step4).    

## <a id="step7">Step 7. To use advance features </a>
After you fully understand all the basic operations, you can try some advance functions of this machine. 
For details, please refer to [**Advance Features Use Guide**][ADVANCE_FEATURES].

----
### <a id="download"> :page_with_curl: Websites for free 3D model files</a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   

----
