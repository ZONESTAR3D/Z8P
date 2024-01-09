## The printer auto shut down when printing from SD card
:warning: The latest version of Z8PM4Pro (Z8PM4Pro-MK2A) has upgraded the AC switch. You can skip the point 1 and 2, start from point 3.
1. Open the control box and check the wire to connect to the AC power socket, these wire may not connect very well.
2. Check the AC power switch on the AC power cord socket, if the switch doesn't work well, try to bypass it and try again.
![](BypassSwitch.jpg)

3. Upload the newest firmware to the control board and try again.
**[:arrow_down:Download the newest firmware](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P)**   
:warning: Please note the version of your machine before downloading firmware.
4. If you used a SD card extend cable, remove it and plug the SD card into the SD card socket directly and try again.   
5. Format the SD card (Must be FAT32) and copy only one gcode file to SD card and try again.
6. Replace a new SD card (<=32G, format to FAT32) and try again.
7. Print another gcode file and try again.
8. Turn off the **PowerLoss Recovery** feature and try again (***Control>>Configre>>PowerLoss Recovery***).     
:pushpin: **Power Loss Recovery** feature requires frequent writing to the SD card. If there are writing errors, it may cause abnormal crashes during the printing.

### If you have tried all above steps and the question can't be fixed, please contact our technical support team : support@zonestar3d.com.