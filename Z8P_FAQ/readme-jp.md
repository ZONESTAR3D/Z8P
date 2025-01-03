## <a id="choose-language">:globe_with_meridians: 言語を選択</a>
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
# Z8Pのトラブルシューティング

-----
## リファレンス
製品の問題を発見して解決するためには、自動テスト機能を使用したり、制御ボックスを開けて配線を確認したり、モータードライブ電流を調整したり、電子部品をチェックする「スワップテスト」を使用する必要がります。ここでは、これらのガイド、図、ビデオチュートリアルをリストアップします。
### 配線
- [:art: 制御ボックスを開く方法](./pic/OpenControlBox.png)
- [:art: 制御ボードの配線](./pic/Z8P_wiring.png)

### 電子部品の自動テスト
Z8Pには、電子部品の自動テストプログラムが組み込まれています。このプログラムを使用して、電子部品に問題が発生した時の問題の原因を特定できます。このプログラムを開始するには、「**Info**」メニューを開いて、ノブを「**Date: xx-xx-xx**」項目に向け、ノブを5回押します。
#### ビデオチュートリアル
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### 「スワップテスト」について
機械に機能問題が発生し、その原因が複数可能性がある場合（複数の部品が同じ問題を引き起こす可能性がある場合）、いわゆる「スワップテスト」を使用して問題の原因をできるだけ早く特定することができます。
例えば、左Z軸モーターが動作しない場合、問題は配線、ステップモーター、モーターケーブル、制御ボード上のモータードライバーモジュール、または制御ボード自体から来る可能性があります。機械には、左Zドライバーシステムと右Zドライバーシステムの2つのセットが同じで存在するため、左右の同じ部品/コンポーネント/ケーブルを個別に交換して、問題の原因を確認できます。
交換テストを行う機械の部品には以下が含まれます：
- X/Yモーターとリミットスイッチ。
- ZL/ZRモーターとリミットスイッチ
- 4つのエクストルーダーモーター
- ホットベッドとホットエンドのカートリッジヒーターと温度センサー。

-----
## コンテンツ
- **[機械が起動しない](./Issue_of_startup/readme.md)**
- **[ホーミング問題](./Issue_of_Homing/readme.md)**
- **[ヒーティング問題](./Issue_heating/readme.md)**
- **[SDカードから印刷時に自動的にシャットダウン](./Issue_auto_shut_down/readme.md)**
- **[ホットエンド/エクストルーダーの詰まり問題を修正する方法](./Issue_extruder_blocked/readme.md)**
- **[エクストルーダーの排出不足問題を修正する方法](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[CuraにUSBを接続したときにクラッシュ](./issue_of_connect_USB_in_Cura/readme.md)**
- **[SDカードから印刷時に自動一時停止](./Issue_auto_pause/readme.md)**
- **[SDカードを読み取れない問題](./Issue_not_read_sdcard/readme.md)**
- **[LCDスクリーンノブの問題](#dwinscreen)**

----
## その他のリファレンス
- **[44つの一般的な3Dプリント問題](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[すべての問題と解決策 (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">LCDスクリーンノブの問題</a>
LCDスクリーンのノブが詰まっている場合は、[:gift: このリンク](https://www.aliexpress.com/item/3256805596235491.html)をクリックして交換キーパッドを購入してください。製品が保証期間内（パッケージ到着日から12か月以内）の場合、ご注文後、アフターサービスを提供します。
LCDスクリーンのキーパッドを交換する方法は、ビデオチュートリアルを参照してください：
- 焊接バージョン（古い）の場合は、[:clapper: このビデオ](https://youtu.be/Xwfczp3nLOY)を参照してください。
- FPCバージョン（新しい）の場合は、[:clapper: このビデオ](https://youtu.be/z9E6glRZRIQ)を参照してください。
####
![](./pic/keypad.jpg)

-----
## :email: FAQを読んだ後も問題の解決策が見つからない場合は、技術サポートチームに連絡してください：support@zonestar3d.com。