********************************************************************************
2024年度第54回天文・天体物理若手夏の学校　集録について
********************************************************************************
サンプルファイル、集録作成方法、提出方法に関する説明書です。
集録に書く内容などは
	2024年度天文・天体物理若手夏の学校HP > 集録作成ガイド
に記載しておりますので、併せてご確認ください。


--------------------------------------------------------------------------------
*** ss24_proceedings_format.zip について ***
--------------------------------------------------------------------------------
readme24.txt
	このテキストファイルです。使い方を説明します。

ss24_sample_UTF-8 > ss24_sample_UTF-8.tex
	集録本文のサンプルファイルです。

ss24_sample_UTF-8 > ss24_UTF-8.sty
	集録作成で使用するスタイルファイルです。

ss24_sample_UTF-8 > pic.pdf
	サンプルで使用する画像ファイルです。

ss24_sample_UTF-8 > ss24_sample.pdf
	ss24_sample_UTF-8.texをコンパイルした際のサンプルPDFファイルです。


環境にあった文字コードのファイルをご利用ください。（TeX Live, Texworks のデフォルトは UTF-8 です。）
UTF-8コードを使っても文字化けしてしまう場合は、お手数ですが環境にあった文字コードに変換して使用してください。
--------------------------------------------------------------------------------



--------------------------------------------------------------------------------
*** "ss24_UTF-8.sty" の説明 ***
--------------------------------------------------------------------------------
本文を書くTexファイルと"ss24_UTF-8.sty"は同じディレクトリに置いてください。
"ss24_UTF-8.sty"の中身は書き換えないでください。
ヘッダ、フッターなどの全体のレイアウトは変更しないでください。

"ss24_UTF-8.sty"では
\usepackage{amsmath, amssymb, amsthm, bm}
上記のパッケージが使用されるようになっています。
それ以外(graphicx, natbibなど)のパッケージを使用したい場合はTexファイルで指定してください。
--------------------------------------------------------------------------------


--------------------------------------------------------------------------------
*** "latexmkrc" の説明 ***
--------------------------------------------------------------------------------
Overleafで日本語環境(pLaTex)でコンパイルする際に、latexmkrcをss24_*ファイルが入っている
ディレクトリと同じ層にlatexmkrcを置き、コンパイラをLaTex(pdfLaTexなどではない）にして
コンパイルを行う必要があります。つまり、自分でlatexmkrcを移動させる必要があります。

詳しくはOverleafの公式HPなどをご参照ください。
https://www.overleaf.com/learn/latex/Questions/Does_Overleaf_support_pTeX%3F
--------------------------------------------------------------------------------


--------------------------------------------------------------------------------
*** 集録作成について ***
--------------------------------------------------------------------------------
"ss24_sample_UTF-8.tex"をそのままコンパイルすれば、同封する"ss24_sample.pdf"と同じファイルが出力されるはずです。
これをもとに、氏名・所属・概要・本文などを記入してください。

Texファイルの最初の行でjarticleクラスファイルと"ss24_##.sty"を読み込んでください。
その時、オプションは("ss24_sample_UTF-8.tex"のままである)以下のものを指定してください。
\documentclass[a4paper,10pt,oneside,twocolumn,notitlepage,final]{jarticle}
\usepackage{ss24_UTF-8}

概要は\abst内に記入してください。
\maketitleは必要ありません。
\abst{}に概要を記入することによりタイトル、名前、概要が一括して出力されます。

Bibtexを使用することはできますが、事務局でbstファイルの用意は行いませんのでご了承ください。
参考文献の本数、形式の指定はありません。

PDFにした際にページ数は4ページ以内、容量は5MB以下に収まるようにしてください。
下限ページ数は設定しておりません。
--------------------------------------------------------------------------------


--------------------------------------------------------------------------------
*** 集録原稿の提出方法 ***
--------------------------------------------------------------------------------
1. ファイル名は「分科会コード_(講演形式)講演番号.pdf」としてください。ただし、講演番号は一桁の場合も0を付け加えて二桁にして記入してください。
	
（例）grcosmo_a01.pdf, compact_b11.pdf

* 分科会コード
	素粒子・重力・宇宙論 : grcosmo
	コンパクト天体 : compact
	銀河・銀河団 : galaxy
	太陽・恒星 : sunstar
	星間現象/星・惑星形成 : isplanet
	観測機器 : instrument
	からお選びください。

* 講演番号
	2024年度天文・天体物理若手夏の学校HP > 資料公開 > プログラム集
	にて、講演番号を記載しますのでご確認ください。
	集録提出開始日までに更新される予定です。



2. Googleフォーム上にPDFファイルを添付して回答してください。

GoogleフォームのURLは
	2024年度天文・天体物理若手夏の学校HP > 集録作成ガイド
で公開します。
また、参加登録時のメールアドレス宛にもURLを送信する予定です。

提出に際して、
・提出は1度のみ
・ファイル名は 「分科会コード_講演番号.pdf」
・PDF形式で4ページ以内　(TeX形式ではありません)
・容量は5MB以内
・正しくコンパイルされている
の5点を改めてご確認いただきますようお願いいたします。


原稿の差し替え、再提出は原則受け付けておりません。
書いた意図通りに出力されることを確認して提出お願いします。
やむを得ず再提出する場合には、
・氏名
・Googleフォームに記入したメールアドレス
を記載の上、提出期間内に下記のメールアドレス宛までお問い合わせください。

提出期間はHP上で決まり次第、更新します。
期間内の提出にご協力よろしくお願いいたします。
--------------------------------------------------------------------------------



--------------------------------------------------------------------------------
*** お問い合わせ ***
--------------------------------------------------------------------------------
その他、集録作成に関するご質問等ございましたらss24集録係までお願いします。

宛名：
2024年度　天文・天体物理若手夏の学校　集録係

アドレス（_at_を@へ置き換える）：
ss24_shuroku_at_astro-wakate.sakura.ne.jp
--------------------------------------------------------------------------------
********************************************************************************
