# dom.addNewSubLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS656C2AB5-46D8-47a8-AC07-431D42F49A02.html)

## バージョン

CS3

## 書式

```
dom.addNewSubLayer(index, name, shared)
```

## 引数

### index:

新しいサブレイヤーの親となるレイヤーのインデックス値を指定するLong型。

### name:

新しいサブレイヤーの名前を指定するString型。名前が```null```の場合、新しくレイヤー名が生成されます。

### shared:

サブレイヤーを共有レイヤーに指定するBoolean型。

## 戻り値

新しいサブレイヤーの名前を含むString値。

## 説明

ドキュメントに新しいサブレイヤーを追加され、それが現在のレイヤーとなります。

## サンプル

次のコマンドは、Fireworksで生成されたデフォルト名の共有されていないサブレイヤーを、indexが0のレイヤーに追加します。

```
fw.getDocumentDOM().addNewSubLayer(0, null, false);
```
