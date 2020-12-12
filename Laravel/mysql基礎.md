### コマンド等

- 作成したマイグレーションファイルを読み込ませる

　　```php artisan migrate```

- 上記は、ファイルを追加した場合は読み込むが、ファイルの更新の場合は読み込まれないので、以下を実施
   しかし、チームで開発している時は実施しないコマンド　通常はファイルを足していく　

　　```php artisan migrate:rollback```
  
- シーダーの読み込み
   
   ```php artisan db:seed;```(全部)

 　```php artisan db:seed --class=PostsTableSeeder```（指定）
