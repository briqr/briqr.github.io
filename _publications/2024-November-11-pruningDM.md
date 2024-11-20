---
title: "Data Pruning in Generative Diffusion Models"
collection: publications
excerpt: 'Data pruning is the problem of identifying a core subset that is most beneficial to training and discarding the remainder. While pruning strategies are well studied for discriminative models like those used in classification, little research has gone into their application to generative models. Generative models aim to estimate the underlying distribution of the data, so presumably they should benefit from larger datasets. In this work we aim to shed light on the accuracy of this statement, specifically answer the question of whether data pruning for generative diffusion models could have a positive impact. Contrary to intuition, we show that eliminating redundant or noisy data in large datasets is beneficial particularly when done strategically. We experiment with several pruning methods including recent-state-of-art methods, and evaluate over CelebA-HQ and ImageNet datasets. We demonstrate that a simple clustering method outperforms other sophisticated and computationally demanding methods. We further exhibit how we can leverage clustering to balance skewed datasets in an unsupervised manner to allow fair sampling for underrepresented populations in the data distribution, which is a crucial problem in generative models.'
date: 2024-November-11
paperurl: 'https://arxiv.org/abs/2411.12523'
venue: ''
---
