# dom.isMasterPageLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-77ba.html)

## バージョン

CS3

## 書式

dom.isMasterPageLayer(layerNum)

## 引数

### layerNum:

A long value that specifies the layer number.

レイヤーナンバーを指定するLong型。

## 戻り値

A Boolean value: true if the specified layer is a master page layer; false otherwise.

Boolean値。指定されたレイヤーがマスターページレイヤーの場合```true```、そうでない場合は```false```。

## 説明

Indicates whether or not the specified layer is a master page layer.

指定したレイヤーがマスターページレイヤーであるかどうかを判定します。

```
fw.getDocumentDOM().isMasterPageLayer(0)
```