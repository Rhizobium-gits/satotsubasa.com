# Yuko Hirose Portfolio Website

広瀬裕子さんのポートフォリオサイト

## 📁 ファイル構成

```
.
├── index.html          # トップページ
├── book.html           # 書籍一覧
├── architecture.html   # 建築プロジェクト
├── other.html          # その他の活動
├── contact.html        # お問い合わせ
├── style.css           # スタイルシート
└── README.md           # このファイル
```

## 🚀 GitHub Pagesでの公開方法

### 1. リポジトリの作成

1. GitHubにログイン
2. 右上の「+」→「New repository」をクリック
3. リポジトリ名を入力（例：`portfolio`）
4. 「Public」を選択
5. 「Create repository」をクリック

### 2. ファイルのアップロード

#### 方法A：ブラウザから直接アップロード

1. 作成したリポジトリページで「uploading an existing file」をクリック
2. すべてのHTMLファイルとCSSファイルをドラッグ&ドロップ
3. 「Commit changes」をクリック

#### 方法B：Git コマンドを使用

```bash
# ローカルにリポジトリをクローン
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY

# ファイルをコピー
# index.html, book.html, architecture.html, other.html, contact.html, style.css

# Git に追加
git add .
git commit -m "Initial commit: Add portfolio website"
git push origin main
```

### 3. GitHub Pagesの有効化

1. リポジトリページで「Settings」タブをクリック
2. 左サイドバーの「Pages」をクリック
3. 「Source」で「Deploy from a branch」を選択
4. 「Branch」で「main」を選択し、フォルダは「/ (root)」を選択
5. 「Save」をクリック

数分後、以下のURLでサイトが公開されます：
```
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

## 🎨 デザイン仕様

### レスポンシブデザイン

- **モバイル（768px以下）**: 上部横並びナビゲーション
- **タブレット/PC（769px以上）**: 左サイドバーナビゲーション

### カラー

- 背景：`#f8f8f8`
- テキスト：`#333`
- アクセント：`#666`

### フォント

- 游明朝（Yu Mincho）
- ヒラギノ明朝（Hiragino Mincho ProN）
- フォールバック：MS 明朝、serif

## 📝 カスタマイズ方法

### 内容の編集

各HTMLファイルを開いて、テキストを直接編集してください。

### スタイルの変更

`style.css`を編集して、色やフォント、レイアウトを変更できます。

### 画像の追加

1. 画像ファイルをリポジトリにアップロード
2. HTMLファイルで画像のパスを指定：
   ```html
   <img src="your-image.jpg" alt="説明">
   ```

## 🔗 リンク構造

すべてのページは相対パスでリンクされています：

- トップページ：`index.html`
- 書籍：`book.html`
- 建築：`architecture.html`
- その他：`other.html`
- コンタクト：`contact.html`

## ⚡ 技術仕様

- HTML5
- CSS3（Flexbox、メディアクエリ）
- レスポンシブデザイン
- モバイルファースト
- JavaScriptなし（純粋なHTML/CSS）

## 📱 対応ブラウザ

- Chrome（最新版）
- Firefox（最新版）
- Safari（最新版）
- Edge（最新版）
- モバイルブラウザ

## 📄 ライセンス

このテンプレートは自由に使用・カスタマイズできます。
