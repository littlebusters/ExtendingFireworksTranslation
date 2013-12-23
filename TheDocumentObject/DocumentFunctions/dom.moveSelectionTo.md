# dom.moveSelectionTo()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c7f.html)

## バージョン

3

## 書式

dom.moveSelectionTo(location, bMakeCopy, doSubSel)

## 引数

### location:

A point that specifies the x-,y-coordinate values of the location to which the selection is moved or copied (see Point data type).

選択範囲の移動またはコピー先のX/Y座標を指定するPoint型（Point型を参照）。

### bMakeCopy:

Specifies copying instead of moving the selection.

オブジェクトを移動させる代わりにコピーします。

### doSubSel:

If doSubSel is set to true, the function moves only the subselected parts of a path. If the argument is set to false, the function moves the whole object.

doSubSelが```true```の場合、この関数はパス上のパーツのみを移動します。引数に```false```が設定された場合、この関数はオブジェクト全体を移動させます。

## 戻り値

なし

## 説明

Moves or copies the selection to the specified location.

選択範囲を指定した場所に移動またはコピーします。

## 例

The following command copies only the selected parts of a path to the specified coordinates:

次のコマンドを実行すると、選択したパスのパーツだけを指定した座標にコピーします。

```
fw.getDocumentDOM().moveSelectionTo({x:163, y:0}, true, true);
```
