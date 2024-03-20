## <a id="choose-language">:globe_with_meridians: Choose language </a>
[![](../../lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme.md)
[![](../../lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-es.md)
[![](../../lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-pt.md)
[![](../../lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-fr.md)
[![](../../lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-de.md)
[![](../../lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-it.md)
[![](../../lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-ru.md)
[![](../../lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-jp.md)
[![](../../lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-kr.md)
<!-- [![](../../lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling/readme-ar.md) -->

----
## 침대 자동레벨링 사용안내
#### :warning: 참고하세요:
1. 설치 매뉴얼에 명시된 대로 기계의 편심 컬럼을 조정했는지 확인하십시오. 운송 중 제품이 손상되지 않도록 공장에서 편심 기둥을 상대적으로 느슨한 위치로 조정합니다. 특히 핫베드 브래킷의 편심 기둥을 조정하여 핫베드가 크게 흔들리지 않도록 해야 합니다. 자세한 내용은 [이 페이지][ECCENTRIC]를 참조하세요.
2. 레벨링 장치의 설치 위치를 주의 깊게 확인하시기 바랍니다. 센서 하단이 노즐보다 **2~3mm** 높아야 합니다. 추신: **PEI 스프링 스티커를 업그레이드**하는 경우 노즐보다 **4~5mm** 높아야 합니다.
###### ![](./install.jpg)
3. 베드 자동 레벨링을 수행할 때 다음 단계를 단계별로 따르십시오. **[레벨 코너](#step1)>>[캐치 프로브 Z 오프셋](#step2)>>[베드 레벨링](#step3)** .
4. 베드 자동 레벨링을 수행한 후 첫 번째 개체를 인쇄할 때 첫 번째 레이어를 인쇄할 때 Z 오프셋을 조정해야 합니다(*커서가 **Tune** 메뉴를 가리킨 다음 손잡이를 두 번 눌러 **Babystep(베이비스텝)** 메뉴에서 노즐과 핫베드 사이의 높이를 관찰하고 손잡이를 돌려 적절한 위치로 조정합니다*). 조정이 완료되면 다음 인쇄 시 더 이상 조정할 필요가 없습니다.
5. 히팅베드를 고정한 나사를 수동으로 조정하고, 핫엔드를 교체하고, 레벨링 센서를 다시 설치하거나 **Probe Z Offset(Z 프로브 오프셋)** 값을 변경할 수 있는 기타 작업을 수행한 후에는 모든 베드 레벨링 단계를 다시 반복해야 합니다.

-----
### <a id="step1"> :one: 수평 코너</a>
:loudspeaker: 자동 베드 레벨링 기능은 절대값이 아닌 Z축 높이에서 핫베드의 다양한 위치의 상대적인 오프셋을 수정하는 데 사용됩니다. Bed Auto Leveling을 실행하기 전에 기계가 Z축 시작점(기계의 **Z축 절대 영점**이라고 함)의 정확한 절대값을 얻을 수 있도록 **코너 레벨 조정**을 수행해야 합니다. 아래와 같은 단계:
##### 1단계: 3D 프린터의 전원을 켜고 LCD 메뉴에서 "Prepare>>Auto Home>>Home All(준비>>자동 홈>>모두 홈)"을 수행하고 핫엔드가 홈 위치로 갈 때까지 기다립니다.
##### 2단계: 침대 아래 핸드 너트를 조여 침대를 가장 낮은 위치로 이동합니다(그림 1).
##### 3단계: 제어판에서 "Prepare>> Bed leveling>> Point 1(준비>> 베드 레벨링>>포인트 1)"을 수행합니다(그림 2). 노즐이 베드 모서리로 이동하고 핫베드 아래의 핸드 너트를 풉니다(그림 3). 노즐이 온상에 거의 닿도록 합니다(그림 4). 4개의 모서리가 모두 수평이 될 때까지 계속해서 "Point 2/3/4"를 수행합니다.
##### 4단계: 3단계를 반복하고 네 모서리가 모두 같은 높이가 될 때까지 2~3회 반복합니다.
![](1.png)

### <a id="step2"> :two: 프로브 Z 오프셋 잡기</a>
**Prepare>>Bed Leveling>>Catch Z-Offset(준비>>베드 레벨링>>Z-오프셋 잡기)** 를 수행하여 베드 자동 레벨링을 수행하기 전에 **Probe Z Offset** 을 얻습니다.
###### ![](3.png)
:warning: 이 메뉴가 표시되지 않으면 ***Control>>Configure>>Auto Leveling(제어>>구성>>자동 레벨링)*** 을 수행하여 **침대 자동 레벨링 기능** 을 켜세요.
###### ![](2.png)
:warning: Z ENDSTOP이 트리거되기 전에 베드 레벨링 센서가 핫베드를 검색할 수 없는 경우 LCD 화면에 "프로빙 실패"가 표시됩니다. 그 이유는 다음과 같습니다: 1. 베드 레벨링 센서의 설치 위치가 너무 높거나, 2. 베드 레벨링 센서가 제어 보드와 잘 연결되지 않거나, 심지어 3.베드 레벨링 센서가 소손되었습니다.     
##### :pushpin: "프로브 Z 오프셋"이란 무엇입니까?
**Probe Z Offset**은 센서가 핫베드를 감지했을 때 노즐과 Z축 절대 영점 사이의 거리를 나타냅니다.
센서가 올바르게 설치된 경우 센서가 핫베드를 감지했을 때 노즐은 항상 핫베드 위에 있으므로 **Probe Z Offset**은 항상 음수 값입니다. PL-08N 센서마다 감지 거리가 다르고, PL-08N의 실제 설치 높이도 다르기 때문에 기계마다 **Probe Z Offset**도 다릅니다.

### <a id="step3"> :three: 침대 수평 조정 </a>
위의 단계를 완료하면 온상 표면을 측정하고 모든 매개변수를 이미 설정하는 신뢰할 수 있는 센서를 갖게 됩니다. 이제 표면의 핫베드 높이에 대한 데이터 시트를 얻기 위해 핫베드 표면을 포괄적으로 측정하는 기계가 필요합니다.     
**Prepare>>Bed Leveling>>Auto Leveling(준비>>베드레벨링>>자동레벨링)** 을 하세요.
###### ![](4.png)
측정이 완료되면 레벨링 메뉴의 자동 레벨링 상태가 **-NA-** 에서 **Actived(활성화)** 로 변경됩니다.

### :four: 확인
이제 테스트 파일을 인쇄하여 침대 자동 레벨링 결과를 확인할 수 있습니다. 아래와 같은 단계:
1. **[level_test_310.gcode :arrow_down:](./level_test_310.zip)** 을 SD 카드에 복사하고 SD 카드에서 인쇄합니다(그림 1).
2. 인쇄가 시작되면 손잡이를 두 번 클릭(1초에 두 번 클릭)하여 Baby Z 오프셋 메뉴를 엽니다(그림 2).
3. 손잡이를 돌려 노즐 높이를 미세 조정하고 필라멘트가 핫베드에 잘 붙도록 합니다(그림 3).
4. 인쇄 결과를 확인합니다(그림 4).
###### ![](5.png)

-----
### 프린터 재설정 후 활성 자동 레벨링
자동 레벨링 기능은 프린터가 재설정되면 자동으로 비활성화됩니다. LCD 화면에서 수동으로 켤 수 있습니다.
- **1단계. Menu>>Prepare>>Auto Home(메뉴>>준비>>자동 홈)**
- **2단계. Motion>>Control>>Configure>>Active autolevel: ON(동작>>제어>>구성>>활성 자동 레벨: ON)**
참고: 이 2단계를 수행한 후 프린터는 마지막 "베드 레벨"에 저장된 레벨링 수정 매개변수를 적용합니다.
###### ![](6.png)

### 각 인쇄 전 베드 자동 수평 조정
프린터가 각 인쇄마다 베드 자동 레벨링을 수행하려면 슬라이싱 소프트웨어의 프린터 설정의 "Gcode 시작"에 "G29" 명령을 추가해야 합니다.
###### ![](7.png)
##### :pushpin: 참고하세요
1. G29를 사용하면 3단계의 기능만 대체되므로 1단계와 2단계도 수동으로 완료해야 합니다.
2. 히팅베드를 고정한 나사를 수동으로 조정하고 핫엔드를 교체하고 레벨링 센서 높이를 조정하는 등 "Z 프로브 오프셋" 값이 변경될 수 있는 작업을 수행한 후에는 1단계와 1단계를 반복해야 합니다. 2단계를 수동으로 수행합니다.

----

[ECCENTRIC]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide#8-tune-the-eccentric-columns