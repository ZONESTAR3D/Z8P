## The printer auto shut down when printing from SD card
#### :one: Check AC power switch 
  :warning: The latest version of Z8PM4Pro (Z8PM4Pro-MK2A) has upgraded the AC switch, you can skip this step.
  1. Open the control box and check the wire to connect to the AC power socket, these wire may not connect very well.
  2. Check the AC power switch on the AC power cord socket, if the switch doesn't work well, try to bypass it and try again.
  ![](BypassSwitch.jpg)

#### :two: Upload the newest firmware
Upload the newest firmware to the control board and try again. **[:arrow_down:Download the newest firmware](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P)**   
:warning: Please note the version of your machine before downloading firmware.

#### :three: Check SD card 
1. If you used a SD card extend cable, remove it and plug the SD card into the SD card socket directly and try again.   
2. Format the SD card (Must be FAT32) and copy only one gcode file to SD card and try again.
3. Replace a new SD card (<=32G, format to FAT32) and try again.
4. Choose another gcode file to print.

#### :four: Turn off "PowerLoss Recovery" feature
Turn off the **PowerLoss Recovery** feature from LCD Menu (***Control>>Configre>>PowerLoss Recovery***) and try again.     
:pushpin: **Power Loss Recovery** feature requires frequent writing to the SD card. If there are writing errors, it may cause abnormal crashes during the printing.

### If you have tried all above steps and the question can't be fixed, please contact our technical support team : support@zonestar3d.com.