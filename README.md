# BudgetControllerBot
企画倒れになったBudget-controll LINE Botの墓場

```
# お金の予実管理LINE Bot!
1. LINE DeveloperサイトからChat Bot作成
https://developers.line.biz/ja/
2. Herokuで今回用のアプリ作成。自分のGithubにリポジトリ作成。herokuのgo-getting-startedをコピーしてdeploy
https://github.com/heroku/go-getting-started
3. herokuのGo用のチュートリアルに沿って、PostgreSQLのアドオン追加
https://devcenter.heroku.com/articles/getting-started-with-go
4. Go用のMessaging API SDKのインストールとオウム返しするbotを作るまでdone
『HerokuとGoでLINEの Messaging API環境を作ってみた』
https://qiita.com/hirosat/items/39cd6ba954a451bc01b8
5. ORMが欲しいのでgormをモジュールに追加
https://qiita.com/rikiyafujii/items/9772d92b5fe8cb3b82b0.
6. herokuでのpostgreへの接続は以下の記事参照
https://www.y-techmemo.work/entry/2019/06/14/163651
7. Model定義
http://jinzhu.me/gorm/models.html#conventions
8. main.goがカオスなのでディレクトリを分ける。↓を参考に
https://qiita.com/Asuforce/items/0bde8cabb30ac094fcb4
ローカルビルド
go build -o bin/go-getting-started -v .
https://account.line.biz/login?scope=line&redirectUri=https%3A%2F%2Fdevelopers.line.biz%2Fconsole%2Fchannel%2F1653481185%2Fbasics
https://developers.line.biz/ja/reference/messaging-api/
https://developers.line.biz/ja/reference/messaging-api/#webhook-event-objects
https://github.com/line/line-bot-sdk-go
https://tanaken.me/posts/190222/
https://devcenter.heroku.com/articles/getting-started-with-go#use-a-database
https://id.heroku.com/login
http://gorm.io/docs/connecting_to_the_database.html
https://qiita.com/gorilla0513/items/27cd34433a48fc8b65db#where%E5%8F%A5
http://jinzhu.me/gorm/models.html
https://qiita.com/Asuforce/items/0bde8cabb30ac094fcb4
https://github.com/teriyakiegg/til/blob/master/SoftwareDevelopment/web-application-architecture.md
https://qiita.com/hirotakan/items/698c1f5773a3cca6193e
https://atcoder.jp/contests/abs/tasks/practice_1
```
