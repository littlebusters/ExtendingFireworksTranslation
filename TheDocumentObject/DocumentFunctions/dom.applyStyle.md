# dom.applyStyle()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f18.html)

## バージョン

3

## 書式

```
dom.applyStyle(styleName, styleIndex)
```

## 引数

### styleName:

A string that specifies the style name to be applied. The style group from which the style is being applied should be selected.

適用するスタイル名を指定するString型。どのスタイルを適用すべきかスタイルグループから選択する必要があります。

### styleIndex:

An index to the style to apply. This is usually zero. However, if there are multiple styles with the same name, styleIndex is used to resolve the ambiguity (0 references the first style with that name, 1 references the second, and so on).

スタイルへのインデックスが適用されます。通常は```0```です。同じ名前を持つスタイルがある場合、styleIndexはあいまいさを解決するために使用されます。（0は1番目ののスタイルの名前を、1は2番目…など）

## 戻り値

なし

## 説明

Applies the specified style to the selection.

選択範囲に指定されたスタイルを適用します。

## 例

The following command applies the first style that Fireworks encounters named “Style 7”, which, in this case, is a default style:

次のコマンドを実行すると、Fireworksは"スタイル7"という名前で検出された最初のスタイルを適用します。

```
fw.getDocumentDOM().applyStyle("Style 7", 0);
```