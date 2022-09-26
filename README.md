<h1 align="center"> Document Clustering and Topic Modeling </h1>

# Introduction
This project leverages unsupervised models to cluster unlabeled ecommerce product reviews into groups for customer sentiment analysis.
The data is retrieved from [Amazon Customer Reviews Dataset](https://s3.amazonaws.com/amazon-reviews-pds/readme.html), which is a collection of customers' reviews on US watches. Tokenization and stemming are firstly performed on the raw data for preprocessing. TF-IDF model is then applied on the documents for feature engineering. Based on the TF-IDF matrix, models including K Means Clustering and Latent Dirichlet Allocation are applied to group customer reviews into clusters and identify the hidden topics of the corpus.
