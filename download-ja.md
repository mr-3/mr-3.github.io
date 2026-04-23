---
layout: ja_page
ja_title: ダウンロード
permalink: /download-ja.html
---

* [MR<sup>3</sup>のインストーラ](https://github.com/mr-3/MR3/releases) 

# インストール方法
## Windows
1. [Microsoft StoreのMRCubeのページ]( https://apps.microsoft.com/detail/9nmgtwtl1fvg?hl=ja-JP&gl=JP) にアクセスし，「Microsoft Store で見る」ボタンをクリックする． 
2. 「インストール」ボタンをクリックする．
3. デスクトップに作成されるショートカットを実行する．

## macOS (dmgファイル)
1. [ダウンロードページ](https://github.com/mr-3/mrcube/releases) から **mrcube-26.4.3.dmg** をダウンロードしてファイルを開く．
2. 「MRCube.app」をApplicationsディレクトリにドラッグアンドドロップし，「MRCube.app」を実行する．
3. 「“MRCube”はインターネットからダウンロードされたアプリケーションです。開いてもよろしいですか?」と表示されるため，「開く」ボタンをクリックする．

## macOS (Homebrew)
1. [Homebrew](https://brew.sh/) をインストールする．
2. ターミナル.appから ``brew tap mr-3/tap`` と ``brew install --cask mrcube`` を実行する．
3. Applicationsディレクトリの中の「MRCube.app」を実行する．
4. 「“MRCube”はインターネットからダウンロードされたアプリケーションです。開いてもよろしいですか?」と表示されるため，「開く」ボタンをクリックする．

# ライセンス
MR<sup>3</sup>はフリーソフトウェアです．Free Software Foundation による [GNU Generic Public License](http://www.gnu.org/copyleft/gpl.html) のバージョン2 （または，それ以降のバージョン）に従う限り自由に変更し再配布することができます．

# 利用ライブラリ
* [Liberica Standard JDK](https://bell-sw.com/pages/downloads/#jdk-21-lts) ([License](https://bell-sw.com/liberica_eula/))
* [FlatLaf - Flat Look and Feel](https://www.formdev.com/flatlaf/) ([License](http://www.apache.org/licenses/LICENSE-2.0))
* [JGraph and JGraphAddons](http://www.jgraph.com/) ([License](https://github.com/jgraph/legacy-jgraph5/blob/master/LICENSE)]
* [Apache Jena](https://jena.apache.org/) ([License](http://www.apache.org/licenses/LICENSE-2.0))
* [Apache Batik SVG Toolkit](https://xmlgraphics.apache.org/batik/) ([License](https://xmlgraphics.apache.org/batik/license.html))
* [Drawing Graphs with VGJ](http://www.eng.auburn.edu/department/cse/research/graph_drawing/graph_drawing.html) ([License](http://www.eng.auburn.edu/department/cse/research/graph_drawing/COPYING))
* [Material Design icons by Google](https://github.com/google/material-design-icons) ([License](https://www.apache.org/licenses/LICENSE-2.0.txt))
* [Badass Runtime Plugin](https://github.com/beryx/badass-runtime-plugin) ([License](https://www.apache.org/licenses/LICENSE-2.0.txt))
* [Shadow](https://github.com/GradleUp/shadow) ([License](https://www.apache.org/licenses/LICENSE-2.0.txt))


# 謝辞
* 上田俊夫 様より，多大なご助言をいただきました
* 程涛 様 より，[中国語版言語ファイル](https://github.com/mr-3/mrcube/blob/master/src/main/resources/MR3_zh.properties) (MR<sup>3</sup> 1.0RC5以降には組み込まれています)を作成いただきました
