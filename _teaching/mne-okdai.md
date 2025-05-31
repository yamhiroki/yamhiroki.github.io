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
#### 2025/5/31
行動実験の解析について、説明付きのスクリプト(R markdown形式)を追加しました。復習に使ってください。

#### 2025/5/20
サイトを公開しました。今後、授業の進捗に合わせて更新していきます。  
URL [https://yamhiroki.github.io/teaching/mne-okadai](https://yamhiroki.github.io/teaching/mne-okadai)
#### 質問等
[Google Form](https://docs.google.com/forms/d/e/1FAIpQLSeikKubclt8G23Q-b_Akfemc_8qKf4H3GcZWfDubrrx1gxNFQ/viewform)
京都大学大学院人間・環境学研究科 山本洋紀
yamhiroki@gmail.com

# 授業内容
R言語を使った心理実験解析とMNE-Pythonを使った脳波解析を実習します。

# 準備
- 授業までに授業資料を[ダウンロード](https://www.dropbox.com/scl/fi/lr8cyjhmna2zvqi2mgoc4/Lecture2025.zip?rlkey=a7vreump46bohpkhuntdq59wc&dl=0)して展開しておいてください。
- ソフトウェアの準備
    - RとRstudioの[インストール](https://syunsuke.github.io/r_install_guide_for_beginners/index.html)
    - Rパッケージの[インストール](https://syunsuke.github.io/r_install_guide_for_beginners/05_installation_of_packages.html)
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
    - MNEの[インストール](https://mne.tools/stable/install/index.html)
        - 時間がかかります。途中でハングしているようになりますが、辛抱強く待ってください。
    - VisualStudio Codeの[インストール](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
    - WinMergeの[インストール](https://winmergejp.bitbucket.io/)
    - SigViewerの[インストール](https://github.com/cbrnr/sigviewer)　
    
# 実習 2025/5/22(木)
## AM 心理実験の解析
- 触覚心理実験の結果の分析を通じて以下を学びます。
    - R言語の基礎：ファイル入出力, for loop, 文字列処理, 可視化
    - 探索的データ解析(EDA): ggplot2による可視化,主観的等価点, 心理測定関数
    - 確証的データ解析(CDA)：lme4による一般化線形モデル
- 自学自習に適したサイトを紹介しておきます。
    - [R for Data Science](https://r4ds.had.co.nz/)
    - [Statistical Thinking for the 21st Century](https://statsthinking21.github.io/statsthinking21-core-site/index.html#why-does-this-book-exist)  
    - [Statistical Methods for Behavioral and Social Sciences](https://psych252.github.io/)
        - [course book](https://psych252.github.io/psych252book/)
- [説明つきのスクリプト](https://www.dropbox.com/scl/fi/cmoo0qg16p9h7t1y9w7bj/EDA_CDA_touch_lecture.Rmd?rlkey=tradzb2qurtvneoxlcaf01ere&st=gp2c5ffi&dl=0)です。Rstudioでオープンして、説明を読みながら、クリックするだけでコードが実行できます。EDA_CDA_touch_lecture.Rと同じフォルダーにいれてください。Rstudioでknitボタンを押すと、[説明と計算結果を含むHTMLファイル](https://www.dropbox.com/scl/fi/3n2z81mh2arx2q94oe712/EDA_CDA_touch_lecture.html?rlkey=fl25t6xn61a5hexd6cqbinqhu&st=hsmgy7an&dl=0)が出力されます。

<iframe src="EDA_CDA_touch_lecture.html", width="1024" height="600"></iframe>


## PM　脳波解析
- python言語の基礎, 脳波データの入出力
- ノイズ除去(ICA etc.)
- 事象関連電位
- ピーク検出（振幅, 潜時）
- 行動データとの比較, 一般線形モデル, 線形判別分析
- (脳表面へのマッピング)
