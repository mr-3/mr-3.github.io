---
layout: ja_page
title: 更新履歴
permalink: /history-ja.html
---
# 20.6.1 (2020-06-14)
* RDFエディタ上の属性ダイアログから，RDFタイプを編集する際にエラーが発生していたのを修正
* その他の変更点については，[GitHub](https://github.com/mr-3/MR3/commits/master)を参照してください

# 20.5.1 (2020-05-27)
* Look and Feelを[FlatLaf - Flat Look and Feel](https://www.formdev.com/flatlaf/)に変更
* jpackageでWindowsとmacOS用のインストーラを作成
* その他の変更点については，[GitHub](https://github.com/mr-3/MR3/commits/master)を参照してください

# 2019.05_1 (2019-05-25)
* SPARQL検索機能を追加
* SVG形式でグラフ画像ファイルを保存する機能を追加
* レンダリングオプションを再実装
* ログファイルが複数生成されていたのを修正
* その他の変更点については，[GitHub](https://github.com/mr-3/MR3/commits/master)を参照してください

# 2019.03_1 (2019-03-06)
* [GitHub](https://github.com/mr-3/MR3/commits/master)を参照してください

# 1.0.1 (2016-04-14)
* [GitHub](https://github.com/mr-3/MR3/commits/master)を参照してください

# 1.0 (2015-03-16)
* [GitHub](https://github.com/mr-3/MR3/commits/master)を参照してください

<h1 id="doc2_1750">1.0 RC5 (2005-12-29)</h1>
<ul>
<li> 中国語でインタフェースの表示が可能になった(東京工業大学の程涛様にMR3_zh.propertiesを作成して頂きました．）</li>
</ul>
<h1 id="doc2_1681">1.0 RC4 (2005-12-19)</h1>
<ul>
<li> RDFエディタでmr3:nilプロパティをプロパティエディタで定義されていないプロパティに変更しようとした時に，メタモデル管理機能によって名前変更と新規作成の両方を尋ねていたのを，新規作成するかどうかのみ尋ねるように修正．</li>
<li> リソースディレクトリをオプションダイアログで設定できるようにした．（デフォルトはインストールディレクトリ/resources．MR3_ドメイン.propertiesファイルを読み込む．）</li>
</ul>
<h2 id="doc2_1692">不具合修正</h2>
<ul>
<li> RDFまたはRDFS要素をコピーした状態で，MR3を再起動した際にペースト時に例外が発生していたのを修正．</li>
<li> 各エディタでコピーした内容を別のエディタでペーストできていたのを修正．(例：クラスをコピーした状態で，RDFエディタにペーストできていた．）</li>
</ul>
<h1 id="doc2_1705">1.0 RC3 (2005-12-04)</h1>
<ul>
<li> Turtleのインポート，エクスポートができるようになった</li>
<li> N3-PP, N3-PLAIN, N3-TRIPLEのエクスポートができるようになった</li>
<li> エクスポートダイアログにUTF-8でURLエンコードするオプションを追加</li>
</ul>
<h2 id="doc2_1719">不具合修正</h2>
<ul>
<li> コピーしたブランクノードのＩＤが同一になっていたのを修正</li>
<li> インポート中に例外が発生した時に，インポートダイアログを閉じるように修正．</li>
<li> ローカル名が数字からはじまるリソースの名前空間を獲得できていなかったのを修正．</li>
<li> rdf:liプロパティをRDFモデル作成に利用するとエラーが起きていたのを修正.</li>
<li> インポートダイアログで1度追加したフォルダが，再起動後に消える場合があったのを修正．</li>
<li> デフォルトのプラグインディレクトリを指定した状態で，オプションダイアログで適用ボタンを押すと例外が発生していたのを修正．</li>
</ul>
<h1 id="doc2_1744">1.0 RC2 (2005-10-31)</h1>
<ul>
<li> jdk 5以上のみで動作するようになった</li>
<li> vowlidatorを利用して，モデルの整合性チェックをできるようにした．</li>
<li> プロジェクト情報（リソース数・クラス数など）を表示できるようにした．</li>
<li> デフォルトのクラスクラス・プロパティクラスを設定できるようにした．(Tools-&gt;OptionsのMeta Classメニュー）</li>
<li> Undo/Redoの簡易実装</li>
<li> 設定ダイアログとアトリビュートダイアログのインタフェースを修正</li>
<li> RDFプロパティ（ラベル）の表示・非表示機能を追加</li>
<li> ２リソース間に複数プロパティをあたえる場合に，重ならないようにレイアウトできるようになった．</li>
<li> 標準エラー出力発生時にMR3LogConsoleを表示するように修正．</li>
<li> RDFSの置き換えで，RDFエディタで編集をしていない場合にはダイアログを表示せずに置き換えるように変更．</li>
<li> DataTypeを切り替えた時にインポートダイアログのファイルのリストの位置を保存するようにした</li>
<li> プロパティのIDをインクリメンタルサーチできるようにした．</li>
<li> インポート時に新規プロジェクトを実行するようにした</li>
<li> プログレスバーをステータスバーに表示するように変更．</li>
<li> JGraphのバージョンを5.4.7にアップ．</li>
<li> Jenaのバージョンを2.3にアップ．</li>
<li> JGraphAddons(ver 1.0.8)を利用</li>
<li> プラグインマネージャーを表示するためのツールバーのアイコンを追加</li>
<li> メニューを整理した</li>
<li> mr3:Property, mr3:nil, rdfs:Resource, rdfs:Literalを自動的に作成しないようにした．</li>
<li> エクスポートダイアログで，ファイル保存時に.owl拡張子で保存可能になった．</li>
<li> その他，細かい修正．</li>
</ul>
<h2 id="doc2_1815">不具合修正</h2>
<ul>
<li> プロパティエディタで，ノードではなくエッジを選択した状態で，RDFモデルのリソース間をプロパティで接続すると例外が発生していたのを修正．</li>
<li> いくつかの警告ダイアログがウィンドウの後ろに隠れて見えなくなっていたを修正．</li>
<li> インポートダイアログで，Linuxのドットフォルダを選択できなかったのを修正．</li>
<li> domainとrange追加がうまく行えなかったのを修正．</li>
<li> リソースのタイプを表示した状態でグラフの整列をすると，リソースのタイプが整列されていなかったのを修正．</li>
<li> リソースのタイプを表示にした状態でインポートやプロジェクトを開くことができなかったのを修正．</li>
<li> プロジェクトセーブ時にセーブするファイルが指定されていない場合にエラーを表示するように修正．</li>
<li> １度MR3LogConsoleを開くまで，標準出力，標準エラー出力が出力されていなかったのを修正．</li>
<li> プロジェクト保存時に，リテラルのデータタイプが設定されていない場合にエラーが表示されていたのを修正．</li>
<li> RDFプロパティに対応するRDFSプロパティを削除した時，RDFプロパティのURI(Label)の表示が消えていたのを修正．</li>
<li> プラグインディレクトリの設定時にエラーが発生していたのを修正．</li>
</ul>
<h1 id="doc10_13670">1.0 RC1 (2004-02-26)</h1>
<ul>
<li> ユーザインタフェースを全体的に改良．</li>
<li> ショートカットキーを設定．</li>
<li> クラスエディタでクラスを一つ選択した状態でRDFリソースを挿入するとそのクラスをタイプとする　RDFリソースを挿入できるようになった．</li>
<li> プロパティエディタでプロパティを一つ選択した状態でRDFリソース間を接続すると，そのプロパティを　ＲＤＦプロパティとするようになった．</li>
<li> RDFリソースのラベルとコメントを編集できるようになった．(RDFグラフにrdfs:labelとrdfs:commentが　定義されている場合には，ラベルテーブルとコメントテーブルに読み込まれる）</li>
<li> ウィンドウのレイアウトの種類を２つ増やした．</li>
<li> リソースのタイプをまとめて変換できるようになった．</li>
<li> RDFプロパティをまとめて変換できるようになった．</li>
<li> 各グラフをレイアウトするボタンをツールバーに追加．</li>
<li> ソースダイアログをエクスポートダイアログに変更．エクスポートダイアログからエクスポートするようになった．</li>
<li> インポートダイアログからインポートするように変更．</li>
<li> RDFのマージで，RDFS(クラス＋プロパティ）をクラスエディタとプロパティエディタに表示していたのを，　すべてRDFとして読み込むように変更．</li>
<li> Java Web Start版とアプリケーション版の設定を別々にした．</li>
<li> リソース検索ダイアログ改良して同時に各エディタのリソースを検索できるようにした．</li>
<li> ツールバーに検索フィールドを追加．Alt+/でフォーカスを合わせることができる．</li>
<li> プラグインAPIにgetClassTreeModelとgetPropertyTreeModelを追加．</li>
<li> Jenaのバージョンを2.1にアップ．</li>
<li> その他，細かい修正．</li>
</ul>
<h2 id="doc10_13729">不具合修正</h2>
<ul>
<li> 無名ノードがリテラルを持つ時に，レイアウトがうまくできないことがあったのを修正．</li>
<li> インポート時にすべての内部フレームが見えなくなっていたのを修正．（エディタのみを隠すようにした）</li>
<li> RDFリソースのタイプが自動でサイズ変更していなかったのを修正．</li>
</ul>
<h1 id="doc10_13745">Beta3.1 (2004-01-24)</h1>
<ul>
<li> リソースを編集するときに修正をリセットできるようにした．</li>
<li> プラグインマネージャーからプラグインを起動するように変更した．</li>
</ul>
<h2 id="doc10_13756">不具合修正</h2>
<ul>
<li> <em>名前空間テーブルに登録されていない名前空間をもつＲＤＦリソースを入力すると プロジェクトファイルを開くことができなくなっていたのを修正．</em></li>
<li> <em>RDFの置き換えを行った後に，置き換える前に使われていたリソースを挿入できなくなっていた のを修正．</em></li>
<li> 同じ文字列のリテラルのレイアウトがうまくできていなかったのを修正．</li>
<li> 起動時に設定ダイアログのノードサイズの自動と固定の選択が正しく行われていなかったのを修正．</li>
</ul>
<h1 id="doc10_13781">Beta3 (2004-01-22)</h1>
<ul>
<li> VGJTreeLayoutで，各エディタのノードの水平方向と垂直方向の間隔を指定できるようになった．</li>
<li> 各グラフを再レイアウトできるようになった．</li>
<li> WindowsでエクスプローラからRDFsファイルをエディタにドロップして，RDFsをマージできるようになった．</li>
<li> SourceDialogにRDF, Class, PropertyをRDF/XML, N-Triple形式で出力するためのボタンを追加．</li>
<li> ClassとPropertyをソースダイアログで開いた際に，JTreeで階層を表示するようにした．</li>
<li> プラグインを置くためのディレクトリを指定できるようになった．</li>
<li> プラグインＡＰＩを追加(emphasisRDFNodes, emphasisClassNodes, emphasisPropertyNodes)</li>
<li> ステータスバーを追加し，エディタのノードをクリックした時にＵＲＩを表示するようにした．</li>
<li> ノードのサイズを自動調節するか固定のサイズにするかを選択できるようになった．</li>
<li> OWL（クラスとプロパティの階層＋ラベル＋コメントのみ）をインポートできるようにした．</li>
<li> InsertConnectedResource, InsertConnectedLiteral, InsertSubClass, InsertSubPropertyをやめて，それぞれInsertResource, InsertLiteral, InsertClass, InsertPropertyに同様の機能をもたせるようにした．ノードを選択しない場合は以前の機能と同様．</li>
<li> JFontChooserを使ってフォントを設定できるようになった．</li>
<li> LessPagerを使って，ソースを表示するようになった．</li>
<li> JGraphのバージョンを3.1にアップ</li>
<li> その他，細かい修正．</li>
</ul>
<h2 id="doc10_13831">不具合修正</h2>
<ul>
<li> N-Triple形式で出力ができなくなっていたのを修正．</li>
<li> mergeOntlogyModelを修正．</li>
<li> replaceRDFSで，クラスとプロパティが空の場合にうまく読み込めなかったのを修正．</li>
<li> NewProjectでソースダイアログの内容をクリアしていなかったのを修正．</li>
</ul>
<h1 id="doc10_13850">Beta2 (2003-12-23)</h1>
<ul>
<li> 各エディタのポップアップメニューの接続モードメニューを接続モードと移動モードを状況に合わせて変化するように修正した．</li>
<li> 設定ダイアログの構成を修正．</li>
<li> 名前空間の接頭辞の定義を名前空間テーブルに反映できるようになった．</li>
<li> mergeOntologyModelメソッドをプラグインAPIに追加</li>
<li> ノードをダブルクリックして編集した結果が，表示モード（URI,ラベル，ID）に合わせて反映されるようになった．(RDFリソースのタイプを表示しない場合は，RDFリソースをダブルクリックで編集可能）</li>
<li> ベースURIを書き込むかどうかを選択できるようになった．</li>
<li> XML宣言とエンコーディングを出力するようになった．</li>
<li> RDFリソースのタイプとURIを別のタブで編集するように変更．</li>
<li> 各エディタのレイアウトの方向を変更できるようになった．</li>
<li> レイアウトアルゴリズムを選択できるようになった．（VGJ or JGraph Tree Layout)</li>
<li> ファイルを読み込んでいる際に，進行状況を表示するようになった．</li>
<li> VGJTreeLayoutによるインポート時間を大幅に短縮．</li>
<li> JavaHelpを削除．</li>
<li> その他細かい修正．</li>
</ul>
<h2 id="doc10_13897">不具合修正</h2>
<ul>
<li> Literalの編集で言語が扱えなくなっていたのを修正．</li>
<li> OWLImportPluginで多重継承がうまく扱えなかったのを修正．</li>
</ul>
<h1 id="doc10_13910">Beta1 (2003-12-01)</h1>
<ul>
<li> パッケージ名をorg.semanticweb.mmm.mr3に変更</li>
<li> デフォルトの名前空間にowlを追加</li>
<li> OWLImportPluginを作成</li>
<li> JGraphpadのグラフレイアウトライブラリを利用する場合とVGJのグラフレイアウトライブラリを利用する場合で実装を分けた．（前者を利用する場合にはLGPL，後者を利用する場合にはGPL）</li>
<li> クラスおよびプロパティにおける矢印の向きをis-aの方向（サブクラスからスーパークラス）に合わせた．</li>
<li> ノードをダブルクリックすることで，アトリビュートダイアログを表示できるようになった．</li>
<li> クラスとプロパティの概念間の矢印をダブルクリックしてラベルが編集可能になった</li>
<li> ノードのグループ化・非グループ化ができるようになった</li>
<li> プラグインAPIを追加</li>
<li> その他細かい修正</li>
</ul>
<h2 id="doc10_13945">不具合修正</h2>
<ul>
<li> RDFリソースのタイプを非表示にするとコピー，カット，ペーストができなくなるバグを修正</li>
</ul>
<h1 id="doc10_13955">Alpha9 (2003-10-06)</h1>
<ul>
<li> RDFリソースからRDFSクラス，RDFSプロパティへの変換，RDFSクラスからRDFリソース，RDFSプロパティへの変換，RDFSプロパティか らRDFリソース，RDFSクラスへの変換が可能になった．(ポップアップメニューの「Transform from X to X」)</li>
<li> デフォルトのLangをEdit-&gt;Preferenceで設定できるようになった．</li>
<li> プロジェクト保存時に，デフォルトのLangも保存できるようになった．</li>
<li> RDFグラフ，クラスグラフ，プロパティグラフをPNG形式でエクスポートできるようになった．File-&gt;Export-&gt;IMG-&gt;*</li>
<li> RDFSの置換ができるようになった．File-&gt;Import-&gt;Replace-&gt;RDFS/XML(File|URI)</li>
<li> N-Tripleのインポートができるようになった．</li>
<li> getRDFGraph()，getClassGraph()，getPropertyGraph()メソッドをMR3Pluginクラスに追加．プラグ インで，レイアウトを行えるようになった．(File-&gt;Plugins-&gt;SugiyamaLayout)</li>
<li> Look &amp; Feelを変更できるようになった．(View-&gt;Look &amp; Feel-&gt;Metal, Windows, Motif)</li>
<li> インタフェースの表示を日本語と英語の２種類から選択できるようになった．</li>
<li> JenaのバージョンがJena2になった．</li>
<li> JavaHelpを作成した．（ヘルプ-&gt;ヘルプ）</li>
<li> その他，細かい修正．</li>
</ul>
<h2 id="doc10_13995">不具合修正</h2>
<ul>
<li> 初めて起動するときに，各エディタが表示されていなかったのを修正．</li>
<li> デフォルトの選択時の色とRDFSプロパティの色がRDFリソースの色と同色だったのを修正．</li>
<li> ポップアップメニュー，ツールバー，ショートカットを使って，Copy, Cut, Pasteを行う際にそれぞれに同期がとれていなかったのを修正．</li>
<li> MR<sup>3</sup>α7で作成したプロジェクトが読めなくなっていたのを修正．（プロパティにrdf:_1.._nが含まれている場合）</li>
</ul>
<h1 id="doc10_14017">Alpha8 (2003-09-05)</h1>
<ul>
<li> RDFS Class，RDFS Propertyを判断するためのメタクラスをEdit-&gt;PreferenceのMeta Class Listで指定できるようになった．</li>
<li> 各グラフのOverviewが表示できるようになった．(Window-&gt;Show RDF Graph Overview, Show Class Graph Overview, Show Property Graph Overview)</li>
<li> 起動時にSplashWindowを表示するようになった．</li>
<li> RDFリテラルにデータ型を指定できるようになった．</li>
<li> rdf_1&#8230;_(数)のプロパティは，表示しないようになった．</li>
<li> パッケージ名を変更(jp.ac.shizuoka.cs.panda.mmm.mr3.*)</li>
<li> JenaのバージョンをJena2 Betaに変更．</li>
<li> JGraphのバージョンをJGraph4に変更．</li>
<li> その他，細かい修正．</li>
</ul>
<h2 id="doc10_14049">不具合修正</h2>
<ul>
<li> 複数回ペーストする際に，位置が重なっていたのを修正．</li>
</ul>
<h1 id="doc10_14059">Alpha7 (2003-07-31)</h1>
<ul>
<li> 各グラフのノードの色を変更できるようになった．</li>
<li> 標準出力と標準エラー出力をウィンドウに表示できるようになった．(メニュー- &gt;Window-&gt;Log Consoleで表示)</li>
</ul>
<h2 id="doc10_14070">不具合修正</h2>
<ul>
<li> <em>New Project後に，RDFプロパティの編集ができなくなっていたのを修正．</em></li>
<li> <em>プロジェクトの保存で，RDFSクラス及びプロパティのlabelとcommentを保   存できなかったのを修正．その他，プロジェクトの保存関連の不具合を修正．</em></li>
<li> RDFプロパティ編集中に，RDFSプロパティの新規作成または，名前の変更を行った直後に，Attribute DialogのProperty IDに変更が反映されていなかったのを修正．</li>
<li> プロジェクト保存時に，AnonymousリソースがRDFAnon1..nと復元される場合があったのを修正．</li>
</ul>
<h1 id="doc10_14093">Alpha6 (2003-07-24)</h1>
<ul>
<li> importのエンコーディングを指定できるようになった．</li>
<li> ツールバーに，名前空間テーブルを表示するためのボタンを追加した．</li>
<li> URI入力時に，prefix一覧をプルダウンメニューから選択することで名前空間を入力できるようになった．(選択可能なprefixは，名前空間テーブルを参照．)</li>
<li> プラグインメニューをソートして表示するようになった．</li>
<li> 名前空間テーブルに任意の接頭辞と名前空間を追加できるようになった．</li>
<li> RDFエディタで編集中に，RDFSクラス及びプロパティを新規作成し挿入する際に，スーパークラス，スーパープロパティを選択できるようになった．</li>
<li> import時に，prefix，NameSpaceを名前空間テーブルに登録し，有効にするようになった．</li>
<li> リソースのタイプの表示，非表示を選択でいるようになった．</li>
<li> RDFシンタックスで，プロジェクトの保存が可能となった．</li>
<li> コピー（Ctrl-C)，カット(Ctrl-X)，ペースト(Ctrl-V)のショートカットキーを設定した．</li>
<li> よく使われる名前空間の接頭辞は，import時に名前空間テーブルに反映するようにした.（rss, foaf, dc)</li>
</ul>
<h2 id="doc10_14130">不具合修正</h2>
<ul>
<li> Linuxで，クラスまたはプロパティを挿入する際に，IDを選択できなくなっていたバグを修正．</li>
<li> クラス及びプロパティのCommentを削除できなかったのを修正．</li>
<li> N-Tripleで出力できなくなっていたのを修正．</li>
<li> baseURIを名前空間テーブルで処理できなかったのを修正．</li>
<li> AtributeDialogを表示していない状態で，各エディタのリソースを選択し，その後にAttributeDialogを表示すると，リソースの情報がAttributeDialogに表示されなかったのを修正．</li>
<li> 定義されていないクラスをRDFリソースのタイプとして指定した際に，新規に作成されたクラスを編集できなくなっていたバグを修正．</li>
<li> エディタのノードが，スクロールしても表示できなくなることがあったのを修正．</li>
<li> import，export時にファイルを選択した状態で取り消しボタンを押しても反映されていたのを修正．</li>
<li> リソースを編集または，カット，コピーして貼り付けしたすぐ後に，リソースをドラッグして移動するとリソースの表示が編集前に戻ってしまっていたのを修正．</li>
<li> ショートカットキーの設定が，JGraphのものを使用していたのを修正．</li>
<li> ダイアログのownerがnullになっていたのを修正．</li>
<li> RDFSプロパティを初めて挿入したときには，挿入したプロパティではなく，mr3:Propertyの表示内容がAttribute Dialogに表示されていたのを修正．</li>
<li> その他，細かい修正．</li>
</ul>
<h1 id="doc10_14175">Alpha5 (2003-06-27)</h1>
<ul>
<li> Convertメニューに，Selected RDFとSelected RDFSメニューを追加した．選択しているリソースを，XML表現または，N-Tripleに変換可能になった．</li>
<li> 選択しているリソースを，XML表現または，N-Triple表現で保存(export)可能になった．(RDF及びRDFSで可能)</li>
<li> Pluginのユーティリティメソッドに，getSelectedRDFModel, getSelectedRDFSModel, getSelectedClassModel, getSelectedPropertyModelを追加した．</li>
<li> プロジェクト名がタイトルバーに表示されるようになった</li>
<li> プログラム終了時に，プロジェクトの保存を確認するようになった．</li>
<li> Class Editorのメニューバー上のInsert Classアイコンを楕円から矩形にした</li>
<li> プロジェクトの保存で，ネームスペースのチェックを保存できるようになった．</li>
<li> 名前空間テーブルで，接頭辞を設定してテーブルに加えた時にデフォルトでチェックするように変更した．</li>
<li> Help -&gt; About MR^3でバージョンを表示するようになった．</li>
<li> 新規にRDFリソースを作った時点で，URI，ID，Anonymousの設定ができるようになった．</li>
<li> RDFSクラス，プロパティでURI，IDを選択できるようになった．</li>
<li> exportで，ファイルのエンコーディングを選択できるようになった．</li>
<li> その他，細かい修正をした．</li>
</ul>
<h2 id="doc10_14218">不具合修正</h2>
<ul>
<li> ソースコードを表示するウィンドウが前面に表示されなかったのを修正．</li>
<li> ファイル出力時のエンコーディングがnullになるのを修正した．(EncodingをUTF-8または，UTF-16にすると，nullになる)</li>
<li> URIタイプがIDのＲＤＦリソースをコピー，ペーストする際，URIの重複を許していたのを修正．</li>
<li> プロジェクト保存時に，URIのタイプを保存できていなかったのを修正．</li>
<li> RDF/XMLをimportする際に，URIとIDの判別ができていなかったのを修正．</li>
</ul>
<h1 id="doc10_14240">Alpha4 (2003-06-16)</h1>
<ul>
<li> RDF Editorのポップアップメニューに，Insert Connected ResourceとInsertConnected Literalメニューを追加した．(選択されているリソースと矢印でつながった状態で，リソース（リテラル）が挿入される）</li>
</ul>
<h2 id="doc10_14248">不具合修正</h2>
<ul>
<li> <em>同じＩＤを持つはずの無名リソースがすべて違うＩＤを持ってしまうバグを修正．</em></li>
</ul>
<h1 id="doc10_14261">Alpha3 (2003-06-12)</h1>
<ul>
<li> プロジェクトの保存，復元が可能になった．</li>
<li> Windowメニューから各エディタを選択することによって，選択したEditorを手前に表示可能になった．</li>
<li> 各エディタのツールバーに，各エディタとAttributeDialogを手前に表示するためのボタンと，検索ボタンを追加した．</li>
<li> デフォルトの作業ディレクトリが設定できるようになった．</li>
<li> ファイル出力するときに，ファイル名に拡張子を自動でつけるようになった．(RDF/XML -&gt; rdf, RDFS/XML -&gt; rdfs, N-Triple -&gt; n3, Project File -&gt; mr3)</li>
<li> RDFリソースのタイプとRDFリソースのプロパティのコピー，カットが可能になった．</li>
<li> RDFSプロパティのdomainとrangeのコピー，カットが可能になった．</li>
<li> ViewメニューにID表示を追加した．(URIの#以下を表示)</li>
<li> Select Resource Typeダイアログ及びSelect Region Dialogで，クラスの検索が可能になった．</li>
<li> RDF EditorでInsert Resourceを実行したときの入力ダイアログで，プルダウンメニューから，リソースのタイプを選択できるようになった．</li>
</ul>
<h2 id="doc10_14295">不具合修正</h2>
<ul>
<li> RDF Editorでコピーしたリソースのタイプが設定できなくなっていたのを修正．</li>
<li> RDFリソースのURITypeがANONYMOUSの時，コピー，カットができなかったのを修正．</li>
<li> Attribute DialogでRDF Editorのプロパティを選んでいるとき、NameSpaceを選んでいなくてもNameSpaceのリストの一番上のLocalNameのリストが表示されていたのを，最初はLocalNameを表示しないように修正．</li>
<li> RDF EditorのRDFリソースをAttribute Dialogを使って編集してApplyボタンを押したときに，RDFリソースのグループ化が解除されていたのを修正．(その他にも，RDF Editorのリソースのグループ化が解除される可能性あり）</li>
<li> すべてのEditorでノードを追加したとき、Attribute Dialogに表示が反映されていなかったのを修正．</li>
<li> RDFSクラスを削除したときに，RDFSプロパティのdomain, rangeとRDFSクラスの一貫性が保持できていなかったのを修正．</li>
</ul>
<h1 id="doc10_14320">Alpha2 (2003-06-02)</h1>
<ul>
<li> RDF Editorのリソースを選んだ時、Class EditorやProperty Editorの対応するリソースが選択されるようになった．</li>
<li> 選択されているリソースの色が変更されるようになった．</li>
<li> 右クリックをすると出てくるPopupメニューにAttributeDialogを表示するメニューが追加された．</li>
<li> クラスエディタのノードの形が矩形になった．(RDFリソースのタイプの形に合わせた)</li>
<li> Class EditorとProperty Editorのリソースを右クリックしたメニューにサブクラスまたはサブプロパティを挿入する項目が追加された．</li>
<li> SelectPropertyDialogをRDFプロパティにおけるAttribute Dialogに組み込んだ．</li>
<li> 前回終了時のウィンドウサイズが保存されるようになった．</li>
<li> Class Editor, Property Editor, RDF Editorのそれぞれにコピー，カット，ペースト機能を追加した．RDFSプロパティのdomainとrange，RDFリソースのタイプ，RDFプロ パティのdomain, rangeのコピー，カットは行うことができない．</li>
<li> Proxyの設定が可能となった．</li>
</ul>
<h2 id="doc10_14351">不具合修正</h2>
<ul>
<li> JDK1.4.2 BetaでAttributeDialogの表示がくずれていたバグを修正した．</li>
<li> RDF Editorでリソースを編集しているとき、Attribute Dialogを使ってURI TypeをURI,ID,ANONYMOUSとあるラジオボックスを順にクリックするとそれがRDF Editorに反映されてしまうバグを修正．Applyボタンを押すことで反映されるようになった．</li>
</ul>
<h1 id="doc10_14363">Alpha1 (2003-05-15)</h1>
<ul>
<li> 初公開の版</li>
</ul>
