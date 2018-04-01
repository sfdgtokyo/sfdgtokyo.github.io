---
layout: post
title:  "TrailheaDX(2日目)(2018/03/29)"
date:   2018-03-29
image: 2018-03-28-tdx18-top.png
author: Takahiro Yonei
twitter: yonet77
---

<p class="intro"><span class="dropcap">T</span>railheaDXにお邪魔した2日目です。米井です。こんにちは</p>
<br/>

## Keynote: The Future of Salesforce App Dev with Parker Harris & Friends

どんなフューチャーを魅せてくれるのか...とやや期待して参加してみたのですが、何か新しいフューチャーを、というよりもこれまで発表してきたモノを再構成して、改めてこんな未来になるよ、という話がメインだったかな、という印象でした。

（つまりは何か新しいモノは特になk...）

というわけで、いくつかスライドの写真など共有します。

<img src="{{ '/assets/img/posts/2018-03-29-with_Parker_01.jpeg' | prepend: site.baseurl }}" alt="history" />

これまで色んなものがあったよね、と。（いくつか見当たらないモノがあるような気がしますが、気にしてはいけません）

<img src="{{ '/assets/img/posts/2018-03-29-with_Parker_02.jpeg' | prepend: site.baseurl }}" alt="build apps summary" />

ここでいう"Build Apps Faster", "Build Smarter Apps"では、Dream House Appをデモしながら素早く、インテリジェントなアプリケーションを作る

"Build Apps Faster"では、主にLightning Component..特にLightning Flowを使ったサンプルを紹介してました。"Build Smarter Apps"では、Einsteinを組み込んだサンプル、特にPrediction Builderを使ったサンプルを紹介してました。

<img src="{{ '/assets/img/posts/2018-03-29-with_Parker_03.jpeg' | prepend: site.baseurl }}" alt="build apps together" />

変更セットによるシステム構築と、パッケージング(DCPのことでしょうかね)によるシステム構築を（ケンカしないで）共に進めていくための道しるべ的なモノなど。

<img src="{{ '/assets/img/posts/2018-03-29-with_Parker_04.jpeg' | prepend: site.baseurl }}" alt="new tools for building apps" />

また、それを支えるための新たなツールを紹介したり...と。

最後に示した"Build Apps Together"は、AdminとDevが共にシステムを創り、進化させていくには...というテーマの話だったと思います。このあたりについては、もっと別のところで色々と議論を深めていきたいですね。


## その他セッションなど

### "Architecting Unlocked Packages in Your Salesforce Org"

システムの規模が非常に大きく、複雑化した組織の中で、unlocked packageを使ってアーキテクチャをどう再構成していったか？という話だったと思います。

<img src="{{ '/assets/img/posts/2018-03-29-architecting_unlocked_packages_02.jpeg' | prepend: site.baseurl }}" alt="unlocked package" />

機能別に分類して、unlocked packageを利用することで、packageのモジュール化を図る、といった具合でしょうか。

<img src="{{ '/assets/img/posts/2018-03-29-architecting_unlocked_packages_03.jpeg' | prepend: site.baseurl }}" alt="benefit of unlocked package" />

依存関係の管理については、あまり深く理解できてなかったのですが、何かうまくできるようになるのでしょうか...？？

<img src="{{ '/assets/img/posts/2018-03-29-architecting_unlocked_packages_04.jpeg' | prepend: site.baseurl }}" alt="package dependencies" />

このセッションでの事例としては、["Apex Common"](https://github.com/financialforcedev/fflib-apex-common), ["Apex Mocks"](https://github.com/financialforcedev/fflib-apex-mocks)といったOSSのライブラリをベースにして、"mmlib", "common"という独自のベースパッケージを作成し、それらの上に"marketing", "matter"といった業務用のパッケージを構築していく、というアーキテクチャ構成をとったようです。

#### もう少し内部の話など

（以下、断片的な話ですみません）

<img src="{{ '/assets/img/posts/2018-03-29-architecting_unlocked_packages_05.jpeg' | prepend: site.baseurl }}" alt="name conventions" />

もう少し突っ込んだところでは、Apex Classの命名規則をきっちり管理しているようです。

<img src="{{ '/assets/img/posts/2018-03-29-architecting_unlocked_packages_06.jpeg' | prepend: site.baseurl }}" alt="breaking down std and custom sobjects" />

<img src="{{ '/assets/img/posts/2018-03-29-architecting_unlocked_packages_07.jpeg' | prepend: site.baseurl }}" alt="manage object field additions through DI" />

また、クエリする際には、各パッケージで利用するフィールドは最小限にして適宜追加できるようにと、カスタムメタデータをベースにしたDIの仕組みを構築しているようです。

<img src="{{ '/assets/img/posts/2018-03-29-architecting_unlocked_packages_08.jpeg' | prepend: site.baseurl }}" alt="inter package communication" />

その他、トリガに関しては、Platform EventをベースにしたDIの仕組みを構築しているようです。

ただ、上記のDIの仕組みについては、具体的なところはわからず...。そのうち、自分でも検討してみたいと思いました。

### "The Extracurricular: Why Dit That Do That?, Managing Application State w/ SPAs"

["Code Coverage"](https://www.codecoverage.org/)というPodcastを活動しているMatt Laceyさんがメインスピーカーで、そのほかDan ApplemanさんなどDev系のエキスパートな方々がパネリストとして参加するセッションでした。

途中、Reduxの概要にも触れながら、["Lighting-Redux"](https://github.com/madmax983/lightning-redux)を紹介しつつ([DF16でのセッション:Lightning Components and Redux](https://www.youtube.com/watch?v=94ZkxJX3w_0)も併せて参考に)、Salesforce上でSPAを作る上で実践的な内容を紹介していた...と思いますが、正直なところ僕の英語力では理解が追いつきませんでした。（そして時差ボケのせいか意識も時々失ってました）

## 所感

"TrailheaDX" というイベントとは何でしょうか？

僕自身、"Dev系のためのイベント"という認識が強かったのですが、今回に限って言えば、Dev系にフォーカスを当てる...というものでなかったように思えます。

振り返ると、このイベントは、"Trailblazer Community"を拡大することがメインテーマだったのではないでしょうか。

3日間の"BootCamp"では、みっちりとSalesforceのことを学んだり、2日間のセッションでは様々なワークショップがあったり、これからSalesforceのことを学んで、"Trailblazer"となることをサポートしている、という見方もできるのではないか？と思った次第でした。

新機能に関する発表が少なかったり、技術系に突っ込んだ内容のセッションが比較的少なかった（全部は見れてないので印象の話です）のは、残念なところもありますが、イベントの位置づけとしてはそこはメインではなかったのかな？と。（それにしても、"switch"の導入で拍手とはなんぞや？と思っt...）

やはり新機能などワクワクするような内容をイチ早く知りたかったら、"Dreamforce"に参加するのがベストでしょう、ということだと思います。

そして、こういったイベントに参加した後には必ずと言っていいほど「英語力を強化したい」と願いますが、今回もしっかりとそんな気持ちを抱くこととなりました。やはりブースで聞きたいことを質問して、コミュニケーション取れる程度の英語力があると、さらに有意義なものになると思いました...（遠い目

## GlobalGathering

そして最後に、4/25にはTrailheaDXの体験を全世界に広めるべく、["GlobalGathering"](https://www.meetup.com/ja-JP/Tokyo-Salesforce-Developer-Group/events/247044256/)というイベントがあります。

今回発表された新機能だったり、実際に参加した方々の熱い体験談をみなさんと共有したいと思います。どうぞお楽しみにー！


<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
