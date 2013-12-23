# dom.save()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b9a.html)

## バージョン

3

## 書式

dom.save({bOkToSaveAs})

## 引数

### bOkToSaveAs:

If this optional argument is true or omitted and the file was never saved, then the Save As dialog box appears. If bOkToSaveAs is false and the file was never saved, the file is not saved.

これはオプションの引数で、```true```または省略され、ファイルが保存出来なかった場合は、「別名で保存」ダイアログを表示します。bOkToSaveAdが```false```でファイルが保存できなかった場合、ファイルは保存されません。

## 戻り値

true if the save operation is successful; false otherwise.

```true```なら保存は成功、```false```ならそれ以外です。

## 説明

Saves the document in its default location. After a successful save operation, the document’s isDirty property is cleared.

デフォルトの場所にドキュメントを保存します。保存が成功した後に、ドキュメントのプロパティをクリアします。
