[Bioinformatics](http://inoue0426.me/Bioinformatics)   [home](http://inoue0426.me/)

# Network-based machine learning and graph theory algorithms for precision oncology.

## 1. どういう内容か
ネットワーク（PPIやリアクションネットワーク）に対して機械学習やグラフ理論を用いてガン特異的なメカニズム、個別医療の最適化について知見をまとめた。

## 2.  先行研究と比べて何がすごいのか
今までは遺伝子レベルでの薬の作成及び個別化医療の最適化を図ってきていたが、そこに対してネットワークレベルでの知見を用いることで、全体像からガンを俯瞰してみることが可能となる。これにより、今まで個々の遺伝子を用いた段階ではわからなかった病気の原因の特定を可能にすることが出来るであろう。

## 3. 技術・手法の新規性
遺伝子ではなくネットワークを用いて各種手法を行うことで、ダイナミクスを考えることにつながり、より詳細にデータから知見を得ることが出来る。

## 4. どうやって有効だと検証したか
KEGG Pathwayのネットワークを作成し、これにTCGAのMutationと10000個のrandomからのP値をマッピングしたものと遺伝子をenrichment analysisにかけ、超幾何検定をしたものから効果を比較検討した。

## 5. 議論はあるか
実際の現場で使う場合、
- データの質
- 汎用性
- スケーラビリティ
上記の3つに問題があるため、これらを改善しなければならない

## 6. 次に読むべき論文は？
[Hybrid approach of relation network and localized graph convolutional filtering for breast cancer subtype classification](https://arxiv.org/abs/1711.05859)