---
title: '[Unity入門] 1. Unity Editorのインストールをしよう'
tags:
  - 'Unity'
  - '初心者'
  - 'ゲークリ'
private: false
updated_at: ''
id: null
organization_url_name: null
slide: false
ignorePublish: false
---
# はじめに
こんにちは、rinngo です！

この記事では、Unityをこれから始めたい、ゲームをつくってみたいという方向けにUnityのインストール方法をまとめたものです。

また、これは私が所属している[徳島大学ゲームクリエイトプロジェクト](https://qiita.com/organizations/tugc)の勉強会で使用するものです。
興味がありましたら、[Unityroom](https://unityroom.com/users/tugamecreate)と[X公式アカウント](https://x.com/tugameproject)なども見に行ってください！

# この記事の目標
- [x] **Unity** について知る
- [x] 開発環境を整える
- [x] **Cube** を置いてみる

# ゲームをつくるには？
ゲームをつくるといっても、どのようなツールを使うのか、どうやってつくるのかなど選択肢はたくさんあります。

この記事では **Unity** というツールを使ってゲームをつくることを想定して、その最初の一歩であるインストール手順をまとめます。

## Unityとは？
先ほどから **Unity** という単語を出していますが、これはどんなツールでしょうか？

**Unity** とは　**ゲームエンジン** と呼ばれるツールの１つで、これを使えば簡単なゲームから本格的なゲームまでつくることができます。
他にも、同じゲームエンジンでは **Unreal Engine** というツールが有名ですね。

https://unity.com/ja

# Unityのインストール
Unityを使うためには2つのツールをインストールします。
- Unity Hub
- Unity Editor

それぞれ順番にインストールしていきましょう！

::: note info
- Unity Hub: プロジェクトやUnity Editorを管理する
- Unity Editor: ゲームを開発する
:::

## Unity Hub のインストール
まずは「`Unity`」と検索してみましょう。
すると、Unityの公式サイト(`https://unity.com`)が出てくると思いますのでそこにアクセスしてみましょう！

https://unity.com/ja

アクセスできたら、下の画像のように **「ダウンロード」** のボタンをクリックしましょう。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/0c59250e-240a-4f45-8af2-e3a3e8106501.png)

次に下の画像のボタンを押してください。
今回はmacOSを使っているため「MAC用ダウンロード ARM64」になっていますが、Windowsでアクセスすると自動でWindows用に切り替わると思うのでそのままボタンを押してください。

![スクリーンショット 2026-02-19 12.05.13.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/b9e37ed1-4aa2-4045-9b89-b23d0027c7dc.png)

すると、Unity Hubのインストールをするためのインストーラがダウンロードされるので、それを実行してインストールをしてください。

## Unity IDアカウントの作成
Unity Hub を起動してみましょう。

Unityを使うには、ライセンスがいるためアカウントを作成しましょう。
基本、学生や個人制作くらいでしたら無料で使えます。

それでは **「アカウントを作成」** ボタンを押してください。

![スクリーンショット 2026-02-19 21.29.03.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/05652346-062e-48a9-8720-234745271b81.png)

それでは自分のメールアドレスやApple ID, Googleアカウントなどでアカウントを作成しましょう。
メールアドレスでもいいですが、できるだけApple IDやGoogleアカウントなどに連携すると便利だと思います。

![スクリーンショット 2026-02-19 21.34.43.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/d48fc2f0-768d-4887-b725-23fcb94f88ac.png)

アカウントの作成ができたら、下の画像のようにUnity Hubを自動で起動するようにアラートが出るのでそのままUnity Hubを起動しましょう。
するとそのままアカウントにサインインできると思います。

![スクリーンショット 2026-02-19 21.36.10.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/df355155-e609-4236-877d-02a70b39bc51.png)

## 言語設定を日本語にする
おそらく、最初は英語になっていると思いますので日本語に変えましょう。

左下の **「Settings」** をクリックしてください。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/2da51048-ac90-4ce3-b1a9-cc7d51df9718.png)

次に左の **「Appearance」** を押してください。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/4ebc5191-3f31-4606-bf97-be4a36d21a33.png)

そして、 **「Language」** という項目があるのでそれを「English」から「日本語」に変更してください。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/0c6986c7-8961-410a-a452-e1fe025174bd.png)

これで日本語に設定できたと思います。

## Unity Editor をインストールする
先ほどインストールしてもらった **Unity Hub** はゲームをつくるためのツールというより、プロジェクトやゲームをつくるためのツールである **Unity Editor** を管理するためのものです。
ですので、今からこれを使って **Unity Editor** をインストールしてみましょう。

まずは、左の項目から **「インストール」** をクリックしてください。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/2a985676-ae2d-47b5-b95e-f82020f0a6e0.png)

この画面では複数のバージョンのUnity Editorを管理することができます。
複数のプロジェクトを扱うとき、それぞれUnity Editorのバージョンが違う可能性があるのでこの画面で管理をすることが多いです。

では、 **「エディターをインストール」** のボタンをクリックしてください。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/561d5447-4dc3-4038-8a39-def2f0a2b396.png)

この画面ではインストールするバージョンを選択します。
新しい方がいいというのは皆さんもお分かりだとは思いますが、実は新しすぎるのもよくありません。
なぜなら、新しすぎるものはバグなどの不具合が隠れていることが多く安定していないかもしれないからです。

そこで、この画面では **「推奨」** と書かれたものがありますよね。これを基本は使うといいと思います。
また、もう一つの指標として **LTS** と書かれたものがいいです。LTSとついているものは基本的に安定しているバージョンであるため、もし「推奨」がなくてもこれを選んでおくと間違いはありません。
<details>
<summary> LTSとは？ </summary>
LTSとは、「Long Term Support」の略称のことです。
英語のとおり長期的にサポートをするという意味で、これがついているバージョンは基本的に2年間、バグが見つかっても修正し続けてくれるバージョンです。<br>
そして、この期間が切れる前に新しいLTSのバージョンが公開されるので、それに乗り換えると常に安定したバージョンを使い続けることができます。
</details>

では、とりあえず画像のように **「インストール」** をクリックしましょう。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/19ab1445-d084-4305-88a3-901439e41a65.png)

次の画面では追加でなにをインストールするかを決めることができます。

今回は、 **全てのチェックマークをつけないでください。**
あとで必要なものはインストールしましょう。

チェックマークを外し終えたら、 **「インストール」** ボタンを押してください。

![スクリーンショット 2026-02-19 23.18.18.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/8deaabdd-ba92-48ff-b12e-2efd49ff5cda.png)

それではしばらく時間がかかりますので気長に待ちましょう。

インストールが完了すれば、下の画面のようにインストールしたUnity Editorが表示されると思います。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/28ee7eff-5db7-4ca9-8446-18532cbd2425.png)

これで完了です！

## プロジェクトの作成
それでは早速プロジェクトの作成をしていきましょう！

左の **「プロジェクト」** を押してください。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/f90e9f72-aa37-46e1-8c81-7280fc8d922d.png)

それでは **「新しいプロジェクト」** のボタンをクリックしましょう。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/fce7cded-0071-48d2-8566-0bf74de4227a.png)

この画面では、どんなプロジェクトを作成するかを設定することができます。
したの画像のように
1. **Universal 3D** を選択する。
2. プロジェクト名を設定する。今回は`GameCreateProgrammingSample` などにしておきましょう。
3. 保存場所を設定する。PC上のどこかに保存してください。
このとき、OneDrive上には **くれぐれも** 生成しないでください。
4. 設定できれば **「プロジェクトを作成」** ボタンを押してください。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/1290fb55-77a0-4021-bc8f-3b541c39dd35.png)

プロジェクト生成にも結構時間がかかると思いますので、これも気長に待ちましょう。

このような画面が出ればプロジェクト生成は完了です！
少しレイアウトが違うと思いますが、雰囲気は同じだと思うので大丈夫です！

![スクリーンショット 2026-02-19 23.42.19.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/82993a52-f2a2-4ebf-bb93-89ec9f2a0695.png)

## Cube を作成しよう
それでは最後に、1つだけ3Dオブジェクトを作成してみましょう。

画面左の **Hierarchy** という場所があります。
ここで、 **右クリック** をしてみましょう。

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/105f329d-bac0-484d-ba7f-db3f3ae66cc6.png)

すると、下の画像のように色々項目が出てくるので
1. **3D Object** を選択する
2. **Cube** を選択する

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/5e60459b-3be0-49a4-a68a-bf57b6dfd362.png)

このように立方体が出てきました！
他にも色々なオブジェクトがあるので試しに色々出してみてください！

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2735967/9a775f88-1f2a-4f9a-bd7c-cc60cf16884d.png)

# まとめ
この記事ではゲーム開発の簡単なやり方とその準備をしていきました。
次の記事から本格的にゲーム開発をしていこうと思うので楽しみにしてください！

それではおつかれさまでしたー