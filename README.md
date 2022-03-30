# Stratification of Preterm Birth Risk in Brazil Through Unsupervised Learning Methods and Socioeconomic Data

This repository contains the main codes/notebooks and files used in the making of this Master's research.

- Author: `Márcio Lopes Jr`
- Area of Study: `Intelligent Information Processing`
- Program: [`MSc in Electrical and Computer Engineering`](https://posgraduacao.ufrn.br/ppgeec)
- University: [`UFRN-Natal`](https://ufrn.br/)

## Summary
Preterm birth (PTB) is a phenomenon that brings risks and challenges for the survival of the newborn child. Despite many advances in research, not all the causes of PTB are yet clear. It is currently understood that PTB risk is multi-factorial and may also be associated with socioeconomic factors. In order to analyse this possible relationship, this work seeks to stratify PTB risk in Brazil using only socioeconomic data, extracting and analysing those clusters that present relevant PTB divergence, all of which will be found by automatic clustering processes using a series of unsupervised machine learning methods. Through the use of datasets made publicly available by the Federal Government of Brazil, a new dataset was generated with municipality-level socioeconomic data and a PTB occurrence rate. This dataset was processed using two separate clustering methods, both built by assembling unsupervised learning techniques, such as k-means, principal component analysis (PCA), density-based spatial clustering of applications with noise (DBSCAN), self-organising maps (SOM) and hierarchical clustering. The methods dis- covered clusters of municipalities with both high levels and low levels of PTB occurrence. The clusters with high PTB were comprised mostly of municipalities with lower levels of education, worse quality of public services – such as basic sanitation and garbage collection – and a less white population. The regional distribution of the clusters was also observed, with clusters of high PTB located mostly in the North and Northeast regions of Brazil. The results indicate a positive influence of the quality of life and the offer of public services on the reduction of PTB risk

**Keywords**: `Preterm birth`, `Clustering`, `Unsupervised learning`, `PTB risk`, `k-Means`,
`Self-Organising Maps`, `Brazil`.

## Organisation

- Preprocessing Notebooks:
   1. [PTB Rate Dataset](https://github.com/marciojunior159/ptb_rate_research/blob/main/(PTB-Research)%20PTB%20Rate%20Dataset.ipynb)
   2. [Socioeconomic Dataset](https://github.com/marciojunior159/ptb_rate_research/blob/main/(PTB-Research)%20Socioeconomic%20Dataset.ipynb)
- k-Means Method:
   1. [k-Means](https://github.com/marciojunior159/ptb_rate_research/blob/main/(PTB-Research)%20kMeans.ipynb)
   2. [DBSCAN](https://github.com/marciojunior159/ptb_rate_research/blob/main/(PTB-Research)%20DBSCAN.ipynb)
- SOM Method:
   1. [SOM/Hierarchical Clustering](https://github.com/marciojunior159/ptb_rate_research/blob/main/(PTB-Research)%20SOM.ipynb)

> PS: The notebooks containing the generated plots will be added soon
