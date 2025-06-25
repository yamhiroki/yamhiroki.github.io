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
#### 5/20/2025
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

## 第4回 6/25
- MATLAB基礎１ レッスン1, 2, 3
  - キーワード 変数、行列、インデックス、サイズ、コロンオペレータ
  - 練習A
- お手本研究ソースコード解読: artmuse_nBack_sampleCode.m
  - line 57-73, 127-142
  - line 153, How to shuffle

## 第3回 6/11（水）
- R言語の続きをします。
- matlab互換フリーウェアのoctaveをインストールします。

## 第2回 6/4（水）
- matlabの障害が続いているようですので、R言語の実習を行います。
- [資料1式](https://www.dropbox.com/scl/fi/7m9tbbkiayskivjmbjdgx/materials_2nd.zip?rlkey=ln1dq302c4w0ga6wk4aajq8rq&dl=0)
- 実習した[Rマークダウンスクリプト](https://www.dropbox.com/scl/fi/ohzosw4x951mv83gg00hy/lec_2nd.Rmd?rlkey=a9m8izfywbarv5b55h4l8m70p&st=2mimh2mf&dl=0)

## 第1回 5/28（水)
- 下記PC環境準備のサポートの回にします。
- ご自身で問題なく準備が完了した方は出席不要です。
- 準備がうまくいかなかった人は出席してください。サポートします。

## 第0回 授業日まで
### PC環境の整備等
- matlab はすでに月浦先生の回でインストールされていると思います。まだの方は[情報環境機構のHP](https://www.iimc.kyoto-u.ac.jp/ja/services/ismc/license/how-to-use/matlab)を参照してください。[インストールガイド](https://www.iimc.kyoto-u.ac.jp/sites/default/files/2025-02/ku-matlab-start-guide-ja.pdf)
- エディター VS Code を[インストール](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)しておいてください。
- R言語とRStudioを[インストール](https://www.crepe.e.u-tokyo.ac.jp/research/research20210624/%EF%BC%88%E5%8F%82%E8%80%83%E8%B3%87%E6%96%993%EF%BC%89RStudio%E3%81%AE%E5%88%A9%E7%94%A8%E3%82%AC%E3%82%A4%E3%83%89.pdf)しておいて下さい。
