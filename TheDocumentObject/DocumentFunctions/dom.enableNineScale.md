# dom.enableNineScale()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7843.html)

## バージョン

CS3

## 書式

```
dom.enableNineScale(status)
```

## 引数

### status:

A Boolean value that toggles 9-slice scaling between enabled and disabled.

9スライスの有効 / 無効を切り替えるBoolean型。

## 戻り値

なし

## 説明

Enables or disables 9-slice scaling for the selected symbol.

選択したシンボルの9スライスを有効または無効にします。

## サンプル

The following command enables 9-slice scaling for the selected symbol:

次のコマンドを実行すると、選択したシンボルの9スライスを有効にします。

```
fw.getDocumentDOM().enableNineScale(true);
```