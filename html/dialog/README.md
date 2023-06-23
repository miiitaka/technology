# Memo

HTMLDialogElement

https://developer.mozilla.org/ja/docs/Web/API/HTMLDialogElement

- HTMLDialogElement.close()
ダイアログを閉じます。任意で引数として文字列を渡すことができ、これがダイアログの returnValue を更新します。

- HTMLDialogElement.show()
ダイアログをモードレスで開きます。すなわち、その間にダイアログの外のコンテンツが操作できます。

- HTMLDialogElement.showModal()
ダイアログをモーダルで、他のダイアログがあればその最も上に表示します。ダイアログの外の操作はブロックされます。

- cancel
ユーザーがエスケープキーで現在開いているダイアログを解除したときに発行されます。

- close
エスケープキー、HTMLDialogElement.close() メソッド、または method="dialog" でダイアログ内のフォームを送信することによって、このダイアログが閉じられたときに発行されます。