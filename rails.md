# Railsエンジニア初心者研修資料

## 前提
Macを使っていることを前提とします。

## ターミナルを設定する
黒い画面に慣れましょう。oh-my-zshでちょっと便利にしておきます。

* 参考
	* http://qiita.com/udzura/items/0d08d71d809bfd8c5981

## Vimを使う
まずは開発に使うエディタを設定します。おすすめはVimです。Sublime Textもメジャーですが、リモートサーバにログインした時に使えないので、Vimに慣れておくのがおすすめです。

* 参考
	* [ドットインストール](http://dotinstall.com/lessons/basic_vim)

## Unixコマンドを使う

ターミナルで作業をする時にUnixの基本的なコマンドを使えると非常に捗ります。

* 参考
	* [ドットインストール](http://dotinstall.com/lessons/basic_unix)

## Gitを使う

ソースコードの管理にはGithubを使います。Gitの基本的な使い方を押さえておきましょう。

* 参考
	* [ドットインストール](http://dotinstall.com/lessons/basic_git)
	* [サルでもわかるGit入門](http://www.backlog.jp/git-guide/)

## HTML、CSS、Javascriptに慣れる

フロントもちょっと書くのでフロントのコーディングにも慣れておきましょう。

* 参考
	* [ドットインストール（HTML）](http://dotinstall.com/lessons/basic_html_v2)
	* [ドットインストール（CSS）](http://dotinstall.com/lessons/basic_css_v2)
	* [ドットインストール（Javascript）](http://dotinstall.com/lessons/basic_javascript_v2)

## Chrome Developer Toolsを使う

フロントの開発においてGoogle Developer Toolsは必須です。使い方をマスターしておきましょう。

* 参考
	* [ドットインストール](http://dotinstall.com/lessons/basic_chrome_dev_v2)

## Rubyを学ぶ

Railsの前にRubyの基本的な構文をみておくことが大事です。

* 参考
	* [ドットインストール](http://dotinstall.com/lessons/basic_ruby_v2)

## Sinatraでアプリケーションを作成する

Railsについて学ぶ前に軽量フレームワークのSinatraに触れてみましょう。社内勉強会の資料があるのでこちらをみてみてください。

* 参考
	* [Sinatra: 社内勉強会](http://lo-upe.hatenablog.com/entry/2014/09/09/000516)

## Railsに乗ろう

いよいよRailsに乗ります。RailsTutorialは非常に便利なドキュメントなので、こちら全体を通して進めてみましょう。コードのコピー&ペーストは決してやらずにすべてタイプしてください。タイポによりはまる人が多いので焦らず一つずつ進めてください。

* 参考
	* [Ruby on Rails Tutorial](http://ruby.railstutorial.org/)


## WIPプルリクとGithub Flow

Githubを用いて開発を進めるにあたってWIPのプルリクエストとGithub-Flowの考え方に則ります。下記URLの流れにそって開発を進めてください。

http://qiita.com/sue738/items/09d9292e7654747ca208

## 考え方
* DRY
	* Don't Repeat Yourself.
	* 3回同じコードを書いたら共通化する
* CoC
	* Convention over Configuration 
	* 設定より規約
* YAGNI
	* You ain't gonna need it
	* 機能は実際に必要となるまでは追加しない
