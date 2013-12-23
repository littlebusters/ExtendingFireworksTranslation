# dom.enableElementMask()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7fce.html)

## バージョン

4、新しい引数はMX

## 書式

```
dom.enableElementMask(enable, selectAndEnterPaintModeIfPossible, {newSelectionMask})
```

## 引数

### enable:

A Boolean value that toggles the element mask between enabled (true) and disabled (false).

オブジェクトマスクの有効と無効を切り替えるBoolean型。

### selectAndEnterPaintModeIfPossible:

A Boolean value that determines the mode for the mask. If selectAndEnterPaintModeIfPossible is true, and the mask is a bitmap mask, then bitmap mode is entered for the mask. It is false by default.

マスクモードを決定するBoolean型。selectAndEnterPaintModeIfPossibleがtrueかつマスクはビットマップマスクの場合、ビットマップモードとしてマスクが追加されます。デフォルト値は```false```です。

### newSelectionMask[Optional] :

An optional bitmap selection mask. If newSelectionMask is not null, and selectAndEnterPaintModeIfPossible is true, the selection will be set on the mask after entering paint mode. This argument is null by default.

ビットマップマスクのオプション。newSelectionMaskが```null```ではないかつ```true```ならば、選択範囲をマスクとして追加し、ビットマップモードに移行します。この引数はnullがデフォルトです。

## 戻り値

なし

## 説明

Enables or disables the element mask on the selected element. If more than one element (or no elements) are selected when this function is called, Fireworks throws an exception.

選択されているオブジェクトのマスクを有効化または無効化します。この関数が呼び出された時に1つ以上のオブジェクトが選択（または選択されていない）されていない場合、Fireworksは例外を投げます。