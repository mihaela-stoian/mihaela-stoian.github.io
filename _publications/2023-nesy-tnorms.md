---
title: "Exploiting T-norms for Deep Learning in Autonomous Driving"
collection: publications
permalink: /publication/2023-nesy-tnorms
excerpt: 'In this paper, we show how it is possible to define memory-efficient t-norm-based losses, allowing for exploiting t-norms for the task of event detection in autonomous driving.'
date: 2023-06-01
venue: 'NeSy'
paperurl: ''
citation: 'Mihaela C. Stoian, Eleonora Giunchiglia, Thomas Lukasiewicz. Exploiting T-norms for Deep Learning in Autonomous Driving. Proceedings of the 17th International Workshop on Neural-Symbolic Learning and Reasoning (NeSy), 2023.'
---

Deep learning has been at the core of the autonomous driving field development, due to the neural networks' success in finding patterns in raw data and turning them into accurate predictions. Moreover, recent neuro-symbolic works have shown that incorporating the available background knowledge about the problem at hand in the loss function via t-norms can further improve the deep learning models' performance. However, t-norm-based losses may have very high memory requirements and, thus, they may be impossible to apply in complex application domains like autonomous driving. In this paper, we show how it is possible to define memory-efficient t-norm-based losses, allowing for exploiting t-norms for the task of event detection in autonomous driving. We conduct an extensive experimental analysis on the ROAD-R dataset and show (i) that our proposal can be implemented and run on GPUs with less than 25 GiB of available memory, while standard t-norm-based losses are estimated to require more than 100 GiB, far exceeding the amount of memory normally available, (ii) that t-norm-based losses improve performance, especially when limited labelled data are available, and (iii) that t-norm-based losses can further improve performance when exploited on both labelled and unlabelled data. 

Paper available [here](https://arxiv.org/abs/2402.11362).
