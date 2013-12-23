# dom.close()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7eaa.html)

## バージョン

3

## 書式

```
dom.close(bPromptToSaveChanges)
```

## 引数

### bPromptToSaveChanges:

If bPromptToSaveChanges is true, and the document was changed since the last time it was saved, the user is prompted to save any changes to the document. If bPromptToSaveChanges is false, the user is not prompted, and changes to the document are discarded.

bPromptToSaveChangesが```true```かつドキュメントの最後の保存以降に変更された場合、ユーザーにドキュメントを保存するするように要求するメッセージが表示されます。bPromptToSaveChangesが```false```の場合、ユーザーに確認なく、ドキュメントへの変更を破棄します。

## 戻り値

なし

## 説明

Closes the document.

ドキュメントを閉じます。