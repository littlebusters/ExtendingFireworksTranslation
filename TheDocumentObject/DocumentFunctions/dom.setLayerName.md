# dom.setLayerName()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79b6.html)

## バージョン

3

## 書式

dom.setLayerName(layerIndex, layerName)

## 引数

### layerIndex:

An integer value that specifies the layer to be renamed, starting with 0 (although, to specify the current layer, pass –1 here).

名前を変更するレイヤーを指定する、0から始まるInteger型（現在のレイヤーを指定する場合は、-1を渡します）。

### layerName:

A string that specifies the new name for the layer.

レイヤーの新しい名前を指定するString型。

## 戻り値

なし

## 説明

Renames the specified layer. Layers aren’t required to have unique names, so no duplicate checking occurs.

指定したレイヤーの名前を変更します。レイヤーは一意の名前を持つ必要がなく、重複チェックは行われません。