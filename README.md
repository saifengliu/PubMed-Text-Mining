# PubMed Text Mining: Towards Understanding Research Topics in Susceptibiltiy Weighted Imaging and Quantitative Susceptibiltiy Mapping
This study is about mining and clustering research articles related to susceptibility weighted imaging and quantitative susceptibility mapping. The goal is to understand the relationships between different research articles and to discover trends in the field of Susceptibility Weighted Imaging (SWI) and Quantitative Susceptibility Mapping (QSM) using Magnetic Resonance Imaging (MRI). 

PubMed and Google scholar records were processed using NLTK and gensim. Latent semantic analysis was performed to map each paper to the latent data space. Clustering was performed using KMeans algorithm. The year of publication and the citation number were used to study the popularity of each topic. 

All codes were written in Python, in the format of iPython notebooks. 
Data Acquisition: GoogleScholar.ipynb and Pubmed-data-extraction.ipynb. 
Data pre-processing: Pre-processing.ipynb
