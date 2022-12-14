# ディズニーAIナビ
- 画像をタップするとデモ動画が再生されます！
[![IMAGE ALT TEXT HERE](https://user-images.githubusercontent.com/68996392/197320591-7ea2510a-c4f1-4069-8e7c-4c7ba88a9a67.png)](https://youtu.be/CXY7Xw-7Lj0)

## 製品概要
<span style="font-weight:bold">テーマパーク(ディズニーランド) × Tech</span>


### 背景
コロナからの回復とともに、 テーマパーク需要も増えていく昨今では、久しぶりにテーマパーク(東京ディズニーリゾート)に行きたい！といった声も増えていると思います。

しかし、効率良い(待ち時間・歩く時間が少ない)回り方を考えるのは、慣れていない人だと難しいですよね？

そこで、私たちはディズニーランドに詳しくない人でも「完全攻略」(効率の良い回り方を見つけることが)できるアプリを作成しました！

### こんな人におすすめ
- ディズニーランドを効率的に楽しみたい！
    - できるだけ多くのアトラクションを楽しみたい人
    - 極力待ち時間を減らしたい人
    - 移動距離を少なく抑えたい人
- ディズニーランドの攻略法(回り方)に詳しくない人
- 事前に計画を立てたい人
- 遠方に住んでいる人

遠方に住んでいると、たまにしか行けないのでできるだけ多くのアトラクションを楽しみたいですよね！

そんな人へは特におすすめのアプリです！！

### 特長
⭐ ルート探索(組合せ最適化)×待ち時間予測(機械学習)を**両方とも私たち**が構築しました！
#### 🛣️ (1)おすすめルートを提案！

- 待ち時間・移動距離が少なくなるルートを探索
- ルート候補を複数表示(バリエーション豊富！)

#### 🎡 (2)待ち時間をアトラクションごとに予測！

- 1日あたり48点(**15分間隔**)の待ち時間予測
- 1日ごとに予測をアップデート

#### 💬 (3)ユーザーの要望に合わせた計画をカスタマイズ可能！

- 乗りたいアトラクションの選択
- 昼食・夕食・買い物時間を考慮し、それにあったルートを提案

### 製品説明（具体的な製品の説明）
ディズニー初心者でも簡単ルート計画を立てられるiOS,Androidアプリ

![image](https://user-images.githubusercontent.com/56294749/197316895-325fc7cc-ae5a-4c19-ab2f-8bd15b6f41ff.png)

- 希望のルートを選択します。出発時間の設定、休憩時間と買い物の時間の設定、乗りたいアトラクションの追加ができます!
- アトラクション検索の機能も実装。キーワード（アトラクション名、エリア名）を入力すると一致するアトラクションが即座に表示され追加することができます。

![image](https://user-images.githubusercontent.com/56294749/197316890-6f8cb24c-fe3d-437a-a81f-9f7f81527677.png)

- 計算結果を見やすくタイムライン形式で表示。トータル情報（プランの合計の時間、歩く時間の合計）、アトラクションの待ち時間等、様々なデータを確認し比較検証ができます。
- ルートを端末に保存が可能。サムネイル画像は初めに乗るアトラクションが選ばれます。

![image](https://user-images.githubusercontent.com/56294749/197316882-6d75bccf-443d-4975-a4a5-b28c03148e23.png)

- 保存したルートの一覧を確認することができます。サムネイル画像・ルート名を見やすく表示し、保存したルートを見つけやすいようなUIにしました。
- 保存したルートをタップすると、ルートの詳細を確認することができます。（今後、位置情報を活用してリアルタイムでルート案内をする機能の実装を計画中のため、案内開始ボタンが存在しています。）

![image](https://user-images.githubusercontent.com/56294749/197316880-6a36997a-0706-4813-a73a-05a9fec7f367.png)

- 使い方ガイドで簡単に機能の使い方、見方を確認することができます。
- こちらも、サムネイル画像と見出しを見やすくデザインして、簡単に探したい項目に辿り着けるようにしています。

#### なぜネイティブアプリ？
このアプリの使用を想定しているシーンとしては、パーク内や開園前にルートを確認したり、計画を立てたりする場面です。

そのため、スマホでの使用が多く想定されることからネイティブアプリで作成しました！


#### ルート提案(経路探索)
独自に予測した待ち時間データを元に、待ち時間・移動距離が少なくなるルートを提案します！
ここで提案されるルートは、予測した待ち時間だけでなく、アトラクション体験時間や移動時間も考慮して実装しているので、そのままパーク内で使うことができます！！


#### 待ち時間予測
東京ディズニーランド全37種のアトラクションの待ち時間をそれぞれ予測しました！！

実際に美女と野獣の(1番混雑度の高い)アトラクションについて予測してみた結果は以下の通りです！1日の混雑度推移の特徴を捉えることができていることがわかると思います！


##### 10/15の予測 (実際の過去データと比較)
<img src="https://user-images.githubusercontent.com/56294749/197298852-f60a4591-e28f-447e-8797-4e0264b30a72.png" />

<img src="https://user-images.githubusercontent.com/56294749/197318321-241a30d8-e666-4aa9-9a24-7980832c32e4.png" />

### 競合サービスとの差別化
今回実装した東京ディズニーランドの **「待ち時間予測」、「最適なルート提案」を行えるアプリはいずれもない** です。
その点で差別化は大きくできていると考えられますが、 本アプリの想定ユーザーが他に活用すると予想されるツールとの比較は以下の通りです。

- Tokyo Disney Resort App 【公式アプリ】
    - 入園日当日 リアルタイムでの待ち時間を表示
    - 当日にならないと待ち時間がわからないため、 事前計画が立てられない

- その他のアプリ
    - 待ち時間の表示や過去の待ち時間をグラフ化
    - 未来の待ち時間予測・ルート提案は存在しない

- ブログ , YouTubeなど
    - 1日のおすすめルートの提案
        - 一般論になってしまい、 行きたいアトラクションや最新の混雑度合いに対応することは困難
    - 混雑度予測
        - 1日ごとの大まかな予測はあるが、 その多くがルールベースをはじめとしたヒューリスティック

### 解決出来ること
本アプリを使うことで、 **ディズニーランドに詳しくない人でも**自分に合ったルートプランを作ることができます！！

ルートプランを練る際にネックとなる「待ち時間予測」や「回る順番」を考えることはもう必要なし！

必要なことは「**乗りたいアトラクション**」を入力するだけ！！

### 実現可能性
- 市場規模
    - 東京ディズニーリゾートの年間利用者数はコロナ前(2019年以前)では、約3000万人


### 今後の展望
追加機能としていくつか想定していたものがあるのですが、 Hack Dayまでに完成しきれていなかったものがありました。
あと少しで実装までたどりついていたものもあるので、展望として紹介します！！
- ディズニーシー版の作成
    - 現状、待ち時間予測と経路探索のプログラムまでは完成
    - 残り フロント・データベースの実装
- 待ち時間の予測をアプリ上に表示
    - 現状、待ち時間予測と予測データのデータベース管理までは完成
    - 残り フロントの実装
    - これができることで、今まで知ることができなかった未来の待ち時間情報をアプリで確認できるように！！
- リアルタイムでの予測・運用
    - パーク当日でも使えるような形での実装
    - リアルタイムでの待ち時間予測(1日1回の予測→数十分毎の予測)
    - 最新の混雑状況に対応したルート提案
- グリーティングの考慮
    - アトラクションのみではなく、キャラクターグリーティングも含めた上でのルート提案

### 注力したこと（こだわり等）
- ディズニーランドの知識を活用した特徴量生成(ディズニー知識×機械学習)
    - アトラクションごとに混雑が少ない時間帯が異なる     
        - 「美女と野獣」や「ベイマックス」のアトラクションは朝が一番混みやすいので行かないなど
    - 過去の経験・データを元に、定量的な評価指標による評価をするだけでなく、実際のルートの考え方と照らし合わせ定性的にも評価を行い開発を行った
    - 以下は実際に私が今年ディズニーランド全アトラクション+2つショーを回ったルートです！！
       
<img src="https://user-images.githubusercontent.com/56294749/197316449-e759d441-1b7a-42ac-9f46-693313e24362.png" width="300" /><img src="https://user-images.githubusercontent.com/56294749/197316490-3975e93a-0c5b-48b3-8b7e-afdb2d44aaaf.png" width="300" />

- デザイン・設計 ※ UI設計は開発期間以前に行いました。
    - 多くの事例を集め検証を繰り返しながら設計を行いました。一つの画面に対して、10以上のアートボードを作成し、何度もアップデートを行っています。
    - コンポーネント化を意識し、１週間という短い開発期間でも完成するような設計にしました。
    - flutterのクロスプラットフォームでの開発の特徴を考慮して、Apple社とDoogle社の推奨すデザイン規則を踏襲、融合してios、Andoridどちらの端末でも気持ちよく使用できるよう設計しています。
    
- フロントエンド開発
    - 自身で書いた設計書を見ながら、体力に物を言わせてゴリゴリ開発しました。
    - 1人での開発でしたが、チーム開発を意識して可能な限り可読性の高いコーディングを意識しました。
    - 
- インフラ整備
    - Serverless Frameworkを使用し、コストパフォーマンスが高く、拡張性に富んだサーバーレスアーキテクチャを実現しました。
    - 「毎日23時に翌日の待ち時間予測を行って結果をDBに格納するラムダ関数」と「フロントからリクエストがあった際に経路探索を行い、結果を返すラムダ関数」の2つを実装しました。
    - ローカル環境ではDockerコンテナ内で開発を行い、プロジェクトファイルを含むDockerイメージをLambda関数にデプロイするだけでアプリケーションを更新できる仕組みを作り上げました。
    - 開発ブランチがメインブランチにマージされた際に自動でデプロイが行われるようGitHub Actionsを構築しました。
        - テストが行われないままデプロイが行われてしまうのが現在の課題です。



## 開発技術
<img src="https://user-images.githubusercontent.com/68996392/197286388-f03457dd-320e-4f5c-94be-384e7affa990.png" />

### 活用した技術

#### フレームワーク・ライブラリ・モジュール
- フロントエンド
    - フレームワーク
        - Flutter
    - ライブラリ
        - geolocator
        - sqflite
    - DB
      - SQLite
- バックエンド
    - ランタイム
        - Python3.7
    - コンテナ
      - Docker
    - サーバー
      - AWS Lambda
      - Serverless Framework
    - DB
      - Amazon DynamoDB
    - 経路探索ライブラリ
        - jMetalPy
    - 機械学習ライブラリ
        - LightGBM
        - Optuna
- その他
  - GitHub Actions

#### デバイス
* iOS

### 独自技術
#### ハッカソンで開発した独自機能・技術
* 独自で開発したものの内容をこちらに記載してください
* 特に力を入れた部分をファイルリンク、またはcommit_idを記載してください。



##### ルート提案(経路探索)
- 組合せ最適化問題を進化戦略(進化計算の一手法)によって解く
    - 目的: 総所要時間と移動距離を最小化
    - 巡回セールスマン問題(TSP)の派生問題と考えることもできるが、 待ち時間が時間によって変動することを考慮する必要あるので難しい問題である
    - 進化計算ライブラリであるjMetalを用いて一般的な巡回セールスマン問題(TSP)を解くアルゴリズムを参考にして、 **待ち時間を考慮したアルゴリズムをハッカソン期間中に独自に開発**

##### 待ち時間予測
- 各アトラクションの待ち時間を予測
    - 機械学習手法として、LightGBMを用いて学習
    - **特徴量生成部分から全てハッカソン期間中に独自に開発**
    - 評価指標: 平均絶対値誤差
        - MAE: 10.0以下 (35/37アトラクション)
        - 5.0以下(20/37アトラクション)
 
    - 用いた主な特徴量は以下の通り
        - チケット価格
        - イベント(祝日・ハロウィン・イースターなど)
        - 1~7日前,2週間前,3週間前,4週間前の待ち時間
        - 曜日,チケット価格ごとの待ち時間　など



### メンバー紹介
#### 小島
- 担当: デザイン制作・UI設計、フロントエンド開発
- 得意技術: Vue.js

#### 竹味
- 担当: バックエンド開発(機械学習での待ち時間予測・進化計算でのルート探索)
- 得意技術: 機械学習(Kaggle), 進化計算(研究)

#### 刀祢
- 担当: インフラ整備、バックエンド開発(機械学習)
- 得意技術: サーバー整備、機械学習

