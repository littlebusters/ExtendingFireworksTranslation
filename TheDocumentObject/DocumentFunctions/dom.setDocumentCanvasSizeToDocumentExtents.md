# dom.setDocumentCanvasSizeToDocumentExtents()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a97.html)

## バージョン

3

## 書式

dom.setDocumentCanvasSizeToDocumentExtents(bGrowCanvas)

## 引数

### bGrowCanvas

Boolean. If true, the canvas can expand or shrink in size; if false, it only shrinks.

Boolean型。```true```ならば、カンバスを拡張または縮小することができ、```false	```の場合は、カンバスを縮小することができます。

## 戻り値

なし

## 説明

Calculates the size of all the items in the document and resizes the document canvas to that size. This action is the same behavior as Modify > Trim Canvas.

ドキュメントにあるすべてのオブジェクトのサイズを計算し、ドキュメントのカンバスサイズをそのサイズに変更します。このアクションは、「変更 -> カンバス -> カンバスを切り抜き」と同じ動作です。

## サンプル

The following command resizes the canvas to include all the items in the document, enlarging the canvas if necessary:

次のコマンドを実行すると、必要に応じてカンバスを拡大し、ドキュメントにあるすべてのオブジェクトを含むように、カンバスをリサイズします。

```
fw.getDocumentDOM().setDocumentCanvasSizeToDocumentExtents(true);
```