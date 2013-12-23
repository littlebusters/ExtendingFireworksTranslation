# dom.setLayerDisclosure()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79bd.html)

## バージョン

4

## 書式

dom.setLayerDisclosure(layerIndex, bDisclosed)

## 引数

### layerIndex:

An integer value that specifies the layer that contains the elements to be displayed or hidden, starting with 0 (although, to specify the current layer, pass –1 here).

表示または非表示するオブジェクトが含まれるレイヤーを指定する、0から始まるInteger型。（現在のレイヤーを指定するには-1を渡します）

### bDisclosed:

Boolean. If true, all elements on the specified layer are displayed in the Layers list; if false, only the layer name appears on the list. 

Boolean型。```true```ならば、指定されたレイヤーのすべてのオブジェクトをレイヤーリストに表示します（レイヤーリストの展開）。```false```ならば、レイヤー名のみをリストに表示します。

## 戻り値

なし

## 説明

Specifies whether the elements on a specified layer appear in the Layers list. Disclosure affects the layer, regardless of which frame appears.

レイヤーリストに指定されたレイヤーのオブジェクトを表示するかどうかを指定します。フレームが表示されているかに関わらず、開示はレイヤーに影響を影響します。

## 参照

dom.setAllLayersDisclosure()