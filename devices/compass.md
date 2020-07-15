---
title: コンパス
tag: micro:bitの機能
---

## コンパス

地磁気を計ります。方位を知ることができます。
{% include badge.html key='コンパス' %}

## 校正 (キャリブレーション)

コンパスをはじめて使用するとき、校正を行う必要があります。
校正を行うと、生成される読み取り値がより正確になります。

校正が始まると LED 画面上に `TILT TO FILL SCREEN` (傾けて画面を埋めてください) とスクロール表示されます。
校正が完了するまでプログラムは一時停止します。
校正は、LED 画面をすべて点灯するように機体を回転させることで完了します。

<div style="width:100%;height:0px;position:relative;padding-bottom:75.000%;"><iframe src="https://streamable.com/e/5c9ppl?loop=0" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

## 磁場

コンパスは磁場に反応します。たとえば micro:bit を金属製の物体に取り付けたりすると、地磁気の読み取り精度に悪影響を及ぼします。
