# dom.addElementMask()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7fca.html)

## バージョン

4

## 書式

```
dom.addElementMask(mode, {bEnterMaskEditMode})
```

## 引数

### mode:

モードの許容値は、“reveal all"、"hide all"、"reveal selection"、"hide selection"です。ビットマップモードでないまたはピクセルが選択されていない場合、"reveal selection"と"hide selection"は、それぞれ“reveal all"と"hide all"と同じ動作となります。

### bEnterMaskEditMode:

オプションのbEnterMaskEditModeが```true```の場合、Fireworksは新しく追加されたマスクのマスク編集モードになります。省略された場合、デフォルトはfalseです。

## 戻り値

なし

## 説明

選択した要素に新しい空のマスクを追加します。選択範囲に要素マスクを適用されている場合、新しいマスクに置き換わります。この関数を呼び出すときは、要素を1つだけ選択することができます。関数を呼び出した時点で、複数の要素または要素の選択がない場合、Fireworksは例外をスローします。
