# Z8P Troubleshooting

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
- **[The machine can't start up](./Issue_of_startup/readme.md)**
- **[Hot end is blocked/clogged](./Issue_mix_color_hotend_clogged/readme.md)**
- **[Heating issue](./Issue_heating/readme.md)**
- **[Auto shut down when printing from SD card](./Issue_auto_shut_down/readme.md)**
- **[How to fix Extruder block issue](./Issue_extruder_blocked/readme.md)**
- **[How to fix Extruder insufficient discharge issue](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Crash when connecting USB in Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[The printer auto pause when printing from SD card](./Issue_auto_pause/readme.md)**
- **[Not read SD card issue](./Issue_not_read_sdcard/readme.md)**
- **[LCD screen knob issue](#lcd-screen-knob-issue)**

----
## Other references
- **[44 Common 3D Print Problems](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[All Problems & Solutions (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## LCD screen knob issue
If you find that the knob of the LCD screen is stuck, you can click on [:gift: this link](https://www.aliexpress.com/item/3256805596235491.html) to purchase a replacement keypad. If your product is within the warranty period (within 12 months from the date of receiving the package), please contact us after placing the order, and we will provide you with after-sales service.     
How to replace the keypad of the LCD screen, please watch the video tutorial:
- For the welding version (older), please refer to [:clapper: this video](https://youtu.be/Xwfczp3nLOY).   
- For the FPC version (newer), please refer to [:clapper: this video](https://youtu.be/z9E6glRZRIQ).  
![](./pic/keypad.jpg)

-----
## :email: If you can't find a solution to solve your problem after readed the FAQ , please contact our technical support team : support@zonestar3d.com .


