# dom.lockNineScale()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7844.html)

## バージョン

CS3

## 書式

dom.lockNineScale(status)

## 引数

### status:

A Boolean value that toggles 9-slice scaling between locked and unlocked.

9スライスによる拡大・縮小のロックとロック解除を切り替えるBoolean型。

## 戻り値

なし

## 説明

Locks or unlocks 9-slice scaling guides for the selected symbol.

選択したシンボルの9スライスガイドによる拡大・縮小のロック・ロック解除をします。

## サンプル

The following command locks 9-slice scaling guides for the selected symbol:

次のコマンドを実行すると、選択したシンボルの9スライスをロックします。

```
fw.getDocumentDOM().lockNineScale(true);
```