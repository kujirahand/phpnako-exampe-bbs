# なでしこ3PHPのサンプル集

 - 「なでしこ3PHP」に関しては詳しい解説は『[なでしこ3PHP](https://github.com/kujirahand/nadesiko3php)』を参考のこと。

# このサンプル集は何？

なでしこ3PHPで掲示板やチャットを作ってみたサンプル集です。
なでしこ3PHPで作る簡単なWEBアプリのサンプルです。

WEBアプリの開発では、プログラミング言語＋HTML＋CSS＋SQLとたくさんの知識が必要になります。
なでしこ3PHPを使えば、プログラミング言語の部分を日本語で楽しく記述できます。

## セットアップの方法

まずは、Node.jsをインストールし、その後、なでしこ3PHPをインストールします。
ターミナル(ターミナル.app / PowerShell)を起動し、以下のコマンドを実行すると、なでしこ3PHPがインストールされます。

```sh
npm install -g nadesiko3php
```

## プログラムを変換して実行する方法

例えば、サンプルのbbsを実行するには、以下のコマンドを実行します。
以下のコマンドを実行すると、なでしこのプログラムがPHPに変換されます。

```sh
# BBSのサンプルフォルダに移動
cd bbs
# なでしこのプログラムをPHPに変換
npm start
# PHPのローカルサーバーを起動
php -S localhost:8888
```

ブラウザを起動して `http://localhost:8888` にアクセスすると掲示板アプリを実行できます。

## その他の方法

あるいは、Linux/macOSでは以下のように書いても同じです。

```sh
cd bbs
npm install -g nadesiko3php 
phpnako -r .
```

