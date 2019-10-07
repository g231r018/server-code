# server-code

<私のgitアカウント>
URL:https://github.com/g231r018/server-code

<参考文献>
URL:https://qiita.com/qoAop/items/96a586337fa9f8983e48

佐藤くんへ　サーバ作りました。
"サーバコード"　&　"pingコード"は高橋のgitアカウントにプッシュ しました。
リポジトリ：   g231r018/server-code
ファイル名："server.py" & "check.py"

サーバの動かし方:参考文献の通り
Flaskサーバの稼働環境作る（python3用）　Flaskインストール
testapp/appを稼働させる. server.pyをpython3で実行（実行させて待機）. その後check.pyでping送信
"received -> b"が出たら,多分通信成立.
 
check.pyがping送信用プログラムです。（TCP/IP通信の死活監視）

FlaskのWebサーバとアプリは以下のパス。
サーバープログラム、Pingプログラムも含む。
Users/g231r018[ここは任意]/[path]/proj/testapp/app/server.py　・・・①
・/Users/g231r018[ここは任意]/[path]/proj/testapp/app/check.py　・・・②
このパスを参考に。
佐藤さんがFlaskのWebサーバの環境を作って
通信をテストしてください。


