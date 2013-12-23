# dom.filterSelectionByName()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d8f.html)

## バージョン

3

## 書式

```
dom.filterSelectonByName(category, name)
```

## 引数

### category:

A string that specifies the category of the pixel filter to be applied. Acceptable values depend on which filters you have installed.

適用したいピクセルフィルターのカテゴリを指定するString型。許容値はインストールされているフィルターに依存します。

### name:

A string that specifies the name of the pixel filter to be applied. Acceptable values depend on which filters you have installed.

適用したいピクセルフィルター名を指定するString型。許容値はインストールされているフィルターに依存します。

## 戻り値

なし

## 説明

Applies the specified pixel filter to the selection as a permanent action, not as a Live Effect. (To apply filters that can also be Live Effects, you can use dom.filterSelection().) This function always displays a dialog box.

恒久的なアクションとして選択されたピクセルに、ライブエフェクトできないフィルタを適用されます。（ライブエフェクトできるフィルタを適用するには、```dom.filterSelection()```を使用します）この関数は常にダイアログボックスが表示されます。