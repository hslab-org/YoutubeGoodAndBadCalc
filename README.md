Reolの動画って何で異常に高評価率高いんだろと言う疑問から生まれた。<br>
高評価／低評価＝900の動画見て、これは匿名ビットコインVPSを複数借りて、<br>
youtubeアカウント大量に作成して自動で高評価押させてるんじゃないかとしか思えなかった笑<br>

すぐ計算できるようにyoutubecalcを/usr/binに突っ込む使い方した。<br>
その際chmodで実行権限つけてくださいね。<br>

入れ方（要gitコマンド）

cd /tmp
git clone https://github.com/hslab-org/YoutubeGoodAndBadCalc.git
su
cp ./youtubecalc /usr/bin
chmod 755 /usr/bin/youtubecalc
exit
youtubecalc
