# StockSense LP

StockSenseのランディングページです。

## 概要

StockSenseは、日本の個別株の割安銘柄を分析し、中期〜長期投資向けにLINEで通知するサービスです。

## 技術スタック

- [Astro](https://astro.build/) - 静的サイトジェネレーター
- [Cloudflare Pages](https://pages.cloudflare.com/) - ホスティング

## 開発

```bash
# 依存関係のインストール
pnpm install

# 開発サーバー起動（localhost:4321）
pnpm dev

# ビルド
pnpm build

# ビルド結果のプレビュー
pnpm preview
```

## デプロイ

mainブランチにpushすると、Cloudflare Pagesで自動デプロイされます。
