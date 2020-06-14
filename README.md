# Data Science : Hands-on with Applied Theory
---

- Painless tutorials with relevant theory for painless data science learning
- Python
- TensorFlow 2.x

## NLP
- Word Embedding: [Word2Vec using Gensim with Examples](https://github.com/silpara/data-science/blob/master/word2vec/Word2Vec%20using%20Gensim.ipynb)
  - Train your own **Word2Vec** model using gensim. Understand the relationships learned by the model through examples.
  - Find words nearest to a word by using functionalities built into gensim library.
- Word Embedding: [Word2Vec using Wiki-words-250-with-normalization with Examples](https://github.com/silpara/data-science/blob/master/word2vec-Wiki-words-250-with-normalization/word2vec-Wiki-words-250-with-normalization.ipynb)
  - Use pretrained **Word2Vec** model from Google's **Wiki-words-250-with-normalization**. Understand the relationships learned by the model through examples.
  - Find words nearest to a word by using SimpleNeighbours library by Annoy.
- Sentence Embedding: [Universal Sentence Encoder + Nearest Neighbour Search using SimpleNeighbors[annoy]](https://github.com/silpara/data-science/blob/master/universal-sentence-encoder/Universal%20Sentence%20Encoder%20%2B%20Nearest%20Neighbour%20Search%20using%20SimpleNeighbors%5Bannoy%5D.ipynb)
  - Using Google's **Universal Sentence Encoder (USE)** model to get sentence embeddings in TensorFlow 2.0. 
  - Use SimpleNeighbours library by Annoy to find sentences nearest to a sentence by nearest neighbour search in N-dimensional vector space.
- Sentence Embedding: [nnlm-en-dim128 + Nearest Neighbour Search using SimpleNeighbors[annoy]](https://github.com/silpara/data-science/blob/master/nnlm-en-dim128/nnlm-en-dim128%20%2B%20Nearest%20Neighbour%20Search%20using%20SimpleNeighbors%5Bannoy%5D.ipynb)
  - Using Google's **NNLM** model to get sentence embeddings in TensorFlow 2.0. This model is faster than USE.
  - Use SimpleNeighbours library by Annoy to find sentences nearest to a sentence by nearest neighbour search in N-dimensional vector space.
- Nearest Neighbour Search: [Self Contained Example of NNS using Annoy](https://github.com/silpara/data-science/blob/master/nearest-neighbour-search/self_contained_annoy_example.ipynb)
  - Search nearest neighbours to a given vector.
  - Search nearest neighbour to a given index. Here you must know what the index means, e.g. index idx may represent embedding of an item.

