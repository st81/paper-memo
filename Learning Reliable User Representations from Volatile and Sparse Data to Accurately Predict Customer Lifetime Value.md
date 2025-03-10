Learning Reliable User Representations from Volatile and Sparse Data to Accurately Predict Customer Lifetime Value

https://dl.acm.org/doi/10.1145/3447548.3467079

- アプリの広告クリックを revenue と定義
- revenue を日次のタイムシリーズデータとして扱う
- revenue は volatile なので、discreate wavelet transform (DWT) を利用して低周波数、高周波数領域に分解
- 似ているユーザー同士は revenue タイムシリーズが似ていると考えられる。そこで、ユーザー同士の関連性を Graph Attention Network (GAT) で学習
- GAT で得られたユーザークラスタと、DWT で得られた低周波数をもとにしたクラスタがアラインするように学習させることで、タイムシリーズとユーザー関連性を同時に予測に活かす
