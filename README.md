Step.1
AWS Lightsailのインスタンス接続で「SSHを使用して接続」クリックして、サーバー内にログインする。

Step.2
下記2コマンドを分けて入力する。

↓Bitnamiロゴを削除区するコマンド

sudo /opt/bitnami/apps/wordpress/bnconfig --disable_banner 1
↓サーバー内のApachを再起動するコマンド

sudo /opt/bitnami/ctlscript.sh restart apache
Step.3
ブラウザ再読み込み！以上！
