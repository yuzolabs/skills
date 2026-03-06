# skills

[English README](README.md)

このリポジトリは yuzolabs の個人的な Agent Skills の保管場所です。

## Agent Skills

このリポジトリには以下の Agent Skills が含まれています。

### fetch-github-copilot-reviews

GitHub Copilot が生成した Pull Request レビューを取得するスキルです。
GitHub Copilotによるレビューは通常の`gh pr`コマンドでは取得できないため、内部的にGitHub APIを直接呼び出してレビューを取得します。

**主な機能：**

- PR 番号またはフル URL をサポート
- Copilot によるレビューのフィルタリング（Bot 検出パターンを使用）
- レビュー本文とインラインコメントの取得
- 構造化された JSON 出力

### markdown-format

markdownlint-cli2と textlint を繰り返し実行して、Markdown ファイルをフォーマットするスキルです。

**主な機能：**

- Markdown 構文エラーの自動修正
- 日本語スタイルの校正
- 手動修正が必要な問題の特定
