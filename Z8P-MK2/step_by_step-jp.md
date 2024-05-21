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

----
# Z8P-MK2 ステップガイド
3 Dプリンタ初心者であれば、こんなにたくさんのドキュメントを読む必要があるので、どこから始めたらいいかわからないかもしれません。心配しないで、次はこれらの書類を詳しく紹介します。
つまり、次の4つのステップが必要です。**インストールマシン>>テストファイルの印刷>>スライス自分の3 dファイル>>3 dファイルの印刷**です。
まず、[:arrow_down: **すべてのドキュメント**][USER_GUIDE]をダウンロードしてコンピュータに保存し、ブラウザのお気に入りにWebページを追加することをお勧めします。

### <a id="step1">ステップ1。機械と配線を取り付ける </a>
インストールマシンをインストールするには、[:book: **インストレーションガイド**][INSTALLATION_GUIDE]および[:clapper: **インストレーションビデオチュートリアル**][INSTALL_VIDEO]を参照してください。
- **結線**。配線のプロセスは、基本的にプラグを適切なソケットに差し込むことです。プラグがコンセントに完全に差し込まれていることを確認する必要があります。特に、接触不良の場合がある2 PINソケットについては :warning: 印刷ヘッド（hotedコンポーネント）を接続する際は、インストールガイドの画像をよく参照し、コネクタの色とワイヤの色を区別するように注意してください。

### <a id="step2">ステップ2。maicheの電源を入れて簡単なテストと検証を行う </a>
- **電源投入**AC電源を投入する前に、110 V/220 V電源選択スイッチの設定が正しい位置に設定されているかどうかを確認してください ([**この図を参照**][IMG_ACSWITCH])。それから[**マシンの電源を入れる**][POWER_ON]ことができます。:warning:マシンには2つの電源スイッチがあります。1つは***交流スイッチ*（制御ボックスの背面にある赤いスイッチ、交流電源コンセントに近い）、もう1つは**直流スイッチ*（制御ボックスの右側にある円形の金属ボタンスイッチ）です。まず交流スイッチをオンにしてから、**直流スイッチを約5秒*（液晶ディスプレイにZONESTAR LOGOが表示されるまで）押し続けてマシンを開く必要があります。
- **簡易テスト**電源投入後、LCD画面のメニュー（[**LCDメニューの説明**][LCD_MENU]）を操作して、マシンが正常に動作するかどうかを確認するには、次の手順に従います。
  - **準備>>自動ホームページ>>すべてのホームページ**。この手順は、マシンのプリントヘッドを原点位置に戻すことです。
  - **準備>>温度>>PLA**を予熱します。この手順では、ホットエンドとホットベッドが正常に加熱できるかどうかを確認します。この手順では、ノズルの温度が60度を超えると、印刷ヘッド**の右側**にあるファン（ホットエンド）が回転しているのがわかるはずです。このファンは「ホットエンド冷却ファン」と呼ばれています。
  - **準備>>温度>>ファン**。つまみを押してファンの回転数を255に設定し、**左側の上**のファンを上に回転させます。
  以上の3つのステップを完了した後、機械が正常に動作していることを基本的に確定し、以下のステップを行うことができる。正常に動作していない部品が見つかった場合は、配線をよくチェックするか、電子自動テストを行ってチェックしてください。（参照[:clapper: **マシン自動テストビデオチュートリアル**][AUTOTEST_VIDEO]）。

### <a id="step3">ステップ3。レベリングベッド </a>
[![](https://img.youtube.com/vi/R3RfGnxx8hY/0.jpg)](https://www.youtube.com/watch?v=R3RfGnxx8hY)     
テストファイルを印刷する前に、印刷時にフィラメントをベッドにしっかり接着するために、ノズルとベッド（印刷プラットフォーム）の間の高さを設定する簡単なベッドレベリングを行う必要があります。[**レベリングベッド**][LEVEL_BED]を参照してください。

### <a id="step4"> ステップ4。テスト3 Dモデルを印刷する </a>
FDM 3 Dプリンタはgcodeファイルしか認識できません。gcodeファイルをSDカードにコピーし、SDカードを3 DプリンタのSDカードスロットに挿入し、LCD画面を操作して印刷を開始する必要があります。
:warning: 3 Dプリンタに精通している場合でも、機械が正常に動作していることを確認するために、少なくとも1つの4色テストモデルを印刷することをお勧めします。
- **4.1 モノクロテストファイルを印刷**    
[![](https://img.youtube.com/vi/ITHbO9VxTMo/0.jpg)](https://www.youtube.com/watch?v=ITHbO9VxTMo)
  - **gcodeファイル**を準備します。[:arrow_down: **xyz_cube.zip**][XYZ_CUBE]をダウンロードしてPCで解凍し、**xyz_cub.gcode**をSDカードにコピーします。SDカードを機械のSDカードソケットに差し込みます。
  - **フィラメント**をロードします。[:book: **ここ**][LOAD_FILAMENT]を参照して、すべての4本のフィラメントを押出機とホットエンドにロードしてください。
    **:warning: M4V6 hotendの場合、単色3 d印刷を印刷しても、ホットエンドに4本のフィラメントをロードする必要があります。***
  - **SDカードから**を印刷します。アイテムをLCD上の**印刷**アイテムに移動し、ノブをクリックして**xyz_cube.gcode**ファイルを選択し、ノブをクリックして印刷を開始します。
  - **ノズル高さ**を微調整します。ノズルとホットベッドが加熱されるのを待って、第1層を印刷するときにノズルとベッドの距離を観察し、太りすぎたり近すぎたりしたら、LCD画面のつまみをダブルクリックして**「babystep」**メニューを開き、つまみを回転してノズルとベッドの距離を微調整します。
  - **印刷が完了するまで待機**

- **4.2 4色テストファイルを印刷**     
[![](https://img.youtube.com/vi/CA8pWOuJYmE/0.jpg)](https://www.youtube.com/watch?v=CA8pWOuJYmE)
  -**gcodeファイル**を準備します。[:arrow_down: **M4_4CTest.zip**][M4_4CTEST] をダウンロードしてPCで解凍し、**M4_4CTest.gcode**をSDカードにコピーします。SDカードを機械のSDカードソケットに差し込みます。   
  -**フィラメント**をロードします。[:book: **ここ**][LOAD_FILAMENT]を参照して、すべての4本のフィラメントを押出機とホットエンドにロードしてください。
  -**SDカードから**を印刷します。アイテムをLCD上の**印刷**アイテムに移動し、ノブをクリックして**M4_4CTest.gcode**ファイルを選択し、ノブをクリックして印刷を開始します。
  -**ノズル高さ**を微調整します。ノズルとホットベッドが加熱されるのを待って、第1層を印刷するときにノズルとベッドの距離を観察し、太りすぎたり近すぎたりしたら、LCD画面のつまみをダブルクリックして**「babystep」**メニューを開き、つまみを回転してノズルとベッドの距離を微調整します。
  -**印刷が完了するまで待機**

### <a id="step5">ステップ5。独自の3 Dモデルを切り取る </a>
- 独自の3 Dモデルを印刷する前に、3 Dモデルファイル（stl/obj/AMF形式のファイル、[インターネットからダウンロード](#download)または独自に描画）をgcodeファイルに変換し、このgcodeファイルをSDカードに保存し、SDカードを3 Dプリンタに挿入する必要があります。      
:pushpin: **3 Dモデルをgcodeファイルに変換するプロセスを*スライス***と呼びます。
- まず、スライスソフトウェアをダウンロードしてコンピュータにインストールし、スライスソフトウェアにマシンのパラメータを設定するか、3 dプリンタの製造元によって設定されたマシンのプリセットファイルをロードする必要があります。
- 次に、スライスソフトウェアを実行する必要があります。3 Dモデルファイルのプロパティに基づいてスライス設定を設定してから、スライスする必要がある場合もあります。    
:pushpin: 推奨されるスライスソフトウェアは**PrusaSlicer**、ダウンロード、インストール、使用方法については[**スライスガイド**][SLICING_GUIDE]を参照してください。

### <a id="step6">ステップ6。独自の3 Dモデルを印刷する </a>
スライスしたら、生成したgcodeファイルをSDカードにコピーし、[**ステップ4。テスト3 Dモデルを印刷する**](#step4)に従って印刷します。

### <a id="step7">ステップ7。高度な機能の使用 </a>
すべての基本的な操作を完全に理解した後、この機械のいくつかの高度な機能を試してみることができます。
詳細については、[**高度な機能の使用方法ガイド**][ADVANCE_FEATURES]を参照してください。

##### <a id="download"> :page_with_curl: 有名無料3 Dモデルダウンロードサイト</a>
  -[thingiverse](https://www.thingiverse.com/)     
  -[printables](https://www.printables.com/)     
  -[youmagine](https://www.youmagine.com/)   

----
