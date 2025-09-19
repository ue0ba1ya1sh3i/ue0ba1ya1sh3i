## 目次 
- ### [開発者について](#開発者について-1) 
- ### [習得したスキル](#習得したいスキル-1) 
- ### [復習したいスキル](#復習したいスキル-1) 
- ### [習得したいスキル](#習得したいスキル-1) 
- ### [コードルール](#コードルール-1)

## 開発者について
- ### 主に JavaScriptを起点に、いろんなものを作りながらReactやPython、Node.jsを学習中
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
| 変数 / 関数 / ファイル / フォルダー / 基本 | camelCase | `userData`, `loginCheck` |
| コンポーネント | PascalCase | `UserCard`, `LoginForm` |
| 定数 / 環境変数(.env) | UPPER_SNAKE_CASE(すべて大文字で) | `FIREBASE_API`, `DB_URL` |
| 同じ名前でアンダースコアで区別しないといけない場合 | snake_case | `stripe_price`, `firebase_data` |

### 基本ルール
- #### これはあくまで基本なので例外があるならそれに従う
- #### `node_modules`内のファイルなどは自分が作ったものではないものは対象外
- #### まとまりのないデータは先に記入
- #### まとまりのないデータとあるデータの間は改行
- #### 基本は同種類のものは一つのまとまりにまとめる
- #### 同種類でも別種類として扱うほうが良い場合、別種類にまとめる
- #### 最後は改行する
- #### SaaS思考で開発(不要なコメントやコードなどは作らない)
- #### Tabスペースのインデント数は2にしてください

### コード
- ### 定義関係は最初に定義しておく
- #### まとまりがあって名前がついていない場合コメントで分かりやすく書く
- #### セミコロンはつけない
- #### JSON型オブジェクトはJSONと同じ書き方で記入する

### JSON
- ### 不要なまとまりなのに指定しなければならないのなら一つの行にまとめる

### コメント / Markdown
- #### コメントの間にはスペースを入れる
- ### コメントは定義ルールにのっとらなくて良い
- ### 余計なことは書かない

### 例

#### JSON
```json
{
  "title": "XXXX",
  "message": "XXXX",

  // 1つにまとめる
  "rewrites": [{ "source": "**", "destination": "/index.html" }],

  // 複数あるのでまとめない
  "headers": [
    {
      "source": "/assets/**",
      "headers": [{ "key": "Cache-Control", "value": "public,max-age=31536000,immutable" }]
    },
  },

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
