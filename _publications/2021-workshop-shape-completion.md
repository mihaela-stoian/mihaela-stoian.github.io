---
title: "Recurrently Estimating Reflective Symmetry Planes from Partial Pointclouds"
collection: publications
permalink: /publication/2021-workshop-shape-completion
excerpt: 'In this paper we present a novel method to estimate planar reflective symmetries that efficiently handles 3D inputs by slicing the data along the height dimension and passing it sequentially to a 2D convolutional recurrent regression scheme.'
date: 2021-06-30
venue: 'arXiv (Presented at the CVPR 2021 Workshop on 3D Vision and Robotics)'
paperurl: ''
citation: 'Mihaela C. Stoian, Tommaso Cavallari. Recurrently Estimating Reflective Symmetry Planes from Partial Pointclouds. arXiv abs/2106.16129, 2021.'
---

Many man-made objects are characterised by a shape that is symmetric along one or more planar directions. Estimating the location and orientation of such symmetry planes can aid many tasks such as estimating the overall orientation of an object of interest or performing shape completion, where a partial scan of an object is reflected across the estimated symmetry plane in order to obtain a more detailed shape. Many methods processing 3D data rely on expensive 3D convolutions. In this paper we present an alternative novel encoding that instead slices the data along the height dimension and passes it sequentially to a 2D convolutional recurrent regression scheme. The method also comprises a differentiable least squares step, allowing for end-to-end accurate and fast processing of both full and partial scans of symmetric objects. We use this approach to efficiently handle 3D inputs to design a method to estimate planar reflective symmetries. We show that our approach has an accuracy comparable to state-of-the-art techniques on the task of planar reflective symmetry estimation on full synthetic objects. Additionally, we show that it can be deployed on partial scans of objects in a real-world pipeline to improve the outputs of a 3D object detector. 

Paper available [here](https://arxiv.org/abs/2106.16129).
