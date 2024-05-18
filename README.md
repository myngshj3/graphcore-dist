# graphcore-dist
GraphCore binary distribution repository

Japanese follows English

[English Version]

This repository is open to present GraphCore products, my artifacts.
This repository also will contain binary executable programs and data.
It may contain also source code set for some developers who try building and executing by themselves.

GraphCore PoC version was opened in IPSJ/SIGSE Winter Workshop 2022, and author presented software project analysis using GraphCore simulation tool. This version is exposed in public repository as below.

  https:/github.com/myngshj3/graphcore-poc

You can down load and try this application.

Past GraphCore is located in the graphcore-poc repository to avoid repository name confliction.
Past GraphCore needed Networkml library wich enabled universal network manipulations. NetworkML can be implemented as interpreter in your own application and GraphCore employed NetworkML as its interpreter.
However, in current release, NetworkML is not under maintenance and GraphCore contains NetworkML as parts of functionalities.
 
GraphCore-Lite:

GraphCore-Lite is a GraphCore Light-weight Edition which enables us to manipulate and analyze network structure and also simulate discrete network system.
Current release of GraphCore-Lite contains no Window-UI based functionality and supports only command-line interfacd (CLI).

To boot GraphCore-Lite edition in current release, type as the following:

PROMPT> graphcore

Here 'graphcore' command is binary distributed program and you don't need to install and setup for your own environment.

For more detail, see doc/UserManual.txt.



[日本語版]

このリポジトリは筆者の成果物、現在の GraphCore プロダクトを公開しています。
このリポジトリはバイナリ実行プログラムとデータを含みます。
また、自分でビルドし実行しようとする開発者のために、ソースコードのセットを公開するかもしれません。

GraphCore PoC バージョンは、IPSJ/SIGSE Winter Workshop 2022 にて公開されました。
そして筆者は、GraphCoreのシミュレーションツールを用いたソフトウェアアプロジェクト分析を発表しました。このバージョンは、以下のGitHubのディレクトリに保存されています。

  https:/github.com/myngshj3/graphcore-poc

このリポジトリのメインテンス予定はありません。

以前の GraphCore は graphcore-poc に保存されています。リポジトリ名のコンフリクトを避けるためです。
以前の GraphCore は 一般的なネットワークを操作するためのライブラリ NetworkML を必要としていました。NetworkMLはあなたのアプリケーションの中でインタープリターとして実装でき、GraphCore もまた NetworkML をインタープリターとして実装しています。
しかし現在のリリースでは、NetworkMLはメンテナンスされておらず、GraphCoreの機能の一部として取り込まれています。
 
GraphCore-Lite:

GraphCore-Lite は GraphCore の軽量版で、ネットワークの操作や分析、また、分散ネットワークシステムのシミュレーションが可能です。
現在は、GUIベースの機能を含んでおらず、コマンドラインインターフェース(CLI)のみの提供となります。

GraphCore-Lite を起動するには、以下のようにタイプします。

PROMPT> graphcore

ここで、'graphcore' コマンドはバイナリで配布されるプログラムで、自分でインストールしたり自分の環境でセットアップしたりする必要はありません。

コマンドの詳細は doc/UserManual.txt をご覧ください。
