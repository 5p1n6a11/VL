# AWS

## 初期設定

### セキュリティ対策

#### ルートユーザーへの不正ログイン予防

* ルートユーザーの多要素認証設定

#### IAMユーザーへの不正ログイン予防

* IAMユーザーのパスワードポリシー設定
  * Security HubのIAMコントロール[^iam-controls]を基にパスワード要件を決定

[^iam-controls]:https://docs.aws.amazon.com/ja_jp/securityhub/latest/userguide/iam-controls.html

### コスト管理

* IAM ユーザーおよびロールによる請求情報へのアクセスの有効化
* Cost Explorerの有効化
*  予算の作成

### 管理者用IAMユーザー作成

* 管理者用ユーザーグループ作成
* 管理者用ユーザー作成
* 多要素認証設定
