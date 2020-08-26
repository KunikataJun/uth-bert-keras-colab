# UTH-BERT を Tensorflow2.X / Keras BERT から利用して文書分類を行う

東京大学の[医療AI開発学講座](https://ai-health.m.u-tokyo.ac.jp/)が日本語の医療テキストで事前学習したBERTモデルである[UTH-BERT](https://ai-health.m.u-tokyo.ac.jp/uth-bert)を[Keras BERT](https://github.com/CyberZHG/keras-bert)を用いてファインチューニングして文書分類を行うGoogle Colabノートブックです。

特に前準備は必要なくそのまま実行できるようにしてありますが、リソースの割り当てによってはメモリやストレージが不足する可能性がありますのでご了承ください。

UTH-BERTは日本語医療テキストに適用することを目的としたモデルですが、簡単に入手できて一般公開できる日本語医療テキストが見当たりませんので、このノートブックでは医療テキストではなくブログで構成されたデータセットであるKNBコーパス（KNBC）を対象にしています。そのため、今回の結果はUTH-BERTの本来の性能を発揮できていないことをご了承ください。



### 公式サイト

- [BERT(Google)](https://github.com/google-research/bert)

- [UTH-BERT](https://ai-health.m.u-tokyo.ac.jp/uth-bert) \([東京大学 医療AI開発学講座](https://ai-health.m.u-tokyo.ac.jp/)\)

- [Keras BERT](https://github.com/CyberZHG/keras-bert)