# スライド置き場

GitHub Pagesで公開するスライド置き場です。

## セットアップ

```bash
# 依存関係のインストール
npm install
```

## 使い方

### ローカルでプレビュー

```bash
# スライドサーバーを起動（http://localhost:8080）
npm run serve
```

### ビルド

```bash
# distフォルダにHTMLを生成
npm run build
```

### 開発モード

```bash
# ファイル変更を監視して自動ビルド
npm run watch
```

## 構成

- `slides/` - Markdownスライドファイル
- `dist/` - ビルド出力（gitignore）
- `.github/workflows/deploy.yml` - GitHub Actions設定