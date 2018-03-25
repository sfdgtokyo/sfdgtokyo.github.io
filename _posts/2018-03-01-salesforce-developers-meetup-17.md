---
layout: post
title:  "Salesforce Developers Meetup #17(2018/03/01)"
date:   2018-03-01
image: 2018-03-01-meetup.jpg
author: Akira Kuratani
twitter: a_kuratani
---

<p class="intro"><span class="dropcap">S</span>alesforce Developer Group Tokyo主催で2018年3月1日(木)に「<a href="https://www.meetup.com/ja-JP/Tokyo-Salesforce-Developer-Group/events/247136464/" target="\_blank">Salesforce Developers Meetup #17</a>」を開催しました。</p>

今回はいつもと会場を変えて、[株式会社ウフル](https://uhuru.co.jp/)のおしゃれなオフィスで開催しました。

# プログラム

Salesforce Spring'18がリリースされました。これまではリリースごとにリリースノート輪読を行っていましたが、セールスフォース・ドットコム社の岡本さんがリリース機能の説明をしっかりしてくれています。そのため、リリースノート輪読に代わって、今回は Spring'18 に関連するネタで LT してみることにしました

技術系セッションは、[アクセンチュア株式会社](https://www.accenture.com/jp-ja/new-applied-now)の小坂さんからオムニチャネルについて話していただきました。

## LT

### 山﨑さん : YACD(Yet Another Chatter Desktop)

[株式会社チームスピリット](https://www.teamspirit.co.jp)の[山﨑(@zaki___yama)](https://twitter.com/zaki___yama)さんから Summer'18 で廃止される Chatter Desktop の代替アプリを Electron で作ってみている話でした。認証周りで苦労していたが、Salesforce MVP の冨田さんの Qiita 記事がタイムリーに流れてきて、参考になったそうです。

そういえば、<a href="https://developer.salesforce.com/entries/771/show">Yaccl ~Yet Another Chatter CLient~</a> を思い出しました。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/nXhOatdCUXPHIK" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">Electron製Chatter Desktop、今日はまだ「使ってみて下さい！」と言えるところまでできなかったので、ご自由にStarだけしていってください（ゲス顔） <a href="https://t.co/baQPfuCQd8">https://t.co/baQPfuCQd8</a> <a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a></p>&mdash; Shingo Yamazaki (@zaki___yama) <a href="https://twitter.com/zaki___yama/status/969156536072196096?ref_src=twsrc%5Etfw">2018年3月1日</a></blockquote>
<br/>

### 横内さん : Lightning Design Systemのいろはと最近のアップデート

[株式会社チームスピリット](https://www.teamspirit.co.jp)の横内さんから Lightning Design System について話してもらいました。Salesforce 界隈以外でも言及されることが多い、とのこと。Spring'18 でも多くの機能追加を受けて、LDS も大量に変更があったようです。Lightning Experience 上で開発するときには、このあたりも気にしていく必要が出てきているので、今回のような発表はありがたいです。

<script async class="speakerdeck-embed" data-id="8f9e2f817ef541a4ac1fa1c0932fa7c9" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
<br/>

### 宮本さん : 新しいLightning ComponentとSalesforce Surveys

[アクセンチュア株式会社](https://www.accenture.com/jp-ja/new-applied-now)の[宮本(@takahito0508)](https://twitter.com/takahito0508)さんに Spring'18 で追加された新しい Lightning Component と Salesforce Surveys について話してもらいました。Salesforce Surveys は良さそうだなぁ、と思っていましたが、有償とのことでした。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/m5pxpkjuN89pYo" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">さっきの資料見なくてもいいように、リポジトリのURLを貼ります。<a href="https://t.co/cSyUWrYRyP">https://t.co/cSyUWrYRyP</a><a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a></p>&mdash; Takahito Miyamoto (@takahito0508) <a href="https://twitter.com/takahito0508/status/969165868545359873?ref_src=twsrc%5Etfw">2018年3月1日</a></blockquote>
<br/>

### 荻野さん : Visualforce帳票出力Tips

[株式会社ウフル](https://uhuru.co.jp/)の萩野さんからVisualforceからExcelを出力する方法について話してもらいました。画像の差し込み、罫線を引く、背景色やヘッダ／フッタを設定する、などいろいろできるようです。

LTの内容をまとめたQiita記事はこちらになります。<br/>
[VF帳票出力Tips Excel編](https://qiita.com/k-o/items/f095b6580b9686865a7a)

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">VFからExcel出力の方法を模索。ExcelBuilder.jsは残念ながらメンテ終了 <a href="https://t.co/yTlX11v4tM">https://t.co/yTlX11v4tM</a> <a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a></p>&mdash; Shingo Yamazaki (@zaki___yama) <a href="https://twitter.com/zaki___yama/status/969160537891196928?ref_src=twsrc%5Etfw">2018年3月1日</a></blockquote>
<br/>

### 川畑さん : Developer Controlled Packaging（DCP）を試してみた

[株式会社セールスフォース・ドットコム](https://www.salesforce.com/jp/)の[川畑(@tak4hir0)](https://twitter.com/tak4hir0)さんからDeveloper Controlled Packaging（DCP）を試してみて動かなかったことについて話してもらいました。日曜日まではできていたが、エラーのため動かなくなってしまったとのこと。うーん、残念。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/mLMFCFmITkOnGq" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>
<br/>

## 技術系セッション

### 小坂さん : オムニチャネルの今とこれから

[アクセンチュア株式会社](https://www.accenture.com/jp-ja/new-applied-now)の[小坂(@shunkosa)](https://twitter.com/shunkosa)さんからオムニチャネルについて話してもらいました。Service Cloud をやらないと触れることがあまりない CTI やルーティングの話など奥深い話を聴くことができました。[External Routing for Omni-Channel (Beta)](https://developer.salesforce.com/docs/atlas.en-us.omni_channel_dev.meta/omni_channel_dev/omnichannel_external_routing.htm)が新しい機能なんですね。

いやぁ、面白かった。

<script async class="speakerdeck-embed" data-id="3b00448afc7c49a384799912734f1711" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>
<br/>

# イベント参加ブログ

今回のイベントに関連するブログ記事はこちらです（ブログ投稿など追記しますのでご連絡ください）。

- [Salesforce Developers Meetup #17 LT登壇観戦レポート - TeamSpirit Developer Blog](http://teamspirit.hatenablog.com/entry/2018/03/12/144445)

# まとめ

開催中のツイートまとめは[こちら](https://togetter.com/li/1204384)です。
<br/>
今回は久しぶりにアンケートを取ってみました。参加者の実に 40% の方が RANGER ランクを獲得されていて、参加者の分布自体がかなり特異点な感じがします（汗）。

アンケートの結果を見ると満足されている割合が多いように感じました。前回からの比較などができないのでなんとも言えないところですが、今回の LT 中心にする試みが良い方向に影響を与えていればいいなぁ、と思いました。

Developer Group の皆さんと一緒に改善していければと考えていますので、ぜひフィードバックをよろしくお願いします！
<br/>

# 宣伝

直近予定されているイベントもありますので、ぜひご参加ください。

- 2018/3/10 [JAWS DAYS にサポーターとして参加](https://jawsdays2018.jaws-ug.jp/supporter/499/)
- 2018/3/15 [React-Lightningコードリーディングの会](https://www.meetup.com/ja-JP/Tokyo-Salesforce-Developer-Group/events/248247820/)
- 2018/4/25 [TrailheaDX 2018 Global Gatherings](https://www.meetup.com/ja-JP/Tokyo-Salesforce-Developer-Group/events/247044256/)
<br/>

# ギャラリー

<blockquote class="twitter-tweet" data-lang="ja"><p lang="en" dir="ltr">Salesforce Developers Meetup #17 <a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> <a href="https://t.co/M2jeeGNDcc">pic.twitter.com/M2jeeGNDcc</a></p>&mdash; Salesforce DG Tokyo (@SfdgTokyo) <a href="https://twitter.com/SfdgTokyo/status/969158883569643520?ref_src=twsrc%5Etfw">2018年3月1日</a></blockquote>

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">LT発表その1 <a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> <a href="https://t.co/AO0ptKGy79">pic.twitter.com/AO0ptKGy79</a></p>&mdash; Salesforce DG Tokyo (@SfdgTokyo) <a href="https://twitter.com/SfdgTokyo/status/969168228474695681?ref_src=twsrc%5Etfw">2018年3月1日</a></blockquote>

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">LT発表その2とTechセッション <a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> <a href="https://t.co/AiDqBlmfa8">pic.twitter.com/AiDqBlmfa8</a></p>&mdash; Salesforce DG Tokyo (@SfdgTokyo) <a href="https://twitter.com/SfdgTokyo/status/969168700396851200?ref_src=twsrc%5Etfw">2018年3月1日</a></blockquote>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
