# dom.restoreSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7bb3.html)

## バージョン

4

## 書式

dom.restoreSelection(selectionName, fromDocument, {operation}, {invert})

## 引数

### selectionName:

User-specified name of the selection to restore. If selection name is not specified, the selection named "default" will be restored.

復元する選択範囲のユーザが指定した名前。選択範囲に名前が指定されていない場合、"default"という選択範囲が復元されます。

### fromDocument:

Index of a currently open document from which to load the selection. If the from document is not specified, the selection will be restored from the active document.

選択範囲を読み込む開かれているドキュメントのインデックス。ドキュメントが指定されない場合、アクティブなドキュメントから復元されます。

### operation:

Operation to perform on the selection and on the document being loaded. Acceptable values are "new or replace", "add", "subtract", and "intersect". This parameter is optional. If the operation is not specified, Fireworks will behave as if "new or replace" is specified.

この操作は、ドキュメントに選択範囲が読み込まれている状態で実行できます。許容値は、```"new or replace"``` / ```"add"``` / ```"subtract"``` / ```"intersect"```です。このパラメーターはオプションです。この操作が指定されていない場合、Fireworksは```"new or replace"```が指定されたとして動作します。

### invert:

A Boolean value that determines if the selection should be inverted before performing the operation on it. This parameter is optional. If invert is not specified, defaults to false.

選択範囲を反転させるかどうかを決定するBoolean値。このパラメーターはオプションです。invertに指定がない場合、デフォルトは```false```です。

## 戻り値

true if the selection is inverted; otherwise false.

選択範囲が反転したなら```true```、そうでなければ```false```です。

## 説明

Restores the selection that is specified in dom.saveSelection().

dom.saveSelection()から指定した選択範囲を復元します。

## 参照

dom.saveSelection()
