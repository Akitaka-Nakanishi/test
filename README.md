# 機械学習のデモンストレーション

0. サンプルデータを作成
1. k最近傍法 (k-Nearest Neighbor, k-NN)で分類。
2. モデルの適用領域 (Applicability Domain, AD)をk-NNで計算。モデル構築用データ・クロスバリデーション・予測データのTrue Positive (TP), False Positive (FP), False Negative (FN), True Negative (TN), 正解率 (Accuracy)を表示
3. 二重交差検証 (Double Cross Validation)でその予測性能を推定。二重交差検証は複数回実行し、TP, FP, FN, TN, 正解率それぞれの平均と分散を表示。


二重交差検証については、以下を参照

https://datachemeng.com/doublecrossvalidation/

http://univprof.com/archives/16-06-12-3889388.html
