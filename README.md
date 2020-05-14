# ながの CAKE
![alt](images/logo.png)
長野県にある小さなな洋菓子店「ながのCAKE」の商品を通販するためのECサイト

# 使い方
'''
インストール方法
    $ git clone https://github.com/DMM-WEBCAMP-Avengers/nagano_cake.git
    $ cd nagano-cake
    $ bundle install
    $ rails db:migrate
'''
'''
テスト方法
ターミナルで下記のコマンドでサーバー立ち上げ後に
[ローカルサーバー](http://localhost:3000)にアクセスしてご覧ください。 
    $ rails s -b 0.0.0.0

管理者用アカウント
メールアドレス：admin@example.com  
パスワード：password
を入力してログインしてください。

顧客用アカウント
メールアドレス:example0@gmail.com
パスワード:password
を入力してログインしてください。
（登録画面にて新規登録も可能です。）
'''

# 実装機能

| カテゴリ | 機能名 | 説明 | 非ログイン時利用可否|
|---|---|---|---|
| 顧客  | 1ログイン機能 |・メールアドレス、パスワードでログインできる。 ・ログイン時のみ利用できる機能が利用できるようになる。|○|
||2ログアウト機能|・ログインしている状態からログアウト状態にする。 ・ログイン時のみ利用できる機能が利用できなくなる。|×|
3商品一覧表示機能
・商品を一覧表示する。 ・検索結果を表示する場合は、検索条件に当てはまる商品のみ一覧表示する。○
4商品詳細情報表示機能
・商品一覧画面で選択した商品の詳細情報を表示する。 ・カート追加機能が表示されている。○
5カート追加機能
・カートに商品を追加することができる。×
6カート一覧機能
・カートの中身を一覧表示することができる。×
7カート編集機能
・カートの中身の個数を編集したり、削除したりすることができる。×
8注文機能
・カートの中身の購入をすることができる。 ・支払方法や発送先を設定することができる。×
9会員情報編集機能
・登録している情報を編集することができる。×
10退会機能
・退会手続きをすることができる。×
11配送先追加・編集機能
・登録している配送先を一覧で確認することができる。 ・配送先の新規追加・修正・削除をすることができる。×
12注文履歴一覧表示機能
・過去の注文概要を一覧で確認することができる。 ×
13注文履歴詳細表示機能
・注文の詳細(注文商品や個数など)を確認することができる。×
管理者
1ログイン機能
・メールアドレス、パスワードでログインできる。 ・ログイン時のみ利用できる機能が利用できるようになる。○
2ログアウト機能
・ログインしている状態からログアウト状態にする。 ・ログイン時のみ利用できる機能が利用できなくなる。×
3注文履歴一覧表示機能
・過去の注文概要を一覧で確認することができる。×
4注文履歴詳細表示機能
・注文の詳細(注文商品や個数など)を確認することができる。 ・注文ステータス、製作ステータスを変更することができる×
5顧客一覧表示機能
・顧客情報を一覧で確認することができる。×
6顧客詳細情報表示機能
・顧客の詳細情報を確認することができる。 ・顧客のステータス(有効/退会)を切り替えることができる。×
7商品一覧表示機能
・登録商品を一覧で確認することができる。×
8商品詳細情報表示機能
・商品の詳細情報を確認することができる。×
9商品情報変更機能
・商品の登録情報を変更することができる。 ・販売ステータスを変更することができる。×
10ジャンル設定機能
・ジャンルの追加・変更・ステータス切り替えを行うことができる。×

# 開発環境
-vagrant
-Ruby 2.5.7

### 製作グループ アベンジャーズ(4名)