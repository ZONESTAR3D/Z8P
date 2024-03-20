## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-kr.md)
<!-- [![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/readme-ar.md) -->

------
# Z8P-MK2 사용설명서
## :warning: 주의하세�?### :loudspeaker: 기기�?사용하기 전에 [:book:"M4V6 사용 �?주의사항"](https://github.com/ZONESTAR3D/Upgrade-kit-guide/blob/main/HOTEND/M4/M4_V6/M4V6_Precaution.md) 주의 깊게 살펴보세�?
### :loudspeaker: M4V6 핫엔드에 4개의 필라멘트�?동시�?로드해야 합니�? 잘못�?작동으로 인해 혼합 색상 핫엔드가 차단�?�?있습니다. 잘못�?작동으로 인해 핫엔드가 막힌 경우에는 보증�?적용되지 않습니다. 필라멘트�?로드하는 방법은 [:book: �?가이드](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filments)�?참조하세�?
### :loudspeaker: 3D 프린�?초보자라�?[:book: 단계�?가이드][step_by_step_guide]�?주의 깊게 읽고, 가이드�?따라 단계별로 수행�?보세�? 3D 프린�?사용 경험�?있으�?분은 최소�?[:book: Step-by-Step Guide][step_by_step_guide]�?간략�?읽어보시�?M4 핫엔드에 필라멘트�?장착하는 방법�?숙지하시�?바랍니다.

### [:clapper: 비디�?튜토리얼 보기](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)
우리�?�?기계�?대�?많은 비디�?튜토리얼�?만들었습니다. [:clapper:**여기**](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)�?클릭하여 시청하세�?

### :file_folder: [1.설치 가이드][INSTALLATION]
- **[:book:설치 안내서][INSTALLATION]**
- **[:blue_book:설치 �?빠른 사용 가이드 PDF 파일](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/Z8PMK2_Installation_and_quick_use_guide.pdf)**
- **[:clapper: 설치 동영�?튜토리얼](https://youtu.be/-oieO7U0LCc)**
- **[:book: LCD 화면 메뉴 설명][LCD_MENU]**
- **[:book: 배선 블록](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PMK2_Wiring_Block.jpg)**
- **[:art: 배선 다이어그램](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PM4-MK2_Wiring_Diagram.jpg)**

### :file_folder: [2.조작 가이드][Operation_Guide]
- **[:book: 기본 조작 가이드][Operation_Guide]**
- **[:book: M4V6 믹스 컬러 핫엔�?사용�?가이드][M4V6_Guide]**
- **고급 기능**
   - **[자동 종료 :book:][auto_shutdown] [:clapper:](https://youtu.be/SJLpmJL-tG4)**
   - **[혼합 컬러 인쇄 :book:][mix_color]**
   - **[침대 자동 레벨�?:book:][auto_leveling] [:clapper:](https://youtu.be/Zoyl6PybsUk)**
   - **[정전 복구 :clapper:](https://youtu.be/f-PpasByiiE)**
   - **[자동 철회 :book:][Auto_Retraction]**
- **[:book: PC에서 인쇄][PrintFromPC]**
  
### :file_folder: [3.테스�?Gcode 파일 인쇄][Test_gcode]
#### :arrow_down: [테스�?gcode 파일 다운로드][Test_gcode]
#### :pencil: 3D 프린팅에�?G 코드란 무엇인가�?
G-code�?3D 프린터가 3차원 물체�?출력하기 위해 필요�?정보 또는 명령어로, 3D 프린터가 이해�?�?있는 언어입니�? G 코드�?STL 파일�?같은 표준 3D 모델�?파일�?특정 3D 프린터가 이해�?�?있는 코드�?변환하�?슬라이싱 소프트웨어에 의해 생성됩니�?
:page_with_curl: [**참조 1**](https://beginner3dprinting.com/what-is-g-code-in-3d-printing/) :page_with_curl: [**참조 2**](https://www.reprap.org/wiki/G-코드)


### :file_folder: [4.슬라이싱 가이드][Slicing_Guide_Z8P]
#### :arrow_down: [silcer 소프트웨�?다운로드 �?슬라이싱 가이드 읽기][Slicing_Guide_Z8P]
#### :pencil: 3D 프린팅에�?슬라이싱이란 무엇인가�?
슬라이싱(Slicing)은 3D 프린터로 물체�?제품�?만들 �?누구�?사용하는 소프트웨어입니다. 소프트웨어는 프린터가 따라�?�?경로�?제공합니�? 슬라이싱 소프트웨어는 이미지�?가져와 3D 프린터가 이해�?�?있는 G 코드�?변환합니다. 이러�?G 코드�?프린터가 디자인을 인쇄하는 �?필요�?방법�?대�?일종�?지침입니다.:page_with_curl: [**참조 1**](https://loveandrobots.com/what-is-slicing-in-3d-printing/ ) :page_with_curl: [**참고자료 2**](https://en.wikipedia.org/wiki/Slicer_(3D_printing))


### :file_folder: [5. 부�?인쇄 stl][PrintParts]
#### :arrow_down: [인쇄 부�?stl 파일 다운로드][PrintParts]

### :link: [6.펌웨어](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2)
- **[:arrow_down: 펌웨�?�?파일](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2).**
- **[:arrow_down: 펌웨�?소스 코드](https://github.com/ZONESTAR3D/source-code-for-3d-printer).**
#### :pencil: bin 파일�?소스 코드가 무엇인가�?
> **펌웨�?�?파일**은 내장 플래시에 기록되는 정확�?메모리입니다.
> **펌웨�?소스코드**�?펌웨어의 핵심 부분입니다. 전체 펌웨어는 서로 다른 하위 모듈�?간주�?�?있습니다. 여러 개의 하위 파일�?나누어져 있습니다. 이러�?파일�?소스 파일이라�?합니�? 그리�?전체 프로그램 파일�?소스파일 또는 소스코드라고 합니�? 이제 우리�?펌웨�?소스 코드�?[**marlin**](https://www.marlinfw.org)�?기반으로 합니�?

### 7.문제 해결
- :book: [**Z8P 문제 해결**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/readme.md)

### 업그레이�?가능한 기능
- **PEI 스프�?히트베드 스티�?:+1:**    
PEI 스프�?강판 핫베�?스티커는 원래 핫베�?스티커보�?내구성이 뛰어납니�? 단면�?부드러�?핫베드를 위로 향하�?하면 인쇄물의 바닥�?�?매끄럽게 만들 수도 있습니다. **[:gift: 구매](http://bit.ly/3GbI9Sr) / [:gift:구매](https://bit.ly/3VkmXOi)**    
- **이중 기어 압출�?:+1:**     
듀�?기어 압출기는 필라멘트�?밀거나 당기�?힘을 크게 증가시켜 압출기에�?필라멘트가 미끄러져 발생하는 인쇄 결함 �?인쇄 실패 가능성�?크게 줄일 �?있습니다.**[:book: 사용 설명서](https://bit.ly/UM_BMG)** **[:gift: 구매 ](https://bit.ly/46Vyd9H) / [:gift: 구매](https://bit.ly/AE_4xBMG)**
- **필라멘트 소진 센서 :+1:**    
�?항목�?업그레이드하�?3D 프린터를 원격으로 제어�?�?있습니다. **[:book: 사용 설명서][guide_FROD]** [:gift:구매](https://www.aliexpress.com/item/4001309957376.html)  
- **WiFi 무선 제어 모듈  :+1:**    
�?항목�?업그레이드하�?3D 프린터를 원격으로 제어�?�?있습니다. **[:book: 사용 설명서][guide_WIFI]** [:gift:구매](https://www.aliexpress.com/item/1005002378551489.html)
- **비혼�?색상 핫엔�? :+1:**    
�?항목�?업그레이드하�?멀�?컬러 모델 프린팅을 위한 컬러 프라�?타워의 크기가 훨씬 작아집니�? **[:book: 사용 설명서][guide_E4]** [:gift:구매](https://www.aliexpress.com/item/1005002951777699.html)
- **직접 구동 압출�?:+1:**    
�?프로젝트�?업그레이드하�?유연�?소재(�? TPU 필라멘트)�?프린트할 �?있습니다. **[:book: 사용 설명서][guide_DDE]** [:gift:구매](https://www.aliexpress.com/item/1005002847644867.html)
- **레이저 엔진**    
�?아이템을 업그레이드하�?3D 프린터를 간단�?레이저 조각 기계�?바꿀 �?있습니다. 고출�?레이저 모듈은 조각 속도�?향상시키거나 융점�?�?높은 재료�?지원할 �?있습니다. **[:book: 사용 설명서][guide_Laser]** [:gift:구매](https://www.aliexpress.com/item/1005004908160260.html)

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
