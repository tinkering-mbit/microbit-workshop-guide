## 表情が見えるマスク

[![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)

マスクの上から micro:bit を取り付けることによって、表情を伝えられるようにしてみました。

<div style="width:100%;height:0;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/1SgD5OYJinU?autoplay=1&rel=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen width="100%" height="100%" style="width:100%;height:100%;position:absolute;left:0;top:0;overflow:hidden;" loading="lazy"></iframe></div>

### 用意するもの

- マスク … 1 つ
- 針と糸 … 1 式
- micro:bit … 2 つ
- micro:bit 用電池 … 1 つ

![用意するもの](https://i.gyazo.com/f23fc77b80badcb869f51368abb59b78.jpg){:loading="lazy"}

### 作り方

針に糸を付け、針をマスクのウラ面から通します。

![マスクに針を通す](https://i.gyazo.com/7d98b5f3a36e4a113c64c0d08c203c45.jpg){:loading="lazy"}

micro:bit の側部の穴に針を通します。

![micro:bitに針を通す](https://i.gyazo.com/e95b646aa36c6e8a155352fb4223f654.jpg){:loading="lazy"}

針を通し終えたら糸を結んで固定します。反対側も同じように糸を結びます。

![2箇所とめる](https://i.gyazo.com/3327a16cf76a81d89b476902b5c89d45.jpg){:loading="lazy"}

外観です。

![外観](https://i.gyazo.com/a4d497345f1cc70fa6987436e71e6bdf.jpg){:loading="lazy"}

micro:bit に電池を取り付けて完成です。電池はマスクのウラ面など見えにくいところに隠しましょう。

![電池を取り付ける](https://i.gyazo.com/a0756793234eac8813f472b495a8315f.jpg){:loading="lazy"}

### マスク側のプログラム

無線で受け取った文字列をもとに表情を表示するプログラムです。マスクに取り付けてある側の micro:bit に書き込みます。

無線グループは `2` にしました。実際に試すときは周囲の人と無線グループが同じ番号にならないよう変更しましょう。

[![コントローラー側のプログラム](https://img.shields.io/badge/MakeCode-3454d1){:loading="lazy" style="margin: 0;"}](https://makecode.microbit.org/#pub:_Hks2J6TtthLm){:target="\_blank"}

<div style="position:relative;height:calc(300 + 5em);width:100%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_Hks2J6TtthLm" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin" loading="lazy"></iframe></div>

| 受け取る文字列 | 意味   |
| -------------- | ------ |
| `happiness`    | 幸福   |
| `sadness`      | 悲しみ |
| `anger`        | 怒り   |
| `contempt`     | 軽蔑   |
| `disgust`      | 不愉快 |
| `fear`         | 恐れ   |
| `surprise`     | 驚き   |
| 上記以外       | 無関心 |

### コントローラー側のプログラム

マスクの表情を制御するための手元のコントローラーのプログラムです。A/B ボタンを押すと、それぞれ `happiness`/`sadness` が送信されます。

マスク側のプログラムに合わせて無線グループを設定します。

[![コントローラー側のプログラム](https://img.shields.io/badge/MakeCode-3454d1){:loading="lazy" style="margin: 0;"}](https://makecode.microbit.org/#pub:_duCMMUY4wUA0){:target="\_blank"}

<div style="position:relative;height:calc(300px + 5em);width:100%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_duCMMUY4wUA0" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin" loading="lazy"></iframe></div>

### この作品に使われている機能

マスク側: LED 画面 (出力装置)、無線

コントローラー側: A/B ボタン (入力装置)、無線
