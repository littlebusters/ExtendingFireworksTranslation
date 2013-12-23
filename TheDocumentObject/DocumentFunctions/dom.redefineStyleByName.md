# dom.redefineStyleByName()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c36.html)

## バージョン

10

## 書式

dom.redefineStyleByName(sourcestyle, targetstyle)

## 引数
     
### sourcestyle:

Name of the source style.

元となるスタイルの名前。

### targetstyle:

Name of the style that is being redefined.

再定義されるスタイルの名前。

## 戻り値

なし

## 説明

Redefines the target style with the source style.

元となるスタイルで、対象のスタイルを再定義します。

## サンプル

The following command redefines the attributes of the target style “Chrome Reflective 016" with the attributes of the source style “Chrome Misc 011”.

次のコマンドを実行すると、元となるスタイル“Chrome Misc 011”の属性で、対象のスタイル“Chrome Reflective 016"の属性を再定義します。

```
fw.getDocumentDOM().redefineStyleByName("Chrome Misc 011", "Chrome Reflective 016");
```
