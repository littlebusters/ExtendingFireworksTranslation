# dom.addNewImageViaCut()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7fa2.html)

## バージョン

MX

## 書式

```
dom.addNewImageViaCut()
```

## 引数

なし

## 戻り値

なし

## 説明

ドキュメントにビットマップモードで現在選択している範囲を、新しいビットマップとして追加します。新しいビットマップは、現在のビットマップの上に配置されます。このコマンドを実行するには、ピクセルを選択している必要があります。選択していた範囲は、元のビットマップから切り取られます。新しいビットマップは、ビットマップモードとしてFireworksに表示されます。

## サンプル

次のコマンドでは、500×500pxの空のビットマップを作成し、ビットマップモードに入ります。

```
fw.getDocumentDOM().addNewImage({left:0, top:0, right:500, bottom:500}, true);
```
