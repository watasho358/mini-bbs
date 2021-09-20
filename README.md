## Twitter風ひとこと掲示板サイト「mini-bbs」
# [mini-bbs](https://mini-bbs0710.herokuapp.com/)
## サービス概要
Twitterに似たインターフェースのメッセージングサイトです。 

Udemyの[PHP+MySQL（MariaDB） Webサーバーサイドプログラミング入門](https://www.udemy.com/course/php7basic/)で大部分を作り、機能追加をしました。

会員登録ページから新規会員登録もできますが、ひとつこちらでアカウントを用意しました。  
【ユーザー】  
メールアドレス：`test@test.com`  
パスワード：1111  
投稿画面右上の「管理する」から管理者でログインするときは、こちらでログインできます。  
【管理者】  
ID：admin  
パスワード：1111

<img src="https://user-images.githubusercontent.com/34031637/133959212-eb697745-9866-4736-8d1f-13a1573fcc7e.jpg" width="600px">

## 基本機能
- 会員登録、ログイン、ログアウト
- 画像アップロード（会員登録時のアイコン画像登録）
- メッセージ投稿、削除、返信
## 追加機能  
- 画像アップロード時の保存先をAWS S3へ変更
- 管理画面
- 管理画面での登録ユーザー一覧表示、登録ユーザーの削除
## 使用技術
- PHP 7.4.1
- AWS S3
