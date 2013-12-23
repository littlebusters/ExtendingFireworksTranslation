# dom.setOnionSkinning()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-798e.html)

## バージョン

3

## 書式

dom.setOnionSkinning(before, after)

## before

### 引数 / after:

Integers that specify the number of frames to display before and after the current one. To disable onion skinning, pass 0 for both arguments. To enable onion skinning for all frames, pass 0 for before and a large number (for example, 99,999) for after.

現在のフレームの前後を表示するフレームナンバーを指定するInteger型。オニオンスキンを無効にするなら、両方の引数に0を渡します。オニオンスキンをすべてのフレームに適用するには、beforeに0を私、afterにそれより大きい数字（例えば99,999）を渡します。

## 戻り値

なし

## 説明

Sets the onion-skinning options for the document.

ドキュメントのオニオンスキンオプションを設定します。

## サンプル

The following command turns on onion skinning two frames before the selected frame and zero frames after it:

次のコマンドを実行すると、選択したフレームより前2フレームのオニオンスキンを有効にし、後ろ0フレームのオニオンスキンを有効にします。

```
fw.getDocumentDOM().setOnionSkinning(2, 0);
```