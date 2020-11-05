## tips
- maildevはメール送信アプリのテストをする時に使用する
  https://qiita.com/kanemu/items/1f2da063c7e5b5477502
  
  ```docker-compose up -d app wev mysql maildev```
  
  - 3306使われているか？どこかで使っているのであれば対象ディレクトリにいって以下コマンドでどっかー止める
  ```docker-compose down```
