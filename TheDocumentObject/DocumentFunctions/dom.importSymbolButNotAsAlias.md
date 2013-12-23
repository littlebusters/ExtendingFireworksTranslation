# dom.importSymbolButNotAsAlias()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d20.html)

## バージョン

MX

## 書式

dom.importSymbolButNotAsAlias(filepath, whichSymbol)

## 引数

### filepath:

The fileURL of the file that contains the symbol to be copied.

コピーされるシンボルが含まれるファイルパス（fileURL）。

### whichSymbol:

The index of the symbol within the document, which is specified in the filepath.

ファイルパスで指定される、ドキュメント内のシンボルインデックス。

## 戻り値

なし

## 説明

Extracts the component elements from the selected symbol and places copies of those elements in the document.

選択されたシンボル及びドキュメント内のそれらの要素のコピーから、構成要素を抽出します。

This function is similar to the dom.importSymbol API. dom.importSymbol places an instance of a symbol in your document—for example, when you select Edit > Libraries > Buttons, and dom.importSymbolButNotAsAlias extracts the component elements from the selected symbol and places copies of those elements in the document. dom.importSymbolButNotAsAlias does not place in an instance in the document.

この関数は、dom.importSymbol AIPと似ています。dom.importSymbolはドキュメントにシンボルのインスタンスを配置します。例えば、編集 > ライブラリ > ボタン（シンボルの編集　> （PI内の）ボタンの読み込み）を選択すると、dom.importSymbolButNotAsAliasは選択したシンボルから構成要素を抽出し、ドキュメント内のそれらの要素のコピーを配置します。dom.importSymbolButNotAsAliasはドキュメントにインスタンスを配置しません。
