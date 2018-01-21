# Creating personalized Medicine that redefines cancer treatments  

**The project is currently under development**  


## Introduction

Inspiration of this project is [this](https://www.kaggle.com/c/msk-redefining-cancer-treatment) Kaggle competition.   

The objective is to develop algorithms to classify genetic mutations based on clinical evidence (text).  

A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated.Once sequenced, a cancer tumor can have thousands of genetic mutations. The challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers).Using an expert-annotated knowledge base where world-class researchers and oncologists have manually annotated thousands of mutations, the objective is to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.  

## Data  

There are nine different classes a genetic mutation can be classified on.  

Both, training and test, data sets are provided via two different files.  

One (training/test\_variants) provides the information about the genetic mutations, whereas the other (training/test\_text) provides the clinical evidence (text) that the human experts used to classify the genetic mutations. Both are linked via the ID field.  

## Metrics  

Performance of the classifier is evaluated using the multi class log loss between the predicted probability and the observed target for each ID in the test set.



