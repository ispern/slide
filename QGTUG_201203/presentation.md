# Chrome Developer Toolsの<br>便利な機能
----
## 自己紹介

* 名前：松岡 宏満
* 会社：株式会社W・I・Z
* スマホアプリ作ったり、スマホ向けWebサイト作ったり、業務Webシステム作ったり

----

## Chrome Developer Toolsって？

* Google Chrome標準の開発者向けツール
* DOMやCSSの検証、変更ができる
* JavaScriptのデバッグ機能

----

## こんな感じです。

![about](http://img.skitch.com/20120310-f19ucaxi7dd872phcgfcdcitxb.jpg)

----

## 各パネルの説明
<p>&nbsp;</p>
<div id="tableWrapper" style="width: 100%; "><table id="vsTable"><tbody><tr><td class="cat title" style="width: 50%; "></td><td class="title" style="width: 50%; "><div class="">説明</div></td></tr><tr class="second"><td class="cat" style="width: 50%; "><div class="">Elements</div></td><td style="width: 50%; " class="text"><div class="">DOMやCSSの検証、動的な変更ができる</div></td></tr><tr><td class="cat" style="width: 50%; "><div class="">Resources</div></td><td style="width: 50%; " class="text"><div class="">静的コンテンツ（JSやCSS）、Local StrageやCookieなどが参照できる</div></td></tr><tr class="second"><td class="cat" style="width: 50%; "><div class="">Network</div></td><td style="width: 50%; " class="text"><div class="">ページのリクエストを参照できる（静的コンテンツとかXHRとか）</div></td></tr><tr><td class="cat" style="width: 50%; "><div class="">Scripts</div></td><td style="width: 50%; " class="text"><div class="">JSデバッガー</div></td></tr><tr class="second"><td class="cat" style="width: 50%; "><div class="">Timeline</div></td><td style="width: 50%; " class="text"><div class="">JSの評価、実行、レンダリングの時間、メモリ使用量を参照できる。</div></td></tr><tr><td class="cat" style="width: 50%; "><div class="">Profiles</div></td><td style="width: 50%; " class="text"><div class="">CPU、メモリのプロファイラ</div></td></tr><tr class="second"><td class="cat" style="width: 50%; "><div class="">Audits</div></td><td style="width: 50%; " class="text"><div class="">Webサイトのチェック（Y!Slowみたいな）</div></td></tr><tr><td class="cat" style="width: 50%; "><div class="">Console</div></td><td style="width: 50%; " class="text"><div class="">JSの対話式コンソール</div></td></tr></tbody></table></div>
<p>This table was created with <a href='http://www.compareninja.com' target='_blank'>Compare Ninja</a>.</p>

----

## ショートカットキーを覚えよう

最低限これを覚えておくと便利かも

<div id="tableWrapper" style="width: 100%; "><table id="vsTable"><tbody><tr><td class="cat title" style="width: 33%; "></td><td class="title" style="width: 33%; "><div class="">Win &amp; Linux</div></td><td class="title" style="width: 33%; "><div class="">Mac</div></td></tr><tr class="second"><td class="cat" style="width: 33%; "><div class="">Chrome Developer Tools起動</div></td><td style="width: 33%; " class="text"><div class="">Control + Shift + i</div></td><td style="width: 33%; " class="text"><div class="">Cmd + Shift + i</div></td></tr><tr><td class="cat" style="width: 33%; "><div class="">Toggle Inspect Element mode</div></td><td style="width: 33%; " class="text"><div class="">Control + Shift + c</div></td><td style="width: 33%; " class="text"><div class="">Cmd + Shift + c</div></td></tr><tr class="second"><td class="cat" style="width: 33%; "><div class="">Toggle Console</div></td><td style="width: 33%; " class="text"><div class="">Esc</div></td><td style="width: 33%; " class="text"><div class="">Esc</div></td></tr><tr><td class="cat" style="width: 33%; "><div class="">Next Panel</div></td><td style="width: 33%; " class="text"><div class="">Ctrl + ]</div></td><td style="width: 33%; " class="text"><div class="">Cmd + ]</div></td></tr><tr class="second"><td class="cat" style="width: 33%; "><div class="">Previous Panel</div></td><td style="width: 33%; " class="text"><div class="">Ctrl + [</div></td><td style="width: 33%; " class="text"><div class="">Cmd + [</div></td></tr></tbody></table></div>
<p>This table was created with <a href='http://www.compareninja.com' target='_blank'>Compare Ninja</a>.</p>

----

# 各パネルの便利だと思う機能のみ紹介

----

# Elementsパネル

----

## 疑似要素のスタイル確認

DOMの疑似要素のスタイルをマウスを動かさずに確認できる

![elements1](http://img.skitch.com/20120310-n2hfahawsbbk9gta1wj9ct9pcd.jpg)

----

## イベントリスナーの確認

DOMのイベントリスナーを確認できる

![elements2](http://img.skitch.com/20120310-p4heuimuk6hx18ytd6nxcngdj2.jpg)

----

# Resourcesパネル

----

## JS,CSSファイルの編集、保存①

編集したいJS,CSSファイルを選択して、左下のエンピツボタンを押す

![resources1](http://img.skitch.com/20120310-jj23h7rryuqsjjksgcwtyucagb.jpg)

----

## JS,CSSファイルの編集、保存②

編集ができる

![resources1](http://img.skitch.com/20120310-rg5xch275aaghdhj85w5gpq6ep.jpg)

----

## JS,CSSファイルの編集、保存③

編集後、再度エンピツボタンを押すか、Ctrl + s or Cmd + s で保存できる

編集した行は薄緑にハイライト表示される

![resources1](http://img.skitch.com/20120310-8c6kc3ibq4wrrmu8tg1wpuny8j.jpg)


----

## JS,CSSファイルの編集、保存④

保存したファイルは時刻毎に保存される

![resources1](https://img.skitch.com/20120310-1btbx27iwffanbct9dstsc6apt.jpg)

※originalは元々読み込んだファイル

----

## Web Storageを操作

Local Storage, Session Storageのレコード追加・編集・削除ができる

Cookieは参照と削除のみ

![resources2](http://img.skitch.com/20120310-1qqrifxfj1ebjpjibns9cdysu2.jpg)

----

# Networkパネル

----

## 各リソースの通信にかかった時間を確認

DNS Lookup,Blocking,Sending,Waiting,Receivingを確認できる

![network2](http://img.skitch.com/20120310-kietc1cmjbp68854g4g9rc12bf.jpg)

----

# Scriptsパネル

----

## 条件付きブレークポイント①

条件付きブレークポイントを設定できる

![scripts1](http://img.skitch.com/20120310-g15xpuc4puk8w4drbb8ss2a59x.jpg)

対象行で右クリックして、「Add Conditional BreakPoint...」を選択

----

## 条件付きブレークポイント②

条件を入力する

![scripts2](http://img.skitch.com/20120310-ch2wyus2xggwxmnwdixjq6r4gu.jpg)

----

## 変数の参照

ローカル、グローバル、クロージャ毎に変数が確認できる

![scripts3](http://img.skitch.com/20120310-g69chhnbeyqk927kibj7r6wysp.jpg)

----

## ファイルが選択しにくい①

Chrome Extensionsで使っているJSも表示されるので。

![scripts4](http://img.skitch.com/20120310-bjryi3an1sq1wm6n9w5epwxu1m.jpg)

----

## ファイルが選択しにくい②

2012/03/09時点のdev版（Chrome 19）では、ページのJSとextensionsのJSは別々のタブで表示できるようになっている！

![scripts5](http://img.skitch.com/20120310-xuyhxk1i3gyk6p3y6efx7tnhfq.jpg)

----

# オンライン編集

デモで説明します。

----

## ミニファイされたファイルの整形①

ミニファイされたファイルを･･･

![scripts6](http://img.skitch.com/20120310-f8qe29upbfand22844ewrwptup.jpg)

----

## ミニファイされたファイルの整形②

整形！

![scripts7](http://img.skitch.com/20120310-1p2cnyne5jwu9irhey3u86ucq8.jpg)

----

# Timelineパネル

----

## リソース読み込み〜レンダリングの解析

リソースの読み込みからJSの評価・実行、レンダリングをタイムラインで確認できる

青色がリソースの読み込み、黄色がJSの実行、紫がレンダリング

![timeline1](https://img.skitch.com/20120310-qg9csxefjwgr8a2xkhu52b2yfg.jpg)

----

## メモリの使用量の表示①

メモリの使用量もグラフで確認できる

![timeline2](http://img.skitch.com/20120310-trx8k8rihf7dc5uma3uhrx9c98.jpg)

----

## メモリの使用量の表示②

2012/03/09時点のdev版（Chrome 19）だと、Document,DOM,イベントリスナーの数も確認できる

![timeline3](http://img.skitch.com/20120310-hmei7fanxkxd9m7w2j36t6f97.jpg)

----

# Profilesパネル

----

## CPUのプロファイル

![profile1](http://img.skitch.com/20120310-thj1r2i387fwpy2qw3q2cd2fqt.jpg)

----

## CSSセレクタのプロファイル

使用しているセレクタとマッチ率とマッチ数が確認できる

2012/03/09時点のdev版（Chrome 19）のみ

![profile3](http://img.skitch.com/20120310-1dqnswfcw31mkqgget7bmaji1h.jpg)


----

# Auditsパネル

* ページのロード時間を短縮する手段を教えてくれる

（Y!Slowみたいなもの）

![audits1](http://img.skitch.com/20120310-ji6xyty61n96y3apaa8egjkc6y.jpg)

----

# Consoleパネル

----
## オートコンプリート

メソッドとかを補完してくれる

大文字・小文字はちゃんと書かないとダメ

マルチラインで書くとできない

![console1](http://img.skitch.com/20120310-pjmy1yptpej4uan4j84yhjj7cu.jpg)

----

# 設定

-----

## 設定

右下のアイコンクリックで、Chrome Developer Toolsの設定が表示される

![settings1](http://img.skitch.com/20120310-b1b3gkyyr4htqc4u9i2gjd9t2j.jpg)

----

## キャッシュの無効化

![settings2](http://img.skitch.com/20120310-ep59bdxkqbekqu2ai36smyiars.jpg)

----

## ユーザエージェントの変更

![settings3](http://img.skitch.com/20120310-uiaqhr13cc7tu7mx73hw5pxwi.jpg)
