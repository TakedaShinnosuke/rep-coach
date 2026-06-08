# rep-coach

筋トレ記録 + AI セット提案アプリの個人学習プロジェクト。
**現在は開発を停止しています**(下記「ステータス」参照)。

## ステータス

- 状態: ⏸️ Paused / Archived
- 停止理由: 共同開発の新プロジェクト `move-mate` (健康維持アプリ) への移行
- 移行先: [move-mate](https://github.com/TakedaShinnosuke/move-mate) ※リポジトリ作成後に URL を更新
- 達成済み: 開発環境構築 (WSL2 + Node.js + Claude Code + Git/GitHub + Docker)、Next.js 15 プロジェクトの初期化、GitHub 連携

## 当初の構想

| 項目 | 内容 |
|---|---|
| ジャンル | 筋トレ記録 + AI 提案 |
| 想定スタック | Next.js 15 (App Router) + TypeScript + Tailwind CSS + Prisma + PostgreSQL (Docker) + Anthropic Claude API |
| 差別化軸 | 過去履歴をもとに Claude API が次回のセット (重量・回数) を提案する機能 |
| デプロイ | Vercel + Supabase (予定だった) |

## 学んだこと

- WSL2 上での Node.js / npm の運用
- Next.js プロジェクトの初期化 (`create-next-app`、App Router、Turbopack、AGENTS.md)
- Git/GitHub の SSH 鍵設定、リモート連携
- Docker による PostgreSQL コンテナ運用の準備
- `.env` / `.gitignore` の使い分けによるシークレット管理

## ライセンス

未設定 (個人学習用)。