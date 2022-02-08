# Kaggle-Happywhale

## 概要
画像からクジラとイルカの個体を予測．

## 評価
評価指標はMAP@5を用いる．
要するに候補を5つ挙げてk番目で正解したら1/kのスコアが得られ，それを平均したものである．
例えば，正解がAの時，予測とスコアは以下である．
* (A, B, C, D, E): 1.0
* (B, A, C, D, E): 0.8
* (B, C, A, D, E): 0.6
* (B, C, D, E, F): 0.0

## データ
* image: 画像ファイル名
* species: 種類
* individual_id: 個体id

## 提出
個体idを5つまで予測してcsvファイルを提出．
個体idはnew_individualもOK．

## その他
過去コンペ[Humpback Whale Identification](https://www.kaggle.com/c/humpback-whale-identification/overview)ではクジラの個体識別をした．今回はそれの拡張．