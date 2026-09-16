# 学習暗記カード PWA版

GitHub Pages にそのまま置けます。

## 主なファイル
- index.html: ホーム
- subjects.json: 科目一覧
- manifest.webmanifest: PWA設定
- service-worker.js: オフライン/キャッシュ
- social/index.html
- kanji/index.html
- english/index.html

## 科目を増やす
1. 新しいフォルダ（例 math）を作る
2. その中に index.html を置く
3. subjects.json に1件追加する

新しい科目ページは一度開くと自動キャッシュされます。

## ホーム画面に追加
- iPhone: Safari → 共有 → ホーム画面に追加
- Android: Chrome → メニュー → ホーム画面に追加 / アプリをインストール
