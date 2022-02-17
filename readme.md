# プロダクトのタイトル
KAIZO-DO -プロ野球編- (編集・削除追加)

## プロダクトの紹介
- 物事に対する「解像度」の高さが似ている人同士で繋がるWebサービス「KAIZO-DO」のプロトタイプ版
- 今回もプロ野球をテーマにしています。
- 各投稿を押下すると、投稿の詳細ページに遷移し、編集・削除ができます。

## 工夫した点，こだわった点
- 投稿の改行やデザイン調整など、前回の課題では不十分だった点を改めて改善しました。
- 削除は確認モーダルを表示するなど、JSも組み合わせて実装しました。

## 苦戦した点，共有したいハマりポイントなど
- 本来はindex.phpで新規会員・ログイン機能を作り、ログインセッションでユーザーごとの投稿管理ができるところまで実装したかったのですが、ユーザーごとのログインセッションのDBと投稿のDBをmysqlでどう管理すればいいかわからず、断念しました。今後のセッションの講義で実装できるようにします。
- ログイン機能・画像投稿機能が実装できれば、大枠のプロトタイプが作れそうなので、もっと魅力的なサービスになるための企画やコンセプトのブラッシュアップを行っていきます。

## レビューいただく方でのご留意事項
- 私のM1チップMacPCではXAMPPのapacheがうまく起動しないため、MAMPで実装をしています。DB接続の書き方をMAMP用に少し修正しているのでご留意ください。

## URL
