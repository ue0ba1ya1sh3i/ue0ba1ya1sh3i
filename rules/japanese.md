## 基本コードルール
- 推奨される文法で記述する
- セミコロンはつけない
- 不要なスペースやタブスペースを開けない
- 固定値やインポート系は最初に記述する
- 三項演算子はあまり使はない
- 関連するコードには改行を入れて、視覚的にまとめる
  - そのときに必ず上部にコメントを記述する

## 命名コード規則
| 種類 | 命名規則 | 例 |
| - | - | - |
| 基本の変数 / 関数 / ファイル / フォルダー | camelCase | `googleLogin`, `getUserData` |
| プロジェクト名 | kebab-case | `react-template` |
| スペースを開けたい場合の変数 / 関数 / ファイル / フォルダー | snake_case | `user_profile`, `api_client` |
| 環境変数 | UPPER_SNAKE_CASE | `FIREBASE_API_KEY`, `MAX_CONNECTIONS` |
| クラス / コンポーネント | PascalCase | `UserProfile`, `ApplicationLogger` |

## コードのわかりやすさとSaaSを両立
- 変数名は、わかりやすさを重視して最低限の情報は示す
  - 例: `id`ではなく`userID`にするなど
- 関連する変数が多いなら、JSONオブジェクトにまとめて構造化する
  - 例: `userId`や`userData`、`userEmail`など`user`に関する変数が多ければ`user`というJSONオブジェクトを作って管理する

## コードコメント
  - コメントの間にはスペースを開けて見やすくする
  - やるべきことは`TODO: `、修正は`FIX: `をコメントの最初に着ける