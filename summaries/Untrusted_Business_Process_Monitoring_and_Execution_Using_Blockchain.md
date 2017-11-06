研究のために全部自前で作成し、実際にデータを検証している。
論文も論理立っていて読みやすく、レイアウトの書き方も綺麗。
こんな感じの研究を実際にやりたい。

## 要約

### 問題点
- 既存の中央管理型Collaborative business processの問題点は、**lack-of-trust**。
- 全く無関係の中立的な第３者機関を設立することなしに、信頼を担保する場所がなかった。  
- 具体例
  - SCMなどの関係者が多いと、責任の所在が不明瞭になる
  - かといって、ステークホルダが協力・またはどこかが先導して包括的な管理システムを作ることは、政治的な観点からも困難を極める
  - やってもコストが高く、incentiveがうまれない

### 既存研究

Prior research on collaborative business processes has intensively investigated different notions of compatibility between the local processes of different partners and between local processes and a global process



#### **collaborative**解決のデザインに関する先行研究
  - [P2P approach](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.28.3010&rep=rep1&type=pdf)
  - [transformations from a global choreography](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.540.1544&rep=rep1&type=pdf)
  - [interaction modeling](http://www.iaas.uni-stuttgart.de/RUS-data/INPROC-2011-04%20-%20BPELgold.pdf)

#### **business process** excutionに関する重要なコンセプト

[XX]部分は、[該当論文](https://link.springer.com/content/pdf/10.1007%2F978-3-319-45348-4_19.pdf)の引用番号を参照

> Various important concepts such as conformance [19], reliability [16] and quality of services [24] have been investigated for centrally controlled business process execution


### 今回の研究の重要ポイント

- smart contractが外部のAPIを叩ける様にする*trigger*の開発
- smart contractから、blockchain transactionを生成する、*translator*の開発

### 実験方法

1. 必要なソフトウェアの構築
1. feasibility testを、[2], [11] 等から取得したbusiness processで実行
1. 500のsmart contractを行い、8000のblockchainを生成
1. ![application images](https://www.evernote.com/l/AWSGoGceb8tLYoEVXMYbDqBRV8zBvZw_Z3Q)
1. その他、必要項目も確認を実際に確認。

### 実装方法

comming soon ...

### 提案

#### Trustの担保の仕方

いずれにせよ、**algorithmを信頼する**という課題が残る。

担保の仕方 -> 
- 関係者がコードを読んでコンパイルをして生成物が正しいかどうかを判断すればよい
