---
title: コンパス
tag: micro:bitの機能
---

## コンパス

地磁気を計ります。方位を知ることができます。
{% include badge.html key='コンパス' %}

## 利用時のポイント

- コンパスをはじめて使用するとき、校正を行う必要があります。構成は一度行うと保存され次回からはそのまま利用できるようになります。
- 周辺環境に合わせて再度校正を行うことで、生成される読み取り値がより正確になります。明示的に再度校正を行いたいときは、一度校正用プログラムを書き込んで校正してからまた作品で使うプログラムに戻します。
- コンパスは磁場に反応します。例えば micro:bit を金属製の物体に取り付けたりすると、地磁気の読み取り精度に悪影響を及ぼします。
- 異なる場所で利用する場合や micro:bit 本体に接続している機材を変える場合は、再校正することによって精度が高まります。

### 校正 (キャリブレーション)

コンパスをはじめて使用するとき、校正を行う必要があります。

校正が始まると LED 画面上に `TILT TO FILL SCREEN` (傾けて画面を埋めてください) とスクロール表示されます。
校正が完了するまでプログラムは一時停止します。
校正は、LED 画面をすべて点灯するように機体を色々な方向に傾け、回転させることで完了します。

<div style="width:100%;height:0;position:relative;padding-bottom:75.000%;"><iframe src="https://www.youtube.com/embed/FTSoCqeYe08?autoplay=1&rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen width="100%" height="100%" style="width:100%;height:100%;position:absolute;left:0;top:0;overflow:hidden;" loading="lazy"></iframe></div>

## 参考文献

<iframe title="コンパス" src="https://hatenablog-parts.com/embed?url=https://makecode.microbit.org/projects/compass" width="100%" height="150" frameborder="0" scrolling="no" loading="lazy"></iframe>
