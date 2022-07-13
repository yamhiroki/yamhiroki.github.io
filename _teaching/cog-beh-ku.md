---
title: "認知行動科学実験1:認知科学のためのプログラミング"
collection: teaching
type: "Lecture"
permalink: /teaching/cog-beh-ku
venue: "京都大学, 総人"
date: 2022-04-13
location: "Kyoto, Japan"
---

認知行動科学実験1(京大）に関する情報を提供します。

### お知らせ  
#### 6/3/2022
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

## 第6回 7/13（水)
- 前回の課題講評　　
- MATLABの基礎6 レッスン12, 14  
  - データ構造: セル配列, 構造体配列  
  - データ入力: fopen(), fgets(), textscan(), csv file
- お手本研究ソースコード解読 artmuse_nBack_analysisCode.m
  - 実験結果データ入力部 [line 26 - 32.](https://www.dropbox.com/s/yetkbx6j3q75pdl/Otehon_DataInput.png?dl=0)
  - 結果ファイル例 [csv](https://www.dropbox.com/s/y3kv3jjpgmbdg3w/HY_L_indexfinger_hf202207s11n01_20220712T205120.csv?dl=0)
- 課題　
  - 教科書　練習問題G 　WEBフォームより提出(PDF or text)  
  - ご自身のPCにR言語をインストールしてください。[ダウンロードサイト](https://cran.ism.ac.jp/)
  - ご自身のPCにRStudio（Free版)をインストールしてください。[ダウンロードサイト](https://rstudio.com/products/rstudio/download/)
- 今回のスクリプト [lec6th.txt](https://www.dropbox.com/s/2lrfl0eik6i916r/lec6th.txt?dl=0)

## 第5回 7/6（水）
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
- 今回のスクリプト・関数
  [lesson8.m](https://www.dropbox.com/s/04z80h7gg2s7h9u/lesson8.m?dl=0)
  [nearest.m](https://www.dropbox.com/s/8y216yu6hpj4mr7/nearest.m?dl=0)
  [lec5th.txt](https://www.dropbox.com/s/izs95ek0blk23sn/lec5th.txt?dl=0)
- 課題　教科書　練習問題F WEBフォームより提出(PDF or text)
  - 解答例 [練習F](https://www.dropbox.com/s/giqtlp76dr7459z/ex_f.m?dl=0), [標準誤差の関数](https://www.dropbox.com/s/v92j32hk78y3wjj/std_error.m?dl=0)

## 第4回 6/29（水)
- 前回の課題講評
- 前回の復習 練習問題D
- MATLABの基礎4 レッスン8  
  - グラフ, plot
  - お手本研究ソースコード解読  artmuse_nBack_analysisCode.m, line 43-73
    - accuracy, RT
  - 参考　Rでグラフ [ggplot2](https://ggplot2-book.org/)  
  - 課題　教科書　練習問題E　WEBフォームより提出(PDF or text)  
    - [new data set (including exercise2.mat)](https://www.dropbox.com/s/fgrn90m2e22px98/matlab_exercises.zip?dl=0)
  - [今回の授業スクリプト](https://www.dropbox.com/s/ukm0osiaivlymz1/lec4th_2022.txt?dl=0)
  - 解答例 [練習E](https://www.dropbox.com/s/l5zyba6m95kela8/ex_e.m?dl=0)

## 第3回 6/22　(水)
- 前回の課題講評
- MATLAB基礎3 レッスン4, 5, 6, 7  　　
  - 転置, 四則演算, ドット積, 関数, 引数, 論理演算子, NaN
  - [演習用データ](https://www.dropbox.com/s/sn1dkwk4wsebau5/m4psych_exercises_datasets.zip?dl=0)
  - [matファイルはload関数で読み込めます](https://jp.mathworks.com/help/matlab/ref/load.html) 　　
- 課題　教科書 練習課題B,C WEBフォームより提出(PDF or text)  
 - 解答例 [練習B](https://www.dropbox.com/s/c7c8s5l5knk229d/ex_b.m?dl=0), [練習C](https://www.dropbox.com/s/m2qe0sl06d5bnuz/ex_c.m?dl=0), [練習D](https://www.dropbox.com/s/s18j2zeeg2l95zb/ex_d.m?dl=0)
- [今回の授業スクリプト](https://www.dropbox.com/s/mb9b7upk2bdc4p3/lev_3rd_2022.txt?dl=0)
- **octaveにはnanmean(), nanstd()がデフォルトでは入っていません。**下記の手順で[statisticsパッケージ](https://octave.sourceforge.io/statistics/index.html)  をインストールしてください。lsline()もこのパッケージです。
```
>> pkg install -forge io
>> pkg install -forge statistics
```
statisticsパッケージの関数（nanmean()等）を使うときは、まず、以下のように、パッケージをロードする必要があります。
```
>> pkg load statistics
```

## 第2回 6/15（水)
- MATLAB基礎2 レッスン1, 2, 3
  - キーワード 変数、行列、インデックス、サイズ、コロンオペレータ
  - 解答例 [練習A](https://www.dropbox.com/s/lbbmbwumkqf56he/ex_a.m?dl=0)
- お手本研究ソースコード解読: artmuse_nBack_sampleCode.m
  - line 57-73, 127-142
  - line 153, How to shuffle

## 第1回 6/8（水)
- 認知科学実験の作り方  
デモを通じてお手本研究の刺激呈示の流れを把握します。保存された実験結果のファイルを見ながら、刺激呈示と結果解析のプログラミングに何が必要か考えます。
- MATLAB基礎1  
教科書にそって、実際に手を動かしてプログラミングします。

## 第0回 授業日まで
### PC環境の整備等
- [GNU Octave](https://www.gnu.org/software/octave/index)
最新のバージョン(7.1.0)を[インストール](https://www.gnu.org/software/octave/download)しておいて下さい。
- お好みのエディター（[VS Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/), [Atom](https://atom.io/), [サクラエディタ](https://sakura-editor.github.io/)等）も少なくとも一つインストールしておいてください。
- [Octave Online](https://octave-online.net/)に一度アクセスして、1+1が計算できるか確認しておいてください。
