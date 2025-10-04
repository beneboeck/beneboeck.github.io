---
title: "Variational Autoencoder for Channel Estimation: Real-World Measurement Insights"
collection: publications
category: ieee_conferences
permalink: /publication/vae_real_world
excerpt: ''
authors: ["Michael Baur", "Benedikt Böck", "Nurettin Turan", "Wolfgang Utschick"]
date: 2024-03-17
venue: 'International Workshop on Smart Antennas (WSA)'
paperurl: 'https://ieeexplore.ieee.org/document/10512030'
---
This work utilizes a variational autoencoder for channel estimation and evaluates it on real-world measurements. The estimator is trained solely on noisy channel observations and parameterizes an approximation to the mean squared error-optimal estimator by learning observation-dependent conditional first and second moments. The proposed estimator significantly outperforms related state-of-the-art estimators on real-world measurements. We investigate the effect of pre-training with synthetic data and find that the proposed estimator exhibits comparable results to the related estimators if trained on synthetic data and evaluated on the measurement data. Furthermore, pre-training on synthetic data also helps to reduce the required measurement training dataset size.