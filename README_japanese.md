## 目次 
- ### [開発者について](#開発者について-1) 
- ### [習得したスキル](#習得したいスキル-1) 
- ### [復習したいスキル](#復習したいスキル-1) 
- ### [習得したいスキル](#習得したいスキル-1) 
- ### [コードルール](#コードルール-1)

## 開発者について
- ### 主に JavaScript を起点に、いろんなものを作りながら学習中
- ### 仲間募集中

## 習得したスキル

| カテゴリ | 技術 |
|----------|------|
| 言語（実務レベル） | JavaScript, HTML / CSS, Markdown, Command Prompt |
| フレームワーク | Node.js, Express |
| サービス | GitHub, Firebase, SwichBot, LINE, Google Analytics, Google Search Console |
| ツール | VSCode, Git, Vite |

## 復習したいスキル

| カテゴリ | 技術 |
|----------|------|
| 言語 | TypeScript, Google Apps Script (GAS) |
| フレームワーク | React, Tailwind CSS |

## 習得したいスキル

| カテゴリ | 技術 |
|----------|------|
| 言語 | Dart, C#, VBA |
| フレームワーク | Next.js |
| サービス | GCP, AWS, Stripe |
| ツール / その他 | Linux, WSL, ネットワーク, データベース |

## コードルール

### 定義関係
| 用途 | 命名規則 | 例 |
|------|-----------|----|
| 変数 / 関数 | camelCase | `userData`, `loginCheck` |
| コンポーネント / ファイル | PascalCase | `UserCard`, `LoginForm` |
| 定数 / 環境変数 (.env) | UPPER_SNAKE_CASE(すべて大文字で) | `API_KEY`, `DB_URL` |
| 同じ名前でアンダースコアで区別しないといけない場合 | UPPER_SNAKE_CASE | `stripe_price`, `firebase_data` |
| アンダースコアをつけたほうが絶対読みやすい場合(優先) | UPPER_SNAKE_CASE | CodeRule_japanese linux_arch |

### JSONなどのデータ
- #### まとまりのないデータは先に記入

### コード
- #### 必要なところで改行する
- #### 変数定義などの命名定義の基本はcamelCase

### コメント
- #### 複雑な処理や忘れそうな部分にはコメントを付ける  
- #### まとまりごとに説明を入れる

### ディレクトリ構成
- #### 基本は同じ種類のものは一つのディレクトリにまとめる
- #### 分かりにくければ外に出す(/components/pagesを/pagesに)

### コード整理の流れ
#### 1. 定義や設定系は最初にまとめる
#### 2. 処理の流れは上から順に書く
#### 3. 一時的・試行用のコードは上に置き、リファクタリング
