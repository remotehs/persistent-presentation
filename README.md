# README
## Useful information for the workshop on persistent.

Please go though the [official persistent introduction page](http://www.yesodweb.com/book/persistent) before the meetup.

The **code** directory contains a small example of using persisent.
Do `stack build`, followed by `stack exec code` to run the example. This will ensure you have a working persistent setup.

Install a sqlite program `sudo apt-get install sqlite3`.

Download the [Chinook database](https://chinookdatabase.codeplex.com/downloads/get/557773)

It would be great to also have the persistent code ready for quick reference.
`git clone https://github.com/yesodweb/persistent.git`



## Persistent ワークショップ (上記の日本語訳)

まずはこちらを一読しておいてください。

[Official persistent introduction page](http://www.yesodweb.com/book/persistent)

**code** ディレクトリには Persistent を使ったサンプルアプリが入っています。
**code** ディレクトリに移動して次のコマンドを打ってください。

```
% cd code
% stack build
```

これで Persistent に必要なセットアップが済みます。

注）ネットッワーク上からライブラリをダウンロードするので、やや時間がかかります。


コードを実行するには次のコマンドを打ってください。

```
% stack exec code
```

SQLite をインストールしておいてください。

*Ubuntu*

```
% sudo apt-get install sqlite3
```

*Mac*

```
% brew install sqlite3
```

[Chinook database](https://chinookdatabase.codeplex.com/downloads/get/557773) をダウンロードしておいてください。

Persistent のコードをダウンロードしておくと便利です。

```
% git clone https://github.com/yesodweb/persistent.git
```
