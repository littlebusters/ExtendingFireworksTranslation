# dom.addNewSinglePointPath()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f78.html)

## バージョン

3

## 書式

```
dom.addNewSinglePointPath(controlPointFirst, mainpoint, controlPointLast, bCopyAttrs)
```

## 引数

### controlPointFirst / mainpoint / controlPointLast:

ベジェパスの前パスのポイントハンドル・ポイントアンカー・次パスのポイントハンドルのX/Y座標を指定するPoint型。（Point型を参照）

### bCopyAttrs:

bCopyAttrsが```false```なら、パスのストロークと塗は、ドキュメントの現在のストロークと塗が適用されます。```true```の場合は、塗は透明・ブラシがなし以外に設定されます。

## 戻り値

なし

## 説明

1つのベジェパスで構成される新しいパスを追加します。パスはデフォルトの塗とストローク設定が適用された状態で、現在のフレームとレイヤーに追加されます。パスが追加された後、選択状態となります。

## サンプル

次のコマンドは、指定された座標に、ストロークと塗りはドキュメントの現在のストロークと塗りから設定された、新しい単一のベジェパスを追加します。

```
fw.getDocumentDOM().addNewRectanglePrimitive({left:0, top:0, right:100, bottom:100}, 0);
```
