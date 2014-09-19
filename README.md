Intel_Galileo
=============
any data.  
#YoctoProjectのカーネルビルドでSWAPをEnableにしました。  
ZIPをDLして展開してください。  
SDのパーティションは2パーティションとし後方パーティションにSWAP領域を設定してください。  
login:debian pass:debian です。適時変更して下さい。  
本Debianのイメージ作成は以下のプロセスで行っています。  
https://github.com/jitomesky/Installing_Galileo-debian/blob/master/galileo-debian.md  
本イメージでは[aptitudeでSegmentation fault]は確認されていません。  
ライセンスは各Kernel及びモジュール、アプリケーションのライセンスと同様となります。  
config.baseはLinuxビルドコンフィグファイルです。本イメージのコンフィグファイルとなります。  
config.baseはSDカードに入れる必要はありません。  
SDカードにコピーするファイルはconfig.base以外の全てです。  
Galileoのファームウェアは現行のファームでは確認していません。  
