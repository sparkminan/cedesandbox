# 📱 Quick Deck - すぐにアクセスできるリンク集

GitHub Pagesが見れない場合の代替アクセス方法をまとめました。

## 🚀 即座にアクセスできる方法（推奨）

### 方法1: HTMLPreview.github.io 経由（最も簡単）

以下のURLをiPhoneのSafariで開いてください：

```
https://htmlpreview.github.io/?https://raw.githubusercontent.com/sparkminan/cedesandbox/claude/quick-deck-v1-prototype-011CUKLPZfdDNwLbY58VKkHR/index.html
```

または、docsフォルダ版：

```
https://htmlpreview.github.io/?https://raw.githubusercontent.com/sparkminan/cedesandbox/claude/quick-deck-v1-prototype-011CUKLPZfdDNwLbY58VKkHR/docs/index.html
```

### 方法2: GitHub Raw URL（直接アクセス）

```
https://raw.githubusercontent.com/sparkminan/cedesandbox/claude/quick-deck-v1-prototype-011CUKLPZfdDNwLbY58VKkHR/docs/index.html
```

※ただし、reveal.jsのCDNが読み込めない可能性があります

### 方法3: ローカルサーバー（同じWi-Fi内のみ）

```
http://21.0.0.100:8080/index.html
```

※ iPhoneとコンピューターが同じWi-Fiネットワークに接続している必要があります

---

## 🔧 GitHub Pagesが見れない理由

### 考えられる原因

1. **リポジトリがPrivateになっている**
   - 解決: Settings → General → Change repository visibility → Public

2. **GitHub Pagesの設定がされていない**
   - 解決: Settings → Pages → Source設定

3. **ブランチ名が長すぎる**
   - 現在のブランチ: `claude/quick-deck-v1-prototype-011CUKLPZfdDNwLbY58VKkHR`
   - 解決: メインブランチにマージするか、短いブランチ名を使用

---

## ✅ GitHub Pages 正しい設定方法

1. リポジトリページ: https://github.com/sparkminan/cedesandbox
2. Settings → Pages
3. 以下のように設定:
   - **Source**: Deploy from a branch
   - **Branch**: `claude/quick-deck-v1-prototype-011CUKLPZfdDNwLbY58VKkHR`
   - **Folder**: `/docs`
   - **Save** をクリック

4. 数分待つ

5. 以下のURLでアクセス可能になります:
   ```
   https://sparkminan.github.io/cedesandbox/
   ```

---

## 📝 オンラインエディタで開く

### CodePen
1. https://codepen.io/pen/ にアクセス
2. HTML タブに `index.html` の内容を貼り付け

### JSFiddle
1. https://jsfiddle.net/ にアクセス
2. HTML パネルに貼り付け

---

## 🎯 最も確実な方法

**HTMLPreview.github.io** のリンクを使用してください。これは設定不要で、すぐにアクセスできます。

iPhoneで以下のURLを開いてください：

```
https://htmlpreview.github.io/?https://raw.githubusercontent.com/sparkminan/cedesandbox/claude/quick-deck-v1-prototype-011CUKLPZfdDNwLbY58VKkHR/docs/index.html
```

これで Quick Deck がすぐに表示されるはずです！
