# ExplorerPatcher-jp
ExplorerPatcherに多言語化が実装されたため、ExplorerPatcher-jpの更新は終了しました。  
今後は[ExplorerPatcher](https://github.com/valinet/ExplorerPatcher)をご利用ください。
## お礼

翻訳に貢献してくださったreindex-otさん、Rukotoさん、Syuugoさん  
ExploerPatcherを開発、維持している皆さん  
そして、ExplorerPatcher-jpを利用してくださった皆さん  
今まで本当にありがとうございました！

---------------------------------------  

このプロジェクトは、Windows上での作業環境を改善することを目的としています。  
[![Discordに参加する](https://discordapp.com/api/guilds/1155912047897350204/widget.png?style=shield)](https://discord.gg/gsPcfqHTD2)  
ExplorerPatcher-jpは、ExplorerPatcherの日本語化と日本語環境向けの最適化を行ったExplorerPatcherの「非公式なビルド」です! 公式ではありません!  
非公式日本語訳の更新は遅れる場合があります。  
更新に気づいていない場合もありますので、Twitterでメンション等して頂ければできるだけ早く更新します。

このプログラムはWindows Updateによって正常に動作しなくなる可能性があります。自己責任でご利用ください。

もし、無限再起動等でアンインストールできなくなった場合は以下の方法をお試しください。

> アンインストール方法
>
> Win + R を押下して、appwiz.cpl と入力し、［アプリと機能］を起動します。
>
> ExplorerPatcherを検索し、アンインストールします。

![Build status](https://github.com/valinet/ExplorerPatcher/actions/workflows/build.yml/badge.svg)

## ExplorerPatcherの概要

* Windows 11またはWindows 10のタスクバーから選択できます。(ラベルや小さなアイコンなど多くのカスタマイズが可能です)
* Windows 11で変更されたコンテキストメニューとコマンドバーを無効化することができます。
* スタートメニューがデフォルトですべてのアプリを表示するよう変更したり、頻繁に表示するアプリの数を選んだり、アクティブなディスプレイに表示したりできます。
* Windows 11、Windows 10、Windows NT Alt-Tab Window Switcherの3種類から、自由に選択できます。

* Explorerの使いやすさを向上させるために、以下の工夫をしています:
  * トレイメニューのスキンをWindowsのスタイルに合わせ、ポップアップするようにし、アイコンに対して中央に配置を可能にする
  * ネットワークアイコンを左クリックまたは右クリックをしたときの動作の変更
  * ファイルエクスプローラーの検索ボックスをWindows 7に戻すか、Windows検索の完全な無効化
  * 没入型メニューを無効にし、本物のクラシックテーマを不具合なく動作させるための緩和策の提供
  * ExplorerPatcherが提供するすべての機能については、公式版Wiki内の記事で詳しく説明をしています。(https://github.com/valinet/ExplorerPatcher/wiki/All-features)

Windows 10では、一部の機能が使用できない場合があります。

## インストール

1. 最新版の[セットアップ用ファイル](https://github.com/creeper-0910/ExplorerPatcher-jp/releases/latest/download/ep_setup.exe)をダウンロードします。
2. ダウンロードをしたファイルを実行します。管理者権限での実行が要求され、その後に必要なファイルがインストールされます。
3. インストールが完了すると、見慣れたWindows 10のタスクバーが表示されます。設定を変更するには、タスクバーを右クリックをして「プロパティ」を選択します。

ね、超簡単でしょ?

## 次は?

* 一度[公式版のWiki](https://github.com/valinet/ExplorerPatcher/wiki) を読むことを強く推奨します。こちらにはExplorerPatcherのより高度な機能についての情報があります。
* ExplorerPatcherが提供する機能のほとんどを[ここ](https://github.com/valinet/ExplorerPatcher/wiki/All-features)で知ることができます。
* アップデートの管理方法、新しいバージョンや新しいWindowsビルドに期待することについては、[こちら](https://github.com/valinet/ExplorerPatcher/wiki/Configure-updates)をご覧ください。
* 質問がある方は[よくある質問](https://github.com/valinet/ExplorerPatcher/wiki/Frequently-asked-questions)をご覧ください。
* 他に質問のある方は[議論](https://github.com/valinet/ExplorerPatcher/discussions)ページにスレッドを立ててください。
* バグを発見した、もしくはアプリケーションで問題が発生した方は[問題を報告](https://github.com/valinet/ExplorerPatcher/wiki/Reporting-problems)してください。
* ぜひ、[ソースコード](https://github.com/valinet/ExplorerPatcher/tree/master) をチェックして、色々といじってみてください。私は、新しい機能、拡張、修正をマージすることに前向きです。また、この分野で関心のあるトピックについて良い洞察が得られると思います。

## 既知の問題

"Bug"と表示されている項目の中で、"open"になっていない物は既知の問題です。さらに"investigating"とマークされている項目は積極的な調査が行われています。
特に"help wanted"となっている項目は助けが必要です。[issue](https://github.com/valinet/ExplorerPatcher/issues)を参照してください。

## アンインストール
アンインストールは以下の方法になります
* コントロールパネルの「プログラムと機能」、または設定アプリの「アプリと機能」でアンインストール
* コマンドプロンプト(Windowsターミナル)で `ep_setup.exe /uninstall` を実行
* `ep_setup.exe` を `ep_uninstall.exe` にファイル名を変更をして実行

## 更新について

* ExplorerPatcherは、アップデート通知機能があります。「プロパティ」-「アップデート」で、最新のアップデートを設定、チェック、インストールができます。詳しくは[こちら](https://github.com/valinet/ExplorerPatcher/wiki/Configure-updates)をご覧ください。
* アップデートは最新版のセットアップファイルをダウンロードし、実行をするだけで更新がされます。

## 詳細

* [仕組みについて](https://github.com/valinet/ExplorerPatcher/wiki/How-does-it-work)
* [ウイルス対策ソフトの誤検知について](https://github.com/valinet/ExplorerPatcher/wiki/Antivirus-false-positives)
* [コンパイルの方法](https://github.com/valinet/ExplorerPatcher/wiki/Compiling)
* [私がExplorerPatcher-jpの開発とリリースをする理由となる記事](https://www.naporitansushi.com/ep11-japanese/)

## 寄付について
valinet氏 (ExplorerPatcher公式の作者)へ寄付は、[PayPal](https://www.paypal.com/donate?business=valentingabrielradu%40gmail.com&no_recurring=0&item_name=ExplorerPatcher&currency_code=EUR) もしくはメール(valentingabrielradu@gmail.com) からお願いします。

creeper-0910 (ExplorerPatcher-jpの作者)へ寄付は、[Github Sponsor](https://github.com/sponsors/creeper-0910)かTwitterのDMからAmazonギフト券を送っていただけるとめちゃくちゃ喜びます。

ExplorerPatcherについての詳細は[こちら](https://github.com/valinet/ExplorerPatcher/wiki)から確認できます。(英語)
