# pyterrier-colbert & ColBERT-PRF

Advanced [PyTerrier](https://github.com/terrier-org/pyterrier) bindings for [ColBERT](https://github.com/stanford-futuredata/ColBERT/), including for dense indexing and retrieval. This also includes the implementations of [ColBERT PRF](https://arxiv.org/abs/2106.11251), [approximate ANN scoring](https://arxiv.org/abs/2108.11480) and [query embedding pruning](https://arxiv.org/abs/2108.10341). 

## Usage
Takes ColBERT-PRF and the Vaswani data set and cuts the queries in 3 different ways to compare the results. Queries are cut by removing the first 3 words, the last 3 words, and 2 words from the beggining and end: [Colab](https://colab.research.google.com/drive/1ivvF5W_8CR_NeWtESpGfyvU5FrwCpl-o).

Additional Tests: [Colab](https://colab.research.google.com/drive/1GAmsJgLnaubkTTdXDYJ_A15Y7xOru-EM#scrollTo=_ZgEnqANEngP)