ssl化とはurlのスキームがhttpではなく、httpsになること。

ssl化することのメリット
・安全性（データを悪意のある人に盗聴されても重要なデータを見られないようにする。）
・ユーザの安全性（ssl化されていないサービスら危険だと感じさせてしまう。）
・seoの観点でも優れている。
ssl認証を適応するには
・ssl証明書を認証局から取得して設置。letsencryptを使用すると無料で取得できる。
・webサーバをhttpsに対応するように設定する。
・httpでアクセスされたら、httpsにリダイレクトするようにする。

学習元
https://www.youtube.com/watch?v=ZTk4F8KhRrs
https://www.youtube.com/watch?v=13NTn6WiQvU
