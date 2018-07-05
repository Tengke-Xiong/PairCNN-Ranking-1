# PairCNN-Ranking
A tensorflow implementation of [Learning to Rank Short Text Pairs with Convolutional Deep Neural Networks](http://disi.unitn.it/~severyn/papers/sigir-2015-long.pdf)

## Require
Python 3.6 + Tensorflow 1.8

## Training Data
As **train.txt** and **test.txt** in **./data** dir, each line is an sample, which is splited by comma: query, document, label. And the example data is created by me to test the code, which is not real click data.

## Usage
```bash
python train.py
```
