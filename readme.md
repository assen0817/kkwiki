# pukiwikiの変更を監視して通知を送るツール(DISCORD)

## 初回
`pip install -r requirements.txt`

## 実行
`python wiki.py`


## 準備
* tokens.py
    - DISCORD_CHANNEL にDISCORDのチャンネルのwebhookを入れる
        + wiki通知
    - DISCORD_CHANNEL_DETEIL にDISCORDのチャンネルのwebhookを入れる
        + wiki通知_連絡事項
    - DISCORD_CHANNEL_DETEIL_ALL にDISCORDのチャンネルのwebhookを入れる
        + wiki通知_連絡事項_全て
    - WIKI にwikiの承認情報を入れる
        + 適当なwikiのページにアクセスする
        + リクエストヘッダー内のAuthorizationの値

wiki内データを取るだけならWIKIだけ埋める
