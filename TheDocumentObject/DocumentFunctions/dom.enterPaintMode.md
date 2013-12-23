# dom.enterPaintMode()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS20894F1B-D1A7-4794-8428-185CF8A2B22F.html)

## バージョン

3、引数のnewSelectionMaskはMXで追加された。

## 書式

```
dom.enterPaintMode({newSelectionMask})
```

## 引数

### newSelectionMask:

An optional bitmap selection mask. When newSelectionMask is not null, the selection is set on the currently selected bitmap after entering paint mode. This argument is null by default.

オプションのビットマップの選択範囲マスク。newSelectionMaskが```null```でない場合、選択範囲をビットマップモードに移行した後、現在選択されているビットマップが設定されます。
この引数のデフォルトは```null```です。

## 戻り値

なし

## 説明

Enters image edit mode on the selected items. Has no effect if nothing is selected or if a non-image item is selected.

選択したオブジェクトでビットマップモードに移行します。何も選択されていない場合またはビットマップではないオブジェクトが選択されている場合は、効果がありません。（空のビットマップ挿入やビットマップには変換されない）