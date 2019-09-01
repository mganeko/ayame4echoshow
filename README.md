## ayame4echoshow

[OpenAyame/ayame-web-sdk](https://github.com/OpenAyame/ayame-web-sdk) のサンプル集[OpenAyame/ayame-web-sdk-samples](https://github.com/OpenAyame/ayame-web-sdk-samples)をベースに、EchoShow5のFirefoxで表示できるように変更したものです。

### レポジトリ

- https://github.com/mganeko/ayame4echoshow

### GitHub Pages

- https://mganeko.github.io/ayame4echoshow/

## 変更内容

- ayame.js --> ayame4echoshow.js ... sdpSemantics: 'unified-plan' を明示的に指定
- main.js ... デフォルトのルームを変更
- sendonly.html ... コーデックにVP8を指定
- recvonly.html --> recv4echoshow.html ... レイアウトを変更

## 利用方法

- 送信側
  - [sendonly.html](sendonly.html) をブラウザで開く
  - 「接続」ボタンをクリック
- 受信側
  - [recvonly.html](recvonly.html) をブラウザで開く
  - 「接続」ボタンをクリック◊
- EchoShow5で受信
  - Firefoxで[recv4echoshow.html](recv4echoshow.html) を開く
  - 「接続」ボタンをクリック

## ライセンス

ayame4echoshowはApache License 2.0で公開しています。

## 謝辞

ayame4echoshowは、次のレポジトリ/サービスを利用しています。ありがとうございます。

- [OpenAyame/ayame-web-sdk](https://github.com/OpenAyame/ayame-web-sdk)  (Apache License 2.0)
- [OpenAyame/ayame-web-sdk-samples](https://github.com/OpenAyame/ayame-web-sdk-samples) (Apache License 2.0)
- [shiguredo/momo](https://github.com/shiguredo/momo) (Apache License 2.0)
- [WebRTC シグナリングサービス Ayame Lite](https://ayame-lite.shiguredo.jp/beta)（株式会社時雨堂）

