---
title: このガイドへの貢献
tag: 先生向け
---

## このガイドへの貢献

誤字・脱字の修正、ドキュメント追加、その他改善するための Pull Request を歓迎します。
また、そのほか質問、提案などあれば GitHub Issues やページ末尾の入力フォーム (GitHub Issues に書き込まれるため Github アカウントとログインが必要) にてお気軽にご報告ください。

## 修正の確認方法

簡単な修正であれば手元の動作確認無しで Pull Request を送っていただいても構いませんが、大きな修正を行う場合、事前に編集結果を確認していただくには、手元の環境で Docker Compose を使ってご確認ください。
あらかじめ Docker Compose をインストールしてください。

[Docker Compose のインストール](https://docs.docker.com/compose/install/)

このリポジトリを clone したら次のコマンドで開発サーバーを起動します。

```sh
docker-compose up
```

開発サーバーが起動後、[http://localhost:4000](http://localhost:4000) にアクセスして確認します。
