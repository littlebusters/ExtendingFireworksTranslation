# dom.setDocumentCanvasSize()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a9e.html)

## バージョン

3、新しい引数をCS3で追加

## 書式

dom.setDocumentCanvasSize(boundingRectangle, currentPageOnly)

## 引数

### boundingRectangle:

A rectangle that specifies the new canvas size for the document, in pixels (see Rectangle data type). Any items outside the specified rectangle are removed.

ドキュメントの新しいカンバスサイズをピクセルで指定するRectangle型（Rectangle型を参照）。指定された矩形外のオブジェクトは削除されます。

### currentPageOnly:

A Boolean value that specifies whether the change in canvas size applies to all pages or only the current page. If the value is true, only the current page is resized. If it is false, all pages of the document are resized. The default value is true.

現在のページまたはすべてのページに、カンバスサイズの変更を適用するかどうかを指定するBoolean型。```true```の場合、現在のページのみをリサイズします。```false```の場合、ドキュメントのすべてのページをリサイズします。デフォルトは```true```です。

## 戻り値

なし

## 説明

Sets the document’s canvas size to the specified rectangle and apply the change to the current page or all pages.

指定された矩形にドキュメントのカンバスサイズを設定し、すべてのページまたは現在のページに変更を適用します。

## サンプル

The following command sets the canvas to a size of 200 by 200 pixels:

次のコマンドを実行すると、200×200ピクセルのサイズにカンバスサイズを設定します。

```
fw.getDocumentDOM().setDocumentCanvasSize({left:150, top:150, right:350, bottom:350});
```