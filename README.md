# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。
[_Ruby on Rails チュートリアル_](https://railstutorial.jp/)
（第 7 版）
[Michael Hartl](https://www.michaelhartl.com/) 著

## ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)内にある
ソースコードは MIT ライセンスと Beerware ライセンスのもとで公開されています。
詳細は [LICENSE.md](LICENSE.md) をご覧ください。

## 使い方

このアプリケーションを動かす場合は、まずはリポジトリをフォークしてください。
次に、ローカル環境にクローンし、プロジェクトディレクトリに移動します。

```
$ git clone https://github.com/あなたのユーザー名/リポジトリ名.git
$ cd リポジトリ名
```

必要な Ruby のバージョンをインストールし（例: 3.2.8）、依存する gem をインストールします。

```
$ rbenv install 3.2.8

$ rbenv local 3.2.8

$ gem install rails -v 7.0.4.3

$ gem install bundler -v 2.5.6

$ bundle install
```

次に、データベースへのマイグレーションを実行します。

```
$ bin/rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ bin/rails test
```

詳しくは、[_Ruby on Rails チュートリアル_](https://railstutorial.jp/)
を参考にしてください。
