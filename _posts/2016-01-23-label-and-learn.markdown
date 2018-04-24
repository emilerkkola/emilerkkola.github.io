---
title: "Label and Learn: Ethereum"
layout: post
date: 2018-01-05
tag: data labelling, classifier, neural network, ethereum
image: https://www.ethereum.org/images/logos/ETHEREUM-ICON_Black_small.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a simple and minimalist template for Jekyll for those who likes to eat noodles."
category: project
author: johndoe
externalLink: false
---

![Screen-shot](/assets/screen-shot.png){:class="img-responsive"}

Obtaining labelled data to train a classifier can be tedious and expensive. The motivation behind the Label and Learn project was to cut down time spent obtaining labelled data, and allow for easy cooperation on machine learning projects by creating a simple front-end that anyone can use to label and re-train the neural network. This can speed up the process of data labelling and model training as work can be delegated to anyone without coding knowledge, as long as there is a consistent logic behind labels. 

There are several problems to deal with when collecting meaningful data to train a classifier. Collecting texts from social media will yield a large number of meaningless data, spam bots and promotional texts taking up a large fraction of posts on Twitter for example. In the case of this demo, when collecting tweets that yield an overall sentiment on Ethereum for price prediction, at least 75% of tweets are useless for intelligent data analysis. The purpose of this demo is to focus on collecting useful data, as often this is the starting point of any machine learning project.

The demo here is a simplified version of the front-end I use myself, however it serves as a showcase on the potential a front-end such as Label and Learn has. Future plans include creating a generalised version, for any classifier network with n-classes, with a database holding descriptions, data sets, models, weights, and most recent accuracies. Currently the demo uses datasets and models from the Github repository, and serves as a proof-of-concept. 


Follow this link for the demo.

Follow [this](https://github.com/youngmil/labelandlearn) link for the Github repository.

---

Stack:

- AWS
- Flask
- Python - keras, tensorflow, pandas, matplotlib
- HTML / Bootstrap

---

