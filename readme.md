# 説明
<br>YUKI TUBEに少し改造を加えました。<br>
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。  <br>
画像は使えません。  <br>
cookieにyuki=Trueを設定すると認証されます。  <br>
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。  <br>
## renderでのデプロイ
<br>(事前にrenderのアカウントを作っておく)<br>
<a href="https://render.com/deploy?repo=https://github.com/mochidukiyukimi/Yuki-Youtube-slim-2">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
### コードスペースでデプロイ
<br>これはpokemogukunnがさらに改良を加えました。
すると、なんとコードスペースを使って
今すぐYUKIを使いたい方向けの改良に成功したのです。
<br>
## やり方
<img src="https://pokemogukunns.github.io/codespase1.png">
<br>ここの中の緑色の枠の中の
<br>

＜ ＞ Code▼   を選択します。
<br>
次に、<br>
<img src="https://pokemogukunns.github.io/codespase2.png">
<br>この中の、Codespaceを押すと、<br>
<img src="https://pokemogukunns.github.io/codespase3.png"><br>
こうなるので、この中の＋を押しましょう。（新しいタブでコードスペースが開かれますが、閉じないでください。）<br>
```bash
pip install -r requirements.txt
