# 白石流司 / LIU CHENXI

## 自己紹介

**白石流司（日本での通称） / LIU CHENXI（中国名）**

- **職種：** ITコンサルタント・インフラエンジニア
- **言語：** 日本語・英語・中国語の3言語
- **3つの視点：** 経済・プロダクト、技術、法律
- **仕事・学習のスタイル：** 素早い独学、知識の体系化、構築・検証・改善のフィードバックループ
- **大切にしている考え方：** 車輪の再発明を避け、世界各地のベストプラクティスから学ぶ

## 経歴・年表

### 1999年 — 中国で誕生
- デジタルネイティブ世代として育つ。

### 2011年 — 初めてのパソコン
- 自分専用のパソコンを初めて手に入れる。

### 2018〜2019年 — プログラミングとWebプロダクト業界への関心
- 大学在学中にプログラミングを本格的に学び始める。
- 技術系YouTuberを通じて、SaaSを中心とするWebプロダクト業界への理解を深める。
- インフラストラクチャとソフトウェアエンジニアリングに関心を持つ。

### 2022年 — フリーランス翻訳
- 海外渡航経験がない段階で、日本語から英語への翻訳業務をフリーランスとして開始。
- 後期には医療翻訳を中心に担当。

### 2023年 — 翻訳用語集データベース
- Webスクレイピングによって翻訳用語データを収集。
- 約**8万組の対訳用語**を収録する用語集データベースを構築。

### 2024年 — GMS v1
- 個人SaaS「**Glossary Management System（GMS）**」の開発・運営を開始。
- Webサイト：[sunlightjetrans.com](http://sunlightjetrans.com/)

### 2025年 — ITインフラストラクチャ
- ITインフラ領域を幅広く学習。
- 中国のネットワークエンジニア国家資格を取得。

### 2026年3月 — 初来日
- 初めて日本に渡航。
- 同年春、AKKODiSコンサルティングでインフラエンジニアとしての実務キャリアを開始。

### 2026年7月 — エンタープライズ案件への参画
- それまでに学んだ技術知識を、実際の企業案件へ適用し始める。
- 2案件を並行して担当し、主にネットワークの基本設計資料を作成。

### 2026年8月 — 個人研究の拡大
- 以下の領域を中心に、独立した技術研究を展開：
  - GMS v3・v4・v5・DevOps
  - Site Reliability Engineering（SRE）
  - Platform EngineeringのPoC
  - Harness Engineering・Context Engineering
  - AI支援によるコードのセキュリティ解析・ペネトレーションテスト研究
  - Spec-Driven Development（SDD）、Test-Driven Development（TDD）、Extreme Programming（XP）
  - AIネイティブなインフラ・コーディングのエンドツーエンドワークフロー(AI-DLC, AIUP)

## プロジェクト

### 2023年 — Webスクレイピング
- 翻訳用語データの収集に用いるWebスクレイピング処理を開発。

### 2024年 — GMS v1（Glossary Management System）
- GMSの初期バージョンを公開：[sunlightjetrans.com](http://sunlightjetrans.com/)。
- 現在、公開サービスは**v3.1**に到達。
- 初期機能・構成：
  - 基本的なCRUD機能
  - 管理者・一般ユーザーの権限分離
  - IPv4ネットワーク
  - Amazon RDS
  - Amazon EC2
  - DreamHost

### 2025年 — GMS v2
- 無料利用枠の終了を契機に、インフラ構成を見直し。
- RDS、IPv4関連の費用、不要な構成要素を削減。
- 月額運用コストを約**11ドルから5ドル**へ削減。

### 2026年8月 — GMS v3
- 既存システムを対象とするBrownfield開発を実施。
- 以下の仕組みを追加：
  - PrometheusによるObservability
  - TerraformによるInfrastructure as Code（IaC）
  - CI/CD

### 2026年9月 — Platform EngineeringとAI Pipeline

#### TVP — Thinnest Viable Platform
- **Golden Path**をコンセプトとしたPlatform EngineeringのPoCを構築。

#### AIVP v1 — AI Verified Pipeline
- コード生成とレビューをそれぞれ担当する2つのAI Agentを用いたパイプラインを設計。

### 2026年10月 — AI-Native Software Engineering

#### AIVP v2 — AI Verified Pipeline
- AIによるコーディングプロセスを統制・検証する**Harness Panel**を導入。

#### ANSE Prototype — AI-Native Software Engineering Loop
- 人間の意図からコーディング、検証、CI/CDデプロイまでをつなぐ、エンドツーエンドのエンジニアリングワークフローを研究。

#### SWE-bench実験
- SWE-benchを用い、AIコーディングとHarnessの成果を再現可能なデータで評価。

#### AI-Native Security Research
- DeepSecを活用し、大手テクノロジー企業に関連するOSSから潜在的なセキュリティ問題を抽出・調査。
- Webアプリケーション、MCPツール、CI/CDソフトウェア、機械学習の最適化フレームワークなどを対象に研究。
- 必要な検証を経たFindingについて責任ある開示を予定。静的解析のFindingをそのまま確認済み脆弱性とは扱わない。

#### AI-Native Penetration Testing
- **今後の予定：** DeepSec研究を基盤とするペネトレーションテストの実験を計画。

#### GMS v4 — AI-DLC / AIUPによる開発
- ユーザーが自身のデータとSaaS/API認証情報を持ち込める翻訳ワークフローを設計。
- 機械翻訳とポストエディットの統合に注力。

#### GMS v5 — 開発中
- AI-DLC / AIUPに基づくソフトウェア開発プロセスでGMS v5を開発中。
- GMS v3とv4の構想を統合し、個人用語集の管理と翻訳サービスを提供するシステムを目指す。
