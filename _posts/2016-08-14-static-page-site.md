---
layout: post
title:  Googleサイト駆逐
date:   2016-08-15 01:23:38 +0900
categories: static page site
---
あれこれ片付けたい。

- dotfilesの整理
  - [x] aliases/vimrc/zshrcの分割と整理
  - [ ] zshrc見直し
  - [ ] vimrc見直し
  - [ ] tmux見直し
- github pagesの活用
  - [x] ブログ立ち上げ
  - [ ] UI改修
- ローカル掃除
  - [ ] gistへ退避
- サイトの掃除
  - [ ] Googleサイト駆逐

## Googleサイト
無料appsで運用中のドメインで
複数人のITリテラシ低い編集者がいる前提で作ったgoogleサイト。
- 編集する人が実はいない
- 記述が特殊
- 静的ページしかない
ので書き直してしまった。
進歩ないけど、とりあえずrailsでslim。

## heroku
あとはherokuに上げてお仕舞いなんだけど、
今年、iPhone替えた時に二段階認証無効にするの忘れて、
拙い英語で問い合わせた結果、

> I'm afraid that I did nor supply a URL. You will need to provide this information:
>
> Last 4 digits from your credit card on file
> Name of app most recently deployed on your account
> The Git SHA of the last commit deployed and the date of the deployment
> If you can't provide this information then we will be unable to disable 2fa for your account.

カード登録してないただの無料ユーザーなんで諦めますって経緯があった。
新しいアカウント作ればよかったんだけど、heroku以外を探してみることに。

## S3
rails使える無料のpaas、海外のホストしか見つからなくて、
国内の限られた人すら見てるか分からない静的サイトだし、
DNSはroute53だしってことでS3にしてしまった。

