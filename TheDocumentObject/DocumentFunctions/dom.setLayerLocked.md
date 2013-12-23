# dom.setLayerLocked()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79b6.html)

## バージョン

3

## 書式

dom.setLayerLocked(layerIndex, frameIndex, bLock, bAllLayers)

## 引数

### layerIndex:

An integer value that specifies the layer to be locked or unlocked, starting with 0 (although, to specify the current layer, pass –1 here). To lock or unlock all the layers on a frame, use the bAllLayers argument.

ロックまたはロック解除するレイヤーを指定する、0から始まるInteger型（現在のレイヤーを指定するには-1を渡します）。フレーム内すべてのレイヤーのロックまたはロック解除をするには、bAllLayersを使います。

### frameIndex:

An integer value that specifies the frame that contains the layer that is to be locked or unlocked, starting with 0 (although, to specify the current frame, pass –1 here).

ロックまたはロック解除をするレイヤーが含まれるフレームを指定する、0から始まるInteger型（現在おフレームを指定するには-1を渡します）。

### bLock:

Boolean. If true, the layer is locked; if false, the layer is unlocked. 

Boolean型。```true```の場合はレイヤーをロックし、```false```の場合はレイヤーのロックを解除します。

### bAllLayers:

Boolean. If true, all the layers on the specified frame are locked or unlocked, and any value passed for layerIndex is ignored. 

Boolean型。```true```の場合は、指定したフレーム内のすべてのレイヤーをロックまたはロック解除します。layerIndexの値は無視されます。

## 戻り値

なし

## 説明

Locks or unlocks one or all the layers on the specified frame.

指定したフレームのレイヤーをロックまたはロック解除します。

## サンプル

The following command locks all the layers on the first frame:

次のコマンドを実行すると、最初のフレームにあるすべてのレイヤーをロックします。

```
fw.getDocumentDOM().setLayerLocked(1, 0, true, true);
```