chrome-ext-kit
================

Google Chromeの拡張機能を簡単に作れるキット

ファイルを書き換えると自動的に拡張機能をリロードする機能付き

事前に必要なもの
-----------------
- [node.js] (http://nodejs.org)
- [Google Chrome] (http://www.google.co.jp/intl/ja/chrome/browser/)
- [Extensions Reloader(Google Chromeの拡張)] (https://chrome.google.com/webstore/detail/extensions-reloader/fimgfedafeadlieiabdeeaodndnlbhid)

インストール方法
-----------------
[このchrome-ext-kitのzip] (https://github.com/castaneai/chrome-ext-kit/archive/master.zip)をダウンロードして適当な場所に解凍

解凍したchrome-ext-kitの中で以下の2つのコマンドを実行

```sh
npm install -g gulp
npm install
```

実行方法
-----------
以下のコマンドを打つだけでOK!

```sh
gulp
```

html, json, js, cssファイルが変更されるたびにChromeで拡張機能がリロードされる。

Ctrl+Cでgulpを終了させることができます
