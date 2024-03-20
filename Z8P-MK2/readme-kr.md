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
## :warning:  주의하세요
### :loudspeaker: 기기를 사용하기 전에 [:book:"Precautions for using M4V6"](https://github.com/ZONESTAR3D/Upgrade-kit-guide/blob/main/HOTEND/M4/M4_V6/M4V6_Precaution.md) 주의 깊게 살펴보세요.
### :loudspeaker: M4V6 핫엔드에 4개의 필라멘트를 동시에 로드해야 합니다. 잘못된 작동으로 인해 혼합 색상 핫엔드가 차단될 수 있습니다. 잘못된 작동으로 인해 핫엔드가 막힌 경우에는 보증이 적용되지 않습니다. 필라멘트를 로드하는 방법은 [:book: 이 가이드](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filments)를 참조하세요.
### :loudspeaker: 3D 프린터 초보자라면 [:book: Step-by-Step Guide][step_by_step_guide]를 주의 깊게 읽고, 가이드에 따라 단계별로 수행해 보세요. 3D 프린터 사용 경험이 있으신 분은 최소한 [:book: Step-by-Step Guide][step_by_step_guide]를 간략히 읽어보시고 M4 핫엔드에 필라멘트를 장착하는 방법을 숙지하시기 바랍니다.

### [:clapper: 비디오 튜토리얼 보기](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)
우리는 이 기계에 대한 많은 비디오 튜토리얼을 만들었습니다. [:clapper:**여기**](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)를 클릭하여 시청하세요.

### :file_folder: [1.설치 가이드][INSTALLATION]
- **[:book:  설치 안내서][INSTALLATION]**
- **[:blue_book: 설치 및 빠른 사용 가이드 PDF 파일](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/Z8PMK2_Installation_and_quick_use_guide.pdf)**
- **[:clapper: 설치 동영상 튜토리얼](https://youtu.be/-oieO7U0LCc)**
- **[:book: LCD 화면 메뉴 설명][LCD_MENU]**
- **[:art: 배선 블록](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PMK2_Wiring_Block.jpg)**
- **[:art: 배선 다이어그램](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PM4-MK2_Wiring_Diagram.jpg)**

### :file_folder: [2.조작 가이드][Operation_Guide]
- **[:book: 기본 조작 가이드][Operation_Guide]**
- **[:book: M4V6 믹스 컬러 핫엔드 사용자 가이드][M4V6_Guide]**
- **고급 기능**
   - **[자동 종료:book:][auto_shutdown] [:clapper:](https://youtu.be/SJLpmJL-tG4)**
   - **[혼합 컬러 인쇄 :book:][mix_color]**
   - **[침대 자동 레벨링 :book:][auto_leveling] [:clapper:](https://youtu.be/Zoyl6PybsUk)**
   - **[정전 복구 :clapper:](https://youtu.be/f-PpasByiiE)**
   - **[자동 철회 :book:][Auto_Retraction]**
- **[:book: PC에서 인쇄][PrintFromPC]**
  
### :file_folder: [3.테스트 Gcode 파일 인쇄][Test_gcode]
#### :arrow_down: [테스트 gcode 파일 다운로드][Test_gcode]
#### :pencil: 3D 프린팅에서 G 코드란 무엇인가요?
G-code는 3D 프린터가 3차원 물체를 출력하기 위해 필요한 정보 또는 명령어로, 3D 프린터가 이해할 수 있는 언어입니다. G 코드는 STL 파일과 같은 표준 3D 모델링 파일을 특정 3D 프린터가 이해할 수 있는 코드로 변환하여 슬라이싱 소프트웨어에 의해 생성됩니다.
:page_with_curl: [**참조 1**](https://beginner3dprinting.com/what-is-g-code-in-3d-printing/) :page_with_curl: [**참조 2**](https://www.reprap.org/wiki/G-code)

### :file_folder: [4.슬라이싱 가이드][Slicing_Guide_Z8P]
#### :arrow_down: [silcer 소프트웨어 다운로드 및 슬라이싱 가이드 읽기][Slicing_Guide_Z8P]
#### :pencil: 3D 프린팅에서 슬라이싱이란 무엇인가요?
슬라이싱(Slicing)은 3D 프린터로 물체나 제품을 만들 때 누구나 사용하는 소프트웨어입니다. 소프트웨어는 프린터가 따라야 할 경로를 제공합니다. 슬라이싱 소프트웨어는 이미지를 가져와 3D 프린터가 이해할 수 있는 G 코드로 변환합니다. 이러한 G 코드는 프린터가 디자인을 인쇄하는 데 필요한 방법에 대한 일종의 지침입니다.:page_with_curl: [**참조 1**](https://loveandrobots.com/what-is-slicing-in-3d-printing/) :page_with_curl: [**참고자료 2**](https://www.reprap.org/wiki/G-code)

### :file_folder: [5. 부품 인쇄 stl][PrintParts]
#### :arrow_down: [인쇄 부품 stl 파일 다운로드][PrintParts]

### :link: [6.펌웨어](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P)
- **[:arrow_down: 펌웨어 빈 파일](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P).**
- **[:arrow_down: 펌웨어 소스 코드](https://github.com/ZONESTAR3D/source-code-for-3d-printer).**
#### :pencil: bin 파일과 소스 코드가 무엇인가요?
> **펌웨어 빈 파일**은 내장 플래시에 기록되는 정확한 메모리입니다.
> **펌웨어 소스코드**는 펌웨어의 핵심 부분입니다. 전체 펌웨어는 서로 다른 하위 모듈로 간주될 수 있습니다. 여러 개의 하위 파일로 나누어져 있습니다. 이러한 파일을 소스 파일이라고 합니다. 그리고 전체 프로그램 파일을 소스파일 또는 소스코드라고 합니다. 이제 우리의 펌웨어 소스 코드는 [**marlin**](https://www.marlinfw.org)을 기반으로 합니다.

### 7.문제 해결
- :book: [**Z8P 문제 해결**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/readme.md)

### 업그레이드 가능한 기능
- **PEI 스프링 히트베드 스티커 :+1:**
PEI 스프링 강판 핫베드 스티커는 원래 핫베드 스티커보다 내구성이 뛰어납니다. 단면이 부드러운 핫베드를 위로 향하게 하면 인쇄물의 바닥을 더 매끄럽게 만들 수도 있습니다. **[:gift: 구매](http://bit.ly/3GbI9Sr) / [:gift: 구매](https://bit.ly/3VkmXOi)**
- **이중 기어 압출기 :+1:**
듀얼 기어 압출기는 필라멘트를 밀거나 당기는 힘을 크게 증가시켜 압출기에서 필라멘트 미끄러짐으로 인한 인쇄 결함 및 인쇄 실패 가능성을 크게 줄일 수 있습니다.**:book: [사용 설명서](https://bit.ly/UM_BMG)** **[:gift: 구매](https://bit.ly/46Vyd9H) / [:gift: 구매](https://bit.ly/AE_4xBMG)**
- **필라멘트 소모 센서 :+1:**
이 항목을 업그레이드하면 3D 프린터를 원격으로 제어할 수 있습니다. **[:book: 사용 설명서][guide_FROD]** [:gift: 구매](https://www.aliexpress.com/item/4001309957376.html)
- **WiFi 무선 제어 모듈:+1:**
이 항목을 업그레이드하면 3D 프린터를 원격으로 제어할 수 있습니다. **[:book: 사용 설명서][guide_WIFI]** [:gift: 구매](https://www.aliexpress.com/item/1005002378551489.html)
- **비혼합 색상 핫엔드 :+1:**
이 항목을 업그레이드하면 멀티 컬러 모델 프린팅을 위한 컬러 프라임 타워의 크기가 훨씬 작아집니다. **[:book: 사용 설명서][guide_E4]** [:gift: 구매](https://www.aliexpress.com/item/1005002951777699.html)
- **직접 구동 압출기 :+1:**
이 프로젝트를 업그레이드하면 유연한 소재(예: TPU 필라멘트)를 프린트할 수 있습니다. **[:book: 사용 설명서][guide_DDE]** [:gift: 구매](https://www.aliexpress.com/item/1005002847644867.html)
- **레이저 엔진**
이 아이템을 업그레이드하면 3D 프린터를 간단한 레이저 조각 기계로 바꿀 수 있습니다. 고출력 레이저 모듈은 조각 속도를 향상시키거나 융점이 더 높은 재료를 지원할 수 있습니다. **[:book: 사용 설명서][guide_Laser]** [:gift: 구매](https://www.aliexpress.com/item/1005004908160260.html)

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
