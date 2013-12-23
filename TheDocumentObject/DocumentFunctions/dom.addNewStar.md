# dom.addNewStar()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f71.html)

## バージョン

3

## 書式

```
dom.AddNewStar(numSides, spikiness, bIsStar, centerPoint, outsidePoint)
```

## 引数

### numSides:

新しいパスの辺数を指定するInteger型。

### spikiness:

星形や多角形の規則性を制御するFloat型。-1を渡すとFireworksが適正な値を計算し、0から1の間を渡すことで手動制御できます。

### bIsStar:

blsStarが```true```の場合、指定したポイント数を持つ星形が生成されます。```fales```の場合、指定された辺数の正多角形が生成されます。

### centerPoint:

星形や多角形の中心点を指定します。（Point型参照）

### outsidePoint:

星形や多角形の半径を指定するPoint型。

## 戻り値

なし

## 説明

新しい星形や多角形を追加します。

## サンプル

次のコマンドは5辺の星形が追加されます。

```
fw.getDocumentDOM().addNewStar(5, -1, true, {x:186, y:72}, {x:265, y:89});
```
