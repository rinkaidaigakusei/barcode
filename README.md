# 食材バーコード

スマホのブラウザで食材のJANコードを読み取り、AIに送る買い物テキストを作るWebアプリ。

- 読み取り：html5-qrcode 2.3.8（EAN-13 / EAN-8）
- 商品検索：Open Food Facts → （任意）楽天市場 商品検索API
- 保存：localStorage（買い物リスト・商品履歴・設定）

## ファイル
- `index.html` … アプリ本体（これ1つで動く）
- `manifest.json`, `icon-180.png`, `icon-512.png` … ホーム画面に追加したとき用

## 公開（GitHub Pages）
1. GitHub で Public リポジトリ `food-barcode` を作る
2. このフォルダの4ファイルをアップロード
3. Settings → Pages → Branch: `main` / `(root)` → Save
4. `https://<ユーザー名>.github.io/food-barcode/` を開く

## 楽天API（任意）
- https://webservice.rakuten.co.jp/ でアプリ登録 → アプリIDとアクセスキーを取得
- 許可するWebサイトに `https://<ユーザー名>.github.io` を登録
- アプリ下部の「設定」に入力して保存
