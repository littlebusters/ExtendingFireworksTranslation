# dom.distributeLayerToFrames()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e1f.html)

## バージョン

3

## 書式

```
dom.distributeLayerToFrames(layerIndex)
```

## 引数

### layerIndex:

An integer value that specifies the layer that contains the items to be distributed, starting with 0 (although, to specify the current layer, pass –1 here).

0から始まる、分配するオブジェクトが含まれるレイヤーを指定するInteger型。（現在のレイヤーを指定するには-1を渡します。）

## 戻り値

なし

## 説明

Distributes the items on the specified layer to the frames of the document, adding frames if necessary. The first item on the layer goes to the first frame, the second item to the second frame, and so on. New frames are added to the document, if necessary. If there is only one item in the specified layer, this function has no effect.

必要に応じてフレーム（ステート）を追加し、ドキュメントのフレームに指定されたレイヤー上のオブジェクトを分配します。レイヤー上で最初のオブジェクトは最初のフレーム、2番目のオブジェクトは2番目のフレームとなります。必要に応じてドキュメントに新しいフレームを追加します。指定されたレイヤー上のオブジェクトが1つしかない場合、この関数は効果がありません。