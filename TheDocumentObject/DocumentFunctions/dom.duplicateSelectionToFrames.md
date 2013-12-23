# dom.duplicateSelectionToFrames()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7df1.html)

## バージョン

3

## 書式

```
dom.duplicateSelectionToFrames(whichFrames)
```

## 引数

### whichFrames:

Acceptable values are "all", "previous", "next", and "end". Note that "end" means the last frame of the document; it does not add a new frame.

許容される値は、```all```(すべてのステート)
 / ```previous```（前のステート） / ```next```（次のステート） / ```end```（最後のステート）です。```end```はドキュメントの最後のフレームを意味します。新しいフレームは追加しません。

## 戻り値

なし

## 説明

Duplicates the selection to specified frames of the document.

ドキュメントの指定されたフレームに選択範囲を複製します。