# Utilythes v.2.0 Beta
###### Electronで、ネイティブに。
---
## ソフトについての詳細情報
|　||
|:-|:-|
|ソフト名|Utilythes|
|開発者|[自分](https://sorakime.github.io/me/)|
|ビット|64ビット|
|バージョン|2.0 Beta(なんか知らんけど1.0ってなってるところもある)|
|動作確認済みWindowsバージョン|Windows 10 Home 64bit 20H1(2004)|
|動作確認済みmacOSバージョン|macOS High Sierra 10.13.6(17G14033) カーネルバージョン17.7.0|
|いけるんじゃね？Windowsバージョン|Windows 7 Home Basic 64bit(サポートが終了したため推奨はしない)|
|いけるんじゃね？macOSバージョン|OS X Lion 10.7(クソ古いため推奨はしない)|
|重さ|めっちゃ軽いっすよ？同じElectron採用しているAtomとかと比べても格段に高速だよ？クリックした瞬間に起動しますし、使ってても全然性能要りませんよ？|
<!--多分だけどね？-->
あとさ、Macは難しそう。自分の環境でパッケージングしてくれたらいいかな。ソース配布するんで。あの、趣味でやってるんでできるだけ金払いたくないんだわ。署名しないと起動できないそうなので。。。Apple Developer Programにはね、、ガチの開発者じゃないんで加入できないよ

## ネイティブになって帰ってきました。
開発者のSorakimeです。最後リリースしたのはv.1.5?だったかな。このバージョンは、2.0 Betaです。[Electron](https://electronjs.org/)使いました。何かというと、[GitHub](https://github.com)社が開発している、アプリケーションを開発するためのフレームワークです。HTMLとCSS、Node.jsが使用可能なJavaScriptを使って開発できます。一言で言うとWeb技術を使ってマルチプラットフォームに対応したアプリケーションが開発できるなんかすごいやつってことです。
似たようなものに[NW.js](https://nwjs.io)というものが存在しますが、エントリポイントがElectronがJavaScriptファイルなのに対してNW.jsはエントリポイントがHTMLファイルだったような気がします。難しいのはそうなんだけど、かなり自由度やコマンドラインからの変更などが楽なのとGitHub社お手製のフレームワークなので安心できます。情報量も多いのがいいね。
というか最近のJ-POPは変わってるねぇ。馴染めないわ。というか久しぶりにSpotify使ってるけど結構いいね。PC版は。iPhoneで使ってるとかなり使いにくい。BGMとして使っているなら別に何でもいいんだけどね。ただ、時々出てくるAdvertisementがね。広告がね。Windowsで使ってたらタスクの名前(?)がAdvertisementになったので一応英語の表記で行くよ()
さすがにElectron使ってるんでWindows(exe)とmacOS(dmg)、Linux(deb)の3プラットフォーム向けくらいは作ってやるよ。C#とSwiftとValaと、、ってプラットフォームごとで言語変えるとかWebが大好きな自分からしたらウザすぎるんだよ。めっちゃ今日だけ？ネット快調だね。昨日とか上り2Mbpsしか出てなかったから。光回線(だと思う)のに。

## 使い方
多分すぐにわかる。
![i'm-an-idiot](https://user-images.githubusercontent.com/69241694/99891912-6679ef00-2cb2-11eb-9e3a-b6560596c0d7.png)
この画像は、WindowsでUtilythesを起動したときの様子です。下の青い部分が、Dockと呼ばれるところになります。そして、ウィンドウ上部にある灰色の長細い部分が特に名前が決まっていません。一応`<header>`要素が使われています。その左上にあるのはただの飾りです。著作権です(?)。右上にある時間が表示されているところは、時計です(?)。それをクリックしてみてください。
![image](https://user-images.githubusercontent.com/69241694/99891986-58789e00-2cb3-11eb-8bde-4e029cbbd523.png)
上の画像のように、大きなダイアログというかモーダルウィンドウが出現しました。大きく時間が表示されています。では、その大きく表示されている時間をクリックしてください。消えます。まぁ、もう一度右上の時間表示のところ押しても消えるんだけどね。
それでは、メインの機能を起動してみましょう。
先ほど言った、Dockにある何かしらのアイコンをおすか、先ほどのようにモーダルウィンドウを出現させてからアプリケーションの下にある検索、Calcer・・・などといった文字を押してみましょう。ここでは検索、Dockで言う一番左の虫眼鏡マークをクリックします。そうしたら「検索」というウィンドウが開かれると思います。ではここから検索の使い方について解説していきます。

### 検索の使い方
![image](https://user-images.githubusercontent.com/69241694/99894724-bdd78980-2cc9-11eb-9aaf-6f44a0a9df63.png)
シンプルですね。ここからGoogleやBing、DuckDuckGoのように使うことができます。設定項目はおろか、時間表示などもないです。かなり殺風景なものに仕上がっていますね。エンジンはDuckDuckGoです。エンジンというか、そっちに転送するだけだけどね。
ちなみに、入力し終わってから`Enter`を押すだけじゃ飛べません。マウスで移動させる必要があります。
DuckDuckGoに転送するだけなので、DuckDuckGo特有のコマンドなどは使えます。

### Calcerの使い方
は紹介しません。だって、未完成ですもん。勘で使ってみてください。計算できません(´・ω・`)パス！

### Promptの使いかた
Promptの使い方は紹介します。かなりHTMLの記述量は少ないですが比較的うまくいったと思います。文法？独自流だよ
ここにコマンド一覧＋引数表書きますね

|コマンド|引数|備考|
|:-|:-|:-|
|`exit`|なし|ただウィンドウを閉じるだけ|
|`help`|なし|現在準備中、できてないけど応答だけあり|
|`hello`|なし|挨拶してくれる。また、現在の日時を取得できる|
|`open`|開くURL|URLとか言いつつもローカルのパスして可能。新しいウィンドウで開く|
|`search`|検索キーワード|DuckDuckGoに引数を渡す。というか開く。当然DuckDuckGoのコマンド使用可能。スペースは適用される|

取り敢えず全部のコマンドの記述例書いてみますね。

<br>

`exit`
```bash:
exit
```

<br>

`help`
```bash:
help
```

<br>

`hello`
```bash:
hello
```

<br>

`open`
```bash:
open https://www.apple.com/jp/
```

<br>

`search`
```bash:
search !yt Sorakime
```
<br>

便利ですね(?)
というかそもそも使うのかな、CUIで。

### Universal
特に言うことはなし。起動したら上のほうににPCに設定されている時間が表示されます。その下にUTC(世界協定時間)、まぁGMTとほぼ同等の時刻が表示されます。
一応、10ミリ秒=0.01秒ごとに更新して表示しています。正確性と軽量さを一番保てると思うのが10msだね。
それだけ。次のバージョンではアナログ時計追加&デザイン変更というかおしゃれにすることを目標にします。

<br><br>

&copy; 2020 Sorakime. [monochrome License.](https://sorakime.github.io/mncr/license?v=1.1)
