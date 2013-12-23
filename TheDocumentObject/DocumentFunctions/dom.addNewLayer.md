# dom.addNewLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f9c.html)

## バージョン

3

## 書式

```
dom.addNewLayer(name, bshared)
```

## 引数

### name:

新しいレイヤーの名前を指定するString型。```null```の場合、新しくレイヤー名が生成されます。

### bshared:

新しいレイヤーを共有レイヤーにするかどうかを指定するBoolean型。

## 戻り値

新しいレイヤー名を含むString値。

## 説明

ドキュメントに新しいレイヤーを追加し、現在のレイヤーとします。

## サンプル

次のコマンドは、Fireworksで生成されたデフォルト名で、新しい共有されていないレイヤーを追加します。

```
fw.getDocumentDOM().addNewLayer(null, false);
```
