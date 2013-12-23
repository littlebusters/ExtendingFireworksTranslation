# dom.setDocumentImageSize()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a88.html)

## バージョン

3、新しい引数をCS3で追加。

## 書式

dom.setDocumentImageSize(boundingRectangle, resolution, currentPageOnly)

## 引数

### boundingRectangle:

A rectangle that specifies the size to which the document should be scaled (see Rectangle data type).

ドキュメントを拡大縮小させるサイズを指定するRectangle型（Rectangle型を参照）。

### resolution:

Specifies the resolution for the scaled document (see Resolution data type).

拡大縮小するドキュメントの解像度を指定します。

### currentPageOnly:

A Boolean value that specifies whether the change in document size applies to all pages or only the current page. If the value is true, only the current page is resized. If it is false, all pages of the document are resized. The default value is true.

ドキュメントサイズの変更を、現在のページのみまたはすべてのページに適用するかどうかを指定するBoolean型。```true```ならば、現在のページのみがリサイズされます。```false```ならば、ドキュメントのすべてのページがリサイズされます。デフォルトは```true```です。

## 戻り値

なし

## 説明

Scales the document to fit in the specified rectangle at the specified resolution.

指定された解像度で指定された矩形に収まるよう、ドキュメントを拡大縮小します。
