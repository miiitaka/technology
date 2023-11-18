# Memo

MutationObserver<br>
https://developer.mozilla.org/ja/docs/Web/API/MutationObserver


## Point

値のセット時にプロパティに直接値をセットすると動作しない。

```
// 動作OK
HTMLElement.setAttribute('value', formatMonth());
```

```
// 動作しないパターン
HTMLElement.value = formatMonth();
```