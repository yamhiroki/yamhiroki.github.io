---
title: "心理実験・脳波解析実習"
collection: teaching
type: "Lecture"
permalink: /teaching/mne-okadai
venue: "岡山大学"
date: 2025-5-20
location: "Okayama, Japan"
---

心理・脳波計測の解析実習(岡大）に関する情報を提供します。

### お知らせ 
#### 2025/5/20
サイトを公開しました。今後、授業の進捗に合わせて更新していきます。  
URL [https://yamhiroki.github.io/teaching/mne-okadai](https://yamhiroki.github.io/teaching/mne-okadai)
#### 質問等
[Google Form](https://docs.google.com/forms/d/e/1FAIpQLSeikKubclt8G23Q-b_Akfemc_8qKf4H3GcZWfDubrrx1gxNFQ/viewform)
京都大学大学院人間・環境学研究科 山本洋紀
yamhiroki@gmail.com

# 授業内容
R言語を使った心理実験解析とMNE-Pythonを使った脳波解析を実習します。

# 講義 2024/5/22(木)
## AM 心理実験の解析
- ソフトウェアの準備
    - [RとRstudioのインストール](https://syunsuke.github.io/r_install_guide_for_beginners/index.html)
    - [Rパッケージのインストール](https://syunsuke.github.io/r_install_guide_for_beginners/05_installation_of_packages.html)
        - tidyverse)
        - ggExtra
        - cowplot
        - viridis
        - R.matlab
        - quickpsy 
        - lmerTes
        - MuMIn
        - effects
        - performance
        - knitr
        - papaja

- [実習資料のダウンロード](https://www.dropbox.com/scl/fi/apbob8pxu2gxzy3zxuodb/am.zip?rlkey=wwhrl7bumm7cp9rntcrrnzkid&e=1&dl=0)
- 触覚心理実験の結果の分析を通じて以下を学びます。
    - R言語の基礎：ファイル入出力, for loop, 文字列処理, 可視化
    - 探索的データ解析(EDA): ggplot2による可視化,主観的等価点, 心理測定関数
    - 確証的データ解析(CDA)：lme4による一般化線形モデル
- 自学自習に適したサイトを紹介しておきます。
    - [R for Data Science](https://r4ds.had.co.nz/)
    - [Statistical Thinking for the 21st Century](https://statsthinking21.github.io/statsthinking21-core-site/index.html#why-does-this-book-exist)  
    - [Statistical Methods for Behavioral and Social Sciences](https://psych252.github.io/)
        - [course book](https://psych252.github.io/psych252book/)

## PM　脳波解析
- ソフトウェアの準備
    - MNEの[インストール](https://mne.tools/stable/install/index.html)
    - Visual Studio Codeの[インストール](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
- [授業資料のダウンロード](https://www.dropbox.com/scl/fi/89ckkeaxx15itdi2ymcvs/day2.zip?rlkey=5iryjick7fkvwpqo0q6ezez0v&st=p0fva8rg&dl=0)
- python言語の基礎, 脳波データの入出力
- ノイズ除去(ICA etc.)
- 事象関連電位
- ピーク検出
- 行動データとの比較, 線形判別分析
- (脳表面へのマッピング)
