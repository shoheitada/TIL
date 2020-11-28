### Tips
- コントローラーからViewの受け渡し with/compactメソッド

https://qiita.com/ryo2132/items/63ced19601b3fa30e6de

- webphpでのグループ化①
　
　Route::group(['prefix' => ''],
 
  prefix はURLが同じであれば''内に書くことで省略できる
  
- webphpでのグループ化②

　Route::group['middeware' => 'auth']
 
  authにきめられたことをすべてのコントローラーで実施
  
-　webphpでの記載

　get('/home', 'HomeController@index')->name('home');
 
　->name('home');とすることでveiwのaタグにこれを書けばwebphpを変えればOK
 
 - viewの中の@sectionの意味
 
 　@sectionで自分固有のパーツを定義する。https://qiita.com/yukibe/items/86ccd3f72ecf943825a6
