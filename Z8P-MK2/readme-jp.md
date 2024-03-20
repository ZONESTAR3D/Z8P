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

-----
# Z8P-MK2 ユーザーガイド
## :warning: 注意してください
### :loudspeaker: マシンを使用する前に、[:book:「M4V6 使用上の注意事項」](https://github.com/ZONESTAR3D/Upgrade-kit-guide/blob/main/HOTEND/M4/M4_V6/M4V6_Precaution.md) を注意深く確認してください�?### :loudspeaker: M4V6 ホットエンド�?4 つのフィラメントを同時にロードする必要があります。間違った操作を行うと、ミック�?カラ�?ホットエンドがブロックされる可能性があります�?誤操作によるホットエンドの詰まりは保証の対象外となります�?フィラメントのロード方法については、[:book: this guide](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/2-Operation_Guide/readme.md#load-filaments)を参照してください�?### :loudspeaker: 3D プリンターの初心者の方は、[:book: ステップバイステップ ガイド][step_by_step_guide] をよく読み、ガイドに従ってステップバイステップで操作してください�?3D プリンターの経験がある場合は、少なくとも [:book: ステップバイステップ ガイド][step_by_step_guide] も簡単に読んで、M4 ホッ�?エンドにフィラメントをロードする方法を理解していることを確認してください�?
### [:clapper: ビデオチュートリアルを見る](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial)
このマシン用のビデオ チュートリアルを多数作成しています。[:clapper:**こち�?*](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P-MK2/6-VideoTutorial) をクリックしてご覧ください�?
### :file_folder: [1.インストールガイド][INSTALLATION]
- **[:book: インストール ガイド][INSTALLATION]**
- **[:blue_book:インストールおよびクイック使用ガイド PDF ファイル](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/Z8PMK2_installation_and_quick_use_guide.pdf)**
- **[:clapper: インストールビデオチュートリアル](https://youtu.be/-oieO7U0LCc)**
- **[:book: LCD 画面メニューの説明][LCD_MENU]**
- **[:art: 配線ブロック](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PMK2_Wiring_Block.jpg)**
- **[:art: 配線図](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P-MK2/1-Installation_Guide/Z8PM4-MK2_Wiring_Diagram.jpg)**

### :file_folder: [2.操作ガイド][Operation_Guide]
- **[:book: 基本操作ガイド][Operation_Guide]**
- **[:book: M4V6 ミックス カラ�?ホットエンド ユーザー ガイド][M4V6_Guide]**
- **高度な機�?*
   - **[自動シャットダウン :book:][auto_shutdown] [:clapper:](https://youtu.be/SJLpmJL-tG4)**
   - **[混合カラー印�?:book:][mix_color]**
   - **[ベッドオートレベリン�?:book:][auto_leveling] [:clapper:](https://youtu.be/Zoyl6PybsUk)**
   - **[停電回復 :clapper:](https://youtu.be/f-PpasByiiE)**
   - **[自動撤回 :book:][Auto_Retraction]**
- **[:book: PC から印刷][PrintFromPC]**
  
### :file_folder: [3.テス�?Gcode ファイルを印刷][Test_gcode]
#### :arrow_down: [テス�?gcode ファイルをダウンロード][Test_gcode]
#### :pencil: 3D プリントにおける G コードとは何です�?
G コードとは�?D プリンターが 3 次元オブジェクトを印刷するために必要な情報、または命令であり�?D プリンターが理解できる言語です�?G コードは、STL ファイルなどの標�?3D モデリン�?ファイルを特定の 3D プリンタが理解できるコードに変換することにより、スライシン�?ソフトウェアによって生成されます�?:page_with_curl: [**リファレンス 1**](https://beginner3dprinting.com/what-is-g-code-in-3d-printing/) :page_with_curl: [**リファレンス 2**](https:/ /www.reprap.org/wiki/G コー�?


### :file_folder: [4.スライスガイド][Slicing_Guide_Z8P]
#### :arrow_down: [シルサー ソフトウェアをダウンロードしてスライ�?ガイドを読む][Slicing_Guide_Z8P]
#### :pencil: 3D プリントにおけるスライスとは何ですか?
スライシングは�?D プリンターでオブジェクトや製品を作成するときに誰もが使用するソフトウェアの一部です�?ソフトウェアはプリンタにたどるべきパスを与えます�?スライス ソフトウェアは画像を取得し�?D プリンターが理解でき�?G コードに変換します�?これらの G コードは、プリンターがデザインを印刷する方法についての指示の一種です�?page_with_curl: [**参�?1**](https://loveandrobots.com/what-is-slicing-in-3d-printing/) :page_with_curl: [**参考資�?2**](https://en.wikipedia.org/wiki/Slicer_(3D_printing))


### :file_folder: [5. 印刷パー�?stl][PrintParts]
#### :arrow_down: [印刷パーツの stl ファイルをダウンロード][PrintParts]

### :link: [6.ファームウェア](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2)
- **[:arrow_down: ファームウェ�?bin ファイル](https://github.com/ZONESTAR3D/Firmware/tree/master/Z8/Z8P/Z8PM4Pro-MK2).**
- **[:arrow_down: ファームウェ�?ソー�?コード](https://github.com/ZONESTAR3D/source-code-for-3d-printer).**
#### :pencil: bin ファイルとソース コードとは何です�?
> **ファームウェ�?bin ファイル** は、内蔵フラッシュに書き込まれる正確なメモリです�?> **ファームウェ�?ソー�?コー�?* はファームウェアの中核部分です�?ファームウェア全体は、異なるサブモジュールとして考えることができます�?多くのサブファイルに分かれています�?これらのファイルはソース ファイルと呼ばれます�?また、プログラムファイル全体をソースファイルまたはソースコードと呼びます�?現在、ファームウェアのソース コードは [**marlin**](https://www.marlinfw.org) に基づいています�?
### 7.トラブルシューティン�?- :book: [**Z8P のトラブルシューティング**](https://github.com/ZONESTAR3D/Z8P/tree/main/Z8P_FAQ/readme.md)

### アップグレード可能な機能
- **PEI スプリン�?ヒートベッド ステッカ�?:+1:**      
PEI スプリング鋼板ホットベッ�?ステッカーは、オリジナルのホットベッ�?ステッカーよりも耐久性があります�?片面滑らかなホットベッドを上に向けると、プリントの底部をより滑らかにすることもできます�?**[:gift: 購入](http://bit.ly/3GbI9Sr) / [:gift: 購入](https://bit.ly/3VkmXOi)**
- **デュアルギアエクストルーダ�?+1:**     
デュアルギア押出機は、フィラメントを押したり引いたりする力を大幅に増加させることができ、押出機上でのフィラメントの滑りによる印刷欠陥や印刷失敗の可能性を大幅に低減します�?*[:book: ユーザーガイド](https://bit.ly/UM_BMG)** **[:gift: 購入する](https://bit.ly/46Vyd9H) / [:gift: 購入する](https://bit.ly/AE_4xBMG)**   
- **フィラメント切れセンサー :+1:**    
このアイテムをアップグレードすると�?D プリンターを遠隔操作できるようになります�?**[:book: ユーザーガイド][guide_FROD]** [:gift:購入](https://www.aliexpress.com/item/4001309957376.html)
- **WiFi ワイヤレス制御モジュール :+1:**    
このアイテムをアップグレードすると�?D プリンターを遠隔操作できるようになります�?**[:book: ユーザーガイド][guide_WIFI]** [:gift:購入](https://www.aliexpress.com/item/1005002378551489.html)
- **非混合カラーホットエンド :+1:**    
このアイテムをアップグレードすると、多色モデルを印刷するためのカラープライムタワーのサイズが大幅に小さくなります�?**[:book: ユーザーガイド][guide_E4]** [:gift:購入](https://www.aliexpress.com/item/1005002951777699.html)
- **ダイレクトドライブ押出�?:+1:**    
このプロジェクトをアップグレードすると、柔軟な素材 (TPU フィラメントなど) を印刷できるようになります�?**[:book: ユーザーガイド][guide_DDE]** [:gift:購入](https://www.aliexpress.com/item/1005002847644867.html)
- **レーザーエンジン**    
このアイテムをアップグレードすると�?D プリンターを簡単なレーザー彫刻機に変えることができます�?より高出力のレーザー モジュールにより、彫刻速度が向上したり、より高い融点の材料をサポートしたりできます�?**[:book: ユーザーガイド][guide_Laser]** [:gift:購入](https://www.aliexpress.com/item/1005004908160260.html)

------
### Upgradable Features
- **SD Card Extender :+1:**    
By upgrading this item, it is easier to access (Plug/Unplug) the SD card. [:gift: Buy](https://www.aliexpress.com/item/1005005342958433.html)
- **Filament run out sensor :+1:**    
By upgrading this item, you can remote control your 3d printer. **[:book: User guide][guide_FROD]**  [:gift: Buy](https://www.aliexpress.com/item/4001309957376.html)   
- **WiFi wireless control module  :+1:**    
By upgrading this item, you can remote control your 3d printer. **[:book: User guide][guide_WIFI]** [:gift: Buy](https://www.aliexpress.com/item/1005002378551489.html)    
- **Non mix color hotend  :+1:**   
By upgrading this item, the size of the color prime tower for printing multi-color models is much smaller. **[:book: User guide][guide_E4]** [:gift: Buy](https://www.aliexpress.com/item/1005002951777699.html)   
- **Direct drive extruder :+1:**     
By upgrading this project, you can print flexible materials (such as TPU filament). **[:book: User guide][guide_DDE]** [:gift: Buy](https://www.aliexpress.com/item/1005002847644867.html)    
- **Laser engine**     
By upgrading this item, you can turn your 3D printer into a simple laser engraving machine. Higher power laser modules can improve engraving speed or support materials with higher melting point. **[:book: User guide][guide_Laser]** [:gift: Buy](https://www.aliexpress.com/item/1005004908160260.html)     -->

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
