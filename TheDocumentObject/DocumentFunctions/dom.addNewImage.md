# dom.addNewImage()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS821E2FAD-5A03-4762-BAD1-C5B3396EAED0.html)

## バージョン

3

## 書式

```
dom.AddNewImage(boundRectangle, bEnterPaintMode)
```

## 引数

### boundRectangle:

追加する画像の範囲（大きさ）を指定するrectangle型（rectangle型を参照）。ドキュメントより大きな画像を作成することはできません。ドキュメントサイズより大きなビットマップを作成した場合は、ドキュメントサイズに制限されたビットマップが作成されます。

### bEnterPaintMode:

bEnterPaintModeが```true```の場合、新しいビットマップを作成し、すぐにビットマップモードに入ります。

## 戻り値

なし

## 説明

ドキュメントに新しい空（透明）のビットマップを追加します。

## サンプル

次のコマンドでは、500×500pxの空のビットマップを作成し、ビットマップモードに入ります。

```
fw.getDocumentDOM().addNewImage({left:0, top:0, right:500, bottom:500}, true);
```