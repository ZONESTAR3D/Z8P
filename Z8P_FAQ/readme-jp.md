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
# Z8P のトラブルシューティング

-----
## 参照
製品の問題を発見して解決するには、自動テスト機能を使用したり、コントロールボックスを開けて配線を確認したり、モーター駆動電流を調整したり、「交換テスト」を使用して電子部品をチェックしたりする必要がある場合があります。 .. ここでは、参考のためにこれらのガイド、写真、ビデオチュートリアルをリストします。
### 配線
- [:art: コントロール ボックスの開き方](./pic/OpenControlBox.png)
- [:art: 制御基板上の配線](./pic/Z8P_wiring.png)

### 電子部品自動検査
Z8Pには電子機器自動テストプログラムが組み込まれています。 このプログラムを使用すると、電子コンポーネントに問題が発生したときに、問題の原因を特定できます。 このプログラムを開始するには、「**情報**」メニューを開き、ノブを回して「**日付: xx-xx-xx**」項目をポイントし、ノブを 5 回押します。
#### ビデオチュートリアル
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### 「スワップテスト」について
マシンに機能上の問題があり、問題の原因が複数の可能性があることが判明した場合 (複数の部品が同じ問題を引き起こす可能性がある)、いわゆる「**スワップ テスト**」を使用する機会があります。 」 問題の原因をできるだけ早く特定します。
たとえば、左側の Z 軸モーターが動作しない場合は、配線、ステッピング モーター、モーター ケーブル、制御基板上のモーター駆動モジュール、または制御基板に問題がある可能性があります。 機械内には同一の Z 軸駆動系が 2 組あります (左 Z 駆動系と右 Z 駆動系) ので、左右の同じ部品/コンポーネント/配線を 1 つずつ交換して確認することができます。 問題はどこから来るのか。
交換テストを実行できる機械の部品には次のものがあります。
- X/Y モーターとリミット スイッチ。
- ZL/ZRモーターとリミットスイッチ
- 4セットの押出機モーター
- ホットベッドとホットエンドのカートリッジヒーターと温度センサー。

-----
## コンテンツ
- **[マシンを起動できません](./Issue_of_startup/readme.md)**
- **[ホットエンドがブロックされています/詰まっています](./Issue_mix_color_hotend_clogged/readme.md)**
- **[加熱の問題](./Issue_heating/readme.md)**
- **[SD カードから印刷するときの自動シャットダウン](./Issue_auto_shut_down/readme.md)**
- **[エクストルーダーブロックの問題を修正する方法](./Issue_extruder_blocked/readme.md)**
- **[エクストルーダーの排出不足の問題を修正する方法](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[Cura で USB 接続時にクラッシュする](./issue_of_connect_USB_in_Cura/readme.md)**
- **[SD カードから印刷するときにプリンターが自動的に一時停止する](./Issue_auto_pause/readme.md)**
- **[SD カードが読み取れない問題](./Issue_not_read_sdcard/readme.md)**
- **[LCD スクリーンのノブの問題](#dwinscreen)**

----
## その他の参考資料
- **[44 の一般的な 3D プリントの問題](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[すべての問題と解決策 (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">LCD 画面のノブの問題</a>
LCD 画面のノブが固着している場合は、[:gift: this link](https://www.aliexpress.com/item/3256805596235491.html) をクリックして交換用キーパッドを購入できます。 製品が保証期間内（パッケージを受け取った日から12か月以内）の場合は、注文後にご連絡ください。アフターサービスを提供します。
LCD スクリーンのキーパッドを交換する方法については、ビデオチュートリアルをご覧ください。
- 溶接編（旧）は[:clapper:この動画](https://youtu.be/Xwfczp3nLOY)をご覧ください。
- FPC バージョン (新しいもの) については、[:clapper: このビデオ](https://youtu.be/z9E6glRZRIQ) を参照してください。
####
![](./pic/keypad.jpg)

-----
## :email: FAQ を読んでも問題を解決する解決策が見つからない場合は、テクニカル サポート チーム (support@zonestar3d.com) までご連絡ください。