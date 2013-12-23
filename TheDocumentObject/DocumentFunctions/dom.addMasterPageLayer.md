# dom.addMasterPageLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS2509E549-9FAD-4b32-B8B1-348A159A3B11.html)

## バージョン

CS3

## 書式

```
dom.addMasterPageLayer()
```

## 引数

マスターページレイヤー追加するには、ドキュメントにマスターページレイヤーがすでに準備されている必要があります。マスターページレイヤーを挿入するレベル（深度）を指定します。

__例：__

```
fw.getDocumentDOM().addMasterPageLayer(-1)
```

## 戻り値

なし

## 説明

現在のページにあるレイヤーの最下部に、マスターページレイヤーを追加します。