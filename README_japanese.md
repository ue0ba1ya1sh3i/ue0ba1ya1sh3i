## 目次 
- ### [開発者について](#開発者について-1) 
- ### [習得したスキル](#習得したいスキル-1) 
- ### [復習したいスキル](#復習したいスキル-1) 
- ### [習得したいスキル](#習得したいスキル-1) 
- ### [コードルール](#コードルール-1)

## 開発者について
- ### 主に JavaScript を起点に、いろんなものを作りながら学習中
- ### 仲間募集中
- ### SaaSの考え方で開発中

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
| 変数 / 関数 / ファイル / フォルダー | camelCase | `userData`, `loginCheck` |
| コンポーネント | PascalCase | `UserCard`, `LoginForm` |
| 定数 / 環境変数(.env) | UPPER_SNAKE_CASE(すべて大文字で) | `FIREBASE_API`, `DB_URL` |
| 同じ名前でアンダースコアで区別しないといけない場合 | UPPER_SNAKE_CASE | `stripe_price`, `firebase_data` |

### 基本ルール
- #### まとまりのないデータは先に記入
- #### まとまりのないデータとあるデータの間は改行
- #### 基本は同種類のものは一つのまとまりにまとめる
- #### 同種類でも別種類として扱うほうが良い場合、別種類にまとめる
- #### 最後は改行する

### コード
- ### 定義関係は最初に定義しておく
- #### まとまりがあって名前がついていない場合コメントで分かりやすく書く
- #### セミコロンはつけない

### コメント
- #### コメントの間にはスペースを入れる
- ### コメントは定義ルールにのっとらなくて良い

### 例

#### JSON
```json
{
  "title": "XXXX",
  "message": "XXXX",

  "user": {
    "mail": "XXXX@XXXX.XXXX",
    "name": "XXXX"
  }
}
```

#### JavaScript(コード)
```javascript

// Library
import { StrictMode, Suspense } from "react"
import { BrowserRouter, Routes, Route } from "react-router-dom"

```

#### ディレクトリ
```tree
index.html
index.css
index.js
font/
└── index.rtf
favicon/
├── index.png
├── 96.png
├── 192.png
└── 512.png
```
