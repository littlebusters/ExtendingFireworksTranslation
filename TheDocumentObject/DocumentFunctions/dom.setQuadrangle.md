# dom.setQuadrangle()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7980.html)

## バージョン

3

## 書式

dom.setQuadrangle(pTopLeft, pTopRight, pBottomRight, pBottomLeft, options)

## 引数

### pTopLeft / pTopRight / pBottomRight / pBottomLeft:

Relative coordinates of a quadrangle expressed as percentages of an arbitrary square. These are not specific x, y coordinates.

四角を相対的な座標で示した矩形の割合。X / Y 座標の指定ではありません。

### options:

Acceptable values are "transformAttributes", "autoTrimImages", and "autoTrimImages transformAttributes".

許容された値は、"transformAttributes" / "autoTrimImages" / "autoTrimImages transformAttributes"です。

## 戻り値

なし

## 説明

Creates a bounding quadrangle based on percentages of an arbitrary square, and then transforms the selection within the bounding quadrangle. The effect is the same as performing a transform operation within Fireworks, and then replaying the Transform step from the History panel while other items are selected.

任意の矩形の割合を四角形の境界の基準として作成し、選択範囲内の四角を変換します。効果はFireworks内の変換操作と同じで、選択したオブジェクトに対し、ヒストリーパネルから同じ変形を再生できます。

## サンプル

The following command performs the transform operation on the selection within the specified points:

次のコマンドを実行すると、選択範囲内を指定したポイントで変形します。

```
fw.getDocumentDOM().setQuadrangle({x:-0.300884962, y:0.207964599}, {x:1, y:0.207964599}, {x:1, y:0.792035401}, {x:-0.300884962, y:0.792035401}, "autoTrimImages transformAttributes");
```