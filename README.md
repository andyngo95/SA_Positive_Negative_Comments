# Sentiment Analysis: Distinguish Positive and Negative Comments

## Introduction
With the development of e-commerce sites, collecting reviews from user comments is likely to be essential. Users' comments make it easy for them to filter, recommend items, locations that are suitable for each users and evaluate the quality of the partners' services. With thousands of comments per day, categorizing (good, bad) for comments from users is not easy and require a lot of manpower. Along with the development of AI, we can now solve this problem with deep learning models and high accuracy equivalent to humans.

![alt text](https://github.com/andyngo95/SA_Positive_Negative_Comments/blob/master/Images/comments.png)

## Build the strategy to solve this problem

### Dataset
We use the review data set on Foody page with about 30,000 labeled templates. Including 15,000 positive samples and 15,000 negative samples. Source: https://streetcodevn.com/blog/dataset

### RNN architecture
![alt text](https://github.com/andyngo95/SA_Positive_Negative_Comments/blob/master/Images/architecture.png)

### Result

| Model                        | F1-Score      |
| -------------------------    |:-------------:|
| RNN + Bahdanau Attention     | 0.853         |
| CNN                          | 0.872         |
| Voting ensemble              | 0.887         |
