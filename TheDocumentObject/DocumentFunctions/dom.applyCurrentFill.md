# dom.applyCurrentFill()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f2c.html)

## バージョン

3

## 書式

```
dom.applyCurrentFill(NoNullFills)
```

## 引数

### NoNullFills:

If bNoNullFills is true and the current fill is None, then a default fill is applied instead of no fill.

bNoNullFillsが```true```で塗りつぶしが「なし」の場合、「塗りなし」の代わりにデフォルトの塗りが適用されます。

## 戻り値

なし

## 説明

Applies the document’s current fill to the selection.

選択範囲に、ドキュメントの現在の塗りを適用します。

## サンプル

The following command applies the current fill to the selection:

次のコマンドは、選択範囲に現在の塗りを適用します。

```
fw.getDocumentDOM().applyCurrentFill(true);
```