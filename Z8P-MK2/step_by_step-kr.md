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

-----
# Z8P-MK2 단계별 가이드
3D 프린터 초보자이고 읽어야 할 문서가 너무 많으면 어디서부터 시작해야 할지 모를 수도 있습니다. 걱정하지 마십시오. 다음 단계에서 이러한 문서의 세부 사항을 살펴보겠습니다.
한마디로, 당신이 해야 할 일은 아래 4단계를 포함합니다: **머신 설치 >> 테스트 파일 인쇄 >> 자신의 3D 파일 슬라이싱 >> 3D 파일 인쇄**.
우선, [:arrow_down: **모든 문서를 다운로드**][USER_GUIDE]하여 컴퓨터에 저장하고 이 웹페이지를 브라우저의 즐겨찾기에 추가하는 것이 좋습니다.

## <a id="step1">Step 1. 기계 설치 및 배선 </a>
- **설치**. [:book: **설치 가이드**][INSTALLATION_GUIDE] 및 [ :clapper: **설치 비디오 튜토리얼**][INSTALL_VIDEO]를 참조하여 머신을 설치하세요.
- **배선**. 배선 과정은 기본적으로 해당 소켓에 플러그를 삽입하는 것입니다. 주의할 점은 플러그가 소켓에 완전히 꽂혀 있는지 확인하는 것입니다. 특히 접촉 불량이 발생하는 2PIN 소켓의 경우 더욱 그렇습니다. :warning:  프린트 헤드(핫엔드 어셈블리)를 배선할 때 설치 가이드의 그림을 주의 깊게 참조하고 커넥터 색상과 와이어 색상을 모두 구별하도록 주의하십시오.

## <a id="step2">Step 2. 본체의 전원을 켜고 간단하게 테스트 및 검증을 합니다. </a>
- **전원 켜짐**. AC 전원을 켜기 전에 110V/220V 전원 공급 선택 스위치의 설정이 올바른 위치로 설정되어 있는지 확인하십시오([**이 그림 참조**][IMG_ACSWITCH]). 그런 다음 [**머신의 전원을 켤 수 있습니다**][POWER_ON]. :warning:  기기에는 2개의 전원 스위치가 있습니다. 하나는 ***AC 스위치***(제어 상자 뒷면, AC 전원 소켓 근처에 있는 빨간색 스위치)이고 다른 하나는 ***DC 스위치입니다. ***(컨트롤 박스 오른쪽에 있는 둥근 금속 푸시 버튼 스위치) 먼저 AC 스위치를 켠 다음 **DC 스위치를 약 5초 동안**누르고 있어야 합니다 LCD 나사가 나올 때까지 손을 뗍니다 ZONESTAR 로고 표시 를 눌러 기기를 켜세요.
- **간단한 테스트**. 전원을 켠 후 LCD 화면의 메뉴([**LCD 메뉴 설명**][LCD_MENU])를 조작하여 기기가 정상적으로 작동하는지 확인할 수 있습니다. 다음 단계를 따르세요.
   - **준비>>자동 홈>>모두 홈**을 준비하세요. 이 단계는 기계의 프린트 헤드를 원점 위치로 되돌리는 단계입니다.
   - **준비>>온도>>PLA예열**. 이 단계는 핫엔드를 확인하고 핫베드가 정상적으로 가열될 수 있는지 확인하는 단계입니다. 이 단계에서 노즐의 온도가 60도를 초과하면 프린트 헤드(핫 엔드)의 **오른쪽**에 있는 팬이 회전하는 것을 볼 수 있으며, 이 팬을 "핫 엔드 냉각 팬"이라고 합니다.
   - **준비>>온도>>팬**을 준비하세요. 손잡이를 누르고 팬 속도를 255로 설정하면 **왼쪽이 위로** 팬이 회전해야 합니다.
     위의 3단계를 수행한 후 기본적으로 기기가 정상적으로 작동하는 것으로 확인되면 다음 단계를 진행할 수 있습니다. 부품이 제대로 작동하지 않는 경우 배선을 다시 확인하거나 "전자 장치 자동 테스트"를 수행하여 확인하십시오. ([ :clapper: **머신 자동 테스트 동영상 튜토리얼**][AUTOTEST_VIDEO] 참조).

## <a id="step3">Step 3. 침대 수평 맞추기 </a>
[![](https://img.youtube.com/vi/R3RfGnxx8hY/0.jpg)](https://www.youtube.com/watch?v=R3RfGnxx8hY)     
테스트 파일을 출력하기 전 간단한 베드 레벨링을 하여 노즐과 베드(프린팅 플랫폼) 사이의 높이를 설정해야 프린팅 시 필라멘트가 베드에 잘 붙을 수 있습니다. [**침대 수평 맞추기**][LEVEL_BED]를 참조하여 수행하세요.

## <a id="step4"> Step 4. 3D 모델 프린트 테스트 </a>
FDM 3D 프린터는 gcode 파일만 인식할 수 있습니다. gcode 파일을 SD 카드에 복사한 다음 SD 카드를 3D 프린터의 SD 카드 슬롯에 삽입한 다음 LCD 화면을 조작하여 인쇄를 시작해야 합니다.
:warning:  3D 프린터에 익숙하더라도 4색 테스트 모델을 1개 이상 출력하여 기계가 정상적으로 작동하는지 확인하는 것이 좋습니다.
- **4.1 단색 테스트 파일 인쇄**    
[![](https://img.youtube.com/vi/ITHbO9VxTMo/0.jpg)](https://www.youtube.com/watch?v=ITHbO9VxTMo)
   - **gcode 파일을 준비하세요**. [:arrow_down: **xyz_cube zip 파일 다운로드**][XYZ_CUBE] PC에서 압축을 푼 후 **xyz_cube.gcode**를 SD 카드에 복사하세요. SD 카드를 기기의 SD 소켓에 연결합니다.
   - **필라멘트를 로드하세요**. 필라멘트 4개를 모두 압출기와 핫엔드에 로드하려면 [:book: **여기**][LOAD_FILAMENT]를 참조하세요.
     ***:warning:  M4V6 핫엔드의 경우 단색 3D 프린트를 인쇄하더라도 핫엔드에 필라멘트 4개를 로드해야 합니다.***
   - **SD 카드에서 인쇄**. LCD 화면의 **Print** 항목으로 항목을 이동한 후 손잡이를 클릭하고 **xyz_cube.gcode** 파일을 선택한 후 손잡이를 클릭하여 인쇄를 시작합니다.
   - **노즐 높이를 미세 조정하세요**. 노즐과 핫베드가 가열될 때까지 기다렸다가 첫 번째 레이어를 인쇄할 때 노즐에서 베드까지의 거리를 확인하세요. 너무 뚱뚱하거나 너무 가까운 경우 LCD 화면의 손잡이를 두 번 클릭하여 **"베이비스텝"** 메뉴를 엽니다. 을 누른 다음 손잡이를 돌려 노즐에서 베드까지의 거리를 미세 조정합니다.
   - **인쇄가 완료될 때까지 기다립니다**.
- **4.2 4색 테스트 파일 인쇄**     
[![](https://img.youtube.com/vi/CA8pWOuJYmE/0.jpg)](https://www.youtube.com/watch?v=CA8pWOuJYmE)
   - **gcode 파일을 준비하세요**. [:arrow_down: **M4_4CTest.zip 파일 다운로드**][M4_4CTEST] PC에서 압축을 푼 후 **M4_4CTest.gcode**를 SD 카드에 복사하세요. SD 카드를 기기의 SD 소켓에 연결합니다.
   - **필라멘트를 로드하세요**. [:book: **여기**][LOAD_FILAMENT]를 참조하여 필라멘트 4개를 모두 압출기와 핫엔드에 로드하세요.
   - **SD 카드에서 인쇄**. LCD 화면에서 항목을 **Print** 항목으로 이동하고 손잡이를 클릭한 후 **M4_4CTest.gcode** 파일을 선택하고 손잡이를 클릭하여 인쇄를 시작합니다.
   - **노즐 높이를 미세 조정하세요**. 노즐과 핫베드가 가열될 때까지 기다렸다가 첫 번째 레이어를 인쇄할 때 노즐에서 베드까지의 거리를 확인하세요. 너무 뚱뚱하거나 너무 가까운 경우 LCD 화면의 손잡이를 두 번 클릭하여 **"베이비스텝"** 메뉴를 엽니다. 을 누른 다음 손잡이를 돌려 노즐에서 베드까지의 거리를 미세 조정합니다.
   - **인쇄가 완료될 때까지 기다립니다**.

## <a id="step5">Step 5. 나만의 3D 모델 슬라이스하기 </a>
- 자신만의 3D 모델을 인쇄하기 전에 3D 모델 파일([인터넷에서 다운로드](#download)하거나 직접 그리는 stl/obj/AMF 형식 파일)을 gcode 파일로 변환하고 이 gcode 파일을 저장해야 합니다. SD 카드에 연결한 다음 SD 카드를 3D 프린터에 연결하세요.      
   :pushpin: **3D 모델을 gcode 파일로 변환하는 과정을 *슬라이싱***이라고 합니다.
- 먼저 슬라이싱 소프트웨어를 다운로드하여 컴퓨터에 설치하고 슬라이싱 소프트웨어에서 기계의 매개변수를 설정하거나 3D 프린터 제조업체에서 설정한 기계의 사전 설정 파일을 로드해야 합니다.
- 다음으로 슬라이싱 소프트웨어를 실행해야 하며, 3D 모델 파일의 특성에 따라 일부 슬라이싱 설정을 지정한 다음 슬라이싱을 수행해야 할 수도 있습니다.      
   :pushpin: 권장되는 슬라이싱 소프트웨어는 **PrusaSlicer**입니다. **PrusaSlicer** 다운로드, 설치 및 사용 방법은 [***슬라이싱 가이드***][SLICING_GUIDE]를 참조하세요.

## <a id="step6">Step 6. 나만의 3D 모델 프린팅 </a>
슬라이스 후 생성된 gcode 파일을 SD 카드에 복사한 후 [**4단계**](#step4)에 따라 인쇄합니다.

## <a id="step7">Step 7. 고급 기능을 사용하려면 </a>
모든 기본 작동을 완전히 이해한 후에는 이 기기의 일부 고급 기능을 사용해 볼 수 있습니다.
자세한 내용은 [**고급 기능 사용 가이드**][ADVANCE_FEATURES]를 참조하세요.

----
#### <a id="download"> :page_with_curl: 유명한 무료 3D 모델 다운로드 웹사이트 </a>
   - [thingiverse](https://www.thingiverse.com/)
   - [printables](https://www.printables.com/)
   - [youmagine](https://www.youmagine.com/)

----