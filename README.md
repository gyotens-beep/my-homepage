# my-homepage

シンプルな静的ホームページです。HTML と CSS だけで作られているので、ビルド不要でそのまま公開できます。

## ファイル構成

- `index.html` — ページ本体（自己紹介・作品・お問い合わせのセクション）
- `style.css` — スタイル（ライト/ダークモード対応、レスポンシブ）

## カスタマイズ方法

1. `index.html` を開き、「ここに〜を書きます」となっているプレースホルダーの文章を自分の内容に書き換える
2. お問い合わせセクションのメールアドレス（`example@example.com`）を自分のものに変更する
3. 色を変えたい場合は `style.css` の先頭にある `:root` の変数（`--accent` など）を編集する

## 公開方法（GitHub Pages）

1. GitHub のリポジトリページで **Settings → Pages** を開く
2. Source を「Deploy from a branch」にして、ブランチ（例: `main`）と `/ (root)` を選択して保存
3. 数分後に `https://<ユーザー名>.github.io/my-homepage/` で公開されます
