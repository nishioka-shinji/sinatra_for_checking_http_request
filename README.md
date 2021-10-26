# sinatra_for_checking_http_request

## local実行方法
`bundle exec ruby app.rb`
## 目的
cloudfront経由でのHTTPリクエストの中身を確認する
## 本番環境構築参考
### EC2
https://qiita.com/na0AaooQ/items/d7f814b184c6c1bd9d9c
### sinatra起動
https://qiita.com/onoda_kenta/items/88cf7840904f8b144043
### public DNS設定（elb無しでcloudfront設定できるように）
https://qiita.com/KKDDD/items/89af575523eab915b002