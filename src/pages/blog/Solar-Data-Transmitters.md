---
templateKey: article-page
title: ソーラ・データ・トランスミッタ
slug: Solar-Data-Transmitters
date: 2020-07-01T22:00:00+09:00
cover: /img/STM431J-300x55.png
meta_title: Solar Data Transmitters
meta_description: >-
tags:
  - Solar
---
「TECHNO-FRONTIER 2017」（※１）という展示会を見に行ってきた。目当ては「エコパワーソリューション展」で、自社開発プロダクトのコミュニケーション・デバイスに搭載するバッテリーの代わりに、エナジーハーベスティングを搭載する事で、バッテリーレスによる小型化とメンテナンスフリーにできる何かを探しに行った。しかしながら、自分に吸収できる知識が足りないこともあるが、ソリューション展とは言うものの、エコパワーに対する解決方法がワイヤレス給電や研究成果の発表であり、求めているものとは違っていた。展示会最終日の昼過ぎのわりには混雑もなく、他の展示ブロックもゆっくり見て回ったところ、ローム社のブースで、電池不要無線通信モジュール(EnOcean製品)の展示が行われていた。聞けば、トランジスタ技術の増刊号で、EnOcean開発キットが付録についた書籍（※２）が創刊されているとのことで、展示会の収穫も乏しいままに会場を後にして、秋葉原の書泉で目的の書籍を購入し、不発に終わった展示会の隙間を埋めるべく電子部品通りへ向かった。ちょうど千石電商本店が引越しの最中で店内は人も商品も雑然としていて何がどこにあるのか分からず、一旦離脱して秋月電子通商へ避難しようとしたところ、電子部品通りには展示会の袋を肩から下げた方々が往来していた。皆さん不発に終わった展示会の隙間を埋めにきたのか、もしくは良いものを見つけてサンプルや周辺部品を買いに来られたのかもしれない。展示会では数軒先に店舗があるマルツエレックがオンライン通販サイトの展示を行っていたが、結局行き着く場所はココらしい。
展示会の袋が認知するきっかけとなり意識に変換されてしまうとコミュニケーションに発展する状況が形成される。きっかけがあまりにも乏しいので流石に声をかけるには至らなかったが、意識にはコミュニケーション・デバイスのインターフェースを形成する要素が含まれるのではないかと感じた。しかしながら、今のところデバイスに組み込むべき要素が何なのかは検討がついていない。

自社に戻り、先ほど購入した開発キット書籍の開封の儀を執り行う。先ずは太陽電池を搭載した温度データ送信機を取り出し、バネが付いていることに違和感を感じる。書籍の裏表紙を見ると、「植物を植えたプランタの温度センサ、土壌湿度センサ、照度センサのデータを伝送 
…」とある。なるほど。バネは土壌湿度を計測するセンサで、土に挿して固定するためにバネ状にしたのかと妙に納得してしまったのだが、書籍をめくると送信機のデータシートにアンテナ部品が記載されている。アンテナの名称は「ヘリカル・アンテナ」つまり、螺旋状のアンテナとのことで、危うく土に挿すところであったバネの正体はアンテナであった。2.4GHz帯のWi-Fi, 
Bluetooth, 
ZigBeeなどのアンテナを見慣れていたせいもあり、バネ状のアンテナがあることを知らなかった。無線技術者にとっては常識と思われるが、先入観を拠り所にした思い込みは致命的な結果を招くものの喩えとして「ヘリカル・アンテナ」を覚えておく。

※１）TECHNO-FRONTIER 2017 :
https://www.jma.or.jp/tf/ja/index.html

※２）電池レス無線マイコンEnOcean IoT開発キット
http://shop.cqpub.co.jp/hanbai/books/48/48041.html
