# GitHub Pages セットアップ手順

Quick DeckをGitHub Pagesで公開する方法

## 📱 iPhoneで開けるURLを取得する手順

### ステップ 1: GitHub Pagesを有効にする

1. GitHubのリポジトリページにアクセス:
   ```
   https://github.com/sparkminan/cedesandbox
   ```

2. 「Settings」タブをクリック

3. 左サイドバーの「Pages」をクリック

4. 「Source」セクションで以下を設定:
   - **Branch**: `claude/quick-deck-v1-prototype-011CUKLPZfdDNwLbY58VKkHR` を選択
   - **Folder**: `/ (root)` を選択

5. 「Save」ボタンをクリック

### ステップ 2: URLを確認

設定後、数分待つと以下のようなURLが表示されます:

```
https://sparkminan.github.io/cedesandbox/
```

このURLをiPhoneのSafariで開けば、Quick Deckが表示されます！

---

## 🔧 別の方法: docs フォルダを使う

もし上記の方法がうまくいかない場合、以下の手順を試してください:

### 1. docs フォルダを作成（こちらで実行済み）

```bash
mkdir docs
cp index.html docs/
git add docs/
git commit -m "Add docs folder for GitHub Pages"
git push
```

### 2. GitHub Settings で設定

- **Branch**: 現在のブランチを選択
- **Folder**: `/docs` を選択

---

## ⚡ 即座にアクセスしたい場合

以下のサービスにindex.htmlをアップロードすれば、すぐに公開できます:

### CodePen (推奨)
1. https://codepen.io/pen/ にアクセス
2. HTMLタブに `index.html` の内容を貼り付け
3. 「Save」をクリックして共有可能なURLを取得

### JSFiddle
1. https://jsfiddle.net/ にアクセス
2. HTMLパネルに貼り付け
3. 「Save」で公開

### その他のオプション
- **Netlify Drop**: https://app.netlify.com/drop にindex.htmlをドラッグ&ドロップ
- **GitHub Gist**: https://gist.github.com/ でHTMLファイルを作成（即座に公開）

---

## 📞 サポート

問題が発生した場合は、以下を確認してください:

- リポジトリが公開（Public）になっているか
- ブランチが正しくプッシュされているか
- GitHub Pagesの設定が保存されているか

設定完了後、iPhoneのSafariでURLを開いてQuick Deck をお楽しみください！
