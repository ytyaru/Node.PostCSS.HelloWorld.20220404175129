[en](./README.md)

# PostCSS.HelloWorld

　PostCSSを使ってみた。

# 特徴

* セールスポイント

# 開発環境

* <time datetime="2022-04-04T17:50:57+0900">2022-04-04</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspberry Pi OS](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2020-08-20 <small>[setup](http://ytyaru.hatenablog.com/entry/2020/10/06/111111)</small>
* bash 5.0.3(1)-release
* Node 16.14.2
* npm 8.5.0

```sh
$ uname -a
Linux raspberrypi 5.10.63-v7l+ #1496 SMP Wed Dec 1 15:58:56 GMT 2021 armv7l GNU/Linux
```

# インストール

## Node.js

* [ラズパイ4に最新Node.jsをインストールする](https://ytyaru.hatenablog.com/entry/2020/01/10/222222)

## このリポジトリ

```sh
git clone https://github.com/ytyaru/Node.PostCSS.HelloWorld.20220404175129
cd Node.PostCSS.HelloWorld.20220404175129
```

## 必要パッケージ（PostCSS, postcss-simple-vars）

```sh
cd Node.PostCSS.HelloWorld.20220404175129/src/hello-post-css
npm install
```

# 使い方

```sh
pcss=./node_modules/.bin/postcss
input=./src/css
output./dst/css
$pcss $input -d $output
```

　`dst`ディレクトリにCSSファイルが出力される。

# 著者

　ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![twitter](http://www.google.com/s2/favicons?domain=twitter.com)](https://twitter.com/ytyaru1 "twitter")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# ライセンス

　このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

