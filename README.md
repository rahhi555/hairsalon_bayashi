# hairsalon_bayashi
スッキリわかるSQL入門のドリルに登場する美容院予約システムを実際に作成。RaislのAPIモード、Nuxtjs、Terraformの練習アプリ。

## 使用技術
- インフラ
  - docker
  - docker-compose
  - AWS ECS(Fargate)
- インフラコード化
  - terraform
- フロントエンド
  - Nuxtjs 2.15.2(SSRモード)
- バックエンド
  - Rails 6.1.3.1(APIモード)
- データベース
  - MySQL 8.0.23
- CD/CI
  - GithubActions(プッシュ時にテスト、マージ時にデプロイ)
- 認証
  - firebase Auth(フロント側はSSRに対応させるためCookieにして管理。API側は技術力不足により認証なし。)
  - firebase Admin SDK
- CSSフレームワーク
  - Tailwind CSS
- 主なパッケージ
  - `@nuxtjs/composition-api`(Nuxtjsでcomposition-api記法をするために使用)
  - `@fullcalendar`(予約情報等をカレンダーとして確認するために使用)
  - `vee-validate`(フォームのバリデーション)
  - `Rspec`(API側のテスト。)
 <hr>
 
 ## 見た目サンプル
 - TOP
 ![トップ画像](https://github.com/rahhi555/github_image_garage/blob/master/hairsalon_bayashi/2175B20E-86E2-4079-8D21-DE93A718A641_1_105_c.jpeg)
 - 予約
 ![予約画像](https://github.com/rahhi555/github_image_garage/blob/master/hairsalon_bayashi/1E1CDB9F-435A-4417-B296-6BBF822D5C47_1_105_c.jpeg)
 - カットメニュー追加
 ![メニュー追加画像](https://github.com/rahhi555/github_image_garage/blob/master/hairsalon_bayashi/CCDAEC06-2108-4EF7-8535-E08283830D11_1_105_c.jpeg)
 - 予約カレンダー
 ![予約カレンダー画像](https://github.com/rahhi555/github_image_garage/blob/master/hairsalon_bayashi/E0504325-D363-48A9-A959-D38D880C0A5F.png)
 - レスポンシブデザイン・画像投稿
 ![お客様画像](https://github.com/rahhi555/github_image_garage/blob/master/hairsalon_bayashi/0A87A309-633B-4A8F-ACD2-D3B006AC287E_1_105_c.jpeg)
 - 入力フォームバリデーション
 ![バリデーション画像](https://github.com/rahhi555/github_image_garage/blob/master/hairsalon_bayashi/5A505F1B-7F44-40E2-8A8B-43E0CB746A6B.png)
 
 ###### 現在はデプロイしていません
