# MkDocs Playground

GitHub Actionsを使用したPRプレビュー環境のデモリポジトリです。

## 機能

- PRごとのプレビュー環境の自動生成
- PRクローズ時のプレビュー環境の自動削除
- メインサイトの自動デプロイ

## URL構造

- メインサイト: `https://take4mats.github.io/mkdocs-playground/main/`
- プレビューサイト: `https://take4mats.github.io/mkdocs-playground/preview/{PR番号}/`

## 使用方法

1. 新しいブランチを作成し、変更をpush
2. PRを作成すると、自動的にプレビューサイトが生成され、PRにコメントでURLが通知される
3. PRがクローズされると、対応するプレビューサイトは自動的に削除される
