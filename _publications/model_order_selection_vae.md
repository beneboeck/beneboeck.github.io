---
title: "Model Order Selection with Variational Autoencoding"
collection: publications
category: ieee_conferences
permalink: /publication/model_order_selection_vae
excerpt: ''
authors: ["Michael Baur", "Franz Weißer", "Benedikt Böck", "Wolfgang Utschick"]
date: 2023-09-25
venue: 'IEEE International Workshop on Signal Processing Advances in Wireless Communications (SPAWC)'
paperurl: 'https://ieeexplore.ieee.org/document/10304435'
---
Classical methods for model order selection often fail in scenarios with low SNR or few snapshots. Deep learning-based methods are promising alternatives for such challenging situations as they compensate lack of information in the available observations with training on large datasets. This manuscript proposes an approach that uses a variational autoencoder (VAE) for model order selection. The idea is to learn a parameterized conditional covariance matrix at the VAE decoder that approximates the true signal covariance matrix. The method is unsupervised and only requires a small representative dataset for calibration after training the VAE. Numerical simulations show that the proposed method outperforms classical methods and even reaches or beats a supervised approach depending on the considered snapshots.