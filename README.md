# vitePress-v2

## Overview

VitePress V2を使用したドキュメントサイトのプロジェクトです。VitePressは、Viteを利用した高速な静的サイトジェネレーターで、マークダウンベースのドキュメント作成に最適化されています。

## Tech Stack

- **VitePress** v1.6.3 - 静的サイトジェネレーター
- **Vue 3** - UIフレームワーク
- **TypeScript** - 型安全な開発環境
- **Node.js** - JavaScript実行環境

## Setup

プロジェクトのセットアップ手順:

```bash
# 依存関係のインストール
npm install
```

## Usage

開発用の各種コマンド:

```bash
# 開発サーバーの起動 (http://localhost:5173)
npm run docs:dev

# 本番用ビルド
npm run docs:build

# ビルドしたサイトのプレビュー
npm run docs:preview
```

## Directory Structure

```
.
├── docs/                  # ドキュメントソースファイル
│   ├── .vitepress/       # VitePress設定ディレクトリ
│   │   ├── config.mts    # サイト設定ファイル
│   │   ├── cache/        # ビルドキャッシュ
│   │   └── dist/         # ビルド出力ディレクトリ
│   ├── index.md          # ホームページ
│   ├── markdown-examples.md
│   └── api-examples.md
├── package.json          # プロジェクト設定
└── README.md            # このファイル
```

## License

This repository is for personal/private use only.
