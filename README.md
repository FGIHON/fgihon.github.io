# GIHON GitHub Server

## Note

### cookie/index.html
Cookieの使えないサービス（GAS WebAppなど）で擬似的にCookieを利用するためのファイル。
`url`パラメータに`encodeURIComponent()`したURLを渡すと、`id`パラメータにCookie用IDを加えた上で埋め込む。
