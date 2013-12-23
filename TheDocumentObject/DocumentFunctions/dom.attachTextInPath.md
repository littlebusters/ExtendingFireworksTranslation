# dom.attachTextInPath()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WSc1b83f70210cd101148817c311fb7a6f7e8-8000.html)

## バージョン

CS5

## 書式

```
dom.attachtTextInPath()
```

## 引数

なし

## 戻り値

なし

## 説明

Attaches the selected text inside the selected path. If no text and path are selected, no action occurs.

選択しているパス内に、選択しているテキストを流し込みます。パスもテキストも選択されていない場合、アクションは発生しません。

## サンプル

When two items are selected (one a text block and the other a shape), the following command attaches the text block inside the shape's path:

2つのオブジェクト（テキストとその他の図形）が選択されている場合、次のコマンドを実行すると図形のパス内にテキストを流し込みます。

```
fw.getDocumentDOM().attachTextInPath();
```