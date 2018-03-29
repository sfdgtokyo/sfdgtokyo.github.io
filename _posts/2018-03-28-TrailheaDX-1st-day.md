---
layout: post
title:  "TrailheaDX(1日目)(2018/03/28)"
date:   2018-03-28
image: 2018-03-28-tdx18-top.png
author: Takahiro Yonei
twitter: yonet77
---

<p class="intro"><span class="dropcap">T</span>railheaDXにお邪魔してます。米井です。こんにちは</p>
<br/>

## Opening Keynote

一応MVP用の席が用意されていたので、そこで聞かせて頂きました。

前半は何度も聞いてきた内容ですが、何度も繰り返し丁寧に説明してSalesforceのコトをじっくりと身体に染み込ませていくよ...！という具合でした。（脚色あり）

後半に新機能の発表などがありました。

### Integration Cloud
（おそらく）MuleSoft買収によって新たに創り出されたサービスで、他cloudとの連携を強化したものとか思います。

デモで確認できたのは

 1. データソースを選択して（現状は SalesCloud, ServiceCloud, CommerceCloud...）
 2. データマッピングを定義

というあたりで、データ連携が常に同期されるのか、連携した分でレコードの容量はさらに圧迫されるのか（多分圧迫されるでしょう）、データマッピングにカスタムロジック（数式とか）を入れられるのか...など色々と分からないことが多々ありますが、まぁ今後に期待しましょうと。

あとはETLをサービスとして提供しているパートナーにおかれましては、ゆくゆくどう迎え撃つのか、それとも仲良く手を取り合えるのか...今後のロードマップがやはり気になるあたりかと思いました。

MuleSoft自体は既に広く使われているサービスでブラウザ上で処理を定義したり、IDEを使って処理を定義したりすることもできるようです。そして、作った連携サービスをそのままクラウドデプロイする、と。
連携処理自体もバージョン管理できるようで、やはり完成度は非常に高いという印象でした。（お値段は知りません...）


### SalesforceDX
[Salesforce Pipelines with Heroku Flow](https://developer.salesforce.com/blogs/2018/03/salesforce-pipelines-with-heroku-flow.html)のようなデモをみれました。
herokuと連携したリポジトリ(githubとかbitbucketとか)でPRを作成すると、review appとしてScratchOrgが作成され、デプロイ＆heroku CIでのテストが実行される、というもので、salesforceでのアプリ開発をheroku pipelineに乗っけることができる...！と。

もちろん、これまでJenkinsやCircleCI,Travisなんかと既に開発フローが出来上がっているのであればすぐに移行する必要はないでしょうが、review appの機能はなかなか便利だと思うので、ゆくゆくは移行を検討しても良いかと思います。

ちなみに[salesforce-buildpack](https://github.com/heroku/salesforce-buildpack)の /bin/compile をザッとみてるとまだ要対応な箇所が残っているようです。こちらも今後に期待しましょうと。

その他、sfdxの機能強化ということで、プラグインの作成、メタデータの内容をより広く提供できる（依存関係をクエリ＆可視化したり）ようになるみたいでした。

## その他セッションなど

"ISVs Adopting Salesforce DX with Managed Packages"というセッションに出てみました。詳しいところまでは理解できずすみませんが、大きなアップデートはなかった...ように思えます。
ここに出てる図が概要で、番号の順にデモしていった、という具合でした。

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">sfdxを使って、パッケージングするとかの話の流れ。<br>※細かいところは抜けてるけど、大体こんな流れかと…<a href="https://twitter.com/hashtag/TDX18?src=hash&amp;ref_src=twsrc%5Etfw">#TDX18</a> <a href="https://t.co/UDg8lPgNhy">pic.twitter.com/UDg8lPgNhy</a></p>&mdash; yonet77 (@yonet77) <a href="https://twitter.com/yonet77/status/979153739427672066?ref_src=twsrc%5Etfw">2018年3月29日</a></blockquote>

もうsfdxコマンドでベータ版のパッケージを作って、他のScratchOrgにインストールして色々とテストしてみるとか、そんな流れがあるんですね。
ちなみに、リリース版のパッケージはsfdxコマンドから作成するところはまだですかね。

DCPも気になるあたりですが、ここでは特に触れられてませんでした。

## 所感

DevForestエリアは非常に広くて、色々な機能のブース(Heroku, DX, IntegrationCloud, CommunityCloud...etc)が出ており非常に賑やかでした。話によるとシアターの内容の方がよりDeepなTech系ネタが聞けるそうで、ちょっと失敗したな...と思いつつ初日を終えました。

それでは！

<img src="{{ '/assets/img/posts/2018-03-28-tdx18-niku.png' | prepend: site.baseurl }}" alt="肉の様子です。ご査収どうぞw" />

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
