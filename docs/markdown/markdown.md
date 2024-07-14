# Markdown記法一覧

::: info
表に記載のある「実装方法」ですが、反映には半角スペースが必要です。
:::

| やりたいこと | 実装方法 | 備考 |
| ------- | -------- | --------|
| 見出しh1 | # |  |
| 見出しh2 | ## | 最大で見出し6までいけるっぽい |
| 引用 | > | 入れ子は >> |
| リスト | * | Tab + * で入れ子 |
| Decimalリスト | 1. | Tab使えるよ |  
| checkboxリスト | [ ] [x] | |
| 水平線 | --- | ハイフン、アスタリスクを記述することで出力 |
| リンク | <リンク> | リンクにはURLを記載 |
| インラインリンク | [タイトル] + (リンク "タイトルがつくよ") | 「+」は無視してね |
| 強調 | ** + つよいことば + ** | 「+」は無視してね。アスタは1～3まで |
| 画像 | ! + [ダミー画像] + (URL) | 「+」は無視してね。150pxの設定例→ https://via.placeholder.com/150
| 打ち消し | ~~ + 打ち消したい内容 + ~~ | 「+」は無視してね |
| インライン表示 | 「`」で囲む | Shift + @ |
| シンタックスハイライト | 「```」で、(言語 + :タイトル)を囲む | +は無視してね |

<br>

### その他 vitepress独自記法
<br>

```
::: info
This is an info box.
:::

```

::: info
This is an info box.
:::

```
::: tip
This is a tip.
:::
```

::: tip
This is a tip.
:::

```
::: warning
This is a warning.
:::
```

::: warning
This is a warning.
:::

```
::: danger
This is a dangerous warning.
:::
```

::: danger
This is a dangerous warning.
:::

```
::: details
This is a details block.
:::
```

::: details
This is a details block.
:::