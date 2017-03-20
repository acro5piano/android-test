# Android app test

コマンドラインからアンドロイドアプリを開発したい。

とりあえず、Android studio は無事にインストールした。が、重すぎて使いたくない。

普段Vimに慣れてしまっているのが問題かもしれない。

で、「新規プロジェクト作成」で作られたファイルだけを持ってきた。


- 自分のAndroidスマホをつなぐ
- ./gradle build
- adb install -r app/build/outputs/apk/app-debug.apk

でインストールできることは確認できた。もしかして毎回これやるのか。

