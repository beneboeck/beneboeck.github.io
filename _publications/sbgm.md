---
title: "Sparse Bayesian Generative Modeling for Compressive Sensing | [Paper](https://openreview.net/forum?id=GqefKjw1OR)"
collection: publications
category: ml_conferences
permalink: /publication/sbgm
excerpt: ''
authors: ["Benedikt Böck", "Sadaf Syed", "Wolfgang Utschick"]
date: 2024-09-25
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://openreview.net/forum?id=GqefKjw1OR'
bibtexurl: 'https://github.com/beneboeck/sparse-bayesian-gen-mod'
---
This work addresses the fundamental linear inverse problem in compressive sensing (CS) by introducing a new type of regularizing generative prior. Our proposed method utilizes ideas from classical dictionary-based CS and, in particular, sparse Bayesian learning (SBL), to integrate a strong regularization towards sparse solutions. At the same time, by leveraging the notion of conditional Gaussianity, it also incorporates the adaptability from generative models to training data. However, unlike most state-of-the-art generative models, it is able to learn from a few compressed and noisy data samples and requires no optimization algorithm for solving the inverse problem. Additionally, similar to Dirichlet prior networks, our model parameterizes a conjugate prior enabling its application for uncertainty quantification. We support our approach theoretically through the concept of variational inference and validate it empirically using different types of compressible signals.