---
title: "NLP and AWS 2018"
layout: post
date: 2018-07-01
tag: nlp, keras, neural network, classification, topic modelling, cloud computing, cloud infrastructure, cloud backend, GUI frontend
image: https://images.techhive.com/images/article/2015/05/aws-logo-100584713-primary.idge.jpg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Training state of the art NLP models with an AWS cloud backend"
category: project
author: eemelierkkola
externalLink: false
---

![Screen-shot](/assets/aws.png){:class="img-responsive"}

In June 2018 I started work as a data scientist at a news company. This gave be access to very large text based datasets, and allowed me to learn multiple different uses for NLP in a real business environment. In addition to NLP / machine learning, in the first two months of my work I quickly became certified with the AWS Cloud Practicioner certificate. At the current moment, I am studying to pass my AWS Solutions Architect Associate, and hopefully AWS Certified Developer Associate soon after (as I find the two to compliment each other very well).

Learning to use cloud resources in this kind of business environment gave me invaluable experience as a data scientist. I soon began building a simple cloud backend for my model training and development, using AWS EC2, AWS S3 and AWS Lambda. For unlabelled data, I built a simple GUI for labelling that I distributed amongst the senior team members who wanted to quality control the data. I made labelling as easy as using keybinds for different classes, which extemely sped up the labelling process. I am currently in the process of learning Vue.js so I can build an easy API and analytics dashboard that other developers / seniors can query for information (this will be done using Vue.js, AWS cognito and AWS API Gateway).

Natural Language Processing projects involved classification, topic modelling, entity extraction and involved using many different state-of-the-art models that I learned through my experimentation / lecture series / Kaggle. I have gained heavy experience in classification problems, and access to AWS gave me an arsenal of powerful GPU's to speed up training of complex recurrent neural networks on large amounts of data. I have experience with with normal neural networks, convolutional networks and recurrent networks, all of which I have applied to NLP problems at large scales. To optimise model architectures I have practiced tuning in a variety of ways, and one of my favourite is to use Hyperopt (or for Keras, the Keras version [Hyperas](https://github.com/maxpumperla/hyperas). Cloud GPU's and Hyperas have proven to be a very quick and powerful way to optimise architecture if I'm working with Keras in my pipeline. For legal reasons I have not provided the source code for these projects here, however a small example of fine tuning topic models on a general dataset can be seen on my [Github page](https://github.com/emilerkkola/Visual-Topic-Modeling). Additionally, you can track my participation in Kaggle competitions through my [Kaggle profile](https://www.kaggle.com/eeeedev). 

---

Stack:

- AWS
- Python - keras, pytorch, tensorflow, pandas, matplotlib, hyperas, NLTK, spacy, gensim
- HTML / Bootstrap

---

