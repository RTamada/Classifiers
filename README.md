
GitHub入門
〜人力バックアップはやめよう〜


次の行程で一通り

1. アカウント作る
2. レポジトリ test を作る, でてきた以下をGit Bashなりで実行

```
touch README.md
(中略)
git push -u origin master
```

3. ファイルをアップロードする http://za.toypark.in/html/2009/02-19.html
4. READMEを編集
5. 変更をpushする

```
# git status  変更のあったファイル名が赤く表示されて確認できる
git add --all   # git add ファイル名でもよい
# git status  緑になったことを確認
git commit -m'Revise README'
git push origin master # サーバーにあがる
```

6. もう一回変更、pushしたものを一個前のcommitに復元してみる
7. 任意：このレポジトリに自分のファイルを pull request してみる


