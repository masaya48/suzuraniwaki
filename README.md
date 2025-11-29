# すずらん整体院いわき - ランディングページ

すずらん整体院いわきの公式ランディングページです。Astroで構築されています。

## プロジェクト構成

```text
/
├── public/               # 静的ファイル（画像、favicon等）
├── src/
│   ├── assets/          # SVGなどのアセット
│   ├── components/      # 再利用可能なコンポーネント
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── RecommendedTreatments.astro
│   │   ├── Concerns.astro
│   │   ├── Trust.astro
│   │   ├── DRTAbout.astro
│   │   ├── MaternityMenu.astro
│   │   ├── Reasons.astro
│   │   ├── DirectorTestimonials.astro
│   │   ├── Access.astro
│   │   └── Footer.astro
│   ├── layouts/         # ページレイアウト
│   │   └── Layout.astro
│   └── pages/           # ページファイル
│       ├── index.astro  # トップページ
│       ├── first.astro  # 初めての方
│       ├── menu.astro   # メニュー
│       ├── access.astro # アクセス
│       └── price.astro  # 料金
└── package.json
```

## コマンド

プロジェクトのルートディレクトリで以下のコマンドを実行してください：

| コマンド | 説明 |
| :--- | :--- |
| `pnpm install` | 依存関係のインストール |
| `pnpm dev` | 開発サーバーを起動（`localhost:4321`） |
| `pnpm build` | 本番用サイトを `./dist/` にビルド |
| `pnpm preview` | ビルドしたサイトをローカルでプレビュー |

## 技術スタック

- Astro 5.16.2
- TypeScript
- コンポーネントベースの構成

## 開発の開始

1. 依存関係をインストール
   ```sh
   pnpm install
   ```

2. 開発サーバーを起動
   ```sh
   pnpm dev
   ```

3. ブラウザで `http://localhost:4321` にアクセス
