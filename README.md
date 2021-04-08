
askw3 package
=================

個人マクロ集。

### 開発履歴

#### v0.0, 2017/01/22
開発開始．
#### v1.0, 2018/10/10
公開．
#### v1.1, 2019/10/31
環境追加．itemize 系，eqv 環境．
#### v1.11, 2020/01/06
パッケージオプションを（ほとんど）廃止して \askwoption を使用することに．Bug
fix．
#### v2.0, 2020/05/01
\makethm を正式に追加．
#### v2.1, 2021/03/10
tlarray パッケージへの依存関係を解消. 人名索引機能 (\namelabelOP) を追加．

### 前提環境

* TeX エンジン： pTeX/upTeX
	- Yato (aka. "ZR")氏による"BXjscls"パッケージバンドルのもとで　LuaTeX,XeTeX
* フォーマット： LaTeX, (bx)jsclsを想定
* DVI ウェア： 不問（pTeX系列の場合はdvipdfmxを想定）
* 必須パッケージ
	- xkeyval
	- iftex
	- bxghost
	- ascmac
	- amsmath,amssymb,amsthm
	- etoolbox
* "links"オプションで読み込むパッケージ
	- hyperref
	- （場合により）pxjahyper

### 構成物
* `askw3.pdf`：説明書（DocStrip 文書）
* `askw3.dtx`： DocStrip ソースファイル
* `askw3.ins`： DocStrip インストーラファイル

### インストール

$ latex askw3.ins

$ mktexlsr	（必要に応じて）

### 使用方法

説明書を参照されたい。

### ライセンス

修正BSDライセンスの下で配布される。

------------------------
Ryoya Ando
https://github.com/ryoya9826
