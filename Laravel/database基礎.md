## Tips
- マイグレーションファイルカラムの追加　https://readouble.com/laravel/5.5/ja/migrations.html

eX) Vacher(255)→$table->string('name', 100);

- データベースのtimestamp型　nullを許容する場合 ->nullable();

ex) $table->timestamp('deleted_at')->nullable();



