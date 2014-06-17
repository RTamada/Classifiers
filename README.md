
GitHub入門
〜人力バックアップはやめよう〜


次の行程で一通り

1. アカウント作る
2. レポジトリ test を作る(右上の+ボタン)

```
touch README.md
(中略)
git push -u origin master
```
こんなのがでてくるのでメモしとく

3. Windowsの人はGit Bashなり入れてください
http://yuheikagaya.hatenablog.jp/entry/2012/12/11/224216 これの6.あたりまでやってみる

3. 先のコマンドにしたがいファイルをアップロードする 参考：http://za.toypark.in/html/2009/02-19.html
4. READMEを編集
5. 変更をpushする

```
git add --all   # git add ファイル名でもよい
git commit -m'Revise README'
git push origin master # サーバーにあがる
```

6. もう一回変更、pushしたものを一個前のcommitに復元してみる
7. 任意：このレポジトリに自分のファイルを pull request してみる


