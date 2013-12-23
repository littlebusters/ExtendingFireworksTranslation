# dom.setButtonOptions()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7ab7.html)

## バージョン

3

## 書式

dom.setButtonOptions(exportOptions, URLString, altTagString, targetTagString, sliceName, statusMessage)

## 引数

### exportOptions:

An ExportOptions object (see ExportOptions object). 

ExportOptions型。（ExportOptions型を参照）

### URLString:

A string that specifies the URL for the button(s).

ボタンのURLを指定するString型。

### altTagString and targetTagString:

Specify the text for the button alt tag and target tag.

ボタンのalt属性とtarget属性を指定するテキスト。

### sliceName:

A string that specifies the name to be assigned to the slice that is associated with the button. If it is null, the slice is set to be named automatically.

ボタンと関連付けられたスライスに割り当てられた名前を指定するString型。```null```の場合、自動的にスライス名が設定されます。

### statusMessage:

A string that specifies a status message to appear in the browser status line. If an empty string or null is passed, no status message appears.

ブラウザーのステータスバーに表示されるステータスメッセージを指定するString型。空文字または```null```を渡した場合、ステータスメッセージは表示されません。

## 戻り値

なし

## 説明

Sets the Button Export options. If the user edits a button, it sets options for the button being edited; if the user edits a normal document, it sets options for all the selected buttons.

ボタンの書き出しオプションを設定します。ユーザーがボタンを編集している場合、編集されているボタンのオプションを設定し、ユーザーがドキュメントを編集している場合、選択しているボタンのオプションを設定します。
