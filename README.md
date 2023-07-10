---
layout: default
title: オープンソースASIC関連リンク集
---
# オープンソースASIC関連リンク集

出典：[github.com/mattvenn/awesome-opensource-asic-resources](github.com/mattvenn/awesome-opensource-asic-resources) 

[用語集](https://zerotoasiccourse.com/terminology/)

## デジタル設計ツール

* [OpenLane](https://openlane.readthedocs.io/en/latest/) - AISCフロー（入り口から出口まで）
* [OpenROAD](https://github.com/The-OpenROAD-Project) - OpenLane を構成するツール群へのリンク集
* [Silicon Compiler](https://www.siliconcompiler.com/) - AISCフロー（入り口から出口まで）をサポートするPythonモジュール
* [Coriolis 2](http://coriolis.lip6.fr/) -- AISCフロー（入り口から出口まで）
* [OSS Cad Suite](https://github.com/YosysHQ/oss-cad-suite-build) -- デジタル設計に有用なオープンソースツールのリンク集
* [VHDL support - with GHDL](https://docs.google.com/document/d/1RAQWjmxpJndlEJdLWXK8irIqWuYTstqu7pU3tOIFccc/edit) -- Yosys GHDL プラグイン
* [Awesome list of verification tools](https://github.com/troyguo/awesome-dv) -- 設計検証系のオープンソースツールのリンク集
* [Awesome list of HDL tools / libraries / cores ...](https://hdl.github.io/awesome/)　-- オープンソースツール・ライブラリ等の広範なリンク集
* [SemiWiki's list of open EDA tools](https://semiwiki.com/wikis/industry-wikis/eda-open-source-tools-wiki/) -- オープンソースツールのWiki
* [Andreas' list of awesome hardware tools](https://github.com/aolofsson/awesome-hardware-tools) -- Andreaさんのオープンハードウェア関連リンク集

## 高位合成関連ツール (HLS)

* [Amaranth Document](https://amaranth-lang.org/docs/amaranth/latest/) -- RTL設計のための Python ライブラリー [GitHub](https://github.com/amaranth-lang) 
* [XLS](https://google.github.io/xls/) -- Google がインハウスで開発していた高位合成言語
* [Spinal Document](https://spinalhdl.github.io/SpinalDoc-RTD/master/index.html) -- 高位合成言語 [GitHub](https://github.com/SpinalHDL/SpinalHDL)

## ロジック系 回路シミュレータ

* [GHDL](https://github.com/ghdl/ghdl) -- VHDLシミュレータ
* [Valigator](https://github.com/verilator/verilator)　-- SystemVerilog シミュレータ
* [Icarus Verilog](https://github.com/steveicarus/iverilog)　-- Verilog シミュレータ
* [IRSIM](http://opencircuitdesign.com/irsim/index.html) -- スイッチ レベル Tr シミュレータ
* [OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA) -- 静的タイミング解析(STA)ツール
* [Meep](https://github.com/NanoComp/meep) -- 有限差分時間領域法(FTDT)の電磁界解析シミュレータ
* [Fault](https://github.com/AUCOHL/Fault) -- テスト容易化設計(DFT)ツール

## アナログ系 回路シミュレータ

* [Ngspice](http://ngspice.sourceforge.net/) -- Spice シミュレータ
* [Xyce](https://xyce.sandia.gov/) -- Spice シミュレータ

## カスタム回路設計ツール

* [Magic](http://opencircuitdesign.com/magic/) -- 古くから有名な Layout 設計ツール, 最近のフローでも活用。[コマンド表](https://github.com/hpretl/iic-osic/blob/main/magic-cheatsheet/magic_cheatsheet.pdf).
* [Klayout](https://www.klayout.de/) -- 現代版、レイアウト設計ツール
* [Xschem](https://xschem.sourceforge.io/stefan/index.html) -- 古くからある、回路入力ツール
* [Xcircuit](https://github.com/RTimothyEdwards/xcircuit/) -- 現代版、回路入力ツール
* [Mosaic](https://nyancad.github.io/Mosaic/) -- Webベース回路入力ツール
* [gdsfactory](https://gdsfactory.github.io/gdsfactory/) -  回路入力からGDSIIまでのチップ設計用 Python モジュール

## 物理検証ツール

* [GDS2Para](https://github.com/purdue-onchip/gds2Para) -- レイアウトパラメータ抽出(LPE)
* [OpenRCX](https://github.com/The-OpenROAD-Project/OpenRCX) -- レイアウトパラメータ抽出(LPE)
* [netgen](https://github.com/RTimothyEdwards/netgen) -- レイアウト対回路比較(LVS)
* [CVC](https://shuharisystem.com/?page_id=185) --　回路妥当性検証(CVC) [GitHub](https://github.com/d-m-bailey/cvc)

## FPGA関連ツール
* [OSFPGA](https://github.com/os-fpga) -- FPGAフロー(入り口から出口まで)
* [F4PGA](https://github.com/chipsalliance/f4pga) -- ChipAllianceによるFPGAフロー(入り口から出口まで)
* [OpenFPGALoader](https://github.com/trabucayre/openFPGALoader) -- FPGAへの書き込みツール
* [VTR](https://github.com/verilog-to-routing/vtr-verilog-to-routing) -- FPGA向けP&Rツール
* [nextprn](https://github.com/YosysHQ/nextpnr) -- FPGA向けタイミングドリブンP&Rツール
* [FASM](https://github.com/chipsalliance/fasm) -- FPGA Assembly(FASM)言語向けツール


## 自動生成系ツール

* [OpenRAM](https://openram.soe.ucsc.edu/) -- SRAM コンパイラー
* [DFFRAM](https://github.com/Cloud-V/DFFRAM) -- FF/Latchを使ったメモリーコンパイラー
* [OpenFASoC](https://github.com/idea-fasoc/OpenFASOC) -- アナログIP自動発生ツール(電源降圧回路、温度センサー等)
* [MOSAIC_BAG2](https://mosaic_group.gitlab.io/mosaic_BAG/virtuoso_template) -- Berkeley Analog Generator(BAG)フレームワーク [GitHub](https://gitlab.com/mosaic_group/mosaic_BAG/virtuoso_template)
* [RgGen](https://github.com/rggen/rggen) - 設定レジスタ(CSR)自動発生ツール(SystemVerilog/Verilog/VHDL RTL, UVM reg model etc)

## PDK (Process Design Kit)

* [Sky130](https://skywater-pdk.readthedocs.io/en/main/)
* [GF180](https://github.com/google/gf180mcu-pdk)
* [iHP130](https://github.com/IHP-GmbH/IHP-Open-PDK)
* Watch this space!

## コミュニティ

* [Slack](https://join.slack.com) -- オープンソースシリコンのSlack #japan_region:日本語チャネル有り
* [VLSI.JP](https://vlsi.jp/) -- 日本語によるオープンソースEDAでの設計例
* [VSD VLSI courses on Udemy](https://www.udemy.com/course/vlsi-academy-custom-layout/) -- Udemy のVLSI設計コース(有料)

## 動画

* [Asianometry - the promise of open source EDA tools](https://www.youtube.com/watch?v=OmEbzRp_NGg) -- OpenEDA の背景説明 (日本語のCCあり)

## Google OpenSilicon 関連

* [Quickstart guide](https://caravel-user-project.readthedocs.io/en/latest/quickstart.html) -- CARAVEL での設計プロジェクトの始め方
* Slack のコミュニティ [ココ](https://join.slack.com/) に参加しましょう！
* FAQ は、[ココ](https://docs.google.com/document/d/1Y7LuP_0dJ_vmD8G_Twc6qc97fj7aW5pRV5nAjN2oOUk/edit#heading=h.dabsoa4nkp71)
* 寄託されたプロジェクトは、[ココ](https://platform.efabless.com/projects/public) 
* [プレゼンテーション: Google + Analog](https://bit.ly/goog-analog)
* [プレゼンテーション: Google + NIST](https://bit.ly/goog-nist)
* [プレゼンテーション: SERDES, PIPE and protocols](https://bit.ly/open-pipe-talk)
* [プレゼンテーション: Open source (e)FPGA generators](https://bit.ly/goog-fpga-22q3)
* [プレゼンテーション: A fully OSS memory controller with LPDDR4/5 support](https://bit.ly/ops21-litedram)
* [プレゼンテーション: 15th Oct 2022 @VSDOpen Conference](https://bit.ly/vsdopen22-goog) -- 動画は、[ココ](https://bit.ly/vsdopen22-goog-video)
* [プレゼンテーション: 24th Apr 2022 @CICC](https://bit.ly/cicc22-edu-goog)

## 学会関連

* [The open source digital design conference](https://orconf.org/) -- ORConf へのリンク
* [Open Tapeout Conference](https://www.youtube.com/playlist?list=PLyynFETmdQDQdLCIu_HJBFNY17AAFp5W7) -- YouTube 配信集
* [FOSSi events:](https://www.fossi-foundation.org/events) -- FOSSi のイベントページへのリンク
* [Free silicon conference](https://wiki.f-si.org/index.php?title=Main_Page) -- FSiC へのリンク

## 記事

* [The Register](https://www.theregister.com/2020/07/03/open_chip_hardware/) -- Google OpenSilicon 関連記事
* [Medium](https://medium.com/librecores) -- LibreCore の Medium ページへのリンク

## Zero to ASIC 関連（Matthew Venn :本リンク集の原作者が運営）

* [Zero To ASIC course](https://zerotoasiccourse.com/) -- 「Zero to ASIC」ホームページ
* [Zero to ASIC course videos](https://www.youtube.com/zerotoasic) -- 「Zero to ASIC」コース動画
* [Zero to ASIC Twitter](https://twitter.com/matthewvenn/lists) -- 「Zero to ASIC」Twitterのリンク集
* [Zero to ASIC newsletter](https://zerotoasiccourse.com/newsletter/) -- 「Zero to ASIC」ニュースレタへのリンク
* [Zero to ASIC post](https://zerotoasiccourse.com/post/) -- 「Zero to ASIC」の関連文献へのリンク

## 関連グループ

* [FOSSi](https://www.fossi-foundation.org/) -- FOSSi Foundation は、フリーでオープンなデジタルハードウェア設計とその関連エコシステムを促進および支援することを目的とする非営利財団
* [Chips Alliance](https://chipsalliance.org/) -- CHIPS (Common Hardware for Interfaces, Processors and Systems) Alliance は、オープンソースの連携力によりハードウェア開発を加速する団体
* [WOSET](https://woset-workshop.github.io/) -- WOSET ワークショップは、オープンソースEDA運動を活性化することを目的とする団体

## 関連企業

* [ChipFlow](https://www.chipflow.io/) -- オープンソースツールを使用して独自のチップを製造できるように支援する会社
* [Efabless](https://efabless.com/) -- オープンソースツールを使用してシャトルサービスを展開する会社
* [LibreSilicon](https://libresilicon.com/) -- オープンソースの製造プロセス標準を提供する会社
* [lowRISC](https://lowrisc.org/open-silicon/) -- オープンソースのシリコン設計とツールを開発および維持する非営利企業
* [Skywater Technology](https://www.skywatertechnology.com/) -- 米国投資家所有の半導体ファウンドリー OpenPDK(SKy130nm)をサポート
* [OpenHW Group](https://www.openhwgroup.org/) -- オープンソースハードウェア開発のプラットフォームを提供する非営利のグローバル組織
* [YosysHQ](https://www.yosyshq.com/) -- YOSYS 関連のサポートチームのホームページへのリンク
* [ZeroASIC](https://www.zeroasic.com/) -- ASICツールフロー向けシリコンコンパイラ開発企業
* [Symbiotic](https://www.symbioticeda.com/) -- YOSYS ベースのカスタムツール開発企業

## 現在進行形

* [Luna PnR](https://github.com/asicsforthemasses)
