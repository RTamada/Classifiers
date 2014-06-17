
# GitHub入門
〜やめよう手動バックアップ〜

前回の反省点はコードをみんなで管理しなかった点~~とLINE~~にあると思います。そこでGitHubです。共有・バックアップ・公開が簡単にできます。

1. 最初によんでください：http://samura1.net/2012/10/github_first/
2. アカウント作ったら[Issues](https://github.com/ShigekiKarita/Classifiers/issues)に書き込んでください。このレポジトリの共同作業者に追加します。今後なにか質問・相談があればここで
3. 基本的にブラウザかCUIで説明します。GUIがいい人は「Source Tree」でググってください


<br>


「ブラウザのひと」　ファイル操作のみ。頻繁な更新には面倒

1. アカウント作る
2. 自分のレポジトリ作る（右上の+ボタン）
3. レポジトリにファイルを追加する（真ん中のレポジトリ名/+リンク）
4. 苅田から返信があったら、このレポジトリにファイルを追加する


<br>


「CUIのひと」  全部できる。一度設定すると楽

1. アカウント作る
2. このページを参考に色々設定 http://yuheikagaya.hatenablog.jp/entry/2012/12/11/224216 (5まで)
2. このレポジトリをクローンする

```
cd 適当なフォルダに移動
git clone https://github.com/ShigekiKarita/Classifiers.git
```

3. 自分でレポジトリをつくる（右上の+ボタン
5. でてきたページのコマンドで適当なフォルダ作って試す（READMEができるはず


だいたいいつもの更新用のコマンド：ファイル選択(add)→記録(commit)→アップロード(push)

```
git add --all
git commit -m 'なにかひとこと'
git push origin master
```

応用

1. 前のコミットからファイルを復元してみる
2. Karitaから返信がきたらこのレポジトリに適当なファイルをpushしてみる

---

## 課題について

前回は、OpenCVとかC++使ったせいで取っ付きにくくなった感じがします。そういうのやめます。

一人一個なんか識別器作りましょう。
別に言語はなんでも良いと思います、好きなもの使いましょう。

**色んな言語が試せるサイト**
https://ideone.com/ 

---

## JavaScript

ブラウザがあれば動くのが最高。あと結構速い。

おすすめの入門 http://dotinstall.com/lessons/basic_javascript_v2

JSで作った線形識別器

## D言語

それでもJSは遅いです。C/C++と同じ位速いD言語良いと思います！

D言語のプログラミング環境ない人もいると思いますが、インストールとかポインタとか単体テストとか何もかもC/C++よりはるかに楽で、おすすめです。

わかりやすい入門： https://github.com/k3kaimu/d-manual

いまVisual Studioを使ってるひとは便利なプラグインがあるのでぜひ http://www.dsource.org/projects/visuald

D言語で書いた線形識別器(準備中)


## 連絡先
shigekikarita@gmail.com

最近は土日含めてだいたい研究室(E3, 8階)います...
