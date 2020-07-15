---
title: micro:bit の標準機能
tag: プログラミング入門
---

## micro:bit（マイクロビット）の機能

micro:bit には標準で A/B ボタン、5x5 の LED 画面の他に、温度、加速度、明るさ、地磁気 (コンパス)、タッチセンサー機能が内蔵されています。

これらの内蔵センサー類では足りない機能が必要な場合や高い精度が必要な場合は [外部デバイス](extensions.html) を利用してください。

### ボタンと LET 画面

#### 🅰 A/B ボタン

2 つのボタンを押したか否かを取得します。
{% include badge.html key='スマイリーボタン' %}

#### 💡 LED 画面

5x5 の LED 画面に絵や文字を表示します。

LED 画面にカタカナの表示します。拡張機能「カタカナ」を使います。
{% include badge.html key='カタカナの表示' %}

### 内蔵センサー

内蔵センサーの搭載位置については、[サヌキテックネットが配付している](https://sanuki-tech.net/micro-bit/appendix-events/watcha-programming/) リーフレット「[micro:bitを観察しよう！(PDF)](https://sanuki-tech.net/micro-bit/pdfs/events/watcha-programming/watcha-programming-04.pdf)」で確認すると分かりやすいです。

#### 🌡️ 温度センサー

内蔵の温度センサーを使って温度 (℃)を測ります。

[温度センサー](devices/thermometer.html)

#### 📊 加速度センサー

重力加速度 (G)を測ります。機体の角度・運動 (ゆさぶられたら、など)を取得します。

加速度計
{% include badge.html key='加速度計' %}

回転
{% include badge.html key='回転' %}

歩数計
{% include badge.html key='歩数計' %}

#### 🌞 明るさセンサー

LED 画面の一部を使って周囲の明るさを測ります。

[明るさセンサー](devices/light-level.html)

#### 🧭 コンパス

地磁気を測り、方角を読み取ります。

[コンパス](devices/compass.html)

#### 👇 タッチセンサー

GND 端子と一緒に指が触れたか否かを取得します。

[タッチセンサー](devices/on-pin-pressed.html)

### その他の基本機能

#### ⌚ タイマー

時間 (s)を測ります。
{% include badge.html key='ストップウォッチ' %}

### 📻 Bluetooth 通信

複数の micro:bit を Bluetooth (ベースの独自の通信方式) で無線接続して簡単に連携させることができます。

#### 投票マシーン

投票プログラム
{% include badge.html key='投票プログラム' %}

投票ダッシュボード
{% include badge.html key='投票ダッシュボード' %}
