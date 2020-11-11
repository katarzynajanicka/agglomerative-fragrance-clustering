# agglomerative-fragrance-clustering
Hierarchical agglomerative clustering on fragrance accords

<img src="https://img.shields.io/badge/python-3.8.5 -brightgreen"> <img src='https://img.shields.io/badge/scipy-1.5.2-blue'> <img src='https://img.shields.io/badge/scikitlearn-0.23.2-blue'> <img src='https://img.shields.io/badge/pandas-1.1.1-blue'> <img src='https://img.shields.io/badge/numpy-1.19.2-blue'> <img src="https://img.shields.io/badge/matplotlib-3.3.1 -blue"> <img src="https://img.shields.io/badge/seaborn-0.11.0 -blue"> <br>
<img src="https://img.shields.io/badge/unsupervised-machine--learning-ff69b4"> <img src="https://img.shields.io/badge/cluster-analysis-ff69b4"> <img src="https://img.shields.io/badge/exploratory-data%20analysis-ff69b4">

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Results](#results)
* [Status](#status)

## General info
Unsupervised machine learning project with hierarchical agglomerative clustering performed on different female fragrances.

## Technologies
Project is created with Python - version: 3.8.5.

Python libraries:
* scipy - version 1.5.2
* scikit-learn - version 0.23.2
* pandas - version 1.1.1
* numpy - version 1.19.2
* matplotlib - version 3.3.1
* seaborn - version 0.11.0
  
## Setup

Input data: result.csv, this is the end result of the https://github.com/katarzynajanicka/fragrance-clustering project.

Output data: 
* hierarchical-clustering.ipynb (Jupyter notebook)
* hierarchical_result.csv (end result)

## Results

![](./screens/structure.png)

**Data structure**

![](./screens/data.png)

**Dendrograms**

![](./screens/clusters_v0.png)
![](./screens/clusters_v1.png)

**Hierarchical clustering**

![](./screens/hierarchical_clustering.png)

**Cluster description by top accords**

![](./screens/most_frequent_accords.png)

![](./screens/clusters_per_size.png)

![](./screens/top_accords_per_cluster.png)

**Fragrance tree**

![](./screens/fragrancetree.png)

**Most popular fragrances**

![](./screens/most_popular.png)

**Most popular fragrances by cluster**

![](./screens/patchouli_cluster.png)

![](./screens/animalic_cluster.png)

**Most popular fragrances by brand**

![](./screens/Chanel.png)

![](./screens/Dior.png)

![](./screens/Dolce&Gabbana.png)

![](./screens/Tom_Ford.png)

![](./screens/Bottega_Veneta.png)

**Conclusions**

Agglomerative hierarchical clustering technique turned out be a better approach than K-means++ clustering (see: https://github.com/katarzynajanicka/fragrance-clustering). This is due to the fact that different perfume fragrances usually share the same notes. It is not unusual for a fragrance to have accords from two or three fragrance families (Floral, Fresh, Woody, Oriental).

## Status
Project is finished.
