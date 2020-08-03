---
title: タッチセンサー
tag: micro:bitの機能
---

## タッチセンサー

GND 端子と各 GPIO 端子の間に指が触れたか否かを取得します。指が触れてから 1 秒以内に離したときに機能します。

{% include badge.html key='端子に触れた回数' %}

## 利用時のポイント

- 指が触れてから離れるまでの期間が 1 秒を超えると反応しません。
- 水に濡れた指で端子を直接触れるのは故障や事故につながる危険があるのでやめましょう。
- ほかのいろいろな物体と配線し回路をつくることによって、指で触れる端子を延長できます。

## 参考文献

<iframe title="On Pin Pressed" src="https://hatenablog-parts.com/embed?url=https://makecode.microbit.org/reference/input/on-pin-pressed" width="100%" height="150" frameborder="0" scrolling="no" loading="lazy"></iframe>
