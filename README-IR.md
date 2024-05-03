## Pyterrier Colbert
This is an implementation of the pyterrier_colbert model, testing how query size affects retrieval results and time.
To run the experiment open the colab link and run the cells.
## Usage
Takes ColBERT-PRF and the Vaswani data set and cuts the queries in 3 different ways to compare the results. Queries are cut by removing the first 3 words, the last 3 words, and 2 words from the beggining and end. Total runtime is ~ 7 minutes.
This is the main experiment: [Colab](https://colab.research.google.com/drive/1ivvF5W_8CR_NeWtESpGfyvU5FrwCpl-o).

Initail Test to prove the model works: [Colab](https://colab.research.google.com/drive/1GAmsJgLnaubkTTdXDYJ_A15Y7xOru-EM)
