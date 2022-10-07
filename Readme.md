# lx02 の例題

## 動かし方

ターミナルで `build.sbt` のあるフォルダに移動し、`sbt` コマンドを実行すると以下のように `sbt` が起動します。

~~~
[info] [launcher] getting org.scala-sbt sbt 1.7.2  (this may take some time)...
[info] welcome to sbt 1.7.2 (Homebrew Java 18.0.2.1)
[info] loading project definition from /Users/wakita/Dropbox/doc/classes/prg1/lx02/project
[info] loading settings for project root from build.sbt ...
[info] set current project to root (in build file:/Users/wakita/Dropbox/doc/classes/prg1/lx02/)
[info] sbt server started at local:///Users/wakita/.sbt/1.0/server/f6ef78b5513c44bbb6c4/sock
[info] started sbt server
sbt:root>
~~~

`sbt:root>` が `sbt` のプロンプトで、`sbt` のコマンドの入力を促しています。

ここで `run` コマンドを実行します。`run` を入力して下さい。

すると以下のような 7つの項目からなるメニューが表示されます。

~~~
sbt:root> run

Multiple main classes detected. Select one to run:
 [1] AutomatonApp
 [2] PotonApp
 [3] ScheduledTrafficLightApp
 [4] TimerApp1
 [5] TimerApp2
 [6] TrafficLightApp

Enter number:
~~~

番号づけされた各項目がサンプルコードの実行に対応しています。全部で７つのサンプルを用意しました。番号を入力すると、そのプログラムの実行が始まり、画面のどこかにアプリケーションのウィンドウが開くはずです。サンプルコードによっては、アプリケーションのウィンドウは退屈かもしれません。かわりにターミナルになにか表示されると思います。

サンプルコードによっては永遠に実行が止まらないものもあります。このようなコードを強制終了するには、アプリケーションのウィンドウをクリックして通常の終了手順のとおりです（Mac ならアプリケーション・メニューから終了を選択）。


