id: src
author: jelly
summary: Summary of your codelab that is human readable

# Google Codelabs
<!-- ------------------------ -->
## Google Codelabs とは？
Duration: 10

Google が作成する Google サービスのチュートリアルサイトのようなもの。
Firebase などのチュートリアルをハンズオン形式で使い方を確認できる。

[Codelabs](https://codelabs.developers.google.com/)

![img1](img/img1.png)


Google Codelabs に掲載されているものには間違いが多々あるが、UIは非常に良い

![img2](img/img2.png)


- スライド形式
- 残り時間の表示
- キャッシュで前に進めたところまで保存

また、ソースコードが[Git](https://github.com/googlecodelabs)公開されている。

<!-- ------------------------ -->
## claat
Duration: 5
 
この Codelabs に掲載されているスライドは、上記Gitを参照して作成することもできるし、claat という Go言語で作成された CLI を使用することで作成可能。

Markdown を変換することもできるしお手軽に作成できる。詳細は以下の2サイト。

- https://budougumi0617.github.io/2019/03/27/create-codelab-page-by-claat/

- https://qiita.com/h-takauma/items/86ef51f7261b90d557a7

<!-- ------------------------ -->
## 実際に作ってみました
Duration: 1

1. hackmd で markdown を作成しmdファイルをダウンロード
2. claat で変換
3. gitpages を使って公開

の3手順だけです。

markdwon の書き方は[こちら](https://github.com/googlecodelabs/tools/tree/master/claat/parser/md)