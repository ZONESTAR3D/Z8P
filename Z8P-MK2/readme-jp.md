[M4V6CAUTION]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/blob/main/HOTEND/M4/M4_V6/M4V6_Precaution.md
[LOADFILAMENT]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filaments
[Z8PMK2VIDEO]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial
[INSTALLATION_PDF]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/Z8PMK2_Installation_and_quick_use_guide.pdf
[INSTALLATION_VIDEO]: https://youtu.be/-oieO7U0LCc
[AUTOSUTDOWN_VIDEO]: https://youtu.be/SJLpmJL-tG4
[AUTOLEVELING_VIDEO]: https://youtu.be/Zoyl6PybsUk
[POWERLOSS_VIDEO]: https://youtu.be/f-PpasByiiE
[GCDOE_REF1]: https://beginner3dprinting.com/what-is-g-code-in-3d-printing/
[GCDOE_REF2]: https://www.reprap.org/wiki/G-code
[SLICING_REF1]: https://loveandrobots.com/what-is-slicing-in-3d-printing/
[SLICING_REF2]: https://en.wikipedia.org/wiki/Slicer_(3D_printing)
[Z8PFIRMWARE]: https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P
[SOURCECODE]: https://github.com/ZONESTAR3D/source-code-for-3d-printer
[Z8P_FAQ]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/readme.md
[STEP_GUIDE]: https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/step_by_step.md
[INSTALLATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide
[OPERATION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide
[M4V6_GUIDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/M4/M4_V6
[TEST_GCODE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/3-TestGcode
[Z8P_SLICING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/4-SlicingGuide
[Z8P_PRINTS]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/5-PrintParts/
[LCD_MENU]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/DWIN_LCD_screen_Menu_Description
[MIXCOLOR_GUIDE]: https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/Mixing_Color
[AUTOLEVELING_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Bed_Auto_Leveling
[AUTOSHUTDOWN_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Shut_Down
[AUTORETRACTION_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/Auto_Retraction
[PRINTFROMPC_GUIDE]: https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/2-Operation_Guide/PrintFromPC
[UM_BMG]: https://bit.ly/UM_BMG
[FROD_GUIDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/FROD
[WIFI_GUIDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/WiFi
[E4_GUIDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/HOTEND/E4
[DDE_GUIDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Direct_Drive_Extrruder
[LASER_GUIDE]: https://github.com/ZONESTAR3D/Upgrade-kit-guide/tree/main/Laser_Engraving

----
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

-----
----
# Z8P-MK2 ユーザーガイド
## :warning: 注意してください
### :loudspeaker: 本機をご使用になる前に、[:book:「M4V6 ご使用上の注意」][M4V6CAUTION]をよくお読みください。
### :loudspeaker: M4V6 ホットエンドに 4 つのフィラメントを同時にロードする必要があります。間違った操作を行うと、ミックス カラー ホットエンドがブロックされる可能性があります。 誤操作によるホットエンドの詰まりは保証の対象外となります。 フィラメントのロード方法については、[:book:本書][LOADFILAMENT]を参照してください。
### :loudspeaker: 3D プリンターの初心者の方は、[:book: ステップバイステップ ガイド][STEP_GUIDE] をよく読み、ガイドに従ってステップバイステップで操作してください。 3D プリンタの経験がある場合は、少なくとも [:book: ステップバイステップ ガイド][STEP_GUIDE] も簡単に読んで、M4 ホットエンドにフィラメントをロードする方法を理解していることを確認してください。

### [:clapper: ビデオチュートリアルを見る][Z8PMK2VIDEO]
このマシンについては多数のビデオ チュートリアルを作成しています。[:clapper:**ここ**][Z8PMK2VIDEO] をクリックしてご覧ください。

### :file_folder: [1.インストールガイド][INSTALLATION_GUIDE]
- **[:book: インストール ガイド][INSTALLATION_GUIDE]**
- **[:blue_book: インストールおよびクイック使用ガイド PDF ファイル][INSTALLATION_PDF]**
- **[:clapper: インストール ビデオ チュートリアル][INSTALLATION_VIDEO]**
- **[:book: LCD 画面メニューの説明][LCD_MENU]**
- **[:art: 配線ブロック](./1-Installation_Guide/Wiring_Block.jpg)**
- **[:art: 配線図](./1-Installation_Guide/Wiring_Diagram.jpg)**

### :file_folder: [2.操作ガイド][OPERATION_GUIDE]
- **[:book: 基本操作ガイド][OPERATION_GUIDE]**
- **[:book: M4V6 ミックス カラー ホットエンド ユーザー ガイド][M4V6_GUIDE]**
- **高度な機能**
   - **[自動シャットダウン :book:][AUTOSHUTDOWN_GUIDE] [:clapper:][AUTOSUTDOWN_VIDEO]**
   - **[ミキシングカラー印刷:book:][MIXCOLOR_GUIDE]**
   - **[ベッドの自動レベリング :book:][AUTOLEVELING_GUIDE] [:clapper:][AUTOLEVELING_VIDEO]**
   - **[停電回復 :clapper:][POWERLOSS_VIDEO]**
   - **[自動撤回 :book:][AUTORETRACTION_GUIDE]**
- **[:book: PC から印刷][PRINTFROMPC_GUIDE]**
  
### :file_folder: [3.テスト Gcode ファイルを印刷][TEST_GCODE]
#### :arrow_down: [テスト Gcode ファイルをダウンロード][TEST_GCODE]
#### :pencil: 3D プリントにおける G コードとは何ですか?
G コードとは、3D プリンターが 3 次元オブジェクトを印刷するために必要な情報、または命令であり、3D プリンターが理解できる言語です。 G コードは、STL ファイルなどの標準 3D モデリング ファイルを特定の 3D プリンタが理解できるコードに変換することにより、スライシング ソフトウェアによって生成されます。 :page_with_curl: **[参考 1][GCDOE_REF1]** :page_with_curl: **[参考 2][GCDOE_REF2]**

### :file_folder: [4.スライスガイド][Z8P_SLICING_GUIDE]
#### :arrow_down: [シルサー ソフトウェアをダウンロードしてスライス ガイドを読む][Z8P_SLICING_GUIDE]
#### :pencil: 3D プリントにおけるスライスとは何ですか?
スライシングは、3D プリンターでオブジェクトや製品を作成するときに誰もが使用するソフトウェアの一部です。 ソフトウェアはプリンタにたどるべきパスを与えます。 スライス ソフトウェアは画像を取得し、3D プリンターが理解できる G コードに変換します。 これらの G コードは、プリンターがデザインを印刷する方法についての指示の一種です。 :page_with_curl: **[参考 1][SLICING_REF1]** :page_with_curl: **[参考 2][SLICING_REF2]**。

### :ファイルフォルダ: [5. プリントパーツ stl][Z8P_PRINTS]
#### :arrow_down: [プリントパーツの stl ファイルをダウンロード][Z8P_PRINTS]

### :link: [6.ファームウェア][Z8PFIRMWARE]
- **[:arrow_down: ファームウェア bin ファイル][Z8PFIRMWARE].**
- **[:arrow_down: ファームウェア ソース コード][SOURCECODE].**
#### :pencil: bin ファイルとソース コードとは何ですか?
> **ファームウェア bin ファイル** は、内蔵フラッシュに書き込まれる正確なメモリです。
> **ファームウェア ソース コード** はファームウェアの中核部分です。 ファームウェア全体は、異なるサブモジュールとして考えることができます。 多くのサブファイルに分かれています。 これらのファイルはソース ファイルと呼ばれます。 また、プログラムファイル全体をソースファイルまたはソースコードと呼びます。 現在、ファームウェアのソース コードは [**marlin**](https://www.marlinfw.org) に基づいています。

### 7.トラブルシューティング
- **[:book: Z8P のトラブルシューティング][Z8P_FAQ]**。

### アップグレード可能な機能
- **PEI スプリング ヒートベッド ステッカー :+1:**
PEI スプリング鋼板ホットベッド ステッカーは、オリジナルのホットベッド ステッカーよりも耐久性があります。 片面滑らかなホットベッドを上に向けると、プリントの底部をより滑らかにすることもできます。 **[:gift: 購入](http://bit.ly/3GbI9Sr) / [:gift: 購入](https://bit.ly/3VkmXOi)**
- **デュアルギアエクストルーダー :+1:**
デュアルギア押出機は、フィラメントを押したり引いたりする力を大幅に増加させることができ、押出機上でのフィラメントの滑りによる印刷欠陥や印刷失敗の可能性を大幅に低減します。**:book: [ユーザーガイド][UM_BMG]** **[:gift: 購入](https://bit.ly/46Vyd9H) / [:gift: 購入](https://bit.ly/AE_4xBMG)**
- **フィラメント切れセンサー :+1:**
このアイテムをアップグレードすると、3D プリンターを遠隔操作できるようになります。 **[:book: ユーザーガイド][FROD_GUIDE]** [:gift: 購入](https://www.aliexpress.com/item/4001309957376.html)
- **WiFi ワイヤレス制御モジュール :+1:**
このアイテムをアップグレードすると、3D プリンターを遠隔操作できるようになります。 **[:ブック: ユーザーガイド][WIFI_GUIDE]** [:gift: 購入](https://www.aliexpress.com/item/1005002378551489.html)
- **非混合カラーホットエンド :+1:**
このアイテムをアップグレードすると、多色モデルを印刷するためのカラープライムタワーのサイズが大幅に小さくなります。 **[:book: ユーザーガイド][E4_GUIDE]** [:gift: 購入](https://www.aliexpress.com/item/1005002951777699.html)
- **ダイレクトドライブ押出機 :+1:**
このプロジェクトをアップグレードすると、柔軟な素材 (TPU フィラメントなど) を印刷できるようになります。 **[:book: ユーザーガイド][DDE_GUIDE]** [:gift: 購入](https://www.aliexpress.com/item/1005002847644867.html)
- **レーザーエンジン**
このアイテムをアップグレードすると、3D プリンターを簡単なレーザー彫刻機に変えることができます。 より高出力のレーザー モジュールにより、彫刻速度が向上したり、より高い融点の材料をサポートしたりできます。 **[:book: ユーザーガイド][LASER_GUIDE]** [:gift: 購入](https://www.aliexpress.com/item/1005004908160260.html)
