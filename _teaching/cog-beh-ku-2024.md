---
title: "認知行動科学実験1:認知科学のためのプログラミング"
collection: teaching
type: "Lecture"
permalink: /teaching/cog-beh-ku
venue: "京都大学, 総人"
date: 2024-05-23
location: "Kyoto, Japan"
---

認知行動科学実験1(京大）に関する情報を提供します。

### お知らせ  
#### 5/23/2024
サイトを公開しました。今後、授業の進捗に合わせて更新していきます。  
URL [https://yamhiroki.github.io/teaching/cog-beh-ku](https://yamhiroki.github.io/teaching/cog-beh-ku)

# 授業内容
認知科学実験を行うためのMATLABプログラミングを学びます。そのために、下記の教科書で基本を学びつつ、実際の認知科学実験のソースコードを解読します。
- 教科書　[心理のためのMATLABチュートリアル](http://www.nemotos.net/resources/matlab_for_psychologists_ja.pdf)
- お手本  [M. Aly & Nicholas B. Turk-Browne (2016) Attention promotes episodic encoding by stabilizing hippocampal representations](https://www.pnas.org/content/113/4/E420.short)  
実験2（Nバック課題）の実験制御（視覚刺激呈示、被験者反応取得、眼球運動・fMRI測定との同期）と被験者反応の基礎的な解析（ヒット率、フォールスアラーム率、反応時間等）を理解します。   
[ソースコードと実行例, 論文含む](https://www.dropbox.com/s/5j29xhkktqarc7w/turk-sample-code.zip?dl=0)  
[デモ動画](https://youtu.be/rXGSDsaLuQ8)

# 課題提出・質問
[Googleフォーム](https://docs.google.com/forms/d/e/1FAIpQLSdZeqjQTkIrCUtidvR1tjeNn3YnXdDfFPxo9abLk8pCx-F20A/viewform)で受け付けます。

# 講義
## 補足 R と 心理統計に関する資料
- R言語がほんのさわりだけになってしまう可能性が高いです。心理統計も含めて自学自習に適したサイトを紹介しておきます。
 - [R for Data Science](https://r4ds.had.co.nz/)
 - [Statistical Thinking for the 21st Century](https://statsthinking21.github.io/statsthinking21-core-site/index.html#why-does-this-book-exist)  
 - [Statistical Methods for Behavioral and Social Sciences](https://psych252.github.io/)
    - [course book](https://psych252.github.io/psych252book/)

## 第6回 7/10（水）
- 練習問題H [データ: ex2.csv](https://www.dropbox.com/s/ahx1tzyysa04mt2/ex2.csv?dl=0)
  - 解答例　[練習H matlab script](https://www.dropbox.com/s/dx8mdk10v931mf8/ExH.m?dl=0)
- R言語による探索的データ解析　入門 
  - [練習HのRスクリプト版](https://www.dropbox.com/s/42dd8ohqss3j48j/ExH.R?dl=0)  
  - tidy data, tidyverse
  - read_csv(), write_csv(), ggplot() etc.
  - [参考図書](https://www.amazon.co.jp/R%E3%81%A7%E3%81%AF%E3%81%98%E3%82%81%E3%82%8B%E3%83%87%E3%83%BC%E3%82%BF%E3%82%B5%E3%82%A4%E3%82%A8%E3%83%B3%E3%82%B9-%E7%AC%AC2%E7%89%88-Hadley-Wickham/dp/4814400772?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&ref_=fplfs&psc=1&smid=AN1VRQENFRJN5)   
    [English version, free](https://r4ds.hadley.nz/)

## 第5回 7/3（水)
- MATLABの基礎5 レッスン12, 14  
  - データ構造: セル配列, 構造体配列  
  - データ入力: fopen(), fgets(), textscan(), csv file
- お手本研究ソースコード解読 artmuse_nBack_analysisCode.m
  - 実験結果データ入力部 [line 26 - 32.](https://www.dropbox.com/s/yetkbx6j3q75pdl/Otehon_DataInput.png?dl=0)
  - 結果ファイル例 [csv](https://www.dropbox.com/s/y3kv3jjpgmbdg3w/HY_L_indexfinger_hf202207s11n01_20220712T205120.csv?dl=0)
  - [整然データ(tidy data)](https://www.jstage.jst.go.jp/article/jkg/67/9/67_448/_pdf) 
- 課題　
  - 教科書　練習問題G 　WEBフォームより提出(PDF or text) 
  - 解答例 [練習G](https://www.dropbox.com/s/gecd46qgbbqdfpo/ex_g.m?dl=0)

## 第4回 6/26（水)
- 前回の課題講評
- MATLABの基礎4 レッスン 7, 8, 9, 10, 11  
  - グラフ
  - 参考　Rでグラフ [ggplot2](https://ggplot2-book.org/)  
  - スクリプト, 条件, ループ, エラー検出
  - 課題　教科書　練習問題D, E, Fの(2), WEBフォームより提出(PDF or text)  
    - [new data set (including exercise2.mat)](https://www.dropbox.com/s/fgrn90m2e22px98/matlab_exercises.zip?dl=0)

## 第3回 6/19（水)
- 前回の課題講評
- MATLAB基礎3 レッスン4, 5, 6 　　
  - 転置, 四則演算, ドット積, 関数, 引数, 論理演算子, NaN
  - [演習用データ](https://www.dropbox.com/s/sn1dkwk4wsebau5/m4psych_exercises_datasets.zip?dl=0)
  - [matファイルはload関数で読み込めます](https://jp.mathworks.com/help/matlab/ref/load.html) 　　
- 課題　教科書 練習課題B,C WEBフォームより提出(PDF or text)
- - 解答例 [練習B](https://www.dropbox.com/s/c7c8s5l5knk229d/ex_b.m?dl=0), [練習C](https://www.dropbox.com/s/m2qe0sl06d5bnuz/ex_c.m?dl=0)

## 第2回 6/12（水)
- MATLAB基礎 レッスン1, 2, 3
  - キーワード 変数、行列、インデックス、サイズ、コロンオペレータ
- お手本研究ソースコード解読: artmuse_nBack_sampleCode.m
  - line 57-73, 127-142
  - line 153, How to shuffle
- - 解答例 [練習A](https://www.dropbox.com/s/lbbmbwumkqf56he/ex_a.m?dl=0)

## 第1回 6/5（水)
- 認知科学実験の作り方  
デモを通じてお手本研究の刺激呈示の流れを把握します。保存された実験結果のファイルを見ながら、刺激呈示と結果解析のプログラミングに何が必要か考えます。
- MATLAB基礎1  
教科書にそって、実際に手を動かしてプログラミングします。

## 第0回 授業日まで
### PC環境の整備等
- matlab はすでに月浦先生の回でインストールされていると思います。
- エディター VS Code を[インストール](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)しておいてください。
- R言語とRStudioを[インストール](https://www.crepe.e.u-tokyo.ac.jp/research/research20210624/%EF%BC%88%E5%8F%82%E8%80%83%E8%B3%87%E6%96%993%EF%BC%89RStudio%E3%81%AE%E5%88%A9%E7%94%A8%E3%82%AC%E3%82%A4%E3%83%89.pdf)しておいて下さい。
