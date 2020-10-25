# 概要
radikoを録音する。
以下のaptパッケージが必要。
RaspiZeroWで動作確認済み

```bash:install
sudo apt-get install swftools rtmpdump libxml2-utils ffmpeg
```

# USAGE
```bash:HowToUse
bash rec_radiko.sh CH MIN
```

TBSを120分録音する場合以下のように実行する
実行にはcronを使う。

```bash:HowToUse
bash rec_radiko.sh TBS 120
```