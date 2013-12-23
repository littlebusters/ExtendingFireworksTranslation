# dom.addFrames()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7fc4.html)

## バージョン

3、4で強化された。

## 書式

```
dom.addFrames(howMany, where, {bAdvanceActiveFrame})
```

## 引数

### howMany:

追加するフレーム数を指定するInteger型。

### where:

フレームを追加する位置。指定できる値は、"beginning"、"before current"、"after current"、"end"です。

### bAdvanceActiveFrame:

Fireworks4で追加された、アクティブなフレームを指定するための引数。値が省略された場合はtrueとなり、この関数で追加された最初のフレームを、アクティブなフレームとして設定します。falseの場合、アクティブなフレームは変更されません。ドキュメントに2つのフレームあり、bAdvanceActiveFrameが省略またはtrueだった場合、ユーザーがフレームを追加すると3番目のフレームがアクティブなフレームになります。

## 戻り値

なし

## 説明

ドキュメントに1つまたは複数のフレームを追加します。

## サンプル

次のコマンドは、現在のフレームの後に1フレーム追加しますが、アクティブなフレームの変更はしません。

```
fw.getDocumentDOM().addFrames(1, "after current", false);
```
