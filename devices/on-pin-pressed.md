---
title: タッチセンサー
tag: micro:bitの機能
---

## タッチセンサー

GND 端子に指が触れたか否かを取得します。指が触れてから 1 秒以内に離したときに機能します。

{% include badge.html key='端子に触れた回数' %}

## 利用時のポイント

- 指が触れてから離れるまでの時間が 1 秒以内である必要があることに注意してください。
- 指が乾燥していると反応しにくい場合などがあることに注意してください。但し、反応がないからと言って水に濡らすのは故障や怪我の原因になるため止めましょう。
- GND 端子に直接ではなく、延長して色々な形の端子で検知させることも出来ます。そのための外部デバイスもいろいろ販売されています。

## 参考文献

<iframe title="On Pin Pressed" src="https://hatenablog-parts.com/embed?url=https://makecode.microbit.org/reference/input/on-pin-pressed" width="100%" height="150" frameborder="0" scrolling="no" loading="lazy"></iframe>
