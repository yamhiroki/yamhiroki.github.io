---
title: "MNEによる脳波解析実習"
collection: teaching
type: "Lecture"
permalink: /teaching/mne-okadai
venue: "岡山大学"
date: 2023-11-12
location: "Okayama, Japan"
---
MNEによる脳波解析実習(岡大）に関する情報を提供します。

### お知らせ  
#### 11/11/2023
サイトを公開しました。今後、授業の進捗に合わせて更新していきます。  
URL [https://yamhiroki.github.io/teaching/mne-okadai](https://yamhiroki.github.io/teaching/mne-okadai)
#### 質問等
[Google Form](https://docs.google.com/forms/d/e/1FAIpQLSeikKubclt8G23Q-b_Akfemc_8qKf4H3GcZWfDubrrx1gxNFQ/viewform)
京都大学大学院人間・環境学研究科 山本洋紀
yamhiroki@gmail.com

# 授業内容
MN-Pythonを使った脳波解析を実習します。

# 講義
## 第2回 2023/12/14（木)
- 準備
    - [RとRstudioのインストール](https://syunsuke.github.io/r_install_guide_for_beginners/index.html)
    - [Rパッケージのインストール](https://syunsuke.github.io/r_install_guide_for_beginners/05_installation_of_packages.html): tidyverse, stringr, kinitr, lmerTest, caret, devtools, Hmisc
    - （できれば）[MNE-Rのインストール](https://mne.tools/mne-r/)
- 事象関連応答のピーク検出 [スクリプト](https://www.dropbox.com/scl/fi/o4tagtac3cembpibx598l/GetPeaks.py?rlkey=eihya01mwn99li85j4j5bua39&dl=0)[結果](https://www.dropbox.com/scl/fi/dglwtd5x9yfl62m1ivx61/epochs_peakes.csv?rlkey=coaxzdi0bcnpx3it7qjwrby0u&dl=0)
- 行動データと脳波ピークの同時分析 [スクリプト](https://www.dropbox.com/scl/fi/wiponp9ywn21c23q8rkyf/BehEEGPeaks1.R?rlkey=xxskgfd29y0vq6noznbajba7y&dl=0) [結果](https://www.dropbox.com/scl/fi/35uc748lhd35783hssugk/BehEEGPeaks1.html?rlkey=5u4k1s0f7508nvspp2m3spcew&dl=0)
    - 統合データ [long](https://www.dropbox.com/scl/fi/rtmwwd7hcgb6wrs1gfik9/beh_eeg_long.csv?rlkey=m4qzl0j9m7y75zof7o6gahdrr&dl=0) [wide](https://www.dropbox.com/scl/fi/57ympjzd04aq10r5l1fwm/beh_eeg_wide.csv?rlkey=0gi39ycaeb5gefus29jhnsvwb&dl=0)
    - 反応時間, 正答率の条件間比較（自然シーン、人工シーン）
    - ピーク潜時と振幅の条件間比較
    - 試行毎の分析1：ピーク潜時と反応時間（正誤答）, ピーク振幅と反応時間（正誤答）
    - 試行毎の分析2：ピーク潜時・振幅から反応時間・正誤答を予測
    - 試行毎の分析3：ピーク潜時・振幅から条件をデコーディング
- 行動データのグループ解析[スクリプト](https://www.dropbox.com/scl/fi/zenohbb4y14syx5sknn6m/BehGroup1.R?rlkey=5b2jg6tfj34amt7o08wacmt1i&dl=0) [結果](https://www.dropbox.com/scl/fi/l90b7rgdu533wl7frva5b/BehGroup1.html?rlkey=jyisy7gdl2i9byklo1zwsayvx&dl=0)
    - 線形混合モデルによる反応時間, 正答率の条件間比較（自然シーン、人工シーン）
- 背景知識
    - ブートストラップ法
    - 線形回帰（モデル）
    - 線形判別分析
    - 混同行列
    - 交差検定
    - 線形混合モデル
- 上記知識に関して、自学自習に適したサイトを紹介しておきます。
    - [R for Data Science](https://r4ds.had.co.nz/)
    - [Statistical Thinking for the 21st Century](https://statsthinking21.github.io/statsthinking21-core-site/index.html#why-does-this-book-exist)  
    - [Statistical Methods for Behavioral and Social Sciences](https://psych252.github.io/)
        - [course book](https://psych252.github.io/psych252book/)

## 第1回 2023/11/16（木)
- 実験データの保存形式 [整然データ](https://okumuralab.org/~okumura/python/tidy.html)

- 実験・解析用ディレクトリの構成指針
    
    実験（解析）コード - 実験（解析）結果の対応を明確にすること。

- 各種ノイズ除去 [スクリプト](https://www.dropbox.com/scl/fi/l83ko1m71r9bx8lsuh7pp/noise_removal.zip?rlkey=donfvxbguxvxbms3bf8g27bcc&dl=0)

- 事象関連応答 [スクリプト](https://www.dropbox.com/scl/fi/vnrla4m3beekgcdxo9pvp/Epoching.py?rlkey=9i6b37d7035ualrfp2t6cdl1y&dl=0)
    - topomap[スクリプト](https://www.dropbox.com/scl/fi/qhvjf1huoa23dd842jac5/PlotTopo.py?rlkey=simji8b291fn46klrydmg8004&dl=0)
    - EDF[スクリプト](https://www.dropbox.com/scl/fi/8tyrd3143ehs7dttikb2q/write_edf.py?rlkey=97g3kg3ompl7eam4ven22yhnh&dl=0)

- 脳表活動の推定 [スクリプト](https://www.dropbox.com/scl/fi/yt8dddvx2ue4y0mblm770/surface_map.zip?rlkey=w8kdglsn8goahv2wyd2icmehj&dl=0)

- 授業で使用する実習用 [データ](https://www.dropbox.com/scl/fi/9i97k1l8vkxngzett6kx9/data.zip?rlkey=jii7fgtxwa9d2g2xvey9voh6i&dl=0)

- Rでの読み込み[MNE-R](https://mne.tools/mne-r/)


## 第0回 授業日まで
### PC環境の整備等
- MNEの[インストール](https://mne.tools/stable/install/index.html)
- Visual Studio Codeの[インストール](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
