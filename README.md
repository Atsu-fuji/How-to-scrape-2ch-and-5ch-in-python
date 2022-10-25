# How-to-scrape-2ch-and-5ch-in-pyhon

2ちゃんねる（現5ちゃんねる）の投稿をスクレイピングする方法です。

（ソースの日本語が文字化けを起こしてしまっていますが、GoogleColaboratoryで開けば問題ありません。）

## 注意点
1．スクレイピングするスレッドのURLはすでに取得していることが前提です。Googleドライブに「ターゲットとしているスレッドURL」が1行ごとにまとまったテキストファイルをアップロードした状態で始めてください。

2．出来上がるものはデータフレームなので、そのままでは保存されていません。適宜ファイルとして保存するなどしておきます。ソースではcsv形式で保存しています。

3．スクレイピングをするときには、適宜sleepを入れるなどして相手方サーバーに負担がかからないように配慮しましょう。
