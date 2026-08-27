# 921-Live_Scribe_TV: 板書・意見整理 AI (Live Scribe TV)

## 概要
リアルタイム P2P 通信（PeerJS）と Gemini API を活用した、ワークショップや研修・会議向けの板書・意見整理・グループワーク支援 Web アプリケーション。

## 基本情報
- **バージョン**: v1.36.0
- **公開形式**: GitHub Pages / Public
- **主要機能**:
  - 参加者からのスマホリアルタイム付箋投稿（PeerJS によるサーバーレスP2P同期）
  - メインスクリーン（TV/プロジェクター）向けの板書ボード表示
  - Gemini API による付箋意見の自動分類・要約・レポート生成
  - いいね投票・カテゴリ別カード色分け・アーカイブ保存

## システム構成 (依存関係)

| サービス種別 | 連携システム名 | 開発/設定URL(コード等) | 本番/公開URL(WebApp等) | データ保存先(スプシ等) | 役割・用途 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **その他** | Live Scribe TV | [コードを開く 🔗](https://github.com/fujishinoharatt-cpu/921-Live_Scribe_TV) | [GitHub Pages 公開URL](https://fujishinoharatt-cpu.github.io/921-Live_Scribe_TV/) | LocalStorage / P2P | リアルタイム板書・意見整理 AI 画面を配信（React + PeerJS + Gemini API） |
