# 🚀 クイックスタートガイド

## 最も簡単な方法（GitHubのウェブインターフェースを使用）

### ステップ1: GitHubリポジトリの作成

1. [GitHub](https://github.com)にログイン
2. 右上の「+」→「New repository」をクリック
3. リポジトリ名を入力（例：`my-portfolio`）
4. 「Public」を選択
5. 「Add a README file」のチェックは**外す**
6. 「Create repository」をクリック

### ステップ2: ファイルのアップロード

1. 新しく作成したリポジトリページで「uploading an existing file」をクリック
2. 以下のファイルをすべてドラッグ&ドロップ：
   - ✅ index.html
   - ✅ book.html
   - ✅ architecture.html
   - ✅ other.html
   - ✅ contact.html
   - ✅ style.css
   - ✅ README.md
   - ✅ .gitignore
3. 下部のコミットメッセージに「Initial commit」と入力
4. 「Commit changes」をクリック

### ステップ3: GitHub Pagesの有効化

1. リポジトリページで「Settings」タブをクリック
2. 左サイドバーの「Pages」をクリック
3. 「Source」セクションで：
   - Branch: **main** を選択
   - Folder: **/ (root)** を選択
4. 「Save」をクリック

### ステップ4: サイトの確認

数分後（通常1-5分）、以下のURLでサイトが公開されます：

```
https://あなたのユーザー名.github.io/リポジトリ名/
```

例：`https://yamada-taro.github.io/my-portfolio/`

---

## 📝 内容の更新方法

### 方法1: GitHubのウェブインターフェース

1. リポジトリページで更新したいファイル（例：`index.html`）をクリック
2. 右上の鉛筆アイコン（Edit this file）をクリック
3. 内容を編集
4. 下部の「Commit changes」をクリック
5. 数分後、サイトに反映されます

### 方法2: 新しいファイルをアップロード（上書き）

1. リポジトリページで「Add file」→「Upload files」をクリック
2. 更新したファイルをドラッグ&ドロップ
3. 「Commit changes」をクリック

---

## 🎨 カスタマイズのヒント

### テキストの変更

各HTMLファイルを開いて、以下の部分を編集：

```html
<h1>広瀬裕子</h1>  <!-- あなたの名前に変更 -->
<div class="profile-line">- エッセイスト</div>  <!-- あなたの職業に変更 -->
```

### 色の変更

`style.css`を開いて、以下の色を変更：

```css
background-color: #f8f8f8;  /* 背景色 */
color: #333;                 /* テキスト色 */
```

---

## ❓ よくある質問

### Q: サイトが表示されない
A: 以下を確認してください：
- GitHub Pagesが有効になっているか
- ファイル名が正確か（大文字小文字も区別されます）
- 5分ほど待ってから再度確認

### Q: スマホでも見られる？
A: はい！レスポンシブデザインなので、すべてのデバイスで快適に閲覧できます。

### Q: 独自ドメインを使いたい
A: GitHub Pagesの設定で「Custom domain」を設定できます。

### Q: 無料？
A: はい、GitHub Pagesは完全無料です！

---

## 📞 サポート

問題が発生した場合：
1. [GitHub Pages Documentation](https://docs.github.com/ja/pages)を参照
2. GitHubのヘルプコミュニティで質問

---

**🎉 おめでとうございます！あなたのポートフォリオサイトが完成しました！**
