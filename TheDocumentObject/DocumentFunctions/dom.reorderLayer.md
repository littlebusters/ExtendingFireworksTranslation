# dom.reorderLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7bda.html)

## バージョン

3、新しい引数はCS3から

## 書式

dom.reorderLayer(layerToMove, layerToPutItBefore, bMakeCopy, posInLayer, aboveBelowInto)

## 引数
     
### layerToMove:

A zero-based index that specifies which layer to move or copy.

移動またはコピーするレイヤーを指定する0から始まるインデックス。

### layerToPutItBefore:

A zero-based index that specifies where to place the layer to be moved or copied. For example, if you pass 1 for layerToMove and 0 for layerToPutItBefore, the second layer is placed before the first layer.

移動またはコピーするフレームの配置を指定する0から始まるインデックス。例えば、layerToMoceに1を、layterToPutItBeforeに0を渡した場合、2番目のレイヤーは最初のレイヤーの前に配置します。

### bMakeCopy:

Boolean. If true, the specified layer is copied instead of moved.

Boolean型。```true```ならば、指定されたレイヤーはコピーせず移動します。

### aboveBelowInto:

A zero-based index that specifies whether the layer being moved or copied will be a parent layer or a sub layer. A value of 0 indicates that the layer goes above the destination layer; a value of 1 indicates that the layer goes below the destination later, a value of 2 indicates that the layer goes into the destination layer to become a sub layer.

移動またはコピーするレイヤーサブレイヤーまたは親レイヤーを指定する、0ベースのインデックス。0は目的のレイヤーより上位のレイヤーを示し、1は目的のレイヤーより下のレイヤーを示し、2は目的のレイヤーの中に入ることを示します。

## 戻り値

なし

## 説明

Moves or copies the specified frame before another specified frame.

指定したレイヤーを別の指定されたレイヤーの前に移動またはコピーします。
