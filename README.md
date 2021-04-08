
askw3 package
=================

個人マクロ集。

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

MITライセンスの下で配布される。

------------------------
Ryoya Ando
https://github.com/ryoya9826
