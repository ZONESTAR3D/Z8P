### Choose Language (Translated by google)
[![](../lanpic/ES.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=es)
[![](../lanpic/FR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=fr)
[![](../lanpic/PT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=pt)
[![](../lanpic/DE.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=de)
[![](../lanpic/IT.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=it)
[![](../lanpic/PL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=pl)
[![](../lanpic/RU.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=ru)
[![](../lanpic/GR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=el)
[![](../lanpic/JP.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=ja)
[![](../lanpic/KR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=ko)
[![](../lanpic/ID.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=id)
[![](../lanpic/TH.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=th)
[![](../lanpic/VN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=vi)
[![](../lanpic/IL.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=iw)
[![](../lanpic/SA.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=ar)
[![](../lanpic/TR.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=tr)
[![](../lanpic/CN.png)](https://github-com.translate.goog/ZONESTAR3D/Z8P/tree/main/Z8P_MK2/step_by_step.md?_x_tr_sl=en&_x_tr_tl=zh-CN)

----
## Step by Step Guide of Z8P-MK2
If you're a beginner with 3D printers, with so much documentation to read, you might not know where to start. Don't worry, we'll go into the details of these documents next step by step. In a word, you need to do 4 steps:    
**Install the machine >> Printing test file >> Slicing your own 3d file >> Printing your 3d file**.        
First at all, we recommend that you [:arrow_down: **download all the documents**](https://downgit.github.io/#/home?url=https:%2F%2Fgithub.com%2FZONESTAR3D%2FZ8P%2Ftree%2Fmain%2FZ8P-MK2) and save them to your computer.

### Step 1. Install the machine
- 1.1 **Installation**. Refer to the [:book: **installation guide**](./1-Installation_Guide/readme.md) and [ :movie_camera: **installation video tutorial**](https://youtu.be/-oieO7U0LCc) to install the machine. 
- 1.2 **Wiring**. the process of wiring is basically to insert the plug into the corresponding socket. What you need to pay attention is to make sure the plug is fully inserted into the socket. Especially for those 2PIN sockets that sometimes make poor contact. In addition, for the wiring of the print head (hotend assembly), please note that there are several sockets of the same type but different colors, please pay attention to plug them according to the color of the socket too.
- 1.3 **Power ON**. Before switching on the AC power, please check whether the setting of the 110V/220V power supply selector switch is set to the correct position ([**refer to this picture**](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/1-Installation_Guide/pic/selectAC.png)). And then you can [**turn on the machine**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#power-on). Please note that the machine has 2 power switches. the one is ***AC switch***(the red switch on the back of the control box, near to the AC Power socket) and another is ***DC switch***(a round metal push button switch on the right side of the control box), you need to turn on the AC switch first and then **press and hold** the DC switch about 5 seconds (release until the LCD screew show ZONESTAR LOGO) to turn on the machine.
- 1.4 **Simply Test**. After power on, you can operate the menu on the LCD screen ([**LCD Menu description**](./1.Installation_and_User_Guide/LCD_DWIN_MENU_Description.md)) to verify whether the machine can work normally. Usually this involves several steps:
  - 1.4.1 **Prepare>>Auto Home>>Home All**. This step is to make the print head of the machine return to the origin.
  - 1.4.2 **Prepare>>Temperature>>Preheat PLA**. This step is to check the hot end and the hot bed can be heated normally.In this step, when the temperature of the nozzle exceeds 60 degrees, you should see a fan on the right side of the print head (hot end) spin up, this is the hot end cooling fan. 
  - 1.4.3 **Prepare>>Temperature>>FAN**. After pressing the knob and setting the fan speed (set to 255), you should now be able to turn the fan on the left side up as well.   
  After these 3 steps, it is basically determined that the machine are working normally, you can proceed to the following steps. If you find that any part is not working properly, please double check the wiring, or to do a auto testing (refer to[ :movie_camera: **machine auto testing video turorial**](https://youtu.be/Mf92BlmKA0A)).
- 1.5 **Bed Level - leveling 4 corners of the bed**. Before printing the test file, you need to do a simple bed leveling to set the height between the nozzle and the bed (printing platform), so that the filament can be sticked on the bed well. Please refer to [**level the bed**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#level-the-bed) to do it.

### Step 2. Print test 3d model
FDM 3D printers can only recognize gcode files, we need to copy the gcode files to the SD card, insert the SD card into the SD card slot of the 3D printer, and then start to print.
- 2.1 **Prepare gcode file - one color**. Locate the **xyz_cube.gcode** file from your downloaded files or [:arrow_down: download it](./3-TestGcode/xyz_cube.zip) directly and unzip it on PC, and then copy the **xyz_cube.gcode** to SD card. Plug the SD card to the SD socket of machine.
- 2.2 **Load filament**. Refer to [**here**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments) to load all 4 color filaments to the extruders and hotend.
- 2.3 **Print from SD card - one color**. Move item to **Print** item on LCD screen and click the knob and choose **xyz_cube.gcode** file, click knob to start print.
- 2.4 **Fine tune nozzle height**. Wait the nozzle and hotbed heating, and when the printer starting to print the first layer, double click the knob of LCD screen to fine tune the distance from the nozzle to the bed, and then wait it to finish.
- 2.5 **Prepare gcode file**. Locate the **M4_4CTest.gcode** file from your downloaded files or [:arrow_down: download it](./3-TestGcode/M4_4CTest.zip) directly and  unzip it on PC, and then copy the **M4_4CTest.gcode** to SD card. Plug the SD card to the SD socket of machine.
- 2.6 **Load filaments**. Refer to [**here**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#load-filaments) to load all 4 color filaments to the extruders and hotend.
- 2.7 **Print from SD card - 4 colors**. Move item to **Print** item on LCD screen and click the knob and choose **M4_4CTest.gcode** file, click knob to start print.
- 2.8 **Check Preload**. Wait the nozzle and hotbed heating, and check if the printer can print out 4 colors lines on the side of the hotbed.
- 2.9 **Fine tune nozzle height**. When the hotend moved to the center of the hotbed, double to click the knob of LCD screen to fine turn the distance from the nozzle to the bed. Wait until the printing is finished.

### Step 3. Slicing your own 3d model
Obviously you will have the need to print your own 3D models. The process of converting a 3D model into a gcode file that can be printed on a machine is called slicing. You need to download and install the slicing software, then import the 3D model file (stl, obj, AMF, etc.) and complete the slicing, and finally copy the generated gcode file to the SD card and print it on the machine. Our recommended slicing software is PrusaSlicer. For detailed instructions, please refer to [4. SlicingGuide](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide).   
Several of the most famous free 3D model download websites:
- [thingiverse](https://www.thingiverse.com/)  
- [printables](https://www.printables.com/)  
- [youmagine](https://www.youmagine.com/)   

### Step 4. Printing your own 3d model
Once you are done slicing, copy the generated gcode file to the SD card, then you can print it in the **step 2**.

### Step 5. To use advanced features
After you fully understand all the basic use of the machine, you can try some advanced functions of the machine. For details, please refer to [Advance features](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide#advance-features).

