# graph-nn-resources

## Getting started
- Excellent review on 'traditional' methods for relational machine learning [1]
- Neat unifying framework for graph representation learning methods [2]

## Embedding lookup methods
- [RESCAL] (encompasses [DistMult])
- [TransE]

## Encoder methods 
(i.e. embeddings are generated as a function of adjeecency matrix and inoutt features, if available)
- [GCN]: [How powerful are Graph Convolutions?]
- [VGAE]
- [R-GCN]
- [GraphSAGE]

### Interesting repos
- Comprehensive implementation of TransX methods : [OpenKE]
- Python package for easy deep learning on graph : [dgl.ai]

[TransE]: https://www.utc.fr/~bordesan/dokuwiki/_media/en/transe_nips13.pdf
[RESCAL]: http://www.icml-2011.org/papers/438_icmlpaper.pdf
[GCN]: https://tkipf.github.io/graph-convolutional-networks/
[How powerful are Graph Convolutions?]: https://www.inference.vc/how-powerful-are-graph-convolutions-review-of-kipf-welling-2016-2/
[VGAE]: https://arxiv.org/pdf/1611.07308.pdf
[R-GCN]: https://arxiv.org/pdf/1703.06103.pdf
[GraphSAGE]: https://arxiv.org/pdf/1706.02216.pdf
[OpenKE]: https://github.com/thunlp/OpenKE/tree/OpenKE-PyTorch
[1]: https://arxiv.org/pdf/1503.00759.pdf
[2]: https://arxiv.org/abs/1709.05584
[dgl.ai]: https://github.com/dmlc/dgl
