# Hybrid Recommendation system with feature selection: The impact of image and graph
Movie repository is to supplement the paper "Hybrid Recommendation system with feature selection: The impact of image and graph".

## Abstract
Among the recommendation models, the collaborative filtering recommendation system is the most frequently used method and shows high accuracy performance. However, this method has limitations in improving additional performance due to the problem of sparse rating matrix. To compensate for this problem, many studies have expected performance improvements by adding external and internal features as an input. Because user information is difficult to use due to privacy issues, various graph features and item information are recently considered in this hybrid recommendation model. In this work, we focus on movie recommendation models to compare the performance changes of existing collaborative filtering models by utilizing graph features and item information, especially movie poster images. We first combine additional various graph features in the GraphRec model to verify the influence of graph features. We also propose a fused model for basic matrix factorization models and GraphRec models to add image features. Experiments with two bench-marking datasets demonstrate that the effects of images and graph features differ by model. 

## Overview of our framework
<img src="https://user-images.githubusercontent.com/43632309/105990739-43baeb00-60e6-11eb-8117-a12310ccc655.png" width="480" height="303">
<img src="https://user-images.githubusercontent.com/43632309/105991102-bdeb6f80-60e6-11eb-9f44-ec4419df7760.png" width="515" height="167">
<img src="https://user-images.githubusercontent.com/43632309/105991281-effcd180-60e6-11eb-8cd4-b2420b0329c4.png" width="613" height="168">

## Clone
```
git clone ~anonymous url~
```

## Dataset
MovieLens 100K : https://grouplens.org/datasets/movielens/100k/

MovieLens 1M : https://grouplens.org/datasets/movielens/1m/

## Model Description
* graphrec_image.py : this file provides training GraphRec model adding image features.
* image_processing.py : this file provides an extraction of the image features in the GraphRec by inserting them into the CNN.
* models_mf.py : this file provides a set of basic matrix factorization models.
* preprocess.py : this file proivdes conducting label encoding of user and item columns.
* train_test_mf.py : this file provides training and testing for basic matrix factorization models.
* util.py : this file provides supplements for graphrec_image.py
