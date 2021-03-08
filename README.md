# Litest
Convenient-software by monochrome. It used Electron by GitHub.

訳：monochrome.による便利なソフトウェア。これはGitHubによるElectronを使用した。

# このソフトウェアについて
|||
|:--|:--|
|名前|Litest|
|バージョン|2.0 Beta2|
|OS|Windows, macOS(Linux上でビルド可能)|
|ビット|64ビット|
|開発者|Sorakime|
|フレームワーク|Electron|

そんなところかな

## Windows
|||
|:--|:--|
|ビルドしたPC|HP Pavilion Slimline s5-1350jp|
||Intel Core i5-3450|
||8GB DDR3 RAM|
||512GB HDD|
|PCの環境|Windows 10 Home 64ビット 2009|
||Node.js v.15.9.0|
||Electron v.11.3.0|
||Electron Builder v.22.10.5|
|(動くとは言っていない)動作OS|Windows 10 1703 64bit|

## macOS
|||
|:--|:--|
|ビルドしたPC|[iMac (21.5-inch, Late 2009)最低モデル](https://support.apple.com/kb/SP576?locale=ja_JP&viewlocale=ja_JP)|
|PCの環境|macOS High Sierra 10.13.6|
||Node.js v.14.15.4|
||Electron v.12.0.0|
||Electron Builder v.22.10.5|
|(動くのかは知らない)動作OS)|OS X Mountain Lion 10.8|

こんな感じかな。バージョンがElectron Builder以外が全部不揃いなのが気になる。Node.jsに関しては16が出たらどっちもそれにアップデートして、Electronは新しいディレクトリ作って新しくインストールすればいいかな。どっちもv.12.0.0に揃えたいね。

以下、リリースノートからの抜粋。

# アップデート内容

- 起動直後のウィンドウの変更点
  - Dockを中央ぞろえ、macOS Big Surのようなデザインへ変更
  - ウィンドウの最小サイズの変更
- すべての内臓ソフトにおける改善点
  - メニューをカスタマイズ
  - ダークテーマ(モード)対応
  - アイコンを角丸正方形のものに変更(Prompt除き)
  - ウィンドウの最小サイズの変更
- Search
  - 「検索」から改名
  - 以前よりシンプルにデザイン変更
- Calcer
  - 半分完成させた
  - レスポンシブデザインに少し対応させた
- Prompt
  - コマンドが見つからなかった場合の返答などの変更
  - Enter押下、自動で新たな行にフォーカスが当たるように改良
  - フォーカスされたときに枠線が表示されないように変更
  - すべての行の横幅が少し短くなった
  - 誤った表記(Utilythes by monochrome. ver.1.0)の訂正
- Universal
  - なななんと！？ダークモード有効時では時計が読めません！なんということでしょうか！！！！
  - もし時間以外(分、秒)が一桁の場合、前に0をつけるように改良
    - 5時5分の場合、5:5ではなく5:05と表示

ぜひ試してみて下さい！

Copyright 2021 Sorakime. [monochrome License.](https://sorakime.github.io/mncr/license?v=1.1.1)
