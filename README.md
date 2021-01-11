Using Distill BERT and TF-IDF to create topic model since pre-trained transformer-based models are especially helpful as they are supposed to contain more accurate representations of words and sentences.

Original article: https://towardsdatascience.com/topic-modeling-with-bert-779f7db187e6


What to expect:

- Dataset: Newsgroup - 20 classes - 18846 samples - Text - scikit-learn datasets

- Embeddings created using sentence-transformers leveraging distill bert model

- Dimensionality reduction using Uniform Manifold Approximation and Projection (UMAP)

- Clustering using HDBSCAN - Unsupervised learning to group similar documents together

- Visualisation of clusters using matplotlib

- Topic modeling by finding most important words using TF-IDF (class variant)
 
- Number of topics reduced by a simple trick of merging the very similar topics
