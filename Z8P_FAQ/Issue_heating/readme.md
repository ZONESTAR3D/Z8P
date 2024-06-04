## <a id="choose-language">:globe_with_meridians: Choose language</a>
[![](../lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme.md)
[![](../lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-es.md)
[![](../lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-pt.md)
[![](../lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-fr.md)
[![](../lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-de.md)
[![](../lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-it.md)
[![](../lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-ru.md)
[![](../lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-jp.md)
[![](../lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-kr.md)
[![](../lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/Issue_heating/readme-ar.md)

-----
# Heating issues
## Before checking
1. Ensure that the room temperature is above 15℃ .
2. If the hot bed or hot end (nozzle) is still hot, wait for them to cool.
3. Turn on the power and observe the "status bar" on the LCD display.   
##### ![](./LCD_screen.jpg)  
> 
    1: hot end temperature       2: hotbed temperature
Normally, the showed temperature of the hot end and hot bed should be approximately to the room temperature. 
If the current room temperature is low than 15℃ but both current temperature of the hot end and hot bed are shows 0℃, check the firmware version first.

## Contents
- **[Hot end issue](#a)**
  - **[Hot end always shows 0℃](#a1)**
  - **[Hot end always shows round of 100℃](#a2)**
  - **[Hot end temperature does not rise](#a3)**
  - **[Hot end cannot be heated to the set temperature](#14)**
  - **[Hot end run away issue](#a5)**
- **[Hot bed issue](#b)**
  - **[Hot bed always shows 0℃](#b1)**
  - **[Hot bed max temperature issue](#b2)**
  - **[Hot bed temperature does not rise](#b3)**
  - **[Hot bed can be heated to over 100℃](#b4)**

-----
## <a id="a">Hot end issue</a>
### <a id="a1">Hot end always shows 0℃</a>
##### ![](hotend_min_temperature.jpg)      
If the current temperature of the hot end shows 0 degrees, there may be two reasons:
1. Check the temperature sensor wire of hot end is connected well.     
2. If both current of the hotend and heatbed are shows 0 degree and the current ambient temperature is low than 20℃, please try to upload the newest firmware and try again.    
:pushpin: **HINT**: Z8PM4Pro-MK2 and Z8PM4Pro-MK2A use different versions of motherboards. If your upgraded firmware does not match the version of the motherboard, there will be significant errors in temperature measurement results.

### <a id="a2">Hot end always shows round of 100℃ </a>
If the temperature of the hot end always shows a high temperature (about 100℃) but the nozzle is cold in reality, then it is very likely that you have connected the temperature sensor of the hot end to the fan by mistake, please pay attention to check the wiring of the hot end.   
- **For Z8P-MK2, check the extend wire of hot end**    
##### ![](./Hotend_wiring.jpg)      
- **Check the control board side**     
##### ![](../pic/Z8P_wiring.png)

### <a id="a3">Hot end temperature does not rise </a>
- Check if the heater connector plug well.  
- Use a multi-meter to measure the resistance of the heater, the resistance should be about 10 Ohm. If not, heater is burn.
##### ![](./measure.jpg)
- Open the control box and check if the heater wire is connected well to the control board.
##### ![](./WireOfheater.jpg)
- [:link: Open the control box](../How_to_open_the_control_box.jpg) and check if the LED4 will light when heating the hotend. 
##### <a id="led"></a> ![](LEDs.jpg) 

### <a id="a4">Hot end cannot be heated to the set temperature </a>
If the hotend temperature is raise, but it can't be reached to the setting temperature. LCD will shows **hot end heating fail** after a period of time.     
##### ![](./hotend_heating_fail.jpg)
- **If hot end cannot be heated to more than 150℃:** Check the temperature sensor on the side of hotend, it may be drop out from the heat block. ***In this case, the hot end will not be heated to more than 150℃ usually.***
<!-- ![](sensorhotenddrop.jpg)       -->
- **If hot end can be heated to more than 220℃, but it is unstable**, please refer to the [nex step](#a5)

### <a id="a5">Hot end run away issue </a>
The temperature of the hot end is unstable, sometimes show a "run away" issue.     
##### ![](./runaway.jpg)
  - Check the cooling FAN installation, if it is blowed inside to the housing, please change to blowed outside.
##### ![](./coolingfan.jpg)
  - Do once  ***Control>>Restore Defaults"***, and then heating again.  
#### PID auto tune
If you did the above two steps but the question can't be solved, do the below steps: ***Control>>Configre>>Hotend PID>>PID auto tune: 200 {200 for printing PLA or 240 for printing PETG/ABS}***, and wait until it done. [:movie_camera: **Video Tutorial**](./PID_Auto_Tune.gif).      

-----
## <a id="b">Hot bed issue </a>
### <a id="b1">Hot bed always shows 0℃ </a>
##### ![](hotbed_min_temperature.jpg)   ![](./Hotbed_wiring.jpg)    
If the current temperature of the hot bed shows 0 degrees, there may be two reasons:
1. Check the temperature sensor wire of hot bed is connected well.   
2. If both current of the hotend and heatbed are shows 0 degree and the current ambient temperature is low than 20℃, please try to upload the newest firmware and try again.    

### <a id="b2">Hot bed max temperature issue </a>
When you find the LCD screen shows a "HEATBED Err.: max temperature" screen.      
##### ![](./hotbed_max_temperature.jpg)   
- Disconnect the wire of the hotbed temperature sensor and power off and power on the machine again, if it doesn't show this screen again, replace a new temperature sensor.
- Open the control box and discounect the temperature sensor wire from the control board, and then power off and power on the machine again, if it was fixed, replace a new temperature sensor. If it wasn't solved, replace a new control board.

### <a id="b3">Hot bed temperature does not rise </a>
- Check if [:point_up: the power wire of hot bed](#b1) was connected well.
- Open the control box ([:point_right:Picture](../pic/OpenControlBox.png)) and check if the power wire of hot bed connect well with the control board.     
![](./heatbed_power.jpg)
- Open the control box ([:point_right:Picture](../pic/OpenControlBox.png)) and check if the [:point_up: LED3](#led) will light when heating the hot bed, if not, it means the MOSFET of the control boad is damaged and need to be replaced.

### <a id="b4">Hot bed can be heated to over 100℃ </a>
- Do not put the fan or air conditioner outlet toward the machine.
- If the temperature of the room is low (<15℃), try to wrap around the machine.

--------
## Contact with our support team
:email: If you can't find a solution to solve your problem after readed the FAQ , please contact our technical support team : support@zonestar3d.com.

