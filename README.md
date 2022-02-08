# Kaggle-Happywhale

## 概要
画像からクジラとイルカの個体を予測．

## 評価
評価指標はMAP@5を用いる．
要するに候補を5つ挙げて1つでも合ってたらOKとしてOKの割合．

## データ
* image: 画像ファイル名
* species: 種類
* individual_id: 個体id

## 提出
個体idを5つまで予測してcsvファイルを提出．
個体idはnew_individualもOK．

## その他
過去コンペ[Humpback Whale Identification](https://www.kaggle.com/c/humpback-whale-identification/overview)ではクジラの個体識別をした．今回はそれの拡張．