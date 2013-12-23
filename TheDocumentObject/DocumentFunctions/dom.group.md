# dom.group()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7f86.html)

## バージョン

3

## 書式

```
dom.group({type})
```

## 引数

### type:

An optional string that specifies how to group the items. Acceptable values are "normal", "mask to image", and "mask to path". If the argument is omitted, "normal" is assumed. In Fireworks 4, "mask to image" and "mask to path" are deprecated.

オブジェクトのグループ化のオプションを指定する string値。許容値は、"normal"、"mask to image"、"mask to path"。引数が省略された場合は、"normal"となります。"mask to image"および"mask to path"はFireworks 4では非推奨です。

## 戻り値

なし

次のいずれかの文字： ```left``` / ```center``` / ```right``` / ```justify``` / ```stretch``` / ```vertical left``` / ```vertical center``` / ```vertical right``` / ```vertical justify``` / ```vertical stretch```
```null```が返る場合、テキストが複数の行揃えを持っているか、選択範囲にテキストが含まれていません。

## 説明

Groups the selection. To ungroup elements use dom.ungroup() (see dom.ungroup()).

選択範囲をグループ化します。グループ化を解除するには、`dom.ungroup()`を使用します。（dom.ungroup()を参照）

## サンプル

The following command sets the selected group to mask to the image:

次のコマンドを実行すると、選択されたグループの画像にマスクを設定します。

```
replace with fw.getDocumentDOM().group("normal");
```