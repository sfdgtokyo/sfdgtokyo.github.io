---
layout: post
title:  "React-Lighning コードリーディングの会(2018/03/15)"
date:   2018-03-25
image: 2018-03-25-react-lightning-codereading.jpg
author: Akira Kuratani
twitter: a_kuratani
---

<p class="intro"><a href="https://www.meetup.com/ja-JP/Tokyo-Salesforce-Developer-Group/events/248247820/" target="\_blank"><span class="dropcap">R</span>eact-Lightning コードリーディングの会</a>を2018年3月15日に React-Lightning の作者である <a href="https://twitter.com/stomita" target="\_blank">@stomita</a> さんを招いて開催しました。</p>

## React-Lightning

React-Lightning とは、githubリポジトリの説明によると下記のとおりです。

<blockquote style="font-size: 100%; font-style: italic;">
React Lightning is a React custom renderer implementation targeted to Salesforce Lightning Component development. You can develop your own lightning component using accustomed React-style notation (e.g. JSX, ES6 classes, or SFC), embedding lightning built-in components or custom components as its content.
</blockquote>

引用元： [github.com/stomita/react-lightning](https://github.com/stomita/react-lightning)

## React-Lightning コードリーディング

コードリーディングでは、まず仕組みについて Qiita の記事を元に話してもらいました。

参照： [ReactのカスタムRendererを使ってLightningネイティブコンポーネントを開発する](https://qiita.com/stomita/items/88f7cfcf1b7261140c89)

最初は React の基礎的なところから始まり、React-Lightning を利用すると、どういったことができるのか、React Reconciler とは、Lightning Component 用にカスタマイズしている箇所などを説明してもらいました。

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">コードリーディングはじまった。以外にReactガチじゃない人が多いので、まずは Reactの基礎的なところから <a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a> <a href="https://t.co/NWhoL6CVgU">https://t.co/NWhoL6CVgU</a></p>&mdash; Mitsuhiro Okamoto (@mitsuhiro) <a href="https://twitter.com/mitsuhiro/status/974228989421105152?ref_src=twsrc%5Etfw">2018年3月15日</a></blockquote>

## React Reconciler

React Reconciler は ReactNative でも利用されており、かなり汎用化が進んでいる印象でした。個人的には、XML の SAX Parser に近い印象がありました。面白い応用としては CLI で ASCII アートのアニメーションを動かす際にも利用されているようです。

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">いや、面白かった。カスタムレンダラー熱浮上</p>&mdash; Shingo Yamazaki (@zaki___yama) <a href="https://twitter.com/zaki___yama/status/974271870777286656?ref_src=twsrc%5Etfw">2018年3月15日</a></blockquote>

## まとめ

マニアックな話をしながらのあっという間の2時間半でした。ありがとうございました。

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">React-Lightningコードリーディング面白かった。SalesforceをWebサーバというよりモバイルのような実機確認が必要なデバイスと捉えて<a href="https://t.co/0VbYNnHiN9">https://t.co/0VbYNnHiN9</a> 見たいな開発を考えるというのもかなり面白い <a href="https://t.co/PeyCldSx5r">https://t.co/PeyCldSx5r</a> <a href="https://twitter.com/hashtag/sfdg?src=hash&amp;ref_src=twsrc%5Etfw">#sfdg</a></p>&mdash; Mitsuhiro Okamoto (@mitsuhiro) <a href="https://twitter.com/mitsuhiro/status/974461936011116545?ref_src=twsrc%5Etfw">2018年3月16日</a></blockquote>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
