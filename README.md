# PubMed Text Mining: Towards Understanding Research Topics in Susceptibiltiy Weighted Imaging and Quantitative Susceptibiltiy Mapping
Purpose: This study is about mining and clustering research articles related to susceptibility weighted imaging and quantitative susceptibility mapping, using natural language processing and unsuperivised clustering techniques. 

Goal: The goal is to understand the relationships between different research articles and to discover trends in the field of Susceptibility Weighted Imaging (SWI) and Quantitative Susceptibility Mapping (QSM) using Magnetic Resonance Imaging (MRI). 

Materials and Methods: PubMed and Google scholar records were obtained and processed using NLTK and gensim. Latent semantic analysis was performed to map each paper to the LSI space. Clustering was performed using KMeans algorithm. The year of publication and the citation number were used to study the popularity of each topic. 

All codes were written in Python, in the format of iPython notebooks. 

1. Data Acquisition: GoogleScholar.ipynb and Pubmed-data-extraction.ipynb. 
These notebooks contain codes for web scraping for obtaining paper informaiton on Pubmed and Google scholar, using the API provided by Pubmed and the scholar python package.

2. Data pre-processing: Pre-processing.ipynb
This notebook shows the steps for data pre-processing, including tokenizing the abstracts and keywords, POS tagging, bigram and trigram transform, as well as handling the acronyms in abstracts and keywords. The tokens obtained in this step were used for LSA and clustering analysis. 

3. LSA and clustering: LSA_clustering.ipynb
Using the tokens generated from the abstracts and keywords of the papers, we perform Latent Semantic Analysis (LSA, aka LSI) using gensim. After projecting the papers to the LSA space, kmeans clustering was performed. The best number of clusters was selected using the silhouette score. The obtained clusters were analyzed by checking the papers belong to different clusters, in order to understand the meaning of the clusters. Finally, the current status and potential future directions of quantitative susceptibility mapping and susceptibility weighted imaging using MRI was discussed.