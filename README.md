# オープンソースASIC関連リンク集

[用語集](https://zerotoasiccourse.com/terminology/)

## デジタル設計ツール

* [OpenLane](https://openlane.readthedocs.io/en/latest/) - AISCフロー（入り口から出口まで）
* [OpenROAD](https://github.com/The-OpenROAD-Project) - OpenLane を構成するツール群へのリンク集
* [Silicon Compiler](https://www.siliconcompiler.com/) - AISCフロー（入り口から出口まで）をサポートするPythonモジュール
* [Coriolis 2](http://coriolis.lip6.fr/) - AISCフロー（入り口から出口まで）
* [OSS Cad Suite](https://github.com/YosysHQ/oss-cad-suite-build) - デジタル設計に有用なオープンソースツールのリンク集
* [VHDL support - with GHDL](https://docs.google.com/document/d/1RAQWjmxpJndlEJdLWXK8irIqWuYTstqu7pU3tOIFccc/edit) Yosys GHDLプラグイン
* [Awesome list of verification tools](https://github.com/troyguo/awesome-dv) 設計検証系のオープンソースツールのリンク集
* [Awesome list of HDL tools / libraries / cores ...](https://hdl.github.io/awesome/)　オープンソースツール・ライブラリ等の広範なリンク集
* [SemiWiki's list of open EDA tools](https://semiwiki.com/wikis/industry-wikis/eda-open-source-tools-wiki/)オープンソースツールのWiki
* [Andreas' list of awesome hardware tools](https://github.com/aolofsson/awesome-hardware-tools)Andreaさんのオープンハードウェア関連リンク集

## 高位合成関連ツール (HLS)

* [Amaranth](https://github.com/amaranth-lang)
* [XLS](https://google.github.io/xls/)
* [Spinal](https://github.com/SpinalHDL/SpinalHDL)

## ロジック系 回路シミュレーター

* [GHDL](https://github.com/ghdl/ghdl) -- VHDLシミュレーター
* [Valigator](https://github.com/verilator/verilator)
* [Icarus Verilog](https://github.com/steveicarus/iverilog)
* [IRSIM](http://opencircuitdesign.com/irsim/index.html) -- Switch level Tr simulator
* [OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA) -- STA tool
* [Meep](https://github.com/NanoComp/meep) -- FTDT simulator
* [Fault](https://github.com/AUCOHL/Fault) -- DFT tool

## アナログ系 回路シミュレーター

* [Ngspice](http://ngspice.sourceforge.net/) - Spice simulation
* [Xyce](https://xyce.sandia.gov/) - Spice simulation

## カスタム回路設計ツール

* [Magic](http://opencircuitdesign.com/magic/) - old school, layout drawing tool; still a requirement in the modern flows. [Cheatsheet](https://github.com/hpretl/iic-osic/blob/main/magic-cheatsheet/magic_cheatsheet.pdf).
* [Klayout](https://www.klayout.de/) - modern style layout drawing tool.
* [Xschem](https://xschem.sourceforge.io/stefan/index.html) - old school, schematic capture
* [Xcircuit](https://github.com/RTimothyEdwards/xcircuit/) - schematic capture
* [Mosaic](https://nyancad.github.io/Mosaic/) - schematic capture (experimental)
* [gdsfactory](https://gdsfactory.github.io/gdsfactory/) -  EDA tool to Layout and simulate Integrated Circuits.

## 物理検証ツール

* [GDS2Para](https://github.com/purdue-onchip/gds2Para) -- LPE
* [OpenRCX](https://github.com/The-OpenROAD-Project/OpenRCX) -- LPE
* [netgen](https://github.com/RTimothyEdwards/netgen) -- LVS
* [CVC](https://github.com/d-m-bailey/cvc) -- Circuit Validity Check tool.

## FPGA関連ツール
* [OSFPGA](https://github.com/os-fpga) - end to end FPGA flow with open source tools such as Yosys, VTR and VPR
* [F4PGA](https://github.com/chipsalliance/f4pga) - end to end FPGA flow by ChipAlliance
* [OpenFPGALoader](https://github.com/trabucayre/openFPGALoader)
* [VTR](https://github.com/verilog-to-routing/vtr-verilog-to-routing)
* [nextprn](https://github.com/YosysHQ/nextpnr)
* [FASM](https://github.com/chipsalliance/fasm)


## 自動生成系ツール

* [OpenRAM](https://openram.soe.ucsc.edu/) - SRAM generator
* [DFFRAM](https://github.com/Cloud-V/DFFRAM) - Memory Compiler using FF/Latch cells
* [OpenFASoC](https://github.com/idea-fasoc/OpenFASOC) - Analogue IP generator (LDO, temperature sense etc)
* [MOSAIC_BAG2](https://gitlab.com/mosaic_group/mosaic_BAG/virtuoso_template) - Analogue IP generator framework (w/minimum working example)
* [RgGen](https://github.com/rggen/rggen) - CSR generator (SystemVerilog/Verilog/VHDL RTL, UVM reg model etc)

## PDK (Process Design Kit)

* [Sky130](https://skywater-pdk.readthedocs.io/en/main/)
* [GF180](https://github.com/google/gf180mcu-pdk)
* [iHP130](https://github.com/IHP-GmbH/IHP-Open-PDK)
* Watch this space!

## コミュニティ

* [Skywater PDK Slack](https://join.slack.com/t/skywater-pdk/shared_invite/zt-ggcxts4x-4V5AwC950Zv9YgbZ4g~sMQ)
* [Twitter list](https://twitter.com/i/lists/1510948904736628736)


## 動画

* Zero to ASIC course videos, interviews, news [https://www.youtube.com/zerotoasic](https://www.youtube.com/zerotoasic) 
* Asianometry - the promise of open source EDA tools [https://www.youtube.com/watch?v=OmEbzRp_NGg](https://www.youtube.com/watch?v=OmEbzRp_NGg) 

## Google OpenSilicon 関連

* [Quickstart guide](https://caravel-user-project.readthedocs.io/en/latest/quickstart.html)
* Then [join the community slack](https://join.slack.com/t/skywater-pdk/shared_invite/zt-ggcxts4x-4V5AwC950Zv9YgbZ4g~sMQ) #shuttle & #caravel channels.
* Check the [FAQ](https://docs.google.com/document/d/1Y7LuP_0dJ_vmD8G_Twc6qc97fj7aW5pRV5nAjN2oOUk/edit#heading=h.dabsoa4nkp71)
* See the projects submitted here: [https://platform.efabless.com/projects/public](https://platform.efabless.com/projects/public) 

## 学会関連

* [The open source digital design conference](https://orconf.org/)
* OpenTapeout [https://www.youtube.com/playlist?list=PLyynFETmdQDQdLCIu_HJBFNY17AAFp5W7](https://www.youtube.com/playlist?list=PLyynFETmdQDQdLCIu_HJBFNY17AAFp5W7) 
* FOSSi events: [https://www.fossi-foundation.org/events](https://www.fossi-foundation.org/events) 
* Free silicon conference: [https://wiki.f-si.org/index.php/FSiC2022](https://wiki.f-si.org/index.php/FSiC2022)

## 講義

* [Zero To ASIC course](https://zerotoasiccourse.com/)
* [VSD VLSI courses on Udemy](https://www.udemy.com/course/vlsi-academy-custom-layout/)
* [Google + Analog](https://bit.ly/goog-analog)
* [Google + NIST](https://bit.ly/goog-nist)
* [SERDES, PIPE and protocols](https://bit.ly/open-pipe-talk)
* [Open source (e)FPGA generators](https://bit.ly/goog-fpga-22q3)
* [A fully OSS memory controller with LPDDR4/5 support](https://bit.ly/ops21-litedram)
* [Presentation on 15th October 2022 @ VSDOpen 22 Conference](https://bit.ly/vsdopen22-goog)
        [with recording](https://bit.ly/vsdopen22-goog-video)
* [Presentation on 24th April 2022@CICC](https://bit.ly/cicc22-edu-goog)

## 文献

* [https://www.theregister.com/2020/07/03/open_chip_hardware/](https://www.theregister.com/2020/07/03/open_chip_hardware/)
* [http://olofkindgren.blogspot.com/2019/12/2019-year-of-risc-v-and-open-source.html](http://olofkindgren.blogspot.com/2019/12/2019-year-of-risc-v-and-open-source.html) 
* [https://zerotoasiccourse.com/post/](https://zerotoasiccourse.com/post/) 

## メイリングリスト・ニュースレター

* El correo libre: [https://medium.com/librecores/el-correo-libre-issue-46-11028b1d0e63#ead0](https://medium.com/librecores/el-correo-libre-issue-46-11028b1d0e63#ead0) 
* [https://zerotoasiccourse.com/newsletter/](https://zerotoasiccourse.com/newsletter/) 

## 関連グループ

* [FOSSi](https://www.fossi-foundation.org/) - FOSSi Foundation is a non-profit foundation with the mission to promote and assist free and open digital hardware designs and their related ecosystems. 
* [Chips Alliance](https://chipsalliance.org/) - CHIPS (Common Hardware for Interfaces, Processors and Systems) Alliance harnesses the energy of open source collaboration to accelerate hardware development
* [WOSET](https://woset-workshop.github.io/) - The WOSET workshop aims to galvanize the open-source EDA movement.
* [Slack:open-source-silicon.dev](https://open-source-silicon.slack.com/)

## 関連企業

* [ChipFlow](https://www.chipflow.io/) - Helping product companies to make their own chips with open source tools
* [Efabless](https://efabless.com/) - simplifying chip creation
* [LibreSilicon](https://libresilicon.com/) - open source manufacturing process standard
* [LowRISC](https://lowrisc.org/open-silicon/) - open source silicon designs and tools
* [Skywater Technology](https://www.skywatertechnology.com/) - foundry that first published open source PDK
* [OpenHW Group](https://www.openhwgroup.org/) - open-source cores, verification, software and standards
* [YosysHQ](https://www.yosyshq.com/) - open source EDA & Formal Verification
* [ZeroASIC](https://www.zeroasic.com/) - makers of silicon compiler ASIC tool flow

## 現在進行形

* [Luna PnR](https://github.com/asicsforthemasses)
