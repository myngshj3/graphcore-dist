# graphcore-dist
GraphCore binary distribution repository

Japanese follows English

This repository is open to present GraphCore products, my artifacts.
This repository also will contain binary executable programs and data.
It may contain source code set for some developers who try building and executing by theirselves.

GraphCore PoC version was opened in IPSJ/SIGSE Winter Workshop 2022, and author presented software projecc analysis using GraphCore simulation tool. This version is opened in public repository https:/github.com/myngshj3/graphcore-poc. You can down load and try this application.
Past GraphCore is located in the graphcore-poc repository to avoid repository name confliction.
Past GraphCore nedded Networkml library wich enabled universal network manipulations. NetworkML can be implemented as interpreter in your kind application and GraphCore employed NetworkML for its interpreter.
However in current release, NetworkML is not under maintenance and GraphCore contains NetworkML as its one of functionality.
 
GraphCore-lite:
GraphCore-lite is a GraphCore Light-weight Edition which enables us to analyze network structure and also simulate discrete network system.
GraphCore contains no Window-UI based functionality and supports only command-line interfacd (CLI).

To boot GraphCore-Lite edition in current release, type as the following:

PROMPT> graphcore

Here 'graphcore' command is binary distributed program and you don't need to install and setup for your own environment.

Belows are simple user manual of GraphCore-Lite program.

Light User Manual:
(1) Download binary executable program and setting file.
Down load binary program located on the Web Site https://github.com/myngshj3/graphcore-lite/dist
Setting file is located on the Web Site https://github.com/myngshj3/graphcore-lite/config

(2) Save downloaded file in the same directory, because graphcore-lite program is supposed setting file is located in the directory in which graphcore-lite binary program.

(3) boot GraphCore-Lite
Type the following command and it's quite easy.
$ python graphcore
if successfully executed, your will see command prompt below,
$>

(4) Load simulation data
Simulation data is/was graphcore-lite/data directory.

(5) Try simulation
Simulation example is exposed, and that simulation uses GraphCore and simulation data data/workflow01.grapb

(6) GraphCore functionalities
Current release of GraphCore-lite has a lot of functionalities but it's too narrow space to present my reasoning.


日本語
このリポジトリは筆者の成果物、現在の GraphCore プロダクトを公開しています。
このリポジトリはバイナリ実行プログラムとデータを含みます。
また、自分でビルドし実行しようとする開発者のために、ソースコードのセットを公開するかもしれません。

GraphCore PoC バージョンは、IPSJ/SIGSE Winter Workshop 2022 にて公開されました。
そして筆者は、GraphCoreのシミュレーションツールを用いたソフトウェアアプロジェクト分析を発表しました。このバージョンは、GitHubのディレクトリ https:/github.com/myngshj3/graphcore-lite に保存されています。このリポジトリのメインテンス予定はありません。

以前の GraphCore は graphcore-poc に保存されています。リポジトリ名のコンフリクトを避けるためです。
以前の GraphCore は 一般的なネットワークを操作するためのライブラリ NetworkML を必要としていました。NetworkMLはあなたのアプリケーションの中でインタープリターとして実装でき、GraphCore もまた NetworkML をインタープリターとして実装しています。
しかし現在のリリースでは、NetworkMLはメンテナンスされておらず、GraphCoreの機能の一部として取り込まれています。
 
GraphCore-lite:
GraphCore-lite は GraphCore の軽量版で、ネットワークの分析や分散ネットワークシステムのシミュレーションが可能です。
現在は、GUIベースの機能を含んでおらず、コマンドラインインターフェース(CLI)のみの提供となります。

GraphCore-Lite を起動するには、以下のようにタイプします。

PROMPT> graphcore

ここで、'graphcore' コマンドはバイナリで配布されるプログラムで、自分でインストールしたり自分の環境でセットアップしたりする必要はありません。

コマンドの詳細は UserManual.txt をご覧ください。
