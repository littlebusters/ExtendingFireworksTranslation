# dom.clipPasteFromChannelToChannel()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7ec0.html)

## バージョン

MX

## 書式

```
dom.clipPasteFromChannelToChannel(fromChannel, toChannel)
```

## 引数

### fromChannel:

If the current selection is not a single bitmap, a new opaque bitmap is created and the fromChannel is pasted in to all three color channels of the new bitmap, resulting in a grayscale image. This first argument is ignored if the current selection is not a single bitmap.

選択範囲が単一のビットマップではない場合、新しい不透明なビットマップが作成され、formChannelがRGBそれぞれのチャンネルに貼り付けられ、結果グレースケース画像になります。現在の選択範囲が単一のビットマップではない場合、最初の引数は無視されます。

### toChannel:

If the currently selected element is a bitmap, the toChannel argument is used to specify where to paste the color data.

現在選択されている要素がビットマップの場合、toChannel引数は、クリップボードをどのチャンネルに貼り付けるかを指定します。

## 戻り値

なし

## 説明

Pastes the specified color channel on the clipboard into each of the RGB channels of a new image or into the specified channel of the selected image, if any.

クリップボード上にあるそれぞれのRGBチャンネルで指定されたカラーチャンネルから、新しいビットマップまたは選択範囲の指定されたチャンネルに貼り付けます。

## サンプル

The following command copies the red data from the clipboard into the red channel:

次のコマンドを実行すると、クリップボードの赤チャンネルを赤チャンネルにコピーします。

```
fw.getDocumentDOM().clipPasteFromChannelToChannel("red", "red");
```

The following command copies the green data from the clipboard into the alpha channel:

次のコマンドを実行すると、クリップボードの緑チャンネルをアルファチャンネルにコピーします。

```
fw.getDocumentDOM().clipPasteFromChannelToChannel("green", "alpha");
```