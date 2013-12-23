# dom.deleteSavedSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e46.html)

## バージョン

3

## 書式

```
dom.deleteSavedSelection(selection)
```

## 引数

### selection:

The name of the saved bitmap selection.

保護するビットマップの選択範囲の名前

## 戻り値

なし

## 説明

Deletes the selection or the pixel selection if Fireworks is in bitmap mode.

Fireworksがビットマップモードの場合、選択範囲またはビットマップの選択範囲を削除します。

## サンプル

If Fireworks is not in bitmap mode, the following command deletes the selected items. If Fireworks is in bitmap mode, the following command fills the selected items to transparent.

Fireworksがビットマップモードではない場合、次のコマンドを実行すると選択されているオブジェクトを削除します。Fireworksがビットマップモードの場合、次のコマンドを実行すると選択されているオブジェクトの塗りを透明にします。

```
fw.getDocumentDOM().deleteSavedSelection(false);
```