---
title: 明るさセンサー
tag: micro:bitの機能
---

## 明るさセンサー

LED 画面の一部を使って周囲の明るさを測ります。
周囲が暗いとき 0 が得らます。明るさに応じて大きい値が得られ、最大 255 が得られます。

{% include badge.html key='日照センサー' %}

## 制約事項

micro:bit は明るさとアナログ値を同時に取得することができません。同時に読み取ると誤った値が得られます。

<iframe title="Conflict between input.lightLevel and pins.analogReadPin on makecode · Issue #448 · lancaster-university/microbit-dal" src="https://hatenablog-parts.com/embed?url=https://github.com/lancaster-university/microbit-dal/issues/448" width="100%" height="150" frameborder="0" scrolling="no" loading="lazy"></iframe>

## 参考文献

<iframe title="Light Level" src="https://hatenablog-parts.com/embed?url=https://makecode.microbit.org/reference/input/light-level" width="100%" height="150" frameborder="0" scrolling="no" loading="lazy"></iframe>
