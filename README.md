# Hi, I'm Yusho Aoyama 👋
### Backend Engineerを目指して、Webアプリケーション・REST APIを開発しています!
PHP / Laravelを中心に、API設計・データベース・認証 / 認可・テストなど、
保守性を意識したバックエンド開発について学んでいます。

## 👨‍💻 About Me
- 🎓 オーストラリアのTAFEで Information Technology（Back End Web Development） を学習
- 💻 PHP / Laravel を中心にWebアプリケーション・REST APIを開発
- 🤝 チーム開発で要件確認から設計・実装・テスト・デプロイまで経験
- 🗾 日本でバックエンドエンジニアとしてのキャリアを目指しています


## 🛠️ Tech Stack

**Backend**
- PHP
- Laravel
- REST APIs

**Database**
- MySQL
- MariaDB
- MongoDB

**Frontend**
- HTML
- CSS
- JavaScript
- Next.js

**Tools**
- Git
- GitHub
- Postman


## 🚀 Featured Projects

### 💰 Smart Expense API

Laravelで開発した、支出・予算・カテゴリー・ユーザーを管理するRESTful APIです。
要件分析から設計・実装・テスト・デプロイまで取り組み、レビューをもとに個人でリファクタリングを行いました。

**Tech**: `PHP` `Laravel` `MariaDB` `SQLite` `Sanctum` `Pest` `Scramble`　など

**主な実装**
- Admin / Staff / Clientのロールベースアクセス制御
- Laravel Sanctumによるトークンベース認証
- Users / Categories / Expenses / BudgetsのCRUD
- Laravel Policyによる認可処理
- Form Request / API Resourceによる責務分離
- PestによるFeature Test
- 金額データの整数（cents）管理
- Rate Limiting
- ScrambleによるAPIドキュメント

[View Repository](https://github.com/yusho-aoyama/smart-expense-categorizer-api)

### 😄 Joke App
LaravelのMVCアーキテクチャを学ぶために開発した、ジョークの投稿・管理・評価ができるWebアプリケーションです。
認証、CRUD、データベースリレーション、ロール・権限管理など、Laravelを使用したWebアプリケーション開発の基礎を実装しました。

Tech: `PHP` `Laravel` `Blade` `Livewire` `Tailwind CSS` `MySQL`　など

**主な実装**
- ユーザー登録・ログイン・ログアウト
- Jokes / CategoriesのCRUD
- Users / Jokes / Votes / Categoriesのリレーション
- Admin / Staff / Client Userのロール・権限管理
- LivewireによるLike / Dislike機能
- Bladeを使用した画面実装
- セッションを利用したログイン状態の管理

[View Repository](https://github.com/yusho-aoyama/ya-saas-jokes-app)

### 📋 Project Management App

Next.js 15（App Router）を使用して開発した、プロジェクト・タスク・マイルストーンを管理するフロントエンドWebアプリケーションです。

TAFEから提供されたLaravel REST APIと連携し、API仕様の確認からUI/UX設計、CRUD実装、テスト、デプロイまで取り組みました。

Tech: `Next.js` `React` `JavaScript` `Tailwind CSS` `Cloudflare Pages` など

**主な実装**
- Projects / Tasks / MilestonesのCRUD
- REST APIとの連携
- 再利用可能なReactコンポーネント
- Loading / Error / Validationへの対応
- レスポンシブUI
- GitHub / Cloudflare Pagesによる自動ビルド・デプロイ

````
**Note**: 現在は連携していたTAFE提供APIが利用できないため、API通信を必要とする機能は正常に動作しません。
````

[View Repository](https://github.com/yusho-aoyama/nextjs-app-dev)

