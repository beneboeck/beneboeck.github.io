---
title: "Variational Inference Aided Estimation of Time Varying Channels"
collection: publications
category: ieee_conferences
permalink: /publication/channel_estimation_time_varying
excerpt: ''
authors: ["Benedikt Böck", "Michael Baur", "Valentina Rizzello", "Wolfgang Utschick"]
date: 2023-06-04
venue: 'IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
paperurl: 'https://ieeexplore.ieee.org/document/10094953'
---
One way to improve the estimation of time varying channels is to incorporate knowledge of previous observations. In this context, Dynamical VAEs (DVAEs) build a promising deep learning (DL) framework which is well suited to learn the distribution of time series data. We introduce a new DVAE architecture, called k-MemoryMarkovVAE (k-MMVAE), whose sparsity can be controlled by an additional memory parameter. Following the approach in [1] we derive a k-MMVAE aided channel estimator which takes temporal correlations of successive observations into account. The results are evaluated on simulated channels by QuaDRiGa and show that the k-MMVAE aided channel estimator clearly outperforms other machine learning (ML) aided estimators which are either memoryless or naively extended to time varying channels without major adaptions.