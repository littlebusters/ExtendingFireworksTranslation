# dom.deleteLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e54.html)

## バージョン

3

## 書式

```
dom.deleteLayer(layerIndex)
```

## 引数

### layerIndex:

An integer value that specifies the layer to be deleted, starting with 0 (although, to specify the current layer, pass –1 here).

削除するレイヤーを指定するInteger型。始めはレイヤーは0です。（ただし現在のフレームを指定する場合は、-1を渡します）

## 戻り値

なし

## 説明

Deletes a layer.

レイヤーを削除します。

## サンプル

The following command deletes the current layer:

次のコマンドは、現在のレイヤーを削除します。

```
fw.getDocumentDOM().deleteLayer(-1);
```