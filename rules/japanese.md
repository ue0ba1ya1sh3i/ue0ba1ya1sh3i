## 目次
- [このルールについて](#このルールについて)
- [基本](#基本)
- [変数の命名規則](#変数の命名規則)
- [SaaSとわかりやすさの判別方法](#SaaSとわかりやすさの判別方法)
- [コメント](#コメント)
- [エラーハンドリング](#エラーハンドリング)
- [GitHub Issue](#GitHub-Issues)
- [Markdown](./markdown.md)
- [JavaScript](./javascript/japanese.md)
  - [TypeScript](./javascript/typescript/japanese.md)
  - [Node.js](./javascript/node.js/japanese.md)
    - [React](./javascript/node.js/react/japanese.md)

## このルールについて
- ネストされてる目次はネストしてる目次のルールも適用される

## 基本
- わかりやすさとSaaSの両立する
- 文法は推奨される書き方で書く
  - if文などJavaScriptではif (条件式) {}とスペースを入れて書く

## コード
- ファイルの最後は改行する
- 同種類のコードは改行してまとめる

## 変数の命名規則
| 種類 | 命名規則 | 例 |
| - | - | - |
| 変数 | camelCase | `googleLogin` |
| プロジェクト名 | kebab-case | `react-template` |
| ファイル / フォルダー | snake_case | `public`, `node_modules` |
| 定数 / 環境変数 | UPPER_SNAKE_CASE | `FIREBASE_API_KEY` |

## SaaSとわかりやすさの判別方法
- 変数は重複してなければSaaSを優先して重複してればアンダースコアでどんな種類かを記入する
  - 変数事態に関してまとまりが多ければJSONオブジェクトにして分かりやすくする

## コメント
- コメント開始時は最初にスペースを開ける
- まとまりのあるコードやデータにはコメントをつけてわかりやすくする

## エラーハンドリング
- 起こりえるすべてのものにエラーハンドリングを追加する
- 例
  - ユーザーの入力値や環境変数が見つからないとき
  - データのアクセス拒否や見つからないとき

 ## GitHub Issues
 - 詳細は必要であれば書く
 - タグをつける
 - なるべくシンプルにする
 - Sub Issuesを作成してわかりやすくする
