# dom.addNewSymbol()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS37DE5124-3C1C-485c-80A4-FA3F4863B708.html)

## バージョン

3

## 書式

```
dom.addNewSymbol(type, name, bAddToDoc, status)
```

## 引数

### type:

許容値は、```"graphic"```・```"button"```・```"animation"```です。

### name:

シンボル名を指定するString型。

### bAddToDoc:

Boolean型。bAddToDocが```true```の場合は、シンボルインスタンスがドキュメントの中央に挿入されます。```false```の場合は、シンボルはライブラリに作成されますが、インスタンスがドキュメントに挿入されません。

### status:

9スライスの有無を切り替えるBoolean型。

## 戻り値

なし

## 説明

ライブラリに新しいシンボルを追加し、編集モードに移行します。必要に応じて、ドキュメントにシンボルインスタンスを追加します。

## サンプル

次のコマンドは、ライブラリへ"text"という名前の新しいグラフィックシンボルを追加し、ドキュメントにインスタンスを配置します。

```
fw.getDocumentDOM().addNewSymbol("graphic", "text", true, false);
```