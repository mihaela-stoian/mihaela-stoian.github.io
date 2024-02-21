---
title: "How Realistic Is Your Synthetic Data? Constraining Deep Generative Models for Tabular Data"
collection: publications
permalink: /publication/2024-stoian-cdgms
excerpt: 'In this paper, we show how deep generative models for tabular data can be constrained such that their generated samples are guaranteed to be compliant with given constraints. This is achieved by automatically parsing the constraints and transforming them into a Constraint Layer seamlessly integrated with the model.'
date: 2024-02-07
venue: 'arXiv (Accepted at ICLR 2024)'
paperurl: ''
citation: 'Mihaela C. Stoian, Salijona Dyrmishi, Maxime Cordy, Thomas Lukasiewicz, Eleonora Giunchiglia. “How Realistic Is Your Synthetic Data? Constraining Deep Generative Models for Tabular Data.” ArXiv abs/2402.04823 (2024). Accepted at ICLR 2024.'
---

Deep Generative Models (DGMs) have been shown to be powerful tools for generating tabular data, as they have been increasingly able to capture the complex distributions that characterize them. However, to generate realistic synthetic data, it is often not enough to have a good approximation of their distribution, as it also requires compliance with constraints that encode essential background knowledge on the problem at hand. In this paper, we address this limitation and show how DGMs for tabular data can be transformed into Constrained Deep Generative Models (C-DGMs), whose generated samples are guaranteed to be compliant with the given constraints. This is achieved by automatically parsing the constraints and transforming them into a Constraint Layer (CL) seamlessly integrated with the DGM. Our extensive experimental analysis with various DGMs and tasks reveals that standard DGMs often violate constraints, some exceeding 95% non-compliance, while their corresponding C-DGMs are never non-compliant. Then, we quantitatively demonstrate that, at training time, C-DGMs are able to exploit the background knowledge expressed by the constraints to outperform their standard counterparts with up to 6.5% improvement in utility and detection. Further, we show how our CL does not necessarily need to be integrated at training time, as it can be also used as a guardrail at inference time, still producing some improvements in the overall performance of the models. Finally, we show that our CL does not hinder the sample generation time of the models. 

Paper available [here](https://arxiv.org/abs/2402.04823).
