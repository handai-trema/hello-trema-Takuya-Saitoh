課題：スイッチの切断イベント　レポート

ソースコードの改造内容：
イベントハンドラ switch_disconnected を追加した。
これはスイッチがコントローラから切断された時に呼び出されるメソッドで、
切断されたスイッチのIDを引数として受け取る。
このメソッドの中に "Bye (引数として受け取ったID)"のメッセージを出力する
処理を追加すれば良い