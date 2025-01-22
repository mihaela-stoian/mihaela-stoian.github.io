---
title: "Beyond the Convexity Assumption: Realistic Tabular Data Generation under Quantifier-Free Real Linear Constraints."
collection: publications
permalink: /publication/2025-iclr-dgms+drl
excerpt: 'In this paper, we introduce the Disjunctive Refinement Layer (DRL), a novel layer designed to enforce the alignment of generated data with the background knowledge specified in user-defined constraints. DRL is the first method able to automatically make deep learning models inherently compliant with constraints as expressive as quantifier-free linear formulas, which can define non-convex and even disconnected spaces.'
date: 2025-01-22
venue: 'The Proceedings of ICLR'
#paperurl: 'https://doi.org/10.48550/arXiv.2402.04823'
citation: 'Mihaela C. Stoian and Eleonora Giunchiglia. Beyond the Convexity Assumption: Realistic Tabular Data Generation under Quantifier-Free Real Linear Constraints. Accepted at International Conference on Learning Representations (ICLR) 2025.'
---

Synthetic tabular data generation has traditionally been a challenging problem due to the high complexity of the underlying
distributions that characterise this type of data. Despite recent advances in deep generative models (DGMs), existing methods
often fail to produce realistic datapoints that are well-aligned with available background knowledge. In this paper, we address
this limitation by introducing Disjunctive Refinement Layer (DRL), a novel layer designed to enforce the alignment of generated
data with the background knowledge specified in user-defined constraints. DRL is the first method able to automatically make
deep learning models inherently compliant with constraints as expressive as quantifier-free linear formulas, which can define
non-convex and even disconnected spaces. Our experimental analysis shows that DRL not only guarantees constraint
satisfaction but also improves efficacy in downstream tasks. Notably, when applied to DGMs that frequently violate constraints,
DRL eliminates violations entirely. Further, it improves performance metrics by up to 21.4% in F1-score and 20.9% in Area Under
the ROC Curve, thus demonstrating its practical impact on data generation.

[//]: # (Paper available [here]&#40;https://arxiv.org/abs/2402.04823&#41;.)
