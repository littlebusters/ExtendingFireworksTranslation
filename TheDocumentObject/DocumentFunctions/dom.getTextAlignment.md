# dom.getTextAlignment()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d58.html)

## バージョン

3

## 書式

```
dom.getTextAlignment()
```

## 引数

なし

## 戻り値

One of the following strings: "left", "center", "right", "justify", "stretch", "vertical left", "vertical center", "vertical right", "vertical justify", or "vertical stretch". Returns null if the text has multiple alignments or if the selection contains no text.

次のいずれかの文字： ```left``` / ```center``` / ```right``` / ```justify``` / ```stretch``` / ```vertical left``` / ```vertical center``` / ```vertical right``` / ```vertical justify``` / ```vertical stretch```
```null```が返る場合、テキストが複数の行揃えを持っているか、選択範囲にテキストが含まれていません。

## 説明

Gets the alignment of selected text.

選択しているテキストの揃えを取得します。