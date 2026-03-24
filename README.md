# 自己紹介

名前は高橋将希です。1995年生まれ、現在は神奈川県在住です。

# 経歴の概要

- 2017年に大学を卒業後、ウェブアプリケーション開発を中心にシステムエンジニアとして業務に従事
- 主に PHP ( Laravel ) を用いたバックエンド開発と、 TypeScript ( Next.js / Nuxt.js 等) を用いたフロントエンド・バックエンド開発に従事
- 割合はバックエンドが7割、フロントエンドが3割程度。フロントエンドはロジック処理は実装可能。 HTML ・ CSS に苦手意識があるが、最近は AI に頼りに実装
- 業務システムやウェブアプリケーションの開発において、設計から実装、リリースまで一通り担当
- 他に開発環境では Docker 、デプロイには GitHub Actions を利用した経験あり

# スキル

## 言語とフレームワーク

- PHP (6年)
    - Laravel (6年)
        - View を利用した画面表示、 API 、バッチ、 Unit テストなどの一通りの実装が可能
- JavaScript / TypeScript (8年)
    - React / Next.js (5年)
        - フロントのみ実装経験あり
    - Vue.js / Nuxt.js (5年)
        - フロント/バックエンドの実装
    - jQuery (3年)
- Ruby (1年未満)
    - Ruby on Rails (1年未満)

## AI

- ChatGPT
- Gemini
- Claude
- Codex
    - Visual Studio Code の拡張機能を活用し AI エディタ的に利用
    - 無料の範囲でも十分使えて便利
- Cursor
    - 行を指定してスレッドに依頼ができるのが Codex に比べて便利

## その他（インフラ・ツール）

- Git / GitHub (9年)
    - チーム開発での運用経験あり。その他 Revert 、 Rebase などの特殊な操作も可能
- Linux (9年)
    - 調査しながら基本的なサーバー操作は可能
- Docker (8年)
    - アプリケーションコンテナ、 DB コンテナを作成してローカル開発環境/ AWS ECS にて利用経験あり
- AWS (1年)
    - 0から立ち上げた経験はないが立ち上がっている ECS / EC2 / S3 に対してシステム連携/デプロイ等をした経験あり
- Notion
    - ページの作成からデータベースの活用、同期ブロックの活用などを利用した管理業務を一通り実行することが可能

# 直近の主要プロジェクト

## 転職エージェントサービスの運用

期間: 2024/12〜2026/03（1年4ヶ月）

### プロジェクト概要

転職者が会員登録をし、 Salesforce に登録・ Slack に通知するのが主な機能のウェブアプリケーション。
オペレータは、登録された転職者に対して求人を推薦し、面談等は Salesforce 上で対応していた。

### 業務内容

- 既存のウェブシステムを引き継ぎ改修・保守運用を担当
- 既存の仕組みを理解した上で新しい仕組みに切り替え、新規機能の実装等を実施し、安定した保守運用に貢献

### 利用技術

- インフラ
    - AWS ECS・S3 / Docker / MySQL / Linux / Terraform
- アプリケーション
    - TypeScript / Nuxt.js
- その他
    - GitHub / GitHub Actions
    - Salesforce
    - Slack 連携
    - Google Sheets 連携
    - immedio
    - Sentry

### チーム規模

マネージャー1名 / 開発2名(計3名)

## 転職サービスの運用

期間: 2024/12〜2025/08（9ヶ月）

### プロジェクト概要

転職者が求人に対して応募出来、企業側と面談などが行える。かつスカウト機能などが搭載された転職サービス

### 業務内容

- 既存のウェブアプリケーションを引き継ぎ改修・保守運用
- オペレータからの問い合わせ対応
- 複雑な外部連携を含む既存システムにおいて、影響範囲を考慮した改修を継続的に実施し、安定運用に貢献

### 利用技術

- インフラ
    - AWS ECS・S3
    - Docker
    - MySQL
    - Linux
    - Terraform
- アプリケーション
    - Ruby / Ruby on Rails
    - TypeScript / Next.js
- その他
    - GitHub / GitHub Actions
    - Sentry
    - JIRA

### チーム規模

マネージャー1名 / 開発2名(計3名)

## 電子お薬手帳

期間: 2021/07〜2024/08（3年2ヶ月）

### プロジェクト概要

医療 DX 領域における PHR (パーソナルヘルスレコード) アプリの新規開発プロジェクト。

主にアプリでは WebView を活用し、スマートフォン側の機能・情報取得には ネイティブブリッジ を活用。

お薬手帳、バイタルデータ管理、処方箋連携などを備えた多機能サービスにおいて、新規開発から運用・保守まで一貫して担当。

### 業務内容

- 処方箋送信機能を中心に多くのシステムでバックエンド機能・フロントを実装
- Firebase Cloud Messaging を利用したスマートフォンアプリ / PWA への通知を実装
- GitHub Actionを新規構築し、デプロイ作業の自動化を実現。開発効率およびリリースの安定性向上に貢献

### 利用技術

- インフラ
    - AWS ECS・S3
    - Linux
    - MySQL
    - Docker
    - Firebase Cloud Messaging
- アプリケーション
    - PHP / Laravel
    - TypeScript / Next.js
- その他
    - GitHub / GitHub Actions
    - Swagger
    - Backlog

### チーム規模

マネージャー3名 / 開発7名 / その他7名(計13名)

## 工作機営業ツール

期間: 2018/07〜2021/06（3年）

### 業務内容

工作機の営業をするためのウェブアプリケーションの新規開発プロジェクト。新規開発後は機能追加や保守等を実施。

顧客と直接コミュニケーションを取りながら要件整理・機能開発を推進し、業務要件をシステムへ適切に落とし込み実装。ドメイン理解を重視した開発を通じて、複雑な業務ロジックの設計・実装スキルを向上。

長期的なプロジェクト運用を通じて信頼関係を構築し、追加案件の獲得に貢献。

### 利用技術

- インフラ
    - AWS EC2
    - Linux
    - Docker
- アプリケーション
    - PHP / Laravel
    - JavaScript / Vue.js
- その他
    - GitHub
    - Swagger
    - Backlog

### チーム規模

営業2名 / 開発2名(計4名)

# すべての職務経歴(上記の「直近の主要プロジェクト」を含む)

**転職エージェントサービスの運用**
期間: 2024/12〜2026/03（1年4ヶ月）
概要: 転職者の会員登録・Salesforce連携・Slack通知機能を備えたウェブサービスの改修・保守運用
技術: AWS ECS・S3 / Docker / MySQL / Linux / Terraform / TypeScript / Nuxt.js / GitHub / GitHub Actions / Salesforce / Slack / Google Sheets / immedio / Sentry

**転職サービスの運用**
期間: 2024/12〜2025/08（9ヶ月）
概要: 求人応募・企業面談・スカウト機能を備えた転職ウェブアプリケーションの改修・保守運用
技術: AWS ECS・S3 / Docker / MySQL / Linux / Terraform / Ruby / Ruby on Rails / TypeScript / Next.js / GitHub / GitHub Actions / Sentry / JIRA

**企業向けバックオフィスツール開発**
期間: 2024/09〜2024/11（3ヶ月）
概要: 企業向けバックオフィスツール開発
技術: Heroku / Ruby / Ruby on Rails / TypeScript / Next.js / GitHub / GitHub Actions

**電子お薬手帳**
期間: 2021/07〜2024/08（3年2ヶ月）
概要: 医療DX領域のPHR(パーソナルヘルスレコード)アプリ。お薬手帳・バイタルデータ管理・処方箋連携機能の新規開発から運用・保守まで一貫して担当
技術: AWS ECS・S3 / Linux / MySQL / Docker / Firebase Cloud Messaging / PHP / Laravel / TypeScript / Next.js / GitHub / GitHub Actions / Swagger / Backlog

**工場のマシン稼働状況管理ウェブアプリケーション**
期間: 2020/05〜2020/11（7ヶ月）
概要: 工場のマシン稼働状況を可視化するWebアプリケーション開発
技術: Linux / MySQL / Docker / nginx / PHP / JavaScript / Laravel

**公園の案内スマートフォンアプリ**
期間: 2020/03〜2020/07（5ヶ月）
概要: iOS / Android対応の公園案内用スマートフォンアプリ開発
技術: Android Studio / Xcode / JavaScript / React Native

**ガスの依頼会社・卸先業者コミュニケーションWebアプリ**
期間: 2018/12〜2019/03（4ヶ月）
概要: 取引先間のコミュニケーションWebアプリ開発
技術: Linux / MySQL / Docker / PHP / Laravel / JavaScript 

**工作機営業ツール**
期間: 2018/07〜2021/06（3年）
概要: 工作機営業用ウェブアプリケーションの新規開発・機能追加・保守。3年の長期プロジェクト
技術: AWS EC2 / S3 / Linux / Docker / PHP / Laravel / JavaScript / Vue.js / GitHub / Swagger / Backlog

**案件管理システムの改修**
期間: 2018/05〜2018/06（2ヶ月）
概要: 既存案件管理システムの改修
技術: Linux / MySQL / PHP / Zend Framework / JavaScript

**ネット航空券発行システムの保守**
期間: 2017/09〜2018/04（8ヶ月）
概要: 大規模航空券発行システムの保守運用
技術: Java

**自動36協定遵守検査システム**
期間: 2017/06〜2017/08（3ヶ月）
概要: 労働時間管理システムの開発
技術: Google Apps Script / JavaScript
