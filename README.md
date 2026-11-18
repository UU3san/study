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


## 追加内容（2026-11-18）
- 中3英単語に「高校入試・重要動詞」198項目を追加。4範囲に分割。
- 添付画像の表は22行×9列=198枠で、startが2回あるため197種類。画像どおり198項目を登録。
- 日本語訳は画像にはなく、学習用に新たに付けています。
- 中3の範囲選択・定期テスト範囲複数選択・PDF一覧・暗記カードの両方向で使用可能。
- 元の英単語・音楽・社会・漢字・音読は保持。
