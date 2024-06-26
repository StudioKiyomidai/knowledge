# お試し

## どんなもんよ

- おぉぉぉー

## ←のsidebarに項目を追加する方法

- `docs/.vitepress/config.mts`に↓のように追加する
- [公式ドキュメント](https://vitepress.dev/reference/default-theme-config#default-theme-config)に色々あるよ

```js
sidebar: [
      {
        text: 'Examples',
        items: [
          { text: 'Markdown Examples', link: '/markdown-examples' },
          { text: 'Runtime API Examples', link: '/api-examples' },
          { text: 'お試し', link: '/test/test' } // ★★★ ここに追加！
        ]
      }
    ],
```