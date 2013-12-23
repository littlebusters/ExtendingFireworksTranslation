# dom.detachSharedLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7808.html)

## バージョン

CS3

## 書式

```
dom.detachSharedLayer(layerNum, pageNum)
```

## 引数

### layerNum:

A long value that specifies the layer number for the layer that is to be detached.

分離するレイヤーのレイヤー番号を指定するLong型。

### pageNum:

A long value that specifies the page number of the page from which the layer will be detached. 

レイヤーを分離したいページのページ番号を指定するLong型。

## 戻り値

なし

## 説明

Detaches the specified shared layer from the specified page. You can only detach a parent layer, not a sub layer. When the parent later is detached, the sub layers are automatically detached as well.

指定されたページから指定した共有レイヤーを分離します。親レイヤーのみならず、サブレイヤーだけでも分離できます。あとで親レイヤーが分離すれば、サブレイヤーも自動的に分離されます。

```
fw.getDocumentDOM().detachSharedLayer(1, 1)
```