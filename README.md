# アプリケーション名

HITSUDAN APP

# アプリケーション概要

言葉を発することができないとき、チャットで筆談をすることでコミュニケーションを取り合うことができる。1対1のチャットになります。

# URL

https://hitsudan-app.herokuapp.com/

# テスト用アカウント

* Basic認証パスワード : 1111

* Basic認証ID : hatano

 ユーザー 1

* メールアドレス :test@1111

* パスワード :admin1111

 ユーザー 2
* メールアドレス :test@2222

* パスワード :admin2222

# 利用方法

# メッセージ投稿

1.トップページよりユーザー新規登録を行う

2.チャットルームを作成し、参加するメンバーをリストから選択する

3.メッセージ投稿画面からチャット、もしくは画像を投稿する

# アプリケーションを作成した背景
現在入院中の父親と自分とのコミュニケーションツールとしてアプリを作成。

喉の気管切開をしたため 呼吸管理用器具を喉に付けていますが 筆談が必要になることが多い。

父親の直筆が読みづらかった為 正確に把握すべく気軽なチャット形式で開発することにした。

# 洗い出した要件

https://docs.google.com/spreadsheets/d/1Pu29GKmXFXq420mMO6NCT-IzkXikso-SAziw393lNyM/edit#gid=1785908763

# 実装した機能についての画像やGIFおよびその説明

ログイン画面（新規の場合Sign upページより登録）
[![Image from Gyazo](https://i.gyazo.com/c32a8ebbc5eb6c66da854b11ba4f6bcf.png)](https://gyazo.com/c32a8ebbc5eb6c66da854b11ba4f6bcf)

ログイン後、ルーム作成ボタンより筆談作成する
[![Image from Gyazo](https://i.gyazo.com/8f26ede9a1062526154c9a85c00eb644.png)](https://gyazo.com/8f26ede9a1062526154c9a85c00eb644)

タイトル、参加者を入力（１対１のチャット）
[![Image from Gyazo](https://i.gyazo.com/b077f836f729957fbd5db38b1934aa6a.png)](https://gyazo.com/b077f836f729957fbd5db38b1934aa6a)

下段コメント投稿欄よりメッセージ入力（画像も投稿可能）
[![Image from Gyazo](https://i.gyazo.com/01804526417fe75bee567fae101780b8.png)](https://gyazo.com/01804526417fe75bee567fae101780b8)

# 実装予定の機能

カテゴリ別のボタンから言葉をタップ感覚で押せられるような実装予定。

絵文字、スタンプを追加で実装予定


# データベース設計

[![Image from Gyazo](https://i.gyazo.com/a40f9f0f3e00cdef01e004ff8d6c8ebd.png)](https://gyazo.com/a40f9f0f3e00cdef01e004ff8d6c8ebd)

# 画面遷移図

[![Image from Gyazo](https://i.gyazo.com/7d0898fdc6fc0f097226e8c8e577f3e5.png)](https://gyazo.com/7d0898fdc6fc0f097226e8c8e577f3e5)

# 開発環境

* フロントエンド

* バックエンド

* インフラ

* テスト

* テキストエディタ

* タスク管理

# ローカルでの動作方法

以下のコマンドを順に実行。

% git clone https://githum.com/sessi973

% cd hitsudan-app

% bundle install

% yarn install

# 工夫したポイント
ペルソナがガラケー使用且つ高齢者のため、使い勝手を考えシンプルな設計にしたところ

扱う文字を大きく表示するようにしたところ

ボタンの色をわかりやすく同色で統一したところ






