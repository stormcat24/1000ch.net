---
layout: post
title: ハイパフォーマンスJavaScript 書評
date: 2015-01-24
---

# ハイパフォーマンスJavaScript 書評

昔買ったZakasの本を掘り当てたので読みなおした。

<blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="4" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:658px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAAGFBMVEUiIiI9PT0eHh4gIB4hIBkcHBwcHBwcHBydr+JQAAAACHRSTlMABA4YHyQsM5jtaMwAAADfSURBVDjL7ZVBEgMhCAQBAf//42xcNbpAqakcM0ftUmFAAIBE81IqBJdS3lS6zs3bIpB9WED3YYXFPmHRfT8sgyrCP1x8uEUxLMzNWElFOYCV6mHWWwMzdPEKHlhLw7NWJqkHc4uIZphavDzA2JPzUDsBZziNae2S6owH8xPmX8G7zzgKEOPUoYHvGz1TBCxMkd3kwNVbU0gKHkx+iZILf77IofhrY1nYFnB/lQPb79drWOyJVa/DAvg9B/rLB4cC+Nqgdz/TvBbBnr6GBReqn/nRmDgaQEej7WhonozjF+Y2I/fZou/qAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://instagram.com/p/yN2w5Shp7s/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_top">2年前に買った本を掘り当てたので読み返してみる</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by 1000ch (@1000ch) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-01-24T00:25:23+00:00">Jan 23, 2015 at 4:25pm PST</time></p></div></blockquote>
<script async defer src="//platform.instagram.com/en_US/embeds.js"></script>

## ハイパフォーマンスなJavaScriptとは

今やJavaScriptはブラウザに留まらないので、一口にハイパフォーマンスなJavaScriptを括るのは難しい。この本に関しては **Build Faster Web Application Interfaces** とあるようにブラウザ環境におけるJavaScriptにフォーカスしている。

ブラウザのJavaScriptと言っても、Webアプリケーションの形態も多種多様なので、最適化の形もケースバイケースとしか言えない。その最適化の選択肢を増やすための本と言える。

## Nicholas C. Zakas氏について

- [NCZOnline](http://www.nczonline.net/) Website
- [@slicknet](https://twitter.com/slicknet/) - Twitter
- [nzakas (Nicholas C. Zakas)](https://github.com/nzakas/) - GitHub

JavaScript界隈では有名な人なので、前のめりな人なら知っている人も多いと思う。Yahoo!のリードディベロッパーであり、YUIのコントリビュータも務めていた人。今は[Box](https://www.box.com/)で働いているそうで、最近はES6/ES7の仕様に口出ししたり、[ESLint](https://github.com/eslint)にコミットしてる様子。この本以外だと[メンテナブルJavaScript](http://www.amazon.co.jp/gp/product/4873116104/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&camp=247&creative=1211&creativeASIN=4873116104&linkCode=as2&tag=1000ch-22)が有名。

[ブログ](http://www.nczonline.net/blog/)も濃い記事ばかりなので、英語が苦手じゃなかったら読んでみて欲しい。英語が苦手でも読んでみて欲しい。

## ブラウザJavaScriptの最適化に向けて

前述の通り、いわゆるプログラムのアルゴリズム的な部分だけを取り扱っているわけではなく、JavaScriptでブラウザの描画をブロッキングしないためにであったり、効率の良いDOM操作といったような、 **ブラウザに仕事をしてもらう上でどういう最適化を行えば良いか** が書かれている。

### 目次

1. 読み込みと実行
2. データアクセス
3. DOMスクリプティング
4. アルゴリズムと処理の制御
5. 文字列と正規表現
6. 反応性のよいインターフェイス
7. Ajax
8. プログラミングの実践的手法
9. 高パフォーマンスなJavaScriptアプリケーションのビルドと配置
10. ツール

JavaScriptのMVCがどうとか、流行り廃りのあるライブラリや思想より、Webを作っていく上で大事で必要な知識だと思う。2011年刊行で、10章のツール部分は流石に古さがあるけど、駆け出したWebエンジニアが読むべき内容が詰まっている一冊。

<iframe src="http://rcm-fe.amazon-adsystem.com/e/cm?t=1000ch-22&o=9&p=8&l=as1&asins=487311490X&ref=qf_sp_asin_til&fc1=000000&IS2=1&lt1=_blank&m=amazon&lc1=0000FF&bc1=000000&bg1=FFFFFF&f=ifr" style="width:120px;height:240px;" scrolling="no" marginwidth="0" marginheight="0" frameborder="0"></iframe>
