# Previous Works Baseline
## Distant Supervision
### Dataset
[New York Times (NYT) corpus]()
### Baseline
- Mintz [Distant supervision for relation extraction without labeled data](http://www.aclweb.org/anthology/P09-1113)
- MultiR [Knowledge-Based Weak Supervision for Information Extraction of Overlapping Relations](http://www.aclweb.org/anthology/P11-1055)
- MIMLRE [Multi-instance Multi-label Learning for Relation Extraction](http://www.aclweb.org/anthology/D12-1042)
- PCNN [Distant Supervision for Relation Extraction via Piecewise Convolutional Neural Networks
Daojian](http://www.emnlp2015.org/proceedings/EMNLP/pdf/EMNLP203.pdf)
- PCNN+ATT [Neural Relation Extraction with Selective Attention over Instances](http://www.aclweb.org/anthology/P16-1200)
- APCNN+D [Distant Supervision for Relation Extraction with Sentence-Level Attention and Entity Descriptions](<https://pdfs.semanticscholar.org/b8da/823ad81e3b8e5b80d8286129fdb1d9132e7.pdf?_ga=2.25061362.950242724.1556102255-1721389731.1530185202>) 
- BGWA [Improv- ing Distantly Supervised Relation Extraction using Word and Entity Based Attention](https://arxiv.org/pdf/1804.06987.pdf)
- RESIDE [RESIDE: Improving Distantly-Supervised Neural Relation Extraction using Side Information](http://malllabiisc.github.io/publications/papers/reside_emnlp18.pdf)
- SEE-TRANS [SEE: Syntax-aware Entity Embedding for Neural Relation Extraction](http://arxiv.org/abs/1801.03603)
- LFDS [Label-Free Distant Supervision for Relation Extraction via Knowledge Graph Embedding](http://aclweb.org/anthology/D18-1248)
### Accuracy

| Models 	| Top100 	| Top200 	| Top500 	| Average 	|
|--------	|--------	|--------	|--------	|---------	|
|    Mintz    	|0.77|0.71|0.55|0.676|
|   MultiR     	|0.83|0.74|0.59|0.720|
|    MIMLRE    	|0.85|0.75|0.61|0.737|
|    PCNN    	  |0.84|0.77|0.64|0.750|
|    PCNN+ATT   |0.86|0.83|0.73|0.807|
|   APCNN+D     |0.87|0.83|0.74|0.813|
|    BGWA    	  |0.82|0.75|-|-|
|    RESIDE    	|0.84|0.79|-|-|
|    SEE-TRANS  |0.91|0.87|0.77|0.850|
|    LFDS    	  |0.90|0.88|0.83|0.869|
