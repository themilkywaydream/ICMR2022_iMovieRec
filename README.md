# ~Paper title~
Movie repository is to supplement the paper "paper title".

## Abstract
 

## Overview of our framework
<img src="https://user-images.githubusercontent.com/43632309/105990739-43baeb00-60e6-11eb-8117-a12310ccc655.png" width="480" height="303">
<img src="https://user-images.githubusercontent.com/43632309/105991102-bdeb6f80-60e6-11eb-9f44-ec4419df7760.png" width="515" height="167">
<img src="https://user-images.githubusercontent.com/43632309/105991281-effcd180-60e6-11eb-8cd4-b2420b0329c4.png" width="613" height="168">

## Clone
```
git clone ~anonyous url~
```

## Dataset
Movielens 100K
https://grouplens.org/datasets/movielens/100k/

Movielens 1M
https://grouplens.org/datasets/movielens/1m/

## Model Description
* graphrec_image.py : this file provides training Graphrec model adding image features.
* image_processing.py : this file provides an extraction of the image features in the Graphrec by inserting them into the CNN.
* models_mf.py : this file provides a set of basic matrix factorization models.
* preprocess.py : this file proivdes conducting label encoding of user and item columns.
* train_test_mf.py : this file provides training and testing for basic matrix factorization models.
* util.py : this file provides supplements for graphrec_image.py
