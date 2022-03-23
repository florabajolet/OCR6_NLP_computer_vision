# Project 6: Automated classification of goods from text and images

*Keywords*: unsupervised learning, NLP, computer vision, deep learning, transfer learning

## Goal
This project aims at categorizing products with unsupervised learning. Data include names and descriptions of products as well as photos. There are 1050 items to classify in 7 categories.

## What you need

The csv dataset directly on the github repo (flipkart_com-ecommerce_sample_1050.csv).

Main librairies used:
* Python 3.8.10
* Matplotlib 3.4.2
* Pandas 1.1.3
* Nympy 1.19.2
* Seaborn 0.11.0
* Gensim 3.8.3
* Tensorflow 2.7.0
* Plotly 5.4.0

## FILES
* P6_preprocess_clustering.ipynb: main jupyter notebook file
* fonctions_eda.py: basic exploratory data analysis functions
* flipkart_com-ecommerce_sample_1050.csv: text data and link to images
* images directory

## Approaches
* NLP: bag-of-words, tf-idf, word2vec, doc2vec
* Computer vision: ORB, VGG16
