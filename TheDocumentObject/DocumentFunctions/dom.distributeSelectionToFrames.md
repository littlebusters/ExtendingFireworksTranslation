# dom.distributeSelectionToFrames()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e19.html)

## バージョン

3

## 書式

```
dom.distributeSelectionToFrames()
```

## 引数

なし

## 戻り値

なし

## 説明

Distributes the selected items to the frames of the document, adding frames if necessary. The first item goes to the current frame, the second item to the next frame, and so on. If only one item is selected, this function has no effect.

必要に応じてフレーム（ステート）を追加し、ドキュメントのフレームに選択されているオブジェクトを分配します。最初（レイヤーパレットで1番下）のオブジェクトが現在のフレーム、2番目のオブジェクトが次のフレームに、となります。選択されたオブジェクトが1つしかない場合、この関数は効果がありません。