---
layout: post
title:  "Salesforce Developers Meetup #21 開催レポート(2019/08/23)"
date:   2019-08-23
author: Shun Kosaka
twitter: shunkosa
---

<p class="intro"><span class="dropcap">S</span>alesforce Developer Group Tokyo主催で2019年08月23日(金)に「<a href="https://trailblazercommunitygroups.com/events/details/salesforce-tokyo-jp-developers-group-presents-salesforce-developers-meetup-21/" target="\_blank">Salesforce Developers Meetup #21</a>」をセールスフォース・ドットコム社で開催しました。</p>

## セッション

Summer '19 でリリースされた新機能を中心に、開発者向けのお話を幅広く伺うことができました。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">salesforce developer group tokyo meetup #21 !!<a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> <a href="https://t.co/ll9rrCfTbT">pic.twitter.com/ll9rrCfTbT</a></p>&mdash; Ryosuke Kobayashi (@ryosuke921186) <a href="https://twitter.com/ryosuke921186/status/1164844685086511104?ref_src=twsrc%5Etfw">August 23, 2019</a></blockquote>
<br/>

#### [川畑 (@tak4hir0)](https://twitter.com/tak4hir0) さん：Apex での項目レベルセキュリティの適用(パイロット)を試しててみた

セールスフォース・ドットコムの川畑さんより、`Security.stripInaccessible()` の紹介とデモ。Apex でレコードレベルのセキュリティを扱うのは比較的シンプルですが、項目レベルのセキュリティを扱うのはなかなか複雑でした。Summer '19 でパイロットとなった `Security.stripInaccessible()` はその名の通り、アクセスできない項目を取り除いてくれるメソッドです。Spring '19 からベータとなったSOQL の`WITH SECURITY_ENFORCED` と組み合わせることで、この領域の実装がシンプルになりますね。

リリースノート : [Apex での項目レベルセキュリティの適用 (パイロット)](https://releasenotes.docs.salesforce.com/ja-jp/summer19/release-notes/rn_apex_Security_stripInaccessible.htm)

登壇資料 : 
<script async class="speakerdeck-embed" data-id="fce4af00c43b49dda4205339f0319f5f" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>


<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> Apexの項目を除外するのやつ、便利だなあ</p>&mdash; Takahito Miyamoto (@takahito0508) <a href="https://twitter.com/takahito0508/status/1164843180245671936?ref_src=twsrc%5Etfw">August 23, 2019</a></blockquote>
<br/>

#### [田中 (@hrk623)](https://twitter.com/hrk623) さん：LWC オープンソースの紹介

セールスフォース・ドットコムの田中さんより、オープンソース版のLWC の紹介と`lwc-create-app` コマンドのデモ。オープンソース化されたLWCは、Lightning Platform のLWC のうちコアな部分です。Salesforce で開発をしていると、ついついLightning Platform 上での活用ばかりに気を取られてしまいがちですが、JavaScript フレームワークとしてのLWC の今後にも目が離せません。RFC は[こちらのリポジトリ](https://github.com/salesforce/lwc-rfcs) から確認できます。

登壇資料へのリンク (※要Trailblazer Community ログイン) : [https://success.salesforce.com/0D53A00004Y27dJ](https://success.salesforce.com/0D53A00004Y27dJ) 

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a><br>試してみたい <a href="https://t.co/535Mc8Jiir">pic.twitter.com/535Mc8Jiir</a></p>&mdash; dakudo036 (@dakudo036) <a href="https://twitter.com/dakudo036/status/1164845742839619584?ref_src=twsrc%5Etfw">August 23, 2019</a></blockquote>
<br/>

#### 長谷川さん： Solr を使った Salesforce に対するディープサーチ

ベイシスの長谷川さんより、[KonaSearch](https://appexchangejp.salesforce.com/appxListingDetail?listingId=a0N3A00000FeG81UAF)のご紹介とアーキテクチャの概説。自社サービスとして検索インデックスを抱えており、Org を跨いだ検索もできるようで大変興味深かったです。Saleforceの標準機能でも統合検索がありますが、より規模の大きな、または、様々な統合をターゲットにされているのかなという印象を持ちました。

登壇資料 : 
<iframe src="//www.slideshare.net/slideshow/embed_code/key/8xwz7cBXUmUe2U" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/junichih/solr-salesforce" title="Solr と自然言語処理によるSalesforce のディープサーチ" target="_blank">Solr と自然言語処理によるSalesforce のディープサーチ</a> </strong> from <strong><a href="https://www.slideshare.net/junichih" target="_blank">Junichi Hasegawa</a></strong> </div>
<br/>

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">日本語検索は鬼門<a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> <a href="https://t.co/ABXRMy50Ku">pic.twitter.com/ABXRMy50Ku</a></p>&mdash; Ryosuke Kobayashi (@ryosuke921186) <a href="https://twitter.com/ryosuke921186/status/1164850318145798144?ref_src=twsrc%5Etfw">August 23, 2019</a></blockquote>
<br/>

#### [畑本 (@Surounin)](https://twitter.com/Surounin) さん：変更データキャプチャについて

USE の畑本さんから、変更データキャプチャと非同期Apex トリガの概説。個人的には、外部システム連携としての変更データキャプチャは、項目が可変であることやプラットフォームイベントがコミット後に利用できるようになったことから、正直あまり活用イメージが湧きませんが、簡易に設定ができるのはとても良いですね。

非同期のApex トリガに移せるロジックは意外とありそうです。重たくなっているトリガは見直してみると良いかもしれませんね。

リリースノート : [Apex トリガでの変更イベントメッセージの処理](https://releasenotes.docs.salesforce.com/ja-jp/summer19/release-notes/rn_change_event_triggers.htm)

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">変更データキャプチャは、オブジェクトごとにオンオフしたら、オブジェクトごとに対応するオブジェクトに REST でアクセスすれは変更された項目情報がすべて取得できる。MuleSoft で取得するデモ。</p>&mdash; とよてぃ (@toyoty99) <a href="https://twitter.com/toyoty99/status/1164853905819176960?ref_src=twsrc%5Etfw">August 23, 2019</a></blockquote>
<br/>

#### [小坂 (@shunkosa)](https://twitter.com/shunkosa)：LWC でチャットのUIをカスタマイズしよう

私からはLWC でチャットのメッセージをカスタマイズする方法を紹介しました。今時のチャットはテキスト以外のコンテンツは当たり前ではありますが…、ようやくSalesforce のWeb チャットでもこれを実現できるようになりました。ボットの設定で典型的なUI コンポーネントが選べるようになるとなお良いですね！

リリースノート : [Lightning Web コンポーネントを使用したチャットメッセージのカスタマイズ](https://releasenotes.docs.salesforce.com/ja-jp/summer19/release-notes/rn_embedded_service_web_lwc.htm)

登壇資料 : 
<script async class="speakerdeck-embed" data-id="d5a83e852836423b98bb0ac2f28d7001" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>
<br/>

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">やりたい！！！！<a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> <a href="https://t.co/yoMshfeMyv">pic.twitter.com/yoMshfeMyv</a></p>&mdash; おにぎり🍙 (@onigiri36721865) <a href="https://twitter.com/onigiri36721865/status/1164856972920815616?ref_src=twsrc%5Etfw">August 23, 2019</a></blockquote>
<br />

#### [石井 (@ishiid)](https://twitter.com/ishiid) さん：機械学習関連の論文について

Jenio の石井さんより、機械学習領域でホットな論文、提供中のサービスや、API エコシステムなど様々なトピックでお話しいただきました。Chief Scientist のRichard Socher さんは9月のWorld Tour Tokyoで来日されますね。Don't miss it!

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">今日最後に登壇されてた石井さん主催のコミュニティ。<br>動画も配信されてるみたいなので帰りの電車で見ながら帰る<a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a><a href="https://t.co/6OGc2LgXQI">https://t.co/6OGc2LgXQI</a></p>&mdash; ちきすけ (@chksk__c) <a href="https://twitter.com/chksk__c/status/1164883319059668993?ref_src=twsrc%5Etfw">August 23, 2019</a></blockquote>
<br/>

## おわりに

今回のセッションでは、Salesforce の新機能に加えて、自然言語処理や機械学習等のテクノロジーについても幅広く知見を得ることができ、とても充実した会であったと思います。登壇者の皆様、ありがとうございました。次回は Winter '20 リリースのMeetup かDreamforce のGlobal Gathering でしょうか。お楽しみに！
<br/>

## ギャラリー

懇親会ではSWAG 争奪じゃんけん大会もあり大変盛り上がりました！
<br/>

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">そろそろネットワーキング！ <a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> <a href="https://t.co/eRKKuo1qN9">pic.twitter.com/eRKKuo1qN9</a></p>&mdash; Takahito Miyamoto (@takahito0508) <a href="https://twitter.com/takahito0508/status/1164861016674451456?ref_src=twsrc%5Etfw">August 23, 2019</a></blockquote>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
