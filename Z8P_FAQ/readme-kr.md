## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-kr.md)
[![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-ar.md)

----
# Z8P 문제 해결

-----
## 참조
제품의 문제를 찾아 해결하려면 자동 테스트 기능을 사용해야 할 수도 있고, 컨트롤 박스를 열어 배선을 확인하거나 모터 구동 전류를 조정하거나 "스왑 테스트"를 사용하여 전자 부품을 확인해야 할 수도 있습니다. .. 여기에는 참고할 수 있는 가이드, 사진 및 비디오 튜토리얼이 나열되어 있습니다.
### 배선
- [:art: 컨트롤 박스 여는 방법](./pic/OpenControlBox.png)
- [:art: 제어보드 배선](./pic/Z8P_wiring.png)

### 전자부품 자동 테스트
Z8P에는 전자 자동 테스트 프로그램이 내장되어 있습니다. 이 프로그램을 사용하면 전자 부품에 문제가 발생할 때 문제가 어디서 발생하는지 확인할 수 있습니다. 이 프로그램을 시작하려면 "**정보**" 메뉴를 열고 손잡이를 돌려 "**날짜: xx-xx-xx**" 항목을 가리킨 다음 손잡이를 5번 눌러야 합니다.
#### 비디오 튜토리얼
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### "스왑 테스트"에 대해
기계에 기능적 문제가 있음을 발견하고 문제의 원인이 여러 가지 가능성이 있는 경우(여러 부품으로 인해 동일한 문제가 발생할 수 있음) 소위 "**스왑 테스트**를 사용할 수 있습니다. "를 통해 최대한 빨리 문제의 원인을 찾아보세요.
예를 들어 왼쪽 Z축 모터가 작동하지 않으면 배선, 스테퍼 모터, 모터 케이블, 제어 보드의 모터 구동 모듈 또는 제어 보드에서 문제가 발생할 수 있습니다. 기계에는 왼쪽 Z 드라이브 시스템과 오른쪽 Z 드라이브 시스템의 두 세트의 Z축 드라이브 시스템이 동일하므로 왼쪽과 오른쪽에 동일한 부품/구성 요소/와이어를 하나씩 교체하여 확인할 수 있습니다. 문제는 어디서 오는가?
교환 테스트를 수행할 수 있는 기계 부품은 다음과 같습니다.
- X/Y 모터 및 리미트 스위치.
- ZL/ZR 모터 및 리미트 스위치
- 압출기 모터 4세트
- 핫베드 및 핫엔드의 카트리지 히터 및 온도 센서.

-----
## 내용물
- **[기기를 시작할 수 없습니다.](./Issue_of_startup/readme.md)**
<!-- - **[핫엔드가 막혔습니다/막혔습니다](./Issue_mix_color_hotend_clogged/readme.md)** -->
- **[발열 문제](./Issue_heating/readme.md)**
- **[SD 카드에서 인쇄 시 자동 종료](./Issue_auto_shut_down/readme.md)**
- **[압출기 블록 문제 해결 방법](./Issue_extruder_blocked/readme.md)**
- **[압출기 방전 부족 문제 해결 방법](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Cura에서 USB를 연결할 때 충돌이 발생함](./issue_of_connect_USB_in_Cura/readme.md)**
- **[SD 카드에서 인쇄할 때 프린터가 자동으로 일시 중지됩니다.](./Issue_auto_pause/readme.md)**
- **[SD 카드를 읽지 못한 문제](./Issue_not_read_sdcard/readme.md)**
- **[LCD 화면 손잡이 문제](#dwinscreen)**

----
## 기타 참고자료
- **[44가지 일반적인 3D 프린트 문제](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[모든 문제 및 해결 방법(@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">LCD 화면 손잡이 문제</a>
LCD 화면의 손잡이가 걸린 경우 [:선물: 이 링크](https://www.aliexpress.com/item/3256805596235491.html)를 클릭하여 교체용 키패드를 구입할 수 있습니다. 귀하의 제품이 보증 기간(패키지 수령일로부터 12개월 이내) 이내인 경우, 주문 후 당사에 문의해 주시면 A/S를 제공해 드리겠습니다.
LCD 화면의 키패드를 교체하는 방법은 비디오 튜토리얼을 시청하십시오:
- 용접 버전(구)에 대해서는 [:clapper: 이 영상](https://youtu.be/Xwfczp3nLOY)을 참조하세요.
- FPC 버전(최신)에 대해서는 [:clapper: 이 영상](https://youtu.be/z9E6glRZRIQ)을 참조하세요.
####
![](./pic/keypad.jpg)

-----
## :email: FAQ를 읽은 후에도 문제 해결 방법을 찾을 수 없는 경우 기술 지원팀(support@zonestar3d.com)에 문의하세요.