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

-----
# Z8P-MK2 Step-by-Step Guide
If you're a beginner with 3D printers, with so much documentation to read, you might not know where to start. Don't worry, we'll go into the details of these documents next step by step.   
In a word, what you need to do includes the below 4 steps: **Install the machine >> Printing test file >> Slicing your own 3d file >> Printing your 3d file**.        
First at all, we recommend that you [:arrow_down: **download all the documents**][USER_GUIDE] and save them to your computer, and add this web page to your browser's favorites.
## Step 1. Install the machine and Wiring
- **Installation**. Refer to the [:book: **installation guide**][INSTALLATION_GUIDE] and [ :clapper: **installation video tutorial**][INSTALL_VIDEO] to install the machine. 
- **Wiring**. The process of wiring is basically to insert the plug into the corresponding socket. What you need to pay attention is to make sure the plug is fully inserted into the socket. Especially for those 2PIN sockets that sometimes make poor contact. :warning: When you wiring the print head (hotend assembly), please refer to the pictures in the installation guide carefully and pay attention to distinguish both the color of the connectors and the color of the wires.
## Step 2. Power on the maiche and do a simply test and verify
- **Power ON**. Before switching on the AC power, please check whether the setting of the 110V/220V power supply selector switch is set to the correct position ([**refer to this picture**][IMG_ACSWITCH]). And then you can [**turn on the power of machine**][POWER_ON]. :warning: Please note that the machine has 2 power switches, one is ***AC switch***(the red switch on the back of the control box, near to the AC Power socket) and another is ***DC switch***(a round metal push button switch on the right side of the control box), you need to turn on the AC switch first and then press and **hold the DC switch about 5 seconds** (release until the LCD screew show ZONESTAR LOGO) to turn on the machine.
- **Simply Test**. After power on, you can operate the menu on the LCD screen ([**LCD Menu description**][LCD_MENU]) to verify whether the machine can work normally, the steps as below:
  - **Prepare>>Auto Home>>Home All**. This step is to make the print head of the machine return to the origin position.
  - **Prepare>>Temperature>>Preheat PLA**. This step is to check the hot end and the hot bed can be heated normally. In this step, when the temperature of the nozzle exceeds 60 degrees, you should see a fan on the **right side** of the print head (hot end) spin up, this fan is called "hot end cooling fan". 
  - **Prepare>>Temperature>>FAN**. Press the knob and setting the fan speed to 255, the fan on the **left side up** should spin up.   
    After did the above 3 steps, it is basically determined that the machine are working normally, you can proceed the following steps. If you find that any part is not working properly, please double check the wiring, or to do a "electronics auto testing" to check. (refer to[ :clapper: **machine auto testing video turorial**][AUTOTEST_VIDEO]).
## Step 3. Level the bed
Before printing the test file, you need to do a simple bed leveling to set the height between the nozzle and the bed (printing platform), so that the filament can be sticked on the bed well when printing. Please refer to [**level the bed**][LEVEL_BED] to do it.

## <a id="step4">Step 4. Print test 3d model </a>
FDM 3D printers can only recognize gcode files, we need to copy the gcode files to the SD card, and then insert the SD card into the SD card slot of the 3D printer, and then operature the LCD screen to start to print.    
:warning: Even if you are familiar with 3D printers, it is recommended that you print at least one 4-color test model to confirm that the machine works normally.
- **4.1 Print a one color test file**
  - **Prepare gcode file**. [:arrow_down: **download xyz_cube zip file**][XYZ_CUBE] and unzip it on PC, and then copy the **xyz_cube.gcode** to SD card. Plug the SD card to the SD socket of machine.
  - **Load filament**. Refer to [:book: **here**][LOAD_FILAMENT] to load all 4 filaments to the extruders and hot end.     
    ***:warning: For M4V6 hotend, you need to load 4 filament to the hotend even you print one color 3d prints.*** 
  - **Print from SD card**. Move item to **Print** item on LCD screen and click the knob and choose **xyz_cube.gcode** file, click knob to start print.
  - **Fine tune nozzle height**. Wait the nozzle and hotbed heated, and watch the distance from the nozzle to the bed when printing the first layer, if it is too fat or too close, double click the knob of LCD screen to open a **"babystep"** menu, and then rotate the knob to fine tune the distance from the nozzle to the bed.
  - **Wait for printing finished**.
- **4.2 Print a 4 color test file**
  - **Prepare gcode file**. [:arrow_down: **download M4_4CTest.zip file**][M4_4CTEST] and unzip it on PC, and then copy the **M4_4CTest.gcode** to SD card. Plug the SD card to the SD socket of machine.
  - **Load filaments**. Refer to [:book: **here**][LOAD_FILAMENT] to load all 4 filaments to the extruders and the hot end.
  - **Print from SD card**. Move item to **Print** item on LCD screen and click the knob and choose **M4_4CTest.gcode** file, click knob to start print.
  - **Fine tune nozzle height**. Wait the nozzle and hotbed heated, and watch the distance from the nozzle to the bed when printing the first layer, if it is too fat or too close, double click the knob of LCD screen to open a **"babystep"** menu, and then rotate the knob to fine tune the distance from the nozzle to the bed.
  - **Wait for printing finished**.
## Step 5. Slicing your own 3d model
- Before printing your own 3D models, you need to convert the 3d model file (a stl/obj/AMF format file which [downloaded from the internet](#download) or drawing by yourself) to a gcode file, save this gcode file to SD card and then plug the SD card to your 3d printer.      
  :pushpin: **The process of converting a 3D model into a gcode file is called *slicing***.   
- Firstly you need to download the slicing software and install it on your computer, and set the parameters of your machine in the slicing software or load the preset file of your machine which set by the 3d printer manufacture.   
- Next, you need to run the slicing software, and may also need to set some slicing setting according to the characteristics of your 3D model file and then do slicing.      
  :pushpin: The recommended slicing software is **PrusaSlicer**, for how to download, install and use **PrusaSlicer** , please refer to [***Slicing Guide***][SLICING_GUIDE].     
#### <a id="download"> :page_with_curl: Famous free 3D model download websites </a>
  - [thingiverse](https://www.thingiverse.com/)  
  - [printables](https://www.printables.com/)  
  - [youmagine](https://www.youmagine.com/)   
## Step 6. Printing your own 3d model
After sliced, copy the generated gcode file to the SD card and then print it following the [**step 4**](#step4).
## Step 7. To use advance features
After you fully understand all the basic operations, you can try some advance functions of this machine. 
For details, please refer to [**Advance Features Use Guide**][ADVANCE_FEATURES].

-----
[USER_GUIDE]: https://downgit.github.io/#/home?url=https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2
[INSTALLATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/readme.md
[INSTALL_VIDEO]: https://youtu.be/-oieO7U0LCc
[IMG_ACSWITCH]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/1-Installation_Guide/pic/selectAC.png
[POWER_ON]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#power-on
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[LEVEL_BED]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#level-the-bed
[XYZ_CUBE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/xyz_cube.zip
[LOAD_FILAMENT]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments
[M4_4CTEST]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode/M4_4CTest.zip
[SLICING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide/readme.md
[AUTOTEST_VIDEO]: https://youtu.be/iSsuy2ePWw8
[ADVANCE_FEATURES]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#advance-features