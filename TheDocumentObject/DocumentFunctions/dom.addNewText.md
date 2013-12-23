# dom.addNewText()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f63.html)

## バージョン

3

## 書式

```
dom.AddNewText(boundingRectangle, bInitFromPrefs)
```

## 引数

### boundingRectangle:

新しいテキストボックスの大きさを指定するRectangle型。（Rectangle型を参照）

### bInitFromPrefs:

bInitFromPrefsが```falese```の場合、スタイルプロパティのデフォルト値が使用されます。```true```の場合は、ユーザーによって設定されている値が使用されます。

## 戻り値

なし

## 説明

指定した大きさの新しいテキストボックスを追加します。（テキストボックスにテキストを配置するには、```dom.setTextRuns()```を使用します）

## サンプル

次のコマンドを実行すると、最近使用されたスタイルプロパティを使用してテキストボックスを追加します。

```
fw.getDocumentDOM().addNewText({left:43, top:220, right:102, bottom:232}, true); 
```