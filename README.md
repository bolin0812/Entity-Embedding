# Entity Embedding
Embedding methods transform high-dimensional sparse vectors into low-dimensional vectors. 

|    Research Paper    |  Key Points  |
|  :---------  | :------:  |
|  [Distributed Representations of Sentences and Documents](https://arxiv.org/pdf/1405.4053v2.pdf)  |This study proposes Paragraph based Vector, an unsupervised algorithm that learns ﬁxed-length feature representations from variable-length pieces of texts, such as sentences, paragraphs, and documents. The algorithm represents each document by a dense vector which is trained to predict words in the document. Its construction potentially overcome the weaknesses of bag-of words models. | 
|  [Doc2vec paragraph embeddings](https://radimrehurek.com/gensim/models/doc2vec.html)  | Applied doc2vec functions in genism to create lower dimensional transaction vector. It has been used for DBSCAN clustering with cosine similarity metric|
|  [Distributed Representations of Words and Phrases and their Compositionality](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)  | This study presents extensions of Skip-gram that improve both the quality of the vectors and the training speed by subsampling of the frequent words. This study describes a simple alternative to the hierarchical softmax called negative sampling.|
