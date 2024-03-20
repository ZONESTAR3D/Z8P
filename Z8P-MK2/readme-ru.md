## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](./readme.md)
[![](./lanpic/ES.png)](./readme-es.md)
[![](./lanpic/PT.png)](./readme-pt.md)
[![](./lanpic/FR.png)](./readme-fr.md)
[![](./lanpic/DE.png)](./readme-de.md)
[![](./lanpic/IT.png)](./readme-it.md)
[![](./lanpic/RU.png)](./readme-ru.md)
[![](./lanpic/JP.png)](./readme-jp.md)
[![](./lanpic/KR.png)](./readme-kr.md)
<!-- [![](./lanpic/SA.png)](./readme-ar.md) -->

------
# Z8P-MK2 Руководство пользователя 
## :warning: ПОЖАЛУЙСТА, ВНИМАНИЕ
### :loudspeaker: Перед использованием устройства прочтите [:book:"Меры предосторожности при использовании M4V6"](https://github.com/ZONESTAR3D/Upgrade-kit-guide/blob/main/HOTEND/M4/M4_V6/M4V6_Precaution.md) осторожно.
### :loudspeaker: Необходимо одновременно загружать 4 нити накаливания в хотэнд M4V6, неправильная работа может заблокировать хотенд смешивания цветов. Если блокировка горячего конца вызвана неправильной эксплуатацией, гарантия не распространяется. Чтобы узнать, как загружать нити, обратитесь к [:book: этому руководству](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filaments).
### :loudspeaker: Если вы новичок в использовании 3D-принтера, внимательно прочтите [:book: Пошаговое руководство][step_by_step_guide] и следуйте инструкциям, чтобы действовать шаг за шагом. Если у вас есть опыт работы с 3D-принтерами, пожалуйста, также кратко прочитайте [:book: Пошаговое руководство][step_by_step_guide] и убедитесь, что вы знаете, как загружать нить в горячий конец M4.

### [:clapper: Посмотреть видеоурок](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)
Мы создали множество видеоуроков для этой машины. Для просмотра нажмите [:clapper:**здесь**](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial).

### :file_folder: [1.Руководство по установке][INSTALLATION]
- **[:book: Руководство по установке][INSTALLATION]**
- **[:blue_book:Руководство по установке и быстрому использованию PDF-файл](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/Z8PMK2_Installation_and_quick_use_guide.pdf)**
- **[:clapper: Видеоурок по установке](https://youtu.be/-oieO7U0LCc)**
- **[:book: Описание меню ЖК-экрана][LCD_MENU]**
- **[:art: Блок проводки](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PMK2_Wiring_Block.jpg)**
- **[:art: Схема подключения](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PM4-MK2_Wiring_Diagram.jpg)**

### :file_folder: [2.Руководство по эксплуатации][Руководство_по эксплуатации]
- **[:book: Основное руководство по эксплуатации][Operation_Guide]**
- **[:book: Руководство пользователя M4V6 Mix Color Hotend][M4V6_Guide]**
- **Расширенные функции**
   - **[Автовыключение :book:][auto_shutdown] [:clapper:](https://youtu.be/SJLpmJL-tG4)**
   - **[Смешение цветной печати :book:][mix_color]**
   - **[Автовыравнивание кровати :book:][auto_leveling] [:clapper:](https://youtu.be/Zoyl6PybsUk)**
   - **[Восстановление потери питания :clapper:](https://youtu.be/f-PpasByiiE)**
   - **[Автоматическое втягивание :book:][Auto_Retraction]**
- **[:book: Печать с ПК][PrintFromPC]**

### :file_folder: [3.Печать тестовых файлов Gcode][Test_gcode]
#### :arrow_down: [Загрузить тестовый файл gcode][Test_gcode]
#### :pencil: Что такое G-код в 3D-печати?
G-код �?это информация или инструкции, которые требуются 3D-принтеру для печати трехмерного объекта. Это язык, который 3D-принтер может понять. G-код генерируется вашим программным обеспечением для нарезки путем перевода стандартного файла 3D-моделирования, такого как файл STL, в код, понятный вашему конкретному 3D-принтеру.
:page_with_curl: [**Ссылка 1**](https://beginner3dprinting.com/what-is-g-code-in-3d-printing/) :page_with_curl: [**Ссылка 2**](https://www.reprap.org/wiki/G-код)

### :file_folder: [4.Руководство по нарезке][Slicing_Guide_Z8P]
#### :arrow_down: [Загрузите программное обеспечение Silcer и прочитайте руководство по нарезке][Slicing_Guide_Z8P]
#### :pencil: Что такое нарезка в 3D-печати?
Нарезка �?это программа, которую каждый использует при создании объектов и изделий на 3D-принтере. Программное обеспечение указывает принтеру путь, по которому следует следовать. Программное обеспечение для нарезки берет ваше изображение и преобразует его в G-коды, понятные вашему 3D-принтеру. Эти G-коды представляют собой своего рода инструкции о том, как принтеру необходимо распечатать ваш дизайн.:page_with_curl: [**Ссылка 1**](https://loveandrobots.com/what-is-slicing-in-3d-printing/ ) :page_with_curl: [**Ссылка 2**](https://en.wikipedia.org/wiki/Slicer_(3D_printing))

### :file_folder: [5. Распечатать детали stl][PrintParts]
#### :arrow_down: [Загрузить stl-файлы деталей для печати][PrintParts]

### :link: [6.Прошивка](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2)
- **[:arrow_down: Файл прошивки](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2).**
- **[:arrow_down: Исходный код прошивки](https://github.com/ZONESTAR3D/source-code-for-3d-printer).**
#### :pencil: Что такое bin-файл и исходный код?
> **Бин-файл прошивки** �?это именно тот объем памяти, который записан во встроенную флэш-память.
> **Исходный код прошивки** �?это основная часть прошивки. Всю прошивку можно рассматривать как различные подмодули. Он разделен на множество подфайлов. Эти файлы называются исходными файлами. И все файлы программы называются исходным файлом или исходным кодом. Теперь исходный код нашей прошивки основан на [**marlin**](https://www.marlinfw.org).

### 7.Устранение неполадок
- :book: [**Устранение неполадок для Z8P**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/readme.md)

### Обновляемые функции
- **Наклейка с подогревом PEI Springs :+1:**      
Наклейка для рассадника из пружинного стального листа PEI более долговечна, чем оригинальная наклейка для рассадника. Если односторонняя гладкая горячая платформа обращена вверх, это также может сделать нижнюю часть отпечатка более гладкой. **[:gift: Купить](http://bit.ly/3GbI9Sr) / [:gift: Купить](https://bit.ly/3VkmXOi)**
- **Двухшнековый экструдер :+1:**     
Экструдер с двумя шестернями может значительно увеличить силу выталкивания/вытягивания нити, что значительно снижает вероятность дефектов печати и сбоев печати, вызванных проскальзыванием нити в экструдере.**[:book: Руководство пользователя](https://bit.ly/UM_BMG)** **[:gift: Купить ](https://bit.ly/46Vyd9H) / [:gift: Купить](https://bit.ly/AE_4xBMG)**
- **Датчик окончания нити :+1:**    
Обновив этот предмет, вы сможете удаленно управлять своим 3D-принтером. **[:book: Руководство пользователя][guide_FROD]** [:gift:Купить](https://www.aliexpress.com/item/4001309957376.html)
- **Беспроводной модуль управления Wi-Fi :+1:**   
Обновив этот предмет, вы сможете удаленно управлять своим 3D-принтером. **[:book: Руководство пользователя][guide_WIFI]** [:gift:Купить](https://www.aliexpress.com/item/1005002378551489.html)
- **Хотенд без смешивания цветов :+1:**    
Благодаря обновлению этого элемента размер основной цветной башни для печати многоцветных моделей стал намного меньше. **[:book: Руководство пользователя][guide_E4]** [:gift:Купить](https://www.aliexpress.com/item/1005002951777699.html)
- **Экструдер с прямым приводом :+1:**    
Обновив этот проект, вы сможете печатать гибкие материалы (например, нить ТПУ). **[:book: Руководство пользователя][guide_DDE]** [:gift:Купить](https://www.aliexpress.com/item/1005002847644867.html)
- **Лазерный двигатель**   
Обновив этот предмет, вы сможете превратить свой 3D-принтер в простой лазерный гравировальный станок. Лазерные модули более высокой мощности могут повысить скорость гравировки или поддерживать материалы с более высокой температурой плавления. **[:book: Руководство пользователя][guide_Laser]** [:gift:Купить](https://www.aliexpress.com/item/1005004908160260.html)

-----
[step_by_step_guide]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md
[INSTALLATION]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide
[Operation_Guide]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide
[M4V6_Guide]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/M4%20%204-IN-1-OUT%20Mixing%20Color%20Hotend/M4_V6
[Test_gcode]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode
[Slicing_Guide_Z8P]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide
[PrintParts]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/5-PrintParts/
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[mix_color]: https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color
[auto_leveling]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling
[auto_shutdown]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Shut_Down
[Auto_Retraction]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Retraction
[PrintFromPC]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/PrintFromPC
[guide_FROD]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[guide_WIFI]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[guide_E4]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/E4%204-IN-1-OUT%20Non-Mixing%20Color%20Hotend
[guide_DDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Direct_Drive_Extrruder
[guide_Laser]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Laser_Engraving
