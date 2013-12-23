# dom.attachTextToPath()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f0a.html)

## バージョン

3

## 書式

```
dom.attachtTextToPath()
```

## 引数

なし

## 戻り値

なし

## 説明

Attaches the selected text to the selected path. If no text and path are selected, no action occurs. 

選択しているパス内に、選択しているテキストに結合します。パスもテキストも選択されていない場合、アクションは発生しません。

## サンプル

When two items are selected (one a text block and the other a shape), the following command attaches the text block to the shape’s path:

2つのオブジェクト（テキストとその他の図形）が選択されている場合、次のコマンドを実行すると図形のパスにテキストを結合します。

```
fw.getDocumentDOM().attachTextToPath();
```