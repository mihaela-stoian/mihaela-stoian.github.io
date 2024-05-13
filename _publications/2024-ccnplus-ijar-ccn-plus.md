---
title: "CCN+: A neuro-symbolic framework for deep learning with requirements"
collection: publications
permalink: /publication/2024-ccnplus-ijar-ccn-plus
excerpt: 'In this paper, we propose a novel neuro-symbolic framework able to make any neural network compliant by design to a given set of requirements over the output space expressed in full propositional logic. This framework, called CCN+, integrates the requirements into the output layer of the neural network by applying multiple inference rules that ensure compliance with the requirements and adapts the standard binary cross-entropy loss function to the requirement output layer.'
date: 2024-01-22
venue: 'International Journal of Approximate Reasoning'
paperurl: ''
citation: 'Eleonora Giunchiglia‚ Alex Tatomir‚ Mihaela C. Stoian, Thomas Lukasiewicz. CCN+: A neuro-symbolic framework for deep learning with requirements. International Journal of Approximate Reasoning, 2024. (In Press)'
---

For their outstanding ability of finding hidden patterns in data, deep learning models have been extensively applied in many different domains. However, recent works have shown that, if a set of requirements expressing inherent knowledge about the problem at hand is given, then neural networks often fail to comply with them. This represents a major drawback for deep learning models, as requirements compliance is normally considered a necessary condition for standard software deployment. In this paper, we propose a novel neuro-symbolic framework able to make any neural network compliant by design to a given set of requirements over the output space expressed in full propositional logic. This framework, called CCN+, integrates the requirements into the output layer of the neural network by applying multiple inference rules that ensure compliance with the requirements and adapts the standard binary cross-entropy loss function to the requirement output layer. As a result, not only the outputted predictions are guaranteed to be compliant with the requirements, but the neural network itself learns how to exploit the domain knowledge expressed by the requirements to get better performance. We conduct an extensive experimental evaluation of CCN+ on 19 real-world multi-label classification datasets with propositional logic requirements, including a challenging dataset for autonomous driving. Our experimental analysis confirms that CCN+ is able to outperform both its neural counterparts and the state-of-the-art models.

Paper available [here](https://doi.org/10.1016/j.ijar.2024.109124).