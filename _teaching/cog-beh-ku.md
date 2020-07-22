---
title: "認知行動科学実験1:認知科学のためのプログラミング"
collection: teaching
type: "Lecture"
permalink: /teaching/cog-beh-ku
venue: "京都大学, 総人"
date: 2020-06-06
location: "Kyoto, Japan"
---

認知行動科学実験1(京大）に関する情報を提供します。

# お知らせ
## 7/22/2020　　
- 練習Hの解答例を載せました。授業と異なる方法です。こちらも参考にしてください。　　
- 課題提出は今月中にお願いします。

## 7/20/2020
- 明後日、第7回も予定通り行います。
- 第7回の授業内容を追記しました。
- 練習問題Gの解答例をアップしました。未提出の人は、解答例を参考にしながらコーディング＆動作確認して提出してください。

## 7/13/2020
- 明後日、第6回も予定通り行います。
- 第6回の授業内容を追記しました。
- 練習問題Fの解答例をアップしました。未提出の人は、解答例を参考にしながらコーディング＆動作確認して提出してください。

## 7/7/2020
- 明日、第5回も予定通り行います。
- 第5回の授業内容を追記しました。
- 練習問題D,Eの解答例をアップしました。

## 6/29/2020
- 明後日、第4回も予定通り行います。
- 第4回の授業内容を追記しました。
- 練習問題A,B,Cの解答例をアップしました。  

## 6/23/2020
- 明日、第3回も予定通り行います。
- 第3回の授業内容を追記しました。  

## 6/16/2020
- 明日、第2回も予定通り行います。
- 第2回の授業内容を追記しました。
- 標準的なエディターソフト、[VisualStudio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)をインストールしておいてください。プログラムの編集や実験結果など各種ファイルの閲覧、確認に有用です。同種のソフト、[Atom](https://atom.io/)も便利です。使いやすさ重視ならAtomの方が良いかもしれません。日本語用に、[サクラエディタ](https://sakura-editor.github.io/)もインストールしておくとよいです。

## 6/10/2020
課題提出・質問受付のサイトを変更しました。今日の授業について質問などありましたら、利用して下さい。また、授業内容：ソースコードと実行例~のダウンロードも私の許可なくできるようにしました。
## 6/10/2020
デモ動画(one-back task)を追加しました。

## 6/6/2020
サイトを公開しました。今後、授業の進捗に合わせて更新していきます。  
URL [https://yamhiroki.github.io/teaching/cog-beh-ku](https://yamhiroki.github.io/teaching/cog-beh-ku)


# 授業内容
認知科学実験を行うためのMATLABプログラミングを学びます。そのために、下記の教科書で基本を学びつつ、実際の認知科学実験のソースコードを解読します。
- 教科書　[心理のためのMATLABチュートリアル](http://www.nemotos.net/resources/matlab_for_psychologists_ja.pdf)
- お手本  [M. Aly & Nicholas B. Turk-Browne (2016) Attention promotes episodic encoding by stabilizing hippocampal representations](https://www.pnas.org/content/113/4/E420.short)  
実験2（Nバック課題）の実験制御（視覚刺激呈示、被験者反応取得、眼球運動・fMRI測定との同期）と被験者反応の基礎的な解析（ヒット率、フォールスアラーム率、反応時間等）を理解します。  
[ソースコードと実行例, 論文含む](https://www.dropbox.com/s/fmxrkvr40zymstn/turk-sample-code.zip?dl=0)  
[デモ動画](https://youtu.be/rXGSDsaLuQ8)

# 課題提出・質問
[Googleフォーム](https://docs.google.com/forms/d/e/1FAIpQLSeqwO_otAKkcL9yEviFtXxJsfaT7Sn_2g7JNGF6ZmTuznqvrA/viewform)で受け付けます。

# 講義
## 第7回 7/22（水）
- 前回の課題講評
- MATLABの基礎7 レッスン15  
  - データ入出力  
    - fopen(), fclose(), fprintf(), fscanf()
    - table, tableread(), tablewrite()
- 練習問題H [データ: ex2.csv](https://www.dropbox.com/s/ahx1tzyysa04mt2/ex2.csv?dl=0)
  - 解答例　[練習H matlab script](https://www.dropbox.com/s/dx8mdk10v931mf8/ExH.m?dl=0)
- R言語による探索的データ解析　入門  
  - [RStudio cloud](https://rstudio.cloud/)を使いますので、アカウントを作っておいてください。
  - [練習HのRスクリプト版](https://www.dropbox.com/s/42dd8ohqss3j48j/ExH.R?dl=0)  
  - tidy data, tidyverse
  - read_csv(), write_cs(), ggplot()
  - [参考図書](https://www.oreilly.co.jp/books/9784873118147/)   
   [English version, free](https://r4ds.had.co.nz/)
- 課題
  - ご自身のPCにR言語をインストールしてください。[ダウンロードサイト](https://cran.ism.ac.jp/)
  - ご自身のPCにRStudio（Free版)をインストールしてください。[ダウンロードサイト](https://rstudio.com/products/rstudio/download/)
  - 上記課題HのRスクリプトを実行（[動画](https://www.dropbox.com/s/wezqu6ato0myqjh/rstudio.mp4?dl=0)）して、実行結果(htmlファイル)をWEBフォームから提出してください。

## 第6回 7/15（水）
- 前回の課題講評　　
- MATLABの基礎6 レッスン12, 14  
  - データ構造: セル配列, 構造体配列  
  - データ入力: fopen(), fgets(), textscan(), csv file
- お手本研究ソースコード解読 artmuse_nBack_analysisCode.m
  - 実験結果データ入力部 line 26 - 32.
- 課題　教科書　練習問題G 　WEBフォームより提出(PDF or text)  
  - 解答例 [練習G](https://www.dropbox.com/s/gecd46qgbbqdfpo/ex_g.m?dl=0)

## 第5回 7/8（水）
- 前回の課題講評
- MATLABの基礎5 レッスン9, 10, 11
　- スクリプト, 条件, ループ, エラー検出
- お手本研究ソースコード解読 artmuse_nBack_sampleCode.m  
  - 実験のメインループ：2重（ブロック, 試行）ループ line 348 - 629  
    ````matlab
    %start block loop
    for block = 1:2
        :
        % start trial loop
        for trial = 1:numTrials
        :
        end % end trial loop
        :
    end % end block loop
    ````   
- 課題　教科書　練習問題F 　WEBフォームより提出(PDF or text)  
  - 解答例 [練習F](https://www.dropbox.com/s/giqtlp76dr7459z/ex_f.m?dl=0), [練習Cプロット付加](https://www.dropbox.com/s/tbjdf3g0geork43/ex_c2.m?dl=0), [標準誤差の関数](https://www.dropbox.com/s/v92j32hk78y3wjj/std_error.m?dl=0)


## 第4回 7/1（水）
- 前回の課題講評
- 前回の復習 練習問題D
- MATLABの基礎4 レッスン8  
  - グラフ, plot
  - 参考　Rでグラフ [ggplot2](https://ggplot2-book.org/)  

- 課題　教科書　練習問題E　WEBフォームより提出(PDF or text)  
  - [new data set (including exercise2.mat)](https://www.dropbox.com/s/fgrn90m2e22px98/matlab_exercises.zip?dl=0)
  - 解答例 [練習D](https://www.dropbox.com/s/s18j2zeeg2l95zb/ex_d.m?dl=0) [練習E](https://www.dropbox.com/s/l5zyba6m95kela8/ex_e.m?dl=0)

## 第3回 6/24　(水)
- 前回の課題講評
- MATLAB基礎3 レッスン4, 5,6, 7  　　
  - 転置, 四則演算, ドット積, 関数, 引数, 論理演算子, NaN
  - [演習用データ](https://www.dropbox.com/s/sn1dkwk4wsebau5/m4psych_exercises_datasets.zip?dl=0)　　
- お手本研究ソースコード解読  artmuse_nBack_analysisCode.m
  - line 44 - 73
- 課題　教科書 練習課題B,C WEBフォームより提出(PDF or text)  
  - 解答例 [練習B](https://www.dropbox.com/s/c7c8s5l5knk229d/ex_b.m?dl=0), [練習C](https://www.dropbox.com/s/m2qe0sl06d5bnuz/ex_c.m?dl=0)  

## 第2回 6/17（水)
- MATLAB基礎2 レッスン1, 2, 3
  - キーワード 変数、行列、インデックス、サイズ、コロンオペレータ
- お手本研究ソースコード解読: artmuse_nBack_sampleCode.m
  - line 57-73, 127-142
  - line 153, How to shuffle

- 課題
教科書の練習問題Aを解いてもらって、上記フォームから提出してもらいます。
  - 解答例 [練習A](https://www.dropbox.com/s/lbbmbwumkqf56he/ex_a.m?dl=0)


## 第1回 6/10（水）
- 認知科学実験の作り方  
デモを通じてお手本研究の刺激呈示の流れを把握します。保存された実験結果のファイルを見ながら、刺激呈示と結果解析のプログラミングに何が必要か考えます。
- MATLAB基礎1  
教科書にそって、実際に手を動かしてプログラミングします。
