# logictkt.github.io

Rails エンジニア logictkt の自己紹介、今までの経歴、Skills、開発環境、SNS リンクをまとめた、GitHub Pages 用の個人サイトです。
HTML と CSS だけで動作するため、依存パッケージやビルドは不要です。

## 編集

- `index.html`: 表示名、自己紹介文、リンク、ページのタイトル・説明
- `style.css`: 配色、文字、レイアウト。基本の色は先頭の `:root` に定義
- `favicon.ico` / `favicon.png`: 犬の画像から縮小したブラウザのタブ用アイコン（ICO は 16・32・48 px、PNG は 64 px）
- `assets/profile-dog.png`: プロフィールに使用する犬のイラスト（提供画像をそのまま配置）

自己紹介とリンクの編集箇所は、`index.html` のコメントにも記載しています。

## ローカルで確認

このディレクトリで次を実行し、`http://localhost:8000` を開きます。

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

## GitHub Pages で公開

変更を GitHub に push した後、リポジトリの **Settings → Pages** で
**Deploy from a branch** を選択し、ブランチを `main`、フォルダを `/ (root)` に設定します。

公開先は `https://logictkt.github.io/` です。
