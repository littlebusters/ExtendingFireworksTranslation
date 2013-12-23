# dom.setSymbolProperties()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WSB34E5FEE-4CE5-4d21-9781-740500B5FAC1.html)

## バージョン

3、9で変更された。

## 書式

dom.setSymbolProperties(currentName, symbolType, newName, status)

## 引数

### currentName:

A string value that specifies the current name of the symbol in the library. If more than one master exists with a name of currentName, only the first master is changed. If null is passed in for currentName, the name property is set for all selected symbols in the library (not the document).

ライブラリにあるシンボルの現在の名前を指定するString型。carrentNameで指定した名前が複数あった場合、最初のマスターを変更します。currentNameに```null```を渡すと、ライブラリで選択しているすべてのオブジェクトの名前を設定します。

### symbolType:

A string value. Acceptable values are "graphic", "button", and "animation".

String型。許容された値は、```"graphic"``` / ```"button"``` / ```"animation"```です。

### newName:

A string value that specifies the new name for the symbol.

シンボルの新しい名前を指定するString型。

### status:

A Boolean value that enables or disables 9-slice scaling on the specified symbol.

指定したシンボルの9スライスを有効または無効にするBoolean型。

## 戻り値

なし

## 説明

Sets the name and symbol type of the specified symbol.

指定したシンボルの名前とタイプを設定します。
