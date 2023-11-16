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
## 第1回 2023/11/16（木)
- 実験データの保存形式 [整然データ](https://okumuralab.org/~okumura/python/tidy.html)

- 実験・解析用ディレクトリの構成指針
    
    実験（解析）コード - 実験（解析）結果の対応を明確にすること。

- 各種ノイズ除去 [スクリプト](https://www.dropbox.com/scl/fi/l83ko1m71r9bx8lsuh7pp/noise_removal.zip?rlkey=donfvxbguxvxbms3bf8g27bcc&dl=0)

- 事象関連応答 [スクリプト](https://www.dropbox.com/scl/fi/x9enhq6ax7lnuhrbg73pi/Epoching.py?rlkey=uzo2kidgt36jzdfl041q7eg94&dl=0)
    - topomap[スクリプト](https://www.dropbox.com/scl/fi/qhvjf1huoa23dd842jac5/PlotTopo.py?rlkey=simji8b291fn46klrydmg8004&dl=0)
    - EDF[スクリプト](https://www.dropbox.com/scl/fi/8tyrd3143ehs7dttikb2q/write_edf.py?rlkey=97g3kg3ompl7eam4ven22yhnh&dl=0)

- 脳表活動の推定 [スクリプト](https://www.dropbox.com/scl/fi/yt8dddvx2ue4y0mblm770/surface_map.zip?rlkey=w8kdglsn8goahv2wyd2icmehj&dl=0)

- 授業で使用する実習用 [データ](https://www.dropbox.com/scl/fi/9i97k1l8vkxngzett6kx9/data.zip?rlkey=jii7fgtxwa9d2g2xvey9voh6i&dl=0)

- Rでの読み込み[MNE-R](https://mne.tools/mne-r/)


## 第0回 授業日まで
### PC環境の整備等
- MNEの[インストール](https://mne.tools/stable/install/index.html)
- Visual Studio Codeの[インストール](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
