---
title: "Analyzing ASR pretraining for low-resource speech-to-text translation"
collection: publications
permalink: /publication/2020-icassp-speech-to-text
excerpt: 'In this paper we explore what factors help pretraining for low-resource automatic speech-to-text translation (AST). We show that the word error rate (WER) of the pre-trained automatic speech recognition (ASR) models is likely the best direct predictor of AST performance. Additionally, our analysis suggests that the models with better WER are transparently encoding more language-universal phonetic information in the later RNN layers, and this appears to help with AST.'
date: 2020-05-01
venue: 'The Proceedings of ICASSP'
paperurl: 'https://doi.org/10.48550/arXiv.1910.10762'
citation: 'Mihaela C. Stoian, Sameer Bansal, Sharon Goldwater. Analyzing ASR pretraining for low-resource speech-to-text translation. In Proceedings of International Conference on Acoustics, Speech, and Signal Processing (ICASSP), 2020.'
---

Previous work has shown that for low-resource source languages, automatic speech-to-text translation (AST) can be improved by pretraining an end-to-end model on automatic speech recognition (ASR) data from a high-resource language. However, it is not clear what factors --e.g., language relatedness or size of the pretraining data-- yield the biggest improvements, or whether pretraining can be effectively combined with other methods such as data augmentation. Here, we experiment with pretraining on datasets of varying sizes, including languages related and unrelated to the AST source language. We find that the best predictor of final AST performance is the word error rate of the pretrained ASR model, and that differences in ASR/AST performance correlate with how phonetic information is encoded in the later RNN layers of our model. We also show that pretraining and data augmentation yield complementary benefits for AST. 

[//]: # (Paper available [here]&#40;https://arxiv.org/abs/1910.10762&#41;.)


