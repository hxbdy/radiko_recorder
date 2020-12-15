# 概要
ネットラジオを録音する。
以下のaptパッケージが必要。
RaspiZeroWで動作確認済み

```bash:install
sudo apt-get install swftools rtmpdump libxml2-utils ffmpeg
```

# 経緯
20201215以前はrec_radiko.shを使用していた。
radikoの認証に失敗するようになったためradishに以降した。
ベースはradishで作成。
ファイル名のフォーマットを以前のrec_radiko.shと統一したかったため、
ファイル名まわりを変更してある。
# USAGE
https://github.com/uru2/radish
