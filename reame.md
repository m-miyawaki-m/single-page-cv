
# README - 履歴書プロジェクト

## **概要**
このプロジェクトは、開発者としてのスキル、経験、目標を記載した個人の履歴書です。HTML、CSS、およびPWA対応の要素を組み合わせて、オンラインおよびオフラインで閲覧可能な形で提供しています。また、このプロジェクトは[roadmap.shのSingle Page CVプロジェクト](https://roadmap.sh/projects/single-page-cv)の要件に沿って設計されています。

---

## **構成**
プロジェクトのディレクトリ構造は以下の通りです。

```
プロジェクトフォルダ/
├── assets/
│   ├── css/
│   │   └── style.css               # 履歴書のデザインをカスタマイズするCSS
│   ├── images/
│   │   ├── android-chrome-192x192.png  # アイコン画像（192x192）
│   │   ├── android-chrome-512x512.png  # アイコン画像（512x512）
│   │   ├── apple-touch-icon.png       # Apple用アイコン
│   │   ├── favicon-32x32.png          # Favicon（32x32）
│   │   └── favicon-16x16.png          # Favicon（16x16）
├── site.webmanifest                 # PWAの設定ファイル
├── index.html                       # 履歴書のメインHTMLファイル
```

---

## **主な機能**
### **1. セマンティックHTML**
- 適切なHTMLタグ（`header`, `main`, `section`, `article`）を使用して、ページ構造を整理。
- [roadmap.sh](https://roadmap.sh/projects/single-page-cv)の要件に沿い、セマンティックな構造を満たしています。

### **2. スキルと目標の明示**
- バックエンド、DevOps、API設計、QA、Pythonの各分野に分けてスキルを整理。
- 今後学びたい内容を具体的に記載。

### **3. PWA対応**
- `site.webmanifest` によるPWA設定を実装。
- アイコンとテーマカラーの設定を含み、オフライン対応が可能。

### **4. モバイルおよびデスクトップ対応**
- `style.css` によるレスポンシブデザインで、モバイル・デスクトップ両方で閲覧可能。

---

## **使用方法**
### **ローカルでの確認**
1. 任意のHTTPサーバーを使用してプロジェクトを開きます（例: `Live Server`, `Python SimpleHTTPServer`）。
2. ファイルを配置し、ブラウザで `index.html` を開いて動作を確認します。

### **デプロイ**
このプロジェクトは、以下のようなホスティングサービスを使用して簡単に公開できます。
- **GitHub Pages**
- **Netlify**
- **Vercel**

### **オフラインでの使用**
- `site.webmanifest` によるPWA設定を有効化すると、オフラインでも履歴書を閲覧できます。
- モバイルデバイスで「ホーム画面に追加」を選択することで、ネイティブアプリのように動作します。

---

## **カスタマイズ**
- **デザインの変更**:
  `assets/css/style.css` を編集して、配色やフォントをカスタマイズ可能です。
- **アイコンの変更**:
  `assets/images/` に新しいアイコンを追加し、`site.webmanifest` のアイコン設定を更新します。
- **内容の編集**:
  スキルや目標を更新するには、`index.html` を編集してください。

---

## **今後の改善点**
### **1. 追加機能**
- 他言語対応（日本語・英語）。
- 動的データ表示（JSONを利用）。

### **2. デザインの強化**
- より洗練されたUI/UXの導入。

### **3. PWAの高度化**
- サービスワーカーを追加し、完全オフライン対応を実現。

---

## **roadmap.sh要件との整合性**
このプロジェクトは、[roadmap.shのSingle Page CVプロジェクト](https://roadmap.sh/projects/single-page-cv)の以下の要件を満たしています：
1. **Semantic HTML**: 適切なHTMLタグを用いてページ構造を整理。
2. **SEO Meta Tags**: `description`、`keywords`、`author` タグを含む基本的なSEO設定を実装。
3. **Open Graph (OG) Tags**: ソーシャルメディア共有のためのOGタグを設定。
4. **Favicon**: 複数サイズのFaviconを設定。
5. **Structure readiness for styling**: `style.css` によるスタイリング対応。

---