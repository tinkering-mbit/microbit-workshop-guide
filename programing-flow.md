---
title: プログラミングの流れ
tag: プログラミング入門
---

## プログラミングの流れ

<div style="width:100%;height:0;position:relative;padding-bottom:67.353%;"><iframe src="https://www.youtube.com/embed/lxO67fTX-ME?autoplay=1&rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen width="100%" height="100%" style="width:100%;height:100%;position:absolute;left:0;top:0;overflow:hidden;" loading="lazy"></iframe></div>

## プログラムをつくる

micro:bit は小さなコンピューターです。

[MakeCode](https://makecode.microbit.org/) というオンライン型プログラミング環境でコードを書きます (オフラインで書くためのツールも配付されていますがここでは紹介しません)。

## micro:bit にプログラムを転送する

MakeCode で作成したプログラムは「ダウンロードボタン」を押すと .hex ファイルとして micro:bit に書き込まれます。
詳しい手順は [サンプルコードの実行方法](how-to-run.md) を参照してください。

## プログラムを動かす

プログラムが転送されると自動的に動作します。電池をつなげて単体で動作することもできます。

電源が入った時の他、背面 USB 端子横のリセットボタンを押した時にも再度プログラムが最初から実行されます。

## 実際にプログラミングしてみる

実際に micro:bit の LED 画面に「Hello,world!」を表示する方法を知るには、[はじめてのプログラミング (外部サイト)](https://sanuki-tech.net/micro-bit/programming/first-step/)を参照してください。

## 基本的なプログラミングを学ぶ

簡単なサンプルプログラムを試してみたり、書き換えてみたりしながら、自分でも自由にプログラミングできるようになっていきましょう。

- [どきどきハート (アイコンを繰り返し表示する)](https://sanuki-tech.net/micro-bit/appendix-sample-program/dokidoki-heart/)
  - LED 画面にアイコンを表示、一時停止の繰り返しを行います。無限繰り返し処理の基本を確認します。
- [今の気持ちは？ (ボタン A・B で制御する)](https://sanuki-tech.net/micro-bit/appendix-sample-program/button-a-b/)
  - ボタンを押したら LED 画面の表示を切り替えます。〜した時というイベント処理の基本を確認します。
- [5・4・3・2・1・0 (ボタンを押してカウントダウン)](https://sanuki-tech.net/micro-bit/appendix-sample-program/count-down/)
  - 最初に矢印を表示、ボタンを表示する毎に数字を表示します。変数と繰り返し処理の基本を確認します。
- [はじめてのコンピュータサイエンス - 座標 - アニメーションとパターン](https://makecode.microbit.org/courses/csintro/coordinates/activity)
  - LED 画面のひとつひとつの LED の位置を指定してオンオフしたり、ランダムに光らせたり、ボタンを押したときに明るさを変える手順が説明されています

その他、[外部デバイスとサンプルコードページ](examples.md) にある例を参考にしていろいろチャレンジしてみて下さい！

## リファレンス

MakeCode でのプログラミングに利用するブロック・コードの一覧は [MakeCode のリファレンス](https://makecode.microbit.org/reference) を参照してください。

## 注意点

- LED やコンソールなどに表示する文字 (文字列) に日本語は利用できません。全く何も表示されないか文字化けして表示されるため、英数字や記号だけを使うようにしてください
- USB ケーブルには充電専用のものがあります。ケーブルを繋いでも MakeCode で認識されない場合はケーブルも確認してみてください
