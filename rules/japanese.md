## 基本ルール
- 推奨される文法で記述する
- セミコロンはつけない
- 関連するコードには改行を入れて、視覚的にまとめる
- 不要なスペースやタブスペースを開けない
- 起こりえるすべてのエラーをハンドリングしてそれ以外はしない

## 命名規則
| 種類 | 命名規則 | 例 |
| - | - | - |
| 基本の変数 / 関数 | camelCase | `googleLogin`, `getUserData` |
| プロジェクト名 | kebab-case | `react-template` |
| ファイル / フォルダー | snake_case | `user_profile`, `api_client` |
| 環境変数 | UPPER_SNAKE_CASE | `FIREBASE_API_KEY`, `MAX_CONNECTIONS` |
| クラス / コンポーネント | PascalCase | `UserProfile`, `ApplicationLogger` |

## わかりやすさとSaaSを両立
- 変数名は、わかりやすさを重視して最低限の情報は示す
  - 例: `id`ではなく`userID`にするなど
- 関連する変数が多いなら、JSONオブジェクトにまとめて構造化する
  - 例: `userId`や`userData`、`userEmail`など`user`に関する変数が多ければ`user`というJSONオブジェクトを作って管理する

## コメント
  - コメントの間にはスペースを開けて見やすくする
  - やるべきことは`TODO: `、修正は`FIX: `をコメントの最初に着ける
