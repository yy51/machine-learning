# adam_vs_sgd

- オプティマイザのSGDとAdam、損失関数の平均二乗誤差(mean squared error)と多クラス交差エントロピー(categorical crossentropy)での性能比較
- SGDと平均二乗誤差(mean squared error)，SGDと多クラス交差エントロピー(categorical crossentropy)，Adamと平均二乗誤差(mean squared error)，Adamと多クラス交差エントロピー(categorical crossentropy)の4パターンでそれぞれ学習を行った．
- オプティマイザと損失関数以外は全て同じ条件

### レイヤー構成
- テンサーフローのチュートリアルでのレイヤーを利用
- https://www.tensorflow.org/tutorials/images/cnn

### データセット
- mnist
