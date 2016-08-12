---
layout: post
title:  夏になった
date:   2016-08-11 23:52:48 +0900
categories: jekyll
---
あれこれ片付けたい。

- dotfilesの整理
  - [ ] aliases/vimrc/zshrcの分割と整理
  - [ ] zshrc見直し
  - [ ] vimrc見直し
  - [ ] tmux見直し
- github pagesの活用
  - [ ] ブログ立ち上げ
  - [ ] UI改修

## github pages
開いたら始まるチュートリアル通り。  
https://pages.github.com/

markdownで書いてpushしたら公開できるブログをイメージに[探してみた](https://staticsitegenerators.net/)。

- **markdown**  
atomにプレビューが簡単にできる[プラグイン](https://github.com/atom/markdown-preview)があるのでとりあえずこれで。`Ctrl-Shift-M`  
vimrc整理する時にでも検討。  
https://guides.github.com/features/mastering-markdown/

- **code sytax highlighting**  
対応一覧  
https://github.com/github/linguist/blob/master/lib/linguist/languages.yml


## zshrc
内容を用途別に分割した。中身の整理までできなかった。

- **gitignore**  
[qiita](http://qiita.com/anqooqie/items/110957797b3d5280c44f#応用編-ディレクトリの罠)に救われた。


## jekyll
こちらも[チュートリアル](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/)あり。
お試しのつもりだったけどこれでいいかも。
`jekyll serve`でプレビューできるけど、厳密に表現されてなさそう。深くは考えない。URLって自動でリンクしてくれるんじゃないの？とか、はてなみたいにembedしたいとかあるけど、今はいいや。
