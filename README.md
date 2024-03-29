# AWSのまとめ

❗すべての課題は第13回の「課題完成」を達成するための基礎で、それの集大成が第13回の「課題完成」となっています。

|講座|課題内容|苦労した点|構築手順|課題完成|
|---|---|---|---|---|
|**第1回**|ルートユーザーをMFAで保護、BillingをIAM ユーザーで閲覧、AdministratorAccess権限のIAM ユーザーを作成、Cloud9を作成して HelloWorldを出力||[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_1)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_1)|
|**第2回**|Gitの設定、GitHubでプルリクエストの発行||[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_2)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_2)|
|**第3回**|Cloud9でWebアプリをデプロイ|GitHubに画像をプッシュするのに苦労しました。Google検索しても有用な情報を見つけられなかったが、他人のREADMEに書かれてるパスの規則性を見つけたことで解決できました。|[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_3)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_3)|
|**第4回**|VPC・EC2・RDSの作成、EC2からRDSへ接続||[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_4)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_4)|
|**第5回**|EC2インスタンス上にNginxとUnicornを配置して、そこにWebアプリをデプロイする。ブラウザからALB経由でWebアプリにアクセスして、まずはデータをRDSに保存されるようにし、それができたらデータの保存先をS3に変更。手動構築したインフラ環境のAWS構成図を作成|EC2に対してコマンドを実行して成功しているにもかかわらず意図した挙動にならないことに最初戸惑いました。困ったときはとりあえずエラーログとアクセスログを確認することで解決するまでの時間を短縮できました。|[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_5)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_5)|
|**第6回**|CloudTrailのイベントを出力させる、CloudWatchアラームでALB のアラームを設定してメール通知、AWS利用料の見積|CloudWatcアラームが鳴ったらメール送信されるように設定したのにメール送信されませんでした。仮説と検証をひたすら繰り返すことで、この問題を解決することができました。|[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_6)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_6)|
|**第7回**|第5回で作成したインフラ環境のセキュリティに関する脆弱な部分を探して対策方法を報告|||[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_7)|
|**第8回**|課題なし||||
|**第9回**|課題なし||||
|**第10回**|CloudFormationでVPC・EC2・RDS・ALB・S3を作成||[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_10)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_10)|
|**第11回**|ServerSpecでテストコードの実行||[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_11)||[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_11)|
|**第12回**|CloudFormationテンプレートの内容に問題がないかCircleCIを使ってチェック|CircleCIでコードを実行する方法を書いている記事を参考にする際、どの記事も古いバージョンのCircleCIアカウントで行っていて少し操作方法に苦戦しました。これも仮説と検証の繰り返しによって解決することができました。|[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_12)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_12)|
|**第13回**|CircleCIとServerSpecとAnsibleを使ってインフラ環境のデプロイからテストコードの実行までをすべて自動化させる |CircleCIからServerSpecを用いたテストコードの実行がどうしてもできなくて、くじけそうになりました。一旦、今やっている方法を辞めて、まったく違う方法を試してみることで解決できました。|[構築手順](https://github.com/Hidetaka-Konishi/Raise_AWS_13)|[課題完成](https://github.com/Hidetaka-Konishi/Raise_kadai_13)|
|**第14回**|第5回のAWS構成図に第13回の自動化処理を追加、第1回~第14回までの内容をまとめたリポジトリのREADMEを作成|||[課題完成]()|
