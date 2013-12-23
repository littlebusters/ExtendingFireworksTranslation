# dom.filterSelectionByID()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d95.html)

## バージョン

8

## 書式

```
dom.filterSelectionByID(ID)
```

## 引数

### ID:

The EffectMoaID of the filter you want applied.

適用したいフィルターのEffectMoaID。

## 戻り値

なし

## 説明

Applies the specified pixel filter to the selection as a permanent action, not as a Live Effect. (To apply filters that can also be Live Effects, you can use dom.filterSelection().) This function always displays a dialog box.

恒久的なアクションとして選択されたピクセルに、ライブエフェクトできないフィルタを適用されます。（ライブエフェクトできるフィルタを適用するには、```dom.filterSelection()```を使用します）この関数は常にダイアログボックスが表示されます。