### コマンドmemmo

- フォルダを作成したいディレクトリでクローン 

```git clone https://github.com/ScheduleMethod/smart-management.git```

- ディレクトリを移ってブランチの取得

```git fetch```

- ブランチ確認

```git branch -a```

- ブランチの切り替え

```git checkout```

- ブランチを切り替え&新しいものを作成

```git checkout -b```

- 対象プロジェクトに移動

```cd /prj_name```

- リポジトリを作成 

```git init```
```git status //状態確認```

- ローカルプロジェクト内のファイルをコミット

```git add.```
```git commit -m "First commit.```

- リモートリポジトリへ接続し、プッシュ

```git remote add origin ssh://git@github.com:UserName/ProjectName```
```git remote add origin https://github.com/UserName/ProjectName```
or```git push -u origin master```


- マージの状態に関わらず、指定したブランチを削除する

```git branch -D <branchname>```

- 現在のブランチの名前をm以降に変更

```git branch -m 〇〇 ```

- 指定したコミットを引き継ぐ

```git cherry-pick コミットID```

- リモートブランチがローカルブランチの派生元ではない場合も、ローカルブランチの内容で強制的に上書きする 
```git push origin feature/lint-SchoolNotification -f```
