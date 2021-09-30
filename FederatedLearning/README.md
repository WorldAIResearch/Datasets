# 联邦学习 数据集

## LEAF - 卡内基梅隆大学

**Paper: ** Communication-Efficient Learning of Deep Networks from Decentralized Data [[AISTATS'17](http://proceedings.mlr.press/v54/mcmahan17a.html)]

**Resources: **[[Page](https://leaf.cmu.edu/)] [[Github](https://github.com/TalwalkarLab/leaf)]

| 数据集 |           描述            | 数据集大小 | # of Samples (Total) | # of Users | 数据下载 | Access Time | 备注 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | ----- |
| FEMNIST | Image Classification | - | 805,263 | 3,550 | [Github](https://github.com/TalwalkarLab/leaf/tree/master/data/femnist) | 2021-08-19 |  |
| Shakespeare | Next Character Prediction | - | 422,615 | 1,129 | [Github](https://github.com/TalwalkarLab/leaf/tree/master/data/shakespeare) | 2021-08-19 |  |
| Twitter | Sentiment Analysis | - | 1,600,498 | 660,120 | -                                                            | 2021-08-19 |  |
| Celeba | Image Classification | - | 200,288 | 9,343 | [Github](https://github.com/TalwalkarLab/leaf/tree/master/data/celeba) | 2021-08-19 |  |
| Synthetic Dataset | Classification | - | 107,553 | 1,000 | [Github](https://github.com/TalwalkarLab/leaf/tree/master/data/synthetic) | 2021-08-19 |  |
| Reddit | Language Modeling | - | 56,587,343 | 1,660,820 | [Github](https://github.com/TalwalkarLab/leaf/tree/master/data/reddit) | 2021-08-19 |  |

## FedScale - 密歇根大学

`FedScale 本身为计算框架包含如下数据集任务`

**Paper: ** FedScale: Benchmarking Model and System Performance of Federated Learning [[arXiv](https://arxiv.org/abs/2105.11367)]

**Resources: **[[Github](https://github.com/SymbioticLab/FedScale)]

**Download: ** [[Github](https://github.com/SymbioticLab/FedScale/tree/master/dataset)] `提供所有数据集统一下载脚本`


### CV tasks:

| Dataset       | Data Type   |# of Clients  | # of Samples   | Example Task | 
| -----------   | ----------- | -----------  |  ----------- |    ----------- |
| iNature       |   Image     |   2,295      |   193K        |   Classification |
| FMNIST        |   Image     |   3,400      |   640K        |   Classification  |    
| OpenImage     |   Image     |   13,771     |   1.3M        |   Classification, Object detection      |
| Google Landmark|  Image     |   43,484     |   3.6M        |   Classification       |
| Charades      |   Video     |    266       |   10K         |   Action recognition   |
| VLOG          |   Video     |    4,900     |   9.6k        |   Video classification, Object detection |

### NLP tasks:

| Dataset       | Data Type   |# of Clients  | # of Samples   | Example Task | 
| -----------   | ----------- | -----------  |  ----------- |   ----------- |
| Europarl      |   Text      |   27,835     |   1.2M        |   Text translation  |
| Blog Corpus   |   Text      |   19,320     |   137M        |   Word prediction      |
| Stackoverflow |   Text      |   342,477    |   135M        |  Word prediction, classification |
| Reddit        |   Text      |  1,660,820   |   351M        |  Word prediction   |
| Amazon Review |   Text      | 1,822,925    |   166M        | Classification, Word prediction |
|  CoQA         |   Text      |     7,189    |   114K        |  Question Answering |
|LibriTTS       |   Text      |     2,456    |    37K        |   Text to speech    |
|Google Speech  |   Audio     |     2,618    |   105K        |   Speech recognition |
|Common Voice   |   Audio     |     12,976   |    1.1M       |   Speech recognition |

### Misc Applications:

| Dataset       | Data Type   |# of Clients  | # of Samples   | Example Task | 
| -----------   | ----------- | -----------  |  ----------- |   ----------- |
|Taobao         |   Text      |     182,806  |    0.9M       |   Recommendation |
|Go dataset     |   Text      |     150,333  |    4.9M       |   Reinforcement learning | 



## References



