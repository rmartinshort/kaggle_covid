# kaggle_covid

Get the dataset from https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge

## Content

- assemble: extract text and metadata from json format and convert to a pandas database  
- preprocessing: outdated  
- tfidf_umap - lemmatize, extract key terms with RAKE, apply tfidf, reduce dimensions with UMAP, cluster with HDBSCAN and plot  
- cluster_tagging - label each cluster and extract the most common key words and their associated sentences  