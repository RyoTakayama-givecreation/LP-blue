# GiveCareer 現場職LP

GitHub Pagesなどの静的ホスティングで公開できる、単一ページ構成のランディングページです。

## 構成

- `index.html` — LP本体（CSS・JavaScriptを内包）
- `assets/images/` — LP内で使用する画像

## ローカル確認

```bash
python3 -m http.server 8000
```

起動後、`http://localhost:8000/` を開いて確認します。

## 公開前の注意

- 現在の相談フォームはデモ表示で、入力内容の送信・保存は行いません。
- 実績数値やNo.1表記、画像の利用権、プライバシーポリシーを公開前に確認してください。
