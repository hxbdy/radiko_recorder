# 概要
ネットラジオを録音する。
Ubuntu 24.04 LTS で動作確認済み

# 依存
```bash:install
sudo apt install rtmpdump libxml2-utils ffmpeg
```

# 経緯
20201215以前はrec_radiko.shを使用していた。  
radikoの認証に失敗するようになったためradishに以降した。  
ベースはradishで作成。  
ファイル名のフォーマットを以前のrec_radiko.shと統一したかったため、  
ファイル名まわりを変更してある。  

# USAGE
https://github.com/uru2/radish

TBSラジオを 120 min 録音する
```bash:install
./rec_radiko.sh -t radiko -s TBS -d 120
```
