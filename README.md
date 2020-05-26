# memo_myself

何度も調べてしまう事の自分用メモ 

- [Git](#git)  
- [GitHub](#github)
- [Markdown](#markdown)
- [CSS](#css)
- [JS](#js)
- [その他](#その他)
  
## Git
### ・コミットコメントを修正する時
```
$ git commit --amend -m "コメント"

- 一つ前ならこれでOK
```

### ・gitをあとから入れるときの流れ
```
1, Githubでリポジトリ作成
2, ローカルのディレクトリで $git init
３。 git remote add origin https://github.com/nabe-kurage/リポジトリ（Githubのリポジトリに書かれている）　でGithubとつなげる
4, git commit で変更追加
５, git push origin でpushする
```

## GitHub  


## Markdown

### ・画像を表示する
```
![代替テキスト](画像のURL)

- ここ（Readme）に貼りたい時はissueに一回ドラッグアンドドロップして文字列をコピペすると早い
```



### ・リンクを入れる
```
[表示文字](URL)
```

### ・ページ内リンクを入れる
```
[hoge](#hoge)
# Hoge

- 見出しの深さに関係なく#は一つ
- 大文字は全て小文字にする
- 半角空白はハイフン(-) を使う

```

## CSS
### flex で良く使う表現
```
justify-content: space-between;　//左右にアイテムを分ける
align-items: center; //縦方向真ん中寄せ

```

### ボタンなどで選択できないようにする方法
```
user-select: none;
```

###  transitionとtransform
```
transitionが動きの指定
transformが変形

transition: margin-right 2s ease-in-out .5s;
transform: translate(120px, 50%);
```

## JS
### Gatsbyの導入部分と仮サーバー立ち上げ
未

## その他
### 環境変数の設定方法
未
