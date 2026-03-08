# hotline_site

Web公開（GitHub Pages想定）用リポジトリ。

## 目的
- サイト用コードと公開コンテンツを分離して管理する
- `docs/` を公開先として扱える構成にする

## ディレクトリ構成
```text
hotline_site/
├── public/
│   ├── images/
│   ├── icons/
│   └── files/
├── src/
│   ├── pages/
│   ├── components/
│   ├── styles/
│   └── data/
├── content/
│   ├── stories/
│   └── papers/
└── docs/
```

## 運用ルール
- `src/`: 画面コード
- `public/`: 静的アセット（画像・配布ファイル）
- `content/`: 原稿データ（記事・論文など）
- `docs/`: 公開出力（GitHub Pages運用時）

## ライセンス
- 詳細は `LICENSE.md` を参照
