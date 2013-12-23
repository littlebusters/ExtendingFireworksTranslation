# dom.importSymbol()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d26.html)

## バージョン

3

## 書式

dom.importSymbol(fileURL, bAddToDoc, bAllowUI)

## 引数

### fileURL:

The name of the file to be imported into the library, which is expressed as a file://URL.

file://URLのように表されるファイル名を、ライブラリへ読み込むことができます。

### bAddToDoc:

If bAddToDoc is true, the symbol is added to the library and an instance of the symbol is inserted into the center of the document. If it is false, the symbol is added only to the library.

bAddToDocが```true```なら、シンボルがライブラリに追加され、かつドキュメントの中央にインスタンスが挿入されます。```false```ならば、シンボルがライブラリに追加されるだけとなります。

### bAllowUI:

If bAllowUI is true, and fileURL is a Fireworks document that contains symbols, then a dialog box lets the user specify which symbols to import from the external file. If it is false, all the symbols in the external file are imported.

bAllowUIが```true```かつ、fileURLがFireworksのドキュメントに含まれるシンボルならば、ユーザーがダイヤログボックスでシンボルを外部ファイルから読み込むかどうかを指定できます。```false```の場合、すべてのシンボルを外部ファイルから読み込みます。

## 戻り値

なし

## 説明

Imports the specified external graphics file (for example, GIF, JPEG, or Fireworks document) into the library of the document.

指定した外部ファイル（例： GIF / JPEG / Fireworsk ドキュメント）をドキュメントのライブラリへ読み込みます。