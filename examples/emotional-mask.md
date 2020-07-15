## 表情が見えるマスク

[![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)

マスクの上から micro:bit を取り付けることによって、表情を伝えられるようにしてみました。

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://streamable.com/e/jjwhjd" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

### 用意するもの

- マスク … 1 つ
- 針と糸 … 1 式
- micro:bit … 2 つ
- micro:bit 用電池 … 1 つ

![用意するもの](https://i.gyazo.com/f23fc77b80badcb869f51368abb59b78.jpg)

### 作り方

針に糸を付け、針をマスクのウラ面から通します。

![マスクに針を通す](https://i.gyazo.com/7d98b5f3a36e4a113c64c0d08c203c45.jpg)

micro:bit の側部には穴に針を通します。

![micro:bitに針を通す](https://i.gyazo.com/e95b646aa36c6e8a155352fb4223f654.jpg)

針を通し終えたら糸を結んで固定します。反対側も同じように糸を結びます。

![2箇所とめる](https://i.gyazo.com/3327a16cf76a81d89b476902b5c89d45.jpg)

外観です。

![外観](https://i.gyazo.com/a4d497345f1cc70fa6987436e71e6bdf.jpg)

micro:bit に電池を取り付けて完成です。

![電池を取り付ける](https://i.gyazo.com/a0756793234eac8813f472b495a8315f.jpg)

### プログラム (マスク側)

無線で受け取った文字列をもとに表情を表示するプログラムです。マスクに取り付けてある側の micro:bit に書き込みます。

無線グループは `2` にしましたが、実際に試すときは無線グループが周囲の人と同じ番号にならないよう変更しましょう。

<div style="position:relative;height:calc(300px + 5em);width:100%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_Hks2J6TtthLm" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

### プログラム (送信側)

マスクの表情を制御するための手元のコントローラーのプログラムです。

マスク側のプログラムに合わせて無線グループを設定します。

<div style="position:relative;height:calc(300px + 5em);width:100%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_duCMMUY4wUA0" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>
