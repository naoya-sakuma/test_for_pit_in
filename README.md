# Pit In

## 概要
目標とその達成に必要なタスクを管理し、日々の行動に落とし込むサポートをする。


## コンセプト
目標管理を簡単にする。


## バージョン
Ruby 2.6.5
Rails 5.2.4


## 機能一覧
#### ユーザー関連
- ユーザー登録
  - メールアドレスで登録
  - SNSアカウントで登録
- ログイン
- ユーザー情報編集
- 退会

#### 目標作成機能
- 目標を作成
  - 目標一覧
  - 目標作成
  - 目標編集
  - 目標削除

#### プランニング機能
- monthlyプランニング
  - 取り組み中の目標とその解決案を表示
  - 今月取り組む解決案を設定
  - 解決案の作成/編集/削除
  - タスクの作成/編集/削除

- weeklyプランニング
  - 今月取り組む解決案とそのタスクを表示
  - 今週取り組むタスクを設定
  - タスクの作成/編集/削除
  - ステップの作成/編集/削除

- dailyプランニング
  - 今週取り組むタスクとそのステップを表示
  - 今日取り組むステップを設定
  - ステップの作成/編集/削除


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


## 卒業要件
- 就業Term内の技術
  - devise (gem)
  - omniauth (gem)
  - AWS

- カリキュラム外の技術
  - 目標のCSV出力
