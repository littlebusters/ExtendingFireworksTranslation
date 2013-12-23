# dom.addNewOval()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f8f.html)

## バージョン

3

## 書式

```
dom.addNewOval(boundingRectangle)
```

## 引数

### boundingRectangle

楕円の大きさを指定するRectangle型。（Rectangle型を参照）

## 戻り値

なし

## 説明

指定した四角の大きさに沿った新しい楕円を追加します。楕円は、ドキュメントで現在設定されているパス属性を使い、現在のレイヤーとフレームに追加されます。

## サンプル

次のコマンドは、指定した座標内に新しい楕円を追加します。

```
fw.getDocumentDOM().addNewOval({left:72, top:79, right:236, bottom:228});
```
