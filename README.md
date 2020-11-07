# ついでGuys

[![IMAGE ALT TEXT HERE](https://jphacks.com/wp-content/uploads/2020/09/JPHACKS2020_ogp.jpg)](https://www.youtube.com/watch?v=G5rULR53uMk)

## 製品概要
買い物をしている友人や家族に「ついで買い」を頼む

### 背景(製品開発のきっかけ、課題等）
コロナ社会で、できれば外出を避けたいという世の中の流れがあります。
またそれ故に友達と会う機会は減少してしまっています。
私たちは、ついで買いのしやすい環境を整えることで、"外出の抑制"と"何気ない（わざわざ連絡して会う程でもない）コミュニケーションの機会"を増やします。
位置情報サービスとWebソケットを利用してリアルタイムにリクエストを飛ばすことでこれらの機能を実装します。

### 製品説明（具体的な製品の説明）
#### ついで買いを頼む人
フレンドがスーパーマーケット等にいることを確認でき、チャットで頼むことができる。

#### ついで買いをする人
スーパーマーケット等にいるときに、フレンドからチャットでついで買いをお願いされる。

## 機能
### ユーザ
|新規登録|ログイン|
|---|---|
|![新規登録](assets/SingUp.png)|![ログイン](assets/Login.png)|

### HOMEページ
|フレンドが買い物スポットにいるとき|自分が買い物ポイントにいるとき|自分の位置を非公開にしたとき|位置を公開、非公開にできる|
|---|---|---|---|
|![](assets/HOME(通知が来てる時).png)|![](assets/HOME(場所の登録がある時・買い物してる時)Home%20(1).png)|![](assets/HOME(場所の登録がある時・非公開の時).png)|![](assets/LocationStatus(公開設定).png)|

### スポット登録ページ
|スポットを「＋」で登録できる|特定の場所を新規で登録できる|
|---|---|
|![](assets/LocationAdd(押した).png)|![](assets/LocationRegister(特定の場所を検索？？).png)|

### チャットページ
|フレンド一覧画面|フレンドとチャットできる|
|---|---|
|![](assets/場所にいる時？&通知来た時.png)|![](assets/ChatRoom.png)|


### 解決出来ること
- コロナ禍で不必要な外出を避けることができる(このアプリケーションが広まれば外出する人が減る)
- コロナ禍で友人との会話を増やすことができる
### 今後の展望
- ネットマネーや暗号通貨等と紐付けし、このアプリケーションのみで完結させたい
- 
### 注力したこと（こだわり等）
* 親しみやすいデザイン
* 

## 開発技術
### 活用した技術
#### API・データ
* JS(位置情報取得) 
* 

#### フレームワーク・ライブラリ・モジュール
* React(TypeScript)
* FireBass

#### デバイス
* スマートフォン(位置情報を公開)

### 独自技術
#### ハッカソンで開発した独自機能・技術
* 独自で開発したものの内容をこちらに記載してください
* 特に力を入れた部分をファイルリンク、またはcommit_idを記載してください。

## セットアップ

#### ①ファイルの場所を移動
```
cd react
```

#### ②package.json に書かれているライブラリを一括で読み込む

```
npm install
```

#### ライブラリのインストール

```
npm install ライブラリー名
```

#### ③ローカルでテストサーバーを立ち上げる

```
npm run start
```

#### ③ローカルでテストサーバーを立ち上げる(サブ)

```
npm run start:dev
```
