# dom.moveSelectionBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c8c.html)

## バージョン

3

## 書式

dom.moveSelectionBy(delta, bMakeCopy, doSubSel)

## 引数

### delta:

A point that specifies the x,y coordinate values by which the selection moved (see Point data type). For example, passing ({x:1,y:2}) moves the selection 1 pixel to the right and 2 pixels down.

選択範囲の移動させるX/Y座標を指定するPoint型（Point型を参照）。例として、```{x:1,y:2}```を渡した場合、ポイントは右へ1ピクセル・下へ2ピクセル移動します。

### bMakeCopy:

The items that are copied instead of moved.

オブジェクトを移動させる代わりにコピーします。

### doSubSel:

If doSubSel is set to true, the function moves only the subselected parts of a path. If the argument is set to false, the function moves the whole object.

doSubSelが```true```の場合、この関数はパス上のパーツのみを移動します。引数に```false```が設定された場合、この関数はオブジェクト全体を移動させます。

## 戻り値

なし

## 説明

Moves the selected items by the specified amount or makes a copy of them and offsets them from the original by the specified amount.

選択されたオブジェクトを指定量移動したり、オリジナルからオフセットしたコピーを作成したりします。

## 例

The following command moves the selected items right by 62 pixels and 84 pixels down:

次のコマンドを実行すると、選択したオブジェクトが右に62ピクセル・下に84ピクセル移動します。

```
fw.getDocumentDOM().moveSelectionBy({x:62, y:84}, false, false);
```