# dom.convertToSymbol()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WSF2351E11-BB77-4d9a-9165-31A53104D53B.html)

## バージョン

3

## 書式

```
dom.convertToSymbol(type, name, status)
```

## 引数

### type:

Acceptable values are "graphic", "button", and "animation".

許容される値は、```graphic```（グラフィック） / ```button```（ボタン） / ```animtion```（アニメーション）です。

### name:

A name for the new symbol.

新しいシンボルの名前です。

### status:

A Boolean value that toggles 9-slice scaling between enabled and disabled.

9 スライスの有効 / 無効を切り替えるBoolean型。

## 戻り値

なし

## 説明

Converts the selected items to a new symbol.

## 例

The following command creates a graphic symbol from the selected item and names it “star”:

```
fw.getDocumentDOM().convertToSymbol("graphic", "star");
```

## 参照

dom.convertToAnimSymbol(), dom.convertAnimSymbolToGraphicSymbol()