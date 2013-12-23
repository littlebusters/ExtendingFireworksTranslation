# dom.deleteSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e3f.html)

## バージョン

3

## 書式

```
dom.deleteSelection(bFillDeletedArea)
```

## 引数

### bFillDeletedArea:

Fireworksがビットマップモードでない場合、この引数は無視されます。Fireworksがビットマップモードで、bFillDeletedArea が```true```の場合、削除されたピクセルは、現在の塗りつぶし色で塗りつぶされます。```false```の場合、削除されたピクセルは透明になります。

## 戻り値

なし

## 説明

選択範囲の削除またはビットマップモードであれば選択しているピクセルを削除します。

## サンプル

Fireworksがビットマップモードになっていない場合は、次のコマンドで選択しているアイテムを削除します。Fireworksがビットマップモードになっている場合は、次のコマンドで選択範囲が透明になります。

```
fw.getDocumentDOM().deleteSelection(false);
```
