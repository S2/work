# 職務経歴書  

### 音楽作成依頼/納品Webサービスのモック開発
    
#### 所属企業    
フリーランス
    
#### 期間    
2019年1月 ～ 2020年2月    
    
#### 職務内容    
音楽の作成依頼をサイトに登録された作曲者/歌手などを選択して依頼、管理画面ではその依頼を受けて、ユーザーに完了を通知する、といったシステムのモック作成を行っています。
モック、といってもシステム的には概ね動作をすることが要求され、実装がオミットされた機能は実際のクレジットカードなどでの決済機能などとなっております。
システム要件自体は最初決まっておらず、私の得意のRails/Reactで提案は行いましたが、先方企業様の技術スタック、及び先での技術投資を検討され、VueJS/Firebaseという組み合わせとなっております。

#### 開発環境    
言語,フレームワーク : JavaScript(TypeScript) , VueJS 
環境 : Firebase
    
#### 役割/メンバー    
エンジニア3名 (1名兼ディレクター)

エンジニアの一名の方はほぼディレクターとして、プロジェクトに参加しておられ、もう一名のエンジニアの方は途中から参加、及びフロントのページ/デザイン適用などを行っておられました。
私の担当としては、もう一名の方の作られたページへの、Firebaseとのデータ通信の実装などがメインとなっておりました。

Firebaseおよび、VueJSは私にとってこの案件がほぼ初のものとなっております。
VueJSについては、Reactを使ってきたこともあり、リアクティブプログラミングとしての大枠は共通しているものの、VueJSならではの、システムの大きさ、に最初戸惑いがありました。
Reactと比べ、VueJSは決め事、VueJSの作法が大きく、理解、記憶が進むまでは、やりたいことの実装方法を調べる、といったことに翻弄されておりました。
Firebaseについては、RDBMSに慣れ親しんだ身としては、大きく思考方法を考える必要があり、検索処理などの実装を通してFirebaseならではのテーブル定義、といったことを身に付けることができたかと思っております。

### コミュニティサイトのEC拡張、及びリファクタリングど
    
#### 所属企業    
フリーランス
    
#### 期間    
2019年9月 ～ 2020年1月    
    
#### 職務内容    
Railsで構築された、3D系イベントの運営サイトの修正、拡張を行っております。
もとからRailsでのシステムはあり、まずリファクタリングを簡単に行い、その上で拡張を行いました。
リファクタリングについては、テーブル定義類を手直ししています。外部キーの設定、テーブルと列名の名前修正などです。
拡張内容としては、3DCGコンテンツのマイページでのアップロードを可能にし、また、それらをネット経由で購入、ダウンロードを可能とする機能群の追加です。

#### 開発環境    
言語,フレームワーク : Ruby (Ruby on Rails) JavaScript(TypeScript) , ReactJS , 
環境 : AWS EC2(アプリケーションサーバ) , AWS RDS(MySQL) , AWS CloudFront/S3(Javascript、画像配信)  
    
#### 役割/メンバー    
エンジニア4名 デザイナー1名 ディレクター1名

開発に関しては元からサービスはあったので、後からのジョインとなっています。
ただRails、及びWebpackなどについての理解は私が進んでいたこともあり、全体的なリファクタリング、開発内容などについては、それなりに前に立って行ったという自負があります。

### 実在の商品のプロモーションサイト  
    
#### 所属企業    
フリーランス
    
#### 期間    
2019年5月 ～ 2019年8月    
    
#### 職務内容    
概ねの概要、要件を記述します。
商品には印刷されたプロモーションコードがついており、そのコードをサイトで登録することで、キャッシュバック、及び懸賞取得ゲームを行うことができます。
懸賞取得を行うゲームは、プロモーションコード一個に付き一回プレイが可能です。
懸賞取得のゲームはWebGLを用いた、3Dのゲームで、Andorid/iPhoneでプレイが可能となっています。
また、管理画面を作り、キャッシュバック登録や検証取得データは管理画面からダウンロードをすることによって、実際の発送作業をスムーズに行えるようにしております。

#### 開発環境    
言語,フレームワーク : Ruby (Ruby on Rails) JavaScript(TypeScript) , ReactJS , muicss , WebGL
環境 : AWS EC2(アプリケーションサーバ) , AWS RDS(MySQL) , AWS CloudFront/S3(Javascript、画像配信)  
    
#### 役割/メンバー    
エンジニア1名 デザイナー2名 ディレクター1名

本案件ですが、増税前の駆け込み需要に対応した形で、キャッシュバックプロモーションを打つ、ということで、Webシステム部分を担当しております。
プロジェクトとしては、各種広告類の制作、施策から始まり、それらを刈り取る形でWebシステムを構築しております。
このプロジェクトについての苦労話などですが、Webシステム全体設計としては、スタンダードなテーブル定義、API設計でやらせていただいております。
広告予算自体は大きいものの、実際の商品を購入した方からのキャッシュバック施策なので、全体的/瞬間的なユーザー数は大きくないこともあり、特に大きな工夫はありません。

反面、全体設計とは異なり、ゲームの開発は苦労をしております。
別案件ですこし触ってはいましたが、ほぼ初回の導入となる、WebGLでの3Dモデルを用いた3Dゲームということで、色々と勝手が違い大きく難航しました。
この案件では、3D空間での座標移動などスタンダードなものとは、また少し大変な物体の衝突判定など、学ばせていただきました。

### 大手アパレルサイトのモック開発
    
#### 所属企業    
フリーランス
    
#### 期間    
2019年1月 ～ 2019年7月    
    
#### 職務内容    
友人経由の企業様より依頼をいただきました。
3D系の実装を得意としておられる企業様より、大手アパレルサイトにて、3Dモデルを用いた着せ替えの実装を行う予定がある、ということで、Webページ、サーバなどの実装の依頼をいただきました。
3DCG系の企業様の依頼で、3Dの表示ライブラリ類はその企業様から提供いただき、Webページでの3Dモデルの表示/回転/着せ替えなどは私の方で実装をいたしました。

#### 開発環境    
言語,フレームワーク : Ruby (Ruby on Rails) JavaScript(TypeScript) , ReactJS , muicss , WebGL
環境 : AWS EC2(アプリケーションサーバ) , AWS RDS(MySQL)
    
#### 役割/メンバー    
エンジニア2名 ディレクター1名

エンジニア2名となっておりますのは、私と、クライアント企業のエンジニアの方が1名です。
そちらの方がWebGLの3Dライブラリを開発、私が、サーバ、 Webページ、3Dライブラリを使用しての表示などを担当しておりました。

  
## 職務経歴  
* 2018年2月〜 フリーランス  
* 2017年6月 株式会社クラベス  
* 2011年12月 wano株式会社   
* 2010年4月 株式会社eXnetcom   

## 保持スキル一覧
### 得意スキル
* システム要件整理、システム設計、見積  
まずシステム以前の点からの、ビジネス内での現状問題の把握、それらに対するコンピュータ、システムによる解決策の提示、およびその設計、金額提示など。

* サーバサイドアプリケーション構築  
データベースを併用し、各種データ登録処理、登録データからの時限処理構築など。  

* フロントエンドブラウザアプリケーション構築  
JavaScriptを用いてのインタラクティブなブラウザ内Webアプリケーションの構築など。  

* 監視/運用構築  
各種監視ソフトウェアを使用しての、サーバ死活管理、その他トラフィック管理、およびユーザーへの体感速度監視などをもとに、ユーザーへの快適性の提供、およびサーバの異常停止などの防止対応。

### 不得意スキル

* デザイン作成  
こちらは一切行うことができません。  
必要であれば、私のほうで当たることは可能ですが、できればこちらは用意いただきたいと思っております｡  

* デザインからのWebページ実装など  
存在するデザインを現実のWebページとして実装をする部分においては、それほど得意ではございません。  
実際上、一般的なデザイン/サイトにおいて実装に不都合があるレベルで不得意とは申しませんが、高度にユーザーへの使い勝手を訴求する画面などでは専門の方を立てる方向としたいと思っております。  

* 音声/画像/動画等の素材作成  
Webに根差した人間で、デザイン/ビジュアル寄りの人間であれば上記のいずれかは、行うものと思いますが、私のほうではこちらは対応出来兼ねます。  
必要であれば、私のほうで当たることは可能ですが、できればこちらは用意いただきたいと思っております｡  

## 過去職務内容    
  
### 家具共有集合住宅運営サイト  
    
#### 所属企業    
株式会社  クラベス  
    
#### 期間    
2018年3月 ～ 2018年6月    
    
#### 職務内容    
クライアントワークとして、作成しておりました。  
  
作成をしたサイトの内容としては  
  
* アパートの入居管理Webシステム  
* アパートごとに貸し出し可能家具、および貸し出し管理システム  
  
を行い、また、アパートの部屋紹介、貸出可能家具類の説明を行うサイトとなっております。  
  
#### 開発環境    
言語 : Ruby (Ruby on Rails) JavaScript(TypeScript)  
環境 : AWS EC2(アプリケーションサーバ) , AWS RDS(MySQL) , AWS CloudFront/S3(Javascript、画像配信)  
    
#### 役割/メンバー    
エンジニア4名 ディレクター1名  
諸般事情があり、途中からの参加となっております。  
その中で、アサイン当初からプロジェクトの遅延がありましたが、  
  
* プロジェクト内構築環境見直し  
* 要件見直し  
* デザイン実装見直し  
  
等のタスク整理を行い、スケジュールの巻き返しを行いリリースを行っております。  
また合わせて、監視/運用体制構築を行い、安定稼働を続けております。  
  
### アパレルECサイト構築  
    
#### 所属企業    
株式会社  クラベス  
    
#### 期間    
2017年12月 ～ 2018年3月    
    
#### 職務内容    
クライアントワークとして、作成しておりました。  
作成をしたサイトの詳細としては  
  
* オープンソースソフトウェアMagentoを使ってのECサイト構築  
* 特異なデザインのアパレルブランドに合わせ、現代的なデザインでのサイト構築  
* API,キャッシュサーバを用いての高レスポンス性  
を目指して実装しております。  
  
  
#### 開発環境    
言語 : PHP (Magento2) JavaScript(TypeScript)  
環境 : AWS EC2(アプリケーションサーバ) AWS RDS(MySQL) , AWS CloudFront/S3(ページHTML、Javascript、画像配信)  
    
#### 役割/メンバー    
エンジニア1名 ディレクター1名  
要件定義、金額見積、AWS内利用機能等選定、構築、監視/運用体制構築  
  
### 家系図表示アプリケーション  
    
#### 所属企業    
株式会社  クラベス  
    
#### 期間    
2017年9月 ～ 2017年11月    
    
#### 職務内容    
クライアントワークとして、作成しておりました。  
おおむね作成した機能としては  
  
* 管理画面によって、家系内の登場人物を設定  
* 家系内の人物同士の関係性を入力  
    * 婚姻関係  
    * 親子・兄弟関係  
* 入力をした関係性をもとに家系図を作成  
といった内容です。    
  
リリース状態の話があり詳細は開示が不可能となりますが、開発時コンセプトとしては  
  
* 大きなトラフィック、大きな動的性がないことを念頭に、サーバを作成せずに、APIのみでの構築を行い、ランニングコストの最小化  
* 開発においての多様性を排し、API、管理画面、家系図表示処理内において、JavaScriptのみの環境を採用  
* サーバを排し、ファイル配信、API通信等をクラウド提供処理のみとし、耐障害性を高める  
  
といった点に重点を置いています。  
  
#### 開発環境    
言語 : JavaScript(TypeScript)  
環境 : AWS RDS , AWS CloudFront , AWS Lambda , AWS API Gateway  
    
#### 役割/メンバー    
エンジニア1名  
要件定義、金額見積、AWS内利用機能等選定、構築  
  
### 動画広告配信プラットフォーム    
  
#### 所属企業  
Wano株式会社  
  
#### 期間  
2012年4月 ～ 2017年6月  
  
#### 職務内容  
動画での広告配信のシステム構築、及びスマホ、PC向けの動画プレーヤーの開発を担当。  
担当業務は、メインのアーキテクトを担当しております。設計、開発の詳細としては  
① テーブル設計  
② サーバ設計、クラウド選定  
サーバ群はほぼAWS上で構築しております。  
内訳としては、  
1.管理画面サーバ(AWS EC2)  
2.Webサーバ(AWS EC2)  
3.MySQLデータベースサーバ(AWS RDS)  
4.Redisキャッシュサーバ(AWS Elasticache)  
③ 広告管理、配信先メディア管理、レポート等の管理画面を、Perlにて実装。  
④ ③での設定内容のバッチ処理類をPerlにて実装。  
⑤ 広告配信サーバの構築  
エンドユーザがアクセスする処理については、応答速度が要求されるため、PerlではなくNginxにLua、mrubyを組み込み、DBにRedisを使用することで高速な応答を実現。  
フロントでの動画プレーヤーはベースになる物を、別途開発(下記Githubを参照)、これをベースに広告向けにカスタマイズした物を作成して使用。  

https://github.com/S2/TS-movieplayer

⑥ 動画プレーヤーをTypeScriptにて実装  
⑦ AWS Lambda内でのレポート作成処理等をClojureにて実装  
⑧ ログ解析のためにBigQueryへのデータ送信構築。  
⑨ Zabbixを使用しての監視システム構築  
  
#### 開発環境  
言語 : Perl Lua mruby TypeScript Clojure Zabbix  
環境 : Ubuntu Linux , AWS各種サービス , GoogleBigQuery   
ミドルウェア : nginx MySQL Redis fluentd   
  
#### 役割/メンバー  
退社当時営業4名エンジニア2名/開発リーダー担当  

### スマホ向けクイズゲームバックエンド開発  
  
#### 所属企業  
Wano株式会社  
  
#### 期間  
2011年11月 ～ 2012年3月  
  
#### 職務内容  
他社でのスマホ向けのクイズゲーム開発のバックエンドを担当。  
1時間あたりの10万ユーザーに耐える構造での設計、構築が要件。  
内容としては  
① データベース設計  
② クイズ配信処理をPerlにて実装  
③ 配信するクイズ設定、ユーザー管理等を行う管理画面を実装  
④ サーバ構築  
⑤ スマホゲーム本体との通信ライブラリ構築(Android)  
⑥ Zabbixを用いての監視システムを構築  
  
#### 開発環境  
言語 : Perl JavaScript(TypeScript)  
環境 : Ubuntu Linux   
ミドルウェア : MySQL nginx memcached fluentd Zabbix  
  
#### 役割/メンバー  
開発、サーバ構築、仕様書作成、受託元との折衝を担当、他上長が1名  

### テレビ時刻表Androidアプリ開発  
  
#### 所属企業  
株式会社eXnetcom  
  
#### 期間  
2011年1月 ～ 2011年5月  
  
#### 職務内容  
Android2.1 , 2,2 , 2,3をターゲットとした、Androidアプリ開発を行いました。  
自分はフロントアプリケーションを担当、同社の人間がバックエンドを担当  
主にJSON APIを用いてのテレビ時刻表の表示、リコメンド、ブックマーク機能、通知等を実装。  
また同時期に進行していた協業他社にて作成したiOSアプリの監修も担当。  
  
#### 開発環境  
言語 : Android Java   
環境 : Android (2.1 2.2 2.3)  
  
#### 役割/メンバー  
エンジニア2名営業1名/Androidアプリ開発担当  
iOS開発監修  
  

