# ownCuration
自分のために情報を収集することを目的とする

重要視したいコンセプト
* とにかく自分が本当に欲しいものを作る
* 出来る限りシンプルにする

コンテンツとしたいこと
* 暗号通貨の各取引所のレート情報の収集
* 金融機関が公開するAPIを検出して可能な限り実行する

* Google Trend の急上昇ワードの収集

重要な感覚
* 何らかの金融取引に対して、少額でも自動化する仕組みを数多く作りたい
* ↑の仕組みを組み合わせることで、ポートフォリオを組んでリスクを減らして、安定的な収入に繋げたい
* これを自分のライフワークとすることが、仕事にも私生活にもバランスよく好影響をもたらすのではないかと何となく思っている

アイディア例
* 暗号通貨へのトラリピ
* 競馬のAI利用した予測と購入
* 暗号通貨のアービトラージ

# その他メモ
* スマホアプリ作成の経験値を積む
* Google Analyticks を利用する
* Firebase を利用する
* AWS を積極的に利用する
* IaC の経験値を積む

# 技術スタック
* フロントエンドは React 
* スマホアプリは Cordova
* サーバサイドは java8

# AWSメモ
・以下のURLにアクセス  
https://ap-northeast-1.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-1#Instances:sort=instanceType

・conn_test_1 に AWSコンソール から接続

・対象サーバに接続
　ssh -i .ssh/secondKey.pem ec2-user@172.31.19.47

2019/11/10
・conn_test_3 にすべてのデータを移動した。今後は、このサーバに接続すればOK。ほかのサーバは基本的に起動不要

# 進め方
* スマホアプリを最もプアな形でいいので作成して、自身のAndroidスマホにインストールする
 -> PCの制約上断念。。まずは Webサービス を作成して、ブラウザから確認する方式に転換する
* スマホアプリのコンテンツとして、何かしらのAPIを定期的にたたいて、照会する機能を作成する（react）
* Google Analytics, Firebase を を導入する
* 自分が時間空いたときにまず見るアプリとして、必要なコンテンツを揃えていく
* アプリにする際はMONACA使えるかも。試してみる

# 取引アプリ実行メモ
* コマンド
python zaifExecuter.py trade repeat_order STR_20170817

# 過去実施したことメモ
2019/10/23 以前作成した取引ツールはZaif限定。アービトラージツールも作りかけあり。現状整理からしなおしか。 
2019/11/05 ツールを動かしてみようとしたが、zaifAPIのライブラリの中でエラー。呼び出し方が変わったのかもしれない？
2019/11/10 取引ツールをlocalに持って帰ってきた

