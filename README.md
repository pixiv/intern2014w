intern2014w
===========

[エンジニア向け　pixiv開発のbugリストからの脱出！エンジニア職インターン - ピクシブ株式会社 採用サイト](https://ssl.pixiv.net/recruit/entry/winter_intern.php)

こちらの __GitHub選考コース__ の GitHub 選考課題です

## 提出方法

  * ISUCON4 予選問題の AMI を ISUCON4 予選問題の規定通りに立ち上げてください
    * AMI 提出はないので spot instance でもいいですが spot instance にはいくつか注意しなければならない点があるので使う場合は気をつけてください
  * benchmarker を動かして正しく動いているか確認してください
  * デフォルトは ruby 実装が動いているので PHP 実装に切り替えてください
    * supervisord と Nginx の設定変更が必要です
  * benchmarker を動かして正しく動いているか確認してください
    * 今回は API キーは不要なので `./benchmarker bench` と実行してください
    * この時出たスコアを記録しておいてください
  * ブラウザから表示されるか確認して下さい
    * セキュリティ設定に気をつけてください
  * 自分の GitHub アカウントを使って空のリポジトリを作ってください
    * 名前はわかりやすければ何でも構いません
  * `/home/isucon/webapp` ディレクトリを `git init` して，先程作ったあなたのリポジトリにコミットしてください
    * あなたが行った変更の差分が分かるように必ず変更を行う前に `git init` をしてコミットするのを忘れないで下さい
    * public ディレクトリも含まれている必要があるので webapp ディレクトリ以下すべてのディレクトリをコミットしてください
  * PHP のソースコードに一つ以上の変更を加えてスコアを上げてください
    * 変更を行ったら GitHub にプッシュしてください
    * 試行錯誤をしたコミットがあればそのまま残してください
      * その場合はコミットはわかりにくくても構いません
    * README.md に初期のスコアと最終的なスコアを記述してください
    * どうしてそういう実装をしたのか，なぜその実装で速くなると思ったのかを README.md に書いてください
      * 箇条書きなどで書いてください
      * 分かりやすければ形式は問いません
  * （任意課題）Nginx や MySQL などのパラメータなどを変更して，スコアを上げてください
    * どのような変更をしたか README.md に記述してください
    * どうしてそういう変更をしたのか README.md に記述してください
      * 箇条書きなどで書いてください
      * 分かりやすければ形式は問いません
    * README.md に最終的なスコアを記述してください
  * このリポジトリを Fork してください
    * Fork したリポジトリに `intro.md` というファイル名で今回あなたが用意したリポジトリの URL を書いてください
    * このリポジトリに対してプルリクを送ってください

プルリクを送った時点で提出完了です

任意課題と書かれていないものは全て必須となります


## 注意点

  * 本来 ISUCON は（レギュレーション違反にならない限り）何でもありの Web アプリケーション高速化バトルですが，今回は pixiv のソースコード（PHP）を実際に変更してもらうということを考慮して ISUCON4 の初期 PHP 実装に変更を加えてもらうことに限定します
  * 初期の実装に対してどのような変更を加えるのかが選考の対象となります
    * 実際に pixiv のソースコードのバグフィックスをするにあたって任せられる能力があるかどうかを判断したいという意図です
    * 理由を説明できれば変更は数行でも構いません
  * ISUCON はスコアを競うものですが，今回の選考にスコアは関係ありません
    * ただし初期のスコアと最終的なスコアは必ず README.md に記述しておいてください

## 質問チャットルーム

~~技術的な質問については [idobata.io](https://idobata.io/) のチャットルームにてサポートいたします~~
終了しました

https://idobata.io/organizations/pixiv/rooms/intern2014w_guest/join_request/2a304e3e-cdca-4919-be63-f76884b4df4c

  * 基本的に回答は営業時間内（平日10:00-19:00）のみに行います
    * 回答はピクシブ株式会社のエンジニアが行います
  * トラブルが起これば閉じる可能性があります
  * 選考に関する質問には回答できません

以上の点をあらかじめご了承ください

## 参考URL

ISUCON4 予選問題について

  * [ISUCON4 予選問題の解説と講評 ＆ AMIの公開](http://isucon.net/archives/40724693.html)
  * [ISUCON4 予選当日マニュアル](https://gist.github.com/mirakui/e394ed543415852d34a6)
  * [isucon4/qualifier at master · isucon/isucon4](https://github.com/isucon/isucon4/tree/master/qualifier)

AWS の利用方法

  * [AWS クラウドのご利用開始方法 | アマゾン ウェブ サービス（AWS 日本語）](http://aws.amazon.com/jp/getting-started/)

Git の使い方

  * [hatena/Git-for-Designers](https://github.com/hatena/Git-for-Designers)
