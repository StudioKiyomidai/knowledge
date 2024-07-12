# 題名

「# + space」でH2にあたる題名が書けます

# 作業手順

* git clone "URL"で最新のリポジトリをクローン
* 作業開始
* pnpm run docs:dev
* ブランチを切ってadd
    * git checkout -b "ブランチ名"
* git add -A
* git commit -m "コメント"
* git push origin "ブランチ名"

# CSSを追加したよ

addCSSブランチでは、カスタムCSS機能を追加しています。<br>
.vitepress配下の「theme」ディレクトリに「custom.css」を追加、ここでCSSを記述できます<br>
マークダウン記法を使いながら、場合によってhtmlタグとclassで囲ってあげれば、対応した文字色などが反映されます

具体的な使い方はtaichan.mdをどうぞ(コード側ね)