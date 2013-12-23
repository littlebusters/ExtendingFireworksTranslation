# dom.deleteSymbol()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e38.html)

## バージョン

3

## 書式

```
dom.deleteSymbol(symbolName)
```

## 引数

### symbolName:

The name of the symbol to delete from the library. If more than one symbol exists with this name, only the first symbol is deleted.

- To delete all the selected symbols from the library (not document), pass null.
- If the deleted symbols contain any active instances in the document, the instances are also deleted.

ライブラリから削除するシンボルのシンボル名。同じ名前のシンボルが複数ある場合、最初のシンボルが削除されます。

- ライブラリから選択されたすべてのシンボルを削除する場合は、```null```を渡します。（ドキュメントではない）
- 削除されたシンボルのインスタンスがドキュメント上に含まれる場合、インスタンスも同様に削除されます。


## 戻り値

なし

## 説明

Deletes the specified symbols from the library.

ライブラリから指定されたシンボルを削除します。

## サンプル

The following command deletes the selected symbols from the library as well as any active instances from the document:

次のコマンドを実行すると、ライブラリで選択されたシンボルと、ドキュメントでアクティブなインスタンスが削除されます。

```
fw.getDocumentDOM().deleteSymbol(null);
```
