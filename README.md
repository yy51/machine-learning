# adam_vs_sgd

- オプティマイザのSGDとAdam、損失関数の平均二乗誤差(mean squared error)と多クラス交差エントロピー(categorical crossentropy)での性能比較
- SGDと平均二乗誤差(mean squared error)，SGDと多クラス交差エントロピー(categorical crossentropy)，Adamと平均二乗誤差(mean squared error)，Adamと多クラス交差エントロピー(categorical crossentropy)の4パターンでそれぞれ学習を行った．
- オプティマイザと損失関数以外は全て同じ条件

### レイヤー構成
- テンサーフローのチュートリアルでのレイヤーを利用
- https://www.tensorflow.org/tutorials/images/cnn

### データセット
- mnist

# adam_vs_sgd_2
- adam_vs_sgdから、データセットのみを変更して学習を行った．

### レイヤー構成
- adam_vs_sgdと同じ

### データセット
- fashion-mnist

# adam_vs_sgd_2_onelayer
- adam_vs_sgd_2から、レイヤーのみを変更して学習を行った．

### レイヤー構成
- テンサーフローのチュートリアルでのレイヤーを利用
- https://www.tensorflow.org/tutorials/keras/classification

### データセット
- fashion-mnist
