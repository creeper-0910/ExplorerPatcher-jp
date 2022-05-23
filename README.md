# ExplorerPatcher
このプロジェクトは、Windows上での作業環境を改善することを目的としています。  
これは日本語化されたExplorerPatcherのビルドです！公式のものではないことに注意してください。  
製作者様への寄付: [paypal](https://www.paypal.com/donate?business=valentingabrielradu%40gmail.com&no_recurring=0&item_name=ExplorerPatcher&currency_code=EUR) もしくは[メール](valentingabrielradu@gmail.com) からお願いします。

![Build status](https://github.com/valinet/ExplorerPatcher/actions/workflows/build.yml/badge.svg)

## お礼

最近、沢山の方々がこの日本語化したバージョンを使用してくださっているようでとても嬉しいです!  
翻訳に関しての修正はissueで受け付けておりますので、お気軽にどうぞ!

## 機能の概要

* Windows 11またはWindows 10のタスクバーから選択できます。（ラベルや小さなアイコンなど多くのカスタマイズが可能です)
* Windows 11で変更されたコンテキストメニューとコマンドバーを無効化することができます。
* スタートメニューがデフォルトですべてのアプリを表示するよう変更したり、頻繁に表示するアプリの数を選んだり、アクティブなモニターに表示したりできます。
* Windows 11、Windows 10、Windows NT Alt-Tab window switcherの中から、自由に選択できます。
* シェルの質を向上させるために、以下のような工夫をしています:
  * トレイメニューのスキンをWindowsのスタイルに合わせ、ポップアップするようにし、アイコンに対して中央に配置することができます。
  * ネットワークアイコンを左クリックまたは右クリックしたときの動作を選択します。
  * ファイルエクスプローラーの検索ボックスをWindows7に戻すか、Windows検索を完全に無効化します。
  * イマーシブメニューを無効にし、本物のクラシックテーマを不具合なく動作させるための緩和策を提供します。
  * このプログラムが提供するすべての機能については、Wikiの以下の記事で詳しく説明しています。(https://github.com/valinet/ExplorerPatcher/wiki/All-features)

Windows 10では、一部の機能が使用できない場合があります。

## 使用方法

1. 最新版の[セットアップ用プログラム](https://github.com/creeper-0910/ExplorerPatcher-jp/releases/latest/download/ep_setup.exe)をダウンロードします。
2. インストーラーを実行します。管理者での実行が要求され、その後必要なファイルがインストールされます。
3. 完了すると、見慣れたWindows 10のタスクバーが表示されます。設定を変更するには、タスクバーを右クリックして「プロパティ」を選択します。

ね、簡単でしょ？

## 次は？

* 一度[wiki](https://github.com/valinet/ExplorerPatcher/wiki) を読むことを強くお勧めします。そこにはこのパッチャーが提供する、より高度な機能についての情報があります。
* このパッチャーが提供する機能のほとんどを[ここ](https://github.com/valinet/ExplorerPatcher/wiki/All-features)で知ることができます。
* アップデートの管理方法と、新しいバージョンや新しいWindowsビルドに期待することについては、[こちら](https://github.com/valinet/ExplorerPatcher/wiki/Configure-updates)をご覧ください。
* 質問がある方は[よくある質問](https://github.com/valinet/ExplorerPatcher/wiki/Frequently-asked-questions)をご覧ください。
* 他に質問のある方は[議論](https://github.com/valinet/ExplorerPatcher/discussions)ページにスレッドを立ててください。
* バグを見つけた、もしくはアプリケーションで問題が発生した方は[問題を報告](https://github.com/valinet/ExplorerPatcher/wiki/Reporting-problems)してください。
* ぜひ、[ソースコード](https://github.com/valinet/ExplorerPatcher/tree/master) をチェックして、色々といじってみてください。私は、新しい機能、拡張、修正をマージすることに前向きです。また、この分野で関心のあるトピックについて良い洞察が得られると思います。

## 既知の問題

"Bug"と表示されている項目の中で、"open"になっていないものは既知の問題です。さらに"investigating"とマークされている項目は積極的な調査が行われています。
特に"help wanted"となっている項目は助けが必要です。[issue](https://github.com/valinet/ExplorerPatcher/issues)を参照してください。

## アンインストール方法
以下の方法があります。
* コントロールパネルの「プログラムと機能」、または設定アプリの「アプリと機能」を使う
* コマンドプロンプトで `ep_setup.exe /uninstall` を実行する
* `ep_setup.exe` を `ep_uninstall.exe` にリネームして実行する

## 更新について

* プログラムにはアップデート機能が組み込まれています。「プロパティ」-「アップデート」で、最新のアップデートを設定、チェック、インストールすることができます。詳しくは[こちら](https://github.com/valinet/ExplorerPatcher/wiki/Configure-updates)をご覧ください。
* 最新版のセットアップファイルをダウンロードし、実行するだけです。

## 詳細

* [仕組みについて](https://github.com/valinet/ExplorerPatcher/wiki/How-does-it-work)
* [ウイルス対策ソフトの誤検知について](https://github.com/valinet/ExplorerPatcher/wiki/Antivirus-false-positives)
* [コンパイル方法](https://github.com/valinet/ExplorerPatcher/wiki/Compiling)
* [私が日本語化を始めた理由となる記事](https://www.naporitansushi.com/ep11-japanese/#)
