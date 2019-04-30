# Previous Works Baseline
## Distant Supervision
### Dataset
[New York Times (NYT) corpus](http://iesl.cs.umass.edu/riedel/ecml/)
### Baseline
 **Probabilistic Method**
- Mintz [Distant supervision for relation extraction without labeled data](http://www.aclweb.org/anthology/P09-1113)
- MultiR [Knowledge-Based Weak Supervision for Information Extraction of Overlapping Relations](http://www.aclweb.org/anthology/P11-1055)
- MIMLRE [Multi-instance Multi-label Learning for Relation Extraction](http://www.aclweb.org/anthology/D12-1042)

**Neural Network Method(Robust Model)**

- PCNN [Distant Supervision for Relation Extraction via Piecewise Convolutional Neural Networks
Daojian](http://www.emnlp2015.org/proceedings/EMNLP/pdf/EMNLP203.pdf)
- PCNN+ATT [Neural Relation Extraction with Selective Attention over Instances](http://www.aclweb.org/anthology/P16-1200)
- APCNN+D [Distant Supervision for Relation Extraction with Sentence-Level Attention and Entity Descriptions](<https://pdfs.semanticscholar.org/b8da/823ad81e3b8e5b80d8286129fdb1d9132e7.pdf?_ga=2.25061362.950242724.1556102255-1721389731.1530185202>) 

**Neural Network Method**

- BGWA [Improving Distantly Supervised Relation Extraction using Word and Entity Based Attention](https://arxiv.org/pdf/1804.06987.pdf)
- RESIDE [RESIDE: Improving Distantly-Supervised Neural Relation Extraction using Side Information](http://malllabiisc.github.io/publications/papers/reside_emnlp18.pdf)
- MLSSA [Multi-Level Structured Self-Attentions for Distantly Supervised Relation Extraction](https://www.aclweb.org/anthology/D18-1245)
- SEE-TRANS [SEE: Syntax-aware Entity Embedding for Neural Relation Extraction](http://arxiv.org/abs/1801.03603)
- LFDS [Label-Free Distant Supervision for Relation Extraction via Knowledge Graph Embedding](http://aclweb.org/anthology/D18-1248)
### Accuracy

| Models 	| Top100 	| Top200 	| Top500 	| Average 	|
|--------	|--------	|--------	|--------	|---------	|
|    Mintz    	|0.77    |0.71    |0.55    |0.676    |
|   MultiR     	|0.83    |0.74    |0.59    |0.720    |
|    MIMLRE    	|0.85    |0.75    |0.61    |0.737    |
|    PCNN    	  |0.84    |0.77    |0.64    |0.750    |
|    PCNN+ATT   |0.86    |0.83    |0.73    |0.807    |
|   APCNN+D     |0.87    |0.83    |0.74    |0.813    |
|    SEE-TRANS  |**0.91**|0.87    |0.77    |0.850    |
|    LFDS    	  |0.90    |**0.88**|**0.83**|**0.869**|

### Precision
|  	| One 	| One 	| One 	| Two 	| Two 	| Two 	| All 	| All 	| All 	|
|------------	|-------	|-------	|-------	|-------	|-------	|-------	|-------	|-------	|-------	|
| Models 	    | P@100 	| P@200 	| P@300 	| P@100 	| P@200 	| P@300 	| P@100 	| P@200 	| P@300 	|
| PCNN 	      | 73.3 	  | 64.8 	  | 56.8 	  | 70.3 	  | 67.2 	  | 63.1 	  | 72.3 	  | 69.7 	  | 64.1 	  |
| PCNN+ATT 	  | 73.3 	  | 69.2 	  | 60.8 	  | 77.2 	  | 71.6 	  | 66.1 	  | 76.2 	  | 73.1 	  | 67.4 	  |
| BiGRU+ATT 	| 75.0 	  | 69.5 	  | 64.7 	  | 80.0 	  | 72.5 	  | 69.3 	  | 82.0 	  | 76.5 	  | 71.3 	  |
| BiGRU+2ATT 	| 81.0 	  | 74.0 	  | 67.3 	  | 81.0 	  | 75.5 	  | 70.7 	  | 81.0 	  | 76.0 	  | 72.7 	  |
| BGWA 	      | 78.0 	  | 71.0 	  | 63.3 	  | 81.0 	  | 73.0 	  | 64.0 	  | 82.0 	  | 75.0 	  | 72.0 	  |
| RESIDE 	    | 80.0 	  | 75.5 	  | 69.3 	  | 83.0 	  | 73.5 	  | 70.6 	  | 84.0    | 78.5 	  | 75.6 	  |
| MLSSA-1 	  | **88.0**| **77.0**| **70.0**| 88.0 	  | **79.0**| **73.3**| 87.0 	  | **81.5**| 76.0  	|
| MLSSA-2 	  | 87.0 	  | 76.0 	  | **70.0**| **89.0**| 78.5 	  | 72.3 	  | **90.0**| **81.5**| **77.0**|
