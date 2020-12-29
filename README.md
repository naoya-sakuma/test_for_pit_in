#Pit In


## 概要
目標達成をサポートするアプリケーション


## コンセプト



## バージョン
Ruby 2.6.5
Rails 5.2.4


## 機能一覧
#### ユーザー向け機能
- ユーザー登録
  - メールアドレスで登録
  - Facebookアカウントで登録
- ログイン
- ユーザー情報編集

- 商品購入機能
  - 商品閲覧
  - 商品検索
　  - 評価順
　  - 価格順
  - 商品購入（支払い方法：クレジットカードのみ）

- 商品評価機能
  - 商品のお気に入り
  - 商品へ評価付与

- お知らせ機能
  - お知らせ一覧の閲覧
  - お知らせの詳細確認

- 退会

#### 事業者向け機能
- ユーザー登録依頼
- ログイン
- ユーザー情報編集

- 商品管理機能
  - 自社商品閲覧
  - 商品登録/編集
  - 商品詳細確認
  - 商品削除

#### 運営者向け機能
- ユーザー登録依頼
- ログイン
- ユーザー情報編集

- 事業者管理機能
  - 事業者閲覧
  - 事業者登録/編集
  - 事業者詳細確認
  - 事業者削除

- お知らせ機能
  - 新規作成
  - 一覧の閲覧
  - 詳細確認
  - 削除


## カタログ設計
https://docs.google.com/spreadsheets/d/13sQJtfMkbIGoGTB7NlYZbZ9n1wJVpdSL5K5gq98O3gE/edit#gid=23328459


## テーブル定義
https://docs.google.com/spreadsheets/d/1b1Q5IyqyVYp72vtFqO5_8Jt7Mp4FNbm7EJEYaNn4mEY/edit?usp=sharing


## 画面遷移図
https://docs.google.com/spreadsheets/d/1b3sEMgdfR3RLh4Kkh6fZXlQey_Td5pEcs41A1cb43Vs/edit?usp=sharing


## 画面ワイヤーフレーム
https://docs.google.com/spreadsheets/d/1JNdn30eWSvzWOYhq7uVBd1YfIeUQhNr7jq3DHI5_qBc/edit?usp=sharing


## 使用予定Gem
- devise
- omniauth
