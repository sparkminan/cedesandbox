# Quick Deck (クイックデッキ) - v1 Prototype

AIアシスト機能付きの簡易プレゼンテーション作成ツール

## 🎯 概要

Quick Deckは、会議のアジェンダやプレゼンテーションを素早く作成できるWebアプリケーションです。

### 主な機能

- **AIアジェンダ生成モード**: 会議のテーマ、ゴール、トピックを入力するだけで、構造化されたアジェンダを自動生成
- **マニュアル編集モード**: Markdownでスライドを直接編集し、リアルタイムプレビュー
- **reveal.js統合**: キーボード操作でスライドをナビゲーション
- **日本語UI**: すべてのインターフェースが日本語

## 📱 デモ

### GitHub Pages でアクセス

以下の手順でGitHub Pagesを設定してください:

1. リポジトリの「Settings」→「Pages」を開く
2. Source: ブランチ `claude/quick-deck-v1-prototype-011CUKLPZfdDNwLbY58VKkHR` を選択
3. Folder: `/ (root)` または `/docs` を選択
4. 「Save」をクリック

設定後、以下のURLでアクセス可能になります:
```
https://sparkminan.github.io/cedesandbox/
```

詳しい手順は [GITHUB_PAGES_SETUP.md](./GITHUB_PAGES_SETUP.md) を参照してください。

### ローカルで実行

```bash
# HTTPサーバーを起動
python3 -m http.server 8080

# ブラウザで開く
open http://localhost:8080/index.html
```

## 🚀 使い方

### AIモード
1. 「AIアジェンダ生成」タブを開く
2. 会議のテーマ、ゴール、トピックを入力
3. 「AIにアジェンダを作成させる」をクリック
4. 自動生成されたスライドがエディターに表示されます

### マニュアルモード
1. 「マニュアル編集」タブを開く
2. 左側のエディターでMarkdownを編集
3. 右側のプレビューでリアルタイム確認
4. 矢印キー（← →）でスライド移動

## 📝 Markdown記法

```markdown
# スライドタイトル

## セクション見出し

- 箇条書き項目1
- 箇条書き項目2

---

## 次のスライド
- `---` で新しいスライドを作成
```

## 🛠 技術スタック

- **reveal.js** 4.5.0 - スライド表示
- **Pure JavaScript** - フレームワーク不要
- **Single HTML File** - 依存関係なしの単一ファイル

## 📄 ライセンス

Created with CodeSandbox

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
