# 人数集計システムVer.3
- Webアプリケーションにすることによって、室内を移動しながら集計することができます。
- このシステムは、以下に書かれたような不具合/不便な点が見つかったため、人数集計にはVer.2のものを使っています。
- リポジトリは作業記録として残しますが、今後更新する予定はありません。

## デプロイ
- Next.jsの静的エクスポートを使っています。
- 情報メディアセンターの貸出仮想サーバー上に、Dockerを用いて構築しています（Nginx）。
- 学内からのみ参照できます。
  - agwlanか、学内設置PCからアクセスしてください。

## 既知の不具合/不便な点
- 一部スタッフのスマホで、Googleのログイン認証画面が立ち上がらない
- 毎度スマホを使うのが大変
- 複数人でやってしまって、二重で送信される
- 送信した後も画面が変わらないので（トースト表示のみ）、送ったのかわかりにくい。もう一度送ってしまう。
- スマホだとレスポンシブデザインになって、集計しにくい


