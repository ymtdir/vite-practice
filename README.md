# vite-practice

React + TypeScript + Vite を使った学習用リポジトリです。  
モダンなフロントエンド開発の基本的な構成や機能を実際に手を動かしながら学ぶことを目的としています。

## 技術スタック

- **フレームワーク**: React 19 + TypeScript
- **ビルドツール**: Vite 7
- **スタイリング**: Tailwind CSS 4
- **UIコンポーネント**: shadcn/ui (Radix UI)
- **ルーティング**: React Router v7
- **アイコン**: Lucide React
- **リンター**: ESLint

## 実装済みの機能

- サインイン・サインアップフォーム
- 認証（ログイン / ログアウト / ルート保護）
- 認証後の自動遷移
- ダッシュボード（サイドバー付き）
- ユーザー管理

## プロジェクト構成

```
src/
├── components/     # UIコンポーネント
│   └── ui/         # shadcn/ui ベースコンポーネント
├── hooks/          # カスタムフック (useAuth, useMobile)
├── lib/            # ユーティリティ関数
├── routes/         # ルート定義
└── utils/          # 認証ローダーなど
```

## セットアップ

```bash
npm install
npm run dev
```

## スクリプト

| コマンド | 説明 |
| --- | --- |
| `npm run dev` | 開発サーバーの起動 |
| `npm run build` | プロダクションビルド |
| `npm run lint` | ESLint によるコードチェック |
| `npm run preview` | ビルド結果のプレビュー |
