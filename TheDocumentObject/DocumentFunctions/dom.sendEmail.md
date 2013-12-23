# dom.sendEmail()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b39.html)

## バージョン

MX 2004

## 書式

dom.sendEmail(fileAttachment)

## 引数

### fileAttachment

A string, which is expressed as file://URL, denoting the location of a file to send by e-mail.

Eメールで送信する、file://URLで表現されるファイルの場所を示すString型。

## 戻り値

なし

## 説明

Creates a new e-mail with the specified file as an attachment.

新しいEメールを指定されたファイルを添付して作成します。

## サンプル

The following example opens a new e-mail in the default e-mail program and attaches the file foo.png to the message:

次のコマンドを実行すると、既定のメーラーで新しいEメールを作成し、メッセージにfoo.pngファイルを添付します。

```
fw.getDocumentDOM().sendEmail("file:///Users/andy/Documents/foo.png");
```