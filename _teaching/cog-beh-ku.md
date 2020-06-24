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
[Googleフォーム](https://docs.google.com/forms/d/e/1FAIpQLSeqwO_otAKkcL9yEviFtXxJsfaT7Sn_2g7JNGF6ZmTuznqvrA/viewform)で受け付けます。大学で付与されたメールアドレスでサインインしてください。

# 講義
## 第3回 6/23８(水)
- 前回の課題講評
- MATLAB基礎3 レッスン4, 5,6, 7  　　
 - 転置, 四則演算, ドット積, 関数, 引数, 論理演算子, NaN
 - [演習用データ](https://www.dropbox.com/s/sn1dkwk4wsebau5/m4psych_exercises_datasets.zip?dl=0)　　
- お手本研究ソースコード解読  artmuse_nBack_analysisCode.m
 - line 44 - 73
- 課題　教科書 練習課題B,C,D, WEBフォームより提出(PDF or text)

## 第2回 6/17（水)
- MATLAB基礎2 レッスン1, 2, 3
 - キーワード 変数、行列、インデックス、サイズ、コロンオペレータ
- お手本研究ソースコード解読: artmuse_nBack_sampleCode.m
 - line 57-73, 127-142
 - line 153, How to shuffle

- 課題
教科書の練習問題Aを解いてもらって、上記フォームから提出してもらいます。


## 第1回 6/10（水）
- 認知科学実験の作り方  
デモを通じてお手本研究の刺激呈示の流れを把握します。保存された実験結果のファイルを見ながら、刺激呈示と結果解析のプログラミングに何が必要か考えます。
- MATLAB基礎1  
教科書にそって、実際に手を動かしで、プログラミングします。
