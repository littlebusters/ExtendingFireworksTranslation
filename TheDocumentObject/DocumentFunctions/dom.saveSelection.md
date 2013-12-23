# dom.saveSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7fb5.html)

## バージョン

4

## 書式

dom.saveSelection({selectionName}, {toDocument}, {operation})

## 引数

### selectionName:

User-specified name of the selection to save. This parameter is optional. If selectionName is not specified, Fireworks will save the selection with the name "default".

選択範囲を保存する、ユーザーが指定した名前。このパラメーターはオプションです。選択範囲名が指定されない場合、Fireworksは選択範囲を"default"という名前で保存します。

### toDocument:

Index of a currently open document where the selection will be saved. This parameter is optional. If toDocument is not specified, Fireworks will save the selection to the active document.

選択範囲を保存する現在開かれているドキュメントのインデックス。このパラメーターはオプションです。toDocumentが指定されない場合、Fireworksは選択範囲をアクティブなドキュメントに保存します。

### operation:

The operation to be performed on the selection and on the selection being loaded from the selectionName parameter. Acceptable values are "new or replace", "add", "subtract", and "intersect". This parameter is optional. If operation is not specified, Fireworks treats it as if it were specified as "new or replace".

この操作は、selectionNameパラメーターから呼び出される選択範囲に実行されます。許容値は、```"new or replace"``` / ```"add"``` / ```"subtract"``` / ```"intersect"```です。このパラメーターはオプションです。operationが指定されていない場合、Fireworksは```"new or replace"が指定されたとして扱います。

## 戻り値

なし

## 説明

Stores the current selection in bitmap mode as the saved selection. Use dom.restoreSelection() to restore the selection.

保存された選択範囲として、ビットマップモードで現在の選択範囲を保存します。選択範囲を復元するには、dom.restoreJPEGMask()を使います。

## 参照

dom.restoreSelection()