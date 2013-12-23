# dom.saveCopyAs()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b94.html)

## バージョン

3

## 書式

dom.saveCopyAs(fileURL)

## 引数

### fileURL

A string, which is expressed as a file://URL, that specifies the directory and name under which the copy should be saved. 

コピーを保存するために必要なディレクトリとその名前を指定する、file://URLとして表現されるStrig型。

## 戻り値

true if the save operation is successful; false otherwise.

```true```なら保存は成功、```false```ならそれ以外です。

## 説明

Saves a copy of the document in a specified directory with a specified name. This function does not affect the document’s filePathForSave or isDirty properties.

指定したディレクトリに指定した名前でドキュメントのコピーを保存します。この関数は、ドキュメントのfilePathForSaveまたはisDirtyプロパティには影響を与えません。
