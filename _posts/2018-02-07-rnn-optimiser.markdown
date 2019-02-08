---
title: "Optimising RNN Architecture with hyperopt"
layout: post
date: 2018-07-02
tag: nlp, keras, neural network, classification, hyperparameter tuning, bayesian optimization
image: https://www.benlcollins.com/wp-content/uploads/2016/01/quora.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Using Bayesian Optimisation on a Recurrent Neural Networks Hyper-Parameters"
category: project
author: eemelierkkola
externalLink: false
---

![Screen-shot](/assets/tensorboardXample.png){:class="img-responsive"}

In this project I worked on tuning a recurrent neural networks hyper parameters using the popular optimisation package [hyperopt](https://github.com/hyperopt/hyperopt), keras and tensorboardX.

The data used was from the [Kaggle Quora Competition](https://www.kaggle.com/c/quora-insincere-questions-classification), a competition where the aim was to build a insincere question classifier. The inspiration to optimise a neural network for this task came from the competition constraints, the whole network must be able to train and predict within 2 hours on a kaggle docker image with GPU enabled. This meant that a highly optimised neural net architecture would be a sure way to perform well in this competition. Hyperopt is not the only optimisation framework I could have used, and I am eager to try out optuna and others in the near future. 

TensorboardX is one of the most useful tools for visualising scalars / data during training, and when using an optimiser this becomes crucial to monitor the best performing candidate parameters for a network. For the sake of simplicity I have only optimised over a few parameters here, however it is easy to see the potential in using an optimizer such as hyperopt to tune your network.

Please find the code for this project in the [Github Repository](https://github.com/emilerkkola/LSTM-hyperopt-tensorboardX)

---

Stack:

- Python - keras, hyperopt, tensorboardX, pandas, matplotlib, NLTK, spacy, gensim

---

