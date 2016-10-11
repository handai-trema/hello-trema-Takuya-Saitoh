課題: Hello Trema レポート

ソースコードの改造内容：　
start メソッド内で "trema started" とログ出力する部分の "trema" を "self.class.name" と書き換えた。
"self.class" で start メソッドが属するクラス HelloTrema を取得し、
".name" でそのクラス名を文字列として取得している。
"trema" を "HelloTrema" と直接書き換えても結果は同じであるが、
この場合クラス名を変更した時にこの部分を書き換え直さなくてはならなくなり、
プログラムの一貫性が保てなくなる可能性が増加する。
