# dom.addNewRectanglePrimitive()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f80.html)

## バージョン

4

## 書式

```
dom.addNewRectanglePrimitive(boundingRectangle, roundness)
```

## 引数

### boundingRectangle:

新しく追加される矩形プリミティブの大きさを指定した、Rectangle型。

### roundness:

角丸の大きさを指定する、0から1までのFloat型。（0は角丸なし、1は100%の角丸です）

## 戻り値

なし

## 説明

指定した大きさの新しい矩形プリミティブを追加します。矩形プリミティブは、ドキュメントのパス属性を利用し、現在のフレームとレイヤーに追加され、角丸や変形などいくつかの編集可能なプロパティを持っています。矩形は長方形と同様のパスで、矩形プリミティブは矩形属性を維持し、コーナーをドラッグしても四辺を保つ点が異なります。

## サンプル

次のコマンドは、指定した大きさで角丸のない矩形プリミティブを追加します。

```
fw.getDocumentDOM().addNewRectanglePrimitive({left:0, top:0, right:100, bottom:100}, 0);
```

## 次を参照

dom.addNewRectangle(), fw.ungroupPrimitives()
