# dom.setLayerSharing()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79a9.html)

## バージョン

3

## 書式

dom.setLayerSharing(layerIndex, sharedStatus, bUnshareCopiesToAllFrames, bWarnUser)

## 引数

### layerIndex:

An integer value that specifies the layer to be shared or not shared, starting with 0 (although, to specify the current layer, pass –1 here).

共有または非共有するレイヤーを指定する、0から始まるInteger型（現在のレイヤーを指定する場合は、-1を渡します）。

### sharedStatus:

Acceptable values are "shared" or "not shared".

許容された値は、```"shared"``` / ```"not shared"```です。

### bUnshareCopiesToAllFrames:

A Boolean value used only if sharedStatus is "not shared" and the document has multiple frames. If these conditions are met and bUnshareCopiesToAllFrames is true, the items on the layer are duplicated to all the frames of the layer; if false, the items are placed only on the current frame.

ドキュメントに複数のフレームがあり、sharedStatusが```"not shared"```の場合に使われるBoolean型。これらの条件が揃い、bUnshareCopiedToAllFramesが```true```の場合、レイヤー上のオブジェクトはすべてのフレームに複製され、```false```の場合は、現在のフレームのみ配置されます。

### bWarnUser:

Boolean. If bWarnUser is true and bUnshareCopiesToAllFrames is enabled, the user is asked to confirm that data on other frames can be overwritten. If bWarnUser is false, data on other frames of the layer is overwritten without warning.

Boolean型。bWarnUserが```true```かつbUnshareCopiesToAllFramesが有効だった場合、他のフレームの内容を上書きするかをユーザーに確認します。bWarnUserが```false```の場合、他のフレームにあるレイヤーは警告なしに上書きされます。

## 戻り値

なし

## 説明

Changes the Shared layer status of a layer. 

レイヤー共有の状態を変更します。

## サンプル

The following command sets the selected layer to Shared and displays a warning that data loss is possible:

次のコマンドを実行すると、選択しているレイヤーを共有状態にし、データの損失があることを警告で表示します。

```
fw.getDocumentDOM().setLayerSharing(-1, "shared", false, true);
```