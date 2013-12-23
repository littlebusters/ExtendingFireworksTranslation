# dom.hasMasterPage()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-77c6.html)

## バージョン

CS3

## 書式

dom.hasMasterPage()

## 引数

なし

## 戻り値

A Boolean value of true if the current document has a master page, or false if there is no master page.

Boolean値で、trueの場合、現在のドキュメントにマスターページがあります。falseの場合、マスターページはありません。

## 説明

Indicates whether or not a master page exists for the specified document.

マスターページが指定されたドキュメントにあるかどうかを知らせます。

## サンプル

```
fw.getDocumentDOM().hasMasterPage()
```