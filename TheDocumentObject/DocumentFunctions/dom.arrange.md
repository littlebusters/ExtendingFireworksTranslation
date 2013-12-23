# dom.arrange()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f11.html)

## バージョン

3

## 書式

```
dom.arrange(arrangemode)
```

## 引数

### arrangemode:

Acceptable values for arrangemode are "back", "backward", "forward", and "front".

arrangemodeの許容値は、```front```（最前面） / ```forward```（前面） / ```back```（最背面） / ```backward```（背面）です。

## 戻り値

なし

## 説明

Arranges the selection.

選択範囲に重ね順を適用します。

## 例

The following command brings the selected items to the front:

次のコマンドは、選択範囲のオブジェクトを最前面に移動させます。

```
fw.getDocumentDOM().arrange("front");
```