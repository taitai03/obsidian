```
fatal: not a git repository (or any of the parent directories): .git
```
Gitコマンドを実行しようとしたディレクトリが、Gitリポジトリとして初期化されていないことを示すエラーです。Gitはプロジェクトの履歴を管理するために、.gitというディレクトリ（リポジトリの実体）を必要としますが、そのディレクトリが存在しない場合にこのエラーが発生します

# githubアカウントの設定
```
$ git config --global user.email "email@example.com"

```

```
error: src refspec feature/delete-filed-worker-department does not match any
```
このエラー、**ほぼ100％「ブランチ名のスペルミス」** が原因です

# conflictの解消
https://zenn.dev/kkagomme/articles/648325c6dacfb5

# **なぜ CI が exit code 1 で落ちた？**

rubocop はスタイル違反があると exit code 1 を返すから、

GitHub Actions が「失敗」と判断して止まった。


## 並行して作業するときのbranch

switchするときは、どこからswitshしているかの確認を怠らない！
