# dom.getParentLayerNum()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-781a.html)

## バージョン

CS3

## 書式

```
dom.getParentLayerNum(currentLayer)
```

## 引数

### currentLayer:

A long value that specifies the index of the current layer. 

現在のレイヤーインデックスを指定する、Long型。

## 戻り値

The layer index number of the parent layer. If the specified layer is a top-level layer, it returns a value of -1.

親レイヤーのレイヤーインデックス番号。トップレベルのレイヤーを指定した場合、-1が返ります。

## 説明

Gets the parent layer index number for the specified layer.

指定したレイヤーの親レイヤーのインデックス番号を取得します。